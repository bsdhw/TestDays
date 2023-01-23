BSD - Tested Hardware & Statistics (Notebooks)
----------------------------------------------

A project to collect tested hardware configurations for BSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestCoverage_VE](https://github.com/bsdhw/TestCoverage_VE)

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

Total: 2993

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 3442               | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Unknown       | Unknown                     | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Unknown       | Unknown                     | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Acer          | Aspire ES1-571              | [a17d96dde0](https://bsd-hardware.info/?probe=a17d96dde0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Datto         | 1000                        | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e6ad419f5e](https://bsd-hardware.info/?probe=e6ad419f5e) | Jan 20, 2023 |
| Lenovo        | B50-80 80EW                 | [fa42e2faf7](https://bsd-hardware.info/?probe=fa42e2faf7) | Jan 20, 2023 |
| Acer          | TravelMate B311-31          | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Dell          | Precision 5540              | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Datto         | Unknown                     | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| Unknown       | Unknown                     | [cbdab56490](https://bsd-hardware.info/?probe=cbdab56490) | Jan 18, 2023 |
| Datto         | 1000                        | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Intel         | H81U                        | [08d2539153](https://bsd-hardware.info/?probe=08d2539153) | Jan 18, 2023 |
| Unknown       | Unknown                     | [4ccf28379a](https://bsd-hardware.info/?probe=4ccf28379a) | Jan 17, 2023 |
| Intel         | H81U                        | [fe47328dd0](https://bsd-hardware.info/?probe=fe47328dd0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [dcdf55f06e](https://bsd-hardware.info/?probe=dcdf55f06e) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| Lenovo        | B40-70 80F30005BR           | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| HP            | Pavilion dv6                | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | ProBook 455 G7              | [600f7f4f4f](https://bsd-hardware.info/?probe=600f7f4f4f) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| HP            | Pavilion dv6                | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Deciso        | NetBoard-A10                | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Unknown       | Unknown                     | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Datto         | 1000                        | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | [ef45a319a3](https://bsd-hardware.info/?probe=ef45a319a3) | Jan 11, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Lenovo        | G50-80 80E5                 | [549b75038e](https://bsd-hardware.info/?probe=549b75038e) | Jan 08, 2023 |
| Lenovo        | G50-80 80E5                 | [5e81493c8d](https://bsd-hardware.info/?probe=5e81493c8d) | Jan 08, 2023 |
| Deciso        | OPNsense Appliance          | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Lenovo        | B50-80 80EW                 | [b8f49b8d19](https://bsd-hardware.info/?probe=b8f49b8d19) | Jan 07, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [45f592a66f](https://bsd-hardware.info/?probe=45f592a66f) | Jan 06, 2023 |
| Deciso        | Netboard A20                | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Dell          | Latitude E6430              | [1c4bec17bb](https://bsd-hardware.info/?probe=1c4bec17bb) | Jan 06, 2023 |
| SLIMBOOK      | ESSENTIAL-15-11             | [3f758732d3](https://bsd-hardware.info/?probe=3f758732d3) | Jan 05, 2023 |
| HP            | EliteBook 8570p             | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| Deciso        | NetBoard-A10                | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [aa6c483d4f](https://bsd-hardware.info/?probe=aa6c483d4f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Intel         | Milstead Platform           | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Alienware     | m15 R4                      | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [d5fa6c651c](https://bsd-hardware.info/?probe=d5fa6c651c) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | OPNsense Appliance          | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| Deciso        | NetBoard-A10                | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Star Labs     | Lite                        | [9ad15636dd](https://bsd-hardware.info/?probe=9ad15636dd) | Dec 25, 2022 |
| Alienware     | m15 R4                      | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [ca475dd1d0](https://bsd-hardware.info/?probe=ca475dd1d0) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Sony          | VPCSB11FX                   | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Lenovo        | ThinkPad T60 1951A47        | [e254601f07](https://bsd-hardware.info/?probe=e254601f07) | Dec 21, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Dell          | Precision M4800             | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Dell          | Latitude E6430              | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| Dell          | Latitude E6430              | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Lenovo        | B50-80 80EW                 | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Intel         | H81U                        | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Lenovo        | G510 20238                  | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| Intel         | H81U                        | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Lenovo        | B50-80 80EW                 | [9551c57fc3](https://bsd-hardware.info/?probe=9551c57fc3) | Dec 14, 2022 |
| Dell          | Vostro 15-3568              | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProBook 430 G7              | [0e2278affa](https://bsd-hardware.info/?probe=0e2278affa) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | Pavilion dv4                | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| Apple         | MacBook3,1                  | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Deciso        | NetBoard-A10                | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| HP            | 245 G6                      | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| DFI           | BE17X(170/171/173)          | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Apple         | MacBookPro14,1              | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| HASEE Comp... | N95XKP6                     | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Panasonic     | CF-54-1                     | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Dell          | Inspiron 3442               | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Acidanther... | MacBookPro15,1              | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| HP            | Laptop 14s-fq0xxx           | [920a2fe2e9](https://bsd-hardware.info/?probe=920a2fe2e9) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| GPD           | P3 MAX                      | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| HP            | Laptop 14s-fq0xxx           | [9618eb0cbe](https://bsd-hardware.info/?probe=9618eb0cbe) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Apple         | MacBook5,1                  | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| HP            | EliteBook 8570p             | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Acer          | Aspire 5738                 | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Dell          | Latitude D610               | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | [0bbf4f46e7](https://bsd-hardware.info/?probe=0bbf4f46e7) | Nov 24, 2022 |
| ASUSTek       | K55VD                       | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| Deciso        | OPNsense Appliance          | [75a7bf9b27](https://bsd-hardware.info/?probe=75a7bf9b27) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| HP            | ProBook 4540s               | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Deciso        | NetBoard-A10                | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Dell          | Latitude D630               | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | EliteBook 8570p             | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| Acer          | Aspire 5251                 | [c9eb0051ed](https://bsd-hardware.info/?probe=c9eb0051ed) | Nov 16, 2022 |
| Dell          | Vostro 3550                 | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| Medion        | E15415                      | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Google        | Akemi                       | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Deciso        | Netboard A20                | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Deciso        | NetBoard-A20                | [61157ac2b6](https://bsd-hardware.info/?probe=61157ac2b6) | Nov 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| Deciso        | NetBoard-A10                | [1fc6403341](https://bsd-hardware.info/?probe=1fc6403341) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
| HP            | ProBook 4540s               | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [45316a9769](https://bsd-hardware.info/?probe=45316a9769) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| Dell          | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| HP            | Laptop 15-da0xxx            | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Acer          | JM11-MS                     | [3ff8b20107](https://bsd-hardware.info/?probe=3ff8b20107) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Dell          | Inspiron 7720               | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Deciso        | NetBoard-A10                | [5d4c95dcac](https://bsd-hardware.info/?probe=5d4c95dcac) | Oct 26, 2022 |
| Matsushita... | CF-51RCVDNLM                | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [06e6c07e90](https://bsd-hardware.info/?probe=06e6c07e90) | Oct 25, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| Intel         | H81U                        | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Latitude 5591               | [58b577382a](https://bsd-hardware.info/?probe=58b577382a) | Oct 23, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| Alienware     | m15                         | [3304a767ba](https://bsd-hardware.info/?probe=3304a767ba) | Oct 22, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Lenovo        | G500 20236                  | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| Apple         | MacBookPro8,1               | [623594855a](https://bsd-hardware.info/?probe=623594855a) | Oct 22, 2022 |
| Dell          | Precision M4500             | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| Acer          | Aspire E1-570               | [3d62c50607](https://bsd-hardware.info/?probe=3d62c50607) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| HP            | Laptop 15q-bu0xx            | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Unknown       | Unknown                     | [3b7146c456](https://bsd-hardware.info/?probe=3b7146c456) | Oct 14, 2022 |
| Unknown       | Unknown                     | [1ad8d9e64c](https://bsd-hardware.info/?probe=1ad8d9e64c) | Oct 14, 2022 |
| Intel         | H81U                        | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a773a82ff4](https://bsd-hardware.info/?probe=a773a82ff4) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Acer          | Aspire ES1-523              | [92a125995f](https://bsd-hardware.info/?probe=92a125995f) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| Acer          | Aspire F5-573               | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| Dell          | Precision 5510              | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| Dell          | Latitude E6420              | [07b078fdef](https://bsd-hardware.info/?probe=07b078fdef) | Oct 04, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| HP            | ProBook 4540s               | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 255 G8 Notebook PC          | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Deciso        | NetBoard-A10                | [9b95ddf7b9](https://bsd-hardware.info/?probe=9b95ddf7b9) | Oct 01, 2022 |
| IBM           | ThinkPad T43 18714AG        | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| Intel         | H81U                        | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Tactus        | GeoFlex 110                 | [0b93b5f915](https://bsd-hardware.info/?probe=0b93b5f915) | Sep 28, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Deciso        | OPNsense Appliance          | [659b695f09](https://bsd-hardware.info/?probe=659b695f09) | Sep 26, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW003PM... | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Deciso        | Netboard A20                | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| Toshiba       | Satellite BE96-F299         | [15b93c9f4b](https://bsd-hardware.info/?probe=15b93c9f4b) | Sep 21, 2022 |
| Toshiba       | Satellite BE96-F299         | [9beae1547d](https://bsd-hardware.info/?probe=9beae1547d) | Sep 21, 2022 |
| Unknown       | Unknown                     | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Deciso        | NetBoard-A10                | [5cec3595a3](https://bsd-hardware.info/?probe=5cec3595a3) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Dell          | Precision 7710              | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| HP            | Pavilion dv6700             | [f3058f97f9](https://bsd-hardware.info/?probe=f3058f97f9) | Sep 18, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| ASUSTek       | X455LJ                      | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| HP            | EliteBook 840 G3            | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| IBM           | ThinkPad T43 18714AG        | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [eee7bdda02](https://bsd-hardware.info/?probe=eee7bdda02) | Sep 15, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [9e6bd1263d](https://bsd-hardware.info/?probe=9e6bd1263d) | Sep 13, 2022 |
| Deciso        | Netboard A20                | [8af40be425](https://bsd-hardware.info/?probe=8af40be425) | Sep 13, 2022 |
| SIEMENS       | SIMATIC IPC127E             | [d16e38e6b2](https://bsd-hardware.info/?probe=d16e38e6b2) | Sep 12, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Dell          | XPS M1330                   | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Apple         | MacBook5,2                  | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Intel         | SandyBridge Platform        | [7c10326786](https://bsd-hardware.info/?probe=7c10326786) | Sep 09, 2022 |
| Toshiba       | Satellite A200              | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Latitude 5310               | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4f31f81571](https://bsd-hardware.info/?probe=4f31f81571) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Deciso        | NetBoard-A10                | [3547d9da9c](https://bsd-hardware.info/?probe=3547d9da9c) | Sep 01, 2022 |
| Apple         | MacBookPro8,1               | [0ff0fc4c3b](https://bsd-hardware.info/?probe=0ff0fc4c3b) | Sep 01, 2022 |
| Dell          | Latitude E5550              | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Dell          | Precision 7710              | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Toshiba       | Satellite A300              | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fc259fcf3e](https://bsd-hardware.info/?probe=fc259fcf3e) | Aug 30, 2022 |
| Dell          | Precision 5540              | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| HP            | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a5c0fe3db8](https://bsd-hardware.info/?probe=a5c0fe3db8) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Dell          | Latitude 7390               | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Toshiba       | Satellite S55t-B            | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| Deciso        | NetBoard-A10                | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Deciso        | Netboard A20                | [164274c6b4](https://bsd-hardware.info/?probe=164274c6b4) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [692e2f0837](https://bsd-hardware.info/?probe=692e2f0837) | Aug 20, 2022 |
| Unknown       | Unknown                     | [1dfb3adb6b](https://bsd-hardware.info/?probe=1dfb3adb6b) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7576399c3c](https://bsd-hardware.info/?probe=7576399c3c) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [2e7d570822](https://bsd-hardware.info/?probe=2e7d570822) | Aug 20, 2022 |
| Lenovo        | ThinkPad X260 20F5S10W0H    | [7afa139f4f](https://bsd-hardware.info/?probe=7afa139f4f) | Aug 20, 2022 |
| HP            | Pavilion g6                 | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| Deciso        | NetBoard-A20                | [7ec18da9e4](https://bsd-hardware.info/?probe=7ec18da9e4) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| HP            | EliteBook 840 G3            | [28929cae10](https://bsd-hardware.info/?probe=28929cae10) | Aug 17, 2022 |
| Dell          | Studio 1537                 | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| HP            | Victus by Gaming Laptop ... | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [4cc4d44e43](https://bsd-hardware.info/?probe=4cc4d44e43) | Aug 15, 2022 |
| Intel         | Apollolake I Platform       | [8b6b08bc82](https://bsd-hardware.info/?probe=8b6b08bc82) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c9bda4b49d](https://bsd-hardware.info/?probe=c9bda4b49d) | Aug 14, 2022 |
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| Dell          | Inspiron 1545               | [e1a29d8008](https://bsd-hardware.info/?probe=e1a29d8008) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Samsung       | NC210/NC110                 | [6c697b3312](https://bsd-hardware.info/?probe=6c697b3312) | Aug 13, 2022 |
| Alienware     | m15 R4                      | [769c5c43f3](https://bsd-hardware.info/?probe=769c5c43f3) | Aug 13, 2022 |
| Deciso        | NetBoard-A10                | [9d82dae644](https://bsd-hardware.info/?probe=9d82dae644) | Aug 11, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| HUAWEI        | BOM-WXX9                    | [4ba15a31d9](https://bsd-hardware.info/?probe=4ba15a31d9) | Aug 10, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| Dell          | XPS 13 9360                 | [1d342196fb](https://bsd-hardware.info/?probe=1d342196fb) | Aug 08, 2022 |
| HP            | ProBook 4540s               | [0a7891d53f](https://bsd-hardware.info/?probe=0a7891d53f) | Aug 06, 2022 |
| eMachines     | eME728                      | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Dell          | Inspiron 3581               | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Unknown       | Unknown                     | [7cbf489a64](https://bsd-hardware.info/?probe=7cbf489a64) | Aug 04, 2022 |
| Dell          | Inspiron 15-3567            | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Intel         | H81U                        | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| Intel         | H81U                        | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Unknown       | Unknown                     | [3efcb47333](https://bsd-hardware.info/?probe=3efcb47333) | Jul 31, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| HP            | EliteBook 8540w             | [0063369c40](https://bsd-hardware.info/?probe=0063369c40) | Jul 30, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [bf5cea4ab5](https://bsd-hardware.info/?probe=bf5cea4ab5) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Acer          | Aspire E5-521G              | [dcc5d3116f](https://bsd-hardware.info/?probe=dcc5d3116f) | Jul 29, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| Lenovo        | ThinkPad X200 7458NP9       | [4192abf903](https://bsd-hardware.info/?probe=4192abf903) | Jul 20, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Deciso        | Netboard A20                | [2bc988b18a](https://bsd-hardware.info/?probe=2bc988b18a) | Jul 18, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Inspiron 15-3567            | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Deciso        | Netboard A20                | [a4be4171b6](https://bsd-hardware.info/?probe=a4be4171b6) | Jul 17, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Dell          | Inspiron 3505               | [ead2595782](https://bsd-hardware.info/?probe=ead2595782) | Jul 17, 2022 |
| Sony          | VGN-NS21M_S                 | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [d9efb0425b](https://bsd-hardware.info/?probe=d9efb0425b) | Jul 15, 2022 |
| Dell          | XPS 13 7390                 | [6e85a064f0](https://bsd-hardware.info/?probe=6e85a064f0) | Jul 15, 2022 |
| Apple         | MacBook4,1                  | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| Deciso        | OPNsense Appliance          | [05fb88304d](https://bsd-hardware.info/?probe=05fb88304d) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Deciso        | Netboard A20                | [743b330db3](https://bsd-hardware.info/?probe=743b330db3) | Jul 12, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| MSI           | GF63 Thin 10SC              | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| HP            | Laptop 15-da0xxx            | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| Unknown       | Unknown                     | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Acer          | Nitro AN515-55              | [f98a69101e](https://bsd-hardware.info/?probe=f98a69101e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Fujitsu       | LIFEBOOK A555               | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| Shuttle       | DS437                       | [d7b076918a](https://bsd-hardware.info/?probe=d7b076918a) | Jul 07, 2022 |
| Shuttle       | DS437                       | [9fe84a8c9d](https://bsd-hardware.info/?probe=9fe84a8c9d) | Jul 07, 2022 |
| Deciso        | Netboard A20                | [c70ba0979e](https://bsd-hardware.info/?probe=c70ba0979e) | Jul 07, 2022 |
| HP            | 250 G6 Notebook PC          | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Lenovo        | IdeaPad S12 20021,2959      | [c1bf998d6a](https://bsd-hardware.info/?probe=c1bf998d6a) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Lenovo        | ThinkPad T470 20HD000MUK    | [866724656a](https://bsd-hardware.info/?probe=866724656a) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK A555               | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| Deciso        | NetBoard-A10                | [681bb27fbc](https://bsd-hardware.info/?probe=681bb27fbc) | Jul 04, 2022 |
| Star Labs     | LabTop                      | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| Dell          | Inspiron 5515               | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Acer          | AOD260                      | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Unknown       | Unknown                     | [d9e6e5b83a](https://bsd-hardware.info/?probe=d9e6e5b83a) | Jun 29, 2022 |
| Deciso        | NetBoard-A10                | [ace8b06cd3](https://bsd-hardware.info/?probe=ace8b06cd3) | Jun 29, 2022 |
| System76      | Gazelle                     | [7e2dbb0a5b](https://bsd-hardware.info/?probe=7e2dbb0a5b) | Jun 28, 2022 |
| System76      | Gazelle                     | [8cb2a30786](https://bsd-hardware.info/?probe=8cb2a30786) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| ASUSTek       | K53TA                       | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [bb3de13b1a](https://bsd-hardware.info/?probe=bb3de13b1a) | Jun 23, 2022 |
| ASUSTek       | X202E                       | [bdbe613858](https://bsd-hardware.info/?probe=bdbe613858) | Jun 22, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| Dell          | Latitude 5521               | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| HP            | Unknown                     | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| HP            | EliteBook 8440p             | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Deciso        | Netboard A20                | [8692e7d18b](https://bsd-hardware.info/?probe=8692e7d18b) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| Alienware     | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Dell          | Latitude E5420              | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| Apple         | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Dell          | Latitude 7390               | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| HP            | ProBook 4230s               | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| HP            | EliteBook 830 G5            | [03cb6c6c7f](https://bsd-hardware.info/?probe=03cb6c6c7f) | Jun 09, 2022 |
| Dell          | Latitude E5420              | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Dell          | Latitude 5410               | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
| Unknown       | Unknown                     | [e4d449d8dc](https://bsd-hardware.info/?probe=e4d449d8dc) | Jun 04, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| Dell          | Latitude 7490               | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| HP            | Pavilion g6                 | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Apple         | MacBookPro5,3               | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Dell          | G5 5590                     | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| AAEON         | GENE-SKU7                   | [adecd2a0fc](https://bsd-hardware.info/?probe=adecd2a0fc) | May 26, 2022 |
| Unknown       | Unknown                     | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| Notebook      | N7x0WU                      | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [9e2661b9e0](https://bsd-hardware.info/?probe=9e2661b9e0) | May 24, 2022 |
| Dell          | Latitude E6540              | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| HP            | EliteBook 8530w             | [6401363886](https://bsd-hardware.info/?probe=6401363886) | May 23, 2022 |
| Deciso        | Netboard A20                | [eba0ffa870](https://bsd-hardware.info/?probe=eba0ffa870) | May 23, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Deciso        | Netboard A20                | [1fe95544bd](https://bsd-hardware.info/?probe=1fe95544bd) | May 22, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | EliteBook 8460p             | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| Dell          | Latitude 5520               | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| HP            | Pavilion dv6                | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Dell          | XPS 13 9343                 | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| Deciso        | Netboard A20                | [f78f6b9abb](https://bsd-hardware.info/?probe=f78f6b9abb) | May 20, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Acer          | Aspire 5742                 | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Dell          | Precision M4800             | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d2334d7be3](https://bsd-hardware.info/?probe=d2334d7be3) | May 14, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Lenovo        | ThinkPad X230 2325J67       | [3ee0f54d2f](https://bsd-hardware.info/?probe=3ee0f54d2f) | May 12, 2022 |
| Acer          | Aspire A715-42G             | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Unknown       | Unknown                     | [be0027caae](https://bsd-hardware.info/?probe=be0027caae) | May 12, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [34ac291019](https://bsd-hardware.info/?probe=34ac291019) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Intel         | H81U                        | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Acer          | Aspire A715-42G             | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| TUXEDO        | Aura 15 Gen1                | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| HP            | ProBook 4340s               | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Deciso        | OPNsense Appliance          | [70c9fd07ac](https://bsd-hardware.info/?probe=70c9fd07ac) | May 09, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| BESSTAR Te... | U820                        | [6f2aa2d02a](https://bsd-hardware.info/?probe=6f2aa2d02a) | May 07, 2022 |
| Unknown       | W1415A                      | [1b2c63a845](https://bsd-hardware.info/?probe=1b2c63a845) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| Sony          | VGN-NW25GF_S                | [84b50ca3f1](https://bsd-hardware.info/?probe=84b50ca3f1) | May 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Intel         | H81U                        | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Acer          | Aspire E1-570G              | [7fd31252a2](https://bsd-hardware.info/?probe=7fd31252a2) | May 04, 2022 |
| Toshiba       | Satellite P300              | [fca7b38039](https://bsd-hardware.info/?probe=fca7b38039) | May 04, 2022 |
| Lenovo        | B470 HuronRiver Platform    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| HP            | Pavilion m6                 | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| HP            | EliteBook 820 G2            | [3997ff79e4](https://bsd-hardware.info/?probe=3997ff79e4) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| SIEMENS       | SIMATIC IPC127E             | [334103ab86](https://bsd-hardware.info/?probe=334103ab86) | May 02, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| Deciso        | OPNsense Appliance          | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Dell          | Latitude 7490               | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| HP            | ZBook 14                    | [a646255b51](https://bsd-hardware.info/?probe=a646255b51) | May 02, 2022 |
| Dell          | Latitude E5570              | [c214ce4ab0](https://bsd-hardware.info/?probe=c214ce4ab0) | May 01, 2022 |
| Acer          | Aspire A315-41              | [c59d8482e8](https://bsd-hardware.info/?probe=c59d8482e8) | May 01, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Toshiba       | Satellite P25               | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | ThinkPad X240 20AMS1YG01    | [6e38eb1a4e](https://bsd-hardware.info/?probe=6e38eb1a4e) | May 01, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| Dell          | Precision 7730              | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [807676e010](https://bsd-hardware.info/?probe=807676e010) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [22b192afca](https://bsd-hardware.info/?probe=22b192afca) | Apr 28, 2022 |
| Apple         | MacBookPro3,1               | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| HP            | Notebook                    | [eea4cff90b](https://bsd-hardware.info/?probe=eea4cff90b) | Apr 27, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| Notebook      | N7x0WU                      | [b7c06932a3](https://bsd-hardware.info/?probe=b7c06932a3) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| MSI           | Modern 14 B11MOL            | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| ASUSTek       | X550CC                      | [ece6d63cfb](https://bsd-hardware.info/?probe=ece6d63cfb) | Apr 25, 2022 |
| Dell          | Inspiron 5437               | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| Apple         | MacBookPro8,3               | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| Dell          | Latitude E6520              | [c4ae703add](https://bsd-hardware.info/?probe=c4ae703add) | Apr 23, 2022 |
| Dell          | Latitude 5290               | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | 2000                        | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| HP            | ProBook 450 G2              | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Lenovo        | B570 1068FQG                | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Dell          | Studio 1555                 | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| ASUSTek       | X556UJ                      | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| HP            | Notebook                    | [eaff4f0fbf](https://bsd-hardware.info/?probe=eaff4f0fbf) | Apr 19, 2022 |
| Deciso        | OPNsense Appliance          | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| System76      | Lemur Pro                   | [bbeb7d48fa](https://bsd-hardware.info/?probe=bbeb7d48fa) | Apr 17, 2022 |
| Lenovo        | G51-35 80M8                 | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| HUAWEI        | NBLL-WXX9                   | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Dell          | Latitude E5450              | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [eda0880c67](https://bsd-hardware.info/?probe=eda0880c67) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [a3da09ae5e](https://bsd-hardware.info/?probe=a3da09ae5e) | Apr 15, 2022 |
| AMI           | Intel                       | [db87d63d35](https://bsd-hardware.info/?probe=db87d63d35) | Apr 15, 2022 |
| AMI           | Intel                       | [8dc710d126](https://bsd-hardware.info/?probe=8dc710d126) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [f7aa3576ae](https://bsd-hardware.info/?probe=f7aa3576ae) | Apr 13, 2022 |
| System76      | Lemur Pro                   | [276ee4e96e](https://bsd-hardware.info/?probe=276ee4e96e) | Apr 13, 2022 |
| Deciso        | Netboard A20                | [aa1f373bfb](https://bsd-hardware.info/?probe=aa1f373bfb) | Apr 12, 2022 |
| Dell          | Latitude E6440              | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | [edbde611c3](https://bsd-hardware.info/?probe=edbde611c3) | Apr 11, 2022 |
| Deciso        | Netboard A20                | [d12cd9d1a1](https://bsd-hardware.info/?probe=d12cd9d1a1) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Datto         | 1000                        | [745e356caa](https://bsd-hardware.info/?probe=745e356caa) | Apr 11, 2022 |
| HP            | Notebook                    | [6a112cfe6c](https://bsd-hardware.info/?probe=6a112cfe6c) | Apr 11, 2022 |
| HP            | Notebook                    | [a31dd5f48d](https://bsd-hardware.info/?probe=a31dd5f48d) | Apr 11, 2022 |
| Apple         | MacBook5,1                  | [41d62dde7d](https://bsd-hardware.info/?probe=41d62dde7d) | Apr 10, 2022 |
| Apple         | MacBook5,1                  | [c5f7b5499a](https://bsd-hardware.info/?probe=c5f7b5499a) | Apr 10, 2022 |
| Lenovo        | ThinkPad X61 7675K2U        | [24f93b9532](https://bsd-hardware.info/?probe=24f93b9532) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| ASUSTek       | 1001PX                      | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| Panasonic     | CF-B11JWCYS                 | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| Dell          | Vostro 1400                 | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Deciso        | Netboard A20                | [c6217643cc](https://bsd-hardware.info/?probe=c6217643cc) | Apr 07, 2022 |
| Gigabyte      | MMLP7AP-00                  | [8116ea4eac](https://bsd-hardware.info/?probe=8116ea4eac) | Apr 07, 2022 |
| HP            | Pavilion 11                 | [a13373b255](https://bsd-hardware.info/?probe=a13373b255) | Apr 07, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [926afc7ac8](https://bsd-hardware.info/?probe=926afc7ac8) | Apr 07, 2022 |
| HP            | EliteBook 755 G3            | [f14d35a9d5](https://bsd-hardware.info/?probe=f14d35a9d5) | Apr 07, 2022 |
| Deciso        | Netboard A20                | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| Dell          | Precision M4800             | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Dell          | Latitude E5470              | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| ASUSTek       | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| Sony          | VGN-AW21S_B                 | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [1d1db3eab4](https://bsd-hardware.info/?probe=1d1db3eab4) | Apr 03, 2022 |
| BESSTAR Te... | U820                        | [91486df199](https://bsd-hardware.info/?probe=91486df199) | Apr 03, 2022 |
| VIT           | M2420                       | [108b4d79a6](https://bsd-hardware.info/?probe=108b4d79a6) | Apr 03, 2022 |
| LG Electro... | E300-A.CP20T                | [304701f666](https://bsd-hardware.info/?probe=304701f666) | Apr 02, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| Datto         | 1000                        | [5974640141](https://bsd-hardware.info/?probe=5974640141) | Mar 31, 2022 |
| Deciso        | OPNsense Appliance          | [cdd056df79](https://bsd-hardware.info/?probe=cdd056df79) | Mar 31, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK A544               | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| ASUSTek       | VX6                         | [c077198e38](https://bsd-hardware.info/?probe=c077198e38) | Mar 29, 2022 |
| PCSTICK       | Unknown                     | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| IBM           | 2658MNG                     | [e3a5a587fa](https://bsd-hardware.info/?probe=e3a5a587fa) | Mar 28, 2022 |
| ASUSTek       | X555LJ                      | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Deciso        | Netboard A20                | [51a8ceefee](https://bsd-hardware.info/?probe=51a8ceefee) | Mar 26, 2022 |
| Deciso        | Netboard A20                | [43a1f11ae0](https://bsd-hardware.info/?probe=43a1f11ae0) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Deciso        | Netboard A20                | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Deciso        | Netboard A20                | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1af600b3ae](https://bsd-hardware.info/?probe=1af600b3ae) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| Notebook      | N13xWU                      | [8986953acd](https://bsd-hardware.info/?probe=8986953acd) | Mar 22, 2022 |
| Notebook      | N7x0WU                      | [b80f84aef1](https://bsd-hardware.info/?probe=b80f84aef1) | Mar 22, 2022 |
| Notebook      | N8xEJEK                     | [9a62677ea8](https://bsd-hardware.info/?probe=9a62677ea8) | Mar 22, 2022 |
| Dell          | Latitude E6500              | [5fad69bbf0](https://bsd-hardware.info/?probe=5fad69bbf0) | Mar 22, 2022 |
| Dell          | Latitude E6510              | [a040a1a04b](https://bsd-hardware.info/?probe=a040a1a04b) | Mar 22, 2022 |
| Dell          | Vostro 3490                 | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
| Dell          | Latitude E6530              | [9bc5fc70a7](https://bsd-hardware.info/?probe=9bc5fc70a7) | Mar 22, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| Deciso        | Netboard A20                | [8ded6d9af6](https://bsd-hardware.info/?probe=8ded6d9af6) | Mar 21, 2022 |
| ASUSTek       | UX31E                       | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [6a579dca44](https://bsd-hardware.info/?probe=6a579dca44) | Mar 20, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion dv6                | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Lenovo        | ThinkPad X220 4293B43       | [148a268a0f](https://bsd-hardware.info/?probe=148a268a0f) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| ASUSTek       | N50Vc                       | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| Lenovo        | ThinkPad T410 2537BN8       | [bcd5bea2b7](https://bsd-hardware.info/?probe=bcd5bea2b7) | Mar 15, 2022 |
| HASEE Comp... | CW35S                       | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2537BN8       | [086f304f6d](https://bsd-hardware.info/?probe=086f304f6d) | Mar 14, 2022 |
| Gateway       | LT27                        | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| Dell          | Inspiron 5502               | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| HP            | EliteBook 2530p             | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Acer          | Aspire E1-421               | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [be311b6a34](https://bsd-hardware.info/?probe=be311b6a34) | Mar 10, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Itautec       | Infoway w7535               | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| SIEMENS       | SIMATIC IPC127E             | [d1eb8226eb](https://bsd-hardware.info/?probe=d1eb8226eb) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| AEWIN         | CB-7979                     | [ec1e865bbd](https://bsd-hardware.info/?probe=ec1e865bbd) | Mar 07, 2022 |
| Dell          | G5 5590                     | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Lenovo        | ThinkPad T410 2537WEE       | [973ade9e4a](https://bsd-hardware.info/?probe=973ade9e4a) | Mar 07, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| HUAWEI        | BOD-WXX9                    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| Dell          | Vostro 3550                 | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Intel         | H81U                        | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Dell          | Latitude D630               | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Acer          | V5-131                      | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| Dell          | Latitude E5440              | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | Inspiron 5559               | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| HP            | Pavilion Notebook           | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| Acer          | V5-131                      | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude E6430              | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| Dell          | Latitude 7480               | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Shuttle       | DS77U                       | [1ca3d58dfc](https://bsd-hardware.info/?probe=1ca3d58dfc) | Feb 23, 2022 |
| Dell          | Latitude E4310              | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Dell          | Latitude 5591               | [d4d653fba8](https://bsd-hardware.info/?probe=d4d653fba8) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [51b0a953b5](https://bsd-hardware.info/?probe=51b0a953b5) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Vostro 3550                 | [11bed21472](https://bsd-hardware.info/?probe=11bed21472) | Feb 21, 2022 |
| Dell          | Latitude E5470              | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [85441a65a9](https://bsd-hardware.info/?probe=85441a65a9) | Feb 21, 2022 |
| PCSTICK       | Unknown                     | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| Acer          | Aspire A514-52              | [60f9683fb1](https://bsd-hardware.info/?probe=60f9683fb1) | Feb 21, 2022 |
| Dell          | Latitude 7480               | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [deac163b52](https://bsd-hardware.info/?probe=deac163b52) | Feb 19, 2022 |
| Acer          | AO725                       | [f53f627e62](https://bsd-hardware.info/?probe=f53f627e62) | Feb 19, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| TUXEDO        | InfinityBook13V3            | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| ASUSTek       | 1001PX                      | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [bc2860431e](https://bsd-hardware.info/?probe=bc2860431e) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Lenovo        | Flex 2-15 20405             | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Dell          | Latitude 3420               | [f1796d75ed](https://bsd-hardware.info/?probe=f1796d75ed) | Feb 14, 2022 |
| Jumper        | EZbook                      | [35869ff0db](https://bsd-hardware.info/?probe=35869ff0db) | Feb 14, 2022 |
| WOOKING       | X5                          | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| HP            | EliteBook 840 G3            | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Lenovo        | ThinkPad X240 20AMS2QD0C    | [ae597455a4](https://bsd-hardware.info/?probe=ae597455a4) | Feb 13, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [c024d383e7](https://bsd-hardware.info/?probe=c024d383e7) | Feb 13, 2022 |
| HP            | Laptop 15-db0xxx            | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| Apple         | MacBookPro8,1               | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| Deciso        | NetBoard-A20                | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| MiTAC         | 5033                        | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| ASUSTek       | A9T                         | [2962e2b02f](https://bsd-hardware.info/?probe=2962e2b02f) | Feb 09, 2022 |
| Notebook      | N7x0WU                      | [5063e8f546](https://bsd-hardware.info/?probe=5063e8f546) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| HP            | Pavilion Notebook           | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| Lenovo        | G580 20150                  | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Acer          | Aspire E5-511G              | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f107f7c1b1](https://bsd-hardware.info/?probe=f107f7c1b1) | Feb 06, 2022 |
| Deciso        | NetBoard-A20                | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| System76      | Lemur Pro                   | [713b33351f](https://bsd-hardware.info/?probe=713b33351f) | Feb 06, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [f333ed9201](https://bsd-hardware.info/?probe=f333ed9201) | Feb 05, 2022 |
| Sony          | VPCEB1J1E                   | [04c5ee02da](https://bsd-hardware.info/?probe=04c5ee02da) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| Lenovo        | G500s 20245                 | [41f9f804ac](https://bsd-hardware.info/?probe=41f9f804ac) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | Latitude E7450              | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Deciso        | Netboard A20                | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| Dell          | Vostro 3550                 | [0b290f2ac3](https://bsd-hardware.info/?probe=0b290f2ac3) | Feb 02, 2022 |
| HP            | G62                         | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [c03bfe6a21](https://bsd-hardware.info/?probe=c03bfe6a21) | Feb 01, 2022 |
| Lenovo        | ThinkPad X200 745969G       | [f8476c0ea7](https://bsd-hardware.info/?probe=f8476c0ea7) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| GPD           | G1621-02                    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| Sony          | VPCEB1J1E                   | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| HP            | Notebook                    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| HP            | EliteBook 8570p             | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [2d65265b52](https://bsd-hardware.info/?probe=2d65265b52) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| Deciso        | Netboard A20                | [43addbbe84](https://bsd-hardware.info/?probe=43addbbe84) | Jan 28, 2022 |
| Deciso        | Netboard A20                | [5f9588cc87](https://bsd-hardware.info/?probe=5f9588cc87) | Jan 27, 2022 |
| MSI           | GE76 Raider 10UG            | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| Dell          | Latitude 7280               | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| Lenovo        | Y50-70 20378                | [1feb455e8c](https://bsd-hardware.info/?probe=1feb455e8c) | Jan 25, 2022 |
| Dell          | Inspiron 5555               | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| MSI           | GT75VR 7RF                  | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| Deciso        | Netboard A20                | [a25a10c535](https://bsd-hardware.info/?probe=a25a10c535) | Jan 22, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 213       | 9.03%   |
| helloSystem 0.5.0    | 116       | 4.92%   |
| FreeBSD 13.0         | 111       | 4.71%   |
| FreeBSD 13.1         | 95        | 4.03%   |
| helloSystem 0.4.0    | 92        | 3.9%    |
| OpenBSD 6.8          | 90        | 3.82%   |
| helloSystem 0.6.0    | 71        | 3.01%   |
| helloSystem 0.8.0    | 64        | 2.71%   |
| FreeBSD 14.0-CURRENT | 60        | 2.54%   |
| FreeBSD 12.2         | 59        | 2.5%    |
| GhostBSD 20.04.02    | 58        | 2.46%   |
| OpenBSD 6.9          | 55        | 2.33%   |
| OpenBSD 7.0          | 50        | 2.12%   |
| OpenBSD 7.2          | 42        | 1.78%   |
| OpenBSD 7.1          | 40        | 1.7%    |
| FreeBSD 13.0-p4      | 35        | 1.48%   |
| NomadBSD 1.3.2       | 34        | 1.44%   |
| FreeBSD 12.2-p2      | 34        | 1.44%   |
| NomadBSD 5806f915    | 32        | 1.36%   |
| FreeBSD 13.0-CURRENT | 31        | 1.31%   |
| GhostBSD 21.08.27    | 29        | 1.23%   |
| FreeBSD 13.0-STABLE  | 28        | 1.19%   |
| FreeBSD 12.1         | 28        | 1.19%   |
| FreeBSD 12.1-p8      | 26        | 1.1%    |
| FreeBSD 13.0-p5      | 25        | 1.06%   |
| OpenBSD 6.7          | 23        | 0.97%   |
| FreeBSD 13.1-p5      | 23        | 0.97%   |
| FreeBSD 13.0-p3      | 23        | 0.97%   |
| FreeBSD 12.2-p4      | 23        | 0.97%   |
| FreeBSD 12.1-p10     | 23        | 0.97%   |
| FreeBSD 13.1-p2      | 21        | 0.89%   |
| FreeBSD 12.1-p5      | 20        | 0.85%   |
| FreeBSD 13.0-p7      | 19        | 0.81%   |
| NomadBSD 1.4         | 18        | 0.76%   |
| FreeBSD 12.2-p3      | 18        | 0.76%   |
| FreeBSD 13.0-p2      | 17        | 0.72%   |
| FreeBSD 12.1-STABLE  | 15        | 0.64%   |
| FreeBSD 12.1-p7      | 15        | 0.64%   |
| helloSystem 0.3.0    | 14        | 0.59%   |
| GhostBSD 22.01.12    | 13        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 809       | 39.6%   |
| helloSystem | 537       | 26.28%  |
| OpenBSD     | 249       | 12.19%  |
| OPNsense    | 175       | 8.57%   |
| GhostBSD    | 129       | 6.31%   |
| NomadBSD    | 96        | 4.7%    |
| NetBSD      | 18        | 0.88%   |
| HardenedBSD | 7         | 0.34%   |
| DragonFly   | 6         | 0.29%   |
| FuryBSD     | 5         | 0.24%   |
| MidnightBSD | 4         | 0.2%    |
| FuguIta     | 3         | 0.15%   |
| OS108       | 2         | 0.1%    |
| PC-BSD      | 1         | 0.05%   |
| MyBee       | 1         | 0.05%   |
| LibertyBSD  | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 1898      | 95.91%  |
| i386   | 77        | 3.89%   |
| macppc | 3         | 0.15%   |
| arm64  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 592       | 28.23%  |
| Console       | 294       | 14.02%  |
| XFCE          | 231       | 11.02%  |
| fvwm          | 181       | 8.63%   |
| KDE5          | 175       | 8.35%   |
| MATE          | 159       | 7.58%   |
| Openbox       | 111       | 5.29%   |
| GNOME         | 92        | 4.39%   |
| TWM           | 84        | 4.01%   |
| i3            | 72        | 3.43%   |
| Cinnamon      | 19        | 0.91%   |
| AwesomeWM     | 14        | 0.67%   |
| LXQt          | 13        | 0.62%   |
| Fluxbox       | 11        | 0.52%   |
| LXDE          | 8         | 0.38%   |
| Enlightenment | 7         | 0.33%   |
| DWM           | 5         | 0.24%   |
| Lumina        | 4         | 0.19%   |
| ctwm          | 4         | 0.19%   |
| GNUstep       | 3         | 0.14%   |
| spectrwm      | 2         | 0.1%    |
| Picom         | 2         | 0.1%    |
| Mutter        | 2         | 0.1%    |
| IceWM         | 2         | 0.1%    |
| Awesome       | 2         | 0.1%    |
| Xfwm4         | 1         | 0.05%   |
| X-Cinnamon    | 1         | 0.05%   |
| Window Maker  | 1         | 0.05%   |
| sway          | 1         | 0.05%   |
| StumpWM       | 1         | 0.05%   |
| iwm           | 1         | 0.05%   |
| Compton       | 1         | 0.05%   |
| CDE           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1667      | 83.31%  |
| Console | 312       | 15.59%  |
| Wayland | 22        | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 792       | 38.37%  |
| Console | 751       | 36.39%  |
| LightDM | 189       | 9.16%   |
| SDDM    | 179       | 8.67%   |
| XDM     | 75        | 3.63%   |
| GDM     | 68        | 3.29%   |
| Ly      | 7         | 0.34%   |
| PCDM    | 2         | 0.1%    |
| WDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 738       | 35.51%  |
| Unknown         | 635       | 30.56%  |
| C               | 411       | 19.78%  |
| ru_RU           | 47        | 2.26%   |
| de_DE           | 38        | 1.83%   |
| fr_FR           | 31        | 1.49%   |
| en_GB           | 29        | 1.4%    |
| zh_CN           | 15        | 0.72%   |
| es_ES           | 13        | 0.63%   |
| pl_PL           | 10        | 0.48%   |
| it_IT           | 8         | 0.38%   |
| pt_BR           | 7         | 0.34%   |
| en_CA           | 7         | 0.34%   |
| en              | 6         | 0.29%   |
| en_NZ           | 5         | 0.24%   |
| uk_UA           | 4         | 0.19%   |
| nb_NO           | 4         | 0.19%   |
| ja_JP           | 4         | 0.19%   |
| en_AU           | 4         | 0.19%   |
| cs_CZ           | 4         | 0.19%   |
| en_US.US-ASCII  | 3         | 0.14%   |
| en_US.ISO8859-1 | 3         | 0.14%   |
| ru              | 2         | 0.1%    |
| hu_HU           | 2         | 0.1%    |
| fi_FI           | 2         | 0.1%    |
| es_CO           | 2         | 0.1%    |
| es_AR           | 2         | 0.1%    |
| es              | 2         | 0.1%    |
| en_SG           | 2         | 0.1%    |
| en_IE           | 2         | 0.1%    |
| de_DE.ISO8859-1 | 2         | 0.1%    |
| de_CH           | 2         | 0.1%    |
| de              | 2         | 0.1%    |
| zh_TW           | 1         | 0.05%   |
| zh_CN.GB2312    | 1         | 0.05%   |
| tr_TR           | 1         | 0.05%   |
| sv_SE           | 1         | 0.05%   |
| sl_SI           | 1         | 0.05%   |
| sk_SK           | 1         | 0.05%   |
| pt_PT           | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1526      | 76.19%  |
| BIOS | 477       | 23.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 1085      | 53.16%  |
| Ufs     | 550       | 26.95%  |
| Ffs     | 253       | 12.4%   |
| Cd9660  | 147       | 7.2%    |
| Hammer2 | 5         | 0.24%   |
| Xfs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1722      | 86.19%  |
| MBR     | 249       | 12.46%  |
| Unknown | 23        | 1.15%   |
| BSD     | 4         | 0.2%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 654       | 33.08%  |
| Dell                           | 313       | 15.83%  |
| Hewlett-Packard                | 200       | 10.12%  |
| ASUSTek Computer               | 136       | 6.88%   |
| Acer                           | 111       | 5.61%   |
| Apple                          | 82        | 4.15%   |
| Deciso                         | 49        | 2.48%   |
| Toshiba                        | 46        | 2.33%   |
| Unknown                        | 37        | 1.87%   |
| Samsung Electronics            | 33        | 1.67%   |
| Sony                           | 28        | 1.42%   |
| MSI                            | 24        | 1.21%   |
| Fujitsu                        | 20        | 1.01%   |
| TUXEDO                         | 15        | 0.76%   |
| System76                       | 15        | 0.76%   |
| Intel                          | 15        | 0.76%   |
| Panasonic                      | 14        | 0.71%   |
| Notebook                       | 14        | 0.71%   |
| IBM                            | 13        | 0.66%   |
| HUAWEI                         | 13        | 0.66%   |
| Google                         | 12        | 0.61%   |
| Framework                      | 7         | 0.35%   |
| Alienware                      | 7         | 0.35%   |
| Timi                           | 6         | 0.3%    |
| Packard Bell                   | 6         | 0.3%    |
| Gigabyte Technology            | 5         | 0.25%   |
| Gateway                        | 5         | 0.25%   |
| Fujitsu Siemens                | 5         | 0.25%   |
| LG Electronics                 | 4         | 0.2%    |
| eMachines                      | 4         | 0.2%    |
| Datto                          | 4         | 0.2%    |
| SLIMBOOK                       | 3         | 0.15%   |
| Shuttle                        | 3         | 0.15%   |
| Razer                          | 3         | 0.15%   |
| Matsushita Electric Industrial | 3         | 0.15%   |
| GPD                            | 3         | 0.15%   |
| Clevo                          | 3         | 0.15%   |
| BESSTAR Tech                   | 3         | 0.15%   |
| Avell High Performance         | 3         | 0.15%   |
| Star Labs                      | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 46        | 2.33%   |
| Deciso Netboard A20                 | 20        | 1.01%   |
| Deciso NetBoard-A10                 | 13        | 0.66%   |
| Intel H81U                          | 8         | 0.4%    |
| Dell Latitude E7240                 | 8         | 0.4%    |
| Dell Latitude E6420                 | 8         | 0.4%    |
| Deciso OPNsense Appliance           | 8         | 0.4%    |
| HP EliteBook 840 G3                 | 7         | 0.35%   |
| Framework Laptop                    | 7         | 0.35%   |
| Dell Latitude E6430                 | 7         | 0.35%   |
| Lenovo ThinkPad X200 745969G        | 6         | 0.3%    |
| Dell Inspiron 3542                  | 6         | 0.3%    |
| Dell Inspiron 3442                  | 6         | 0.3%    |
| Dell Inspiron 15-3567               | 6         | 0.3%    |
| Apple MacBookPro8,1                 | 6         | 0.3%    |
| Apple MacBook4,1                    | 6         | 0.3%    |
| HP Pavilion g6                      | 5         | 0.25%   |
| Dell Precision M4800                | 5         | 0.25%   |
| Dell Latitude E5470                 | 5         | 0.25%   |
| Dell Inspiron 3521                  | 5         | 0.25%   |
| Deciso DEC2700 - OPNsense Appliance | 5         | 0.25%   |
| Apple MacBook5,1                    | 5         | 0.25%   |
| System76 Lemur Pro                  | 4         | 0.2%    |
| Lenovo ThinkPad T490 20N2CTO1WW     | 4         | 0.2%    |
| HP Pavilion dv6                     | 4         | 0.2%    |
| HP Notebook                         | 4         | 0.2%    |
| HP 2000                             | 4         | 0.2%    |
| Fujitsu LIFEBOOK A555               | 4         | 0.2%    |
| Dell XPS 13 9360                    | 4         | 0.2%    |
| Dell Precision 7710                 | 4         | 0.2%    |
| Dell Latitude E7440                 | 4         | 0.2%    |
| Dell Latitude E6540                 | 4         | 0.2%    |
| Dell Latitude E6530                 | 4         | 0.2%    |
| Dell Latitude E6410                 | 4         | 0.2%    |
| Dell Latitude E5570                 | 4         | 0.2%    |
| Dell Latitude E5420                 | 4         | 0.2%    |
| Dell Latitude 5400                  | 4         | 0.2%    |
| Apple MacBookPro9,2                 | 4         | 0.2%    |
| Apple MacBookPro6,2                 | 4         | 0.2%    |
| Apple MacBookPro5,5                 | 4         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 514       | 26%     |
| Dell Latitude         | 142       | 7.18%   |
| Dell Inspiron         | 83        | 4.2%    |
| Acer Aspire           | 75        | 3.79%   |
| Lenovo IdeaPad        | 53        | 2.68%   |
| Unknown               | 46        | 2.33%   |
| HP EliteBook          | 37        | 1.87%   |
| HP Pavilion           | 35        | 1.77%   |
| Toshiba Satellite     | 32        | 1.62%   |
| Dell Precision        | 32        | 1.62%   |
| HP ProBook            | 30        | 1.52%   |
| HP Laptop             | 22        | 1.11%   |
| Dell XPS              | 22        | 1.11%   |
| Deciso Netboard       | 20        | 1.01%   |
| Dell Vostro           | 19        | 0.96%   |
| Fujitsu LIFEBOOK      | 18        | 0.91%   |
| ASUS VivoBook         | 16        | 0.81%   |
| Deciso NetBoard-A10   | 13        | 0.66%   |
| Lenovo Yoga           | 12        | 0.61%   |
| Lenovo Legion         | 12        | 0.61%   |
| IBM ThinkPad          | 11        | 0.56%   |
| HP ZBook              | 11        | 0.56%   |
| HP Compaq             | 11        | 0.56%   |
| Apple MacBookPro8     | 10        | 0.51%   |
| Apple MacBookPro5     | 9         | 0.46%   |
| Intel H81U            | 8         | 0.4%    |
| Deciso OPNsense       | 8         | 0.4%    |
| ASUS ZenBook          | 8         | 0.4%    |
| Framework Laptop      | 7         | 0.35%   |
| Apple MacBook5        | 7         | 0.35%   |
| TUXEDO Pulse          | 6         | 0.3%    |
| HP 250                | 6         | 0.3%    |
| Dell Studio           | 6         | 0.3%    |
| ASUS TUF              | 6         | 0.3%    |
| Apple MacBook4        | 6         | 0.3%    |
| Acer TravelMate       | 6         | 0.3%    |
| Acer Swift            | 6         | 0.3%    |
| Acer Extensa          | 6         | 0.3%    |
| Toshiba PORTEGE       | 5         | 0.25%   |
| Packard Bell EasyNote | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 209       | 10.57%  |
| 2019    | 200       | 10.12%  |
| 2021    | 157       | 7.94%   |
| 2011    | 157       | 7.94%   |
| 2015    | 145       | 7.33%   |
| 2018    | 142       | 7.18%   |
| 2013    | 140       | 7.08%   |
| 2012    | 123       | 6.22%   |
| 2016    | 112       | 5.67%   |
| 2010    | 102       | 5.16%   |
| 2017    | 99        | 5.01%   |
| 2014    | 90        | 4.55%   |
| 2009    | 82        | 4.15%   |
| 2022    | 76        | 3.84%   |
| 2008    | 58        | 2.93%   |
| 2007    | 33        | 1.67%   |
| 2006    | 24        | 1.21%   |
| Unknown | 9         | 0.46%   |
| 2005    | 6         | 0.3%    |
| 2004    | 5         | 0.25%   |
| 2003    | 5         | 0.25%   |
| 2002    | 3         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1977      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1947      | 98.48%  |
| Yes  | 30        | 1.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 732       | 36.64%  |
| 4.01-8.0    | 480       | 24.02%  |
| 16.01-24.0  | 437       | 21.87%  |
| 32.01-64.0  | 107       | 5.36%   |
| 2.01-3.0    | 93        | 4.65%   |
| 3.01-4.0    | 57        | 2.85%   |
| 0.51-1.0    | 23        | 1.15%   |
| 24.01-32.0  | 22        | 1.1%    |
| 1.01-2.0    | 20        | 1%      |
| 64.01-256.0 | 18        | 0.9%    |
| 0.01-0.5    | 8         | 0.4%    |
| 0           | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1144      | 56.41%  |
| 0.51-1.0    | 545       | 26.87%  |
| 1.01-2.0    | 177       | 8.73%   |
| 2.01-3.0    | 60        | 2.96%   |
| 4.01-8.0    | 24        | 1.18%   |
| Unknown     | 23        | 1.13%   |
| 8.01-16.0   | 19        | 0.94%   |
| 0           | 18        | 0.89%   |
| 3.01-4.0    | 7         | 0.35%   |
| 24.01-32.0  | 4         | 0.2%    |
| 16.01-24.0  | 4         | 0.2%    |
| 32.01-64.0  | 2         | 0.1%    |
| 64.01-256.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1478      | 72.88%  |
| 2      | 396       | 19.53%  |
| 0      | 95        | 4.68%   |
| 3      | 49        | 2.42%   |
| 4      | 10        | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1409      | 70.63%  |
| Yes       | 586       | 29.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1718      | 86.86%  |
| No        | 260       | 13.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1844      | 93.08%  |
| No        | 137       | 6.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1271      | 63.52%  |
| No        | 730       | 36.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 391       | 19.61%  |
| Germany     | 228       | 11.43%  |
| Russia      | 130       | 6.52%   |
| France      | 102       | 5.12%   |
| UK          | 77        | 3.86%   |
| Brazil      | 74        | 3.71%   |
| Canada      | 63        | 3.16%   |
| China       | 59        | 2.96%   |
| Italy       | 55        | 2.76%   |
| Poland      | 53        | 2.66%   |
| Netherlands | 52        | 2.61%   |
| Spain       | 50        | 2.51%   |
| Ukraine     | 39        | 1.96%   |
| Australia   | 34        | 1.71%   |
| Switzerland | 32        | 1.6%    |
| India       | 32        | 1.6%    |
| Sweden      | 27        | 1.35%   |
| Austria     | 27        | 1.35%   |
| Indonesia   | 25        | 1.25%   |
| Japan       | 22        | 1.1%    |
| Norway      | 20        | 1%      |
| Mexico      | 19        | 0.95%   |
| Finland     | 19        | 0.95%   |
| Portugal    | 18        | 0.9%    |
| Hungary     | 18        | 0.9%    |
| Czechia     | 18        | 0.9%    |
| Romania     | 15        | 0.75%   |
| Argentina   | 15        | 0.75%   |
| Denmark     | 14        | 0.7%    |
| New Zealand | 12        | 0.6%    |
| Bulgaria    | 12        | 0.6%    |
| Turkey      | 11        | 0.55%   |
| Philippines | 11        | 0.55%   |
| Latvia      | 11        | 0.55%   |
| Greece      | 11        | 0.55%   |
| Colombia    | 11        | 0.55%   |
| Belgium     | 9         | 0.45%   |
| Vietnam     | 8         | 0.4%    |
| Slovakia    | 8         | 0.4%    |
| Croatia     | 8         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 46        | 2.15%   |
| Berlin            | 24        | 1.12%   |
| Brooklyn          | 22        | 1.03%   |
| Vienna            | 21        | 0.98%   |
| Paris             | 20        | 0.93%   |
| Montreal          | 18        | 0.84%   |
| Zurich            | 15        | 0.7%    |
| St Petersburg     | 15        | 0.7%    |
| Kyiv              | 14        | 0.65%   |
| Amsterdam         | 14        | 0.65%   |
| Warsaw            | 12        | 0.56%   |
| Rome              | 11        | 0.51%   |
| Riga              | 11        | 0.51%   |
| Jakarta           | 11        | 0.51%   |
| Seattle           | 10        | 0.47%   |
| London            | 10        | 0.47%   |
| Frankfurt am Main | 10        | 0.47%   |
| Saint-Laurent     | 9         | 0.42%   |
| Portland          | 9         | 0.42%   |
| New York          | 9         | 0.42%   |
| Madrid            | 9         | 0.42%   |
| Los Angeles       | 9         | 0.42%   |
| Sydney            | 8         | 0.37%   |
| Munich            | 8         | 0.37%   |
| Brighton          | 8         | 0.37%   |
| Barcelona         | 8         | 0.37%   |
| Athens            | 8         | 0.37%   |
| Vancouver         | 7         | 0.33%   |
| Hamburg           | 7         | 0.33%   |
| Guangzhou         | 7         | 0.33%   |
| Franconville      | 7         | 0.33%   |
| Dublin            | 7         | 0.33%   |
| Bucharest         | 7         | 0.33%   |
| Vladivostok       | 6         | 0.28%   |
| Sofia             | 6         | 0.28%   |
| Oslo              | 6         | 0.28%   |
| Gdansk            | 6         | 0.28%   |
| Curitiba          | 6         | 0.28%   |
| Chicago           | 6         | 0.28%   |
| Brisbane          | 6         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 406       | 546    | 17.85%  |
| WDC                 | 314       | 396    | 13.81%  |
| Seagate             | 207       | 260    | 9.1%    |
| Toshiba             | 160       | 221    | 7.04%   |
| Kingston            | 129       | 161    | 5.67%   |
| Crucial             | 114       | 145    | 5.01%   |
| SanDisk             | 112       | 134    | 4.93%   |
| Hitachi             | 86        | 102    | 3.78%   |
| Transcend           | 85        | 113    | 3.74%   |
| NVMe                | 72        | 95     | 3.17%   |
| Intel               | 71        | 82     | 3.12%   |
| HGST                | 45        | 74     | 1.98%   |
| SK hynix            | 44        | 53     | 1.93%   |
| A-DATA Technology   | 36        | 47     | 1.58%   |
| Micron Technology   | 34        | 41     | 1.5%    |
| Apple               | 28        | 29     | 1.23%   |
| Fujitsu             | 22        | 31     | 0.97%   |
| SPCC                | 19        | 22     | 0.84%   |
| PNY                 | 17        | 19     | 0.75%   |
| Phison              | 15        | 22     | 0.66%   |
| KIOXIA              | 15        | 15     | 0.66%   |
| KingSpec            | 15        | 17     | 0.66%   |
| LITEON              | 12        | 16     | 0.53%   |
| Corsair             | 10        | 10     | 0.44%   |
| China               | 10        | 12     | 0.44%   |
| Patriot             | 9         | 12     | 0.4%    |
| OCZ                 | 9         | 12     | 0.4%    |
| Hewlett-Packard     | 9         | 12     | 0.4%    |
| Gigabyte Technology | 9         | 13     | 0.4%    |
| OWC                 | 8         | 9      | 0.35%   |
| Intenso             | 8         | 9      | 0.35%   |
| Apacer              | 8         | 9      | 0.35%   |
| LITEONIT            | 7         | 7      | 0.31%   |
| SSSTC               | 6         | 6      | 0.26%   |
| Lexar               | 6         | 12     | 0.26%   |
| Team                | 5         | 6      | 0.22%   |
| Silicon Motion      | 5         | 5      | 0.22%   |
| Plextor             | 5         | 5      | 0.22%   |
| Netac               | 5         | 5      | 0.22%   |
| Kston               | 5         | 7      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 29        | 1.24%   |
| Seagate ST1000LM035-1RK172 1TB      | 28        | 1.19%   |
| Toshiba MQ01ABD100 1TB              | 26        | 1.11%   |
| Transcend TS256GMTS952T2 256GB      | 23        | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 21        | 0.89%   |
| Samsung SSD 860 EVO 500GB           | 21        | 0.89%   |
| Crucial CT500MX500SSD1 500GB        | 21        | 0.89%   |
| Transcend TS256GMTE652T2 256GB      | 18        | 0.77%   |
| Samsung SSD 850 EVO 250GB           | 18        | 0.77%   |
| Toshiba MQ01ABF050 500GB            | 17        | 0.72%   |
| Samsung SSD 850 EVO 500GB           | 14        | 0.6%    |
| Kingston SA400S37120G 120GB         | 14        | 0.6%    |
| HGST HTS721010A9E630 1TB            | 14        | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB        | 13        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB         | 12        | 0.51%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 0.47%   |
| Samsung SSD 860 EVO 250GB           | 11        | 0.47%   |
| Seagate ST9500325AS 500GB           | 10        | 0.43%   |
| Samsung SSD 860 EVO 1TB             | 10        | 0.43%   |
| Crucial CT240BX500SSD1 240GB        | 10        | 0.43%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 9         | 0.38%   |
| Seagate ST9500420AS 500GB           | 9         | 0.38%   |
| Seagate ST9320423AS 320GB           | 9         | 0.38%   |
| Seagate ST500LT012-1DG142 500GB     | 9         | 0.38%   |
| Seagate ST1000LM048-2E7172 1TB      | 9         | 0.38%   |
| SanDisk SSD PLUS 240GB              | 9         | 0.38%   |
| Kingston SV300S37A120G 120GB        | 9         | 0.38%   |
| Kingston SA400S37480G 480GB         | 9         | 0.38%   |
| HGST HTS725050A7E630 500GB          | 9         | 0.38%   |
| Toshiba MQ04ABF100 1TB              | 8         | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB     | 8         | 0.34%   |
| Seagate ST1000LM049-2GH172 1TB      | 8         | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB        | 8         | 0.34%   |
| Samsung MZVLW256HEHP-000L7 256GB    | 8         | 0.34%   |
| NVMe WDC PC SN730 SDB 256GB         | 8         | 0.34%   |
| NVMe Samsung SSD 980 2TB            | 8         | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB        | 7         | 0.3%    |
| WDC WD10JPVX-22JC3T0 1TB            | 7         | 0.3%    |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB  | 7         | 0.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                                 | Notebooks | Drives | Percent |
|----------------------------------------|-----------|--------|---------|
| Seagate                                | 207       | 260    | 27.17%  |
| WDC                                    | 201       | 246    | 26.38%  |
| Toshiba                                | 113       | 153    | 14.83%  |
| Hitachi                                | 86        | 102    | 11.29%  |
| NVMe                                   | 49        | 63     | 6.43%   |
| HGST                                   | 45        | 74     | 5.91%   |
| Samsung Electronics                    | 26        | 29     | 3.41%   |
| Fujitsu                                | 21        | 29     | 2.76%   |
| Apple                                  | 3         | 3      | 0.39%   |
| Product:              USB Flash Memory | 2         | 2      | 0.26%   |
| Generic                                | 2         | 2      | 0.26%   |
| USB                                    | 1         | 1      | 0.13%   |
| UFD 2.0                                | 1         | 1      | 0.13%   |
| OPENBSD                                | 1         | 1      | 0.13%   |
| Lexar                                  | 1         | 1      | 0.13%   |
| LDLC F6+                               | 1         | 1      | 0.13%   |
| Jetflash                               | 1         | 1      | 0.13%   |
| IBM/Hitachi                            | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 247       | 325    | 22.58%  |
| SanDisk             | 112       | 134    | 10.24%  |
| Kingston            | 109       | 137    | 9.96%   |
| Crucial             | 100       | 126    | 9.14%   |
| Transcend           | 59        | 85     | 5.39%   |
| WDC                 | 57        | 73     | 5.21%   |
| Intel               | 48        | 55     | 4.39%   |
| Apple               | 25        | 26     | 2.29%   |
| Toshiba             | 23        | 29     | 2.1%    |
| A-DATA Technology   | 23        | 32     | 2.1%    |
| NVMe                | 19        | 22     | 1.74%   |
| SK hynix            | 18        | 19     | 1.65%   |
| Micron Technology   | 18        | 22     | 1.65%   |
| SPCC                | 17        | 19     | 1.55%   |
| PNY                 | 15        | 17     | 1.37%   |
| KingSpec            | 15        | 17     | 1.37%   |
| LITEON              | 11        | 15     | 1.01%   |
| Corsair             | 10        | 10     | 0.91%   |
| China               | 10        | 12     | 0.91%   |
| Patriot             | 9         | 12     | 0.82%   |
| OCZ                 | 9         | 12     | 0.82%   |
| OWC                 | 8         | 9      | 0.73%   |
| Intenso             | 8         | 9      | 0.73%   |
| Hewlett-Packard     | 8         | 11     | 0.73%   |
| Apacer              | 8         | 9      | 0.73%   |
| LITEONIT            | 7         | 7      | 0.64%   |
| Gigabyte Technology | 7         | 10     | 0.64%   |
| Team                | 5         | 6      | 0.46%   |
| Plextor             | 5         | 5      | 0.46%   |
| Phison              | 5         | 6      | 0.46%   |
| Netac               | 5         | 5      | 0.46%   |
| Lexar               | 5         | 11     | 0.46%   |
| Kston               | 5         | 7      | 0.46%   |
| Hoodisk             | 5         | 6      | 0.46%   |
| Zheino              | 4         | 7      | 0.37%   |
| GOODRAM             | 4         | 4      | 0.37%   |
| Mushkin             | 3         | 3      | 0.27%   |
| Leven               | 3         | 3      | 0.27%   |
| KingDian            | 3         | 3      | 0.27%   |
| FORESEE             | 3         | 5      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 990       | 1370   | 46.65%  |
| HDD  | 718       | 970    | 33.84%  |
| NVMe | 414       | 555    | 19.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1578      | 2340   | 79.22%  |
| NVMe | 414       | 555    | 20.78%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1254      | 1748   | 73.81%  |
| 0.51-1.0        | 371       | 492    | 21.84%  |
| 1.01-2.0        | 66        | 90     | 3.88%   |
| 4.01-10.0       | 3         | 3      | 0.18%   |
| 3.01-4.0        | 2         | 3      | 0.12%   |
| More than 100.0 | 1         | 1      | 0.06%   |
| 2.01-3.0        | 1         | 2      | 0.06%   |
| 0               | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 655       | 31.34%  |
| 1-20           | 478       | 22.87%  |
| 251-500        | 429       | 20.53%  |
| 501-1000       | 196       | 9.38%   |
| 51-100         | 161       | 7.7%    |
| 21-50          | 113       | 5.41%   |
| 1001-2000      | 34        | 1.63%   |
| Unknown        | 20        | 0.96%   |
| 2001-3000      | 3         | 0.14%   |
| More than 3000 | 1         | 0.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1681      | 81.92%  |
| 21-50          | 181       | 8.82%   |
| 51-100         | 75        | 3.65%   |
| 101-250        | 65        | 3.17%   |
| Unknown        | 20        | 0.97%   |
| 251-500        | 19        | 0.93%   |
| 501-1000       | 10        | 0.49%   |
| More than 3000 | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 9         | 9      | 2.54%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 13     | 2.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 10     | 2.25%   |
| Seagate ST9500420AS 500GB           | 7         | 9      | 1.97%   |
| Toshiba MQ01ABF050 500GB            | 6         | 8      | 1.69%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 1.69%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.69%   |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 6      | 1.69%   |
| HGST HTS725050A7E630 500GB          | 6         | 12     | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 6      | 1.41%   |
| Hitachi HTS541612J9SA00 120GB       | 5         | 5      | 1.41%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 6      | 1.13%   |
| Toshiba MQ01ABD075 752GB            | 3         | 3      | 0.85%   |
| Toshiba MK3261GSYN 320GB            | 3         | 5      | 0.85%   |
| Seagate ST9500325AS 500GB           | 3         | 4      | 0.85%   |
| Seagate ST9320325AS 320GB           | 3         | 3      | 0.85%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.85%   |
| Micron Technology 1100 SATA 256GB   | 3         | 3      | 0.85%   |
| Hitachi HTS545025B9SA02 250GB       | 3         | 5      | 0.85%   |
| HGST HTS721010A9E630 1TB            | 3         | 15     | 0.85%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 2         | 2      | 0.56%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.56%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 2         | 2      | 0.56%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.56%   |
| WDC WD10JPVX-75JC3T0 1TB            | 2         | 2      | 0.56%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 0.56%   |
| Toshiba MQ01ACF032 320GB            | 2         | 4      | 0.56%   |
| Toshiba MQ01ABD032 320GB            | 2         | 3      | 0.56%   |
| Toshiba MK6475GSX 640GB             | 2         | 3      | 0.56%   |
| Toshiba MK5061GSYN 500GB            | 2         | 2      | 0.56%   |
| Toshiba MK3265GSXN 320GB            | 2         | 7      | 0.56%   |
| Toshiba MK2546GSX 250GB             | 2         | 2      | 0.56%   |
| SSSTC CVB-8D128-HP 128GB            | 2         | 2      | 0.56%   |
| Seagate ST9160821AS 160GB           | 2         | 2      | 0.56%   |
| Seagate ST9160412AS 160GB           | 2         | 2      | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.56%   |
| Seagate ST320LT020-9YG142 320GB     | 2         | 2      | 0.56%   |
| Seagate ST1000LM014-1EJ164 1TB      | 2         | 2      | 0.56%   |
| Samsung Electronics HM160HI 160GB   | 2         | 2      | 0.56%   |
| Kingston SV300S37A120G 120GB        | 2         | 2      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 108    | 24.57%  |
| Toshiba             | 52        | 74     | 14.86%  |
| Hitachi             | 48        | 55     | 13.71%  |
| WDC                 | 47        | 50     | 13.43%  |
| Samsung Electronics | 22        | 25     | 6.29%   |
| Kingston            | 14        | 15     | 4%      |
| Intel               | 14        | 17     | 4%      |
| HGST                | 14        | 34     | 4%      |
| SanDisk             | 8         | 9      | 2.29%   |
| Micron Technology   | 7         | 7      | 2%      |
| Fujitsu             | 5         | 8      | 1.43%   |
| Crucial             | 5         | 8      | 1.43%   |
| A-DATA Technology   | 4         | 8      | 1.14%   |
| Corsair             | 3         | 3      | 0.86%   |
| Apple               | 3         | 3      | 0.86%   |
| SSSTC               | 2         | 2      | 0.57%   |
| SK hynix            | 2         | 2      | 0.57%   |
| OCZ                 | 2         | 2      | 0.57%   |
| LITEON              | 2         | 2      | 0.57%   |
| China               | 2         | 3      | 0.57%   |
| Transcend           | 1         | 1      | 0.29%   |
| SMI                 | 1         | 1      | 0.29%   |
| Patriot             | 1         | 1      | 0.29%   |
| Kston               | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| Hewlett-Packard     | 1         | 2      | 0.29%   |
| AGI                 | 1         | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 86        | 108    | 33.2%   |
| Toshiba             | 50        | 68     | 19.31%  |
| Hitachi             | 48        | 55     | 18.53%  |
| WDC                 | 46        | 49     | 17.76%  |
| HGST                | 14        | 34     | 5.41%   |
| Samsung Electronics | 8         | 10     | 3.09%   |
| Fujitsu             | 5         | 8      | 1.93%   |
| IBM/Hitachi         | 1         | 1      | 0.39%   |
| Apple               | 1         | 1      | 0.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 249       | 334    | 73.24%  |
| SSD  | 86        | 105    | 25.29%  |
| NVMe | 5         | 5      | 1.47%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                 | 1         | 1      | 25%     |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 25%     |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 25%     |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| HPE                 | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1573      | 2330   | 78.49%  |
| Malfunc  | 339       | 444    | 16.92%  |
| Detected | 88        | 117    | 4.39%   |
| Failed   | 4         | 4      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1475      | 67.17%  |
| AMD                              | 196       | 8.93%   |
| Samsung Electronics              | 182       | 8.29%   |
| SanDisk                          | 80        | 3.64%   |
| SK hynix                         | 33        | 1.5%    |
| Transcend                        | 24        | 1.09%   |
| Toshiba                          | 24        | 1.09%   |
| Nvidia                           | 22        | 1%      |
| Kingston Technology Company      | 21        | 0.96%   |
| Phison Electronics               | 19        | 0.87%   |
| KIOXIA                           | 19        | 0.87%   |
| Micron Technology                | 18        | 0.82%   |
| Silicon Motion                   | 15        | 0.68%   |
| Micron/Crucial Technology        | 13        | 0.59%   |
| ADATA Technology                 | 11        | 0.5%    |
| Silicon Integrated Systems [SiS] | 6         | 0.27%   |
| Lenovo                           | 6         | 0.27%   |
| Union Memory (Shenzhen)          | 5         | 0.23%   |
| Solid State Storage Technology   | 5         | 0.23%   |
| Realtek Semiconductor            | 5         | 0.23%   |
| JMicron Technology               | 5         | 0.23%   |
| VIA Technologies                 | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.09%   |
| Marvell Technology Group         | 2         | 0.09%   |
| Biwin Storage Technology         | 2         | 0.09%   |
| ULi Electronics                  | 1         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 197       | 8.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 182       | 7.71%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 162       | 6.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 156       | 6.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 116       | 4.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 99        | 4.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 90        | 3.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 80        | 3.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 74        | 3.13%   |
| Unknown                                                                          | 73        | 3.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 56        | 2.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 56        | 2.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 46        | 1.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 45        | 1.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 41        | 1.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 36        | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 36        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 30        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                  | 28        | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                            | 28        | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 25        | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 24        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 24        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 24        | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 23        | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 23        | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 23        | 0.97%   |
| Nvidia MCP79 AHCI Controller                                                     | 22        | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 22        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 18        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 18        | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 17        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 16        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 16        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 15        | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 15        | 0.64%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 14        | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 12        | 0.51%   |
| Samsung SM951 AHCI                                                               | 11        | 0.47%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 11        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1516      | 66.55%  |
| NVMe | 472       | 20.72%  |
| IDE  | 208       | 9.13%   |
| RAID | 82        | 3.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1699      | 85.81%  |
| AMD          | 275       | 13.89%  |
| PowerPC      | 2         | 0.1%    |
| ARM          | 1         | 0.05%   |
| 123456789ABC | 1         | 0.05%   |
| 11th         | 1         | 0.05%   |
| Unknown      | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 52        | 2.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 43        | 2.16%   |
| Intel CPU Version                       | 36        | 1.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 36        | 1.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 32        | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 26        | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 25        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 25        | 1.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 25        | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 23        | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 23        | 1.15%   |
| AMD Ryzen Embedded V1500B               | 23        | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 21        | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 20        | 1%      |
| Intel Core i7-3520M CPU @ 2.90GHz       | 19        | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 19        | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 18        | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 18        | 0.9%    |
| Intel Core 2 Duo                        | 18        | 0.9%    |
| AMD EPYC 3201 8-Core Processor          | 18        | 0.9%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 17        | 0.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 17        | 0.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 17        | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 16        | 0.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 15        | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 15        | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 15        | 0.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 14        | 0.7%    |
| Intel Core i5-2540M CPU @ 2.60GHz       | 14        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 14        | 0.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 13        | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 13        | 0.65%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 13        | 0.65%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 13        | 0.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 13        | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 12        | 0.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 11        | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 11        | 0.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 613       | 30.87%  |
| Intel Core i7           | 438       | 22.05%  |
| Intel Core i3           | 142       | 7.15%   |
| Intel Core 2 Duo        | 130       | 6.55%   |
| Other                   | 114       | 5.74%   |
| Intel Celeron           | 91        | 4.58%   |
| AMD Ryzen 7             | 49        | 2.47%   |
| AMD Ryzen 5             | 43        | 2.17%   |
| Intel Atom              | 39        | 1.96%   |
| Intel Pentium           | 34        | 1.71%   |
| AMD EPYC                | 26        | 1.31%   |
| AMD Ryzen Embedded      | 23        | 1.16%   |
| Intel Pentium M         | 19        | 0.96%   |
| AMD A6                  | 17        | 0.86%   |
| Intel Core 2            | 15        | 0.76%   |
| Intel Genuine           | 14        | 0.7%    |
| AMD Ryzen 7 PRO         | 13        | 0.65%   |
| Intel Xeon              | 11        | 0.55%   |
| Intel Pentium Silver    | 11        | 0.55%   |
| AMD Ryzen 3             | 11        | 0.55%   |
| AMD E                   | 9         | 0.45%   |
| AMD A8                  | 9         | 0.45%   |
| AMD Ryzen 5 PRO         | 8         | 0.4%    |
| AMD E1                  | 8         | 0.4%    |
| Intel Pentium Dual      | 7         | 0.35%   |
| AMD A4                  | 7         | 0.35%   |
| Intel Core i9           | 6         | 0.3%    |
| Intel Pentium Dual-Core | 5         | 0.25%   |
| Intel Core m3           | 5         | 0.25%   |
| AMD E2                  | 5         | 0.25%   |
| AMD A10                 | 5         | 0.25%   |
| Intel Pentium 4         | 4         | 0.2%    |
| Intel Core M            | 4         | 0.2%    |
| Intel Core Duo          | 4         | 0.2%    |
| Intel Celeron M         | 4         | 0.2%    |
| AMD C-50                | 4         | 0.2%    |
| Intel 686-class         | 3         | 0.15%   |
| AMD GX                  | 3         | 0.15%   |
| Intel Mobile Pentium 4  | 2         | 0.1%    |
| Intel Core Solo         | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1021      | 51.38%  |
| 4       | 497       | 25.01%  |
| Unknown | 177       | 8.91%   |
| 8       | 109       | 5.49%   |
| 1       | 59        | 2.97%   |
| 6       | 58        | 2.92%   |
| 16      | 42        | 2.11%   |
| 12      | 21        | 1.06%   |
| 24      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |
| 10      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 1898      | 95.52%  |
| Unknown | 57        | 2.87%   |
| 2       | 32        | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1287      | 64.8%   |
| 1       | 489       | 24.62%  |
| Unknown | 210       | 10.57%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 337       | 16.99%  |
| IvyBridge       | 204       | 10.28%  |
| Haswell         | 185       | 9.32%   |
| SandyBridge     | 182       | 9.17%   |
| Skylake         | 143       | 7.21%   |
| Penryn          | 124       | 6.25%   |
| Broadwell       | 108       | 5.44%   |
| Westmere        | 86        | 4.33%   |
| Core            | 68        | 3.43%   |
| Zen             | 62        | 3.13%   |
| Unknown         | 49        | 2.47%   |
| Bonnell         | 48        | 2.42%   |
| Zen 2           | 41        | 2.07%   |
| Silvermont      | 41        | 2.07%   |
| Zen+            | 39        | 1.97%   |
| TigerLake       | 35        | 1.76%   |
| P6              | 32        | 1.61%   |
| CometLake       | 29        | 1.46%   |
| Goldmont plus   | 19        | 0.96%   |
| Bobcat          | 19        | 0.96%   |
| Goldmont        | 17        | 0.86%   |
| Excavator       | 17        | 0.86%   |
| Puma            | 16        | 0.81%   |
| Zen 3           | 15        | 0.76%   |
| Jaguar          | 14        | 0.71%   |
| IceLake         | 12        | 0.6%    |
| K10             | 8         | 0.4%    |
| NetBurst        | 7         | 0.35%   |
| Piledriver      | 6         | 0.3%    |
| K8 Hammer       | 5         | 0.25%   |
| K10 Llano       | 5         | 0.25%   |
| Nehalem         | 4         | 0.2%    |
| Steamroller     | 3         | 0.15%   |
| K8 & K10 hybrid | 3         | 0.15%   |
| Geode           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1530      | 67.67%  |
| Nvidia                           | 380       | 16.81%  |
| AMD                              | 340       | 15.04%  |
| Silicon Integrated Systems [SiS] | 4         | 0.18%   |
| VIA Technologies                 | 2         | 0.09%   |
| Silicon Motion                   | 2         | 0.09%   |
| Trident Microsystems             | 1         | 0.04%   |
| S3 Graphics                      | 1         | 0.04%   |
| ATI                              | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 192       | 8.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 169       | 7.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 127       | 5.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 102       | 4.33%   |
| Intel HD Graphics 5500                                                                   | 93        | 3.94%   |
| Intel HD Graphics 620                                                                    | 74        | 3.14%   |
| Intel UHD Graphics 620                                                                   | 70        | 2.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 66        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 66        | 2.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 52        | 2.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 49        | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 48        | 2.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 41        | 1.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 41        | 1.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 1.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 1.7%    |
| AMD Renoir                                                                               | 40        | 1.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 1.48%   |
| Intel HD Graphics 530                                                                    | 29        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 0.98%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 23        | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 21        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.85%   |
| Intel HD Graphics 630                                                                    | 20        | 0.85%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 19        | 0.81%   |
| Nvidia C79 [GeForce 9400M]                                                               | 18        | 0.76%   |
| AMD Lucienne                                                                             | 18        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.59%   |
| Nvidia TU117M                                                                            | 13        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 0.55%   |
| Intel HD Graphics 500                                                                    | 13        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.51%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.51%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 12        | 0.51%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 11        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1051      | 52.87%  |
| 1 x AMD                  | 251       | 12.63%  |
| Intel + Nvidia           | 248       | 12.47%  |
| 2 x Intel                | 175       | 8.8%    |
| 1 x Nvidia               | 106       | 5.33%   |
| Intel + AMD              | 57        | 2.87%   |
| Other                    | 52        | 2.62%   |
| AMD + Nvidia             | 22        | 1.11%   |
| 2 x AMD                  | 9         | 0.45%   |
| 2 x Nvidia               | 5         | 0.25%   |
| 1 x SiS                  | 4         | 0.2%    |
| 1 x VIA                  | 2         | 0.1%    |
| 1 x Silicon Motion       | 2         | 0.1%    |
| 2 x Intel + 1 x Nvidia   | 1         | 0.05%   |
| 1 x Trident Microsystems | 1         | 0.05%   |
| 1 x S3 Graphics          | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1753      | 87.56%  |
| Unknown     | 126       | 6.29%   |
| Proprietary | 123       | 6.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1752      | 87.12%  |
| 0.01-0.5   | 121       | 6.02%   |
| 1.01-2.0   | 59        | 2.93%   |
| 0.51-1.0   | 38        | 1.89%   |
| 3.01-4.0   | 24        | 1.19%   |
| 7.01-8.0   | 6         | 0.3%    |
| 5.01-6.0   | 6         | 0.3%    |
| 2.01-3.0   | 4         | 0.2%    |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 308       | 19.49%  |
| AU Optronics            | 296       | 18.73%  |
| Chimei Innolux          | 187       | 11.84%  |
| BOE                     | 177       | 11.2%   |
| Samsung Electronics     | 133       | 8.42%   |
| Lenovo                  | 97        | 6.14%   |
| Apple                   | 50        | 3.16%   |
| Sharp                   | 33        | 2.09%   |
| Chi Mei Optoelectronics | 33        | 2.09%   |
| Dell                    | 24        | 1.52%   |
| InfoVision              | 21        | 1.33%   |
| PANDA                   | 16        | 1.01%   |
| Goldstar                | 16        | 1.01%   |
| Hewlett-Packard         | 15        | 0.95%   |
| Philips                 | 13        | 0.82%   |
| LG Philips              | 13        | 0.82%   |
| AOC                     | 13        | 0.82%   |
| BenQ                    | 11        | 0.7%    |
| Ancor Communications    | 10        | 0.63%   |
| LGD                     | 8         | 0.51%   |
| Acer                    | 8         | 0.51%   |
| HannStar                | 7         | 0.44%   |
| CSO                     | 7         | 0.44%   |
| Panasonic               | 6         | 0.38%   |
| CPT                     | 6         | 0.38%   |
| Toshiba                 | 5         | 0.32%   |
| JDI                     | 5         | 0.32%   |
| Iiyama                  | 5         | 0.32%   |
| ViewSonic               | 4         | 0.25%   |
| Sceptre Tech            | 4         | 0.25%   |
| IBM                     | 4         | 0.25%   |
| Fujitsu Siemens         | 4         | 0.25%   |
| Eizo                    | 3         | 0.19%   |
| ASUSTek Computer        | 3         | 0.19%   |
| Vizio                   | 2         | 0.13%   |
| Unknown                 | 2         | 0.13%   |
| Sony                    | 2         | 0.13%   |
| Nvidia                  | 2         | 0.13%   |
| Lenovo Group Limited    | 2         | 0.13%   |
| ___                     | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 21        | 1.32%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 15        | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 11        | 0.69%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 11        | 0.69%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 10        | 0.63%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 10        | 0.63%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 9         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 9         | 0.57%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 9         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 8         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 8         | 0.5%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 8         | 0.5%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 8         | 0.5%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 8         | 0.5%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 8         | 0.5%    |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 8         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 8         | 0.5%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 8         | 0.5%    |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 8         | 0.5%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 8         | 0.5%    |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 8         | 0.5%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch             | 7         | 0.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch         | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 7         | 0.44%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 7         | 0.44%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 6         | 0.38%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 6         | 0.38%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 6         | 0.38%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 6         | 0.38%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 6         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 6         | 0.38%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                   | 6         | 0.38%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 5         | 0.31%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch              | 5         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 540       | 35.02%  |
| 1366x768 (WXGA)    | 529       | 34.31%  |
| 1280x800 (WXGA)    | 105       | 6.81%   |
| 1600x900 (HD+)     | 98        | 6.36%   |
| 3840x2160 (4K)     | 46        | 2.98%   |
| 2560x1440 (QHD)    | 43        | 2.79%   |
| 1440x900 (WXGA+)   | 29        | 1.88%   |
| 1024x600           | 24        | 1.56%   |
| 1920x1200 (WUXGA)  | 18        | 1.17%   |
| 1280x1024 (SXGA)   | 12        | 0.78%   |
| 1680x1050 (WSXGA+) | 10        | 0.65%   |
| 3200x1800 (QHD+)   | 9         | 0.58%   |
| 2560x1080          | 8         | 0.52%   |
| 2256x1504          | 8         | 0.52%   |
| 2880x1800          | 6         | 0.39%   |
| 2880x1620          | 6         | 0.39%   |
| 1024x768 (XGA)     | 6         | 0.39%   |
| 3440x1440          | 5         | 0.32%   |
| 2560x1600          | 5         | 0.32%   |
| 1920x540           | 4         | 0.26%   |
| Unknown            | 4         | 0.26%   |
| 3000x2000          | 3         | 0.19%   |
| 2160x1440          | 3         | 0.19%   |
| 3840x2400          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1360x768           | 2         | 0.13%   |
| 720x1280           | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3520x1080          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 2520x1680          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1440x960           | 1         | 0.06%   |
| 1280x854           | 1         | 0.06%   |
| 1280x768           | 1         | 0.06%   |
| 1280x720 (HD)      | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 536       | 33.95%  |
| 13      | 480       | 30.4%   |
| 12      | 154       | 9.75%   |
| 17      | 63        | 3.99%   |
| 14      | 60        | 3.8%    |
| 11      | 47        | 2.98%   |
| 24      | 43        | 2.72%   |
| 27      | 33        | 2.09%   |
| 23      | 24        | 1.52%   |
| 10      | 24        | 1.52%   |
| Unknown | 24        | 1.52%   |
| 21      | 13        | 0.82%   |
| 19      | 13        | 0.82%   |
| 34      | 9         | 0.57%   |
| 31      | 8         | 0.51%   |
| 18      | 8         | 0.51%   |
| 22      | 4         | 0.25%   |
| 9       | 4         | 0.25%   |
| 64      | 3         | 0.19%   |
| 29      | 3         | 0.19%   |
| 20      | 3         | 0.19%   |
| 16      | 3         | 0.19%   |
| 42      | 2         | 0.13%   |
| 39      | 2         | 0.13%   |
| 26      | 2         | 0.13%   |
| 54      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 33      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| 6       | 1         | 0.06%   |
| 5       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 890       | 56.54%  |
| 201-300     | 417       | 26.49%  |
| 501-600     | 91        | 5.78%   |
| 351-400     | 67        | 4.26%   |
| 401-500     | 35        | 2.22%   |
| Unknown     | 24        | 1.52%   |
| 601-700     | 19        | 1.21%   |
| 701-800     | 11        | 0.7%    |
| 1001-1500   | 8         | 0.51%   |
| 801-900     | 5         | 0.32%   |
| 101-200     | 4         | 0.25%   |
| 901-1000    | 2         | 0.13%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1196      | 81.64%  |
| 16/10   | 176       | 12.01%  |
| 3/2     | 28        | 1.91%   |
| Unknown | 21        | 1.43%   |
| 21/9    | 14        | 0.96%   |
| 4/3     | 13        | 0.89%   |
| 5/4     | 12        | 0.82%   |
| 6/5     | 1         | 0.07%   |
| 3.18    | 1         | 0.07%   |
| 11/10   | 1         | 0.07%   |
| 1.96    | 1         | 0.07%   |
| 0.46    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 455       | 28.78%  |
| 91-100         | 418       | 26.44%  |
| 61-70          | 154       | 9.74%   |
| 101-110        | 124       | 7.84%   |
| 71-80          | 77        | 4.87%   |
| 201-250        | 75        | 4.74%   |
| 121-130        | 54        | 3.42%   |
| 51-60          | 46        | 2.91%   |
| 301-350        | 37        | 2.34%   |
| 41-50          | 26        | 1.64%   |
| Unknown        | 24        | 1.52%   |
| 351-500        | 21        | 1.33%   |
| 151-200        | 16        | 1.01%   |
| 141-150        | 13        | 0.82%   |
| 251-300        | 11        | 0.7%    |
| 501-1000       | 9         | 0.57%   |
| 131-140        | 6         | 0.38%   |
| More than 1000 | 5         | 0.32%   |
| 1-40           | 5         | 0.32%   |
| 111-120        | 5         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 653       | 41.91%  |
| 101-120       | 488       | 31.32%  |
| 51-100        | 203       | 13.03%  |
| 161-240       | 146       | 9.37%   |
| More than 240 | 41        | 2.63%   |
| Unknown       | 24        | 1.54%   |
| 1-50          | 3         | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1359      | 66.78%  |
| 0     | 514       | 25.26%  |
| 2     | 155       | 7.62%   |
| 3     | 6         | 0.29%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1320      | 42.35%  |
| Realtek Semiconductor             | 754       | 24.19%  |
| Qualcomm Atheros                  | 396       | 12.7%   |
| Broadcom                          | 235       | 7.54%   |
| AMD                               | 50        | 1.6%    |
| Marvell Technology Group          | 48        | 1.54%   |
| Ralink Technology                 | 30        | 0.96%   |
| Ericsson Business Mobile Networks | 26        | 0.83%   |
| TP-Link                           | 25        | 0.8%    |
| Nvidia                            | 21        | 0.67%   |
| Edimax Technology                 | 21        | 0.67%   |
| Sierra Wireless                   | 20        | 0.64%   |
| Ralink                            | 17        | 0.55%   |
| Samsung Electronics               | 14        | 0.45%   |
| Xiaomi                            | 11        | 0.35%   |
| MediaTek                          | 10        | 0.32%   |
| JMicron Technology                | 10        | 0.32%   |
| Google                            | 9         | 0.29%   |
| Huawei Technologies               | 8         | 0.26%   |
| Hewlett-Packard                   | 8         | 0.26%   |
| D-Link System                     | 7         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.19%   |
| Dell                              | 6         | 0.19%   |
| D-Link                            | 6         | 0.19%   |
| ASUSTek Computer                  | 5         | 0.16%   |
| Qualcomm Atheros Communications   | 4         | 0.13%   |
| Qualcomm                          | 4         | 0.13%   |
| NetGear                           | 4         | 0.13%   |
| Apple                             | 4         | 0.13%   |
| Fibocom                           | 3         | 0.1%    |
| VIA Technologies                  | 2         | 0.06%   |
| Realtek                           | 2         | 0.06%   |
| OPPO Electronics                  | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Novatel Wireless                  | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| Atheros                           | 2         | 0.06%   |
| Van Ooijen Technische Informatica | 1         | 0.03%   |
| ULi Electronics                   | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 493       | 12.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 173       | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 162       | 4.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 130       | 3.27%   |
| Intel Wireless 8265 / 8275                                              | 118       | 2.97%   |
| Intel Wireless 7260                                                     | 96        | 2.41%   |
| Intel Wireless 8260                                                     | 94        | 2.36%   |
| Intel Wireless 7265                                                     | 92        | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 72        | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 63        | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 62        | 1.56%   |
| Intel Wi-Fi 6 AX200                                                     | 60        | 1.51%   |
| Intel Ethernet Connection I219-LM                                       | 54        | 1.36%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0               | 49        | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 46        | 1.16%   |
| Intel I210 Gigabit Network Connection                                   | 45        | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                                   | 45        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 44        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                | 43        | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                   | 40        | 1.01%   |
| Intel Ethernet Connection I218-LM                                       | 39        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 39        | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 35        | 0.88%   |
| Intel Ethernet Connection I217-LM                                       | 34        | 0.85%   |
| Intel 82567LM Gigabit Network Connection                                | 33        | 0.83%   |
| Intel Wireless-AC 9260                                                  | 32        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 31        | 0.78%   |
| Intel Wireless 3165                                                     | 30        | 0.75%   |
| Intel Centrino Advanced-N 6200                                          | 30        | 0.75%   |
| Intel I211 Gigabit Network Connection                                   | 29        | 0.73%   |
| Intel Centrino Ultimate-N 6300                                          | 29        | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 29        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 28        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 27        | 0.68%   |
| Intel Wi-Fi 6 AX201                                                     | 27        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                    | 26        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 23        | 0.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 23        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1153      | 56.71%  |
| Qualcomm Atheros                | 348       | 17.12%  |
| Realtek Semiconductor           | 204       | 10.03%  |
| Broadcom                        | 173       | 8.51%   |
| Ralink Technology               | 30        | 1.48%   |
| TP-Link                         | 25        | 1.23%   |
| Edimax Technology               | 21        | 1.03%   |
| Ralink                          | 17        | 0.84%   |
| Sierra Wireless                 | 16        | 0.79%   |
| MediaTek                        | 8         | 0.39%   |
| D-Link System                   | 6         | 0.3%    |
| D-Link                          | 6         | 0.3%    |
| Dell                            | 5         | 0.25%   |
| ASUSTek Computer                | 5         | 0.25%   |
| Qualcomm Atheros Communications | 4         | 0.2%    |
| NetGear                         | 4         | 0.2%    |
| Atheros                         | 2         | 0.1%    |
| Sagem                           | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Mercucys                        | 1         | 0.05%   |
| IMC Networks                    | 1         | 0.05%   |
| BUFFALO                         | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 130       | 6.32%   |
| Intel Wireless 8265 / 8275                                              | 118       | 5.74%   |
| Intel Wireless 7260                                                     | 96        | 4.67%   |
| Intel Wireless 8260                                                     | 94        | 4.57%   |
| Intel Wireless 7265                                                     | 92        | 4.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 72        | 3.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 63        | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 62        | 3.01%   |
| Intel Wi-Fi 6 AX200                                                     | 60        | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 46        | 2.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 44        | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 39        | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 35        | 1.7%    |
| Intel Wireless-AC 9260                                                  | 32        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 31        | 1.51%   |
| Intel Wireless 3165                                                     | 30        | 1.46%   |
| Intel Centrino Advanced-N 6200                                          | 30        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 29        | 1.41%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 28        | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 27        | 1.31%   |
| Intel Wi-Fi 6 AX201                                                     | 27        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 25        | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 23        | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 23        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 22        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 21        | 1.02%   |
| Intel WiFi Link 5100                                                    | 21        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 21        | 1.02%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 21        | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 20        | 0.97%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 20        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 19        | 0.92%   |
| Intel Wireless 3160                                                     | 19        | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 18        | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 18        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 746       | 40.94%  |
| Realtek Semiconductor                  | 671       | 36.83%  |
| Broadcom                               | 105       | 5.76%   |
| Qualcomm Atheros                       | 104       | 5.71%   |
| AMD                                    | 49        | 2.69%   |
| Marvell Technology Group               | 48        | 2.63%   |
| Nvidia                                 | 21        | 1.15%   |
| Samsung Electronics                    | 14        | 0.77%   |
| Xiaomi                                 | 11        | 0.6%    |
| JMicron Technology                     | 10        | 0.55%   |
| Google                                 | 8         | 0.44%   |
| Silicon Integrated Systems [SiS]       | 5         | 0.27%   |
| Qualcomm                               | 4         | 0.22%   |
| Huawei Technologies                    | 3         | 0.16%   |
| Apple                                  | 3         | 0.16%   |
| VIA Technologies                       | 2         | 0.11%   |
| Realtek                                | 2         | 0.11%   |
| OPPO Electronics                       | 2         | 0.11%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.11%   |
| Novatel Wireless                       | 2         | 0.11%   |
| Lenovo                                 | 2         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| HMD Global                             | 1         | 0.05%   |
| Attansic                               | 1         | 0.05%   |
| Aquantia                               | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 493       | 26.88%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 173       | 9.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 162       | 8.83%   |
| Intel Ethernet Connection I219-LM                                 | 54        | 2.94%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 49        | 2.67%   |
| Intel I210 Gigabit Network Connection                             | 45        | 2.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 45        | 2.45%   |
| Intel 82577LM Gigabit Network Connection                          | 43        | 2.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 40        | 2.18%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 1.85%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 29        | 1.58%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 1.2%    |
| Nvidia MCP79 Ethernet                                             | 21        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.93%   |
| Intel 82566MM Gigabit Network Connection                          | 16        | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 14        | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 13        | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 11        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10        | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.55%   |
| Intel 82573L Gigabit Ethernet Controller                          | 10        | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 9         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.49%   |
| Intel Ethernet Connection (3) I218-V                              | 9         | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9         | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1844      | 50.56%  |
| Ethernet | 1718      | 47.11%  |
| Modem    | 54        | 1.48%   |
| Unknown  | 31        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 1346      | 49.74%  |
| WiFi     | 1336      | 49.37%  |
| Modem    | 13        | 0.48%   |
| Unknown  | 11        | 0.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1537      | 77.51%  |
| 1     | 314       | 15.83%  |
| 6     | 46        | 2.32%   |
| 3     | 45        | 2.27%   |
| 5     | 23        | 1.16%   |
| 0     | 11        | 0.55%   |
| 8     | 3         | 0.15%   |
| 4     | 3         | 0.15%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1852      | 92.19%  |
| Yes  | 157       | 7.81%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 684       | 53.15%  |
| Broadcom                        | 139       | 10.8%   |
| Qualcomm Atheros Communications | 90        | 6.99%   |
| Apple                           | 75        | 5.83%   |
| Realtek Semiconductor           | 67        | 5.21%   |
| IMC Networks                    | 45        | 3.5%    |
| Lite-On Technology              | 39        | 3.03%   |
| Foxconn / Hon Hai               | 37        | 2.87%   |
| Dell                            | 30        | 2.33%   |
| Hewlett-Packard                 | 21        | 1.63%   |
| Alps Electric                   | 16        | 1.24%   |
| Cambridge Silicon Radio         | 13        | 1.01%   |
| ASUSTek Computer                | 11        | 0.85%   |
| Ralink                          | 8         | 0.62%   |
| Realtek                         | 7         | 0.54%   |
| Toshiba                         | 2         | 0.16%   |
| Creative Technology             | 2         | 0.16%   |
| Opticis                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 359       | 27.83%  |
| Intel AX201 Bluetooth                                       | 85        | 6.59%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 84        | 6.51%   |
| Intel AX200 Bluetooth                                       | 58        | 4.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 46        | 3.57%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 46        | 3.57%   |
| Apple Bluetooth Host Controller                             | 40        | 3.1%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 28        | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 25        | 1.94%   |
| Intel Wireless-AC 3168 Bluetooth                            | 22        | 1.71%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 21        | 1.63%   |
| Realtek  Bluetooth 4.2 Adapter                              | 17        | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 15        | 1.16%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 14        | 1.09%   |
| Lite-On Atheros AR3012 Bluetooth                            | 14        | 1.09%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 14        | 1.09%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 14        | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 13        | 1.01%   |
| Dell DW375 Bluetooth Module                                 | 12        | 0.93%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 12        | 0.93%   |
| Intel AX210 Bluetooth                                       | 11        | 0.85%   |
| Realtek  Bluetooth Adapter                                  | 10        | 0.78%   |
| Realtek Bluetooth Radio                                     | 10        | 0.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 10        | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 10        | 0.78%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 10        | 0.78%   |
| Apple Built-in iSight (no firmware loaded)                  | 10        | 0.78%   |
| Alps Electric UGTZ4 Bluetooth                               | 10        | 0.78%   |
| Realtek RTL8723B Bluetooth                                  | 9         | 0.7%    |
| Realtek  Bluetooth 4.0 Adapter                              | 9         | 0.7%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 9         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 9         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 9         | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 9         | 0.7%    |
| Ralink RT3290 Bluetooth                                     | 8         | 0.62%   |
| IMC Networks Realtek Bluetooth Adapter                      | 8         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                            | 8         | 0.62%   |
| Realtek Bluetooth Radio                                     | 7         | 0.54%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 7         | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 7         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1648      | 75.49%  |
| AMD                                          | 313       | 14.34%  |
| Nvidia                                       | 145       | 6.64%   |
| Lenovo                                       | 11        | 0.5%    |
| Realtek Semiconductor                        | 7         | 0.32%   |
| GN Netcom                                    | 7         | 0.32%   |
| Silicon Integrated Systems [SiS]             | 6         | 0.27%   |
| Texas Instruments                            | 5         | 0.23%   |
| Logitech                                     | 5         | 0.23%   |
| C-Media Electronics                          | 5         | 0.23%   |
| SteelSeries ApS                              | 3         | 0.14%   |
| Plantronics                                  | 3         | 0.14%   |
| VIA Technologies                             | 2         | 0.09%   |
| Kingston Technology                          | 2         | 0.09%   |
| JMTek                                        | 2         | 0.09%   |
| ESS Technology                               | 2         | 0.09%   |
| Creative Technology                          | 2         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| XMOS                                         | 1         | 0.05%   |
| ULi Electronics                              | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| Sony                                         | 1         | 0.05%   |
| RODE Microphones                             | 1         | 0.05%   |
| Microsoft                                    | 1         | 0.05%   |
| M-Audio                                      | 1         | 0.05%   |
| Hewlett-Packard                              | 1         | 0.05%   |
| Generalplus Technology                       | 1         | 0.05%   |
| DSEA A/S                                     | 1         | 0.05%   |
| CMX Systems                                  | 1         | 0.05%   |
| Cambridge Silicon Radio                      | 1         | 0.05%   |
| Cambridge Audio                              | 1         | 0.05%   |
| Blue Microphones                             | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 259       | 9.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 217       | 8.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 164       | 6.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 145       | 5.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 126       | 4.74%   |
| Intel 8 Series HD Audio Controller                                                                | 125       | 4.7%    |
| Intel Broadwell-U Audio Controller                                                                | 108       | 4.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 103       | 3.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 92        | 3.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 88        | 3.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 73        | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 61        | 2.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 59        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 57        | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 56        | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 53        | 1.99%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 49        | 1.84%   |
| AMD FCH Azalia Controller                                                                         | 48        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 46        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 36        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 33        | 1.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 33        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 31        | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 29        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 28        | 1.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 28        | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 24        | 0.9%    |
| Nvidia MCP79 High Definition Audio                                                                | 22        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 17        | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 16        | 0.6%    |
| AMD Wrestler HDMI Audio                                                                           | 16        | 0.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 0.56%   |
| AMD High Definition Audio Controller                                                              | 14        | 0.53%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 0.45%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 12        | 0.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 11        | 0.41%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 11        | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 561       | 26.61%  |
| SK hynix                     | 435       | 20.64%  |
| Micron Technology            | 204       | 9.68%   |
| Kingston                     | 192       | 9.11%   |
| Unknown                      | 170       | 8.06%   |
| Crucial                      | 91        | 4.32%   |
| Elpida                       | 60        | 2.85%   |
| Transcend                    | 59        | 2.8%    |
| Ramaxel Technology           | 50        | 2.37%   |
| Unknown                      | 44        | 2.09%   |
| Nanya Technology             | 30        | 1.42%   |
| A-DATA Technology            | 30        | 1.42%   |
| Corsair                      | 27        | 1.28%   |
| Smart                        | 22        | 1.04%   |
| G.Skill                      | 14        | 0.66%   |
| Team                         | 10        | 0.47%   |
| 48spaces                     | 8         | 0.38%   |
| Unknown (ABCD)               | 7         | 0.33%   |
| Teikon                       | 7         | 0.33%   |
| PNY                          | 7         | 0.33%   |
| Apacer                       | 7         | 0.33%   |
| Goodram                      | 6         | 0.28%   |
| Neo Forza                    | 5         | 0.24%   |
| Smart Brazil                 | 4         | 0.19%   |
| Patriot                      | 4         | 0.19%   |
| Avant                        | 4         | 0.19%   |
| High Bridge                  | 3         | 0.14%   |
| Goldkey                      | 3         | 0.14%   |
| ASint Technology             | 3         | 0.14%   |
| V-GeN                        | 2         | 0.09%   |
| Toshiba                      | 2         | 0.09%   |
| Super Talent                 | 2         | 0.09%   |
| Silicon Power                | 2         | 0.09%   |
| SHARETRONIC                  | 2         | 0.09%   |
| PUSKILL                      | 2         | 0.09%   |
| Magnum Tech                  | 2         | 0.09%   |
| KomputerBay                  | 2         | 0.09%   |
| V-Color                      | 1         | 0.05%   |
| Unknown (8AFD)               | 1         | 0.05%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown                                                 | 44        | 1.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 42        | 1.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 34        | 1.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 32        | 1.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 31        | 1.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 28        | 1.24%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 27        | 1.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 26        | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 26        | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 24        | 1.06%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s     | 24        | 1.06%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 24        | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 21        | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 21        | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 19        | 0.84%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 18        | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s   | 18        | 0.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 16        | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 15        | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s   | 14        | 0.62%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s   | 14        | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 12        | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s   | 12        | 0.53%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s     | 11        | 0.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 11        | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 11        | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 11        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 10        | 0.44%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 10        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 10        | 0.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 10        | 0.44%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s   | 10        | 0.44%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 10        | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 9         | 0.4%    |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 9         | 0.4%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 9         | 0.4%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 9         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 9         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 9         | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 9         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 879       | 49.63%  |
| DDR4    | 591       | 33.37%  |
| DDR2    | 143       | 8.07%   |
| LPDDR3  | 54        | 3.05%   |
| LPDDR4  | 28        | 1.58%   |
| DDR     | 26        | 1.47%   |
| Unknown | 22        | 1.24%   |
| SDRAM   | 13        | 0.73%   |
| DRAM    | 8         | 0.45%   |
| LPDDR5  | 4         | 0.23%   |
| RAM     | 2         | 0.11%   |
| SRAM    | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1647      | 92.63%  |
| Row Of Chips | 77        | 4.33%   |
| Chip         | 37        | 2.08%   |
| Unknown      | 10        | 0.56%   |
| DIMM         | 7         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 687       | 35.16%  |
| 8192  | 630       | 32.24%  |
| 2048  | 342       | 17.5%   |
| 16384 | 176       | 9.01%   |
| 1024  | 72        | 3.68%   |
| 32768 | 23        | 1.18%   |
| 512   | 15        | 0.77%   |
| 256   | 6         | 0.31%   |
| 128   | 2         | 0.1%    |
| 2560  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 546       | 28.42%  |
| 2667    | 234       | 12.18%  |
| 1333    | 191       | 9.94%   |
| 2400    | 169       | 8.8%    |
| 3200    | 131       | 6.82%   |
| 2133    | 126       | 6.56%   |
| 1334    | 121       | 6.3%    |
| 667     | 91        | 4.74%   |
| Unknown | 62        | 3.23%   |
| 1067    | 58        | 3.02%   |
| 1867    | 51        | 2.65%   |
| 800     | 49        | 2.55%   |
| 533     | 21        | 1.09%   |
| 1066    | 16        | 0.83%   |
| 4267    | 14        | 0.73%   |
| 975     | 11        | 0.57%   |
| 1866    | 6         | 0.31%   |
| 4266    | 4         | 0.21%   |
| 6400    | 3         | 0.16%   |
| 1200    | 3         | 0.16%   |
| 333     | 3         | 0.16%   |
| 2933    | 2         | 0.1%    |
| 166     | 2         | 0.1%    |
| 4800    | 1         | 0.05%   |
| 2666    | 1         | 0.05%   |
| 2048    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |
| 266     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |
| 100     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| ELGIN               | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ELGIN L42PRO                       | 2         | 66.67%  |
| Samsung ML-1610 Mono Laser Printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 411       | 29.76%  |
| Acer                                   | 147       | 10.64%  |
| IMC Networks                           | 138       | 9.99%   |
| Realtek Semiconductor                  | 125       | 9.05%   |
| Microdia                               | 117       | 8.47%   |
| Sunplus Innovation Technology          | 78        | 5.65%   |
| Suyin                                  | 54        | 3.91%   |
| Lite-On Technology                     | 50        | 3.62%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 2.17%   |
| Syntek                                 | 29        | 2.1%    |
| Quanta                                 | 29        | 2.1%    |
| Apple                                  | 24        | 1.74%   |
| Silicon Motion                         | 21        | 1.52%   |
| Lenovo                                 | 20        | 1.45%   |
| Alcor Micro                            | 18        | 1.3%    |
| Luxvisions Innotech Limited            | 12        | 0.87%   |
| Ricoh                                  | 11        | 0.8%    |
| Logitech                               | 11        | 0.8%    |
| ALi                                    | 11        | 0.8%    |
| Z-Star Microelectronics                | 9         | 0.65%   |
| Importek                               | 8         | 0.58%   |
| Primax Electronics                     | 3         | 0.22%   |
| Intel                                  | 3         | 0.22%   |
| Unknown                                | 2         | 0.14%   |
| Tripath Technology                     | 2         | 0.14%   |
| Sonix Technology                       | 2         | 0.14%   |
| ShineTech                              | 2         | 0.14%   |
| Pixart Imaging                         | 2         | 0.14%   |
| OmniVision Technologies                | 2         | 0.14%   |
| DigiTech                               | 2         | 0.14%   |
| SunplusIT                              | 1         | 0.07%   |
| icSpring                               | 1         | 0.07%   |
| Holitech                               | 1         | 0.07%   |
| Genesys Logic                          | 1         | 0.07%   |
| Foxconn / Hon Hai                      | 1         | 0.07%   |
| Denron                                 | 1         | 0.07%   |
| Cubeternet                             | 1         | 0.07%   |
| Creative Technology                    | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 126       | 9.04%   |
| Acer Integrated Camera                    | 67        | 4.81%   |
| Realtek Integrated_Webcam_HD              | 41        | 2.94%   |
| IMC Networks Integrated Camera            | 41        | 2.94%   |
| Chicony HD Webcam                         | 37        | 2.65%   |
| Lite-On Integrated Camera                 | 33        | 2.37%   |
| Microdia Integrated_Webcam_HD             | 32        | 2.3%    |
| Microdia Integrated Webcam                | 32        | 2.3%    |
| Chicony Lenovo Integrated Camera (0.3MP)  | 28        | 2.01%   |
| Sunplus Integrated_Webcam_HD              | 25        | 1.79%   |
| Realtek Realtek USB2.0 PC Camera          | 22        | 1.58%   |
| IMC Networks USB2.0 HD UVC WebCam         | 21        | 1.51%   |
| Chicony Chicony USB2.0 Camera             | 19        | 1.36%   |
| Acer Lenovo EasyCamera                    | 19        | 1.36%   |
| Chicony Integrated Camera (1280x720@30)   | 17        | 1.22%   |
| IMC Networks EasyCamera                   | 16        | 1.15%   |
| Apple FaceTime HD Camera                  | 15        | 1.08%   |
| Syntek Lenovo EasyCamera                  | 14        | 1%      |
| Chicony Integrated Camera [ThinkPad]      | 14        | 1%      |
| Lenovo Integrated Webcam [R5U877]         | 13        | 0.93%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 12        | 0.86%   |
| Chicony HP HD Webcam [Fixed]              | 12        | 0.86%   |
| Realtek USB Camera                        | 11        | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 11        | 0.79%   |
| Acer SunplusIT Integrated Camera          | 11        | 0.79%   |
| Syntek EasyCamera                         | 10        | 0.72%   |
| Acer ThinkPad Integrated Camera           | 10        | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD      | 9         | 0.65%   |
| Microdia Dell Laptop Integrated Webcam HD | 9         | 0.65%   |
| Chicony ThinkPad T490 Webcam              | 9         | 0.65%   |
| Chicony Lenovo EasyCamera                 | 9         | 0.65%   |
| Acer Lenovo Integrated Webcam             | 9         | 0.65%   |
| Microdia Integrated Webcam HD             | 8         | 0.57%   |
| IMC Networks USB2.0 UVC HD Webcam         | 8         | 0.57%   |
| IMC Networks Integrated Webcam            | 8         | 0.57%   |
| Chicony USB2.0 VGA UVC WebCam             | 8         | 0.57%   |
| Chicony USB2.0 HD UVC WebCam              | 8         | 0.57%   |
| ALi Gateway Webcam                        | 8         | 0.57%   |
| Suyin Integrated_Webcam_HD                | 7         | 0.5%    |
| Sunplus HD WebCam                         | 7         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 157       | 39.55%  |
| Synaptics                  | 67        | 16.88%  |
| Upek                       | 49        | 12.34%  |
| AuthenTec                  | 35        | 8.82%   |
| Shenzhen Goodix Technology | 33        | 8.31%   |
| STMicroelectronics         | 25        | 6.3%    |
| Broadcom                   | 15        | 3.78%   |
| LighTuning Technology      | 9         | 2.27%   |
| Elan Microelectronics      | 3         | 0.76%   |
| Samsung Electronics        | 2         | 0.5%    |
| Next Biometrics            | 1         | 0.25%   |
| Focal-systems.Corp         | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 52        | 13.1%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 46        | 11.59%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 30        | 7.56%   |
| Validity Sensors Synaptics WBDI                                              | 26        | 6.55%   |
| STMicroelectronics Fingerprint Reader                                        | 25        | 6.3%    |
| Shenzhen Goodix Fingerprint Reader                                           | 21        | 5.29%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 19        | 4.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 18        | 4.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 15        | 3.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 3.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 14        | 3.53%   |
| AuthenTec AES2810                                                            | 10        | 2.52%   |
| Shenzhen Goodix  FingerPrint Device                                          | 9         | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 9         | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 6         | 1.51%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 6         | 1.51%   |
| Validity Sensors VFS491                                                      | 5         | 1.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 5         | 1.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 5         | 1.26%   |
| AuthenTec AES1600                                                            | 5         | 1.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 4         | 1.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 4         | 1.01%   |
| Validity Sensors Fingerprint scanner                                         | 4         | 1.01%   |
| Unknown                                                                      | 4         | 1.01%   |
| Validity Sensors VFS Fingerprint sensor                                      | 3         | 0.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 3         | 0.76%   |
| Upek TCS5B Fingerprint sensor                                                | 3         | 0.76%   |
| Shenzhen Goodix FingerPrint                                                  | 3         | 0.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 3         | 0.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 3         | 0.76%   |
| LighTuning EgisTec EH575                                                     | 3         | 0.76%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 3         | 0.76%   |
| Synaptics  WBDI                                                              | 2         | 0.5%    |
| Synaptics product 0x00be                                                     | 2         | 0.5%    |
| AuthenTec AuthenTec Inc. AES2660                                             | 2         | 0.5%    |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 0.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 1         | 0.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.25%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 0.25%   |

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
| 1     | 678       | 32.52%  |
| 2     | 606       | 29.06%  |
| 3     | 329       | 15.78%  |
| 0     | 274       | 13.14%  |
| 4     | 144       | 6.91%   |
| 5     | 33        | 1.58%   |
| 6     | 14        | 0.67%   |
| 7     | 5         | 0.24%   |
| 9     | 1         | 0.05%   |
| 8     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1380      | 41.28%  |
| Bluetooth                | 446       | 13.34%  |
| Card reader              | 414       | 12.38%  |
| Net/wireless             | 404       | 12.08%  |
| Fingerprint reader       | 333       | 9.96%   |
| Firewire controller      | 147       | 4.4%    |
| Graphics card            | 65        | 1.94%   |
| Sound                    | 39        | 1.17%   |
| Storage                  | 37        | 1.11%   |
| Network                  | 26        | 0.78%   |
| Modem                    | 22        | 0.66%   |
| Net/ethernet             | 15        | 0.45%   |
| Storage/ata              | 6         | 0.18%   |
| Storage/raid             | 3         | 0.09%   |
| Storage/nvme             | 2         | 0.06%   |
| Storage/ide              | 2         | 0.06%   |
| Dvb card                 | 2         | 0.06%   |

