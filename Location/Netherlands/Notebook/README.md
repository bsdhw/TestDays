BSD in Netherlands - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

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

Total: 127

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Deciso        | OPNsense Appliance          | [f10f897c2a](https://bsd-hardware.info/?probe=f10f897c2a) | Nov 07, 2024 |
| Deciso        | OPNsense Appliance          | [853823751f](https://bsd-hardware.info/?probe=853823751f) | Nov 03, 2024 |
| ASUSTek       | GL752VW                     | [efc1d86951](https://bsd-hardware.info/?probe=efc1d86951) | Nov 02, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [c16eee5fcc](https://bsd-hardware.info/?probe=c16eee5fcc) | Oct 27, 2024 |
| Deciso        | NetBoard-A10                | [98c9b9552b](https://bsd-hardware.info/?probe=98c9b9552b) | Oct 24, 2024 |
| Dell          | Latitude 5440               | [8add6da490](https://bsd-hardware.info/?probe=8add6da490) | Oct 01, 2024 |
| Deciso        | OPNsense Appliance          | [9fbd21afba](https://bsd-hardware.info/?probe=9fbd21afba) | Aug 29, 2024 |
| Deciso        | OPNsense Appliance          | [5eeb077668](https://bsd-hardware.info/?probe=5eeb077668) | Aug 22, 2024 |
| Deciso        | OPNsense Appliance          | [f9c65cab62](https://bsd-hardware.info/?probe=f9c65cab62) | Aug 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [290910cd2c](https://bsd-hardware.info/?probe=290910cd2c) | Jun 07, 2024 |
| HP            | ProBook 6550b               | [8c0329672d](https://bsd-hardware.info/?probe=8c0329672d) | Jun 03, 2024 |
| HP            | OMEN by Laptop              | [7148244e3e](https://bsd-hardware.info/?probe=7148244e3e) | May 21, 2024 |
| Deciso        | NetBoard-A10                | [9dbb0ae3f2](https://bsd-hardware.info/?probe=9dbb0ae3f2) | May 12, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | [0990e7253e](https://bsd-hardware.info/?probe=0990e7253e) | May 07, 2024 |
| Micro Comp... | Venus series                | [11184b32bb](https://bsd-hardware.info/?probe=11184b32bb) | May 05, 2024 |
| HP            | OMEN by Laptop              | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Deciso        | NetBoard-A10                | [659c975065](https://bsd-hardware.info/?probe=659c975065) | Apr 02, 2024 |
| Deciso        | NetBoard-A20                | [f5341b37b3](https://bsd-hardware.info/?probe=f5341b37b3) | Mar 21, 2024 |
| Deciso        | OPNsense Appliance          | [8283ee7c1b](https://bsd-hardware.info/?probe=8283ee7c1b) | Mar 21, 2024 |
| Deciso        | NetBoard-A10                | [0b83b42575](https://bsd-hardware.info/?probe=0b83b42575) | Feb 22, 2024 |
| Micro Comp... | Venus series                | [20e602834b](https://bsd-hardware.info/?probe=20e602834b) | Feb 08, 2024 |
| Micro Comp... | Venus series                | [3a2455558f](https://bsd-hardware.info/?probe=3a2455558f) | Feb 08, 2024 |
| Deciso        | NetBoard-A10                | [6cfe3230e8](https://bsd-hardware.info/?probe=6cfe3230e8) | Feb 07, 2024 |
| Panasonic     | CF-52PGNBX2M                | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| Micro Comp... | Venus series                | [2fbda08743](https://bsd-hardware.info/?probe=2fbda08743) | Feb 03, 2024 |
| Micro Comp... | Venus series                | [e7693b7781](https://bsd-hardware.info/?probe=e7693b7781) | Feb 03, 2024 |
| HP            | ProBook 650 G1              | [50888a6e05](https://bsd-hardware.info/?probe=50888a6e05) | Jan 22, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | [32bc5e823d](https://bsd-hardware.info/?probe=32bc5e823d) | Jan 17, 2024 |
| Micro Comp... | Venus series                | [fc242d0e50](https://bsd-hardware.info/?probe=fc242d0e50) | Jan 13, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Deciso        | NetBoard-A10                | [c728132d77](https://bsd-hardware.info/?probe=c728132d77) | Dec 20, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| Deciso        | OPNsense Appliance          | [cb6b022d45](https://bsd-hardware.info/?probe=cb6b022d45) | Dec 04, 2023 |
| Deciso        | OPNsense Appliance          | [9508bd06f5](https://bsd-hardware.info/?probe=9508bd06f5) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | [d9f0644c56](https://bsd-hardware.info/?probe=d9f0644c56) | Oct 24, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Deciso        | OPNsense Appliance          | [be0008eb2a](https://bsd-hardware.info/?probe=be0008eb2a) | Jun 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| Deciso        | OPNsense Appliance          | [43936f5f1c](https://bsd-hardware.info/?probe=43936f5f1c) | Jun 15, 2023 |
| Deciso        | OPNsense Appliance          | [c47f62b522](https://bsd-hardware.info/?probe=c47f62b522) | May 28, 2023 |
| Apple         | MacBookPro10,1              | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| Medion        | Major X10                   | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Deciso        | OPNsense Appliance          | [2745eadfd9](https://bsd-hardware.info/?probe=2745eadfd9) | May 07, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Deciso        | OPNsense Appliance          | [62452eaaaa](https://bsd-hardware.info/?probe=62452eaaaa) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [96df89832f](https://bsd-hardware.info/?probe=96df89832f) | Feb 04, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| Google        | Cave                        | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Intel         | Milstead Platform           | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Deciso        | NetBoard-A10                | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Deciso        | NetBoard-A10                | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| HP            | EliteBook 840 G3            | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| HP            | EliteBook 840 G3            | [28929cae10](https://bsd-hardware.info/?probe=28929cae10) | Aug 17, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Star Labs     | LabTop                      | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| HP            | EliteBook 8460p             | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Deciso        | OPNsense Appliance          | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| HP            | EliteBook 840 G3            | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Unknown       | Unknown                     | [974e1f4e5e](https://bsd-hardware.info/?probe=974e1f4e5e) | Jan 07, 2022 |
| Toshiba       | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| Apple         | MacBookPro9,2               | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| HP            | 625                         | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| Unknown       | Unknown                     | [d4122c5eb0](https://bsd-hardware.info/?probe=d4122c5eb0) | Aug 03, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| WYSE          | Z CLASS                     | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude E4300              | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| SLIMBOOK      | Unknown                     | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| Notebook      | NL5xRU                      | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Dell          | Latitude E7270              | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| ASUSTek       | X556UA                      | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E4300              | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| Dell          | Latitude E4300              | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Apple         | MacBookPro8,1               | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| Dell          | Latitude 7280               | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Dell          | Latitude 7370               | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| Dell          | Latitude E4300              | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| HP            | EliteBook 2530p             | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| helloSystem 0.7.0   | 8         | 8%      |
| helloSystem 0.8.1   | 6         | 6%      |
| helloSystem 0.5.0   | 6         | 6%      |
| FreeBSD 13.0-STABLE | 5         | 5%      |
| helloSystem 0.8.0   | 4         | 4%      |
| helloSystem 0.6.0   | 3         | 3%      |
| helloSystem 0.3.0   | 3         | 3%      |
| OPNsense 24.1.6     | 2         | 2%      |
| OPNsense 23.10.2    | 2         | 2%      |
| OPNsense 22.10      | 2         | 2%      |
| OpenBSD 7.1         | 2         | 2%      |
| OpenBSD 6.9         | 2         | 2%      |
| OpenBSD 6.8         | 2         | 2%      |
| helloSystem 0.8.2   | 2         | 2%      |
| helloSystem 0.4.0   | 2         | 2%      |
| GhostBSD 22.06.18   | 2         | 2%      |
| FreeBSD 14.0-p6     | 2         | 2%      |
| FreeBSD 14.0-p4     | 2         | 2%      |
| FreeBSD 14.0        | 2         | 2%      |
| FreeBSD 13.1-p4     | 2         | 2%      |
| FreeBSD 13.1        | 2         | 2%      |
| FreeBSD 13.0-p5     | 2         | 2%      |
| OPNsense 24.7.7     | 1         | 1%      |
| OPNsense 24.4.2     | 1         | 1%      |
| OPNsense 24.4.1     | 1         | 1%      |
| OPNsense 24.10      | 1         | 1%      |
| OPNsense 24.1.4     | 1         | 1%      |
| OPNsense 24.1.2     | 1         | 1%      |
| OPNsense 24.1.1     | 1         | 1%      |
| OPNsense 24.1       | 1         | 1%      |
| OPNsense 23.7.10    | 1         | 1%      |
| OPNsense 23.4.1     | 1         | 1%      |
| OPNsense 23.4       | 1         | 1%      |
| OPNsense 23.10      | 1         | 1%      |
| OPNsense 22.7.4     | 1         | 1%      |
| OPNsense 22.7.2     | 1         | 1%      |
| OPNsense 22.7.10    | 1         | 1%      |
| OPNsense 22.10.1    | 1         | 1%      |
| OPNsense 22.1.7     | 1         | 1%      |
| OPNsense 22.1.6     | 1         | 1%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 33        | 41.25%  |
| FreeBSD     | 23        | 28.75%  |
| OPNsense    | 13        | 16.25%  |
| OpenBSD     | 9         | 11.25%  |
| GhostBSD    | 2         | 2.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 79        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 35        | 42.17%  |
| Console      | 17        | 20.48%  |
| MATE         | 5         | 6.02%   |
| GNOME        | 5         | 6.02%   |
| fvwm         | 5         | 6.02%   |
| XFCE         | 4         | 4.82%   |
| TWM          | 3         | 3.61%   |
| KDE5         | 3         | 3.61%   |
| LXQt         | 2         | 2.41%   |
| i3           | 2         | 2.41%   |
| GNUstep      | 1         | 1.2%    |
| AwesomeWM    | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 62        | 78.48%  |
| Console | 15        | 18.99%  |
| Wayland | 2         | 2.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 36        | 44.44%  |
| Console | 30        | 37.04%  |
| LightDM | 5         | 6.17%   |
| XDM     | 4         | 4.94%   |
| SDDM    | 3         | 3.7%    |
| GDM     | 3         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 31        | 37.35%  |
| C       | 20        | 24.1%   |
| Unknown | 19        | 22.89%  |
| nl_NL   | 7         | 8.43%   |
| en      | 3         | 3.61%   |
| fr_FR   | 2         | 2.41%   |
| nl      | 1         | 1.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 68        | 83.95%  |
| BIOS | 13        | 16.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 50        | 62.5%   |
| Ufs    | 11        | 13.75%  |
| Cd9660 | 10        | 12.5%   |
| Ffs    | 9         | 11.25%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 74        | 93.67%  |
| MBR  | 5         | 6.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 23        | 29.11%  |
| Dell                             | 10        | 12.66%  |
| Hewlett-Packard                  | 8         | 10.13%  |
| Deciso                           | 7         | 8.86%   |
| ASUSTek Computer                 | 6         | 7.59%   |
| Apple                            | 4         | 5.06%   |
| Notebook                         | 3         | 3.8%    |
| SLIMBOOK                         | 2         | 2.53%   |
| Micro Computer (HK) Tech Limited | 2         | 2.53%   |
| Acer                             | 2         | 2.53%   |
| Unknown                          | 2         | 2.53%   |
| WYSE                             | 1         | 1.27%   |
| TUXEDO                           | 1         | 1.27%   |
| TOXIC by BTO                     | 1         | 1.27%   |
| Toshiba                          | 1         | 1.27%   |
| Star Labs                        | 1         | 1.27%   |
| Sony                             | 1         | 1.27%   |
| Panasonic                        | 1         | 1.27%   |
| Medion                           | 1         | 1.27%   |
| Intel                            | 1         | 1.27%   |
| Google                           | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Deciso OPNsense Appliance                | 3         | 3.8%    |
| Deciso NetBoard-A10                      | 3         | 3.8%    |
| Unknown                                  | 3         | 3.8%    |
| Micro (HK) Tech Limited Venus series     | 2         | 2.53%   |
| HP EliteBook 840 G3                      | 2         | 2.53%   |
| Dell Latitude E4300                      | 2         | 2.53%   |
| WYSE Z CLASS                             | 1         | 1.27%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 1.27%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 1.27%   |
| Toshiba Satellite C50-B                  | 1         | 1.27%   |
| Star Labs LabTop                         | 1         | 1.27%   |
| Sony SVZ1311C5E                          | 1         | 1.27%   |
| SLIMBOOK PROX-AMD5                       | 1         | 1.27%   |
| Panasonic CF-52PGNBX2M                   | 1         | 1.27%   |
| Notebook NS5x_NS7xPU                     | 1         | 1.27%   |
| Notebook NL5xRU                          | 1         | 1.27%   |
| Notebook N2x0WU                          | 1         | 1.27%   |
| Medion Major X10                         | 1         | 1.27%   |
| Lenovo Yoga 900S-12ISK 80ML              | 1         | 1.27%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 1.27%   |
| Lenovo ThinkPad X61s 76693KG             | 1         | 1.27%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 1.27%   |
| Lenovo ThinkPad X250 20CLS5BU00          | 1         | 1.27%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 1.27%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 1.27%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 1.27%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 1.27%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 1.27%   |
| Lenovo ThinkPad W520 4284GZ1             | 1         | 1.27%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 1         | 1.27%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 1.27%   |
| Lenovo ThinkPad T440 20B7S2LT00          | 1         | 1.27%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 1.27%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MB       | 1         | 1.27%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 1.27%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1      | 1         | 1.27%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.27%   |
| Lenovo IdeaPad 130-15AST 81H5            | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 17        | 21.52%  |
| Dell Latitude                 | 8         | 10.13%  |
| HP EliteBook                  | 4         | 5.06%   |
| Lenovo IdeaPad                | 3         | 3.8%    |
| Deciso OPNsense               | 3         | 3.8%    |
| Deciso NetBoard-A10           | 3         | 3.8%    |
| Unknown                       | 3         | 3.8%    |
| Micro (HK) Tech Limited Venus | 2         | 2.53%   |
| Lenovo Yoga                   | 2         | 2.53%   |
| HP ProBook                    | 2         | 2.53%   |
| Acer Aspire                   | 2         | 2.53%   |
| WYSE Z                        | 1         | 1.27%   |
| TUXEDO Pulse                  | 1         | 1.27%   |
| TOXIC by BTO 15CL872          | 1         | 1.27%   |
| Toshiba Satellite             | 1         | 1.27%   |
| Star Labs LabTop              | 1         | 1.27%   |
| Sony SVZ1311C5E               | 1         | 1.27%   |
| SLIMBOOK PROX-AMD5            | 1         | 1.27%   |
| Panasonic CF-52PGNBX2M        | 1         | 1.27%   |
| Notebook NS5x                 | 1         | 1.27%   |
| Notebook NL5xRU               | 1         | 1.27%   |
| Notebook N2x0WU               | 1         | 1.27%   |
| Medion Major                  | 1         | 1.27%   |
| Lenovo G505s                  | 1         | 1.27%   |
| Intel Milstead                | 1         | 1.27%   |
| HP OMEN                       | 1         | 1.27%   |
| HP 625                        | 1         | 1.27%   |
| Google Cave                   | 1         | 1.27%   |
| Dell XPS                      | 1         | 1.27%   |
| Dell Inspiron                 | 1         | 1.27%   |
| Deciso NetBoard-A20           | 1         | 1.27%   |
| ASUS ZenBook                  | 1         | 1.27%   |
| ASUS X751LB                   | 1         | 1.27%   |
| ASUS X556UA                   | 1         | 1.27%   |
| ASUS VivoBook                 | 1         | 1.27%   |
| ASUS K53TA                    | 1         | 1.27%   |
| ASUS GL752VW                  | 1         | 1.27%   |
| Apple MacBookPro9             | 1         | 1.27%   |
| Apple MacBookPro8             | 1         | 1.27%   |
| Apple MacBookPro10            | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 12        | 15.19%  |
| 2018    | 7         | 8.86%   |
| 2021    | 6         | 7.59%   |
| 2019    | 6         | 7.59%   |
| 2016    | 6         | 7.59%   |
| 2015    | 6         | 7.59%   |
| 2012    | 6         | 7.59%   |
| 2020    | 5         | 6.33%   |
| 2014    | 5         | 6.33%   |
| 2023    | 3         | 3.8%    |
| 2013    | 3         | 3.8%    |
| 2011    | 3         | 3.8%    |
| 2010    | 3         | 3.8%    |
| 2017    | 2         | 2.53%   |
| 2009    | 2         | 2.53%   |
| 2008    | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 79        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 98.73%  |
| Yes  | 1         | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 35        | 44.3%   |
| 16.01-24.0  | 21        | 26.58%  |
| 4.01-8.0    | 16        | 20.25%  |
| 32.01-64.0  | 4         | 5.06%   |
| 64.01-256.0 | 2         | 2.53%   |
| 2.01-3.0    | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 44        | 54.32%  |
| 0.51-1.0 | 23        | 28.4%   |
| 1.01-2.0 | 10        | 12.35%  |
| 3.01-4.0 | 2         | 2.47%   |
| 2.01-3.0 | 2         | 2.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 52        | 63.41%  |
| 2      | 19        | 23.17%  |
| 0      | 7         | 8.54%   |
| 3      | 4         | 4.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 79.75%  |
| Yes       | 16        | 20.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 83.54%  |
| No        | 13        | 16.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 84.81%  |
| No        | 12        | 15.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 64.56%  |
| No        | 28        | 35.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 79        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Amsterdam               | 16        | 18.82%  |
| Utrecht                 | 5         | 5.88%   |
| The Hague               | 5         | 5.88%   |
| Eindhoven               | 4         | 4.71%   |
| Zwolle                  | 3         | 3.53%   |
| Rotterdam               | 2         | 2.35%   |
| Papendrecht             | 2         | 2.35%   |
| Oosterhout              | 2         | 2.35%   |
| Oegstgeest              | 2         | 2.35%   |
| Hoogeveen               | 2         | 2.35%   |
| Hilversum               | 2         | 2.35%   |
| Groningen               | 2         | 2.35%   |
| 's-Hertogenbosch        | 2         | 2.35%   |
| Woerdense Verlaat       | 1         | 1.18%   |
| Westervoort             | 1         | 1.18%   |
| Warmond                 | 1         | 1.18%   |
| Veendam                 | 1         | 1.18%   |
| Tilburg                 | 1         | 1.18%   |
| Rozenburg               | 1         | 1.18%   |
| Roosendaal              | 1         | 1.18%   |
| Rhoon                   | 1         | 1.18%   |
| Ouderkerk aan de Amstel | 1         | 1.18%   |
| Oss                     | 1         | 1.18%   |
| Nuth                    | 1         | 1.18%   |
| Norg                    | 1         | 1.18%   |
| Munnikens-Vinkel        | 1         | 1.18%   |
| Lent                    | 1         | 1.18%   |
| Leiden                  | 1         | 1.18%   |
| Leeuwarden              | 1         | 1.18%   |
| Hoek van Holland        | 1         | 1.18%   |
| Haarlem                 | 1         | 1.18%   |
| Gouda                   | 1         | 1.18%   |
| Elim                    | 1         | 1.18%   |
| Ede                     | 1         | 1.18%   |
| Dronten                 | 1         | 1.18%   |
| Dordrecht               | 1         | 1.18%   |
| Diemen                  | 1         | 1.18%   |
| Deventer                | 1         | 1.18%   |
| Den Dolder              | 1         | 1.18%   |
| De Lutte                | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 31     | 22.09%  |
| WDC                 | 8         | 8      | 9.3%    |
| Transcend           | 8         | 19     | 9.3%    |
| Seagate             | 7         | 10     | 8.14%   |
| Crucial             | 6         | 8      | 6.98%   |
| SanDisk             | 5         | 5      | 5.81%   |
| Toshiba             | 4         | 4      | 4.65%   |
| NVMe                | 3         | 4      | 3.49%   |
| Kingston            | 3         | 3      | 3.49%   |
| VICKTER             | 2         | 4      | 2.33%   |
| Intel               | 2         | 2      | 2.33%   |
| Hitachi             | 2         | 2      | 2.33%   |
| HGST                | 2         | 2      | 2.33%   |
| Gigabyte Technology | 2         | 3      | 2.33%   |
| Apple               | 2         | 3      | 2.33%   |
| Vaseky              | 1         | 1      | 1.16%   |
| Star Drive          | 1         | 1      | 1.16%   |
| SK hynix            | 1         | 1      | 1.16%   |
| Phison              | 1         | 1      | 1.16%   |
| OCZ                 | 1         | 1      | 1.16%   |
| Micron Technology   | 1         | 1      | 1.16%   |
| LITEON              | 1         | 1      | 1.16%   |
| Leven               | 1         | 1      | 1.16%   |
| HPE                 | 1         | 1      | 1.16%   |
| Hoodisk             | 1         | 2      | 1.16%   |
| China               | 1         | 1      | 1.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Transcend TS256GMTE652T2 256GB   | 3         | 3.45%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2.3%    |
| VICKTER SSD 512GB                | 2         | 2.3%    |
| Transcend TS128GMTE110S 128GB    | 2         | 2.3%    |
| Toshiba MQ04ABF100 1TB           | 2         | 2.3%    |
| Seagate ST500LM000-SSHD-8GB      | 2         | 2.3%    |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 2.3%    |
| Samsung SSD 840 EVO 250GB        | 2         | 2.3%    |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 1.15%   |
| WDC WDS500G2B0A 500GB            | 1         | 1.15%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 1.15%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1.15%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1.15%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1         | 1.15%   |
| Vaseky V850-128G                 | 1         | 1.15%   |
| Transcend TS512GMTS430S 512GB    | 1         | 1.15%   |
| Transcend TS256GMTS952T2 256GB   | 1         | 1.15%   |
| Transcend TS256GMTE710T 256GB    | 1         | 1.15%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1.15%   |
| Toshiba THNSFJ256GCSU 256GB      | 1         | 1.15%   |
| Star Drive PCIe SSD 960GB        | 1         | 1.15%   |
| SK hynix SC311 SATA 256GB        | 1         | 1.15%   |
| Seagate ST9250410AS 250GB        | 1         | 1.15%   |
| Seagate ST9160412ASG 160GB       | 1         | 1.15%   |
| Seagate ST500VT000-1DK142 500GB  | 1         | 1.15%   |
| SanDisk SD8SN8U-128G-1006 128GB  | 1         | 1.15%   |
| SanDisk SD8SBAT256G1002 256GB    | 1         | 1.15%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1.15%   |
| SanDisk SD7TB3Q-256G-1006 256GB  | 1         | 1.15%   |
| SanDisk SD6SB1M064G 64GB         | 1         | 1.15%   |
| Samsung SSD PM851 mSATA 512GB    | 1         | 1.15%   |
| Samsung SSD PM841 mSATA 256GB    | 1         | 1.15%   |
| Samsung SSD 980 PRO 1TB          | 1         | 1.15%   |
| Samsung SSD 970 PRO 512GB        | 1         | 1.15%   |
| Samsung SSD 970 EVO 500GB        | 1         | 1.15%   |
| Samsung SSD 870 QVO 1TB          | 1         | 1.15%   |
| Samsung SSD 860 EVO 1TB          | 1         | 1.15%   |
| Samsung SSD 850 EVO 500GB        | 1         | 1.15%   |
| Samsung SSD 850 EVO 250GB        | 1         | 1.15%   |
| Samsung SSD 840 PRO Series 256GB | 1         | 1.15%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 36.84%  |
| WDC                 | 5         | 5      | 26.32%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 22     | 28.26%  |
| SanDisk             | 5         | 5      | 10.87%  |
| Crucial             | 5         | 6      | 10.87%  |
| NVMe                | 3         | 4      | 6.52%   |
| WDC                 | 2         | 2      | 4.35%   |
| VICKTER             | 2         | 4      | 4.35%   |
| Transcend           | 2         | 10     | 4.35%   |
| Apple               | 2         | 3      | 4.35%   |
| Vaseky              | 1         | 1      | 2.17%   |
| Toshiba             | 1         | 1      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| OCZ                 | 1         | 1      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| Leven               | 1         | 1      | 2.17%   |
| Kingston            | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| HPE                 | 1         | 1      | 2.17%   |
| Hoodisk             | 1         | 2      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 42        | 69     | 52.5%   |
| NVMe | 19        | 29     | 23.75%  |
| HDD  | 19        | 22     | 23.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 91     | 75.32%  |
| NVMe | 19        | 29     | 24.68%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 64     | 67.74%  |
| 0.51-1.0   | 19        | 26     | 30.65%  |
| 1.01-2.0   | 1         | 1      | 1.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 24        | 29.27%  |
| 251-500    | 20        | 24.39%  |
| 1-20       | 17        | 20.73%  |
| 501-1000   | 9         | 10.98%  |
| 51-100     | 7         | 8.54%   |
| 21-50      | 2         | 2.44%   |
| 1001-2000  | 2         | 2.44%   |
| Unknown    | 1         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 67        | 83.75%  |
| 21-50    | 4         | 5%      |
| 251-500  | 3         | 3.75%   |
| 101-250  | 2         | 2.5%    |
| 51-100   | 2         | 2.5%    |
| 501-1000 | 1         | 1.25%   |
| Unknown  | 1         | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1      | 20%     |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1      | 20%     |
| Samsung Electronics HS082HB 80GB | 1         | 1      | 20%     |
| Hitachi HTS545032B9A300 320GB    | 1         | 1      | 20%     |
| China SH00M128GB                 | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| SanDisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |
| China               | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 2      | 40%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Transcend TS128GMTE110S 128GB | 1         | 1      | 50%     |
| HPE MK000480GWUGF 480GB       | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor    | Notebooks | Drives | Percent |
|-----------|-----------|--------|---------|
| Transcend | 1         | 1      | 50%     |
| HPE       | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 64        | 107    | 85.33%  |
| Malfunc  | 5         | 5      | 6.67%   |
| Detected | 4         | 6      | 5.33%   |
| Failed   | 2         | 2      | 2.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 52        | 58.43%  |
| AMD                         | 12        | 13.48%  |
| Samsung Electronics         | 9         | 10.11%  |
| Transcend                   | 6         | 6.74%   |
| Phison Electronics          | 3         | 3.37%   |
| Kingston Technology Company | 2         | 2.25%   |
| Toshiba                     | 1         | 1.12%   |
| Seagate Technology          | 1         | 1.12%   |
| SanDisk                     | 1         | 1.12%   |
| Micron/Crucial Technology   | 1         | 1.12%   |
| Micron Technology           | 1         | 1.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 10        | 10.42%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 8         | 8.33%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)  | 5         | 5.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 5         | 5.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 5         | 5.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 5         | 5.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 5.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 4         | 4.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 3         | 3.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 2.08%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 2         | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.08%   |
| Intel Alder Lake-N SATA AHCI Controller                                      | 2         | 2.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 2.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 2.08%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                    | 1         | 1.04%   |
| Toshiba XG4 NVMe SSD Controller                                              | 1         | 1.04%   |
| Seagate FireCuda 520 SSD                                                     | 1         | 1.04%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)    | 1         | 1.04%   |
| Samsung NVMe SSD Controller SM951/PM951                                      | 1         | 1.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 1.04%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 1.04%   |
| Phison E18 PCIe4 NVMe Controller                                             | 1         | 1.04%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.04%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 1         | 1.04%   |
| Micron 2210 NVMe SSD [Cobain]                                                | 1         | 1.04%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 1         | 1.04%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                   | 1         | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 1.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 1         | 1.04%   |
| Intel SSD 660P Series                                                        | 1         | 1.04%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 1.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                            | 1         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 53        | 56.38%  |
| NVMe | 27        | 28.72%  |
| RAID | 10        | 10.64%  |
| IDE  | 4         | 4.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 74.68%  |
| AMD    | 20        | 25.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 5         | 6.33%   |
| Intel N100                              | 2         | 2.53%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 2         | 2.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 2.53%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 2         | 2.53%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 2.53%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 2.53%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 2.53%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 2.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.53%   |
| Intel Core 2 Duo                        | 2         | 2.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.53%   |
| AMD EPYC 3201 8-Core Processor          | 2         | 2.53%   |
| AMD E1-2500 APU with Radeon HD Graphics | 2         | 2.53%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.27%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.27%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 1.27%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i7-3615QM CPU @ 2.30GHz      | 1         | 1.27%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.27%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.27%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.27%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.27%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.27%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.27%   |
| Intel Core i5 CPU M 450 @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.27%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 22        | 27.85%  |
| Intel Core i5      | 15        | 18.99%  |
| Other              | 7         | 8.86%   |
| Intel Core 2 Duo   | 6         | 7.59%   |
| AMD Ryzen Embedded | 5         | 6.33%   |
| AMD Ryzen 7        | 5         | 6.33%   |
| Intel Core i3      | 3         | 3.8%    |
| Intel Core m7      | 2         | 2.53%   |
| AMD EPYC           | 2         | 2.53%   |
| AMD E1             | 2         | 2.53%   |
| Intel Pentium      | 1         | 1.27%   |
| Intel Core m3      | 1         | 1.27%   |
| Intel Celeron      | 1         | 1.27%   |
| Intel Atom         | 1         | 1.27%   |
| AMD Ryzen 5 PRO    | 1         | 1.27%   |
| AMD G              | 1         | 1.27%   |
| AMD E2             | 1         | 1.27%   |
| AMD Athlon II      | 1         | 1.27%   |
| AMD A8             | 1         | 1.27%   |
| AMD A6             | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 39        | 48.75%  |
| 4       | 18        | 22.5%   |
| 8       | 10        | 12.5%   |
| 16      | 4         | 5%      |
| Unknown | 4         | 5%      |
| 6       | 3         | 3.75%   |
| 20      | 1         | 1.25%   |
| 12      | 1         | 1.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 98.73%  |
| 2      | 1         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 48        | 60%     |
| 1       | 28        | 35%     |
| Unknown | 4         | 5%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 10        | 12.66%  |
| Zen         | 8         | 10.13%  |
| Skylake     | 8         | 10.13%  |
| IvyBridge   | 7         | 8.86%   |
| Haswell     | 7         | 8.86%   |
| Unknown     | 7         | 8.86%   |
| Broadwell   | 5         | 6.33%   |
| SandyBridge | 4         | 5.06%   |
| Penryn      | 4         | 5.06%   |
| Zen 2       | 3         | 3.8%    |
| Westmere    | 2         | 2.53%   |
| TigerLake   | 2         | 2.53%   |
| Jaguar      | 2         | 2.53%   |
| Core        | 2         | 2.53%   |
| Silvermont  | 1         | 1.27%   |
| Piledriver  | 1         | 1.27%   |
| K10 Llano   | 1         | 1.27%   |
| K10         | 1         | 1.27%   |
| Excavator   | 1         | 1.27%   |
| CometLake   | 1         | 1.27%   |
| Bonnell     | 1         | 1.27%   |
| Bobcat      | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 70.73%  |
| AMD    | 14        | 17.07%  |
| Nvidia | 10        | 12.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 8.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 6.9%    |
| Intel HD Graphics 5500                                                    | 5         | 5.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 4.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 4.6%    |
| Intel HD Graphics 620                                                     | 3         | 3.45%   |
| Intel HD Graphics 515                                                     | 3         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.45%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 3         | 3.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 2.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 2.3%    |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 2.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.3%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 2.3%    |
| Intel Alder Lake-N [UHD Graphics]                                         | 2         | 2.3%    |
| AMD Lucienne                                                              | 2         | 2.3%    |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 2         | 2.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.15%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.15%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 1.15%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.15%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.15%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.15%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.15%   |
| Intel UHD Graphics 620                                                    | 1         | 1.15%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 1         | 1.15%   |
| Intel HD Graphics 630                                                     | 1         | 1.15%   |
| Intel HD Graphics 530                                                     | 1         | 1.15%   |
| Intel DG2 [Arc A730M]                                                     | 1         | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.15%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.15%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1         | 1.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 1.15%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.15%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 1         | 1.15%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 52.44%  |
| 1 x AMD        | 12        | 14.63%  |
| Intel + Nvidia | 9         | 10.98%  |
| Other          | 7         | 8.54%   |
| 2 x Intel      | 7         | 8.54%   |
| 2 x AMD        | 2         | 2.44%   |
| 1 x Nvidia     | 2         | 2.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 86.42%  |
| Unknown     | 8         | 9.88%   |
| Proprietary | 3         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 86.25%  |
| 0.01-0.5   | 7         | 8.75%   |
| 1.01-2.0   | 2         | 2.5%    |
| 0.51-1.0   | 2         | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 18.64%  |
| Chimei Innolux          | 11        | 18.64%  |
| BOE                     | 8         | 13.56%  |
| AU Optronics            | 8         | 13.56%  |
| Samsung Electronics     | 4         | 6.78%   |
| Apple                   | 4         | 6.78%   |
| Sharp                   | 3         | 5.08%   |
| Lenovo                  | 3         | 5.08%   |
| Chi Mei Optoelectronics | 2         | 3.39%   |
| Sony                    | 1         | 1.69%   |
| Philips                 | 1         | 1.69%   |
| PANDA                   | 1         | 1.69%   |
| Hewlett-Packard         | 1         | 1.69%   |
| AOC                     | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 3.39%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                            | 1         | 1.69%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch                  | 1         | 1.69%   |
| Sharp LCD Monitor SHP1457 2560x1440 280x160mm 12.7-inch                  | 1         | 1.69%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch                  | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.69%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch                  | 1         | 1.69%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch                  | 1         | 1.69%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.69%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 1.69%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.69%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 1.69%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch             | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 380x210mm 17.1-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 380x210mm 17.1-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 340x190mm 15.3-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 340x190mm 15.3-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 350x190mm 15.7-inch | 1         | 1.69%   |
| BOE LCD Monitor BOE0AFC 1920x1080 310x170mm 13.9-inch                    | 1         | 1.69%   |
| BOE LCD Monitor BOE0A81 1920x1080 340x190mm 15.3-inch                    | 1         | 1.69%   |
| BOE LCD Monitor BOE0921 1920x515 310x80mm 12.6-inch                      | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 23        | 38.98%  |
| 1366x768 (WXGA)  | 14        | 23.73%  |
| 1280x800 (WXGA)  | 7         | 11.86%  |
| 1600x900 (HD+)   | 5         | 8.47%   |
| 3840x2160 (4K)   | 3         | 5.08%   |
| 2560x1440 (QHD)  | 3         | 5.08%   |
| 3200x1800 (QHD+) | 1         | 1.69%   |
| 2880x1800        | 1         | 1.69%   |
| 1920x515         | 1         | 1.69%   |
| 1280x1024 (SXGA) | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 19        | 32.2%   |
| 15     | 18        | 30.51%  |
| 12     | 15        | 25.42%  |
| 17     | 3         | 5.08%   |
| 31     | 1         | 1.69%   |
| 27     | 1         | 1.69%   |
| 23     | 1         | 1.69%   |
| 19     | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 50%     |
| 201-300     | 22        | 37.93%  |
| 351-400     | 4         | 6.9%    |
| 601-700     | 2         | 3.45%   |
| 501-600     | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 48        | 82.76%  |
| 16/10 | 7         | 12.07%  |
| 5/4   | 1         | 1.72%   |
| 3/2   | 1         | 1.72%   |
| 3.88  | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 27.12%  |
| 61-70          | 14        | 23.73%  |
| 91-100         | 12        | 20.34%  |
| 101-110        | 6         | 10.17%  |
| 71-80          | 3         | 5.08%   |
| 121-130        | 3         | 5.08%   |
| 351-500        | 1         | 1.69%   |
| 1-40           | 1         | 1.69%   |
| 301-350        | 1         | 1.69%   |
| 201-250        | 1         | 1.69%   |
| 151-200        | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 26        | 45.61%  |
| 101-120       | 14        | 24.56%  |
| 161-240       | 11        | 19.3%   |
| 51-100        | 4         | 7.02%   |
| More than 240 | 2         | 3.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 57        | 70.37%  |
| 0     | 20        | 24.69%  |
| 2     | 4         | 4.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 61        | 49.19%  |
| Realtek Semiconductor             | 28        | 22.58%  |
| Qualcomm Atheros                  | 8         | 6.45%   |
| Broadcom                          | 8         | 6.45%   |
| AMD                               | 7         | 5.65%   |
| TP-Link                           | 4         | 3.23%   |
| Sierra Wireless                   | 1         | 0.81%   |
| Ralink Technology                 | 1         | 0.81%   |
| Ralink                            | 1         | 0.81%   |
| MediaTek                          | 1         | 0.81%   |
| HMD Global                        | 1         | 0.81%   |
| Hewlett-Packard                   | 1         | 0.81%   |
| Fibocom                           | 1         | 0.81%   |
| Ericsson Business Mobile Networks | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 12.9%   |
| Intel Wireless 7265                                                    | 7         | 4.52%   |
| AMD XGMAC 10GbE Controller                                             | 7         | 4.52%   |
| Intel Wireless 7260                                                    | 6         | 3.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 3.23%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 2.58%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.58%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 2.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2.58%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.94%   |
| Intel Wireless 8260                                                    | 3         | 1.94%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 1.94%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 1.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.29%   |
| Intel WiFi Link 5100                                                   | 2         | 1.29%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.29%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 2         | 1.29%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.29%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.29%   |
| TP-Link Wireless USB Adapter                                           | 1         | 0.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 1         | 0.65%   |
| Sierra Wireless EM7455                                                 | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.65%   |
| Ralink RT5370 Wireless Adapter                                         | 1         | 0.65%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                           | 1         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.65%   |
| Intel Wireless 3160                                                    | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 61.54%  |
| Qualcomm Atheros      | 8         | 10.26%  |
| Realtek Semiconductor | 7         | 8.97%   |
| Broadcom              | 7         | 8.97%   |
| TP-Link               | 4         | 5.13%   |
| Sierra Wireless       | 1         | 1.28%   |
| Ralink Technology     | 1         | 1.28%   |
| Ralink                | 1         | 1.28%   |
| MediaTek              | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 7         | 8.97%   |
| Intel Wireless 7260                                            | 6         | 7.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 6.41%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 6.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 5.13%   |
| Intel Wireless 8265 / 8275                                     | 4         | 5.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 5.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 3.85%   |
| Intel Wireless 8260                                            | 3         | 3.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 3.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.56%   |
| Intel WiFi Link 5100                                           | 2         | 2.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 2.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.56%   |
| TP-Link Wireless USB Adapter                                   | 1         | 1.28%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 1.28%   |
| Sierra Wireless EM7455                                         | 1         | 1.28%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.28%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.28%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.28%   |
| Intel Wireless 3160                                            | 1         | 1.28%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 1.28%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.28%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.28%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.28%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 1.28%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 1.28%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 50%     |
| Realtek Semiconductor | 23        | 31.08%  |
| AMD                   | 7         | 9.46%   |
| Broadcom              | 4         | 5.41%   |
| Qualcomm Atheros      | 2         | 2.7%    |
| HMD Global            | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 20        | 27.03%  |
| AMD XGMAC 10GbE Controller                                             | 7         | 9.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 6.76%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 5.41%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 5.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 4.05%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 4.05%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 4.05%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.7%    |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.35%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.35%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.35%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.35%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.35%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.35%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.35%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 1.35%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.35%   |
| Intel 82577LC Gigabit Network Connection                               | 1         | 1.35%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.35%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.35%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data                 | 1         | 1.35%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 49.26%  |
| Ethernet | 66        | 48.53%  |
| Modem    | 2         | 1.47%   |
| Unknown  | 1         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 51.04%  |
| WiFi     | 47        | 48.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 67.09%  |
| 1     | 16        | 20.25%  |
| 5     | 5         | 6.33%   |
| 6     | 3         | 3.8%    |
| 3     | 2         | 2.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 80.72%  |
| Yes  | 16        | 19.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 31        | 59.62%  |
| Broadcom              | 5         | 9.62%   |
| IMC Networks          | 4         | 7.69%   |
| Apple                 | 4         | 7.69%   |
| Hewlett-Packard       | 2         | 3.85%   |
| Foxconn / Hon Hai     | 2         | 3.85%   |
| TP-Link               | 1         | 1.92%   |
| Realtek Semiconductor | 1         | 1.92%   |
| Lite-On Technology    | 1         | 1.92%   |
| Dell                  | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 14        | 26.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 5         | 9.62%   |
| Intel AX200 Bluetooth                                  | 5         | 9.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 2         | 3.85%   |
| Intel AX201 Bluetooth                                  | 2         | 3.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 2         | 3.85%   |
| Apple Bluetooth Host Controller                        | 2         | 3.85%   |
| TP-Link Bluetooth 5.0 USB Adapter                      | 1         | 1.92%   |
| Realtek Bluetooth Adapter                              | 1         | 1.92%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 1.92%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 1.92%   |
| Intel AX211 Bluetooth                                  | 1         | 1.92%   |
| Intel AX210 Bluetooth                                  | 1         | 1.92%   |
| IMC Networks Realtek Bluetooth Adapter                 | 1         | 1.92%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 1.92%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0            | 1         | 1.92%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 1.92%   |
| HP Broadcom 2070 Bluetooth Combo                       | 1         | 1.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 1.92%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 1.92%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth        | 1         | 1.92%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 1.92%   |
| Broadcom Bluetooth 4.1 USB                             | 1         | 1.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 1         | 1.92%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 1.92%   |
| Apple Broadcom Built-in Bluetooth                      | 1         | 1.92%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 58        | 71.6%   |
| AMD    | 20        | 24.69%  |
| Nvidia | 3         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 11        | 10.28%  |
| Intel Sunrise Point-LP HD Audio                                                   | 10        | 9.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 6.54%   |
| Intel Haswell-ULT HD Audio Controller                                             | 6         | 5.61%   |
| Intel 8 Series HD Audio Controller                                                | 6         | 5.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 4.67%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 4.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5         | 4.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 3.74%   |
| AMD FCH Azalia Controller                                                         | 4         | 3.74%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 1.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 1.87%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 2         | 1.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 1.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 1.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 1.87%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 0.93%   |
| Intel Raptor Lake-P/U/H cAVS                                                      | 1         | 0.93%   |
| Intel DG2 Audio Controller                                                        | 1         | 0.93%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1         | 0.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1         | 0.93%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 0.93%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 0.93%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 0.93%   |
| AMD High Definition Audio Controller                                              | 1         | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 0.93%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 0.93%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 23        | 29.11%  |
| Micron Technology     | 14        | 17.72%  |
| SK hynix              | 10        | 12.66%  |
| Transcend             | 7         | 8.86%   |
| Unknown               | 5         | 6.33%   |
| Crucial               | 4         | 5.06%   |
| Kingston              | 3         | 3.8%    |
| Elpida                | 3         | 3.8%    |
| Ramaxel Technology    | 2         | 2.53%   |
| Apacer                | 2         | 2.53%   |
| Team                  | 1         | 1.27%   |
| Nanya Technology      | 1         | 1.27%   |
| Kingmax Semiconductor | 1         | 1.27%   |
| G.Skill               | 1         | 1.27%   |
| Corsair               | 1         | 1.27%   |
| A-DATA Technology     | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 5         | 6.25%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s        | 2         | 2.5%    |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 4000MT/s          | 2         | 2.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.5%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 2         | 2.5%    |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s                | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.25%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.25%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 1.25%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 1.25%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s         | 1         | 1.25%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.25%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.25%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 1.25%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s        | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 1.25%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.25%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.25%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5174BM0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1         | 1.25%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s        | 1         | 1.25%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 1.25%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s       | 1         | 1.25%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 1         | 1.25%   |
| Samsung RAM K4E6E304EB-EGCF 4GB 1867MT/s                     | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 32        | 46.38%  |
| DDR4    | 27        | 39.13%  |
| DDR2    | 3         | 4.35%   |
| LPDDR5  | 2         | 2.9%    |
| LPDDR3  | 2         | 2.9%    |
| LPDDR4  | 1         | 1.45%   |
| DDR5    | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 87.14%  |
| Row Of Chips | 5         | 7.14%   |
| Chip         | 3         | 4.29%   |
| Unknown      | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 31        | 41.33%  |
| 8192  | 26        | 34.67%  |
| 2048  | 9         | 12%     |
| 16384 | 7         | 9.33%   |
| 32768 | 1         | 1.33%   |
| 1024  | 1         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 25.35%  |
| 2667    | 13        | 18.31%  |
| 3200    | 7         | 9.86%   |
| 2133    | 4         | 5.63%   |
| 1867    | 4         | 5.63%   |
| 1334    | 4         | 5.63%   |
| 1333    | 4         | 5.63%   |
| 2400    | 3         | 4.23%   |
| 4000    | 2         | 2.82%   |
| 1866    | 2         | 2.82%   |
| 1067    | 2         | 2.82%   |
| 800     | 2         | 2.82%   |
| 667     | 2         | 2.82%   |
| 4800    | 1         | 1.41%   |
| 4267    | 1         | 1.41%   |
| 1066    | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

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
| Chicony Electronics                    | 18        | 33.33%  |
| IMC Networks                           | 7         | 12.96%  |
| Realtek Semiconductor                  | 6         | 11.11%  |
| Lite-On Technology                     | 4         | 7.41%   |
| Bison Electronics                      | 4         | 7.41%   |
| Microdia                               | 3         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.56%   |
| Apple                                  | 3         | 5.56%   |
| Sunplus Innovation Technology          | 2         | 3.7%    |
| Alcor Micro                            | 2         | 3.7%    |
| Supreme Electronics                    | 1         | 1.85%   |
| Ricoh                                  | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 4         | 7.41%   |
| IMC Networks Integrated Camera                      | 3         | 5.56%   |
| Realtek USB Camera                                  | 2         | 3.7%    |
| Realtek Integrated_Webcam_HD                        | 2         | 3.7%    |
| Microdia Integrated_Webcam_HD                       | 2         | 3.7%    |
| Lite-On Integrated Camera                           | 2         | 3.7%    |
| IMC Networks Realtek PC Camera                      | 2         | 3.7%    |
| Chicony Realtek DMFT RGB                            | 2         | 3.7%    |
| Chicony Chicony USB2.0 Camera                       | 2         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 3.7%    |
| Bison Lenovo EasyCamera                             | 2         | 3.7%    |
| Bison Integrated Camera                             | 2         | 3.7%    |
| Apple FaceTime HD Camera                            | 2         | 3.7%    |
| Supreme Integrated Camera                           | 1         | 1.85%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.85%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.85%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.85%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.85%   |
| Realtek Integrated Webcam HD                        | 1         | 1.85%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.85%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.85%   |
| Lite-On HP Universal Camera                         | 1         | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.85%   |
| IMC Networks EasyCamera                             | 1         | 1.85%   |
| Chicony VGA Webcam                                  | 1         | 1.85%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.85%   |
| Chicony thinkpad t430s camera                       | 1         | 1.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 1.85%   |
| Chicony Integrated IR Camera                        | 1         | 1.85%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.85%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.85%   |
| Chicony HP Webcam [2 MP]                            | 1         | 1.85%   |
| Chicony HD WebCam (Acer)                            | 1         | 1.85%   |
| Chicony HD Webcam                                   | 1         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 1.85%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 1.85%   |
| Alcor Micro ASUS USB2.0 WebCam                      | 1         | 1.85%   |
| Alcor Micro Asus Integrated Webcam                  | 1         | 1.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 3         | 37.5%   |
| Synaptics          | 2         | 25%     |
| AuthenTec          | 2         | 25%     |
| STMicroelectronics | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                   | 1         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 12.5%   |
| STMicroelectronics Fingerprint Reader             | 1         | 12.5%   |
| AuthenTec AES2810                                 | 1         | 12.5%   |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 12.5%   |

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
| 1     | 36        | 45%     |
| 0     | 17        | 21.25%  |
| 2     | 13        | 16.25%  |
| 3     | 9         | 11.25%  |
| 4     | 5         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 52        | 52.53%  |
| Card reader              | 12        | 12.12%  |
| Net/wireless             | 11        | 11.11%  |
| Bluetooth                | 10        | 10.1%   |
| Fingerprint reader       | 7         | 7.07%   |
| Firewire controller      | 4         | 4.04%   |
| Sound                    | 1         | 1.01%   |
| Net/ethernet             | 1         | 1.01%   |
| Graphics card            | 1         | 1.01%   |

