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

Total: 193

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenBSD 6.8         | 7         | 4.76%   |
| helloSystem 0.4.0   | 7         | 4.76%   |
| NomadBSD 1.3.2      | 6         | 4.08%   |
| helloSystem 0.7.0   | 6         | 4.08%   |
| FreeBSD 13.1        | 6         | 4.08%   |
| OpenBSD 7.0         | 5         | 3.4%    |
| GhostBSD 20.04.02   | 5         | 3.4%    |
| FreeBSD 13.1-p7     | 5         | 3.4%    |
| FreeBSD 13.0        | 5         | 3.4%    |
| OpenBSD 7.1         | 4         | 2.72%   |
| NomadBSD 20221130   | 4         | 2.72%   |
| NomadBSD 1.4        | 4         | 2.72%   |
| helloSystem 0.8.0   | 4         | 2.72%   |
| FreeBSD 12.2-p2     | 4         | 2.72%   |
| OpenBSD 6.9         | 3         | 2.04%   |
| FreeBSD 13.1-p3     | 3         | 2.04%   |
| FreeBSD 13.0-STABLE | 3         | 2.04%   |
| FreeBSD 12.2-p4     | 3         | 2.04%   |
| FreeBSD 12.2        | 3         | 2.04%   |
| OPNsense 22.7.6     | 2         | 1.36%   |
| OPNsense 22.10      | 2         | 1.36%   |
| OPNsense 22.1       | 2         | 1.36%   |
| OpenBSD 7.2         | 2         | 1.36%   |
| OpenBSD 6.7         | 2         | 1.36%   |
| helloSystem 0.8.1   | 2         | 1.36%   |
| GhostBSD 22.01.12   | 2         | 1.36%   |
| FreeBSD 13.1-STABLE | 2         | 1.36%   |
| FreeBSD 13.0-RC5    | 2         | 1.36%   |
| FreeBSD 13.0-p6     | 2         | 1.36%   |
| FreeBSD 13.0-p3     | 2         | 1.36%   |
| FreeBSD 13.0-p1     | 2         | 1.36%   |
| FreeBSD 12.1-p10    | 2         | 1.36%   |
| OPNsense 23.1.5     | 1         | 0.68%   |
| OPNsense 23.1.4     | 1         | 0.68%   |
| OPNsense 22.10.2    | 1         | 0.68%   |
| OPNsense 22.1.7     | 1         | 0.68%   |
| OPNsense 21.7.2     | 1         | 0.68%   |
| OPNsense 21.7.1     | 1         | 0.68%   |
| OPNsense 21.1.6     | 1         | 0.68%   |
| OPNsense 21.1.3     | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 54        | 42.86%  |
| OpenBSD     | 20        | 15.87%  |
| helloSystem | 17        | 13.49%  |
| NomadBSD    | 14        | 11.11%  |
| OPNsense    | 10        | 7.94%   |
| GhostBSD    | 9         | 7.14%   |
| NetBSD      | 1         | 0.79%   |
| FuryBSD     | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 111       | 96.52%  |
| i386   | 3         | 2.61%   |
| macppc | 1         | 0.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 23        | 17.69%  |
| XFCE         | 19        | 14.62%  |
| fvwm         | 15        | 11.54%  |
| Console      | 14        | 10.77%  |
| KDE5         | 13        | 10%     |
| Openbox      | 12        | 9.23%   |
| MATE         | 10        | 7.69%   |
| TWM          | 7         | 5.38%   |
| GNOME        | 5         | 3.85%   |
| i3           | 4         | 3.08%   |
| xinitrc      | 3         | 2.31%   |
| AwesomeWM    | 2         | 1.54%   |
| X-Cinnamon   | 1         | 0.77%   |
| sway         | 1         | 0.77%   |
| LXDE         | 1         | 0.77%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 101       | 86.32%  |
| Console | 16        | 13.68%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 48        | 39.02%  |
| SLiM    | 39        | 31.71%  |
| SDDM    | 13        | 10.57%  |
| LightDM | 13        | 10.57%  |
| XDM     | 6         | 4.88%   |
| GDM     | 4         | 3.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 40        | 32%     |
| fr_FR           | 31        | 24.8%   |
| en_US           | 25        | 20%     |
| C               | 20        | 16%     |
| de_DE           | 3         | 2.4%    |
| fr              | 2         | 1.6%    |
| en_GB           | 2         | 1.6%    |
| en_US.ISO8859-1 | 1         | 0.8%    |
| en              | 1         | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 90        | 77.59%  |
| BIOS | 26        | 22.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 64        | 52.89%  |
| Ufs    | 30        | 24.79%  |
| Ffs    | 20        | 16.53%  |
| Cd9660 | 7         | 5.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 93        | 79.49%  |
| MBR     | 23        | 19.66%  |
| Unknown | 1         | 0.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 37        | 32.17%  |
| Dell                | 22        | 19.13%  |
| ASUSTek Computer    | 10        | 8.7%    |
| Hewlett-Packard     | 7         | 6.09%   |
| Intel               | 5         | 4.35%   |
| Apple               | 5         | 4.35%   |
| Deciso              | 4         | 3.48%   |
| Acer                | 4         | 3.48%   |
| TUXEDO              | 3         | 2.61%   |
| Toshiba             | 3         | 2.61%   |
| Sony                | 2         | 1.74%   |
| MSI                 | 2         | 1.74%   |
| Fujitsu             | 2         | 1.74%   |
| SECO                | 1         | 0.87%   |
| Samsung Electronics | 1         | 0.87%   |
| Panasonic           | 1         | 0.87%   |
| Notebook            | 1         | 0.87%   |
| Medion              | 1         | 0.87%   |
| Google              | 1         | 0.87%   |
| Gigabyte Technology | 1         | 0.87%   |
| Clevo               | 1         | 0.87%   |
| Alienware           | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel H81U                               | 4         | 3.48%   |
| Dell Precision M4500                     | 3         | 2.61%   |
| Deciso Netboard A20                      | 3         | 2.61%   |
| TUXEDO InfinityBook13V3                  | 2         | 1.74%   |
| Toshiba PORTEGE Z930                     | 2         | 1.74%   |
| Dell Latitude 3410                       | 2         | 1.74%   |
| TUXEDO Aura 15 Gen1                      | 1         | 0.87%   |
| Toshiba NB300                            | 1         | 0.87%   |
| Sony VGN-FZ19VN                          | 1         | 0.87%   |
| Sony VGN-AR630E                          | 1         | 0.87%   |
| SECO UDOO x86                            | 1         | 0.87%   |
| Samsung R720                             | 1         | 0.87%   |
| Panasonic CF-31-5                        | 1         | 0.87%   |
| Notebook W510LU                          | 1         | 0.87%   |
| MSI P65 Creator 8RE                      | 1         | 0.87%   |
| MSI MS-N033                              | 1         | 0.87%   |
| Medion E15415                            | 1         | 0.87%   |
| Lenovo ThinkPad X280 20KFCTO1WW          | 1         | 0.87%   |
| Lenovo ThinkPad X250 20CLS7WY04          | 1         | 0.87%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 0.87%   |
| Lenovo ThinkPad X230 2325AJ9             | 1         | 0.87%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 0.87%   |
| Lenovo ThinkPad X220 4290EE8             | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1TG00 | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2K000 | 1         | 0.87%   |
| Lenovo ThinkPad W540 20BG001KUK          | 1         | 0.87%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.87%   |
| Lenovo ThinkPad T580 20LAS2TG00          | 1         | 0.87%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 0.87%   |
| Lenovo ThinkPad T495 20NKS0HN1N          | 1         | 0.87%   |
| Lenovo ThinkPad T495 20NJCTO1WW          | 1         | 0.87%   |
| Lenovo ThinkPad T490 20N20009FR          | 1         | 0.87%   |
| Lenovo ThinkPad T480 20L5CTO1WW          | 1         | 0.87%   |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 0.87%   |
| Lenovo ThinkPad T450s 20BWS0L600         | 1         | 0.87%   |
| Lenovo ThinkPad T440p 20AWS0Y40T         | 1         | 0.87%   |
| Lenovo ThinkPad T430 23495P8             | 1         | 0.87%   |
| Lenovo ThinkPad T420 4236NUG             | 1         | 0.87%   |
| Lenovo ThinkPad T420 42368A3             | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 32        | 27.83%  |
| Dell Latitude           | 12        | 10.43%  |
| Dell Precision          | 6         | 5.22%   |
| Intel H81U              | 4         | 3.48%   |
| HP EliteBook            | 3         | 2.61%   |
| Deciso Netboard         | 3         | 2.61%   |
| Acer Aspire             | 3         | 2.61%   |
| TUXEDO InfinityBook13V3 | 2         | 1.74%   |
| Toshiba PORTEGE         | 2         | 1.74%   |
| Lenovo Legion           | 2         | 1.74%   |
| Dell Inspiron           | 2         | 1.74%   |
| TUXEDO Aura             | 1         | 0.87%   |
| Toshiba NB300           | 1         | 0.87%   |
| Sony VGN-FZ19VN         | 1         | 0.87%   |
| Sony VGN-AR630E         | 1         | 0.87%   |
| SECO UDOO               | 1         | 0.87%   |
| Samsung R720            | 1         | 0.87%   |
| Panasonic CF-31-5       | 1         | 0.87%   |
| Notebook W510LU         | 1         | 0.87%   |
| MSI P65                 | 1         | 0.87%   |
| MSI MS-N033             | 1         | 0.87%   |
| Medion E15415           | 1         | 0.87%   |
| Lenovo IdeaPad          | 1         | 0.87%   |
| Lenovo G500             | 1         | 0.87%   |
| Lenovo Flex             | 1         | 0.87%   |
| Intel Jasper            | 1         | 0.87%   |
| HP ZBook                | 1         | 0.87%   |
| HP ProBook              | 1         | 0.87%   |
| HP Pavilion             | 1         | 0.87%   |
| HP Compaq               | 1         | 0.87%   |
| Google Terra            | 1         | 0.87%   |
| Gigabyte P15FR7         | 1         | 0.87%   |
| Fujitsu LIFEBOOK        | 1         | 0.87%   |
| Fujitsu CELSIUS         | 1         | 0.87%   |
| Dell Vostro             | 1         | 0.87%   |
| Dell Studio             | 1         | 0.87%   |
| Deciso NetBoard-A20     | 1         | 0.87%   |
| Clevo W240EU            | 1         | 0.87%   |
| ASUS X75VC              | 1         | 0.87%   |
| ASUS X751LN             | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 18        | 15.65%  |
| 2020    | 15        | 13.04%  |
| 2015    | 10        | 8.7%    |
| 2013    | 9         | 7.83%   |
| 2021    | 8         | 6.96%   |
| 2011    | 8         | 6.96%   |
| 2010    | 8         | 6.96%   |
| 2022    | 7         | 6.09%   |
| 2018    | 7         | 6.09%   |
| 2014    | 6         | 5.22%   |
| 2017    | 4         | 3.48%   |
| 2016    | 4         | 3.48%   |
| 2009    | 3         | 2.61%   |
| 2008    | 3         | 2.61%   |
| 2012    | 2         | 1.74%   |
| 2007    | 2         | 1.74%   |
| Unknown | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 113       | 98.26%  |
| Yes  | 2         | 1.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 40        | 34.19%  |
| 16.01-24.0  | 28        | 23.93%  |
| 4.01-8.0    | 20        | 17.09%  |
| 32.01-64.0  | 9         | 7.69%   |
| 2.01-3.0    | 9         | 7.69%   |
| 64.01-256.0 | 4         | 3.42%   |
| 3.01-4.0    | 3         | 2.56%   |
| 24.01-32.0  | 2         | 1.71%   |
| 1.01-2.0    | 2         | 1.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 67        | 55.37%  |
| 0.51-1.0   | 31        | 25.62%  |
| 1.01-2.0   | 12        | 9.92%   |
| 2.01-3.0   | 6         | 4.96%   |
| 8.01-16.0  | 3         | 2.48%   |
| 32.01-64.0 | 1         | 0.83%   |
| Unknown    | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 63.25%  |
| 2      | 26        | 22.22%  |
| 0      | 11        | 9.4%    |
| 3      | 4         | 3.42%   |
| 4      | 2         | 1.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 73.73%  |
| Yes       | 31        | 26.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 87.93%  |
| No        | 14        | 12.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 92.17%  |
| No        | 9         | 7.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 56.78%  |
| No        | 51        | 43.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 115       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Paris                    | 21        | 16.03%  |
| Franconville             | 7         | 5.34%   |
| Melun                    | 4         | 3.05%   |
| Bordeaux                 | 4         | 3.05%   |
| Marcq-en-Baroeul         | 3         | 2.29%   |
| Fontenay-sous-Bois       | 3         | 2.29%   |
| Carry-le-Rouet           | 3         | 2.29%   |
| Stiring-Wendel           | 2         | 1.53%   |
| Saint-Raphaël           | 2         | 1.53%   |
| Saint-Denis              | 2         | 1.53%   |
| Rosny-sous-Bois          | 2         | 1.53%   |
| Rennes                   | 2         | 1.53%   |
| Noisy-le-Grand           | 2         | 1.53%   |
| Mâcon                   | 2         | 1.53%   |
| Dijon                    | 2         | 1.53%   |
| Colmar                   | 2         | 1.53%   |
| Asnieres-sur-Seine       | 2         | 1.53%   |
| Villeneuve-Saint-Georges | 1         | 0.76%   |
| Villemomble              | 1         | 0.76%   |
| Villejuif                | 1         | 0.76%   |
| Vertou                   | 1         | 0.76%   |
| Tulle                    | 1         | 0.76%   |
| Tournon-sur-RhÃ´ne     | 1         | 0.76%   |
| Toulouse                 | 1         | 0.76%   |
| St-Malo                  | 1         | 0.76%   |
| Soisy-sur-Seine          | 1         | 0.76%   |
| Sartrouville             | 1         | 0.76%   |
| Sarcelles                | 1         | 0.76%   |
| Sallanches               | 1         | 0.76%   |
| Saint-Saulge             | 1         | 0.76%   |
| Saint-Herblain           | 1         | 0.76%   |
| Saint-Germain-en-Laye    | 1         | 0.76%   |
| Saint-Genest-Lerpt       | 1         | 0.76%   |
| Roubaix                  | 1         | 0.76%   |
| Quimper                  | 1         | 0.76%   |
| Poncins                  | 1         | 0.76%   |
| Noirmoutier-en-l'Ile     | 1         | 0.76%   |
| Nogent-sur-Marne         | 1         | 0.76%   |
| Neuilly-sur-Marne        | 1         | 0.76%   |
| Nantes                   | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 34     | 18.05%  |
| Seagate             | 14        | 25     | 10.53%  |
| Crucial             | 14        | 18     | 10.53%  |
| Toshiba             | 12        | 17     | 9.02%   |
| WDC                 | 9         | 12     | 6.77%   |
| SanDisk             | 9         | 11     | 6.77%   |
| Kingston            | 8         | 10     | 6.02%   |
| Transcend           | 7         | 11     | 5.26%   |
| China               | 7         | 7      | 5.26%   |
| NVMe                | 5         | 5      | 3.76%   |
| Micron Technology   | 5         | 8      | 3.76%   |
| Intel               | 4         | 7      | 3.01%   |
| HGST                | 3         | 6      | 2.26%   |
| SK hynix            | 2         | 2      | 1.5%    |
| Phison              | 2         | 2      | 1.5%    |
| Fujitsu             | 2         | 2      | 1.5%    |
| SPCC                | 1         | 1      | 0.75%   |
| LDLC F6+            | 1         | 1      | 0.75%   |
| Integral            | 1         | 1      | 0.75%   |
| Hitachi             | 1         | 1      | 0.75%   |
| Generic             | 1         | 1      | 0.75%   |
| EMTEC               | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB            | 4         | 2.92%   |
| China MSATA 32GB SSD                      | 4         | 2.92%   |
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.19%   |
| Kingston SA400S37240G 240GB               | 3         | 2.19%   |
| Crucial CT1000P1SSD8 1TB                  | 3         | 2.19%   |
| WDC WD3200BPVT-80JJ5T0 320GB              | 2         | 1.46%   |
| Transcend TS256GMTS430S 256GB             | 2         | 1.46%   |
| Toshiba MK2556GSY 250GB                   | 2         | 1.46%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 2         | 1.46%   |
| Samsung SSD 970 EVO Plus 2TB              | 2         | 1.46%   |
| Samsung SSD 950 PRO 512GB                 | 2         | 1.46%   |
| NVMe WDC PC SN720 SDA 512GB               | 2         | 1.46%   |
| Intel SSDPEKKF256G8L 256GB                | 2         | 1.46%   |
| Crucial CT960M500SSD1 960GB               | 2         | 1.46%   |
| Crucial CT1050MX300SSD1 1TB               | 2         | 1.46%   |
| China SH00M240GB                          | 2         | 1.46%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.73%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 0.73%   |
| WDC WD20SDRW-11VUUS0 2TB                  | 1         | 0.73%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.73%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.73%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB      | 1         | 0.73%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 0.73%   |
| Transcend TS256GMTS800 256GB              | 1         | 0.73%   |
| Toshiba THNSNJ256GCSY 256GB               | 1         | 0.73%   |
| Toshiba THNSNF128GMCS 128GB               | 1         | 0.73%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.73%   |
| Toshiba MQ01ACF032 320GB                  | 1         | 0.73%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.73%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.73%   |
| Toshiba MK2555GSX 250GB                   | 1         | 0.73%   |
| Toshiba MK2546GSX_200 200GB               | 1         | 0.73%   |
| Toshiba MK1629GSGF 160GB                  | 1         | 0.73%   |
| SPCC Solid State Disk 512GB               | 1         | 0.73%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB      | 1         | 0.73%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.73%   |
| Seagate ST9750423AS 752GB                 | 1         | 0.73%   |
| Seagate ST95005620AS 500GB                | 1         | 0.73%   |
| Seagate ST9320423AS 320GB                 | 1         | 0.73%   |
| Seagate ST9320325AS 320GB                 | 1         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 25     | 33.33%  |
| Toshiba             | 8         | 11     | 19.05%  |
| WDC                 | 6         | 7      | 14.29%  |
| NVMe                | 5         | 5      | 11.9%   |
| HGST                | 3         | 6      | 7.14%   |
| Fujitsu             | 2         | 2      | 4.76%   |
| Samsung Electronics | 1         | 1      | 2.38%   |
| LDLC F6+            | 1         | 1      | 2.38%   |
| Hitachi             | 1         | 1      | 2.38%   |
| Generic             | 1         | 1      | 2.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 19     | 21.31%  |
| SanDisk             | 9         | 11     | 14.75%  |
| Crucial             | 9         | 9      | 14.75%  |
| Transcend           | 7         | 11     | 11.48%  |
| Kingston            | 7         | 8      | 11.48%  |
| China               | 7         | 7      | 11.48%  |
| Toshiba             | 4         | 6      | 6.56%   |
| WDC                 | 1         | 1      | 1.64%   |
| SPCC                | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 4      | 1.64%   |
| Integral            | 1         | 1      | 1.64%   |
| EMTEC               | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 54        | 79     | 45%     |
| HDD  | 39        | 60     | 32.5%   |
| NVMe | 27        | 44     | 22.5%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 139    | 76.11%  |
| NVMe | 27        | 44     | 23.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 65        | 96     | 67.01%  |
| 0.51-1.0   | 27        | 37     | 27.84%  |
| 1.01-2.0   | 5         | 6      | 5.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 40        | 32.79%  |
| 1-20       | 26        | 21.31%  |
| 251-500    | 18        | 14.75%  |
| 21-50      | 16        | 13.11%  |
| 501-1000   | 11        | 9.02%   |
| 51-100     | 8         | 6.56%   |
| 1001-2000  | 2         | 1.64%   |
| Unknown    | 1         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 97        | 82.91%  |
| 101-250  | 8         | 6.84%   |
| 21-50    | 7         | 5.98%   |
| 51-100   | 3         | 2.56%   |
| 501-1000 | 1         | 0.85%   |
| Unknown  | 1         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-80JJ5T0 320GB          | 2         | 2      | 13.33%  |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 6.67%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 6.67%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 6.67%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 6.67%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 6      | 6.67%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 6.67%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 6.67%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 6.67%   |
| Kingston SUV500MS480G 480GB           | 1         | 1      | 6.67%   |
| HGST HTS545050A7E660 500GB            | 1         | 2      | 6.67%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 10     | 33.33%  |
| WDC                 | 3         | 3      | 20%     |
| Toshiba             | 2         | 4      | 13.33%  |
| SanDisk             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 2      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| HGST                | 1         | 2      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 10     | 45.45%  |
| WDC     | 3         | 3      | 27.27%  |
| Toshiba | 2         | 4      | 18.18%  |
| HGST    | 1         | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 19     | 71.43%  |
| SSD  | 4         | 5      | 28.57%  |

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
| Works    | 92        | 155    | 83.64%  |
| Malfunc  | 14        | 24     | 12.73%  |
| Detected | 4         | 4      | 3.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 86        | 66.67%  |
| Samsung Electronics         | 12        | 9.3%    |
| AMD                         | 11        | 8.53%   |
| Micron/Crucial Technology   | 5         | 3.88%   |
| SanDisk                     | 4         | 3.1%    |
| Micron Technology           | 4         | 3.1%    |
| SK hynix                    | 2         | 1.55%   |
| Phison Electronics          | 2         | 1.55%   |
| Nvidia                      | 1         | 0.78%   |
| KIOXIA                      | 1         | 0.78%   |
| Kingston Technology Company | 1         | 0.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 8.7%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 7.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 5.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 5.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 5.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 5.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 4.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 4.35%   |
| Micron NVMe Storage Controller                                                   | 4         | 2.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.9%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 2.17%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 2.17%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 3         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 2.17%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.45%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.45%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.45%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.72%   |
| SK hynix BC511                                                                   | 1         | 0.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.72%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.72%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.72%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.72%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.72%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.72%   |
| Intel SSD 660P Series                                                            | 1         | 0.72%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.72%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 62.6%   |
| NVMe | 31        | 23.66%  |
| RAID | 11        | 8.4%    |
| IDE  | 7         | 5.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 98        | 84.48%  |
| AMD     | 17        | 14.66%  |
| PowerPC | 1         | 0.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz    | 5         | 4.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 4         | 3.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 4         | 3.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 3         | 2.59%   |
| Intel Core i5 CPU M 560 @ 2.67GH     | 3         | 2.59%   |
| Intel Core i3-4010U CPU @ 1.70GHz    | 3         | 2.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz    | 2         | 1.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 2         | 1.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 2         | 1.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 2         | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 1.72%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 1.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 1.72%   |
| Intel Core i5-3437U CPU @ 1.90GHz    | 2         | 1.72%   |
| Intel Core i3-4025U CPU @ 1.90GHz    | 2         | 1.72%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 2         | 1.72%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 2         | 1.72%   |
| Intel Celeron CPU N3160 @ 1.60GHz    | 2         | 1.72%   |
| AMD EPYC 3201 8-Core Processor       | 2         | 1.72%   |
| AMD EPYC 3101 4-Core Processor       | 2         | 1.72%   |
| PowerPC 7447A (Revision 0x105)       | 1         | 0.86%   |
| Intel Pentium M                      | 1         | 0.86%   |
| Intel CPU Version                    | 1         | 0.86%   |
| Intel Core M-5Y10c CPU @ 0.80GHz     | 1         | 0.86%   |
| Intel Core i7-9850H CPU @ 2.60GHz    | 1         | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 1         | 0.86%   |
| Intel Core i7-8665U CPU @ 1.90GHz    | 1         | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 1         | 0.86%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz   | 1         | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz   | 1         | 0.86%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz   | 1         | 0.86%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 1         | 0.86%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 1         | 0.86%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz   | 1         | 0.86%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz   | 1         | 0.86%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz   | 1         | 0.86%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 1         | 0.86%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 1         | 0.86%   |
| Intel Core i7-4500U CPU @ 1.80GHz    | 1         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 39        | 33.62%  |
| Intel Core i7    | 26        | 22.41%  |
| Intel Core i3    | 11        | 9.48%   |
| Intel Core 2 Duo | 9         | 7.76%   |
| Intel Celeron    | 5         | 4.31%   |
| Other            | 4         | 3.45%   |
| AMD Ryzen 7 PRO  | 4         | 3.45%   |
| AMD Ryzen 7      | 4         | 3.45%   |
| AMD EPYC         | 4         | 3.45%   |
| Intel Atom       | 3         | 2.59%   |
| Intel Pentium M  | 1         | 0.86%   |
| Intel Core M     | 1         | 0.86%   |
| AMD Ryzen 5 PRO  | 1         | 0.86%   |
| AMD Ryzen 5      | 1         | 0.86%   |
| AMD E1           | 1         | 0.86%   |
| AMD A6           | 1         | 0.86%   |
| AMD A4           | 1         | 0.86%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 52        | 44.83%  |
| 4       | 38        | 32.76%  |
| Unknown | 9         | 7.76%   |
| 8       | 8         | 6.9%    |
| 16      | 4         | 3.45%   |
| 6       | 2         | 1.72%   |
| 1       | 2         | 1.72%   |
| 12      | 1         | 0.86%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 109       | 94.78%  |
| Unknown | 4         | 3.48%   |
| 2       | 2         | 1.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 68.1%   |
| 1       | 27        | 23.28%  |
| Unknown | 10        | 8.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 29        | 25%     |
| Haswell     | 16        | 13.79%  |
| IvyBridge   | 10        | 8.62%   |
| Penryn      | 8         | 6.9%    |
| SandyBridge | 7         | 6.03%   |
| Broadwell   | 6         | 5.17%   |
| Zen         | 5         | 4.31%   |
| Westmere    | 5         | 4.31%   |
| Skylake     | 5         | 4.31%   |
| Unknown     | 5         | 4.31%   |
| Silvermont  | 4         | 3.45%   |
| Zen+        | 3         | 2.59%   |
| Zen 2       | 3         | 2.59%   |
| Bonnell     | 3         | 2.59%   |
| Jaguar      | 2         | 1.72%   |
| Core        | 2         | 1.72%   |
| Zen 3       | 1         | 0.86%   |
| P6          | 1         | 0.86%   |
| K10 Llano   | 1         | 0.86%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 65.38%  |
| Nvidia | 26        | 20%     |
| AMD    | 19        | 14.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 8.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 6.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 4.44%   |
| Intel HD Graphics 620                                                                    | 6         | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 4.44%   |
| Intel HD Graphics 5500                                                                   | 5         | 3.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.7%    |
| Intel UHD Graphics 620                                                                   | 4         | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.96%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 3         | 2.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.22%   |
| AMD Renoir                                                                               | 3         | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.48%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.48%   |
| Intel HD Graphics 630                                                                    | 2         | 1.48%   |
| Intel HD Graphics 530                                                                    | 2         | 1.48%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.48%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.48%   |
| AMD Lucienne                                                                             | 2         | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.74%   |
| Nvidia TU117M                                                                            | 1         | 0.74%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.74%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.74%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.74%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GP104GLM [Quadro P3000 Mobile]                                                    | 1         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.74%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.74%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.74%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 60        | 51.72%  |
| 1 x AMD                  | 15        | 12.93%  |
| Intel + Nvidia           | 14        | 12.07%  |
| 1 x Nvidia               | 10        | 8.62%   |
| 2 x Intel                | 9         | 7.76%   |
| Other                    | 4         | 3.45%   |
| 2 x AMD                  | 1         | 0.86%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.86%   |
| Intel + AMD              | 1         | 0.86%   |
| AMD + Nvidia             | 1         | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 87.18%  |
| Proprietary | 8         | 6.84%   |
| Unknown     | 7         | 5.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 89.66%  |
| 0.51-1.0   | 4         | 3.45%   |
| 0.01-0.5   | 3         | 2.59%   |
| 5.01-6.0   | 2         | 1.72%   |
| 3.01-4.0   | 1         | 0.86%   |
| 1.01-2.0   | 1         | 0.86%   |
| 8.01-16.0  | 1         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 20.22%  |
| LG Display              | 14        | 15.73%  |
| Chimei Innolux          | 14        | 15.73%  |
| BOE                     | 8         | 8.99%   |
| Samsung Electronics     | 7         | 7.87%   |
| Chi Mei Optoelectronics | 4         | 4.49%   |
| Apple                   | 4         | 4.49%   |
| Philips                 | 3         | 3.37%   |
| LGD                     | 2         | 2.25%   |
| Lenovo                  | 2         | 2.25%   |
| Iiyama                  | 2         | 2.25%   |
| ViewSonic               | 1         | 1.12%   |
| Sharp                   | 1         | 1.12%   |
| Nvidia                  | 1         | 1.12%   |
| IBM                     | 1         | 1.12%   |
| Hewlett-Packard         | 1         | 1.12%   |
| Goldstar                | 1         | 1.12%   |
| Dell                    | 1         | 1.12%   |
| CSO                     | 1         | 1.12%   |
| CPT                     | 1         | 1.12%   |
| ASUSTek Computer        | 1         | 1.12%   |
| Acer                    | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 3.37%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 2.25%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 2.25%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 2.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 2.25%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 2.25%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 1.12%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch     | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 1         | 1.12%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 1.12%   |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                  | 1         | 1.12%   |
| Nvidia LCD Monitor Default Flat Panel 1440x900                           | 1         | 1.12%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch             | 1         | 1.12%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.12%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 1         | 1.12%   |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD036C 1366x768 280x160mm 12.7-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD0366 1600x900 310x170mm 13.9-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.12%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch              | 1         | 1.12%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 1         | 1.12%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 1         | 1.12%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 1         | 1.12%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 1         | 1.12%   |
| Hewlett-Packard M27f FHD HPN370A 1920x1080 610x360mm 27.9-inch           | 1         | 1.12%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 43.53%  |
| 1366x768 (WXGA)    | 26        | 30.59%  |
| 1600x900 (HD+)     | 5         | 5.88%   |
| 3840x2160 (4K)     | 4         | 4.71%   |
| 1280x800 (WXGA)    | 4         | 4.71%   |
| 2560x1440 (QHD)    | 2         | 2.35%   |
| 1440x900 (WXGA+)   | 2         | 2.35%   |
| 1024x600           | 2         | 2.35%   |
| 2880x1800          | 1         | 1.18%   |
| 1680x1050 (WSXGA+) | 1         | 1.18%   |
| 1440x960           | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 27        | 30.34%  |
| 13      | 23        | 25.84%  |
| 12      | 12        | 13.48%  |
| 17      | 5         | 5.62%   |
| 27      | 3         | 3.37%   |
| 24      | 3         | 3.37%   |
| 23      | 3         | 3.37%   |
| 10      | 3         | 3.37%   |
| Unknown | 3         | 3.37%   |
| 21      | 2         | 2.25%   |
| 14      | 2         | 2.25%   |
| 42      | 1         | 1.12%   |
| 18      | 1         | 1.12%   |
| 11      | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 51.69%  |
| 201-300     | 22        | 24.72%  |
| 501-600     | 8         | 8.99%   |
| 351-400     | 5         | 5.62%   |
| 401-500     | 3         | 3.37%   |
| Unknown     | 3         | 3.37%   |
| 601-700     | 1         | 1.12%   |
| 901-1000    | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 84.62%  |
| 16/10   | 7         | 8.97%   |
| Unknown | 3         | 3.85%   |
| 3/2     | 2         | 2.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 24        | 26.97%  |
| 91-100         | 23        | 25.84%  |
| 61-70          | 12        | 13.48%  |
| 201-250        | 8         | 8.99%   |
| 121-130        | 5         | 5.62%   |
| 101-110        | 4         | 4.49%   |
| 41-50          | 3         | 3.37%   |
| 301-350        | 3         | 3.37%   |
| Unknown        | 3         | 3.37%   |
| 71-80          | 1         | 1.12%   |
| 51-60          | 1         | 1.12%   |
| 141-150        | 1         | 1.12%   |
| 501-1000       | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 45.98%  |
| 101-120       | 27        | 31.03%  |
| 51-100        | 9         | 10.34%  |
| 161-240       | 5         | 5.75%   |
| More than 240 | 3         | 3.45%   |
| Unknown       | 3         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 68.6%   |
| 0     | 27        | 22.31%  |
| 2     | 11        | 9.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 82        | 45.56%  |
| Realtek Semiconductor    | 41        | 22.78%  |
| Qualcomm Atheros         | 20        | 11.11%  |
| Broadcom                 | 11        | 6.11%   |
| Marvell Technology Group | 4         | 2.22%   |
| AMD                      | 4         | 2.22%   |
| TP-Link                  | 2         | 1.11%   |
| Sierra Wireless          | 2         | 1.11%   |
| Edimax Technology        | 2         | 1.11%   |
| Apple                    | 2         | 1.11%   |
| Xiaomi                   | 1         | 0.56%   |
| Sagem                    | 1         | 0.56%   |
| Ralink Technology        | 1         | 0.56%   |
| Ralink                   | 1         | 0.56%   |
| Qualcomm                 | 1         | 0.56%   |
| Nvidia                   | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Hewlett-Packard          | 1         | 0.56%   |
| Dell                     | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 13.73%  |
| Intel Wireless 8265 / 8275                                        | 11        | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.29%   |
| Intel Wireless 7265                                               | 8         | 3.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 3%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.58%   |
| Intel Wireless 7260                                               | 6         | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.15%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.15%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 2.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 2.15%   |
| Intel Wireless-AC 9260                                            | 4         | 1.72%   |
| Intel Wireless 8260                                               | 4         | 1.72%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.72%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.72%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 4         | 1.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.29%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 1.29%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.29%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.29%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.86%   |
| Sierra Wireless EM7305 Modem                                      | 2         | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.86%   |
| Intel Wireless 3165                                               | 2         | 0.86%   |
| Intel WiFi Link 5100                                              | 2         | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.86%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.86%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 2         | 0.86%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.43%   |
| Sagem XG-76NA 802.11bg                                            | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 77        | 65.25%  |
| Qualcomm Atheros      | 18        | 15.25%  |
| Broadcom              | 8         | 6.78%   |
| Realtek Semiconductor | 6         | 5.08%   |
| TP-Link               | 2         | 1.69%   |
| Edimax Technology     | 2         | 1.69%   |
| Sagem                 | 1         | 0.85%   |
| Ralink Technology     | 1         | 0.85%   |
| Ralink                | 1         | 0.85%   |
| MediaTek              | 1         | 0.85%   |
| Dell                  | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 11        | 9.24%   |
| Intel Wireless 7265                                                     | 8         | 6.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 5.04%   |
| Intel Wireless 7260                                                     | 6         | 5.04%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 4.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 4.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 4.2%    |
| Intel Wireless-AC 9260                                                  | 4         | 3.36%   |
| Intel Wireless 8260                                                     | 4         | 3.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 2.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.52%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 2.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.68%   |
| Intel Wireless 3165                                                     | 2         | 1.68%   |
| Intel WiFi Link 5100                                                    | 2         | 1.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.68%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.68%   |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.84%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 1         | 0.84%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.84%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.84%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 50        | 46.3%   |
| Realtek Semiconductor    | 37        | 34.26%  |
| Qualcomm Atheros         | 5         | 4.63%   |
| Marvell Technology Group | 4         | 3.7%    |
| Broadcom                 | 4         | 3.7%    |
| AMD                      | 4         | 3.7%    |
| Xiaomi                   | 1         | 0.93%   |
| Qualcomm                 | 1         | 0.93%   |
| Nvidia                   | 1         | 0.93%   |
| Apple                    | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 29.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 9.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.63%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 4.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 4.63%   |
| Intel I210 Gigabit Network Connection                             | 4         | 3.7%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.7%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.7%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 4         | 3.7%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 2.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.93%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.93%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 49.53%  |
| Ethernet | 102       | 47.66%  |
| Modem    | 3         | 1.4%    |
| Unknown  | 3         | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 50%     |
| Ethernet | 78        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 92        | 79.31%  |
| 1     | 14        | 12.07%  |
| 3     | 5         | 4.31%   |
| 6     | 4         | 3.45%   |
| 0     | 1         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 85.83%  |
| Yes  | 17        | 14.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 71.01%  |
| Broadcom                        | 6         | 8.7%    |
| Foxconn / Hon Hai               | 3         | 4.35%   |
| Apple                           | 3         | 4.35%   |
| IMC Networks                    | 2         | 2.9%    |
| Dell                            | 2         | 2.9%    |
| Realtek Semiconductor           | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| Hewlett-Packard                 | 1         | 1.45%   |
| Creative Technology             | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 23        | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 9         | 13.04%  |
| Intel AX200 Bluetooth                              | 5         | 7.25%   |
| Intel AX201 Bluetooth                              | 4         | 5.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 3         | 4.35%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 2.9%    |
| Intel AX210 Bluetooth                              | 2         | 2.9%    |
| Foxconn / Hon Hai Bluetooth USB Module             | 2         | 2.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 2.9%    |
| Broadcom BCM2045B (BDC-2.1)                        | 2         | 2.9%    |
| Apple Bluetooth Host Controller                    | 2         | 2.9%    |
| Realtek Bluetooth Adapter                          | 1         | 1.45%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1             | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.45%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1        | 1         | 1.45%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS   | 1         | 1.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]      | 1         | 1.45%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter          | 1         | 1.45%   |
| Dell DW375 Bluetooth Module                        | 1         | 1.45%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module        | 1         | 1.45%   |
| Creative Creative Bluetooth Audio W2               | 1         | 1.45%   |
| Broadcom BCM43142A0 Bluetooth Module               | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.45%   |
| Apple Built-in iSight (no firmware loaded)         | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 96        | 70.59%  |
| AMD                 | 21        | 15.44%  |
| Nvidia              | 12        | 8.82%   |
| Lenovo              | 2         | 1.47%   |
| Texas Instruments   | 1         | 0.74%   |
| Logitech            | 1         | 0.74%   |
| Kingston Technology | 1         | 0.74%   |
| GN Netcom           | 1         | 0.74%   |
| DSEA A/S            | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 8.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 7.06%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 7.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 4.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.53%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.94%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 2.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 2.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.76%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.76%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.18%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.18%   |
| Texas Instruments PCM2706 stereo audio DAC                                                        | 1         | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.59%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.59%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.59%   |
| Logitech Logitech Stereo H650e                                                                    | 1         | 0.59%   |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.59%   |
| Intel USB2.0 Device                                                                               | 1         | 0.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.59%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 30.33%  |
| SK hynix            | 26        | 21.31%  |
| Unknown             | 11        | 9.02%   |
| Micron Technology   | 10        | 8.2%    |
| Crucial             | 9         | 7.38%   |
| Kingston            | 7         | 5.74%   |
| Transcend           | 3         | 2.46%   |
| Elpida              | 3         | 2.46%   |
| Corsair             | 3         | 2.46%   |
| Unknown             | 3         | 2.46%   |
| Nanya Technology    | 2         | 1.64%   |
| A-DATA Technology   | 2         | 1.64%   |
| V-Color             | 1         | 0.82%   |
| SHARETRONIC         | 1         | 0.82%   |
| Patriot             | 1         | 0.82%   |
| G.Skill             | 1         | 0.82%   |
| CSX                 | 1         | 0.82%   |
| Avant               | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 3.05%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 3         | 2.29%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 2.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s     | 3         | 2.29%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 3         | 2.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 2.29%   |
| Unknown                                                    | 3         | 2.29%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 2         | 1.53%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s        | 2         | 1.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.53%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.53%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 2         | 1.53%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 2         | 1.53%   |
| Samsung RAM M471B5773CHS-CK0 2GB DDR3 1600MT/s             | 2         | 1.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.53%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s              | 2         | 1.53%   |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s   | 2         | 1.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s    | 2         | 1.53%   |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s | 2         | 1.53%   |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s     | 1         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                | 1         | 0.76%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s             | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM 533MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s           | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR2                         | 1         | 0.76%   |
| Unknown RAM Module 1024MB SODIMM DDR2                      | 1         | 0.76%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s        | 1         | 0.76%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 0.76%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s      | 1         | 0.76%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.76%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s    | 1         | 0.76%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 43        | 44.33%  |
| DDR4    | 39        | 40.21%  |
| DDR2    | 8         | 8.25%   |
| LPDDR3  | 5         | 5.15%   |
| Unknown | 2         | 2.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 95%     |
| Unknown      | 3         | 3%      |
| Row Of Chips | 1         | 1%      |
| Chip         | 1         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 36        | 33.33%  |
| 8192  | 35        | 32.41%  |
| 16384 | 16        | 14.81%  |
| 2048  | 16        | 14.81%  |
| 32768 | 3         | 2.78%   |
| 1024  | 2         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 29.81%  |
| 2667    | 16        | 15.38%  |
| 3200    | 12        | 11.54%  |
| 2400    | 9         | 8.65%   |
| 1333    | 9         | 8.65%   |
| 1334    | 8         | 7.69%   |
| 2133    | 4         | 3.85%   |
| 1867    | 3         | 2.88%   |
| 667     | 3         | 2.88%   |
| Unknown | 3         | 2.88%   |
| 800     | 2         | 1.92%   |
| 1200    | 1         | 0.96%   |
| 1067    | 1         | 0.96%   |
| 975     | 1         | 0.96%   |
| 533     | 1         | 0.96%   |

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
| Chicony Electronics                    | 28        | 35.9%   |
| Bison Electronics                      | 9         | 11.54%  |
| Sunplus Innovation Technology          | 8         | 10.26%  |
| Microdia                               | 7         | 8.97%   |
| Realtek Semiconductor                  | 5         | 6.41%   |
| IMC Networks                           | 5         | 6.41%   |
| Syntek                                 | 3         | 3.85%   |
| Lite-On Technology                     | 3         | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.85%   |
| Suyin                                  | 2         | 2.56%   |
| Alcor Micro                            | 2         | 2.56%   |
| SIMPLO Technology                      | 1         | 1.28%   |
| Quanta                                 | 1         | 1.28%   |
| Apple                                  | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 12.66%  |
| Bison Integrated Camera                             | 6         | 7.59%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 5.06%   |
| Microdia Integrated_Webcam_HD                       | 3         | 3.8%    |
| Microdia Integrated Webcam                          | 3         | 3.8%    |
| Chicony HD WebCam                                   | 3         | 3.8%    |
| Syntek Integrated Camera                            | 2         | 2.53%   |
| Realtek USB Camera                                  | 2         | 2.53%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.53%   |
| Lite-On Integrated Camera                           | 2         | 2.53%   |
| IMC Networks EasyCamera                             | 2         | 2.53%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 2.53%   |
| Bison SunplusIT Integrated Camera                   | 2         | 2.53%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.27%   |
| Suyin USB 2.0 Camera                                | 1         | 1.27%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.27%   |
| Sunplus Integrated HD Webcam                        | 1         | 1.27%   |
| Sunplus Asus Webcam                                 | 1         | 1.27%   |
| SIMPLO USB 2.0 Camera                               | 1         | 1.27%   |
| Realtek Integrated Webcam HD                        | 1         | 1.27%   |
| Quanta HD WebCam                                    | 1         | 1.27%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.27%   |
| Lite-On Realtek DMFT RGB                            | 1         | 1.27%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.27%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.27%   |
| IMC Networks Integrated Camera                      | 1         | 1.27%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.27%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.27%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.27%   |
| Chicony ThinkPad T490 Webcam                        | 1         | 1.27%   |
| Chicony Sonix ST50220 USB Video Camera              | 1         | 1.27%   |
| Chicony Realtek DMFT RGB                            | 1         | 1.27%   |
| Chicony Ltd., USB2.0 HD UVC WebCam                  | 1         | 1.27%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.27%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.27%   |
| Chicony HP Webcam [2 MP]                            | 1         | 1.27%   |
| Chicony HP Webcam [2 MP Macro]                      | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 30.77%  |
| Synaptics                  | 7         | 26.92%  |
| AuthenTec                  | 5         | 19.23%  |
| Shenzhen Goodix Technology | 2         | 7.69%   |
| Upek                       | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |
| Elan Microelectronics      | 1         | 3.85%   |
| Broadcom                   | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 19.23%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 7.69%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 7.69%   |
| AuthenTec AES2810                                                            | 2         | 7.69%   |
| AuthenTec AES1660                                                            | 2         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 3.85%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 3.85%   |
| Synaptics UWP WBDI Device                                                    | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 3.85%   |
| Elan Fingerprint Sensor                                                      | 1         | 3.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.85%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 3.85%   |

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
| 1     | 38        | 30.16%  |
| 2     | 36        | 28.57%  |
| 3     | 19        | 15.08%  |
| 0     | 15        | 11.9%   |
| 4     | 11        | 8.73%   |
| 6     | 4         | 3.17%   |
| 5     | 2         | 1.59%   |
| 7     | 1         | 0.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 82        | 38.32%  |
| Bluetooth                | 35        | 16.36%  |
| Card reader              | 24        | 11.21%  |
| Net/wireless             | 21        | 9.81%   |
| Fingerprint reader       | 21        | 9.81%   |
| Firewire controller      | 13        | 6.07%   |
| Storage                  | 4         | 1.87%   |
| Sound                    | 4         | 1.87%   |
| Graphics card            | 4         | 1.87%   |
| Storage/raid             | 3         | 1.4%    |
| Network                  | 2         | 0.93%   |
| Net/ethernet             | 1         | 0.47%   |

