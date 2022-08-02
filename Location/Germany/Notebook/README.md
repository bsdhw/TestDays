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

Total: 300

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Shuttle       | DS437                       | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Deciso        | NetBoard-A10                | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a4b6a40758](https://bsd-hardware.info/?probe=a4b6a40758) | May 19, 2022 |
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
| Lenovo        | ThinkPad T430s 2356JH4      | [bd49fb21be](https://bsd-hardware.info/?probe=bd49fb21be) | Dec 04, 2021 |
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
| ASUSTek       | TUF Gaming FX505DT_FX505... | [ca2dd5f540](https://bsd-hardware.info/?probe=ca2dd5f540) | Oct 10, 2021 |
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
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b305c0df5e](https://bsd-hardware.info/?probe=b305c0df5e) | Aug 03, 2020 |
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


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| helloSystem 0.4.0      | 14        | 5.96%   |
| OpenBSD 6.8            | 12        | 5.11%   |
| helloSystem 0.5.0      | 12        | 5.11%   |
| helloSystem 0.7.0      | 10        | 4.26%   |
| FreeBSD 12.2           | 10        | 4.26%   |
| OpenBSD 7.0            | 8         | 3.4%    |
| FreeBSD 13.0-p4        | 7         | 2.98%   |
| OpenBSD 6.9            | 6         | 2.55%   |
| helloSystem 0.6.0      | 6         | 2.55%   |
| GhostBSD 22.01.12      | 6         | 2.55%   |
| FreeBSD 12.1-p10       | 6         | 2.55%   |
| OPNsense 21.7.6        | 5         | 2.13%   |
| OpenBSD 6.7            | 5         | 2.13%   |
| GhostBSD 21.08.27      | 5         | 2.13%   |
| FreeBSD 14.0-CURRENT   | 5         | 2.13%   |
| FreeBSD 13.0-CURRENT   | 5         | 2.13%   |
| FreeBSD 13.0           | 5         | 2.13%   |
| FreeBSD 12.2-p2        | 5         | 2.13%   |
| FreeBSD 12.1-STABLE    | 5         | 2.13%   |
| OPNsense 21.1.2        | 4         | 1.7%    |
| NomadBSD 1.4           | 4         | 1.7%    |
| GhostBSD 20.04.02      | 4         | 1.7%    |
| FreeBSD 12.1-p5        | 4         | 1.7%    |
| FreeBSD 12.1           | 4         | 1.7%    |
| OPNsense 22.1.6        | 3         | 1.28%   |
| NomadBSD 5806f915      | 3         | 1.28%   |
| NomadBSD 1.4-RC1       | 3         | 1.28%   |
| helloSystem 0.8.0      | 3         | 1.28%   |
| FreeBSD 12.2-p3        | 3         | 1.28%   |
| FreeBSD 12.1-p7        | 3         | 1.28%   |
| OPNsense 22.4          | 2         | 0.85%   |
| OPNsense 21.7.1        | 2         | 0.85%   |
| OPNsense 21.1.8        | 2         | 0.85%   |
| OPNsense 21.1.6        | 2         | 0.85%   |
| OPNsense 21.1.5        | 2         | 0.85%   |
| OPNsense 21.1.3        | 2         | 0.85%   |
| OPNsense 21.1.1        | 2         | 0.85%   |
| OPNsense 21.1          | 2         | 0.85%   |
| FreeBSD 13.1           | 2         | 0.85%   |
| FreeBSD 13.0-p8        | 2         | 0.85%   |
| FreeBSD 13.0-p6        | 2         | 0.85%   |
| FreeBSD 13.0-p11       | 2         | 0.85%   |
| FreeBSD 13.0-BETA3     | 2         | 0.85%   |
| OPNsense 22.1.9        | 1         | 0.43%   |
| OPNsense 22.1.3        | 1         | 0.43%   |
| OPNsense 22.1.2        | 1         | 0.43%   |
| OPNsense 22.1          | 1         | 0.43%   |
| OPNsense 21.7.8        | 1         | 0.43%   |
| OPNsense 21.7.4        | 1         | 0.43%   |
| OPNsense 21.7.3        | 1         | 0.43%   |
| OPNsense 21.7          | 1         | 0.43%   |
| OPNsense 21.1.7        | 1         | 0.43%   |
| OPNsense 12.1-p21-HBSD | 1         | 0.43%   |
| OpenBSD 7.1            | 1         | 0.43%   |
| OpenBSD 6.6            | 1         | 0.43%   |
| NomadBSD 1.3.2         | 1         | 0.43%   |
| NomadBSD 1.3.1         | 1         | 0.43%   |
| NetBSD 9.2             | 1         | 0.43%   |
| helloSystem 0.3.0      | 1         | 0.43%   |
| HardenedBSD 12.2--HBSD | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 67        | 33%     |
| helloSystem | 45        | 22.17%  |
| OPNsense    | 33        | 16.26%  |
| OpenBSD     | 28        | 13.79%  |
| GhostBSD    | 15        | 7.39%   |
| NomadBSD    | 12        | 5.91%   |
| NetBSD      | 1         | 0.49%   |
| HardenedBSD | 1         | 0.49%   |
| FuryBSD     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 189       | 95.94%  |
| i386   | 7         | 3.55%   |
| macppc | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 47        | 22.82%  |
| Console      | 47        | 22.82%  |
| fvwm         | 25        | 12.14%  |
| MATE         | 21        | 10.19%  |
| XFCE         | 17        | 8.25%   |
| GNOME        | 12        | 5.83%   |
| Openbox      | 9         | 4.37%   |
| TWM          | 8         | 3.88%   |
| KDE5         | 7         | 3.4%    |
| i3           | 4         | 1.94%   |
| AwesomeWM    | 4         | 1.94%   |
| Picom        | 1         | 0.49%   |
| LXQt         | 1         | 0.49%   |
| LXDE         | 1         | 0.49%   |
| iwm          | 1         | 0.49%   |
| Cinnamon     | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 149       | 74.87%  |
| Console | 49        | 24.62%  |
| Wayland | 1         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 85        | 40.87%  |
| SLiM    | 65        | 31.25%  |
| LightDM | 20        | 9.62%   |
| XDM     | 12        | 5.77%   |
| SDDM    | 12        | 5.77%   |
| GDM     | 11        | 5.29%   |
| Ly      | 3         | 1.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 82        | 39.42%  |
| en_US            | 55        | 26.44%  |
| de_DE            | 31        | 14.9%   |
| C                | 30        | 14.42%  |
| en_GB            | 4         | 1.92%   |
| de_DE.ISO8859-1  | 2         | 0.96%   |
| pl_PL            | 1         | 0.48%   |
| en_IE            | 1         | 0.48%   |
| en_CA            | 1         | 0.48%   |
| de_DE.ISO8859-15 | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 153       | 76.12%  |
| BIOS | 48        | 23.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 104       | 51.49%  |
| Ufs    | 63        | 31.19%  |
| Ffs    | 28        | 13.86%  |
| Cd9660 | 7         | 3.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 179       | 89.5%   |
| MBR     | 20        | 10%     |
| Unknown | 1         | 0.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 74        | 37.56%  |
| Dell             | 23        | 11.68%  |
| Hewlett-Packard  | 13        | 6.6%    |
| Apple            | 13        | 6.6%    |
| Acer             | 10        | 5.08%   |
| Unknown          | 9         | 4.57%   |
| Fujitsu          | 8         | 4.06%   |
| Deciso           | 7         | 3.55%   |
| ASUSTek Computer | 7         | 3.55%   |
| TUXEDO           | 4         | 2.03%   |
| Sony             | 3         | 1.52%   |
| Notebook         | 3         | 1.52%   |
| Shuttle          | 2         | 1.02%   |
| Schenker         | 2         | 1.02%   |
| MSI              | 2         | 1.02%   |
| Toshiba          | 1         | 0.51%   |
| Panasonic        | 1         | 0.51%   |
| Packard Bell     | 1         | 0.51%   |
| MiTAC            | 1         | 0.51%   |
| Medion           | 1         | 0.51%   |
| Intel            | 1         | 0.51%   |
| Insyde           | 1         | 0.51%   |
| IBM              | 1         | 0.51%   |
| HUAWEI           | 1         | 0.51%   |
| HKC              | 1         | 0.51%   |
| Hampoo           | 1         | 0.51%   |
| GPD              | 1         | 0.51%   |
| Clevo            | 1         | 0.51%   |
| BESSTAR Tech     | 1         | 0.51%   |
| AMI              | 1         | 0.51%   |
| Alienware        | 1         | 0.51%   |
| AEWIN            | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 5.08%   |
| Deciso Netboard A20                        | 4         | 2.03%   |
| Shuttle DS437                              | 2         | 1.02%   |
| Lenovo ThinkPad X260 20F5S1H800            | 2         | 1.02%   |
| Lenovo ThinkPad T410s 291245G              | 2         | 1.02%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 2         | 1.02%   |
| HP ZBook 15 G4                             | 2         | 1.02%   |
| Dell Latitude E6540                        | 2         | 1.02%   |
| Dell Latitude E6500                        | 2         | 1.02%   |
| ASUS TUF Gaming FX505DT_FX505DT            | 2         | 1.02%   |
| Apple MacBookAir5,1                        | 2         | 1.02%   |
| TUXEDO Pulse 14 Gen1                       | 1         | 0.51%   |
| TUXEDO N13xWU                              | 1         | 0.51%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.51%   |
| Toshiba Satellite Pro L40                  | 1         | 0.51%   |
| Sony VPCM12M1E                             | 1         | 0.51%   |
| Sony VPCEJ1E1E                             | 1         | 0.51%   |
| Sony VGN-SZ3VWP_X                          | 1         | 0.51%   |
| Schenker SCHENKER_COMPACT15_17_SCO15_17M19 | 1         | 0.51%   |
| Schenker N13xWU                            | 1         | 0.51%   |
| Panasonic CF-C1BD06EFG                     | 1         | 0.51%   |
| Packard Bell EasyNote MH36                 | 1         | 0.51%   |
| Notebook N8xEJEK                           | 1         | 0.51%   |
| Notebook N7x0WU                            | 1         | 0.51%   |
| Notebook N13xWU                            | 1         | 0.51%   |
| MSI MS-1613                                | 1         | 0.51%   |
| MSI GT75VR 7RF                             | 1         | 0.51%   |
| MiTAC 5033                                 | 1         | 0.51%   |
| Medion P6812                               | 1         | 0.51%   |
| Lenovo ZIUS6                               | 1         | 0.51%   |
| Lenovo Z50-70 20354                        | 1         | 0.51%   |
| Lenovo V130-15IKB 81HN                     | 1         | 0.51%   |
| Lenovo U310                                | 1         | 0.51%   |
| Lenovo ThinkPad X61 7673AG4                | 1         | 0.51%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01      | 1         | 0.51%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00      | 1         | 0.51%   |
| Lenovo ThinkPad X270 20HNA004CD            | 1         | 0.51%   |
| Lenovo ThinkPad X260 20F5A28AUK            | 1         | 0.51%   |
| Lenovo ThinkPad X250 20CLS02000            | 1         | 0.51%   |
| Lenovo ThinkPad X240 20AMS2QDOC            | 1         | 0.51%   |
| Lenovo ThinkPad X240 20AMS2QD0C            | 1         | 0.51%   |
| Lenovo ThinkPad X240 20AMS0RR00            | 1         | 0.51%   |
| Lenovo ThinkPad X230 2325O76               | 1         | 0.51%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.51%   |
| Lenovo ThinkPad X230 232578G               | 1         | 0.51%   |
| Lenovo ThinkPad X230 23254G7               | 1         | 0.51%   |
| Lenovo ThinkPad X230 23244A9               | 1         | 0.51%   |
| Lenovo ThinkPad X220 4293AF4               | 1         | 0.51%   |
| Lenovo ThinkPad X220 4291OQ6               | 1         | 0.51%   |
| Lenovo ThinkPad X220 4291IR6               | 1         | 0.51%   |
| Lenovo ThinkPad X220 42915CG               | 1         | 0.51%   |
| Lenovo ThinkPad X201 3626HMG               | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003MGE   | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 6th 20KG0022US   | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR0068GE   | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7002CUK   | 1         | 0.51%   |
| Lenovo ThinkPad W541 20EGS04800            | 1         | 0.51%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 0.51%   |
| Lenovo ThinkPad T520 4243FS9               | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 60        | 30.46%  |
| Dell Latitude          | 16        | 8.12%   |
| Unknown                | 10        | 5.08%   |
| Fujitsu LIFEBOOK       | 7         | 3.55%   |
| Lenovo IdeaPad         | 4         | 2.03%   |
| Deciso Netboard        | 4         | 2.03%   |
| HP EliteBook           | 3         | 1.52%   |
| Dell Inspiron          | 3         | 1.52%   |
| Acer TravelMate        | 3         | 1.52%   |
| Acer Aspire            | 3         | 1.52%   |
| Shuttle DS437          | 2         | 1.02%   |
| HP ZBook               | 2         | 1.02%   |
| HP Laptop              | 2         | 1.02%   |
| Dell XPS               | 2         | 1.02%   |
| Dell Precision         | 2         | 1.02%   |
| ASUS TUF               | 2         | 1.02%   |
| Apple MacBookAir5      | 2         | 1.02%   |
| Acer Extensa           | 2         | 1.02%   |
| TUXEDO Pulse           | 1         | 0.51%   |
| TUXEDO N13xWU          | 1         | 0.51%   |
| TUXEDO Aura            | 1         | 0.51%   |
| Toshiba Satellite      | 1         | 0.51%   |
| Sony VPCM12M1E         | 1         | 0.51%   |
| Sony VPCEJ1E1E         | 1         | 0.51%   |
| Sony VGN-SZ3VWP        | 1         | 0.51%   |
| Schenker SCHENKER      | 1         | 0.51%   |
| Schenker N13xWU        | 1         | 0.51%   |
| Panasonic CF-C1BD06EFG | 1         | 0.51%   |
| Packard Bell EasyNote  | 1         | 0.51%   |
| Notebook N8xEJEK       | 1         | 0.51%   |
| Notebook N7x0WU        | 1         | 0.51%   |
| Notebook N13xWU        | 1         | 0.51%   |
| MSI MS-1613            | 1         | 0.51%   |
| MSI GT75VR             | 1         | 0.51%   |
| MiTAC 5033             | 1         | 0.51%   |
| Medion P6812           | 1         | 0.51%   |
| Lenovo ZIUS6           | 1         | 0.51%   |
| Lenovo Z50-70          | 1         | 0.51%   |
| Lenovo V130-15IKB      | 1         | 0.51%   |
| Lenovo U310            | 1         | 0.51%   |
| Lenovo ThinkBook       | 1         | 0.51%   |
| Lenovo Legion          | 1         | 0.51%   |
| Lenovo G550            | 1         | 0.51%   |
| Lenovo G50-45          | 1         | 0.51%   |
| Lenovo B570            | 1         | 0.51%   |
| Lenovo 3000            | 1         | 0.51%   |
| Intel SharkBay         | 1         | 0.51%   |
| Insyde Braswell        | 1         | 0.51%   |
| IBM ThinkPad           | 1         | 0.51%   |
| HUAWEI MACH-WX9        | 1         | 0.51%   |
| HKC NT11T              | 1         | 0.51%   |
| HP ProBook             | 1         | 0.51%   |
| HP OMEN                | 1         | 0.51%   |
| HP nx9010              | 1         | 0.51%   |
| HP Compaq              | 1         | 0.51%   |
| HP 655                 | 1         | 0.51%   |
| HP 255                 | 1         | 0.51%   |
| Hampoo NA123           | 1         | 0.51%   |
| GPD G1621-02           | 1         | 0.51%   |
| Fujitsu CELSIUS        | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 24        | 12.18%  |
| 2019    | 20        | 10.15%  |
| 2017    | 17        | 8.63%   |
| 2018    | 16        | 8.12%   |
| 2021    | 14        | 7.11%   |
| 2013    | 14        | 7.11%   |
| 2011    | 14        | 7.11%   |
| 2010    | 13        | 6.6%    |
| 2012    | 12        | 6.09%   |
| 2015    | 10        | 5.08%   |
| 2016    | 9         | 4.57%   |
| 2014    | 8         | 4.06%   |
| 2008    | 7         | 3.55%   |
| 2009    | 6         | 3.05%   |
| Unknown | 4         | 2.03%   |
| 2022    | 3         | 1.52%   |
| 2007    | 3         | 1.52%   |
| 2006    | 1         | 0.51%   |
| 2003    | 1         | 0.51%   |
| 2002    | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 197       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 197       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 72        | 36.36%  |
| 16.01-24.0  | 52        | 26.26%  |
| 4.01-8.0    | 44        | 22.22%  |
| 32.01-64.0  | 11        | 5.56%   |
| 2.01-3.0    | 8         | 4.04%   |
| 1.01-2.0    | 3         | 1.52%   |
| 0.51-1.0    | 3         | 1.52%   |
| 3.01-4.0    | 1         | 0.51%   |
| 24.01-32.0  | 1         | 0.51%   |
| 64.01-256.0 | 1         | 0.51%   |
| 0.01-0.5    | 1         | 0.51%   |
| 0           | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 117       | 57.92%  |
| 0.51-1.0   | 55        | 27.23%  |
| 1.01-2.0   | 16        | 7.92%   |
| 4.01-8.0   | 4         | 1.98%   |
| 2.01-3.0   | 4         | 1.98%   |
| Unknown    | 3         | 1.49%   |
| 24.01-32.0 | 1         | 0.5%    |
| 16.01-24.0 | 1         | 0.5%    |
| 0          | 1         | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 71.14%  |
| 2      | 44        | 21.89%  |
| 0      | 8         | 3.98%   |
| 3      | 6         | 2.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 70.35%  |
| Yes       | 59        | 29.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 92.39%  |
| No        | 15        | 7.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 86.87%  |
| No        | 26        | 13.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 56.78%  |
| No        | 86        | 43.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 197       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Berlin               | 21        | 10.1%   |
| Frankfurt am Main    | 9         | 4.33%   |
| Munich               | 6         | 2.88%   |
| Hamburg              | 6         | 2.88%   |
| Bedburg              | 6         | 2.88%   |
| Halle                | 4         | 1.92%   |
| Wernigerode          | 3         | 1.44%   |
| Markt Indersdorf     | 3         | 1.44%   |
| Leipzig              | 3         | 1.44%   |
| Bonn                 | 3         | 1.44%   |
| Zwingenberg          | 2         | 0.96%   |
| Wissen               | 2         | 0.96%   |
| Stuttgart            | 2         | 0.96%   |
| Reutlingen           | 2         | 0.96%   |
| Regensburg           | 2         | 0.96%   |
| Potsdam              | 2         | 0.96%   |
| Pleidelsheim         | 2         | 0.96%   |
| Nuremberg            | 2         | 0.96%   |
| Neuss                | 2         | 0.96%   |
| Gummersbach          | 2         | 0.96%   |
| Giessen              | 2         | 0.96%   |
| Detmold              | 2         | 0.96%   |
| Bietigheim-Bissingen | 2         | 0.96%   |
| Bielefeld            | 2         | 0.96%   |
| Betzdorf             | 2         | 0.96%   |
| Bensheim             | 2         | 0.96%   |
| Aachen               | 2         | 0.96%   |
| Zwickau              | 1         | 0.48%   |
| Wolfsburg            | 1         | 0.48%   |
| Wilhelmshaven        | 1         | 0.48%   |
| Wetzlar              | 1         | 0.48%   |
| Wenzenbach           | 1         | 0.48%   |
| Weinbohla            | 1         | 0.48%   |
| Weimar               | 1         | 0.48%   |
| Warendorf            | 1         | 0.48%   |
| Vohringen            | 1         | 0.48%   |
| Versmold             | 1         | 0.48%   |
| Tamm                 | 1         | 0.48%   |
| Strullendorf         | 1         | 0.48%   |
| Strausberg           | 1         | 0.48%   |
| Stade                | 1         | 0.48%   |
| Solingen             | 1         | 0.48%   |
| Sinzig               | 1         | 0.48%   |
| Simmern              | 1         | 0.48%   |
| Siegen               | 1         | 0.48%   |
| Seelze               | 1         | 0.48%   |
| Schwetzingen         | 1         | 0.48%   |
| Sankt Augustin       | 1         | 0.48%   |
| Sandhausen           | 1         | 0.48%   |
| Salzwedel            | 1         | 0.48%   |
| Rudersberg           | 1         | 0.48%   |
| Rodgau               | 1         | 0.48%   |
| Rodenberg            | 1         | 0.48%   |
| Remseck am Neckar    | 1         | 0.48%   |
| Ransbach-Baumbach    | 1         | 0.48%   |
| Ramerberg            | 1         | 0.48%   |
| Prien am Chiemsee    | 1         | 0.48%   |
| Oldenburg            | 1         | 0.48%   |
| Offenburg            | 1         | 0.48%   |
| Oberkirch            | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 60     | 20.54%  |
| WDC                 | 20        | 22     | 8.93%   |
| Crucial             | 16        | 21     | 7.14%   |
| Seagate             | 15        | 17     | 6.7%    |
| Transcend           | 12        | 12     | 5.36%   |
| SanDisk             | 12        | 14     | 5.36%   |
| NVMe                | 11        | 19     | 4.91%   |
| Kingston            | 11        | 13     | 4.91%   |
| Toshiba             | 10        | 23     | 4.46%   |
| Intel               | 10        | 10     | 4.46%   |
| Micron Technology   | 7         | 7      | 3.13%   |
| Hitachi             | 7         | 10     | 3.13%   |
| Apple               | 7         | 7      | 3.13%   |
| SPCC                | 4         | 5      | 1.79%   |
| OCZ                 | 4         | 6      | 1.79%   |
| Fujitsu             | 4         | 4      | 1.79%   |
| SK hynix            | 3         | 4      | 1.34%   |
| KIOXIA              | 3         | 3      | 1.34%   |
| Hoodisk             | 3         | 3      | 1.34%   |
| HGST                | 3         | 5      | 1.34%   |
| LITEON              | 2         | 2      | 0.89%   |
| Kston               | 2         | 2      | 0.89%   |
| Intenso             | 2         | 3      | 0.89%   |
| A-DATA Technology   | 2         | 3      | 0.89%   |
| MyDigitalSSD        | 1         | 1      | 0.45%   |
| Mushkin             | 1         | 1      | 0.45%   |
| Lenovo              | 1         | 1      | 0.45%   |
| Gigabyte Technology | 1         | 1      | 0.45%   |
| FORESEE             | 1         | 1      | 0.45%   |
| Dogfish             | 1         | 1      | 0.45%   |
| Corsair             | 1         | 1      | 0.45%   |
| BIWIN               | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 3         | 1.29%   |
| Transcend TS256GMTE652T2 256GB       | 3         | 1.29%   |
| Samsung SSD 860 EVO 500GB            | 3         | 1.29%   |
| Samsung SSD 850 EVO 500GB            | 3         | 1.29%   |
| Samsung SSD 840 EVO 250GB            | 3         | 1.29%   |
| Hoodisk SSD 128GB                    | 3         | 1.29%   |
| Transcend TS240GMTS420S 240GB        | 2         | 0.86%   |
| SPCC Solid State Disk 1TB            | 2         | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.86%   |
| SanDisk SDSSDP064G 64GB              | 2         | 0.86%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.86%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.86%   |
| Samsung SSD 840 PRO Series 256GB     | 2         | 0.86%   |
| Samsung MZ7LN256HCHP-000L7 256GB     | 2         | 0.86%   |
| NVMe WDC PC SN730 SDB 256GB          | 2         | 0.86%   |
| NVMe SAMSUNG MZVLW256 256GB          | 2         | 0.86%   |
| Micron 2200V_MTFDHBA512TCK 512GB     | 2         | 0.86%   |
| LITEON LCH-128V2S 128GB              | 2         | 0.86%   |
| Kingston SA400S37480G 480GB          | 2         | 0.86%   |
| Intel SSDSC2BF240A5L 240GB           | 2         | 0.86%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 0.86%   |
| Hitachi HTS543225L9A300 250GB        | 2         | 0.86%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.86%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.86%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.86%   |
| Crucial CT240M500SSD3 240GB          | 2         | 0.86%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.86%   |
| Crucial CT1000P1SSD8 1TB             | 2         | 0.86%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.86%   |
| Apple SSD TS128E 121GB               | 2         | 0.86%   |
| Apple SSD SM0512G 500GB              | 2         | 0.86%   |
| WDC WDS500G1B0A-00H9H0 500GB         | 1         | 0.43%   |
| WDC WDS250G1B0A-00H9H0 250GB         | 1         | 0.43%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.43%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPVX-16V0TT3 500GB         | 1         | 0.43%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.43%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 1         | 0.43%   |
| WDC WD5000BPKT-00PK4T0 500GB         | 1         | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.43%   |
| WDC WD2500BEVT-75ZCT2 250GB          | 1         | 0.43%   |
| WDC WD2500BEVS-08VAT2 250GB          | 1         | 0.43%   |
| WDC WD20NMVW-11EDZS7 2TB             | 1         | 0.43%   |
| WDC WD20NMVW-11AV3S2 2TB             | 1         | 0.43%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.43%   |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.43%   |
| WDC WD1600BEVE-00WZT0 160GB          | 1         | 0.43%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.43%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.43%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB   | 1         | 0.43%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.43%   |
| Transcend TS512GMTS952T2 512GB       | 1         | 0.43%   |
| Transcend TS256GMSA230S 256GB        | 1         | 0.43%   |
| Transcend TS128GMSA370S 128GB        | 1         | 0.43%   |
| Transcend TS120GMTS820S 120GB        | 1         | 0.43%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB | 1         | 0.43%   |
| Toshiba THNSNC128GBSJ                | 1         | 0.43%   |
| Toshiba THNSFJ256GCSU 256GB          | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 26.32%  |
| WDC                 | 14        | 16     | 24.56%  |
| NVMe                | 9         | 17     | 15.79%  |
| Hitachi             | 7         | 10     | 12.28%  |
| Toshiba             | 4         | 5      | 7.02%   |
| Fujitsu             | 4         | 4      | 7.02%   |
| HGST                | 3         | 5      | 5.26%   |
| Samsung Electronics | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 42     | 25.78%  |
| Crucial             | 14        | 19     | 10.94%  |
| SanDisk             | 12        | 14     | 9.38%   |
| Intel               | 10        | 10     | 7.81%   |
| Transcend           | 9         | 9      | 7.03%   |
| Kingston            | 9         | 11     | 7.03%   |
| Apple               | 7         | 7      | 5.47%   |
| OCZ                 | 4         | 6      | 3.13%   |
| Micron Technology   | 4         | 4      | 3.13%   |
| WDC                 | 3         | 3      | 2.34%   |
| Toshiba             | 3         | 6      | 2.34%   |
| SPCC                | 3         | 3      | 2.34%   |
| Hoodisk             | 3         | 3      | 2.34%   |
| SK hynix            | 2         | 3      | 1.56%   |
| LITEON              | 2         | 2      | 1.56%   |
| Kston               | 2         | 2      | 1.56%   |
| Intenso             | 2         | 3      | 1.56%   |
| MyDigitalSSD        | 1         | 1      | 0.78%   |
| Mushkin             | 1         | 1      | 0.78%   |
| FORESEE             | 1         | 1      | 0.78%   |
| Dogfish             | 1         | 1      | 0.78%   |
| Corsair             | 1         | 1      | 0.78%   |
| A-DATA Technology   | 1         | 1      | 0.78%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 117       | 153    | 56.25%  |
| HDD  | 54        | 75     | 25.96%  |
| NVMe | 37        | 55     | 17.79%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 228    | 81.31%  |
| NVMe | 37        | 55     | 18.69%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 181    | 80.81%  |
| 0.51-1.0   | 20        | 26     | 11.63%  |
| 1.01-2.0   | 12        | 20     | 6.98%   |
| 4.01-10.0  | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 68        | 32.69%  |
| 1-20           | 56        | 26.92%  |
| 251-500        | 44        | 21.15%  |
| 51-100         | 15        | 7.21%   |
| 501-1000       | 12        | 5.77%   |
| 21-50          | 8         | 3.85%   |
| 1001-2000      | 3         | 1.44%   |
| More than 3000 | 1         | 0.48%   |
| Unknown        | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 164       | 79.61%  |
| 21-50          | 18        | 8.74%   |
| 51-100         | 11        | 5.34%   |
| 101-250        | 7         | 3.4%    |
| 251-500        | 3         | 1.46%   |
| More than 3000 | 1         | 0.49%   |
| 501-1000       | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 9.09%   |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 9.09%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 4.55%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 1         | 4      | 4.55%   |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 4.55%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 4.55%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 4.55%   |
| SanDisk SSD P4 64GB                          | 1         | 1      | 4.55%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 4.55%   |
| Micron Technology 1100 SATA 256GB            | 1         | 1      | 4.55%   |
| Kingston SV300S37A240G 240GB                 | 1         | 1      | 4.55%   |
| Kingston SNV425S264GB                        | 1         | 1      | 4.55%   |
| Intel SSDSC2KF256H6L 256GB                   | 1         | 1      | 4.55%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 2      | 4.55%   |
| Fujitsu MHW2160BH 160GB                      | 1         | 1      | 4.55%   |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 4.55%   |
| Corsair Force GT 120GB                       | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 8      | 22.73%  |
| Seagate             | 4         | 4      | 18.18%  |
| Toshiba             | 2         | 5      | 9.09%   |
| SanDisk             | 2         | 2      | 9.09%   |
| Kingston            | 2         | 2      | 9.09%   |
| WDC                 | 1         | 1      | 4.55%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| Crucial             | 1         | 1      | 4.55%   |
| Corsair             | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 5         | 8      | 41.67%  |
| Seagate | 4         | 4      | 33.33%  |
| WDC     | 1         | 1      | 8.33%   |
| Toshiba | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 15     | 54.55%  |
| SSD  | 9         | 12     | 40.91%  |
| NVMe | 1         | 1      | 4.55%   |

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
| Works    | 166       | 236    | 83%     |
| Malfunc  | 22        | 28     | 11%     |
| Detected | 12        | 19     | 6%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 68.16%  |
| Samsung Electronics              | 23        | 10.31%  |
| AMD                              | 14        | 6.28%   |
| Toshiba                          | 5         | 2.24%   |
| SanDisk                          | 5         | 2.24%   |
| Micron Technology                | 3         | 1.35%   |
| Unknown                          | 3         | 1.35%   |
| SK hynix                         | 2         | 0.9%    |
| Phison Electronics               | 2         | 0.9%    |
| Nvidia                           | 2         | 0.9%    |
| Micron/Crucial Technology        | 2         | 0.9%    |
| KIOXIA                           | 2         | 0.9%    |
| Kingston Technology Company      | 2         | 0.9%    |
| ADATA Technology                 | 2         | 0.9%    |
| ULi Electronics                  | 1         | 0.45%   |
| Silicon Motion                   | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Lenovo                           | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 19        | 7.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 17        | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 17        | 7.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 16        | 6.72%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 14        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 10        | 4.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 9         | 3.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 3.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 8         | 3.36%   |
| Unknown                                                                                | 8         | 3.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 7         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 7         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 7         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 2.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 2.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 2.1%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.68%   |
| Samsung SM951 AHCI                                                                     | 3         | 1.26%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.26%   |
| Toshiba XG6 NVMe SSD Controller                                                        | 2         | 0.84%   |
| Toshiba unknown                                                                        | 2         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 0.84%   |
| ULi M5229 IDE                                                                          | 1         | 0.42%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 0.42%   |
| SK hynix hynix unknown                                                                 | 1         | 0.42%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 0.42%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.42%   |
| SanDisk PC SN530                                                                       | 1         | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.42%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 0.42%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 0.42%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.42%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.42%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.42%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 0.42%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 0.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 0.42%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 0.42%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.42%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 0.42%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 1         | 0.42%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 0.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 1         | 0.42%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.42%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 1         | 0.42%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                          | 1         | 0.42%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 157       | 68.26%  |
| NVMe | 45        | 19.57%  |
| IDE  | 23        | 10%     |
| RAID | 5         | 2.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 174       | 88.32%  |
| AMD     | 22        | 11.17%  |
| PowerPC | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                            | 8         | 4.04%   |
| Intel CPU Version                                            | 7         | 3.54%   |
| Intel Core i5-6300U CPU @ 2.40GHz                            | 7         | 3.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz                            | 6         | 3.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz                            | 6         | 3.03%   |
| Intel Core i5-5300U CPU @ 2.30GHz                            | 4         | 2.02%   |
| Intel Core i7-9750H CPU @ 2.60GHz                            | 3         | 1.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz                            | 3         | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz                            | 3         | 1.52%   |
| Intel Core i7-3520M CPU @ 2.90GHz                            | 3         | 1.52%   |
| Intel Core i5-4250U CPU @ 1.30GHz                            | 3         | 1.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz                            | 3         | 1.52%   |
| Intel Core i5-3317U CPU @ 1.70GHz                            | 3         | 1.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz                            | 3         | 1.52%   |
| Intel Core i5 CPU M 560 @ 2.67GHz                            | 3         | 1.52%   |
| Intel Core i3-4005U CPU @ 1.70GHz                            | 3         | 1.52%   |
| Intel Core 2 Duo                                             | 3         | 1.52%   |
| AMD Ryzen Embedded V1500B                                    | 3         | 1.52%   |
| AMD EPYC 3201 8-Core Processor                               | 3         | 1.52%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz                         | 2         | 1.01%   |
| Intel Genuine CPU                                            | 2         | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz                            | 2         | 1.01%   |
| Intel Core i7-6600U CPU @ 2.60GHz                            | 2         | 1.01%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz                           | 2         | 1.01%   |
| Intel Core i7-4610M CPU @ 3.00GHz                            | 2         | 1.01%   |
| Intel Core i7-2860QM CPU @ 2.50GHz                           | 2         | 1.01%   |
| Intel Core i7-2677M CPU @ 1.80GHz                            | 2         | 1.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz                           | 2         | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz                            | 2         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz                            | 2         | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz                            | 2         | 1.01%   |
| Intel Core i5-4300U CPU @ 1.90GHz                            | 2         | 1.01%   |
| Intel Core i5-4200U CPU @ 1.60GHz                            | 2         | 1.01%   |
| Intel Core i5-4200M CPU @ 2.50GHz                            | 2         | 1.01%   |
| Intel Core i5-2540M CPU @ 2.60GHz                            | 2         | 1.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz                            | 2         | 1.01%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                            | 2         | 1.01%   |
| Intel Core i3-2330M CPU @ 2.20GHz                            | 2         | 1.01%   |
| Intel Celeron CPU N3160 @ 1.60GHz                            | 2         | 1.01%   |
| Intel Celeron CPU 1037U @ 1.80GHz                            | 2         | 1.01%   |
| AMD Ryzen 7 5700U with Radeon Graphics                       | 2         | 1.01%   |
| AMD Ryzen 7 4800H with Radeon Graphics                       | 2         | 1.01%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx                | 2         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx                | 2         | 1.01%   |
| PowerPC 7447A (Revision 0x105)                               | 1         | 0.51%   |
| Intel Pentium(                                               | 1         | 0.51%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                     | 1         | 0.51%   |
| Intel Pentium M processor 1.60GHz ("GenuineIntel" 686-class) | 1         | 0.51%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz                       | 1         | 0.51%   |
| Intel Pentium CPU N3710 @ 1.60GHz                            | 1         | 0.51%   |
| Intel Pentium CPU N3520 @ 2.16GHz                            | 1         | 0.51%   |
| Intel Pentium CPU B940 @ 2.00GHz                             | 1         | 0.51%   |
| Intel Pentium 4                                              | 1         | 0.51%   |
| Intel Pentium 3558U @ 1.70GHz                                | 1         | 0.51%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz                             | 1         | 0.51%   |
| Intel Core M-5Y10c CPU @ 0.80GHz                             | 1         | 0.51%   |
| Intel Core i7-9750HF CPU @ 2.60GHz                           | 1         | 0.51%   |
| Intel Core i7-8850H CPU @ 2.60GHz                            | 1         | 0.51%   |
| Intel Core i7-8650U CPU @ 1.90GHz                            | 1         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                           | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 69        | 35.03%  |
| Intel Core i7        | 46        | 23.35%  |
| Other                | 12        | 6.09%   |
| Intel Core i3        | 10        | 5.08%   |
| Intel Core 2 Duo     | 10        | 5.08%   |
| Intel Celeron        | 8         | 4.06%   |
| Intel Pentium        | 5         | 2.54%   |
| AMD Ryzen 7          | 5         | 2.54%   |
| AMD Ryzen 5          | 5         | 2.54%   |
| Intel Atom           | 4         | 2.03%   |
| AMD EPYC             | 4         | 2.03%   |
| AMD Ryzen Embedded   | 3         | 1.52%   |
| Intel Xeon           | 2         | 1.02%   |
| Intel Genuine        | 2         | 1.02%   |
| Intel Pentium Silver | 1         | 0.51%   |
| Intel Pentium M      | 1         | 0.51%   |
| Intel Pentium Dual   | 1         | 0.51%   |
| Intel Pentium 4      | 1         | 0.51%   |
| Intel Core m3        | 1         | 0.51%   |
| Intel Core M         | 1         | 0.51%   |
| Intel Core 2 Solo    | 1         | 0.51%   |
| Intel Core 2         | 1         | 0.51%   |
| Intel Celeron M      | 1         | 0.51%   |
| AMD Ryzen 7 PRO      | 1         | 0.51%   |
| AMD E2               | 1         | 0.51%   |
| AMD A6               | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 106       | 53.54%  |
| 4       | 45        | 22.73%  |
| Unknown | 14        | 7.07%   |
| 8       | 12        | 6.06%   |
| 1       | 8         | 4.04%   |
| 6       | 7         | 3.54%   |
| 16      | 5         | 2.53%   |
| 12      | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 189       | 95.45%  |
| Unknown | 5         | 2.53%   |
| 2       | 4         | 2.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 135       | 68.53%  |
| 1       | 42        | 21.32%  |
| Unknown | 20        | 10.15%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 35        | 17.77%  |
| Haswell       | 27        | 13.71%  |
| SandyBridge   | 21        | 10.66%  |
| IvyBridge     | 20        | 10.15%  |
| Penryn        | 14        | 7.11%   |
| Skylake       | 11        | 5.58%   |
| Broadwell     | 10        | 5.08%   |
| Unknown       | 8         | 4.06%   |
| Zen           | 7         | 3.55%   |
| Westmere      | 7         | 3.55%   |
| Core          | 6         | 3.05%   |
| Silvermont    | 5         | 2.54%   |
| Zen+          | 4         | 2.03%   |
| Zen 2         | 4         | 2.03%   |
| Bonnell       | 4         | 2.03%   |
| P6            | 2         | 1.02%   |
| NetBurst      | 2         | 1.02%   |
| Goldmont      | 2         | 1.02%   |
| TigerLake     | 1         | 0.51%   |
| Puma          | 1         | 0.51%   |
| Piledriver    | 1         | 0.51%   |
| IceLake       | 1         | 0.51%   |
| Goldmont plus | 1         | 0.51%   |
| Geode         | 1         | 0.51%   |
| CometLake     | 1         | 0.51%   |
| Bobcat        | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 154       | 71.63%  |
| Nvidia                           | 40        | 18.6%   |
| AMD                              | 19        | 8.84%   |
| Trident Microsystems             | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 9.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 8.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 7.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 4.95%   |
| Intel UHD Graphics 620                                                                   | 9         | 4.05%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 3.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.8%    |
| Intel HD Graphics 620                                                                    | 4         | 1.8%    |
| AMD Renoir                                                                               | 4         | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.8%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.35%   |
| AMD Lucienne                                                                             | 3         | 1.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.9%    |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.9%    |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.9%    |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.9%    |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.9%    |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.9%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.9%    |
| Intel HD Graphics P630                                                                   | 2         | 0.9%    |
| Intel HD Graphics 500                                                                    | 2         | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.9%    |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 2         | 0.9%    |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                | 1         | 0.45%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.45%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.45%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.45%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.45%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.45%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.45%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.45%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                                 | 1         | 0.45%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.45%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.45%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.45%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.45%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.45%   |
| Nvidia GF108GLM [Quadro 1000M]                                                           | 1         | 0.45%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.45%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.45%   |
| Nvidia G98M [GeForce G 103M]                                                             | 1         | 0.45%   |
| Nvidia G86GLM [Quadro FX 360M]                                                           | 1         | 0.45%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 1         | 0.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.45%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.45%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.45%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 113       | 57.36%  |
| Intel + Nvidia           | 20        | 10.15%  |
| 2 x Intel                | 17        | 8.63%   |
| 1 x Nvidia               | 17        | 8.63%   |
| 1 x AMD                  | 12        | 6.09%   |
| Other                    | 9         | 4.57%   |
| Intel + AMD              | 4         | 2.03%   |
| AMD + Nvidia             | 3         | 1.52%   |
| 1 x Trident Microsystems | 1         | 0.51%   |
| 1 x SiS                  | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 165       | 82.91%  |
| Unknown     | 21        | 10.55%  |
| Proprietary | 13        | 6.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 93.43%  |
| 0.01-0.5   | 6         | 3.03%   |
| 1.01-2.0   | 3         | 1.52%   |
| 7.01-8.0   | 2         | 1.01%   |
| 3.01-4.0   | 2         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| LG Display           | 29        | 21.32%  |
| AU Optronics         | 29        | 21.32%  |
| Chimei Innolux       | 13        | 9.56%   |
| Apple                | 11        | 8.09%   |
| Lenovo               | 10        | 7.35%   |
| Samsung Electronics  | 9         | 6.62%   |
| BOE                  | 8         | 5.88%   |
| Dell                 | 4         | 2.94%   |
| Sharp                | 3         | 2.21%   |
| PANDA                | 3         | 2.21%   |
| Goldstar             | 3         | 2.21%   |
| BenQ                 | 2         | 1.47%   |
| AOC                  | 2         | 1.47%   |
| Ancor Communications | 2         | 1.47%   |
| Toshiba              | 1         | 0.74%   |
| Panasonic            | 1         | 0.74%   |
| LTM                  | 1         | 0.74%   |
| LG Philips           | 1         | 0.74%   |
| JDI                  | 1         | 0.74%   |
| InfoVision           | 1         | 0.74%   |
| Iiyama               | 1         | 0.74%   |
| Eizo                 | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 3         | 2.21%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch               | 3         | 2.21%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 3         | 2.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 2.21%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 3         | 2.21%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch               | 2         | 1.47%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 2         | 1.47%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch           | 2         | 1.47%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.47%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 2         | 1.47%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 1.47%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 1.47%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 1.47%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 2         | 1.47%   |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                  | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch         | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 1.47%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.74%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 1         | 0.74%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 340x190mm 15.3-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC374A 3200x1800 290x170mm 13.2-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC324A 1366x768 290x170mm 13.2-inch  | 1         | 0.74%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 290x170mm 13.2-inch               | 1         | 0.74%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 1         | 0.74%   |
| LTM LCD Monitor LTM3937 720x1280 130x80mm 6.0-inch                    | 1         | 0.74%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD059E 1920x1080 380x210mm 17.1-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0545 3200x1800 290x170mm 13.2-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD04D5 1920x1080 340x190mm 15.3-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD03DB 1366x768 350x190mm 15.7-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD037E 1920x1080 350x190mm 15.7-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD034C 1366x768 290x160mm 13.0-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD031B 1366x768 310x170mm 13.9-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD02F1 1366x768 340x190mm 15.3-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD01AB 1280x800 260x160mm 12.0-inch           | 1         | 0.74%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 0.74%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch               | 1         | 0.74%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 1         | 0.74%   |
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                 | 1         | 0.74%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch           | 1         | 0.74%   |
| Iiyama PLE2483H IVM6113 1920x1080 530x300mm 24.0-inch                 | 1         | 0.74%   |
| Goldstar W2242 GSM5677 1680x1050 490x320mm 23.0-inch                  | 1         | 0.74%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch           | 1         | 0.74%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 34.33%  |
| 1366x768 (WXGA)    | 40        | 29.85%  |
| 1280x800 (WXGA)    | 9         | 6.72%   |
| 3840x2160 (4K)     | 7         | 5.22%   |
| 1600x900 (HD+)     | 6         | 4.48%   |
| 2560x1440 (QHD)    | 5         | 3.73%   |
| 1440x900 (WXGA+)   | 5         | 3.73%   |
| 1920x1200 (WUXGA)  | 3         | 2.24%   |
| 3200x1800 (QHD+)   | 2         | 1.49%   |
| 1024x768 (XGA)     | 2         | 1.49%   |
| 720x1280           | 1         | 0.75%   |
| 3000x2000          | 1         | 0.75%   |
| 2880x1800          | 1         | 0.75%   |
| 2880x1620          | 1         | 0.75%   |
| 2560x1600          | 1         | 0.75%   |
| 2560x1080          | 1         | 0.75%   |
| 1920x540           | 1         | 0.75%   |
| 1680x1050 (WSXGA+) | 1         | 0.75%   |
| 1280x1024 (SXGA)   | 1         | 0.75%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 42        | 31.11%  |
| 15      | 36        | 26.67%  |
| 12      | 22        | 16.3%   |
| 24      | 6         | 4.44%   |
| 14      | 6         | 4.44%   |
| 17      | 5         | 3.7%    |
| 11      | 5         | 3.7%    |
| 27      | 4         | 2.96%   |
| 23      | 3         | 2.22%   |
| Unknown | 2         | 1.48%   |
| 34      | 1         | 0.74%   |
| 32      | 1         | 0.74%   |
| 31      | 1         | 0.74%   |
| 6       | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 46.67%  |
| 201-300     | 49        | 36.3%   |
| 501-600     | 11        | 8.15%   |
| 351-400     | 4         | 2.96%   |
| 701-800     | 2         | 1.48%   |
| 601-700     | 2         | 1.48%   |
| Unknown     | 2         | 1.48%   |
| 401-500     | 1         | 0.74%   |
| 101-200     | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 101       | 78.29%  |
| 16/10   | 19        | 14.73%  |
| 4/3     | 3         | 2.33%   |
| 3/2     | 2         | 1.55%   |
| Unknown | 2         | 1.55%   |
| 5/4     | 1         | 0.78%   |
| 21/9    | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 37        | 27.21%  |
| 91-100         | 27        | 19.85%  |
| 61-70          | 22        | 16.18%  |
| 71-80          | 10        | 7.35%   |
| 101-110        | 10        | 7.35%   |
| 201-250        | 7         | 5.15%   |
| 51-60          | 5         | 3.68%   |
| 301-350        | 4         | 2.94%   |
| 121-130        | 4         | 2.94%   |
| 351-500        | 3         | 2.21%   |
| 251-300        | 3         | 2.21%   |
| Unknown        | 2         | 1.47%   |
| 1-40           | 1         | 0.74%   |
| 141-150        | 1         | 0.74%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 63        | 47.73%  |
| 101-120       | 24        | 18.18%  |
| 51-100        | 19        | 14.39%  |
| 161-240       | 16        | 12.12%  |
| More than 240 | 8         | 6.06%   |
| Unknown       | 2         | 1.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 115       | 57.21%  |
| 0     | 72        | 35.82%  |
| 2     | 13        | 6.47%   |
| 3     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 141       | 46.23%  |
| Realtek Semiconductor             | 61        | 20%     |
| Qualcomm Atheros                  | 28        | 9.18%   |
| Broadcom                          | 24        | 7.87%   |
| Ericsson Business Mobile Networks | 9         | 2.95%   |
| AMD                               | 7         | 2.3%    |
| Ralink Technology                 | 5         | 1.64%   |
| Edimax Technology                 | 4         | 1.31%   |
| Marvell Technology Group          | 3         | 0.98%   |
| Google                            | 3         | 0.98%   |
| TP-Link                           | 2         | 0.66%   |
| Sierra Wireless                   | 2         | 0.66%   |
| Ralink                            | 2         | 0.66%   |
| Nvidia                            | 2         | 0.66%   |
| ULi Electronics                   | 1         | 0.33%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.33%   |
| National Semiconductor            | 1         | 0.33%   |
| Micro Star International          | 1         | 0.33%   |
| MediaTek                          | 1         | 0.33%   |
| JMicron Technology                | 1         | 0.33%   |
| Huawei Technologies               | 1         | 0.33%   |
| Hewlett-Packard                   | 1         | 0.33%   |
| D-Link System                     | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |
| Aquantia                          | 1         | 0.33%   |
| Apple                             | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 48        | 12.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 24        | 6.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 15        | 3.76%   |
| Intel Wireless 8260                                                         | 11        | 2.76%   |
| Intel Wireless 7265                                                         | 11        | 2.76%   |
| Intel Wireless 8265 / 8275                                                  | 10        | 2.51%   |
| Intel I210 Gigabit Network Connection                                       | 10        | 2.51%   |
| Intel Centrino Ultimate-N 6300                                              | 10        | 2.51%   |
| Intel Wi-Fi 6 AX200                                                         | 9         | 2.26%   |
| Intel Wireless 7260                                                         | 8         | 2.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 7         | 1.75%   |
| Intel I211 Gigabit Network Connection                                       | 7         | 1.75%   |
| Intel Ethernet Connection I219-LM                                           | 7         | 1.75%   |
| Intel Ethernet Connection I217-LM                                           | 7         | 1.75%   |
| Intel 82577LM Gigabit Network Connection                                    | 7         | 1.75%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                   | 7         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 6         | 1.5%    |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 6         | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 5         | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 4         | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 1%      |
| Intel Wireless-AC 9260                                                      | 4         | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 1%      |
| Intel Ethernet Connection (4) I219-V                                        | 4         | 1%      |
| Intel Ethernet Connection (3) I218-LM                                       | 4         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                             | 4         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 3         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 3         | 0.75%   |
| Intel Ethernet Connection I218-LM                                           | 3         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 3         | 0.75%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 3         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                    | 3         | 0.75%   |
| Google Nexus/Pixel Device (tether)                                          | 3         | 0.75%   |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III | 3         | 0.75%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 3         | 0.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                         | 3         | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 2         | 0.5%    |
| Sierra Wireless EM7455                                                      | 2         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 2         | 0.5%    |
| Ralink RT5370 Wireless Adapter                                              | 2         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 0.5%    |
| Nvidia MCP79 Ethernet                                                       | 2         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                     | 2         | 0.5%    |
| Intel Wireless 3165                                                         | 2         | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 2         | 0.5%    |
| Intel Ultimate N WiFi Link 5300                                             | 2         | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 2         | 0.5%    |
| Intel Ethernet Connection I219-V                                            | 2         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                                       | 2         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                        | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                       | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                       | 2         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                                       | 2         | 0.5%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 2         | 0.5%    |
| Intel Centrino Advanced-N 6235                                              | 2         | 0.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                           | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 115       | 60.53%  |
| Qualcomm Atheros         | 25        | 13.16%  |
| Broadcom                 | 17        | 8.95%   |
| Realtek Semiconductor    | 15        | 7.89%   |
| Ralink Technology        | 5         | 2.63%   |
| Edimax Technology        | 4         | 2.11%   |
| TP-Link                  | 2         | 1.05%   |
| Sierra Wireless          | 2         | 1.05%   |
| Ralink                   | 2         | 1.05%   |
| Micro Star International | 1         | 0.53%   |
| MediaTek                 | 1         | 0.53%   |
| ASUSTek Computer         | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 7.85%   |
| Intel Wireless 8260                                            | 11        | 5.76%   |
| Intel Wireless 7265                                            | 11        | 5.76%   |
| Intel Wireless 8265 / 8275                                     | 10        | 5.24%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 5.24%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 4.71%   |
| Intel Wireless 7260                                            | 8         | 4.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 3.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.09%   |
| Intel Wireless-AC 9260                                         | 4         | 2.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 2.09%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 2.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.57%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.57%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3         | 1.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.05%   |
| Sierra Wireless EM7455                                         | 2         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.05%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.05%   |
| Intel Wireless 3165                                            | 2         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.05%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 2         | 1.05%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 1.05%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.05%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.52%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.52%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.52%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.52%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 0.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.52%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.52%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.52%   |
| Micro Star International RT2573                                | 1         | 0.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.52%   |
| Intel WiFi Link 5100                                           | 1         | 0.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.52%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection      | 1         | 0.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 0.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 95        | 49.74%  |
| Realtek Semiconductor    | 58        | 30.37%  |
| Broadcom                 | 13        | 6.81%   |
| AMD                      | 7         | 3.66%   |
| Qualcomm Atheros         | 6         | 3.14%   |
| Marvell Technology Group | 3         | 1.57%   |
| Google                   | 3         | 1.57%   |
| Nvidia                   | 2         | 1.05%   |
| National Semiconductor   | 1         | 0.52%   |
| JMicron Technology       | 1         | 0.52%   |
| Aquantia                 | 1         | 0.52%   |
| Apple                    | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 24.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 12.44%  |
| Intel I210 Gigabit Network Connection                             | 10        | 5.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.63%   |
| Intel I211 Gigabit Network Connection                             | 7         | 3.63%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 3.63%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 3.63%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 3.63%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 7         | 3.63%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.07%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.55%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.55%   |
| Google Nexus/Pixel Device (tether)                                | 3         | 1.55%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.04%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.04%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.04%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.04%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 1.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.52%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.52%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.52%   |
| Intel I210 Gigabit Backplane Connection                           | 1         | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.52%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.52%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.52%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 1         | 0.52%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.52%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 0.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.52%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 182       | 49.32%  |
| WiFi     | 172       | 46.61%  |
| Modem    | 8         | 2.17%   |
| Unknown  | 7         | 1.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 154       | 54.8%   |
| WiFi     | 120       | 42.7%   |
| Unknown  | 6         | 2.14%   |
| Modem    | 1         | 0.36%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 148       | 74.75%  |
| 1     | 25        | 12.63%  |
| 6     | 11        | 5.56%   |
| 3     | 6         | 3.03%   |
| 5     | 3         | 1.52%   |
| 0     | 2         | 1.01%   |
| 8     | 1         | 0.51%   |
| 7     | 1         | 0.51%   |
| 4     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 183       | 91.5%   |
| Yes  | 17        | 8.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 50%     |
| Broadcom                        | 14        | 12.28%  |
| Qualcomm Atheros Communications | 12        | 10.53%  |
| Apple                           | 11        | 9.65%   |
| Realtek Semiconductor           | 6         | 5.26%   |
| Lite-On Technology              | 3         | 2.63%   |
| Foxconn / Hon Hai               | 3         | 2.63%   |
| Dell                            | 2         | 1.75%   |
| Alps Electric                   | 2         | 1.75%   |
| IMC Networks                    | 1         | 0.88%   |
| Hewlett-Packard                 | 1         | 0.88%   |
| Cambridge Silicon Radio         | 1         | 0.88%   |
| ASUSTek Computer                | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 26.32%  |
| Intel AX200 Bluetooth                                       | 10        | 8.77%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 7.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 4.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 5         | 4.39%   |
| Apple Bluetooth Host Controller                             | 5         | 4.39%   |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 3.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 2.63%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 2.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 3         | 2.63%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 2.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 2.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.75%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.75%   |
| Intel AX201 Bluetooth                                       | 2         | 1.75%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 2         | 1.75%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.88%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.88%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 1         | 0.88%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.88%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE        | 1         | 0.88%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.88%   |
| Qualcomm Atheros Bluetooth                                  | 1         | 0.88%   |
| Intel AX210 Bluetooth                                       | 1         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 0.88%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 0.88%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.88%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.88%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.88%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 0.88%   |
| ASUS ASUS USB-BT500                                         | 1         | 0.88%   |
| Apple Bluetooth HCI                                         | 1         | 0.88%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 0.88%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 167       | 80.29%  |
| AMD                                          | 20        | 9.62%   |
| Nvidia                                       | 15        | 7.21%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.48%   |
| ULi Electronics                              | 1         | 0.48%   |
| Texas Instruments                            | 1         | 0.48%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.48%   |
| Logitech                                     | 1         | 0.48%   |
| Lenovo                                       | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 9.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 7.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 7.91%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 6.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 6.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 5.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.95%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 3.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 3.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 2.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.58%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.19%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.79%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.79%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.4%    |
| ULi Electronics M5451 PCI AC-Link Controller Audio Device                                         | 1         | 0.4%    |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.4%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.4%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Logitech Headset H340                                                                             | 1         | 0.4%    |
| Lenovo Lenovo ThinkPad OneLink Pro Dock                                                           | 1         | 0.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.4%    |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.4%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.4%    |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.4%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.4%    |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 52        | 26.53%  |
| SK hynix                     | 35        | 17.86%  |
| Kingston                     | 25        | 12.76%  |
| Micron Technology            | 20        | 10.2%   |
| Unknown                      | 17        | 8.67%   |
| Crucial                      | 10        | 5.1%    |
| Ramaxel Technology           | 7         | 3.57%   |
| Transcend                    | 6         | 3.06%   |
| Corsair                      | 6         | 3.06%   |
| Unknown                      | 5         | 2.55%   |
| Elpida                       | 4         | 2.04%   |
| Nanya Technology             | 3         | 1.53%   |
| Unknown (ABCD)               | 1         | 0.51%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.51%   |
| Team                         | 1         | 0.51%   |
| Patriot                      | 1         | 0.51%   |
| G.Skill                      | 1         | 0.51%   |
| A-DATA Technology            | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 6         | 2.97%   |
| Unknown                                                           | 5         | 2.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 1.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s             | 4         | 1.98%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 4         | 1.98%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 3         | 1.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s             | 3         | 1.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 3         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 3         | 1.49%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 3         | 1.49%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s           | 3         | 1.49%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s               | 2         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 0.99%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s            | 2         | 0.99%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 2         | 0.99%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 2         | 0.99%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s            | 2         | 0.99%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 0.99%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 1333MT/s           | 2         | 0.99%   |
| Micron RAM 16KTF1G64HZ-1G6P1 8GB SODIMM DDR3 1600MT/s             | 2         | 0.99%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s            | 2         | 0.99%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 2         | 0.99%   |
| Kingston RAM 99U5428-042.A00G 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.99%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 0.99%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1333MT/s           | 2         | 0.99%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                         | 1         | 0.5%    |
| Unknown SODIMM 1GB SODIMM DDR2 667MT/s                            | 1         | 0.5%    |
| Unknown RAM PartNum 0 512MB Chip DDR2 533MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DRAM                              | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3                                | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 256MB SODIMM SDRAM                             | 1         | 0.5%    |
| Unknown RAM Module 256MB SODIMM DRAM                              | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM RAM                              | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM 667MT/s                          | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                                | 1         | 0.5%    |
| Unknown RAM Module 1024MB SODIMM DDR                              | 1         | 0.5%    |
| Unknown RAM GD2.09293S.001 16GB SODIMM DDR4 2400MT/s              | 1         | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 0.5%    |
| Unknown (0x7F7F7F94FFFFFFFF) RAM Module 2GB SODIMM DDR2 667MT/s   | 1         | 0.5%    |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s                | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s              | 1         | 0.5%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.5%    |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s              | 1         | 0.5%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s              | 1         | 0.5%    |
| SK hynix RAM HMT851S6CMR6A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.5%    |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 1         | 0.5%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.5%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.5%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s            | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 94        | 54.65%  |
| DDR4    | 52        | 30.23%  |
| DDR2    | 12        | 6.98%   |
| Unknown | 4         | 2.33%   |
| LPDDR3  | 3         | 1.74%   |
| LPDDR4  | 2         | 1.16%   |
| DDR     | 2         | 1.16%   |
| SDRAM   | 1         | 0.58%   |
| RAM     | 1         | 0.58%   |
| DRAM    | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 165       | 95.93%  |
| Row Of Chips | 5         | 2.91%   |
| DIMM         | 1         | 0.58%   |
| Chip         | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 65        | 35.71%  |
| 4096  | 55        | 30.22%  |
| 2048  | 30        | 16.48%  |
| 16384 | 22        | 12.09%  |
| 1024  | 6         | 3.3%    |
| 256   | 2         | 1.1%    |
| 32768 | 1         | 0.55%   |
| 512   | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 32.97%  |
| 1333    | 24        | 13.19%  |
| 2667    | 20        | 10.99%  |
| 2400    | 16        | 8.79%   |
| 1334    | 13        | 7.14%   |
| 3200    | 10        | 5.49%   |
| 667     | 8         | 4.4%    |
| 2133    | 6         | 3.3%    |
| Unknown | 6         | 3.3%    |
| 800     | 5         | 2.75%   |
| 1867    | 4         | 2.2%    |
| 1067    | 3         | 1.65%   |
| 1066    | 2         | 1.1%    |
| 533     | 2         | 1.1%    |
| 4267    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 975     | 1         | 0.55%   |

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
| Chicony Electronics                    | 41        | 34.45%  |
| Acer                                   | 13        | 10.92%  |
| Microdia                               | 10        | 8.4%    |
| Realtek Semiconductor                  | 9         | 7.56%   |
| Suyin                                  | 8         | 6.72%   |
| Lite-On Technology                     | 7         | 5.88%   |
| Sunplus Innovation Technology          | 6         | 5.04%   |
| IMC Networks                           | 6         | 5.04%   |
| Lenovo                                 | 4         | 3.36%   |
| Apple                                  | 4         | 3.36%   |
| Alcor Micro                            | 4         | 3.36%   |
| Syntek                                 | 1         | 0.84%   |
| Ricoh                                  | 1         | 0.84%   |
| Quanta                                 | 1         | 0.84%   |
| Pixart Imaging                         | 1         | 0.84%   |
| Luxvisions Innotech Limited            | 1         | 0.84%   |
| Cubeternet                             | 1         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.84%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 21        | 17.5%   |
| Acer Integrated Camera                               | 6         | 5%      |
| Microdia Integrated Webcam                           | 4         | 3.33%   |
| Lite-On Integrated Camera                            | 4         | 3.33%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 4         | 3.33%   |
| Chicony FJ Camera                                    | 4         | 3.33%   |
| Suyin RGBIR Camera                                   | 3         | 2.5%    |
| Realtek Realtek USB2.0 PC Camera                     | 3         | 2.5%    |
| Realtek Integrated_Webcam_HD                         | 3         | 2.5%    |
| IMC Networks Integrated Camera                       | 3         | 2.5%    |
| Chicony HD WebCam                                    | 3         | 2.5%    |
| Sunplus Integrated_Webcam_HD                         | 2         | 1.67%   |
| Lite-On Realtek PC Camera                            | 2         | 1.67%   |
| Lenovo Integrated Webcam [R5U877]                    | 2         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 1.67%   |
| Chicony HD WebCam (Acer)                             | 2         | 1.67%   |
| Apple FaceTime HD Camera (Built-in)                  | 2         | 1.67%   |
| Alcor Micro USB 2.0 Web Camera                       | 2         | 1.67%   |
| Acer SunplusIT Integrated Camera                     | 2         | 1.67%   |
| Syntek Lenovo EasyCamera                             | 1         | 0.83%   |
| Suyin Sony Visual Communication Camera               | 1         | 0.83%   |
| Suyin Integrated Webcam                              | 1         | 0.83%   |
| Suyin HP Webcam-101                                  | 1         | 0.83%   |
| Suyin HP Integrated Webcam                           | 1         | 0.83%   |
| Suyin Asus Integrated Webcam                         | 1         | 0.83%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 0.83%   |
| Sunplus Integrated Camera                            | 1         | 0.83%   |
| Sunplus HP HD Webcam [Fixed]                         | 1         | 0.83%   |
| Sunplus Asus Webcam                                  | 1         | 0.83%   |
| Ricoh HD Webcam                                      | 1         | 0.83%   |
| Realtek USB Camera                                   | 1         | 0.83%   |
| Realtek USB 2 Webcam                                 | 1         | 0.83%   |
| Realtek Integrated Webcam HD                         | 1         | 0.83%   |
| Quanta HP TrueVision HD Camera                       | 1         | 0.83%   |
| Pixart Imaging VGA Webcam                            | 1         | 0.83%   |
| Microdia Sonix Integrated Webcam                     | 1         | 0.83%   |
| Microdia Lenovo EasyCamera                           | 1         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 0.83%   |
| Microdia Integrated_Webcam_HD                        | 1         | 0.83%   |
| Microdia Dell Laptop Integrated Webcam HD            | 1         | 0.83%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 0.83%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.83%   |
| Lite-On HP HD Webcam [Fixed]                         | 1         | 0.83%   |
| Lenovo Integrated Webcam                             | 1         | 0.83%   |
| Lenovo Integrated Camera                             | 1         | 0.83%   |
| IMC Networks Integrated Webcam                       | 1         | 0.83%   |
| Cubeternet WebCam                                    | 1         | 0.83%   |
| Chicony ThinkPad T490 Webcam                         | 1         | 0.83%   |
| Chicony Ltd., VGA Webcam                             | 1         | 0.83%   |
| Chicony Lenovo EasyCamera                            | 1         | 0.83%   |
| Chicony Integrated Camera [ThinkPad]                 | 1         | 0.83%   |
| Chicony Integrated Camera (1280x720@30)              | 1         | 0.83%   |
| Chicony HP HD Webcam [Fixed]                         | 1         | 0.83%   |
| Chicony Chicony USB2.0 Camera                        | 1         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 1         | 0.83%   |
| Apple FaceTime HD Camera                             | 1         | 0.83%   |
| Apple FaceTime Camera                                | 1         | 0.83%   |
| Alcor Micro WebCam\S6000                             | 1         | 0.83%   |
| Alcor Micro USB 2.0 Camera                           | 1         | 0.83%   |
| Acer ThinkPad Integrated Camera                      | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 35.42%  |
| Upek                       | 9         | 18.75%  |
| Synaptics                  | 7         | 14.58%  |
| AuthenTec                  | 4         | 8.33%   |
| LighTuning Technology      | 3         | 6.25%   |
| Broadcom                   | 3         | 6.25%   |
| STMicroelectronics         | 2         | 4.17%   |
| Shenzhen Goodix Technology | 2         | 4.17%   |
| Next Biometrics            | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 8         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 6         | 12.5%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 4.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 2         | 4.17%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 4.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 4.17%   |
| Unknown                                                                      | 2         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 2.08%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 2.08%   |
| Synaptics product 0x00be                                                     | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.08%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 2.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.08%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 2.08%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 2.08%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.08%   |

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
| 1     | 61        | 29.9%   |
| 2     | 60        | 29.41%  |
| 3     | 33        | 16.18%  |
| 0     | 29        | 14.22%  |
| 4     | 15        | 7.35%   |
| 5     | 4         | 1.96%   |
| 7     | 1         | 0.49%   |
| 6     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 140       | 40.7%   |
| Card reader              | 42        | 12.21%  |
| Bluetooth                | 40        | 11.63%  |
| Fingerprint reader       | 39        | 11.34%  |
| Net/wireless             | 36        | 10.47%  |
| Firewire controller      | 16        | 4.65%   |
| Graphics card            | 9         | 2.62%   |
| Net/ethernet             | 6         | 1.74%   |
| Network                  | 5         | 1.45%   |
| Sound                    | 3         | 0.87%   |
| Modem                    | 3         | 0.87%   |
| Storage                  | 2         | 0.58%   |
| Storage/nvme             | 1         | 0.29%   |
| Storage/ide              | 1         | 0.29%   |
| Storage/ata              | 1         | 0.29%   |

