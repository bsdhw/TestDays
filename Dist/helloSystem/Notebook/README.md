helloSystem - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for helloSystem.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 520

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | Pavilion 11                 | [a13373b255](https://bsd-hardware.info/?probe=a13373b255) | Apr 07, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Dell          | Latitude E5470              | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| Sony          | VGN-AW21S_B                 | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| LG Electro... | E300-A.CP20T                | [304701f666](https://bsd-hardware.info/?probe=304701f666) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| PCSTICK       | Unknown                     | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Dell          | Vostro 3490                 | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
| ASUSTek       | UX31E                       | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| HP            | Pavilion dv6                | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 4293B43       | [148a268a0f](https://bsd-hardware.info/?probe=148a268a0f) | Mar 16, 2022 |
| HASEE Comp... | CW35S                       | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| Acer          | Aspire E1-421               | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Itautec       | Infoway w7535               | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| HUAWEI        | BOD-WXX9                    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Acer          | V5-131                      | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| Acer          | V5-131                      | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| Dell          | Latitude E4310              | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude E5470              | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| PCSTICK       | Unknown                     | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| TUXEDO        | InfinityBook13V3            | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| ASUSTek       | 1001PX                      | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Apple         | MacBookPro4,1               | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| Lenovo        | G580 20150                  | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Acer          | Aspire E5-511G              | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Sony          | VPCEB1J1E                   | [04c5ee02da](https://bsd-hardware.info/?probe=04c5ee02da) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP            | G62                         | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Sony          | VPCEB1J1E                   | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Apple         | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| Dell          | Latitude 7280               | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer          | Aspire ES1-311              | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell          | Latitude E6540              | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| Toshiba       | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| HP            | EliteBook 2560p             | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Acer          | V5-131                      | [ff427cb0c9](https://bsd-hardware.info/?probe=ff427cb0c9) | Jan 18, 2022 |
| Gateway       | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f4c9b911fe](https://bsd-hardware.info/?probe=f4c9b911fe) | Jan 16, 2022 |
| Lenovo        | ThinkPad T440 20B7000PHV    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Apple         | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer          | V5-131                      | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Acer          | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Acer          | Aspire E5-476G              | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| Sony          | VPCYB45JB                   | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Lenovo        | G480 20149                  | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| Dell          | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | G550 2958                   | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MX     | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP            | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Notebook      | N15_17RD                    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| HP            | EliteBook 820 G1            | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |
| Dell          | Latitude 7380               | [590b374836](https://bsd-hardware.info/?probe=590b374836) | Jan 02, 2022 |
| Dell          | Latitude E6540              | [f5a43a9f8b](https://bsd-hardware.info/?probe=f5a43a9f8b) | Jan 02, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Dell          | Latitude E6540              | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo        | ThinkPad E580 20KS005BRI    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| Dell          | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Acer          | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Acer          | TravelMate 5760G            | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| Lenovo        | ThinkPad SL510 2847R96      | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo        | ThinkPad T410 2537EA8       | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba       | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Acer          | Aspire E1-421               | [b2aea3de1b](https://bsd-hardware.info/?probe=b2aea3de1b) | Dec 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba       | Satellite L550              | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek       | N56VB                       | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| Dell          | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| Lenovo        | G500 20236                  | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| Dell          | Inspiron 3521               | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| HP            | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| ASUSTek       | X502CA                      | [45f61ab19e](https://bsd-hardware.info/?probe=45f61ab19e) | Dec 14, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| HP            | EliteBook 2560p             | [a064edad4b](https://bsd-hardware.info/?probe=a064edad4b) | Dec 10, 2021 |
| Acer          | Aspire 5749Z                | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| Philco        | 10B                         | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| ASUSTek       | UX31A                       | [9febab6c01](https://bsd-hardware.info/?probe=9febab6c01) | Dec 05, 2021 |
| HP            | Laptop 15-dw0xxx            | [4903f23b62](https://bsd-hardware.info/?probe=4903f23b62) | Dec 05, 2021 |
| ASUSTek       | X540LA                      | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| ASUSTek       | X540LA                      | [0680188ca4](https://bsd-hardware.info/?probe=0680188ca4) | Dec 01, 2021 |
| HP            | Laptop 15-db0xxx            | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| Toshiba       | Satellite S55t-B            | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| HP            | EliteBook 2560p             | [41c04c8449](https://bsd-hardware.info/?probe=41c04c8449) | Nov 26, 2021 |
| Lenovo        | V310-14IKB 80T2             | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| HP            | EliteBook 2560p             | [8fe8caf37d](https://bsd-hardware.info/?probe=8fe8caf37d) | Nov 21, 2021 |
| Toshiba       | Satellite C640              | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba       | Satellite C640              | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Dell          | Inspiron 5566               | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| Lenovo        | ThinkPad T60 1951FEG        | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| Apple         | MacBookPro9,2               | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| HP            | EliteBook 840 G5            | [a1ece36be8](https://bsd-hardware.info/?probe=a1ece36be8) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Acer          | Aspire 5742G                | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| ASUSTek       | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| Lenovo        | ThinkPad T450s 20BX001PU... | [748312bfbf](https://bsd-hardware.info/?probe=748312bfbf) | Nov 07, 2021 |
| ASUSTek       | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| HP            | 14                          | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP            | EliteBook 840 G3            | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z360                | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430u 3352AA5      | [8619bcca35](https://bsd-hardware.info/?probe=8619bcca35) | Nov 01, 2021 |
| Apple         | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP            | Presario CQ43               | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| Chuwi         | MiniBook                    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell          | Precision M4600             | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| Sony          | SVS1511AJB                  | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell          | Studio 1747                 | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
| Apple         | MacBookPro4,1               | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| HP            | Unknown                     | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell          | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP            | 15                          | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| HP            | ProBook 470 G4              | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| HP            | ProBook 470 G4              | [40c180238f](https://bsd-hardware.info/?probe=40c180238f) | Oct 17, 2021 |
| Lenovo        | G500s 20245                 | [e6141c9ab3](https://bsd-hardware.info/?probe=e6141c9ab3) | Oct 16, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| HP            | Pavilion dv3                | [7f0b7f520f](https://bsd-hardware.info/?probe=7f0b7f520f) | Oct 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek       | U33Jc                       | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| HP            | ProBook 470 G4              | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| MSI           | MS-16F1                     | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [fc1eda0998](https://bsd-hardware.info/?probe=fc1eda0998) | Oct 08, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| Acer          | Aspire 5741                 | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Lenovo        | ThinkPad R500 2718W92       | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| Toshiba       | dynabook Satellite B453/... | [e621531452](https://bsd-hardware.info/?probe=e621531452) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| ASUSTek       | X441BA                      | [2fcb818b78](https://bsd-hardware.info/?probe=2fcb818b78) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| Dell          | Latitude E4300              | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Lenovo        | ThinkPad T490s 20NYS3TU0... | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Toshiba       | dynabook RX3 SM240E/3HD     | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba       | Satellite S55t-B            | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP            | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Toshiba       | Satellite P300              | [13e4aa7026](https://bsd-hardware.info/?probe=13e4aa7026) | Sep 29, 2021 |
| Lenovo        | ThinkPad L520 78594KM       | [7905093412](https://bsd-hardware.info/?probe=7905093412) | Sep 26, 2021 |
| Lenovo        | ThinkPad T410 2537E82       | [4ccdde7b89](https://bsd-hardware.info/?probe=4ccdde7b89) | Sep 20, 2021 |
| Lenovo        | G500s 20245                 | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Lenovo        | ThinkPad T61 64607EU        | [34e48b691d](https://bsd-hardware.info/?probe=34e48b691d) | Sep 17, 2021 |
| HP            | G42                         | [738ccd1adf](https://bsd-hardware.info/?probe=738ccd1adf) | Sep 15, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Dell          | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Apple         | MacBookAir7,2               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Itautec       | Infoway w7530               | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| Toshiba       | Satellite S55t-B            | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba       | Satellite S55t-B            | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| HP            | Pavilion dv6                | [8054d6310f](https://bsd-hardware.info/?probe=8054d6310f) | Aug 19, 2021 |
| MSI           | GF65 Thin 10SDR             | [7e5ebc9c82](https://bsd-hardware.info/?probe=7e5ebc9c82) | Aug 18, 2021 |
| Toshiba       | Satellite L855              | [116ce6af18](https://bsd-hardware.info/?probe=116ce6af18) | Aug 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| ASUSTek       | X55CR                       | [c7c812c2c9](https://bsd-hardware.info/?probe=c7c812c2c9) | Aug 15, 2021 |
| HP            | 250 G4                      | [24e8c3de59](https://bsd-hardware.info/?probe=24e8c3de59) | Aug 13, 2021 |
| HP            | 625                         | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| HP            | 250 G4                      | [43a7b112ba](https://bsd-hardware.info/?probe=43a7b112ba) | Aug 11, 2021 |
| Lenovo        | ThinkPad X230 2330A48       | [791c826f7d](https://bsd-hardware.info/?probe=791c826f7d) | Aug 11, 2021 |
| HP            | Pavilion 11                 | [5300a49632](https://bsd-hardware.info/?probe=5300a49632) | Aug 10, 2021 |
| Dell          | G3 3579                     | [91c803fdf2](https://bsd-hardware.info/?probe=91c803fdf2) | Aug 09, 2021 |
| NEC Comput... | PC-VK17HBBCD                | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| Dell          | Inspiron 15-3567            | [9073f1975d](https://bsd-hardware.info/?probe=9073f1975d) | Aug 07, 2021 |
| ASUSTek       | K55VD                       | [6896c37580](https://bsd-hardware.info/?probe=6896c37580) | Aug 06, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Apple         | MacBookPro3,1               | [3566222830](https://bsd-hardware.info/?probe=3566222830) | Aug 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS4JH00    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Sony          | VPCEJ1E1E                   | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| HP            | 15                          | [c2da1dd654](https://bsd-hardware.info/?probe=c2da1dd654) | Jul 30, 2021 |
| Lenovo        | ThinkPad SL 2746M3C         | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| Apple         | MacBookPro6,2               | [7f25ab7c67](https://bsd-hardware.info/?probe=7f25ab7c67) | Jul 26, 2021 |
| Lenovo        | G500 20236                  | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| HP            | Stream 11 Pro G4 EE         | [bd2bf6b0a0](https://bsd-hardware.info/?probe=bd2bf6b0a0) | Jul 20, 2021 |
| Apple         | MacBookPro9,2               | [6cca4dee6f](https://bsd-hardware.info/?probe=6cca4dee6f) | Jul 15, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Alienware     | 17                          | [aff2be63cd](https://bsd-hardware.info/?probe=aff2be63cd) | Jul 10, 2021 |
| MouseCompu... | W331AU                      | [f9a4733911](https://bsd-hardware.info/?probe=f9a4733911) | Jul 06, 2021 |
| MouseCompu... | W331AU                      | [4adfeaa072](https://bsd-hardware.info/?probe=4adfeaa072) | Jul 06, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
| Lenovo        | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| HP            | ProBook 4440s               | [4aac49bc1e](https://bsd-hardware.info/?probe=4aac49bc1e) | Jul 01, 2021 |
| Lenovo        | ThinkPad X200 7458VP4       | [42100d8ea1](https://bsd-hardware.info/?probe=42100d8ea1) | Jun 30, 2021 |
| HP            | Pavilion 17                 | [9929e0c39b](https://bsd-hardware.info/?probe=9929e0c39b) | Jun 30, 2021 |
| Dell          | Latitude E6410              | [8c904d84e0](https://bsd-hardware.info/?probe=8c904d84e0) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | [6e96d4c26f](https://bsd-hardware.info/?probe=6e96d4c26f) | Jun 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| Lenovo        | G500 20236                  | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [aba7b76575](https://bsd-hardware.info/?probe=aba7b76575) | Jun 27, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [1697ebb0a5](https://bsd-hardware.info/?probe=1697ebb0a5) | Jun 25, 2021 |
| Acer          | Aspire 5750                 | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell          | Precision 7710              | [33653d0c28](https://bsd-hardware.info/?probe=33653d0c28) | Jun 22, 2021 |
| Lenovo        | ThinkPad X230 2325WWB       | [786669cc9c](https://bsd-hardware.info/?probe=786669cc9c) | Jun 21, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| Dell          | Inspiron 3542               | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [d5e4c49986](https://bsd-hardware.info/?probe=d5e4c49986) | Jun 21, 2021 |
| Acer          | Aspire 5750                 | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Toshiba       | PORTEGE Z10t-A              | [cb7cbd17d0](https://bsd-hardware.info/?probe=cb7cbd17d0) | Jun 20, 2021 |
| Gateway       | NE56R                       | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0fe1337b93](https://bsd-hardware.info/?probe=0fe1337b93) | Jun 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [902b4298d4](https://bsd-hardware.info/?probe=902b4298d4) | Jun 19, 2021 |
| WYSE          | Z CLASS                     | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Dell          | Latitude E5420              | [1ed3ff35f6](https://bsd-hardware.info/?probe=1ed3ff35f6) | Jun 19, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell          | Latitude 7280               | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |
| Dell          | Vostro 3560                 | [ce9d5f9a46](https://bsd-hardware.info/?probe=ce9d5f9a46) | Jun 18, 2021 |
| Lenovo        | ThinkPad Edge E530 62724... | [78abd376db](https://bsd-hardware.info/?probe=78abd376db) | Jun 18, 2021 |
| Lenovo        | ThinkPad T420 4236FJ1       | [808f58228e](https://bsd-hardware.info/?probe=808f58228e) | Jun 17, 2021 |
| Toshiba       | PORTEGE R930                | [db520e9382](https://bsd-hardware.info/?probe=db520e9382) | Jun 15, 2021 |
| Toshiba       | Satellite C640              | [ec0d93d08c](https://bsd-hardware.info/?probe=ec0d93d08c) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude 5400               | [1bb6c1f63f](https://bsd-hardware.info/?probe=1bb6c1f63f) | Jun 15, 2021 |
| Dell          | Inspiron 15-3567            | [53049dff12](https://bsd-hardware.info/?probe=53049dff12) | Jun 14, 2021 |
| HP            | OMEN by HP Laptop           | [abc94e9198](https://bsd-hardware.info/?probe=abc94e9198) | Jun 13, 2021 |
| HP            | 255 G2                      | [31177d9e0f](https://bsd-hardware.info/?probe=31177d9e0f) | Jun 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Gateway       | NE56R                       | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Latitude E4300              | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Lenovo        | ThinkPad X240 20AMS39F0K    | [65564434a9](https://bsd-hardware.info/?probe=65564434a9) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| Pegatron      | T12Ah                       | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| HP            | Pavilion dv4                | [27f912e4e4](https://bsd-hardware.info/?probe=27f912e4e4) | May 28, 2021 |
| Dell          | Inspiron 3442               | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | Latitude E6410              | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Dell          | Inspiron 3442               | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| HP            | 240 G5 Notebook PC          | [f9c67b360f](https://bsd-hardware.info/?probe=f9c67b360f) | May 08, 2021 |
| Dell          | Latitude E5570              | [c8477da717](https://bsd-hardware.info/?probe=c8477da717) | May 07, 2021 |
| Apple         | MacBookPro11,3              | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Notebook      | W65KJ1_KK1                  | [d4d0b819bc](https://bsd-hardware.info/?probe=d4d0b819bc) | Apr 24, 2021 |
| Gateway       | NE56R                       | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Gateway       | NE56R                       | [f4031498db](https://bsd-hardware.info/?probe=f4031498db) | Apr 15, 2021 |
| Dell          | Latitude E7240              | [1dbd9a5cee](https://bsd-hardware.info/?probe=1dbd9a5cee) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 7417TPU       | [981517a51a](https://bsd-hardware.info/?probe=981517a51a) | Apr 13, 2021 |
| Apple         | MacBookPro8,1               | [5d3d014284](https://bsd-hardware.info/?probe=5d3d014284) | Apr 12, 2021 |
| Apple         | MacBookPro8,1               | [ffcc46ea0b](https://bsd-hardware.info/?probe=ffcc46ea0b) | Apr 12, 2021 |
| Gateway       | NE56R                       | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| ASUSTek       | TP500LNG                    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Panasonic     | CF-NX1GDHYS                 | [6bbadba65d](https://bsd-hardware.info/?probe=6bbadba65d) | Apr 04, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Dell          | Vostro 14-3468              | [219133fc53](https://bsd-hardware.info/?probe=219133fc53) | Mar 30, 2021 |
| Dell          | Vostro 14-3468              | [2c61fcee12](https://bsd-hardware.info/?probe=2c61fcee12) | Mar 30, 2021 |
| ASUSTek       | X540UP                      | [a9c4506364](https://bsd-hardware.info/?probe=a9c4506364) | Mar 28, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [a5b9f5e79d](https://bsd-hardware.info/?probe=a5b9f5e79d) | Mar 27, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Toshiba       | Satellite L500              | [e07fd4edd9](https://bsd-hardware.info/?probe=e07fd4edd9) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | [42ecf97502](https://bsd-hardware.info/?probe=42ecf97502) | Mar 25, 2021 |
| HP            | Pavilion Notebook           | [88e98e18a5](https://bsd-hardware.info/?probe=88e98e18a5) | Mar 25, 2021 |
| ASUSTek       | G75VW                       | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [10c79ea427](https://bsd-hardware.info/?probe=10c79ea427) | Mar 22, 2021 |
| Dell          | Inspiron 7370               | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| Dell          | Inspiron 7520               | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [860b1cd65b](https://bsd-hardware.info/?probe=860b1cd65b) | Mar 15, 2021 |
| Dell          | Inspiron 3442               | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Packard Be... | EasyNote MH36               | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [cf75f7c9cb](https://bsd-hardware.info/?probe=cf75f7c9cb) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [b90180457c](https://bsd-hardware.info/?probe=b90180457c) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Dell          | Inspiron 7520               | [0054ef2511](https://bsd-hardware.info/?probe=0054ef2511) | Mar 13, 2021 |
| Dell          | Inspiron 3543               | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| Acer          | Aspire 4810T                | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| Lenovo        | B41-80 80LG                 | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [9a7f08f8c1](https://bsd-hardware.info/?probe=9a7f08f8c1) | Mar 11, 2021 |
| TUXEDO        | Aura 15 Gen1                | [d9661207d7](https://bsd-hardware.info/?probe=d9661207d7) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| Lenovo        | ThinkPad T530 2392ASU       | [39f3a4f234](https://bsd-hardware.info/?probe=39f3a4f234) | Mar 09, 2021 |
| Toshiba       | Satellite Pro U400          | [71fd81df30](https://bsd-hardware.info/?probe=71fd81df30) | Mar 07, 2021 |
| ASUSTek       | X556UA                      | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E6500              | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [5e5632d9b6](https://bsd-hardware.info/?probe=5e5632d9b6) | Mar 07, 2021 |
| Lenovo        | 3000 N200 0769AP2           | [6b81593de9](https://bsd-hardware.info/?probe=6b81593de9) | Mar 06, 2021 |
| Dell          | Latitude E5570              | [12eae7a62e](https://bsd-hardware.info/?probe=12eae7a62e) | Mar 05, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b03cb1f957](https://bsd-hardware.info/?probe=b03cb1f957) | Mar 05, 2021 |
| HP            | EliteBook 820 G1            | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| ASUSTek       | X55CR                       | [e887ee2ff5](https://bsd-hardware.info/?probe=e887ee2ff5) | Mar 03, 2021 |
| ASUSTek       | X55CR                       | [e1e4548d22](https://bsd-hardware.info/?probe=e1e4548d22) | Mar 03, 2021 |
| Acer          | Aspire 8730                 | [33e7d80b63](https://bsd-hardware.info/?probe=33e7d80b63) | Mar 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| ASUSTek       | G1S                         | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| ASUSTek       | X555LAB                     | [b0364fffaf](https://bsd-hardware.info/?probe=b0364fffaf) | Feb 25, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| ASUSTek       | X555LAB                     | [45d57c2be0](https://bsd-hardware.info/?probe=45d57c2be0) | Feb 24, 2021 |
| Dell          | XPS 13 9333                 | [7c78b3d42a](https://bsd-hardware.info/?probe=7c78b3d42a) | Feb 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7f35ef7fa9](https://bsd-hardware.info/?probe=7f35ef7fa9) | Feb 23, 2021 |
| Lenovo        | Z50-70 20354                | [d3d9dc620f](https://bsd-hardware.info/?probe=d3d9dc620f) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Dell          | Latitude E7240              | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| Lenovo        | G470 20078                  | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Apple         | MacBookPro9,2               | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | [5d86c90af1](https://bsd-hardware.info/?probe=5d86c90af1) | Feb 21, 2021 |
| HP            | EliteBook 8540p             | [78d9a31074](https://bsd-hardware.info/?probe=78d9a31074) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Packard Be... | EasyNote TS11HR             | [1adcd64182](https://bsd-hardware.info/?probe=1adcd64182) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [9731048099](https://bsd-hardware.info/?probe=9731048099) | Feb 20, 2021 |
| ASUSTek       | X556UA                      | [6bbf9d6e29](https://bsd-hardware.info/?probe=6bbf9d6e29) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [03d4d9a468](https://bsd-hardware.info/?probe=03d4d9a468) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| HP            | ProBook 440 G2              | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Acer          | Aspire ES1-533              | [045cf81f15](https://bsd-hardware.info/?probe=045cf81f15) | Feb 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Dell          | Inspiron 3521               | [10490aef33](https://bsd-hardware.info/?probe=10490aef33) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [abe1869a95](https://bsd-hardware.info/?probe=abe1869a95) | Feb 17, 2021 |
| Fujitsu       | LIFEBOOK E744               | [fc2f449a8a](https://bsd-hardware.info/?probe=fc2f449a8a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| HP            | Pavilion Laptop 14-ce2xx... | [c355a6280b](https://bsd-hardware.info/?probe=c355a6280b) | Feb 17, 2021 |
| Dell          | Latitude 7390               | [3fe6eff89a](https://bsd-hardware.info/?probe=3fe6eff89a) | Feb 17, 2021 |
| Dell          | Venue 11 Pro 7140           | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| HP            | OMEN by HP Laptop           | [bb8beb97be](https://bsd-hardware.info/?probe=bb8beb97be) | Feb 17, 2021 |
| Dell          | Latitude E4300              | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Lenovo        | U310                        | [ccec69b736](https://bsd-hardware.info/?probe=ccec69b736) | Feb 16, 2021 |
| Lenovo        | U310                        | [83805a17c5](https://bsd-hardware.info/?probe=83805a17c5) | Feb 16, 2021 |
| Lenovo        | U310                        | [111385095d](https://bsd-hardware.info/?probe=111385095d) | Feb 16, 2021 |
| Apple         | MacBookAir4,2               | [7d8419c918](https://bsd-hardware.info/?probe=7d8419c918) | Feb 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [19f307ff6d](https://bsd-hardware.info/?probe=19f307ff6d) | Feb 16, 2021 |
| Lenovo        | ThinkPad T430 23427YU       | [79d1896352](https://bsd-hardware.info/?probe=79d1896352) | Feb 16, 2021 |
| eMachines     | eME732ZG                    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| HP            | EliteBook 8440p             | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Dell          | Inspiron 3421               | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| HP            | EliteBook 840 G3            | [0d35b2f5d8](https://bsd-hardware.info/?probe=0d35b2f5d8) | Feb 15, 2021 |
| ASUSTek       | X75VC                       | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5a393bc680](https://bsd-hardware.info/?probe=5a393bc680) | Feb 15, 2021 |
| Medion        | P6812                       | [c2c592bca8](https://bsd-hardware.info/?probe=c2c592bca8) | Feb 15, 2021 |
| Medion        | P6812                       | [afa43a6aab](https://bsd-hardware.info/?probe=afa43a6aab) | Feb 15, 2021 |
| Apple         | MacBookPro6,2               | [4d83633f97](https://bsd-hardware.info/?probe=4d83633f97) | Feb 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| Dell          | Latitude E4300              | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGC       | [f8ce633ed7](https://bsd-hardware.info/?probe=f8ce633ed7) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [6da4116499](https://bsd-hardware.info/?probe=6da4116499) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [d212f58dd2](https://bsd-hardware.info/?probe=d212f58dd2) | Feb 13, 2021 |
| Dell          | Inspiron 3442               | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Samsung       | 910S3K/9310SK/910S3P/911... | [bdf7452299](https://bsd-hardware.info/?probe=bdf7452299) | Feb 13, 2021 |
| Apple         | MacBookPro8,1               | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude E6420              | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [1e243253d1](https://bsd-hardware.info/?probe=1e243253d1) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [1ba418a5e6](https://bsd-hardware.info/?probe=1ba418a5e6) | Feb 12, 2021 |
| Clevo         | C41X0                       | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| Lenovo        | ThinkPad T460s 20F90037L... | [8325c794b3](https://bsd-hardware.info/?probe=8325c794b3) | Feb 12, 2021 |
| Apple         | MacBook5,2                  | [f1bc2178a9](https://bsd-hardware.info/?probe=f1bc2178a9) | Feb 12, 2021 |
| Lenovo        | ThinkPad T440s 20ARS10P0... | [bfee99bebd](https://bsd-hardware.info/?probe=bfee99bebd) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | [3a73ecd855](https://bsd-hardware.info/?probe=3a73ecd855) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | [afd71fdf87](https://bsd-hardware.info/?probe=afd71fdf87) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [1aa2a3a541](https://bsd-hardware.info/?probe=1aa2a3a541) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [4814701c0e](https://bsd-hardware.info/?probe=4814701c0e) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| ASUSTek       | S551LN                      | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Dell          | Latitude 7280               | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Apple         | MacBook6,1                  | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| ASUSTek       | K50IJ                       | [8cd0aedd3a](https://bsd-hardware.info/?probe=8cd0aedd3a) | Feb 11, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [b2bf9a977b](https://bsd-hardware.info/?probe=b2bf9a977b) | Feb 11, 2021 |
| Dell          | Latitude 3410               | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | [43196baf75](https://bsd-hardware.info/?probe=43196baf75) | Feb 11, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z        | [270ca253a3](https://bsd-hardware.info/?probe=270ca253a3) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | [b3569ebb39](https://bsd-hardware.info/?probe=b3569ebb39) | Feb 11, 2021 |
| Lenovo        | ThinkPad L470 20J5S09500    | [b17963cd30](https://bsd-hardware.info/?probe=b17963cd30) | Feb 10, 2021 |
| Lenovo        | ThinkPad T410 253722U       | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| ASUSTek       | K50IJ                       | [52a30e2478](https://bsd-hardware.info/?probe=52a30e2478) | Feb 10, 2021 |
| Toshiba       | TECRA M11                   | [468d16d496](https://bsd-hardware.info/?probe=468d16d496) | Feb 10, 2021 |
| Lenovo        | ThinkPad L512 25975XU       | [b4d22f4179](https://bsd-hardware.info/?probe=b4d22f4179) | Feb 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [ca369843a9](https://bsd-hardware.info/?probe=ca369843a9) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| ASUSTek       | X510UQ                      | [9da77349b9](https://bsd-hardware.info/?probe=9da77349b9) | Feb 07, 2021 |
| ASUSTek       | X502CA                      | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| Samsung       | 300E5M/300E5L               | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Fujitsu       | LIFEBOOK E753               | [37245aca21](https://bsd-hardware.info/?probe=37245aca21) | Feb 03, 2021 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [faa7becf82](https://bsd-hardware.info/?probe=faa7becf82) | Feb 01, 2021 |
| HP            | EliteBook 8570p             | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Clevo         | W55xEU                      | [e17285783e](https://bsd-hardware.info/?probe=e17285783e) | Jan 29, 2021 |
| Dell          | Latitude E6440              | [ed46852cfa](https://bsd-hardware.info/?probe=ed46852cfa) | Jan 26, 2021 |
| Dell          | Latitude E5570              | [bcf60e66d7](https://bsd-hardware.info/?probe=bcf60e66d7) | Jan 26, 2021 |
| Pegatron      | T12Ah                       | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| Apple         | MacBook4,1                  | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| HP            | ProBook 470 G4              | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3444A... | [b659b95d1a](https://bsd-hardware.info/?probe=b659b95d1a) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| HP            | ProBook 470 G4              | [55c762d22e](https://bsd-hardware.info/?probe=55c762d22e) | Jan 17, 2021 |
| Lenovo        | ThinkPad T480s 20L8S6G21... | [a8508f91de](https://bsd-hardware.info/?probe=a8508f91de) | Jan 14, 2021 |
| HP            | ProBook 470 G4              | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| Lenovo        | ThinkPad T410 2537N96       | [8b54f3995d](https://bsd-hardware.info/?probe=8b54f3995d) | Jan 12, 2021 |
| Apple         | MacBookPro5,2               | [e2768ec168](https://bsd-hardware.info/?probe=e2768ec168) | Jan 10, 2021 |
| Apple         | MacBookPro5,2               | [56414400c1](https://bsd-hardware.info/?probe=56414400c1) | Jan 10, 2021 |
| HP            | EliteBook 8570p             | [97a3ac7e36](https://bsd-hardware.info/?probe=97a3ac7e36) | Jan 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34484... | [6133b45179](https://bsd-hardware.info/?probe=6133b45179) | Jan 05, 2021 |
| Fujitsu       | LIFEBOOK E744               | [9d50133c85](https://bsd-hardware.info/?probe=9d50133c85) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [1b0cc7506e](https://bsd-hardware.info/?probe=1b0cc7506e) | Jan 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3JY0... | [c51f274f90](https://bsd-hardware.info/?probe=c51f274f90) | Jan 02, 2021 |
| Apple         | MacBookPro10,2              | [e43a26be8d](https://bsd-hardware.info/?probe=e43a26be8d) | Jan 01, 2021 |
| HP            | EliteBook 8570p             | [60d9540d35](https://bsd-hardware.info/?probe=60d9540d35) | Dec 31, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| helloSystem 0.5.0 | 115       | 27.91%  |
| helloSystem 0.7.0 | 103       | 25%     |
| helloSystem 0.4.0 | 92        | 22.33%  |
| helloSystem 0.6.0 | 69        | 16.75%  |
| helloSystem 0.8.0 | 18        | 4.37%   |
| helloSystem 0.3.0 | 14        | 3.4%    |
| helloSystem       | 1         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 386       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 386       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 382       | 98.45%  |
| KDE5         | 3         | 0.77%   |
| GNOME        | 2         | 0.52%   |
| XFCE         | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 386       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 386       | 99.48%  |
| SDDM | 2         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 373       | 96.63%  |
| de_DE   | 3         | 0.78%   |
| fr_FR   | 2         | 0.52%   |
| es_ES   | 2         | 0.52%   |
| C       | 2         | 0.52%   |
| uk_UA   | 1         | 0.26%   |
| ru_RU   | 1         | 0.26%   |
| it_IT   | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 335       | 85.68%  |
| BIOS | 56        | 14.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 327       | 83.85%  |
| Cd9660 | 63        | 16.15%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 385       | 99.74%  |
| MBR  | 1         | 0.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 121       | 31.35%  |
| Dell                | 60        | 15.54%  |
| Hewlett-Packard     | 50        | 12.95%  |
| ASUSTek Computer    | 36        | 9.33%   |
| Apple               | 27        | 6.99%   |
| Acer                | 19        | 4.92%   |
| Toshiba             | 16        | 4.15%   |
| Samsung Electronics | 9         | 2.33%   |
| Sony                | 5         | 1.3%    |
| Packard Bell        | 4         | 1.04%   |
| TUXEDO              | 3         | 0.78%   |
| Fujitsu             | 3         | 0.78%   |
| Notebook            | 2         | 0.52%   |
| MSI                 | 2         | 0.52%   |
| LG Electronics      | 2         | 0.52%   |
| Itautec             | 2         | 0.52%   |
| Gateway             | 2         | 0.52%   |
| eMachines           | 2         | 0.52%   |
| WYSE                | 1         | 0.26%   |
| TWINHEAD            | 1         | 0.26%   |
| Timi                | 1         | 0.26%   |
| Semp Toshiba        | 1         | 0.26%   |
| Positivo            | 1         | 0.26%   |
| Philco              | 1         | 0.26%   |
| Pegatron            | 1         | 0.26%   |
| PCSTICK             | 1         | 0.26%   |
| Panasonic           | 1         | 0.26%   |
| NEC Computers       | 1         | 0.26%   |
| MouseComputer       | 1         | 0.26%   |
| Medion              | 1         | 0.26%   |
| Kraftway            | 1         | 0.26%   |
| HUAWEI              | 1         | 0.26%   |
| HASEE Computer      | 1         | 0.26%   |
| Hampoo              | 1         | 0.26%   |
| Fujitsu Siemens     | 1         | 0.26%   |
| DNS                 | 1         | 0.26%   |
| Clevo               | 1         | 0.26%   |
| Chuwi               | 1         | 0.26%   |
| Alienware           | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Dell Latitude 7280                      | 3         | 0.78%   |
| Dell Inspiron 15-3567                   | 3         | 0.78%   |
| Apple MacBookPro9,2                     | 3         | 0.78%   |
| Apple MacBook4,1                        | 3         | 0.78%   |
| TUXEDO Aura 15 Gen1                     | 2         | 0.52%   |
| Lenovo Z50-70 20354                     | 2         | 0.52%   |
| Lenovo IdeaPad 110S-11IBR 80WG          | 2         | 0.52%   |
| Lenovo G550 2958                        | 2         | 0.52%   |
| HP Pavilion dv6                         | 2         | 0.52%   |
| HP EliteBook 840 G3                     | 2         | 0.52%   |
| HP 15                                   | 2         | 0.52%   |
| Gateway NE56R                           | 2         | 0.52%   |
| Dell Venue 11 Pro 7140                  | 2         | 0.52%   |
| Dell Latitude E7240                     | 2         | 0.52%   |
| Dell Latitude E6540                     | 2         | 0.52%   |
| Dell Latitude E6410                     | 2         | 0.52%   |
| Dell Latitude E5570                     | 2         | 0.52%   |
| Dell Latitude E5470                     | 2         | 0.52%   |
| Dell Latitude E4300                     | 2         | 0.52%   |
| Dell Latitude 7380                      | 2         | 0.52%   |
| Dell Inspiron 7520                      | 2         | 0.52%   |
| Dell Inspiron 3521                      | 2         | 0.52%   |
| Dell Inspiron 3442                      | 2         | 0.52%   |
| ASUS X556UA                             | 2         | 0.52%   |
| ASUS X502CA                             | 2         | 0.52%   |
| ASUS VivoBook_ASUSLaptop X712DAP_M712DA | 2         | 0.52%   |
| Apple MacBookPro8,1                     | 2         | 0.52%   |
| Apple MacBookPro6,2                     | 2         | 0.52%   |
| Apple MacBookPro5,5                     | 2         | 0.52%   |
| Apple MacBookPro4,1                     | 2         | 0.52%   |
| Apple MacBookAir5,1                     | 2         | 0.52%   |
| Apple MacBook6,1                        | 2         | 0.52%   |
| Apple MacBook5,2                        | 2         | 0.52%   |
| Acer V5-131                             | 2         | 0.52%   |
| Acer Aspire ES1-533                     | 2         | 0.52%   |
| Acer Aspire E1-421                      | 2         | 0.52%   |
| Unknown                                 | 2         | 0.52%   |
| WYSE Z CLASS                            | 1         | 0.26%   |
| TWINHEAD U12CT                          | 1         | 0.26%   |
| TUXEDO InfinityBook13V3                 | 1         | 0.26%   |
| Toshiba TECRA M11                       | 1         | 0.26%   |
| Toshiba Satellite U500                  | 1         | 0.26%   |
| Toshiba Satellite S55t-B                | 1         | 0.26%   |
| Toshiba Satellite Pro U400              | 1         | 0.26%   |
| Toshiba Satellite P300                  | 1         | 0.26%   |
| Toshiba Satellite L855                  | 1         | 0.26%   |
| Toshiba Satellite L550                  | 1         | 0.26%   |
| Toshiba Satellite L500                  | 1         | 0.26%   |
| Toshiba Satellite L50-A                 | 1         | 0.26%   |
| Toshiba Satellite C640                  | 1         | 0.26%   |
| Toshiba Satellite C50-B                 | 1         | 0.26%   |
| Toshiba PORTEGE Z10t-A                  | 1         | 0.26%   |
| Toshiba PORTEGE R930                    | 1         | 0.26%   |
| Toshiba PORTEGE M780                    | 1         | 0.26%   |
| Toshiba dynabook Satellite B453/L       | 1         | 0.26%   |
| Toshiba dynabook RX3 SM240E/3HD         | 1         | 0.26%   |
| Timi RedmiBook Pro 15                   | 1         | 0.26%   |
| Sony VPCYB45JB                          | 1         | 0.26%   |
| Sony VPCEJ1E1E                          | 1         | 0.26%   |
| Sony VPCEB1J1E                          | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 88        | 22.8%   |
| Dell Latitude           | 33        | 8.55%   |
| Dell Inspiron           | 16        | 4.15%   |
| Acer Aspire             | 15        | 3.89%   |
| HP Pavilion             | 12        | 3.11%   |
| HP EliteBook            | 11        | 2.85%   |
| Toshiba Satellite       | 10        | 2.59%   |
| Lenovo IdeaPad          | 10        | 2.59%   |
| HP Laptop               | 5         | 1.3%    |
| Packard Bell EasyNote   | 4         | 1.04%   |
| HP ProBook              | 4         | 1.04%   |
| ASUS VivoBook           | 4         | 1.04%   |
| Toshiba PORTEGE         | 3         | 0.78%   |
| Lenovo Legion           | 3         | 0.78%   |
| HP 15                   | 3         | 0.78%   |
| Fujitsu LIFEBOOK        | 3         | 0.78%   |
| Dell Vostro             | 3         | 0.78%   |
| Apple MacBookPro9       | 3         | 0.78%   |
| Apple MacBookPro5       | 3         | 0.78%   |
| Apple MacBook4          | 3         | 0.78%   |
| TUXEDO Aura             | 2         | 0.52%   |
| Toshiba dynabook        | 2         | 0.52%   |
| Lenovo Z50-70           | 2         | 0.52%   |
| Lenovo Yoga             | 2         | 0.52%   |
| Lenovo G550             | 2         | 0.52%   |
| Itautec Infoway         | 2         | 0.52%   |
| HP OMEN                 | 2         | 0.52%   |
| Gateway NE56R           | 2         | 0.52%   |
| Dell XPS                | 2         | 0.52%   |
| Dell Venue              | 2         | 0.52%   |
| Dell Precision          | 2         | 0.52%   |
| ASUS X556UA             | 2         | 0.52%   |
| ASUS X502CA             | 2         | 0.52%   |
| Apple MacBookPro8       | 2         | 0.52%   |
| Apple MacBookPro6       | 2         | 0.52%   |
| Apple MacBookPro4       | 2         | 0.52%   |
| Apple MacBookAir5       | 2         | 0.52%   |
| Apple MacBook6          | 2         | 0.52%   |
| Apple MacBook5          | 2         | 0.52%   |
| Acer V5-131             | 2         | 0.52%   |
| Unknown                 | 2         | 0.52%   |
| WYSE Z                  | 1         | 0.26%   |
| TWINHEAD U12CT          | 1         | 0.26%   |
| TUXEDO InfinityBook13V3 | 1         | 0.26%   |
| Toshiba TECRA           | 1         | 0.26%   |
| Timi RedmiBook          | 1         | 0.26%   |
| Sony VPCYB45JB          | 1         | 0.26%   |
| Sony VPCEJ1E1E          | 1         | 0.26%   |
| Sony VPCEB1J1E          | 1         | 0.26%   |
| Sony VGN-AW21S          | 1         | 0.26%   |
| Sony SVS1511AJB         | 1         | 0.26%   |
| Semp Toshiba STI        | 1         | 0.26%   |
| Samsung RV411           | 1         | 0.26%   |
| Samsung N150P           | 1         | 0.26%   |
| Samsung N100            | 1         | 0.26%   |
| Samsung 910S3K          | 1         | 0.26%   |
| Samsung 530U3C          | 1         | 0.26%   |
| Samsung 3570R           | 1         | 0.26%   |
| Samsung 305E4A          | 1         | 0.26%   |
| Samsung 300V3Z          | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 45        | 11.66%  |
| 2020    | 33        | 8.55%   |
| 2015    | 33        | 8.55%   |
| 2012    | 32        | 8.29%   |
| 2018    | 31        | 8.03%   |
| 2019    | 28        | 7.25%   |
| 2009    | 28        | 7.25%   |
| 2011    | 27        | 6.99%   |
| 2010    | 26        | 6.74%   |
| 2014    | 25        | 6.48%   |
| 2016    | 23        | 5.96%   |
| 2017    | 17        | 4.4%    |
| 2021    | 16        | 4.15%   |
| 2008    | 13        | 3.37%   |
| 2007    | 7         | 1.81%   |
| 2006    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 386       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 385       | 99.74%  |
| Yes  | 1         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 157       | 40.67%  |
| 8.01-16.0   | 145       | 37.56%  |
| 16.01-24.0  | 60        | 15.54%  |
| 2.01-3.0    | 13        | 3.37%   |
| 32.01-64.0  | 5         | 1.3%    |
| 24.01-32.0  | 3         | 0.78%   |
| 3.01-4.0    | 2         | 0.52%   |
| 64.01-256.0 | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 265       | 68.3%   |
| 0.51-1.0  | 100       | 25.77%  |
| 2.01-3.0  | 11        | 2.84%   |
| 1.01-2.0  | 11        | 2.84%   |
| 8.01-16.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 307       | 78.32%  |
| 2      | 59        | 15.05%  |
| 0      | 20        | 5.1%    |
| 3      | 6         | 1.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 214       | 55.15%  |
| Yes       | 174       | 44.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 345       | 89.38%  |
| No        | 41        | 10.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 379       | 98.19%  |
| No        | 7         | 1.81%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 64.34%  |
| No        | 138       | 35.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 56        | 14.43%  |
| Germany            | 41        | 10.57%  |
| Brazil             | 32        | 8.25%   |
| UK                 | 16        | 4.12%   |
| Italy              | 16        | 4.12%   |
| Netherlands        | 15        | 3.87%   |
| Russia             | 14        | 3.61%   |
| China              | 14        | 3.61%   |
| Ukraine            | 12        | 3.09%   |
| Spain              | 12        | 3.09%   |
| France             | 11        | 2.84%   |
| Mexico             | 8         | 2.06%   |
| Sweden             | 7         | 1.8%    |
| Poland             | 7         | 1.8%    |
| Indonesia          | 7         | 1.8%    |
| Hungary            | 7         | 1.8%    |
| Canada             | 7         | 1.8%    |
| India              | 6         | 1.55%   |
| Australia          | 6         | 1.55%   |
| Romania            | 5         | 1.29%   |
| Portugal           | 5         | 1.29%   |
| Japan              | 5         | 1.29%   |
| Greece             | 5         | 1.29%   |
| Lithuania          | 4         | 1.03%   |
| Vietnam            | 3         | 0.77%   |
| UAE                | 3         | 0.77%   |
| Switzerland        | 3         | 0.77%   |
| South Korea        | 3         | 0.77%   |
| Norway             | 3         | 0.77%   |
| New Zealand        | 3         | 0.77%   |
| Chile              | 3         | 0.77%   |
| Bulgaria           | 3         | 0.77%   |
| Turkey             | 2         | 0.52%   |
| South Africa       | 2         | 0.52%   |
| Slovakia           | 2         | 0.52%   |
| Peru               | 2         | 0.52%   |
| Malaysia           | 2         | 0.52%   |
| Georgia            | 2         | 0.52%   |
| Finland            | 2         | 0.52%   |
| Denmark            | 2         | 0.52%   |
| Croatia            | 2         | 0.52%   |
| Colombia           | 2         | 0.52%   |
| Belarus            | 2         | 0.52%   |
| Austria            | 2         | 0.52%   |
| Argentina          | 2         | 0.52%   |
| Venezuela          | 1         | 0.26%   |
| Tanzania           | 1         | 0.26%   |
| Taiwan             | 1         | 0.26%   |
| Syria              | 1         | 0.26%   |
| Singapore          | 1         | 0.26%   |
| Puerto Rico        | 1         | 0.26%   |
| Philippines        | 1         | 0.26%   |
| Oman               | 1         | 0.26%   |
| Morocco            | 1         | 0.26%   |
| Montenegro         | 1         | 0.26%   |
| Malta              | 1         | 0.26%   |
| Macao              | 1         | 0.26%   |
| Libya              | 1         | 0.26%   |
| Latvia             | 1         | 0.26%   |
| Dominican Republic | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Moscow                    | 5         | 1.23%   |
| Guangzhou                 | 5         | 1.23%   |
| Utrecht                   | 4         | 0.99%   |
| Athens                    | 4         | 0.99%   |
| Wroclaw                   | 3         | 0.74%   |
| Vilnius                   | 3         | 0.74%   |
| Surabaya                  | 3         | 0.74%   |
| Leatherhead               | 3         | 0.74%   |
| Kyiv                      | 3         | 0.74%   |
| Jakarta                   | 3         | 0.74%   |
| Hanoi                     | 3         | 0.74%   |
| Frankfurt am Main         | 3         | 0.74%   |
| Franconville              | 3         | 0.74%   |
| Curitiba                  | 3         | 0.74%   |
| Budapest                  | 3         | 0.74%   |
| Berlin                    | 3         | 0.74%   |
| Zurich                    | 2         | 0.49%   |
| Warsaw                    | 2         | 0.49%   |
| VÃ¤sterÃ¥s            | 2         | 0.49%   |
| Turin                     | 2         | 0.49%   |
| Tula de Allende           | 2         | 0.49%   |
| SГЈo Paulo              | 2         | 0.49%   |
| St Petersburg             | 2         | 0.49%   |
| SÃ£o Paulo              | 2         | 0.49%   |
| Rio de Janeiro            | 2         | 0.49%   |
| Pleidelsheim              | 2         | 0.49%   |
| Oklahoma City             | 2         | 0.49%   |
| New York                  | 2         | 0.49%   |
| Nesttun                   | 2         | 0.49%   |
| Maraba                    | 2         | 0.49%   |
| Lisbon                    | 2         | 0.49%   |
| Lima                      | 2         | 0.49%   |
| Leipzig                   | 2         | 0.49%   |
| K'alak'i T'bilisi         | 2         | 0.49%   |
| Harrisburg                | 2         | 0.49%   |
| Halle                     | 2         | 0.49%   |
| Frisco                    | 2         | 0.49%   |
| Dijon                     | 2         | 0.49%   |
| Detmold                   | 2         | 0.49%   |
| Canberra                  | 2         | 0.49%   |
| Brighton                  | 2         | 0.49%   |
| Berehove                  | 2         | 0.49%   |
| Bengaluru                 | 2         | 0.49%   |
| Beijing                   | 2         | 0.49%   |
| Barcelona                 | 2         | 0.49%   |
| Amsterdam                 | 2         | 0.49%   |
| Abu Dhabi                 | 2         | 0.49%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.25%   |
| Zhengzhou                 | 1         | 0.25%   |
| Zaporizhzhya              | 1         | 0.25%   |
| Zapopan                   | 1         | 0.25%   |
| Zagreb                    | 1         | 0.25%   |
| Yunlin                    | 1         | 0.25%   |
| Youngsville               | 1         | 0.25%   |
| Yokohama                  | 1         | 0.25%   |
| Yeongdong-gun             | 1         | 0.25%   |
| Yaphank                   | 1         | 0.25%   |
| Wuhan                     | 1         | 0.25%   |
| Worthing                  | 1         | 0.25%   |
| Wellington                | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 68        | 72     | 15.45%  |
| Samsung Electronics | 63        | 73     | 14.32%  |
| Seagate             | 49        | 58     | 11.14%  |
| Toshiba             | 37        | 44     | 8.41%   |
| Kingston            | 29        | 33     | 6.59%   |
| Crucial             | 27        | 29     | 6.14%   |
| SanDisk             | 24        | 25     | 5.45%   |
| Intel               | 17        | 19     | 3.86%   |
| Hitachi             | 17        | 19     | 3.86%   |
| A-DATA Technology   | 11        | 12     | 2.5%    |
| HGST                | 10        | 11     | 2.27%   |
| Apple               | 7         | 7      | 1.59%   |
| SPCC                | 6         | 7      | 1.36%   |
| Micron Technology   | 6         | 6      | 1.36%   |
| LITEON              | 5         | 5      | 1.14%   |
| Fujitsu             | 5         | 6      | 1.14%   |
| Transcend           | 4         | 5      | 0.91%   |
| SK Hynix            | 4         | 4      | 0.91%   |
| Patriot             | 4         | 7      | 0.91%   |
| OCZ                 | 4         | 4      | 0.91%   |
| KingSpec            | 3         | 3      | 0.68%   |
| Intenso             | 3         | 3      | 0.68%   |
| Corsair             | 3         | 3      | 0.68%   |
| PNY                 | 2         | 2      | 0.45%   |
| LITEONIT            | 2         | 2      | 0.45%   |
| Lexar               | 2         | 2      | 0.45%   |
| KIOXIA              | 2         | 2      | 0.45%   |
| Hewlett-Packard     | 2         | 3      | 0.45%   |
| Apacer              | 2         | 2      | 0.45%   |
| Zheino              | 1         | 1      | 0.23%   |
| Team                | 1         | 1      | 0.23%   |
| SSSTC               | 1         | 1      | 0.23%   |
| SMART               | 1         | 1      | 0.23%   |
| Silicon Motion      | 1         | 1      | 0.23%   |
| PLEXTOR             | 1         | 1      | 0.23%   |
| Pioneer             | 1         | 1      | 0.23%   |
| MyDigitalSSD        | 1         | 1      | 0.23%   |
| Mushkin             | 1         | 1      | 0.23%   |
| Leven               | 1         | 1      | 0.23%   |
| KingDian            | 1         | 1      | 0.23%   |
| Integral            | 1         | 1      | 0.23%   |
| INDMEM              | 1         | 1      | 0.23%   |
| HPE                 | 1         | 1      | 0.23%   |
| Hikvision           | 1         | 1      | 0.23%   |
| GOODRAM             | 1         | 1      | 0.23%   |
| Gigabyte Technology | 1         | 1      | 0.23%   |
| FORESEE             | 1         | 1      | 0.23%   |
| Colorful            | 1         | 1      | 0.23%   |
| China               | 1         | 1      | 0.23%   |
| AMD                 | 1         | 1      | 0.23%   |
| AGI                 | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 7         | 1.56%   |
| Crucial CT500MX500SSD1 500GB         | 6         | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB         | 5         | 1.11%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.11%   |
| Seagate ST9500325AS 500GB            | 5         | 1.11%   |
| Kingston SA400S37120G 120GB          | 5         | 1.11%   |
| Seagate ST9500420AS 500GB            | 4         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.89%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.89%   |
| Kingston SA400S37240G 240GB          | 4         | 0.89%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 0.89%   |
| WDC WDS120G2G0A-00JH30 120GB         | 3         | 0.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.67%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.67%   |
| Samsung SSD 860 EVO 1TB              | 3         | 0.67%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.67%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.67%   |
| Samsung SSD 840 EVO 250GB            | 3         | 0.67%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 3         | 0.67%   |
| Micron 1100 SATA 256GB               | 3         | 0.67%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 0.67%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.67%   |
| A-DATA SU650 240GB                   | 3         | 0.67%   |
| WDC WDS120G1G0A-00SS50 120GB         | 2         | 0.44%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.44%   |
| WDC WD5000BPKT-00PK4T0 500GB         | 2         | 0.44%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 0.44%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 0.44%   |
| WDC WD1600BEVS-08VAT2 160GB          | 2         | 0.44%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.44%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 2         | 0.44%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.44%   |
| Toshiba MK3261GSYN 320GB             | 2         | 0.44%   |
| SPCC Solid State Disk 512GB          | 2         | 0.44%   |
| SPCC Solid State Disk 256GB          | 2         | 0.44%   |
| SPCC Solid State Disk 1TB            | 2         | 0.44%   |
| Seagate ST9320423AS 320GB            | 2         | 0.44%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 2         | 0.44%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.44%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.44%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.44%   |
| SanDisk SD5SE2256G1002E 256GB        | 2         | 0.44%   |
| Samsung MZ7TE128HMGR-000L1 128GB     | 2         | 0.44%   |
| Samsung HM160HI 160GB                | 2         | 0.44%   |
| Patriot Burst 120GB                  | 2         | 0.44%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB   | 2         | 0.44%   |
| Kingston SV300S37A120G 120GB         | 2         | 0.44%   |
| Kingston SMS200S360G 64GB            | 2         | 0.44%   |
| Kingston SA400S37960G 960GB          | 2         | 0.44%   |
| Kingston SA400M8240G 240GB           | 2         | 0.44%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 0.44%   |
| Hitachi HTS545025B9A300 250GB        | 2         | 0.44%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.44%   |
| Crucial CT120BX500SSD1 120GB         | 2         | 0.44%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.44%   |
| Apple SSD TS128E 121GB               | 2         | 0.44%   |
| A-DATA SU650 120GB                   | 2         | 0.44%   |
| Zheino CHN mSATAM1 256 256GB         | 1         | 0.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 58     | 30.06%  |
| WDC                 | 47        | 48     | 28.83%  |
| Toshiba             | 28        | 35     | 17.18%  |
| Hitachi             | 17        | 19     | 10.43%  |
| HGST                | 10        | 11     | 6.13%   |
| Samsung Electronics | 7         | 7      | 4.29%   |
| Fujitsu             | 4         | 4      | 2.45%   |
| Apple               | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 52     | 20.17%  |
| Kingston            | 26        | 29     | 11.16%  |
| Crucial             | 25        | 27     | 10.73%  |
| SanDisk             | 24        | 25     | 10.3%   |
| WDC                 | 13        | 13     | 5.58%   |
| Intel               | 12        | 13     | 5.15%   |
| A-DATA Technology   | 8         | 9      | 3.43%   |
| SPCC                | 6         | 7      | 2.58%   |
| Apple               | 6         | 6      | 2.58%   |
| Micron Technology   | 5         | 5      | 2.15%   |
| LITEON              | 5         | 5      | 2.15%   |
| Transcend           | 4         | 5      | 1.72%   |
| Patriot             | 4         | 7      | 1.72%   |
| OCZ                 | 4         | 4      | 1.72%   |
| Toshiba             | 3         | 3      | 1.29%   |
| KingSpec            | 3         | 3      | 1.29%   |
| Intenso             | 3         | 3      | 1.29%   |
| Corsair             | 3         | 3      | 1.29%   |
| SK Hynix            | 2         | 2      | 0.86%   |
| PNY                 | 2         | 2      | 0.86%   |
| LITEONIT            | 2         | 2      | 0.86%   |
| Lexar               | 2         | 2      | 0.86%   |
| Hewlett-Packard     | 2         | 3      | 0.86%   |
| Apacer              | 2         | 2      | 0.86%   |
| Zheino              | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| SSSTC               | 1         | 1      | 0.43%   |
| SMART               | 1         | 1      | 0.43%   |
| PLEXTOR             | 1         | 1      | 0.43%   |
| Pioneer             | 1         | 1      | 0.43%   |
| MyDigitalSSD        | 1         | 1      | 0.43%   |
| Mushkin             | 1         | 1      | 0.43%   |
| Leven               | 1         | 1      | 0.43%   |
| KingDian            | 1         | 1      | 0.43%   |
| Integral            | 1         | 1      | 0.43%   |
| INDMEM              | 1         | 1      | 0.43%   |
| HPE                 | 1         | 1      | 0.43%   |
| Hikvision           | 1         | 1      | 0.43%   |
| GOODRAM             | 1         | 1      | 0.43%   |
| Gigabyte Technology | 1         | 1      | 0.43%   |
| Fujitsu             | 1         | 2      | 0.43%   |
| FORESEE             | 1         | 1      | 0.43%   |
| China               | 1         | 1      | 0.43%   |
| AMD                 | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 208       | 253    | 50.49%  |
| HDD  | 155       | 183    | 37.62%  |
| NVMe | 49        | 54     | 11.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 338       | 436    | 87.34%  |
| NVMe | 49        | 54     | 12.66%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 284       | 356    | 79.78%  |
| 0.51-1.0   | 64        | 72     | 17.98%  |
| 1.01-2.0   | 7         | 7      | 1.97%   |
| 4.01-10.0  | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 237       | 59.25%  |
| 101-250    | 75        | 18.75%  |
| 251-500    | 52        | 13%     |
| 501-1000   | 19        | 4.75%   |
| 21-50      | 8         | 2%      |
| 51-100     | 8         | 2%      |
| 1001-2000  | 1         | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 384       | 99.48%  |
| 21-50   | 1         | 0.26%   |
| 101-250 | 1         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                          | 3         | 3      | 3.13%   |
| Seagate ST9500420AS 500GB                       | 3         | 3      | 3.13%   |
| WDC WD3200BEVT-22ZCT0 320GB                     | 2         | 2      | 2.08%   |
| Toshiba MQ01ABF050 500GB                        | 2         | 3      | 2.08%   |
| Toshiba MQ01ABD075 752GB                        | 2         | 2      | 2.08%   |
| Toshiba MK3261GSYN 320GB                        | 2         | 4      | 2.08%   |
| Seagate ST9500325AS 500GB                       | 2         | 2      | 2.08%   |
| Seagate ST9320423AS 320GB                       | 2         | 2      | 2.08%   |
| Seagate ST500LT012-9WS142 500GB                 | 2         | 2      | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                  | 2         | 2      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 2         | 3      | 2.08%   |
| Hitachi HTS545050A7E380 500GB                   | 2         | 2      | 2.08%   |
| Hitachi HTS545032B9A300 320GB                   | 2         | 2      | 2.08%   |
| WDC WDS200T2B0A 2TB                             | 1         | 1      | 1.04%   |
| WDC WD5000LPVX-60V0TT0 500GB                    | 1         | 1      | 1.04%   |
| WDC WD5000LPLX-60ZNTT1 500GB                    | 1         | 1      | 1.04%   |
| WDC WD5000LPCX-75VHAT0 500GB                    | 1         | 1      | 1.04%   |
| WDC WD5000LPCX-60VHAT0 500GB                    | 1         | 1      | 1.04%   |
| WDC WD5000BPVT-22HXZT3 500GB                    | 1         | 1      | 1.04%   |
| WDC WD3200BPVT-55ZEST0 320GB                    | 1         | 1      | 1.04%   |
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 1.04%   |
| WDC WD3200BEVT-60ZCT1 320GB                     | 1         | 1      | 1.04%   |
| WDC WD3200BEKT-60V5T1 320GB                     | 1         | 1      | 1.04%   |
| WDC WD1600BEVT-80A23T0 160GB                    | 1         | 1      | 1.04%   |
| WDC WD1600BEVS-60RST0 160GB                     | 1         | 1      | 1.04%   |
| WDC WD1600BEKT-66F3T2 160GB                     | 1         | 1      | 1.04%   |
| WDC WD10JPVX-75JC3T0 1TB                        | 1         | 1      | 1.04%   |
| WDC WD10JMVW-11AJGS0 1TB                        | 1         | 1      | 1.04%   |
| Toshiba THNSNX024GMNT 24GB                      | 1         | 1      | 1.04%   |
| Toshiba MQ02ABF050H-SSHD-8GB                    | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD100H 1TB                         | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD050 247GB                        | 1         | 1      | 1.04%   |
| Toshiba MQ01ABD032 320GB                        | 1         | 1      | 1.04%   |
| Toshiba MK8034GSX 80GB                          | 1         | 1      | 1.04%   |
| Toshiba MK7559GSXF 752GB                        | 1         | 1      | 1.04%   |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 1.04%   |
| Toshiba MK3265GSXN 320GB                        | 1         | 2      | 1.04%   |
| Toshiba MK2555GSXF 250GB                        | 1         | 1      | 1.04%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 1.04%   |
| SSSTC CVB-8D128-HP 128GB                        | 1         | 1      | 1.04%   |
| Seagate ST9640320AS 640GB                       | 1         | 1      | 1.04%   |
| Seagate ST9320325AS 320GB                       | 1         | 1      | 1.04%   |
| Seagate ST9160821AS 160GB                       | 1         | 1      | 1.04%   |
| Seagate ST9160412AS 160GB                       | 1         | 1      | 1.04%   |
| Seagate ST750LM022 HN-M750MBB 752GB             | 1         | 1      | 1.04%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 1.04%   |
| Seagate ST500LM012 HN-M500MBB 500GB             | 1         | 1      | 1.04%   |
| Seagate ST320LT014-9YK142 320GB                 | 1         | 1      | 1.04%   |
| Seagate ST320LT012-9WS14C 320GB                 | 1         | 4      | 1.04%   |
| Seagate ST320LT007-9ZV142 320GB                 | 1         | 1      | 1.04%   |
| Seagate ST1000LM049-2GH172 1TB                  | 1         | 1      | 1.04%   |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 1.04%   |
| Seagate ST1000LM025 HN-M101ABB 1TB              | 1         | 1      | 1.04%   |
| SanDisk SD5SG2128G1052E 128GB                   | 1         | 1      | 1.04%   |
| SanDisk SD5SE2256G1002E 256GB                   | 1         | 1      | 1.04%   |
| Samsung Electronics SSD 840 Series 500GB        | 1         | 1      | 1.04%   |
| Samsung Electronics HS082HB 80GB                | 1         | 1      | 1.04%   |
| Samsung Electronics HM321HI 320GB               | 1         | 1      | 1.04%   |
| Samsung Electronics HM160HI 160GB               | 1         | 1      | 1.04%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 1.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 27.08%  |
| Toshiba             | 20        | 24     | 20.83%  |
| WDC                 | 17        | 17     | 17.71%  |
| Hitachi             | 10        | 11     | 10.42%  |
| HGST                | 5         | 6      | 5.21%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| SanDisk             | 2         | 2      | 2.08%   |
| Micron Technology   | 2         | 2      | 2.08%   |
| LITEON              | 2         | 2      | 2.08%   |
| SSSTC               | 1         | 1      | 1.04%   |
| Kingston            | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| Fujitsu             | 1         | 1      | 1.04%   |
| Crucial             | 1         | 3      | 1.04%   |
| Corsair             | 1         | 1      | 1.04%   |
| Apple               | 1         | 1      | 1.04%   |
| AGI                 | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 30     | 32.1%   |
| Toshiba             | 19        | 23     | 23.46%  |
| WDC                 | 16        | 16     | 19.75%  |
| Hitachi             | 10        | 11     | 12.35%  |
| HGST                | 5         | 6      | 6.17%   |
| Samsung Electronics | 3         | 3      | 3.7%    |
| Fujitsu             | 1         | 1      | 1.23%   |
| Apple               | 1         | 1      | 1.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 79        | 91     | 84.04%  |
| SSD  | 14        | 16     | 14.89%  |
| NVMe | 1         | 1      | 1.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB       | 1         | 1      | 50%     |
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HPE     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 298       | 378    | 75.25%  |
| Malfunc  | 94        | 108    | 23.74%  |
| Detected | 2         | 2      | 0.51%   |
| Failed   | 2         | 2      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 332       | 79.62%  |
| AMD                              | 29        | 6.95%   |
| Samsung Electronics              | 13        | 3.12%   |
| Sandisk                          | 11        | 2.64%   |
| Nvidia                           | 7         | 1.68%   |
| Toshiba                          | 4         | 0.96%   |
| KIOXIA                           | 4         | 0.96%   |
| Silicon Motion                   | 3         | 0.72%   |
| Kingston Technology Company      | 3         | 0.72%   |
| SK Hynix                         | 2         | 0.48%   |
| Realtek Semiconductor            | 2         | 0.48%   |
| Micron/Crucial Technology        | 2         | 0.48%   |
| JMicron Technology               | 2         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Micron Technology                | 1         | 0.24%   |
| ADATA Technology                 | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 63        | 13.82%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 43        | 9.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 31        | 6.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 29        | 6.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 23        | 5.04%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 4.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 3.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 17        | 3.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 3.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 3.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 3.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 2.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 2.41%   |
| Unknown                                                                          | 8         | 1.75%   |
| Nvidia MCP79 AHCI Controller                                                     | 7         | 1.54%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.32%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 0.88%   |
| KIOXIA unknown                                                                   | 4         | 0.88%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 4         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.44%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.44%   |
| Intel SSD 660P Series                                                            | 2         | 0.44%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.44%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 2         | 0.44%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.44%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.44%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 2         | 0.44%   |
| AMD SB600 IDE                                                                    | 2         | 0.44%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.22%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.22%   |
| Toshiba unknown                                                                  | 1         | 0.22%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.22%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.22%   |
| SK Hynix BC511                                                                   | 1         | 0.22%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.22%   |
| Sandisk unknown                                                                  | 1         | 0.22%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.22%   |
| Samsung SM951 AHCI                                                               | 1         | 0.22%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.22%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.22%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 1         | 0.22%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 336       | 76.02%  |
| NVMe | 49        | 11.09%  |
| IDE  | 36        | 8.14%   |
| RAID | 21        | 4.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 354       | 91.71%  |
| AMD    | 32        | 8.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel CPU Version                    | 12        | 3.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 11        | 2.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz    | 10        | 2.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 8         | 2.07%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 8         | 2.07%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 8         | 2.07%   |
| Intel Core i5-3317U CPU @ 1.70GHz    | 7         | 1.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 7         | 1.81%   |
| Intel Core i7-6600U CPU @ 2.60GHz    | 6         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 6         | 1.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz    | 6         | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 5         | 1.3%    |
| Intel Core i5-3230M CPU @ 2.60GHz    | 5         | 1.3%    |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 5         | 1.3%    |
| Intel Core i3-6006U CPU @ 2.00GHz    | 5         | 1.3%    |
| Intel Core i7-7600U CPU @ 2.80GHz    | 4         | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz    | 4         | 1.04%   |
| Intel Core i7-3520M CPU @ 2.90GHz    | 4         | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 4         | 1.04%   |
| Intel Core i3 CPU M 330 @ 2.13GHz    | 4         | 1.04%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz | 4         | 1.04%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz | 4         | 1.04%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz | 4         | 1.04%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 4         | 1.04%   |
| Intel Core 2 Duo                     | 4         | 1.04%   |
| Intel Atom CPU N450 @ 1.66GHz        | 4         | 1.04%   |
| Intel Genuine CPU                    | 3         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz    | 3         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 3         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 3         | 0.78%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 3         | 0.78%   |
| Intel Core i7-3632QM CPU @ 2.20GHz   | 3         | 0.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz   | 3         | 0.78%   |
| Intel Core i7 CPU M 620 @ 2.67GHz    | 3         | 0.78%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 3         | 0.78%   |
| Intel Core i5 CPU M 540 @ 2.53GHz    | 3         | 0.78%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 3         | 0.78%   |
| Intel Core i3-3227U CPU @ 1.90GHz    | 3         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz    | 3         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz    | 3         | 0.78%   |
| Intel Core i3-2330M CPU @ 2.20GHz    | 3         | 0.78%   |
| Intel Pentium CPU N3530 @ 2.16GHz    | 2         | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 2         | 0.52%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz   | 2         | 0.52%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz   | 2         | 0.52%   |
| Intel Core i7-2677M CPU @ 1.80GHz    | 2         | 0.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 2         | 0.52%   |
| Intel Core i5-8350U CPU @ 1.70GHz    | 2         | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz    | 2         | 0.52%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 0.52%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz   | 2         | 0.52%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz   | 2         | 0.52%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz   | 2         | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 0.52%   |
| Intel Core i5-3340M CPU @ 2.70GHz    | 2         | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 2         | 0.52%   |
| Intel Core i5 CPU M 560 @ 2.67GH     | 2         | 0.52%   |
| Intel Core i3-8145U CPU @ 2.10GHz    | 2         | 0.52%   |
| Intel Core i3-7100U CPU @ 2.40GHz    | 2         | 0.52%   |
| Intel Core i3-5005U CPU @ 2.00GHz    | 2         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 136       | 35.23%  |
| Intel Core i7           | 68        | 17.62%  |
| Intel Core i3           | 43        | 11.14%  |
| Intel Core 2 Duo        | 39        | 10.1%   |
| Intel Celeron           | 22        | 5.7%    |
| Other                   | 16        | 4.15%   |
| Intel Pentium           | 12        | 3.11%   |
| Intel Atom              | 8         | 2.07%   |
| AMD Ryzen 5             | 6         | 1.55%   |
| AMD Ryzen 7             | 5         | 1.3%    |
| AMD A6                  | 5         | 1.3%    |
| Intel Genuine           | 3         | 0.78%   |
| AMD Ryzen 3             | 3         | 0.78%   |
| AMD E1                  | 3         | 0.78%   |
| Intel Core M            | 2         | 0.52%   |
| AMD E                   | 2         | 0.52%   |
| AMD A10                 | 2         | 0.52%   |
| Intel Pentium Silver    | 1         | 0.26%   |
| Intel Pentium Dual-Core | 1         | 0.26%   |
| Intel Core m3           | 1         | 0.26%   |
| Intel Core 2 Solo       | 1         | 0.26%   |
| Intel Core 2            | 1         | 0.26%   |
| AMD Turion 64 X2 Mobile | 1         | 0.26%   |
| AMD Phenom II           | 1         | 0.26%   |
| AMD G                   | 1         | 0.26%   |
| AMD E2                  | 1         | 0.26%   |
| AMD C-60                | 1         | 0.26%   |
| AMD Athlon II           | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 258       | 66.84%  |
| 4       | 69        | 17.88%  |
| Unknown | 38        | 9.84%   |
| 6       | 6         | 1.55%   |
| 1       | 5         | 1.3%    |
| 8       | 4         | 1.04%   |
| 16      | 3         | 0.78%   |
| 12      | 3         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 370       | 95.85%  |
| 2       | 14        | 3.63%   |
| Unknown | 2         | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 257       | 66.58%  |
| 1       | 90        | 23.32%  |
| Unknown | 39        | 10.1%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 58        | 15.03%  |
| KabyLake      | 51        | 13.21%  |
| Haswell       | 44        | 11.4%   |
| SandyBridge   | 42        | 10.88%  |
| Penryn        | 38        | 9.84%   |
| Westmere      | 31        | 8.03%   |
| Skylake       | 30        | 7.77%   |
| Broadwell     | 16        | 4.15%   |
| Core          | 15        | 3.89%   |
| Silvermont    | 12        | 3.11%   |
| Zen 2         | 7         | 1.81%   |
| Bonnell       | 6         | 1.55%   |
| Bobcat        | 6         | 1.55%   |
| Zen+          | 5         | 1.3%    |
| Goldmont      | 4         | 1.04%   |
| Excavator     | 4         | 1.04%   |
| TigerLake     | 3         | 0.78%   |
| Zen 3         | 2         | 0.52%   |
| Piledriver    | 2         | 0.52%   |
| K10           | 2         | 0.52%   |
| Jaguar        | 2         | 0.52%   |
| CometLake     | 2         | 0.52%   |
| Nehalem       | 1         | 0.26%   |
| K8 Hammer     | 1         | 0.26%   |
| K10 Llano     | 1         | 0.26%   |
| Goldmont plus | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 313       | 69.71%  |
| Nvidia                           | 79        | 17.59%  |
| AMD                              | 56        | 12.47%  |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 12.04%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 40        | 8.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 6.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 5.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 4.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 4.38%   |
| Intel HD Graphics 620                                                                    | 20        | 4.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.63%   |
| Intel HD Graphics 5500                                                                   | 11        | 2.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 9         | 1.97%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.53%   |
| Intel HD Graphics 530                                                                    | 7         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.53%   |
| AMD Renoir                                                                               | 7         | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.31%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.31%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.09%   |
| Nvidia TU117M                                                                            | 4         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 0.88%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.88%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 4         | 0.88%   |
| Intel HD Graphics 630                                                                    | 4         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.66%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 3         | 0.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.66%   |
| Intel HD Graphics 5300                                                                   | 3         | 0.66%   |
| Intel HD Graphics 500                                                                    | 3         | 0.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.66%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.44%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.44%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.44%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.44%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.44%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.44%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.44%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 2         | 0.44%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.44%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 2         | 0.44%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.44%   |
| AMD Chelsea LP [Radeon HD 7730M]                                                         | 2         | 0.44%   |
| AMD Cezanne                                                                              | 2         | 0.44%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.22%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.22%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.22%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.22%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.22%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.22%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.22%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 1         | 0.22%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 223       | 57.77%  |
| Intel + Nvidia | 42        | 10.88%  |
| 1 x AMD        | 36        | 9.33%   |
| 2 x Intel      | 33        | 8.55%   |
| 1 x Nvidia     | 31        | 8.03%   |
| Intel + AMD    | 14        | 3.63%   |
| AMD + Nvidia   | 5         | 1.3%    |
| 2 x Nvidia     | 1         | 0.26%   |
| 1 x SiS        | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 335       | 85.9%   |
| Unknown     | 39        | 10%     |
| Proprietary | 16        | 4.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 348       | 89.69%  |
| 0.01-0.5   | 27        | 6.96%   |
| 0.51-1.0   | 8         | 2.06%   |
| 1.01-2.0   | 3         | 0.77%   |
| 5.01-6.0   | 1         | 0.26%   |
| 3.01-4.0   | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 76        | 22.29%  |
| AU Optronics            | 61        | 17.89%  |
| Chimei Innolux          | 48        | 14.08%  |
| Samsung Electronics     | 35        | 10.26%  |
| BOE                     | 33        | 9.68%   |
| Lenovo                  | 24        | 7.04%   |
| Apple                   | 16        | 4.69%   |
| Chi Mei Optoelectronics | 10        | 2.93%   |
| InfoVision              | 7         | 2.05%   |
| Philips                 | 3         | 0.88%   |
| LG Philips              | 2         | 0.59%   |
| Hewlett-Packard         | 2         | 0.59%   |
| Goldstar                | 2         | 0.59%   |
| Dell                    | 2         | 0.59%   |
| BenQ                    | 2         | 0.59%   |
| AOC                     | 2         | 0.59%   |
| Vestel Elektronik       | 1         | 0.29%   |
| Toshiba                 | 1         | 0.29%   |
| TMX                     | 1         | 0.29%   |
| Sony                    | 1         | 0.29%   |
| Sharp                   | 1         | 0.29%   |
| PANDA                   | 1         | 0.29%   |
| Nvidia                  | 1         | 0.29%   |
| Lenovo Group Limited    | 1         | 0.29%   |
| LED                     | 1         | 0.29%   |
| KTC                     | 1         | 0.29%   |
| HannStar                | 1         | 0.29%   |
| Fujitsu Siemens         | 1         | 0.29%   |
| Eizo                    | 1         | 0.29%   |
| CPT                     | 1         | 0.29%   |
| Ancor Communications    | 1         | 0.29%   |
| Acer                    | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 6         | 1.75%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 4         | 1.17%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 4         | 1.17%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch                  | 4         | 1.17%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 4         | 1.17%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 3         | 0.87%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 3         | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 3         | 0.87%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch            | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 0.87%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 2         | 0.58%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch             | 2         | 0.58%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 2         | 0.58%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch              | 2         | 0.58%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 2         | 0.58%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 2         | 0.58%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 2         | 0.58%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 2         | 0.58%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 2         | 0.58%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 310x170mm 13.9-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO1312 1280x800 290x180mm 13.4-inch | 2         | 0.58%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                     | 2         | 0.58%   |
| BOE LCD Monitor BOE0600 1366x768 310x170mm 13.9-inch                     | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 310x170mm 13.9-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO303E 1600x900 310x170mm 13.9-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 340x190mm 15.3-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch            | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 2         | 0.58%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 2         | 0.58%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch       | 1         | 0.29%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 0.29%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                    | 1         | 0.29%   |
| Sony SDM-HS95P SNY2500 1280x1024 380x300mm 19.1-inch                     | 1         | 0.29%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch                  | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch     | 1         | 0.29%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch        | 1         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch     | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch     | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch     | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 154       | 45.97%  |
| 1920x1080 (FHD)    | 89        | 26.57%  |
| 1280x800 (WXGA)    | 33        | 9.85%   |
| 1600x900 (HD+)     | 26        | 7.76%   |
| 1440x900 (WXGA+)   | 6         | 1.79%   |
| 1024x600           | 5         | 1.49%   |
| 2560x1440 (QHD)    | 4         | 1.19%   |
| 1920x1200 (WUXGA)  | 4         | 1.19%   |
| 3840x2160 (4K)     | 3         | 0.9%    |
| 1280x1024 (SXGA)   | 3         | 0.9%    |
| 3200x1800 (QHD+)   | 2         | 0.6%    |
| 1920x540           | 2         | 0.6%    |
| 3200x2000          | 1         | 0.3%    |
| 2560x1600          | 1         | 0.3%    |
| 1680x1050 (WSXGA+) | 1         | 0.3%    |
| 1024x768 (XGA)     | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 119       | 34.69%  |
| 13      | 109       | 31.78%  |
| 12      | 34        | 9.91%   |
| 17      | 15        | 4.37%   |
| 14      | 15        | 4.37%   |
| 11      | 13        | 3.79%   |
| 10      | 7         | 2.04%   |
| 24      | 6         | 1.75%   |
| 27      | 5         | 1.46%   |
| 19      | 5         | 1.46%   |
| 21      | 3         | 0.87%   |
| 31      | 2         | 0.58%   |
| 23      | 2         | 0.58%   |
| 22      | 2         | 0.58%   |
| 54      | 1         | 0.29%   |
| 42      | 1         | 0.29%   |
| 40      | 1         | 0.29%   |
| 18      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 195       | 57.02%  |
| 201-300     | 102       | 29.82%  |
| 351-400     | 17        | 4.97%   |
| 501-600     | 12        | 3.51%   |
| 401-500     | 9         | 2.63%   |
| 601-700     | 3         | 0.88%   |
| 801-900     | 1         | 0.29%   |
| 1001-1500   | 1         | 0.29%   |
| 901-1000    | 1         | 0.29%   |
| Unknown     | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 271       | 83.64%  |
| 16/10   | 46        | 14.2%   |
| 5/4     | 3         | 0.93%   |
| 3/2     | 2         | 0.62%   |
| 4/3     | 1         | 0.31%   |
| Unknown | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 105       | 30.61%  |
| 91-100         | 90        | 26.24%  |
| 61-70          | 34        | 9.91%   |
| 101-110        | 29        | 8.45%   |
| 71-80          | 18        | 5.25%   |
| 51-60          | 13        | 3.79%   |
| 121-130        | 12        | 3.5%    |
| 201-250        | 11        | 3.21%   |
| 41-50          | 7         | 2.04%   |
| 301-350        | 5         | 1.46%   |
| 151-200        | 5         | 1.46%   |
| 351-500        | 2         | 0.58%   |
| 251-300        | 2         | 0.58%   |
| 141-150        | 2         | 0.58%   |
| 131-140        | 2         | 0.58%   |
| 111-120        | 2         | 0.58%   |
| 501-1000       | 2         | 0.58%   |
| More than 1000 | 1         | 0.29%   |
| Unknown        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 40.36%  |
| 101-120       | 136       | 40.36%  |
| 51-100        | 44        | 13.06%  |
| 161-240       | 18        | 5.34%   |
| More than 240 | 2         | 0.59%   |
| Unknown       | 1         | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 305       | 78.01%  |
| 0     | 61        | 15.6%   |
| 2     | 25        | 6.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 222       | 36.82%  |
| Realtek Semiconductor             | 152       | 25.21%  |
| Qualcomm Atheros                  | 92        | 15.26%  |
| Broadcom                          | 66        | 10.95%  |
| Marvell Technology Group          | 13        | 2.16%   |
| Nvidia                            | 7         | 1.16%   |
| JMicron Technology                | 6         | 1%      |
| Ericsson Business Mobile Networks | 6         | 1%      |
| Ralink                            | 5         | 0.83%   |
| Sierra Wireless                   | 4         | 0.66%   |
| Ralink Technology                 | 4         | 0.66%   |
| Huawei Technologies               | 4         | 0.66%   |
| Hewlett-Packard                   | 3         | 0.5%    |
| TP-Link                           | 2         | 0.33%   |
| NetGear                           | 2         | 0.33%   |
| Google                            | 2         | 0.33%   |
| Edimax Technology                 | 2         | 0.33%   |
| Dell                              | 2         | 0.33%   |
| D-Link System                     | 2         | 0.33%   |
| Xiaomi                            | 1         | 0.17%   |
| Toshiba                           | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Mercucys                          | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| AboCom Systems                    | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 96        | 12.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 42        | 5.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 32        | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 3.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 3.21%   |
| Intel Wireless 8265 / 8275                                              | 22        | 2.82%   |
| Intel Wireless 7260                                                     | 22        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 2.44%   |
| Intel Wireless 8260                                                     | 18        | 2.31%   |
| Intel Wireless 7265                                                     | 17        | 2.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 1.79%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 1.54%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 1.54%   |
| Intel Ethernet Connection I218-LM                                       | 11        | 1.41%   |
| Intel WiFi Link 5100                                                    | 10        | 1.28%   |
| Intel Ethernet Connection I219-LM                                       | 10        | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                                   | 10        | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.15%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 7         | 0.9%    |
| Nvidia MCP79 Ethernet                                                   | 7         | 0.9%    |
| Intel Wi-Fi 6 AX200                                                     | 7         | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 0.9%    |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.9%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 7         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 0.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 6         | 0.77%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 6         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 0.77%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 6         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 5         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                                   | 4         | 0.51%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.51%   |
| Broadcom BCM43225 802.11b/g/n                                           | 4         | 0.51%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 3         | 0.38%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.38%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.38%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.38%   |
| Intel Wireless 3165                                                     | 3         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 213       | 51.95%  |
| Qualcomm Atheros      | 84        | 20.49%  |
| Broadcom              | 49        | 11.95%  |
| Realtek Semiconductor | 40        | 9.76%   |
| Ralink                | 5         | 1.22%   |
| Sierra Wireless       | 4         | 0.98%   |
| Ralink Technology     | 4         | 0.98%   |
| TP-Link               | 2         | 0.49%   |
| NetGear               | 2         | 0.49%   |
| Edimax Technology     | 2         | 0.49%   |
| Mercucys              | 1         | 0.24%   |
| Dell                  | 1         | 0.24%   |
| D-Link System         | 1         | 0.24%   |
| D-Link                | 1         | 0.24%   |
| AboCom Systems        | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 6.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 25        | 6.01%   |
| Intel Wireless 8265 / 8275                                              | 22        | 5.29%   |
| Intel Wireless 7260                                                     | 22        | 5.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 4.57%   |
| Intel Wireless 8260                                                     | 18        | 4.33%   |
| Intel Wireless 7265                                                     | 17        | 4.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 3.37%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 2.88%   |
| Intel WiFi Link 5100                                                    | 10        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.68%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 1.68%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 1.68%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 1.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 7         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 6         | 1.44%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 6         | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.96%   |
| Broadcom BCM43225 802.11b/g/n                                           | 4         | 0.96%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 3         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.72%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.72%   |
| Intel Wireless 3165                                                     | 3         | 0.72%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.72%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 3         | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.48%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.48%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.48%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.48%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 0.48%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.24%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.24%   |
| Sierra Wireless EM7455                                                  | 1         | 0.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.24%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 139       | 39.71%  |
| Intel                            | 122       | 34.86%  |
| Broadcom                         | 29        | 8.29%   |
| Qualcomm Atheros                 | 27        | 7.71%   |
| Marvell Technology Group         | 13        | 3.71%   |
| Nvidia                           | 7         | 2%      |
| JMicron Technology               | 6         | 1.71%   |
| Huawei Technologies              | 2         | 0.57%   |
| Google                           | 2         | 0.57%   |
| Xiaomi                           | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Samsung Electronics              | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 96        | 27.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 42        | 12%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 32        | 9.14%   |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 3.43%   |
| Intel Ethernet Connection I218-LM                                              | 11        | 3.14%   |
| Intel Ethernet Connection I219-LM                                              | 10        | 2.86%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 2.86%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 2.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 2%      |
| Nvidia MCP79 Ethernet                                                          | 7         | 2%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 6         | 1.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 1.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.86%   |
| Intel Ethernet Connection (3) I218-V                                           | 3         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.86%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.86%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.86%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 3         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.57%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.57%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.57%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.57%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.57%   |
| Huawei USB Composite Device                                                    | 2         | 0.57%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.57%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.29%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.29%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.29%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.29%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.29%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.29%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.29%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.29%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.29%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.29%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.29%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.29%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 380       | 51.35%  |
| Ethernet | 346       | 46.76%  |
| Modem    | 9         | 1.22%   |
| Unknown  | 5         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 333       | 50.15%  |
| WiFi     | 321       | 48.34%  |
| Modem    | 5         | 0.75%   |
| Unknown  | 5         | 0.75%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 335       | 86.79%  |
| 1     | 50        | 12.95%  |
| 0     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 370       | 95.12%  |
| Yes  | 19        | 4.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 47.22%  |
| Broadcom                        | 29        | 11.51%  |
| Apple                           | 26        | 10.32%  |
| Qualcomm Atheros Communications | 20        | 7.94%   |
| Realtek Semiconductor           | 14        | 5.56%   |
| IMC Networks                    | 10        | 3.97%   |
| Lite-On Technology              | 7         | 2.78%   |
| Hewlett-Packard                 | 5         | 1.98%   |
| Foxconn / Hon Hai               | 5         | 1.98%   |
| Dell                            | 5         | 1.98%   |
| Cambridge Silicon Radio         | 5         | 1.98%   |
| Ralink                          | 3         | 1.19%   |
| ASUSTek Computer                | 2         | 0.79%   |
| Alps Electric                   | 2         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 80        | 31.37%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 10        | 3.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 10        | 3.92%   |
| Apple Bluetooth Host Controller                             | 10        | 3.92%   |
| Intel AX201 Bluetooth                                       | 9         | 3.53%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 3.14%   |
| Intel AX200 Bluetooth                                       | 7         | 2.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 2.35%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 5         | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 5         | 1.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 5         | 1.96%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 5         | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 1.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 4         | 1.57%   |
| Apple Built-in iSight (no firmware loaded)                  | 4         | 1.57%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 1.18%   |
| Realtek Bluetooth Radio                                     | 3         | 1.18%   |
| Ralink RT3290 Bluetooth                                     | 3         | 1.18%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 3         | 1.18%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 3         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 1.18%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 3         | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 1.18%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.18%   |
| Dell DW375 Bluetooth Module                                 | 3         | 1.18%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 0.78%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 2         | 0.78%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 2         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 2         | 0.78%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 2         | 0.78%   |
| Apple Bluetooth HCI                                         | 2         | 0.78%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.39%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.39%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 0.39%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 0.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.39%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.39%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.39%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.39%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0                 | 1         | 0.39%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS     | 1         | 0.39%   |
| IMC Networks Broadcom BCM20702 Bluetooth 4.0 +HS USB Device | 1         | 0.39%   |
| IMC Networks Bluetooth Module                               | 1         | 0.39%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.39%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.39%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth               | 1         | 0.39%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 0.39%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 0.39%   |
| Broadcom Broadcom Bluetooth 4.0                             | 1         | 0.39%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device      | 1         | 0.39%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 1         | 0.39%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 345       | 82.14%  |
| AMD                              | 42        | 10%     |
| Nvidia                           | 26        | 6.19%   |
| XMOS                             | 1         | 0.24%   |
| Texas Instruments                | 1         | 0.24%   |
| SteelSeries ApS                  | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| GN Netcom                        | 1         | 0.24%   |
| Creative Technology              | 1         | 0.24%   |
| C-Media Electronics              | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 68        | 13.44%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 10.28%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 6.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 6.32%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 6.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 30        | 5.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 28        | 5.53%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 2.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 2.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.58%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.58%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.19%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.79%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.79%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.59%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.4%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.4%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.4%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.4%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.4%    |
| XMOS retrieving string failed                                                                     | 1         | 0.2%    |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.2%    |
| SteelSeries ApS SteelSeries Siberia 350                                                           | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.2%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.2%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.2%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.2%    |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.2%    |
| Creative Technology SB X-Fi Surround 5.1                                                          | 1         | 0.2%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.2%    |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]                                 | 1         | 0.2%    |
| AMD RS600 HDMI Audio [Radeon Xpress 1250]                                                         | 1         | 0.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.2%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 124       | 26.27%  |
| SK Hynix            | 93        | 19.7%   |
| Micron Technology   | 46        | 9.75%   |
| Kingston            | 42        | 8.9%    |
| Unknown             | 38        | 8.05%   |
| Elpida              | 23        | 4.87%   |
| Ramaxel Technology  | 15        | 3.18%   |
| Crucial             | 14        | 2.97%   |
| Smart               | 11        | 2.33%   |
| Nanya Technology    | 10        | 2.12%   |
| Unknown             | 8         | 1.69%   |
| A-DATA Technology   | 7         | 1.48%   |
| Teikon              | 5         | 1.06%   |
| Corsair             | 5         | 1.06%   |
| Apacer              | 5         | 1.06%   |
| High Bridge         | 3         | 0.64%   |
| Transcend           | 2         | 0.42%   |
| Team                | 2         | 0.42%   |
| Smart Brazil        | 2         | 0.42%   |
| Silicon Power       | 2         | 0.42%   |
| G.Skill             | 2         | 0.42%   |
| 48spaces            | 2         | 0.42%   |
| V-GeN               | 1         | 0.21%   |
| Unknown (ABCD)      | 1         | 0.21%   |
| Unknown (08B5)      | 1         | 0.21%   |
| Toshiba             | 1         | 0.21%   |
| SHARETRONIC         | 1         | 0.21%   |
| Sesame              | 1         | 0.21%   |
| PNY                 | 1         | 0.21%   |
| PKI/Kingston        | 1         | 0.21%   |
| Kingmax             | 1         | 0.21%   |
| Axiom               | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 10        | 2%      |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 8         | 1.6%    |
| Unknown                                                     | 8         | 1.6%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 7         | 1.4%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 7         | 1.4%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 7         | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 7         | 1.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 7         | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 7         | 1.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 1333MT/s            | 6         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 6         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s               | 5         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 1%      |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                 | 4         | 0.8%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s       | 4         | 0.8%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                | 4         | 0.8%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 0.8%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 4         | 0.8%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 4         | 0.8%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 3         | 0.6%    |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 0.6%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s       | 3         | 0.6%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s       | 3         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s       | 3         | 0.6%    |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s       | 3         | 0.6%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 3         | 0.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 3         | 0.6%    |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 3         | 0.6%    |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s        | 3         | 0.6%    |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s               | 3         | 0.6%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s       | 3         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                          | 2         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                  | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                          | 2         | 0.4%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s       | 2         | 0.4%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 2         | 0.4%    |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s     | 2         | 0.4%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 2         | 0.4%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s      | 2         | 0.4%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                 | 2         | 0.4%    |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                 | 2         | 0.4%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 2         | 0.4%    |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s       | 2         | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s       | 2         | 0.4%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s       | 2         | 0.4%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 2         | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 0.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s       | 2         | 0.4%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 2         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.4%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2133MT/s       | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 235       | 61.52%  |
| DDR4    | 90        | 23.56%  |
| DDR2    | 38        | 9.95%   |
| LPDDR3  | 9         | 2.36%   |
| Unknown | 6         | 1.57%   |
| LPDDR4  | 2         | 0.52%   |
| DRAM    | 2         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 361       | 94.01%  |
| Row Of Chips | 11        | 2.86%   |
| Chip         | 7         | 1.82%   |
| DIMM         | 4         | 1.04%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 187       | 44.1%   |
| 2048  | 115       | 27.12%  |
| 8192  | 92        | 21.7%   |
| 16384 | 21        | 4.95%   |
| 1024  | 6         | 1.42%   |
| 32768 | 3         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 141       | 33.41%  |
| 1333    | 62        | 14.69%  |
| 2400    | 37        | 8.77%   |
| 2667    | 30        | 7.11%   |
| 1334    | 30        | 7.11%   |
| 667     | 28        | 6.64%   |
| 1067    | 25        | 5.92%   |
| 2133    | 21        | 4.98%   |
| 3200    | 15        | 3.55%   |
| 800     | 11        | 2.61%   |
| Unknown | 8         | 1.9%    |
| 1867    | 6         | 1.42%   |
| 1066    | 3         | 0.71%   |
| 4267    | 1         | 0.24%   |
| 1777    | 1         | 0.24%   |
| 975     | 1         | 0.24%   |
| 533     | 1         | 0.24%   |
| 333     | 1         | 0.24%   |

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
| Chicony Electronics                    | 81        | 27.65%  |
| Realtek Semiconductor                  | 29        | 9.9%    |
| Acer                                   | 28        | 9.56%   |
| Microdia                               | 24        | 8.19%   |
| IMC Networks                           | 23        | 7.85%   |
| Sunplus Innovation Technology          | 19        | 6.48%   |
| Suyin                                  | 12        | 4.1%    |
| Lite-On Technology                     | 12        | 4.1%    |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.73%   |
| Apple                                  | 8         | 2.73%   |
| Syntek                                 | 7         | 2.39%   |
| Silicon Motion                         | 7         | 2.39%   |
| Quanta                                 | 6         | 2.05%   |
| Lenovo                                 | 5         | 1.71%   |
| Alcor Micro                            | 5         | 1.71%   |
| Luxvisions Innotech Limited            | 3         | 1.02%   |
| Importek                               | 3         | 1.02%   |
| Z-Star Microelectronics                | 2         | 0.68%   |
| Ricoh                                  | 2         | 0.68%   |
| Logitech                               | 2         | 0.68%   |
| ALi                                    | 2         | 0.68%   |
| Tripath Technology                     | 1         | 0.34%   |
| Primax Electronics                     | 1         | 0.34%   |
| Holitech                               | 1         | 0.34%   |
| Foxconn / Hon Hai                      | 1         | 0.34%   |
| Creative Technology                    | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                  | 21        | 7.07%   |
| Realtek Realtek USB2.0 PC Camera                           | 9         | 3.03%   |
| Realtek Integrated_Webcam_HD                               | 8         | 2.69%   |
| Lite-On Integrated Camera                                  | 8         | 2.69%   |
| Acer Integrated Camera                                     | 8         | 2.69%   |
| Sunplus Integrated_Webcam_HD                               | 7         | 2.36%   |
| Chicony Lenovo Integrated Camera (0.3MP)                   | 6         | 2.02%   |
| Acer Lenovo EasyCamera                                     | 6         | 2.02%   |
| Microdia Integrated_Webcam_HD                              | 5         | 1.68%   |
| IMC Networks USB2.0 HD UVC WebCam                          | 5         | 1.68%   |
| Apple FaceTime HD Camera                                   | 5         | 1.68%   |
| Syntek Lenovo EasyCamera                                   | 4         | 1.35%   |
| Realtek USB Camera                                         | 4         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_HD                       | 4         | 1.35%   |
| Microdia Integrated Webcam                                 | 4         | 1.35%   |
| IMC Networks Integrated Camera                             | 4         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                              | 4         | 1.35%   |
| Chicony HD WebCam                                          | 4         | 1.35%   |
| Sunplus Integrated Camera                                  | 3         | 1.01%   |
| Microdia Dell Laptop Integrated Webcam HD                  | 3         | 1.01%   |
| Lenovo Integrated Webcam [R5U877]                          | 3         | 1.01%   |
| IMC Networks EasyCamera                                    | 3         | 1.01%   |
| Chicony UVC 1.00 device HD UVC WebCam                      | 3         | 1.01%   |
| Chicony USB2.0 HD UVC WebCam                               | 3         | 1.01%   |
| Chicony Lenovo EasyCamera                                  | 3         | 1.01%   |
| Chicony Integrated Camera [ThinkPad]                       | 3         | 1.01%   |
| Chicony HP HD Webcam [Fixed]                               | 3         | 1.01%   |
| Chicony EasyCamera                                         | 3         | 1.01%   |
| Chicony Chicony USB 2.0 Camera                             | 3         | 1.01%   |
| Alcor Micro Acer Integrated Webcam                         | 3         | 1.01%   |
| Acer ThinkPad Integrated Camera                            | 3         | 1.01%   |
| Acer Lenovo Integrated Webcam                              | 3         | 1.01%   |
| Syntek EasyCamera                                          | 2         | 0.67%   |
| Suyin Integrated_Webcam_HD                                 | 2         | 0.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                       | 2         | 0.67%   |
| Sunplus Asus Webcam                                        | 2         | 0.67%   |
| Silicon Motion Realtek USB2.0 PC Camera                    | 2         | 0.67%   |
| Realtek Integrated_Webcam_FHD                              | 2         | 0.67%   |
| Realtek Integrated_Webcam_8M                               | 2         | 0.67%   |
| Realtek Integrated Webcam                                  | 2         | 0.67%   |
| Quanta HP Webcam                                           | 2         | 0.67%   |
| Quanta HP TrueVision HD Camera                             | 2         | 0.67%   |
| Microdia Sonix USB 2.0 Camera                              | 2         | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera        | 2         | 0.67%   |
| Lenovo Integrated Webcam                                   | 2         | 0.67%   |
| IMC Networks USB2.0 UVC VGA WebCam                         | 2         | 0.67%   |
| IMC Networks USB2.0 UVC HD Webcam                          | 2         | 0.67%   |
| Chicony TOSHIBA Web Camera - HD                            | 2         | 0.67%   |
| Chicony thinkpad t430s camera                              | 2         | 0.67%   |
| Chicony HP HD Camera                                       | 2         | 0.67%   |
| Chicony FJ Camera                                          | 2         | 0.67%   |
| Chicony 1.3M Webcam                                        | 2         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera | 2         | 0.67%   |
| Apple FaceTime HD Camera (Built-in)                        | 2         | 0.67%   |
| Acer SunplusIT Integrated Camera                           | 2         | 0.67%   |
| Acer SunplusIT INC. Integrated Camera                      | 2         | 0.67%   |
| Acer HD Webcam                                             | 2         | 0.67%   |
| Z-Star WebCam SC-03FFL11739P                               | 1         | 0.34%   |
| Z-Star Webcam                                              | 1         | 0.34%   |
| Tripath 2M Front Camera                                    | 1         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 31        | 46.27%  |
| Upek                       | 12        | 17.91%  |
| AuthenTec                  | 11        | 16.42%  |
| STMicroelectronics         | 4         | 5.97%   |
| Synaptics                  | 3         | 4.48%   |
| LighTuning Technology      | 2         | 2.99%   |
| Broadcom                   | 2         | 2.99%   |
| Shenzhen Goodix Technology | 1         | 1.49%   |
| Elan Microelectronics      | 1         | 1.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 11        | 16.42%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 8         | 11.94%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 8.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 5         | 7.46%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 5.97%   |
| STMicroelectronics Fingerprint Reader                                        | 4         | 5.97%   |
| AuthenTec AES2810                                                            | 4         | 5.97%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 2.99%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 2         | 2.99%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 2.99%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.99%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 2         | 2.99%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.99%   |
| AuthenTec AES1600                                                            | 2         | 2.99%   |
| Validity Sensors VFS491                                                      | 1         | 1.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 1.49%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.49%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 1.49%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 1.49%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 1.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 1.49%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 1.49%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 1.49%   |

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
| 2     | 129       | 32.41%  |
| 1     | 120       | 30.15%  |
| 3     | 62        | 15.58%  |
| 0     | 56        | 14.07%  |
| 4     | 25        | 6.28%   |
| 5     | 4         | 1.01%   |
| 6     | 2         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 281       | 43.5%   |
| Card reader              | 124       | 19.2%   |
| Bluetooth                | 70        | 10.84%  |
| Net/wireless             | 69        | 10.68%  |
| Fingerprint reader       | 66        | 10.22%  |
| Firewire controller      | 17        | 2.63%   |
| Storage                  | 6         | 0.93%   |
| Sound                    | 4         | 0.62%   |
| Network                  | 3         | 0.46%   |
| Storage/raid             | 2         | 0.31%   |
| Net/ethernet             | 2         | 0.31%   |
| Dvb card                 | 2         | 0.31%   |

