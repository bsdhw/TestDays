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

Total: 204

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Dell          | System Vostro 3750          | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| Dell          | Inspiron 15 3511            | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Dell          | Vostro 5415                 | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Sony          | VGN-UX1XRN                  | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
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
| helloSystem 0.7.0    | 12        | 9.09%   |
| OpenBSD 6.8          | 10        | 7.58%   |
| FreeBSD 13.1         | 8         | 6.06%   |
| NomadBSD 1.3.2       | 7         | 5.3%    |
| FreeBSD 13.0         | 6         | 4.55%   |
| OpenBSD 7.1          | 5         | 3.79%   |
| FreeBSD 14.0-CURRENT | 5         | 3.79%   |
| FreeBSD 13.0-CURRENT | 5         | 3.79%   |
| NomadBSD 5806f915    | 4         | 3.03%   |
| helloSystem 0.8.0    | 4         | 3.03%   |
| helloSystem 0.6.0    | 4         | 3.03%   |
| FreeBSD 12.1-STABLE  | 4         | 3.03%   |
| OpenBSD 6.9          | 3         | 2.27%   |
| GhostBSD 20.04.02    | 3         | 2.27%   |
| FreeBSD 13.1-p1      | 3         | 2.27%   |
| FreeBSD 12.2-p4      | 3         | 2.27%   |
| OpenBSD 6.7          | 2         | 1.52%   |
| FreeBSD 13.0-p3      | 2         | 1.52%   |
| FreeBSD 12.3-STABLE  | 2         | 1.52%   |
| FreeBSD 12.2-STABLE  | 2         | 1.52%   |
| FreeBSD 12.2-p3      | 2         | 1.52%   |
| FreeBSD 12.1-p8      | 2         | 1.52%   |
| FreeBSD 12.1-p7      | 2         | 1.52%   |
| FreeBSD 12.1-p5      | 2         | 1.52%   |
| OS108 9.0            | 1         | 0.76%   |
| OpenBSD 7.0          | 1         | 0.76%   |
| NomadBSD 1.4         | 1         | 0.76%   |
| NomadBSD 1.3.1       | 1         | 0.76%   |
| NetBSD 9.99.94       | 1         | 0.76%   |
| NetBSD 9.1           | 1         | 0.76%   |
| NetBSD 7.2           | 1         | 0.76%   |
| LibertyBSD 6.1       | 1         | 0.76%   |
| helloSystem 0.3.0    | 1         | 0.76%   |
| GhostBSD 21.08.27    | 1         | 0.76%   |
| FreeBSD 8.4          | 1         | 0.76%   |
| FreeBSD 13.1-STABLE  | 1         | 0.76%   |
| FreeBSD 13.1-p2      | 1         | 0.76%   |
| FreeBSD 13.1-BETA3   | 1         | 0.76%   |
| FreeBSD 13.0-STABLE  | 1         | 0.76%   |
| FreeBSD 13.0-RC1     | 1         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 62        | 50.41%  |
| OpenBSD     | 20        | 16.26%  |
| helloSystem | 20        | 16.26%  |
| NomadBSD    | 12        | 9.76%   |
| GhostBSD    | 4         | 3.25%   |
| NetBSD      | 3         | 2.44%   |
| OS108       | 1         | 0.81%   |
| LibertyBSD  | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 102       | 87.93%  |
| i386  | 14        | 12.07%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 24        | 19.51%  |
| Console       | 15        | 12.2%   |
| XFCE          | 14        | 11.38%  |
| Openbox       | 13        | 10.57%  |
| fvwm          | 13        | 10.57%  |
| KDE5          | 12        | 9.76%   |
| MATE          | 6         | 4.88%   |
| GNOME         | 6         | 4.88%   |
| TWM           | 5         | 4.07%   |
| i3            | 3         | 2.44%   |
| LXQt          | 2         | 1.63%   |
| LXDE          | 2         | 1.63%   |
| IceWM         | 2         | 1.63%   |
| AwesomeWM     | 2         | 1.63%   |
| StumpWM       | 1         | 0.81%   |
| Lumina        | 1         | 0.81%   |
| Enlightenment | 1         | 0.81%   |
| DWM           | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 101       | 83.47%  |
| Console | 18        | 14.88%  |
| Wayland | 2         | 1.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 49        | 40.5%   |
| SLiM    | 44        | 36.36%  |
| SDDM    | 10        | 8.26%   |
| LightDM | 7         | 5.79%   |
| XDM     | 6         | 4.96%   |
| GDM     | 3         | 2.48%   |
| PCDM    | 1         | 0.83%   |
| Ly      | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 37        | 30.58%  |
| en_US   | 34        | 28.1%   |
| Unknown | 29        | 23.97%  |
| C       | 19        | 15.7%   |
| en_GB   | 1         | 0.83%   |
| en_EN   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 64.17%  |
| BIOS | 43        | 35.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Ufs    | 48        | 39.34%  |
| Zfs    | 44        | 36.07%  |
| Ffs    | 21        | 17.21%  |
| Cd9660 | 8         | 6.56%   |
| Xfs    | 1         | 0.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 87        | 73.73%  |
| MBR     | 28        | 23.73%  |
| Unknown | 2         | 1.69%   |
| BSD     | 1         | 0.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 35        | 30.17%  |
| Dell                | 17        | 14.66%  |
| Hewlett-Packard     | 14        | 12.07%  |
| ASUSTek Computer    | 12        | 10.34%  |
| Acer                | 12        | 10.34%  |
| Sony                | 6         | 5.17%   |
| Samsung Electronics | 4         | 3.45%   |
| Toshiba             | 2         | 1.72%   |
| IBM                 | 2         | 1.72%   |
| Apple               | 2         | 1.72%   |
| Timi                | 1         | 0.86%   |
| Panasonic           | 1         | 0.86%   |
| Packard Bell        | 1         | 0.86%   |
| MSI                 | 1         | 0.86%   |
| Kraftway            | 1         | 0.86%   |
| HUAWEI              | 1         | 0.86%   |
| Google              | 1         | 0.86%   |
| eMachines           | 1         | 0.86%   |
| DNS                 | 1         | 0.86%   |
| DEXP                | 1         | 0.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N145P/N250P/N260P                | 2         | 1.72%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 2         | 1.72%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 1.72%   |
| Acer Aspire 4820T                        | 2         | 1.72%   |
| Toshiba Satellite M100                   | 1         | 0.86%   |
| Toshiba Satellite A300                   | 1         | 0.86%   |
| Timi TM1612                              | 1         | 0.86%   |
| Sony VPCX115KX                           | 1         | 0.86%   |
| Sony VPCM13M1R                           | 1         | 0.86%   |
| Sony VGN-UX1XRN                          | 1         | 0.86%   |
| Sony VGN-S150(UC)                        | 1         | 0.86%   |
| Sony SVP1321V9RB                         | 1         | 0.86%   |
| Sony SVE1713S1RW                         | 1         | 0.86%   |
| Samsung R530/R730/R540                   | 1         | 0.86%   |
| Samsung N150P                            | 1         | 0.86%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.86%   |
| Packard Bell EasyNote TE69HW             | 1         | 0.86%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.86%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.86%   |
| Lenovo V580 20147                        | 1         | 0.86%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V      | 1         | 0.86%   |
| Lenovo ThinkPad X240 20AMA52RUK          | 1         | 0.86%   |
| Lenovo ThinkPad X240 20AL00DKRT          | 1         | 0.86%   |
| Lenovo ThinkPad X230 2325Y36             | 1         | 0.86%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT     | 1         | 0.86%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT     | 1         | 0.86%   |
| Lenovo ThinkPad X121e 3053A52            | 1         | 0.86%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES42E0L | 1         | 0.86%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 0.86%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DW00 | 1         | 0.86%   |
| Lenovo ThinkPad T495s 20QKS1812F         | 1         | 0.86%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 0.86%   |
| Lenovo ThinkPad T480s 20L7001HRT         | 1         | 0.86%   |
| Lenovo ThinkPad T430 23511A6             | 1         | 0.86%   |
| Lenovo ThinkPad T420 4178A72             | 1         | 0.86%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT     | 1         | 0.86%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.86%   |
| Lenovo ThinkPad E480 20KN005CRT          | 1         | 0.86%   |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT     | 1         | 0.86%   |
| Lenovo ThinkBook 14 G2 ARE 20VF          | 1         | 0.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 19        | 16.38%  |
| Acer Aspire            | 10        | 8.62%   |
| Lenovo IdeaPad         | 9         | 7.76%   |
| Dell Inspiron          | 7         | 6.03%   |
| Dell Latitude          | 6         | 5.17%   |
| HP ProBook             | 5         | 4.31%   |
| HP Laptop              | 3         | 2.59%   |
| ASUS VivoBook          | 3         | 2.59%   |
| Toshiba Satellite      | 2         | 1.72%   |
| Samsung N145P          | 2         | 1.72%   |
| IBM ThinkPad           | 2         | 1.72%   |
| Acer Extensa           | 2         | 1.72%   |
| Timi TM1612            | 1         | 0.86%   |
| Sony VPCX115KX         | 1         | 0.86%   |
| Sony VPCM13M1R         | 1         | 0.86%   |
| Sony VGN-UX1XRN        | 1         | 0.86%   |
| Sony VGN-S150(UC)      | 1         | 0.86%   |
| Sony SVP1321V9RB       | 1         | 0.86%   |
| Sony SVE1713S1RW       | 1         | 0.86%   |
| Samsung R530           | 1         | 0.86%   |
| Samsung N150P          | 1         | 0.86%   |
| Panasonic CF-19AHNC8FN | 1         | 0.86%   |
| Packard Bell EasyNote  | 1         | 0.86%   |
| MSI GE75               | 1         | 0.86%   |
| Lenovo Yoga            | 1         | 0.86%   |
| Lenovo V580            | 1         | 0.86%   |
| Lenovo ThinkBook       | 1         | 0.86%   |
| Lenovo S20-30          | 1         | 0.86%   |
| Lenovo G570            | 1         | 0.86%   |
| Lenovo E31-80          | 1         | 0.86%   |
| Lenovo B50-30          | 1         | 0.86%   |
| Kraftway KW10T         | 1         | 0.86%   |
| HUAWEI CREM-WXX9       | 1         | 0.86%   |
| HP Pavilion            | 1         | 0.86%   |
| HP OmniBook            | 1         | 0.86%   |
| HP EliteBook           | 1         | 0.86%   |
| HP Compaq              | 1         | 0.86%   |
| HP 255                 | 1         | 0.86%   |
| HP 250                 | 1         | 0.86%   |
| Google Chell           | 1         | 0.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 16        | 13.79%  |
| 2020 | 14        | 12.07%  |
| 2011 | 12        | 10.34%  |
| 2018 | 10        | 8.62%   |
| 2021 | 8         | 6.9%    |
| 2012 | 8         | 6.9%    |
| 2008 | 6         | 5.17%   |
| 2017 | 5         | 4.31%   |
| 2015 | 5         | 4.31%   |
| 2009 | 5         | 4.31%   |
| 2016 | 4         | 3.45%   |
| 2014 | 4         | 3.45%   |
| 2013 | 4         | 3.45%   |
| 2010 | 4         | 3.45%   |
| 2022 | 2         | 1.72%   |
| 2007 | 2         | 1.72%   |
| 2006 | 2         | 1.72%   |
| 2005 | 2         | 1.72%   |
| 2004 | 2         | 1.72%   |
| 2003 | 1         | 0.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 116       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 99.14%  |
| Yes  | 1         | 0.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 36        | 30.51%  |
| 4.01-8.0    | 32        | 27.12%  |
| 16.01-24.0  | 22        | 18.64%  |
| 2.01-3.0    | 9         | 7.63%   |
| 0.51-1.0    | 5         | 4.24%   |
| 1.01-2.0    | 4         | 3.39%   |
| 24.01-32.0  | 3         | 2.54%   |
| 0.01-0.5    | 3         | 2.54%   |
| 3.01-4.0    | 2         | 1.69%   |
| 32.01-64.0  | 1         | 0.85%   |
| 64.01-256.0 | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 67        | 54.92%  |
| 0.51-1.0   | 31        | 25.41%  |
| 2.01-3.0   | 7         | 5.74%   |
| Unknown    | 5         | 4.1%    |
| 1.01-2.0   | 4         | 3.28%   |
| 0          | 4         | 3.28%   |
| 4.01-8.0   | 2         | 1.64%   |
| 24.01-32.0 | 1         | 0.82%   |
| 8.01-16.0  | 1         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 67.77%  |
| 2      | 28        | 23.14%  |
| 0      | 6         | 4.96%   |
| 4      | 3         | 2.48%   |
| 3      | 2         | 1.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 79.31%  |
| Yes       | 24        | 20.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 85.34%  |
| No        | 17        | 14.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 97.41%  |
| No        | 3         | 2.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 66.67%  |
| No        | 39        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 116       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 37        | 31.36%  |
| St Petersburg    | 15        | 12.71%  |
| Vladivostok      | 6         | 5.08%   |
| Yekaterinburg    | 4         | 3.39%   |
| Novosibirsk      | 4         | 3.39%   |
| Ulyanovsk        | 3         | 2.54%   |
| Ufa              | 3         | 2.54%   |
| Tyumen           | 3         | 2.54%   |
| Krasnoyarsk      | 3         | 2.54%   |
| Chelyabinsk      | 3         | 2.54%   |
| Tolyatti         | 2         | 1.69%   |
| Kirov            | 2         | 1.69%   |
| Zhukovskiy       | 1         | 0.85%   |
| Yoshkar-Ola      | 1         | 0.85%   |
| Yegorlykskaya    | 1         | 0.85%   |
| Yaroslavl        | 1         | 0.85%   |
| Vorkuta          | 1         | 0.85%   |
| Vladimir         | 1         | 0.85%   |
| Ust'-Luga        | 1         | 0.85%   |
| Tsarskoye Selo   | 1         | 0.85%   |
| Surgut           | 1         | 0.85%   |
| Smolensk         | 1         | 0.85%   |
| Sevastopol'      | 1         | 0.85%   |
| Rostov-on-Don    | 1         | 0.85%   |
| Pushkino         | 1         | 0.85%   |
| Perm             | 1         | 0.85%   |
| Penza            | 1         | 0.85%   |
| Ozersk           | 1         | 0.85%   |
| Oryol            | 1         | 0.85%   |
| Obninsk          | 1         | 0.85%   |
| Nizhniy Novgorod | 1         | 0.85%   |
| Michurinsk       | 1         | 0.85%   |
| Kstovo           | 1         | 0.85%   |
| Krasnokamsk      | 1         | 0.85%   |
| Krasnodar        | 1         | 0.85%   |
| Korolyov         | 1         | 0.85%   |
| Kislovodsk       | 1         | 0.85%   |
| Khabarovsk       | 1         | 0.85%   |
| Kez              | 1         | 0.85%   |
| Kaliningrad      | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 31     | 18.84%  |
| Seagate             | 16        | 19     | 11.59%  |
| Samsung Electronics | 14        | 17     | 10.14%  |
| Toshiba             | 11        | 12     | 7.97%   |
| SanDisk             | 9         | 11     | 6.52%   |
| SK hynix            | 8         | 9      | 5.8%    |
| Hitachi             | 8         | 10     | 5.8%    |
| Kingston            | 6         | 7      | 4.35%   |
| Intel               | 6         | 8      | 4.35%   |
| HGST                | 5         | 6      | 3.62%   |
| SPCC                | 4         | 5      | 2.9%    |
| Transcend           | 3         | 3      | 2.17%   |
| Micron Technology   | 3         | 3      | 2.17%   |
| NVMe                | 2         | 2      | 1.45%   |
| Innostor            | 2         | 2      | 1.45%   |
| Gigabyte Technology | 2         | 5      | 1.45%   |
| USB                 | 1         | 1      | 0.72%   |
| UFD 2.0             | 1         | 1      | 0.72%   |
| Silicon Motion      | 1         | 1      | 0.72%   |
| OCZ                 | 1         | 2      | 0.72%   |
| Netac               | 1         | 1      | 0.72%   |
| KLLISRE             | 1         | 1      | 0.72%   |
| KIOXIA              | 1         | 1      | 0.72%   |
| Hewlett-Packard     | 1         | 1      | 0.72%   |
| FORESEE             | 1         | 2      | 0.72%   |
| Apple               | 1         | 1      | 0.72%   |
| Apacer              | 1         | 1      | 0.72%   |
| AMD                 | 1         | 1      | 0.72%   |
| A-DATA Technology   | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 3         | 2.07%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 2.07%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 2.07%   |
| Kingston SV300S37A120G 120GB         | 3         | 2.07%   |
| HGST HTS721010A9E630 1TB             | 3         | 2.07%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.38%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 1.38%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 1.38%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.38%   |
| Seagate ST9500325AS 500GB            | 2         | 1.38%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.38%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.38%   |
| Micron 1100 SATA 256GB               | 2         | 1.38%   |
| Innostor SSD 15GB                    | 2         | 1.38%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.69%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.69%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.69%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.69%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.69%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.69%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.69%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.69%   |
| WDC WD20SPZX-00UA7T0 2TB             | 1         | 0.69%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.69%   |
| WDC WD2000JB-00GVC0 200GB            | 1         | 0.69%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.69%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.69%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.69%   |
| WDC WD10JPVX-08JC3T5 1TB             | 1         | 0.69%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.69%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.69%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 0.69%   |
| WDC PC SN730 SDBPNTY-512G            | 1         | 0.69%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB | 1         | 0.69%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.69%   |
| USB SanDisk 3.2Gen1 64GB             | 1         | 0.69%   |
| UFD 2.0 Silicon-Power16G 18302PB     | 1         | 0.69%   |
| Transcend TS256GMTS400 256GB         | 1         | 0.69%   |
| Transcend TS240GMTS420S 240GB        | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 26.67%  |
| Seagate             | 16        | 19     | 26.67%  |
| Toshiba             | 10        | 11     | 16.67%  |
| Hitachi             | 8         | 10     | 13.33%  |
| HGST                | 5         | 6      | 8.33%   |
| NVMe                | 2         | 2      | 3.33%   |
| USB                 | 1         | 1      | 1.67%   |
| UFD 2.0             | 1         | 1      | 1.67%   |
| Samsung Electronics | 1         | 1      | 1.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 9         | 11     | 17.31%  |
| Samsung Electronics | 8         | 9      | 15.38%  |
| Kingston            | 5         | 6      | 9.62%   |
| WDC                 | 4         | 5      | 7.69%   |
| SPCC                | 4         | 5      | 7.69%   |
| Intel               | 4         | 6      | 7.69%   |
| Micron Technology   | 3         | 3      | 5.77%   |
| Transcend           | 2         | 2      | 3.85%   |
| Innostor            | 2         | 2      | 3.85%   |
| SK hynix            | 1         | 1      | 1.92%   |
| OCZ                 | 1         | 2      | 1.92%   |
| Netac               | 1         | 1      | 1.92%   |
| KLLISRE             | 1         | 1      | 1.92%   |
| Hewlett-Packard     | 1         | 1      | 1.92%   |
| Gigabyte Technology | 1         | 3      | 1.92%   |
| FORESEE             | 1         | 2      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |
| Apacer              | 1         | 1      | 1.92%   |
| AMD                 | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 68     | 42.86%  |
| SSD  | 46        | 64     | 36.51%  |
| NVMe | 26        | 33     | 20.63%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 132    | 77.39%  |
| NVMe | 26        | 33     | 22.61%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 73        | 104    | 73.74%  |
| 0.51-1.0        | 22        | 24     | 22.22%  |
| 1.01-2.0        | 3         | 3      | 3.03%   |
| More than 100.0 | 1         | 1      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 35        | 27.78%  |
| 1-20       | 28        | 22.22%  |
| 251-500    | 24        | 19.05%  |
| 21-50      | 12        | 9.52%   |
| 501-1000   | 12        | 9.52%   |
| 51-100     | 10        | 7.94%   |
| 1001-2000  | 3         | 2.38%   |
| Unknown    | 2         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 84        | 70%     |
| 21-50   | 15        | 12.5%   |
| 101-250 | 11        | 9.17%   |
| 51-100  | 6         | 5%      |
| 251-500 | 2         | 1.67%   |
| Unknown | 2         | 1.67%   |

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
| Works    | 89        | 130    | 71.77%  |
| Malfunc  | 30        | 30     | 24.19%  |
| Detected | 4         | 4      | 3.23%   |
| Failed   | 1         | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 80        | 61.54%  |
| AMD                              | 20        | 15.38%  |
| SK hynix                         | 8         | 6.15%   |
| SanDisk                          | 6         | 4.62%   |
| Samsung Electronics              | 6         | 4.62%   |
| Toshiba                          | 1         | 0.77%   |
| Silicon Motion                   | 1         | 0.77%   |
| Silicon Integrated Systems [SiS] | 1         | 0.77%   |
| Phison Electronics               | 1         | 0.77%   |
| Nvidia                           | 1         | 0.77%   |
| Marvell Technology Group         | 1         | 0.77%   |
| KIOXIA                           | 1         | 0.77%   |
| Kingston Technology Company      | 1         | 0.77%   |
| JMicron Technology               | 1         | 0.77%   |
| Unknown                          | 1         | 0.77%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 12.41%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 8.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 5.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5.11%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 3.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 3.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.65%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 2.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 2.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 2.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.19%   |
| Unknown                                                                          | 3         | 2.19%   |
| SK hynix BC511                                                                   | 2         | 1.46%   |
| SanDisk PC SN530                                                                 | 2         | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.46%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 1.46%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.46%   |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 1.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.46%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.73%   |
| SK hynix hynix unknown                                                           | 1         | 0.73%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.73%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.73%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.73%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.73%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.73%   |
| JMicron JMB360 AHCI Controller                                                   | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 88        | 66.17%  |
| NVMe | 27        | 20.3%   |
| IDE  | 16        | 12.03%  |
| RAID | 2         | 1.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 78.45%  |
| AMD    | 25        | 21.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 5         | 4.24%   |
| Intel CPU Version                                                   | 3         | 2.54%   |
| Intel C1                                                            | 3         | 2.54%   |
| Intel Pentium M processor 1.60GHz                                   | 2         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 2         | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 2         | 1.69%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 1.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 2         | 1.69%   |
| Intel Core i5-2430M CPU @ 2.40GHz                                   | 2         | 1.69%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                                   | 2         | 1.69%   |
| Intel Core 2 Duo                                                    | 2         | 1.69%   |
| Intel 686-class                                                     | 2         | 1.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics                              | 2         | 1.69%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 2         | 1.69%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                       | 2         | 1.69%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                       | 2         | 1.69%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                                   | 1         | 0.85%   |
| Intel Pentium Silver N6000 @ 1.10GHz                                | 1         | 0.85%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 0.85%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 0.85%   |
| Intel Pentium M processor                                           | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 0.85%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 1         | 0.85%   |
| Intel Pentium CPU N3700 @ 1.60GHz                                   | 1         | 0.85%   |
| Intel Pentium CPU N3530 @ 2.16GHz                                   | 1         | 0.85%   |
| Intel Pentium CPU 4417U @ 2.30GHz                                   | 1         | 0.85%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 0.85%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 0.85%   |
| Intel Genuine CPU U7300 @ 1.30GHz                                   | 1         | 0.85%   |
| Intel Genuine CPU T2                                                | 1         | 0.85%   |
| Intel Genuine CPU                                                   | 1         | 0.85%   |
| Intel Core Solo CPU U1500 @ 1.33GHz                                 | 1         | 0.85%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                                    | 1         | 0.85%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                                    | 1         | 0.85%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                                     | 1         | 0.85%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                                 | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz                                   | 1         | 0.85%   |
| Intel Core i7-8665U CPU @ 1.90GHz                                   | 1         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                                  | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 17.8%   |
| Intel Core i7           | 15        | 12.71%  |
| Intel Core i3           | 11        | 9.32%   |
| Other                   | 9         | 7.63%   |
| AMD Ryzen 3             | 7         | 5.93%   |
| Intel Core 2 Duo        | 6         | 5.08%   |
| Intel Atom              | 5         | 4.24%   |
| AMD Ryzen 7             | 5         | 4.24%   |
| Intel Pentium M         | 4         | 3.39%   |
| Intel Pentium           | 4         | 3.39%   |
| Intel Celeron           | 4         | 3.39%   |
| Intel Genuine           | 3         | 2.54%   |
| AMD Ryzen 5             | 3         | 2.54%   |
| AMD E                   | 3         | 2.54%   |
| Intel Pentium Silver    | 2         | 1.69%   |
| Intel 686-class         | 2         | 1.69%   |
| AMD Ryzen 7 PRO         | 2         | 1.69%   |
| AMD A6                  | 2         | 1.69%   |
| Intel Xeon              | 1         | 0.85%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Core Solo         | 1         | 0.85%   |
| Intel Core m5           | 1         | 0.85%   |
| Intel Core m3           | 1         | 0.85%   |
| Intel Core M            | 1         | 0.85%   |
| Intel Core i9           | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD E1                  | 1         | 0.85%   |
| AMD A10                 | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 50        | 42.02%  |
| 4       | 30        | 25.21%  |
| Unknown | 15        | 12.61%  |
| 1       | 10        | 8.4%    |
| 8       | 8         | 6.72%   |
| 16      | 3         | 2.52%   |
| 6       | 2         | 1.68%   |
| 12      | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 110       | 92.44%  |
| Unknown | 9         | 7.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 57        | 47.9%   |
| 1       | 41        | 34.45%  |
| Unknown | 21        | 17.65%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 14.53%  |
| Skylake       | 9         | 7.69%   |
| SandyBridge   | 8         | 6.84%   |
| Penryn        | 8         | 6.84%   |
| P6            | 8         | 6.84%   |
| IvyBridge     | 7         | 5.98%   |
| Bonnell       | 7         | 5.98%   |
| Haswell       | 6         | 5.13%   |
| Zen+          | 5         | 4.27%   |
| Zen 2         | 5         | 4.27%   |
| Silvermont    | 5         | 4.27%   |
| Zen 3         | 3         | 2.56%   |
| Zen           | 3         | 2.56%   |
| Westmere      | 3         | 2.56%   |
| Core          | 3         | 2.56%   |
| Unknown       | 3         | 2.56%   |
| Goldmont      | 2         | 1.71%   |
| Excavator     | 2         | 1.71%   |
| CometLake     | 2         | 1.71%   |
| Broadwell     | 2         | 1.71%   |
| Bobcat        | 2         | 1.71%   |
| TigerLake     | 1         | 0.85%   |
| Puma          | 1         | 0.85%   |
| Piledriver    | 1         | 0.85%   |
| K8 Hammer     | 1         | 0.85%   |
| Jaguar        | 1         | 0.85%   |
| IceLake       | 1         | 0.85%   |
| Goldmont plus | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 57.25%  |
| AMD    | 38        | 27.54%  |
| Nvidia | 20        | 14.49%  |
| ATI    | 1         | 0.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 4.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.55%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 3.55%   |
| AMD Renoir                                                                               | 5         | 3.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.84%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.13%   |
| Intel HD Graphics 630                                                                    | 3         | 2.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 2.13%   |
| AMD Cezanne                                                                              | 3         | 2.13%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.42%   |
| Intel HD Graphics 620                                                                    | 2         | 1.42%   |
| Intel HD Graphics 520                                                                    | 2         | 1.42%   |
| Intel HD Graphics 515                                                                    | 2         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.42%   |
| Nvidia TU117M                                                                            | 1         | 0.71%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.71%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.71%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.71%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.71%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.71%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.71%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.71%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 0.71%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.71%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 42.74%  |
| 1 x AMD        | 32        | 27.35%  |
| Intel + Nvidia | 14        | 11.97%  |
| 2 x Intel      | 11        | 9.4%    |
| 1 x Nvidia     | 4         | 3.42%   |
| Intel + AMD    | 4         | 3.42%   |
| AMD + Nvidia   | 2         | 1.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 105       | 88.98%  |
| Proprietary | 7         | 5.93%   |
| Unknown     | 6         | 5.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 79.17%  |
| 0.01-0.5   | 14        | 11.67%  |
| 1.01-2.0   | 6         | 5%      |
| 0.51-1.0   | 3         | 2.5%    |
| 3.01-4.0   | 1         | 0.83%   |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 24.21%  |
| LG Display              | 16        | 16.84%  |
| BOE                     | 11        | 11.58%  |
| Samsung Electronics     | 10        | 10.53%  |
| Chimei Innolux          | 8         | 8.42%   |
| InfoVision              | 4         | 4.21%   |
| LG Philips              | 3         | 3.16%   |
| Chi Mei Optoelectronics | 3         | 3.16%   |
| ViewSonic               | 2         | 2.11%   |
| PANDA                   | 2         | 2.11%   |
| Lenovo                  | 2         | 2.11%   |
| Acer                    | 2         | 2.11%   |
| Toshiba                 | 1         | 1.05%   |
| Panasonic               | 1         | 1.05%   |
| NEC Computers           | 1         | 1.05%   |
| HannStar                | 1         | 1.05%   |
| Goldstar                | 1         | 1.05%   |
| CSO                     | 1         | 1.05%   |
| CPT                     | 1         | 1.05%   |
| Apple                   | 1         | 1.05%   |
| Ancor Communications    | 1         | 1.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 2.11%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 2.11%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 2.11%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 2.11%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 1.05%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 1.05%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 1.05%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 1.05%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 1.05%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 1.05%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 1.05%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 1.05%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 1.05%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD06FF 1920x1080 340x190mm 15.3-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD05EE 2560x1440 310x170mm 13.9-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.05%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.05%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 1.05%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 1.05%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 1         | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 39        | 41.05%  |
| 1366x768 (WXGA)   | 26        | 27.37%  |
| 1280x800 (WXGA)   | 6         | 6.32%   |
| 1600x900 (HD+)    | 4         | 4.21%   |
| 1024x600          | 4         | 4.21%   |
| 2560x1440 (QHD)   | 3         | 3.16%   |
| 1440x900 (WXGA+)  | 3         | 3.16%   |
| 3840x2160 (4K)    | 2         | 2.11%   |
| 1280x1024 (SXGA)  | 2         | 2.11%   |
| 3200x1800 (QHD+)  | 1         | 1.05%   |
| 2880x1620         | 1         | 1.05%   |
| 2560x1080         | 1         | 1.05%   |
| 2240x1400         | 1         | 1.05%   |
| 1920x540          | 1         | 1.05%   |
| 1920x1200 (WUXGA) | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 39        | 41.05%  |
| 13     | 25        | 26.32%  |
| 17     | 6         | 6.32%   |
| 11     | 5         | 5.26%   |
| 10     | 5         | 5.26%   |
| 14     | 4         | 4.21%   |
| 12     | 3         | 3.16%   |
| 21     | 2         | 2.11%   |
| 54     | 1         | 1.05%   |
| 34     | 1         | 1.05%   |
| 31     | 1         | 1.05%   |
| 27     | 1         | 1.05%   |
| 23     | 1         | 1.05%   |
| 19     | 1         | 1.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 61.05%  |
| 201-300     | 24        | 25.26%  |
| 351-400     | 6         | 6.32%   |
| 501-600     | 2         | 2.11%   |
| 401-500     | 2         | 2.11%   |
| 701-800     | 1         | 1.05%   |
| 601-700     | 1         | 1.05%   |
| 1001-1500   | 1         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 74        | 83.15%  |
| 16/10 | 12        | 13.48%  |
| 5/4   | 2         | 2.25%   |
| 21/9  | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 32        | 33.68%  |
| 81-90          | 23        | 24.21%  |
| 101-110        | 7         | 7.37%   |
| 71-80          | 6         | 6.32%   |
| 51-60          | 5         | 5.26%   |
| 41-50          | 5         | 5.26%   |
| 61-70          | 3         | 3.16%   |
| 201-250        | 3         | 3.16%   |
| 131-140        | 3         | 3.16%   |
| 351-500        | 2         | 2.11%   |
| 121-130        | 2         | 2.11%   |
| More than 1000 | 1         | 1.05%   |
| 301-350        | 1         | 1.05%   |
| 151-200        | 1         | 1.05%   |
| 141-150        | 1         | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 42.11%  |
| 101-120       | 28        | 29.47%  |
| 51-100        | 14        | 14.74%  |
| 161-240       | 11        | 11.58%  |
| More than 240 | 2         | 2.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 89        | 71.77%  |
| 0     | 26        | 20.97%  |
| 2     | 9         | 7.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 63        | 30.88%  |
| Realtek Semiconductor             | 55        | 26.96%  |
| Qualcomm Atheros                  | 34        | 16.67%  |
| Broadcom                          | 13        | 6.37%   |
| Marvell Technology Group          | 9         | 4.41%   |
| TP-Link                           | 4         | 1.96%   |
| Ralink Technology                 | 4         | 1.96%   |
| Samsung Electronics               | 2         | 0.98%   |
| Ralink                            | 2         | 0.98%   |
| Fibocom                           | 2         | 0.98%   |
| Ericsson Business Mobile Networks | 2         | 0.98%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.49%   |
| Realtek                           | 1         | 0.49%   |
| Nvidia                            | 1         | 0.49%   |
| Mercucys                          | 1         | 0.49%   |
| MediaTek                          | 1         | 0.49%   |
| JMicron Technology                | 1         | 0.49%   |
| Huawei Technologies               | 1         | 0.49%   |
| Dell                              | 1         | 0.49%   |
| D-Link                            | 1         | 0.49%   |
| BUFFALO                           | 1         | 0.49%   |
| Attansic                          | 1         | 0.49%   |
| Atheros                           | 1         | 0.49%   |
| Arduino SA                        | 1         | 0.49%   |
| 3Com                              | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 38        | 15.38%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 11        | 4.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 8         | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 7         | 2.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 6         | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 6         | 2.43%   |
| Intel Wireless 8265 / 8275                                                  | 6         | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 5         | 2.02%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 5         | 2.02%   |
| Intel Wireless 7265                                                         | 5         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 1.62%   |
| Intel Wi-Fi 6 AX200                                                         | 4         | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 1.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 4         | 1.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 3         | 1.21%   |
| Intel Wireless 8260                                                         | 3         | 1.21%   |
| Intel Wireless 3165                                                         | 3         | 1.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 3         | 1.21%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                  | 2         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 2         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 0.81%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 2         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 2         | 0.81%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                               | 2         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 2         | 0.81%   |
| Intel Wireless-AC 9260                                                      | 2         | 0.81%   |
| Intel Wireless 7260                                                         | 2         | 0.81%   |
| Intel WiFi Link 5100                                                        | 2         | 0.81%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.81%   |
| Intel Ethernet Connection I219-LM                                           | 2         | 0.81%   |
| Intel Ethernet Connection I218-LM                                           | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                                        | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 2         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 2         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 2         | 0.81%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                           | 2         | 0.81%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 45.04%  |
| Qualcomm Atheros      | 29        | 22.14%  |
| Realtek Semiconductor | 20        | 15.27%  |
| Broadcom              | 8         | 6.11%   |
| TP-Link               | 4         | 3.05%   |
| Ralink Technology     | 4         | 3.05%   |
| Ralink                | 2         | 1.53%   |
| Mercucys              | 1         | 0.76%   |
| MediaTek              | 1         | 0.76%   |
| D-Link                | 1         | 0.76%   |
| BUFFALO               | 1         | 0.76%   |
| Atheros               | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 11        | 8.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 6         | 4.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 4.44%   |
| Intel Wireless 8265 / 8275                                          | 6         | 4.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5         | 3.7%    |
| Intel Wireless 7265                                                 | 5         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 4         | 2.96%   |
| Intel Wi-Fi 6 AX200                                                 | 4         | 2.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 4         | 2.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4         | 2.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 3         | 2.22%   |
| Intel Wireless 8260                                                 | 3         | 2.22%   |
| Intel Wireless 3165                                                 | 3         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 3         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 3         | 2.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 2         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.48%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 2         | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 2         | 1.48%   |
| Realtek Realtek Bluetooth 4.2 Adapter                               | 2         | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 1.48%   |
| Intel Wireless-AC 9260                                              | 2         | 1.48%   |
| Intel Wireless 7260                                                 | 2         | 1.48%   |
| Intel WiFi Link 5100                                                | 2         | 1.48%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection           | 2         | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 2         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2         | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 1.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1         | 0.74%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1         | 0.74%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                     | 1         | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1         | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1         | 0.74%   |
| Ralink RT3572 Wireless Adapter                                      | 1         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 0.74%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1         | 0.74%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                           | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 47        | 46.08%  |
| Intel                            | 22        | 21.57%  |
| Qualcomm Atheros                 | 10        | 9.8%    |
| Marvell Technology Group         | 9         | 8.82%   |
| Broadcom                         | 6         | 5.88%   |
| Samsung Electronics              | 2         | 1.96%   |
| Silicon Integrated Systems [SiS] | 1         | 0.98%   |
| Realtek                          | 1         | 0.98%   |
| Nvidia                           | 1         | 0.98%   |
| JMicron Technology               | 1         | 0.98%   |
| Attansic                         | 1         | 0.98%   |
| 3Com                             | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 37.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 6.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 4.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.96%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.96%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.96%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.96%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.96%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 1.96%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.98%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.98%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.98%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.98%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.98%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.98%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.98%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.98%   |
| Intel PRO/100 VM Network Connection                               | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.98%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.98%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 0.98%   |
| Intel 82801CAM (ICH3) PRO/100 VM (KM) Ethernet Controller         | 1         | 0.98%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.98%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.98%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.98%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.98%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 50.9%   |
| Ethernet | 99        | 44.59%  |
| Modem    | 5         | 2.25%   |
| Unknown  | 5         | 2.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 51.3%   |
| Ethernet | 73        | 47.4%   |
| Unknown  | 2         | 1.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 95        | 81.9%   |
| 1     | 21        | 18.1%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 97.44%  |
| Yes  | 3         | 2.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 46.84%  |
| Realtek Semiconductor           | 8         | 10.13%  |
| Qualcomm Atheros Communications | 8         | 10.13%  |
| Broadcom                        | 5         | 6.33%   |
| Lite-On Technology              | 3         | 3.8%    |
| IMC Networks                    | 3         | 3.8%    |
| ASUSTek Computer                | 3         | 3.8%    |
| Alps Electric                   | 3         | 3.8%    |
| Hewlett-Packard                 | 2         | 2.53%   |
| Foxconn / Hon Hai               | 2         | 2.53%   |
| Apple                           | 2         | 2.53%   |
| Realtek                         | 1         | 1.27%   |
| Ralink                          | 1         | 1.27%   |
| Dell                            | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 21.52%  |
| Intel AX201 Bluetooth                                       | 5         | 6.33%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 5.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 5.06%   |
| Intel AX200 Bluetooth                                       | 4         | 5.06%   |
| Realtek  Bluetooth Adapter                                  | 3         | 3.8%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 3.8%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 3.8%    |
| Realtek RTL8723B Bluetooth                                  | 2         | 2.53%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 2.53%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.53%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 2.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.53%   |
| Realtek Bluetooth Radio                                     | 1         | 1.27%   |
| Realtek Bluetooth Radio                                     | 1         | 1.27%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.27%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.27%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.27%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.27%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.27%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 1.27%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.27%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.27%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.27%   |
| Broadcom Broadcom Bluetooth 4.0                             | 1         | 1.27%   |
| Broadcom BCM43142A0 Bluetooth Module                        | 1         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.27%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.27%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.27%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.27%   |
| Apple Bluetooth Host Controller                             | 1         | 1.27%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.27%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.27%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 1.27%   |
| Alps Electric BCM2046 Bluetooth Device                      | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 88        | 69.29%  |
| AMD                              | 28        | 22.05%  |
| Nvidia                           | 5         | 3.94%   |
| Lenovo                           | 2         | 1.57%   |
| Texas Instruments                | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |
| ESS Technology                   | 1         | 0.79%   |
| Creative Technology              | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 10.76%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 10.13%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 5.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 5.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.8%    |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.53%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.9%    |
| AMD FCH Azalia Controller                                                                         | 3         | 1.9%    |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 1.27%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.27%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.27%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.27%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.27%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.27%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.63%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.63%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 22.58%  |
| SK hynix            | 25        | 20.16%  |
| Unknown             | 19        | 15.32%  |
| Kingston            | 17        | 13.71%  |
| Micron Technology   | 12        | 9.68%   |
| Elpida              | 3         | 2.42%   |
| A-DATA Technology   | 3         | 2.42%   |
| 48spaces            | 3         | 2.42%   |
| Transcend           | 2         | 1.61%   |
| Ramaxel Technology  | 2         | 1.61%   |
| Crucial             | 2         | 1.61%   |
| Corsair             | 2         | 1.61%   |
| Unknown             | 2         | 1.61%   |
| Silicon Power       | 1         | 0.81%   |
| GeIL                | 1         | 0.81%   |
| Apacer              | 1         | 0.81%   |
| AMD                 | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 2.99%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 2.24%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 2.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 2.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 2.24%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 2.24%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 2.24%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 1.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 1.49%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 1.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.49%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.49%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.49%   |
| Unknown                                                                   | 2         | 1.49%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.75%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.75%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.75%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR 800MT/s                              | 1         | 0.75%   |
| Unknown RAM Module 128MB SODIMM DRAM                                      | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266(3.8ns)MT/s                     | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                     | 1         | 0.75%   |
| Unknown RAM Module 1024MB SODIMM DDR                                      | 1         | 0.75%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                            | 1         | 0.75%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                         | 1         | 0.75%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                      | 1         | 0.75%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.75%   |
| SK hynix RAM Module 1024MB SODIMM DDR3 1067MT/s                           | 1         | 0.75%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 41        | 39.42%  |
| DDR3    | 33        | 31.73%  |
| DDR2    | 12        | 11.54%  |
| LPDDR3  | 6         | 5.77%   |
| DDR     | 5         | 4.81%   |
| DRAM    | 3         | 2.88%   |
| SDRAM   | 2         | 1.92%   |
| RAM     | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 94.23%  |
| Row Of Chips | 4         | 3.85%   |
| DIMM         | 1         | 0.96%   |
| Chip         | 1         | 0.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 39        | 32.5%   |
| 4096  | 35        | 29.17%  |
| 2048  | 24        | 20%     |
| 1024  | 8         | 6.67%   |
| 16384 | 5         | 4.17%   |
| 512   | 4         | 3.33%   |
| 256   | 2         | 1.67%   |
| 32768 | 1         | 0.83%   |
| 2560  | 1         | 0.83%   |
| 128   | 1         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 16.51%  |
| 3200    | 14        | 12.84%  |
| 2667    | 14        | 12.84%  |
| 2400    | 12        | 11.01%  |
| 1333    | 11        | 10.09%  |
| Unknown | 10        | 9.17%   |
| 667     | 9         | 8.26%   |
| 1867    | 5         | 4.59%   |
| 2133    | 4         | 3.67%   |
| 800     | 4         | 3.67%   |
| 1067    | 3         | 2.75%   |
| 2933    | 1         | 0.92%   |
| 1334    | 1         | 0.92%   |
| 975     | 1         | 0.92%   |
| 266     | 1         | 0.92%   |
| 100     | 1         | 0.92%   |

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
| Chicony Electronics                    | 24        | 26.37%  |
| IMC Networks                           | 13        | 14.29%  |
| Realtek Semiconductor                  | 10        | 10.99%  |
| Microdia                               | 7         | 7.69%   |
| Acer                                   | 7         | 7.69%   |
| Suyin                                  | 5         | 5.49%   |
| Quanta                                 | 4         | 4.4%    |
| Lite-On Technology                     | 4         | 4.4%    |
| Syntek                                 | 3         | 3.3%    |
| ALi                                    | 3         | 3.3%    |
| Silicon Motion                         | 2         | 2.2%    |
| Z-Star Microelectronics                | 1         | 1.1%    |
| Sunplus Innovation Technology          | 1         | 1.1%    |
| Sonix Technology                       | 1         | 1.1%    |
| ShineTech                              | 1         | 1.1%    |
| Ricoh                                  | 1         | 1.1%    |
| Intel                                  | 1         | 1.1%    |
| DigiTech                               | 1         | 1.1%    |
| Denron                                 | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 9         | 9.68%   |
| IMC Networks Integrated Camera                      | 5         | 5.38%   |
| Microdia Integrated_Webcam_HD                       | 4         | 4.3%    |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 3.23%   |
| Quanta VGA WebCam                                   | 3         | 3.23%   |
| Acer Lenovo EasyCamera                              | 3         | 3.23%   |
| Syntek EasyCamera                                   | 2         | 2.15%   |
| Silicon Motion WebCam SCX Series                    | 2         | 2.15%   |
| Realtek Integrated Webcam                           | 2         | 2.15%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.15%   |
| Microdia Integrated Webcam                          | 2         | 2.15%   |
| Lite-On Integrated Camera                           | 2         | 2.15%   |
| Lite-On HP HD Camera                                | 2         | 2.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 2.15%   |
| IMC Networks EasyCamera                             | 2         | 2.15%   |
| ALi Gateway Webcam                                  | 2         | 2.15%   |
| Z-Star Webcam                                       | 1         | 1.08%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.08%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 1.08%   |
| Suyin HP Webcam                                     | 1         | 1.08%   |
| Suyin HD WebCam                                     | 1         | 1.08%   |
| Suyin HD Video WebCam                               | 1         | 1.08%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.08%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.08%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.08%   |
| ShineTech HD Camera                                 | 1         | 1.08%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.08%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.08%   |
| Realtek USB Webcam                                  | 1         | 1.08%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 1.08%   |
| Realtek Integrated_Webcam_8M                        | 1         | 1.08%   |
| Quanta Realtek DMFT - RGB                           | 1         | 1.08%   |
| Microdia Integrated Webcam HD                       | 1         | 1.08%   |
| Intel WiMAX Connection 2400m                        | 1         | 1.08%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.08%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.08%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.08%   |
| IMC Networks HP TrueVision HD Camera                | 1         | 1.08%   |
| DigiTech WebCam SCB-0350M                           | 1         | 1.08%   |
| Denron Corp., 2M Front Camera                       | 1         | 1.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 36%     |
| Synaptics                  | 8         | 32%     |
| STMicroelectronics         | 3         | 12%     |
| AuthenTec                  | 2         | 8%      |
| Upek                       | 1         | 4%      |
| Shenzhen Goodix Technology | 1         | 4%      |
| Broadcom                   | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 20%     |
| STMicroelectronics Fingerprint Reader                                        | 3         | 12%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 8%      |
| AuthenTec AES1600                                                            | 2         | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 4%      |
| Validity Sensors Synaptics WBDI                                              | 1         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 4%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 4%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 4%      |
| Shenzhen Goodix  Fingerprint Device                                          | 1         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4%      |

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
| 1     | 43        | 33.59%  |
| 2     | 33        | 25.78%  |
| 4     | 17        | 13.28%  |
| 3     | 15        | 11.72%  |
| 0     | 15        | 11.72%  |
| 9     | 1         | 0.78%   |
| 8     | 1         | 0.78%   |
| 7     | 1         | 0.78%   |
| 6     | 1         | 0.78%   |
| 5     | 1         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 61        | 29.05%  |
| Net/wireless             | 39        | 18.57%  |
| Card reader              | 26        | 12.38%  |
| Bluetooth                | 26        | 12.38%  |
| Fingerprint reader       | 21        | 10%     |
| Firewire controller      | 12        | 5.71%   |
| Sound                    | 7         | 3.33%   |
| Graphics card            | 6         | 2.86%   |
| Storage                  | 5         | 2.38%   |
| Network                  | 3         | 1.43%   |
| Modem                    | 3         | 1.43%   |
| Storage/ata              | 1         | 0.48%   |

