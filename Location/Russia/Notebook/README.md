BSD in Russia - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

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

Total: 190

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Lenovo        | V580 20147                  | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| Acer          | Aspire A114-33              | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Toshiba       | Satellite A300              | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| HP            | Laptop 15s-fq1xxx           | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| HP            | ProBook 455 G7              | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Lenovo        | B50-30 20382                | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| DEXP          | NAVIS P100                  | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Timi          | TM1612                      | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| ASUSTek       | M51Sr                       | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Acer          | Aspire A114-33              | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| HP            | ProBook 445 G7              | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| MSI           | GE75 Raider 10SFS           | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Lenovo        | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| ASUSTek       | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| IBM           | ThinkPad H 1846AQG          | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Acer          | Aspire A715-75G             | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| eMachines     | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines     | eM350                       | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Acer          | Aspire ES1-132              | [bf95bf607d](https://bsd-hardware.info/?probe=bf95bf607d) | Jun 06, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Acer          | Extensa 2540                | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Samsung       | N145P/N250P/N260P           | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Samsung       | N145P/N250P/N260P           | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| Dell          | Latitude 3410               | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| HP            | 255 G3                      | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| HP            | Compaq 6820s                | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Dell          | Studio 1537                 | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Apple         | MacBook5,1                  | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Apple         | MacBook5,1                  | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [5e4643fe26](https://bsd-hardware.info/?probe=5e4643fe26) | Feb 18, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| Acer          | Extensa 5635Z               | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Sony          | VPCM13M1R                   | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Acer          | Aspire V5-122               | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Panasonic     | CF-19AHNC8FN                | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| Sony          | SVP1321V9RB                 | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| Sony          | SVP1321V9RB                 | [d4250ef269](https://bsd-hardware.info/?probe=d4250ef269) | Dec 01, 2020 |
| Sony          | VGN-S150(UC)                | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Toshiba       | Satellite M100              | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| Sony          | SVP1321V9RB                 | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Dell          | Latitude C400               | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| Google        | Chell                       | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| ASUSTek       | X71SL                       | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| Dell          | Inspiron 1525               | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| Dell          | Latitude 7490               | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| HP            | ProBook 430 G2              | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Lenovo        | G570 20079                  | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Dell          | Latitude E5400              | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Dell          | Latitude E6420              | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Acer          | Aspire 4820T                | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| ASUSTek       | GL553VE                     | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [709a3db7de](https://bsd-hardware.info/?probe=709a3db7de) | May 25, 2020 |
| Lenovo        | G570 20079                  | [0b7b4083bd](https://bsd-hardware.info/?probe=0b7b4083bd) | May 22, 2020 |
| Lenovo        | G570 20079                  | [f7cb1aa38d](https://bsd-hardware.info/?probe=f7cb1aa38d) | May 21, 2020 |
| Dell          | Latitude E6530              | [04cd35a77b](https://bsd-hardware.info/?probe=04cd35a77b) | May 21, 2020 |
| Lenovo        | G570 20079                  | [dc3c3cff26](https://bsd-hardware.info/?probe=dc3c3cff26) | May 21, 2020 |
| Lenovo        | G570 20079                  | [807f3398e3](https://bsd-hardware.info/?probe=807f3398e3) | May 20, 2020 |
| Lenovo        | G570 20079                  | [8212868b9f](https://bsd-hardware.info/?probe=8212868b9f) | May 19, 2020 |
| Lenovo        | G570 20079                  | [ab53dfc003](https://bsd-hardware.info/?probe=ab53dfc003) | May 19, 2020 |
| Lenovo        | G570 20079                  | [d3f180e9ef](https://bsd-hardware.info/?probe=d3f180e9ef) | May 17, 2020 |
| Lenovo        | G570 20079                  | [bdd93164cf](https://bsd-hardware.info/?probe=bdd93164cf) | May 17, 2020 |
| Lenovo        | G570 20079                  | [6a1b7867f0](https://bsd-hardware.info/?probe=6a1b7867f0) | May 16, 2020 |
| Lenovo        | G570 20079                  | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| Lenovo        | G570 20079                  | [4a419328b8](https://bsd-hardware.info/?probe=4a419328b8) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| ASUSTek       | A3L                         | [0d292bca2f](https://bsd-hardware.info/?probe=0d292bca2f) | May 15, 2020 |
| ASUSTek       | X71SL                       | [2fd46cb7c7](https://bsd-hardware.info/?probe=2fd46cb7c7) | May 15, 2020 |
| ASUSTek       | X71SL                       | [8a027d0a73](https://bsd-hardware.info/?probe=8a027d0a73) | May 14, 2020 |
| Dell          | Latitude E6530              | [2c5eec6613](https://bsd-hardware.info/?probe=2c5eec6613) | May 09, 2020 |
| Dell          | Latitude E6530              | [1542f8e5a8](https://bsd-hardware.info/?probe=1542f8e5a8) | May 09, 2020 |
| ASUSTek       | X71SL                       | [adf290251e](https://bsd-hardware.info/?probe=adf290251e) | May 09, 2020 |
| ASUSTek       | X71SL                       | [7b4d0958ec](https://bsd-hardware.info/?probe=7b4d0958ec) | May 09, 2020 |
| Sony          | SVE1713S1RW                 | [9a751ddfd8](https://bsd-hardware.info/?probe=9a751ddfd8) | May 08, 2020 |
| Lenovo        | G570 20079                  | [25fd1154c0](https://bsd-hardware.info/?probe=25fd1154c0) | May 08, 2020 |
| ASUSTek       | X71SL                       | [ab5297a63d](https://bsd-hardware.info/?probe=ab5297a63d) | May 07, 2020 |
| ASUSTek       | X71SL                       | [b8e364a2c0](https://bsd-hardware.info/?probe=b8e364a2c0) | May 07, 2020 |
| ASUSTek       | X71SL                       | [2aac4c3564](https://bsd-hardware.info/?probe=2aac4c3564) | May 07, 2020 |
| Lenovo        | G570 20079                  | [4909d93faf](https://bsd-hardware.info/?probe=4909d93faf) | May 06, 2020 |
| Lenovo        | G570 20079                  | [fb9c475d48](https://bsd-hardware.info/?probe=fb9c475d48) | May 06, 2020 |
| Lenovo        | G570 20079                  | [2efd2c4c7a](https://bsd-hardware.info/?probe=2efd2c4c7a) | May 06, 2020 |
| Lenovo        | G570 20079                  | [f1c2bcae9d](https://bsd-hardware.info/?probe=f1c2bcae9d) | May 06, 2020 |
| ASUSTek       | A3L                         | [0c73038abc](https://bsd-hardware.info/?probe=0c73038abc) | May 06, 2020 |
| ASUSTek       | A3L                         | [ff5b6e3024](https://bsd-hardware.info/?probe=ff5b6e3024) | May 06, 2020 |
| Lenovo        | G570 20079                  | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |
| ASUSTek       | X71SL                       | [b48cb0f2ce](https://bsd-hardware.info/?probe=b48cb0f2ce) | May 05, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |
| Lenovo        | G570 20079                  | [0370bc0522](https://bsd-hardware.info/?probe=0370bc0522) | May 02, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 11        | 9.24%   |
| OpenBSD 6.8          | 10        | 8.4%    |
| NomadBSD 1.3.2       | 7         | 5.88%   |
| FreeBSD 13.0         | 6         | 5.04%   |
| OpenBSD 7.1          | 5         | 4.2%    |
| FreeBSD 14.0-CURRENT | 5         | 4.2%    |
| FreeBSD 13.1         | 5         | 4.2%    |
| FreeBSD 13.0-CURRENT | 5         | 4.2%    |
| NomadBSD 5806f915    | 4         | 3.36%   |
| helloSystem 0.6.0    | 4         | 3.36%   |
| FreeBSD 12.1-STABLE  | 4         | 3.36%   |
| OpenBSD 6.9          | 3         | 2.52%   |
| GhostBSD 20.04.02    | 3         | 2.52%   |
| FreeBSD 12.2-p4      | 3         | 2.52%   |
| OpenBSD 6.7          | 2         | 1.68%   |
| FreeBSD 13.0-p3      | 2         | 1.68%   |
| FreeBSD 12.3-STABLE  | 2         | 1.68%   |
| FreeBSD 12.2-STABLE  | 2         | 1.68%   |
| FreeBSD 12.2-p3      | 2         | 1.68%   |
| FreeBSD 12.1-p8      | 2         | 1.68%   |
| FreeBSD 12.1-p7      | 2         | 1.68%   |
| FreeBSD 12.1-p5      | 2         | 1.68%   |
| OS108 9.0            | 1         | 0.84%   |
| OpenBSD 7.0          | 1         | 0.84%   |
| NomadBSD 1.4         | 1         | 0.84%   |
| NomadBSD 1.3.1       | 1         | 0.84%   |
| NetBSD 9.99.94       | 1         | 0.84%   |
| NetBSD 9.1           | 1         | 0.84%   |
| NetBSD 7.2           | 1         | 0.84%   |
| LibertyBSD 6.1       | 1         | 0.84%   |
| helloSystem 0.8.0    | 1         | 0.84%   |
| helloSystem 0.3.0    | 1         | 0.84%   |
| GhostBSD 21.08.27    | 1         | 0.84%   |
| FreeBSD 8.4          | 1         | 0.84%   |
| FreeBSD 13.1-BETA3   | 1         | 0.84%   |
| FreeBSD 13.0-STABLE  | 1         | 0.84%   |
| FreeBSD 13.0-RC1     | 1         | 0.84%   |
| FreeBSD 13.0-p7      | 1         | 0.84%   |
| FreeBSD 13.0-p4      | 1         | 0.84%   |
| FreeBSD 13.0-p2      | 1         | 0.84%   |
| FreeBSD 13.0-p10     | 1         | 0.84%   |
| FreeBSD 13.0-BETA1   | 1         | 0.84%   |
| FreeBSD 12.2-p6      | 1         | 0.84%   |
| FreeBSD 12.2-p2      | 1         | 0.84%   |
| FreeBSD 12.2         | 1         | 0.84%   |
| FreeBSD 12.1-p6      | 1         | 0.84%   |
| FreeBSD 12.1-p3      | 1         | 0.84%   |
| FreeBSD 12.1         | 1         | 0.84%   |
| FreeBSD 11.4-p8      | 1         | 0.84%   |
| FreeBSD 11.4-p5      | 1         | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 53        | 47.75%  |
| OpenBSD     | 20        | 18.02%  |
| helloSystem | 17        | 15.32%  |
| NomadBSD    | 12        | 10.81%  |
| GhostBSD    | 4         | 3.6%    |
| NetBSD      | 3         | 2.7%    |
| OS108       | 1         | 0.9%    |
| LibertyBSD  | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 91        | 87.5%   |
| i386  | 13        | 12.5%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 21        | 18.92%  |
| Openbox       | 13        | 11.71%  |
| fvwm          | 13        | 11.71%  |
| Console       | 13        | 11.71%  |
| XFCE          | 11        | 9.91%   |
| KDE5          | 10        | 9.01%   |
| MATE          | 6         | 5.41%   |
| TWM           | 5         | 4.5%    |
| GNOME         | 5         | 4.5%    |
| LXQt          | 2         | 1.8%    |
| LXDE          | 2         | 1.8%    |
| IceWM         | 2         | 1.8%    |
| i3            | 2         | 1.8%    |
| AwesomeWM     | 2         | 1.8%    |
| StumpWM       | 1         | 0.9%    |
| Lumina        | 1         | 0.9%    |
| Enlightenment | 1         | 0.9%    |
| DWM           | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 91        | 83.49%  |
| Console | 16        | 14.68%  |
| Wayland | 2         | 1.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 44        | 40.37%  |
| SLiM    | 40        | 36.7%   |
| SDDM    | 7         | 6.42%   |
| LightDM | 7         | 6.42%   |
| XDM     | 6         | 5.5%    |
| GDM     | 3         | 2.75%   |
| PCDM    | 1         | 0.92%   |
| Ly      | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 36        | 33.03%  |
| Unknown | 29        | 26.61%  |
| en_US   | 28        | 25.69%  |
| C       | 14        | 12.84%  |
| en_GB   | 1         | 0.92%   |
| en_EN   | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 68        | 62.96%  |
| BIOS | 40        | 37.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Ufs    | 43        | 39.09%  |
| Zfs    | 39        | 35.45%  |
| Ffs    | 21        | 19.09%  |
| Cd9660 | 6         | 5.45%   |
| Xfs    | 1         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 76        | 71.7%   |
| MBR     | 27        | 25.47%  |
| Unknown | 2         | 1.89%   |
| BSD     | 1         | 0.94%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 31        | 29.81%  |
| Hewlett-Packard     | 14        | 13.46%  |
| Dell                | 14        | 13.46%  |
| Acer                | 11        | 10.58%  |
| ASUSTek Computer    | 9         | 8.65%   |
| Sony                | 5         | 4.81%   |
| Samsung Electronics | 4         | 3.85%   |
| Toshiba             | 2         | 1.92%   |
| IBM                 | 2         | 1.92%   |
| Apple               | 2         | 1.92%   |
| Timi                | 1         | 0.96%   |
| Panasonic           | 1         | 0.96%   |
| Packard Bell        | 1         | 0.96%   |
| MSI                 | 1         | 0.96%   |
| Kraftway            | 1         | 0.96%   |
| HUAWEI              | 1         | 0.96%   |
| Google              | 1         | 0.96%   |
| eMachines           | 1         | 0.96%   |
| DNS                 | 1         | 0.96%   |
| DEXP                | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N145P/N250P/N260P                | 2         | 1.92%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 2         | 1.92%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 1.92%   |
| Acer Aspire 4820T                        | 2         | 1.92%   |
| Toshiba Satellite M100                   | 1         | 0.96%   |
| Toshiba Satellite A300                   | 1         | 0.96%   |
| Timi TM1612                              | 1         | 0.96%   |
| Sony VPCX115KX                           | 1         | 0.96%   |
| Sony VPCM13M1R                           | 1         | 0.96%   |
| Sony VGN-S150(UC)                        | 1         | 0.96%   |
| Sony SVP1321V9RB                         | 1         | 0.96%   |
| Sony SVE1713S1RW                         | 1         | 0.96%   |
| Samsung R530/R730/R540                   | 1         | 0.96%   |
| Samsung N150P                            | 1         | 0.96%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.96%   |
| Packard Bell EasyNote TE69HW             | 1         | 0.96%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.96%   |
| Lenovo V580 20147                        | 1         | 0.96%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V      | 1         | 0.96%   |
| Lenovo ThinkPad X240 20AMA52RUK          | 1         | 0.96%   |
| Lenovo ThinkPad X240 20AL00DKRT          | 1         | 0.96%   |
| Lenovo ThinkPad X230 2325Y36             | 1         | 0.96%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT     | 1         | 0.96%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT     | 1         | 0.96%   |
| Lenovo ThinkPad X121e 3053A52            | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DW00 | 1         | 0.96%   |
| Lenovo ThinkPad T495s 20QKS1812F         | 1         | 0.96%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 0.96%   |
| Lenovo ThinkPad T480s 20L7001HRT         | 1         | 0.96%   |
| Lenovo ThinkPad T430 23511A6             | 1         | 0.96%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT     | 1         | 0.96%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.96%   |
| Lenovo ThinkPad E480 20KN005CRT          | 1         | 0.96%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT     | 1         | 0.96%   |
| Lenovo ThinkBook 14 G2 ARE 20VF          | 1         | 0.96%   |
| Lenovo S20-30 Touch 20434                | 1         | 0.96%   |
| Lenovo IdeaPad Z570 HuronRiver Platform  | 1         | 0.96%   |
| Lenovo IdeaPad L340-15API 81LW           | 1         | 0.96%   |
| Lenovo IdeaPad 330-15IGM 81D1            | 1         | 0.96%   |
| Lenovo IdeaPad 320-15ISK 80XH            | 1         | 0.96%   |
| Lenovo IdeaPad 310-15ISK 80SM            | 1         | 0.96%   |
| Lenovo IdeaPad 100S-14IBR 80R9           | 1         | 0.96%   |
| Lenovo G570 20079                        | 1         | 0.96%   |
| Lenovo E31-80 80MX                       | 1         | 0.96%   |
| Lenovo B50-30 20382                      | 1         | 0.96%   |
| Kraftway KW10T                           | 1         | 0.96%   |
| IBM ThinkPad X41 2525FAG                 | 1         | 0.96%   |
| IBM ThinkPad H 1846AQG                   | 1         | 0.96%   |
| HUAWEI CREM-WXX9                         | 1         | 0.96%   |
| HP ProBook 655 G1                        | 1         | 0.96%   |
| HP ProBook 455 G7                        | 1         | 0.96%   |
| HP ProBook 445 G7                        | 1         | 0.96%   |
| HP ProBook 440 G6                        | 1         | 0.96%   |
| HP ProBook 430 G2                        | 1         | 0.96%   |
| HP Pavilion g6                           | 1         | 0.96%   |
| HP OmniBook PC                           | 1         | 0.96%   |
| HP Laptop 15s-fq1xxx                     | 1         | 0.96%   |
| HP Laptop 15-rb0xx                       | 1         | 0.96%   |
| HP Laptop 15-bw0xx                       | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 16.35%  |
| Acer Aspire            | 9         | 8.65%   |
| Lenovo IdeaPad         | 8         | 7.69%   |
| Dell Latitude          | 6         | 5.77%   |
| Dell Inspiron          | 6         | 5.77%   |
| HP ProBook             | 5         | 4.81%   |
| HP Laptop              | 3         | 2.88%   |
| Toshiba Satellite      | 2         | 1.92%   |
| Samsung N145P          | 2         | 1.92%   |
| IBM ThinkPad           | 2         | 1.92%   |
| Acer Extensa           | 2         | 1.92%   |
| Timi TM1612            | 1         | 0.96%   |
| Sony VPCX115KX         | 1         | 0.96%   |
| Sony VPCM13M1R         | 1         | 0.96%   |
| Sony VGN-S150(UC)      | 1         | 0.96%   |
| Sony SVP1321V9RB       | 1         | 0.96%   |
| Sony SVE1713S1RW       | 1         | 0.96%   |
| Samsung R530           | 1         | 0.96%   |
| Samsung N150P          | 1         | 0.96%   |
| Panasonic CF-19AHNC8FN | 1         | 0.96%   |
| Packard Bell EasyNote  | 1         | 0.96%   |
| MSI GE75               | 1         | 0.96%   |
| Lenovo V580            | 1         | 0.96%   |
| Lenovo ThinkBook       | 1         | 0.96%   |
| Lenovo S20-30          | 1         | 0.96%   |
| Lenovo G570            | 1         | 0.96%   |
| Lenovo E31-80          | 1         | 0.96%   |
| Lenovo B50-30          | 1         | 0.96%   |
| Kraftway KW10T         | 1         | 0.96%   |
| HUAWEI CREM-WXX9       | 1         | 0.96%   |
| HP Pavilion            | 1         | 0.96%   |
| HP OmniBook            | 1         | 0.96%   |
| HP EliteBook           | 1         | 0.96%   |
| HP Compaq              | 1         | 0.96%   |
| HP 255                 | 1         | 0.96%   |
| HP 250                 | 1         | 0.96%   |
| Google Chell           | 1         | 0.96%   |
| eMachines eM350        | 1         | 0.96%   |
| DNS W9x0LU             | 1         | 0.96%   |
| DEXP NAVIS             | 1         | 0.96%   |
| Dell Venue             | 1         | 0.96%   |
| Dell Studio            | 1         | 0.96%   |
| ASUS X71SL             | 1         | 0.96%   |
| ASUS X101CH            | 1         | 0.96%   |
| ASUS VX7SX             | 1         | 0.96%   |
| ASUS VivoBook          | 1         | 0.96%   |
| ASUS UX21A             | 1         | 0.96%   |
| ASUS M51Sr             | 1         | 0.96%   |
| ASUS GL553VE           | 1         | 0.96%   |
| ASUS A3L               | 1         | 0.96%   |
| ASUS 1225B             | 1         | 0.96%   |
| Apple MacBookAir6      | 1         | 0.96%   |
| Apple MacBook5         | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 14.42%  |
| 2020 | 13        | 12.5%   |
| 2011 | 11        | 10.58%  |
| 2018 | 9         | 8.65%   |
| 2012 | 7         | 6.73%   |
| 2009 | 6         | 5.77%   |
| 2017 | 5         | 4.81%   |
| 2015 | 5         | 4.81%   |
| 2021 | 4         | 3.85%   |
| 2016 | 4         | 3.85%   |
| 2014 | 4         | 3.85%   |
| 2013 | 4         | 3.85%   |
| 2010 | 4         | 3.85%   |
| 2008 | 4         | 3.85%   |
| 2006 | 2         | 1.92%   |
| 2005 | 2         | 1.92%   |
| 2004 | 2         | 1.92%   |
| 2022 | 1         | 0.96%   |
| 2007 | 1         | 0.96%   |
| 2003 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 99.04%  |
| Yes  | 1         | 0.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 32        | 30.19%  |
| 8.01-16.0   | 31        | 29.25%  |
| 16.01-24.0  | 18        | 16.98%  |
| 2.01-3.0    | 9         | 8.49%   |
| 1.01-2.0    | 4         | 3.77%   |
| 0.51-1.0    | 4         | 3.77%   |
| 0.01-0.5    | 3         | 2.83%   |
| 24.01-32.0  | 2         | 1.89%   |
| 32.01-64.0  | 1         | 0.94%   |
| 3.01-4.0    | 1         | 0.94%   |
| 64.01-256.0 | 1         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 63        | 57.27%  |
| 0.51-1.0   | 26        | 23.64%  |
| 2.01-3.0   | 5         | 4.55%   |
| Unknown    | 5         | 4.55%   |
| 1.01-2.0   | 4         | 3.64%   |
| 0          | 4         | 3.64%   |
| 4.01-8.0   | 1         | 0.91%   |
| 24.01-32.0 | 1         | 0.91%   |
| 8.01-16.0  | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 66.97%  |
| 2      | 27        | 24.77%  |
| 0      | 4         | 3.67%   |
| 4      | 3         | 2.75%   |
| 3      | 2         | 1.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 79.81%  |
| Yes       | 21        | 20.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 87.5%   |
| No        | 13        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 97.12%  |
| No        | 3         | 2.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 63.46%  |
| No        | 38        | 36.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 104       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 34        | 32.38%  |
| St Petersburg    | 12        | 11.43%  |
| Vladivostok      | 5         | 4.76%   |
| Yekaterinburg    | 4         | 3.81%   |
| Novosibirsk      | 4         | 3.81%   |
| Ulyanovsk        | 3         | 2.86%   |
| Krasnoyarsk      | 3         | 2.86%   |
| Ufa              | 2         | 1.9%    |
| Tyumen           | 2         | 1.9%    |
| Tolyatti         | 2         | 1.9%    |
| Kirov            | 2         | 1.9%    |
| Chelyabinsk      | 2         | 1.9%    |
| Zhukovskiy       | 1         | 0.95%   |
| Yoshkar-Ola      | 1         | 0.95%   |
| Yegorlykskaya    | 1         | 0.95%   |
| Yaroslavl        | 1         | 0.95%   |
| Vorkuta          | 1         | 0.95%   |
| Vladimir         | 1         | 0.95%   |
| Ust'-Luga        | 1         | 0.95%   |
| Tsarskoye Selo   | 1         | 0.95%   |
| Surgut           | 1         | 0.95%   |
| Sevastopol'      | 1         | 0.95%   |
| Rostov-on-Don    | 1         | 0.95%   |
| Pushkino         | 1         | 0.95%   |
| Penza            | 1         | 0.95%   |
| Ozersk           | 1         | 0.95%   |
| Oryol            | 1         | 0.95%   |
| Obninsk          | 1         | 0.95%   |
| Nizhniy Novgorod | 1         | 0.95%   |
| Michurinsk       | 1         | 0.95%   |
| Kstovo           | 1         | 0.95%   |
| Krasnokamsk      | 1         | 0.95%   |
| Krasnodar        | 1         | 0.95%   |
| Korolyov         | 1         | 0.95%   |
| Kislovodsk       | 1         | 0.95%   |
| Khabarovsk       | 1         | 0.95%   |
| Kez              | 1         | 0.95%   |
| Kaliningrad      | 1         | 0.95%   |
| Izhevsk          | 1         | 0.95%   |
| Dolgoprudnyy     | 1         | 0.95%   |
| Chita            | 1         | 0.95%   |
| Chebarkul'       | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 25        | 30     | 19.69%  |
| Seagate             | 14        | 17     | 11.02%  |
| Samsung Electronics | 12        | 15     | 9.45%   |
| Toshiba             | 11        | 12     | 8.66%   |
| SanDisk             | 9         | 11     | 7.09%   |
| Hitachi             | 8         | 10     | 6.3%    |
| SK hynix            | 7         | 8      | 5.51%   |
| Intel               | 5         | 7      | 3.94%   |
| HGST                | 5         | 6      | 3.94%   |
| SPCC                | 4         | 5      | 3.15%   |
| Kingston            | 4         | 5      | 3.15%   |
| Transcend           | 3         | 3      | 2.36%   |
| Micron Technology   | 3         | 3      | 2.36%   |
| NVMe                | 2         | 2      | 1.57%   |
| Innostor            | 2         | 2      | 1.57%   |
| Gigabyte Technology | 2         | 5      | 1.57%   |
| USB                 | 1         | 1      | 0.79%   |
| UFD 2.0             | 1         | 1      | 0.79%   |
| OCZ                 | 1         | 2      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| KLLISRE             | 1         | 1      | 0.79%   |
| Hewlett-Packard     | 1         | 1      | 0.79%   |
| FORESEE             | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |
| Apacer              | 1         | 1      | 0.79%   |
| AMD                 | 1         | 1      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                  | 3         | 2.24%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 3         | 2.24%   |
| Kingston SV300S37A120G 120GB              | 3         | 2.24%   |
| HGST HTS721010A9E630 1TB                  | 3         | 2.24%   |
| WDC WDS240G2G0A-00JH30 240GB              | 2         | 1.49%   |
| WDC WD5000LPVX-60V0TT0 500GB              | 2         | 1.49%   |
| WDC WD2500BEVT-22A23T0 250GB              | 2         | 1.49%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.49%   |
| Seagate ST9500325AS 500GB                 | 2         | 1.49%   |
| Seagate ST500LT012-1DG142 500GB           | 2         | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 1.49%   |
| Micron 1100 SATA 256GB                    | 2         | 1.49%   |
| Innostor SSD 15GB                         | 2         | 1.49%   |
| WDC WDS500G2B0A-00SM50 500GB              | 1         | 0.75%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1         | 0.75%   |
| WDC WDS100T3X0C-00SJG0 1TB                | 1         | 0.75%   |
| WDC WD5000LPLX-60ZNTT1 500GB              | 1         | 0.75%   |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 0.75%   |
| WDC WD5000LPCX-24VHAT0 500GB              | 1         | 0.75%   |
| WDC WD5000BPVT-24HXZT3 500GB              | 1         | 0.75%   |
| WDC WD3200BPVT-24JJ5T0 320GB              | 1         | 0.75%   |
| WDC WD20EARX-00PASB0 2TB                  | 1         | 0.75%   |
| WDC WD2000JB-00GVC0 200GB                 | 1         | 0.75%   |
| WDC WD1600BEVT-22ZCT0 160GB               | 1         | 0.75%   |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.75%   |
| WDC WD10JPVX-08JC3T5 1TB                  | 1         | 0.75%   |
| WDC WD10JPVT-08A1YT2 1TB                  | 1         | 0.75%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB      | 1         | 0.75%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB        | 1         | 0.75%   |
| WDC PC SN730 SDBPNTY-512G                 | 1         | 0.75%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB      | 1         | 0.75%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB      | 1         | 0.75%   |
| USB SanDisk 3.2Gen1 64GB                  | 1         | 0.75%   |
| UFD 2.0 Silicon-Power16G 18302PB          | 1         | 0.75%   |
| Transcend TS256GMTS400 256GB              | 1         | 0.75%   |
| Transcend TS240GMTS420S 240GB             | 1         | 0.75%   |
| Transcend TS1TMTE110S 1TB                 | 1         | 0.75%   |
| Toshiba MQ04ABF100 1TB                    | 1         | 0.75%   |
| Toshiba MK7575GSX 752GB                   | 1         | 0.75%   |
| Toshiba MK2546GSX 250GB                   | 1         | 0.75%   |
| Toshiba MK1637GSX 160GB                   | 1         | 0.75%   |
| Toshiba MK1517GAP 16GB                    | 1         | 0.75%   |
| Toshiba KBG30ZMV512G 512GB                | 1         | 0.75%   |
| SPCC Solid State Disk 64GB                | 1         | 0.75%   |
| SPCC Solid State Disk 240GB               | 1         | 0.75%   |
| SPCC Solid State Disk 128GB               | 1         | 0.75%   |
| SPCC Solid State Disk 120GB               | 1         | 0.75%   |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 0.75%   |
| SK hynix HFS128G32TNF-N3A0A 128GB         | 1         | 0.75%   |
| SK hynix HFM256GDJTNG-8310A 256GB         | 1         | 0.75%   |
| SK hynix HFM256GDHTNG-8510B 256GB         | 1         | 0.75%   |
| SK hynix BC511 NVMe 512GB                 | 1         | 0.75%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 0.75%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB   | 1         | 0.75%   |
| Seagate ST9250320AS 250GB                 | 1         | 0.75%   |
| Seagate ST500LM030-2E717D 500GB           | 1         | 0.75%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 0.75%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 26.32%  |
| Seagate             | 14        | 17     | 24.56%  |
| Toshiba             | 10        | 11     | 17.54%  |
| Hitachi             | 8         | 10     | 14.04%  |
| HGST                | 5         | 6      | 8.77%   |
| NVMe                | 2         | 2      | 3.51%   |
| USB                 | 1         | 1      | 1.75%   |
| UFD 2.0             | 1         | 1      | 1.75%   |
| Samsung Electronics | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 9         | 11     | 17.65%  |
| Samsung Electronics | 8         | 9      | 15.69%  |
| WDC                 | 4         | 5      | 7.84%   |
| SPCC                | 4         | 5      | 7.84%   |
| Kingston            | 4         | 5      | 7.84%   |
| Intel               | 4         | 6      | 7.84%   |
| Micron Technology   | 3         | 3      | 5.88%   |
| Transcend           | 2         | 2      | 3.92%   |
| Innostor            | 2         | 2      | 3.92%   |
| SK hynix            | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 2      | 1.96%   |
| Netac               | 1         | 1      | 1.96%   |
| KLLISRE             | 1         | 1      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| Gigabyte Technology | 1         | 3      | 1.96%   |
| FORESEE             | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| Apacer              | 1         | 1      | 1.96%   |
| AMD                 | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 65     | 44.35%  |
| SSD  | 45        | 62     | 39.13%  |
| NVMe | 19        | 26     | 16.52%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 127    | 81.73%  |
| NVMe | 19        | 26     | 18.27%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 72        | 102    | 75.79%  |
| 0.51-1.0        | 20        | 22     | 21.05%  |
| 1.01-2.0        | 2         | 2      | 2.11%   |
| More than 100.0 | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 29        | 25.44%  |
| 1-20       | 27        | 23.68%  |
| 251-500    | 22        | 19.3%   |
| 21-50      | 11        | 9.65%   |
| 501-1000   | 10        | 8.77%   |
| 51-100     | 10        | 8.77%   |
| 1001-2000  | 3         | 2.63%   |
| Unknown    | 2         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 77        | 71.3%   |
| 21-50   | 14        | 12.96%  |
| 101-250 | 9         | 8.33%   |
| 51-100  | 4         | 3.7%    |
| 251-500 | 2         | 1.85%   |
| Unknown | 2         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 6.67%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 6.67%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 3.33%   |
| WDC WD2000JB-00GVC0 200GB           | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 3.33%   |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 3.33%   |
| Toshiba MK2546GSX 250GB             | 1         | 1      | 3.33%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 3.33%   |
| Seagate ST9250320AS 250GB           | 1         | 1      | 3.33%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 3.33%   |
| Samsung Electronics HM080HI 80GB    | 1         | 1      | 3.33%   |
| Kingston SV300S37A120G 120GB        | 1         | 1      | 3.33%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 3.33%   |
| Intel SSDSC2CW060A3 64GB            | 1         | 1      | 3.33%   |
| Intel SSDSC2BB480G7 480GB           | 1         | 1      | 3.33%   |
| Hitachi HTS725025A9A364 250GB       | 1         | 1      | 3.33%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 3.33%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 3.33%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 3.33%   |
| Hitachi HTC426060G9AT00 64GB        | 1         | 1      | 3.33%   |
| Hitachi DK23AA-12 12GB              | 1         | 1      | 3.33%   |
| HGST HTS541075A7E630 752GB          | 1         | 1      | 3.33%   |
| HGST HTE725032A7E630 320GB          | 1         | 1      | 3.33%   |
| Apple SSD SD0128F 121GB             | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 23.33%  |
| Hitachi             | 6         | 6      | 20%     |
| Toshiba             | 5         | 5      | 16.67%  |
| Intel               | 3         | 3      | 10%     |
| WDC                 | 2         | 2      | 6.67%   |
| Micron Technology   | 2         | 2      | 6.67%   |
| HGST                | 2         | 2      | 6.67%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Kingston            | 1         | 1      | 3.33%   |
| Apple               | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 30.43%  |
| Hitachi             | 6         | 6      | 26.09%  |
| Toshiba             | 5         | 5      | 21.74%  |
| WDC                 | 2         | 2      | 8.7%    |
| HGST                | 2         | 2      | 8.7%    |
| Samsung Electronics | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 23     | 76.67%  |
| SSD  | 7         | 7      | 23.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 79        | 118    | 69.3%   |
| Malfunc  | 30        | 30     | 26.32%  |
| Detected | 4         | 4      | 3.51%   |
| Failed   | 1         | 1      | 0.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 73        | 63.48%  |
| AMD                              | 18        | 15.65%  |
| SK hynix                         | 7         | 6.09%   |
| SanDisk                          | 6         | 5.22%   |
| Samsung Electronics              | 4         | 3.48%   |
| Toshiba                          | 1         | 0.87%   |
| Silicon Integrated Systems [SiS] | 1         | 0.87%   |
| Phison Electronics               | 1         | 0.87%   |
| Nvidia                           | 1         | 0.87%   |
| Marvell Technology Group         | 1         | 0.87%   |
| JMicron Technology               | 1         | 0.87%   |
| Unknown                          | 1         | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 12.4%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 8.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 4.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.13%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 3.31%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 3.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 3.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 3.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 3.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.48%   |
| SK hynix BC511                                                                   | 2         | 1.65%   |
| SanDisk PC SN530                                                                 | 2         | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.65%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 1.65%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.65%   |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.65%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.83%   |
| SK hynix hynix unknown                                                           | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.83%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.83%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.83%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.83%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.83%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 1         | 0.83%   |
| Intel SSD 660P Series                                                            | 1         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.83%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.83%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.83%   |
| AMD SB600 IDE                                                                    | 1         | 0.83%   |
| Unknown                                                                          | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 80        | 68.38%  |
| NVMe | 20        | 17.09%  |
| IDE  | 15        | 12.82%  |
| RAID | 2         | 1.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 83        | 79.81%  |
| AMD    | 21        | 20.19%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 5         | 4.72%   |
| Intel C1                                                            | 3         | 2.83%   |
| Intel Pentium M processor 1.60GHz                                   | 2         | 1.89%   |
| Intel CPU Version                                                   | 2         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 2         | 1.89%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 1.89%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 1.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 2         | 1.89%   |
| Intel Core i5-2430M CPU @ 2.40GHz                                   | 2         | 1.89%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                                   | 2         | 1.89%   |
| Intel Core 2 Duo                                                    | 2         | 1.89%   |
| Intel 686-class                                                     | 2         | 1.89%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 2         | 1.89%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                       | 2         | 1.89%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                       | 2         | 1.89%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                                   | 1         | 0.94%   |
| Intel Pentium Silver N6000 @ 1.10GHz                                | 1         | 0.94%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 0.94%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 0.94%   |
| Intel Pentium M processor                                           | 1         | 0.94%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 0.94%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 1         | 0.94%   |
| Intel Pentium CPU N3700 @ 1.60GHz                                   | 1         | 0.94%   |
| Intel Pentium CPU N3530 @ 2.16GHz                                   | 1         | 0.94%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 0.94%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 0.94%   |
| Intel Genuine CPU U7300 @ 1.30GHz                                   | 1         | 0.94%   |
| Intel Genuine CPU T2                                                | 1         | 0.94%   |
| Intel Genuine CPU                                                   | 1         | 0.94%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                                    | 1         | 0.94%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                                    | 1         | 0.94%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                                     | 1         | 0.94%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                                 | 1         | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz                                   | 1         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 1         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                                  | 1         | 0.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz                                   | 1         | 0.94%   |
| Intel Core i7-4600U CPU @ 2.10GHz                                   | 1         | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz                                  | 1         | 0.94%   |
| Intel Core i7-3520M CPU @ 2.90GHz                                   | 1         | 0.94%   |
| Intel Core i7-3517U CPU @ 1.90GHz                                   | 1         | 0.94%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                                  | 1         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz                                  | 1         | 0.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz                                   | 1         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz                                   | 1         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz                                   | 1         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz                                   | 1         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz                                   | 1         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz                                   | 1         | 0.94%   |
| Intel Core i5-4250U CPU @ 1.30GHz                                   | 1         | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz                                   | 1         | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz                                   | 1         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GH                                    | 1         | 0.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz                                  | 1         | 0.94%   |
| Intel Core i5-10310U CPU @ 1.70GHz                                  | 1         | 0.94%   |
| Intel Core i3-7020U CPU @ 2.30GHz                                   | 1         | 0.94%   |
| Intel Core i3-5005U CPU @ 2.00GHz                                   | 1         | 0.94%   |
| Intel Core i3-4030U CPU @ 1.90GHz                                   | 1         | 0.94%   |
| Intel Core i3-3120M CPU @ 2.50GHz                                   | 1         | 0.94%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz                                | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 18.87%  |
| Intel Core i7           | 12        | 11.32%  |
| Intel Core i3           | 11        | 10.38%  |
| Other                   | 7         | 6.6%    |
| Intel Core 2 Duo        | 6         | 5.66%   |
| Intel Atom              | 5         | 4.72%   |
| AMD Ryzen 3             | 5         | 4.72%   |
| Intel Pentium M         | 4         | 3.77%   |
| Intel Celeron           | 4         | 3.77%   |
| AMD Ryzen 7             | 4         | 3.77%   |
| Intel Pentium           | 3         | 2.83%   |
| Intel Genuine           | 3         | 2.83%   |
| AMD E                   | 3         | 2.83%   |
| Intel Pentium Silver    | 2         | 1.89%   |
| Intel 686-class         | 2         | 1.89%   |
| AMD Ryzen 7 PRO         | 2         | 1.89%   |
| AMD Ryzen 5             | 2         | 1.89%   |
| AMD A6                  | 2         | 1.89%   |
| Intel Xeon              | 1         | 0.94%   |
| Intel Pentium Dual-Core | 1         | 0.94%   |
| Intel Core m5           | 1         | 0.94%   |
| Intel Core m3           | 1         | 0.94%   |
| Intel Core M            | 1         | 0.94%   |
| Intel Core i9           | 1         | 0.94%   |
| AMD E2                  | 1         | 0.94%   |
| AMD E1                  | 1         | 0.94%   |
| AMD A10                 | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 46        | 42.99%  |
| 4       | 26        | 24.3%   |
| Unknown | 15        | 14.02%  |
| 1       | 9         | 8.41%   |
| 8       | 7         | 6.54%   |
| 16      | 2         | 1.87%   |
| 6       | 2         | 1.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 98        | 91.59%  |
| Unknown | 9         | 8.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 51        | 47.66%  |
| 1       | 36        | 33.64%  |
| Unknown | 20        | 18.69%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 13.33%  |
| Skylake       | 9         | 8.57%   |
| Penryn        | 7         | 6.67%   |
| P6            | 7         | 6.67%   |
| IvyBridge     | 7         | 6.67%   |
| Bonnell       | 7         | 6.67%   |
| SandyBridge   | 6         | 5.71%   |
| Haswell       | 6         | 5.71%   |
| Zen 2         | 5         | 4.76%   |
| Silvermont    | 5         | 4.76%   |
| Zen+          | 4         | 3.81%   |
| Zen           | 3         | 2.86%   |
| Westmere      | 3         | 2.86%   |
| Core          | 3         | 2.86%   |
| Goldmont      | 2         | 1.9%    |
| Excavator     | 2         | 1.9%    |
| CometLake     | 2         | 1.9%    |
| Broadwell     | 2         | 1.9%    |
| Bobcat        | 2         | 1.9%    |
| Unknown       | 2         | 1.9%    |
| Zen 3         | 1         | 0.95%   |
| Puma          | 1         | 0.95%   |
| Piledriver    | 1         | 0.95%   |
| K8 Hammer     | 1         | 0.95%   |
| Jaguar        | 1         | 0.95%   |
| IceLake       | 1         | 0.95%   |
| Goldmont plus | 1         | 0.95%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 72        | 59.5%   |
| AMD    | 34        | 28.1%   |
| Nvidia | 14        | 11.57%  |
| ATI    | 1         | 0.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.07%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 4.07%   |
| AMD Renoir                                                                               | 5         | 4.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.44%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.44%   |
| Intel HD Graphics 630                                                                    | 3         | 2.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.44%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.63%   |
| Intel HD Graphics 620                                                                    | 2         | 1.63%   |
| Intel HD Graphics 520                                                                    | 2         | 1.63%   |
| Intel HD Graphics 515                                                                    | 2         | 1.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.63%   |
| Nvidia TU117M                                                                            | 1         | 0.81%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.81%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.81%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.81%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.81%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.81%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.81%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 1         | 0.81%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.81%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.81%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.81%   |
| Intel HD Graphics 500                                                                    | 1         | 0.81%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.81%   |
| Intel Comet Lake-H WS GT2 Integrated UHD Graphics Controller                             | 1         | 0.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 0.81%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.81%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.81%   |
| Intel 82830M/MG Integrated Graphics Controller                                           | 1         | 0.81%   |
| ATI Robson CE [Radeon HD 6370M/7370M]                                                    | 1         | 0.81%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 0.81%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.81%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.81%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.81%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.81%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 0.81%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 1         | 0.81%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                                | 1         | 0.81%   |
| AMD RV516/M62-S [Mobility Radeon X1350]                                                  | 1         | 0.81%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 45.71%  |
| 1 x AMD        | 29        | 27.62%  |
| 2 x Intel      | 10        | 9.52%   |
| Intel + Nvidia | 10        | 9.52%   |
| Intel + AMD    | 4         | 3.81%   |
| 1 x Nvidia     | 3         | 2.86%   |
| AMD + Nvidia   | 1         | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 96        | 91.43%  |
| Unknown     | 5         | 4.76%   |
| Proprietary | 4         | 3.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 81.48%  |
| 0.01-0.5   | 13        | 12.04%  |
| 1.01-2.0   | 4         | 3.7%    |
| 0.51-1.0   | 2         | 1.85%   |
| 2.01-3.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 22.35%  |
| LG Display              | 13        | 15.29%  |
| Samsung Electronics     | 10        | 11.76%  |
| BOE                     | 10        | 11.76%  |
| Chimei Innolux          | 7         | 8.24%   |
| InfoVision              | 4         | 4.71%   |
| Chi Mei Optoelectronics | 3         | 3.53%   |
| ViewSonic               | 2         | 2.35%   |
| PANDA                   | 2         | 2.35%   |
| LG Philips              | 2         | 2.35%   |
| Lenovo                  | 2         | 2.35%   |
| Acer                    | 2         | 2.35%   |
| Toshiba                 | 1         | 1.18%   |
| Panasonic               | 1         | 1.18%   |
| NEC Computers           | 1         | 1.18%   |
| HannStar                | 1         | 1.18%   |
| Goldstar                | 1         | 1.18%   |
| CSO                     | 1         | 1.18%   |
| CPT                     | 1         | 1.18%   |
| Apple                   | 1         | 1.18%   |
| Ancor Communications    | 1         | 1.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 2.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 2.35%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 2.35%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 1.18%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 1.18%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 1.18%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 1.18%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 1.18%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 1.18%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 1.18%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 1.18%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 1.18%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.18%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.18%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 1.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.18%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 1         | 1.18%   |
| InfoVision M116NWR1 R0  IVO0489 1366x768 260x140mm 11.6-inch             | 1         | 1.18%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 310x170mm 13.9-inch             | 1         | 1.18%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch             | 1         | 1.18%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 1         | 1.18%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 1         | 1.18%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch               | 1         | 1.18%   |
| CSO LCD Monitor CSO1500 3840x2160 340x190mm 15.3-inch                    | 1         | 1.18%   |
| CPT LCD Monitor CPT1401 1280x800 330x210mm 15.4-inch                     | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN1731 1600x900 390x220mm 17.6-inch          | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 340x190mm 15.3-inch         | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15D9 1920x1080 340x190mm 15.3-inch         | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 1         | 1.18%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch         | 1         | 1.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 1         | 1.18%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                    | 1         | 1.18%   |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                    | 1         | 1.18%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 1.18%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                    | 1         | 1.18%   |
| BOE LCD Monitor BOE06EE 1920x1080 310x170mm 13.9-inch                    | 1         | 1.18%   |
| BOE LCD Monitor BOE06BA 1920x1080 340x190mm 15.3-inch                    | 1         | 1.18%   |
| BOE LCD Monitor BOE06A5 1366x768 340x190mm 15.3-inch                     | 1         | 1.18%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                    | 1         | 1.18%   |
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                     | 1         | 1.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 35        | 41.18%  |
| 1366x768 (WXGA)   | 25        | 29.41%  |
| 1280x800 (WXGA)   | 5         | 5.88%   |
| 1024x600          | 4         | 4.71%   |
| 1440x900 (WXGA+)  | 3         | 3.53%   |
| 3840x2160 (4K)    | 2         | 2.35%   |
| 2560x1440 (QHD)   | 2         | 2.35%   |
| 1600x900 (HD+)    | 2         | 2.35%   |
| 1280x1024 (SXGA)  | 2         | 2.35%   |
| 3200x1800 (QHD+)  | 1         | 1.18%   |
| 2880x1620         | 1         | 1.18%   |
| 2560x1080         | 1         | 1.18%   |
| 1920x540          | 1         | 1.18%   |
| 1920x1200 (WUXGA) | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 34        | 40%     |
| 13     | 22        | 25.88%  |
| 17     | 5         | 5.88%   |
| 11     | 5         | 5.88%   |
| 10     | 5         | 5.88%   |
| 14     | 3         | 3.53%   |
| 12     | 3         | 3.53%   |
| 21     | 2         | 2.35%   |
| 54     | 1         | 1.18%   |
| 34     | 1         | 1.18%   |
| 31     | 1         | 1.18%   |
| 27     | 1         | 1.18%   |
| 23     | 1         | 1.18%   |
| 19     | 1         | 1.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 50        | 58.82%  |
| 201-300     | 23        | 27.06%  |
| 351-400     | 5         | 5.88%   |
| 501-600     | 2         | 2.35%   |
| 401-500     | 2         | 2.35%   |
| 701-800     | 1         | 1.18%   |
| 601-700     | 1         | 1.18%   |
| 1001-1500   | 1         | 1.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 83.54%  |
| 16/10 | 10        | 12.66%  |
| 5/4   | 2         | 2.53%   |
| 21/9  | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 28        | 32.94%  |
| 81-90          | 19        | 22.35%  |
| 71-80          | 6         | 7.06%   |
| 101-110        | 6         | 7.06%   |
| 51-60          | 5         | 5.88%   |
| 41-50          | 5         | 5.88%   |
| 61-70          | 3         | 3.53%   |
| 201-250        | 3         | 3.53%   |
| 131-140        | 3         | 3.53%   |
| 351-500        | 2         | 2.35%   |
| More than 1000 | 1         | 1.18%   |
| 301-350        | 1         | 1.18%   |
| 151-200        | 1         | 1.18%   |
| 141-150        | 1         | 1.18%   |
| 121-130        | 1         | 1.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 35        | 41.18%  |
| 101-120       | 26        | 30.59%  |
| 51-100        | 13        | 15.29%  |
| 161-240       | 9         | 10.59%  |
| More than 240 | 2         | 2.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 79        | 70.54%  |
| 0     | 24        | 21.43%  |
| 2     | 9         | 8.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 56        | 30.43%  |
| Realtek Semiconductor             | 48        | 26.09%  |
| Qualcomm Atheros                  | 32        | 17.39%  |
| Broadcom                          | 13        | 7.07%   |
| Marvell Technology Group          | 7         | 3.8%    |
| TP-Link                           | 4         | 2.17%   |
| Ralink Technology                 | 4         | 2.17%   |
| Ralink                            | 2         | 1.09%   |
| Fibocom                           | 2         | 1.09%   |
| Ericsson Business Mobile Networks | 2         | 1.09%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.54%   |
| Samsung Electronics               | 1         | 0.54%   |
| Realtek                           | 1         | 0.54%   |
| Nvidia                            | 1         | 0.54%   |
| Mercucys                          | 1         | 0.54%   |
| JMicron Technology                | 1         | 0.54%   |
| Huawei Technologies               | 1         | 0.54%   |
| Dell                              | 1         | 0.54%   |
| D-Link                            | 1         | 0.54%   |
| BUFFALO                           | 1         | 0.54%   |
| Attansic                          | 1         | 0.54%   |
| Atheros                           | 1         | 0.54%   |
| Arduino SA                        | 1         | 0.54%   |
| 3Com                              | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 35        | 15.49%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 11        | 4.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 8         | 3.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 6         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 5         | 2.21%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 5         | 2.21%   |
| Intel Wireless 8265 / 8275                                                  | 5         | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 1.77%   |
| Intel Wireless 7265                                                         | 4         | 1.77%   |
| Intel Wi-Fi 6 AX200                                                         | 4         | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 4         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 3         | 1.33%   |
| Intel Wireless 8260                                                         | 3         | 1.33%   |
| Intel Wireless 3165                                                         | 3         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 3         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 1.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 2         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 2         | 0.88%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 2         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                               | 2         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 2         | 0.88%   |
| Intel Wireless-AC 9260                                                      | 2         | 0.88%   |
| Intel Wireless 7260                                                         | 2         | 0.88%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.88%   |
| Intel Ethernet Connection I219-LM                                           | 2         | 0.88%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                        | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 2         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 2         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 2         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 0.88%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                           | 2         | 0.88%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 0.88%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                    | 2         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                 | 1         | 0.44%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]         | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter               | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                               | 1         | 0.44%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                             | 1         | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1         | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 0.44%   |
| Ralink RT3572 Wireless Adapter                                              | 1         | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 0.44%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                           | 1         | 0.44%   |
| Ralink MT7601U Wireless Adapter                                             | 1         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                   | 1         | 0.44%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                               | 1         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                               | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 44.92%  |
| Qualcomm Atheros      | 27        | 22.88%  |
| Realtek Semiconductor | 16        | 13.56%  |
| Broadcom              | 8         | 6.78%   |
| TP-Link               | 4         | 3.39%   |
| Ralink Technology     | 4         | 3.39%   |
| Ralink                | 2         | 1.69%   |
| Mercucys              | 1         | 0.85%   |
| D-Link                | 1         | 0.85%   |
| BUFFALO               | 1         | 0.85%   |
| Atheros               | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 11        | 9.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 4.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 4.1%    |
| Intel Wireless 8265 / 8275                                                    | 5         | 4.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 4         | 3.28%   |
| Intel Wireless 7265                                                           | 4         | 3.28%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 3.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 3.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 2.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 3         | 2.46%   |
| Intel Wireless 8260                                                           | 3         | 2.46%   |
| Intel Wireless 3165                                                           | 3         | 2.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 3         | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 2.46%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.64%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 1.64%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                         | 2         | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.64%   |
| Intel Wireless-AC 9260                                                        | 2         | 1.64%   |
| Intel Wireless 7260                                                           | 2         | 1.64%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 1.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 2         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 2         | 1.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.82%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U]           | 1         | 0.82%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                               | 1         | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.82%   |
| Ralink RT3572 Wireless Adapter                                                | 1         | 0.82%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.82%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                             | 1         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.82%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.82%   |
| Mercucys MERCUSYS Wireless USB Adapter                                        | 1         | 0.82%   |
| Intel WiMAX/WiFi Link 5150                                                    | 1         | 0.82%   |
| Intel WiFi Link 5100                                                          | 1         | 0.82%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 0.82%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 1         | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 1         | 0.82%   |
| Intel Centrino Wireless-N 6150                                                | 1         | 0.82%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 0.82%   |
| Intel Centrino WiMAX 6150                                                     | 1         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                                | 1         | 0.82%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.82%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.B1) [Ralink RT5370]                 | 1         | 0.82%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]                      | 1         | 0.82%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 1         | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 1         | 0.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 1         | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 44        | 46.81%  |
| Intel                            | 20        | 21.28%  |
| Qualcomm Atheros                 | 10        | 10.64%  |
| Marvell Technology Group         | 7         | 7.45%   |
| Broadcom                         | 6         | 6.38%   |
| Silicon Integrated Systems [SiS] | 1         | 1.06%   |
| Samsung Electronics              | 1         | 1.06%   |
| Realtek                          | 1         | 1.06%   |
| Nvidia                           | 1         | 1.06%   |
| JMicron Technology               | 1         | 1.06%   |
| Attansic                         | 1         | 1.06%   |
| 3Com                             | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 37.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 8.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.38%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 5.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.13%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 2.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.13%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.13%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.13%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 2.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.06%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.06%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 1.06%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 1.06%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.06%   |
| Intel PRO/100 VM Network Connection                               | 1         | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.06%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.06%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.06%   |
| Intel 82801CAM (ICH3) PRO/100 VM (KM) Ethernet Controller         | 1         | 1.06%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.06%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.06%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 1.06%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.06%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.06%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 1.06%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 50%     |
| Ethernet | 91        | 45.05%  |
| Modem    | 5         | 2.48%   |
| Unknown  | 5         | 2.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 50.34%  |
| Ethernet | 70        | 48.28%  |
| Unknown  | 2         | 1.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 88        | 84.62%  |
| 1     | 16        | 15.38%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 102       | 97.14%  |
| Yes  | 3         | 2.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 47.76%  |
| Realtek Semiconductor           | 7         | 10.45%  |
| Qualcomm Atheros Communications | 7         | 10.45%  |
| Broadcom                        | 4         | 5.97%   |
| Lite-On Technology              | 3         | 4.48%   |
| ASUSTek Computer                | 3         | 4.48%   |
| Hewlett-Packard                 | 2         | 2.99%   |
| Apple                           | 2         | 2.99%   |
| Alps Electric                   | 2         | 2.99%   |
| Realtek                         | 1         | 1.49%   |
| Ralink                          | 1         | 1.49%   |
| IMC Networks                    | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |
| Dell                            | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 14        | 20.9%   |
| Intel AX201 Bluetooth                                       | 5         | 7.46%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 5.97%   |
| Intel AX200 Bluetooth                                       | 4         | 5.97%   |
| Realtek  Bluetooth Adapter                                  | 3         | 4.48%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 4.48%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 4.48%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 2.99%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 2.99%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.99%   |
| Realtek Bluetooth Radio                                     | 1         | 1.49%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.49%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.49%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.49%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.49%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 1.49%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.49%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.49%   |
| Broadcom Broadcom Bluetooth 4.0                             | 1         | 1.49%   |
| Broadcom BCM43142A0 Bluetooth Module                        | 1         | 1.49%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.49%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.49%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.49%   |
| Apple Bluetooth Host Controller                             | 1         | 1.49%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.49%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.49%   |
| Alps Electric BCM2046 Bluetooth Device                      | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 80        | 70.18%  |
| AMD                              | 24        | 21.05%  |
| Nvidia                           | 5         | 4.39%   |
| Texas Instruments                | 1         | 0.88%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| Lenovo                           | 1         | 0.88%   |
| ESS Technology                   | 1         | 0.88%   |
| Creative Technology              | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 9.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 9.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 4.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 4.26%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 4.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.84%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.13%   |
| AMD FCH Azalia Controller                                                                         | 3         | 2.13%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.42%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.42%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.42%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.42%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.42%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.42%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.71%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.71%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.71%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.71%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.71%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.71%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.71%   |
| ESS Technology ES1988 Allegro-1                                                                   | 1         | 0.71%   |
| Creative Technology USB Sound Blaster HD                                                          | 1         | 0.71%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.71%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 23.85%  |
| SK hynix            | 20        | 18.35%  |
| Unknown             | 17        | 15.6%   |
| Kingston            | 15        | 13.76%  |
| Micron Technology   | 11        | 10.09%  |
| Elpida              | 3         | 2.75%   |
| 48spaces            | 3         | 2.75%   |
| Transcend           | 2         | 1.83%   |
| Ramaxel Technology  | 2         | 1.83%   |
| Crucial             | 2         | 1.83%   |
| Corsair             | 2         | 1.83%   |
| A-DATA Technology   | 2         | 1.83%   |
| Silicon Power       | 1         | 0.92%   |
| Apacer              | 1         | 0.92%   |
| AMD                 | 1         | 0.92%   |
| Unknown             | 1         | 0.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 3.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 2.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 2.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 2.56%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 2.56%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 2         | 1.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 1.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 2         | 1.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.71%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.71%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.71%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 0.85%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.85%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.85%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR 800MT/s                              | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 1         | 0.85%   |
| Unknown RAM Module 128MB SODIMM DRAM                                      | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266(3.8ns)MT/s                     | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                     | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR                                      | 1         | 0.85%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                            | 1         | 0.85%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                         | 1         | 0.85%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.85%   |
| SK hynix RAM Module 1024MB SODIMM DDR3 1067MT/s                           | 1         | 0.85%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                      | 1         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.85%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s             | 1         | 0.85%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s          | 1         | 0.85%   |
| SK hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.85%   |
| Silicon Power RAM SP004GLSTU160N02 4GB SODIMM DDR3 1600MT/s               | 1         | 0.85%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                             | 1         | 0.85%   |
| Samsung RAM M474A4G43AB1-CVF 32GB SODIMM DDR4 2933MT/s                    | 1         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.85%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.85%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.85%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 1         | 0.85%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 1         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 36.96%  |
| DDR3    | 31        | 33.7%   |
| DDR2    | 11        | 11.96%  |
| LPDDR3  | 5         | 5.43%   |
| DDR     | 4         | 4.35%   |
| DRAM    | 3         | 3.26%   |
| SDRAM   | 2         | 2.17%   |
| RAM     | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 95.65%  |
| Row Of Chips | 2         | 2.17%   |
| DIMM         | 1         | 1.09%   |
| Chip         | 1         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 31.13%  |
| 8192  | 31        | 29.25%  |
| 2048  | 23        | 21.7%   |
| 1024  | 7         | 6.6%    |
| 16384 | 4         | 3.77%   |
| 512   | 3         | 2.83%   |
| 256   | 2         | 1.89%   |
| 32768 | 1         | 0.94%   |
| 2560  | 1         | 0.94%   |
| 128   | 1         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 18.09%  |
| 2667    | 13        | 13.83%  |
| 2400    | 10        | 10.64%  |
| 3200    | 9         | 9.57%   |
| 1333    | 9         | 9.57%   |
| Unknown | 9         | 9.57%   |
| 667     | 8         | 8.51%   |
| 1867    | 5         | 5.32%   |
| 800     | 4         | 4.26%   |
| 1067    | 3         | 3.19%   |
| 2133    | 2         | 2.13%   |
| 2933    | 1         | 1.06%   |
| 1334    | 1         | 1.06%   |
| 975     | 1         | 1.06%   |
| 266     | 1         | 1.06%   |
| 100     | 1         | 1.06%   |

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
| Chicony Electronics                    | 22        | 27.5%   |
| Realtek Semiconductor                  | 10        | 12.5%   |
| IMC Networks                           | 10        | 12.5%   |
| Acer                                   | 6         | 7.5%    |
| Microdia                               | 5         | 6.25%   |
| Suyin                                  | 4         | 5%      |
| Quanta                                 | 4         | 5%      |
| Lite-On Technology                     | 4         | 5%      |
| Syntek                                 | 3         | 3.75%   |
| ALi                                    | 3         | 3.75%   |
| Silicon Motion                         | 2         | 2.5%    |
| Z-Star Microelectronics                | 1         | 1.25%   |
| Sunplus Innovation Technology          | 1         | 1.25%   |
| ShineTech                              | 1         | 1.25%   |
| Intel                                  | 1         | 1.25%   |
| DigiTech                               | 1         | 1.25%   |
| Denron                                 | 1         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 9.76%   |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 3.66%   |
| Quanta VGA WebCam                                   | 3         | 3.66%   |
| IMC Networks Integrated Camera                      | 3         | 3.66%   |
| Acer Lenovo EasyCamera                              | 3         | 3.66%   |
| Syntek EasyCamera                                   | 2         | 2.44%   |
| Silicon Motion WebCam SCX Series                    | 2         | 2.44%   |
| Realtek Integrated Webcam                           | 2         | 2.44%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.44%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.44%   |
| Microdia Integrated Webcam                          | 2         | 2.44%   |
| Lite-On Integrated Camera                           | 2         | 2.44%   |
| Lite-On HP HD Camera                                | 2         | 2.44%   |
| IMC Networks EasyCamera                             | 2         | 2.44%   |
| ALi Gateway Webcam                                  | 2         | 2.44%   |
| Z-Star Webcam                                       | 1         | 1.22%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.22%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 1.22%   |
| Suyin HP Webcam                                     | 1         | 1.22%   |
| Suyin HD WebCam                                     | 1         | 1.22%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.22%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.22%   |
| ShineTech HD Camera                                 | 1         | 1.22%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.22%   |
| Realtek USB Webcam                                  | 1         | 1.22%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 1.22%   |
| Realtek Integrated_Webcam_8M                        | 1         | 1.22%   |
| Quanta Realtek DMFT - RGB                           | 1         | 1.22%   |
| Microdia Integrated Webcam HD                       | 1         | 1.22%   |
| Intel WiMAX Connection 2400m                        | 1         | 1.22%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.22%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.22%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.22%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.22%   |
| IMC Networks HP TrueVision HD Camera                | 1         | 1.22%   |
| DigiTech WebCam SCB-0350M                           | 1         | 1.22%   |
| Denron Corp., 2M Front Camera                       | 1         | 1.22%   |
| Chicony XiaoMi USB 2.0 Webcam                       | 1         | 1.22%   |
| Chicony USB2.0 0.3M UVC WebCam                      | 1         | 1.22%   |
| Chicony USB 2.0 Camera                              | 1         | 1.22%   |
| Chicony thinkpad t430s camera                       | 1         | 1.22%   |
| Chicony Lenovo Integrated Camera UVC                | 1         | 1.22%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.22%   |
| Chicony Integrated IR Camera                        | 1         | 1.22%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.22%   |
| Chicony Integrated Camera [ThinkPad]                | 1         | 1.22%   |
| Chicony HP Webcam                                   | 1         | 1.22%   |
| Chicony HP HD Webcam [Fixed]                        | 1         | 1.22%   |
| Chicony HD WebCam                                   | 1         | 1.22%   |
| Chicony EasyCamera                                  | 1         | 1.22%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 1.22%   |
| Chicony Asus 720p CMOS webcam                       | 1         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 1.22%   |
| ALi WebCam                                          | 1         | 1.22%   |
| Acer USB2.0 Camera                                  | 1         | 1.22%   |
| Acer SunplusIT Integrated Camera                    | 1         | 1.22%   |
| Acer Lenovo Integrated Webcam                       | 1         | 1.22%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 40.91%  |
| Synaptics                  | 7         | 31.82%  |
| STMicroelectronics         | 2         | 9.09%   |
| Upek                       | 1         | 4.55%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |
| Broadcom                   | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 4         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 9.09%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 4.55%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 4.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 4.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 4.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 4.55%   |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |
| AuthenTec AES1600                                                            | 1         | 4.55%   |

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
| 1     | 35        | 30.43%  |
| 2     | 30        | 26.09%  |
| 4     | 17        | 14.78%  |
| 0     | 15        | 13.04%  |
| 3     | 13        | 11.3%   |
| 9     | 1         | 0.87%   |
| 8     | 1         | 0.87%   |
| 7     | 1         | 0.87%   |
| 6     | 1         | 0.87%   |
| 5     | 1         | 0.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 55        | 28.65%  |
| Net/wireless             | 35        | 18.23%  |
| Card reader              | 26        | 13.54%  |
| Bluetooth                | 23        | 11.98%  |
| Fingerprint reader       | 18        | 9.38%   |
| Firewire controller      | 11        | 5.73%   |
| Sound                    | 7         | 3.65%   |
| Graphics card            | 6         | 3.13%   |
| Storage                  | 4         | 2.08%   |
| Network                  | 3         | 1.56%   |
| Modem                    | 3         | 1.56%   |
| Storage/ata              | 1         | 0.52%   |

