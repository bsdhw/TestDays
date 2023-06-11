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

Total: 203

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OpenBSD 6.8          | 7         | 4.55%   |
| helloSystem 0.4.0    | 7         | 4.55%   |
| NomadBSD 1.3.2       | 6         | 3.9%    |
| helloSystem 0.7.0    | 6         | 3.9%    |
| FreeBSD 13.1         | 6         | 3.9%    |
| OpenBSD 7.0          | 5         | 3.25%   |
| GhostBSD 20.04.02    | 5         | 3.25%   |
| FreeBSD 13.1-p7      | 5         | 3.25%   |
| FreeBSD 13.0         | 5         | 3.25%   |
| OpenBSD 7.1          | 4         | 2.6%    |
| NomadBSD 20221130    | 4         | 2.6%    |
| NomadBSD 1.4         | 4         | 2.6%    |
| helloSystem 0.8.0    | 4         | 2.6%    |
| FreeBSD 12.2-p2      | 4         | 2.6%    |
| OpenBSD 6.9          | 3         | 1.95%   |
| helloSystem 0.8.1    | 3         | 1.95%   |
| FreeBSD 13.1-p3      | 3         | 1.95%   |
| FreeBSD 13.0-STABLE  | 3         | 1.95%   |
| FreeBSD 12.2-p4      | 3         | 1.95%   |
| FreeBSD 12.2         | 3         | 1.95%   |
| OPNsense 22.7.6      | 2         | 1.3%    |
| OPNsense 22.10       | 2         | 1.3%    |
| OPNsense 22.1        | 2         | 1.3%    |
| OpenBSD 7.2          | 2         | 1.3%    |
| OpenBSD 6.7          | 2         | 1.3%    |
| GhostBSD 22.01.12    | 2         | 1.3%    |
| FreeBSD 14.0-CURRENT | 2         | 1.3%    |
| FreeBSD 13.2         | 2         | 1.3%    |
| FreeBSD 13.1-STABLE  | 2         | 1.3%    |
| FreeBSD 13.0-RC5     | 2         | 1.3%    |
| FreeBSD 13.0-p6      | 2         | 1.3%    |
| FreeBSD 13.0-p3      | 2         | 1.3%    |
| FreeBSD 13.0-p1      | 2         | 1.3%    |
| FreeBSD 12.1-p10     | 2         | 1.3%    |
| OPNsense 23.4        | 1         | 0.65%   |
| OPNsense 23.1.9      | 1         | 0.65%   |
| OPNsense 23.1.8      | 1         | 0.65%   |
| OPNsense 23.1.5      | 1         | 0.65%   |
| OPNsense 23.1.4      | 1         | 0.65%   |
| OPNsense 22.10.2     | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 57        | 43.18%  |
| OpenBSD     | 20        | 15.15%  |
| helloSystem | 18        | 13.64%  |
| NomadBSD    | 14        | 10.61%  |
| OPNsense    | 12        | 9.09%   |
| GhostBSD    | 9         | 6.82%   |
| NetBSD      | 1         | 0.76%   |
| FuryBSD     | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 117       | 96.69%  |
| i386   | 3         | 2.48%   |
| macppc | 1         | 0.83%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 24        | 17.65%  |
| XFCE         | 19        | 13.97%  |
| Console      | 16        | 11.76%  |
| KDE5         | 15        | 11.03%  |
| fvwm         | 15        | 11.03%  |
| Openbox      | 12        | 8.82%   |
| MATE         | 10        | 7.35%   |
| TWM          | 7         | 5.15%   |
| GNOME        | 6         | 4.41%   |
| i3           | 4         | 2.94%   |
| xinitrc      | 3         | 2.21%   |
| AwesomeWM    | 2         | 1.47%   |
| X-Cinnamon   | 1         | 0.74%   |
| sway         | 1         | 0.74%   |
| LXDE         | 1         | 0.74%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 105       | 85.37%  |
| Console | 18        | 14.63%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 50        | 38.76%  |
| SLiM    | 40        | 31.01%  |
| SDDM    | 15        | 11.63%  |
| LightDM | 13        | 10.08%  |
| XDM     | 6         | 4.65%   |
| GDM     | 5         | 3.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 42        | 32.06%  |
| fr_FR           | 33        | 25.19%  |
| en_US           | 26        | 19.85%  |
| C               | 21        | 16.03%  |
| de_DE           | 3         | 2.29%   |
| fr              | 2         | 1.53%   |
| en_GB           | 2         | 1.53%   |
| en_US.ISO8859-1 | 1         | 0.76%   |
| en              | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 93        | 76.23%  |
| BIOS | 29        | 23.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 67        | 52.76%  |
| Ufs    | 33        | 25.98%  |
| Ffs    | 20        | 15.75%  |
| Cd9660 | 7         | 5.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 97        | 78.86%  |
| MBR     | 24        | 19.51%  |
| BSD     | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 37        | 30.58%  |
| Dell                | 24        | 19.83%  |
| ASUSTek Computer    | 10        | 8.26%   |
| Hewlett-Packard     | 8         | 6.61%   |
| Intel               | 5         | 4.13%   |
| Apple               | 5         | 4.13%   |
| Deciso              | 4         | 3.31%   |
| Acer                | 4         | 3.31%   |
| TUXEDO              | 3         | 2.48%   |
| Toshiba             | 3         | 2.48%   |
| Sony                | 2         | 1.65%   |
| Notebook            | 2         | 1.65%   |
| MSI                 | 2         | 1.65%   |
| Fujitsu             | 2         | 1.65%   |
| Alienware           | 2         | 1.65%   |
| SECO                | 1         | 0.83%   |
| Samsung Electronics | 1         | 0.83%   |
| Panasonic           | 1         | 0.83%   |
| Medion              | 1         | 0.83%   |
| Google              | 1         | 0.83%   |
| Gigabyte Technology | 1         | 0.83%   |
| Clevo               | 1         | 0.83%   |
| Unknown             | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel H81U                               | 4         | 3.31%   |
| Dell Precision M4500                     | 3         | 2.48%   |
| Deciso Netboard A20                      | 3         | 2.48%   |
| TUXEDO InfinityBook13V3                  | 2         | 1.65%   |
| Toshiba PORTEGE Z930                     | 2         | 1.65%   |
| Dell Latitude 3410                       | 2         | 1.65%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.83%   |
| Toshiba NB300                            | 1         | 0.83%   |
| Sony VGN-FZ19VN                          | 1         | 0.83%   |
| Sony VGN-AR630E                          | 1         | 0.83%   |
| SECO UDOO x86                            | 1         | 0.83%   |
| Samsung R720                             | 1         | 0.83%   |
| Panasonic CF-31-5                        | 1         | 0.83%   |
| Notebook W510LU                          | 1         | 0.83%   |
| Notebook N7x0WU                          | 1         | 0.83%   |
| MSI P65 Creator 8RE                      | 1         | 0.83%   |
| MSI MS-N033                              | 1         | 0.83%   |
| Medion E15415                            | 1         | 0.83%   |
| Lenovo ThinkPad X280 20KFCTO1WW          | 1         | 0.83%   |
| Lenovo ThinkPad X250 20CLS7WY04          | 1         | 0.83%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 0.83%   |
| Lenovo ThinkPad X230 2325AJ9             | 1         | 0.83%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.83%   |
| Lenovo ThinkPad X220 4290EE8             | 1         | 0.83%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1TG00 | 1         | 0.83%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 0.83%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2K000 | 1         | 0.83%   |
| Lenovo ThinkPad W540 20BG001KUK          | 1         | 0.83%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.83%   |
| Lenovo ThinkPad T580 20LAS2TG00          | 1         | 0.83%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 0.83%   |
| Lenovo ThinkPad T495 20NKS0HN1N          | 1         | 0.83%   |
| Lenovo ThinkPad T495 20NJCTO1WW          | 1         | 0.83%   |
| Lenovo ThinkPad T490 20N20009FR          | 1         | 0.83%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 0.83%   |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 0.83%   |
| Lenovo ThinkPad T450s 20BWS0L600         | 1         | 0.83%   |
| Lenovo ThinkPad T440p 20AWS0Y40T         | 1         | 0.83%   |
| Lenovo ThinkPad T430 23495P8             | 1         | 0.83%   |
| Lenovo ThinkPad T420 4236NUG             | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 32        | 26.45%  |
| Dell Latitude           | 13        | 10.74%  |
| Dell Precision          | 6         | 4.96%   |
| Intel H81U              | 4         | 3.31%   |
| HP EliteBook            | 4         | 3.31%   |
| Deciso Netboard         | 3         | 2.48%   |
| Acer Aspire             | 3         | 2.48%   |
| TUXEDO InfinityBook13V3 | 2         | 1.65%   |
| Toshiba PORTEGE         | 2         | 1.65%   |
| Lenovo Legion           | 2         | 1.65%   |
| Dell Inspiron           | 2         | 1.65%   |
| TUXEDO Aura             | 1         | 0.83%   |
| Toshiba NB300           | 1         | 0.83%   |
| Sony VGN-FZ19VN         | 1         | 0.83%   |
| Sony VGN-AR630E         | 1         | 0.83%   |
| SECO UDOO               | 1         | 0.83%   |
| Samsung R720            | 1         | 0.83%   |
| Panasonic CF-31-5       | 1         | 0.83%   |
| Notebook W510LU         | 1         | 0.83%   |
| Notebook N7x0WU         | 1         | 0.83%   |
| MSI P65                 | 1         | 0.83%   |
| MSI MS-N033             | 1         | 0.83%   |
| Medion E15415           | 1         | 0.83%   |
| Lenovo IdeaPad          | 1         | 0.83%   |
| Lenovo G500             | 1         | 0.83%   |
| Lenovo Flex             | 1         | 0.83%   |
| Intel Jasper            | 1         | 0.83%   |
| HP ZBook                | 1         | 0.83%   |
| HP ProBook              | 1         | 0.83%   |
| HP Pavilion             | 1         | 0.83%   |
| HP Compaq               | 1         | 0.83%   |
| Google Terra            | 1         | 0.83%   |
| Gigabyte P15FR7         | 1         | 0.83%   |
| Fujitsu LIFEBOOK        | 1         | 0.83%   |
| Fujitsu CELSIUS         | 1         | 0.83%   |
| Dell Vostro             | 1         | 0.83%   |
| Dell System             | 1         | 0.83%   |
| Dell Studio             | 1         | 0.83%   |
| Deciso NetBoard-A20     | 1         | 0.83%   |
| Clevo W240EU            | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 18        | 14.88%  |
| 2020    | 16        | 13.22%  |
| 2015    | 10        | 8.26%   |
| 2013    | 10        | 8.26%   |
| 2022    | 8         | 6.61%   |
| 2021    | 8         | 6.61%   |
| 2018    | 8         | 6.61%   |
| 2011    | 8         | 6.61%   |
| 2010    | 8         | 6.61%   |
| 2014    | 7         | 5.79%   |
| 2017    | 4         | 3.31%   |
| 2016    | 4         | 3.31%   |
| 2012    | 3         | 2.48%   |
| 2009    | 3         | 2.48%   |
| 2008    | 3         | 2.48%   |
| 2007    | 2         | 1.65%   |
| Unknown | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 121       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 98.35%  |
| Yes  | 2         | 1.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 41        | 33.33%  |
| 16.01-24.0  | 30        | 24.39%  |
| 4.01-8.0    | 22        | 17.89%  |
| 32.01-64.0  | 10        | 8.13%   |
| 2.01-3.0    | 9         | 7.32%   |
| 64.01-256.0 | 4         | 3.25%   |
| 3.01-4.0    | 3         | 2.44%   |
| 24.01-32.0  | 2         | 1.63%   |
| 1.01-2.0    | 2         | 1.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 70        | 55.12%  |
| 0.51-1.0   | 32        | 25.2%   |
| 1.01-2.0   | 13        | 10.24%  |
| 2.01-3.0   | 6         | 4.72%   |
| 8.01-16.0  | 4         | 3.15%   |
| 32.01-64.0 | 1         | 0.79%   |
| Unknown    | 1         | 0.79%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 63.41%  |
| 2      | 27        | 21.95%  |
| 0      | 11        | 8.94%   |
| 3      | 5         | 4.07%   |
| 4      | 2         | 1.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 73.39%  |
| Yes       | 33        | 26.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 87.7%   |
| No        | 15        | 12.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 91.74%  |
| No        | 10        | 8.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 56.45%  |
| No        | 54        | 43.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 121       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Paris                    | 22        | 15.83%  |
| Franconville             | 7         | 5.04%   |
| Bordeaux                 | 6         | 4.32%   |
| Melun                    | 4         | 2.88%   |
| Marcq-en-Baroeul         | 3         | 2.16%   |
| Fontenay-sous-Bois       | 3         | 2.16%   |
| Carry-le-Rouet           | 3         | 2.16%   |
| Stiring-Wendel           | 2         | 1.44%   |
| Saint-Raphaël           | 2         | 1.44%   |
| Saint-Denis              | 2         | 1.44%   |
| Rosny-sous-Bois          | 2         | 1.44%   |
| Rennes                   | 2         | 1.44%   |
| Noisy-le-Grand           | 2         | 1.44%   |
| Mâcon                   | 2         | 1.44%   |
| Dijon                    | 2         | 1.44%   |
| Colombes                 | 2         | 1.44%   |
| Colmar                   | 2         | 1.44%   |
| Asnieres-sur-Seine       | 2         | 1.44%   |
| Villeneuve-Saint-Georges | 1         | 0.72%   |
| Villemomble              | 1         | 0.72%   |
| Villejuif                | 1         | 0.72%   |
| Vertou                   | 1         | 0.72%   |
| Tulle                    | 1         | 0.72%   |
| Tournon-sur-RhÃ´ne     | 1         | 0.72%   |
| Toulouse                 | 1         | 0.72%   |
| St-Malo                  | 1         | 0.72%   |
| Soisy-sur-Seine          | 1         | 0.72%   |
| Sartrouville             | 1         | 0.72%   |
| Sarcelles                | 1         | 0.72%   |
| Sallanches               | 1         | 0.72%   |
| Saint-Saulge             | 1         | 0.72%   |
| Saint-Herblain           | 1         | 0.72%   |
| Saint-Germain-en-Laye    | 1         | 0.72%   |
| Saint-Genest-Lerpt       | 1         | 0.72%   |
| Roubaix                  | 1         | 0.72%   |
| Quimper                  | 1         | 0.72%   |
| Poncins                  | 1         | 0.72%   |
| Oudon                    | 1         | 0.72%   |
| Noirmoutier-en-l'Ile     | 1         | 0.72%   |
| Nogent-sur-Marne         | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 35     | 17.73%  |
| Seagate             | 14        | 26     | 9.93%   |
| Crucial             | 14        | 18     | 9.93%   |
| Toshiba             | 13        | 19     | 9.22%   |
| WDC                 | 10        | 13     | 7.09%   |
| SanDisk             | 9         | 11     | 6.38%   |
| Kingston            | 9         | 11     | 6.38%   |
| Transcend           | 7         | 12     | 4.96%   |
| China               | 7         | 7      | 4.96%   |
| NVMe                | 5         | 5      | 3.55%   |
| Micron Technology   | 5         | 8      | 3.55%   |
| HGST                | 5         | 8      | 3.55%   |
| Intel               | 4         | 7      | 2.84%   |
| SK hynix            | 3         | 3      | 2.13%   |
| Phison              | 2         | 2      | 1.42%   |
| Fujitsu             | 2         | 2      | 1.42%   |
| SPCC                | 1         | 1      | 0.71%   |
| Lexar               | 1         | 1      | 0.71%   |
| LDLC F6+            | 1         | 1      | 0.71%   |
| Integral            | 1         | 1      | 0.71%   |
| Hitachi             | 1         | 1      | 0.71%   |
| Generic             | 1         | 1      | 0.71%   |
| EMTEC               | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB            | 4         | 2.76%   |
| China MSATA 32GB SSD                      | 4         | 2.76%   |
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.07%   |
| Kingston SA400S37240G 240GB               | 3         | 2.07%   |
| Crucial CT1000P1SSD8 1TB                  | 3         | 2.07%   |
| WDC WD3200BPVT-80JJ5T0 320GB              | 2         | 1.38%   |
| Transcend TS256GMTS430S 256GB             | 2         | 1.38%   |
| Toshiba MK2556GSY 250GB                   | 2         | 1.38%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 2         | 1.38%   |
| Samsung SSD 970 EVO Plus 2TB              | 2         | 1.38%   |
| Samsung SSD 950 PRO 512GB                 | 2         | 1.38%   |
| NVMe WDC PC SN720 SDA 512GB               | 2         | 1.38%   |
| Intel SSDPEKKF256G8L 256GB                | 2         | 1.38%   |
| HGST HTS725050A7E630 500GB                | 2         | 1.38%   |
| HGST HTS721010A9E630 1TB                  | 2         | 1.38%   |
| Crucial CT960M500SSD1 960GB               | 2         | 1.38%   |
| Crucial CT1050MX300SSD1 1TB               | 2         | 1.38%   |
| China SH00M240GB                          | 2         | 1.38%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.69%   |
| WDC WDS120G2G0B-00EPW0 120GB              | 1         | 0.69%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 0.69%   |
| WDC WD20SDRW-11VUUS0 2TB                  | 1         | 0.69%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.69%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB      | 1         | 0.69%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 0.69%   |
| Transcend TS256GMTS800 256GB              | 1         | 0.69%   |
| Toshiba THNSNJ256GCSY 256GB               | 1         | 0.69%   |
| Toshiba THNSNF128GMCS 128GB               | 1         | 0.69%   |
| Toshiba THNSN51T02DUK NVMe 1024GB         | 1         | 0.69%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.69%   |
| Toshiba MQ01ACF032 320GB                  | 1         | 0.69%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.69%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.69%   |
| Toshiba MK2555GSX 250GB                   | 1         | 0.69%   |
| Toshiba MK2546GSX_200 200GB               | 1         | 0.69%   |
| Toshiba MK1629GSGF 160GB                  | 1         | 0.69%   |
| SPCC Solid State Disk 512GB               | 1         | 0.69%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB      | 1         | 0.69%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 26     | 31.11%  |
| Toshiba             | 8         | 11     | 17.78%  |
| WDC                 | 6         | 7      | 13.33%  |
| NVMe                | 5         | 5      | 11.11%  |
| HGST                | 5         | 8      | 11.11%  |
| Fujitsu             | 2         | 2      | 4.44%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| Lexar               | 1         | 1      | 2.22%   |
| LDLC F6+            | 1         | 1      | 2.22%   |
| Hitachi             | 1         | 1      | 2.22%   |
| Generic             | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 19     | 20.63%  |
| SanDisk             | 9         | 11     | 14.29%  |
| Crucial             | 9         | 9      | 14.29%  |
| Kingston            | 8         | 9      | 12.7%   |
| Transcend           | 7         | 12     | 11.11%  |
| China               | 7         | 7      | 11.11%  |
| Toshiba             | 4         | 6      | 6.35%   |
| WDC                 | 2         | 2      | 3.17%   |
| SPCC                | 1         | 1      | 1.59%   |
| Micron Technology   | 1         | 4      | 1.59%   |
| Integral            | 1         | 1      | 1.59%   |
| EMTEC               | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 56        | 82     | 43.75%  |
| HDD  | 42        | 64     | 32.81%  |
| NVMe | 30        | 48     | 23.44%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 91        | 146    | 75.21%  |
| NVMe | 30        | 48     | 24.79%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 102    | 67.65%  |
| 0.51-1.0   | 28        | 38     | 27.45%  |
| 1.01-2.0   | 5         | 6      | 4.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 41        | 32.03%  |
| 1-20       | 26        | 20.31%  |
| 251-500    | 21        | 16.41%  |
| 21-50      | 17        | 13.28%  |
| 501-1000   | 12        | 9.38%   |
| 51-100     | 8         | 6.25%   |
| 1001-2000  | 2         | 1.56%   |
| Unknown    | 1         | 0.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 101       | 82.11%  |
| 21-50    | 9         | 7.32%   |
| 101-250  | 8         | 6.5%    |
| 51-100   | 3         | 2.44%   |
| 501-1000 | 1         | 0.81%   |
| Unknown  | 1         | 0.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB          | 2         | 2      | 12.5%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 6.25%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 6.25%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 6.25%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 6.25%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 7      | 6.25%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 6.25%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 6.25%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 6.25%   |
| Kingston SUV500MS480G 480GB           | 1         | 1      | 6.25%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 6.25%   |
| HGST HTS545050A7E660 500GB            | 1         | 2      | 6.25%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 11     | 31.25%  |
| WDC                 | 3         | 3      | 18.75%  |
| Toshiba             | 2         | 4      | 12.5%   |
| HGST                | 2         | 3      | 12.5%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 2      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 11     | 41.67%  |
| WDC     | 3         | 3      | 25%     |
| Toshiba | 2         | 4      | 16.67%  |
| HGST    | 2         | 3      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 21     | 73.33%  |
| SSD  | 4         | 5      | 26.67%  |

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
| Works    | 96        | 163    | 82.76%  |
| Malfunc  | 15        | 26     | 12.93%  |
| Detected | 5         | 5      | 4.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 91        | 66.42%  |
| Samsung Electronics         | 13        | 9.49%   |
| AMD                         | 11        | 8.03%   |
| Micron/Crucial Technology   | 5         | 3.65%   |
| SanDisk                     | 4         | 2.92%   |
| Micron Technology           | 4         | 2.92%   |
| SK hynix                    | 3         | 2.19%   |
| Phison Electronics          | 2         | 1.46%   |
| Toshiba                     | 1         | 0.73%   |
| Nvidia                      | 1         | 0.73%   |
| KIOXIA                      | 1         | 0.73%   |
| Kingston Technology Company | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 8.16%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 7.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 6.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 5.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 5.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 4.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 4.08%   |
| Micron NVMe Storage Controller                                                   | 4         | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.72%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.04%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 2.04%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2.04%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 3         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 2.04%   |
| SK hynix BC511                                                                   | 2         | 1.36%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.36%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.36%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.36%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.68%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.68%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.68%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.68%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.68%   |
| Intel SSD 660P Series                                                            | 1         | 0.68%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.68%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 86        | 61.87%  |
| NVMe | 34        | 24.46%  |
| RAID | 11        | 7.91%   |
| IDE  | 8         | 5.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 104       | 85.25%  |
| AMD     | 17        | 13.93%  |
| PowerPC | 1         | 0.82%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz    | 5         | 4.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz    | 4         | 3.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 4         | 3.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 3         | 2.46%   |
| Intel Core i5 CPU M 560 @ 2.67GH     | 3         | 2.46%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 3         | 2.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 1.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 2         | 1.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 2         | 1.64%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 2         | 1.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 1.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 1.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 1.64%   |
| Intel Core i5-3437U CPU @ 1.90GHz    | 2         | 1.64%   |
| Intel Core i3-4025U CPU @ 1.90GHz    | 2         | 1.64%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 2         | 1.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 1.64%   |
| Intel Celeron CPU N3160 @ 1.60GHz    | 2         | 1.64%   |
| AMD EPYC 3201 8-Core Processor       | 2         | 1.64%   |
| AMD EPYC 3101 4-Core Processor       | 2         | 1.64%   |
| PowerPC 7447A (Revision 0x105)       | 1         | 0.82%   |
| Intel Pentium M                      | 1         | 0.82%   |
| Intel CPU Version                    | 1         | 0.82%   |
| Intel Core M-5Y10c CPU @ 0.80GHz     | 1         | 0.82%   |
| Intel Core i7-9850H CPU @ 2.60GHz    | 1         | 0.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 0.82%   |
| Intel Core i7-8665U CPU @ 1.90GHz    | 1         | 0.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 1         | 0.82%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz   | 1         | 0.82%   |
| Intel Core i7-7820HK CPU @ 2.90GHz   | 1         | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 1         | 0.82%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 1         | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 1         | 0.82%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 1         | 0.82%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz   | 1         | 0.82%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz   | 1         | 0.82%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz   | 1         | 0.82%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 1         | 0.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 1         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 40        | 32.79%  |
| Intel Core i7    | 29        | 23.77%  |
| Intel Core i3    | 12        | 9.84%   |
| Intel Core 2 Duo | 9         | 7.38%   |
| Intel Celeron    | 6         | 4.92%   |
| Other            | 4         | 3.28%   |
| AMD Ryzen 7 PRO  | 4         | 3.28%   |
| AMD Ryzen 7      | 4         | 3.28%   |
| AMD EPYC         | 4         | 3.28%   |
| Intel Atom       | 3         | 2.46%   |
| Intel Pentium M  | 1         | 0.82%   |
| Intel Core M     | 1         | 0.82%   |
| AMD Ryzen 5 PRO  | 1         | 0.82%   |
| AMD Ryzen 5      | 1         | 0.82%   |
| AMD E1           | 1         | 0.82%   |
| AMD A6           | 1         | 0.82%   |
| AMD A4           | 1         | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 55        | 45.08%  |
| 4       | 41        | 33.61%  |
| Unknown | 9         | 7.38%   |
| 8       | 8         | 6.56%   |
| 16      | 4         | 3.28%   |
| 6       | 2         | 1.64%   |
| 1       | 2         | 1.64%   |
| 12      | 1         | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 115       | 95.04%  |
| Unknown | 4         | 3.31%   |
| 2       | 2         | 1.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 84        | 68.85%  |
| 1       | 28        | 22.95%  |
| Unknown | 10        | 8.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 32        | 26.23%  |
| Haswell     | 16        | 13.11%  |
| IvyBridge   | 12        | 9.84%   |
| SandyBridge | 8         | 6.56%   |
| Penryn      | 8         | 6.56%   |
| Broadwell   | 6         | 4.92%   |
| Zen         | 5         | 4.1%    |
| Westmere    | 5         | 4.1%    |
| Skylake     | 5         | 4.1%    |
| Unknown     | 5         | 4.1%    |
| Silvermont  | 4         | 3.28%   |
| Zen+        | 3         | 2.46%   |
| Zen 2       | 3         | 2.46%   |
| Bonnell     | 3         | 2.46%   |
| Jaguar      | 2         | 1.64%   |
| Core        | 2         | 1.64%   |
| Zen 3       | 1         | 0.82%   |
| P6          | 1         | 0.82%   |
| K10 Llano   | 1         | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 90        | 65.22%  |
| Nvidia | 28        | 20.29%  |
| AMD    | 20        | 14.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 8.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 6.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 4.2%    |
| Intel HD Graphics 620                                                                    | 6         | 4.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 4.2%    |
| Intel UHD Graphics 620                                                                   | 5         | 3.5%    |
| Intel HD Graphics 5500                                                                   | 5         | 3.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.8%    |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 2.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.1%    |
| Intel HD Graphics 630                                                                    | 3         | 2.1%    |
| AMD Renoir                                                                               | 3         | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.4%    |
| Intel HD Graphics 530                                                                    | 2         | 1.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.4%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.4%    |
| AMD Lucienne                                                                             | 2         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.7%    |
| Nvidia TU117M                                                                            | 1         | 0.7%    |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.7%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.7%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.7%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.7%    |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                                    | 1         | 0.7%    |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                                 | 1         | 0.7%    |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.7%    |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 63        | 51.64%  |
| Intel + Nvidia           | 16        | 13.11%  |
| 1 x AMD                  | 16        | 13.11%  |
| 1 x Nvidia               | 10        | 8.2%    |
| 2 x Intel                | 9         | 7.38%   |
| Other                    | 4         | 3.28%   |
| 2 x AMD                  | 1         | 0.82%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.82%   |
| Intel + AMD              | 1         | 0.82%   |
| AMD + Nvidia             | 1         | 0.82%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 107       | 86.99%  |
| Proprietary | 9         | 7.32%   |
| Unknown     | 7         | 5.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 88.52%  |
| 0.51-1.0   | 5         | 4.1%    |
| 0.01-0.5   | 3         | 2.46%   |
| 5.01-6.0   | 2         | 1.64%   |
| 7.01-8.0   | 1         | 0.82%   |
| 3.01-4.0   | 1         | 0.82%   |
| 1.01-2.0   | 1         | 0.82%   |
| 8.01-16.0  | 1         | 0.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 20.65%  |
| LG Display              | 14        | 15.22%  |
| Chimei Innolux          | 14        | 15.22%  |
| BOE                     | 9         | 9.78%   |
| Samsung Electronics     | 8         | 8.7%    |
| Chi Mei Optoelectronics | 4         | 4.35%   |
| Apple                   | 4         | 4.35%   |
| Philips                 | 3         | 3.26%   |
| LGD                     | 2         | 2.17%   |
| Lenovo                  | 2         | 2.17%   |
| Iiyama                  | 2         | 2.17%   |
| ViewSonic               | 1         | 1.09%   |
| Sharp                   | 1         | 1.09%   |
| Nvidia                  | 1         | 1.09%   |
| IBM                     | 1         | 1.09%   |
| Hewlett-Packard         | 1         | 1.09%   |
| Goldstar                | 1         | 1.09%   |
| Dell                    | 1         | 1.09%   |
| CSO                     | 1         | 1.09%   |
| CPT                     | 1         | 1.09%   |
| ASUSTek Computer        | 1         | 1.09%   |
| Acer                    | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 3.26%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 2.17%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 2.17%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2.17%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 2.17%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 1.09%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 340x190mm 15.3-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch     | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.09%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 1.09%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 1.09%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 1.09%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1.09%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD036C 1366x768 280x160mm 12.7-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD0366 1600x900 310x170mm 13.9-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.09%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch              | 1         | 1.09%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1.09%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.09%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 1         | 1.09%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 1         | 1.09%   |
| Hewlett-Packard M27f FHD HPN370A 1920x1080 610x360mm 27.9-inch           | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 43.18%  |
| 1366x768 (WXGA)    | 26        | 29.55%  |
| 1600x900 (HD+)     | 6         | 6.82%   |
| 3840x2160 (4K)     | 4         | 4.55%   |
| 1280x800 (WXGA)    | 4         | 4.55%   |
| 2560x1440 (QHD)    | 3         | 3.41%   |
| 1440x900 (WXGA+)   | 2         | 2.27%   |
| 1024x600           | 2         | 2.27%   |
| 2880x1800          | 1         | 1.14%   |
| 1680x1050 (WSXGA+) | 1         | 1.14%   |
| 1440x960           | 1         | 1.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 29        | 31.52%  |
| 13      | 23        | 25%     |
| 12      | 12        | 13.04%  |
| 17      | 5         | 5.43%   |
| Unknown | 4         | 4.35%   |
| 27      | 3         | 3.26%   |
| 24      | 3         | 3.26%   |
| 23      | 3         | 3.26%   |
| 10      | 3         | 3.26%   |
| 21      | 2         | 2.17%   |
| 14      | 2         | 2.17%   |
| 42      | 1         | 1.09%   |
| 18      | 1         | 1.09%   |
| 11      | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 52.17%  |
| 201-300     | 22        | 23.91%  |
| 501-600     | 8         | 8.7%    |
| 351-400     | 5         | 5.43%   |
| Unknown     | 4         | 4.35%   |
| 401-500     | 3         | 3.26%   |
| 601-700     | 1         | 1.09%   |
| 901-1000    | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 83.95%  |
| 16/10   | 7         | 8.64%   |
| Unknown | 4         | 4.94%   |
| 3/2     | 2         | 2.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 25        | 27.17%  |
| 81-90          | 24        | 26.09%  |
| 61-70          | 12        | 13.04%  |
| 201-250        | 8         | 8.7%    |
| 121-130        | 5         | 5.43%   |
| 101-110        | 4         | 4.35%   |
| Unknown        | 4         | 4.35%   |
| 41-50          | 3         | 3.26%   |
| 301-350        | 3         | 3.26%   |
| 71-80          | 1         | 1.09%   |
| 51-60          | 1         | 1.09%   |
| 141-150        | 1         | 1.09%   |
| 501-1000       | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 45.56%  |
| 101-120       | 28        | 31.11%  |
| 51-100        | 9         | 10%     |
| 161-240       | 5         | 5.56%   |
| Unknown       | 4         | 4.44%   |
| More than 240 | 3         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 67.72%  |
| 0     | 29        | 22.83%  |
| 2     | 12        | 9.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 87        | 46.03%  |
| Realtek Semiconductor    | 43        | 22.75%  |
| Qualcomm Atheros         | 21        | 11.11%  |
| Broadcom                 | 11        | 5.82%   |
| Marvell Technology Group | 4         | 2.12%   |
| AMD                      | 4         | 2.12%   |
| TP-Link                  | 3         | 1.59%   |
| Sierra Wireless          | 2         | 1.06%   |
| Edimax Technology        | 2         | 1.06%   |
| Apple                    | 2         | 1.06%   |
| Xiaomi                   | 1         | 0.53%   |
| Sagem                    | 1         | 0.53%   |
| Ralink Technology        | 1         | 0.53%   |
| Ralink                   | 1         | 0.53%   |
| Qualcomm                 | 1         | 0.53%   |
| Nvidia                   | 1         | 0.53%   |
| MediaTek                 | 1         | 0.53%   |
| Huawei Technologies      | 1         | 0.53%   |
| Hewlett-Packard          | 1         | 0.53%   |
| Dell                     | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 13.93%  |
| Intel Wireless 8265 / 8275                                        | 11        | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 4.51%   |
| Intel Wireless 7265                                               | 8         | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.46%   |
| Intel Wireless 7260                                               | 6         | 2.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 2.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.05%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.05%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 2.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 2.05%   |
| Intel Wireless-AC 9260                                            | 4         | 1.64%   |
| Intel Wireless 8260                                               | 4         | 1.64%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.64%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 4         | 1.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.23%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.23%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.23%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.82%   |
| Sierra Wireless EM7305 Modem                                      | 2         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.82%   |
| Intel Wireless 3165                                               | 2         | 0.82%   |
| Intel WiFi Link 5100                                              | 2         | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.82%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 2         | 0.82%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 65.32%  |
| Qualcomm Atheros      | 19        | 15.32%  |
| Broadcom              | 8         | 6.45%   |
| Realtek Semiconductor | 6         | 4.84%   |
| TP-Link               | 3         | 2.42%   |
| Edimax Technology     | 2         | 1.61%   |
| Sagem                 | 1         | 0.81%   |
| Ralink Technology     | 1         | 0.81%   |
| Ralink                | 1         | 0.81%   |
| MediaTek              | 1         | 0.81%   |
| Dell                  | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 11        | 8.8%    |
| Intel Wireless 7265                                                     | 8         | 6.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 6.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.8%    |
| Intel Wireless 7260                                                     | 6         | 4.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 4.8%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 4%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 4%      |
| Intel Wireless-AC 9260                                                  | 4         | 3.2%    |
| Intel Wireless 8260                                                     | 4         | 3.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.4%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 2.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.4%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.6%    |
| Intel Wireless 3165                                                     | 2         | 1.6%    |
| Intel WiFi Link 5100                                                    | 2         | 1.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.6%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.6%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.8%    |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.8%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 1         | 0.8%    |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.8%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 52        | 46.02%  |
| Realtek Semiconductor    | 39        | 34.51%  |
| Qualcomm Atheros         | 6         | 5.31%   |
| Marvell Technology Group | 4         | 3.54%   |
| Broadcom                 | 4         | 3.54%   |
| AMD                      | 4         | 3.54%   |
| Xiaomi                   | 1         | 0.88%   |
| Qualcomm                 | 1         | 0.88%   |
| Nvidia                   | 1         | 0.88%   |
| Apple                    | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 30.09%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 9.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.42%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 4.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 4.42%   |
| Intel I210 Gigabit Network Connection                             | 4         | 3.54%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.54%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.54%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 4         | 3.54%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.77%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.88%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.88%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.88%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.88%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.88%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.88%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.88%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 49.55%  |
| Ethernet | 107       | 47.77%  |
| Modem    | 3         | 1.34%   |
| Unknown  | 3         | 1.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 50.92%  |
| WiFi     | 80        | 49.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 96        | 78.69%  |
| 1     | 15        | 12.3%   |
| 6     | 5         | 4.1%    |
| 3     | 5         | 4.1%    |
| 0     | 1         | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 84.92%  |
| Yes  | 19        | 15.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 70.83%  |
| Broadcom                        | 6         | 8.33%   |
| Foxconn / Hon Hai               | 3         | 4.17%   |
| Apple                           | 3         | 4.17%   |
| Qualcomm Atheros Communications | 2         | 2.78%   |
| IMC Networks                    | 2         | 2.78%   |
| Dell                            | 2         | 2.78%   |
| Realtek Semiconductor           | 1         | 1.39%   |
| Hewlett-Packard                 | 1         | 1.39%   |
| Creative Technology             | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 23        | 31.94%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 9         | 12.5%   |
| Intel AX201 Bluetooth                              | 5         | 6.94%   |
| Intel AX200 Bluetooth                              | 5         | 6.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 3         | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                   | 2         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 2.78%   |
| Intel AX210 Bluetooth                              | 2         | 2.78%   |
| Foxconn / Hon Hai Bluetooth USB Module             | 2         | 2.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 2.78%   |
| Broadcom BCM2045B (BDC-2.1)                        | 2         | 2.78%   |
| Apple Bluetooth Host Controller                    | 2         | 2.78%   |
| Realtek Bluetooth Adapter                          | 1         | 1.39%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1             | 1         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1        | 1         | 1.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS   | 1         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]      | 1         | 1.39%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter          | 1         | 1.39%   |
| Dell DW375 Bluetooth Module                        | 1         | 1.39%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module        | 1         | 1.39%   |
| Creative Creative Bluetooth Audio W2               | 1         | 1.39%   |
| Broadcom BCM43142A0 Bluetooth Module               | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.39%   |
| Apple Built-in iSight (no firmware loaded)         | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 101       | 71.13%  |
| AMD                 | 22        | 15.49%  |
| Nvidia              | 12        | 8.45%   |
| Lenovo              | 2         | 1.41%   |
| Texas Instruments   | 1         | 0.7%    |
| Logitech            | 1         | 0.7%    |
| Kingston Technology | 1         | 0.7%    |
| GN Netcom           | 1         | 0.7%    |
| DSEA A/S            | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 8.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 6.82%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 6.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.41%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.84%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 2.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.7%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.7%    |
| AMD FCH Azalia Controller                                                                         | 3         | 1.7%    |
| Lenovo Realtek USB Audio                                                                          | 2         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.14%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.14%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.14%   |
| Texas Instruments PCM2706 stereo audio DAC                                                        | 1         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.57%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.57%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.57%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.57%   |
| Logitech Logitech Stereo H650e                                                                    | 1         | 0.57%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.57%   |
| Intel USB2.0 Device                                                                               | 1         | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 31.01%  |
| SK hynix            | 26        | 20.16%  |
| Unknown             | 11        | 8.53%   |
| Micron Technology   | 10        | 7.75%   |
| Crucial             | 10        | 7.75%   |
| Kingston            | 8         | 6.2%    |
| Transcend           | 3         | 2.33%   |
| Nanya Technology    | 3         | 2.33%   |
| Elpida              | 3         | 2.33%   |
| Corsair             | 3         | 2.33%   |
| Unknown             | 3         | 2.33%   |
| A-DATA Technology   | 2         | 1.55%   |
| V-Color             | 1         | 0.78%   |
| SHARETRONIC         | 1         | 0.78%   |
| Ramaxel Technology  | 1         | 0.78%   |
| Patriot             | 1         | 0.78%   |
| G.Skill             | 1         | 0.78%   |
| CSX                 | 1         | 0.78%   |
| Avant               | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 2.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 3         | 2.16%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 2.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s     | 3         | 2.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3         | 2.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 2.16%   |
| Unknown                                                    | 3         | 2.16%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 2         | 1.44%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s        | 2         | 1.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 2         | 1.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 2         | 1.44%   |
| Samsung RAM M471B5773CHS-CK0 2GB DDR3 1600MT/s             | 2         | 1.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 2         | 1.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s     | 2         | 1.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.44%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s              | 2         | 1.44%   |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s   | 2         | 1.44%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s    | 2         | 1.44%   |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s | 2         | 1.44%   |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s     | 1         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                | 1         | 0.72%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s             | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM 533MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s           | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 1GB SODIMM DDR2                         | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 0.72%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s        | 1         | 0.72%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 0.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s      | 1         | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.72%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s    | 1         | 0.72%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 46        | 44.66%  |
| DDR4    | 42        | 40.78%  |
| DDR2    | 8         | 7.77%   |
| LPDDR3  | 5         | 4.85%   |
| Unknown | 2         | 1.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 94.34%  |
| Unknown      | 3         | 2.83%   |
| Row Of Chips | 2         | 1.89%   |
| Chip         | 1         | 0.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 39        | 33.91%  |
| 8192  | 37        | 32.17%  |
| 16384 | 17        | 14.78%  |
| 2048  | 17        | 14.78%  |
| 32768 | 3         | 2.61%   |
| 1024  | 2         | 1.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 32        | 28.83%  |
| 2667    | 17        | 15.32%  |
| 3200    | 12        | 10.81%  |
| 2400    | 11        | 9.91%   |
| 1333    | 10        | 9.01%   |
| 1334    | 9         | 8.11%   |
| 2133    | 4         | 3.6%    |
| 1867    | 4         | 3.6%    |
| 667     | 3         | 2.7%    |
| Unknown | 3         | 2.7%    |
| 800     | 2         | 1.8%    |
| 1200    | 1         | 0.9%    |
| 1067    | 1         | 0.9%    |
| 975     | 1         | 0.9%    |
| 533     | 1         | 0.9%    |

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
| Chicony Electronics                    | 30        | 36.14%  |
| Bison Electronics                      | 9         | 10.84%  |
| Sunplus Innovation Technology          | 8         | 9.64%   |
| Microdia                               | 8         | 9.64%   |
| Realtek Semiconductor                  | 6         | 7.23%   |
| IMC Networks                           | 5         | 6.02%   |
| Syntek                                 | 3         | 3.61%   |
| Lite-On Technology                     | 3         | 3.61%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.61%   |
| Suyin                                  | 2         | 2.41%   |
| Quanta                                 | 2         | 2.41%   |
| Alcor Micro                            | 2         | 2.41%   |
| SIMPLO Technology                      | 1         | 1.2%    |
| Apple                                  | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 11.9%   |
| Bison Integrated Camera                             | 6         | 7.14%   |
| Realtek Integrated_Webcam_HD                        | 3         | 3.57%   |
| Microdia Integrated_Webcam_HD                       | 3         | 3.57%   |
| Microdia Integrated Webcam                          | 3         | 3.57%   |
| Chicony HD WebCam                                   | 3         | 3.57%   |
| Syntek Integrated Camera                            | 2         | 2.38%   |
| Sunplus SPCA2650 AV Camera                          | 2         | 2.38%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.38%   |
| Realtek USB Camera                                  | 2         | 2.38%   |
| Lite-On Integrated Camera                           | 2         | 2.38%   |
| IMC Networks EasyCamera                             | 2         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 2.38%   |
| Chicony Realtek DMFT RGB                            | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.38%   |
| Bison SunplusIT Integrated Camera                   | 2         | 2.38%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.19%   |
| Suyin USB 2.0 Camera                                | 1         | 1.19%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 1.19%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.19%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.19%   |
| Sunplus Integrated HD Webcam                        | 1         | 1.19%   |
| Sunplus Asus Webcam                                 | 1         | 1.19%   |
| SIMPLO USB 2.0 Camera                               | 1         | 1.19%   |
| Realtek Integrated Webcam HD                        | 1         | 1.19%   |
| Quanta Integrated Webcam                            | 1         | 1.19%   |
| Quanta HD WebCam                                    | 1         | 1.19%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.19%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.19%   |
| Lite-On Realtek DMFT RGB                            | 1         | 1.19%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.19%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.19%   |
| IMC Networks Integrated Camera                      | 1         | 1.19%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.19%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.19%   |
| Chicony ThinkPad T490 Webcam                        | 1         | 1.19%   |
| Chicony Sonix ST50220 USB Video Camera              | 1         | 1.19%   |
| Chicony Ltd., USB2.0 HD UVC WebCam                  | 1         | 1.19%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 32.14%  |
| Synaptics                  | 7         | 25%     |
| AuthenTec                  | 5         | 17.86%  |
| Shenzhen Goodix Technology | 2         | 7.14%   |
| Elan Microelectronics      | 2         | 7.14%   |
| Upek                       | 1         | 3.57%   |
| LighTuning Technology      | 1         | 3.57%   |
| Broadcom                   | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 17.86%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 7.14%   |
| Elan Fingerprint Sensor                                                      | 2         | 7.14%   |
| AuthenTec AES2810                                                            | 2         | 7.14%   |
| AuthenTec AES1660                                                            | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 3.57%   |
| Validity Sensors VFS491                                                      | 1         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 3.57%   |
| Synaptics UWP WBDI Device                                                    | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.57%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 3.57%   |

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
| 1     | 40        | 30.3%   |
| 2     | 38        | 28.79%  |
| 3     | 21        | 15.91%  |
| 0     | 15        | 11.36%  |
| 4     | 11        | 8.33%   |
| 6     | 4         | 3.03%   |
| 5     | 2         | 1.52%   |
| 7     | 1         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 88        | 39.29%  |
| Bluetooth                | 35        | 15.63%  |
| Card reader              | 24        | 10.71%  |
| Fingerprint reader       | 23        | 10.27%  |
| Net/wireless             | 22        | 9.82%   |
| Firewire controller      | 14        | 6.25%   |
| Storage                  | 4         | 1.79%   |
| Sound                    | 4         | 1.79%   |
| Graphics card            | 4         | 1.79%   |
| Storage/raid             | 3         | 1.34%   |
| Network                  | 2         | 0.89%   |
| Net/ethernet             | 1         | 0.45%   |

