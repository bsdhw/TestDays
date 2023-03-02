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

Total: 186

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Deciso        | NetBoard-A10                | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| Deciso        | NetBoard-A10                | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
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
| helloSystem 0.7.0    | 10        | 8.93%   |
| FreeBSD 13.0         | 8         | 7.14%   |
| FreeBSD 14.0-CURRENT | 6         | 5.36%   |
| FreeBSD 13.1         | 5         | 4.46%   |
| helloSystem 0.5.0    | 4         | 3.57%   |
| helloSystem 0.4.0    | 4         | 3.57%   |
| GhostBSD 20.04.02    | 4         | 3.57%   |
| FreeBSD 12.2         | 4         | 3.57%   |
| OpenBSD 7.2          | 3         | 2.68%   |
| OpenBSD 7.1          | 3         | 2.68%   |
| OpenBSD 6.8          | 3         | 2.68%   |
| NomadBSD 1.4-RC1     | 3         | 2.68%   |
| NomadBSD 1.3.2       | 3         | 2.68%   |
| helloSystem 0.6.0    | 3         | 2.68%   |
| OPNsense 22.4.3      | 2         | 1.79%   |
| helloSystem 0.8.0    | 2         | 1.79%   |
| FreeBSD 13.0-p5      | 2         | 1.79%   |
| FreeBSD 13.0-CURRENT | 2         | 1.79%   |
| FreeBSD 12.2-p6      | 2         | 1.79%   |
| FreeBSD 12.2-p4      | 2         | 1.79%   |
| FreeBSD 12.2-p3      | 2         | 1.79%   |
| FreeBSD 12.2-p2      | 2         | 1.79%   |
| FreeBSD 12.1-p9      | 2         | 1.79%   |
| OPNsense 22.7.4      | 1         | 0.89%   |
| OPNsense 22.1.6      | 1         | 0.89%   |
| OPNsense 22.1.10     | 1         | 0.89%   |
| OPNsense 21.1.4      | 1         | 0.89%   |
| OPNsense 21.1.3      | 1         | 0.89%   |
| OPNsense 21.1.1      | 1         | 0.89%   |
| OpenBSD 7.0          | 1         | 0.89%   |
| OpenBSD 6.9          | 1         | 0.89%   |
| NomadBSD 20221130    | 1         | 0.89%   |
| NomadBSD 1.4         | 1         | 0.89%   |
| helloSystem          | 1         | 0.89%   |
| GhostBSD 23.02.02    | 1         | 0.89%   |
| GhostBSD 22.08.06    | 1         | 0.89%   |
| GhostBSD 22.06.26    | 1         | 0.89%   |
| GhostBSD 22.06.07    | 1         | 0.89%   |
| GhostBSD 22.01.12    | 1         | 0.89%   |
| GhostBSD 21.08.27    | 1         | 0.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 30        | 34.88%  |
| helloSystem | 21        | 24.42%  |
| OpenBSD     | 11        | 12.79%  |
| NomadBSD    | 8         | 9.3%    |
| GhostBSD    | 8         | 9.3%    |
| OPNsense    | 6         | 6.98%   |
| FuryBSD     | 1         | 1.16%   |
| DragonFly   | 1         | 1.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 79        | 97.53%  |
| i386  | 2         | 2.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 25        | 29.07%  |
| KDE5          | 11        | 12.79%  |
| XFCE          | 10        | 11.63%  |
| MATE          | 10        | 11.63%  |
| Console       | 10        | 11.63%  |
| Openbox       | 7         | 8.14%   |
| fvwm          | 5         | 5.81%   |
| i3            | 3         | 3.49%   |
| GNOME         | 2         | 2.33%   |
| Cinnamon      | 2         | 2.33%   |
| Enlightenment | 1         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 69        | 83.13%  |
| Console | 12        | 14.46%  |
| Wayland | 2         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 35        | 41.18%  |
| Console | 24        | 28.24%  |
| SDDM    | 15        | 17.65%  |
| LightDM | 8         | 9.41%   |
| XDM     | 3         | 3.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 28        | 30.77%  |
| Unknown         | 24        | 26.37%  |
| C               | 23        | 25.27%  |
| en_GB           | 12        | 13.19%  |
| ru_RU           | 1         | 1.1%    |
| it_CH           | 1         | 1.1%    |
| en_GB.US-ASCII  | 1         | 1.1%    |
| en_GB.ISO8859-1 | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 64        | 78.05%  |
| BIOS | 18        | 21.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 43        | 50.59%  |
| Ufs     | 24        | 28.24%  |
| Ffs     | 11        | 12.94%  |
| Cd9660  | 6         | 7.06%   |
| Hammer2 | 1         | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 72        | 87.8%   |
| MBR     | 8         | 9.76%   |
| BSD     | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 21        | 25.93%  |
| Hewlett-Packard     | 12        | 14.81%  |
| Dell                | 12        | 14.81%  |
| Apple               | 5         | 6.17%   |
| Toshiba             | 4         | 4.94%   |
| Samsung Electronics | 4         | 4.94%   |
| Deciso              | 3         | 3.7%    |
| ASUSTek Computer    | 3         | 3.7%    |
| HUAWEI              | 2         | 2.47%   |
| TUXEDO              | 1         | 1.23%   |
| System76            | 1         | 1.23%   |
| Star Labs           | 1         | 1.23%   |
| Sony                | 1         | 1.23%   |
| Pegatron            | 1         | 1.23%   |
| Panasonic           | 1         | 1.23%   |
| Packard Bell        | 1         | 1.23%   |
| MSI                 | 1         | 1.23%   |
| Jumper              | 1         | 1.23%   |
| Google              | 1         | 1.23%   |
| GEO                 | 1         | 1.23%   |
| Fujitsu Siemens     | 1         | 1.23%   |
| Fujitsu             | 1         | 1.23%   |
| Alienware           | 1         | 1.23%   |
| Acer                | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HP EliteBook 8570p                       | 3         | 3.7%    |
| Dell XPS 13 9343                         | 2         | 2.47%   |
| Dell Inspiron 3793                       | 2         | 2.47%   |
| Deciso NetBoard-A10                      | 2         | 2.47%   |
| ASUS ZenBook S UX391UA                   | 2         | 2.47%   |
| TUXEDO Aura 15 Gen1                      | 1         | 1.23%   |
| Toshiba TECRA M11                        | 1         | 1.23%   |
| Toshiba Satellite Pro U400               | 1         | 1.23%   |
| Toshiba Satellite L50-C                  | 1         | 1.23%   |
| Toshiba Satellite C660                   | 1         | 1.23%   |
| System76 Gazelle                         | 1         | 1.23%   |
| Star Labs Lite                           | 1         | 1.23%   |
| Sony VPCF12C5E                           | 1         | 1.23%   |
| Samsung NC10                             | 1         | 1.23%   |
| Samsung N140                             | 1         | 1.23%   |
| Samsung 550P5C/550P7C                    | 1         | 1.23%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.23%   |
| Pegatron T12Ah                           | 1         | 1.23%   |
| Panasonic CF-C1BT02EGE                   | 1         | 1.23%   |
| Packard Bell EasyNote_MX52-B-071         | 1         | 1.23%   |
| MSI Modern 14 B11MOL                     | 1         | 1.23%   |
| Lenovo Z50-70 20354                      | 1         | 1.23%   |
| Lenovo ThinkPad Yoga 11e 20D9000QUK      | 1         | 1.23%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DS00    | 1         | 1.23%   |
| Lenovo ThinkPad X240 20AMS1YG01          | 1         | 1.23%   |
| Lenovo ThinkPad X230 2325J67             | 1         | 1.23%   |
| Lenovo ThinkPad X220 4291QT1             | 1         | 1.23%   |
| Lenovo ThinkPad X220 4291H77             | 1         | 1.23%   |
| Lenovo ThinkPad X220 42902WU             | 1         | 1.23%   |
| Lenovo ThinkPad X201 3680MG1             | 1         | 1.23%   |
| Lenovo ThinkPad X200 7459ZLW             | 1         | 1.23%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK | 1         | 1.23%   |
| Lenovo ThinkPad W520 42844DG             | 1         | 1.23%   |
| Lenovo ThinkPad T560 20FJS0CE00          | 1         | 1.23%   |
| Lenovo ThinkPad T470 20HD000MUK          | 1         | 1.23%   |
| Lenovo ThinkPad T460 20FMS3320G          | 1         | 1.23%   |
| Lenovo ThinkPad T430 2347C32             | 1         | 1.23%   |
| Lenovo ThinkPad T420 4236NHG             | 1         | 1.23%   |
| Lenovo ThinkPad T410 2522E38             | 1         | 1.23%   |
| Lenovo ThinkPad R61 8935WCS              | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 19        | 23.46%  |
| Dell Latitude          | 5         | 6.17%   |
| Toshiba Satellite      | 3         | 3.7%    |
| HP EliteBook           | 3         | 3.7%    |
| Dell Inspiron          | 3         | 3.7%    |
| Apple MacBookPro5      | 3         | 3.7%    |
| HP Pavilion            | 2         | 2.47%   |
| Dell XPS               | 2         | 2.47%   |
| Deciso NetBoard-A10    | 2         | 2.47%   |
| ASUS ZenBook           | 2         | 2.47%   |
| TUXEDO Aura            | 1         | 1.23%   |
| Toshiba TECRA          | 1         | 1.23%   |
| System76 Gazelle       | 1         | 1.23%   |
| Star Labs Lite         | 1         | 1.23%   |
| Sony VPCF12C5E         | 1         | 1.23%   |
| Samsung NC10           | 1         | 1.23%   |
| Samsung N140           | 1         | 1.23%   |
| Samsung 550P5C         | 1         | 1.23%   |
| Samsung 305E4A         | 1         | 1.23%   |
| Pegatron T12Ah         | 1         | 1.23%   |
| Panasonic CF-C1BT02EGE | 1         | 1.23%   |
| Packard Bell EasyNote  | 1         | 1.23%   |
| MSI Modern             | 1         | 1.23%   |
| Lenovo Z50-70          | 1         | 1.23%   |
| Lenovo IdeaPad         | 1         | 1.23%   |
| Jumper EZbook          | 1         | 1.23%   |
| HUAWEI MACHD-WXX9      | 1         | 1.23%   |
| HUAWEI BOM-WXX9        | 1         | 1.23%   |
| HP ZBook               | 1         | 1.23%   |
| HP ProBook             | 1         | 1.23%   |
| HP Laptop              | 1         | 1.23%   |
| HP ENVY                | 1         | 1.23%   |
| HP Compaq              | 1         | 1.23%   |
| HP 250                 | 1         | 1.23%   |
| HP 15                  | 1         | 1.23%   |
| Google Lulu            | 1         | 1.23%   |
| GEO GeoBook3           | 1         | 1.23%   |
| Fujitsu Siemens AMILO  | 1         | 1.23%   |
| Fujitsu LIFEBOOK       | 1         | 1.23%   |
| Dell Vostro            | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 8         | 9.88%   |
| 2016 | 8         | 9.88%   |
| 2011 | 8         | 9.88%   |
| 2010 | 7         | 8.64%   |
| 2019 | 6         | 7.41%   |
| 2013 | 6         | 7.41%   |
| 2012 | 6         | 7.41%   |
| 2009 | 6         | 7.41%   |
| 2022 | 5         | 6.17%   |
| 2021 | 5         | 6.17%   |
| 2018 | 5         | 6.17%   |
| 2015 | 3         | 3.7%    |
| 2008 | 3         | 3.7%    |
| 2014 | 2         | 2.47%   |
| 2007 | 2         | 2.47%   |
| 2017 | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 97.53%  |
| Yes  | 2         | 2.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 38        | 46.34%  |
| 4.01-8.0   | 20        | 24.39%  |
| 16.01-24.0 | 17        | 20.73%  |
| 32.01-64.0 | 3         | 3.66%   |
| 2.01-3.0   | 3         | 3.66%   |
| 3.01-4.0   | 1         | 1.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 52        | 61.18%  |
| 0.51-1.0  | 23        | 27.06%  |
| 1.01-2.0  | 4         | 4.71%   |
| 2.01-3.0  | 3         | 3.53%   |
| 4.01-8.0  | 1         | 1.18%   |
| 3.01-4.0  | 1         | 1.18%   |
| 8.01-16.0 | 1         | 1.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 64        | 71.91%  |
| 2      | 20        | 22.47%  |
| 0      | 3         | 3.37%   |
| 3      | 2         | 2.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 56        | 65.88%  |
| Yes       | 29        | 34.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 80.25%  |
| No        | 16        | 19.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 96.3%   |
| No        | 3         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 60.71%  |
| No        | 33        | 39.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 81        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 10        | 10.53%  |
| Brighton            | 7         | 7.37%   |
| Glasgow             | 5         | 5.26%   |
| Leatherhead         | 3         | 3.16%   |
| Worthing            | 2         | 2.11%   |
| Swindon             | 2         | 2.11%   |
| Greenwich           | 2         | 2.11%   |
| Gloucester          | 2         | 2.11%   |
| City of London      | 2         | 2.11%   |
| Wraysbury           | 1         | 1.05%   |
| Woking              | 1         | 1.05%   |
| Watford             | 1         | 1.05%   |
| Walsall             | 1         | 1.05%   |
| Tottenham           | 1         | 1.05%   |
| Sutton              | 1         | 1.05%   |
| St Austell          | 1         | 1.05%   |
| Southampton         | 1         | 1.05%   |
| Ruislip             | 1         | 1.05%   |
| Rugby               | 1         | 1.05%   |
| Reigate             | 1         | 1.05%   |
| Reading             | 1         | 1.05%   |
| Plymouth            | 1         | 1.05%   |
| Perth               | 1         | 1.05%   |
| Oxford              | 1         | 1.05%   |
| Oxenhope            | 1         | 1.05%   |
| Okehampton          | 1         | 1.05%   |
| Notting Hill Gate   | 1         | 1.05%   |
| North Tawton        | 1         | 1.05%   |
| Newcastle upon Tyne | 1         | 1.05%   |
| Morden              | 1         | 1.05%   |
| Milton Keynes       | 1         | 1.05%   |
| Middlesbrough       | 1         | 1.05%   |
| Manchester          | 1         | 1.05%   |
| Malton              | 1         | 1.05%   |
| Lytham St Annes     | 1         | 1.05%   |
| Longfield           | 1         | 1.05%   |
| Lincoln             | 1         | 1.05%   |
| Leicester           | 1         | 1.05%   |
| Kensington          | 1         | 1.05%   |
| Islington           | 1         | 1.05%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 43     | 23.76%  |
| WDC                 | 13        | 18     | 12.87%  |
| Toshiba             | 8         | 22     | 7.92%   |
| Seagate             | 7         | 7      | 6.93%   |
| HGST                | 6         | 26     | 5.94%   |
| Intel               | 4         | 4      | 3.96%   |
| Hitachi             | 4         | 4      | 3.96%   |
| Transcend           | 3         | 4      | 2.97%   |
| SanDisk             | 3         | 3      | 2.97%   |
| NVMe                | 3         | 3      | 2.97%   |
| Kingston            | 3         | 3      | 2.97%   |
| XUM                 | 2         | 2      | 1.98%   |
| SK hynix            | 2         | 2      | 1.98%   |
| Crucial             | 2         | 2      | 1.98%   |
| Apple               | 2         | 3      | 1.98%   |
| Star Drive          | 1         | 1      | 0.99%   |
| Solid State Storage | 1         | 1      | 0.99%   |
| SATA3 60            | 1         | 1      | 0.99%   |
| PNY                 | 1         | 1      | 0.99%   |
| Phison              | 1         | 1      | 0.99%   |
| OWC                 | 1         | 1      | 0.99%   |
| Micron Technology   | 1         | 1      | 0.99%   |
| MicroDream          | 1         | 1      | 0.99%   |
| LITEON              | 1         | 1      | 0.99%   |
| Lexar               | 1         | 1      | 0.99%   |
| Intenso             | 1         | 1      | 0.99%   |
| Fujitsu             | 1         | 6      | 0.99%   |
| Corsair             | 1         | 1      | 0.99%   |
| Apacer              | 1         | 1      | 0.99%   |
| A-DATA Technology   | 1         | 1      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 4         | 3.88%   |
| HGST HTS725050A7E630 500GB                         | 4         | 3.88%   |
| Samsung HM251JX 250GB                              | 3         | 2.91%   |
| XUM HX256GSSDSATA3 256GB                           | 2         | 1.94%   |
| WDC WDS250G2B0B-00YS70 250GB                       | 2         | 1.94%   |
| WDC WDS240G2G0A-00JH30 240GB                       | 2         | 1.94%   |
| WDC WD1600BEVT-80A23T0 160GB                       | 2         | 1.94%   |
| WDC WD1600BEVT-22ZCT0 160GB                        | 2         | 1.94%   |
| Transcend TS256GMTE652T2 256GB                     | 2         | 1.94%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 1.94%   |
| Samsung SSD PM851 M.2 2280 256GB                   | 2         | 1.94%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 1.94%   |
| Samsung MZVLW512HMJP-00000 512GB                   | 2         | 1.94%   |
| WDC WDS250G2B0A 250GB                              | 1         | 0.97%   |
| WDC WDS120G2G0A-00JH30 120GB                       | 1         | 0.97%   |
| WDC WD7500BPKX-00HPJT0 752GB                       | 1         | 0.97%   |
| WDC WD2500BEVT-80A23T0 250GB                       | 1         | 0.97%   |
| WDC WD1600BEVS-08VAT2 160GB                        | 1         | 0.97%   |
| Transcend TS128GMTE110S 128GB                      | 1         | 0.97%   |
| Toshiba THNSNJ128GMCU 128GB                        | 1         | 0.97%   |
| Toshiba THNSF5256GPUK 256GB                        | 1         | 0.97%   |
| Toshiba MK5061GSY 500GB                            | 1         | 0.97%   |
| Toshiba KBG30ZMV256G 256GB                         | 1         | 0.97%   |
| Star Drive SATA SSD 960GB                          | 1         | 0.97%   |
| Solid State Storage CL1-3D128-Q11 NVMe SSSTC 128GB | 1         | 0.97%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB               | 1         | 0.97%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.97%   |
| Seagate ST9320423AS 320GB                          | 1         | 0.97%   |
| Seagate ST9160821AS 160GB                          | 1         | 0.97%   |
| Seagate ST9160310AS 160GB                          | 1         | 0.97%   |
| Seagate ST2000LM015-2E8174 2TB                     | 1         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 1         | 0.97%   |
| SATA3 60 GB SSD 64GB                               | 1         | 0.97%   |
| SanDisk SD6SB1M128G1022I 128GB                     | 1         | 0.97%   |
| SanDisk Extreme 55AE 500GB                         | 1         | 0.97%   |
| SanDisk Cruzer Fit 32GB                            | 1         | 0.97%   |
| Samsung SSD PM871 2.5 7mm 128GB                    | 1         | 0.97%   |
| Samsung SSD PM810 2.5-inch 7mm 256GB               | 1         | 0.97%   |
| Samsung SSD 980 PRO 500GB                          | 1         | 0.97%   |
| Samsung SSD 980 1TB                                | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 20%     |
| Seagate             | 7         | 7      | 20%     |
| HGST                | 6         | 26     | 17.14%  |
| Toshiba             | 5         | 17     | 14.29%  |
| Hitachi             | 4         | 4      | 11.43%  |
| Samsung Electronics | 3         | 3      | 8.57%   |
| NVMe                | 2         | 2      | 5.71%   |
| Fujitsu             | 1         | 6      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 32     | 29.41%  |
| WDC                 | 6         | 10     | 11.76%  |
| SanDisk             | 3         | 3      | 5.88%   |
| Kingston            | 3         | 3      | 5.88%   |
| Intel               | 3         | 3      | 5.88%   |
| XUM                 | 2         | 2      | 3.92%   |
| Crucial             | 2         | 2      | 3.92%   |
| Apple               | 2         | 3      | 3.92%   |
| Toshiba             | 1         | 1      | 1.96%   |
| Star Drive          | 1         | 1      | 1.96%   |
| SATA3 60            | 1         | 1      | 1.96%   |
| PNY                 | 1         | 1      | 1.96%   |
| Phison              | 1         | 1      | 1.96%   |
| OWC                 | 1         | 1      | 1.96%   |
| NVMe                | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| MicroDream          | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| Lexar               | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| Corsair             | 1         | 1      | 1.96%   |
| Apacer              | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 46        | 73     | 51.11%  |
| HDD  | 29        | 73     | 32.22%  |
| NVMe | 15        | 20     | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 146    | 81.71%  |
| NVMe | 15        | 20     | 18.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 118    | 80.56%  |
| 0.51-1.0   | 12        | 25     | 16.67%  |
| 1.01-2.0   | 2         | 3      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 36        | 39.13%  |
| 1-20       | 21        | 22.83%  |
| 251-500    | 17        | 18.48%  |
| 501-1000   | 9         | 9.78%   |
| 21-50      | 4         | 4.35%   |
| Unknown    | 3         | 3.26%   |
| 51-100     | 2         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 66        | 73.33%  |
| 21-50   | 14        | 15.56%  |
| 51-100  | 5         | 5.56%   |
| Unknown | 3         | 3.33%   |
| 101-250 | 2         | 2.22%   |

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
| Works    | 69        | 124    | 78.41%  |
| Malfunc  | 14        | 35     | 15.91%  |
| Detected | 5         | 7      | 5.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 62        | 72.09%  |
| Samsung Electronics            | 8         | 9.3%    |
| Transcend                      | 3         | 3.49%   |
| Nvidia                         | 3         | 3.49%   |
| AMD                            | 3         | 3.49%   |
| Toshiba                        | 2         | 2.33%   |
| SK hynix                       | 2         | 2.33%   |
| Solid State Storage Technology | 1         | 1.16%   |
| Phison Electronics             | 1         | 1.16%   |
| Kingston Technology Company    | 1         | 1.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 9.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 7.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 7.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 5.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 5.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 5.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 4.26%   |
| Unknown                                                                          | 4         | 4.26%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 3.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 3.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.13%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 2.13%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 2.13%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 1.06%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 1.06%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 1.06%   |
| SK hynix BC511                                                                   | 1         | 1.06%   |
| Samsung SM951 AHCI                                                               | 1         | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.06%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 1.06%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.06%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 1.06%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.06%   |
| Intel SSD 660P Series                                                            | 1         | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.06%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 1.06%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 1.06%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.06%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.06%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 59        | 65.56%  |
| NVMe | 17        | 18.89%  |
| RAID | 7         | 7.78%   |
| IDE  | 7         | 7.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 88.89%  |
| AMD    | 8         | 9.88%   |
| 11th   | 1         | 1.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel CPU Version                        | 3         | 3.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 3.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 3.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 3.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 3.7%    |
| AMD Ryzen Embedded V1500B                | 3         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 2.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 2         | 2.47%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 2         | 2.47%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 2.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 2         | 2.47%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 2         | 2.47%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 2         | 2.47%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 1.23%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 1.23%   |
| Intel Pentium CPU 967 @ 1.30GHz          | 1         | 1.23%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 1         | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 1         | 1.23%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 1.23%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz       | 1         | 1.23%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz       | 1         | 1.23%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 1.23%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 1.23%   |
| Intel Core i7-3612QM CPU @ 2.10GHz       | 1         | 1.23%   |
| Intel Core i7-3540M CPU @ 3.00GHz        | 1         | 1.23%   |
| Intel Core i7-2820QM CPU @ 2.30GHz       | 1         | 1.23%   |
| Intel Core i7-2630QM CPU @ 2.00GHz       | 1         | 1.23%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 1         | 1.23%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz        | 1         | 1.23%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 1         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 1         | 1.23%   |
| Intel Core i5-4278U CPU @ 2.60GHz        | 1         | 1.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 1.23%   |
| Intel Core i5-2430M CPU @ 2.40GHz        | 1         | 1.23%   |
| Intel Core i5-2410M CPU @ 2.30GH         | 1         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 1         | 1.23%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 1.23%   |
| Intel Core i5 CPU M 560 @ 2.67GH         | 1         | 1.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 24        | 29.63%  |
| Intel Core i5        | 24        | 29.63%  |
| Intel Core 2 Duo     | 8         | 9.88%   |
| Other                | 6         | 7.41%   |
| Intel Celeron        | 5         | 6.17%   |
| AMD Ryzen Embedded   | 3         | 3.7%    |
| Intel Pentium        | 2         | 2.47%   |
| AMD A6               | 2         | 2.47%   |
| Intel Pentium Silver | 1         | 1.23%   |
| Intel Core i3        | 1         | 1.23%   |
| Intel Core 2         | 1         | 1.23%   |
| Intel Atom           | 1         | 1.23%   |
| AMD Ryzen 7          | 1         | 1.23%   |
| AMD Ryzen 5          | 1         | 1.23%   |
| AMD Athlon 64 X2     | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 51.85%  |
| 4       | 22        | 27.16%  |
| Unknown | 8         | 9.88%   |
| 8       | 4         | 4.94%   |
| 1       | 3         | 3.7%    |
| 16      | 1         | 1.23%   |
| 12      | 1         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 77        | 95.06%  |
| 2       | 2         | 2.47%   |
| Unknown | 2         | 2.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 53        | 65.43%  |
| 1       | 20        | 24.69%  |
| Unknown | 8         | 9.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| SandyBridge   | 10        | 12.35%  |
| Haswell       | 9         | 11.11%  |
| Penryn        | 8         | 9.88%   |
| IvyBridge     | 8         | 9.88%   |
| Skylake       | 7         | 8.64%   |
| KabyLake      | 7         | 8.64%   |
| Westmere      | 4         | 4.94%   |
| Zen           | 3         | 3.7%    |
| Goldmont plus | 3         | 3.7%    |
| Broadwell     | 3         | 3.7%    |
| Bonnell       | 3         | 3.7%    |
| Unknown       | 3         | 3.7%    |
| Silvermont    | 2         | 2.47%   |
| IceLake       | 2         | 2.47%   |
| Core          | 2         | 2.47%   |
| Zen 2         | 1         | 1.23%   |
| TigerLake     | 1         | 1.23%   |
| Nehalem       | 1         | 1.23%   |
| K8 Hammer     | 1         | 1.23%   |
| K10 Llano     | 1         | 1.23%   |
| Goldmont      | 1         | 1.23%   |
| Excavator     | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 73.86%  |
| Nvidia | 14        | 15.91%  |
| AMD    | 9         | 10.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 10.53%  |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 7.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 5.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 5.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 4.21%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 3.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 3.16%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 3.16%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 2.11%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 2.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 2.11%   |
| Intel UHD Graphics 620                                                                   | 2         | 2.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.11%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 2.11%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 2.11%   |
| Intel HD Graphics 5500                                                                   | 2         | 2.11%   |
| Intel HD Graphics 530                                                                    | 2         | 2.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2.11%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 1.05%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 1.05%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 1.05%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 1.05%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 1.05%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 1.05%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 1.05%   |
| Nvidia GF114M [GeForce GTX 580M]                                                         | 1         | 1.05%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 1.05%   |
| Intel HD Graphics 620                                                                    | 1         | 1.05%   |
| Intel HD Graphics 500                                                                    | 1         | 1.05%   |
| Intel HD Graphics                                                                        | 1         | 1.05%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.05%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.05%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 54.88%  |
| 2 x Intel      | 10        | 12.2%   |
| Intel + Nvidia | 9         | 10.98%  |
| 1 x AMD        | 8         | 9.76%   |
| 1 x Nvidia     | 4         | 4.88%   |
| Other          | 3         | 3.66%   |
| 2 x Nvidia     | 2         | 2.44%   |
| Intel + AMD    | 1         | 1.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 72        | 87.8%   |
| Unknown     | 6         | 7.32%   |
| Proprietary | 4         | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 89.16%  |
| 1.01-2.0   | 3         | 3.61%   |
| 0.51-1.0   | 3         | 3.61%   |
| 0.01-0.5   | 3         | 3.61%   |

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
| 1     | 57        | 67.86%  |
| 0     | 22        | 26.19%  |
| 2     | 5         | 5.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 58        | 47.54%  |
| Realtek Semiconductor             | 23        | 18.85%  |
| Qualcomm Atheros                  | 12        | 9.84%   |
| Broadcom                          | 8         | 6.56%   |
| Marvell Technology Group          | 4         | 3.28%   |
| Nvidia                            | 3         | 2.46%   |
| Hewlett-Packard                   | 3         | 2.46%   |
| AMD                               | 3         | 2.46%   |
| Sierra Wireless                   | 2         | 1.64%   |
| Ericsson Business Mobile Networks | 2         | 1.64%   |
| D-Link System                     | 2         | 1.64%   |
| TP-Link                           | 1         | 0.82%   |
| Edimax Technology                 | 1         | 0.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 13        | 8.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 13        | 8.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 11        | 6.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 4.32%   |
| Intel Wireless 7260                                                         | 7         | 4.32%   |
| Intel Wireless 8260                                                         | 6         | 3.7%    |
| Intel Ethernet Connection I219-LM                                           | 4         | 2.47%   |
| Intel Ethernet Connection I218-LM                                           | 4         | 2.47%   |
| Intel Centrino Ultimate-N 6300                                              | 4         | 2.47%   |
| Intel Centrino Advanced-N 6200                                              | 4         | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 3         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 3         | 1.85%   |
| Nvidia MCP79 Ethernet                                                       | 3         | 1.85%   |
| Intel Wireless 8265 / 8275                                                  | 3         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                         | 3         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 1.85%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                     | 3         | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 1.85%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                   | 3         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 2         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 1.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 2         | 1.23%   |
| Intel Wireless 3165                                                         | 2         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                         | 2         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 1.23%   |
| Intel I211 Gigabit Network Connection                                       | 2         | 1.23%   |
| Intel I210 Gigabit Network Connection                                       | 2         | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 2         | 1.23%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.23%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W]  | 2         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 1         | 0.62%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 0.62%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.62%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 0.62%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 63.86%  |
| Qualcomm Atheros      | 11        | 13.25%  |
| Realtek Semiconductor | 8         | 9.64%   |
| Broadcom              | 6         | 7.23%   |
| D-Link System         | 2         | 2.41%   |
| TP-Link               | 1         | 1.2%    |
| Sierra Wireless       | 1         | 1.2%    |
| Edimax Technology     | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 11        | 12.94%  |
| Intel Wireless 7260                                                        | 7         | 8.24%   |
| Intel Wireless 8260                                                        | 6         | 7.06%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 4.71%   |
| Intel Centrino Advanced-N 6200                                             | 4         | 4.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 3         | 3.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)    | 3         | 3.53%   |
| Intel Wireless 8265 / 8275                                                 | 3         | 3.53%   |
| Intel Wi-Fi 6 AX200                                                        | 3         | 3.53%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 3         | 3.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 2.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 2.35%   |
| Intel Wireless 3165                                                        | 2         | 2.35%   |
| Intel Wi-Fi 6 AX201                                                        | 2         | 2.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 2         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 2         | 2.35%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 2         | 2.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 1         | 1.18%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                              | 1         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.18%   |
| Realtek RTL8723DE Wireless Network Adapter                                 | 1         | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 1.18%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                      | 1         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 1         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 1         | 1.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 1.18%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)    | 1         | 1.18%   |
| Intel Wireless 3160                                                        | 1         | 1.18%   |
| Intel WiFi Link 5100                                                       | 1         | 1.18%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                    | 1         | 1.18%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.18%   |
| Intel Centrino Advanced-N 6235                                             | 1         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 1         | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                           | 1         | 1.18%   |
| Edimax Edimax AC600 Wireless LAN USB Adapter                               | 1         | 1.18%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                | 1         | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 1.18%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 1.18%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 34        | 48.57%  |
| Realtek Semiconductor    | 21        | 30%     |
| Marvell Technology Group | 4         | 5.71%   |
| Nvidia                   | 3         | 4.29%   |
| Broadcom                 | 3         | 4.29%   |
| AMD                      | 3         | 4.29%   |
| Qualcomm Atheros         | 2         | 2.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 18.31%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 18.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 9.86%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 5.63%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 5.63%   |
| Nvidia MCP79 Ethernet                                             | 3         | 4.23%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 4.23%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 3         | 4.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 2.82%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.82%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.41%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.41%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.41%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.41%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 52.35%  |
| Ethernet | 65        | 43.62%  |
| Modem    | 3         | 2.01%   |
| Unknown  | 3         | 2.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 53.04%  |
| Ethernet | 51        | 44.35%  |
| Modem    | 3         | 2.61%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 62        | 75.61%  |
| 1     | 16        | 19.51%  |
| 5     | 3         | 3.66%   |
| 3     | 1         | 1.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 89.41%  |
| Yes  | 9         | 10.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 50.98%  |
| Broadcom                        | 7         | 13.73%  |
| Apple                           | 5         | 9.8%    |
| Dell                            | 4         | 7.84%   |
| Realtek Semiconductor           | 2         | 3.92%   |
| Qualcomm Atheros Communications | 2         | 3.92%   |
| Foxconn / Hon Hai               | 2         | 3.92%   |
| Realtek                         | 1         | 1.96%   |
| ASUSTek Computer                | 1         | 1.96%   |
| Alps Electric                   | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 29.41%  |
| Apple Bluetooth Host Controller                                                     | 5         | 9.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 5.88%   |
| Intel AX201 Bluetooth                                                               | 3         | 5.88%   |
| Intel AX200 Bluetooth                                                               | 3         | 5.88%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 5.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 3.92%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 3.92%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.96%   |
| Realtek  Bluetooth 4.0 Adapter                                                      | 1         | 1.96%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.96%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                                             | 1         | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.96%   |
| Intel Intel Wireless Bluetooth                                                      | 1         | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.96%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.96%   |
| Foxconn / Hon Hai Bluetooth USB Module                                              | 1         | 1.96%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                                         | 1         | 1.96%   |
| Broadcom Bluetooth                                                                  | 1         | 1.96%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.96%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 1.96%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 1.96%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 69        | 75%     |
| AMD                 | 11        | 11.96%  |
| Nvidia              | 6         | 6.52%   |
| SteelSeries ApS     | 3         | 3.26%   |
| JMTek               | 1         | 1.09%   |
| GN Netcom           | 1         | 1.09%   |
| C-Media Electronics | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 9.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 8.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 7.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 6.67%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 6.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 3.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 3.81%   |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 3         | 2.86%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 2.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.86%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.9%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.9%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.95%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.95%   |
| JMTek audio controller                                                                            | 1         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.95%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.95%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.95%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                                            | 1         | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.95%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.95%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.95%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 30.59%  |
| SK hynix            | 18        | 21.18%  |
| Micron Technology   | 11        | 12.94%  |
| Unknown             | 9         | 10.59%  |
| Kingston            | 4         | 4.71%   |
| Crucial             | 4         | 4.71%   |
| Transcend           | 3         | 3.53%   |
| Elpida              | 3         | 3.53%   |
| Unknown (ABCD)      | 2         | 2.35%   |
| A-DATA Technology   | 2         | 2.35%   |
| Corsair             | 1         | 1.18%   |
| A Force             | 1         | 1.18%   |
| Unknown             | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 5.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 4.26%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 4.26%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 4.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 3.19%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 3.19%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s | 2         | 2.13%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 2.13%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 2.13%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 2         | 2.13%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 2.13%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 2.13%   |
| Elpida RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s             | 2         | 2.13%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 1.06%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.06%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 1.06%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s            | 1         | 1.06%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 1.06%   |
| SK hynix RAM LX8GDDR3LS1600 8GB SODIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.06%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 1         | 1.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.06%   |
| SK hynix RAM GKE800SO102408-2400 8GB SODIMM DDR4 2400MT/s        | 1         | 1.06%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s           | 1         | 1.06%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 38        | 52.78%  |
| DDR4    | 18        | 25%     |
| DDR2    | 8         | 11.11%  |
| LPDDR4  | 3         | 4.17%   |
| LPDDR3  | 2         | 2.78%   |
| Unknown | 2         | 2.78%   |
| DDR     | 1         | 1.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 90.14%  |
| Row Of Chips | 3         | 4.23%   |
| Chip         | 3         | 4.23%   |
| Unknown      | 1         | 1.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 32        | 41.03%  |
| 8192  | 27        | 34.62%  |
| 2048  | 16        | 20.51%  |
| 16384 | 3         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 22        | 27.5%   |
| 2667  | 9         | 11.25%  |
| 2133  | 7         | 8.75%   |
| 1334  | 7         | 8.75%   |
| 1333  | 7         | 8.75%   |
| 2400  | 5         | 6.25%   |
| 1867  | 5         | 6.25%   |
| 667   | 5         | 6.25%   |
| 1067  | 4         | 5%      |
| 3200  | 2         | 2.5%    |
| 800   | 2         | 2.5%    |
| 533   | 2         | 2.5%    |
| 4267  | 1         | 1.25%   |
| 1066  | 1         | 1.25%   |
| 333   | 1         | 1.25%   |

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
| Chicony Electronics                    | 14        | 25.93%  |
| Realtek Semiconductor                  | 7         | 12.96%  |
| Bison Electronics                      | 5         | 9.26%   |
| Z-Star Microelectronics                | 3         | 5.56%   |
| Suyin                                  | 3         | 5.56%   |
| Lite-On Technology                     | 3         | 5.56%   |
| IMC Networks                           | 3         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 3.7%    |
| Silicon Motion                         | 2         | 3.7%    |
| Microdia                               | 2         | 3.7%    |
| Syntek                                 | 1         | 1.85%   |
| Luxvisions Innotech Limited            | 1         | 1.85%   |
| Logitech                               | 1         | 1.85%   |
| Lenovo                                 | 1         | 1.85%   |
| Creative Technology                    | 1         | 1.85%   |
| Apple                                  | 1         | 1.85%   |
| Alcor Micro                            | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                             | 4         | 7.27%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 3         | 5.45%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 5.45%   |
| Chicony Integrated Camera                                                | 3         | 5.45%   |
| Realtek USB 2 Webcam                                                     | 2         | 3.64%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 3.64%   |
| Z-Star WebCam SC-03FFL11739P                                             | 1         | 1.82%   |
| Z-Star Webcam                                                            | 1         | 1.82%   |
| Z-Star Namuga 1.3M Webcam                                                | 1         | 1.82%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera                            | 1         | 1.82%   |
| Suyin Laptop_Integrated_Webcam_3M                                        | 1         | 1.82%   |
| Suyin Acer Crystal Eye webcam                                            | 1         | 1.82%   |
| Suyin 1.3M HD Webcam                                                     | 1         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                     | 1         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                                    | 1         | 1.82%   |
| Silicon Motion WebCam SC-13HDL11939N                                     | 1         | 1.82%   |
| Silicon Motion 300k Pixel Camera                                         | 1         | 1.82%   |
| Realtek Realtek USB2.0 PC Camera                                         | 1         | 1.82%   |
| Microdia USB 2.0 Camera                                                  | 1         | 1.82%   |
| Microdia Integrated Webcam                                               | 1         | 1.82%   |
| Luxvisions Innotech Limited Integrated RGB Camera                        | 1         | 1.82%   |
| Logitech Webcam C930e                                                    | 1         | 1.82%   |
| Logitech B525 HD Webcam                                                  | 1         | 1.82%   |
| Lite-On Integrated Camera                                                | 1         | 1.82%   |
| Lite-On HP Wide Vision HD Camera                                         | 1         | 1.82%   |
| Lite-On HP HD Camera                                                     | 1         | 1.82%   |
| Lenovo Integrated Webcam                                                 | 1         | 1.82%   |
| IMC Networks Integrated Webcam                                           | 1         | 1.82%   |
| Creative Webcam Live! Motion                                             | 1         | 1.82%   |
| Chicony Webcam                                                           | 1         | 1.82%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 1.82%   |
| Chicony Thinkpad T430 camera                                             | 1         | 1.82%   |
| Chicony Integrated Camera [ThinkPad]                                     | 1         | 1.82%   |
| Chicony Chicony USB 2.0 Camera                                           | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera           | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.82%   |
| Bison ThinkPad P50 Integrated Camera                                     | 1         | 1.82%   |
| Bison Lenovo EasyCamera                                                  | 1         | 1.82%   |
| Bison Integrated Camera                                                  | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Upek                       | 3         | 20%     |
| Shenzhen Goodix Technology | 3         | 20%     |
| Synaptics                  | 2         | 13.33%  |
| Broadcom                   | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 20%     |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 1         | 6.67%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 6.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 6.67%   |
| Unknown                                                                      | 1         | 6.67%   |

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
| 2     | 30        | 34.09%  |
| 1     | 25        | 28.41%  |
| 0     | 15        | 17.05%  |
| 3     | 10        | 11.36%  |
| 4     | 6         | 6.82%   |
| 5     | 2         | 2.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 57        | 42.54%  |
| Bluetooth                | 23        | 17.16%  |
| Net/wireless             | 15        | 11.19%  |
| Fingerprint reader       | 13        | 9.7%    |
| Firewire controller      | 11        | 8.21%   |
| Card reader              | 11        | 8.21%   |
| Storage                  | 2         | 1.49%   |
| Sound                    | 1         | 0.75%   |
| Graphics card            | 1         | 0.75%   |

