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

Total: 149

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| HP        | EliteBook 2530p             | [dd52bb1163](https://bsd-hardware.info/?probe=dd52bb1163) | Feb 15, 2022 |
| Lenovo    | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Deciso    | Netboard A20                | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Deciso    | Netboard A20                | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
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
| Lenovo    | G500 20236                  | [6e96d4c26f](https://bsd-hardware.info/?probe=6e96d4c26f) | Jun 28, 2021 |
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
| ASUSTek   | X102BA                      | [9156250b96](https://bsd-hardware.info/?probe=9156250b96) | Oct 31, 2020 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| Lenovo    | ThinkPad X230 2325AJ9       | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo    | ThinkPad S5-S540 20B3001... | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |
| ASUSTek   | X102BA                      | [47e04c9378](https://bsd-hardware.info/?probe=47e04c9378) | Oct 19, 2020 |
| ASUSTek   | UX305FA                     | [4ecb1e9cd3](https://bsd-hardware.info/?probe=4ecb1e9cd3) | Sep 25, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [986575086d](https://bsd-hardware.info/?probe=986575086d) | Sep 05, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [152377b2ea](https://bsd-hardware.info/?probe=152377b2ea) | Sep 05, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [f95de56bcd](https://bsd-hardware.info/?probe=f95de56bcd) | Sep 03, 2020 |
| TUXEDO    | InfinityBook13V3            | [d508fb472b](https://bsd-hardware.info/?probe=d508fb472b) | Aug 10, 2020 |
| Sony      | VGN-AR630E                  | [b417df513f](https://bsd-hardware.info/?probe=b417df513f) | Aug 07, 2020 |
| MSI       | P65 Creator 8RE             | [4031d186c2](https://bsd-hardware.info/?probe=4031d186c2) | Aug 06, 2020 |
| Lenovo    | ThinkPad X280 20KFCTO1WW    | [82de136ad3](https://bsd-hardware.info/?probe=82de136ad3) | Aug 06, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [f3e2acbb66](https://bsd-hardware.info/?probe=f3e2acbb66) | Jul 31, 2020 |
| Lenovo    | ThinkPad W540 20BG001KUK    | [7ae8c247e9](https://bsd-hardware.info/?probe=7ae8c247e9) | Jul 31, 2020 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [90e2b57f16](https://bsd-hardware.info/?probe=90e2b57f16) | Jun 14, 2020 |
| Lenovo    | ThinkPad T590 20N4CTO1WW    | [5b35ada62a](https://bsd-hardware.info/?probe=5b35ada62a) | Jun 14, 2020 |
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


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| OpenBSD 6.8           | 7         | 6.31%   |
| helloSystem 0.4.0     | 7         | 6.31%   |
| NomadBSD 1.3.2        | 6         | 5.41%   |
| helloSystem 0.7.0     | 6         | 5.41%   |
| OpenBSD 7.0           | 5         | 4.5%    |
| GhostBSD 20.04.02     | 5         | 4.5%    |
| NomadBSD 1.4          | 4         | 3.6%    |
| FreeBSD 13.0          | 4         | 3.6%    |
| FreeBSD 12.2-p2       | 4         | 3.6%    |
| OpenBSD 7.1           | 3         | 2.7%    |
| OpenBSD 6.9           | 3         | 2.7%    |
| FreeBSD 13.1          | 3         | 2.7%    |
| FreeBSD 13.0-STABLE   | 3         | 2.7%    |
| FreeBSD 12.2-p4       | 3         | 2.7%    |
| FreeBSD 12.2          | 3         | 2.7%    |
| OPNsense 22.1         | 2         | 1.8%    |
| OpenBSD 6.7           | 2         | 1.8%    |
| GhostBSD 22.01.12     | 2         | 1.8%    |
| FreeBSD 13.1-STABLE   | 2         | 1.8%    |
| FreeBSD 13.0-RC5      | 2         | 1.8%    |
| FreeBSD 13.0-p6       | 2         | 1.8%    |
| FreeBSD 13.0-p3       | 2         | 1.8%    |
| FreeBSD 13.0-p1       | 2         | 1.8%    |
| FreeBSD 12.1-p10      | 2         | 1.8%    |
| OPNsense 22.1.7       | 1         | 0.9%    |
| OPNsense 21.7.2       | 1         | 0.9%    |
| OPNsense 21.7.1       | 1         | 0.9%    |
| OPNsense 21.1.6       | 1         | 0.9%    |
| OPNsense 21.1.3       | 1         | 0.9%    |
| NomadBSD 5806f915     | 1         | 0.9%    |
| helloSystem 0.8.0     | 1         | 0.9%    |
| helloSystem 0.6.0     | 1         | 0.9%    |
| helloSystem 0.5.0     | 1         | 0.9%    |
| GhostBSD 22.04.30     | 1         | 0.9%    |
| GhostBSD 22.04.06     | 1         | 0.9%    |
| GhostBSD 21.08.27     | 1         | 0.9%    |
| FuryBSD 12.1-p6       | 1         | 0.9%    |
| FreeBSD 13.0-RC3      | 1         | 0.9%    |
| FreeBSD 13.0-p5       | 1         | 0.9%    |
| FreeBSD 13.0-p2       | 1         | 0.9%    |
| FreeBSD 13.0-CURRENT  | 1         | 0.9%    |
| FreeBSD 12.2-STABLE   | 1         | 0.9%    |
| FreeBSD 12.2-p3       | 1         | 0.9%    |
| FreeBSD 12.1-STABLE   | 1         | 0.9%    |
| FreeBSD 12.1-p9       | 1         | 0.9%    |
| FreeBSD 12.1-p8       | 1         | 0.9%    |
| FreeBSD 12.1-p7       | 1         | 0.9%    |
| FreeBSD 12.1-p5       | 1         | 0.9%    |
| FreeBSD 12.1-p22-HBSD | 1         | 0.9%    |
| FreeBSD 12.1          | 1         | 0.9%    |
| FreeBSD 11.3-p6       | 1         | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 40        | 40.82%  |
| OpenBSD     | 18        | 18.37%  |
| helloSystem | 14        | 14.29%  |
| NomadBSD    | 10        | 10.2%   |
| GhostBSD    | 9         | 9.18%   |
| OPNsense    | 6         | 6.12%   |
| FuryBSD     | 1         | 1.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 85        | 97.7%   |
| macppc | 1         | 1.15%   |
| i386   | 1         | 1.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 17        | 17%     |
| XFCE         | 15        | 15%     |
| fvwm         | 15        | 15%     |
| Openbox      | 11        | 11%     |
| KDE5         | 11        | 11%     |
| Console      | 9         | 9%      |
| MATE         | 6         | 6%      |
| TWM          | 4         | 4%      |
| i3           | 4         | 4%      |
| GNOME        | 4         | 4%      |
| AwesomeWM    | 2         | 2%      |
| X-Cinnamon   | 1         | 1%      |
| LXDE         | 1         | 1%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 77        | 86.52%  |
| Console | 12        | 13.48%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 37        | 39.36%  |
| SLiM    | 31        | 32.98%  |
| LightDM | 12        | 12.77%  |
| XDM     | 5         | 5.32%   |
| SDDM    | 5         | 5.32%   |
| GDM     | 4         | 4.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 33        | 34.74%  |
| fr_FR           | 23        | 24.21%  |
| en_US           | 21        | 22.11%  |
| C               | 13        | 13.68%  |
| en_GB           | 2         | 2.11%   |
| de_DE           | 2         | 2.11%   |
| en_US.ISO8859-1 | 1         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 70        | 79.55%  |
| BIOS | 18        | 20.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 46        | 49.46%  |
| Ufs    | 24        | 25.81%  |
| Ffs    | 18        | 19.35%  |
| Cd9660 | 5         | 5.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 69        | 77.53%  |
| MBR     | 19        | 21.35%  |
| Unknown | 1         | 1.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 31        | 35.63%  |
| Dell                | 15        | 17.24%  |
| ASUSTek Computer    | 10        | 11.49%  |
| Hewlett-Packard     | 7         | 8.05%   |
| Apple               | 4         | 4.6%    |
| Deciso              | 3         | 3.45%   |
| Acer                | 3         | 3.45%   |
| TUXEDO              | 2         | 2.3%    |
| MSI                 | 2         | 2.3%    |
| Sony                | 1         | 1.15%   |
| SECO                | 1         | 1.15%   |
| Samsung Electronics | 1         | 1.15%   |
| Notebook            | 1         | 1.15%   |
| Intel               | 1         | 1.15%   |
| Google              | 1         | 1.15%   |
| Gigabyte Technology | 1         | 1.15%   |
| Fujitsu             | 1         | 1.15%   |
| Clevo               | 1         | 1.15%   |
| Alienware           | 1         | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Deciso Netboard A20                      | 3         | 3.45%   |
| TUXEDO InfinityBook13V3                  | 2         | 2.3%    |
| Dell Latitude 3410                       | 2         | 2.3%    |
| Sony VGN-AR630E                          | 1         | 1.15%   |
| SECO UDOO x86                            | 1         | 1.15%   |
| Samsung R720                             | 1         | 1.15%   |
| Notebook W510LU                          | 1         | 1.15%   |
| MSI P65 Creator 8RE                      | 1         | 1.15%   |
| MSI MS-N033                              | 1         | 1.15%   |
| Lenovo ThinkPad X280 20KFCTO1WW          | 1         | 1.15%   |
| Lenovo ThinkPad X250 20CLS7WY04          | 1         | 1.15%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 1.15%   |
| Lenovo ThinkPad X230 2325AJ9             | 1         | 1.15%   |
| Lenovo ThinkPad X220 4290W42             | 1         | 1.15%   |
| Lenovo ThinkPad X220 4290EE8             | 1         | 1.15%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1TG00 | 1         | 1.15%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 1.15%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2K000 | 1         | 1.15%   |
| Lenovo ThinkPad W540 20BG001KUK          | 1         | 1.15%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 1.15%   |
| Lenovo ThinkPad T580 20LAS2TG00          | 1         | 1.15%   |
| Lenovo ThinkPad T500 2056Y2Z             | 1         | 1.15%   |
| Lenovo ThinkPad T495 20NJCTO1WW          | 1         | 1.15%   |
| Lenovo ThinkPad T490 20N20009FR          | 1         | 1.15%   |
| Lenovo ThinkPad T450s 20BWS0L600         | 1         | 1.15%   |
| Lenovo ThinkPad T430 23495P8             | 1         | 1.15%   |
| Lenovo ThinkPad T420 4236NUG             | 1         | 1.15%   |
| Lenovo ThinkPad T420 42368A3             | 1         | 1.15%   |
| Lenovo ThinkPad T400 6475P1G             | 1         | 1.15%   |
| Lenovo ThinkPad T14 Gen 1 20S0CTO1WW     | 1         | 1.15%   |
| Lenovo ThinkPad S5-S540 20B3001XFR       | 1         | 1.15%   |
| Lenovo ThinkPad P50 20EQS0U60C           | 1         | 1.15%   |
| Lenovo ThinkPad P14s Gen 1 20Y1002AFR    | 1         | 1.15%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW     | 1         | 1.15%   |
| Lenovo ThinkPad A485 20MVS0FD00          | 1         | 1.15%   |
| Lenovo Legion Y540-15IRH 81SX            | 1         | 1.15%   |
| Lenovo Legion 5 15ARH05 82B5             | 1         | 1.15%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 1.15%   |
| Lenovo G500 20236                        | 1         | 1.15%   |
| Lenovo Flex 2-15 20405                   | 1         | 1.15%   |
| Intel H81U                               | 1         | 1.15%   |
| HP ZBook 15                              | 1         | 1.15%   |
| HP ProBook 650 G5                        | 1         | 1.15%   |
| HP Pavilion Gaming Laptop 17-cd0xxx      | 1         | 1.15%   |
| HP EliteBook 8440p                       | 1         | 1.15%   |
| HP EliteBook 820 G1                      | 1         | 1.15%   |
| HP EliteBook 2530p                       | 1         | 1.15%   |
| HP Compaq 15                             | 1         | 1.15%   |
| Google Terra                             | 1         | 1.15%   |
| Gigabyte P15FR7                          | 1         | 1.15%   |
| Fujitsu LIFEBOOK NH570                   | 1         | 1.15%   |
| Dell Vostro 5481                         | 1         | 1.15%   |
| Dell Studio 1555                         | 1         | 1.15%   |
| Dell Precision 7730                      | 1         | 1.15%   |
| Dell Latitude E6420                      | 1         | 1.15%   |
| Dell Latitude E6230                      | 1         | 1.15%   |
| Dell Latitude E5450                      | 1         | 1.15%   |
| Dell Latitude E5440                      | 1         | 1.15%   |
| Dell Latitude 7490                       | 1         | 1.15%   |
| Dell Latitude 5490                       | 1         | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 26        | 29.89%  |
| Dell Latitude           | 10        | 11.49%  |
| HP EliteBook            | 3         | 3.45%   |
| Deciso Netboard         | 3         | 3.45%   |
| Acer Aspire             | 3         | 3.45%   |
| TUXEDO InfinityBook13V3 | 2         | 2.3%    |
| Lenovo Legion           | 2         | 2.3%    |
| Dell Inspiron           | 2         | 2.3%    |
| Sony VGN-AR630E         | 1         | 1.15%   |
| SECO UDOO               | 1         | 1.15%   |
| Samsung R720            | 1         | 1.15%   |
| Notebook W510LU         | 1         | 1.15%   |
| MSI P65                 | 1         | 1.15%   |
| MSI MS-N033             | 1         | 1.15%   |
| Lenovo IdeaPad          | 1         | 1.15%   |
| Lenovo G500             | 1         | 1.15%   |
| Lenovo Flex             | 1         | 1.15%   |
| Intel H81U              | 1         | 1.15%   |
| HP ZBook                | 1         | 1.15%   |
| HP ProBook              | 1         | 1.15%   |
| HP Pavilion             | 1         | 1.15%   |
| HP Compaq               | 1         | 1.15%   |
| Google Terra            | 1         | 1.15%   |
| Gigabyte P15FR7         | 1         | 1.15%   |
| Fujitsu LIFEBOOK        | 1         | 1.15%   |
| Dell Vostro             | 1         | 1.15%   |
| Dell Studio             | 1         | 1.15%   |
| Dell Precision          | 1         | 1.15%   |
| Clevo W240EU            | 1         | 1.15%   |
| ASUS X75VC              | 1         | 1.15%   |
| ASUS X751LN             | 1         | 1.15%   |
| ASUS X550LC             | 1         | 1.15%   |
| ASUS X102BA             | 1         | 1.15%   |
| ASUS UX305FA            | 1         | 1.15%   |
| ASUS S550CA             | 1         | 1.15%   |
| ASUS N75SF              | 1         | 1.15%   |
| ASUS K53TA              | 1         | 1.15%   |
| ASUS E200HA             | 1         | 1.15%   |
| ASUS 1015PEM            | 1         | 1.15%   |
| Apple PowerBook5        | 1         | 1.15%   |
| Apple MacBookPro8       | 1         | 1.15%   |
| Apple MacBook5          | 1         | 1.15%   |
| Apple MacBook4          | 1         | 1.15%   |
| Alienware M18xR2        | 1         | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 13        | 14.94%  |
| 2019    | 13        | 14.94%  |
| 2015    | 8         | 9.2%    |
| 2011    | 8         | 9.2%    |
| 2021    | 6         | 6.9%    |
| 2013    | 6         | 6.9%    |
| 2018    | 5         | 5.75%   |
| 2014    | 5         | 5.75%   |
| 2017    | 4         | 4.6%    |
| 2016    | 4         | 4.6%    |
| 2010    | 4         | 4.6%    |
| 2009    | 3         | 3.45%   |
| 2022    | 2         | 2.3%    |
| 2012    | 2         | 2.3%    |
| 2008    | 2         | 2.3%    |
| 2007    | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 87        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 97.7%   |
| Yes  | 2         | 2.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 32        | 35.96%  |
| 16.01-24.0 | 23        | 25.84%  |
| 4.01-8.0   | 15        | 16.85%  |
| 32.01-64.0 | 8         | 8.99%   |
| 2.01-3.0   | 5         | 5.62%   |
| 3.01-4.0   | 3         | 3.37%   |
| 1.01-2.0   | 2         | 2.25%   |
| 24.01-32.0 | 1         | 1.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 51        | 54.84%  |
| 0.51-1.0   | 26        | 27.96%  |
| 1.01-2.0   | 10        | 10.75%  |
| 8.01-16.0  | 3         | 3.23%   |
| 2.01-3.0   | 2         | 2.15%   |
| 32.01-64.0 | 1         | 1.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 49        | 55.06%  |
| 2      | 26        | 29.21%  |
| 0      | 9         | 10.11%  |
| 3      | 3         | 3.37%   |
| 4      | 2         | 2.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 73.33%  |
| Yes       | 24        | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 90.91%  |
| No        | 8         | 9.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 94.25%  |
| No        | 5         | 5.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 59.09%  |
| No        | 36        | 40.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 87        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Paris                    | 17        | 17.35%  |
| Franconville             | 7         | 7.14%   |
| Bordeaux                 | 4         | 4.08%   |
| Fontenay-sous-Bois       | 3         | 3.06%   |
| Stiring-Wendel           | 2         | 2.04%   |
| Saint-Denis              | 2         | 2.04%   |
| Mâcon                   | 2         | 2.04%   |
| Dijon                    | 2         | 2.04%   |
| Asnieres-sur-Seine       | 2         | 2.04%   |
| Villeneuve-Saint-Georges | 1         | 1.02%   |
| Villejuif                | 1         | 1.02%   |
| Vertou                   | 1         | 1.02%   |
| Tulle                    | 1         | 1.02%   |
| Tournon-sur-RhÃ´ne     | 1         | 1.02%   |
| Toulouse                 | 1         | 1.02%   |
| St-Malo                  | 1         | 1.02%   |
| Soisy-sur-Seine          | 1         | 1.02%   |
| Sallanches               | 1         | 1.02%   |
| Saint-Saulge             | 1         | 1.02%   |
| Saint-Herblain           | 1         | 1.02%   |
| Saint-Germain-en-Laye    | 1         | 1.02%   |
| Saint-Genest-Lerpt       | 1         | 1.02%   |
| Rosny-sous-Bois          | 1         | 1.02%   |
| Rennes                   | 1         | 1.02%   |
| Quimper                  | 1         | 1.02%   |
| Poncins                  | 1         | 1.02%   |
| Noisy-le-Grand           | 1         | 1.02%   |
| Noirmoutier-en-l'Ile     | 1         | 1.02%   |
| Nogent-sur-Marne         | 1         | 1.02%   |
| Neuilly-sur-Marne        | 1         | 1.02%   |
| Nantes                   | 1         | 1.02%   |
| Nancy                    | 1         | 1.02%   |
| Montreuil                | 1         | 1.02%   |
| Montgeron                | 1         | 1.02%   |
| Montesquiu d'Albera      | 1         | 1.02%   |
| Modane                   | 1         | 1.02%   |
| Mirepeix                 | 1         | 1.02%   |
| Mions                    | 1         | 1.02%   |
| Marseille                | 1         | 1.02%   |
| Lyon                     | 1         | 1.02%   |
| Lanton                   | 1         | 1.02%   |
| Lamothe-Goas             | 1         | 1.02%   |
| Lalinde                  | 1         | 1.02%   |
| Guyancourt               | 1         | 1.02%   |
| Groslay                  | 1         | 1.02%   |
| Gretz-Armainvilliers     | 1         | 1.02%   |
| Fleury-Merogis           | 1         | 1.02%   |
| Ermont                   | 1         | 1.02%   |
| Corbarieu                | 1         | 1.02%   |
| Colombes                 | 1         | 1.02%   |
| Colmar                   | 1         | 1.02%   |
| Cognac                   | 1         | 1.02%   |
| Clichy-sous-Bois         | 1         | 1.02%   |
| Clermont                 | 1         | 1.02%   |
| Chaudeney-sur-Moselle    | 1         | 1.02%   |
| Chalon-sur-SaÃ´ne      | 1         | 1.02%   |
| Castillon-de-Castets     | 1         | 1.02%   |
| Castelginest             | 1         | 1.02%   |
| Bonnes                   | 1         | 1.02%   |
| Biot                     | 1         | 1.02%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 27     | 18.1%   |
| Seagate             | 14        | 22     | 13.33%  |
| Crucial             | 11        | 13     | 10.48%  |
| Toshiba             | 9         | 14     | 8.57%   |
| SanDisk             | 8         | 10     | 7.62%   |
| Kingston            | 8         | 10     | 7.62%   |
| WDC                 | 6         | 8      | 5.71%   |
| Transcend           | 5         | 6      | 4.76%   |
| Intel               | 4         | 7      | 3.81%   |
| NVMe                | 3         | 3      | 2.86%   |
| Micron Technology   | 3         | 6      | 2.86%   |
| HGST                | 3         | 6      | 2.86%   |
| China               | 3         | 3      | 2.86%   |
| SK hynix            | 2         | 2      | 1.9%    |
| SPCC                | 1         | 1      | 0.95%   |
| LDLC F6+            | 1         | 1      | 0.95%   |
| Integral            | 1         | 1      | 0.95%   |
| Hitachi             | 1         | 1      | 0.95%   |
| Generic             | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |
| EMTEC               | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB            | 3         | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.78%   |
| Kingston SA400S37240G 240GB               | 3         | 2.78%   |
| Crucial CT1000P1SSD8 1TB                  | 3         | 2.78%   |
| Toshiba MK2556GSY 250GB                   | 2         | 1.85%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 2         | 1.85%   |
| Samsung SSD 950 PRO 512GB                 | 2         | 1.85%   |
| Intel SSDPEKKF256G8L 256GB                | 2         | 1.85%   |
| Crucial CT960M500SSD1 960GB               | 2         | 1.85%   |
| Crucial CT1050MX300SSD1 1TB               | 2         | 1.85%   |
| China SH00M240GB                          | 2         | 1.85%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.93%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 0.93%   |
| WDC WD20SDRW-11VUUS0 2TB                  | 1         | 0.93%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.93%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 0.93%   |
| Transcend TS256GMTS800 256GB              | 1         | 0.93%   |
| Transcend TS256GMTS430S 256GB             | 1         | 0.93%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.93%   |
| Toshiba MQ01ACF032 320GB                  | 1         | 0.93%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.93%   |
| Toshiba MQ01ABD075 752GB                  | 1         | 0.93%   |
| Toshiba MK2546GSX_200 200GB               | 1         | 0.93%   |
| Toshiba MK1629GSGF 160GB                  | 1         | 0.93%   |
| SPCC Solid State Disk 512GB               | 1         | 0.93%   |
| SK hynix SKHynix_HFS001TDE9X081N 1TB      | 1         | 0.93%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.93%   |
| Seagate ST9750423AS 752GB                 | 1         | 0.93%   |
| Seagate ST95005620AS 500GB                | 1         | 0.93%   |
| Seagate ST9320423AS 320GB                 | 1         | 0.93%   |
| Seagate ST9320325AS 320GB                 | 1         | 0.93%   |
| Seagate ST9250827AS 250GB                 | 1         | 0.93%   |
| Seagate ST320LT012-9WS14C 320GB           | 1         | 0.93%   |
| Seagate ST3160212AS 160GB                 | 1         | 0.93%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB            | 1         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.93%   |
| Seagate ST1000LM014-1EJ164 1TB            | 1         | 0.93%   |
| SanDisk SSD U110 16GB                     | 1         | 0.93%   |
| SanDisk SSD PLUS 120GB                    | 1         | 0.93%   |
| SanDisk SSD G5 BICS4 1TB                  | 1         | 0.93%   |
| SanDisk SDSSDXP120G 120GB                 | 1         | 0.93%   |
| SanDisk SDSSDH3 500G                      | 1         | 0.93%   |
| SanDisk SDSSDA240G 240GB                  | 1         | 0.93%   |
| SanDisk SD7UB3Q256G1001 256GB             | 1         | 0.93%   |
| SanDisk SD7SN3Q128G1002 128GB             | 1         | 0.93%   |
| Samsung SSD PM830 FDE 2.5-inch 7mm 256GB  | 1         | 0.93%   |
| Samsung SSD 970 EVO Plus 2TB              | 1         | 0.93%   |
| Samsung SSD 960 PRO 512GB                 | 1         | 0.93%   |
| Samsung SSD 860 PRO 512GB                 | 1         | 0.93%   |
| Samsung SSD 860 EVO 250GB                 | 1         | 0.93%   |
| Samsung SSD 860 EVO 1TB                   | 1         | 0.93%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 0.93%   |
| Samsung SSD 850 EVO 1TB                   | 1         | 0.93%   |
| Samsung SSD 840 PRO Series 128GB          | 1         | 0.93%   |
| Samsung SSD 840 EVO 500GB                 | 1         | 0.93%   |
| Samsung PM981 NVMe 256GB                  | 1         | 0.93%   |
| Samsung MZVLB512HAJQ-000L7 512GB          | 1         | 0.93%   |
| Samsung MZVLB512HAJQ-000H1 512GB          | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 22     | 38.89%  |
| Toshiba             | 7         | 10     | 19.44%  |
| WDC                 | 4         | 4      | 11.11%  |
| NVMe                | 3         | 3      | 8.33%   |
| HGST                | 3         | 6      | 8.33%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| LDLC F6+            | 1         | 1      | 2.78%   |
| Hitachi             | 1         | 1      | 2.78%   |
| Generic             | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 16     | 20.83%  |
| SanDisk             | 8         | 10     | 16.67%  |
| Crucial             | 8         | 8      | 16.67%  |
| Kingston            | 7         | 8      | 14.58%  |
| Transcend           | 5         | 6      | 10.42%  |
| China               | 3         | 3      | 6.25%   |
| Toshiba             | 2         | 4      | 4.17%   |
| WDC                 | 1         | 1      | 2.08%   |
| SPCC                | 1         | 1      | 2.08%   |
| Micron Technology   | 1         | 4      | 2.08%   |
| Integral            | 1         | 1      | 2.08%   |
| EMTEC               | 1         | 1      | 2.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 41        | 63     | 44.09%  |
| HDD  | 33        | 50     | 35.48%  |
| NVMe | 19        | 31     | 20.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 113    | 77.91%  |
| NVMe | 19        | 31     | 22.09%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 77     | 65.38%  |
| 0.51-1.0   | 23        | 32     | 29.49%  |
| 1.01-2.0   | 4         | 4      | 5.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 30        | 31.91%  |
| 1-20       | 24        | 25.53%  |
| 251-500    | 13        | 13.83%  |
| 21-50      | 10        | 10.64%  |
| 501-1000   | 8         | 8.51%   |
| 51-100     | 6         | 6.38%   |
| 1001-2000  | 2         | 2.13%   |
| Unknown    | 1         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 73        | 82.02%  |
| 21-50    | 6         | 6.74%   |
| 101-250  | 6         | 6.74%   |
| 51-100   | 2         | 2.25%   |
| 501-1000 | 1         | 1.12%   |
| Unknown  | 1         | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 7.69%   |
| Toshiba MK1629GSGF 160GB              | 1         | 3      | 7.69%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 7.69%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 7.69%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 4      | 7.69%   |
| Seagate ST3160212AS 160GB             | 1         | 1      | 7.69%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 7.69%   |
| SanDisk SD7UB3Q256G1001 256GB         | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 840 EVO 500GB | 1         | 2      | 7.69%   |
| Kingston SUV500MS480G 480GB           | 1         | 1      | 7.69%   |
| HGST HTS545050A7E660 500GB            | 1         | 2      | 7.69%   |
| Crucial CT525MX300SSD1 528GB          | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 8      | 38.46%  |
| Toshiba             | 2         | 4      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| SanDisk             | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 2      | 7.69%   |
| Kingston            | 1         | 1      | 7.69%   |
| HGST                | 1         | 2      | 7.69%   |
| Crucial             | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 8      | 55.56%  |
| Toshiba | 2         | 4      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| HGST    | 1         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 15     | 66.67%  |
| SSD  | 4         | 5      | 33.33%  |

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
| Works    | 69        | 122    | 83.13%  |
| Malfunc  | 12        | 20     | 14.46%  |
| Detected | 2         | 2      | 2.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 65        | 67.01%  |
| Samsung Electronics         | 10        | 10.31%  |
| AMD                         | 10        | 10.31%  |
| Micron/Crucial Technology   | 3         | 3.09%   |
| SK hynix                    | 2         | 2.06%   |
| SanDisk                     | 2         | 2.06%   |
| Micron Technology           | 2         | 2.06%   |
| Nvidia                      | 1         | 1.03%   |
| KIOXIA                      | 1         | 1.03%   |
| Kingston Technology Company | 1         | 1.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 9.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 8.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 6.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7         | 6.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 5.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 5.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 4.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 4.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 4.81%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 2.88%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 2.88%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 3         | 2.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.92%   |
| Unknown                                                                          | 2         | 1.92%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.96%   |
| SK hynix BC511                                                                   | 1         | 0.96%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.96%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.96%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.96%   |
| Intel SSD 660P Series                                                            | 1         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.96%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.96%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.96%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 62        | 62.63%  |
| NVMe | 22        | 22.22%  |
| RAID | 10        | 10.1%   |
| IDE  | 5         | 5.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 74        | 84.09%  |
| AMD     | 13        | 14.77%  |
| PowerPC | 1         | 1.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz               | 4         | 4.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 4.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 3.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 2.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 2         | 2.27%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 2         | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 2         | 2.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 2.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 2.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 2         | 2.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 2         | 2.27%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 2         | 2.27%   |
| Intel Celeron CPU N3160 @ 1.60GHz               | 2         | 2.27%   |
| AMD EPYC 3201 8-Core Processor                  | 2         | 2.27%   |
| PowerPC 7447A (Revision 0x105)                  | 1         | 1.14%   |
| Intel CPU Version                               | 1         | 1.14%   |
| Intel Core M-5Y10c CPU @ 0.80GHz                | 1         | 1.14%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 1.14%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 1.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 1.14%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 1.14%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 1.14%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz              | 1         | 1.14%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 1.14%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 1.14%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 1         | 1.14%   |
| Intel Core i7-3940XM CPU @ 3.00GHz              | 1         | 1.14%   |
| Intel Core i7-3740QM CPU @ 2.70GHz              | 1         | 1.14%   |
| Intel Core i7-2675QM CPU @ 2.20GHz              | 1         | 1.14%   |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 1.14%   |
| Intel Core i5-8400H CPU @ 2.50GHz               | 1         | 1.14%   |
| Intel Core i5-7300U CPU @ 2.60GHz               | 1         | 1.14%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.14%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 1.14%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.14%   |
| Intel Core i5-2540M CPU @ 2.60GH                | 1         | 1.14%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 1         | 1.14%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 1.14%   |
| Intel Core i3-4025U CPU @ 1.90GHz               | 1         | 1.14%   |
| Intel Core i3-4010U CPU @ 1.70GHz               | 1         | 1.14%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 1.14%   |
| Intel Core i3-3130M CPU @ 2.60GHz               | 1         | 1.14%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 1         | 1.14%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 1         | 1.14%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 1         | 1.14%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 1         | 1.14%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 1         | 1.14%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz            | 1         | 1.14%   |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz            | 1         | 1.14%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 1         | 1.14%   |
| Intel Celeron CPU 1005M @ 1.90GHz               | 1         | 1.14%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1         | 1.14%   |
| Intel Atom CPU N550 @ 1.50GHz                   | 1         | 1.14%   |
| Intel Atom CPU N280 @ 1.66GH                    | 1         | 1.14%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 1         | 1.14%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 1         | 1.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 29        | 32.95%  |
| Intel Core i7    | 21        | 23.86%  |
| Intel Core i3    | 8         | 9.09%   |
| Intel Core 2 Duo | 7         | 7.95%   |
| Intel Celeron    | 4         | 4.55%   |
| Intel Atom       | 3         | 3.41%   |
| AMD Ryzen 7 PRO  | 3         | 3.41%   |
| AMD Ryzen 7      | 3         | 3.41%   |
| AMD EPYC         | 3         | 3.41%   |
| Other            | 2         | 2.27%   |
| Intel Core M     | 1         | 1.14%   |
| AMD Ryzen 5      | 1         | 1.14%   |
| AMD E1           | 1         | 1.14%   |
| AMD A6           | 1         | 1.14%   |
| AMD A4           | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 39        | 44.32%  |
| 4       | 30        | 34.09%  |
| Unknown | 8         | 9.09%   |
| 8       | 5         | 5.68%   |
| 16      | 3         | 3.41%   |
| 12      | 1         | 1.14%   |
| 6       | 1         | 1.14%   |
| 1       | 1         | 1.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 81        | 93.1%   |
| Unknown | 4         | 4.6%    |
| 2       | 2         | 2.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 60        | 68.18%  |
| 1       | 19        | 21.59%  |
| Unknown | 9         | 10.23%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 22        | 25%     |
| Haswell     | 11        | 12.5%   |
| IvyBridge   | 8         | 9.09%   |
| SandyBridge | 7         | 7.95%   |
| Penryn      | 7         | 7.95%   |
| Skylake     | 5         | 5.68%   |
| Broadwell   | 5         | 5.68%   |
| Zen         | 4         | 4.55%   |
| Silvermont  | 4         | 4.55%   |
| Unknown     | 3         | 3.41%   |
| Zen+        | 2         | 2.27%   |
| Zen 2       | 2         | 2.27%   |
| Westmere    | 2         | 2.27%   |
| Jaguar      | 2         | 2.27%   |
| Bonnell     | 2         | 2.27%   |
| K10 Llano   | 1         | 1.14%   |
| Core        | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 65.31%  |
| Nvidia | 19        | 19.39%  |
| AMD    | 15        | 15.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 8.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 6.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 4.95%   |
| Intel HD Graphics 620                                                                    | 5         | 4.95%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 3.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 3.96%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.97%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.98%   |
| Intel HD Graphics 530                                                                    | 2         | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.98%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.98%   |
| AMD Renoir                                                                               | 2         | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.98%   |
| AMD Lucienne                                                                             | 2         | 1.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.99%   |
| Nvidia TU117M                                                                            | 1         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.99%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.99%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.99%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.99%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.99%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.99%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.99%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.99%   |
| Nvidia GK104M [GeForce GTX 780M]                                                         | 1         | 0.99%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.99%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.99%   |
| Nvidia G86M [GeForce 8400M GT]                                                           | 1         | 0.99%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.99%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.99%   |
| Intel HD Graphics 630                                                                    | 1         | 0.99%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 0.99%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.99%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.99%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 0.99%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                                  | 1         | 0.99%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                            | 1         | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.99%   |
| AMD Kabini [Radeon HD 8210]                                                              | 1         | 0.99%   |
| AMD Kabini [Radeon HD 8180]                                                              | 1         | 0.99%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 53.41%  |
| 1 x AMD        | 12        | 13.64%  |
| Intel + Nvidia | 11        | 12.5%   |
| 1 x Nvidia     | 7         | 7.95%   |
| 2 x Intel      | 5         | 5.68%   |
| Other          | 3         | 3.41%   |
| 2 x AMD        | 1         | 1.14%   |
| Intel + AMD    | 1         | 1.14%   |
| AMD + Nvidia   | 1         | 1.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 86.52%  |
| Proprietary | 6         | 6.74%   |
| Unknown     | 6         | 6.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 92.05%  |
| 0.01-0.5   | 3         | 3.41%   |
| 5.01-6.0   | 2         | 2.27%   |
| 3.01-4.0   | 1         | 1.14%   |
| 0.51-1.0   | 1         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 22.08%  |
| LG Display              | 13        | 16.88%  |
| Chimei Innolux          | 13        | 16.88%  |
| BOE                     | 7         | 9.09%   |
| Samsung Electronics     | 5         | 6.49%   |
| Chi Mei Optoelectronics | 4         | 5.19%   |
| Philips                 | 3         | 3.9%    |
| Apple                   | 3         | 3.9%    |
| Lenovo                  | 2         | 2.6%    |
| Iiyama                  | 2         | 2.6%    |
| Nvidia                  | 1         | 1.3%    |
| IBM                     | 1         | 1.3%    |
| Hewlett-Packard         | 1         | 1.3%    |
| Goldstar                | 1         | 1.3%    |
| Dell                    | 1         | 1.3%    |
| CSO                     | 1         | 1.3%    |
| CPT                     | 1         | 1.3%    |
| Acer                    | 1         | 1.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch             | 3         | 3.9%    |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                  | 2         | 2.6%    |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch          | 2         | 2.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch  | 2         | 2.6%    |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch            | 2         | 2.6%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch             | 2         | 2.6%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch     | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch      | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch      | 1         | 1.3%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch      | 1         | 1.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 1         | 1.3%    |
| Philips PHL 439P1 PHL0973 3840x2160 940x530mm 42.5-inch                   | 1         | 1.3%    |
| Nvidia LCD Monitor Default Flat Panel 1440x900                            | 1         | 1.3%    |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD063F 1920x1080 380x210mm 17.1-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch              | 1         | 1.3%    |
| LG Display LCD Monitor LGD0438 1366x768 340x190mm 15.3-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD0390 1600x900 380x210mm 17.1-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD036C 1366x768 280x160mm 12.7-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD0366 1600x900 310x170mm 13.9-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch               | 1         | 1.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 1         | 1.3%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                  | 1         | 1.3%    |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                   | 1         | 1.3%    |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                      | 1         | 1.3%    |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                      | 1         | 1.3%    |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                     | 1         | 1.3%    |
| Hewlett-Packard M27f FHD HPN370A 1920x1080 610x360mm 27.9-inch            | 1         | 1.3%    |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 1         | 1.3%    |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                         | 1         | 1.3%    |
| CSO LCD Monitor CSO1400 3840x2160 310x170mm 13.9-inch                     | 1         | 1.3%    |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                      | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 380x210mm 17.1-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 340x190mm 15.3-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN152E 1920x1080 340x190mm 15.3-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 310x170mm 13.9-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 310x170mm 13.9-inch          | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch           | 1         | 1.3%    |
| Chimei Innolux LCD Monitor CMN1372 1920x1080 290x170mm 13.2-inch          | 1         | 1.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 380x210mm 17.1-inch | 1         | 1.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.3%    |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                     | 1         | 1.3%    |
| BOE LCD Monitor BOE0806 1920x1080 310x170mm 13.9-inch                     | 1         | 1.3%    |
| BOE LCD Monitor BOE07E8 1366x768 310x170mm 13.9-inch                      | 1         | 1.3%    |
| BOE LCD Monitor BOE070D 1366x768 310x170mm 13.9-inch                      | 1         | 1.3%    |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                     | 1         | 1.3%    |
| BOE LCD Monitor BOE06EE 1920x1080 310x170mm 13.9-inch                     | 1         | 1.3%    |
| BOE LCD Monitor BOE06A5 1366x768 340x190mm 15.3-inch                      | 1         | 1.3%    |
| AU Optronics LCD Monitor AUO9314 1280x800 260x160mm 12.0-inch             | 1         | 1.3%    |
| AU Optronics LCD Monitor AUO48EC 1366x768 340x190mm 15.3-inch             | 1         | 1.3%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch             | 1         | 1.3%    |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch            | 1         | 1.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 47.3%   |
| 1366x768 (WXGA)    | 26        | 35.14%  |
| 1280x800 (WXGA)    | 4         | 5.41%   |
| 3840x2160 (4K)     | 3         | 4.05%   |
| 1600x900 (HD+)     | 2         | 2.7%    |
| 1680x1050 (WSXGA+) | 1         | 1.35%   |
| 1440x960           | 1         | 1.35%   |
| 1440x900 (WXGA+)   | 1         | 1.35%   |
| 1024x600           | 1         | 1.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 24        | 31.17%  |
| 13      | 20        | 25.97%  |
| 12      | 12        | 15.58%  |
| 17      | 5         | 6.49%   |
| 24      | 3         | 3.9%    |
| 23      | 3         | 3.9%    |
| 27      | 2         | 2.6%    |
| 10      | 2         | 2.6%    |
| 42      | 1         | 1.3%    |
| 21      | 1         | 1.3%    |
| 18      | 1         | 1.3%    |
| 14      | 1         | 1.3%    |
| 11      | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 41        | 53.25%  |
| 201-300     | 19        | 24.68%  |
| 501-600     | 7         | 9.09%   |
| 351-400     | 5         | 6.49%   |
| 401-500     | 2         | 2.6%    |
| 601-700     | 1         | 1.3%    |
| 901-1000    | 1         | 1.3%    |
| Unknown     | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 88.24%  |
| 16/10   | 5         | 7.35%   |
| 3/2     | 2         | 2.94%   |
| Unknown | 1         | 1.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 20        | 25.97%  |
| 91-100         | 20        | 25.97%  |
| 61-70          | 12        | 15.58%  |
| 201-250        | 7         | 9.09%   |
| 121-130        | 5         | 6.49%   |
| 101-110        | 4         | 5.19%   |
| 41-50          | 2         | 2.6%    |
| 301-350        | 2         | 2.6%    |
| 71-80          | 1         | 1.3%    |
| 51-60          | 1         | 1.3%    |
| 141-150        | 1         | 1.3%    |
| 501-1000       | 1         | 1.3%    |
| Unknown        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 49.33%  |
| 101-120       | 23        | 30.67%  |
| 51-100        | 9         | 12%     |
| 161-240       | 4         | 5.33%   |
| More than 240 | 1         | 1.33%   |
| Unknown       | 1         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 61        | 65.59%  |
| 0     | 22        | 23.66%  |
| 2     | 10        | 10.75%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 64        | 46.72%  |
| Realtek Semiconductor    | 32        | 23.36%  |
| Qualcomm Atheros         | 19        | 13.87%  |
| Broadcom                 | 7         | 5.11%   |
| Marvell Technology Group | 3         | 2.19%   |
| AMD                      | 3         | 2.19%   |
| Edimax Technology        | 2         | 1.46%   |
| Xiaomi                   | 1         | 0.73%   |
| Ralink Technology        | 1         | 0.73%   |
| Ralink                   | 1         | 0.73%   |
| Qualcomm                 | 1         | 0.73%   |
| Nvidia                   | 1         | 0.73%   |
| Dell                     | 1         | 0.73%   |
| Apple                    | 1         | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 25        | 14.12%  |
| Intel Wireless 8265 / 8275                                              | 8         | 4.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 4.52%   |
| Intel Wireless 7265                                                     | 7         | 3.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 4         | 2.26%   |
| Intel Wireless 8260                                                     | 4         | 2.26%   |
| Intel Wireless 7260                                                     | 4         | 2.26%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.26%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 2.26%   |
| Intel Ethernet Connection (3) I218-LM                                   | 4         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.69%   |
| Intel I210 Gigabit Network Connection                                   | 3         | 1.69%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.69%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0               | 3         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 1.13%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.13%   |
| Intel Wireless 3165                                                     | 2         | 1.13%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 1.13%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.56%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.56%   |
| Qualcomm ALCATEL Composite RNDIS Interface                              | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Intel WiFi Link 5100                                                    | 1         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                   | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                                   | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                   | 1         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (10) I219-LM                                  | 1         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.56%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.56%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 66.67%  |
| Qualcomm Atheros      | 17        | 18.89%  |
| Broadcom              | 5         | 5.56%   |
| Realtek Semiconductor | 3         | 3.33%   |
| Edimax Technology     | 2         | 2.22%   |
| Ralink Technology     | 1         | 1.11%   |
| Ralink                | 1         | 1.11%   |
| Dell                  | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 8         | 8.89%   |
| Intel Wireless 7265                                                     | 7         | 7.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 7.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 6.67%   |
| Intel Wireless 8260                                                     | 4         | 4.44%   |
| Intel Wireless 7260                                                     | 4         | 4.44%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 4.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 4.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 4.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.22%   |
| Intel Wireless-AC 9260                                                  | 2         | 2.22%   |
| Intel Wireless 3165                                                     | 2         | 2.22%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.11%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1         | 1.11%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| Intel WiFi Link 5100                                                    | 1         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.11%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.11%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.11%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.11%   |
| Dell Hub of E-Port Replicator                                           | 1         | 1.11%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.11%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.11%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 39        | 45.88%  |
| Realtek Semiconductor    | 29        | 34.12%  |
| Qualcomm Atheros         | 5         | 5.88%   |
| Marvell Technology Group | 3         | 3.53%   |
| Broadcom                 | 3         | 3.53%   |
| AMD                      | 3         | 3.53%   |
| Xiaomi                   | 1         | 1.18%   |
| Qualcomm                 | 1         | 1.18%   |
| Nvidia                   | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 29.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 9.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.71%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 4.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 4.71%   |
| Intel I210 Gigabit Network Connection                             | 3         | 3.53%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 3.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.53%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 3.53%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 3         | 3.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.35%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.35%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.18%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.18%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.18%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 1.18%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.18%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.18%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.18%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.18%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.18%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.18%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.18%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.18%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 50%     |
| Ethernet | 80        | 48.78%  |
| Modem    | 1         | 0.61%   |
| Unknown  | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 65        | 50.78%  |
| WiFi     | 63        | 49.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 84.09%  |
| 1     | 8         | 9.09%   |
| 6     | 3         | 3.41%   |
| 3     | 3         | 3.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 85.71%  |
| Yes  | 13        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 69.81%  |
| Broadcom                        | 6         | 11.32%  |
| Apple                           | 3         | 5.66%   |
| IMC Networks                    | 2         | 3.77%   |
| Foxconn / Hon Hai               | 2         | 3.77%   |
| Dell                            | 2         | 3.77%   |
| Qualcomm Atheros Communications | 1         | 1.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 17        | 32.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 7         | 13.21%  |
| Intel AX201 Bluetooth                              | 4         | 7.55%   |
| Intel AX200 Bluetooth                              | 4         | 7.55%   |
| Intel Centrino Bluetooth Wireless Transceiver      | 2         | 3.77%   |
| Foxconn / Hon Hai Bluetooth USB Module             | 2         | 3.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]         | 2         | 3.77%   |
| Broadcom BCM2045B (BDC-2.1)                        | 2         | 3.77%   |
| Apple Bluetooth Host Controller                    | 2         | 3.77%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1            | 1         | 1.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter           | 1         | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                   | 1         | 1.89%   |
| Intel AX210 Bluetooth                              | 1         | 1.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1        | 1         | 1.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS   | 1         | 1.89%   |
| Dell DW375 Bluetooth Module                        | 1         | 1.89%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module        | 1         | 1.89%   |
| Broadcom BCM43142A0 Bluetooth Module               | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 1         | 1.89%   |
| Apple Built-in iSight (no firmware loaded)         | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 72        | 72%     |
| AMD      | 16        | 16%     |
| Nvidia   | 8         | 8%      |
| Lenovo   | 2         | 2%      |
| Logitech | 1         | 1%      |
| DSEA A/S | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 8.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 7.26%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 7.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 6.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 5.65%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 4.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 4.03%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 4.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 4.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 2.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.61%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.61%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.61%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.61%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.81%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.81%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.81%   |
| Logitech Logitech Stereo H650e                                                                    | 1         | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.81%   |
| DSEA A/S EPOS BTD 800                                                                             | 1         | 0.81%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.81%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 33.33%  |
| SK hynix            | 15        | 16.67%  |
| Unknown             | 9         | 10%     |
| Crucial             | 7         | 7.78%   |
| Micron Technology   | 6         | 6.67%   |
| Kingston            | 6         | 6.67%   |
| Elpida              | 3         | 3.33%   |
| Corsair             | 3         | 3.33%   |
| Transcend           | 2         | 2.22%   |
| A-DATA Technology   | 2         | 2.22%   |
| V-Color             | 1         | 1.11%   |
| SHARETRONIC         | 1         | 1.11%   |
| Patriot             | 1         | 1.11%   |
| Nanya Technology    | 1         | 1.11%   |
| G.Skill             | 1         | 1.11%   |
| CSX                 | 1         | 1.11%   |
| Avant               | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 3         | 3.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 3.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 3.06%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s          | 2         | 2.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 2.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 2.04%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2.04%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.04%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 2.04%   |
| Crucial RAM CT204864BF160B.C16 16GB SODIMM DDR3 1600MT/s     | 2         | 2.04%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 2.04%   |
| A-DATA RAM AO1P32NCST2-BZ6SHD 16384MB SODIMM DDR4 3200MT/s   | 2         | 2.04%   |
| V-Color RAM TN48G24S817-VHA/R 8GB SODIMM DDR4 2400MT/s       | 1         | 1.02%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 1.02%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 1.02%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 1.02%   |
| Unknown RAM Module 4GB SODIMM 533MT/s                        | 1         | 1.02%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s             | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                  | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                        | 1         | 1.02%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 1         | 1.02%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s        | 1         | 1.02%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.02%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.02%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.02%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.02%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 1.02%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s              | 1         | 1.02%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s           | 1         | 1.02%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.02%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.02%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.02%   |
| Samsung RAM M471B1G73QH0-CH9 8GB SODIMM DDR3 1333MT/s        | 1         | 1.02%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1         | 1.02%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.02%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.02%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s       | 1         | 1.02%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.02%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 1         | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.02%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.02%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 1.02%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s        | 1         | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.02%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.02%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1600MT/s              | 1         | 1.02%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s       | 1         | 1.02%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s         | 1         | 1.02%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.02%   |
| Patriot RAM Module 8GB SODIMM DDR3 1333MT/s                  | 1         | 1.02%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s         | 1         | 1.02%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 33        | 46.48%  |
| DDR4    | 28        | 39.44%  |
| LPDDR3  | 4         | 5.63%   |
| DDR2    | 4         | 5.63%   |
| Unknown | 2         | 2.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 95.83%  |
| Row Of Chips | 1         | 1.39%   |
| Chip         | 1         | 1.39%   |
| Unknown      | 1         | 1.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 29        | 37.18%  |
| 4096  | 26        | 33.33%  |
| 16384 | 12        | 15.38%  |
| 2048  | 9         | 11.54%  |
| 32768 | 1         | 1.28%   |
| 1024  | 1         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 33.77%  |
| 2667    | 9         | 11.69%  |
| 3200    | 8         | 10.39%  |
| 2400    | 8         | 10.39%  |
| 1333    | 7         | 9.09%   |
| 1334    | 5         | 6.49%   |
| 2133    | 3         | 3.9%    |
| 1867    | 3         | 3.9%    |
| 667     | 2         | 2.6%    |
| Unknown | 2         | 2.6%    |
| 1200    | 1         | 1.3%    |
| 1067    | 1         | 1.3%    |
| 975     | 1         | 1.3%    |
| 533     | 1         | 1.3%    |

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
| Chicony Electronics                    | 23        | 35.94%  |
| Sunplus Innovation Technology          | 8         | 12.5%   |
| Acer                                   | 6         | 9.38%   |
| Realtek Semiconductor                  | 5         | 7.81%   |
| IMC Networks                           | 5         | 7.81%   |
| Microdia                               | 4         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 4.69%   |
| Syntek                                 | 2         | 3.13%   |
| Lite-On Technology                     | 2         | 3.13%   |
| Alcor Micro                            | 2         | 3.13%   |
| Suyin                                  | 1         | 1.56%   |
| Sonix Technology                       | 1         | 1.56%   |
| Quanta                                 | 1         | 1.56%   |
| Apple                                  | 1         | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 9         | 14.06%  |
| Sunplus Integrated_Webcam_HD                                               | 5         | 7.81%   |
| Acer Integrated Camera                                                     | 3         | 4.69%   |
| Realtek USB Camera                                                         | 2         | 3.13%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 3.13%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.13%   |
| IMC Networks EasyCamera                                                    | 2         | 3.13%   |
| Chicony HD WebCam                                                          | 2         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 3.13%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.56%   |
| Syntek Integrated Camera                                                   | 1         | 1.56%   |
| Suyin Laptop_Integrated_Webcam_FHD                                         | 1         | 1.56%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 1.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.56%   |
| Sunplus Asus Webcam                                                        | 1         | 1.56%   |
| Sonix USB 2.0 Camera                                                       | 1         | 1.56%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.56%   |
| Quanta HD WebCam                                                           | 1         | 1.56%   |
| Microdia Integrated Webcam                                                 | 1         | 1.56%   |
| Microdia Dell Integrated HD Webcam                                         | 1         | 1.56%   |
| Lite-On Realtek DMFT - RGB                                                 | 1         | 1.56%   |
| Lite-On Integrated Camera                                                  | 1         | 1.56%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.56%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.56%   |
| IMC Networks Integrated Camera                                             | 1         | 1.56%   |
| Chicony UVC 1.00 device HD UVC WebCam                                      | 1         | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.56%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.56%   |
| Chicony ThinkPad T490 Webcam                                               | 1         | 1.56%   |
| Chicony Sonix ST50220 USB Video Camera                                     | 1         | 1.56%   |
| Chicony Ltd., USB2.0 HD UVC WebCam                                         | 1         | 1.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.56%   |
| Chicony HP Webcam [2 MP]                                                   | 1         | 1.56%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.56%   |
| Chicony Chicony USB2.0 Camera                                              | 1         | 1.56%   |
| Chicony Chicony USB 2.0 Camera                                             | 1         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.56%   |
| Apple FaceTime HD Camera                                                   | 1         | 1.56%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.56%   |
| Alcor Micro ASUS USB2.0 WebCam                                             | 1         | 1.56%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 1.56%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.56%   |
| Acer HD Webcam                                                             | 1         | 1.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 37.5%   |
| Synaptics                  | 3         | 18.75%  |
| AuthenTec                  | 3         | 18.75%  |
| Upek                       | 1         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 18.75%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 12.5%   |
| AuthenTec AES2810                                                            | 2         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 6.25%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 6.25%   |

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
| 1     | 29        | 29.9%   |
| 2     | 27        | 27.84%  |
| 3     | 16        | 16.49%  |
| 0     | 11        | 11.34%  |
| 4     | 8         | 8.25%   |
| 6     | 4         | 4.12%   |
| 7     | 1         | 1.03%   |
| 5     | 1         | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 64        | 38.55%  |
| Bluetooth                | 27        | 16.27%  |
| Card reader              | 20        | 12.05%  |
| Net/wireless             | 17        | 10.24%  |
| Fingerprint reader       | 13        | 7.83%   |
| Firewire controller      | 10        | 6.02%   |
| Graphics card            | 4         | 2.41%   |
| Storage/raid             | 3         | 1.81%   |
| Storage                  | 3         | 1.81%   |
| Sound                    | 3         | 1.81%   |
| Network                  | 1         | 0.6%    |
| Net/ethernet             | 1         | 0.6%    |

