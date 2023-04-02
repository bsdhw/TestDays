BSD in UK - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for BSD in UK.

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

Total: 197

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [c83b0dda87](https://bsd-hardware.info/?probe=c83b0dda87) | Mar 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9ac4738956](https://bsd-hardware.info/?probe=9ac4738956) | Mar 18, 2023 |
| OEGStone      | W54_55SU1,SUW               | [7a2b28c47f](https://bsd-hardware.info/?probe=7a2b28c47f) | Mar 17, 2023 |
| ASUSTek       | 1001P                       | [76eae56ba3](https://bsd-hardware.info/?probe=76eae56ba3) | Mar 15, 2023 |
| OEGStone      | W54_55SU1,SUW               | [64316408f0](https://bsd-hardware.info/?probe=64316408f0) | Mar 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Star Labs     | StarBook                    | [80f6445f54](https://bsd-hardware.info/?probe=80f6445f54) | Mar 10, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9466e6d4f4](https://bsd-hardware.info/?probe=9466e6d4f4) | Mar 07, 2023 |
| Deciso        | OPNsense Appliance          | [1cca4a556d](https://bsd-hardware.info/?probe=1cca4a556d) | Mar 07, 2023 |
| HP            | EliteBook 8570p             | [1a4897cb53](https://bsd-hardware.info/?probe=1a4897cb53) | Feb 26, 2023 |
| HP            | EliteBook 8570p             | [1e548fa114](https://bsd-hardware.info/?probe=1e548fa114) | Feb 24, 2023 |
| Lenovo        | ThinkPad T460 20FMS3320G    | [c85f94d574](https://bsd-hardware.info/?probe=c85f94d574) | Feb 19, 2023 |
| HP            | EliteBook 8570p             | [1ba2a827d9](https://bsd-hardware.info/?probe=1ba2a827d9) | Feb 18, 2023 |
| Apple         | MacBookPro11,1              | [673f6c0a01](https://bsd-hardware.info/?probe=673f6c0a01) | Feb 17, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [b7a491a010](https://bsd-hardware.info/?probe=b7a491a010) | Feb 03, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Star Labs     | Lite                        | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Deciso        | NetBoard-A10                | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Deciso        | OPNsense Appliance          | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Deciso        | OPNsense Appliance          | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Dell          | Precision 7710              | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Dell          | Inspiron 1545               | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Deciso        | OPNsense Appliance          | [05fb88304d](https://bsd-hardware.info/?probe=05fb88304d) | Jul 13, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| System76      | Gazelle                     | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| Lenovo        | ThinkPad X230 2325J67       | [3ee0f54d2f](https://bsd-hardware.info/?probe=3ee0f54d2f) | May 12, 2022 |
| TUXEDO        | Aura 15 Gen1                | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| HP            | Pavilion m6                 | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| Lenovo        | ThinkPad X240 20AMS1YG01    | [6e38eb1a4e](https://bsd-hardware.info/?probe=6e38eb1a4e) | May 01, 2022 |
| MSI           | Modern 14 B11MOL            | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Lenovo        | Z50-70 20354                | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Jumper        | EZbook                      | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| HP            | EliteBook 8570p             | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| Jumper        | EZbook                      | [7d648bcdc7](https://bsd-hardware.info/?probe=7d648bcdc7) | Jan 17, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| HP            | EliteBook 8570p             | [1bbb37d4c6](https://bsd-hardware.info/?probe=1bbb37d4c6) | Jan 03, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| HP            | Laptop 15-db0xxx            | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| HP            | EliteBook 8570p             | [822a2481bb](https://bsd-hardware.info/?probe=822a2481bb) | Nov 17, 2021 |
| ASUSTek       | 1001P                       | [648081d75b](https://bsd-hardware.info/?probe=648081d75b) | Nov 09, 2021 |
| Dell          | XPS 13 9343                 | [227c2380d0](https://bsd-hardware.info/?probe=227c2380d0) | Nov 04, 2021 |
| Samsung       | 550P5C/550P7C               | [69fe175fb8](https://bsd-hardware.info/?probe=69fe175fb8) | Oct 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell          | XPS 13 9343                 | [4b8421b910](https://bsd-hardware.info/?probe=4b8421b910) | Oct 21, 2021 |
| HP            | 15                          | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| HP            | EliteBook 8570p             | [86613b04d3](https://bsd-hardware.info/?probe=86613b04d3) | Oct 17, 2021 |
| Dell          | XPS 13 9343                 | [7dd8f42ab1](https://bsd-hardware.info/?probe=7dd8f42ab1) | Oct 15, 2021 |
| HP            | EliteBook 8570p             | [27f01061f2](https://bsd-hardware.info/?probe=27f01061f2) | Sep 12, 2021 |
| Dell          | XPS 13 9343                 | [1f9857aa23](https://bsd-hardware.info/?probe=1f9857aa23) | Sep 08, 2021 |
| Apple         | MacBookPro5,1               | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| HP            | EliteBook 8570p             | [fae9e84f60](https://bsd-hardware.info/?probe=fae9e84f60) | Aug 27, 2021 |
| Toshiba       | Satellite L50-C             | [250db17f57](https://bsd-hardware.info/?probe=250db17f57) | Aug 20, 2021 |
| Toshiba       | Satellite L50-C             | [a2e1cbd3d8](https://bsd-hardware.info/?probe=a2e1cbd3d8) | Aug 20, 2021 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [f7725f06df](https://bsd-hardware.info/?probe=f7725f06df) | Aug 18, 2021 |
| HP            | EliteBook 8570p             | [71092e78e2](https://bsd-hardware.info/?probe=71092e78e2) | Aug 17, 2021 |
| HP            | EliteBook 8570p             | [6e97c9a59e](https://bsd-hardware.info/?probe=6e97c9a59e) | Aug 14, 2021 |
| HP            | ZBook 17 G2                 | [f2d911563a](https://bsd-hardware.info/?probe=f2d911563a) | Aug 07, 2021 |
| HP            | ZBook 17 G2                 | [2faf8af7be](https://bsd-hardware.info/?probe=2faf8af7be) | Jul 30, 2021 |
| HP            | ZBook 17 G2                 | [c7fb9e9dee](https://bsd-hardware.info/?probe=c7fb9e9dee) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [50c349b7b5](https://bsd-hardware.info/?probe=50c349b7b5) | Jul 27, 2021 |
| HP            | ZBook 17 G2                 | [6149ab50a8](https://bsd-hardware.info/?probe=6149ab50a8) | Jul 24, 2021 |
| HP            | ZBook 17 G2                 | [1ef99f31dd](https://bsd-hardware.info/?probe=1ef99f31dd) | Jul 23, 2021 |
| HP            | ProBook 440 G7              | [63dc88528c](https://bsd-hardware.info/?probe=63dc88528c) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [7138e2a9e7](https://bsd-hardware.info/?probe=7138e2a9e7) | Jul 17, 2021 |
| HP            | ProBook 440 G7              | [b73eb50747](https://bsd-hardware.info/?probe=b73eb50747) | Jul 16, 2021 |
| HP            | EliteBook 8570p             | [462fc329a9](https://bsd-hardware.info/?probe=462fc329a9) | Jul 16, 2021 |
| HP            | ProBook 440 G7              | [d2866f01b5](https://bsd-hardware.info/?probe=d2866f01b5) | Jul 16, 2021 |
| Dell          | Latitude E6410              | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | [cc24e867fc](https://bsd-hardware.info/?probe=cc24e867fc) | Jun 19, 2021 |
| Pegatron      | T12Ah                       | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| HP            | EliteBook 8570p             | [52ba4e835f](https://bsd-hardware.info/?probe=52ba4e835f) | Jun 03, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [e27342ab94](https://bsd-hardware.info/?probe=e27342ab94) | May 13, 2021 |
| Toshiba       | TECRA M11                   | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| Pegatron      | T12Ah                       | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Acer          | Aspire V5-531               | [edbf1ff1c6](https://bsd-hardware.info/?probe=edbf1ff1c6) | May 01, 2021 |
| Acer          | Aspire V5-531               | [8282b3e5fb](https://bsd-hardware.info/?probe=8282b3e5fb) | May 01, 2021 |
| Dell          | Inspiron 3793               | [c2d56fc369](https://bsd-hardware.info/?probe=c2d56fc369) | Apr 29, 2021 |
| Apple         | MacBookPro8,1               | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Dell          | Inspiron 3793               | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Toshiba       | Satellite L50-C             | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Samsung       | NC10                        | [3307e80418](https://bsd-hardware.info/?probe=3307e80418) | Apr 17, 2021 |
| Samsung       | NC10                        | [dd4310d56f](https://bsd-hardware.info/?probe=dd4310d56f) | Apr 13, 2021 |
| Apple         | MacBookPro8,1               | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Dell          | Latitude E6430s             | [563ad840b0](https://bsd-hardware.info/?probe=563ad840b0) | Apr 07, 2021 |
| Toshiba       | Satellite L50-C             | [ff59142f85](https://bsd-hardware.info/?probe=ff59142f85) | Apr 03, 2021 |
| Apple         | MacBookPro8,1               | [e4e3731289](https://bsd-hardware.info/?probe=e4e3731289) | Apr 01, 2021 |
| Toshiba       | Satellite L50-C             | [32f33a7a8b](https://bsd-hardware.info/?probe=32f33a7a8b) | Mar 31, 2021 |
| Dell          | Latitude E6430s             | [c366bef9bf](https://bsd-hardware.info/?probe=c366bef9bf) | Mar 28, 2021 |
| HP            | EliteBook 8570p             | [ed80dc9019](https://bsd-hardware.info/?probe=ed80dc9019) | Mar 27, 2021 |
| Toshiba       | Satellite L50-C             | [70cf274538](https://bsd-hardware.info/?probe=70cf274538) | Mar 23, 2021 |
| Toshiba       | Satellite C660              | [7d64801e2b](https://bsd-hardware.info/?probe=7d64801e2b) | Mar 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b9eeb28ada](https://bsd-hardware.info/?probe=b9eeb28ada) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Toshiba       | Satellite C660              | [83f9d05407](https://bsd-hardware.info/?probe=83f9d05407) | Mar 14, 2021 |
| TUXEDO        | Aura 15 Gen1                | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| Toshiba       | Satellite Pro U400          | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| Apple         | MacBookPro5,5               | [50ac436475](https://bsd-hardware.info/?probe=50ac436475) | Mar 06, 2021 |
| Dell          | Latitude E5570              | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| Toshiba       | Satellite L50-C             | [3af26c7a29](https://bsd-hardware.info/?probe=3af26c7a29) | Feb 25, 2021 |
| Acer          | Aspire V5-531               | [fc868b6179](https://bsd-hardware.info/?probe=fc868b6179) | Feb 25, 2021 |
| GEO           | GeoBook3                    | [ba18b9bf80](https://bsd-hardware.info/?probe=ba18b9bf80) | Feb 19, 2021 |
| HP            | 250 G7 Notebook PC          | [366f8d1eaf](https://bsd-hardware.info/?probe=366f8d1eaf) | Feb 18, 2021 |
| Acer          | Aspire V5-531               | [ad4634140e](https://bsd-hardware.info/?probe=ad4634140e) | Feb 16, 2021 |
| HP            | 250 G7 Notebook PC          | [a3380d4b0c](https://bsd-hardware.info/?probe=a3380d4b0c) | Feb 16, 2021 |
| Pegatron      | T12Ah                       | [a5ab7068dc](https://bsd-hardware.info/?probe=a5ab7068dc) | Feb 14, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Dell          | Latitude E6420              | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| HP            | EliteBook 8570p             | [72137c63f8](https://bsd-hardware.info/?probe=72137c63f8) | Feb 09, 2021 |
| Alienware     | M18xR1                      | [67a336fac6](https://bsd-hardware.info/?probe=67a336fac6) | Feb 08, 2021 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [39c8cd6d0c](https://bsd-hardware.info/?probe=39c8cd6d0c) | Feb 08, 2021 |
| Sony          | VPCF12C5E                   | [df8c1de8a5](https://bsd-hardware.info/?probe=df8c1de8a5) | Feb 07, 2021 |
| Toshiba       | Satellite L50-C             | [7a5a694be1](https://bsd-hardware.info/?probe=7a5a694be1) | Feb 06, 2021 |
| Apple         | MacBookPro5,5               | [254e518190](https://bsd-hardware.info/?probe=254e518190) | Feb 03, 2021 |
| HP            | EliteBook 8570p             | [46c938b853](https://bsd-hardware.info/?probe=46c938b853) | Feb 01, 2021 |
| HP            | EliteBook 8570p             | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Pegatron      | T12Ah                       | [4bda74f229](https://bsd-hardware.info/?probe=4bda74f229) | Jan 31, 2021 |
| Acer          | Aspire V5-531               | [b917d2b6ad](https://bsd-hardware.info/?probe=b917d2b6ad) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | [98af88dfe6](https://bsd-hardware.info/?probe=98af88dfe6) | Jan 30, 2021 |
| Toshiba       | Satellite L50-C             | [f76ea8946b](https://bsd-hardware.info/?probe=f76ea8946b) | Jan 28, 2021 |
| Acer          | Aspire V5-531               | [41caa6acaa](https://bsd-hardware.info/?probe=41caa6acaa) | Jan 24, 2021 |
| HP            | EliteBook 8570p             | [c2e361eeff](https://bsd-hardware.info/?probe=c2e361eeff) | Jan 23, 2021 |
| Pegatron      | T12Ah                       | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| HP            | EliteBook 8570p             | [86e5ba4c5b](https://bsd-hardware.info/?probe=86e5ba4c5b) | Jan 22, 2021 |
| HP            | EliteBook 8570p             | [fcedf7a28d](https://bsd-hardware.info/?probe=fcedf7a28d) | Jan 19, 2021 |
| HP            | EliteBook 8570p             | [bb4f8afc82](https://bsd-hardware.info/?probe=bb4f8afc82) | Jan 09, 2021 |
| HP            | EliteBook 8570p             | [97a3ac7e36](https://bsd-hardware.info/?probe=97a3ac7e36) | Jan 08, 2021 |
| HP            | EliteBook 8570p             | [60d9540d35](https://bsd-hardware.info/?probe=60d9540d35) | Dec 31, 2020 |
| Pegatron      | T12Ah                       | [427bb18c90](https://bsd-hardware.info/?probe=427bb18c90) | Dec 27, 2020 |
| Toshiba       | Satellite L50-C             | [8195760dd6](https://bsd-hardware.info/?probe=8195760dd6) | Dec 23, 2020 |
| Samsung       | N140                        | [cab912c576](https://bsd-hardware.info/?probe=cab912c576) | Dec 21, 2020 |
| Toshiba       | Satellite L50-C             | [2b478c0d01](https://bsd-hardware.info/?probe=2b478c0d01) | Dec 08, 2020 |
| Acer          | Aspire V5-531               | [f62cab95dd](https://bsd-hardware.info/?probe=f62cab95dd) | Dec 03, 2020 |
| HP            | EliteBook 8570p             | [1f3fa432dc](https://bsd-hardware.info/?probe=1f3fa432dc) | Nov 21, 2020 |
| HP            | Compaq nx7400 (RU430ET#A... | [c9c7bae008](https://bsd-hardware.info/?probe=c9c7bae008) | Nov 01, 2020 |
| Toshiba       | Satellite L50-C             | [e5c99b958d](https://bsd-hardware.info/?probe=e5c99b958d) | Oct 31, 2020 |
| Acer          | Aspire V5-531               | [f9a374a310](https://bsd-hardware.info/?probe=f9a374a310) | Oct 30, 2020 |
| Lenovo        | ThinkPad T560 20FJS0CE00    | [be16cb1839](https://bsd-hardware.info/?probe=be16cb1839) | Oct 19, 2020 |
| Panasonic     | CF-C1BT02EGE                | [8a80fb614e](https://bsd-hardware.info/?probe=8a80fb614e) | Oct 19, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | [6cd0b0ed25](https://bsd-hardware.info/?probe=6cd0b0ed25) | Sep 28, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [d7d299f9fc](https://bsd-hardware.info/?probe=d7d299f9fc) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [ec434bfdcd](https://bsd-hardware.info/?probe=ec434bfdcd) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [628b379afb](https://bsd-hardware.info/?probe=628b379afb) | Sep 14, 2020 |
| ASUSTek       | ZenBook S UX391UA           | [decfd42a65](https://bsd-hardware.info/?probe=decfd42a65) | Sep 13, 2020 |
| Acer          | Aspire V5-531               | [9168df8552](https://bsd-hardware.info/?probe=9168df8552) | Aug 08, 2020 |
| Google        | Lulu                        | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Toshiba       | Satellite L50-C             | [cef5a64eb8](https://bsd-hardware.info/?probe=cef5a64eb8) | Jul 11, 2020 |
| Acer          | Aspire V5-531               | [2394ca7e03](https://bsd-hardware.info/?probe=2394ca7e03) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | [4f34d107bc](https://bsd-hardware.info/?probe=4f34d107bc) | Jul 03, 2020 |
| Toshiba       | Satellite L50-C             | [067478e4be](https://bsd-hardware.info/?probe=067478e4be) | Jul 03, 2020 |
| Lenovo        | ThinkPad X220 42902WU       | [e8a2f44b21](https://bsd-hardware.info/?probe=e8a2f44b21) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 10        | 8.26%   |
| FreeBSD 13.0         | 8         | 6.61%   |
| FreeBSD 14.0-CURRENT | 7         | 5.79%   |
| FreeBSD 13.1         | 6         | 4.96%   |
| OpenBSD 7.2          | 4         | 3.31%   |
| helloSystem 0.5.0    | 4         | 3.31%   |
| helloSystem 0.4.0    | 4         | 3.31%   |
| GhostBSD 20.04.02    | 4         | 3.31%   |
| FreeBSD 12.2         | 4         | 3.31%   |
| OpenBSD 7.1          | 3         | 2.48%   |
| OpenBSD 6.8          | 3         | 2.48%   |
| NomadBSD 1.4-RC1     | 3         | 2.48%   |
| NomadBSD 1.3.2       | 3         | 2.48%   |
| helloSystem 0.6.0    | 3         | 2.48%   |
| OPNsense 22.4.3      | 2         | 1.65%   |
| NomadBSD 20221130    | 2         | 1.65%   |
| helloSystem 0.8.1    | 2         | 1.65%   |
| helloSystem 0.8.0    | 2         | 1.65%   |
| GhostBSD 23.02.02    | 2         | 1.65%   |
| FreeBSD 13.0-p5      | 2         | 1.65%   |
| FreeBSD 13.0-CURRENT | 2         | 1.65%   |
| FreeBSD 12.2-p6      | 2         | 1.65%   |
| FreeBSD 12.2-p4      | 2         | 1.65%   |
| FreeBSD 12.2-p3      | 2         | 1.65%   |
| FreeBSD 12.2-p2      | 2         | 1.65%   |
| FreeBSD 12.1-p9      | 2         | 1.65%   |
| OPNsense 23.1.1      | 1         | 0.83%   |
| OPNsense 22.7.4      | 1         | 0.83%   |
| OPNsense 22.1.6      | 1         | 0.83%   |
| OPNsense 22.1.10     | 1         | 0.83%   |
| OPNsense 21.1.4      | 1         | 0.83%   |
| OPNsense 21.1.3      | 1         | 0.83%   |
| OPNsense 21.1.1      | 1         | 0.83%   |
| OpenBSD 7.0          | 1         | 0.83%   |
| OpenBSD 6.9          | 1         | 0.83%   |
| NomadBSD 1.4         | 1         | 0.83%   |
| helloSystem          | 1         | 0.83%   |
| GhostBSD 22.08.06    | 1         | 0.83%   |
| GhostBSD 22.06.26    | 1         | 0.83%   |
| GhostBSD 22.06.07    | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 32        | 34.41%  |
| helloSystem | 23        | 24.73%  |
| OpenBSD     | 12        | 12.9%   |
| NomadBSD    | 9         | 9.68%   |
| GhostBSD    | 9         | 9.68%   |
| OPNsense    | 6         | 6.45%   |
| FuryBSD     | 1         | 1.08%   |
| DragonFly   | 1         | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 86        | 97.73%  |
| i386  | 2         | 2.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 28        | 30.11%  |
| KDE5          | 12        | 12.9%   |
| XFCE          | 11        | 11.83%  |
| MATE          | 11        | 11.83%  |
| Console       | 10        | 10.75%  |
| Openbox       | 8         | 8.6%    |
| fvwm          | 5         | 5.38%   |
| i3            | 3         | 3.23%   |
| GNOME         | 2         | 2.15%   |
| Cinnamon      | 2         | 2.15%   |
| Enlightenment | 1         | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 76        | 84.44%  |
| Console | 12        | 13.33%  |
| Wayland | 2         | 2.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 37        | 40.22%  |
| Console | 26        | 28.26%  |
| SDDM    | 17        | 18.48%  |
| LightDM | 9         | 9.78%   |
| XDM     | 3         | 3.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 30        | 30.61%  |
| Unknown         | 26        | 26.53%  |
| C               | 25        | 25.51%  |
| en_GB           | 13        | 13.27%  |
| ru_RU           | 1         | 1.02%   |
| it_CH           | 1         | 1.02%   |
| en_GB.US-ASCII  | 1         | 1.02%   |
| en_GB.ISO8859-1 | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 71        | 79.78%  |
| BIOS | 18        | 20.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 47        | 51.09%  |
| Ufs     | 25        | 27.17%  |
| Ffs     | 12        | 13.04%  |
| Cd9660  | 7         | 7.61%   |
| Hammer2 | 1         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 78        | 87.64%  |
| MBR     | 9         | 10.11%  |
| BSD     | 1         | 1.12%   |
| Unknown | 1         | 1.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 27.27%  |
| Hewlett-Packard     | 13        | 14.77%  |
| Dell                | 12        | 13.64%  |
| Apple               | 5         | 5.68%   |
| Toshiba             | 4         | 4.55%   |
| Samsung Electronics | 4         | 4.55%   |
| Deciso              | 3         | 3.41%   |
| ASUSTek Computer    | 3         | 3.41%   |
| Star Labs           | 2         | 2.27%   |
| HUAWEI              | 2         | 2.27%   |
| TUXEDO              | 1         | 1.14%   |
| System76            | 1         | 1.14%   |
| Sony                | 1         | 1.14%   |
| Pegatron            | 1         | 1.14%   |
| Panasonic           | 1         | 1.14%   |
| Packard Bell        | 1         | 1.14%   |
| OEGStone            | 1         | 1.14%   |
| MSI                 | 1         | 1.14%   |
| Jumper              | 1         | 1.14%   |
| Google              | 1         | 1.14%   |
| GEO                 | 1         | 1.14%   |
| Fujitsu Siemens     | 1         | 1.14%   |
| Fujitsu             | 1         | 1.14%   |
| Dynabook Europe     | 1         | 1.14%   |
| Alienware           | 1         | 1.14%   |
| Acer                | 1         | 1.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 8570p                       | 3         | 3.41%   |
| Dell XPS 13 9343                         | 2         | 2.27%   |
| Dell Inspiron 3793                       | 2         | 2.27%   |
| Deciso OPNsense Appliance                | 2         | 2.27%   |
| ASUS ZenBook S UX391UA                   | 2         | 2.27%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.14%   |
| Toshiba TECRA M11                        | 1         | 1.14%   |
| Toshiba Satellite Pro U400               | 1         | 1.14%   |
| Toshiba Satellite L50-C                  | 1         | 1.14%   |
| Toshiba Satellite C660                   | 1         | 1.14%   |
| System76 Gazelle                         | 1         | 1.14%   |
| Star Labs StarBook                       | 1         | 1.14%   |
| Star Labs Lite                           | 1         | 1.14%   |
| Sony VPCF12C5E                           | 1         | 1.14%   |
| Samsung NC10                             | 1         | 1.14%   |
| Samsung N140                             | 1         | 1.14%   |
| Samsung 550P5C/550P7C                    | 1         | 1.14%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.14%   |
| Pegatron T12Ah                           | 1         | 1.14%   |
| Panasonic CF-C1BT02EGE                   | 1         | 1.14%   |
| Packard Bell EasyNote_MX52-B-071         | 1         | 1.14%   |
| OEGStone W54_55SU1,SUW                   | 1         | 1.14%   |
| MSI Modern 14 B11MOL                     | 1         | 1.14%   |
| Lenovo Z50-70 20354                      | 1         | 1.14%   |
| Lenovo ThinkPad Yoga 11e 20D9000QUK      | 1         | 1.14%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DS00    | 1         | 1.14%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05    | 1         | 1.14%   |
| Lenovo ThinkPad X240 20AMS1YG01          | 1         | 1.14%   |
| Lenovo ThinkPad X230 2325J67             | 1         | 1.14%   |
| Lenovo ThinkPad X230 23255NG             | 1         | 1.14%   |
| Lenovo ThinkPad X220 4291QT1             | 1         | 1.14%   |
| Lenovo ThinkPad X220 4291H77             | 1         | 1.14%   |
| Lenovo ThinkPad X220 42902WU             | 1         | 1.14%   |
| Lenovo ThinkPad X201 3680MG1             | 1         | 1.14%   |
| Lenovo ThinkPad X200 7459ZLW             | 1         | 1.14%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK | 1         | 1.14%   |
| Lenovo ThinkPad W520 42844DG             | 1         | 1.14%   |
| Lenovo ThinkPad T560 20FJS0CE00          | 1         | 1.14%   |
| Lenovo ThinkPad T470 20HD000MUK          | 1         | 1.14%   |
| Lenovo ThinkPad T460 20FMS3320G          | 1         | 1.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 21        | 23.86%  |
| Dell Latitude          | 5         | 5.68%   |
| Toshiba Satellite      | 3         | 3.41%   |
| HP EliteBook           | 3         | 3.41%   |
| Dell Inspiron          | 3         | 3.41%   |
| Apple MacBookPro5      | 3         | 3.41%   |
| Lenovo IdeaPad         | 2         | 2.27%   |
| HP ProBook             | 2         | 2.27%   |
| HP Pavilion            | 2         | 2.27%   |
| Dell XPS               | 2         | 2.27%   |
| Deciso OPNsense        | 2         | 2.27%   |
| ASUS ZenBook           | 2         | 2.27%   |
| TUXEDO Aura            | 1         | 1.14%   |
| Toshiba TECRA          | 1         | 1.14%   |
| System76 Gazelle       | 1         | 1.14%   |
| Star Labs StarBook     | 1         | 1.14%   |
| Star Labs Lite         | 1         | 1.14%   |
| Sony VPCF12C5E         | 1         | 1.14%   |
| Samsung NC10           | 1         | 1.14%   |
| Samsung N140           | 1         | 1.14%   |
| Samsung 550P5C         | 1         | 1.14%   |
| Samsung 305E4A         | 1         | 1.14%   |
| Pegatron T12Ah         | 1         | 1.14%   |
| Panasonic CF-C1BT02EGE | 1         | 1.14%   |
| Packard Bell EasyNote  | 1         | 1.14%   |
| OEGStone W54           | 1         | 1.14%   |
| MSI Modern             | 1         | 1.14%   |
| Lenovo Z50-70          | 1         | 1.14%   |
| Jumper EZbook          | 1         | 1.14%   |
| HUAWEI MACHD-WXX9      | 1         | 1.14%   |
| HUAWEI BOM-WXX9        | 1         | 1.14%   |
| HP ZBook               | 1         | 1.14%   |
| HP Laptop              | 1         | 1.14%   |
| HP ENVY                | 1         | 1.14%   |
| HP Compaq              | 1         | 1.14%   |
| HP 250                 | 1         | 1.14%   |
| HP 15                  | 1         | 1.14%   |
| Google Lulu            | 1         | 1.14%   |
| GEO GeoBook3           | 1         | 1.14%   |
| Fujitsu Siemens AMILO  | 1         | 1.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 9         | 10.23%  |
| 2016 | 8         | 9.09%   |
| 2011 | 8         | 9.09%   |
| 2022 | 7         | 7.95%   |
| 2012 | 7         | 7.95%   |
| 2010 | 7         | 7.95%   |
| 2019 | 6         | 6.82%   |
| 2018 | 6         | 6.82%   |
| 2013 | 6         | 6.82%   |
| 2009 | 6         | 6.82%   |
| 2021 | 5         | 5.68%   |
| 2015 | 3         | 3.41%   |
| 2014 | 3         | 3.41%   |
| 2008 | 3         | 3.41%   |
| 2007 | 2         | 2.27%   |
| 2023 | 1         | 1.14%   |
| 2017 | 1         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 88        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 95.45%  |
| Yes  | 4         | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 43        | 47.78%  |
| 4.01-8.0    | 21        | 23.33%  |
| 16.01-24.0  | 17        | 18.89%  |
| 32.01-64.0  | 4         | 4.44%   |
| 2.01-3.0    | 3         | 3.33%   |
| 3.01-4.0    | 1         | 1.11%   |
| 64.01-256.0 | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 56        | 60.22%  |
| 0.51-1.0  | 26        | 27.96%  |
| 1.01-2.0  | 5         | 5.38%   |
| 2.01-3.0  | 3         | 3.23%   |
| 4.01-8.0  | 1         | 1.08%   |
| 3.01-4.0  | 1         | 1.08%   |
| 8.01-16.0 | 1         | 1.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 70.83%  |
| 2      | 22        | 22.92%  |
| 0      | 4         | 4.17%   |
| 3      | 2         | 2.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 67.39%  |
| Yes       | 30        | 32.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 79.55%  |
| No        | 18        | 20.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 96.59%  |
| No        | 3         | 3.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 61.54%  |
| No        | 35        | 38.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 88        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 10        | 9.71%   |
| Brighton            | 7         | 6.8%    |
| Glasgow             | 5         | 4.85%   |
| Leatherhead         | 3         | 2.91%   |
| City of London      | 3         | 2.91%   |
| Worthing            | 2         | 1.94%   |
| Swindon             | 2         | 1.94%   |
| Greenwich           | 2         | 1.94%   |
| Gloucester          | 2         | 1.94%   |
| Coventry            | 2         | 1.94%   |
| Wraysbury           | 1         | 0.97%   |
| Woking              | 1         | 0.97%   |
| Watford             | 1         | 0.97%   |
| Walsall             | 1         | 0.97%   |
| Wakefield           | 1         | 0.97%   |
| Tottenham           | 1         | 0.97%   |
| Tatsfield           | 1         | 0.97%   |
| Sutton              | 1         | 0.97%   |
| St Austell          | 1         | 0.97%   |
| Southampton         | 1         | 0.97%   |
| Shoreham-by-Sea     | 1         | 0.97%   |
| Ruislip             | 1         | 0.97%   |
| Rugby               | 1         | 0.97%   |
| Reigate             | 1         | 0.97%   |
| Reading             | 1         | 0.97%   |
| Plymouth            | 1         | 0.97%   |
| Peterborough        | 1         | 0.97%   |
| Perth               | 1         | 0.97%   |
| Oxford              | 1         | 0.97%   |
| Oxenhope            | 1         | 0.97%   |
| Okehampton          | 1         | 0.97%   |
| Notting Hill Gate   | 1         | 0.97%   |
| North Tawton        | 1         | 0.97%   |
| Newcastle upon Tyne | 1         | 0.97%   |
| Morden              | 1         | 0.97%   |
| Milton Keynes       | 1         | 0.97%   |
| Middlesbrough       | 1         | 0.97%   |
| Manchester          | 1         | 0.97%   |
| Malton              | 1         | 0.97%   |
| Lytham St Annes     | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 46     | 24.55%  |
| WDC                 | 13        | 18     | 11.82%  |
| Toshiba             | 9         | 23     | 8.18%   |
| Seagate             | 8         | 8      | 7.27%   |
| HGST                | 6         | 26     | 5.45%   |
| Intel               | 4         | 4      | 3.64%   |
| Hitachi             | 4         | 4      | 3.64%   |
| Transcend           | 3         | 5      | 2.73%   |
| SanDisk             | 3         | 3      | 2.73%   |
| NVMe                | 3         | 3      | 2.73%   |
| Kingston            | 3         | 3      | 2.73%   |
| Crucial             | 3         | 3      | 2.73%   |
| XUM                 | 2         | 2      | 1.82%   |
| Star Drive          | 2         | 2      | 1.82%   |
| SK hynix            | 2         | 2      | 1.82%   |
| Corsair             | 2         | 2      | 1.82%   |
| Apple               | 2         | 3      | 1.82%   |
| UMIS                | 1         | 1      | 0.91%   |
| Solid State Storage | 1         | 1      | 0.91%   |
| SATA3 60            | 1         | 1      | 0.91%   |
| PNY                 | 1         | 1      | 0.91%   |
| Phison              | 1         | 1      | 0.91%   |
| OWC                 | 1         | 1      | 0.91%   |
| Micron Technology   | 1         | 1      | 0.91%   |
| MicroDream          | 1         | 1      | 0.91%   |
| LITEON              | 1         | 1      | 0.91%   |
| Lexar               | 1         | 1      | 0.91%   |
| Intenso             | 1         | 1      | 0.91%   |
| Fujitsu             | 1         | 6      | 0.91%   |
| Apacer              | 1         | 1      | 0.91%   |
| A-DATA Technology   | 1         | 1      | 0.91%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 5         | 4.46%   |
| HGST HTS725050A7E630 500GB                         | 4         | 3.57%   |
| Samsung HM251JX 250GB                              | 3         | 2.68%   |
| XUM HX256GSSDSATA3 256GB                           | 2         | 1.79%   |
| WDC WDS250G2B0B-00YS70 250GB                       | 2         | 1.79%   |
| WDC WDS240G2G0A-00JH30 240GB                       | 2         | 1.79%   |
| WDC WD1600BEVT-80A23T0 160GB                       | 2         | 1.79%   |
| WDC WD1600BEVT-22ZCT0 160GB                        | 2         | 1.79%   |
| Transcend TS256GMTE652T2 256GB                     | 2         | 1.79%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 1.79%   |
| Samsung SSD PM851 M.2 2280 256GB                   | 2         | 1.79%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 1.79%   |
| Samsung MZVLW512HMJP-00000 512GB                   | 2         | 1.79%   |
| WDC WDS250G2B0A 250GB                              | 1         | 0.89%   |
| WDC WDS120G2G0A-00JH30 120GB                       | 1         | 0.89%   |
| WDC WD7500BPKX-00HPJT0 752GB                       | 1         | 0.89%   |
| WDC WD2500BEVT-80A23T0 250GB                       | 1         | 0.89%   |
| WDC WD1600BEVS-08VAT2 160GB                        | 1         | 0.89%   |
| UMIS RPJTJ512MEE1OWX 512GB                         | 1         | 0.89%   |
| Transcend TS128GMTE110S 128GB                      | 1         | 0.89%   |
| Toshiba THNSNJ128GMCU 128GB                        | 1         | 0.89%   |
| Toshiba THNSF5256GPUK 256GB                        | 1         | 0.89%   |
| Toshiba MK5061GSY 500GB                            | 1         | 0.89%   |
| Toshiba KBG30ZMV256G 256GB                         | 1         | 0.89%   |
| Star Drive SATA SSD 960GB                          | 1         | 0.89%   |
| Star Drive PCIe SSD 960GB                          | 1         | 0.89%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.89%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB               | 1         | 0.89%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.89%   |
| Seagate ST9320423AS 320GB                          | 1         | 0.89%   |
| Seagate ST9160821AS 160GB                          | 1         | 0.89%   |
| Seagate ST9160310AS 160GB                          | 1         | 0.89%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 0.89%   |
| Seagate ST2000LM005 HN-M201AAD 2TB                 | 1         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 0.89%   |
| SATA3 60 GB SSD 64GB                               | 1         | 0.89%   |
| SanDisk SD6SB1M128G1022I 128GB                     | 1         | 0.89%   |
| SanDisk Extreme 55AE 500GB                         | 1         | 0.89%   |
| SanDisk Cruzer Fit 32GB                            | 1         | 0.89%   |
| Samsung SSD PM871 2.5 7mm 128GB                    | 1         | 0.89%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 21.62%  |
| WDC                 | 7         | 8      | 18.92%  |
| Toshiba             | 6         | 18     | 16.22%  |
| HGST                | 6         | 26     | 16.22%  |
| Hitachi             | 4         | 4      | 10.81%  |
| Samsung Electronics | 3         | 3      | 8.11%   |
| NVMe                | 2         | 2      | 5.41%   |
| Fujitsu             | 1         | 6      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 33     | 29.63%  |
| WDC                 | 6         | 10     | 11.11%  |
| SanDisk             | 3         | 3      | 5.56%   |
| Kingston            | 3         | 3      | 5.56%   |
| Intel               | 3         | 3      | 5.56%   |
| Crucial             | 3         | 3      | 5.56%   |
| XUM                 | 2         | 2      | 3.7%    |
| Corsair             | 2         | 2      | 3.7%    |
| Apple               | 2         | 3      | 3.7%    |
| Toshiba             | 1         | 1      | 1.85%   |
| Star Drive          | 1         | 1      | 1.85%   |
| SATA3 60            | 1         | 1      | 1.85%   |
| PNY                 | 1         | 1      | 1.85%   |
| Phison              | 1         | 1      | 1.85%   |
| OWC                 | 1         | 1      | 1.85%   |
| NVMe                | 1         | 1      | 1.85%   |
| Micron Technology   | 1         | 1      | 1.85%   |
| MicroDream          | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| Lexar               | 1         | 1      | 1.85%   |
| Intenso             | 1         | 1      | 1.85%   |
| Apacer              | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 49        | 76     | 49.49%  |
| HDD  | 31        | 75     | 31.31%  |
| NVMe | 19        | 25     | 19.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 71        | 151    | 78.89%  |
| NVMe | 19        | 25     | 21.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 122    | 80.26%  |
| 0.51-1.0   | 11        | 24     | 14.47%  |
| 1.01-2.0   | 4         | 5      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 37        | 37.37%  |
| 1-20       | 23        | 23.23%  |
| 251-500    | 18        | 18.18%  |
| 501-1000   | 9         | 9.09%   |
| 21-50      | 5         | 5.05%   |
| 51-100     | 3         | 3.03%   |
| Unknown    | 3         | 3.03%   |
| 1001-2000  | 1         | 1.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 73        | 74.49%  |
| 21-50   | 15        | 15.31%  |
| 51-100  | 5         | 5.1%    |
| Unknown | 3         | 3.06%   |
| 101-250 | 2         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                       | 4         | 10     | 25%     |
| WDC WD2500BEVT-80A23T0 250GB                     | 1         | 1      | 6.25%   |
| WDC WD1600BEVT-80A23T0 160GB                     | 1         | 1      | 6.25%   |
| Seagate ST9320423AS 320GB                        | 1         | 1      | 6.25%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 6.25%   |
| Samsung Electronics SSD PM810 2.5-inch 7mm 256GB | 1         | 1      | 6.25%   |
| Samsung Electronics HM251JX 250GB                | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB       | 1         | 1      | 6.25%   |
| Hitachi HTS545032B9A302 320GB                    | 1         | 1      | 6.25%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB                         | 1         | 14     | 6.25%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 6.25%   |
| A-DATA Technology SP550 240GB                    | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 25     | 33.33%  |
| WDC                 | 2         | 2      | 13.33%  |
| Seagate             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Hitachi             | 2         | 2      | 13.33%  |
| Micron Technology   | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 25     | 41.67%  |
| WDC                 | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Hitachi             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 32     | 78.57%  |
| SSD  | 3         | 3      | 21.43%  |

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
| Works    | 75        | 134    | 79.79%  |
| Malfunc  | 14        | 35     | 14.89%  |
| Detected | 5         | 7      | 5.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 66        | 69.47%  |
| Samsung Electronics                     | 10        | 10.53%  |
| AMD                                     | 4         | 4.21%   |
| Transcend                               | 3         | 3.16%   |
| Nvidia                                  | 3         | 3.16%   |
| Toshiba                                 | 2         | 2.11%   |
| SK hynix                                | 2         | 2.11%   |
| Phison Electronics                      | 2         | 2.11%   |
| Solid State Storage Technology          | 1         | 1.05%   |
| Shenzhen Unionmemory Information System | 1         | 1.05%   |
| Kingston Technology Company             | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 8.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 7.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 6.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 4.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 4.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.85%   |
| Unknown                                                                          | 5         | 4.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 3.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 2.91%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.91%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 2.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.91%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3         | 2.91%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.94%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.97%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.97%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.97%   |
| SK hynix BC511                                                                   | 1         | 0.97%   |
| Samsung SM951 AHCI                                                               | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.97%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.97%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.97%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.97%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.97%   |
| Intel SSD 660P Series                                                            | 1         | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.97%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.97%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 63        | 63.64%  |
| NVMe | 21        | 21.21%  |
| RAID | 8         | 8.08%   |
| IDE  | 7         | 7.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 88.64%  |
| AMD    | 9         | 10.23%  |
| 11th   | 1         | 1.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz        | 4         | 4.55%   |
| Intel CPU Version                        | 3         | 3.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 3.41%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 3.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 3.41%   |
| AMD Ryzen Embedded V1500B                | 3         | 3.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 2         | 2.27%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 2.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 2         | 2.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 2         | 2.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 2         | 2.27%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 2         | 2.27%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 2         | 2.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 2.27%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 1.14%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 1.14%   |
| Intel Pentium CPU 967 @ 1.30GHz          | 1         | 1.14%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 1         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 1         | 1.14%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 1.14%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz       | 1         | 1.14%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz       | 1         | 1.14%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 1.14%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 1.14%   |
| Intel Core i7-3612QM CPU @ 2.10GHz       | 1         | 1.14%   |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.14%   |
| Intel Core i7-2820QM CPU @ 2.30GHz       | 1         | 1.14%   |
| Intel Core i7-2630QM CPU @ 2.00GHz       | 1         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.14%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz        | 1         | 1.14%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 1         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.14%   |
| Intel Core i5-4278U CPU @ 2.60GHz        | 1         | 1.14%   |
| Intel Core i5-4210M CPU @ 2.60GHz        | 1         | 1.14%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.14%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 1.14%   |
| Intel Core i5-2410M CPU @ 2.30GH         | 1         | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 27        | 30.68%  |
| Intel Core i7        | 24        | 27.27%  |
| Other                | 8         | 9.09%   |
| Intel Core 2 Duo     | 8         | 9.09%   |
| Intel Celeron        | 6         | 6.82%   |
| AMD Ryzen Embedded   | 3         | 3.41%   |
| Intel Pentium        | 2         | 2.27%   |
| AMD Ryzen 7          | 2         | 2.27%   |
| AMD A6               | 2         | 2.27%   |
| Intel Pentium Silver | 1         | 1.14%   |
| Intel Core i3        | 1         | 1.14%   |
| Intel Core 2         | 1         | 1.14%   |
| Intel Atom           | 1         | 1.14%   |
| AMD Ryzen 5          | 1         | 1.14%   |
| AMD Athlon 64 X2     | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 46        | 52.27%  |
| 4       | 24        | 27.27%  |
| Unknown | 8         | 9.09%   |
| 8       | 4         | 4.55%   |
| 1       | 3         | 3.41%   |
| 16      | 2         | 2.27%   |
| 12      | 1         | 1.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 84        | 95.45%  |
| 2       | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 58        | 65.91%  |
| 1       | 22        | 25%     |
| Unknown | 8         | 9.09%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 10        | 11.36%  |
| Haswell       | 10        | 11.36%  |
| IvyBridge     | 9         | 10.23%  |
| Skylake       | 8         | 9.09%   |
| Penryn        | 8         | 9.09%   |
| KabyLake      | 7         | 7.95%   |
| Westmere      | 4         | 4.55%   |
| Goldmont plus | 4         | 4.55%   |
| Unknown       | 4         | 4.55%   |
| Zen           | 3         | 3.41%   |
| TigerLake     | 3         | 3.41%   |
| Broadwell     | 3         | 3.41%   |
| Bonnell       | 3         | 3.41%   |
| Silvermont    | 2         | 2.27%   |
| IceLake       | 2         | 2.27%   |
| Core          | 2         | 2.27%   |
| Zen 2         | 1         | 1.14%   |
| Nehalem       | 1         | 1.14%   |
| K8 Hammer     | 1         | 1.14%   |
| K10 Llano     | 1         | 1.14%   |
| Goldmont      | 1         | 1.14%   |
| Excavator     | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 74.74%  |
| Nvidia | 14        | 14.74%  |
| AMD    | 10        | 10.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 9.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 6.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 5.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 4.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 3.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.92%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 2.94%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 2.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.94%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 2.94%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 1.96%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.96%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.96%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.96%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.96%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.96%   |
| Intel HD Graphics 530                                                                    | 2         | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.96%   |
| AMD Lucienne                                                                             | 2         | 1.96%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 0.98%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.98%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.98%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.98%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 0.98%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.98%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.98%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 0.98%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.98%   |
| Intel HD Graphics 620                                                                    | 1         | 0.98%   |
| Intel HD Graphics 500                                                                    | 1         | 0.98%   |
| Intel HD Graphics                                                                        | 1         | 0.98%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.98%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.98%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 57.3%   |
| 2 x Intel      | 10        | 11.24%  |
| Intel + Nvidia | 9         | 10.11%  |
| 1 x AMD        | 9         | 10.11%  |
| 1 x Nvidia     | 4         | 4.49%   |
| Other          | 3         | 3.37%   |
| 2 x Nvidia     | 2         | 2.25%   |
| Intel + AMD    | 1         | 1.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 79        | 88.76%  |
| Unknown     | 6         | 6.74%   |
| Proprietary | 4         | 4.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 90%     |
| 1.01-2.0   | 3         | 3.33%   |
| 0.51-1.0   | 3         | 3.33%   |
| 0.01-0.5   | 3         | 3.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 13        | 20.31%  |
| LG Display              | 10        | 15.63%  |
| Samsung Electronics     | 6         | 9.38%   |
| Chimei Innolux          | 5         | 7.81%   |
| Philips                 | 4         | 6.25%   |
| Lenovo                  | 4         | 6.25%   |
| BOE                     | 4         | 6.25%   |
| Sharp                   | 3         | 4.69%   |
| LG Philips              | 2         | 3.13%   |
| Hewlett-Packard         | 2         | 3.13%   |
| HannStar                | 2         | 3.13%   |
| Apple                   | 2         | 3.13%   |
| Vestel Elektronik       | 1         | 1.56%   |
| Sony                    | 1         | 1.56%   |
| SDC                     | 1         | 1.56%   |
| PANDA                   | 1         | 1.56%   |
| InnoLux Display         | 1         | 1.56%   |
| CPT                     | 1         | 1.56%   |
| Chi Mei Optoelectronics | 1         | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch             | 3         | 4.55%   |
| LG Display LCD Monitor LGD0258 1600x900 350x190mm 15.7-inch           | 3         | 4.55%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 4.55%   |
| Sharp LCD Monitor SHP1421 3200x1800 290x170mm 13.2-inch               | 2         | 3.03%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 290x170mm 13.2-inch        | 2         | 3.03%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 1.52%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                  | 1         | 1.52%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 1.52%   |
| SDC LCD Monitor 3520x1080                                             | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch  | 1         | 1.52%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 380x210mm 17.1-inch  | 1         | 1.52%   |
| Philips LCD Monitor 271P4 3520x1080                                   | 1         | 1.52%   |
| Philips LCD Monitor 271P4                                             | 1         | 1.52%   |
| PANDA LCD Monitor NCP004F 1920x1080 310x170mm 13.9-inch               | 1         | 1.52%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.52%   |
| LG Philips LCD Monitor LPL1279 1680x1050 330x210mm 15.4-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD6E01 1366x768 340x190mm 15.3-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 1.52%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x170mm 13.9-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.52%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 1         | 1.52%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch               | 1         | 1.52%   |
| InnoLux Display BT101IW03V1 INL000D 1024x600 220x120mm 9.9-inch       | 1         | 1.52%   |
| Hewlett-Packard LCD Monitor LA2306 3520x1080                          | 1         | 1.52%   |
| Hewlett-Packard LA2306 HWP2949 1920x1080 510x290mm 23.1-inch          | 1         | 1.52%   |
| HannStar LCD Monitor HSD1CF3 1920x1200 590x370mm 27.4-inch            | 1         | 1.52%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.52%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                  | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch      | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 1         | 1.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 18        | 28.57%  |
| 1366x768 (WXGA)    | 16        | 25.4%   |
| 1280x800 (WXGA)    | 7         | 11.11%  |
| 1600x900 (HD+)     | 6         | 9.52%   |
| 3200x1800 (QHD+)   | 3         | 4.76%   |
| 1024x600           | 3         | 4.76%   |
| 1920x1200 (WUXGA)  | 2         | 3.17%   |
| 3520x1080          | 1         | 1.59%   |
| 2880x1800          | 1         | 1.59%   |
| 2560x1440 (QHD)    | 1         | 1.59%   |
| 1920x540           | 1         | 1.59%   |
| 1680x1050 (WSXGA+) | 1         | 1.59%   |
| 1440x900 (WXGA+)   | 1         | 1.59%   |
| 1280x1024 (SXGA)   | 1         | 1.59%   |
| Unknown            | 1         | 1.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 20        | 31.75%  |
| 13      | 17        | 26.98%  |
| 12      | 6         | 9.52%   |
| 27      | 4         | 6.35%   |
| 17      | 4         | 6.35%   |
| 11      | 2         | 3.17%   |
| 10      | 2         | 3.17%   |
| 42      | 1         | 1.59%   |
| 23      | 1         | 1.59%   |
| 22      | 1         | 1.59%   |
| 19      | 1         | 1.59%   |
| 18      | 1         | 1.59%   |
| 14      | 1         | 1.59%   |
| 9       | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 46.77%  |
| 201-300     | 20        | 32.26%  |
| 351-400     | 5         | 8.06%   |
| 501-600     | 4         | 6.45%   |
| 401-500     | 2         | 3.23%   |
| 901-1000    | 1         | 1.61%   |
| Unknown     | 1         | 1.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 42        | 73.68%  |
| 16/10   | 12        | 21.05%  |
| 5/4     | 1         | 1.75%   |
| 3/2     | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 19.05%  |
| 101-110        | 10        | 15.87%  |
| 91-100         | 10        | 15.87%  |
| 71-80          | 6         | 9.52%   |
| 61-70          | 6         | 9.52%   |
| 301-350        | 4         | 6.35%   |
| 121-130        | 4         | 6.35%   |
| 41-50          | 3         | 4.76%   |
| 51-60          | 2         | 3.17%   |
| 201-250        | 2         | 3.17%   |
| 151-200        | 1         | 1.59%   |
| 141-150        | 1         | 1.59%   |
| 501-1000       | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 20        | 32.79%  |
| 101-120       | 19        | 31.15%  |
| 51-100        | 11        | 18.03%  |
| 161-240       | 7         | 11.48%  |
| More than 240 | 3         | 4.92%   |
| Unknown       | 1         | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 70.33%  |
| 0     | 22        | 24.18%  |
| 2     | 5         | 5.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 64        | 46.72%  |
| Realtek Semiconductor             | 27        | 19.71%  |
| Qualcomm Atheros                  | 13        | 9.49%   |
| Broadcom                          | 8         | 5.84%   |
| Marvell Technology Group          | 4         | 2.92%   |
| Nvidia                            | 3         | 2.19%   |
| Hewlett-Packard                   | 3         | 2.19%   |
| D-Link System                     | 3         | 2.19%   |
| AMD                               | 3         | 2.19%   |
| Sierra Wireless                   | 2         | 1.46%   |
| Ericsson Business Mobile Networks | 2         | 1.46%   |
| Edimax Technology                 | 2         | 1.46%   |
| Dell                              | 2         | 1.46%   |
| TP-Link                           | 1         | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 16        | 8.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 14        | 7.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 11        | 6.18%   |
| Intel Wireless 7260                                                         | 8         | 4.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 3.93%   |
| Intel Wireless 8260                                                         | 7         | 3.93%   |
| Intel Ethernet Connection I219-LM                                           | 5         | 2.81%   |
| Intel Wi-Fi 6 AX201                                                         | 4         | 2.25%   |
| Intel Ethernet Connection I218-LM                                           | 4         | 2.25%   |
| Intel Centrino Ultimate-N 6300                                              | 4         | 2.25%   |
| Intel Centrino Advanced-N 6200                                              | 4         | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 3         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 1.69%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 1.69%   |
| Intel Wireless 8265 / 8275                                                  | 3         | 1.69%   |
| Intel Wireless 3165                                                         | 3         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 1.69%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                     | 3         | 1.69%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 3         | 1.69%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 1.69%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                   | 3         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 2         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 1.12%   |
| Intel I211 Gigabit Network Connection                                       | 2         | 1.12%   |
| Intel I210 Gigabit Network Connection                                       | 2         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 2         | 1.12%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.12%   |
| Dell DW5811e Snapdragon X7 LTE DM Port                                      | 2         | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 0.56%   |
| Sierra Wireless EM7345 4G LTE                                               | 1         | 0.56%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 0.56%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 63.04%  |
| Qualcomm Atheros      | 12        | 13.04%  |
| Realtek Semiconductor | 9         | 9.78%   |
| Broadcom              | 6         | 6.52%   |
| D-Link System         | 3         | 3.26%   |
| Edimax Technology     | 2         | 2.17%   |
| TP-Link               | 1         | 1.09%   |
| Sierra Wireless       | 1         | 1.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 11        | 11.7%   |
| Intel Wireless 7260                                                        | 8         | 8.51%   |
| Intel Wireless 8260                                                        | 7         | 7.45%   |
| Intel Wi-Fi 6 AX201                                                        | 4         | 4.26%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 4.26%   |
| Intel Centrino Advanced-N 6200                                             | 4         | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 3.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 3         | 3.19%   |
| Intel Wireless 8265 / 8275                                                 | 3         | 3.19%   |
| Intel Wireless 3165                                                        | 3         | 3.19%   |
| Intel Wi-Fi 6 AX200                                                        | 3         | 3.19%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 3         | 3.19%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 2.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 2.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 2         | 2.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 1.06%   |
| Sierra Wireless EM7345 4G LTE                                              | 1         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 1.06%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1         | 1.06%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 1         | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 1.06%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)    | 1         | 1.06%   |
| Intel Wireless 3160                                                        | 1         | 1.06%   |
| Intel WiFi Link 5100                                                       | 1         | 1.06%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.06%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 1         | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 1         | 1.06%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                   | 1         | 1.06%   |
| Edimax AC600 Wireless LAN USB Adapter                                      | 1         | 1.06%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 36        | 48%     |
| Realtek Semiconductor    | 24        | 32%     |
| Marvell Technology Group | 4         | 5.33%   |
| Nvidia                   | 3         | 4%      |
| Broadcom                 | 3         | 4%      |
| AMD                      | 3         | 4%      |
| Qualcomm Atheros         | 2         | 2.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 21.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 18.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 9.21%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 6.58%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 5.26%   |
| Nvidia MCP79 Ethernet                                             | 3         | 3.95%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.95%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 3         | 3.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 2.63%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.63%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.32%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.32%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.32%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.32%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.32%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 52.15%  |
| Ethernet | 70        | 42.94%  |
| Unknown  | 5         | 3.07%   |
| Modem    | 3         | 1.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 54.1%   |
| Ethernet | 53        | 43.44%  |
| Modem    | 3         | 2.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 67        | 75.28%  |
| 1     | 18        | 20.22%  |
| 5     | 3         | 3.37%   |
| 3     | 1         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 83        | 90.22%  |
| Yes  | 9         | 9.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 53.57%  |
| Broadcom                        | 7         | 12.5%   |
| Apple                           | 5         | 8.93%   |
| Dell                            | 4         | 7.14%   |
| Realtek Semiconductor           | 3         | 5.36%   |
| Qualcomm Atheros Communications | 2         | 3.57%   |
| Foxconn / Hon Hai               | 2         | 3.57%   |
| Skylight Digital                | 1         | 1.79%   |
| ASUSTek Computer                | 1         | 1.79%   |
| Alps Electric                   | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 17        | 30.36%  |
| Intel AX201 Bluetooth                                                               | 5         | 8.93%   |
| Apple Bluetooth Host Controller                                                     | 5         | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 5.36%   |
| Intel AX200 Bluetooth                                                               | 3         | 5.36%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 5.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 3.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 3.57%   |
| Skylight Digital Realtek Bluetooth Adapter                                          | 1         | 1.79%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.79%   |
| Realtek Bluetooth Adapter                                                           | 1         | 1.79%   |
| Realtek Bluetooth 4.0 Adapter                                                       | 1         | 1.79%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                                              | 1         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.79%   |
| Intel Wireless Bluetooth                                                            | 1         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.79%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 1.79%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 1.79%   |
| Broadcom Bluetooth                                                                  | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.79%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.79%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 1.79%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 75        | 75.76%  |
| AMD                 | 12        | 12.12%  |
| Nvidia              | 6         | 6.06%   |
| SteelSeries ApS     | 3         | 3.03%   |
| JMTek               | 1         | 1.01%   |
| GN Netcom           | 1         | 1.01%   |
| C-Media Electronics | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 8.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 8.77%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 7.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 6.14%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 6.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 3.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 3.51%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 3         | 2.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 2.63%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.63%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.75%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.88%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.88%   |
| JMTek audio controller                                                                            | 1         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.88%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.88%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.88%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                            | 1         | 0.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.88%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.88%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.88%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.88%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 30.11%  |
| SK hynix            | 20        | 21.51%  |
| Micron Technology   | 12        | 12.9%   |
| Unknown             | 9         | 9.68%   |
| Kingston            | 5         | 5.38%   |
| Crucial             | 4         | 4.3%    |
| Unknown (ABCD)      | 3         | 3.23%   |
| Transcend           | 3         | 3.23%   |
| Elpida              | 3         | 3.23%   |
| A-DATA Technology   | 2         | 2.15%   |
| GSkill              | 1         | 1.08%   |
| Corsair             | 1         | 1.08%   |
| A Force             | 1         | 1.08%   |
| Unknown             | 1         | 1.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 4.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 3.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 3.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 3.88%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 3         | 2.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.91%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 1.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 1.94%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 1.94%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.94%   |
| Elpida RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s             | 2         | 1.94%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.97%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                        | 1         | 0.97%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.97%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.97%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s            | 1         | 0.97%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.97%   |
| SK hynix RAM LX8GDDR3LS1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.97%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.97%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.97%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 0.97%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK hynix RAM GKE800SO102408-2400 8GB SODIMM DDR4 2400MT/s        | 1         | 0.97%   |
| Samsung RAM Module 4GB SODIMM DDR4 3200MT/s                      | 1         | 0.97%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.97%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s                 | 1         | 0.97%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s           | 1         | 0.97%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.97%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.97%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 50.63%  |
| DDR4    | 22        | 27.85%  |
| DDR2    | 8         | 10.13%  |
| LPDDR4  | 4         | 5.06%   |
| LPDDR3  | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| DDR     | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 89.74%  |
| Row Of Chips | 4         | 5.13%   |
| Chip         | 3         | 3.85%   |
| Unknown      | 1         | 1.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 37        | 43.02%  |
| 8192  | 28        | 32.56%  |
| 2048  | 16        | 18.6%   |
| 16384 | 3         | 3.49%   |
| 32768 | 2         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 24        | 27.27%  |
| 2667  | 9         | 10.23%  |
| 2133  | 8         | 9.09%   |
| 1334  | 7         | 7.95%   |
| 1333  | 7         | 7.95%   |
| 3200  | 6         | 6.82%   |
| 2400  | 6         | 6.82%   |
| 1867  | 5         | 5.68%   |
| 667   | 5         | 5.68%   |
| 1067  | 4         | 4.55%   |
| 800   | 2         | 2.27%   |
| 533   | 2         | 2.27%   |
| 4267  | 1         | 1.14%   |
| 1066  | 1         | 1.14%   |
| 333   | 1         | 1.14%   |

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
| Chicony Electronics                    | 16        | 26.67%  |
| Realtek Semiconductor                  | 7         | 11.67%  |
| Bison Electronics                      | 5         | 8.33%   |
| Microdia                               | 4         | 6.67%   |
| Z-Star Microelectronics                | 3         | 5%      |
| Suyin                                  | 3         | 5%      |
| Lite-On Technology                     | 3         | 5%      |
| IMC Networks                           | 3         | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5%      |
| Syntek                                 | 2         | 3.33%   |
| Sunplus Innovation Technology          | 2         | 3.33%   |
| Silicon Motion                         | 2         | 3.33%   |
| Luxvisions Innotech Limited            | 2         | 3.33%   |
| Logitech                               | 1         | 1.67%   |
| Lenovo                                 | 1         | 1.67%   |
| Creative Technology                    | 1         | 1.67%   |
| Apple                                  | 1         | 1.67%   |
| Alcor Micro                            | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 4         | 6.56%   |
| Chicony Integrated Camera                                                | 4         | 6.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 3         | 4.92%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 4.92%   |
| Realtek USB 2.0 Webcam                                                   | 2         | 3.28%   |
| Microdia USB 2.0 Camera                                                  | 2         | 3.28%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 3.28%   |
| Z-Star WebCam SC-03FFL11739P                                             | 1         | 1.64%   |
| Z-Star Webcam                                                            | 1         | 1.64%   |
| Z-Star Namuga 1.3M Webcam                                                | 1         | 1.64%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera                            | 1         | 1.64%   |
| Syntek Integrated Camera                                                 | 1         | 1.64%   |
| Suyin Laptop_Integrated_Webcam_3M                                        | 1         | 1.64%   |
| Suyin Acer Crystal Eye webcam                                            | 1         | 1.64%   |
| Suyin 1.3M HD Webcam                                                     | 1         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 1.64%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                                    | 1         | 1.64%   |
| Silicon Motion WebCam SC-13HDL11939N                                     | 1         | 1.64%   |
| Silicon Motion 300k Pixel Camera                                         | 1         | 1.64%   |
| Realtek USB 2.0 PC Camera                                                | 1         | 1.64%   |
| Microdia Webcam Vitade AF                                                | 1         | 1.64%   |
| Microdia Integrated Webcam                                               | 1         | 1.64%   |
| Luxvisions Innotech Limited Integrated Camera                            | 1         | 1.64%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 1         | 1.64%   |
| Logitech Webcam C930e                                                    | 1         | 1.64%   |
| Logitech B525 HD Webcam                                                  | 1         | 1.64%   |
| Lite-On Integrated Camera                                                | 1         | 1.64%   |
| Lite-On HP Wide Vision HD Camera                                         | 1         | 1.64%   |
| Lite-On HP HD Camera                                                     | 1         | 1.64%   |
| Lenovo Integrated Webcam                                                 | 1         | 1.64%   |
| IMC Networks Integrated Webcam                                           | 1         | 1.64%   |
| Creative Webcam Live! Motion                                             | 1         | 1.64%   |
| Chicony Webcam                                                           | 1         | 1.64%   |
| Chicony USB Video Device                                                 | 1         | 1.64%   |
| Chicony USB 2.0 Camera                                                   | 1         | 1.64%   |
| Chicony Thinkpad T430 camera                                             | 1         | 1.64%   |
| Chicony Ltd., Chicony USB 2.0 Camera                                     | 1         | 1.64%   |
| Chicony Integrated Camera [ThinkPad]                                     | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera           | 1         | 1.64%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 31.25%  |
| Upek                       | 3         | 18.75%  |
| Shenzhen Goodix Technology | 3         | 18.75%  |
| Synaptics                  | 2         | 12.5%   |
| Elan Microelectronics      | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 18.75%  |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 18.75%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 12.5%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 6.25%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 6.25%   |
| Synaptics UWP WBDI                                                           | 1         | 6.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 6.25%   |
| Elan Fingerprint Sensor                                                      | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| AuthenTec AES1660                                                            | 1         | 6.25%   |

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
| 2     | 32        | 33.68%  |
| 1     | 28        | 29.47%  |
| 0     | 16        | 16.84%  |
| 3     | 11        | 11.58%  |
| 4     | 5         | 5.26%   |
| 5     | 3         | 3.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 63        | 43.45%  |
| Bluetooth                | 25        | 17.24%  |
| Net/wireless             | 15        | 10.34%  |
| Fingerprint reader       | 14        | 9.66%   |
| Firewire controller      | 11        | 7.59%   |
| Card reader              | 11        | 7.59%   |
| Storage                  | 2         | 1.38%   |
| Network                  | 2         | 1.38%   |
| Sound                    | 1         | 0.69%   |
| Graphics card            | 1         | 0.69%   |

