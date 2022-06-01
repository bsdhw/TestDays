helloSystem 0.7.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 154

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [9e2661b9e0](https://bsd-hardware.info/?probe=9e2661b9e0) | May 24, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| HP            | Pavilion dv6                | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [34ac291019](https://bsd-hardware.info/?probe=34ac291019) | May 11, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| HP            | ProBook 4340s               | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Unknown       | W1415A                      | [1b2c63a845](https://bsd-hardware.info/?probe=1b2c63a845) | May 07, 2022 |
| Sony          | VGN-NW25GF_S                | [84b50ca3f1](https://bsd-hardware.info/?probe=84b50ca3f1) | May 06, 2022 |
| Toshiba       | Satellite P300              | [fca7b38039](https://bsd-hardware.info/?probe=fca7b38039) | May 04, 2022 |
| Lenovo        | B470 HuronRiver Platform    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| HP            | Pavilion m6                 | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Acer          | Aspire A315-41              | [c59d8482e8](https://bsd-hardware.info/?probe=c59d8482e8) | May 01, 2022 |
| Apple         | MacBookPro5,5               | [807676e010](https://bsd-hardware.info/?probe=807676e010) | Apr 30, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| Dell          | Inspiron 5437               | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| HP            | 2000                        | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| ASUSTek       | X556UJ                      | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| Lenovo        | G51-35 80M8                 | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [a3da09ae5e](https://bsd-hardware.info/?probe=a3da09ae5e) | Apr 15, 2022 |
| System76      | Lemur Pro                   | [276ee4e96e](https://bsd-hardware.info/?probe=276ee4e96e) | Apr 13, 2022 |
| Lenovo        | ThinkPad X61 7675K2U        | [24f93b9532](https://bsd-hardware.info/?probe=24f93b9532) | Apr 10, 2022 |
| Panasonic     | CF-B11JWCYS                 | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| HP            | Pavilion 11                 | [a13373b255](https://bsd-hardware.info/?probe=a13373b255) | Apr 07, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| LG Electro... | E300-A.CP20T                | [304701f666](https://bsd-hardware.info/?probe=304701f666) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Dell          | Vostro 3490                 | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
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
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Acer          | V5-131                      | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| Dell          | Latitude E4310              | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude E5470              | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| TUXEDO        | InfinityBook13V3            | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Acer          | Aspire E5-511G              | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP            | G62                         | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Apple         | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| Dell          | Latitude 7280               | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer          | Aspire ES1-311              | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell          | Latitude E6540              | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| HP            | EliteBook 2560p             | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Acer          | V5-131                      | [ff427cb0c9](https://bsd-hardware.info/?probe=ff427cb0c9) | Jan 18, 2022 |
| Gateway       | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Lenovo        | ThinkPad T440 20B7000PHV    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer          | V5-131                      | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Acer          | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Acer          | Aspire E5-476G              | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Dell          | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MX     | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP            | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Notebook      | N15_17RD                    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
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
| HP            | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba       | Satellite L550              | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek       | N56VB                       | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| Dell          | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| HP            | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek       | X540LA                      | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Toshiba       | Satellite S55t-B            | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Lenovo        | V310-14IKB 80T2             | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| Toshiba       | Satellite C640              | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba       | Satellite C640              | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Lenovo        | ThinkPad T60 1951FEG        | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| ASUSTek       | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 129       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 128       | 99.22%  |
| GNOME        | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 129       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 129       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 123       | 95.35%  |
| C     | 2         | 1.55%   |
| uk_UA | 1         | 0.78%   |
| it_IT | 1         | 0.78%   |
| fr_FR | 1         | 0.78%   |
| es_ES | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 125       | 96.9%   |
| BIOS | 4         | 3.1%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 70        | 53.44%  |
| Zfs    | 61        | 46.56%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 128       | 99.22%  |
| MBR  | 1         | 0.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 30.23%  |
| Hewlett-Packard     | 20        | 15.5%   |
| Dell                | 16        | 12.4%   |
| Acer                | 13        | 10.08%  |
| ASUSTek Computer    | 9         | 6.98%   |
| Apple               | 7         | 5.43%   |
| Toshiba             | 5         | 3.88%   |
| TUXEDO              | 3         | 2.33%   |
| Samsung Electronics | 3         | 2.33%   |
| Sony                | 2         | 1.55%   |
| TWINHEAD            | 1         | 0.78%   |
| Razer               | 1         | 0.78%   |
| Panasonic           | 1         | 0.78%   |
| Packard Bell        | 1         | 0.78%   |
| Notebook            | 1         | 0.78%   |
| MSI                 | 1         | 0.78%   |
| LG Electronics      | 1         | 0.78%   |
| Itautec             | 1         | 0.78%   |
| HASEE Computer      | 1         | 0.78%   |
| Gateway             | 1         | 0.78%   |
| DNS                 | 1         | 0.78%   |
| Unknown             | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen1                                | 2         | 1.55%   |
| Dell Latitude E5470                                | 2         | 1.55%   |
| Apple MacBook4,1                                   | 2         | 1.55%   |
| Acer V5-131                                        | 2         | 1.55%   |
| TWINHEAD U12CT                                     | 1         | 0.78%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.78%   |
| Toshiba Satellite S55t-B                           | 1         | 0.78%   |
| Toshiba Satellite P300                             | 1         | 0.78%   |
| Toshiba Satellite L550                             | 1         | 0.78%   |
| Toshiba Satellite C640                             | 1         | 0.78%   |
| Toshiba Satellite C50-B                            | 1         | 0.78%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.78%   |
| Sony SVZ1311C5E                                    | 1         | 0.78%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.78%   |
| Samsung N100                                       | 1         | 0.78%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.78%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.78%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.78%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.78%   |
| Notebook N15_17RD                                  | 1         | 0.78%   |
| MSI GF65 Thin 10SER                                | 1         | 0.78%   |
| LG E300-A.CP20T                                    | 1         | 0.78%   |
| Lenovo Z50-70 20354                                | 1         | 0.78%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.78%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.78%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.78%   |
| Lenovo ThinkPad X220 Tablet 4298B65                | 1         | 0.78%   |
| Lenovo ThinkPad X220 Tablet 42962WU                | 1         | 0.78%   |
| Lenovo ThinkPad X220 4293B43                       | 1         | 0.78%   |
| Lenovo ThinkPad X220 4293AF4                       | 1         | 0.78%   |
| Lenovo ThinkPad X220 4291H77                       | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00           | 1         | 0.78%   |
| Lenovo ThinkPad T61 766301U                        | 1         | 0.78%   |
| Lenovo ThinkPad T60 1951FEG                        | 1         | 0.78%   |
| Lenovo ThinkPad T510 4384AJ6                       | 1         | 0.78%   |
| Lenovo ThinkPad T460 20FMS75800                    | 1         | 0.78%   |
| Lenovo ThinkPad T440p 20AWS3RH00                   | 1         | 0.78%   |
| Lenovo ThinkPad T440 20B7000PHV                    | 1         | 0.78%   |
| Lenovo ThinkPad T430 2349AK1                       | 1         | 0.78%   |
| Lenovo ThinkPad T420 4236BD5                       | 1         | 0.78%   |
| Lenovo ThinkPad T410 2537EA8                       | 1         | 0.78%   |
| Lenovo ThinkPad T410 2522E38                       | 1         | 0.78%   |
| Lenovo ThinkPad SL510 2847R96                      | 1         | 0.78%   |
| Lenovo ThinkPad R61 8935WCS                        | 1         | 0.78%   |
| Lenovo ThinkPad L450 20DSS1S402                    | 1         | 0.78%   |
| Lenovo ThinkPad L440 20ASS0FP00                    | 1         | 0.78%   |
| Lenovo ThinkPad E580 20KS005BRI                    | 1         | 0.78%   |
| Lenovo ThinkPad E15 20RD0011MX                     | 1         | 0.78%   |
| Lenovo ThinkBook 14 G2 ARE 20VF                    | 1         | 0.78%   |
| Lenovo Legion Y540-15IRH 81SX                      | 1         | 0.78%   |
| Lenovo IdeaPad Y700-17ISK 80Q0                     | 1         | 0.78%   |
| Lenovo IdeaPad N585                                | 1         | 0.78%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL              | 1         | 0.78%   |
| Lenovo IdeaPad 510-15IKB 80SV                      | 1         | 0.78%   |
| Lenovo IdeaPad 310-15ISK 80SM                      | 1         | 0.78%   |
| Lenovo IdeaPad 110S-11IBR 80WG                     | 1         | 0.78%   |
| Lenovo G51-35 80M8                                 | 1         | 0.78%   |
| Lenovo E31-80 80MX                                 | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 26        | 20.16%  |
| Dell Latitude           | 9         | 6.98%   |
| Acer Aspire             | 9         | 6.98%   |
| Lenovo IdeaPad          | 6         | 4.65%   |
| HP Pavilion             | 6         | 4.65%   |
| Toshiba Satellite       | 5         | 3.88%   |
| Dell Inspiron           | 5         | 3.88%   |
| HP Laptop               | 3         | 2.33%   |
| HP EliteBook            | 3         | 2.33%   |
| TUXEDO Aura             | 2         | 1.55%   |
| HP ProBook              | 2         | 1.55%   |
| Apple MacBook4          | 2         | 1.55%   |
| Acer V5-131             | 2         | 1.55%   |
| TWINHEAD U12CT          | 1         | 0.78%   |
| TUXEDO InfinityBook13V3 | 1         | 0.78%   |
| Sony VGN-NW25GF         | 1         | 0.78%   |
| Sony SVZ1311C5E         | 1         | 0.78%   |
| Samsung N150P           | 1         | 0.78%   |
| Samsung N100            | 1         | 0.78%   |
| Samsung 305E4A          | 1         | 0.78%   |
| Razer Blade             | 1         | 0.78%   |
| Panasonic CF-B11JWCYS   | 1         | 0.78%   |
| Packard Bell EasyNote   | 1         | 0.78%   |
| Notebook N15            | 1         | 0.78%   |
| MSI GF65                | 1         | 0.78%   |
| LG E300-A.CP20T         | 1         | 0.78%   |
| Lenovo Z50-70           | 1         | 0.78%   |
| Lenovo V310-14IKB       | 1         | 0.78%   |
| Lenovo ThinkBook        | 1         | 0.78%   |
| Lenovo Legion           | 1         | 0.78%   |
| Lenovo G51-35           | 1         | 0.78%   |
| Lenovo E31-80           | 1         | 0.78%   |
| Lenovo B470             | 1         | 0.78%   |
| Itautec Infoway         | 1         | 0.78%   |
| HP ZBook                | 1         | 0.78%   |
| HP Mini                 | 1         | 0.78%   |
| HP G62                  | 1         | 0.78%   |
| HP Compaq               | 1         | 0.78%   |
| HP 2000                 | 1         | 0.78%   |
| HP 15                   | 1         | 0.78%   |
| HASEE CW35S             | 1         | 0.78%   |
| Gateway NE56R           | 1         | 0.78%   |
| DNS W9x0LU              | 1         | 0.78%   |
| Dell Vostro             | 1         | 0.78%   |
| Dell Venue              | 1         | 0.78%   |
| ASUS X556UJ             | 1         | 0.78%   |
| ASUS X555LA             | 1         | 0.78%   |
| ASUS X540LA             | 1         | 0.78%   |
| ASUS S550CA             | 1         | 0.78%   |
| ASUS N56VB              | 1         | 0.78%   |
| ASUS K52Jc              | 1         | 0.78%   |
| ASUS K52F               | 1         | 0.78%   |
| ASUS F50SL              | 1         | 0.78%   |
| ASUS ASUS               | 1         | 0.78%   |
| Apple MacBookPro5       | 1         | 0.78%   |
| Apple MacBookAir5       | 1         | 0.78%   |
| Apple MacBookAir1       | 1         | 0.78%   |
| Apple MacBook6          | 1         | 0.78%   |
| Apple MacBook5          | 1         | 0.78%   |
| Acer TravelMate         | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2015    | 13        | 10.08%  |
| 2013    | 13        | 10.08%  |
| 2018    | 12        | 9.3%    |
| 2021    | 11        | 8.53%   |
| 2011    | 11        | 8.53%   |
| 2020    | 10        | 7.75%   |
| 2010    | 10        | 7.75%   |
| 2012    | 9         | 6.98%   |
| 2017    | 8         | 6.2%    |
| 2009    | 8         | 6.2%    |
| 2016    | 7         | 5.43%   |
| 2008    | 6         | 4.65%   |
| 2014    | 4         | 3.1%    |
| 2007    | 3         | 2.33%   |
| 2019    | 2         | 1.55%   |
| 2006    | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 129       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 39.53%  |
| 8.01-16.0   | 41        | 31.78%  |
| 16.01-24.0  | 22        | 17.05%  |
| 2.01-3.0    | 9         | 6.98%   |
| 32.01-64.0  | 2         | 1.55%   |
| 3.01-4.0    | 2         | 1.55%   |
| 24.01-32.0  | 1         | 0.78%   |
| 64.01-256.0 | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 84        | 65.12%  |
| 0.51-1.0 | 34        | 26.36%  |
| 1.01-2.0 | 7         | 5.43%   |
| 2.01-3.0 | 4         | 3.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 95        | 73.08%  |
| 2      | 27        | 20.77%  |
| 0      | 6         | 4.62%   |
| 3      | 2         | 1.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 55.04%  |
| Yes       | 58        | 44.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 120       | 93.02%  |
| No        | 9         | 6.98%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 66.67%  |
| No        | 43        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 21        | 16.28%  |
| Russia              | 11        | 8.53%   |
| Italy               | 9         | 6.98%   |
| Germany             | 8         | 6.2%    |
| UK                  | 7         | 5.43%   |
| Spain               | 6         | 4.65%   |
| Brazil              | 5         | 3.88%   |
| Ukraine             | 4         | 3.1%    |
| Romania             | 4         | 3.1%    |
| Netherlands         | 4         | 3.1%    |
| Mexico              | 4         | 3.1%    |
| Vietnam             | 3         | 2.33%   |
| Indonesia           | 3         | 2.33%   |
| France              | 3         | 2.33%   |
| China               | 3         | 2.33%   |
| Chile               | 3         | 2.33%   |
| Turkey              | 2         | 1.55%   |
| Portugal            | 2         | 1.55%   |
| Poland              | 2         | 1.55%   |
| Peru                | 2         | 1.55%   |
| Norway              | 2         | 1.55%   |
| Hungary             | 2         | 1.55%   |
| Greece              | 2         | 1.55%   |
| Denmark             | 2         | 1.55%   |
| Trinidad and Tobago | 1         | 0.78%   |
| Tanzania            | 1         | 0.78%   |
| Sweden              | 1         | 0.78%   |
| New Zealand         | 1         | 0.78%   |
| Malaysia            | 1         | 0.78%   |
| Lithuania           | 1         | 0.78%   |
| India               | 1         | 0.78%   |
| Georgia             | 1         | 0.78%   |
| Czechia             | 1         | 0.78%   |
| Cuba                | 1         | 0.78%   |
| Colombia            | 1         | 0.78%   |
| Bulgaria            | 1         | 0.78%   |
| Belarus             | 1         | 0.78%   |
| Austria             | 1         | 0.78%   |
| Argentina           | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 4         | 3.08%   |
| Hanoi                         | 3         | 2.31%   |
| Warsaw                        | 2         | 1.54%   |
| Lima                          | 2         | 1.54%   |
| Leatherhead                   | 2         | 1.54%   |
| Jakarta                       | 2         | 1.54%   |
| Dijon                         | 2         | 1.54%   |
| Amsterdam                     | 2         | 1.54%   |
| Zhaoqing                      | 1         | 0.77%   |
| Zaporizhzhya                  | 1         | 0.77%   |
| Zapopan                       | 1         | 0.77%   |
| Youngsville                   | 1         | 0.77%   |
| Yaphank                       | 1         | 0.77%   |
| Washington                    | 1         | 0.77%   |
| Vilnius                       | 1         | 0.77%   |
| VÃ¤sterÃ¥s                | 1         | 0.77%   |
| Vandalia                      | 1         | 0.77%   |
| Ugarchin                      | 1         | 0.77%   |
| Turley                        | 1         | 0.77%   |
| Turin                         | 1         | 0.77%   |
| Tromsø                       | 1         | 0.77%   |
| Torokszentmiklos              | 1         | 0.77%   |
| Tolyatti                      | 1         | 0.77%   |
| Tiruchi                       | 1         | 0.77%   |
| Thessaloniki                  | 1         | 0.77%   |
| Susanville                    | 1         | 0.77%   |
| Suceava                       | 1         | 0.77%   |
| St Petersburg                 | 1         | 0.77%   |
| Shah Alam                     | 1         | 0.77%   |
| Sevastopol                    | 1         | 0.77%   |
| Seattle                       | 1         | 0.77%   |
| Santiago                      | 1         | 0.77%   |
| San SebastiÃ¡n de los Reyes | 1         | 0.77%   |
| San Luis PotosÃ­ City       | 1         | 0.77%   |
| San Antonio                   | 1         | 0.77%   |
| Riverton                      | 1         | 0.77%   |
| Rio de Janeiro                | 1         | 0.77%   |
| Rho                           | 1         | 0.77%   |
| Ransbach-Baumbach             | 1         | 0.77%   |
| Pudong                        | 1         | 0.77%   |
| Pruszcz Gdanski               | 1         | 0.77%   |
| Potsdam                       | 1         | 0.77%   |
| Portland                      | 1         | 0.77%   |
| Port of Spain                 | 1         | 0.77%   |
| Piovene Rocchette             | 1         | 0.77%   |
| Pflugerville                  | 1         | 0.77%   |
| Patterson                     | 1         | 0.77%   |
| Passignano sul Trasimeno      | 1         | 0.77%   |
| Paracuru                      | 1         | 0.77%   |
| Orlando                       | 1         | 0.77%   |
| Oldenburg                     | 1         | 0.77%   |
| Odense                        | 1         | 0.77%   |
| Novosibirsk                   | 1         | 0.77%   |
| Nesttun                       | 1         | 0.77%   |
| Mt. Pleasant                  | 1         | 0.77%   |
| Monterrey                     | 1         | 0.77%   |
| Minsk                         | 1         | 0.77%   |
| Minneapolis                   | 1         | 0.77%   |
| Milan                         | 1         | 0.77%   |
| Mendoza                       | 1         | 0.77%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 32        | 33     | 20.92%  |
| Samsung Electronics | 21        | 23     | 13.73%  |
| Toshiba             | 13        | 13     | 8.5%    |
| Seagate             | 12        | 15     | 7.84%   |
| Kingston            | 12        | 13     | 7.84%   |
| Crucial             | 10        | 10     | 6.54%   |
| SanDisk             | 6         | 7      | 3.92%   |
| Intel               | 6         | 7      | 3.92%   |
| Hitachi             | 5         | 5      | 3.27%   |
| HGST                | 5         | 5      | 3.27%   |
| Micron Technology   | 3         | 3      | 1.96%   |
| A-DATA Technology   | 3         | 3      | 1.96%   |
| SPCC                | 2         | 3      | 1.31%   |
| SK Hynix            | 2         | 2      | 1.31%   |
| Patriot             | 2         | 2      | 1.31%   |
| Intenso             | 2         | 2      | 1.31%   |
| Fujitsu             | 2         | 2      | 1.31%   |
| Zheino              | 1         | 1      | 0.65%   |
| Transcend           | 1         | 1      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| Mushkin             | 1         | 1      | 0.65%   |
| LITEON              | 1         | 1      | 0.65%   |
| KIOXIA              | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| Integral            | 1         | 1      | 0.65%   |
| INDMEM              | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| Corsair             | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |
| Apacer              | 1         | 1      | 0.65%   |
| AGI                 | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS120G2G0A-00JH30 120GB         | 4         | 2.55%   |
| Toshiba MQ01ABF050 500GB             | 4         | 2.55%   |
| HGST HTS545050A7E680 500GB           | 4         | 2.55%   |
| Kingston SA400S37240G 240GB          | 3         | 1.91%   |
| Kingston SA400S37120G 120GB          | 3         | 1.91%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.91%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.91%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.27%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.27%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 1.27%   |
| SK Hynix HFS256G39TND-N210A 256GB    | 2         | 1.27%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.27%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.27%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 2         | 1.27%   |
| Zheino CHN mSATAM1 256 256GB         | 1         | 0.64%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.64%   |
| WDC WDS240G1G0A-00SS50 240GB         | 1         | 0.64%   |
| WDC WDBNCE5000PNC 500GB              | 1         | 0.64%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.64%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.64%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.64%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.64%   |
| WDC WD5000BPKX-22HPJT0 500GB         | 1         | 0.64%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.64%   |
| WDC WD3200BEKX-60B7WT0 320GB         | 1         | 0.64%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.64%   |
| WDC WD1600BEVT-80A23T0 160GB         | 1         | 0.64%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.64%   |
| WDC WD1600BEKT-66F3T2 160GB          | 1         | 0.64%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 0.64%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 0.64%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.64%   |
| WDC WD10SDZW-11UMGS0 1TB             | 1         | 0.64%   |
| WDC WD10JMVW-11AJGS4 1TB             | 1         | 0.64%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 0.64%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.64%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.64%   |
| Transcend TS240GMTS420S 240GB        | 1         | 0.64%   |
| Toshiba THNSNX024GMNT 24GB           | 1         | 0.64%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.64%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.64%   |
| Toshiba MK8034GSX 80GB               | 1         | 0.64%   |
| Toshiba MK7559GSXF 752GB             | 1         | 0.64%   |
| Toshiba MK3265GSXN 320GB             | 1         | 0.64%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.64%   |
| Toshiba MK2561GSYN 250GB             | 1         | 0.64%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.64%   |
| Team TEAML5Lite3D120G 120GB          | 1         | 0.64%   |
| SPCC Solid State Disk 512GB          | 1         | 0.64%   |
| SPCC Solid State Disk 256GB          | 1         | 0.64%   |
| Seagate ST980813AS 80GB              | 1         | 0.64%   |
| Seagate ST9640320AS 640GB            | 1         | 0.64%   |
| Seagate ST9500325AS 500GB            | 1         | 0.64%   |
| Seagate ST9320423AS 320GB            | 1         | 0.64%   |
| Seagate ST9320325AS 320GB            | 1         | 0.64%   |
| Seagate ST9320320AS 320GB            | 1         | 0.64%   |
| Seagate ST9160411AS 160GB            | 1         | 0.64%   |
| Seagate ST500LM030-1RK17D 500GB      | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 21     | 35.71%  |
| Seagate             | 12        | 15     | 21.43%  |
| Toshiba             | 11        | 11     | 19.64%  |
| Hitachi             | 5         | 5      | 8.93%   |
| HGST                | 5         | 5      | 8.93%   |
| Samsung Electronics | 2         | 2      | 3.57%   |
| Fujitsu             | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 14.67%  |
| Kingston            | 10        | 10     | 13.33%  |
| Crucial             | 10        | 10     | 13.33%  |
| WDC                 | 8         | 8      | 10.67%  |
| SanDisk             | 6         | 7      | 8%      |
| Intel               | 4         | 4      | 5.33%   |
| SPCC                | 2         | 3      | 2.67%   |
| SK Hynix            | 2         | 2      | 2.67%   |
| Patriot             | 2         | 2      | 2.67%   |
| Intenso             | 2         | 2      | 2.67%   |
| A-DATA Technology   | 2         | 2      | 2.67%   |
| Zheino              | 1         | 1      | 1.33%   |
| Transcend           | 1         | 1      | 1.33%   |
| Toshiba             | 1         | 1      | 1.33%   |
| Team                | 1         | 1      | 1.33%   |
| Netac               | 1         | 1      | 1.33%   |
| Mushkin             | 1         | 1      | 1.33%   |
| Micron Technology   | 1         | 1      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |
| KingSpec            | 1         | 1      | 1.33%   |
| Integral            | 1         | 1      | 1.33%   |
| INDMEM              | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |
| Fujitsu             | 1         | 1      | 1.33%   |
| Corsair             | 1         | 1      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |
| Apacer              | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 66        | 78     | 47.14%  |
| HDD  | 52        | 60     | 37.14%  |
| NVMe | 22        | 25     | 15.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 138    | 83.58%  |
| NVMe | 22        | 25     | 16.42%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 117    | 82.91%  |
| 0.51-1.0   | 18        | 19     | 15.38%  |
| 1.01-2.0   | 1         | 1      | 0.85%   |
| 4.01-10.0  | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 69        | 53.08%  |
| 251-500    | 23        | 17.69%  |
| 101-250    | 23        | 17.69%  |
| 21-50      | 6         | 4.62%   |
| 501-1000   | 6         | 4.62%   |
| 51-100     | 3         | 2.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 127       | 98.45%  |
| 21-50   | 1         | 0.78%   |
| 101-250 | 1         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 3.13%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 3.13%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 3.13%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 3.13%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 3.13%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 3.13%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 3.13%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 3.13%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 3.13%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 3.13%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 3.13%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 3.13%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 3.13%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 3.13%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 3.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 3.13%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 3.13%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 3.13%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 3.13%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 3.13%   |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 3.13%   |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 3.13%   |
| Hitachi HTS542516K9SA00 160GB      | 1         | 1      | 3.13%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 3.13%   |
| HGST HTS541075A7E630 752GB         | 1         | 1      | 3.13%   |
| AGI AGI512G16AI198 512GB           | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 8      | 25%     |
| WDC                 | 7         | 7      | 21.88%  |
| Seagate             | 6         | 6      | 18.75%  |
| Hitachi             | 4         | 4      | 12.5%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| HGST                | 2         | 2      | 6.25%   |
| LITEON              | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |
| AGI                 | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 25%     |
| Toshiba             | 7         | 7      | 25%     |
| Seagate             | 6         | 6      | 21.43%  |
| Hitachi             | 4         | 4      | 14.29%  |
| Samsung Electronics | 2         | 2      | 7.14%   |
| HGST                | 2         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 28     | 87.1%   |
| SSD  | 3         | 3      | 9.68%   |
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
| Works    | 97        | 130    | 75.19%  |
| Malfunc  | 31        | 32     | 24.03%  |
| Detected | 1         | 1      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 72.03%  |
| AMD                              | 15        | 10.49%  |
| Samsung Electronics              | 9         | 6.29%   |
| Sandisk                          | 4         | 2.8%    |
| Nvidia                           | 3         | 2.1%    |
| Micron Technology                | 2         | 1.4%    |
| KIOXIA                           | 2         | 1.4%    |
| Kingston Technology Company      | 2         | 1.4%    |
| Silicon Motion                   | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| ADATA Technology                 | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 9.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 8.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 7.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 6.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 5.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 4.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 4.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 3.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 2.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 2.58%   |
| Unknown                                                                          | 4         | 2.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.94%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.29%   |
| KIOXIA unknown                                                                   | 2         | 1.29%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.65%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.65%   |
| Sandisk unknown                                                                  | 1         | 0.65%   |
| Sandisk PC SN530                                                                 | 1         | 0.65%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.65%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.65%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.65%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.65%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.65%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.65%   |
| AMD SB600 IDE                                                                    | 1         | 0.65%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 74.17%  |
| NVMe | 22        | 14.57%  |
| IDE  | 12        | 7.95%   |
| RAID | 5         | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 111       | 86.05%  |
| AMD    | 18        | 13.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 7         | 5.43%   |
| Intel CPU Version                           | 3         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 2.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 2.33%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 3         | 2.33%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.55%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.55%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 1.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.55%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.55%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.55%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 2         | 1.55%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 2         | 1.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.55%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.55%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.55%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.55%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 1.55%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.78%   |
| Intel Pentium CPU P6200 @ 2.13GH            | 1         | 0.78%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.78%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.78%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.78%   |
| Intel Core M-5Y71 CPU @ 1.20GHz             | 1         | 0.78%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.78%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.78%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.78%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.78%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 0.78%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.78%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 0.78%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 0.78%   |
| Intel Core i5 CPU U 560 @ 1.33GHz           | 1         | 0.78%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GH            | 1         | 0.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 0.78%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 0.78%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 0.78%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 0.78%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 33.33%  |
| Intel Core i7           | 16        | 12.4%   |
| Intel Core 2 Duo        | 15        | 11.63%  |
| Intel Core i3           | 13        | 10.08%  |
| Intel Celeron           | 10        | 7.75%   |
| Intel Pentium           | 5         | 3.88%   |
| AMD Ryzen 5             | 5         | 3.88%   |
| AMD A6                  | 4         | 3.1%    |
| Other                   | 3         | 2.33%   |
| Intel Atom              | 3         | 2.33%   |
| AMD Ryzen 7             | 2         | 1.55%   |
| AMD E2                  | 2         | 1.55%   |
| AMD E1                  | 2         | 1.55%   |
| Intel Pentium Dual-Core | 1         | 0.78%   |
| Intel Core M            | 1         | 0.78%   |
| Intel Core 2            | 1         | 0.78%   |
| AMD Ryzen 3             | 1         | 0.78%   |
| AMD A8                  | 1         | 0.78%   |
| AMD A10                 | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 57.36%  |
| 4       | 27        | 20.93%  |
| Unknown | 18        | 13.95%  |
| 8       | 4         | 3.1%    |
| 6       | 3         | 2.33%   |
| 12      | 2         | 1.55%   |
| 1       | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 121       | 93.8%   |
| 2       | 6         | 4.65%   |
| Unknown | 2         | 1.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 72        | 55.81%  |
| 1       | 39        | 30.23%  |
| Unknown | 18        | 13.95%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 15        | 11.63%  |
| Penryn      | 14        | 10.85%  |
| KabyLake    | 13        | 10.08%  |
| Haswell     | 12        | 9.3%    |
| Westmere    | 11        | 8.53%   |
| SandyBridge | 11        | 8.53%   |
| Skylake     | 10        | 7.75%   |
| Silvermont  | 7         | 5.43%   |
| Core        | 6         | 4.65%   |
| Zen 2       | 4         | 3.1%    |
| Broadwell   | 4         | 3.1%    |
| CometLake   | 3         | 2.33%   |
| Bonnell     | 3         | 2.33%   |
| Bobcat      | 3         | 2.33%   |
| Zen+        | 2         | 1.55%   |
| Jaguar      | 2         | 1.55%   |
| Goldmont    | 2         | 1.55%   |
| Excavator   | 2         | 1.55%   |
| Zen 3       | 1         | 0.78%   |
| Zen         | 1         | 0.78%   |
| Puma        | 1         | 0.78%   |
| Piledriver  | 1         | 0.78%   |
| K10 Llano   | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 95        | 62.5%   |
| AMD    | 31        | 20.39%  |
| Nvidia | 26        | 17.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 9.43%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 6.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 5.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 5.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 3.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 3.77%   |
| Intel HD Graphics 620                                                                    | 5         | 3.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.52%   |
| AMD Renoir                                                                               | 4         | 2.52%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.89%   |
| Intel HD Graphics 530                                                                    | 3         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.89%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.89%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 1.89%   |
| Nvidia TU117M                                                                            | 2         | 1.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.26%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.26%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.26%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.26%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.26%   |
| Intel HD Graphics 500                                                                    | 2         | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.26%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 1.26%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.63%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.63%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.63%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.63%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.63%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.63%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.63%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.63%   |
| Nvidia G86M [Quadro NVS 135M]                                                            | 1         | 0.63%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 0.63%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.63%   |
| Intel HD Graphics 630                                                                    | 1         | 0.63%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.63%   |
| Intel HD Graphics 520                                                                    | 1         | 0.63%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.63%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.63%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.63%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.63%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.63%   |
| AMD RS600M [Radeon Xpress 1250]                                                          | 1         | 0.63%   |
| AMD Richland [Radeon HD 8650G]                                                           | 1         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.63%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 48.06%  |
| 1 x AMD        | 23        | 17.83%  |
| Intel + Nvidia | 15        | 11.63%  |
| 2 x Intel      | 12        | 9.3%    |
| 1 x Nvidia     | 9         | 6.98%   |
| Intel + AMD    | 6         | 4.65%   |
| AMD + Nvidia   | 2         | 1.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 116       | 89.92%  |
| Proprietary | 10        | 7.75%   |
| Unknown     | 3         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 77.52%  |
| 0.01-0.5   | 19        | 14.73%  |
| 0.51-1.0   | 6         | 4.65%   |
| 1.01-2.0   | 2         | 1.55%   |
| 5.01-6.0   | 1         | 0.78%   |
| 3.01-4.0   | 1         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 27        | 20.45%  |
| AU Optronics            | 23        | 17.42%  |
| Chimei Innolux          | 19        | 14.39%  |
| Samsung Electronics     | 17        | 12.88%  |
| BOE                     | 14        | 10.61%  |
| Lenovo                  | 13        | 9.85%   |
| Apple                   | 7         | 5.3%    |
| Chi Mei Optoelectronics | 2         | 1.52%   |
| Vestel Elektronik       | 1         | 0.76%   |
| Toshiba                 | 1         | 0.76%   |
| Sony                    | 1         | 0.76%   |
| SLD                     | 1         | 0.76%   |
| Philips                 | 1         | 0.76%   |
| Lenovo Group Limited    | 1         | 0.76%   |
| LED                     | 1         | 0.76%   |
| BenQ                    | 1         | 0.76%   |
| Ancor Communications    | 1         | 0.76%   |
| Acer                    | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 2         | 1.48%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 1.48%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 2         | 1.48%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 1.48%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch                | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch        | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 1.48%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 530x300mm 24.0-inch     | 1         | 0.74%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.74%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                          | 1         | 0.74%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                   | 1         | 0.74%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1         | 0.74%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1         | 0.74%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD03DF 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0324 1280x800 220x140mm 10.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD029B 1366x768 310x170mm 13.9-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0222 1366x768 340x190mm 15.3-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD01CA 1600x900 380x210mm 17.1-inch            | 1         | 0.74%   |
| Lenovo LEN T24i-20 LEN61F7 1920x1080 530x300mm 24.0-inch               | 1         | 0.74%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 600x340mm 27.2-inch               | 1         | 0.74%   |
| Lenovo LEN L193pC LEN114F 1280x1024 400x320mm 20.2-inch                | 1         | 0.74%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.74%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                | 1         | 0.74%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                | 1         | 0.74%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 63        | 48.84%  |
| 1920x1080 (FHD)   | 34        | 26.36%  |
| 1280x800 (WXGA)   | 14        | 10.85%  |
| 1600x900 (HD+)    | 5         | 3.88%   |
| 3840x2160 (4K)    | 2         | 1.55%   |
| 2560x1440 (QHD)   | 2         | 1.55%   |
| 1920x540          | 2         | 1.55%   |
| 1440x900 (WXGA+)  | 2         | 1.55%   |
| 1024x600          | 2         | 1.55%   |
| 1920x1200 (WUXGA) | 1         | 0.78%   |
| 1280x1024 (SXGA)  | 1         | 0.78%   |
| 1024x768 (XGA)    | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 49        | 36.3%   |
| 13      | 35        | 25.93%  |
| 12      | 12        | 8.89%   |
| 14      | 7         | 5.19%   |
| 17      | 6         | 4.44%   |
| 11      | 5         | 3.7%    |
| 27      | 3         | 2.22%   |
| 24      | 3         | 2.22%   |
| 23      | 3         | 2.22%   |
| 10      | 3         | 2.22%   |
| 64      | 1         | 0.74%   |
| 54      | 1         | 0.74%   |
| 42      | 1         | 0.74%   |
| 40      | 1         | 0.74%   |
| 31      | 1         | 0.74%   |
| 20      | 1         | 0.74%   |
| 18      | 1         | 0.74%   |
| 16      | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 53.33%  |
| 201-300     | 39        | 28.89%  |
| 501-600     | 9         | 6.67%   |
| 351-400     | 8         | 5.93%   |
| 1001-1500   | 2         | 1.48%   |
| 801-900     | 1         | 0.74%   |
| 601-700     | 1         | 0.74%   |
| 401-500     | 1         | 0.74%   |
| 901-1000    | 1         | 0.74%   |
| Unknown     | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 82.93%  |
| 16/10   | 15        | 12.2%   |
| 3/2     | 3         | 2.44%   |
| 5/4     | 1         | 0.81%   |
| 4/3     | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 40        | 29.63%  |
| 81-90          | 35        | 25.93%  |
| 61-70          | 12        | 8.89%   |
| 101-110        | 10        | 7.41%   |
| 71-80          | 6         | 4.44%   |
| 51-60          | 5         | 3.7%    |
| 201-250        | 5         | 3.7%    |
| 121-130        | 4         | 2.96%   |
| 41-50          | 3         | 2.22%   |
| 301-350        | 3         | 2.22%   |
| More than 1000 | 2         | 1.48%   |
| 131-140        | 2         | 1.48%   |
| 501-1000       | 2         | 1.48%   |
| 351-500        | 1         | 0.74%   |
| 251-300        | 1         | 0.74%   |
| 151-200        | 1         | 0.74%   |
| 141-150        | 1         | 0.74%   |
| 111-120        | 1         | 0.74%   |
| Unknown        | 1         | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 54        | 40.91%  |
| 121-160 | 52        | 39.39%  |
| 51-100  | 22        | 16.67%  |
| 161-240 | 3         | 2.27%   |
| Unknown | 1         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 111       | 85.38%  |
| 2     | 14        | 10.77%  |
| 0     | 5         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 29.86%  |
| Realtek Semiconductor             | 64        | 28.96%  |
| Qualcomm Atheros                  | 34        | 15.38%  |
| Broadcom                          | 24        | 10.86%  |
| Marvell Technology Group          | 7         | 3.17%   |
| Ralink                            | 3         | 1.36%   |
| Nvidia                            | 3         | 1.36%   |
| JMicron Technology                | 3         | 1.36%   |
| NetGear                           | 2         | 0.9%    |
| Ericsson Business Mobile Networks | 2         | 0.9%    |
| Edimax Technology                 | 2         | 0.9%    |
| Dell                              | 2         | 0.9%    |
| TP-Link                           | 1         | 0.45%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.45%   |
| Sierra Wireless                   | 1         | 0.45%   |
| OPPO Electronics                  | 1         | 0.45%   |
| Mercucys                          | 1         | 0.45%   |
| Huawei Technologies               | 1         | 0.45%   |
| Hewlett-Packard                   | 1         | 0.45%   |
| Google                            | 1         | 0.45%   |
| D-Link System                     | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 43        | 15.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 5.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 4.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.56%   |
| Intel Wireless 8260                                                     | 7         | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.83%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.83%   |
| Intel Wireless 7265                                                     | 4         | 1.47%   |
| Intel Wireless 7260                                                     | 4         | 1.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.47%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.1%    |
| Nvidia MCP79 Ethernet                                                   | 3         | 1.1%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 1.1%    |
| Intel Wireless 8265 / 8275                                              | 3         | 1.1%    |
| Intel WiFi Link 5100                                                    | 3         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.1%    |
| Intel Ethernet Connection I219-LM                                       | 3         | 1.1%    |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.1%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.1%    |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.1%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.73%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.73%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.73%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.73%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 2         | 0.73%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.73%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.73%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.73%   |
| Intel 82566MM Gigabit Network Connection                                | 2         | 0.73%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 0.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.73%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.37%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.37%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.37%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.37%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.37%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 45.77%  |
| Qualcomm Atheros      | 33        | 23.24%  |
| Realtek Semiconductor | 18        | 12.68%  |
| Broadcom              | 15        | 10.56%  |
| Ralink                | 3         | 2.11%   |
| NetGear               | 2         | 1.41%   |
| Edimax Technology     | 2         | 1.41%   |
| TP-Link               | 1         | 0.7%    |
| Sierra Wireless       | 1         | 0.7%    |
| Mercucys              | 1         | 0.7%    |
| Dell                  | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 6.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 6.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 4.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 4.79%   |
| Intel Wireless 8260                                                     | 7         | 4.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.42%   |
| Intel Wireless 7265                                                     | 4         | 2.74%   |
| Intel Wireless 7260                                                     | 4         | 2.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 2.74%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 2.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.05%   |
| Intel Wireless 8265 / 8275                                              | 3         | 2.05%   |
| Intel WiFi Link 5100                                                    | 3         | 2.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 2.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.05%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 2.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.05%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.37%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.37%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.37%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.37%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.68%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.68%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.68%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.68%   |
| Mercucys MERCUSYS Wireless USB Adapter                                  | 1         | 0.68%   |
| Intel Wireless 3160                                                     | 1         | 0.68%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.68%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.68%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.68%   |
| Edimax Edimax AC600 Wireless LAN USB Adapter                            | 1         | 0.68%   |
| Dell Hub of E-Port Replicator                                           | 1         | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.68%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.68%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 58        | 47.93%  |
| Intel                            | 33        | 27.27%  |
| Broadcom                         | 9         | 7.44%   |
| Marvell Technology Group         | 7         | 5.79%   |
| Qualcomm Atheros                 | 5         | 4.13%   |
| Nvidia                           | 3         | 2.48%   |
| JMicron Technology               | 3         | 2.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| OPPO Electronics                 | 1         | 0.83%   |
| Google                           | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 35.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 12.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 9.09%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 3.31%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 2.48%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.48%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 2.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.65%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.65%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 1.65%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.83%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.83%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 0.83%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.83%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.83%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.83%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.83%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.83%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.83%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.83%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.83%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.83%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 50.59%  |
| Ethernet | 120       | 47.06%  |
| Modem    | 3         | 1.18%   |
| Unknown  | 3         | 1.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 52.79%  |
| WiFi     | 89        | 45.18%  |
| Unknown  | 3         | 1.52%   |
| Modem    | 1         | 0.51%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 118       | 91.47%  |
| 1     | 10        | 7.75%   |
| 0     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 122       | 94.57%  |
| Yes  | 7         | 5.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 38.37%  |
| Broadcom                        | 10        | 11.63%  |
| Qualcomm Atheros Communications | 9         | 10.47%  |
| Realtek Semiconductor           | 7         | 8.14%   |
| Apple                           | 7         | 8.14%   |
| Lite-On Technology              | 5         | 5.81%   |
| Ralink                          | 3         | 3.49%   |
| Hewlett-Packard                 | 3         | 3.49%   |
| Foxconn / Hon Hai               | 3         | 3.49%   |
| IMC Networks                    | 2         | 2.33%   |
| Dell                            | 2         | 2.33%   |
| Cambridge Silicon Radio         | 2         | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 23.86%  |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 5         | 5.68%   |
| Intel AX200 Bluetooth                                       | 5         | 5.68%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 5         | 5.68%   |
| Ralink RT3290 Bluetooth                                     | 3         | 3.41%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 3.41%   |
| Intel AX201 Bluetooth                                       | 3         | 3.41%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 3.41%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.27%   |
| Realtek Bluetooth Radio                                     | 2         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 2.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 2.27%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 2         | 2.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 2.27%   |
| Apple Bluetooth Host Controller                             | 2         | 2.27%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.14%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.14%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.14%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 1.14%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.14%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 1.14%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.14%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.14%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.14%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.14%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.14%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.14%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 1.14%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device      | 1         | 1.14%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.14%   |
| Apple Broadcom Bluetooth 2.1 module                         | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 106       | 72.6%   |
| AMD                              | 24        | 16.44%  |
| Nvidia                           | 11        | 7.53%   |
| GN Netcom                        | 2         | 1.37%   |
| Texas Instruments                | 1         | 0.68%   |
| Silicon Integrated Systems [SiS] | 1         | 0.68%   |
| Creative Technology              | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 8.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 8.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 4.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 4.47%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 4.47%   |
| AMD FCH Azalia Controller                                                                         | 8         | 4.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 4.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.23%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 2.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.23%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 2.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.68%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.12%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.12%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.56%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.56%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.56%   |
| Creative Technology SB X-Fi Surround 5.1                                                          | 1         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.56%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.56%   |
| AMD RS600 HDMI Audio [Radeon Xpress 1250]                                                         | 1         | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.56%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 29.49%  |
| Kingston            | 23        | 14.74%  |
| SK Hynix            | 21        | 13.46%  |
| Unknown             | 11        | 7.05%   |
| Micron Technology   | 11        | 7.05%   |
| Ramaxel Technology  | 6         | 3.85%   |
| Nanya Technology    | 6         | 3.85%   |
| Crucial             | 6         | 3.85%   |
| Elpida              | 4         | 2.56%   |
| Unknown             | 4         | 2.56%   |
| Smart               | 3         | 1.92%   |
| A-DATA Technology   | 3         | 1.92%   |
| Silicon Power       | 2         | 1.28%   |
| 48spaces            | 2         | 1.28%   |
| Unknown (ABCD)      | 1         | 0.64%   |
| Transcend           | 1         | 0.64%   |
| Sesame              | 1         | 0.64%   |
| Kingmax             | 1         | 0.64%   |
| High Bridge         | 1         | 0.64%   |
| Corsair             | 1         | 0.64%   |
| ASint Technology    | 1         | 0.64%   |
| Apacer              | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 5         | 2.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 2.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 2.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 2.4%    |
| Unknown                                                                   | 4         | 2.4%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 3         | 1.8%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 1.8%    |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 1.2%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 1.2%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.2%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 2         | 1.2%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 1.2%    |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 1.2%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.2%    |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 1.2%    |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 1.2%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s          | 1         | 0.6%    |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.6%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.6%    |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.6%    |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.6%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1333MT/s                              | 1         | 0.6%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 0.6%    |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.6%    |
| SK Hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.6%    |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 1         | 0.6%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.6%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.6%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.6%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.6%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 1         | 0.6%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.6%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 0.6%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.6%    |
| SK Hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s          | 1         | 0.6%    |
| Silicon Power RAM SP008GBSFU240B02 8GB SODIMM DDR4 2400MT/s               | 1         | 0.6%    |
| Silicon Power RAM SP004GLSTU160N02 4GB SODIMM DDR3 1600MT/s               | 1         | 0.6%    |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.6%    |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                               | 1         | 0.6%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 0.6%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5273DH0-YH9 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.6%    |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 75        | 59.06%  |
| DDR4    | 30        | 23.62%  |
| DDR2    | 16        | 12.6%   |
| LPDDR3  | 2         | 1.57%   |
| SDRAM   | 1         | 0.79%   |
| LPDDR4  | 1         | 0.79%   |
| DRAM    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 125       | 98.43%  |
| Row Of Chips | 1         | 0.79%   |
| DIMM         | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 54        | 37.76%  |
| 2048  | 38        | 26.57%  |
| 8192  | 35        | 24.48%  |
| 16384 | 9         | 6.29%   |
| 1024  | 5         | 3.5%    |
| 32768 | 2         | 1.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 32.39%  |
| 1333    | 16        | 11.27%  |
| 2667    | 13        | 9.15%   |
| 1334    | 13        | 9.15%   |
| 667     | 13        | 9.15%   |
| 3200    | 8         | 5.63%   |
| 1067    | 7         | 4.93%   |
| 2400    | 6         | 4.23%   |
| 2133    | 6         | 4.23%   |
| 800     | 5         | 3.52%   |
| Unknown | 5         | 3.52%   |
| 1867    | 3         | 2.11%   |
| 1066    | 1         | 0.7%    |

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
| Chicony Electronics                    | 30        | 31.58%  |
| Realtek Semiconductor                  | 9         | 9.47%   |
| Quanta                                 | 7         | 7.37%   |
| Microdia                               | 7         | 7.37%   |
| IMC Networks                           | 7         | 7.37%   |
| Acer                                   | 6         | 6.32%   |
| Lite-On Technology                     | 5         | 5.26%   |
| Sunplus Innovation Technology          | 4         | 4.21%   |
| Syntek                                 | 3         | 3.16%   |
| Alcor Micro                            | 3         | 3.16%   |
| Z-Star Microelectronics                | 2         | 2.11%   |
| Suyin                                  | 2         | 2.11%   |
| Lenovo                                 | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.11%   |
| Silicon Motion                         | 1         | 1.05%   |
| Ricoh                                  | 1         | 1.05%   |
| Primax Electronics                     | 1         | 1.05%   |
| Luxvisions Innotech Limited            | 1         | 1.05%   |
| Importek                               | 1         | 1.05%   |
| Apple                                  | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 5.21%   |
| Chicony HD WebCam                                   | 4         | 4.17%   |
| Realtek USB Camera                                  | 3         | 3.13%   |
| Lite-On Integrated Camera                           | 3         | 3.13%   |
| Chicony EasyCamera                                  | 3         | 3.13%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.08%   |
| Realtek Realtek USB2.0 PC Camera                    | 2         | 2.08%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.08%   |
| Quanta HP Webcam                                    | 2         | 2.08%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.08%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 2.08%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.08%   |
| Microdia Dell Laptop Integrated Webcam HD           | 2         | 2.08%   |
| IMC Networks Integrated Camera                      | 2         | 2.08%   |
| Chicony Integrated Camera                           | 2         | 2.08%   |
| Chicony HD WebCam (Acer)                            | 2         | 2.08%   |
| Chicony Chicony USB 2.0 Camera                      | 2         | 2.08%   |
| Acer Lenovo EasyCamera                              | 2         | 2.08%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 1.04%   |
| Z-Star Webcam                                       | 1         | 1.04%   |
| Syntek EasyCamera                                   | 1         | 1.04%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.04%   |
| Suyin HD Video WebCam                               | 1         | 1.04%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.04%   |
| Sunplus Integrated Camera                           | 1         | 1.04%   |
| Sunplus HP Universal Camera                         | 1         | 1.04%   |
| Sunplus HD WebCam                                   | 1         | 1.04%   |
| Silicon Motion HP Webcam-50                         | 1         | 1.04%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.04%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 1.04%   |
| Realtek Integrated_Webcam_8M                        | 1         | 1.04%   |
| Realtek HD WebCam                                   | 1         | 1.04%   |
| Quanta VGA WebCam                                   | 1         | 1.04%   |
| Quanta Realtek DMFT - RGB                           | 1         | 1.04%   |
| Quanta HD WebCam                                    | 1         | 1.04%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 1.04%   |
| Microdia Integrated Webcam                          | 1         | 1.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.04%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.04%   |
| Lite-On HP HD Camera                                | 1         | 1.04%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.04%   |
| Lenovo Integrated Webcam                            | 1         | 1.04%   |
| Importek TOSHIBA Web Camera                         | 1         | 1.04%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.04%   |
| IMC Networks USB Camera                             | 1         | 1.04%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.04%   |
| IMC Networks Integrated Webcam                      | 1         | 1.04%   |
| IMC Networks EasyCamera                             | 1         | 1.04%   |
| Chicony Webcam-101                                  | 1         | 1.04%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 1.04%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.04%   |
| Chicony USB 2.0 VGA UVC WebCam                      | 1         | 1.04%   |
| Chicony USB 2.0 Camera                              | 1         | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.04%   |
| Chicony thinkpad t430s camera                       | 1         | 1.04%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.04%   |
| Chicony HP Webcam                                   | 1         | 1.04%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 1.04%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 1         | 1.04%   |
| Chicony 1.3M Webcam                                 | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 32.14%  |
| Upek                       | 8         | 28.57%  |
| AuthenTec                  | 4         | 14.29%  |
| STMicroelectronics         | 3         | 10.71%  |
| LighTuning Technology      | 2         | 7.14%   |
| Synaptics                  | 1         | 3.57%   |
| Shenzhen Goodix Technology | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 7         | 25%     |
| STMicroelectronics Fingerprint Reader                  | 3         | 10.71%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 7.14%   |
| Validity Sensors VFS491                                | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.57%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.57%   |
| AuthenTec AES2810                                      | 1         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.57%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.57%   |
| AuthenTec AES1600                                      | 1         | 3.57%   |

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
| 1     | 46        | 35.38%  |
| 2     | 39        | 30%     |
| 0     | 22        | 16.92%  |
| 3     | 16        | 12.31%  |
| 4     | 7         | 5.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 80        | 42.33%  |
| Net/wireless             | 36        | 19.05%  |
| Fingerprint reader       | 27        | 14.29%  |
| Bluetooth                | 23        | 12.17%  |
| Card reader              | 20        | 10.58%  |
| Storage                  | 1         | 0.53%   |
| Sound                    | 1         | 0.53%   |
| Network                  | 1         | 0.53%   |

