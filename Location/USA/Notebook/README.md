BSD in USA - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for BSD in USA.

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

Total: 536

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | XPS 13 7390                 | [5ec12d679e](https://bsd-hardware.info/?probe=5ec12d679e) | Jul 01, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Unknown       | Unknown                     | [d9e6e5b83a](https://bsd-hardware.info/?probe=d9e6e5b83a) | Jun 29, 2022 |
| Deciso        | NetBoard-A10                | [ace8b06cd3](https://bsd-hardware.info/?probe=ace8b06cd3) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Dell          | Inspiron 5559               | [e0c49be06e](https://bsd-hardware.info/?probe=e0c49be06e) | Jun 27, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Dell          | Inspiron 5559               | [5b7a6bf8f8](https://bsd-hardware.info/?probe=5b7a6bf8f8) | Jun 19, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| Dell          | Inspiron 5559               | [3344e5152d](https://bsd-hardware.info/?probe=3344e5152d) | Jun 16, 2022 |
| Dell          | Inspiron 5559               | [9f630c894a](https://bsd-hardware.info/?probe=9f630c894a) | Jun 16, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| Dell          | Inspiron 5559               | [e7017b0ea5](https://bsd-hardware.info/?probe=e7017b0ea5) | Jun 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Precision M4800             | [b9169c863c](https://bsd-hardware.info/?probe=b9169c863c) | Jun 08, 2022 |
| Dell          | Inspiron 5559               | [1a9b85f6c5](https://bsd-hardware.info/?probe=1a9b85f6c5) | Jun 07, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| Dell          | Inspiron 5559               | [0f0c2bcf67](https://bsd-hardware.info/?probe=0f0c2bcf67) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | [ca9f2125af](https://bsd-hardware.info/?probe=ca9f2125af) | May 31, 2022 |
| Dell          | Inspiron 5559               | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| GPD           | MicroPC                     | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| System76      | Galago Pro                  | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Dell          | Latitude E6430              | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| Deciso        | Netboard A20                | [eba0ffa870](https://bsd-hardware.info/?probe=eba0ffa870) | May 23, 2022 |
| Dell          | Precision M4800             | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Deciso        | Netboard A20                | [1fe95544bd](https://bsd-hardware.info/?probe=1fe95544bd) | May 22, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| HP            | Pavilion dv6                | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Deciso        | Netboard A20                | [f78f6b9abb](https://bsd-hardware.info/?probe=f78f6b9abb) | May 20, 2022 |
| Dell          | Precision M4800             | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| Acer          | Aspire A715-42G             | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Acer          | Aspire A715-42G             | [6dce802641](https://bsd-hardware.info/?probe=6dce802641) | May 10, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Dell          | Inspiron 15-7568            | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| Toshiba       | Satellite P25               | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Framework     | Laptop                      | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| HP            | 2000                        | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Lenovo        | G51-35 80M8                 | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| Deciso        | Netboard A20                | [aa1f373bfb](https://bsd-hardware.info/?probe=aa1f373bfb) | Apr 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [0e836941e0](https://bsd-hardware.info/?probe=0e836941e0) | Apr 11, 2022 |
| Deciso        | Netboard A20                | [d12cd9d1a1](https://bsd-hardware.info/?probe=d12cd9d1a1) | Apr 11, 2022 |
| Datto         | 1000                        | [745e356caa](https://bsd-hardware.info/?probe=745e356caa) | Apr 11, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Dell          | Vostro 1400                 | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Deciso        | Netboard A20                | [c6217643cc](https://bsd-hardware.info/?probe=c6217643cc) | Apr 07, 2022 |
| Gigabyte      | MMLP7AP-00                  | [8116ea4eac](https://bsd-hardware.info/?probe=8116ea4eac) | Apr 07, 2022 |
| MSI           | Bravo 15 A4DDR              | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Datto         | 1000                        | [5974640141](https://bsd-hardware.info/?probe=5974640141) | Mar 31, 2022 |
| Deciso        | Netboard A20                | [51a8ceefee](https://bsd-hardware.info/?probe=51a8ceefee) | Mar 26, 2022 |
| Deciso        | Netboard A20                | [43a1f11ae0](https://bsd-hardware.info/?probe=43a1f11ae0) | Mar 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1af600b3ae](https://bsd-hardware.info/?probe=1af600b3ae) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| HP            | Pavilion dv6                | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo        | ThinkPad X201 32492EU       | [4a5ba4f3e4](https://bsd-hardware.info/?probe=4a5ba4f3e4) | Mar 13, 2022 |
| Apple         | MacBookPro12,1              | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| Framework     | Laptop                      | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Dell          | Latitude D630               | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Dell          | Inspiron 5559               | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude 7480               | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [deac163b52](https://bsd-hardware.info/?probe=deac163b52) | Feb 19, 2022 |
| Acer          | AO725                       | [f53f627e62](https://bsd-hardware.info/?probe=f53f627e62) | Feb 19, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| Notebook      | NS50_70MU                   | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | G3 3500                     | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| Deciso        | Netboard A20                | [43addbbe84](https://bsd-hardware.info/?probe=43addbbe84) | Jan 28, 2022 |
| Deciso        | Netboard A20                | [5f9588cc87](https://bsd-hardware.info/?probe=5f9588cc87) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [208819a667](https://bsd-hardware.info/?probe=208819a667) | Jan 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| Dell          | Inspiron 5555               | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| Deciso        | Netboard A20                | [a25a10c535](https://bsd-hardware.info/?probe=a25a10c535) | Jan 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Deciso        | Netboard A20                | [3559282047](https://bsd-hardware.info/?probe=3559282047) | Jan 18, 2022 |
| Unknown       | Unknown                     | [699e8fdf32](https://bsd-hardware.info/?probe=699e8fdf32) | Jan 16, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| HP            | Laptop 15-dw2xxx            | [a6d7796cea](https://bsd-hardware.info/?probe=a6d7796cea) | Jan 13, 2022 |
| Dell          | Latitude 5510               | [a620d284cb](https://bsd-hardware.info/?probe=a620d284cb) | Jan 12, 2022 |
| Dell          | Latitude E5510              | [5c6b94df97](https://bsd-hardware.info/?probe=5c6b94df97) | Jan 09, 2022 |
| Dell          | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| HP            | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Dell          | XPS 15 9575                 | [e7925aa387](https://bsd-hardware.info/?probe=e7925aa387) | Jan 05, 2022 |
| Framework     | Laptop                      | [324f0fdebc](https://bsd-hardware.info/?probe=324f0fdebc) | Jan 05, 2022 |
| Framework     | Laptop                      | [ba81f48282](https://bsd-hardware.info/?probe=ba81f48282) | Jan 05, 2022 |
| Deciso        | Netboard A20                | [7d859a2d87](https://bsd-hardware.info/?probe=7d859a2d87) | Jan 04, 2022 |
| Deciso        | Netboard A20                | [3896ed1da8](https://bsd-hardware.info/?probe=3896ed1da8) | Jan 04, 2022 |
| Deciso        | Netboard A20                | [c092bc0341](https://bsd-hardware.info/?probe=c092bc0341) | Jan 04, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [0c153d0c98](https://bsd-hardware.info/?probe=0c153d0c98) | Jan 02, 2022 |
| Framework     | Laptop                      | [9c201bb573](https://bsd-hardware.info/?probe=9c201bb573) | Jan 01, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [30590e8ccf](https://bsd-hardware.info/?probe=30590e8ccf) | Dec 31, 2021 |
| Deciso        | Netboard A20                | [3499735c40](https://bsd-hardware.info/?probe=3499735c40) | Dec 31, 2021 |
| Deciso        | Netboard A20                | [9d39675350](https://bsd-hardware.info/?probe=9d39675350) | Dec 30, 2021 |
| Deciso        | Netboard A20                | [41bc512034](https://bsd-hardware.info/?probe=41bc512034) | Dec 30, 2021 |
| Deciso        | Netboard A20                | [291b7f2750](https://bsd-hardware.info/?probe=291b7f2750) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [32080a81c5](https://bsd-hardware.info/?probe=32080a81c5) | Dec 15, 2021 |
| Lenovo        | ThinkPad L470 20J40013US    | [e517ae0a82](https://bsd-hardware.info/?probe=e517ae0a82) | Dec 15, 2021 |
| Dell          | Inspiron 3521               | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| Deciso        | Netboard A20                | [22eae64139](https://bsd-hardware.info/?probe=22eae64139) | Dec 14, 2021 |
| HP            | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| Framework     | Laptop                      | [46dec0c088](https://bsd-hardware.info/?probe=46dec0c088) | Dec 08, 2021 |
| Framework     | Laptop                      | [a8cd4dc680](https://bsd-hardware.info/?probe=a8cd4dc680) | Dec 08, 2021 |
| Toshiba       | Satellite P755              | [44818070a2](https://bsd-hardware.info/?probe=44818070a2) | Dec 08, 2021 |
| Lenovo        | ThinkPad X61 7675H7U        | [545cbe065d](https://bsd-hardware.info/?probe=545cbe065d) | Dec 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4903f23b62](https://bsd-hardware.info/?probe=4903f23b62) | Dec 05, 2021 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| Lenovo        | ThinkPad T520 4243E51       | [82f5612822](https://bsd-hardware.info/?probe=82f5612822) | Nov 29, 2021 |
| Dell          | Latitude 5510               | [3da78c9445](https://bsd-hardware.info/?probe=3da78c9445) | Nov 24, 2021 |
| Acer          | Aspire A315-21              | [44c1f82bee](https://bsd-hardware.info/?probe=44c1f82bee) | Nov 20, 2021 |
| Deciso        | Netboard A20                | [6e7cf5b40b](https://bsd-hardware.info/?probe=6e7cf5b40b) | Nov 20, 2021 |
| Acer          | AO722                       | [98b88ae138](https://bsd-hardware.info/?probe=98b88ae138) | Nov 15, 2021 |
| Datto         | 1000                        | [294ee97676](https://bsd-hardware.info/?probe=294ee97676) | Nov 15, 2021 |
| Deciso        | Netboard A20                | [424007a067](https://bsd-hardware.info/?probe=424007a067) | Nov 13, 2021 |
| Deciso        | Netboard A20                | [127c951a65](https://bsd-hardware.info/?probe=127c951a65) | Nov 12, 2021 |
| Dell          | Vostro 1400                 | [1c594c9ded](https://bsd-hardware.info/?probe=1c594c9ded) | Nov 12, 2021 |
| Apple         | MacBook3,1                  | [61f1f0aef0](https://bsd-hardware.info/?probe=61f1f0aef0) | Nov 10, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [cdccf02902](https://bsd-hardware.info/?probe=cdccf02902) | Nov 04, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [2471e3f337](https://bsd-hardware.info/?probe=2471e3f337) | Nov 04, 2021 |
| Lenovo        | IdeaPad U430 Touch 20270    | [bf50a58600](https://bsd-hardware.info/?probe=bf50a58600) | Nov 04, 2021 |
| Dell          | Latitude D630               | [7e3a92badc](https://bsd-hardware.info/?probe=7e3a92badc) | Nov 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d23636abb2](https://bsd-hardware.info/?probe=d23636abb2) | Oct 31, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Acer          | Aspire E5-573G              | [e390271460](https://bsd-hardware.info/?probe=e390271460) | Oct 29, 2021 |
| HP            | Pavilion g6                 | [9754bc2e72](https://bsd-hardware.info/?probe=9754bc2e72) | Oct 27, 2021 |
| GPD           | MicroPC                     | [8d0ac5e551](https://bsd-hardware.info/?probe=8d0ac5e551) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| Deciso        | Netboard A20                | [d0a79955c6](https://bsd-hardware.info/?probe=d0a79955c6) | Oct 22, 2021 |
| Deciso        | Netboard A20                | [36387cac1a](https://bsd-hardware.info/?probe=36387cac1a) | Oct 21, 2021 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [eaa64b8f25](https://bsd-hardware.info/?probe=eaa64b8f25) | Oct 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 5570               | [9eab523504](https://bsd-hardware.info/?probe=9eab523504) | Oct 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |
| Apple         | MacBookPro10,1              | [1a3d253769](https://bsd-hardware.info/?probe=1a3d253769) | Oct 12, 2021 |
| Deciso        | Netboard A20                | [e4698339bc](https://bsd-hardware.info/?probe=e4698339bc) | Oct 10, 2021 |
| Deciso        | Netboard A20                | [bde99a9c6a](https://bsd-hardware.info/?probe=bde99a9c6a) | Oct 10, 2021 |
| ASUSTek       | K53E                        | [4572d8b5e7](https://bsd-hardware.info/?probe=4572d8b5e7) | Oct 08, 2021 |
| Framework     | Laptop                      | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| Dell          | Latitude E4300              | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [4b03ca3191](https://bsd-hardware.info/?probe=4b03ca3191) | Oct 03, 2021 |
| Dell          | Inspiron 3521               | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Framework     | Laptop                      | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| HP            | Stream Notebook PC 11       | [c8ea8a4c4f](https://bsd-hardware.info/?probe=c8ea8a4c4f) | Sep 30, 2021 |
| HP            | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| System76      | Darter Pro                  | [f99c9f56b7](https://bsd-hardware.info/?probe=f99c9f56b7) | Sep 25, 2021 |
| Lenovo        | ThinkPad T410 2518C5U       | [e937639adc](https://bsd-hardware.info/?probe=e937639adc) | Sep 25, 2021 |
| Dell          | Precision 7710              | [f0bebc2b21](https://bsd-hardware.info/?probe=f0bebc2b21) | Sep 23, 2021 |
| System76      | Galago Pro                  | [ebe0575f31](https://bsd-hardware.info/?probe=ebe0575f31) | Sep 23, 2021 |
| System76      | Galago Pro                  | [2769c09619](https://bsd-hardware.info/?probe=2769c09619) | Sep 23, 2021 |
| Dell          | Precision 7710              | [46e9438bf9](https://bsd-hardware.info/?probe=46e9438bf9) | Sep 22, 2021 |
| Dell          | Latitude 5491               | [006dc5a9f4](https://bsd-hardware.info/?probe=006dc5a9f4) | Sep 22, 2021 |
| Dell          | Latitude E7450              | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| Lenovo        | ThinkPad T61 64607EU        | [34e48b691d](https://bsd-hardware.info/?probe=34e48b691d) | Sep 17, 2021 |
| ASUSTek       | G551JW                      | [5624c69d4b](https://bsd-hardware.info/?probe=5624c69d4b) | Sep 16, 2021 |
| System76      | Galago Pro                  | [41cd62c0fe](https://bsd-hardware.info/?probe=41cd62c0fe) | Sep 16, 2021 |
| Lenovo        | ThinkPad W540 20BG0014US    | [b6dffe77eb](https://bsd-hardware.info/?probe=b6dffe77eb) | Sep 15, 2021 |
| HP            | G42                         | [738ccd1adf](https://bsd-hardware.info/?probe=738ccd1adf) | Sep 15, 2021 |
| Dell          | XPS 13 7390 2-in-1          | [577e0ed7fe](https://bsd-hardware.info/?probe=577e0ed7fe) | Sep 13, 2021 |
| HP            | 250 G5 Notebook PC          | [6e50039406](https://bsd-hardware.info/?probe=6e50039406) | Sep 09, 2021 |
| Apple         | MacBookPro6,2               | [4632683b4b](https://bsd-hardware.info/?probe=4632683b4b) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [4cc349d29a](https://bsd-hardware.info/?probe=4cc349d29a) | Sep 08, 2021 |
| Lenovo        | ThinkPad X250 20CM0046US    | [1ed50b75f1](https://bsd-hardware.info/?probe=1ed50b75f1) | Sep 08, 2021 |
| ASUSTek       | G551JW                      | [309b5d559f](https://bsd-hardware.info/?probe=309b5d559f) | Sep 07, 2021 |
| System76      | Galago Pro                  | [203560e1f5](https://bsd-hardware.info/?probe=203560e1f5) | Sep 07, 2021 |
| System76      | Galago Pro                  | [d3b33c7681](https://bsd-hardware.info/?probe=d3b33c7681) | Sep 07, 2021 |
| System76      | Kudu                        | [c10fc12e40](https://bsd-hardware.info/?probe=c10fc12e40) | Sep 05, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [713b72cfff](https://bsd-hardware.info/?probe=713b72cfff) | Sep 05, 2021 |
| HP            | 2000                        | [4e83c9da3f](https://bsd-hardware.info/?probe=4e83c9da3f) | Sep 02, 2021 |
| HP            | 2000                        | [7a48e639e6](https://bsd-hardware.info/?probe=7a48e639e6) | Sep 02, 2021 |
| Sony          | VGN-P698E                   | [c8274e858d](https://bsd-hardware.info/?probe=c8274e858d) | Aug 30, 2021 |
| Lenovo        | FLEX 3-1120 80LX            | [2f1a1a42b8](https://bsd-hardware.info/?probe=2f1a1a42b8) | Aug 29, 2021 |
| Lenovo        | ThinkPad P73 20QRS00200     | [dfc86a0368](https://bsd-hardware.info/?probe=dfc86a0368) | Aug 29, 2021 |
| HP            | ZBook 15 G3                 | [01521236eb](https://bsd-hardware.info/?probe=01521236eb) | Aug 27, 2021 |
| Apple         | MacBookPro8,3               | [455af20b0d](https://bsd-hardware.info/?probe=455af20b0d) | Aug 26, 2021 |
| HP            | ZBook 15 G3                 | [d05a95551d](https://bsd-hardware.info/?probe=d05a95551d) | Aug 24, 2021 |
| HP            | ZBook 15 G3                 | [c37c317da3](https://bsd-hardware.info/?probe=c37c317da3) | Aug 24, 2021 |
| Deciso        | Netboard A20                | [971ff9ea80](https://bsd-hardware.info/?probe=971ff9ea80) | Aug 22, 2021 |
| HP            | Pavilion dv6                | [8054d6310f](https://bsd-hardware.info/?probe=8054d6310f) | Aug 19, 2021 |
| IBM           | ThinkPad T42 2374K46        | [d93b6d68fa](https://bsd-hardware.info/?probe=d93b6d68fa) | Aug 18, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | [6f7976c329](https://bsd-hardware.info/?probe=6f7976c329) | Aug 16, 2021 |
| ASUSTek       | X55CR                       | [c7c812c2c9](https://bsd-hardware.info/?probe=c7c812c2c9) | Aug 15, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [b5018b8651](https://bsd-hardware.info/?probe=b5018b8651) | Aug 14, 2021 |
| Unknown       | Unknown                     | [3cf2ad31a8](https://bsd-hardware.info/?probe=3cf2ad31a8) | Aug 14, 2021 |
| HP            | Pavilion g6                 | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| Dell          | Latitude E7240              | [762d8366d0](https://bsd-hardware.info/?probe=762d8366d0) | Aug 12, 2021 |
| Dell          | G3 3579                     | [91c803fdf2](https://bsd-hardware.info/?probe=91c803fdf2) | Aug 09, 2021 |
| HP            | 2000                        | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | Legion Y7000P 81LD          | [7364ae3b3d](https://bsd-hardware.info/?probe=7364ae3b3d) | Aug 04, 2021 |
| Apple         | MacBookPro8,1               | [1d941ee61d](https://bsd-hardware.info/?probe=1d941ee61d) | Jul 31, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Unknown       | Unknown                     | [6f9c88c35e](https://bsd-hardware.info/?probe=6f9c88c35e) | Jul 24, 2021 |
| Dell          | G5 5505                     | [9933a09c4f](https://bsd-hardware.info/?probe=9933a09c4f) | Jul 24, 2021 |
| GPU Compan... | GWTN156-5                   | [bc44d767cc](https://bsd-hardware.info/?probe=bc44d767cc) | Jul 22, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [e16321d2fb](https://bsd-hardware.info/?probe=e16321d2fb) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [122a5774ab](https://bsd-hardware.info/?probe=122a5774ab) | Jul 21, 2021 |
| IBM           | ThinkPad T43 26686CU        | [fdb4ebcf10](https://bsd-hardware.info/?probe=fdb4ebcf10) | Jul 21, 2021 |
| Apple         | MacBookPro8,1               | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| HP            | Stream 11 Pro G4 EE         | [bd2bf6b0a0](https://bsd-hardware.info/?probe=bd2bf6b0a0) | Jul 20, 2021 |
| Dell          | Inspiron 3521               | [1fed4e841b](https://bsd-hardware.info/?probe=1fed4e841b) | Jul 19, 2021 |
| Dell          | Inspiron 5559               | [e38b3f1f93](https://bsd-hardware.info/?probe=e38b3f1f93) | Jul 19, 2021 |
| Framework     | Laptop                      | [8a7b477512](https://bsd-hardware.info/?probe=8a7b477512) | Jul 15, 2021 |
| Apple         | MacBookPro9,2               | [6cca4dee6f](https://bsd-hardware.info/?probe=6cca4dee6f) | Jul 15, 2021 |
| Framework     | Laptop                      | [647138144b](https://bsd-hardware.info/?probe=647138144b) | Jul 14, 2021 |
| Apple         | MacBook5,1                  | [1e54d2fbdf](https://bsd-hardware.info/?probe=1e54d2fbdf) | Jul 05, 2021 |
| Apple         | MacBook5,1                  | [f5d7a16498](https://bsd-hardware.info/?probe=f5d7a16498) | Jul 05, 2021 |
| Unknown       | Unknown                     | [fb7b81afdd](https://bsd-hardware.info/?probe=fb7b81afdd) | Jul 04, 2021 |
| HP            | Pavilion dm1                | [a863347147](https://bsd-hardware.info/?probe=a863347147) | Jul 03, 2021 |
| HP            | ProBook 4440s               | [4aac49bc1e](https://bsd-hardware.info/?probe=4aac49bc1e) | Jul 01, 2021 |
| Dell          | Inspiron 15-5568            | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| HP            | Pavilion 17                 | [9929e0c39b](https://bsd-hardware.info/?probe=9929e0c39b) | Jun 30, 2021 |
| Unknown       | Unknown                     | [53465d6022](https://bsd-hardware.info/?probe=53465d6022) | Jun 28, 2021 |
| Toshiba       | Satellite C655D             | [10bdf263b3](https://bsd-hardware.info/?probe=10bdf263b3) | Jun 27, 2021 |
| Unknown       | Unknown                     | [dcfbb8a46e](https://bsd-hardware.info/?probe=dcfbb8a46e) | Jun 26, 2021 |
| Dell          | Latitude E6420              | [2e8b431cc6](https://bsd-hardware.info/?probe=2e8b431cc6) | Jun 25, 2021 |
| Lenovo        | ThinkPad W520 42763KU       | [591cbc0879](https://bsd-hardware.info/?probe=591cbc0879) | Jun 24, 2021 |
| Dell          | Inspiron 5567               | [0b90603ace](https://bsd-hardware.info/?probe=0b90603ace) | Jun 23, 2021 |
| Dell          | Precision 7710              | [33653d0c28](https://bsd-hardware.info/?probe=33653d0c28) | Jun 22, 2021 |
| Lenovo        | ThinkPad X230 2325WWB       | [786669cc9c](https://bsd-hardware.info/?probe=786669cc9c) | Jun 21, 2021 |
| Dell          | Studio 1558                 | [c2ba752ab5](https://bsd-hardware.info/?probe=c2ba752ab5) | Jun 20, 2021 |
| Unknown       | Unknown                     | [f37bf77853](https://bsd-hardware.info/?probe=f37bf77853) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| IBM           | ThinkPad T42 2374K46        | [acf931a3e0](https://bsd-hardware.info/?probe=acf931a3e0) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7138c789e3](https://bsd-hardware.info/?probe=7138c789e3) | Jun 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0fe1337b93](https://bsd-hardware.info/?probe=0fe1337b93) | Jun 19, 2021 |
| Dell          | Latitude E5420              | [1ed3ff35f6](https://bsd-hardware.info/?probe=1ed3ff35f6) | Jun 19, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [7d36d27958](https://bsd-hardware.info/?probe=7d36d27958) | Jun 19, 2021 |
| Lenovo        | ThinkPad Edge E530 62724... | [78abd376db](https://bsd-hardware.info/?probe=78abd376db) | Jun 18, 2021 |
| Lenovo        | ThinkPad T420 4236FJ1       | [808f58228e](https://bsd-hardware.info/?probe=808f58228e) | Jun 17, 2021 |
| Dell          | G5 5505                     | [97319295ee](https://bsd-hardware.info/?probe=97319295ee) | Jun 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [1138d47591](https://bsd-hardware.info/?probe=1138d47591) | Jun 10, 2021 |
| Dell          | Latitude D530               | [ef0dac3de0](https://bsd-hardware.info/?probe=ef0dac3de0) | Jun 09, 2021 |
| Acer          | Aspire E5-573G              | [52de90ff3d](https://bsd-hardware.info/?probe=52de90ff3d) | Jun 02, 2021 |
| Apple         | MacBookPro9,1               | [afc70d9c77](https://bsd-hardware.info/?probe=afc70d9c77) | Jun 01, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [6311d603ff](https://bsd-hardware.info/?probe=6311d603ff) | May 31, 2021 |
| System76      | Gazelle                     | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [107ac19795](https://bsd-hardware.info/?probe=107ac19795) | May 28, 2021 |
| Acer          | Nitro AN515-54              | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| ASUSTek       | 1015PX                      | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Unknown       | Unknown                     | [b296fb35e2](https://bsd-hardware.info/?probe=b296fb35e2) | May 19, 2021 |
| Unknown       | Unknown                     | [750e01de05](https://bsd-hardware.info/?probe=750e01de05) | May 19, 2021 |
| ASUSTek       | G750JM                      | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Apple         | MacBookPro6,2               | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| Dell          | G5 5505                     | [ba74d8eee0](https://bsd-hardware.info/?probe=ba74d8eee0) | May 08, 2021 |
| Dell          | G5 5505                     | [23ae99e489](https://bsd-hardware.info/?probe=23ae99e489) | May 08, 2021 |
| Dell          | Latitude E5570              | [c8477da717](https://bsd-hardware.info/?probe=c8477da717) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| HP            | Laptop 17-by0xxx            | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Toshiba       | Satellite C655D             | [6398601e16](https://bsd-hardware.info/?probe=6398601e16) | Apr 29, 2021 |
| Dell          | Inspiron N4010              | [c1a55b1147](https://bsd-hardware.info/?probe=c1a55b1147) | Apr 29, 2021 |
| HP            | Laptop 17-by0xxx            | [14cf64712f](https://bsd-hardware.info/?probe=14cf64712f) | Apr 29, 2021 |
| Lenovo        | ThinkPad T430 2344C4U       | [0f001f65d2](https://bsd-hardware.info/?probe=0f001f65d2) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | ProBook 4530s               | [4fb8582dc1](https://bsd-hardware.info/?probe=4fb8582dc1) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| Dell          | Precision 5520              | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Alienware     | M15x                        | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Dell          | Latitude 5580               | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| Deciso        | Netboard A20                | [29856c2092](https://bsd-hardware.info/?probe=29856c2092) | Apr 19, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [4faceaf6e5](https://bsd-hardware.info/?probe=4faceaf6e5) | Apr 17, 2021 |
| Dell          | XPS 13 9360                 | [f8bfc70f13](https://bsd-hardware.info/?probe=f8bfc70f13) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 7417TPU       | [981517a51a](https://bsd-hardware.info/?probe=981517a51a) | Apr 13, 2021 |
| Dell          | Latitude D610               | [d2cbb1f229](https://bsd-hardware.info/?probe=d2cbb1f229) | Apr 12, 2021 |
| Dell          | Inspiron 3521               | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |
| Deciso        | Netboard A20                | [209a39e5ae](https://bsd-hardware.info/?probe=209a39e5ae) | Apr 11, 2021 |
| Deciso        | Netboard A20                | [7b0aee5afd](https://bsd-hardware.info/?probe=7b0aee5afd) | Apr 10, 2021 |
| Deciso        | Netboard A20                | [9bfa19b9dc](https://bsd-hardware.info/?probe=9bfa19b9dc) | Apr 10, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [812939c17f](https://bsd-hardware.info/?probe=812939c17f) | Apr 05, 2021 |
| Lenovo        | ThinkPad A485 20MUS07E00    | [22b35a127a](https://bsd-hardware.info/?probe=22b35a127a) | Apr 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U3C... | [2de4bc8337](https://bsd-hardware.info/?probe=2de4bc8337) | Apr 04, 2021 |
| Dell          | Latitude E5420              | [be14a1d28e](https://bsd-hardware.info/?probe=be14a1d28e) | Apr 04, 2021 |
| Deciso        | Netboard A20                | [a3057b99f1](https://bsd-hardware.info/?probe=a3057b99f1) | Apr 02, 2021 |
| Sony          | VGN-FW290J                  | [4a6ca78bc0](https://bsd-hardware.info/?probe=4a6ca78bc0) | Apr 01, 2021 |
| HP            | ProBook 640 G1              | [6bc6c5b2bf](https://bsd-hardware.info/?probe=6bc6c5b2bf) | Mar 31, 2021 |
| Deciso        | Netboard A20                | [a096d54ca7](https://bsd-hardware.info/?probe=a096d54ca7) | Mar 27, 2021 |
| Dell          | Precision M4600             | [04fb75b4ea](https://bsd-hardware.info/?probe=04fb75b4ea) | Mar 26, 2021 |
| Lenovo        | ThinkPad Edge 05796AU       | [4a094815c0](https://bsd-hardware.info/?probe=4a094815c0) | Mar 24, 2021 |
| Lenovo        | ThinkPad R61 77331CU        | [d223a9b1fb](https://bsd-hardware.info/?probe=d223a9b1fb) | Mar 23, 2021 |
| ASUSTek       | 900A                        | [e920222f0e](https://bsd-hardware.info/?probe=e920222f0e) | Mar 23, 2021 |
| ASUSTek       | 900A                        | [a76303a060](https://bsd-hardware.info/?probe=a76303a060) | Mar 21, 2021 |
| Apple         | MacBookPro6,2               | [d0b3b5da10](https://bsd-hardware.info/?probe=d0b3b5da10) | Mar 21, 2021 |
| Dell          | Latitude 5580               | [175191ccff](https://bsd-hardware.info/?probe=175191ccff) | Mar 18, 2021 |
| Dell          | Latitude 5580               | [f6225cf8d8](https://bsd-hardware.info/?probe=f6225cf8d8) | Mar 18, 2021 |
| DFI           | BE17X(170/171/173)          | [9e0509bd54](https://bsd-hardware.info/?probe=9e0509bd54) | Mar 18, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [bec05a34de](https://bsd-hardware.info/?probe=bec05a34de) | Mar 18, 2021 |
| Gateway       | Solo 450                    | [41e40c653e](https://bsd-hardware.info/?probe=41e40c653e) | Mar 16, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [cf75f7c9cb](https://bsd-hardware.info/?probe=cf75f7c9cb) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | [b90180457c](https://bsd-hardware.info/?probe=b90180457c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T530 2392ASU       | [39f3a4f234](https://bsd-hardware.info/?probe=39f3a4f234) | Mar 09, 2021 |
| Gateway       | Solo 450                    | [5dcb6e0ef6](https://bsd-hardware.info/?probe=5dcb6e0ef6) | Mar 09, 2021 |
| HP            | ProBook 450 G2              | [9f4a3cd83d](https://bsd-hardware.info/?probe=9f4a3cd83d) | Mar 08, 2021 |
| Lenovo        | ThinkPad T60 20076PU        | [5375f351a5](https://bsd-hardware.info/?probe=5375f351a5) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| ASUSTek       | X55CR                       | [e887ee2ff5](https://bsd-hardware.info/?probe=e887ee2ff5) | Mar 03, 2021 |
| ASUSTek       | X55CR                       | [e1e4548d22](https://bsd-hardware.info/?probe=e1e4548d22) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6a4b5b90b7](https://bsd-hardware.info/?probe=6a4b5b90b7) | Mar 02, 2021 |
| Lenovo        | ThinkPad T490 20N3X50500    | [5f4ec887b6](https://bsd-hardware.info/?probe=5f4ec887b6) | Mar 02, 2021 |
| Acer          | Spin SP111-32N              | [9f44af71aa](https://bsd-hardware.info/?probe=9f44af71aa) | Feb 28, 2021 |
| Dell          | Inspiron 1000               | [70604dcbfa](https://bsd-hardware.info/?probe=70604dcbfa) | Feb 28, 2021 |
| Dell          | Latitude 5580               | [ab4ea78367](https://bsd-hardware.info/?probe=ab4ea78367) | Feb 28, 2021 |
| ASUSTek       | X555LAB                     | [b0364fffaf](https://bsd-hardware.info/?probe=b0364fffaf) | Feb 25, 2021 |
| ASUSTek       | X555LAB                     | [45d57c2be0](https://bsd-hardware.info/?probe=45d57c2be0) | Feb 24, 2021 |
| Dell          | XPS 13 9333                 | [7c78b3d42a](https://bsd-hardware.info/?probe=7c78b3d42a) | Feb 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7f35ef7fa9](https://bsd-hardware.info/?probe=7f35ef7fa9) | Feb 23, 2021 |
| Dell          | Inspiron 910                | [047950e61b](https://bsd-hardware.info/?probe=047950e61b) | Feb 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 4... | [f8f9140d92](https://bsd-hardware.info/?probe=f8f9140d92) | Feb 21, 2021 |
| Acer          | AOA150                      | [91e5ec60b9](https://bsd-hardware.info/?probe=91e5ec60b9) | Feb 21, 2021 |
| IBM           | ThinkPad T42 2374K46        | [311f93ab37](https://bsd-hardware.info/?probe=311f93ab37) | Feb 20, 2021 |
| Dell          | Latitude E7450              | [0a8e2a2e29](https://bsd-hardware.info/?probe=0a8e2a2e29) | Feb 19, 2021 |
| ASUSTek       | G73Jh                       | [ba7fb8e83c](https://bsd-hardware.info/?probe=ba7fb8e83c) | Feb 19, 2021 |
| HP            | ProBook 440 G2              | [63038d613f](https://bsd-hardware.info/?probe=63038d613f) | Feb 19, 2021 |
| Dell          | Inspiron 3521               | [10490aef33](https://bsd-hardware.info/?probe=10490aef33) | Feb 17, 2021 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [12c985b708](https://bsd-hardware.info/?probe=12c985b708) | Feb 17, 2021 |
| ASUSTek       | G73Jh                       | [e730b4215a](https://bsd-hardware.info/?probe=e730b4215a) | Feb 17, 2021 |
| ASUSTek       | G73Jh                       | [35164ad41b](https://bsd-hardware.info/?probe=35164ad41b) | Feb 17, 2021 |
| Acer          | Spin SP111-32N              | [dd7644026b](https://bsd-hardware.info/?probe=dd7644026b) | Feb 16, 2021 |
| Lenovo        | ThinkPad T430 23427YU       | [79d1896352](https://bsd-hardware.info/?probe=79d1896352) | Feb 16, 2021 |
| MOTILE        | M142                        | [5ec101bb3e](https://bsd-hardware.info/?probe=5ec101bb3e) | Feb 15, 2021 |
| Apple         | MacBookPro6,2               | [4d83633f97](https://bsd-hardware.info/?probe=4d83633f97) | Feb 15, 2021 |
| Dell          | G7 7500                     | [a1c2eaee5f](https://bsd-hardware.info/?probe=a1c2eaee5f) | Feb 14, 2021 |
| Dell          | Inspiron 1000               | [104175ae13](https://bsd-hardware.info/?probe=104175ae13) | Feb 13, 2021 |
| Dell          | Inspiron 3521               | [3a73ecd855](https://bsd-hardware.info/?probe=3a73ecd855) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c2c9931f74](https://bsd-hardware.info/?probe=c2c9931f74) | Feb 12, 2021 |
| Lenovo        | ThinkPad T61 6459CTO        | [c9e6341e78](https://bsd-hardware.info/?probe=c9e6341e78) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | [afd71fdf87](https://bsd-hardware.info/?probe=afd71fdf87) | Feb 12, 2021 |
| DFI           | BE17X(170/171/173)          | [63442140dd](https://bsd-hardware.info/?probe=63442140dd) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | [43196baf75](https://bsd-hardware.info/?probe=43196baf75) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | [b3569ebb39](https://bsd-hardware.info/?probe=b3569ebb39) | Feb 11, 2021 |
| Lenovo        | ThinkPad L512 25975XU       | [b4d22f4179](https://bsd-hardware.info/?probe=b4d22f4179) | Feb 10, 2021 |
| Lenovo        | 20QD0000US                  | [8d1c80c2cb](https://bsd-hardware.info/?probe=8d1c80c2cb) | Feb 09, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [55debb2f24](https://bsd-hardware.info/?probe=55debb2f24) | Feb 08, 2021 |
| Lenovo        | 20QD0000US                  | [77e80759a0](https://bsd-hardware.info/?probe=77e80759a0) | Feb 08, 2021 |
| System76      | Galago Pro                  | [8f39c38e2e](https://bsd-hardware.info/?probe=8f39c38e2e) | Feb 08, 2021 |
| Chuwi         | CoreBox X                   | [2e51dfe463](https://bsd-hardware.info/?probe=2e51dfe463) | Feb 07, 2021 |
| Chuwi         | CoreBox X                   | [be6f23d3ed](https://bsd-hardware.info/?probe=be6f23d3ed) | Feb 07, 2021 |
| Apple         | MacBookPro8,2               | [ad4260feeb](https://bsd-hardware.info/?probe=ad4260feeb) | Feb 02, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [c69095f46d](https://bsd-hardware.info/?probe=c69095f46d) | Feb 02, 2021 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | [faa7becf82](https://bsd-hardware.info/?probe=faa7becf82) | Feb 01, 2021 |
| Apple         | MacBookPro6,2               | [6174748602](https://bsd-hardware.info/?probe=6174748602) | Feb 01, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [dbc05e2913](https://bsd-hardware.info/?probe=dbc05e2913) | Jan 30, 2021 |
| Dell          | Latitude E5570              | [bcf60e66d7](https://bsd-hardware.info/?probe=bcf60e66d7) | Jan 26, 2021 |
| Acer          | Aspire 5515                 | [d9ef473a7a](https://bsd-hardware.info/?probe=d9ef473a7a) | Jan 25, 2021 |
| System76      | Bonobo Extreme              | [8e91df5bb8](https://bsd-hardware.info/?probe=8e91df5bb8) | Jan 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3444A... | [b659b95d1a](https://bsd-hardware.info/?probe=b659b95d1a) | Jan 18, 2021 |
| Dell          | Vostro 1510                 | [ef1c0e0f2e](https://bsd-hardware.info/?probe=ef1c0e0f2e) | Jan 17, 2021 |
| HP            | OMEN by HP Laptop           | [14857eb6b7](https://bsd-hardware.info/?probe=14857eb6b7) | Jan 15, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [f32bbdaff3](https://bsd-hardware.info/?probe=f32bbdaff3) | Jan 13, 2021 |
| Sony          | VGN-FW290J                  | [6683d77c92](https://bsd-hardware.info/?probe=6683d77c92) | Jan 11, 2021 |
| Dell          | Latitude 7480               | [9c8bd9c479](https://bsd-hardware.info/?probe=9c8bd9c479) | Jan 04, 2021 |
| Dell          | Latitude 7480               | [78d3823932](https://bsd-hardware.info/?probe=78d3823932) | Jan 04, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [c5e7d3037f](https://bsd-hardware.info/?probe=c5e7d3037f) | Jan 03, 2021 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [bb0846a279](https://bsd-hardware.info/?probe=bb0846a279) | Dec 30, 2020 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [59a72ffcad](https://bsd-hardware.info/?probe=59a72ffcad) | Dec 29, 2020 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [41c388c760](https://bsd-hardware.info/?probe=41c388c760) | Dec 29, 2020 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [6491c362f0](https://bsd-hardware.info/?probe=6491c362f0) | Dec 29, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b6ae43880d](https://bsd-hardware.info/?probe=b6ae43880d) | Dec 22, 2020 |
| HP            | 2000                        | [f83c769501](https://bsd-hardware.info/?probe=f83c769501) | Dec 18, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [d019e14245](https://bsd-hardware.info/?probe=d019e14245) | Dec 18, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [c4d6dd6438](https://bsd-hardware.info/?probe=c4d6dd6438) | Dec 16, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [7b7c8bf457](https://bsd-hardware.info/?probe=7b7c8bf457) | Dec 16, 2020 |
| Toshiba       | Satellite C655D             | [23ca402ed6](https://bsd-hardware.info/?probe=23ca402ed6) | Dec 16, 2020 |
| Lenovo        | IdeaPad Slim 7 14IIL05 8... | [3278083ba9](https://bsd-hardware.info/?probe=3278083ba9) | Dec 16, 2020 |
| Dell          | XPS 15 9570                 | [91c4a075a1](https://bsd-hardware.info/?probe=91c4a075a1) | Dec 16, 2020 |
| Lenovo        | ThinkPad T450 20BV0064US    | [b397848c7e](https://bsd-hardware.info/?probe=b397848c7e) | Dec 16, 2020 |
| Lenovo        | G50-80 80E5                 | [61c248a1e6](https://bsd-hardware.info/?probe=61c248a1e6) | Dec 16, 2020 |
| Toshiba       | Satellite C855              | [6bc78fc7fc](https://bsd-hardware.info/?probe=6bc78fc7fc) | Dec 16, 2020 |
| Lenovo        | ThinkPad T420s 417153U      | [7af178dcda](https://bsd-hardware.info/?probe=7af178dcda) | Dec 15, 2020 |
| Eluktronic... | THINN-15                    | [b898297110](https://bsd-hardware.info/?probe=b898297110) | Dec 10, 2020 |
| Eluktronic... | THINN-15                    | [6e254f47fd](https://bsd-hardware.info/?probe=6e254f47fd) | Dec 10, 2020 |
| Eluktronic... | THINN-15                    | [78bab7cda9](https://bsd-hardware.info/?probe=78bab7cda9) | Dec 10, 2020 |
| Acer          | Peppy                       | [d15caaca04](https://bsd-hardware.info/?probe=d15caaca04) | Dec 08, 2020 |
| Dell          | Latitude 3300               | [108a030875](https://bsd-hardware.info/?probe=108a030875) | Dec 07, 2020 |
| Apple         | MacBookPro11,3              | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| Lenovo        | ThinkPad T410 2537NB5       | [d6a3aa6f8d](https://bsd-hardware.info/?probe=d6a3aa6f8d) | Dec 06, 2020 |
| Lenovo        | ThinkPad R400 7439X13       | [0d85bf3f3a](https://bsd-hardware.info/?probe=0d85bf3f3a) | Dec 03, 2020 |
| MSI           | X460/X460DX                 | [099fbcbec8](https://bsd-hardware.info/?probe=099fbcbec8) | Dec 01, 2020 |
| HP            | ProBook 640 G1              | [8f36943974](https://bsd-hardware.info/?probe=8f36943974) | Nov 29, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [ab385a348d](https://bsd-hardware.info/?probe=ab385a348d) | Nov 18, 2020 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [624be8f7d6](https://bsd-hardware.info/?probe=624be8f7d6) | Nov 16, 2020 |
| HP            | ProBook 640 G1              | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [bfd9130d4b](https://bsd-hardware.info/?probe=bfd9130d4b) | Nov 10, 2020 |
| HP            | ProBook 650 G2              | [b6c63ea3f8](https://bsd-hardware.info/?probe=b6c63ea3f8) | Nov 09, 2020 |
| HP            | ProBook 650 G2              | [0d5f2584b7](https://bsd-hardware.info/?probe=0d5f2584b7) | Nov 09, 2020 |
| System76      | Serval WS                   | [0ac6aed43b](https://bsd-hardware.info/?probe=0ac6aed43b) | Nov 09, 2020 |
| System76      | Bonobo Extreme              | [de33b2c793](https://bsd-hardware.info/?probe=de33b2c793) | Nov 09, 2020 |
| System76      | Serval WS                   | [b23f15f795](https://bsd-hardware.info/?probe=b23f15f795) | Nov 09, 2020 |
| Apple         | MacBookPro6,2               | [81e299fd14](https://bsd-hardware.info/?probe=81e299fd14) | Nov 03, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [ded161fe2e](https://bsd-hardware.info/?probe=ded161fe2e) | Oct 31, 2020 |
| Lenovo        | ThinkPad W530 2436CTO       | [e108d4a375](https://bsd-hardware.info/?probe=e108d4a375) | Oct 31, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [d5b0402c0e](https://bsd-hardware.info/?probe=d5b0402c0e) | Oct 29, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [393a8ce89a](https://bsd-hardware.info/?probe=393a8ce89a) | Oct 28, 2020 |
| Lenovo        | ThinkPad T490 20N3X50500    | [0a6ee35d3a](https://bsd-hardware.info/?probe=0a6ee35d3a) | Oct 28, 2020 |
| Lenovo        | ThinkPad T450 20BV0005US    | [603e66300a](https://bsd-hardware.info/?probe=603e66300a) | Oct 27, 2020 |
| Toshiba       | Satellite C655D             | [4492d307fc](https://bsd-hardware.info/?probe=4492d307fc) | Oct 25, 2020 |
| Lenovo        | Unknown                     | [7bab490506](https://bsd-hardware.info/?probe=7bab490506) | Oct 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [03602ed2c0](https://bsd-hardware.info/?probe=03602ed2c0) | Oct 23, 2020 |
| Lenovo        | Unknown                     | [c659708e94](https://bsd-hardware.info/?probe=c659708e94) | Oct 23, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [82398321f6](https://bsd-hardware.info/?probe=82398321f6) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325R74       | [1cc3cc20e8](https://bsd-hardware.info/?probe=1cc3cc20e8) | Oct 21, 2020 |
| Dell          | Latitude E7240              | [0e736e5e31](https://bsd-hardware.info/?probe=0e736e5e31) | Oct 20, 2020 |
| ASUSTek       | G551JW                      | [594e6f28fb](https://bsd-hardware.info/?probe=594e6f28fb) | Oct 19, 2020 |
| Acer          | Aspire one                  | [8514ff3ee8](https://bsd-hardware.info/?probe=8514ff3ee8) | Oct 14, 2020 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [ec1fa2e60c](https://bsd-hardware.info/?probe=ec1fa2e60c) | Oct 13, 2020 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [655613c78b](https://bsd-hardware.info/?probe=655613c78b) | Oct 04, 2020 |
| Dell          | Latitude E7240              | [fe74f6600f](https://bsd-hardware.info/?probe=fe74f6600f) | Oct 03, 2020 |
| Dell          | Precision 7530              | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Dell          | Precision 5510              | [a167382d6e](https://bsd-hardware.info/?probe=a167382d6e) | Sep 26, 2020 |
| Dell          | Precision 5510              | [621d3ea7a0](https://bsd-hardware.info/?probe=621d3ea7a0) | Sep 26, 2020 |
| Dell          | Precision 5510              | [80d5930e7d](https://bsd-hardware.info/?probe=80d5930e7d) | Sep 26, 2020 |
| Dell          | Precision 5510              | [e6fb884d8f](https://bsd-hardware.info/?probe=e6fb884d8f) | Sep 26, 2020 |
| Dell          | Precision 5510              | [837ffdd649](https://bsd-hardware.info/?probe=837ffdd649) | Sep 26, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [4d2c24a0e3](https://bsd-hardware.info/?probe=4d2c24a0e3) | Sep 15, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [fbf90aaf0d](https://bsd-hardware.info/?probe=fbf90aaf0d) | Sep 11, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [e06815d9dc](https://bsd-hardware.info/?probe=e06815d9dc) | Sep 11, 2020 |
| Toshiba       | Satellite C75D-B            | [9fb68e38d8](https://bsd-hardware.info/?probe=9fb68e38d8) | Sep 10, 2020 |
| Dell          | Precision M4800             | [ce29daf5ad](https://bsd-hardware.info/?probe=ce29daf5ad) | Sep 05, 2020 |
| Dell          | Precision M4800             | [1565096482](https://bsd-hardware.info/?probe=1565096482) | Sep 04, 2020 |
| Dell          | Precision M4800             | [ec0e767276](https://bsd-hardware.info/?probe=ec0e767276) | Sep 04, 2020 |
| Lenovo        | ThinkPad T420 4180MNU       | [4ea892826e](https://bsd-hardware.info/?probe=4ea892826e) | Sep 02, 2020 |
| Lenovo        | ThinkPad T495 20NJ0002US    | [0f7fdfb5f8](https://bsd-hardware.info/?probe=0f7fdfb5f8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [309d82d225](https://bsd-hardware.info/?probe=309d82d225) | Aug 29, 2020 |
| IBM           | ThinkPad T42 2374K46        | [bdd45acd8d](https://bsd-hardware.info/?probe=bdd45acd8d) | Aug 29, 2020 |
| Lenovo        | ThinkPad T60 20076PU        | [522182f3c4](https://bsd-hardware.info/?probe=522182f3c4) | Aug 29, 2020 |
| ASUSTek       | K53SD                       | [975e9ccbe2](https://bsd-hardware.info/?probe=975e9ccbe2) | Aug 27, 2020 |
| Lenovo        | ThinkPad T530 239242U       | [7c8087322d](https://bsd-hardware.info/?probe=7c8087322d) | Aug 27, 2020 |
| Google        | Link                        | [ad371b5358](https://bsd-hardware.info/?probe=ad371b5358) | Aug 22, 2020 |
| Dell          | Latitude 2100               | [13dd55a097](https://bsd-hardware.info/?probe=13dd55a097) | Aug 20, 2020 |
| Razer         | Blade Stealth               | [a467ffacf3](https://bsd-hardware.info/?probe=a467ffacf3) | Aug 17, 2020 |
| Razer         | Blade Stealth               | [37b1b5d950](https://bsd-hardware.info/?probe=37b1b5d950) | Aug 17, 2020 |
| Unknown       | Unknown                     | [2dca4f98fc](https://bsd-hardware.info/?probe=2dca4f98fc) | Aug 17, 2020 |
| Apple         | MacBookAir4,1               | [b517071f26](https://bsd-hardware.info/?probe=b517071f26) | Aug 15, 2020 |
| Apple         | MacBookPro8,3               | [052524523b](https://bsd-hardware.info/?probe=052524523b) | Aug 15, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [90e154cf08](https://bsd-hardware.info/?probe=90e154cf08) | Aug 14, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [c98c08b739](https://bsd-hardware.info/?probe=c98c08b739) | Aug 14, 2020 |
| System76      | Kudu                        | [418b97d56f](https://bsd-hardware.info/?probe=418b97d56f) | Aug 14, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [ce9330472e](https://bsd-hardware.info/?probe=ce9330472e) | Aug 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [a215fde229](https://bsd-hardware.info/?probe=a215fde229) | Aug 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [ce38287004](https://bsd-hardware.info/?probe=ce38287004) | Aug 13, 2020 |
| HP            | ProBook 640 G1              | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Toshiba       | Satellite C655D             | [26c82135bc](https://bsd-hardware.info/?probe=26c82135bc) | Aug 09, 2020 |
| HP            | EliteBook 820 G1            | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Toshiba       | Satellite C655D             | [d88981f3c3](https://bsd-hardware.info/?probe=d88981f3c3) | Aug 05, 2020 |
| Toshiba       | Satellite C655D             | [0d7992edcb](https://bsd-hardware.info/?probe=0d7992edcb) | Aug 01, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| HP            | Laptop 15-bs0xx             | [4cfc4cff49](https://bsd-hardware.info/?probe=4cfc4cff49) | Jul 28, 2020 |
| Dell          | Inspiron 3521               | [300cbce244](https://bsd-hardware.info/?probe=300cbce244) | Jul 26, 2020 |
| Timi          | RedmiBook 14 II             | [a7bf2669ce](https://bsd-hardware.info/?probe=a7bf2669ce) | Jul 24, 2020 |
| Dell          | Precision M4800             | [bbd03815ce](https://bsd-hardware.info/?probe=bbd03815ce) | Jul 20, 2020 |
| Toshiba       | Satellite C655D             | [191b32d117](https://bsd-hardware.info/?probe=191b32d117) | Jul 17, 2020 |
| Toshiba       | Satellite C655D             | [1a5890839c](https://bsd-hardware.info/?probe=1a5890839c) | Jul 16, 2020 |
| Toshiba       | Satellite C655D             | [ea366ca7f6](https://bsd-hardware.info/?probe=ea366ca7f6) | Jul 16, 2020 |
| Toshiba       | Satellite C655D             | [9b2cb9f62c](https://bsd-hardware.info/?probe=9b2cb9f62c) | Jul 15, 2020 |
| Toshiba       | Satellite C655D             | [981c74a766](https://bsd-hardware.info/?probe=981c74a766) | Jul 15, 2020 |
| Dell          | Precision 7550              | [9983a81086](https://bsd-hardware.info/?probe=9983a81086) | Jul 10, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0VK0... | [b726c4536b](https://bsd-hardware.info/?probe=b726c4536b) | Jul 04, 2020 |
| Acer          | Peppy                       | [f5bf2c1fc7](https://bsd-hardware.info/?probe=f5bf2c1fc7) | Jun 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [2d0dc32ced](https://bsd-hardware.info/?probe=2d0dc32ced) | Jun 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfef5fdcbf](https://bsd-hardware.info/?probe=dfef5fdcbf) | Jun 10, 2020 |
| Dell          | Latitude E6410              | [996540c1dc](https://bsd-hardware.info/?probe=996540c1dc) | Jun 04, 2020 |
| Toshiba       | Satellite L775D             | [bb218a14a6](https://bsd-hardware.info/?probe=bb218a14a6) | Jun 03, 2020 |
| Toshiba       | Satellite L775D             | [f0ec90217a](https://bsd-hardware.info/?probe=f0ec90217a) | Jun 03, 2020 |
| Dell          | Latitude E6320              | [2ebfa76c28](https://bsd-hardware.info/?probe=2ebfa76c28) | Jun 01, 2020 |
| Lenovo        | ThinkPad X220 42872WU       | [a95465cdda](https://bsd-hardware.info/?probe=a95465cdda) | May 29, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [f4e8ffb5dc](https://bsd-hardware.info/?probe=f4e8ffb5dc) | May 27, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0H70... | [dfd9a97efc](https://bsd-hardware.info/?probe=dfd9a97efc) | May 27, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0H70... | [0c4faa7698](https://bsd-hardware.info/?probe=0c4faa7698) | May 27, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [59c5b6d6b9](https://bsd-hardware.info/?probe=59c5b6d6b9) | May 27, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [6ea713bf51](https://bsd-hardware.info/?probe=6ea713bf51) | May 25, 2020 |
| Lenovo        | ThinkPad X230 2324A57       | [7b67911c5a](https://bsd-hardware.info/?probe=7b67911c5a) | May 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b4ca8bbc46](https://bsd-hardware.info/?probe=b4ca8bbc46) | May 25, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [916596bfa8](https://bsd-hardware.info/?probe=916596bfa8) | May 25, 2020 |
| Lenovo        | ThinkPad T430s 23539LU      | [eab6164233](https://bsd-hardware.info/?probe=eab6164233) | May 23, 2020 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [9ff1537692](https://bsd-hardware.info/?probe=9ff1537692) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [8ed0fee673](https://bsd-hardware.info/?probe=8ed0fee673) | May 22, 2020 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [010db0aed4](https://bsd-hardware.info/?probe=010db0aed4) | May 22, 2020 |
| Lenovo        | ThinkPad T440p 20AWS07F0... | [9001a6ea5b](https://bsd-hardware.info/?probe=9001a6ea5b) | May 22, 2020 |
| Lenovo        | ThinkPad T440p 20AWS07F0... | [79ec87b2db](https://bsd-hardware.info/?probe=79ec87b2db) | May 22, 2020 |
| Dell          | Precision 7540              | [aa891d8f27](https://bsd-hardware.info/?probe=aa891d8f27) | May 22, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| FreeBSD 13.0                  | 28        | 7.16%   |
| helloSystem 0.7.0             | 25        | 6.39%   |
| helloSystem 0.5.0             | 20        | 5.12%   |
| OpenBSD 6.9                   | 14        | 3.58%   |
| OpenBSD 6.8                   | 14        | 3.58%   |
| helloSystem 0.4.0             | 14        | 3.58%   |
| GhostBSD 20.04.02             | 13        | 3.32%   |
| FreeBSD 12.1-p8               | 12        | 3.07%   |
| FreeBSD 13.0-p4               | 11        | 2.81%   |
| FreeBSD 12.2                  | 10        | 2.56%   |
| FreeBSD 14.0-CURRENT          | 9         | 2.3%    |
| FreeBSD 13.1                  | 9         | 2.3%    |
| OpenBSD 7.0                   | 8         | 2.05%   |
| GhostBSD 21.08.27             | 7         | 1.79%   |
| FreeBSD 12.2-p2               | 7         | 1.79%   |
| OpenBSD 6.7                   | 6         | 1.53%   |
| NomadBSD 5806f915             | 6         | 1.53%   |
| NomadBSD 1.3.2                | 6         | 1.53%   |
| helloSystem 0.6.0             | 6         | 1.53%   |
| FreeBSD 13.0-STABLE           | 6         | 1.53%   |
| FreeBSD 13.0-p2               | 6         | 1.53%   |
| FreeBSD 12.2-p3               | 6         | 1.53%   |
| FreeBSD 13.0-p11              | 5         | 1.28%   |
| FreeBSD 12.2-p4               | 5         | 1.28%   |
| FreeBSD 12.1-p10              | 5         | 1.28%   |
| FreeBSD 12.1                  | 5         | 1.28%   |
| OPNsense 21.7.7               | 4         | 1.02%   |
| OPNsense 21.1                 | 4         | 1.02%   |
| FreeBSD 13.0-p7               | 4         | 1.02%   |
| FreeBSD 13.0-p5               | 4         | 1.02%   |
| FreeBSD 13.0-p3               | 4         | 1.02%   |
| FreeBSD 13.0-CURRENT          | 4         | 1.02%   |
| FreeBSD 12.2-p6               | 4         | 1.02%   |
| OPNsense 22.1.7               | 3         | 0.77%   |
| OPNsense 22.1.5               | 3         | 0.77%   |
| OPNsense 22.1                 | 3         | 0.77%   |
| OPNsense 21.7.3               | 3         | 0.77%   |
| helloSystem 0.8.0             | 3         | 0.77%   |
| FreeBSD 13.1-RC6              | 3         | 0.77%   |
| FreeBSD 13.0-p6               | 3         | 0.77%   |
| FreeBSD 12.2-STABLE           | 3         | 0.77%   |
| FreeBSD 12.1-STABLE           | 3         | 0.77%   |
| FreeBSD 12.1-p5               | 3         | 0.77%   |
| OPNsense 22.1.4               | 2         | 0.51%   |
| OPNsense 22.1.1               | 2         | 0.51%   |
| OPNsense 21.1.4               | 2         | 0.51%   |
| OpenBSD 7.1                   | 2         | 0.51%   |
| HardenedBSD 13.0-STABLE-HBSD  | 2         | 0.51%   |
| HardenedBSD 13.0-CURRENT-HBSD | 2         | 0.51%   |
| FreeBSD 13.0-RC1              | 2         | 0.51%   |
| FreeBSD 13.0-BETA1            | 2         | 0.51%   |
| FreeBSD 12.2-p9               | 2         | 0.51%   |
| FreeBSD 12.2-p8               | 2         | 0.51%   |
| FreeBSD 12.2-p11              | 2         | 0.51%   |
| FreeBSD 12.1-p9               | 2         | 0.51%   |
| FreeBSD 12.1-p4               | 2         | 0.51%   |
| DragonFly 6.0                 | 2         | 0.51%   |
| OPNsense 22.4.1               | 1         | 0.26%   |
| OPNsense 21.7.5               | 1         | 0.26%   |
| OPNsense 21.7.4               | 1         | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 161       | 47.21%  |
| helloSystem | 65        | 19.06%  |
| OpenBSD     | 43        | 12.61%  |
| OPNsense    | 26        | 7.62%   |
| GhostBSD    | 22        | 6.45%   |
| NomadBSD    | 13        | 3.81%   |
| HardenedBSD | 4         | 1.17%   |
| DragonFly   | 3         | 0.88%   |
| MidnightBSD | 2         | 0.59%   |
| NetBSD      | 1         | 0.29%   |
| FuryBSD     | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 315       | 94.31%  |
| i386  | 18        | 5.39%   |
| arm64 | 1         | 0.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 63        | 17.95%  |
| XFCE          | 44        | 12.54%  |
| Console       | 43        | 12.25%  |
| fvwm          | 38        | 10.83%  |
| MATE          | 31        | 8.83%   |
| KDE5          | 31        | 8.83%   |
| TWM           | 26        | 7.41%   |
| Openbox       | 19        | 5.41%   |
| GNOME         | 17        | 4.84%   |
| i3            | 13        | 3.7%    |
| Cinnamon      | 6         | 1.71%   |
| Enlightenment | 4         | 1.14%   |
| Fluxbox       | 3         | 0.85%   |
| AwesomeWM     | 3         | 0.85%   |
| GNUstep       | 2         | 0.57%   |
| Xfwm4         | 1         | 0.28%   |
| spectrwm      | 1         | 0.28%   |
| LXQt          | 1         | 0.28%   |
| LXDE          | 1         | 0.28%   |
| Lumina        | 1         | 0.28%   |
| DWM           | 1         | 0.28%   |
| Compton       | 1         | 0.28%   |
| CDE           | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 283       | 83.98%  |
| Console | 51        | 15.13%  |
| Wayland | 3         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 137       | 39.26%  |
| SLiM    | 115       | 32.95%  |
| SDDM    | 34        | 9.74%   |
| LightDM | 34        | 9.74%   |
| GDM     | 14        | 4.01%   |
| XDM     | 13        | 3.72%   |
| Ly      | 2         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 131       | 37.64%  |
| en_US           | 124       | 35.63%  |
| C               | 87        | 25%     |
| en_US.US-ASCII  | 2         | 0.57%   |
| es_CO           | 1         | 0.29%   |
| en_US.ISO8859-1 | 1         | 0.29%   |
| en_GB           | 1         | 0.29%   |
| de_DE           | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 240       | 70.8%   |
| BIOS | 99        | 29.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 183       | 53.2%   |
| Ufs     | 100       | 29.07%  |
| Ffs     | 43        | 12.5%   |
| Cd9660  | 15        | 4.36%   |
| Hammer2 | 3         | 0.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 283       | 83.24%  |
| MBR     | 50        | 14.71%  |
| Unknown | 5         | 1.47%   |
| BSD     | 2         | 0.59%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 113       | 34.04%  |
| Dell                | 68        | 20.48%  |
| Hewlett-Packard     | 41        | 12.35%  |
| Apple               | 18        | 5.42%   |
| ASUSTek Computer    | 16        | 4.82%   |
| Deciso              | 11        | 3.31%   |
| Acer                | 11        | 3.31%   |
| System76            | 9         | 2.71%   |
| Toshiba             | 7         | 2.11%   |
| Framework           | 7         | 2.11%   |
| MSI                 | 4         | 1.2%    |
| Unknown             | 3         | 0.9%    |
| Timi                | 2         | 0.6%    |
| Sony                | 2         | 0.6%    |
| IBM                 | 2         | 0.6%    |
| Gateway             | 2         | 0.6%    |
| Datto               | 2         | 0.6%    |
| TUXEDO              | 1         | 0.3%    |
| Samsung Electronics | 1         | 0.3%    |
| Razer               | 1         | 0.3%    |
| Notebook            | 1         | 0.3%    |
| MOTILE              | 1         | 0.3%    |
| LG Electronics      | 1         | 0.3%    |
| GPU Company         | 1         | 0.3%    |
| GPD                 | 1         | 0.3%    |
| Google              | 1         | 0.3%    |
| Gigabyte Technology | 1         | 0.3%    |
| Eluktronics         | 1         | 0.3%    |
| DFI                 | 1         | 0.3%    |
| Chuwi               | 1         | 0.3%    |
| Alienware           | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Deciso Netboard A20                     | 9         | 2.71%   |
| Framework Laptop                        | 7         | 2.11%   |
| Dell Inspiron 3521                      | 5         | 1.51%   |
| Unknown                                 | 4         | 1.2%    |
| Lenovo ThinkPad X220 4286CTO            | 3         | 0.9%    |
| HP Pavilion dv6                         | 3         | 0.9%    |
| HP 2000                                 | 3         | 0.9%    |
| Dell Latitude E5420                     | 3         | 0.9%    |
| Apple MacBookPro6,2                     | 3         | 0.9%    |
| System76 Kudu                           | 2         | 0.6%    |
| System76 Galago Pro                     | 2         | 0.6%    |
| System76 Bonobo Extreme                 | 2         | 0.6%    |
| Lenovo ThinkPad X220 42872WU            | 2         | 0.6%    |
| Lenovo ThinkPad T60 20076PU             | 2         | 0.6%    |
| Lenovo ThinkPad T430s 2352CTO           | 2         | 0.6%    |
| Dell Precision M4800                    | 2         | 0.6%    |
| Dell Precision 7710                     | 2         | 0.6%    |
| Dell Latitude E7450                     | 2         | 0.6%    |
| Dell Latitude E7240                     | 2         | 0.6%    |
| Dell Latitude D630                      | 2         | 0.6%    |
| Dell Latitude 2100                      | 2         | 0.6%    |
| Datto 1000                              | 2         | 0.6%    |
| ASUS VivoBook_ASUSLaptop X712DAP_M712DA | 2         | 0.6%    |
| ASUS G551JW                             | 2         | 0.6%    |
| Apple MacBookPro9,2                     | 2         | 0.6%    |
| Apple MacBookPro8,3                     | 2         | 0.6%    |
| TUXEDO Pulse 15 Gen1                    | 1         | 0.3%    |
| Toshiba Satellite P755                  | 1         | 0.3%    |
| Toshiba Satellite P25                   | 1         | 0.3%    |
| Toshiba Satellite L775D                 | 1         | 0.3%    |
| Toshiba Satellite C855                  | 1         | 0.3%    |
| Toshiba Satellite C75D-B                | 1         | 0.3%    |
| Toshiba Satellite C655D                 | 1         | 0.3%    |
| Toshiba PORTEGE R700                    | 1         | 0.3%    |
| Timi TM1701                             | 1         | 0.3%    |
| Timi RedmiBook 14 II                    | 1         | 0.3%    |
| System76 Serval WS                      | 1         | 0.3%    |
| System76 Gazelle                        | 1         | 0.3%    |
| System76 Darter Pro                     | 1         | 0.3%    |
| Sony VGN-P698E                          | 1         | 0.3%    |
| Sony VGN-FW290J                         | 1         | 0.3%    |
| Samsung 950XCJ/951XCJ/950XCR            | 1         | 0.3%    |
| Razer Blade Stealth                     | 1         | 0.3%    |
| Notebook NS50_70MU                      | 1         | 0.3%    |
| MSI X460/X460DX                         | 1         | 0.3%    |
| MSI Summit E13FlipEvo A11MT             | 1         | 0.3%    |
| MSI GS65 Stealth Thin 8RF               | 1         | 0.3%    |
| MSI Bravo 15 A4DDR                      | 1         | 0.3%    |
| MOTILE M142                             | 1         | 0.3%    |
| LG 17Z990-R.AAC9U1                      | 1         | 0.3%    |
| Lenovo Yoga 6 13ARE05 82FN              | 1         | 0.3%    |
| Lenovo ThinkPad Yoga 11e 20DAS02S00     | 1         | 0.3%    |
| Lenovo ThinkPad X61 7675H7U             | 1         | 0.3%    |
| Lenovo ThinkPad X395 20NL000HGE         | 1         | 0.3%    |
| Lenovo ThinkPad X270 20HN001HUS         | 1         | 0.3%    |
| Lenovo ThinkPad X260 20F5S45W00         | 1         | 0.3%    |
| Lenovo ThinkPad X250 20CMCTO1WW         | 1         | 0.3%    |
| Lenovo ThinkPad X250 20CM0046US         | 1         | 0.3%    |
| Lenovo ThinkPad X250 20CLS1WP01         | 1         | 0.3%    |
| Lenovo ThinkPad X250 20CLS02V00         | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 97        | 29.22%  |
| Dell Latitude      | 27        | 8.13%   |
| Dell Inspiron      | 18        | 5.42%   |
| HP Pavilion        | 11        | 3.31%   |
| Dell Precision     | 10        | 3.01%   |
| Deciso Netboard    | 9         | 2.71%   |
| Lenovo IdeaPad     | 8         | 2.41%   |
| Framework Laptop   | 7         | 2.11%   |
| Toshiba Satellite  | 6         | 1.81%   |
| HP ProBook         | 6         | 1.81%   |
| HP Laptop          | 6         | 1.81%   |
| Dell XPS           | 6         | 1.81%   |
| Acer Aspire        | 5         | 1.51%   |
| HP EliteBook       | 4         | 1.2%    |
| Apple MacBookPro8  | 4         | 1.2%    |
| Unknown            | 4         | 1.2%    |
| HP 2000            | 3         | 0.9%    |
| ASUS VivoBook      | 3         | 0.9%    |
| Apple MacBookPro9  | 3         | 0.9%    |
| Apple MacBookPro6  | 3         | 0.9%    |
| System76 Kudu      | 2         | 0.6%    |
| System76 Galago    | 2         | 0.6%    |
| System76 Bonobo    | 2         | 0.6%    |
| Lenovo Flex        | 2         | 0.6%    |
| IBM ThinkPad       | 2         | 0.6%    |
| HP ZBook           | 2         | 0.6%    |
| HP Stream          | 2         | 0.6%    |
| HP OMEN            | 2         | 0.6%    |
| Dell Vostro        | 2         | 0.6%    |
| Dell G3            | 2         | 0.6%    |
| Datto 1000         | 2         | 0.6%    |
| ASUS G551JW        | 2         | 0.6%    |
| TUXEDO Pulse       | 1         | 0.3%    |
| Toshiba PORTEGE    | 1         | 0.3%    |
| Timi TM1701        | 1         | 0.3%    |
| Timi RedmiBook     | 1         | 0.3%    |
| System76 Serval    | 1         | 0.3%    |
| System76 Gazelle   | 1         | 0.3%    |
| System76 Darter    | 1         | 0.3%    |
| Sony VGN-P698E     | 1         | 0.3%    |
| Sony VGN-FW290J    | 1         | 0.3%    |
| Samsung 950XCJ     | 1         | 0.3%    |
| Razer Blade        | 1         | 0.3%    |
| Notebook NS50      | 1         | 0.3%    |
| MSI X460           | 1         | 0.3%    |
| MSI Summit         | 1         | 0.3%    |
| MSI GS65           | 1         | 0.3%    |
| MSI Bravo          | 1         | 0.3%    |
| MOTILE M142        | 1         | 0.3%    |
| LG 17Z990-R.AAC9U1 | 1         | 0.3%    |
| Lenovo Yoga        | 1         | 0.3%    |
| Lenovo Legion      | 1         | 0.3%    |
| Lenovo G51-35      | 1         | 0.3%    |
| Lenovo G50-80      | 1         | 0.3%    |
| Lenovo 20QD0000US  | 1         | 0.3%    |
| HP G42             | 1         | 0.3%    |
| HP ENVY            | 1         | 0.3%    |
| HP Compaq          | 1         | 0.3%    |
| HP 250             | 1         | 0.3%    |
| HP 15              | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 47        | 14.16%  |
| 2021    | 35        | 10.54%  |
| 2019    | 32        | 9.64%   |
| 2015    | 32        | 9.64%   |
| 2011    | 31        | 9.34%   |
| 2018    | 25        | 7.53%   |
| 2013    | 20        | 6.02%   |
| 2016    | 19        | 5.72%   |
| 2012    | 15        | 4.52%   |
| 2010    | 14        | 4.22%   |
| 2014    | 13        | 3.92%   |
| 2009    | 12        | 3.61%   |
| 2017    | 10        | 3.01%   |
| 2008    | 7         | 2.11%   |
| 2007    | 6         | 1.81%   |
| 2006    | 6         | 1.81%   |
| 2022    | 3         | 0.9%    |
| 2004    | 2         | 0.6%    |
| 2005    | 1         | 0.3%    |
| 2002    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 332       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 327       | 98.49%  |
| Yes  | 5         | 1.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 126       | 37.39%  |
| 16.01-24.0  | 82        | 24.33%  |
| 4.01-8.0    | 60        | 17.8%   |
| 32.01-64.0  | 23        | 6.82%   |
| 3.01-4.0    | 14        | 4.15%   |
| 2.01-3.0    | 14        | 4.15%   |
| 64.01-256.0 | 9         | 2.67%   |
| 24.01-32.0  | 3         | 0.89%   |
| 1.01-2.0    | 3         | 0.89%   |
| 0.51-1.0    | 2         | 0.59%   |
| 0.01-0.5    | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 167       | 49.26%  |
| 0.51-1.0    | 101       | 29.79%  |
| 1.01-2.0    | 33        | 9.73%   |
| 2.01-3.0    | 17        | 5.01%   |
| 8.01-16.0   | 7         | 2.06%   |
| 4.01-8.0    | 4         | 1.18%   |
| 0           | 4         | 1.18%   |
| 16.01-24.0  | 2         | 0.59%   |
| 3.01-4.0    | 1         | 0.29%   |
| 24.01-32.0  | 1         | 0.29%   |
| 64.01-256.0 | 1         | 0.29%   |
| Unknown     | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 272       | 79.53%  |
| 2      | 48        | 14.04%  |
| 0      | 11        | 3.22%   |
| 3      | 10        | 2.92%   |
| 4      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 65.18%  |
| Yes       | 117       | 34.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 290       | 87.35%  |
| No        | 42        | 12.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 93.69%  |
| No        | 21        | 6.31%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 62.2%   |
| No        | 127       | 37.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 332       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Brooklyn         | 21        | 5.97%   |
| Seattle          | 8         | 2.27%   |
| Portland         | 8         | 2.27%   |
| Los Angeles      | 7         | 1.99%   |
| New York         | 6         | 1.7%    |
| Chicago          | 6         | 1.7%    |
| Washington       | 5         | 1.42%   |
| Vienna           | 4         | 1.14%   |
| Harrisburg       | 4         | 1.14%   |
| Frisco           | 4         | 1.14%   |
| Whittier         | 3         | 0.85%   |
| Rochester        | 3         | 0.85%   |
| Phoenix          | 3         | 0.85%   |
| Omaha            | 3         | 0.85%   |
| Midvale          | 3         | 0.85%   |
| Eugene           | 3         | 0.85%   |
| Dublin           | 3         | 0.85%   |
| Dallas           | 3         | 0.85%   |
| Charlotte        | 3         | 0.85%   |
| Apex             | 3         | 0.85%   |
| Springfield      | 2         | 0.57%   |
| San Francisco    | 2         | 0.57%   |
| San Diego        | 2         | 0.57%   |
| San Antonio      | 2         | 0.57%   |
| Queens           | 2         | 0.57%   |
| Papillion        | 2         | 0.57%   |
| Palmer           | 2         | 0.57%   |
| Oklahoma City    | 2         | 0.57%   |
| New Braunfels    | 2         | 0.57%   |
| Las Vegas        | 2         | 0.57%   |
| Lake Forest      | 2         | 0.57%   |
| Lafayette        | 2         | 0.57%   |
| Hyattsville      | 2         | 0.57%   |
| Henderson        | 2         | 0.57%   |
| Hannibal         | 2         | 0.57%   |
| Gettysburg       | 2         | 0.57%   |
| Fresno           | 2         | 0.57%   |
| Frederick        | 2         | 0.57%   |
| Denver           | 2         | 0.57%   |
| Columbia         | 2         | 0.57%   |
| Clemmons         | 2         | 0.57%   |
| Chapel Hill      | 2         | 0.57%   |
| Belmar           | 2         | 0.57%   |
| Atlanta          | 2         | 0.57%   |
| Ypsilanti        | 1         | 0.28%   |
| Youngsville      | 1         | 0.28%   |
| Yaphank          | 1         | 0.28%   |
| Woodland         | 1         | 0.28%   |
| Windsor          | 1         | 0.28%   |
| Wheatland        | 1         | 0.28%   |
| West Valley City | 1         | 0.28%   |
| West Orange      | 1         | 0.28%   |
| Wenatchee        | 1         | 0.28%   |
| Wausau           | 1         | 0.28%   |
| Waukee           | 1         | 0.28%   |
| Warsaw           | 1         | 0.28%   |
| Warrensburg      | 1         | 0.28%   |
| Warner           | 1         | 0.28%   |
| Ventura          | 1         | 0.28%   |
| Vandalia         | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 68        | 81     | 17.75%  |
| WDC                 | 62        | 65     | 16.19%  |
| Crucial             | 27        | 36     | 7.05%   |
| Toshiba             | 23        | 31     | 6.01%   |
| Seagate             | 23        | 25     | 6.01%   |
| SanDisk             | 22        | 26     | 5.74%   |
| Transcend           | 17        | 29     | 4.44%   |
| NVMe                | 12        | 16     | 3.13%   |
| Kingston            | 12        | 13     | 3.13%   |
| Intel               | 12        | 14     | 3.13%   |
| Hitachi             | 10        | 12     | 2.61%   |
| SK hynix            | 8         | 8      | 2.09%   |
| Apple               | 8         | 8      | 2.09%   |
| PNY                 | 7         | 8      | 1.83%   |
| Phison              | 7         | 14     | 1.83%   |
| OWC                 | 7         | 8      | 1.83%   |
| HGST                | 7         | 8      | 1.83%   |
| SPCC                | 4         | 4      | 1.04%   |
| KingSpec            | 4         | 4      | 1.04%   |
| Corsair             | 4         | 4      | 1.04%   |
| Zheino              | 3         | 6      | 0.78%   |
| SSSTC               | 3         | 3      | 0.78%   |
| Mushkin             | 3         | 3      | 0.78%   |
| Micron Technology   | 3         | 3      | 0.78%   |
| A-DATA Technology   | 3         | 4      | 0.78%   |
| Netac               | 2         | 2      | 0.52%   |
| Lexar               | 2         | 5      | 0.52%   |
| Fujitsu             | 2         | 2      | 0.52%   |
| BIWIN               | 2         | 3      | 0.52%   |
| ZTC                 | 1         | 1      | 0.26%   |
| Team                | 1         | 2      | 0.26%   |
| T-FORCE             | 1         | 1      | 0.26%   |
| Silicon Motion      | 1         | 1      | 0.26%   |
| Plextor             | 1         | 1      | 0.26%   |
| Patriot             | 1         | 1      | 0.26%   |
| OPENBSD             | 1         | 1      | 0.26%   |
| LITEONIT            | 1         | 1      | 0.26%   |
| LITEON              | 1         | 1      | 0.26%   |
| Lenovo              | 1         | 1      | 0.26%   |
| KIOXIA              | 1         | 1      | 0.26%   |
| IBM/Hitachi         | 1         | 1      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| Generic             | 1         | 1      | 0.26%   |
| FLEXXON             | 1         | 2      | 0.26%   |
| China               | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB         | 9         | 2.3%    |
| Transcend TS256GMTS952T2 256GB       | 8         | 2.05%   |
| Crucial CT1000MX500SSD1 1TB          | 5         | 1.28%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 4         | 1.02%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.02%   |
| Seagate ST500LM021-1KJ152 500GB      | 4         | 1.02%   |
| SanDisk SSD PLUS 240GB               | 4         | 1.02%   |
| Samsung SSD 850 EVO 250GB            | 4         | 1.02%   |
| NVMe WDC PC SN730 SDB 256GB          | 4         | 1.02%   |
| Kingston SA400S37240G 240GB          | 4         | 1.02%   |
| WDC WDBNCE5000PNC 500GB              | 3         | 0.77%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 3         | 0.77%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.77%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 0.77%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.77%   |
| Samsung SSD 850 PRO 512GB            | 3         | 0.77%   |
| Samsung SSD 850 EVO 1TB              | 3         | 0.77%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 3         | 0.77%   |
| Phison PCIe SSD 512GB                | 3         | 0.77%   |
| Hitachi HTS547550A9E384 500GB        | 3         | 0.77%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 0.77%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.51%   |
| WDC WD1600BEVT-75ZCT2 160GB          | 2         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.51%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 2         | 0.51%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 0.51%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 2         | 0.51%   |
| Transcend TS128GMTS430S 128GB        | 2         | 0.51%   |
| Toshiba KXG50ZNV256G NVMe 256GB      | 2         | 0.51%   |
| SSSTC CVB-8D128-HP 128GB             | 2         | 0.51%   |
| SPCC Solid State Disk 128GB          | 2         | 0.51%   |
| SK hynix SC311 SATA 256GB            | 2         | 0.51%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.51%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.51%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.51%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.51%   |
| SanDisk pSSD 256GB                   | 2         | 0.51%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.51%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.51%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.51%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.51%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 2         | 0.51%   |
| Samsung MZNLN256HCHP-000L7 256GB     | 2         | 0.51%   |
| Samsung MZ7TY256HDHP-000L7 256GB     | 2         | 0.51%   |
| OWC Mercury Extreme Pro SSD 240GB    | 2         | 0.51%   |
| OWC Mercury EXTREME Pro 6G SSD       | 2         | 0.51%   |
| OWC Mercury Electra 6G SSD           | 2         | 0.51%   |
| NVMe Samsung SSD 970 250GB           | 2         | 0.51%   |
| Intel SSDSC2KW256G8 256GB            | 2         | 0.51%   |
| Intel SSDPEKKF256G8L 256GB           | 2         | 0.51%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.51%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.51%   |
| Crucial CT525MX300SSD1 528GB         | 2         | 0.51%   |
| BIWIN SSD 256GB                      | 2         | 0.51%   |
| ZTC MS001-128G                       | 1         | 0.26%   |
| Zheino CHN-mSATAQ3-120 120GB         | 1         | 0.26%   |
| Zheino CHN mSATAM1 256 256GB         | 1         | 0.26%   |
| Zheino CHN mSATA01M 060 64GB         | 1         | 0.26%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 38     | 32.46%  |
| Seagate             | 23        | 25     | 20.18%  |
| Toshiba             | 18        | 26     | 15.79%  |
| NVMe                | 10        | 12     | 8.77%   |
| Hitachi             | 10        | 12     | 8.77%   |
| HGST                | 7         | 8      | 6.14%   |
| Apple               | 3         | 3      | 2.63%   |
| Fujitsu             | 2         | 2      | 1.75%   |
| Samsung Electronics | 1         | 2      | 0.88%   |
| OPENBSD             | 1         | 1      | 0.88%   |
| IBM/Hitachi         | 1         | 1      | 0.88%   |
| Generic             | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 51     | 23.47%  |
| Crucial             | 24        | 31     | 12.24%  |
| SanDisk             | 22        | 26     | 11.22%  |
| Transcend           | 15        | 27     | 7.65%   |
| Kingston            | 10        | 10     | 5.1%    |
| WDC                 | 8         | 8      | 4.08%   |
| Intel               | 8         | 9      | 4.08%   |
| PNY                 | 7         | 8      | 3.57%   |
| OWC                 | 7         | 8      | 3.57%   |
| SK hynix            | 5         | 5      | 2.55%   |
| Apple               | 5         | 5      | 2.55%   |
| KingSpec            | 4         | 4      | 2.04%   |
| Corsair             | 4         | 4      | 2.04%   |
| Zheino              | 3         | 6      | 1.53%   |
| SPCC                | 3         | 3      | 1.53%   |
| NVMe                | 3         | 3      | 1.53%   |
| SSSTC               | 2         | 2      | 1.02%   |
| Phison              | 2         | 2      | 1.02%   |
| Netac               | 2         | 2      | 1.02%   |
| Mushkin             | 2         | 2      | 1.02%   |
| Lexar               | 2         | 5      | 1.02%   |
| BIWIN               | 2         | 3      | 1.02%   |
| A-DATA Technology   | 2         | 2      | 1.02%   |
| ZTC                 | 1         | 1      | 0.51%   |
| Team                | 1         | 2      | 0.51%   |
| Plextor             | 1         | 1      | 0.51%   |
| Patriot             | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| FLEXXON             | 1         | 2      | 0.51%   |
| China               | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 176       | 236    | 49.3%   |
| HDD  | 112       | 131    | 31.37%  |
| NVMe | 69        | 96     | 19.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 272       | 367    | 79.77%  |
| NVMe | 69        | 96     | 20.23%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 209       | 272    | 72.57%  |
| 0.51-1.0   | 72        | 86     | 25%     |
| 1.01-2.0   | 7         | 9      | 2.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 120       | 34.48%  |
| 251-500    | 93        | 26.72%  |
| 1-20       | 56        | 16.09%  |
| 501-1000   | 41        | 11.78%  |
| 51-100     | 20        | 5.75%   |
| 21-50      | 9         | 2.59%   |
| 1001-2000  | 7         | 2.01%   |
| Unknown    | 2         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 287       | 83.67%  |
| 21-50   | 31        | 9.04%   |
| 101-250 | 11        | 3.21%   |
| 51-100  | 11        | 3.21%   |
| Unknown | 2         | 0.58%   |
| 251-500 | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                              | Notebooks | Drives | Percent |
|----------------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB                    | 3         | 3      | 6.98%   |
| SSSTC CVB-8D128-HP 128GB                           | 2         | 2      | 4.65%   |
| WDC WD5000LPCX-75VHAT0 500GB                       | 1         | 1      | 2.33%   |
| WDC WD3200BPVT-75ZEST0 320GB                       | 1         | 1      | 2.33%   |
| WDC WD3200BPVT-75JJ5T0 320GB                       | 1         | 1      | 2.33%   |
| WDC WD3200BEKT-60V5T1 320GB                        | 1         | 1      | 2.33%   |
| WDC WD1600BEKT-66F3T2 160GB                        | 1         | 1      | 2.33%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1      | 2.33%   |
| Toshiba MK7559GSXF 752GB                           | 1         | 1      | 2.33%   |
| Toshiba MK5061GSYN 500GB                           | 1         | 1      | 2.33%   |
| Toshiba MK3265GSXN 320GB                           | 1         | 6      | 2.33%   |
| Toshiba MK1637GSX 160GB                            | 1         | 2      | 2.33%   |
| SK hynix SC210 mSATA 256GB                         | 1         | 1      | 2.33%   |
| Seagate ST96023AS 58GB                             | 1         | 1      | 2.33%   |
| Seagate ST95005620AS 500GB                         | 1         | 1      | 2.33%   |
| Seagate ST9320423AS 320GB                          | 1         | 1      | 2.33%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 1      | 2.33%   |
| Seagate ST320LT007-9ZV142 320GB                    | 1         | 1      | 2.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                 | 1         | 1      | 2.33%   |
| SanDisk SSD PLUS 240GB                             | 1         | 1      | 2.33%   |
| SanDisk SD5SG2128G1052E 128GB                      | 1         | 1      | 2.33%   |
| Samsung Electronics SSD UM410 Series 2.5-inch 16GB | 1         | 1      | 2.33%   |
| Samsung Electronics HM121HI 120GB                  | 1         | 2      | 2.33%   |
| Kingston SV300S37A120G 120GB                       | 1         | 1      | 2.33%   |
| Kingston SNS4151S332G 32GB                         | 1         | 1      | 2.33%   |
| Kingston SMSM151S3128GD 128GB                      | 1         | 1      | 2.33%   |
| Kingston SA400S37240G 240GB                        | 1         | 1      | 2.33%   |
| KingSpec KSD-PA25.6-032MS 32GB                     | 1         | 1      | 2.33%   |
| Intel SSDSC2KW256G8 256GB                          | 1         | 1      | 2.33%   |
| IBM/Hitachi IC25N080ATMR04-0 80GB                  | 1         | 1      | 2.33%   |
| Hitachi HTS722010K9SA00 100GB                      | 1         | 1      | 2.33%   |
| Hitachi HTS547550A9E384 500GB                      | 1         | 1      | 2.33%   |
| Hitachi HTS545025B9SA02 250GB                      | 1         | 2      | 2.33%   |
| Hitachi HTS543225A7A384 250GB                      | 1         | 1      | 2.33%   |
| HGST HTS725025A7E630 250GB                         | 1         | 1      | 2.33%   |
| HGST HTS721010A9E630 1TB                           | 1         | 1      | 2.33%   |
| HGST HTS545050A7E680 500GB                         | 1         | 1      | 2.33%   |
| Apple HDD HTS545050A7E362 500GB                    | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 20.93%  |
| Toshiba             | 7         | 13     | 16.28%  |
| WDC                 | 5         | 5      | 11.63%  |
| Kingston            | 4         | 4      | 9.3%    |
| Hitachi             | 4         | 5      | 9.3%    |
| HGST                | 3         | 3      | 6.98%   |
| SSSTC               | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 2      | 4.65%   |
| Samsung Electronics | 2         | 3      | 4.65%   |
| SK hynix            | 1         | 1      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| IBM/Hitachi         | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 29.03%  |
| Toshiba             | 7         | 13     | 22.58%  |
| WDC                 | 5         | 5      | 16.13%  |
| Hitachi             | 4         | 5      | 12.9%   |
| HGST                | 3         | 3      | 9.68%   |
| Samsung Electronics | 1         | 2      | 3.23%   |
| IBM/Hitachi         | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 39     | 72.09%  |
| SSD  | 12        | 12     | 27.91%  |

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
| Works    | 280       | 393    | 83.09%  |
| Malfunc  | 43        | 51     | 12.76%  |
| Detected | 14        | 19     | 4.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 233       | 62.8%   |
| AMD                              | 48        | 12.94%  |
| Samsung Electronics              | 28        | 7.55%   |
| SanDisk                          | 21        | 5.66%   |
| Phison Electronics               | 6         | 1.62%   |
| Toshiba                          | 5         | 1.35%   |
| SK hynix                         | 5         | 1.35%   |
| Micron Technology                | 4         | 1.08%   |
| Silicon Motion                   | 2         | 0.54%   |
| Nvidia                           | 2         | 0.54%   |
| Lenovo                           | 2         | 0.54%   |
| KIOXIA                           | 2         | 0.54%   |
| Kingston Technology Company      | 2         | 0.54%   |
| JMicron Technology               | 2         | 0.54%   |
| Unknown                          | 2         | 0.54%   |
| Union Memory (Shenzhen)          | 1         | 0.27%   |
| Solid State Storage Technology   | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| Realtek Semiconductor            | 1         | 0.27%   |
| Micron/Crucial Technology        | 1         | 0.27%   |
| Lite-On Technology               | 1         | 0.27%   |
| ADATA Technology                 | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 40        | 9.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 36        | 8.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 7.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 5.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 4.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 3.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 13        | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 2.99%   |
| Unknown                                                                          | 12        | 2.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 2.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 2.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 2.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.24%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 2%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.25%   |
| Phison E12 NVMe Controller                                                       | 4         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1%      |
| Toshiba unknown                                                                  | 3         | 0.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.75%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.75%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.75%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.75%   |
| AMD FCH IDE Controller                                                           | 3         | 0.75%   |
| SK hynix hynix unknown                                                           | 2         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.5%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.5%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.5%    |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.5%    |
| Lenovo unknown                                                                   | 2         | 0.5%    |
| KIOXIA unknown                                                                   | 2         | 0.5%    |
| JMicron JMB360 AHCI Controller                                                   | 2         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 0.5%    |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 0.5%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 0.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.5%    |
| Union Memory (Shenzhen) Memory unknown                                           | 1         | 0.25%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.25%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.25%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.25%   |
| SK hynix BC511                                                                   | 1         | 0.25%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] 5518 UDMA IDE Controller                        | 1         | 0.25%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.25%   |
| SanDisk unknown                                                                  | 1         | 0.25%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.25%   |
| Samsung SM951 AHCI                                                               | 1         | 0.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 250       | 65.27%  |
| NVMe | 80        | 20.89%  |
| IDE  | 41        | 10.7%   |
| RAID | 12        | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 272       | 81.68%  |
| AMD    | 60        | 18.02%  |
| ARM    | 1         | 0.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz        | 13        | 3.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 7         | 2.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 1.78%   |
| Intel Core 2 Duo                         | 6         | 1.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 5         | 1.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 5         | 1.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 5         | 1.48%   |
| Intel Core i3-3227U CPU @ 1.90GHz        | 5         | 1.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 5         | 1.48%   |
| AMD EPYC 3201 8-Core Processor           | 5         | 1.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 4         | 1.18%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 4         | 1.18%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz     | 4         | 1.18%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 4         | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 4         | 1.18%   |
| AMD EPYC 3101 4-Core Processor           | 4         | 1.18%   |
| Intel CPU Version                        | 3         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 3         | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 3         | 0.89%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 3         | 0.89%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 3         | 0.89%   |
| Intel Core i7-2760QM CPU @ 2.40GHz       | 3         | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 0.89%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz       | 3         | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 3         | 0.89%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 3         | 0.89%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 2         | 0.59%   |
| Intel Pentium M processor                | 2         | 0.59%   |
| Intel Pentium 4                          | 2         | 0.59%   |
| Intel Genuine CPU                        | 2         | 0.59%   |
| Intel Core i9-8950HK CPU @ 2.90GHz       | 2         | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 0.59%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 2         | 0.59%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz       | 2         | 0.59%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 2         | 0.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 2         | 0.59%   |
| Intel Core i7-3720QM CPU @ 2.60GHz       | 2         | 0.59%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 2         | 0.59%   |
| Intel Core i7-2620M CPU @ 2.70GHz        | 2         | 0.59%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 0.59%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 2         | 0.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 0.59%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz       | 2         | 0.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 0.59%   |
| Intel Core i5-4310U CPU @ 2.00GHz        | 2         | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 2         | 0.59%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 2         | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GH         | 2         | 0.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 2         | 0.59%   |
| Intel Core i5-10300H CPU @ 2.50GHz       | 2         | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 0.59%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 2         | 0.59%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 0.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 2         | 0.59%   |
| Intel Core i3-8145U CPU @ 2.10GHz        | 2         | 0.59%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz     | 2         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 98        | 29.17%  |
| Intel Core i7          | 82        | 24.4%   |
| Other                  | 20        | 5.95%   |
| Intel Core 2 Duo       | 20        | 5.95%   |
| Intel Core i3          | 18        | 5.36%   |
| Intel Celeron          | 9         | 2.68%   |
| AMD Ryzen 7            | 9         | 2.68%   |
| AMD EPYC               | 9         | 2.68%   |
| AMD Ryzen 5            | 6         | 1.79%   |
| Intel Core 2           | 5         | 1.49%   |
| Intel Atom             | 5         | 1.49%   |
| AMD Ryzen 5 PRO        | 4         | 1.19%   |
| Intel Pentium M        | 3         | 0.89%   |
| Intel Pentium          | 3         | 0.89%   |
| Intel Core i9          | 3         | 0.89%   |
| AMD Ryzen 7 PRO        | 3         | 0.89%   |
| AMD Ryzen 3            | 3         | 0.89%   |
| AMD A10                | 3         | 0.89%   |
| Intel Xeon             | 2         | 0.6%    |
| Intel Pentium Silver   | 2         | 0.6%    |
| Intel Pentium 4        | 2         | 0.6%    |
| Intel Genuine          | 2         | 0.6%    |
| AMD Ryzen Embedded     | 2         | 0.6%    |
| AMD GX                 | 2         | 0.6%    |
| AMD E                  | 2         | 0.6%    |
| AMD C-50               | 2         | 0.6%    |
| AMD A8                 | 2         | 0.6%    |
| AMD A6                 | 2         | 0.6%    |
| Intel Pentium Dual     | 1         | 0.3%    |
| Intel Mobile Pentium 4 | 1         | 0.3%    |
| Intel Mobile Celeron   | 1         | 0.3%    |
| Intel Core m3          | 1         | 0.3%    |
| Intel Core 2 Extreme   | 1         | 0.3%    |
| ARM Cortex             | 1         | 0.3%    |
| AMD Ryzen 9            | 1         | 0.3%    |
| AMD Phenom II          | 1         | 0.3%    |
| AMD E2                 | 1         | 0.3%    |
| AMD E1                 | 1         | 0.3%    |
| AMD C-60               | 1         | 0.3%    |
| AMD Athlon II Neo      | 1         | 0.3%    |
| AMD A12                | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 154       | 45.97%  |
| 4       | 103       | 30.75%  |
| Unknown | 27        | 8.06%   |
| 8       | 21        | 6.27%   |
| 6       | 9         | 2.69%   |
| 1       | 9         | 2.69%   |
| 16      | 8         | 2.39%   |
| 12      | 4         | 1.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 324       | 97.01%  |
| Unknown | 7         | 2.1%    |
| 2       | 3         | 0.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 217       | 64.78%  |
| 1       | 86        | 25.67%  |
| Unknown | 32        | 9.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 53        | 15.92%  |
| IvyBridge     | 36        | 10.81%  |
| SandyBridge   | 34        | 10.21%  |
| Haswell       | 27        | 8.11%   |
| Skylake       | 20        | 6.01%   |
| Westmere      | 17        | 5.11%   |
| Core          | 16        | 4.8%    |
| Broadwell     | 16        | 4.8%    |
| Zen           | 13        | 3.9%    |
| Zen 2         | 11        | 3.3%    |
| Zen+          | 10        | 3%      |
| Penryn        | 10        | 3%      |
| TigerLake     | 9         | 2.7%    |
| Bonnell       | 8         | 2.4%    |
| Bobcat        | 7         | 2.1%    |
| Silvermont    | 5         | 1.5%    |
| Goldmont plus | 4         | 1.2%    |
| Excavator     | 4         | 1.2%    |
| CometLake     | 4         | 1.2%    |
| Puma          | 3         | 0.9%    |
| P6            | 3         | 0.9%    |
| NetBurst      | 3         | 0.9%    |
| IceLake       | 3         | 0.9%    |
| Unknown       | 3         | 0.9%    |
| Nehalem       | 2         | 0.6%    |
| K10 Llano     | 2         | 0.6%    |
| K10           | 2         | 0.6%    |
| Jaguar        | 2         | 0.6%    |
| Goldmont      | 2         | 0.6%    |
| Zen 3         | 1         | 0.3%    |
| Steamroller   | 1         | 0.3%    |
| Piledriver    | 1         | 0.3%    |
| K8 Hammer     | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 242       | 65.41%  |
| AMD                              | 67        | 18.11%  |
| Nvidia                           | 60        | 16.22%  |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 34        | 8.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 8.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 3.87%   |
| Intel HD Graphics 5500                                                                   | 14        | 3.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 2.84%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.58%   |
| AMD Renoir                                                                               | 10        | 2.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 2.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.32%   |
| Intel HD Graphics 620                                                                    | 9         | 2.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 2.06%   |
| Intel HD Graphics 530                                                                    | 8         | 2.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.8%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 1.55%   |
| Intel HD Graphics 630                                                                    | 5         | 1.29%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.03%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 4         | 1.03%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.77%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 3         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.52%   |
| Nvidia TU117M                                                                            | 2         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.52%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.52%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.52%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.52%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.52%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.52%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.52%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.52%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.52%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 2         | 0.52%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.52%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                                         | 2         | 0.52%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.52%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 2         | 0.52%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.52%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 2         | 0.52%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter                | 1         | 0.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.26%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.26%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                                         | 1         | 0.26%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 0.26%   |
| Nvidia NV34M [GeForce FX Go5200 64M]                                                     | 1         | 0.26%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 176       | 52.85%  |
| 1 x AMD        | 50        | 15.02%  |
| Intel + Nvidia | 34        | 10.21%  |
| 2 x Intel      | 23        | 6.91%   |
| 1 x Nvidia     | 21        | 6.31%   |
| Other          | 11        | 3.3%    |
| Intel + AMD    | 9         | 2.7%    |
| AMD + Nvidia   | 5         | 1.5%    |
| 2 x AMD        | 3         | 0.9%    |
| 1 x SiS        | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 289       | 86.79%  |
| Proprietary | 23        | 6.91%   |
| Unknown     | 21        | 6.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 289       | 85.25%  |
| 0.01-0.5   | 20        | 5.9%    |
| 1.01-2.0   | 15        | 4.42%   |
| 0.51-1.0   | 6         | 1.77%   |
| 3.01-4.0   | 5         | 1.47%   |
| 5.01-6.0   | 2         | 0.59%   |
| 7.01-8.0   | 1         | 0.29%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 57        | 21.76%  |
| AU Optronics            | 44        | 16.79%  |
| BOE                     | 35        | 13.36%  |
| Samsung Electronics     | 25        | 9.54%   |
| Chimei Innolux          | 23        | 8.78%   |
| Lenovo                  | 18        | 6.87%   |
| Apple                   | 8         | 3.05%   |
| Sharp                   | 7         | 2.67%   |
| Chi Mei Optoelectronics | 7         | 2.67%   |
| Sceptre Tech            | 4         | 1.53%   |
| LGD                     | 3         | 1.15%   |
| Dell                    | 3         | 1.15%   |
| Ancor Communications    | 3         | 1.15%   |
| InfoVision              | 2         | 0.76%   |
| IBM                     | 2         | 0.76%   |
| Hewlett-Packard         | 2         | 0.76%   |
| HannStar                | 2         | 0.76%   |
| BenQ                    | 2         | 0.76%   |
| Acer                    | 2         | 0.76%   |
| Vizio                   | 1         | 0.38%   |
| Tech Concepts           | 1         | 0.38%   |
| PANDA                   | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| LG Philips              | 1         | 0.38%   |
| LG Electronics          | 1         | 0.38%   |
| Lenovo Group Limited    | 1         | 0.38%   |
| HJW                     | 1         | 0.38%   |
| Goldstar                | 1         | 0.38%   |
| CTO                     | 1         | 0.38%   |
| ASUSTek Computer        | 1         | 0.38%   |
| AOC                     | 1         | 0.38%   |
| AGO                     | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 6         | 2.28%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 6         | 2.28%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 5         | 1.9%    |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch           | 3         | 1.14%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 3         | 1.14%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 3         | 1.14%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 3         | 1.14%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 3         | 1.14%   |
| Lenovo LCD Monitor LEN4031 1280x800 290x180mm 13.4-inch                  | 3         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 3         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch     | 2         | 0.76%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch     | 2         | 0.76%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 2         | 0.76%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch              | 2         | 0.76%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 2         | 0.76%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 2         | 0.76%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 2         | 0.76%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                     | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 2         | 0.76%   |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                   | 2         | 0.76%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                   | 2         | 0.76%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 600x340mm 27.2-inch    | 2         | 0.76%   |
| Vizio E65-F1 VIZ1035 3840x2160 1430x800mm 64.5-inch                      | 1         | 0.38%   |
| Tech Concepts LCD Monitor 43S435                                         | 1         | 0.38%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 340x190mm 15.3-inch                  | 1         | 0.38%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                  | 1         | 0.38%   |
| Sharp LCD Monitor SHP148E 1920x1080 340x190mm 15.3-inch                  | 1         | 0.38%   |
| Sharp LCD Monitor SHP148D 3840x2160 340x190mm 15.3-inch                  | 1         | 0.38%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                  | 1         | 0.38%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch                  | 1         | 0.38%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                  | 1         | 0.38%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch           | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC354C 1366x768 350x200mm 15.9-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 340x190mm 15.3-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC8B4F 1920x1080 340x190mm 15.3-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC364D 1920x1080 310x170mm 13.9-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch   | 1         | 0.38%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 800x330mm 34.1-inch        | 1         | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 1         | 0.38%   |
| PANDA LCD Monitor NCP0040 1920x1080 340x190mm 15.3-inch                  | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 90        | 34.88%  |
| 1920x1080 (FHD)    | 78        | 30.23%  |
| 1600x900 (HD+)     | 20        | 7.75%   |
| 1280x800 (WXGA)    | 18        | 6.98%   |
| 2560x1440 (QHD)    | 10        | 3.88%   |
| 3840x2160 (4K)     | 7         | 2.71%   |
| 2256x1504          | 6         | 2.33%   |
| 2560x1080          | 4         | 1.55%   |
| 1440x900 (WXGA+)   | 4         | 1.55%   |
| 1024x600           | 4         | 1.55%   |
| 3440x1440          | 2         | 0.78%   |
| 2560x1600          | 2         | 0.78%   |
| 1680x1050 (WSXGA+) | 2         | 0.78%   |
| Unknown            | 2         | 0.78%   |
| 5760x2160          | 1         | 0.39%   |
| 4480x1080          | 1         | 0.39%   |
| 3840x1600          | 1         | 0.39%   |
| 3200x1800 (QHD+)   | 1         | 0.39%   |
| 2880x1620          | 1         | 0.39%   |
| 1920x1200 (WUXGA)  | 1         | 0.39%   |
| 1400x1050          | 1         | 0.39%   |
| 1280x1024 (SXGA)   | 1         | 0.39%   |
| 1024x768 (XGA)     | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 34.62%  |
| 13      | 77        | 29.62%  |
| 12      | 22        | 8.46%   |
| 17      | 14        | 5.38%   |
| 14      | 13        | 5%      |
| 11      | 9         | 3.46%   |
| 27      | 7         | 2.69%   |
| Unknown | 6         | 2.31%   |
| 24      | 4         | 1.54%   |
| 29      | 3         | 1.15%   |
| 64      | 2         | 0.77%   |
| 34      | 2         | 0.77%   |
| 23      | 2         | 0.77%   |
| 10      | 2         | 0.77%   |
| 37      | 1         | 0.38%   |
| 35      | 1         | 0.38%   |
| 31      | 1         | 0.38%   |
| 19      | 1         | 0.38%   |
| 16      | 1         | 0.38%   |
| 9       | 1         | 0.38%   |
| 8       | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 143       | 55.21%  |
| 201-300     | 70        | 27.03%  |
| 351-400     | 14        | 5.41%   |
| 501-600     | 12        | 4.63%   |
| Unknown     | 6         | 2.32%   |
| 601-700     | 5         | 1.93%   |
| 801-900     | 2         | 0.77%   |
| 701-800     | 2         | 0.77%   |
| 101-200     | 2         | 0.77%   |
| 1001-1500   | 2         | 0.77%   |
| 401-500     | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 195       | 79.27%  |
| 16/10   | 29        | 11.79%  |
| 21/9    | 7         | 2.85%   |
| 3/2     | 6         | 2.44%   |
| Unknown | 5         | 2.03%   |
| 4/3     | 3         | 1.22%   |
| 5/4     | 1         | 0.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 79        | 30.38%  |
| 91-100         | 72        | 27.69%  |
| 61-70          | 23        | 8.85%   |
| 101-110        | 20        | 7.69%   |
| 121-130        | 11        | 4.23%   |
| 301-350        | 10        | 3.85%   |
| 71-80          | 9         | 3.46%   |
| 51-60          | 8         | 3.08%   |
| 201-250        | 6         | 2.31%   |
| Unknown        | 6         | 2.31%   |
| 351-500        | 4         | 1.54%   |
| More than 1000 | 2         | 0.77%   |
| 41-50          | 2         | 0.77%   |
| 1-40           | 2         | 0.77%   |
| 131-140        | 2         | 0.77%   |
| 151-200        | 1         | 0.38%   |
| 141-150        | 1         | 0.38%   |
| 111-120        | 1         | 0.38%   |
| 501-1000       | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 110       | 42.47%  |
| 101-120       | 89        | 34.36%  |
| 51-100        | 25        | 9.65%   |
| 161-240       | 24        | 9.27%   |
| Unknown       | 6         | 2.32%   |
| More than 240 | 5         | 1.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 223       | 66.37%  |
| 0     | 86        | 25.6%   |
| 2     | 26        | 7.74%   |
| 3     | 1         | 0.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 235       | 46.63%  |
| Realtek Semiconductor            | 123       | 24.4%   |
| Qualcomm Atheros                 | 52        | 10.32%  |
| Broadcom                         | 44        | 8.73%   |
| AMD                              | 11        | 2.18%   |
| Edimax Technology                | 8         | 1.59%   |
| TP-Link                          | 4         | 0.79%   |
| Marvell Technology Group         | 4         | 0.79%   |
| Ralink                           | 3         | 0.6%    |
| NetGear                          | 3         | 0.6%    |
| Ralink Technology                | 2         | 0.4%    |
| Nvidia                           | 2         | 0.4%    |
| ASUSTek Computer                 | 2         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Samsung Electronics              | 1         | 0.2%    |
| Qualcomm                         | 1         | 0.2%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.2%    |
| Novatel Wireless                 | 1         | 0.2%    |
| MediaTek                         | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| Google                           | 1         | 0.2%    |
| dog hunter                       | 1         | 0.2%    |
| D-Link System                    | 1         | 0.2%    |
| D-Link                           | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 78        | 11.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 38        | 5.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 4.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 4.23%   |
| Intel Wireless 7260                                                     | 21        | 3.17%   |
| Intel Wireless 8265 / 8275                                              | 18        | 2.72%   |
| Intel Wireless 8260                                                     | 16        | 2.42%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.42%   |
| Intel Wireless 7265                                                     | 14        | 2.11%   |
| Intel I210 Gigabit Network Connection                                   | 12        | 1.81%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0               | 11        | 1.66%   |
| Intel Ethernet Connection I217-LM                                       | 10        | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.36%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.36%   |
| Intel Ethernet Connection (3) I218-LM                                   | 9         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.21%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 8         | 1.21%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 8         | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 1.06%   |
| Intel Wireless 3165                                                     | 7         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 7         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                   | 6         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.91%   |
| Intel 82566MM Gigabit Network Connection                                | 6         | 0.91%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 6         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 0.76%   |
| Intel Wireless 3160                                                     | 5         | 0.76%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 5         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 5         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                   | 4         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.6%    |
| Intel Centrino Advanced-N 6200                                          | 4         | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.45%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 3         | 0.45%   |
| Intel WiFi Link 5100                                                    | 3         | 0.45%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.45%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.45%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.45%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.45%   |
| Intel 82573L Gigabit Ethernet Controller                                | 3         | 0.45%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                       | 3         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 202       | 59.24%  |
| Qualcomm Atheros      | 44        | 12.9%   |
| Realtek Semiconductor | 36        | 10.56%  |
| Broadcom              | 35        | 10.26%  |
| Edimax Technology     | 8         | 2.35%   |
| TP-Link               | 4         | 1.17%   |
| Ralink                | 3         | 0.88%   |
| NetGear               | 3         | 0.88%   |
| Ralink Technology     | 2         | 0.59%   |
| ASUSTek Computer      | 2         | 0.59%   |
| D-Link System         | 1         | 0.29%   |
| D-Link                | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 28        | 8.16%   |
| Intel Wireless 7260                                                                   | 21        | 6.12%   |
| Intel Wireless 8265 / 8275                                                            | 18        | 5.25%   |
| Intel Wireless 8260                                                                   | 16        | 4.66%   |
| Intel Wi-Fi 6 AX200                                                                   | 16        | 4.66%   |
| Intel Wireless 7265                                                                   | 14        | 4.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 9         | 2.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 9         | 2.62%   |
| Intel Wireless-AC 9260                                                                | 9         | 2.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 8         | 2.33%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 8         | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 8         | 2.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 7         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 7         | 2.04%   |
| Intel Wireless 3165                                                                   | 7         | 2.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 6         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 6         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 6         | 1.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 6         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 6         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 5         | 1.46%   |
| Intel Wireless 3160                                                                   | 5         | 1.46%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 5         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 5         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 4         | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 4         | 1.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 4         | 1.17%   |
| Intel Centrino Advanced-N 6200                                                        | 4         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 4         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 3         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 3         | 0.87%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]                           | 3         | 0.87%   |
| Intel WiFi Link 5100                                                                  | 3         | 0.87%   |
| Intel Wi-Fi 6 AX201                                                                   | 3         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 3         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 3         | 0.87%   |
| Intel Centrino Wireless-N 2230                                                        | 3         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                                        | 3         | 0.87%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 3         | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 2         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                            | 2         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 2         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 2         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                                        | 2         | 0.58%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.58%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 2         | 0.58%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                                 | 2         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 2         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.58%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                         | 2         | 0.58%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 0.58%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 2         | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 1         | 0.29%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 1         | 0.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 133       | 43.18%  |
| Realtek Semiconductor            | 110       | 35.71%  |
| Broadcom                         | 27        | 8.77%   |
| Qualcomm Atheros                 | 14        | 4.55%   |
| AMD                              | 11        | 3.57%   |
| Marvell Technology Group         | 4         | 1.3%    |
| Nvidia                           | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Samsung Electronics              | 1         | 0.32%   |
| Qualcomm                         | 1         | 0.32%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.32%   |
| Novatel Wireless                 | 1         | 0.32%   |
| Lenovo                           | 1         | 0.32%   |
| Google                           | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 25.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 12.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 9.32%   |
| Intel I210 Gigabit Network Connection                             | 12        | 3.86%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 11        | 3.54%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 3.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 2.89%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 2.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 2.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 1.93%   |
| Intel 82566MM Gigabit Network Connection                          | 6         | 1.93%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 1.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.29%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 1.29%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.29%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.96%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 0.96%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.96%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 3         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.64%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.64%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 2         | 0.64%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.32%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.32%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1         | 0.32%   |
| OnePlus (Shenzhen) IN2025 RNDIS Control RNDIS Ethernet Data       | 1         | 0.32%   |
| Novatel Wireless MiFi 8800L RNDIS Control RNDIS Ethernet Data     | 1         | 0.32%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.32%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.32%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.32%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.32%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.32%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.32%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.32%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.32%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.32%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.32%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 0.32%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.32%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 312       | 51.15%  |
| Ethernet | 290       | 47.54%  |
| Modem    | 7         | 1.15%   |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 239       | 50%     |
| Ethernet | 239       | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 257       | 76.95%  |
| 1     | 51        | 15.27%  |
| 3     | 13        | 3.89%   |
| 6     | 9         | 2.69%   |
| 5     | 2         | 0.6%    |
| 0     | 2         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 308       | 90.86%  |
| Yes  | 31        | 9.14%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 56.13%  |
| Broadcom                        | 30        | 14.15%  |
| Apple                           | 18        | 8.49%   |
| Realtek Semiconductor           | 13        | 6.13%   |
| Qualcomm Atheros Communications | 11        | 5.19%   |
| IMC Networks                    | 6         | 2.83%   |
| Dell                            | 6         | 2.83%   |
| Foxconn / Hon Hai               | 3         | 1.42%   |
| Alps Electric                   | 2         | 0.94%   |
| Realtek                         | 1         | 0.47%   |
| Lite-On Technology              | 1         | 0.47%   |
| Hewlett-Packard                 | 1         | 0.47%   |
| ASUSTek Computer                | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 61        | 28.64%  |
| Intel AX200 Bluetooth                                       | 15        | 7.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 5.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 12        | 5.63%   |
| Apple Bluetooth Host Controller                             | 12        | 5.63%   |
| Intel AX201 Bluetooth                                       | 11        | 5.16%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 9         | 4.23%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 7         | 3.29%   |
| Realtek  Bluetooth 4.2 Adapter                              | 6         | 2.82%   |
| Intel AX210 Bluetooth                                       | 6         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 1.88%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 1.88%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 1.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 3         | 1.41%   |
| Dell DW375 Bluetooth Module                                 | 3         | 1.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 3         | 1.41%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 3         | 1.41%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.94%   |
| Realtek Bluetooth Radio                                     | 2         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 0.94%   |
| IMC Networks Bluetooth module                               | 2         | 0.94%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 0.94%   |
| Alps Electric BCM2046 Bluetooth Device                      | 2         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.47%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.47%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.47%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 0.47%   |
| Realtek Bluetooth Radio                                     | 1         | 0.47%   |
| Qualcomm Atheros  QCA61x4 Bluetooth 4.1                     | 1         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.47%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.47%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.47%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.47%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 1         | 0.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.47%   |
| IMC Networks Wireless_Device                                | 1         | 0.47%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.47%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.47%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.47%   |
| Dell Wireless 360 Bluetooth                                 | 1         | 0.47%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.47%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.47%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 0.47%   |
| ASUS ASUS USB-BT500                                         | 1         | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 266       | 69.82%  |
| AMD                              | 69        | 18.11%  |
| Nvidia                           | 31        | 8.14%   |
| Realtek Semiconductor            | 3         | 0.79%   |
| C-Media Electronics              | 3         | 0.79%   |
| Texas Instruments                | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Logitech                         | 1         | 0.26%   |
| Lenovo                           | 1         | 0.26%   |
| JMTek                            | 1         | 0.26%   |
| ESS Technology                   | 1         | 0.26%   |
| CMX Systems                      | 1         | 0.26%   |
| Cambridge Silicon Radio          | 1         | 0.26%   |
| Blue Microphones                 | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 8.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 6.9%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 6.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 27        | 5.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 4.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 3.45%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 2.59%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 2.37%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 9         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.08%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.86%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.65%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 2         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.43%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.43%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.43%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.43%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.43%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.43%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.43%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.43%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.43%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.43%   |
| Texas Instruments PCM2900C Audio CODEC                                                            | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.22%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.22%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.22%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.22%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.22%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 104       | 29.05%  |
| SK hynix            | 83        | 23.18%  |
| Micron Technology   | 35        | 9.78%   |
| Unknown             | 29        | 8.1%    |
| Crucial             | 28        | 7.82%   |
| Kingston            | 15        | 4.19%   |
| Transcend           | 12        | 3.35%   |
| Elpida              | 9         | 2.51%   |
| Nanya Technology    | 6         | 1.68%   |
| G.Skill             | 6         | 1.68%   |
| Ramaxel Technology  | 5         | 1.4%    |
| PNY                 | 5         | 1.4%    |
| Team                | 3         | 0.84%   |
| Goldkey             | 3         | 0.84%   |
| Avant               | 3         | 0.84%   |
| Unknown (ABCD)      | 1         | 0.28%   |
| Super Talent        | 1         | 0.28%   |
| Silicon Power       | 1         | 0.28%   |
| Sesame              | 1         | 0.28%   |
| PKI/Kingston        | 1         | 0.28%   |
| Patriot             | 1         | 0.28%   |
| Golden Empire       | 1         | 0.28%   |
| Gold Key            | 1         | 0.28%   |
| Corsair             | 1         | 0.28%   |
| Apacer              | 1         | 0.28%   |
| A-DATA Technology   | 1         | 0.28%   |
| 09490000802C        | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 29        | 7.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 2.34%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 8         | 2.08%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 2.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 1.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s            | 6         | 1.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.3%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 1.3%    |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s              | 4         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.04%   |
| Samsung RAM M471A4G43MB1-CTD 0kB SODIMM DDR4 2667MT/s            | 4         | 1.04%   |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s               | 3         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 3         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 3         | 0.78%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 0.78%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.78%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 3         | 0.78%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.78%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.78%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 0.52%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 0.52%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s             | 2         | 0.52%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 2         | 0.52%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 0.52%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s             | 2         | 0.52%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s           | 2         | 0.52%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M4 70T2864QZ3-CF7 1GB SODIMM DDR2 800MT/s            | 2         | 0.52%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.52%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Micron RAM 16ATF1G64HZ-2G1A2 8GB SODIMM DDR4 2133MT/s            | 2         | 0.52%   |
| G.Skill RAM F3-10666CL9-4GBSQ 4GB SODIMM DDR3 1334MT/s           | 2         | 0.52%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s            | 2         | 0.52%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.52%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s       | 2         | 0.52%   |
| Avant RAM Module 8GB SODIMM DDR3 1333MT/s                        | 2         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s | 1         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 153       | 51.52%  |
| DDR4    | 103       | 34.68%  |
| DDR2    | 21        | 7.07%   |
| LPDDR3  | 7         | 2.36%   |
| DDR     | 6         | 2.02%   |
| LPDDR4  | 3         | 1.01%   |
| Unknown | 2         | 0.67%   |
| SRAM    | 1         | 0.34%   |
| SDRAM   | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 281       | 93.67%  |
| Row Of Chips | 10        | 3.33%   |
| Chip         | 7         | 2.33%   |
| Unknown      | 2         | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 122       | 36.09%  |
| 4096  | 114       | 33.73%  |
| 2048  | 48        | 14.2%   |
| 16384 | 26        | 7.69%   |
| 1024  | 15        | 4.44%   |
| 32768 | 11        | 3.25%   |
| 512   | 1         | 0.3%    |
| 256   | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 91        | 27.41%  |
| 1333    | 44        | 13.25%  |
| 2667    | 42        | 12.65%  |
| 2400    | 29        | 8.73%   |
| 1334    | 25        | 7.53%   |
| 3200    | 21        | 6.33%   |
| 2133    | 21        | 6.33%   |
| 667     | 13        | 3.92%   |
| 1067    | 9         | 2.71%   |
| 1867    | 8         | 2.41%   |
| 800     | 7         | 2.11%   |
| Unknown | 7         | 2.11%   |
| 533     | 4         | 1.2%    |
| 4267    | 2         | 0.6%    |
| 1200    | 2         | 0.6%    |
| 975     | 2         | 0.6%    |
| 4800    | 1         | 0.3%    |
| 1866    | 1         | 0.3%    |
| 1066    | 1         | 0.3%    |
| 200     | 1         | 0.3%    |
| 166     | 1         | 0.3%    |

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
| Chicony Electronics                    | 65        | 29.68%  |
| Acer                                   | 24        | 10.96%  |
| Microdia                               | 20        | 9.13%   |
| IMC Networks                           | 17        | 7.76%   |
| Realtek Semiconductor                  | 16        | 7.31%   |
| Sunplus Innovation Technology          | 14        | 6.39%   |
| Apple                                  | 9         | 4.11%   |
| Suyin                                  | 8         | 3.65%   |
| Quanta                                 | 7         | 3.2%    |
| Lite-On Technology                     | 7         | 3.2%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.74%   |
| Luxvisions Innotech Limited            | 5         | 2.28%   |
| Syntek                                 | 3         | 1.37%   |
| Lenovo                                 | 3         | 1.37%   |
| Importek                               | 3         | 1.37%   |
| Ricoh                                  | 2         | 0.91%   |
| Primax Electronics                     | 2         | 0.91%   |
| Logitech                               | 2         | 0.91%   |
| Silicon Motion                         | 1         | 0.46%   |
| OmniVision Technologies                | 1         | 0.46%   |
| Intel                                  | 1         | 0.46%   |
| ALi                                    | 1         | 0.46%   |
| Alcor Micro                            | 1         | 0.46%   |
| Unknown                                | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 20        | 9.09%   |
| Acer Integrated Camera                              | 15        | 6.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 8         | 3.64%   |
| Microdia Integrated Webcam                          | 7         | 3.18%   |
| Apple FaceTime HD Camera                            | 7         | 3.18%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 2.73%   |
| Lite-On Integrated Camera                           | 5         | 2.27%   |
| IMC Networks Integrated Camera                      | 5         | 2.27%   |
| Chicony Integrated Camera [ThinkPad]                | 5         | 2.27%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 2.27%   |
| Realtek Realtek USB2.0 PC Camera                    | 4         | 1.82%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.82%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.82%   |
| Suyin Integrated_Webcam_HD                          | 3         | 1.36%   |
| Quanta HP Webcam                                    | 3         | 1.36%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.36%   |
| Lenovo Integrated Webcam [R5U877]                   | 3         | 1.36%   |
| IMC Networks UVC VGA Webcam                         | 3         | 1.36%   |
| Chicony HD Webcam                                   | 3         | 1.36%   |
| Chicony Chicony USB2.0 Camera                       | 3         | 1.36%   |
| Acer ThinkPad Integrated Camera                     | 3         | 1.36%   |
| Syntek Lenovo EasyCamera                            | 2         | 0.91%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 2         | 0.91%   |
| Sunplus HD WebCam                                   | 2         | 0.91%   |
| Sunplus Dell E5570 integrated webcam                | 2         | 0.91%   |
| Realtek Laptop Camera                               | 2         | 0.91%   |
| Realtek Integrated Webcam                           | 2         | 0.91%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.91%   |
| Microdia Integrated_Webcam_HD                       | 2         | 0.91%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.91%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 0.91%   |
| Chicony VGA WebCam                                  | 2         | 0.91%   |
| Chicony thinkpad t430s camera                       | 2         | 0.91%   |
| Chicony HP TrueVision HD Camera                     | 2         | 0.91%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 0.91%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.91%   |
| Acer Lenovo EasyCamera                              | 2         | 0.91%   |
| Syntek EasyCamera                                   | 1         | 0.45%   |
| Suyin Integrated Webcam                             | 1         | 0.45%   |
| Suyin HP Webcam-101                                 | 1         | 0.45%   |
| Suyin HD WebCam                                     | 1         | 0.45%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.45%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.45%   |
| Sunplus MTD camera                                  | 1         | 0.45%   |
| Sunplus Integrated Webcam                           | 1         | 0.45%   |
| Silicon Motion Chromebook HD WebCam                 | 1         | 0.45%   |
| Ricoh Sony Visual Communication Camera              | 1         | 0.45%   |
| Ricoh Integrated Camera                             | 1         | 0.45%   |
| Realtek USB Camera                                  | 1         | 0.45%   |
| Realtek USB 2 Webcam                                | 1         | 0.45%   |
| Realtek Integrated Webcam HD                        | 1         | 0.45%   |
| Realtek EasyCamera                                  | 1         | 0.45%   |
| Quanta HP Webcam-50                                 | 1         | 0.45%   |
| OmniVision OV2640 Webcam                            | 1         | 0.45%   |
| Microdia Webcam Vitade AF                           | 1         | 0.45%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.45%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 36.51%  |
| Upek                       | 10        | 15.87%  |
| Synaptics                  | 10        | 15.87%  |
| STMicroelectronics         | 9         | 14.29%  |
| Shenzhen Goodix Technology | 5         | 7.94%   |
| AuthenTec                  | 3         | 4.76%   |
| Samsung Electronics        | 1         | 1.59%   |
| Focal-systems.Corp         | 1         | 1.59%   |
| Broadcom                   | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 11        | 17.46%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 10        | 15.87%  |
| STMicroelectronics Fingerprint Reader                                        | 9         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 7.94%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 7.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 4         | 6.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 4.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 3.17%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 3.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.59%   |
| Validity Sensors VFS491                                                      | 1         | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.59%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.59%   |
| Synaptics product 0x00be                                                     | 1         | 1.59%   |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 1.59%   |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 1.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.59%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 1.59%   |
| AuthenTec AES2810                                                            | 1         | 1.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 1.59%   |

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
| 1     | 106       | 30.29%  |
| 2     | 104       | 29.71%  |
| 3     | 57        | 16.29%  |
| 0     | 50        | 14.29%  |
| 4     | 24        | 6.86%   |
| 5     | 6         | 1.71%   |
| 6     | 3         | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 224       | 40.95%  |
| Bluetooth                | 77        | 14.08%  |
| Net/wireless             | 67        | 12.25%  |
| Card reader              | 63        | 11.52%  |
| Fingerprint reader       | 52        | 9.51%   |
| Firewire controller      | 27        | 4.94%   |
| Sound                    | 9         | 1.65%   |
| Storage                  | 7         | 1.28%   |
| Graphics card            | 7         | 1.28%   |
| Modem                    | 6         | 1.1%    |
| Network                  | 3         | 0.55%   |
| Net/ethernet             | 2         | 0.37%   |
| Storage/ide              | 1         | 0.18%   |
| Storage/ata              | 1         | 0.18%   |
| Dvb card                 | 1         | 0.18%   |

