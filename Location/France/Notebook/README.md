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

Total: 224

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OpenBSD 6.8          | 7         | 4.12%   |
| helloSystem 0.4.0    | 7         | 4.12%   |
| NomadBSD 1.3.2       | 6         | 3.53%   |
| helloSystem 0.7.0    | 6         | 3.53%   |
| FreeBSD 13.1         | 6         | 3.53%   |
| OpenBSD 7.0          | 5         | 2.94%   |
| NomadBSD 20221130    | 5         | 2.94%   |
| helloSystem 0.8.1    | 5         | 2.94%   |
| GhostBSD 20.04.02    | 5         | 2.94%   |
| FreeBSD 13.1-p7      | 5         | 2.94%   |
| FreeBSD 13.0         | 5         | 2.94%   |
| OpenBSD 7.1          | 4         | 2.35%   |
| NomadBSD 1.4         | 4         | 2.35%   |
| helloSystem 0.8.0    | 4         | 2.35%   |
| FreeBSD 12.2-p2      | 4         | 2.35%   |
| OpenBSD 6.9          | 3         | 1.76%   |
| FreeBSD 13.2         | 3         | 1.76%   |
| FreeBSD 13.1-p3      | 3         | 1.76%   |
| FreeBSD 13.0-STABLE  | 3         | 1.76%   |
| FreeBSD 12.2-p4      | 3         | 1.76%   |
| FreeBSD 12.2         | 3         | 1.76%   |
| OPNsense 23.1.11     | 2         | 1.18%   |
| OPNsense 22.7.6      | 2         | 1.18%   |
| OPNsense 22.10       | 2         | 1.18%   |
| OPNsense 22.1        | 2         | 1.18%   |
| OpenBSD 7.2          | 2         | 1.18%   |
| OpenBSD 6.7          | 2         | 1.18%   |
| GhostBSD 22.01.12    | 2         | 1.18%   |
| FreeBSD 14.0-CURRENT | 2         | 1.18%   |
| FreeBSD 13.2-p3      | 2         | 1.18%   |
| FreeBSD 13.2-p2      | 2         | 1.18%   |
| FreeBSD 13.1-STABLE  | 2         | 1.18%   |
| FreeBSD 13.0-RC5     | 2         | 1.18%   |
| FreeBSD 13.0-p6      | 2         | 1.18%   |
| FreeBSD 13.0-p3      | 2         | 1.18%   |
| FreeBSD 13.0-p1      | 2         | 1.18%   |
| FreeBSD 12.1-p10     | 2         | 1.18%   |
| OPNsense 23.7.6      | 1         | 0.59%   |
| OPNsense 23.7.3      | 1         | 0.59%   |
| OPNsense 23.4        | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 63        | 43.75%  |
| OpenBSD     | 21        | 14.58%  |
| helloSystem | 20        | 13.89%  |
| NomadBSD    | 15        | 10.42%  |
| OPNsense    | 14        | 9.72%   |
| GhostBSD    | 9         | 6.25%   |
| NetBSD      | 1         | 0.69%   |
| FuryBSD     | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 129       | 96.99%  |
| i386   | 3         | 2.26%   |
| macppc | 1         | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 27        | 18.24%  |
| XFCE         | 22        | 14.86%  |
| Console      | 18        | 12.16%  |
| KDE5         | 16        | 10.81%  |
| fvwm         | 15        | 10.14%  |
| Openbox      | 13        | 8.78%   |
| MATE         | 10        | 6.76%   |
| GNOME        | 8         | 5.41%   |
| TWM          | 7         | 4.73%   |
| i3           | 4         | 2.7%    |
| xinitrc      | 3         | 2.03%   |
| AwesomeWM    | 2         | 1.35%   |
| X-Cinnamon   | 1         | 0.68%   |
| sway         | 1         | 0.68%   |
| LXDE         | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 114       | 84.44%  |
| Console | 20        | 14.81%  |
| Wayland | 1         | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 53        | 37.59%  |
| SLiM    | 46        | 32.62%  |
| SDDM    | 17        | 12.06%  |
| LightDM | 13        | 9.22%   |
| XDM     | 7         | 4.96%   |
| GDM     | 5         | 3.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 45        | 31.47%  |
| fr_FR           | 36        | 25.17%  |
| en_US           | 29        | 20.28%  |
| C               | 24        | 16.78%  |
| de_DE           | 3         | 2.1%    |
| fr              | 2         | 1.4%    |
| en_GB           | 2         | 1.4%    |
| en_US.ISO8859-1 | 1         | 0.7%    |
| en              | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 105       | 78.36%  |
| BIOS | 29        | 21.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 75        | 53.96%  |
| Ufs    | 36        | 25.9%   |
| Ffs    | 21        | 15.11%  |
| Cd9660 | 7         | 5.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 109       | 80.74%  |
| MBR     | 24        | 17.78%  |
| BSD     | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 41        | 30.83%  |
| Dell                | 24        | 18.05%  |
| ASUSTek Computer    | 13        | 9.77%   |
| Hewlett-Packard     | 9         | 6.77%   |
| Intel               | 5         | 3.76%   |
| Deciso              | 5         | 3.76%   |
| Apple               | 5         | 3.76%   |
| Acer                | 4         | 3.01%   |
| TUXEDO              | 3         | 2.26%   |
| Toshiba             | 3         | 2.26%   |
| Sony                | 2         | 1.5%    |
| Notebook            | 2         | 1.5%    |
| MSI                 | 2         | 1.5%    |
| Fujitsu             | 2         | 1.5%    |
| Alienware           | 2         | 1.5%    |
| Unknown             | 2         | 1.5%    |
| SECO                | 1         | 0.75%   |
| Samsung Electronics | 1         | 0.75%   |
| Panasonic           | 1         | 0.75%   |
| Medion              | 1         | 0.75%   |
| Google              | 1         | 0.75%   |
| Gigabyte Technology | 1         | 0.75%   |
| Getac               | 1         | 0.75%   |
| Clevo               | 1         | 0.75%   |
| Chuwi               | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel H81U                               | 4         | 3.01%   |
| Dell Precision M4500                     | 3         | 2.26%   |
| Deciso Netboard A20                      | 3         | 2.26%   |
| TUXEDO InfinityBook13V3                  | 2         | 1.5%    |
| Toshiba PORTEGE Z930                     | 2         | 1.5%    |
| Dell Latitude 3410                       | 2         | 1.5%    |
| Deciso NetBoard-A20                      | 2         | 1.5%    |
| Unknown                                  | 2         | 1.5%    |
| TUXEDO Aura 15 Gen1                      | 1         | 0.75%   |
| Toshiba NB300                            | 1         | 0.75%   |
| Sony VGN-FZ19VN                          | 1         | 0.75%   |
| Sony VGN-AR630E                          | 1         | 0.75%   |
| SECO UDOO x86                            | 1         | 0.75%   |
| Samsung R720                             | 1         | 0.75%   |
| Panasonic CF-31-5                        | 1         | 0.75%   |
| Notebook W510LU                          | 1         | 0.75%   |
| Notebook N7x0WU                          | 1         | 0.75%   |
| MSI P65 Creator 8RE                      | 1         | 0.75%   |
| MSI MS-N033                              | 1         | 0.75%   |
| Medion E15415                            | 1         | 0.75%   |
| Lenovo ThinkPad X280 20KFCTO1WW          | 1         | 0.75%   |
| Lenovo ThinkPad X260 20F6006XUK          | 1         | 0.75%   |
| Lenovo ThinkPad X250 20CLS7WY04          | 1         | 0.75%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 0.75%   |
| Lenovo ThinkPad X230 2325AJ9             | 1         | 0.75%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.75%   |
| Lenovo ThinkPad X220 4290EE8             | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1TG00 | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2K000 | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS003LFR | 1         | 0.75%   |
| Lenovo ThinkPad W540 20BG001KUK          | 1         | 0.75%   |
| Lenovo ThinkPad T60 1951CZ1              | 1         | 0.75%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.75%   |
| Lenovo ThinkPad T580 20LAS2TG00          | 1         | 0.75%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 0.75%   |
| Lenovo ThinkPad T495 20NKS0HN1N          | 1         | 0.75%   |
| Lenovo ThinkPad T495 20NJCTO1WW          | 1         | 0.75%   |
| Lenovo ThinkPad T490 20N20009FR          | 1         | 0.75%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 36        | 27.07%  |
| Dell Latitude           | 13        | 9.77%   |
| Dell Precision          | 6         | 4.51%   |
| Intel H81U              | 4         | 3.01%   |
| HP EliteBook            | 4         | 3.01%   |
| Deciso Netboard         | 3         | 2.26%   |
| Acer Aspire             | 3         | 2.26%   |
| TUXEDO InfinityBook13V3 | 2         | 1.5%    |
| Toshiba PORTEGE         | 2         | 1.5%    |
| Lenovo Legion           | 2         | 1.5%    |
| Dell Inspiron           | 2         | 1.5%    |
| Deciso NetBoard-A20     | 2         | 1.5%    |
| Unknown                 | 2         | 1.5%    |
| TUXEDO Aura             | 1         | 0.75%   |
| Toshiba NB300           | 1         | 0.75%   |
| Sony VGN-FZ19VN         | 1         | 0.75%   |
| Sony VGN-AR630E         | 1         | 0.75%   |
| SECO UDOO               | 1         | 0.75%   |
| Samsung R720            | 1         | 0.75%   |
| Panasonic CF-31-5       | 1         | 0.75%   |
| Notebook W510LU         | 1         | 0.75%   |
| Notebook N7x0WU         | 1         | 0.75%   |
| MSI P65                 | 1         | 0.75%   |
| MSI MS-N033             | 1         | 0.75%   |
| Medion E15415           | 1         | 0.75%   |
| Lenovo IdeaPad          | 1         | 0.75%   |
| Lenovo G500             | 1         | 0.75%   |
| Lenovo Flex             | 1         | 0.75%   |
| Intel Jasper            | 1         | 0.75%   |
| HP ZBook                | 1         | 0.75%   |
| HP Stream               | 1         | 0.75%   |
| HP ProBook              | 1         | 0.75%   |
| HP Pavilion             | 1         | 0.75%   |
| HP Compaq               | 1         | 0.75%   |
| Google Terra            | 1         | 0.75%   |
| Gigabyte P15FR7         | 1         | 0.75%   |
| Getac V110G2            | 1         | 0.75%   |
| Fujitsu LIFEBOOK        | 1         | 0.75%   |
| Fujitsu CELSIUS         | 1         | 0.75%   |
| Dell Vostro             | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 19        | 14.29%  |
| 2020    | 15        | 11.28%  |
| 2013    | 11        | 8.27%   |
| 2022    | 10        | 7.52%   |
| 2015    | 10        | 7.52%   |
| 2021    | 9         | 6.77%   |
| 2018    | 9         | 6.77%   |
| 2011    | 9         | 6.77%   |
| 2010    | 8         | 6.02%   |
| 2016    | 7         | 5.26%   |
| 2014    | 7         | 5.26%   |
| 2017    | 4         | 3.01%   |
| 2012    | 3         | 2.26%   |
| 2009    | 3         | 2.26%   |
| 2008    | 3         | 2.26%   |
| 2023    | 2         | 1.5%    |
| 2007    | 2         | 1.5%    |
| 2006    | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 133       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 98.5%   |
| Yes  | 2         | 1.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 45        | 33.33%  |
| 16.01-24.0  | 35        | 25.93%  |
| 4.01-8.0    | 23        | 17.04%  |
| 32.01-64.0  | 10        | 7.41%   |
| 2.01-3.0    | 9         | 6.67%   |
| 3.01-4.0    | 4         | 2.96%   |
| 64.01-256.0 | 4         | 2.96%   |
| 24.01-32.0  | 3         | 2.22%   |
| 1.01-2.0    | 2         | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 76        | 54.29%  |
| 0.51-1.0   | 39        | 27.86%  |
| 1.01-2.0   | 13        | 9.29%   |
| 2.01-3.0   | 6         | 4.29%   |
| 8.01-16.0  | 4         | 2.86%   |
| 32.01-64.0 | 1         | 0.71%   |
| Unknown    | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 87        | 64.44%  |
| 2      | 28        | 20.74%  |
| 0      | 13        | 9.63%   |
| 3      | 5         | 3.7%    |
| 4      | 2         | 1.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 75%     |
| Yes       | 34        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 87.31%  |
| No        | 17        | 12.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 90.23%  |
| No        | 13        | 9.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 58.09%  |
| No        | 57        | 41.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 133       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Paris                    | 23        | 15.13%  |
| Franconville             | 7         | 4.61%   |
| Bordeaux                 | 6         | 3.95%   |
| Melun                    | 4         | 2.63%   |
| Marcq-en-Baroeul         | 3         | 1.97%   |
| Fontenay-sous-Bois       | 3         | 1.97%   |
| Carry-le-Rouet           | 3         | 1.97%   |
| Urcuit                   | 2         | 1.32%   |
| Stiring-Wendel           | 2         | 1.32%   |
| Saint-Raphaël           | 2         | 1.32%   |
| Saint-Germain-en-Laye    | 2         | 1.32%   |
| Saint-Denis              | 2         | 1.32%   |
| Rosny-sous-Bois          | 2         | 1.32%   |
| Rennes                   | 2         | 1.32%   |
| Noisy-le-Grand           | 2         | 1.32%   |
| Mâcon                   | 2         | 1.32%   |
| Dijon                    | 2         | 1.32%   |
| Colombes                 | 2         | 1.32%   |
| Colmar                   | 2         | 1.32%   |
| Asnieres-sur-Seine       | 2         | 1.32%   |
| Villeneuve-Saint-Georges | 1         | 0.66%   |
| Villemomble              | 1         | 0.66%   |
| Villejuif                | 1         | 0.66%   |
| Villefontaine            | 1         | 0.66%   |
| Vertou                   | 1         | 0.66%   |
| Tulle                    | 1         | 0.66%   |
| Tournon-sur-RhÃ´ne     | 1         | 0.66%   |
| Toulouse                 | 1         | 0.66%   |
| St-Malo                  | 1         | 0.66%   |
| Soisy-sur-Seine          | 1         | 0.66%   |
| Sartrouville             | 1         | 0.66%   |
| Sarcelles                | 1         | 0.66%   |
| Samatan                  | 1         | 0.66%   |
| Sallanches               | 1         | 0.66%   |
| Saint-Saulge             | 1         | 0.66%   |
| Saint-Martin-d'Hères    | 1         | 0.66%   |
| Saint-Herblain           | 1         | 0.66%   |
| Saint-Genest-Lerpt       | 1         | 0.66%   |
| Roubaix                  | 1         | 0.66%   |
| Quimper                  | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 37     | 17.11%  |
| Crucial             | 15        | 19     | 9.87%   |
| Seagate             | 14        | 26     | 9.21%   |
| Toshiba             | 13        | 19     | 8.55%   |
| WDC                 | 10        | 14     | 6.58%   |
| Kingston            | 10        | 12     | 6.58%   |
| Transcend           | 9         | 15     | 5.92%   |
| SanDisk             | 9         | 11     | 5.92%   |
| China               | 7         | 7      | 4.61%   |
| Micron Technology   | 6         | 10     | 3.95%   |
| Intel               | 6         | 9      | 3.95%   |
| NVMe                | 5         | 5      | 3.29%   |
| HGST                | 5         | 8      | 3.29%   |
| SK hynix            | 3         | 3      | 1.97%   |
| Fujitsu             | 3         | 3      | 1.97%   |
| Phison              | 2         | 2      | 1.32%   |
| SPCC                | 1         | 1      | 0.66%   |
| Lexar               | 1         | 2      | 0.66%   |
| LDLC F6+            | 1         | 1      | 0.66%   |
| Integral            | 1         | 1      | 0.66%   |
| Hitachi             | 1         | 1      | 0.66%   |
| Generic             | 1         | 1      | 0.66%   |
| EMTEC               | 1         | 1      | 0.66%   |
| BHT                 | 1         | 1      | 0.66%   |
| AirDisk             | 1         | 1      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 5         | 3.21%   |
| China MSATA 32GB SSD                 | 4         | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.92%   |
| Kingston SA400S37240G 240GB          | 3         | 1.92%   |
| Crucial CT1000P1SSD8 1TB             | 3         | 1.92%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 2         | 1.28%   |
| Transcend TS256GMTS430S 256GB        | 2         | 1.28%   |
| Toshiba MK2556GSY 250GB              | 2         | 1.28%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB  | 2         | 1.28%   |
| Samsung SSD 970 EVO Plus 2TB         | 2         | 1.28%   |
| Samsung SSD 950 PRO 512GB            | 2         | 1.28%   |
| NVMe WDC PC SN720 SDA 512GB          | 2         | 1.28%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 1.28%   |
| HGST HTS725050A7E630 500GB           | 2         | 1.28%   |
| HGST HTS721010A9E630 1TB             | 2         | 1.28%   |
| Crucial CT960M500SSD1 960GB          | 2         | 1.28%   |
| Crucial CT1050MX300SSD1 1TB          | 2         | 1.28%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.28%   |
| China SH00M240GB                     | 2         | 1.28%   |
| WDC WDS240G2G0B-00EPW0 240GB         | 1         | 0.64%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.64%   |
| WDC WD3200BEVT-75ZCT2 320GB          | 1         | 0.64%   |
| WDC WD20SDRW-11VUUS0 2TB             | 1         | 0.64%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.64%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.64%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB | 1         | 0.64%   |
| Transcend TS256GMTS800 256GB         | 1         | 0.64%   |
| Transcend TS128GMTS400 128GB         | 1         | 0.64%   |
| Toshiba THNSNJ256GCSY 256GB          | 1         | 0.64%   |
| Toshiba THNSNF128GMCS 128GB          | 1         | 0.64%   |
| Toshiba THNSN51T02DUK NVMe 1024GB    | 1         | 0.64%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.64%   |
| Toshiba MQ01ACF032 320GB             | 1         | 0.64%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.64%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.64%   |
| Toshiba MK2555GSX 250GB              | 1         | 0.64%   |
| Toshiba MK2546GSX_200 200GB          | 1         | 0.64%   |
| Toshiba MK1629GSGF 160GB             | 1         | 0.64%   |
| SPCC Solid State Disk 512GB          | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 26     | 30.43%  |
| Toshiba             | 8         | 11     | 17.39%  |
| WDC                 | 6         | 7      | 13.04%  |
| NVMe                | 5         | 5      | 10.87%  |
| HGST                | 5         | 8      | 10.87%  |
| Fujitsu             | 3         | 3      | 6.52%   |
| Samsung Electronics | 1         | 1      | 2.17%   |
| Lexar               | 1         | 2      | 2.17%   |
| LDLC F6+            | 1         | 1      | 2.17%   |
| Hitachi             | 1         | 1      | 2.17%   |
| Generic             | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 20     | 20%     |
| Crucial             | 10        | 10     | 14.29%  |
| Transcend           | 9         | 15     | 12.86%  |
| SanDisk             | 9         | 11     | 12.86%  |
| Kingston            | 8         | 9      | 11.43%  |
| China               | 7         | 7      | 10%     |
| Toshiba             | 4         | 6      | 5.71%   |
| WDC                 | 2         | 3      | 2.86%   |
| Micron Technology   | 2         | 6      | 2.86%   |
| SPCC                | 1         | 1      | 1.43%   |
| Intel               | 1         | 1      | 1.43%   |
| Integral            | 1         | 1      | 1.43%   |
| EMTEC               | 1         | 1      | 1.43%   |
| BHT                 | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 62        | 92     | 44.93%  |
| HDD  | 43        | 66     | 31.16%  |
| NVMe | 33        | 52     | 23.91%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 158    | 74.81%  |
| NVMe | 33        | 52     | 25.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 112    | 68.18%  |
| 0.51-1.0   | 30        | 40     | 27.27%  |
| 1.01-2.0   | 5         | 6      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 46        | 32.62%  |
| 1-20       | 27        | 19.15%  |
| 251-500    | 24        | 17.02%  |
| 21-50      | 18        | 12.77%  |
| 501-1000   | 14        | 9.93%   |
| 51-100     | 9         | 6.38%   |
| 1001-2000  | 2         | 1.42%   |
| Unknown    | 1         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 111       | 82.22%  |
| 21-50    | 11        | 8.15%   |
| 101-250  | 8         | 5.93%   |
| 51-100   | 3         | 2.22%   |
| 501-1000 | 1         | 0.74%   |
| Unknown  | 1         | 0.74%   |

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
| Works    | 106       | 178    | 84.13%  |
| Malfunc  | 15        | 26     | 11.9%   |
| Detected | 5         | 6      | 3.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 99        | 66.44%  |
| Samsung Electronics         | 13        | 8.72%   |
| AMD                         | 13        | 8.72%   |
| Micron/Crucial Technology   | 5         | 3.36%   |
| SanDisk                     | 4         | 2.68%   |
| Micron Technology           | 4         | 2.68%   |
| SK hynix                    | 3         | 2.01%   |
| Phison Electronics          | 2         | 1.34%   |
| Kingston Technology Company | 2         | 1.34%   |
| Toshiba                     | 1         | 0.67%   |
| Nvidia                      | 1         | 0.67%   |
| MAXIO Technology (Hangzhou) | 1         | 0.67%   |
| KIOXIA                      | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 8.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 7.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 5.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 4.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.5%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.88%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                        | 3         | 1.88%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 3         | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.88%   |
| Intel Comet Lake RAID Controller                                                 | 3         | 1.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.88%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.25%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 1.25%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.25%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 1.25%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 2         | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.25%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.63%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 1         | 0.63%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.63%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                              | 1         | 0.63%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.63%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 0.63%   |
| Micron 2300 NVMe SSD [Santana]                                                   | 1         | 0.63%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 62.5%   |
| NVMe | 37        | 24.34%  |
| RAID | 11        | 7.24%   |
| IDE  | 9         | 5.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 114       | 85.07%  |
| AMD     | 19        | 14.18%  |
| PowerPC | 1         | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz    | 5         | 3.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 4         | 2.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 4         | 2.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 3         | 2.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 3         | 2.24%   |
| Intel Core i5 CPU M 560 @ 2.67GH     | 3         | 2.24%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 3         | 2.24%   |
| AMD EPYC 3101 4-Core Processor       | 3         | 2.24%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 2         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 1.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 2         | 1.49%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 2         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 1.49%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 1.49%   |
| Intel Core i5-3437U CPU @ 1.90GHz    | 2         | 1.49%   |
| Intel Core i3-4025U CPU @ 1.90GHz    | 2         | 1.49%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 2         | 1.49%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 1.49%   |
| Intel Celeron CPU N3160 @ 1.60GHz    | 2         | 1.49%   |
| AMD EPYC 3201 8-Core Processor       | 2         | 1.49%   |
| PowerPC 7447A (Revision 0x105)       | 1         | 0.75%   |
| Intel Pentium M                      | 1         | 0.75%   |
| Intel CPU Version                    | 1         | 0.75%   |
| Intel Core M-5Y10c CPU @ 0.80GHz     | 1         | 0.75%   |
| Intel Core i7-9850H CPU @ 2.60GHz    | 1         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 0.75%   |
| Intel Core i7-8665U CPU @ 1.90GHz    | 1         | 0.75%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz   | 1         | 0.75%   |
| Intel Core i7-7820HK CPU @ 2.90GHz   | 1         | 0.75%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 1         | 0.75%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 1         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 1         | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 1         | 0.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz    | 1         | 0.75%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz   | 1         | 0.75%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz   | 1         | 0.75%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz   | 1         | 0.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 42        | 31.34%  |
| Intel Core i7    | 33        | 24.63%  |
| Intel Core i3    | 12        | 8.96%   |
| Intel Core 2 Duo | 9         | 6.72%   |
| Intel Celeron    | 7         | 5.22%   |
| Other            | 6         | 4.48%   |
| AMD EPYC         | 5         | 3.73%   |
| AMD Ryzen 7 PRO  | 4         | 2.99%   |
| AMD Ryzen 7      | 4         | 2.99%   |
| Intel Atom       | 3         | 2.24%   |
| AMD A4           | 2         | 1.49%   |
| Intel Pentium M  | 1         | 0.75%   |
| Intel Core M     | 1         | 0.75%   |
| Intel Core 2     | 1         | 0.75%   |
| AMD Ryzen 5 PRO  | 1         | 0.75%   |
| AMD Ryzen 5      | 1         | 0.75%   |
| AMD E1           | 1         | 0.75%   |
| AMD A6           | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 59        | 44.03%  |
| 4       | 46        | 34.33%  |
| Unknown | 10        | 7.46%   |
| 8       | 9         | 6.72%   |
| 16      | 4         | 2.99%   |
| 12      | 2         | 1.49%   |
| 6       | 2         | 1.49%   |
| 1       | 2         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 127       | 95.49%  |
| Unknown | 4         | 3.01%   |
| 2       | 2         | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 90        | 67.16%  |
| 1       | 33        | 24.63%  |
| Unknown | 11        | 8.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 33        | 24.63%  |
| Haswell       | 16        | 11.94%  |
| IvyBridge     | 12        | 8.96%   |
| SandyBridge   | 9         | 6.72%   |
| Penryn        | 8         | 5.97%   |
| Broadwell     | 8         | 5.97%   |
| Skylake       | 7         | 5.22%   |
| Unknown       | 7         | 5.22%   |
| Zen           | 6         | 4.48%   |
| Westmere      | 5         | 3.73%   |
| Silvermont    | 4         | 2.99%   |
| Zen+          | 3         | 2.24%   |
| Zen 2         | 3         | 2.24%   |
| Core          | 3         | 2.24%   |
| Bonnell       | 3         | 2.24%   |
| Jaguar        | 2         | 1.49%   |
| Zen 3         | 1         | 0.75%   |
| P6            | 1         | 0.75%   |
| K10 Llano     | 1         | 0.75%   |
| Goldmont plus | 1         | 0.75%   |
| Excavator     | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 100       | 66.23%  |
| Nvidia | 30        | 19.87%  |
| AMD    | 21        | 13.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 7.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 6.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 4.46%   |
| Intel HD Graphics 5500                                                                   | 7         | 4.46%   |
| Intel HD Graphics 620                                                                    | 6         | 3.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 3.82%   |
| Intel UHD Graphics 620                                                                   | 5         | 3.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.55%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 1.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.91%   |
| Intel HD Graphics 630                                                                    | 3         | 1.91%   |
| Intel HD Graphics 530                                                                    | 3         | 1.91%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.27%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.27%   |
| AMD Lucienne                                                                             | 2         | 1.27%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.64%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.64%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.64%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.64%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                                    | 1         | 0.64%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                                 | 1         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.64%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.64%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.64%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 70        | 52.24%  |
| Intel + Nvidia           | 18        | 13.43%  |
| 1 x AMD                  | 17        | 12.69%  |
| 2 x Intel                | 10        | 7.46%   |
| 1 x Nvidia               | 10        | 7.46%   |
| Other                    | 5         | 3.73%   |
| 2 x AMD                  | 1         | 0.75%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.75%   |
| Intel + AMD              | 1         | 0.75%   |
| AMD + Nvidia             | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 117       | 86.67%  |
| Proprietary | 10        | 7.41%   |
| Unknown     | 8         | 5.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 119       | 88.81%  |
| 0.51-1.0   | 5         | 3.73%   |
| 0.01-0.5   | 4         | 2.99%   |
| 5.01-6.0   | 2         | 1.49%   |
| 7.01-8.0   | 1         | 0.75%   |
| 3.01-4.0   | 1         | 0.75%   |
| 1.01-2.0   | 1         | 0.75%   |
| 8.01-16.0  | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 20%     |
| LG Display              | 15        | 15%     |
| Chimei Innolux          | 15        | 15%     |
| BOE                     | 10        | 10%     |
| Samsung Electronics     | 8         | 8%      |
| Apple                   | 5         | 5%      |
| Chi Mei Optoelectronics | 4         | 4%      |
| Philips                 | 3         | 3%      |
| Lenovo                  | 3         | 3%      |
| ViewSonic               | 2         | 2%      |
| LGD                     | 2         | 2%      |
| Iiyama                  | 2         | 2%      |
| Goldstar                | 2         | 2%      |
| Sharp                   | 1         | 1%      |
| Nvidia                  | 1         | 1%      |
| IBM                     | 1         | 1%      |
| Hewlett-Packard         | 1         | 1%      |
| Dell                    | 1         | 1%      |
| CSO                     | 1         | 1%      |
| CPT                     | 1         | 1%      |
| ASUSTek Computer        | 1         | 1%      |
| Acer                    | 1         | 1%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 3%      |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 2%      |
| LGD LCD Monitor 1600x900                                                 | 2         | 2%      |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 2%      |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2%      |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 2%      |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 2%      |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 2%      |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 2%      |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 1%      |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch            | 1         | 1%      |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC3659 1600x900 340x190mm 15.3-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch     | 1         | 1%      |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1%      |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 1%      |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 1%      |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 1%      |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD04F9 1920x1080 310x170mm 13.9-inch             | 1         | 1%      |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD036C 1366x768 280x160mm 12.7-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD0366 1600x900 310x170mm 13.9-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1%      |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch              | 1         | 1%      |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1%      |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1%      |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch                 | 1         | 1%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 42        | 44.21%  |
| 1366x768 (WXGA)    | 28        | 29.47%  |
| 1600x900 (HD+)     | 6         | 6.32%   |
| 3840x2160 (4K)     | 4         | 4.21%   |
| 1280x800 (WXGA)    | 4         | 4.21%   |
| 2560x1440 (QHD)    | 3         | 3.16%   |
| 1440x900 (WXGA+)   | 2         | 2.11%   |
| 1024x600           | 2         | 2.11%   |
| 2880x1800          | 1         | 1.05%   |
| 1680x1050 (WSXGA+) | 1         | 1.05%   |
| 1440x960           | 1         | 1.05%   |
| 1400x1050          | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 29        | 29%     |
| 13      | 26        | 26%     |
| 12      | 13        | 13%     |
| 17      | 5         | 5%      |
| 24      | 4         | 4%      |
| 23      | 4         | 4%      |
| Unknown | 4         | 4%      |
| 27      | 3         | 3%      |
| 14      | 3         | 3%      |
| 10      | 3         | 3%      |
| 21      | 2         | 2%      |
| 11      | 2         | 2%      |
| 42      | 1         | 1%      |
| 18      | 1         | 1%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 51%     |
| 201-300     | 25        | 25%     |
| 501-600     | 10        | 10%     |
| 351-400     | 5         | 5%      |
| Unknown     | 4         | 4%      |
| 401-500     | 3         | 3%      |
| 601-700     | 1         | 1%      |
| 901-1000    | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 84.09%  |
| 16/10   | 7         | 7.95%   |
| Unknown | 4         | 4.55%   |
| 3/2     | 2         | 2.27%   |
| 4/3     | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 27        | 27%     |
| 91-100         | 26        | 26%     |
| 61-70          | 13        | 13%     |
| 201-250        | 10        | 10%     |
| 121-130        | 5         | 5%      |
| 101-110        | 4         | 4%      |
| Unknown        | 4         | 4%      |
| 41-50          | 3         | 3%      |
| 301-350        | 3         | 3%      |
| 51-60          | 2         | 2%      |
| 71-80          | 1         | 1%      |
| 141-150        | 1         | 1%      |
| 501-1000       | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 45        | 45.92%  |
| 101-120       | 29        | 29.59%  |
| 51-100        | 11        | 11.22%  |
| 161-240       | 6         | 6.12%   |
| Unknown       | 4         | 4.08%   |
| More than 240 | 3         | 3.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 92        | 66.19%  |
| 0     | 34        | 24.46%  |
| 2     | 13        | 9.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 96        | 46.6%   |
| Realtek Semiconductor    | 46        | 22.33%  |
| Qualcomm Atheros         | 23        | 11.17%  |
| Broadcom                 | 11        | 5.34%   |
| AMD                      | 5         | 2.43%   |
| Marvell Technology Group | 4         | 1.94%   |
| TP-Link                  | 3         | 1.46%   |
| Sierra Wireless          | 3         | 1.46%   |
| Xiaomi                   | 2         | 0.97%   |
| Edimax Technology        | 2         | 0.97%   |
| Apple                    | 2         | 0.97%   |
| Sagem                    | 1         | 0.49%   |
| Ralink Technology        | 1         | 0.49%   |
| Ralink                   | 1         | 0.49%   |
| Qualcomm                 | 1         | 0.49%   |
| Nvidia                   | 1         | 0.49%   |
| MediaTek                 | 1         | 0.49%   |
| Huawei Technologies      | 1         | 0.49%   |
| Hewlett-Packard          | 1         | 0.49%   |
| Dell                     | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 13.16%  |
| Intel Wireless 8265 / 8275                                        | 11        | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 4.14%   |
| Intel Wireless 7265                                               | 10        | 3.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 3.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.26%   |
| Intel Wireless 8260                                               | 6         | 2.26%   |
| Intel Wireless 7260                                               | 6         | 2.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 2.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 1.88%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.88%   |
| Intel I210 Gigabit Network Connection                             | 5         | 1.88%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.88%   |
| AMD XGMAC 10GbE Controller                                        | 5         | 1.88%   |
| Intel Wireless-AC 9260                                            | 4         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.5%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 1.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.13%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.13%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.75%   |
| Sierra Wireless EM7305 Modem                                      | 2         | 0.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.75%   |
| Intel Wireless 3165                                               | 2         | 0.75%   |
| Intel WiFi Link 5100                                              | 2         | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 88        | 65.67%  |
| Qualcomm Atheros      | 20        | 14.93%  |
| Broadcom              | 8         | 5.97%   |
| Realtek Semiconductor | 7         | 5.22%   |
| TP-Link               | 3         | 2.24%   |
| Edimax Technology     | 2         | 1.49%   |
| Sierra Wireless       | 1         | 0.75%   |
| Sagem                 | 1         | 0.75%   |
| Ralink Technology     | 1         | 0.75%   |
| Ralink                | 1         | 0.75%   |
| MediaTek              | 1         | 0.75%   |
| Dell                  | 1         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 11        | 8.15%   |
| Intel Wireless 7265                                                     | 10        | 7.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 5.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.44%   |
| Intel Wireless 8260                                                     | 6         | 4.44%   |
| Intel Wireless 7260                                                     | 6         | 4.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 4.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 4.44%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.7%    |
| Intel Wireless-AC 9260                                                  | 4         | 2.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 2.22%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.22%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.48%   |
| Intel Wireless 3165                                                     | 2         | 1.48%   |
| Intel WiFi Link 5100                                                    | 2         | 1.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.48%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.48%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.74%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.74%   |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.74%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 1         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.74%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 59        | 47.2%   |
| Realtek Semiconductor    | 41        | 32.8%   |
| Qualcomm Atheros         | 7         | 5.6%    |
| AMD                      | 5         | 4%      |
| Marvell Technology Group | 4         | 3.2%    |
| Broadcom                 | 4         | 3.2%    |
| Xiaomi                   | 2         | 1.6%    |
| Qualcomm                 | 1         | 0.8%    |
| Nvidia                   | 1         | 0.8%    |
| Apple                    | 1         | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 28%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 8.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 4.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4%      |
| Intel I210 Gigabit Network Connection                             | 5         | 4%      |
| Intel Ethernet Connection (4) I219-V                              | 5         | 4%      |
| AMD XGMAC 10GbE Controller                                        | 5         | 4%      |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.2%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2.4%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.6%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.8%    |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.8%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.8%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.8%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.8%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.8%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.8%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.8%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.8%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.8%    |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.8%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.8%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.8%    |
| Intel 82583V Gigabit Network Connection                           | 1         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.8%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.8%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 49.38%  |
| Ethernet | 117       | 48.15%  |
| Modem    | 3         | 1.23%   |
| Unknown  | 3         | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 88        | 50.29%  |
| WiFi     | 87        | 49.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 102       | 76.12%  |
| 1     | 19        | 14.18%  |
| 6     | 6         | 4.48%   |
| 3     | 6         | 4.48%   |
| 0     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 84.89%  |
| Yes  | 21        | 15.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 70.37%  |
| Broadcom                        | 7         | 8.64%   |
| Realtek Semiconductor           | 3         | 3.7%    |
| Foxconn / Hon Hai               | 3         | 3.7%    |
| Apple                           | 3         | 3.7%    |
| Qualcomm Atheros Communications | 2         | 2.47%   |
| IMC Networks                    | 2         | 2.47%   |
| Dell                            | 2         | 2.47%   |
| Hewlett-Packard                 | 1         | 1.23%   |
| Creative Technology             | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 26        | 32.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 10        | 12.35%  |
| Intel AX201 Bluetooth                              | 7         | 8.64%   |
| Intel AX200 Bluetooth                              | 5         | 6.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 3         | 3.7%    |
| Realtek Bluetooth Adapter                          | 2         | 2.47%   |
| Intel Wireless-AC 3168 Bluetooth                   | 2         | 2.47%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 2.47%   |
| Intel AX210 Bluetooth                              | 2         | 2.47%   |
| Foxconn / Hon Hai Bluetooth USB Module             | 2         | 2.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 2.47%   |
| Broadcom BCM2045B (BDC-2.1)                        | 2         | 2.47%   |
| Apple Bluetooth Host Controller                    | 2         | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                     | 1         | 1.23%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1             | 1         | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 1         | 1.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1        | 1         | 1.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS   | 1         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]      | 1         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Adapter                | 1         | 1.23%   |
| Dell DW375 Bluetooth Module                        | 1         | 1.23%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module        | 1         | 1.23%   |
| Creative Creative Bluetooth Audio W2               | 1         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth Module               | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]   | 1         | 1.23%   |
| Apple Built-in iSight (no firmware loaded)         | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 111       | 70.7%   |
| AMD                 | 24        | 15.29%  |
| Nvidia              | 13        | 8.28%   |
| Logitech            | 2         | 1.27%   |
| Lenovo              | 2         | 1.27%   |
| Texas Instruments   | 1         | 0.64%   |
| Kingston Technology | 1         | 0.64%   |
| GN Netcom           | 1         | 0.64%   |
| DSEA A/S            | 1         | 0.64%   |
| ASUSTek Computer    | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 8.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 6.19%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 6.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 4.12%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 4.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.61%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.58%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 2.58%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.55%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.55%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.55%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.03%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.03%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.03%   |
| Texas Instruments PCM2706 stereo audio DAC                                                        | 1         | 0.52%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.52%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.52%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.52%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.52%   |
| Logitech Logitech Stereo H650e                                                                    | 1         | 0.52%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.52%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.29%  |
| SK hynix            | 29        | 20.71%  |
| Unknown             | 12        | 8.57%   |
| Micron Technology   | 12        | 8.57%   |
| Crucial             | 10        | 7.14%   |
| Kingston            | 9         | 6.43%   |
| Transcend           | 4         | 2.86%   |
| Nanya Technology    | 3         | 2.14%   |
| Elpida              | 3         | 2.14%   |
| Corsair             | 3         | 2.14%   |
| Unknown             | 3         | 2.14%   |
| G.Skill             | 2         | 1.43%   |
| A-DATA Technology   | 2         | 1.43%   |
| V-Color             | 1         | 0.71%   |
| Unknown (ABCD)      | 1         | 0.71%   |
| SHARETRONIC         | 1         | 0.71%   |
| Ramaxel Technology  | 1         | 0.71%   |
| Patriot             | 1         | 0.71%   |
| CSX                 | 1         | 0.71%   |
| Avant               | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 2.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.63%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s              | 3         | 1.97%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 1.97%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 3         | 1.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.97%   |
| Unknown                                                          | 3         | 1.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.32%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.32%   |
| Samsung RAM M471B5773CHS-CK0 2GB DDR3 1600MT/s                   | 2         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.32%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s           | 2         | 1.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 2         | 1.32%   |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s         | 2         | 1.32%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.32%   |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s       | 2         | 1.32%   |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s           | 1         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM 533MT/s                            | 1         | 0.66%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.66%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.66%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 1         | 0.66%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 42.11%  |
| DDR4    | 46        | 40.35%  |
| DDR2    | 9         | 7.89%   |
| LPDDR3  | 6         | 5.26%   |
| Unknown | 2         | 1.75%   |
| LPDDR5  | 1         | 0.88%   |
| LPDDR4  | 1         | 0.88%   |
| DDR5    | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 108       | 91.53%  |
| Row Of Chips | 4         | 3.39%   |
| Chip         | 3         | 2.54%   |
| Unknown      | 3         | 2.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 42        | 33.07%  |
| 8192  | 41        | 32.28%  |
| 16384 | 19        | 14.96%  |
| 2048  | 19        | 14.96%  |
| 32768 | 3         | 2.36%   |
| 1024  | 3         | 2.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 27.64%  |
| 2667    | 18        | 14.63%  |
| 2400    | 13        | 10.57%  |
| 3200    | 12        | 9.76%   |
| 1333    | 11        | 8.94%   |
| 1334    | 9         | 7.32%   |
| 2133    | 7         | 5.69%   |
| 1867    | 4         | 3.25%   |
| Unknown | 4         | 3.25%   |
| 667     | 3         | 2.44%   |
| 800     | 2         | 1.63%   |
| 6400    | 1         | 0.81%   |
| 4800    | 1         | 0.81%   |
| 1200    | 1         | 0.81%   |
| 1067    | 1         | 0.81%   |
| 975     | 1         | 0.81%   |
| 533     | 1         | 0.81%   |

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
| Chicony Electronics                    | 32        | 34.78%  |
| Bison Electronics                      | 10        | 10.87%  |
| Sunplus Innovation Technology          | 9         | 9.78%   |
| Microdia                               | 8         | 8.7%    |
| Realtek Semiconductor                  | 6         | 6.52%   |
| IMC Networks                           | 6         | 6.52%   |
| Lite-On Technology                     | 4         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.35%   |
| Syntek                                 | 3         | 3.26%   |
| Quanta                                 | 3         | 3.26%   |
| Suyin                                  | 2         | 2.17%   |
| Alcor Micro                            | 2         | 2.17%   |
| SIMPLO Technology                      | 1         | 1.09%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.09%   |
| Apple                                  | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 11        | 11.83%  |
| Bison Integrated Camera                               | 7         | 7.53%   |
| Realtek Integrated_Webcam_HD                          | 3         | 3.23%   |
| Microdia Integrated_Webcam_HD                         | 3         | 3.23%   |
| Microdia Integrated Webcam                            | 3         | 3.23%   |
| Lite-On Integrated Camera                             | 3         | 3.23%   |
| Chicony HD WebCam                                     | 3         | 3.23%   |
| Syntek Integrated Camera                              | 2         | 2.15%   |
| Sunplus Integrated_Webcam_HD                          | 2         | 2.15%   |
| Sunplus hama C-600 Pro Webcam                         | 2         | 2.15%   |
| Realtek USB Camera                                    | 2         | 2.15%   |
| IMC Networks EasyCamera                               | 2         | 2.15%   |
| Chicony TOSHIBA Web Camera - HD                       | 2         | 2.15%   |
| Chicony Realtek DMFT RGB                              | 2         | 2.15%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam   | 2         | 2.15%   |
| Bison SunplusIT Integrated Camera                     | 2         | 2.15%   |
| Syntek Lenovo EasyCamera                              | 1         | 1.08%   |
| Suyin USB 2.0 Camera                                  | 1         | 1.08%   |
| Suyin Laptop_Integrated_Webcam_FHD                    | 1         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 1         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.08%   |
| Sunplus Integrated HD Webcam                          | 1         | 1.08%   |
| Sunplus Hy HD Camera                                  | 1         | 1.08%   |
| Sunplus Asus Webcam                                   | 1         | 1.08%   |
| SIMPLO USB 2.0 Camera                                 | 1         | 1.08%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 1.08%   |
| Realtek Integrated Webcam HD                          | 1         | 1.08%   |
| Quanta Realtek DMFT RGB                               | 1         | 1.08%   |
| Quanta Integrated Webcam                              | 1         | 1.08%   |
| Quanta HD WebCam                                      | 1         | 1.08%   |
| Microdia Integrated_Webcam_FHD                        | 1         | 1.08%   |
| Microdia Dell Integrated HD Webcam                    | 1         | 1.08%   |
| Lite-On Realtek DMFT RGB                              | 1         | 1.08%   |
| IMC Networks UVC VGA Webcam                           | 1         | 1.08%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 1         | 1.08%   |
| IMC Networks Realtek PC Camera                        | 1         | 1.08%   |
| IMC Networks Integrated Camera                        | 1         | 1.08%   |
| Chicony UVC 1.00 device HD UVC WebCam                 | 1         | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam                         | 1         | 1.08%   |
| Chicony USB2.0 HD UVC WebCam                          | 1         | 1.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 37.5%   |
| Synaptics                  | 7         | 21.88%  |
| AuthenTec                  | 5         | 15.63%  |
| Shenzhen Goodix Technology | 2         | 6.25%   |
| LighTuning Technology      | 2         | 6.25%   |
| Elan Microelectronics      | 2         | 6.25%   |
| Upek                       | 1         | 3.13%   |
| Broadcom                   | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 15.63%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 9.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 9.38%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 6.25%   |
| Elan Fingerprint Sensor                                                      | 2         | 6.25%   |
| AuthenTec AES2810                                                            | 2         | 6.25%   |
| AuthenTec AES1660                                                            | 2         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 3.13%   |
| Validity Sensors VFS491                                                      | 1         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 3.13%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 3.13%   |
| Synaptics UWP WBDI Device                                                    | 1         | 3.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 3.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.13%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 3.13%   |

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
| 1     | 44        | 30.56%  |
| 2     | 42        | 29.17%  |
| 3     | 22        | 15.28%  |
| 0     | 17        | 11.81%  |
| 4     | 12        | 8.33%   |
| 6     | 4         | 2.78%   |
| 5     | 2         | 1.39%   |
| 7     | 1         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 97        | 40.08%  |
| Bluetooth                | 39        | 16.12%  |
| Fingerprint reader       | 26        | 10.74%  |
| Card reader              | 25        | 10.33%  |
| Net/wireless             | 23        | 9.5%    |
| Firewire controller      | 14        | 5.79%   |
| Storage                  | 4         | 1.65%   |
| Sound                    | 4         | 1.65%   |
| Graphics card            | 4         | 1.65%   |
| Storage/raid             | 3         | 1.24%   |
| Network                  | 2         | 0.83%   |
| Net/ethernet             | 1         | 0.41%   |

