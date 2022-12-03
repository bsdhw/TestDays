BSD in Germany - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for BSD in Germany.

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

Total: 321

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude D610               | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Deciso        | NetBoard-A20                | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Deciso        | NetBoard-A10                | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Acer          | JM11-MS                     | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Dell          | Latitude 5591               | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Deciso        | Netboard A20                | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Samsung       | NC210/NC110                 | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Shuttle       | DS437                       | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Deciso        | NetBoard-A10                | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| HP            | 255 G8 Notebook PC          | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Deciso        | OPNsense Appliance          | [70c9fd07ac](https://bsd-hardware.info/?probe=70c9fd07ac) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Acer          | Aspire E1-570G              | [7fd31252a2](https://bsd-hardware.info/?probe=7fd31252a2) | May 04, 2022 |
| HP            | EliteBook 820 G2            | [3997ff79e4](https://bsd-hardware.info/?probe=3997ff79e4) | May 03, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [22b192afca](https://bsd-hardware.info/?probe=22b192afca) | Apr 28, 2022 |
| Apple         | MacBookPro3,1               | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| AMI           | Intel                       | [db87d63d35](https://bsd-hardware.info/?probe=db87d63d35) | Apr 15, 2022 |
| AMI           | Intel                       | [8dc710d126](https://bsd-hardware.info/?probe=8dc710d126) | Apr 14, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Deciso        | Netboard A20                | [8ded6d9af6](https://bsd-hardware.info/?probe=8ded6d9af6) | Mar 21, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| AEWIN         | CB-7979                     | [ec1e865bbd](https://bsd-hardware.info/?probe=ec1e865bbd) | Mar 07, 2022 |
| Dell          | Latitude 5591               | [d4d653fba8](https://bsd-hardware.info/?probe=d4d653fba8) | Feb 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| MiTAC         | 5033                        | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Apple         | MacBookPro4,1               | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Apple         | MacBookPro11,4              | [6d580e8270](https://bsd-hardware.info/?probe=6d580e8270) | Jan 21, 2022 |
| Dell          | Latitude E6540              | [f13972c935](https://bsd-hardware.info/?probe=f13972c935) | Jan 21, 2022 |
| Fujitsu       | CELSIUS H780                | [a173366c78](https://bsd-hardware.info/?probe=a173366c78) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c36023a724](https://bsd-hardware.info/?probe=c36023a724) | Jan 17, 2022 |
| Acer          | TravelMate 8481TG           | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| MSI           | GT75VR 7RF                  | [cca6cc3c0b](https://bsd-hardware.info/?probe=cca6cc3c0b) | Jan 07, 2022 |
| Apple         | MacBook5,1                  | [f0aeeb7f3c](https://bsd-hardware.info/?probe=f0aeeb7f3c) | Jan 05, 2022 |
| Dell          | Latitude 3400               | [41bf32aff1](https://bsd-hardware.info/?probe=41bf32aff1) | Jan 02, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [42b4bcbcc2](https://bsd-hardware.info/?probe=42b4bcbcc2) | Dec 27, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [695d7201d4](https://bsd-hardware.info/?probe=695d7201d4) | Dec 27, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| Unknown       | Unknown                     | [aa872042e3](https://bsd-hardware.info/?probe=aa872042e3) | Dec 15, 2021 |
| ASUSTek       | 1005P                       | [4c43bd561f](https://bsd-hardware.info/?probe=4c43bd561f) | Dec 14, 2021 |
| Intel         | SharkBay Platform           | [383d1e31c9](https://bsd-hardware.info/?probe=383d1e31c9) | Dec 14, 2021 |
| Unknown       | Unknown                     | [8c3ba89ddd](https://bsd-hardware.info/?probe=8c3ba89ddd) | Dec 12, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | [0b6ab3ba1b](https://bsd-hardware.info/?probe=0b6ab3ba1b) | Dec 09, 2021 |
| Dell          | Precision M4300             | [08fe78379d](https://bsd-hardware.info/?probe=08fe78379d) | Dec 08, 2021 |
| Deciso        | Netboard A20                | [593d123f0c](https://bsd-hardware.info/?probe=593d123f0c) | Dec 07, 2021 |
| Lenovo        | ThinkPad T430s 2356JH4      | [b1377872cd](https://bsd-hardware.info/?probe=b1377872cd) | Dec 03, 2021 |
| Unknown       | Unknown                     | [5d1a3bbfe3](https://bsd-hardware.info/?probe=5d1a3bbfe3) | Nov 30, 2021 |
| Shuttle       | DS437                       | [b5d1bcffdb](https://bsd-hardware.info/?probe=b5d1bcffdb) | Nov 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Shuttle       | DS437                       | [687fc514ba](https://bsd-hardware.info/?probe=687fc514ba) | Nov 27, 2021 |
| Shuttle       | DS437                       | [e65a62f5a5](https://bsd-hardware.info/?probe=e65a62f5a5) | Nov 27, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [8b178d13c7](https://bsd-hardware.info/?probe=8b178d13c7) | Nov 22, 2021 |
| Alienware     | m15                         | [20afd3904b](https://bsd-hardware.info/?probe=20afd3904b) | Nov 21, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [d8628f80c0](https://bsd-hardware.info/?probe=d8628f80c0) | Nov 19, 2021 |
| Shuttle       | DS437                       | [0dc3d4619e](https://bsd-hardware.info/?probe=0dc3d4619e) | Nov 17, 2021 |
| Acer          | TravelMate B117-M           | [4f02660d9c](https://bsd-hardware.info/?probe=4f02660d9c) | Nov 14, 2021 |
| Lenovo        | ThinkPad W520 4276CTO       | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| Lenovo        | ThinkPad T420 4180EE8       | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| BESSTAR Te... | U820                        | [3bd9cd5b98](https://bsd-hardware.info/?probe=3bd9cd5b98) | Nov 03, 2021 |
| Lenovo        | IdeaPad Z360                | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| BESSTAR Te... | U820                        | [1a39d8a6e3](https://bsd-hardware.info/?probe=1a39d8a6e3) | Nov 02, 2021 |
| Apple         | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d910c79d75](https://bsd-hardware.info/?probe=d910c79d75) | Oct 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d8a6d0daf3](https://bsd-hardware.info/?probe=d8a6d0daf3) | Oct 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [b4ba704356](https://bsd-hardware.info/?probe=b4ba704356) | Oct 17, 2021 |
| Lenovo        | ThinkPad X230 23254G7       | [06c6a282ca](https://bsd-hardware.info/?probe=06c6a282ca) | Oct 16, 2021 |
| Dell          | Inspiron 3493               | [ed41c18cfc](https://bsd-hardware.info/?probe=ed41c18cfc) | Oct 16, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [be42957ecd](https://bsd-hardware.info/?probe=be42957ecd) | Oct 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5b08c1de3d](https://bsd-hardware.info/?probe=5b08c1de3d) | Oct 06, 2021 |
| ASUSTek       | UX305FA                     | [decf219ff2](https://bsd-hardware.info/?probe=decf219ff2) | Sep 30, 2021 |
| Lenovo        | ThinkPad X230 2325O76       | [b8729e39e1](https://bsd-hardware.info/?probe=b8729e39e1) | Sep 29, 2021 |
| Unknown       | Unknown                     | [27f807ae11](https://bsd-hardware.info/?probe=27f807ae11) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d9762d6c2d](https://bsd-hardware.info/?probe=d9762d6c2d) | Sep 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0d00ce5de9](https://bsd-hardware.info/?probe=0d00ce5de9) | Sep 22, 2021 |
| Lenovo        | ThinkPad T400 6474E18       | [2dd5b5869f](https://bsd-hardware.info/?probe=2dd5b5869f) | Sep 13, 2021 |
| Dell          | XPS 15 9570                 | [ee8980fec1](https://bsd-hardware.info/?probe=ee8980fec1) | Sep 07, 2021 |
| Dell          | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell          | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Apple         | MacBookAir7,2               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
| Dell          | Latitude 5591               | [f0ee8a7da0](https://bsd-hardware.info/?probe=f0ee8a7da0) | Aug 25, 2021 |
| Acer          | Aspire ES1-132              | [43c82b1b16](https://bsd-hardware.info/?probe=43c82b1b16) | Aug 22, 2021 |
| Insyde        | Braswell                    | [6c8e94b016](https://bsd-hardware.info/?probe=6c8e94b016) | Aug 19, 2021 |
| Dell          | Latitude 5591               | [c21b6fde68](https://bsd-hardware.info/?probe=c21b6fde68) | Aug 12, 2021 |
| Deciso        | Netboard A20                | [5be914e123](https://bsd-hardware.info/?probe=5be914e123) | Aug 03, 2021 |
| Lenovo        | ThinkPad L512 44444XG       | [a6c8fbcb20](https://bsd-hardware.info/?probe=a6c8fbcb20) | Aug 01, 2021 |
| Sony          | VPCEJ1E1E                   | [c471fb3f82](https://bsd-hardware.info/?probe=c471fb3f82) | Aug 01, 2021 |
| Lenovo        | G550 2958                   | [86880c29cf](https://bsd-hardware.info/?probe=86880c29cf) | Jul 31, 2021 |
| Lenovo        | G550 2958                   | [4fe522eaf3](https://bsd-hardware.info/?probe=4fe522eaf3) | Jul 31, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK E780               | [71b543094c](https://bsd-hardware.info/?probe=71b543094c) | Jul 22, 2021 |
| MSI           | MS-1613                     | [795e61c1a3](https://bsd-hardware.info/?probe=795e61c1a3) | Jul 21, 2021 |
| Unknown       | Unknown                     | [a37195bcb8](https://bsd-hardware.info/?probe=a37195bcb8) | Jul 15, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [a8c497b58b](https://bsd-hardware.info/?probe=a8c497b58b) | Jul 09, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | [25e208721d](https://bsd-hardware.info/?probe=25e208721d) | Jul 02, 2021 |
| Fujitsu       | LIFEBOOK E780               | [2e8c2afe50](https://bsd-hardware.info/?probe=2e8c2afe50) | Jun 20, 2021 |
| Apple         | MacBookAir6,1               | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| HP            | ProBook 640 G1              | [937ed102d1](https://bsd-hardware.info/?probe=937ed102d1) | Jun 12, 2021 |
| ASUSTek       | UX330UAK                    | [430c90b88d](https://bsd-hardware.info/?probe=430c90b88d) | Jun 12, 2021 |
| Unknown       | Unknown                     | [1f2d078d2e](https://bsd-hardware.info/?probe=1f2d078d2e) | Jun 01, 2021 |
| Deciso        | Netboard A20                | [f4a0f0941b](https://bsd-hardware.info/?probe=f4a0f0941b) | May 26, 2021 |
| Unknown       | Unknown                     | [b4b6cfff1f](https://bsd-hardware.info/?probe=b4b6cfff1f) | May 24, 2021 |
| Lenovo        | ThinkPad SL510 28477MG      | [bdbd2d0a05](https://bsd-hardware.info/?probe=bdbd2d0a05) | May 20, 2021 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [2be8cf963c](https://bsd-hardware.info/?probe=2be8cf963c) | May 02, 2021 |
| HP            | Compaq Presario CQ71        | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [6e8891f184](https://bsd-hardware.info/?probe=6e8891f184) | Apr 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [7ec73fe36d](https://bsd-hardware.info/?probe=7ec73fe36d) | Apr 23, 2021 |
| Lenovo        | ThinkPad W541 20EGS04800    | [91d2cd471c](https://bsd-hardware.info/?probe=91d2cd471c) | Apr 16, 2021 |
| Clevo         | W55xEU                      | [229587fbd5](https://bsd-hardware.info/?probe=229587fbd5) | Apr 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [403a237513](https://bsd-hardware.info/?probe=403a237513) | Apr 14, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Apple         | MacBookPro8,1               | [5d3d014284](https://bsd-hardware.info/?probe=5d3d014284) | Apr 12, 2021 |
| Apple         | MacBookPro8,1               | [ffcc46ea0b](https://bsd-hardware.info/?probe=ffcc46ea0b) | Apr 12, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bd88655975](https://bsd-hardware.info/?probe=bd88655975) | Apr 10, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2376cf30b2](https://bsd-hardware.info/?probe=2376cf30b2) | Apr 03, 2021 |
| Dell          | Latitude 5591               | [dadf2c296f](https://bsd-hardware.info/?probe=dadf2c296f) | Mar 30, 2021 |
| TUXEDO        | Unknown                     | [35aa6590c6](https://bsd-hardware.info/?probe=35aa6590c6) | Mar 29, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c5e824b558](https://bsd-hardware.info/?probe=c5e824b558) | Mar 29, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [3e9aab9818](https://bsd-hardware.info/?probe=3e9aab9818) | Mar 25, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [dc40b42864](https://bsd-hardware.info/?probe=dc40b42864) | Mar 22, 2021 |
| Packard Be... | EasyNote MH36               | [2a98cae4e8](https://bsd-hardware.info/?probe=2a98cae4e8) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [bcb99d0f09](https://bsd-hardware.info/?probe=bcb99d0f09) | Mar 13, 2021 |
| Fujitsu       | LIFEBOOK A555               | [ee894449af](https://bsd-hardware.info/?probe=ee894449af) | Mar 13, 2021 |
| Acer          | Aspire 4810T                | [14af887195](https://bsd-hardware.info/?probe=14af887195) | Mar 11, 2021 |
| HP            | EliteBook 2760p             | [5707fc27ce](https://bsd-hardware.info/?probe=5707fc27ce) | Mar 11, 2021 |
| Clevo         | W55xEU                      | [e51ee3b14c](https://bsd-hardware.info/?probe=e51ee3b14c) | Mar 08, 2021 |
| Dell          | Latitude E6500              | [d25dacc162](https://bsd-hardware.info/?probe=d25dacc162) | Mar 07, 2021 |
| Clevo         | W55xEU                      | [d874753fe2](https://bsd-hardware.info/?probe=d874753fe2) | Mar 07, 2021 |
| Lenovo        | 3000 N200 0769AP2           | [6b81593de9](https://bsd-hardware.info/?probe=6b81593de9) | Mar 06, 2021 |
| Dell          | Latitude 5591               | [e570513187](https://bsd-hardware.info/?probe=e570513187) | Mar 05, 2021 |
| Dell          | Latitude 5400               | [b9d1f08bcf](https://bsd-hardware.info/?probe=b9d1f08bcf) | Mar 04, 2021 |
| Fujitsu       | LIFEBOOK E754               | [d3d033f879](https://bsd-hardware.info/?probe=d3d033f879) | Mar 03, 2021 |
| Fujitsu       | LIFEBOOK E736               | [845c584693](https://bsd-hardware.info/?probe=845c584693) | Mar 03, 2021 |
| Acer          | Extensa 5630                | [6a1b523efb](https://bsd-hardware.info/?probe=6a1b523efb) | Mar 03, 2021 |
| Hampoo        | B3W6_NA123C Reserved        | [bc138c0580](https://bsd-hardware.info/?probe=bc138c0580) | Feb 27, 2021 |
| Fujitsu       | LIFEBOOK E780               | [57506cbdcf](https://bsd-hardware.info/?probe=57506cbdcf) | Feb 26, 2021 |
| Dell          | Latitude 5591               | [0424bf31ca](https://bsd-hardware.info/?probe=0424bf31ca) | Feb 25, 2021 |
| Lenovo        | ThinkPad T520 4242A16       | [49dacee7d0](https://bsd-hardware.info/?probe=49dacee7d0) | Feb 23, 2021 |
| Lenovo        | Z50-70 20354                | [d3d9dc620f](https://bsd-hardware.info/?probe=d3d9dc620f) | Feb 23, 2021 |
| Unknown       | Unknown                     | [eaa6a36e6e](https://bsd-hardware.info/?probe=eaa6a36e6e) | Feb 22, 2021 |
| Lenovo        | ThinkPad T450 20BUS08800    | [d783b3b4dd](https://bsd-hardware.info/?probe=d783b3b4dd) | Feb 22, 2021 |
| Dell          | Latitude 5424 Rugged        | [b94ae57278](https://bsd-hardware.info/?probe=b94ae57278) | Feb 22, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7f8c483af1](https://bsd-hardware.info/?probe=7f8c483af1) | Feb 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a9604cfdb8](https://bsd-hardware.info/?probe=a9604cfdb8) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [893c17f73a](https://bsd-hardware.info/?probe=893c17f73a) | Feb 19, 2021 |
| Lenovo        | V130-15IKB 81HN             | [d0f504fad2](https://bsd-hardware.info/?probe=d0f504fad2) | Feb 19, 2021 |
| Lenovo        | ZIUS6                       | [1c239bac92](https://bsd-hardware.info/?probe=1c239bac92) | Feb 18, 2021 |
| Clevo         | W55xEU                      | [a66041bae0](https://bsd-hardware.info/?probe=a66041bae0) | Feb 17, 2021 |
| Dell          | Latitude E6330              | [abe1869a95](https://bsd-hardware.info/?probe=abe1869a95) | Feb 17, 2021 |
| Lenovo        | U310                        | [ccec69b736](https://bsd-hardware.info/?probe=ccec69b736) | Feb 16, 2021 |
| Lenovo        | U310                        | [83805a17c5](https://bsd-hardware.info/?probe=83805a17c5) | Feb 16, 2021 |
| Lenovo        | U310                        | [111385095d](https://bsd-hardware.info/?probe=111385095d) | Feb 16, 2021 |
| Apple         | MacBookAir4,2               | [7d8419c918](https://bsd-hardware.info/?probe=7d8419c918) | Feb 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [19f307ff6d](https://bsd-hardware.info/?probe=19f307ff6d) | Feb 16, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5a393bc680](https://bsd-hardware.info/?probe=5a393bc680) | Feb 15, 2021 |
| Medion        | P6812                       | [c2c592bca8](https://bsd-hardware.info/?probe=c2c592bca8) | Feb 15, 2021 |
| Medion        | P6812                       | [afa43a6aab](https://bsd-hardware.info/?probe=afa43a6aab) | Feb 15, 2021 |
| Fujitsu       | LIFEBOOK E780               | [0f5e891a5d](https://bsd-hardware.info/?probe=0f5e891a5d) | Feb 14, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [6da4116499](https://bsd-hardware.info/?probe=6da4116499) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [d212f58dd2](https://bsd-hardware.info/?probe=d212f58dd2) | Feb 13, 2021 |
| Dell          | Latitude 7380               | [1aa2a3a541](https://bsd-hardware.info/?probe=1aa2a3a541) | Feb 12, 2021 |
| Dell          | Latitude 7380               | [4814701c0e](https://bsd-hardware.info/?probe=4814701c0e) | Feb 12, 2021 |
| Clevo         | W55xEU                      | [796ad51947](https://bsd-hardware.info/?probe=796ad51947) | Feb 11, 2021 |
| Clevo         | W55xEU                      | [c28a6397b5](https://bsd-hardware.info/?probe=c28a6397b5) | Feb 11, 2021 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [ca369843a9](https://bsd-hardware.info/?probe=ca369843a9) | Feb 09, 2021 |
| Lenovo        | ThinkPad X220 42915CG       | [0bc3ba767e](https://bsd-hardware.info/?probe=0bc3ba767e) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [5d6a8a51d0](https://bsd-hardware.info/?probe=5d6a8a51d0) | Feb 06, 2021 |
| Acer          | Extensa 5220                | [c443decee1](https://bsd-hardware.info/?probe=c443decee1) | Feb 06, 2021 |
| Fujitsu       | LIFEBOOK E753               | [37245aca21](https://bsd-hardware.info/?probe=37245aca21) | Feb 03, 2021 |
| Unknown       | Unknown                     | [95e264ef56](https://bsd-hardware.info/?probe=95e264ef56) | Feb 02, 2021 |
| Lenovo        | ThinkPad SL510 2847Q9G      | [12e9632d4b](https://bsd-hardware.info/?probe=12e9632d4b) | Jan 31, 2021 |
| Clevo         | W55xEU                      | [ecacada83f](https://bsd-hardware.info/?probe=ecacada83f) | Jan 29, 2021 |
| Clevo         | W55xEU                      | [e17285783e](https://bsd-hardware.info/?probe=e17285783e) | Jan 29, 2021 |
| Fujitsu       | LIFEBOOK E753               | [9a615ebaf8](https://bsd-hardware.info/?probe=9a615ebaf8) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [ecf07ad5fe](https://bsd-hardware.info/?probe=ecf07ad5fe) | Jan 24, 2021 |
| HP            | Laptop 17-ca1xxx            | [fb318623f3](https://bsd-hardware.info/?probe=fb318623f3) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [97a89d4eb0](https://bsd-hardware.info/?probe=97a89d4eb0) | Jan 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [806c954739](https://bsd-hardware.info/?probe=806c954739) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5f469ceeb9](https://bsd-hardware.info/?probe=5f469ceeb9) | Jan 20, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [5359b4dee9](https://bsd-hardware.info/?probe=5359b4dee9) | Jan 18, 2021 |
| Dell          | Inspiron 3542               | [3c41c474ad](https://bsd-hardware.info/?probe=3c41c474ad) | Jan 16, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [a0b1fd0ca5](https://bsd-hardware.info/?probe=a0b1fd0ca5) | Jan 12, 2021 |
| Lenovo        | ThinkPad X201 3626HMG       | [f384858fd6](https://bsd-hardware.info/?probe=f384858fd6) | Jan 12, 2021 |
| Dell          | XPS 15 7590                 | [6cd195aa69](https://bsd-hardware.info/?probe=6cd195aa69) | Jan 05, 2021 |
| Dell          | XPS 15 7590                 | [50ca36db01](https://bsd-hardware.info/?probe=50ca36db01) | Jan 05, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [1ffaf5420c](https://bsd-hardware.info/?probe=1ffaf5420c) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [1b0cc7506e](https://bsd-hardware.info/?probe=1b0cc7506e) | Jan 03, 2021 |
| Apple         | MacBookPro10,2              | [e43a26be8d](https://bsd-hardware.info/?probe=e43a26be8d) | Jan 01, 2021 |
| HP            | Laptop 14-dk0xxx            | [5cd8e23152](https://bsd-hardware.info/?probe=5cd8e23152) | Dec 26, 2020 |
| HP            | Laptop 14-dk0xxx            | [fdbd71db5e](https://bsd-hardware.info/?probe=fdbd71db5e) | Dec 26, 2020 |
| HP            | 655                         | [ae2de01d19](https://bsd-hardware.info/?probe=ae2de01d19) | Dec 26, 2020 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [0f9b8d2e3b](https://bsd-hardware.info/?probe=0f9b8d2e3b) | Dec 22, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [7e80ced15e](https://bsd-hardware.info/?probe=7e80ced15e) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [d2e3890c19](https://bsd-hardware.info/?probe=d2e3890c19) | Dec 16, 2020 |
| Lenovo        | ThinkPad X230 23244A9       | [7aaf6835e2](https://bsd-hardware.info/?probe=7aaf6835e2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [1952513db8](https://bsd-hardware.info/?probe=1952513db8) | Dec 15, 2020 |
| Lenovo        | ThinkPad T420 4180AJ3       | [683eca8c23](https://bsd-hardware.info/?probe=683eca8c23) | Dec 11, 2020 |
| Lenovo        | ThinkPad X250 20CLS02000    | [cbd9f8a13c](https://bsd-hardware.info/?probe=cbd9f8a13c) | Dec 09, 2020 |
| Dell          | Latitude 2100               | [899ce6ffe4](https://bsd-hardware.info/?probe=899ce6ffe4) | Dec 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [16206c4970](https://bsd-hardware.info/?probe=16206c4970) | Dec 07, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [c811e29e6c](https://bsd-hardware.info/?probe=c811e29e6c) | Nov 30, 2020 |
| Dell          | Latitude E6440              | [f9278127a1](https://bsd-hardware.info/?probe=f9278127a1) | Nov 27, 2020 |
| Lenovo        | ThinkPad T420 4236N2G       | [1565d5d570](https://bsd-hardware.info/?probe=1565d5d570) | Nov 24, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0738824c51](https://bsd-hardware.info/?probe=0738824c51) | Nov 22, 2020 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [1b7b105e5c](https://bsd-hardware.info/?probe=1b7b105e5c) | Nov 08, 2020 |
| Lenovo        | V130-15IKB 81HN             | [d20a8be7d4](https://bsd-hardware.info/?probe=d20a8be7d4) | Nov 03, 2020 |
| Lenovo        | ThinkPad T520 4243FS9       | [242cd8a6e7](https://bsd-hardware.info/?probe=242cd8a6e7) | Nov 02, 2020 |
| Dell          | Precision M4800             | [8afb8e7443](https://bsd-hardware.info/?probe=8afb8e7443) | Oct 29, 2020 |
| Schenker      | N13xWU                      | [c23a22a72d](https://bsd-hardware.info/?probe=c23a22a72d) | Oct 29, 2020 |
| HUAWEI        | MACH-WX9                    | [2a1b806f39](https://bsd-hardware.info/?probe=2a1b806f39) | Oct 29, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [26c750117f](https://bsd-hardware.info/?probe=26c750117f) | Oct 28, 2020 |
| IBM           | ThinkPad X41 2525F8G        | [c58f946d2a](https://bsd-hardware.info/?probe=c58f946d2a) | Oct 22, 2020 |
| Lenovo        | ThinkPad Edge E531 68852... | [e6b45d36e5](https://bsd-hardware.info/?probe=e6b45d36e5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [fdc7310ca7](https://bsd-hardware.info/?probe=fdc7310ca7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [857f9809b7](https://bsd-hardware.info/?probe=857f9809b7) | Oct 19, 2020 |
| Lenovo        | ThinkPad X270 20HNA004CD    | [79160b17c4](https://bsd-hardware.info/?probe=79160b17c4) | Oct 19, 2020 |
| Apple         | PowerBook6,7                | [7ac5f5530a](https://bsd-hardware.info/?probe=7ac5f5530a) | Oct 19, 2020 |
| Alienware     | m15                         | [8f8cf7d956](https://bsd-hardware.info/?probe=8f8cf7d956) | Oct 19, 2020 |
| Unknown       | Unknown                     | [fd77b4658f](https://bsd-hardware.info/?probe=fd77b4658f) | Oct 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee1f866775](https://bsd-hardware.info/?probe=ee1f866775) | Oct 13, 2020 |
| Lenovo        | ThinkPad X220 4291OQ6       | [ed0340e006](https://bsd-hardware.info/?probe=ed0340e006) | Oct 04, 2020 |
| ASUSTek       | N56VJ                       | [9fb23e0394](https://bsd-hardware.info/?probe=9fb23e0394) | Sep 22, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [53e545fcb9](https://bsd-hardware.info/?probe=53e545fcb9) | Sep 17, 2020 |
| Acer          | TravelMate 270              | [56a5581907](https://bsd-hardware.info/?probe=56a5581907) | Sep 17, 2020 |
| HP            | nx9010 (DN775T)             | [b7c0cb252f](https://bsd-hardware.info/?probe=b7c0cb252f) | Sep 16, 2020 |
| Lenovo        | ThinkPad X61 7673AG4        | [650e00a14a](https://bsd-hardware.info/?probe=650e00a14a) | Sep 14, 2020 |
| Panasonic     | CF-C1BD06EFG                | [3e876bada1](https://bsd-hardware.info/?probe=3e876bada1) | Sep 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| HKC           | NT11T                       | [1988c603c9](https://bsd-hardware.info/?probe=1988c603c9) | Aug 22, 2020 |
| Acer          | E1-510                      | [c65d08aa57](https://bsd-hardware.info/?probe=c65d08aa57) | Aug 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3032cd9409](https://bsd-hardware.info/?probe=3032cd9409) | Aug 20, 2020 |
| HP            | Compaq Presario CQ71        | [b34e70d7d4](https://bsd-hardware.info/?probe=b34e70d7d4) | Aug 20, 2020 |
| Lenovo        | ThinkPad T450 20BUS08800    | [359cd8cf1b](https://bsd-hardware.info/?probe=359cd8cf1b) | Aug 11, 2020 |
| Sony          | VGN-SZ3VWP_X                | [ace534d784](https://bsd-hardware.info/?probe=ace534d784) | Aug 10, 2020 |
| HP            | ZBook 15 G4                 | [a8953b4964](https://bsd-hardware.info/?probe=a8953b4964) | Aug 03, 2020 |
| HP            | ZBook 15 G4                 | [a97053c5d4](https://bsd-hardware.info/?probe=a97053c5d4) | Aug 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [20f3e760eb](https://bsd-hardware.info/?probe=20f3e760eb) | Aug 03, 2020 |
| Lenovo        | ThinkPad T480 20L5000BMD    | [6259248178](https://bsd-hardware.info/?probe=6259248178) | Jul 31, 2020 |
| Dell          | Precision M4800             | [adbaced1b1](https://bsd-hardware.info/?probe=adbaced1b1) | Jul 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [ac13b0591f](https://bsd-hardware.info/?probe=ac13b0591f) | Jul 27, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [2e8c0ef401](https://bsd-hardware.info/?probe=2e8c0ef401) | Jul 21, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [ff2a0edd8a](https://bsd-hardware.info/?probe=ff2a0edd8a) | Jul 21, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [de1425a34c](https://bsd-hardware.info/?probe=de1425a34c) | Jul 19, 2020 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5b8fe1f4f7](https://bsd-hardware.info/?probe=5b8fe1f4f7) | Jul 19, 2020 |
| Schenker      | N13xWU                      | [225afaa47f](https://bsd-hardware.info/?probe=225afaa47f) | Jul 15, 2020 |
| Dell          | Latitude E6440              | [a59bcf04fe](https://bsd-hardware.info/?probe=a59bcf04fe) | Jul 13, 2020 |
| Dell          | Inspiron 7773               | [0b335f5918](https://bsd-hardware.info/?probe=0b335f5918) | Jul 12, 2020 |
| Schenker      | SCHENKER_COMPACT15_17_SC... | [95434cbf80](https://bsd-hardware.info/?probe=95434cbf80) | Jul 07, 2020 |
| Lenovo        | G50-45 80E3                 | [56d1b97dc1](https://bsd-hardware.info/?probe=56d1b97dc1) | Jun 11, 2020 |
| Lenovo        | ThinkPad T450s 20BWS16X0... | [f83f765ab3](https://bsd-hardware.info/?probe=f83f765ab3) | Jun 06, 2020 |
| Schenker      | SCHENKER_COMPACT15_17_SC... | [96fcd8fc28](https://bsd-hardware.info/?probe=96fcd8fc28) | May 28, 2020 |
| Fujitsu       | LIFEBOOK A357               | [b02640458b](https://bsd-hardware.info/?probe=b02640458b) | May 26, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0087b62853](https://bsd-hardware.info/?probe=0087b62853) | May 25, 2020 |
| HP            | EliteBook 8560w             | [c240e3a1ea](https://bsd-hardware.info/?probe=c240e3a1ea) | May 25, 2020 |
| TUXEDO        | N13xWU                      | [9649f2d700](https://bsd-hardware.info/?probe=9649f2d700) | May 25, 2020 |
| TUXEDO        | N13xWU                      | [7230dca5a8](https://bsd-hardware.info/?probe=7230dca5a8) | May 25, 2020 |
| Sony          | VPCM12M1E                   | [1e5d0a4d7a](https://bsd-hardware.info/?probe=1e5d0a4d7a) | May 25, 2020 |
| Lenovo        | ThinkPad T410s 291245G      | [6394ae37a8](https://bsd-hardware.info/?probe=6394ae37a8) | May 25, 2020 |
| Lenovo        | ThinkPad T410s 291245G      | [b453d7ac18](https://bsd-hardware.info/?probe=b453d7ac18) | May 25, 2020 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [85567202a8](https://bsd-hardware.info/?probe=85567202a8) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.4.0    | 14        | 5.41%   |
| OpenBSD 6.8          | 12        | 4.63%   |
| helloSystem 0.5.0    | 12        | 4.63%   |
| helloSystem 0.7.0    | 11        | 4.25%   |
| FreeBSD 12.2         | 10        | 3.86%   |
| OpenBSD 7.0          | 8         | 3.09%   |
| FreeBSD 13.0-p4      | 7         | 2.7%    |
| OpenBSD 6.9          | 6         | 2.32%   |
| helloSystem 0.6.0    | 6         | 2.32%   |
| GhostBSD 22.01.12    | 6         | 2.32%   |
| FreeBSD 14.0-CURRENT | 6         | 2.32%   |
| FreeBSD 12.1-p10     | 6         | 2.32%   |
| OPNsense 21.7.6      | 5         | 1.93%   |
| OpenBSD 6.7          | 5         | 1.93%   |
| NomadBSD 5806f915    | 5         | 1.93%   |
| helloSystem 0.8.0    | 5         | 1.93%   |
| GhostBSD 21.08.27    | 5         | 1.93%   |
| FreeBSD 13.0-CURRENT | 5         | 1.93%   |
| FreeBSD 13.0         | 5         | 1.93%   |
| FreeBSD 12.2-p2      | 5         | 1.93%   |
| FreeBSD 12.1-STABLE  | 5         | 1.93%   |
| OPNsense 21.1.2      | 4         | 1.54%   |
| NomadBSD 1.4         | 4         | 1.54%   |
| GhostBSD 20.04.02    | 4         | 1.54%   |
| FreeBSD 12.1-p5      | 4         | 1.54%   |
| FreeBSD 12.1         | 4         | 1.54%   |
| OPNsense 22.1.6      | 3         | 1.16%   |
| NomadBSD 1.4-RC1     | 3         | 1.16%   |
| FreeBSD 13.1-p2      | 3         | 1.16%   |
| FreeBSD 12.2-p3      | 3         | 1.16%   |
| FreeBSD 12.1-p7      | 3         | 1.16%   |
| OPNsense 22.7.6      | 2         | 0.77%   |
| OPNsense 22.4        | 2         | 0.77%   |
| OPNsense 21.7.1      | 2         | 0.77%   |
| OPNsense 21.1.8      | 2         | 0.77%   |
| OPNsense 21.1.6      | 2         | 0.77%   |
| OPNsense 21.1.5      | 2         | 0.77%   |
| OPNsense 21.1.3      | 2         | 0.77%   |
| OPNsense 21.1.1      | 2         | 0.77%   |
| OPNsense 21.1        | 2         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 74        | 33.04%  |
| helloSystem | 48        | 21.43%  |
| OPNsense    | 39        | 17.41%  |
| OpenBSD     | 30        | 13.39%  |
| GhostBSD    | 15        | 6.7%    |
| NomadBSD    | 14        | 6.25%   |
| NetBSD      | 1         | 0.45%   |
| MidnightBSD | 1         | 0.45%   |
| HardenedBSD | 1         | 0.45%   |
| FuryBSD     | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 207       | 95.39%  |
| i386   | 9         | 4.15%   |
| macppc | 1         | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 53        | 23.25%  |
| helloDesktop | 51        | 22.37%  |
| fvwm         | 25        | 10.96%  |
| MATE         | 22        | 9.65%   |
| XFCE         | 19        | 8.33%   |
| GNOME        | 13        | 5.7%    |
| Openbox      | 11        | 4.82%   |
| KDE5         | 11        | 4.82%   |
| TWM          | 9         | 3.95%   |
| i3           | 4         | 1.75%   |
| AwesomeWM    | 4         | 1.75%   |
| Cinnamon     | 2         | 0.88%   |
| Picom        | 1         | 0.44%   |
| LXQt         | 1         | 0.44%   |
| LXDE         | 1         | 0.44%   |
| iwm          | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 160       | 73.06%  |
| Console | 58        | 26.48%  |
| Wayland | 1         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 97        | 42.17%  |
| SLiM    | 71        | 30.87%  |
| LightDM | 21        | 9.13%   |
| SDDM    | 15        | 6.52%   |
| XDM     | 12        | 5.22%   |
| GDM     | 11        | 4.78%   |
| Ly      | 3         | 1.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 95        | 41.48%  |
| en_US            | 58        | 25.33%  |
| C                | 33        | 14.41%  |
| de_DE            | 32        | 13.97%  |
| en_GB            | 5         | 2.18%   |
| de_DE.ISO8859-1  | 2         | 0.87%   |
| pl_PL            | 1         | 0.44%   |
| en_IE            | 1         | 0.44%   |
| en_CA            | 1         | 0.44%   |
| de_DE.ISO8859-15 | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 170       | 76.92%  |
| BIOS | 51        | 23.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 112       | 50.22%  |
| Ufs    | 73        | 32.74%  |
| Ffs    | 30        | 13.45%  |
| Cd9660 | 8         | 3.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 196       | 89.09%  |
| MBR     | 23        | 10.45%  |
| Unknown | 1         | 0.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 77        | 35.48%  |
| Dell                | 24        | 11.06%  |
| Hewlett-Packard     | 13        | 5.99%   |
| Apple               | 13        | 5.99%   |
| Deciso              | 11        | 5.07%   |
| Acer                | 11        | 5.07%   |
| Fujitsu             | 10        | 4.61%   |
| Unknown             | 9         | 4.15%   |
| ASUSTek Computer    | 8         | 3.69%   |
| TUXEDO              | 6         | 2.76%   |
| Sony                | 3         | 1.38%   |
| Notebook            | 3         | 1.38%   |
| Shuttle             | 2         | 0.92%   |
| Schenker            | 2         | 0.92%   |
| MSI                 | 2         | 0.92%   |
| IBM                 | 2         | 0.92%   |
| Gigabyte Technology | 2         | 0.92%   |
| Toshiba             | 1         | 0.46%   |
| Tactus              | 1         | 0.46%   |
| Samsung Electronics | 1         | 0.46%   |
| Panasonic           | 1         | 0.46%   |
| Packard Bell        | 1         | 0.46%   |
| MiTAC               | 1         | 0.46%   |
| Medion              | 1         | 0.46%   |
| Intel               | 1         | 0.46%   |
| Insyde              | 1         | 0.46%   |
| HUAWEI              | 1         | 0.46%   |
| HKC                 | 1         | 0.46%   |
| Hampoo              | 1         | 0.46%   |
| GPD                 | 1         | 0.46%   |
| Google              | 1         | 0.46%   |
| Clevo               | 1         | 0.46%   |
| BESSTAR Tech        | 1         | 0.46%   |
| AMI                 | 1         | 0.46%   |
| Alienware           | 1         | 0.46%   |
| AEWIN               | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 4.61%   |
| Deciso Netboard A20                        | 5         | 2.3%    |
| TUXEDO Pulse 14 Gen1                       | 2         | 0.92%   |
| Shuttle DS437                              | 2         | 0.92%   |
| Lenovo ThinkPad X260 20F5S1H800            | 2         | 0.92%   |
| Lenovo ThinkPad T410s 291245G              | 2         | 0.92%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 2         | 0.92%   |
| HP ZBook 15 G4                             | 2         | 0.92%   |
| Gigabyte GB-BSi5A-6200                     | 2         | 0.92%   |
| Dell Latitude E6540                        | 2         | 0.92%   |
| Dell Latitude E6500                        | 2         | 0.92%   |
| Deciso NetBoard-A10                        | 2         | 0.92%   |
| Deciso DEC2700 - OPNsense Appliance        | 2         | 0.92%   |
| ASUS TUF Gaming FX505DT_FX505DT            | 2         | 0.92%   |
| Apple MacBookAir5,1                        | 2         | 0.92%   |
| TUXEDO N13xWU                              | 1         | 0.46%   |
| TUXEDO InfinityBook S 15 Gen6              | 1         | 0.46%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.46%   |
| Toshiba Satellite Pro L40                  | 1         | 0.46%   |
| Tactus GeoFlex 110                         | 1         | 0.46%   |
| Sony VPCM12M1E                             | 1         | 0.46%   |
| Sony VPCEJ1E1E                             | 1         | 0.46%   |
| Sony VGN-SZ3VWP_X                          | 1         | 0.46%   |
| Schenker SCHENKER_COMPACT15_17_SCO15_17M19 | 1         | 0.46%   |
| Schenker N13xWU                            | 1         | 0.46%   |
| Samsung NC210/NC110                        | 1         | 0.46%   |
| Panasonic CF-C1BD06EFG                     | 1         | 0.46%   |
| Packard Bell EasyNote MH36                 | 1         | 0.46%   |
| Notebook N8xEJEK                           | 1         | 0.46%   |
| Notebook N7x0WU                            | 1         | 0.46%   |
| Notebook N13xWU                            | 1         | 0.46%   |
| MSI MS-1613                                | 1         | 0.46%   |
| MSI GT75VR 7RF                             | 1         | 0.46%   |
| MiTAC 5033                                 | 1         | 0.46%   |
| Medion P6812                               | 1         | 0.46%   |
| Lenovo ZIUS6                               | 1         | 0.46%   |
| Lenovo Z50-70 20354                        | 1         | 0.46%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 O 82N5       | 1         | 0.46%   |
| Lenovo V130-15IKB 81HN                     | 1         | 0.46%   |
| Lenovo U310                                | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 62        | 28.57%  |
| Dell Latitude          | 17        | 7.83%   |
| Unknown                | 10        | 4.61%   |
| Fujitsu LIFEBOOK       | 9         | 4.15%   |
| Deciso Netboard        | 5         | 2.3%    |
| Lenovo IdeaPad         | 4         | 1.84%   |
| HP EliteBook           | 3         | 1.38%   |
| Dell Inspiron          | 3         | 1.38%   |
| Acer TravelMate        | 3         | 1.38%   |
| Acer Aspire            | 3         | 1.38%   |
| TUXEDO Pulse           | 2         | 0.92%   |
| Shuttle DS437          | 2         | 0.92%   |
| IBM ThinkPad           | 2         | 0.92%   |
| HP ZBook               | 2         | 0.92%   |
| HP Laptop              | 2         | 0.92%   |
| Gigabyte GB-BSi5A-6200 | 2         | 0.92%   |
| Dell XPS               | 2         | 0.92%   |
| Dell Precision         | 2         | 0.92%   |
| Deciso NetBoard-A10    | 2         | 0.92%   |
| Deciso DEC2700         | 2         | 0.92%   |
| ASUS TUF               | 2         | 0.92%   |
| Apple MacBookAir5      | 2         | 0.92%   |
| Acer Extensa           | 2         | 0.92%   |
| TUXEDO N13xWU          | 1         | 0.46%   |
| TUXEDO InfinityBook    | 1         | 0.46%   |
| TUXEDO Aura            | 1         | 0.46%   |
| Toshiba Satellite      | 1         | 0.46%   |
| Tactus GeoFlex         | 1         | 0.46%   |
| Sony VPCM12M1E         | 1         | 0.46%   |
| Sony VPCEJ1E1E         | 1         | 0.46%   |
| Sony VGN-SZ3VWP        | 1         | 0.46%   |
| Schenker SCHENKER      | 1         | 0.46%   |
| Schenker N13xWU        | 1         | 0.46%   |
| Samsung NC210          | 1         | 0.46%   |
| Panasonic CF-C1BD06EFG | 1         | 0.46%   |
| Packard Bell EasyNote  | 1         | 0.46%   |
| Notebook N8xEJEK       | 1         | 0.46%   |
| Notebook N7x0WU        | 1         | 0.46%   |
| Notebook N13xWU        | 1         | 0.46%   |
| MSI MS-1613            | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 23        | 10.6%   |
| 2021    | 20        | 9.22%   |
| 2018    | 20        | 9.22%   |
| 2019    | 18        | 8.29%   |
| 2017    | 18        | 8.29%   |
| 2013    | 15        | 6.91%   |
| 2011    | 15        | 6.91%   |
| 2010    | 14        | 6.45%   |
| 2012    | 13        | 5.99%   |
| 2016    | 11        | 5.07%   |
| 2015    | 11        | 5.07%   |
| 2014    | 8         | 3.69%   |
| 2008    | 8         | 3.69%   |
| 2009    | 6         | 2.76%   |
| 2022    | 5         | 2.3%    |
| Unknown | 4         | 1.84%   |
| 2007    | 3         | 1.38%   |
| 2003    | 2         | 0.92%   |
| 2006    | 1         | 0.46%   |
| 2005    | 1         | 0.46%   |
| 2002    | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 217       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 216       | 99.54%  |
| Yes  | 1         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 77        | 35.16%  |
| 16.01-24.0  | 59        | 26.94%  |
| 4.01-8.0    | 46        | 21%     |
| 32.01-64.0  | 13        | 5.94%   |
| 2.01-3.0    | 10        | 4.57%   |
| 3.01-4.0    | 3         | 1.37%   |
| 1.01-2.0    | 3         | 1.37%   |
| 0.51-1.0    | 3         | 1.37%   |
| 0.01-0.5    | 2         | 0.91%   |
| 24.01-32.0  | 1         | 0.46%   |
| 64.01-256.0 | 1         | 0.46%   |
| 0           | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 128       | 57.4%   |
| 0.51-1.0   | 60        | 26.91%  |
| 1.01-2.0   | 19        | 8.52%   |
| 2.01-3.0   | 5         | 2.24%   |
| 4.01-8.0   | 4         | 1.79%   |
| Unknown    | 3         | 1.35%   |
| 0          | 2         | 0.9%    |
| 24.01-32.0 | 1         | 0.45%   |
| 16.01-24.0 | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 71.49%  |
| 2      | 47        | 21.27%  |
| 0      | 10        | 4.52%   |
| 3      | 6         | 2.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 71.23%  |
| Yes       | 63        | 28.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 91.71%  |
| No        | 18        | 8.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 85.78%  |
| No        | 31        | 14.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 56.62%  |
| No        | 95        | 43.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 217       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Berlin               | 23        | 10%     |
| Frankfurt am Main    | 10        | 4.35%   |
| Munich               | 8         | 3.48%   |
| Hamburg              | 7         | 3.04%   |
| Bedburg              | 6         | 2.61%   |
| Halle                | 4         | 1.74%   |
| Wernigerode          | 3         | 1.3%    |
| Markt Indersdorf     | 3         | 1.3%    |
| Lübeck              | 3         | 1.3%    |
| Leipzig              | 3         | 1.3%    |
| Bonn                 | 3         | 1.3%    |
| Zwingenberg          | 2         | 0.87%   |
| Wuppertal            | 2         | 0.87%   |
| Wissen               | 2         | 0.87%   |
| Stuttgart            | 2         | 0.87%   |
| Reutlingen           | 2         | 0.87%   |
| Regensburg           | 2         | 0.87%   |
| Potsdam              | 2         | 0.87%   |
| Pleidelsheim         | 2         | 0.87%   |
| Nuremberg            | 2         | 0.87%   |
| Neuss                | 2         | 0.87%   |
| Ludwigsburg          | 2         | 0.87%   |
| Habichtswald         | 2         | 0.87%   |
| Gummersbach          | 2         | 0.87%   |
| Giessen              | 2         | 0.87%   |
| Detmold              | 2         | 0.87%   |
| Bietigheim-Bissingen | 2         | 0.87%   |
| Bielefeld            | 2         | 0.87%   |
| Betzdorf             | 2         | 0.87%   |
| Bensheim             | 2         | 0.87%   |
| Aachen               | 2         | 0.87%   |
| Zwickau              | 1         | 0.43%   |
| Wolfsburg            | 1         | 0.43%   |
| Wilhelmshaven        | 1         | 0.43%   |
| Wetzlar              | 1         | 0.43%   |
| Wenzenbach           | 1         | 0.43%   |
| Weissach             | 1         | 0.43%   |
| Weinbohla            | 1         | 0.43%   |
| Weimar               | 1         | 0.43%   |
| Warendorf            | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 52        | 68     | 21.31%  |
| WDC                 | 21        | 24     | 8.61%   |
| Crucial             | 17        | 22     | 6.97%   |
| Transcend           | 16        | 16     | 6.56%   |
| Seagate             | 16        | 18     | 6.56%   |
| SanDisk             | 15        | 17     | 6.15%   |
| NVMe                | 11        | 21     | 4.51%   |
| Kingston            | 11        | 13     | 4.51%   |
| Toshiba             | 10        | 25     | 4.1%    |
| Intel               | 10        | 10     | 4.1%    |
| Hitachi             | 8         | 11     | 3.28%   |
| Micron Technology   | 7         | 7      | 2.87%   |
| Apple               | 7         | 7      | 2.87%   |
| SPCC                | 4         | 5      | 1.64%   |
| OCZ                 | 4         | 6      | 1.64%   |
| Intenso             | 4         | 5      | 1.64%   |
| Fujitsu             | 4         | 4      | 1.64%   |
| SK hynix            | 3         | 4      | 1.23%   |
| KIOXIA              | 3         | 3      | 1.23%   |
| Hoodisk             | 3         | 3      | 1.23%   |
| HGST                | 3         | 5      | 1.23%   |
| LITEON              | 2         | 2      | 0.82%   |
| Kston               | 2         | 2      | 0.82%   |
| A-DATA Technology   | 2         | 3      | 0.82%   |
| PNY                 | 1         | 1      | 0.41%   |
| MyDigitalSSD        | 1         | 1      | 0.41%   |
| Mushkin             | 1         | 1      | 0.41%   |
| Lenovo              | 1         | 1      | 0.41%   |
| Gigabyte Technology | 1         | 1      | 0.41%   |
| FORESEE             | 1         | 1      | 0.41%   |
| Dogfish             | 1         | 1      | 0.41%   |
| Corsair             | 1         | 1      | 0.41%   |
| BIWIN               | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB     | 4         | 1.58%   |
| Transcend TS256GMTE652T2 256GB     | 4         | 1.58%   |
| Samsung SSD 860 EVO 500GB          | 3         | 1.19%   |
| Samsung SSD 850 EVO 500GB          | 3         | 1.19%   |
| Samsung SSD 840 EVO 250GB          | 3         | 1.19%   |
| Hoodisk SSD 128GB                  | 3         | 1.19%   |
| Transcend TS512GMTS952T2 512GB     | 2         | 0.79%   |
| Transcend TS240GMTS420S 240GB      | 2         | 0.79%   |
| SPCC Solid State Disk 1TB          | 2         | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.79%   |
| SanDisk SDSSDP064G 64GB            | 2         | 0.79%   |
| Samsung SSD 970 EVO 500GB          | 2         | 0.79%   |
| Samsung SSD 870 EVO 250GB          | 2         | 0.79%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.79%   |
| Samsung SSD 840 PRO Series 256GB   | 2         | 0.79%   |
| Samsung MZ7LN256HCHP-000L7 256GB   | 2         | 0.79%   |
| NVMe WDC PC SN730 SDB 256GB        | 2         | 0.79%   |
| NVMe SAMSUNG MZVLW256 256GB        | 2         | 0.79%   |
| Micron 2200V_MTFDHBA512TCK 512GB   | 2         | 0.79%   |
| LITEON LCH-128V2S 128GB            | 2         | 0.79%   |
| Kingston SA400S37480G 480GB        | 2         | 0.79%   |
| Intenso SSD 128GB                  | 2         | 0.79%   |
| Intel SSDSC2BF240A5L 240GB         | 2         | 0.79%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 0.79%   |
| Hitachi HTS543225L9A300 250GB      | 2         | 0.79%   |
| HGST HTS721010A9E630 1TB           | 2         | 0.79%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.79%   |
| Crucial CT250MX500SSD1 250GB       | 2         | 0.79%   |
| Crucial CT240M500SSD3 240GB        | 2         | 0.79%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.79%   |
| Crucial CT1000P1SSD8 1TB           | 2         | 0.79%   |
| Crucial CT1000MX500SSD1 1TB        | 2         | 0.79%   |
| Apple SSD TS128E 121GB             | 2         | 0.79%   |
| Apple SSD SM0512G 500GB            | 2         | 0.79%   |
| WDC WDS500G1B0A-00H9H0 500GB       | 1         | 0.4%    |
| WDC WDS250G1B0A-00H9H0 250GB       | 1         | 0.4%    |
| WDC WDS120G1G0A-00SS50 120GB       | 1         | 0.4%    |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 26.67%  |
| WDC                 | 15        | 17     | 25%     |
| NVMe                | 9         | 19     | 15%     |
| Hitachi             | 8         | 11     | 13.33%  |
| Toshiba             | 4         | 5      | 6.67%   |
| Fujitsu             | 4         | 4      | 6.67%   |
| HGST                | 3         | 5      | 5%      |
| Samsung Electronics | 1         | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 44     | 25.18%  |
| SanDisk             | 15        | 17     | 10.79%  |
| Crucial             | 15        | 20     | 10.79%  |
| Transcend           | 11        | 11     | 7.91%   |
| Intel               | 10        | 10     | 7.19%   |
| Kingston            | 9         | 11     | 6.47%   |
| Apple               | 7         | 7      | 5.04%   |
| OCZ                 | 4         | 6      | 2.88%   |
| Micron Technology   | 4         | 4      | 2.88%   |
| Intenso             | 4         | 5      | 2.88%   |
| WDC                 | 3         | 3      | 2.16%   |
| Toshiba             | 3         | 7      | 2.16%   |
| SPCC                | 3         | 3      | 2.16%   |
| Hoodisk             | 3         | 3      | 2.16%   |
| SK hynix            | 2         | 3      | 1.44%   |
| LITEON              | 2         | 2      | 1.44%   |
| Kston               | 2         | 2      | 1.44%   |
| PNY                 | 1         | 1      | 0.72%   |
| MyDigitalSSD        | 1         | 1      | 0.72%   |
| Mushkin             | 1         | 1      | 0.72%   |
| FORESEE             | 1         | 1      | 0.72%   |
| Dogfish             | 1         | 1      | 0.72%   |
| Corsair             | 1         | 1      | 0.72%   |
| A-DATA Technology   | 1         | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 127       | 165    | 55.7%   |
| HDD  | 57        | 80     | 25%     |
| NVMe | 44        | 65     | 19.3%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 174       | 245    | 79.82%  |
| NVMe | 44        | 65     | 20.18%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 150       | 193    | 80.65%  |
| 0.51-1.0   | 22        | 28     | 11.83%  |
| 1.01-2.0   | 12        | 22     | 6.45%   |
| 3.01-4.0   | 1         | 1      | 0.54%   |
| 4.01-10.0  | 1         | 1      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 80        | 34.93%  |
| 1-20           | 58        | 25.33%  |
| 251-500        | 45        | 19.65%  |
| 51-100         | 19        | 8.3%    |
| 501-1000       | 13        | 5.68%   |
| 21-50          | 9         | 3.93%   |
| 1001-2000      | 3         | 1.31%   |
| More than 3000 | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 180       | 79.3%   |
| 21-50          | 19        | 8.37%   |
| 101-250        | 11        | 4.85%   |
| 51-100         | 11        | 4.85%   |
| 251-500        | 3         | 1.32%   |
| More than 3000 | 1         | 0.44%   |
| 501-1000       | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 8.7%    |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 8.7%    |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 4.35%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 1         | 5      | 4.35%   |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 4.35%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 4.35%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 4.35%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 4.35%   |
| SanDisk SSD P4 64GB                          | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 4.35%   |
| Micron Technology 1100 SATA 256GB            | 1         | 1      | 4.35%   |
| Kingston SV300S37A240G 240GB                 | 1         | 1      | 4.35%   |
| Kingston SNV425S264GB                        | 1         | 1      | 4.35%   |
| Intel SSDSC2KF256H6L 256GB                   | 1         | 1      | 4.35%   |
| Hitachi HTS548040M9AT00 37GB                 | 1         | 1      | 4.35%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 2      | 4.35%   |
| Fujitsu MHW2160BH 160GB                      | 1         | 1      | 4.35%   |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 4.35%   |
| Corsair Force GT 120GB                       | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 9      | 26.09%  |
| Seagate             | 4         | 4      | 17.39%  |
| Toshiba             | 2         | 6      | 8.7%    |
| SanDisk             | 2         | 2      | 8.7%    |
| Kingston            | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Micron Technology   | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Fujitsu             | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |
| Corsair             | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 6         | 9      | 46.15%  |
| Seagate | 4         | 4      | 30.77%  |
| WDC     | 1         | 1      | 7.69%   |
| Toshiba | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 56.52%  |
| SSD  | 9         | 13     | 39.13%  |
| NVMe | 1         | 1      | 4.35%   |

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
| Works    | 183       | 259    | 83.94%  |
| Malfunc  | 23        | 30     | 10.55%  |
| Detected | 12        | 21     | 5.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 164       | 66.67%  |
| Samsung Electronics              | 28        | 11.38%  |
| AMD                              | 17        | 6.91%   |
| SanDisk                          | 6         | 2.44%   |
| Transcend                        | 5         | 2.03%   |
| Toshiba                          | 5         | 2.03%   |
| Micron Technology                | 3         | 1.22%   |
| SK hynix                         | 2         | 0.81%   |
| Phison Electronics               | 2         | 0.81%   |
| Nvidia                           | 2         | 0.81%   |
| Micron/Crucial Technology        | 2         | 0.81%   |
| KIOXIA                           | 2         | 0.81%   |
| Kingston Technology Company      | 2         | 0.81%   |
| ADATA Technology                 | 2         | 0.81%   |
| ULi Electronics                  | 1         | 0.41%   |
| Silicon Motion                   | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Lenovo                           | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 20        | 7.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 19        | 7.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 19        | 7.28%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 6.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 16        | 6.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 13        | 4.98%   |
| Unknown                                                                                | 10        | 3.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 9         | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 9         | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 3.07%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 8         | 3.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 7         | 2.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 7         | 2.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 2.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 1.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.53%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 1.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.53%   |
| Samsung SM951 AHCI                                                                     | 3         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.15%   |
| Toshiba XG6 NVMe SSD Controller                                                        | 2         | 0.77%   |
| Toshiba XG5 NVMe SSD Controller                                                        | 2         | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 0.77%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.77%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.77%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 2         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 0.77%   |
| ULi M5229 IDE                                                                          | 1         | 0.38%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 0.38%   |
| SK hynix hynix unknown                                                                 | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 170       | 67.19%  |
| NVMe | 53        | 20.95%  |
| IDE  | 25        | 9.88%   |
| RAID | 5         | 1.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 188       | 86.64%  |
| AMD     | 28        | 12.9%   |
| PowerPC | 1         | 0.46%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz      | 8         | 3.67%   |
| Intel CPU Version                      | 7         | 3.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz      | 7         | 3.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 7         | 3.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz      | 6         | 2.75%   |
| AMD Ryzen Embedded V1500B              | 5         | 2.29%   |
| AMD EPYC 3201 8-Core Processor         | 5         | 2.29%   |
| Intel Core i5-5300U CPU @ 2.30GHz      | 4         | 1.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 4         | 1.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz      | 3         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz      | 3         | 1.38%   |
| Intel Core i7-7500U CPU @ 2.70GHz      | 3         | 1.38%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 3         | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 3         | 1.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz      | 3         | 1.38%   |
| Intel Core i5-4250U CPU @ 1.30GHz      | 3         | 1.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 3         | 1.38%   |
| Intel Core i5-3317U CPU @ 1.70GHz      | 3         | 1.38%   |
| Intel Core i5 CPU M 560 @ 2.67GHz      | 3         | 1.38%   |
| Intel Core i3-4005U CPU @ 1.70GHz      | 3         | 1.38%   |
| Intel Core 2 Duo                       | 3         | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics | 3         | 1.38%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz   | 2         | 0.92%   |
| Intel Genuine CPU                      | 2         | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 0.92%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 2         | 0.92%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz     | 2         | 0.92%   |
| Intel Core i7-4610M CPU @ 3.00GHz      | 2         | 0.92%   |
| Intel Core i7-2860QM CPU @ 2.50GHz     | 2         | 0.92%   |
| Intel Core i7-2677M CPU @ 1.80GHz      | 2         | 0.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 2         | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 2         | 0.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz      | 2         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz      | 2         | 0.92%   |
| Intel Core i5-4200M CPU @ 2.50GHz      | 2         | 0.92%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 2         | 0.92%   |
| Intel Core i5-2450M CPU @ 2.50GHz      | 2         | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz     | 2         | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 2         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 76        | 35.02%  |
| Intel Core i7        | 46        | 21.2%   |
| Other                | 13        | 5.99%   |
| Intel Core 2 Duo     | 11        | 5.07%   |
| Intel Core i3        | 10        | 4.61%   |
| Intel Celeron        | 9         | 4.15%   |
| AMD Ryzen 7          | 7         | 3.23%   |
| AMD EPYC             | 6         | 2.76%   |
| Intel Pentium        | 5         | 2.3%    |
| Intel Atom           | 5         | 2.3%    |
| AMD Ryzen Embedded   | 5         | 2.3%    |
| AMD Ryzen 5          | 5         | 2.3%    |
| Intel Pentium M      | 3         | 1.38%   |
| Intel Genuine        | 3         | 1.38%   |
| Intel Xeon           | 2         | 0.92%   |
| Intel Pentium Silver | 1         | 0.46%   |
| Intel Pentium Dual   | 1         | 0.46%   |
| Intel Pentium 4      | 1         | 0.46%   |
| Intel Core m3        | 1         | 0.46%   |
| Intel Core M         | 1         | 0.46%   |
| Intel Core 2 Solo    | 1         | 0.46%   |
| Intel Core 2         | 1         | 0.46%   |
| Intel Celeron M      | 1         | 0.46%   |
| AMD Ryzen 7 PRO      | 1         | 0.46%   |
| AMD E2               | 1         | 0.46%   |
| AMD A6               | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 113       | 51.83%  |
| 4       | 48        | 22.02%  |
| 8       | 16        | 7.34%   |
| Unknown | 16        | 7.34%   |
| 1       | 10        | 4.59%   |
| 16      | 7         | 3.21%   |
| 6       | 7         | 3.21%   |
| 12      | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 208       | 95.41%  |
| Unknown | 6         | 2.75%   |
| 2       | 4         | 1.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 143       | 65.9%   |
| 1       | 50        | 23.04%  |
| Unknown | 24        | 11.06%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 38        | 17.51%  |
| Haswell       | 27        | 12.44%  |
| IvyBridge     | 22        | 10.14%  |
| SandyBridge   | 21        | 9.68%   |
| Penryn        | 16        | 7.37%   |
| Skylake       | 13        | 5.99%   |
| Zen           | 11        | 5.07%   |
| Broadwell     | 10        | 4.61%   |
| Unknown       | 8         | 3.69%   |
| Westmere      | 7         | 3.23%   |
| Core          | 6         | 2.76%   |
| Zen 2         | 5         | 2.3%    |
| Silvermont    | 5         | 2.3%    |
| Bonnell       | 5         | 2.3%    |
| Zen+          | 4         | 1.84%   |
| P6            | 4         | 1.84%   |
| TigerLake     | 2         | 0.92%   |
| NetBurst      | 2         | 0.92%   |
| Goldmont plus | 2         | 0.92%   |
| Goldmont      | 2         | 0.92%   |
| Zen 3         | 1         | 0.46%   |
| Puma          | 1         | 0.46%   |
| Piledriver    | 1         | 0.46%   |
| IceLake       | 1         | 0.46%   |
| Geode         | 1         | 0.46%   |
| CometLake     | 1         | 0.46%   |
| Bobcat        | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 71.98%  |
| Nvidia                           | 40        | 17.24%  |
| AMD                              | 23        | 9.91%   |
| Trident Microsystems             | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 9.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 7.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 7.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 5.44%   |
| Intel UHD Graphics 620                                                                   | 10        | 4.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 3.77%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 3.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 3.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.09%   |
| Intel HD Graphics 620                                                                    | 5         | 2.09%   |
| AMD Renoir                                                                               | 5         | 2.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.67%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.26%   |
| AMD Lucienne                                                                             | 3         | 1.26%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.84%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.84%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.84%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.84%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.84%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.84%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.84%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.84%   |
| Intel HD Graphics P630                                                                   | 2         | 0.84%   |
| Intel HD Graphics 500                                                                    | 2         | 0.84%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 2         | 0.84%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                | 1         | 0.42%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.42%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 122       | 55.96%  |
| Intel + Nvidia           | 21        | 9.63%   |
| 2 x Intel                | 20        | 9.17%   |
| 1 x Nvidia               | 17        | 7.8%    |
| 1 x AMD                  | 16        | 7.34%   |
| Other                    | 13        | 5.96%   |
| Intel + AMD              | 4         | 1.83%   |
| AMD + Nvidia             | 3         | 1.38%   |
| 1 x Trident Microsystems | 1         | 0.46%   |
| 1 x SiS                  | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 180       | 81.82%  |
| Unknown     | 27        | 12.27%  |
| Proprietary | 13        | 5.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 204       | 93.15%  |
| 0.01-0.5   | 8         | 3.65%   |
| 1.01-2.0   | 3         | 1.37%   |
| 7.01-8.0   | 2         | 0.91%   |
| 3.01-4.0   | 2         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 31        | 20.95%  |
| AU Optronics         | 31        | 20.95%  |
| Chimei Innolux       | 14        | 9.46%   |
| Apple                | 12        | 8.11%   |
| Lenovo               | 11        | 7.43%   |
| Samsung Electronics  | 9         | 6.08%   |
| BOE                  | 8         | 5.41%   |
| Dell                 | 4         | 2.7%    |
| Sharp                | 3         | 2.03%   |
| PANDA                | 3         | 2.03%   |
| InfoVision           | 3         | 2.03%   |
| Goldstar             | 3         | 2.03%   |
| Iiyama               | 2         | 1.35%   |
| BenQ                 | 2         | 1.35%   |
| AOC                  | 2         | 1.35%   |
| Ancor Communications | 2         | 1.35%   |
| TRU                  | 1         | 0.68%   |
| Toshiba              | 1         | 0.68%   |
| Panasonic            | 1         | 0.68%   |
| LTM                  | 1         | 0.68%   |
| LG Philips           | 1         | 0.68%   |
| JDI                  | 1         | 0.68%   |
| Hewlett-Packard      | 1         | 0.68%   |
| Eizo                 | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 3         | 2.01%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 2.01%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 3         | 2.01%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch               | 2         | 1.34%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 2         | 1.34%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch           | 2         | 1.34%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.34%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 2         | 1.34%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 2         | 1.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 1.34%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 1.34%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.34%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch         | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch        | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 1.34%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                  | 1         | 0.67%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.67%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.67%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 340x190mm 15.3-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 290x170mm 13.2-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch  | 1         | 0.67%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 290x170mm 13.2-inch               | 1         | 0.67%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 1         | 0.67%   |
| LTM LCD Monitor LTM3937 720x1280 130x80mm 6.0-inch                    | 1         | 0.67%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD0612 1920x1080 340x190mm 15.3-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD059E 1920x1080 380x210mm 17.1-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch          | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 34.93%  |
| 1366x768 (WXGA)    | 43        | 29.45%  |
| 1280x800 (WXGA)    | 10        | 6.85%   |
| 3840x2160 (4K)     | 8         | 5.48%   |
| 1600x900 (HD+)     | 7         | 4.79%   |
| 2560x1440 (QHD)    | 5         | 3.42%   |
| 1440x900 (WXGA+)   | 5         | 3.42%   |
| 1920x1200 (WUXGA)  | 4         | 2.74%   |
| 3200x1800 (QHD+)   | 2         | 1.37%   |
| 1024x768 (XGA)     | 2         | 1.37%   |
| 720x1280           | 1         | 0.68%   |
| 3000x2000          | 1         | 0.68%   |
| 2880x1800          | 1         | 0.68%   |
| 2880x1620          | 1         | 0.68%   |
| 2560x1600          | 1         | 0.68%   |
| 2560x1080          | 1         | 0.68%   |
| 1920x540           | 1         | 0.68%   |
| 1680x1050 (WSXGA+) | 1         | 0.68%   |
| 1280x1024 (SXGA)   | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 46        | 31.29%  |
| 15      | 40        | 27.21%  |
| 12      | 23        | 15.65%  |
| 24      | 7         | 4.76%   |
| 14      | 6         | 4.08%   |
| 11      | 6         | 4.08%   |
| 17      | 5         | 3.4%    |
| 27      | 4         | 2.72%   |
| 23      | 3         | 2.04%   |
| Unknown | 2         | 1.36%   |
| 39      | 1         | 0.68%   |
| 34      | 1         | 0.68%   |
| 32      | 1         | 0.68%   |
| 31      | 1         | 0.68%   |
| 6       | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 69        | 46.94%  |
| 201-300     | 53        | 36.05%  |
| 501-600     | 12        | 8.16%   |
| 351-400     | 4         | 2.72%   |
| 701-800     | 2         | 1.36%   |
| 601-700     | 2         | 1.36%   |
| Unknown     | 2         | 1.36%   |
| 801-900     | 1         | 0.68%   |
| 401-500     | 1         | 0.68%   |
| 101-200     | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 111       | 78.72%  |
| 16/10   | 21        | 14.89%  |
| 4/3     | 3         | 2.13%   |
| 3/2     | 2         | 1.42%   |
| Unknown | 2         | 1.42%   |
| 5/4     | 1         | 0.71%   |
| 21/9    | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 40        | 27.03%  |
| 91-100         | 29        | 19.59%  |
| 61-70          | 23        | 15.54%  |
| 101-110        | 12        | 8.11%   |
| 71-80          | 11        | 7.43%   |
| 201-250        | 7         | 4.73%   |
| 51-60          | 6         | 4.05%   |
| 301-350        | 4         | 2.7%    |
| 251-300        | 4         | 2.7%    |
| 121-130        | 4         | 2.7%    |
| 351-500        | 3         | 2.03%   |
| Unknown        | 2         | 1.35%   |
| 1-40           | 1         | 0.68%   |
| 141-150        | 1         | 0.68%   |
| 501-1000       | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 47.92%  |
| 101-120       | 27        | 18.75%  |
| 51-100        | 21        | 14.58%  |
| 161-240       | 17        | 11.81%  |
| More than 240 | 8         | 5.56%   |
| Unknown       | 2         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 128       | 57.66%  |
| 0     | 79        | 35.59%  |
| 2     | 14        | 6.31%   |
| 3     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 158       | 46.61%  |
| Realtek Semiconductor             | 68        | 20.06%  |
| Qualcomm Atheros                  | 29        | 8.55%   |
| Broadcom                          | 26        | 7.67%   |
| AMD                               | 11        | 3.24%   |
| Ericsson Business Mobile Networks | 9         | 2.65%   |
| Ralink Technology                 | 5         | 1.47%   |
| Edimax Technology                 | 4         | 1.18%   |
| Marvell Technology Group          | 3         | 0.88%   |
| Google                            | 3         | 0.88%   |
| TP-Link                           | 2         | 0.59%   |
| Sierra Wireless                   | 2         | 0.59%   |
| Ralink                            | 2         | 0.59%   |
| Nvidia                            | 2         | 0.59%   |
| MediaTek                          | 2         | 0.59%   |
| ASUSTek Computer                  | 2         | 0.59%   |
| ULi Electronics                   | 1         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| National Semiconductor            | 1         | 0.29%   |
| Micro Star International          | 1         | 0.29%   |
| JMicron Technology                | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Hewlett-Packard                   | 1         | 0.29%   |
| D-Link System                     | 1         | 0.29%   |
| Aquantia                          | 1         | 0.29%   |
| Apple                             | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 52        | 11.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 24        | 5.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 16        | 3.64%   |
| Intel I210 Gigabit Network Connection                                       | 13        | 2.96%   |
| Intel Wireless 8265 / 8275                                                  | 12        | 2.73%   |
| Intel Wireless 7265                                                         | 12        | 2.73%   |
| Intel Wireless 8260                                                         | 11        | 2.51%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                   | 11        | 2.51%   |
| Intel Wi-Fi 6 AX200                                                         | 10        | 2.28%   |
| Intel Centrino Ultimate-N 6300                                              | 10        | 2.28%   |
| Intel Wireless 7260                                                         | 9         | 2.05%   |
| Intel Ethernet Connection I219-LM                                           | 9         | 2.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 8         | 1.82%   |
| Intel I211 Gigabit Network Connection                                       | 8         | 1.82%   |
| Intel Ethernet Connection I217-LM                                           | 7         | 1.59%   |
| Intel 82577LM Gigabit Network Connection                                    | 7         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 6         | 1.37%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 6         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 5         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                        | 5         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 4         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 0.91%   |
| Intel Wireless-AC 9260                                                      | 4         | 0.91%   |
| Intel Wireless 3165                                                         | 4         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                                       | 4         | 0.91%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 4         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 3         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 3         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 3         | 0.68%   |
| Intel Ethernet Connection I218-LM                                           | 3         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                                       | 3         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 3         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 3         | 0.68%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 3         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                    | 3         | 0.68%   |
| Google Nexus/Pixel Device (tether)                                          | 3         | 0.68%   |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 127       | 61.35%  |
| Qualcomm Atheros         | 25        | 12.08%  |
| Broadcom                 | 18        | 8.7%    |
| Realtek Semiconductor    | 17        | 8.21%   |
| Ralink Technology        | 5         | 2.42%   |
| Edimax Technology        | 4         | 1.93%   |
| TP-Link                  | 2         | 0.97%   |
| Sierra Wireless          | 2         | 0.97%   |
| Ralink                   | 2         | 0.97%   |
| MediaTek                 | 2         | 0.97%   |
| ASUSTek Computer         | 2         | 0.97%   |
| Micro Star International | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 16        | 7.69%   |
| Intel Wireless 8265 / 8275                                     | 12        | 5.77%   |
| Intel Wireless 7265                                            | 12        | 5.77%   |
| Intel Wireless 8260                                            | 11        | 5.29%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 4.81%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 4.81%   |
| Intel Wireless 7260                                            | 9         | 4.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 1.92%   |
| Intel Wireless-AC 9260                                         | 4         | 1.92%   |
| Intel Wireless 3165                                            | 4         | 1.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 1.44%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.44%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3         | 1.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.96%   |
| Sierra Wireless EM7455                                         | 2         | 0.96%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.96%   |
| Intel WiFi Link 5100                                           | 2         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.96%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 0.96%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 0.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 0.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 0.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 105       | 49.3%   |
| Realtek Semiconductor    | 63        | 29.58%  |
| Broadcom                 | 14        | 6.57%   |
| AMD                      | 11        | 5.16%   |
| Qualcomm Atheros         | 7         | 3.29%   |
| Marvell Technology Group | 3         | 1.41%   |
| Google                   | 3         | 1.41%   |
| Nvidia                   | 2         | 0.94%   |
| Samsung Electronics      | 1         | 0.47%   |
| National Semiconductor   | 1         | 0.47%   |
| JMicron Technology       | 1         | 0.47%   |
| Aquantia                 | 1         | 0.47%   |
| Apple                    | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 24.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 11.16%  |
| Intel I210 Gigabit Network Connection                             | 13        | 6.05%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 11        | 5.12%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 4.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.72%   |
| Intel I211 Gigabit Network Connection                             | 8         | 3.72%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 3.26%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 3.26%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 2.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.86%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.4%    |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.4%    |
| Google Nexus/Pixel Device (tether)                                | 3         | 1.4%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.93%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.47%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.47%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.47%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.47%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.47%   |
| Intel I210 Gigabit Backplane Connection                           | 1         | 0.47%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 199       | 49.5%   |
| WiFi     | 187       | 46.52%  |
| Modem    | 9         | 2.24%   |
| Unknown  | 7         | 1.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 55.52%  |
| WiFi     | 126       | 42.14%  |
| Unknown  | 6         | 2.01%   |
| Modem    | 1         | 0.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 159       | 72.94%  |
| 1     | 30        | 13.76%  |
| 6     | 13        | 5.96%   |
| 3     | 6         | 2.75%   |
| 5     | 5         | 2.29%   |
| 0     | 2         | 0.92%   |
| 8     | 1         | 0.46%   |
| 7     | 1         | 0.46%   |
| 4     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 196       | 89.09%  |
| Yes  | 24        | 10.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 49.6%   |
| Broadcom                        | 16        | 12.8%   |
| Qualcomm Atheros Communications | 12        | 9.6%    |
| Apple                           | 11        | 8.8%    |
| Realtek Semiconductor           | 6         | 4.8%    |
| Foxconn / Hon Hai               | 5         | 4%      |
| Lite-On Technology              | 3         | 2.4%    |
| Dell                            | 2         | 1.6%    |
| Cambridge Silicon Radio         | 2         | 1.6%    |
| ASUSTek Computer                | 2         | 1.6%    |
| Alps Electric                   | 2         | 1.6%    |
| IMC Networks                    | 1         | 0.8%    |
| Hewlett-Packard                 | 1         | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 32        | 25.6%   |
| Intel AX200 Bluetooth                                       | 11        | 8.8%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 6.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 5         | 4%      |
| Apple Bluetooth Host Controller                             | 5         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 3.2%    |
| Intel AX201 Bluetooth                                       | 4         | 3.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.4%    |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 2.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 2.4%    |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 2.4%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 2.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 2.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.6%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.6%    |
| Foxconn / Hon Hai Wireless_Device                           | 2         | 1.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.6%    |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 1.6%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.8%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.8%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1         | 0.8%    |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.8%    |
| Qualcomm Atheros Bluetooth                                  | 1         | 0.8%    |
| Intel AX210 Bluetooth                                       | 1         | 0.8%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.8%    |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.8%    |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.8%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.8%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 0.8%    |
| Dell DW375 Bluetooth Module                                 | 1         | 0.8%    |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.8%    |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device      | 1         | 0.8%    |
| Broadcom Bluetooth                                          | 1         | 0.8%    |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 0.8%    |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.8%    |
| ASUS ASUS USB-BT500                                         | 1         | 0.8%    |
| Apple Bluetooth HCI                                         | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 181       | 78.7%   |
| AMD                                          | 26        | 11.3%   |
| Nvidia                                       | 15        | 6.52%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.43%   |
| ULi Electronics                              | 1         | 0.43%   |
| Texas Instruments                            | 1         | 0.43%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.43%   |
| Logitech                                     | 1         | 0.43%   |
| Lenovo                                       | 1         | 0.43%   |
| Hewlett-Packard                              | 1         | 0.43%   |
| GN Netcom                                    | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 10.11%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 7.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 7.22%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 6.5%    |
| Intel 8 Series HD Audio Controller                                                                | 17        | 6.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 5.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 4.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.61%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.44%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.44%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.72%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.72%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.36%   |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 1         | 0.36%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.36%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.36%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.36%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 57        | 26.15%  |
| SK hynix                     | 38        | 17.43%  |
| Kingston                     | 28        | 12.84%  |
| Micron Technology            | 21        | 9.63%   |
| Unknown                      | 20        | 9.17%   |
| Crucial                      | 11        | 5.05%   |
| Transcend                    | 9         | 4.13%   |
| Ramaxel Technology           | 7         | 3.21%   |
| Corsair                      | 6         | 2.75%   |
| Unknown                      | 6         | 2.75%   |
| Elpida                       | 5         | 2.29%   |
| Nanya Technology             | 3         | 1.38%   |
| Unknown (ABCD)               | 1         | 0.46%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.46%   |
| Team                         | 1         | 0.46%   |
| Patriot                      | 1         | 0.46%   |
| G.Skill                      | 1         | 0.46%   |
| A-DATA Technology            | 1         | 0.46%   |
| 48spaces                     | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 6         | 2.64%   |
| Unknown                                                   | 6         | 2.64%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s       | 4         | 1.76%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s              | 4         | 1.76%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 4         | 1.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 4         | 1.76%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 4         | 1.76%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s       | 3         | 1.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 3         | 1.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 3         | 1.32%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 1.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s     | 3         | 1.32%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 3         | 1.32%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s   | 3         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.88%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s    | 2         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.88%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 0.88%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s    | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.88%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 1333MT/s   | 2         | 0.88%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s     | 2         | 0.88%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s    | 2         | 0.88%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s    | 2         | 0.88%   |
| Kingston RAM 99U5428-042.A00G 4096MB SODIMM DDR3 1334MT/s | 2         | 0.88%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s   | 2         | 0.88%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1333MT/s   | 2         | 0.88%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                 | 1         | 0.44%   |
| Unknown SODIMM 1GB SODIMM DDR2 667MT/s                    | 1         | 0.44%   |
| Unknown RAM PartNum 0 512MB Chip DDR2 533MT/s             | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DRAM                      | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DDR                       | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s               | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s            | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s               | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 95        | 49.74%  |
| DDR4    | 65        | 34.03%  |
| DDR2    | 15        | 7.85%   |
| DDR     | 4         | 2.09%   |
| Unknown | 4         | 2.09%   |
| LPDDR3  | 3         | 1.57%   |
| LPDDR4  | 2         | 1.05%   |
| SDRAM   | 1         | 0.52%   |
| RAM     | 1         | 0.52%   |
| DRAM    | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 183       | 95.81%  |
| Row Of Chips | 6         | 3.14%   |
| DIMM         | 1         | 0.52%   |
| Chip         | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 73        | 36.14%  |
| 4096  | 58        | 28.71%  |
| 2048  | 33        | 16.34%  |
| 16384 | 25        | 12.38%  |
| 1024  | 8         | 3.96%   |
| 512   | 2         | 0.99%   |
| 256   | 2         | 0.99%   |
| 32768 | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 29.41%  |
| 1333    | 26        | 12.75%  |
| 2667    | 25        | 12.25%  |
| 2400    | 18        | 8.82%   |
| 3200    | 15        | 7.35%   |
| 1334    | 13        | 6.37%   |
| 667     | 11        | 5.39%   |
| 2133    | 8         | 3.92%   |
| 800     | 7         | 3.43%   |
| Unknown | 7         | 3.43%   |
| 1867    | 4         | 1.96%   |
| 1067    | 3         | 1.47%   |
| 1066    | 2         | 0.98%   |
| 533     | 2         | 0.98%   |
| 4267    | 1         | 0.49%   |
| 2933    | 1         | 0.49%   |
| 975     | 1         | 0.49%   |

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
| Chicony Electronics                    | 45        | 34.88%  |
| Acer                                   | 13        | 10.08%  |
| Microdia                               | 10        | 7.75%   |
| Suyin                                  | 9         | 6.98%   |
| Realtek Semiconductor                  | 9         | 6.98%   |
| Lite-On Technology                     | 7         | 5.43%   |
| IMC Networks                           | 7         | 5.43%   |
| Sunplus Innovation Technology          | 6         | 4.65%   |
| Lenovo                                 | 4         | 3.1%    |
| Apple                                  | 4         | 3.1%    |
| Alcor Micro                            | 4         | 3.1%    |
| Syntek                                 | 2         | 1.55%   |
| Tripath Technology                     | 1         | 0.78%   |
| Silicon Motion                         | 1         | 0.78%   |
| Ricoh                                  | 1         | 0.78%   |
| Quanta                                 | 1         | 0.78%   |
| Pixart Imaging                         | 1         | 0.78%   |
| Luxvisions Innotech Limited            | 1         | 0.78%   |
| Logitech                               | 1         | 0.78%   |
| Cubeternet                             | 1         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 22        | 16.92%  |
| Acer Integrated Camera                   | 6         | 4.62%   |
| Microdia Integrated Webcam               | 4         | 3.08%   |
| Lite-On Integrated Camera                | 4         | 3.08%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 4         | 3.08%   |
| Chicony HD Webcam                        | 4         | 3.08%   |
| Chicony FJ Camera                        | 4         | 3.08%   |
| Suyin RGBIR Camera                       | 3         | 2.31%   |
| Realtek Realtek USB2.0 PC Camera         | 3         | 2.31%   |
| Realtek Integrated_Webcam_HD             | 3         | 2.31%   |
| IMC Networks Integrated Camera           | 3         | 2.31%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.54%   |
| Lite-On Realtek PC Camera                | 2         | 1.54%   |
| Lenovo Integrated Webcam [R5U877]        | 2         | 1.54%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 1.54%   |
| Chicony HD WebCam (Acer)                 | 2         | 1.54%   |
| Chicony Chicony USB2.0 Camera            | 2         | 1.54%   |
| Apple FaceTime HD Camera (Built-in)      | 2         | 1.54%   |
| Alcor Micro USB 2.0 Web Camera           | 2         | 1.54%   |
| Acer SunplusIT Integrated Camera         | 2         | 1.54%   |
| Tripath PC Camera                        | 1         | 0.77%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.77%   |
| Syntek Integrated Camera                 | 1         | 0.77%   |
| Suyin Sony Visual Communication Camera   | 1         | 0.77%   |
| Suyin Integrated Webcam                  | 1         | 0.77%   |
| Suyin HP Webcam-101                      | 1         | 0.77%   |
| Suyin HP Integrated Webcam               | 1         | 0.77%   |
| Suyin Asus Integrated Webcam             | 1         | 0.77%   |
| Suyin Acer/Lenovo Webcam [CN0316]        | 1         | 0.77%   |
| Sunplus Integrated_Webcam_FHD            | 1         | 0.77%   |
| Sunplus Integrated Camera                | 1         | 0.77%   |
| Sunplus HP HD Webcam [Fixed]             | 1         | 0.77%   |
| Sunplus Asus Webcam                      | 1         | 0.77%   |
| Silicon Motion WebCam SCB-0385N          | 1         | 0.77%   |
| Ricoh HD Webcam                          | 1         | 0.77%   |
| Realtek USB Camera                       | 1         | 0.77%   |
| Realtek USB 2 Webcam                     | 1         | 0.77%   |
| Realtek Integrated Webcam HD             | 1         | 0.77%   |
| Quanta HP TrueVision HD Camera           | 1         | 0.77%   |
| Pixart Imaging VGA Webcam                | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 34%     |
| Upek                       | 9         | 18%     |
| Synaptics                  | 8         | 16%     |
| AuthenTec                  | 5         | 10%     |
| LighTuning Technology      | 3         | 6%      |
| Broadcom                   | 3         | 6%      |
| STMicroelectronics         | 2         | 4%      |
| Shenzhen Goodix Technology | 2         | 4%      |
| Next Biometrics            | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 8         | 16%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 6         | 12%     |
| Validity Sensors Synaptics WBDI                                              | 4         | 8%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 4%      |
| STMicroelectronics Fingerprint Reader                                        | 2         | 4%      |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 4%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 4%      |
| Unknown                                                                      | 2         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 2%      |
| Upek TCS5B Fingerprint sensor                                                | 1         | 2%      |
| Synaptics product 0x00be                                                     | 1         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2%      |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2%      |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 2%      |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 2%      |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 2%      |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2%      |
| AuthenTec AES1600                                                            | 1         | 2%      |

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
| 1     | 71        | 31.56%  |
| 2     | 64        | 28.44%  |
| 0     | 34        | 15.11%  |
| 3     | 33        | 14.67%  |
| 4     | 17        | 7.56%   |
| 5     | 4         | 1.78%   |
| 7     | 1         | 0.44%   |
| 6     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 149       | 40.82%  |
| Bluetooth                | 44        | 12.05%  |
| Card reader              | 43        | 11.78%  |
| Fingerprint reader       | 41        | 11.23%  |
| Net/wireless             | 39        | 10.68%  |
| Firewire controller      | 16        | 4.38%   |
| Graphics card            | 9         | 2.47%   |
| Net/ethernet             | 6         | 1.64%   |
| Network                  | 5         | 1.37%   |
| Sound                    | 4         | 1.1%    |
| Modem                    | 4         | 1.1%    |
| Storage                  | 2         | 0.55%   |
| Storage/nvme             | 1         | 0.27%   |
| Storage/ide              | 1         | 0.27%   |
| Storage/ata              | 1         | 0.27%   |

