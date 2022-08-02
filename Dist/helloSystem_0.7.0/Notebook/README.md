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

Total: 183

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Apple         | MacBook4,1                  | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| MSI           | GF63 Thin 10SC              | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Fujitsu       | LIFEBOOK A555               | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Alienware     | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| HP            | ProBook 4230s               | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
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
| amd64 | 157       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 155       | 98.73%  |
| GNOME        | 2         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 157       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 157       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 147       | 93.04%  |
| es_ES | 3         | 1.9%    |
| C     | 3         | 1.9%    |
| fr_FR | 2         | 1.27%   |
| uk_UA | 1         | 0.63%   |
| it_IT | 1         | 0.63%   |
| de_DE | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 153       | 97.45%  |
| BIOS | 4         | 2.55%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 85        | 53.46%  |
| Zfs    | 74        | 46.54%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 156       | 99.36%  |
| MBR  | 1         | 0.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 31.21%  |
| Hewlett-Packard     | 27        | 17.2%   |
| Dell                | 18        | 11.46%  |
| Acer                | 15        | 9.55%   |
| Apple               | 10        | 6.37%   |
| ASUSTek Computer    | 9         | 5.73%   |
| Toshiba             | 6         | 3.82%   |
| TUXEDO              | 3         | 1.91%   |
| Samsung Electronics | 3         | 1.91%   |
| Sony                | 2         | 1.27%   |
| MSI                 | 2         | 1.27%   |
| TWINHEAD            | 1         | 0.64%   |
| Razer               | 1         | 0.64%   |
| Panasonic           | 1         | 0.64%   |
| Packard Bell        | 1         | 0.64%   |
| Notebook            | 1         | 0.64%   |
| LG Electronics      | 1         | 0.64%   |
| Itautec             | 1         | 0.64%   |
| HASEE Computer      | 1         | 0.64%   |
| Gateway             | 1         | 0.64%   |
| Fujitsu             | 1         | 0.64%   |
| DNS                 | 1         | 0.64%   |
| Alienware           | 1         | 0.64%   |
| Unknown             | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 3         | 1.91%   |
| TUXEDO Aura 15 Gen1                                | 2         | 1.27%   |
| Dell Latitude E5470                                | 2         | 1.27%   |
| Apple MacBook6,1                                   | 2         | 1.27%   |
| Acer V5-131                                        | 2         | 1.27%   |
| Acer Aspire E1-522                                 | 2         | 1.27%   |
| TWINHEAD U12CT                                     | 1         | 0.64%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.64%   |
| Toshiba Satellite S55t-B                           | 1         | 0.64%   |
| Toshiba Satellite P300                             | 1         | 0.64%   |
| Toshiba Satellite L550                             | 1         | 0.64%   |
| Toshiba Satellite C640                             | 1         | 0.64%   |
| Toshiba Satellite C50-B                            | 1         | 0.64%   |
| Toshiba PORTEGE R700                               | 1         | 0.64%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.64%   |
| Sony SVZ1311C5E                                    | 1         | 0.64%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.64%   |
| Samsung N100                                       | 1         | 0.64%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.64%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.64%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.64%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.64%   |
| Notebook N15_17RD                                  | 1         | 0.64%   |
| MSI GF65 Thin 10SER                                | 1         | 0.64%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.64%   |
| LG E300-A.CP20T                                    | 1         | 0.64%   |
| Lenovo Z50-70 20354                                | 1         | 0.64%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.64%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.64%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.64%   |
| Lenovo ThinkPad X260 20F5S45W00                    | 1         | 0.64%   |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.64%   |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.64%   |
| Lenovo ThinkPad X220 Tablet 4298B65                | 1         | 0.64%   |
| Lenovo ThinkPad X220 Tablet 42962WU                | 1         | 0.64%   |
| Lenovo ThinkPad X220 4293B43                       | 1         | 0.64%   |
| Lenovo ThinkPad X220 4293AF4                       | 1         | 0.64%   |
| Lenovo ThinkPad X220 4291H77                       | 1         | 0.64%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00           | 1         | 0.64%   |
| Lenovo ThinkPad T61 766301U                        | 1         | 0.64%   |
| Lenovo ThinkPad T61 7661GY9                        | 1         | 0.64%   |
| Lenovo ThinkPad T60 1951FEG                        | 1         | 0.64%   |
| Lenovo ThinkPad T510 4384AJ6                       | 1         | 0.64%   |
| Lenovo ThinkPad T460 20FN004CUK                    | 1         | 0.64%   |
| Lenovo ThinkPad T460 20FMS75800                    | 1         | 0.64%   |
| Lenovo ThinkPad T440p 20AWS3RH00                   | 1         | 0.64%   |
| Lenovo ThinkPad T440p 20AWS0DU00                   | 1         | 0.64%   |
| Lenovo ThinkPad T440 20B7000PHV                    | 1         | 0.64%   |
| Lenovo ThinkPad T430s 2356CV6                      | 1         | 0.64%   |
| Lenovo ThinkPad T430 2349AK1                       | 1         | 0.64%   |
| Lenovo ThinkPad T420 4236MY0                       | 1         | 0.64%   |
| Lenovo ThinkPad T420 4236BD5                       | 1         | 0.64%   |
| Lenovo ThinkPad T410 2537EA8                       | 1         | 0.64%   |
| Lenovo ThinkPad T410 2522E38                       | 1         | 0.64%   |
| Lenovo ThinkPad T410 2522CS7                       | 1         | 0.64%   |
| Lenovo ThinkPad SL510 2847R96                      | 1         | 0.64%   |
| Lenovo ThinkPad R61 8935WCS                        | 1         | 0.64%   |
| Lenovo ThinkPad L450 20DSS1S402                    | 1         | 0.64%   |
| Lenovo ThinkPad L440 20ASS0FP00                    | 1         | 0.64%   |
| Lenovo ThinkPad L412 0585AD9                       | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 34        | 21.66%  |
| Acer Aspire             | 11        | 7.01%   |
| Dell Latitude           | 10        | 6.37%   |
| HP Pavilion             | 9         | 5.73%   |
| Lenovo IdeaPad          | 7         | 4.46%   |
| Dell Inspiron           | 6         | 3.82%   |
| Toshiba Satellite       | 5         | 3.18%   |
| HP ProBook              | 5         | 3.18%   |
| HP Laptop               | 3         | 1.91%   |
| HP EliteBook            | 3         | 1.91%   |
| Apple MacBook4          | 3         | 1.91%   |
| TUXEDO Aura             | 2         | 1.27%   |
| HP Compaq               | 2         | 1.27%   |
| Apple MacBook6          | 2         | 1.27%   |
| Apple MacBook5          | 2         | 1.27%   |
| Acer V5-131             | 2         | 1.27%   |
| TWINHEAD U12CT          | 1         | 0.64%   |
| TUXEDO InfinityBook13V3 | 1         | 0.64%   |
| Toshiba PORTEGE         | 1         | 0.64%   |
| Sony VGN-NW25GF         | 1         | 0.64%   |
| Sony SVZ1311C5E         | 1         | 0.64%   |
| Samsung N150P           | 1         | 0.64%   |
| Samsung N100            | 1         | 0.64%   |
| Samsung 305E4A          | 1         | 0.64%   |
| Razer Blade             | 1         | 0.64%   |
| Panasonic CF-B11JWCYS   | 1         | 0.64%   |
| Packard Bell EasyNote   | 1         | 0.64%   |
| Notebook N15            | 1         | 0.64%   |
| MSI GF65                | 1         | 0.64%   |
| MSI GF63                | 1         | 0.64%   |
| LG E300-A.CP20T         | 1         | 0.64%   |
| Lenovo Z50-70           | 1         | 0.64%   |
| Lenovo V310-14IKB       | 1         | 0.64%   |
| Lenovo ThinkBook        | 1         | 0.64%   |
| Lenovo Legion           | 1         | 0.64%   |
| Lenovo G51-35           | 1         | 0.64%   |
| Lenovo G40-30           | 1         | 0.64%   |
| Lenovo E31-80           | 1         | 0.64%   |
| Lenovo B470             | 1         | 0.64%   |
| Itautec Infoway         | 1         | 0.64%   |
| HP ZBook                | 1         | 0.64%   |
| HP Mini                 | 1         | 0.64%   |
| HP G62                  | 1         | 0.64%   |
| HP 2000                 | 1         | 0.64%   |
| HP 15                   | 1         | 0.64%   |
| HASEE CW35S             | 1         | 0.64%   |
| Gateway NE56R           | 1         | 0.64%   |
| Fujitsu LIFEBOOK        | 1         | 0.64%   |
| DNS W9x0LU              | 1         | 0.64%   |
| Dell Vostro             | 1         | 0.64%   |
| Dell Venue              | 1         | 0.64%   |
| ASUS X556UJ             | 1         | 0.64%   |
| ASUS X555LA             | 1         | 0.64%   |
| ASUS X540LA             | 1         | 0.64%   |
| ASUS S550CA             | 1         | 0.64%   |
| ASUS N56VB              | 1         | 0.64%   |
| ASUS K52Jc              | 1         | 0.64%   |
| ASUS K52F               | 1         | 0.64%   |
| ASUS F50SL              | 1         | 0.64%   |
| ASUS ASUS               | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 15        | 9.55%   |
| 2021    | 14        | 8.92%   |
| 2018    | 14        | 8.92%   |
| 2015    | 14        | 8.92%   |
| 2016    | 13        | 8.28%   |
| 2011    | 13        | 8.28%   |
| 2010    | 12        | 7.64%   |
| 2020    | 10        | 6.37%   |
| 2017    | 9         | 5.73%   |
| 2012    | 9         | 5.73%   |
| 2009    | 9         | 5.73%   |
| 2008    | 8         | 5.1%    |
| 2014    | 6         | 3.82%   |
| 2007    | 5         | 3.18%   |
| 2019    | 2         | 1.27%   |
| 2006    | 2         | 1.27%   |
| 2022    | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 157       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 157       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 39.49%  |
| 8.01-16.0   | 49        | 31.21%  |
| 16.01-24.0  | 27        | 17.2%   |
| 2.01-3.0    | 11        | 7.01%   |
| 32.01-64.0  | 3         | 1.91%   |
| 3.01-4.0    | 3         | 1.91%   |
| 24.01-32.0  | 1         | 0.64%   |
| 64.01-256.0 | 1         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 100       | 63.69%  |
| 0.51-1.0 | 45        | 28.66%  |
| 1.01-2.0 | 7         | 4.46%   |
| 2.01-3.0 | 5         | 3.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 74.05%  |
| 2      | 31        | 19.62%  |
| 0      | 7         | 4.43%   |
| 3      | 2         | 1.27%   |
| 4      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 52.87%  |
| Yes       | 74        | 47.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 94.27%  |
| No        | 9         | 5.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 99.36%  |
| No        | 1         | 0.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 66.24%  |
| No        | 53        | 33.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 25        | 15.92%  |
| Russia              | 11        | 7.01%   |
| Germany             | 10        | 6.37%   |
| Italy               | 9         | 5.73%   |
| Brazil              | 9         | 5.73%   |
| UK                  | 8         | 5.1%    |
| Spain               | 6         | 3.82%   |
| France              | 6         | 3.82%   |
| Romania             | 5         | 3.18%   |
| Netherlands         | 5         | 3.18%   |
| Mexico              | 5         | 3.18%   |
| China               | 5         | 3.18%   |
| Ukraine             | 4         | 2.55%   |
| Indonesia           | 4         | 2.55%   |
| Vietnam             | 3         | 1.91%   |
| Chile               | 3         | 1.91%   |
| Turkey              | 2         | 1.27%   |
| Sweden              | 2         | 1.27%   |
| Portugal            | 2         | 1.27%   |
| Poland              | 2         | 1.27%   |
| Peru                | 2         | 1.27%   |
| Norway              | 2         | 1.27%   |
| India               | 2         | 1.27%   |
| Hungary             | 2         | 1.27%   |
| Greece              | 2         | 1.27%   |
| Denmark             | 2         | 1.27%   |
| Colombia            | 2         | 1.27%   |
| Trinidad and Tobago | 1         | 0.64%   |
| Tanzania            | 1         | 0.64%   |
| Taiwan              | 1         | 0.64%   |
| New Zealand         | 1         | 0.64%   |
| Myanmar             | 1         | 0.64%   |
| Malaysia            | 1         | 0.64%   |
| Lithuania           | 1         | 0.64%   |
| Ireland             | 1         | 0.64%   |
| Georgia             | 1         | 0.64%   |
| Finland             | 1         | 0.64%   |
| Czechia             | 1         | 0.64%   |
| Cuba                | 1         | 0.64%   |
| Canada              | 1         | 0.64%   |
| Bulgaria            | 1         | 0.64%   |
| Belarus             | 1         | 0.64%   |
| Austria             | 1         | 0.64%   |
| Argentina           | 1         | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 4         | 2.52%   |
| Hanoi                         | 3         | 1.89%   |
| Warsaw                        | 2         | 1.26%   |
| Lima                          | 2         | 1.26%   |
| Leatherhead                   | 2         | 1.26%   |
| Jakarta                       | 2         | 1.26%   |
| Dijon                         | 2         | 1.26%   |
| Bucharest                     | 2         | 1.26%   |
| Amsterdam                     | 2         | 1.26%   |
| Zhaoqing                      | 1         | 0.63%   |
| Zaporizhzhya                  | 1         | 0.63%   |
| Zapopan                       | 1         | 0.63%   |
| Youngsville                   | 1         | 0.63%   |
| Yichun                        | 1         | 0.63%   |
| Yaphank                       | 1         | 0.63%   |
| Yangon                        | 1         | 0.63%   |
| Windsor                       | 1         | 0.63%   |
| Washington                    | 1         | 0.63%   |
| Vilnius                       | 1         | 0.63%   |
| Ventura                       | 1         | 0.63%   |
| VÃ¤sterÃ¥s                | 1         | 0.63%   |
| Vaudreuil-Dorion              | 1         | 0.63%   |
| Vandalia                      | 1         | 0.63%   |
| Ugarchin                      | 1         | 0.63%   |
| Turley                        | 1         | 0.63%   |
| Turin                         | 1         | 0.63%   |
| Tromsø                       | 1         | 0.63%   |
| Torokszentmiklos              | 1         | 0.63%   |
| Tolyatti                      | 1         | 0.63%   |
| Tiruchi                       | 1         | 0.63%   |
| Thessaloniki                  | 1         | 0.63%   |
| Taipei                        | 1         | 0.63%   |
| Susanville                    | 1         | 0.63%   |
| Suceava                       | 1         | 0.63%   |
| St Petersburg                 | 1         | 0.63%   |
| Shah Alam                     | 1         | 0.63%   |
| Sevastopol                    | 1         | 0.63%   |
| Seattle                       | 1         | 0.63%   |
| Scottsdale                    | 1         | 0.63%   |
| Sao Paulo                     | 1         | 0.63%   |
| Sao Bernardo do Campo         | 1         | 0.63%   |
| Santiago                      | 1         | 0.63%   |
| San SebastiÃ¡n de los Reyes | 1         | 0.63%   |
| San Luis PotosÃ­ City       | 1         | 0.63%   |
| San Antonio                   | 1         | 0.63%   |
| Riverton                      | 1         | 0.63%   |
| Rio de Janeiro                | 1         | 0.63%   |
| Rho                           | 1         | 0.63%   |
| Ransbach-Baumbach             | 1         | 0.63%   |
| Quimper                       | 1         | 0.63%   |
| Putkilahti                    | 1         | 0.63%   |
| Pudong                        | 1         | 0.63%   |
| Pruszcz Gdanski               | 1         | 0.63%   |
| Potsdam                       | 1         | 0.63%   |
| Portland                      | 1         | 0.63%   |
| Port of Spain                 | 1         | 0.63%   |
| Piovene Rocchette             | 1         | 0.63%   |
| Pflugerville                  | 1         | 0.63%   |
| Patterson                     | 1         | 0.63%   |
| Passignano sul Trasimeno      | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 38     | 19.68%  |
| Samsung Electronics | 26        | 28     | 13.83%  |
| Seagate             | 18        | 21     | 9.57%   |
| Toshiba             | 16        | 16     | 8.51%   |
| Kingston            | 15        | 16     | 7.98%   |
| Crucial             | 12        | 12     | 6.38%   |
| SanDisk             | 8         | 9      | 4.26%   |
| Intel               | 7         | 8      | 3.72%   |
| Hitachi             | 7         | 7      | 3.72%   |
| HGST                | 6         | 6      | 3.19%   |
| Fujitsu             | 4         | 4      | 2.13%   |
| Micron Technology   | 3         | 3      | 1.6%    |
| A-DATA Technology   | 3         | 3      | 1.6%    |
| SPCC                | 2         | 3      | 1.06%   |
| SK hynix            | 2         | 2      | 1.06%   |
| Patriot             | 2         | 2      | 1.06%   |
| KingSpec            | 2         | 2      | 1.06%   |
| Intenso             | 2         | 2      | 1.06%   |
| Zheino              | 1         | 1      | 0.53%   |
| Transcend           | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| SSSTC               | 1         | 1      | 0.53%   |
| Netac               | 1         | 1      | 0.53%   |
| Mushkin             | 1         | 1      | 0.53%   |
| LITEON              | 1         | 1      | 0.53%   |
| KIOXIA              | 1         | 1      | 0.53%   |
| Integral            | 1         | 1      | 0.53%   |
| INDMEM              | 1         | 1      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| Corsair             | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |
| Apacer              | 1         | 1      | 0.53%   |
| ANACOMDA            | 1         | 1      | 0.53%   |
| AGI                 | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB           | 5         | 2.6%    |
| WDC WDS120G2G0A-00JH30 120GB         | 4         | 2.08%   |
| Toshiba MQ01ABF050 500GB             | 4         | 2.08%   |
| Kingston SA400S37240G 240GB          | 3         | 1.56%   |
| Kingston SA400S37120G 120GB          | 3         | 1.56%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.56%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.56%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.04%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 1.04%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1.04%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 1.04%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.04%   |
| SK hynix HFS256G39TND-N210A 256GB    | 2         | 1.04%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.04%   |
| Samsung SSD PM871 2.5 7mm 128GB      | 2         | 1.04%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.04%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 2         | 1.04%   |
| Zheino CHN mSATAM1 256 256GB         | 1         | 0.52%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.52%   |
| WDC WDS240G1G0A-00SS50 240GB         | 1         | 0.52%   |
| WDC WDBNCE5000PNC 500GB              | 1         | 0.52%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.52%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.52%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.52%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.52%   |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.52%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.52%   |
| WDC WD5000BPKX-22HPJT0 500GB         | 1         | 0.52%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.52%   |
| WDC WD3200BEKX-60B7WT0 320GB         | 1         | 0.52%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.52%   |
| WDC WD1600BEVT-80A23T0 160GB         | 1         | 0.52%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.52%   |
| WDC WD1600BEKT-66F3T2 160GB          | 1         | 0.52%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 0.52%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.52%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.52%   |
| WDC WD10SDZW-11UMGS0 1TB             | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.52%   |
| WDC WD10JMVW-11AJGS4 1TB             | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 0.52%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.52%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.52%   |
| Transcend TS240GMTS420S 240GB        | 1         | 0.52%   |
| Toshiba THNSNX024GMNT 24GB           | 1         | 0.52%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.52%   |
| Toshiba MQ01ABD075 752GB             | 1         | 0.52%   |
| Toshiba MK8034GSX 80GB               | 1         | 0.52%   |
| Toshiba MK7559GSXF 752GB             | 1         | 0.52%   |
| Toshiba MK6034GSX 64GB               | 1         | 0.52%   |
| Toshiba MK3265GSXN 320GB             | 1         | 0.52%   |
| Toshiba MK3261GSYN 320GB             | 1         | 0.52%   |
| Toshiba MK2561GSYN 250GB             | 1         | 0.52%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.52%   |
| Team TEAML5Lite3D120G 120GB          | 1         | 0.52%   |
| SSSTC CL1-4D256 256GB                | 1         | 0.52%   |
| SPCC Solid State Disk 512GB          | 1         | 0.52%   |
| SPCC Solid State Disk 256GB          | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 26     | 33.33%  |
| Seagate             | 18        | 21     | 24%     |
| Toshiba             | 14        | 14     | 18.67%  |
| Hitachi             | 7         | 7      | 9.33%   |
| HGST                | 6         | 6      | 8%      |
| Fujitsu             | 3         | 3      | 4%      |
| Samsung Electronics | 2         | 2      | 2.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 17.05%  |
| Kingston            | 12        | 12     | 13.64%  |
| Crucial             | 12        | 12     | 13.64%  |
| WDC                 | 8         | 8      | 9.09%   |
| SanDisk             | 8         | 9      | 9.09%   |
| Intel               | 5         | 5      | 5.68%   |
| SPCC                | 2         | 3      | 2.27%   |
| SK hynix            | 2         | 2      | 2.27%   |
| Patriot             | 2         | 2      | 2.27%   |
| KingSpec            | 2         | 2      | 2.27%   |
| Intenso             | 2         | 2      | 2.27%   |
| A-DATA Technology   | 2         | 2      | 2.27%   |
| Zheino              | 1         | 1      | 1.14%   |
| Transcend           | 1         | 1      | 1.14%   |
| Toshiba             | 1         | 1      | 1.14%   |
| Team                | 1         | 1      | 1.14%   |
| Netac               | 1         | 1      | 1.14%   |
| Mushkin             | 1         | 1      | 1.14%   |
| Micron Technology   | 1         | 1      | 1.14%   |
| LITEON              | 1         | 1      | 1.14%   |
| Integral            | 1         | 1      | 1.14%   |
| INDMEM              | 1         | 1      | 1.14%   |
| Hewlett-Packard     | 1         | 1      | 1.14%   |
| Fujitsu             | 1         | 1      | 1.14%   |
| Corsair             | 1         | 1      | 1.14%   |
| Apple               | 1         | 1      | 1.14%   |
| Apacer              | 1         | 1      | 1.14%   |
| ANACOMDA            | 1         | 1      | 1.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 77        | 91     | 45.03%  |
| HDD  | 69        | 79     | 40.35%  |
| NVMe | 25        | 28     | 14.62%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 137       | 170    | 84.57%  |
| NVMe | 25        | 28     | 15.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 116       | 138    | 80%     |
| 0.51-1.0   | 27        | 30     | 18.62%  |
| 1.01-2.0   | 1         | 1      | 0.69%   |
| 4.01-10.0  | 1         | 1      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 82        | 51.57%  |
| 101-250    | 31        | 19.5%   |
| 251-500    | 25        | 15.72%  |
| 501-1000   | 10        | 6.29%   |
| 21-50      | 6         | 3.77%   |
| 51-100     | 4         | 2.52%   |
| Unknown    | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 153       | 97.45%  |
| 21-50   | 2         | 1.27%   |
| 101-250 | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 2.44%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 2.44%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 2.44%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.44%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2.44%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 2.44%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 2.44%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 2.44%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 2.44%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 2.44%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 2.44%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 2.44%   |
| Seagate ST9120821AS 118GB          | 1         | 1      | 2.44%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.44%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.44%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 2.44%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 2.44%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 2.44%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 2.44%   |
| Kingston SUV500MS480G 480GB        | 1         | 1      | 2.44%   |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 2.44%   |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9SA02 250GB      | 1         | 1      | 2.44%   |
| Hitachi HTS542516K9SA00 160GB      | 1         | 1      | 2.44%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 2.44%   |
| HGST HTS541075A7E630 752GB         | 1         | 1      | 2.44%   |
| Fujitsu MHZ2250BH G2 250GB         | 1         | 1      | 2.44%   |
| AGI AGI512G16AI198 512GB           | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 21.95%  |
| Toshiba             | 9         | 9      | 21.95%  |
| Seagate             | 9         | 9      | 21.95%  |
| Hitachi             | 5         | 5      | 12.2%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| Kingston            | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| LITEON              | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| AGI                 | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 25%     |
| Seagate             | 9         | 9      | 25%     |
| Toshiba             | 8         | 8      | 22.22%  |
| Hitachi             | 5         | 5      | 13.89%  |
| Samsung Electronics | 2         | 2      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| Fujitsu             | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 36     | 86.84%  |
| SSD  | 4         | 4      | 10.53%  |
| NVMe | 1         | 1      | 2.63%   |

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
| Works    | 119       | 156    | 75.32%  |
| Malfunc  | 38        | 41     | 24.05%  |
| Detected | 1         | 1      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 127       | 73.84%  |
| AMD                              | 16        | 9.3%    |
| Samsung Electronics              | 10        | 5.81%   |
| Nvidia                           | 5         | 2.91%   |
| SanDisk                          | 4         | 2.33%   |
| Micron Technology                | 2         | 1.16%   |
| KIOXIA                           | 2         | 1.16%   |
| Kingston Technology Company      | 2         | 1.16%   |
| Solid State Storage Technology   | 1         | 0.58%   |
| Silicon Motion                   | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| ADATA Technology                 | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 8.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 8.56%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 8.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 6.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 5.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 4.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 4.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 4.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 3.21%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.67%   |
| Unknown                                                                          | 5         | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.07%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.07%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.53%   |
| SanDisk unknown                                                                  | 1         | 0.53%   |
| SanDisk PC SN530                                                                 | 1         | 0.53%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.53%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.53%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.53%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.53%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.53%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.53%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.53%   |
| AMD SB600 IDE                                                                    | 1         | 0.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 136       | 74.32%  |
| NVMe | 24        | 13.11%  |
| IDE  | 16        | 8.74%   |
| RAID | 7         | 3.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 87.26%  |
| AMD    | 20        | 12.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 5.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.55%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 4         | 2.55%   |
| Intel CPU Version                           | 3         | 1.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.91%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 1.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.91%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 3         | 1.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.27%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 1.27%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 2         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.27%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.27%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.27%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.27%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.27%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 2         | 1.27%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.27%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.27%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.27%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.27%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 1.27%   |
| Intel Pentium M                             | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.64%   |
| Intel Pentium CPU P6200 @ 2.13GH            | 1         | 0.64%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.64%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.64%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.64%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.64%   |
| Intel Genuine CPU                           | 1         | 0.64%   |
| Intel Core M-5Y71 CPU @ 1.20GHz             | 1         | 0.64%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.64%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.64%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.64%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.64%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 0.64%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.64%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.64%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 0.64%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.64%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.64%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 0.64%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.64%   |
| Intel Core i5-10500H CPU @ 2.50GHz          | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 56        | 35.67%  |
| Intel Core 2 Duo        | 19        | 12.1%   |
| Intel Core i7           | 17        | 10.83%  |
| Intel Core i3           | 17        | 10.83%  |
| Intel Celeron           | 11        | 7.01%   |
| AMD Ryzen 5             | 6         | 3.82%   |
| Intel Pentium           | 5         | 3.18%   |
| AMD A6                  | 4         | 2.55%   |
| Other                   | 3         | 1.91%   |
| Intel Atom              | 3         | 1.91%   |
| AMD E1                  | 3         | 1.91%   |
| Intel Core 2            | 2         | 1.27%   |
| AMD Ryzen 7             | 2         | 1.27%   |
| AMD E2                  | 2         | 1.27%   |
| Intel Pentium M         | 1         | 0.64%   |
| Intel Pentium Dual-Core | 1         | 0.64%   |
| Intel Genuine           | 1         | 0.64%   |
| Intel Core M            | 1         | 0.64%   |
| AMD Ryzen 3             | 1         | 0.64%   |
| AMD A8                  | 1         | 0.64%   |
| AMD A10                 | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 93        | 59.24%  |
| 4       | 29        | 18.47%  |
| Unknown | 23        | 14.65%  |
| 8       | 5         | 3.18%   |
| 6       | 4         | 2.55%   |
| 12      | 2         | 1.27%   |
| 1       | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 146       | 92.99%  |
| 2       | 9         | 5.73%   |
| Unknown | 2         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 91        | 57.96%  |
| 1       | 43        | 27.39%  |
| Unknown | 23        | 14.65%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 18        | 11.46%  |
| IvyBridge   | 18        | 11.46%  |
| KabyLake    | 15        | 9.55%   |
| Haswell     | 15        | 9.55%   |
| Westmere    | 14        | 8.92%   |
| SandyBridge | 14        | 8.92%   |
| Skylake     | 13        | 8.28%   |
| Silvermont  | 8         | 5.1%    |
| Core        | 8         | 5.1%    |
| Broadwell   | 5         | 3.18%   |
| Zen 2       | 4         | 2.55%   |
| CometLake   | 4         | 2.55%   |
| Zen+        | 3         | 1.91%   |
| Jaguar      | 3         | 1.91%   |
| Bonnell     | 3         | 1.91%   |
| Bobcat      | 3         | 1.91%   |
| Goldmont    | 2         | 1.27%   |
| Excavator   | 2         | 1.27%   |
| Zen 3       | 1         | 0.64%   |
| Zen         | 1         | 0.64%   |
| Puma        | 1         | 0.64%   |
| Piledriver  | 1         | 0.64%   |
| K10 Llano   | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 63.93%  |
| AMD    | 35        | 19.13%  |
| Nvidia | 31        | 16.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 8.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 7.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 5.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 5.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 4.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 4.15%   |
| Intel HD Graphics 620                                                                    | 6         | 3.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.59%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 2.07%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.07%   |
| AMD Renoir                                                                               | 4         | 2.07%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.55%   |
| Intel HD Graphics 530                                                                    | 3         | 1.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.55%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.04%   |
| Nvidia TU117M                                                                            | 2         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.04%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.04%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.04%   |
| Intel HD Graphics 500                                                                    | 2         | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.04%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 1.04%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.52%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.52%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.52%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.52%   |
| Nvidia GK104M [GeForce GTX 780M]                                                         | 1         | 0.52%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.52%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.52%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.52%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.52%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.52%   |
| Nvidia G86M [Quadro NVS 135M]                                                            | 1         | 0.52%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 0.52%   |
| Intel HD Graphics 630                                                                    | 1         | 0.52%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.52%   |
| Intel HD Graphics 520                                                                    | 1         | 0.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.52%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.52%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.52%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.52%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.52%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 49.68%  |
| 1 x AMD        | 26        | 16.56%  |
| Intel + Nvidia | 17        | 10.83%  |
| 2 x Intel      | 15        | 9.55%   |
| 1 x Nvidia     | 12        | 7.64%   |
| Intel + AMD    | 7         | 4.46%   |
| AMD + Nvidia   | 2         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 141       | 89.81%  |
| Proprietary | 13        | 8.28%   |
| Unknown     | 3         | 1.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 77.71%  |
| 0.01-0.5   | 23        | 14.65%  |
| 0.51-1.0   | 6         | 3.82%   |
| 1.01-2.0   | 3         | 1.91%   |
| 3.01-4.0   | 2         | 1.27%   |
| 5.01-6.0   | 1         | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 32        | 20.13%  |
| Chimei Innolux          | 26        | 16.35%  |
| AU Optronics            | 26        | 16.35%  |
| Samsung Electronics     | 21        | 13.21%  |
| Lenovo                  | 16        | 10.06%  |
| BOE                     | 16        | 10.06%  |
| Apple                   | 10        | 6.29%   |
| Chi Mei Optoelectronics | 2         | 1.26%   |
| Vestel Elektronik       | 1         | 0.63%   |
| Toshiba                 | 1         | 0.63%   |
| Sony                    | 1         | 0.63%   |
| SLD                     | 1         | 0.63%   |
| Philips                 | 1         | 0.63%   |
| Lenovo Group Limited    | 1         | 0.63%   |
| LED                     | 1         | 0.63%   |
| BenQ                    | 1         | 0.63%   |
| Ancor Communications    | 1         | 0.63%   |
| Acer                    | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 4         | 2.47%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                | 3         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch        | 3         | 1.85%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 2         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 2         | 1.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 1.23%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 2         | 1.23%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 1.23%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                | 2         | 1.23%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch        | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 2         | 1.23%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.62%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.62%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                          | 1         | 0.62%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                   | 1         | 0.62%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.62%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.62%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4E41 1280x800 260x160mm 12.0-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.62%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1         | 0.62%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1         | 0.62%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD0455 1366x768 310x170mm 13.9-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD03DF 1366x768 340x190mm 15.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0324 1280x800 220x140mm 10.3-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch            | 1         | 0.62%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch            | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 74        | 47.44%  |
| 1920x1080 (FHD)   | 39        | 25%     |
| 1280x800 (WXGA)   | 20        | 12.82%  |
| 1600x900 (HD+)    | 8         | 5.13%   |
| 3840x2160 (4K)    | 3         | 1.92%   |
| 2560x1440 (QHD)   | 2         | 1.28%   |
| 1920x540          | 2         | 1.28%   |
| 1440x900 (WXGA+)  | 2         | 1.28%   |
| 1024x768 (XGA)    | 2         | 1.28%   |
| 1024x600          | 2         | 1.28%   |
| 1920x1200 (WUXGA) | 1         | 0.64%   |
| 1280x1024 (SXGA)  | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 55        | 33.95%  |
| 13      | 48        | 29.63%  |
| 12      | 14        | 8.64%   |
| 14      | 9         | 5.56%   |
| 17      | 7         | 4.32%   |
| 11      | 6         | 3.7%    |
| 27      | 4         | 2.47%   |
| 24      | 3         | 1.85%   |
| 23      | 3         | 1.85%   |
| 10      | 3         | 1.85%   |
| 18      | 2         | 1.23%   |
| 64      | 1         | 0.62%   |
| 54      | 1         | 0.62%   |
| 42      | 1         | 0.62%   |
| 40      | 1         | 0.62%   |
| 31      | 1         | 0.62%   |
| 20      | 1         | 0.62%   |
| 16      | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 87        | 53.7%   |
| 201-300     | 48        | 29.63%  |
| 501-600     | 9         | 5.56%   |
| 351-400     | 9         | 5.56%   |
| 601-700     | 2         | 1.23%   |
| 401-500     | 2         | 1.23%   |
| 1001-1500   | 2         | 1.23%   |
| 801-900     | 1         | 0.62%   |
| 901-1000    | 1         | 0.62%   |
| Unknown     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 122       | 81.33%  |
| 16/10   | 20        | 13.33%  |
| 3/2     | 4         | 2.67%   |
| 4/3     | 2         | 1.33%   |
| 5/4     | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 49        | 30.25%  |
| 91-100         | 45        | 27.78%  |
| 61-70          | 15        | 9.26%   |
| 101-110        | 11        | 6.79%   |
| 71-80          | 7         | 4.32%   |
| 51-60          | 5         | 3.09%   |
| 201-250        | 5         | 3.09%   |
| 121-130        | 5         | 3.09%   |
| 301-350        | 4         | 2.47%   |
| 41-50          | 3         | 1.85%   |
| More than 1000 | 2         | 1.23%   |
| 141-150        | 2         | 1.23%   |
| 131-140        | 2         | 1.23%   |
| 501-1000       | 2         | 1.23%   |
| 351-500        | 1         | 0.62%   |
| 251-300        | 1         | 0.62%   |
| 151-200        | 1         | 0.62%   |
| 111-120        | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 70        | 44.03%  |
| 121-160 | 62        | 38.99%  |
| 51-100  | 23        | 14.47%  |
| 161-240 | 3         | 1.89%   |
| Unknown | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 138       | 87.34%  |
| 2     | 15        | 9.49%   |
| 0     | 5         | 3.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 81        | 30.8%   |
| Realtek Semiconductor             | 75        | 28.52%  |
| Qualcomm Atheros                  | 39        | 14.83%  |
| Broadcom                          | 30        | 11.41%  |
| Marvell Technology Group          | 8         | 3.04%   |
| Nvidia                            | 5         | 1.9%    |
| Ralink                            | 3         | 1.14%   |
| JMicron Technology                | 3         | 1.14%   |
| NetGear                           | 2         | 0.76%   |
| Ericsson Business Mobile Networks | 2         | 0.76%   |
| Edimax Technology                 | 2         | 0.76%   |
| Dell                              | 2         | 0.76%   |
| Xiaomi                            | 1         | 0.38%   |
| TP-Link                           | 1         | 0.38%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.38%   |
| Sierra Wireless                   | 1         | 0.38%   |
| Samsung Electronics               | 1         | 0.38%   |
| OPPO Electronics                  | 1         | 0.38%   |
| Mercucys                          | 1         | 0.38%   |
| Huawei Technologies               | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Google                            | 1         | 0.38%   |
| D-Link System                     | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 52        | 15.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 5.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 3.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 3.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 3.34%   |
| Intel Wireless 8260                                                     | 9         | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.13%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.82%   |
| Intel Wireless 7260                                                     | 6         | 1.82%   |
| Intel 82577LM Gigabit Network Connection                                | 6         | 1.82%   |
| Nvidia MCP79 Ethernet                                                   | 5         | 1.52%   |
| Intel Wireless 7265                                                     | 5         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.22%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 1.22%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 1.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.91%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 3         | 0.91%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.91%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.91%   |
| Intel WiFi Link 5100                                                    | 3         | 0.91%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.91%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.91%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.61%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.61%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                   | 2         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.61%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.61%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.3%    |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.3%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.3%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.3%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.3%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 47.34%  |
| Qualcomm Atheros      | 37        | 21.89%  |
| Realtek Semiconductor | 22        | 13.02%  |
| Broadcom              | 19        | 11.24%  |
| Ralink                | 3         | 1.78%   |
| NetGear               | 2         | 1.18%   |
| Edimax Technology     | 2         | 1.18%   |
| TP-Link               | 1         | 0.59%   |
| Sierra Wireless       | 1         | 0.59%   |
| Mercucys              | 1         | 0.59%   |
| Dell                  | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 6.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 6.36%   |
| Intel Wireless 8260                                                     | 9         | 5.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 4.05%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 4.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.47%   |
| Intel Wireless 7260                                                     | 6         | 3.47%   |
| Intel Wireless 7265                                                     | 5         | 2.89%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.31%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 2.31%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 2.31%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.73%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.73%   |
| Intel WiFi Link 5100                                                    | 3         | 1.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.73%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.16%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.16%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.16%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.16%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.16%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.16%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.58%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.58%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.58%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.58%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.58%   |
| Mercucys MERCUSYS Wireless USB Adapter                                  | 1         | 0.58%   |
| Intel Wireless 3160                                                     | 1         | 0.58%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.58%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.58%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.58%   |
| Edimax Edimax AC600 Wireless LAN USB Adapter                            | 1         | 0.58%   |
| Dell Hub of E-Port Replicator                                           | 1         | 0.58%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.58%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.58%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 69        | 46%     |
| Intel                            | 42        | 28%     |
| Broadcom                         | 11        | 7.33%   |
| Marvell Technology Group         | 8         | 5.33%   |
| Qualcomm Atheros                 | 7         | 4.67%   |
| Nvidia                           | 5         | 3.33%   |
| JMicron Technology               | 3         | 2%      |
| Xiaomi                           | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.67%   |
| Samsung Electronics              | 1         | 0.67%   |
| OPPO Electronics                 | 1         | 0.67%   |
| Google                           | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 34.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 11.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 8.67%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 4%      |
| Nvidia MCP79 Ethernet                                             | 5         | 3.33%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.67%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 2%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 2%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 3         | 2%      |
| Intel 82566MM Gigabit Network Connection                          | 3         | 2%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.67%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 0.67%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.67%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.67%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.67%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.67%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.67%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.67%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.67%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.67%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.67%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.67%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 156       | 50.32%  |
| Ethernet | 148       | 47.74%  |
| Modem    | 3         | 0.97%   |
| Unknown  | 3         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 116       | 52.25%  |
| WiFi     | 102       | 45.95%  |
| Unknown  | 3         | 1.35%   |
| Modem    | 1         | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 144       | 91.72%  |
| 1     | 12        | 7.64%   |
| 0     | 1         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 149       | 94.9%   |
| Yes  | 8         | 5.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 35.58%  |
| Broadcom                        | 14        | 13.46%  |
| Realtek Semiconductor           | 10        | 9.62%   |
| Qualcomm Atheros Communications | 10        | 9.62%   |
| Apple                           | 9         | 8.65%   |
| Lite-On Technology              | 6         | 5.77%   |
| Hewlett-Packard                 | 4         | 3.85%   |
| Foxconn / Hon Hai               | 4         | 3.85%   |
| Ralink                          | 3         | 2.88%   |
| Dell                            | 3         | 2.88%   |
| IMC Networks                    | 2         | 1.92%   |
| Cambridge Silicon Radio         | 2         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 21.7%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 7.55%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 5.66%   |
| Intel AX200 Bluetooth                                       | 5         | 4.72%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 3.77%   |
| Intel AX201 Bluetooth                                       | 4         | 3.77%   |
| Apple Bluetooth Host Controller                             | 4         | 3.77%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 2.83%   |
| Ralink RT3290 Bluetooth                                     | 3         | 2.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 2.83%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 2.83%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.89%   |
| Realtek Bluetooth Radio                                     | 2         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 1.89%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 1.89%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.89%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.94%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.94%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.94%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.94%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.94%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.94%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.94%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.94%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.94%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.94%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.94%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device      | 1         | 0.94%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.94%   |
| Apple Broadcom Bluetooth 2.1 module                         | 1         | 0.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 130       | 73.86%  |
| AMD                              | 26        | 14.77%  |
| Nvidia                           | 15        | 8.52%   |
| GN Netcom                        | 2         | 1.14%   |
| Texas Instruments                | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Creative Technology              | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 8.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 8.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 6.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 6.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 4.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 4.65%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 4.65%   |
| AMD FCH Azalia Controller                                                                         | 9         | 4.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 2.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.33%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.86%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.4%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.93%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.93%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.47%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.47%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.47%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.47%   |
| Creative Technology SB X-Fi Surround 5.1                                                          | 1         | 0.47%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.47%   |
| AMD RS600 HDMI Audio [Radeon Xpress 1250]                                                         | 1         | 0.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.47%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 27.72%  |
| SK hynix            | 28        | 15.22%  |
| Kingston            | 25        | 13.59%  |
| Micron Technology   | 15        | 8.15%   |
| Unknown             | 13        | 7.07%   |
| Nanya Technology    | 8         | 4.35%   |
| Ramaxel Technology  | 6         | 3.26%   |
| Elpida              | 6         | 3.26%   |
| Crucial             | 6         | 3.26%   |
| Unknown             | 4         | 2.17%   |
| Smart               | 3         | 1.63%   |
| A-DATA Technology   | 3         | 1.63%   |
| Silicon Power       | 2         | 1.09%   |
| ASint Technology    | 2         | 1.09%   |
| 48spaces            | 2         | 1.09%   |
| Unknown (ABCD)      | 1         | 0.54%   |
| Transcend           | 1         | 0.54%   |
| Smart Brazil        | 1         | 0.54%   |
| Sesame              | 1         | 0.54%   |
| PNY                 | 1         | 0.54%   |
| Kingmax             | 1         | 0.54%   |
| High Bridge         | 1         | 0.54%   |
| Corsair             | 1         | 0.54%   |
| Avant               | 1         | 0.54%   |
| Apacer              | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 6         | 3.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 2.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 4         | 2.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 2.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 2.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 2.02%   |
| Unknown                                                                   | 4         | 2.02%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.52%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 1.01%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                      | 2         | 1.01%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 2         | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 1.01%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.01%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 1.01%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 1.01%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 1.01%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.01%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 1.01%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s                     | 2         | 1.01%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 1.01%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2133MT/s          | 1         | 0.51%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.51%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.51%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.51%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.51%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.51%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s              | 1         | 0.51%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.51%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                              | 1         | 0.51%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 0.51%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.51%   |
| SK hynix RAM HYMP512S64CP8-C4 1GB SODIMM DDR 533MT/s                      | 1         | 0.51%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.51%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.51%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 1         | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.51%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.51%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s          | 1         | 0.51%   |
| Silicon Power RAM SP008GBSFU240B02 8GB SODIMM DDR4 2400MT/s               | 1         | 0.51%   |
| Silicon Power RAM SP004GLSTU160N02 4GB SODIMM DDR3 1600MT/s               | 1         | 0.51%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                               | 1         | 0.51%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 0.51%   |
| Samsung RAM Module 4GB SODIMM DDR4 2133MT/s                               | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 91        | 59.09%  |
| DDR4    | 36        | 23.38%  |
| DDR2    | 20        | 12.99%  |
| LPDDR3  | 2         | 1.3%    |
| SDRAM   | 1         | 0.65%   |
| LPDDR4  | 1         | 0.65%   |
| DRAM    | 1         | 0.65%   |
| DDR     | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 151       | 98.69%  |
| Row Of Chips | 1         | 0.65%   |
| DIMM         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 63        | 36.63%  |
| 2048  | 47        | 27.33%  |
| 8192  | 43        | 25%     |
| 16384 | 10        | 5.81%   |
| 1024  | 7         | 4.07%   |
| 32768 | 2         | 1.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 31.18%  |
| 1333    | 18        | 10.59%  |
| 2667    | 16        | 9.41%   |
| 667     | 16        | 9.41%   |
| 1334    | 14        | 8.24%   |
| 1067    | 10        | 5.88%   |
| 3200    | 9         | 5.29%   |
| 2400    | 8         | 4.71%   |
| 2133    | 8         | 4.71%   |
| 800     | 6         | 3.53%   |
| Unknown | 5         | 2.94%   |
| 1867    | 3         | 1.76%   |
| 975     | 2         | 1.18%   |
| 1066    | 1         | 0.59%   |
| 533     | 1         | 0.59%   |

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
| Chicony Electronics                    | 35        | 31.53%  |
| Realtek Semiconductor                  | 10        | 9.01%   |
| Microdia                               | 9         | 8.11%   |
| Acer                                   | 9         | 8.11%   |
| Quanta                                 | 8         | 7.21%   |
| Lite-On Technology                     | 7         | 6.31%   |
| IMC Networks                           | 7         | 6.31%   |
| Sunplus Innovation Technology          | 4         | 3.6%    |
| Syntek                                 | 3         | 2.7%    |
| Suyin                                  | 3         | 2.7%    |
| Lenovo                                 | 3         | 2.7%    |
| Alcor Micro                            | 3         | 2.7%    |
| Z-Star Microelectronics                | 2         | 1.8%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.8%    |
| Silicon Motion                         | 1         | 0.9%    |
| Ricoh                                  | 1         | 0.9%    |
| Primax Electronics                     | 1         | 0.9%    |
| Luxvisions Innotech Limited            | 1         | 0.9%    |
| Importek                               | 1         | 0.9%    |
| Apple                                  | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 4.46%   |
| Chicony HD WebCam                                   | 5         | 4.46%   |
| Lite-On Integrated Camera                           | 4         | 3.57%   |
| Realtek USB Camera                                  | 3         | 2.68%   |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 2.68%   |
| Chicony Integrated Camera                           | 3         | 2.68%   |
| Chicony HD WebCam (Acer)                            | 3         | 2.68%   |
| Chicony EasyCamera                                  | 3         | 2.68%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.79%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.79%   |
| Quanta Realtek DMFT - RGB                           | 2         | 1.79%   |
| Quanta HP Webcam                                    | 2         | 1.79%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.79%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.79%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.79%   |
| Microdia Integrated Webcam                          | 2         | 1.79%   |
| Microdia Dell Laptop Integrated Webcam HD           | 2         | 1.79%   |
| Lite-On HP HD Camera                                | 2         | 1.79%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.79%   |
| IMC Networks Integrated Camera                      | 2         | 1.79%   |
| Chicony Chicony USB 2.0 Camera                      | 2         | 1.79%   |
| Acer SunplusIT INC. Integrated Camera               | 2         | 1.79%   |
| Acer Lenovo EasyCamera                              | 2         | 1.79%   |
| Acer Integrated Camera                              | 2         | 1.79%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 0.89%   |
| Z-Star Webcam                                       | 1         | 0.89%   |
| Syntek EasyCamera                                   | 1         | 0.89%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 0.89%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.89%   |
| Suyin HD Video WebCam                               | 1         | 0.89%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.89%   |
| Sunplus Integrated Camera                           | 1         | 0.89%   |
| Sunplus HP Universal Camera                         | 1         | 0.89%   |
| Sunplus HD WebCam                                   | 1         | 0.89%   |
| Silicon Motion HP Webcam-50                         | 1         | 0.89%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.89%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.89%   |
| Realtek Integrated_Webcam_8M                        | 1         | 0.89%   |
| Realtek HD WebCam                                   | 1         | 0.89%   |
| Quanta VGA WebCam                                   | 1         | 0.89%   |
| Quanta HD WebCam                                    | 1         | 0.89%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 0.89%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.89%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 0.89%   |
| Lenovo Integrated Webcam                            | 1         | 0.89%   |
| Importek TOSHIBA Web Camera                         | 1         | 0.89%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 0.89%   |
| IMC Networks USB Camera                             | 1         | 0.89%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 0.89%   |
| IMC Networks Integrated Webcam                      | 1         | 0.89%   |
| IMC Networks EasyCamera                             | 1         | 0.89%   |
| Chicony Webcam-101                                  | 1         | 0.89%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 0.89%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 0.89%   |
| Chicony USB 2.0 VGA UVC WebCam                      | 1         | 0.89%   |
| Chicony USB 2.0 Camera                              | 1         | 0.89%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 0.89%   |
| Chicony thinkpad t430s camera                       | 1         | 0.89%   |
| Chicony Lenovo EasyCamera                           | 1         | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 35.14%  |
| Upek                       | 11        | 29.73%  |
| AuthenTec                  | 6         | 16.22%  |
| STMicroelectronics         | 3         | 8.11%   |
| LighTuning Technology      | 2         | 5.41%   |
| Synaptics                  | 1         | 2.7%    |
| Shenzhen Goodix Technology | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 24.32%  |
| STMicroelectronics Fingerprint Reader                  | 3         | 8.11%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.41%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 5.41%   |
| Validity Sensors VFS491                                | 2         | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.41%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.41%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 5.41%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 5.41%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.7%    |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 2.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.7%    |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.7%    |
| AuthenTec AES2810                                      | 1         | 2.7%    |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.7%    |
| AuthenTec AES1600                                      | 1         | 2.7%    |

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
| 1     | 54        | 34.18%  |
| 2     | 48        | 30.38%  |
| 0     | 27        | 17.09%  |
| 3     | 22        | 13.92%  |
| 4     | 7         | 4.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 100       | 42.92%  |
| Net/wireless             | 42        | 18.03%  |
| Fingerprint reader       | 36        | 15.45%  |
| Bluetooth                | 27        | 11.59%  |
| Card reader              | 24        | 10.3%   |
| Storage                  | 2         | 0.86%   |
| Sound                    | 1         | 0.43%   |
| Network                  | 1         | 0.43%   |

