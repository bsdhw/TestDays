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

Total: 213

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Timi          | Redmi Book Pro 14 2022      | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| HUAWEI        | CREM-WXX9                   | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| ASUSTek       | K50IN                       | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Sony          | SVP1321V9RB                 | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
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
| eMachines     | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
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
| helloSystem 0.7.0    | 15        | 10.49%  |
| OpenBSD 6.8          | 10        | 6.99%   |
| FreeBSD 13.1         | 9         | 6.29%   |
| NomadBSD 1.3.2       | 7         | 4.9%    |
| FreeBSD 14.0-CURRENT | 6         | 4.2%    |
| FreeBSD 13.0         | 6         | 4.2%    |
| OpenBSD 7.1          | 5         | 3.5%    |
| helloSystem 0.8.0    | 5         | 3.5%    |
| FreeBSD 13.0-CURRENT | 5         | 3.5%    |
| NomadBSD 5806f915    | 4         | 2.8%    |
| helloSystem 0.6.0    | 4         | 2.8%    |
| FreeBSD 13.1-p5      | 4         | 2.8%    |
| FreeBSD 12.1-STABLE  | 4         | 2.8%    |
| OpenBSD 6.9          | 3         | 2.1%    |
| GhostBSD 20.04.02    | 3         | 2.1%    |
| FreeBSD 13.1-p1      | 3         | 2.1%    |
| FreeBSD 12.2-p4      | 3         | 2.1%    |
| OpenBSD 6.7          | 2         | 1.4%    |
| FreeBSD 13.0-p3      | 2         | 1.4%    |
| FreeBSD 12.3-STABLE  | 2         | 1.4%    |
| FreeBSD 12.2-STABLE  | 2         | 1.4%    |
| FreeBSD 12.2-p3      | 2         | 1.4%    |
| FreeBSD 12.1-p8      | 2         | 1.4%    |
| FreeBSD 12.1-p7      | 2         | 1.4%    |
| FreeBSD 12.1-p5      | 2         | 1.4%    |
| OS108 9.0            | 1         | 0.7%    |
| OpenBSD 7.0          | 1         | 0.7%    |
| NomadBSD 1.4         | 1         | 0.7%    |
| NomadBSD 1.3.1       | 1         | 0.7%    |
| NetBSD 9.99.94       | 1         | 0.7%    |
| NetBSD 9.1           | 1         | 0.7%    |
| NetBSD 7.2           | 1         | 0.7%    |
| LibertyBSD 6.1       | 1         | 0.7%    |
| helloSystem 0.3.0    | 1         | 0.7%    |
| GhostBSD 21.08.27    | 1         | 0.7%    |
| FreeBSD 8.4          | 1         | 0.7%    |
| FreeBSD 13.1-STABLE  | 1         | 0.7%    |
| FreeBSD 13.1-p4      | 1         | 0.7%    |
| FreeBSD 13.1-p2      | 1         | 0.7%    |
| FreeBSD 13.1-BETA3   | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 68        | 51.13%  |
| helloSystem | 24        | 18.05%  |
| OpenBSD     | 20        | 15.04%  |
| NomadBSD    | 12        | 9.02%   |
| GhostBSD    | 4         | 3.01%   |
| NetBSD      | 3         | 2.26%   |
| OS108       | 1         | 0.75%   |
| LibertyBSD  | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 112       | 88.89%  |
| i386  | 14        | 11.11%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 28        | 21.05%  |
| XFCE          | 15        | 11.28%  |
| KDE5          | 15        | 11.28%  |
| Console       | 15        | 11.28%  |
| Openbox       | 13        | 9.77%   |
| fvwm          | 13        | 9.77%   |
| GNOME         | 7         | 5.26%   |
| TWM           | 6         | 4.51%   |
| MATE          | 6         | 4.51%   |
| i3            | 3         | 2.26%   |
| LXQt          | 2         | 1.5%    |
| LXDE          | 2         | 1.5%    |
| IceWM         | 2         | 1.5%    |
| AwesomeWM     | 2         | 1.5%    |
| StumpWM       | 1         | 0.75%   |
| Lumina        | 1         | 0.75%   |
| Enlightenment | 1         | 0.75%   |
| DWM           | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 111       | 84.73%  |
| Console | 18        | 13.74%  |
| Wayland | 2         | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 50        | 38.17%  |
| SLiM    | 49        | 37.4%   |
| SDDM    | 14        | 10.69%  |
| LightDM | 7         | 5.34%   |
| XDM     | 6         | 4.58%   |
| GDM     | 3         | 2.29%   |
| PCDM    | 1         | 0.76%   |
| Ly      | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| ru_RU   | 39        | 29.77%  |
| en_US   | 38        | 29.01%  |
| Unknown | 29        | 22.14%  |
| C       | 22        | 16.79%  |
| en_GB   | 1         | 0.76%   |
| en_EN   | 1         | 0.76%   |
| ba_RU   | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 66.15%  |
| BIOS | 44        | 33.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 51        | 38.64%  |
| Ufs    | 50        | 37.88%  |
| Ffs    | 21        | 15.91%  |
| Cd9660 | 9         | 6.82%   |
| Xfs    | 1         | 0.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 97        | 75.78%  |
| MBR     | 28        | 21.88%  |
| Unknown | 2         | 1.56%   |
| BSD     | 1         | 0.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 35        | 27.78%  |
| Dell                | 18        | 14.29%  |
| Hewlett-Packard     | 15        | 11.9%   |
| Acer                | 14        | 11.11%  |
| ASUSTek Computer    | 13        | 10.32%  |
| Sony                | 6         | 4.76%   |
| Samsung Electronics | 5         | 3.97%   |
| HUAWEI              | 3         | 2.38%   |
| Toshiba             | 2         | 1.59%   |
| Timi                | 2         | 1.59%   |
| MSI                 | 2         | 1.59%   |
| IBM                 | 2         | 1.59%   |
| Apple               | 2         | 1.59%   |
| Panasonic           | 1         | 0.79%   |
| Packard Bell        | 1         | 0.79%   |
| Kraftway            | 1         | 0.79%   |
| Google              | 1         | 0.79%   |
| eMachines           | 1         | 0.79%   |
| DNS                 | 1         | 0.79%   |
| DEXP                | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N145P/N250P/N260P                | 2         | 1.59%   |
| Lenovo IdeaPad 330-15ARR 81D2            | 2         | 1.59%   |
| HUAWEI CREM-WXX9                         | 2         | 1.59%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 1.59%   |
| Acer Aspire 4820T                        | 2         | 1.59%   |
| Toshiba Satellite M100                   | 1         | 0.79%   |
| Toshiba Satellite A300                   | 1         | 0.79%   |
| Timi TM1612                              | 1         | 0.79%   |
| Timi Redmi Book Pro 14 2022              | 1         | 0.79%   |
| Sony VPCX115KX                           | 1         | 0.79%   |
| Sony VPCM13M1R                           | 1         | 0.79%   |
| Sony VGN-UX1XRN                          | 1         | 0.79%   |
| Sony VGN-S150(UC)                        | 1         | 0.79%   |
| Sony SVP1321V9RB                         | 1         | 0.79%   |
| Sony SVE1713S1RW                         | 1         | 0.79%   |
| Samsung R530/R730/R540                   | 1         | 0.79%   |
| Samsung Q430/Q530                        | 1         | 0.79%   |
| Samsung N150P                            | 1         | 0.79%   |
| Panasonic CF-19AHNC8FN                   | 1         | 0.79%   |
| Packard Bell EasyNote TE69HW             | 1         | 0.79%   |
| MSI PS63 Modern 8M                       | 1         | 0.79%   |
| MSI GE75 Raider 10SFS                    | 1         | 0.79%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS       | 1         | 0.79%   |
| Lenovo V580 20147                        | 1         | 0.79%   |
| Lenovo ThinkPad Yoga 260 20FES1K81V      | 1         | 0.79%   |
| Lenovo ThinkPad X240 20AMA52RUK          | 1         | 0.79%   |
| Lenovo ThinkPad X240 20AL00DKRT          | 1         | 0.79%   |
| Lenovo ThinkPad X230 2325Y36             | 1         | 0.79%   |
| Lenovo ThinkPad X13 Gen 1 20UF000QRT     | 1         | 0.79%   |
| Lenovo ThinkPad X13 Gen 1 20T2003PRT     | 1         | 0.79%   |
| Lenovo ThinkPad X121e 3053A52            | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 7th 20QES42E0L | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00 | 1         | 0.79%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DW00 | 1         | 0.79%   |
| Lenovo ThinkPad T495s 20QKS1812F         | 1         | 0.79%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 0.79%   |
| Lenovo ThinkPad T480s 20L7001HRT         | 1         | 0.79%   |
| Lenovo ThinkPad T430 23511A6             | 1         | 0.79%   |
| Lenovo ThinkPad T420 4178A72             | 1         | 0.79%   |
| Lenovo ThinkPad P15 Gen 1 20ST005VRT     | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 19        | 15.08%  |
| Acer Aspire            | 12        | 9.52%   |
| Lenovo IdeaPad         | 9         | 7.14%   |
| Dell Latitude          | 7         | 5.56%   |
| Dell Inspiron          | 7         | 5.56%   |
| HP ProBook             | 6         | 4.76%   |
| HP Laptop              | 3         | 2.38%   |
| ASUS VivoBook          | 3         | 2.38%   |
| Toshiba Satellite      | 2         | 1.59%   |
| Samsung N145P          | 2         | 1.59%   |
| IBM ThinkPad           | 2         | 1.59%   |
| HUAWEI CREM-WXX9       | 2         | 1.59%   |
| Acer Extensa           | 2         | 1.59%   |
| Timi TM1612            | 1         | 0.79%   |
| Timi Redmi             | 1         | 0.79%   |
| Sony VPCX115KX         | 1         | 0.79%   |
| Sony VPCM13M1R         | 1         | 0.79%   |
| Sony VGN-UX1XRN        | 1         | 0.79%   |
| Sony VGN-S150(UC)      | 1         | 0.79%   |
| Sony SVP1321V9RB       | 1         | 0.79%   |
| Sony SVE1713S1RW       | 1         | 0.79%   |
| Samsung R530           | 1         | 0.79%   |
| Samsung Q430           | 1         | 0.79%   |
| Samsung N150P          | 1         | 0.79%   |
| Panasonic CF-19AHNC8FN | 1         | 0.79%   |
| Packard Bell EasyNote  | 1         | 0.79%   |
| MSI PS63               | 1         | 0.79%   |
| MSI GE75               | 1         | 0.79%   |
| Lenovo Yoga            | 1         | 0.79%   |
| Lenovo V580            | 1         | 0.79%   |
| Lenovo ThinkBook       | 1         | 0.79%   |
| Lenovo S20-30          | 1         | 0.79%   |
| Lenovo G570            | 1         | 0.79%   |
| Lenovo E31-80          | 1         | 0.79%   |
| Lenovo B50-30          | 1         | 0.79%   |
| Kraftway KW10T         | 1         | 0.79%   |
| HUAWEI KLVL-WXXW       | 1         | 0.79%   |
| HP Pavilion            | 1         | 0.79%   |
| HP OmniBook            | 1         | 0.79%   |
| HP EliteBook           | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 18        | 14.29%  |
| 2020 | 14        | 11.11%  |
| 2011 | 13        | 10.32%  |
| 2021 | 10        | 7.94%   |
| 2018 | 10        | 7.94%   |
| 2012 | 8         | 6.35%   |
| 2010 | 6         | 4.76%   |
| 2008 | 6         | 4.76%   |
| 2017 | 5         | 3.97%   |
| 2016 | 5         | 3.97%   |
| 2015 | 5         | 3.97%   |
| 2009 | 5         | 3.97%   |
| 2022 | 4         | 3.17%   |
| 2014 | 4         | 3.17%   |
| 2013 | 4         | 3.17%   |
| 2007 | 2         | 1.59%   |
| 2006 | 2         | 1.59%   |
| 2005 | 2         | 1.59%   |
| 2004 | 2         | 1.59%   |
| 2003 | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 126       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 125       | 99.21%  |
| Yes  | 1         | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 39        | 30.47%  |
| 4.01-8.0    | 34        | 26.56%  |
| 16.01-24.0  | 27        | 21.09%  |
| 2.01-3.0    | 9         | 7.03%   |
| 0.51-1.0    | 5         | 3.91%   |
| 1.01-2.0    | 4         | 3.13%   |
| 24.01-32.0  | 3         | 2.34%   |
| 0.01-0.5    | 3         | 2.34%   |
| 3.01-4.0    | 2         | 1.56%   |
| 32.01-64.0  | 1         | 0.78%   |
| 64.01-256.0 | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 70        | 53.03%  |
| 0.51-1.0   | 34        | 25.76%  |
| 1.01-2.0   | 8         | 6.06%   |
| 2.01-3.0   | 7         | 5.3%    |
| Unknown    | 5         | 3.79%   |
| 0          | 4         | 3.03%   |
| 4.01-8.0   | 2         | 1.52%   |
| 24.01-32.0 | 1         | 0.76%   |
| 8.01-16.0  | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 68.7%   |
| 2      | 30        | 22.9%   |
| 0      | 6         | 4.58%   |
| 4      | 3         | 2.29%   |
| 3      | 2         | 1.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 79.37%  |
| Yes       | 26        | 20.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 83.33%  |
| No        | 21        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 96.83%  |
| No        | 4         | 3.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 66.93%  |
| No        | 42        | 33.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 126       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 43        | 33.59%  |
| St Petersburg    | 15        | 11.72%  |
| Vladivostok      | 6         | 4.69%   |
| Yekaterinburg    | 4         | 3.13%   |
| Novosibirsk      | 4         | 3.13%   |
| Ulyanovsk        | 3         | 2.34%   |
| Ufa              | 3         | 2.34%   |
| Tyumen           | 3         | 2.34%   |
| Krasnoyarsk      | 3         | 2.34%   |
| Chelyabinsk      | 3         | 2.34%   |
| Tsarskoye Selo   | 2         | 1.56%   |
| Tolyatti         | 2         | 1.56%   |
| Perm             | 2         | 1.56%   |
| Kirov            | 2         | 1.56%   |
| Zhukovskiy       | 1         | 0.78%   |
| Yoshkar-Ola      | 1         | 0.78%   |
| Yegorlykskaya    | 1         | 0.78%   |
| Yaroslavl        | 1         | 0.78%   |
| Vorkuta          | 1         | 0.78%   |
| Vladimir         | 1         | 0.78%   |
| Ust'-Luga        | 1         | 0.78%   |
| Surgut           | 1         | 0.78%   |
| Smolensk         | 1         | 0.78%   |
| Sevastopol'      | 1         | 0.78%   |
| Rostov-on-Don    | 1         | 0.78%   |
| Pushkino         | 1         | 0.78%   |
| Penza            | 1         | 0.78%   |
| Ozersk           | 1         | 0.78%   |
| Oryol            | 1         | 0.78%   |
| Obninsk          | 1         | 0.78%   |
| Nizhniy Novgorod | 1         | 0.78%   |
| Minusinsk        | 1         | 0.78%   |
| Michurinsk       | 1         | 0.78%   |
| Kstovo           | 1         | 0.78%   |
| Krasnokamsk      | 1         | 0.78%   |
| Krasnodar        | 1         | 0.78%   |
| Korolyov         | 1         | 0.78%   |
| Kogalym          | 1         | 0.78%   |
| Kislovodsk       | 1         | 0.78%   |
| Khabarovsk       | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 34     | 19.33%  |
| Seagate             | 17        | 20     | 11.33%  |
| Samsung Electronics | 16        | 20     | 10.67%  |
| Toshiba             | 11        | 12     | 7.33%   |
| SanDisk             | 9         | 11     | 6%      |
| SK hynix            | 8         | 9      | 5.33%   |
| Hitachi             | 8         | 10     | 5.33%   |
| Kingston            | 7         | 8      | 4.67%   |
| Intel               | 6         | 8      | 4%      |
| HGST                | 5         | 6      | 3.33%   |
| SPCC                | 4         | 5      | 2.67%   |
| Transcend           | 3         | 3      | 2%      |
| Micron Technology   | 3         | 3      | 2%      |
| NVMe                | 2         | 2      | 1.33%   |
| KIOXIA              | 2         | 2      | 1.33%   |
| Innostor            | 2         | 2      | 1.33%   |
| Gigabyte Technology | 2         | 5      | 1.33%   |
| A-DATA Technology   | 2         | 2      | 1.33%   |
| USB                 | 1         | 1      | 0.67%   |
| UFD 2.0             | 1         | 1      | 0.67%   |
| SSSTC               | 1         | 1      | 0.67%   |
| Smartbuy            | 1         | 1      | 0.67%   |
| Silicon Motion      | 1         | 1      | 0.67%   |
| Phison              | 1         | 1      | 0.67%   |
| OCZ                 | 1         | 2      | 0.67%   |
| Netac               | 1         | 1      | 0.67%   |
| KLLISRE             | 1         | 1      | 0.67%   |
| Hewlett-Packard     | 1         | 1      | 0.67%   |
| FORESEE             | 1         | 2      | 0.67%   |
| Apple               | 1         | 1      | 0.67%   |
| Apacer              | 1         | 1      | 0.67%   |
| AMD                 | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 3         | 1.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.91%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.91%   |
| Kingston SV300S37A120G 120GB         | 3         | 1.91%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.91%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1.27%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 1.27%   |
| WDC WD2500BEVT-22A23T0 250GB         | 2         | 1.27%   |
| WDC PC SN730 SDBPNTY-512G            | 2         | 1.27%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.27%   |
| Seagate ST9500325AS 500GB            | 2         | 1.27%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.27%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.27%   |
| Micron 1100 SATA 256GB               | 2         | 1.27%   |
| Kingston SA400S37120G 120GB          | 2         | 1.27%   |
| Innostor SSD 15GB                    | 2         | 1.27%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB         | 1         | 0.64%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.64%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.64%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.64%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 0.64%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 0.64%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.64%   |
| WDC WD20SPZX-00UA7T0 2TB             | 1         | 0.64%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.64%   |
| WDC WD2000JB-00GVC0 200GB            | 1         | 0.64%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.64%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.64%   |
| WDC WD10JPVX-08JC3T5 1TB             | 1         | 0.64%   |
| WDC WD10JPVT-08A1YT2 1TB             | 1         | 0.64%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.64%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 0.64%   |
| WDC PC SN530 SDBPNPZ-512G-1014 512GB | 1         | 0.64%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.64%   |
| WDC PC SN520 NVMe 512GB              | 1         | 0.64%   |
| USB SanDisk 3.2Gen1 64GB             | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 18     | 27.42%  |
| Seagate             | 17        | 20     | 27.42%  |
| Toshiba             | 10        | 11     | 16.13%  |
| Hitachi             | 8         | 10     | 12.9%   |
| HGST                | 5         | 6      | 8.06%   |
| NVMe                | 2         | 2      | 3.23%   |
| USB                 | 1         | 1      | 1.61%   |
| UFD 2.0             | 1         | 1      | 1.61%   |
| Samsung Electronics | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 17.86%  |
| SanDisk             | 9         | 11     | 16.07%  |
| Kingston            | 6         | 7      | 10.71%  |
| WDC                 | 4         | 5      | 7.14%   |
| SPCC                | 4         | 5      | 7.14%   |
| Intel               | 4         | 6      | 7.14%   |
| Micron Technology   | 3         | 3      | 5.36%   |
| Transcend           | 2         | 2      | 3.57%   |
| Innostor            | 2         | 2      | 3.57%   |
| Smartbuy            | 1         | 1      | 1.79%   |
| SK hynix            | 1         | 1      | 1.79%   |
| OCZ                 | 1         | 2      | 1.79%   |
| Netac               | 1         | 1      | 1.79%   |
| KLLISRE             | 1         | 1      | 1.79%   |
| Hewlett-Packard     | 1         | 1      | 1.79%   |
| Gigabyte Technology | 1         | 3      | 1.79%   |
| FORESEE             | 1         | 2      | 1.79%   |
| Apple               | 1         | 1      | 1.79%   |
| Apacer              | 1         | 1      | 1.79%   |
| AMD                 | 1         | 1      | 1.79%   |
| A-DATA Technology   | 1         | 1      | 1.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 70     | 40.58%  |
| SSD  | 50        | 69     | 36.23%  |
| NVMe | 32        | 39     | 23.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 139    | 74.6%   |
| NVMe | 32        | 39     | 25.4%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 78        | 111    | 75%     |
| 0.51-1.0        | 22        | 24     | 21.15%  |
| 1.01-2.0        | 3         | 3      | 2.88%   |
| More than 100.0 | 1         | 1      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 38        | 27.94%  |
| 251-500    | 29        | 21.32%  |
| 1-20       | 29        | 21.32%  |
| 21-50      | 12        | 8.82%   |
| 501-1000   | 12        | 8.82%   |
| 51-100     | 11        | 8.09%   |
| 1001-2000  | 3         | 2.21%   |
| Unknown    | 2         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 92        | 70.77%  |
| 21-50   | 16        | 12.31%  |
| 101-250 | 11        | 8.46%   |
| 51-100  | 7         | 5.38%   |
| 251-500 | 2         | 1.54%   |
| Unknown | 2         | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 6.45%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 6.45%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 6.45%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 3.23%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 1      | 3.23%   |
| WDC WD2000JB-00GVC0 200GB           | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 3.23%   |
| Toshiba MK7575GSX 752GB             | 1         | 1      | 3.23%   |
| Toshiba MK2546GSX 250GB             | 1         | 1      | 3.23%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 3.23%   |
| Seagate ST9250320AS 250GB           | 1         | 1      | 3.23%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 3.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 3.23%   |
| Samsung Electronics HM080HI 80GB    | 1         | 1      | 3.23%   |
| Kingston SV300S37A120G 120GB        | 1         | 1      | 3.23%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 3.23%   |
| Intel SSDSC2CW060A3 64GB            | 1         | 1      | 3.23%   |
| Intel SSDSC2BB480G7 480GB           | 1         | 1      | 3.23%   |
| Hitachi HTS725025A9A364 250GB       | 1         | 1      | 3.23%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 3.23%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 1      | 3.23%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 3.23%   |
| Hitachi HTC426060G9AT00 64GB        | 1         | 1      | 3.23%   |
| Hitachi DK23AA-12 12GB              | 1         | 1      | 3.23%   |
| HGST HTS541075A7E630 752GB          | 1         | 1      | 3.23%   |
| HGST HTE725032A7E630 320GB          | 1         | 1      | 3.23%   |
| Apple SSD SD0128F 121GB             | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 22.58%  |
| Hitachi             | 6         | 6      | 19.35%  |
| Toshiba             | 5         | 5      | 16.13%  |
| WDC                 | 3         | 3      | 9.68%   |
| Intel               | 3         | 3      | 9.68%   |
| Micron Technology   | 2         | 2      | 6.45%   |
| HGST                | 2         | 2      | 6.45%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Kingston            | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 29.17%  |
| Hitachi             | 6         | 6      | 25%     |
| Toshiba             | 5         | 5      | 20.83%  |
| WDC                 | 3         | 3      | 12.5%   |
| HGST                | 2         | 2      | 8.33%   |
| Samsung Electronics | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 24     | 77.42%  |
| SSD  | 7         | 7      | 22.58%  |

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
| Works    | 99        | 142    | 73.33%  |
| Malfunc  | 31        | 31     | 22.96%  |
| Detected | 4         | 4      | 2.96%   |
| Failed   | 1         | 1      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 85        | 59.03%  |
| AMD                              | 22        | 15.28%  |
| SK hynix                         | 8         | 5.56%   |
| SanDisk                          | 8         | 5.56%   |
| Samsung Electronics              | 6         | 4.17%   |
| Phison Electronics               | 2         | 1.39%   |
| Nvidia                           | 2         | 1.39%   |
| KIOXIA                           | 2         | 1.39%   |
| Transcend                        | 1         | 0.69%   |
| Toshiba                          | 1         | 0.69%   |
| Solid State Storage Technology   | 1         | 0.69%   |
| Silicon Motion                   | 1         | 0.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |
| Realtek Semiconductor            | 1         | 0.69%   |
| Marvell Technology Group         | 1         | 0.69%   |
| Kingston Technology Company      | 1         | 0.69%   |
| JMicron Technology               | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 12.58%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 7.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 5.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 4.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 3.97%   |
| Unknown                                                                          | 6         | 3.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 3.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 3.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 3.31%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.99%   |
| SK hynix BC511                                                                   | 2         | 1.32%   |
| SanDisk PC SN530                                                                 | 2         | 1.32%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.32%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 1.32%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 1.32%   |
| Intel 82801CAM IDE U100 Controller                                               | 2         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.32%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.66%   |
| SK hynix hynix unknown                                                           | 1         | 0.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.66%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.66%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.66%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.66%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 64.63%  |
| NVMe | 33        | 22.45%  |
| IDE  | 16        | 10.88%  |
| RAID | 3         | 2.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 97        | 76.98%  |
| AMD    | 29        | 23.02%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Core i3-6006U CPU @ 2.00GHz                                   | 5         | 3.91%   |
| Intel CPU Version                                                   | 3         | 2.34%   |
| Intel Core i7-8565U CPU @ 1.80GHz                                   | 3         | 2.34%   |
| Intel C1                                                            | 3         | 2.34%   |
| AMD Ryzen 7 5800H with Radeon Graphics                              | 3         | 2.34%   |
| Intel Pentium M processor 1.60GHz                                   | 2         | 1.56%   |
| Intel Genuine CPU                                                   | 2         | 1.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz                                   | 2         | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz                                   | 2         | 1.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz                                  | 2         | 1.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz                                   | 2         | 1.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz                                   | 2         | 1.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz                                   | 2         | 1.56%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                                   | 2         | 1.56%   |
| Intel Core 2 Duo                                                    | 2         | 1.56%   |
| Intel 686-class                                                     | 2         | 1.56%   |
| AMD Ryzen 7 4700U with Radeon Graphics                              | 2         | 1.56%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx                       | 2         | 1.56%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx                       | 2         | 1.56%   |
| Intel Xeon W-10885M CPU @ 2.40GHz                                   | 1         | 0.78%   |
| Intel Pentium Silver N6000 @ 1.10GHz                                | 1         | 0.78%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                            | 1         | 0.78%   |
| Intel Pentium M processor 1.86GHz ("GenuineIntel" 686-class)        | 1         | 0.78%   |
| Intel Pentium M processor                                           | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz                         | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz                         | 1         | 0.78%   |
| Intel Pentium CPU N4200 @ 1.10GHz                                   | 1         | 0.78%   |
| Intel Pentium CPU N3700 @ 1.60GHz                                   | 1         | 0.78%   |
| Intel Pentium CPU N3530 @ 2.16GHz                                   | 1         | 0.78%   |
| Intel Pentium CPU 4417U @ 2.30GHz                                   | 1         | 0.78%   |
| Intel Mobile Pentium III CPU - M 1200MHz ("GenuineIntel" 686-class) | 1         | 0.78%   |
| Intel Mobile Pentium III CPU - M 1000MHz ("GenuineIntel" 686-class) | 1         | 0.78%   |
| Intel Genuine CPU U7300 @ 1.30GHz                                   | 1         | 0.78%   |
| Intel Genuine CPU T2                                                | 1         | 0.78%   |
| Intel Core Solo CPU U1500 @ 1.33GHz                                 | 1         | 0.78%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                                    | 1         | 0.78%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz                                    | 1         | 0.78%   |
| Intel Core M-5Y71 CPU @ 1.20GHz                                     | 1         | 0.78%   |
| Intel Core i9-10980HK CPU @ 2.40GHz                                 | 1         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz                                   | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 16.41%  |
| Intel Core i7           | 17        | 13.28%  |
| Intel Core i3           | 11        | 8.59%   |
| Other                   | 10        | 7.81%   |
| AMD Ryzen 7             | 7         | 5.47%   |
| AMD Ryzen 3             | 7         | 5.47%   |
| Intel Core 2 Duo        | 6         | 4.69%   |
| Intel Atom              | 5         | 3.91%   |
| Intel Pentium M         | 4         | 3.13%   |
| Intel Pentium           | 4         | 3.13%   |
| Intel Genuine           | 4         | 3.13%   |
| Intel Celeron           | 4         | 3.13%   |
| AMD Ryzen 5             | 4         | 3.13%   |
| AMD E                   | 3         | 2.34%   |
| AMD A6                  | 3         | 2.34%   |
| Intel Pentium Silver    | 2         | 1.56%   |
| Intel Pentium Dual-Core | 2         | 1.56%   |
| Intel 686-class         | 2         | 1.56%   |
| AMD Ryzen 7 PRO         | 2         | 1.56%   |
| Intel Xeon              | 1         | 0.78%   |
| Intel Core Solo         | 1         | 0.78%   |
| Intel Core m5           | 1         | 0.78%   |
| Intel Core m3           | 1         | 0.78%   |
| Intel Core M            | 1         | 0.78%   |
| Intel Core i9           | 1         | 0.78%   |
| Intel Celeron Dual-Core | 1         | 0.78%   |
| AMD E2                  | 1         | 0.78%   |
| AMD E1                  | 1         | 0.78%   |
| AMD A10                 | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 52        | 40.31%  |
| 4       | 34        | 26.36%  |
| Unknown | 16        | 12.4%   |
| 1       | 10        | 7.75%   |
| 8       | 8         | 6.2%    |
| 16      | 5         | 3.88%   |
| 12      | 2         | 1.55%   |
| 6       | 2         | 1.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 120       | 93.02%  |
| Unknown | 9         | 6.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 61        | 47.29%  |
| 1       | 46        | 35.66%  |
| Unknown | 22        | 17.05%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 14.96%  |
| Penryn        | 10        | 7.87%   |
| Skylake       | 9         | 7.09%   |
| SandyBridge   | 8         | 6.3%    |
| P6            | 8         | 6.3%    |
| IvyBridge     | 7         | 5.51%   |
| Bonnell       | 7         | 5.51%   |
| Haswell       | 6         | 4.72%   |
| Zen+          | 5         | 3.94%   |
| Zen 2         | 5         | 3.94%   |
| Silvermont    | 5         | 3.94%   |
| Unknown       | 5         | 3.94%   |
| Zen 3         | 4         | 3.15%   |
| Westmere      | 4         | 3.15%   |
| Zen           | 3         | 2.36%   |
| Core          | 3         | 2.36%   |
| TigerLake     | 2         | 1.57%   |
| Puma          | 2         | 1.57%   |
| Goldmont      | 2         | 1.57%   |
| Excavator     | 2         | 1.57%   |
| CometLake     | 2         | 1.57%   |
| Broadwell     | 2         | 1.57%   |
| Bobcat        | 2         | 1.57%   |
| Piledriver    | 1         | 0.79%   |
| K8 Hammer     | 1         | 0.79%   |
| Jaguar        | 1         | 0.79%   |
| IceLake       | 1         | 0.79%   |
| Goldmont plus | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 83        | 56.08%  |
| AMD    | 42        | 28.38%  |
| Nvidia | 22        | 14.86%  |
| ATI    | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 3.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 3.29%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 3.29%   |
| AMD Renoir                                                                               | 5         | 3.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.29%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 2.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.97%   |
| Intel HD Graphics 630                                                                    | 3         | 1.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.97%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.32%   |
| Intel HD Graphics 620                                                                    | 2         | 1.32%   |
| Intel HD Graphics 520                                                                    | 2         | 1.32%   |
| Intel HD Graphics 515                                                                    | 2         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.32%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.32%   |
| AMD Lucienne                                                                             | 2         | 1.32%   |
| Nvidia TU117M                                                                            | 1         | 0.66%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.66%   |
| Nvidia TU104GLM [Quadro RTX 5000 Mobile / Max-Q]                                         | 1         | 0.66%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.66%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.66%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.66%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.66%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.66%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.66%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.66%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 41.73%  |
| 1 x AMD        | 35        | 27.56%  |
| Intel + Nvidia | 14        | 11.02%  |
| 2 x Intel      | 12        | 9.45%   |
| 1 x Nvidia     | 6         | 4.72%   |
| Intel + AMD    | 4         | 3.15%   |
| AMD + Nvidia   | 2         | 1.57%   |
| 2 x AMD        | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 88.28%  |
| Proprietary | 9         | 7.03%   |
| Unknown     | 6         | 4.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 76.92%  |
| 0.01-0.5   | 18        | 13.85%  |
| 1.01-2.0   | 6         | 4.62%   |
| 0.51-1.0   | 4         | 3.08%   |
| 3.01-4.0   | 1         | 0.77%   |
| 2.01-3.0   | 1         | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 25.24%  |
| LG Display              | 16        | 15.53%  |
| BOE                     | 13        | 12.62%  |
| Samsung Electronics     | 11        | 10.68%  |
| Chimei Innolux          | 10        | 9.71%   |
| InfoVision              | 4         | 3.88%   |
| LG Philips              | 3         | 2.91%   |
| Chi Mei Optoelectronics | 3         | 2.91%   |
| ViewSonic               | 2         | 1.94%   |
| PANDA                   | 2         | 1.94%   |
| Lenovo                  | 2         | 1.94%   |
| Acer                    | 2         | 1.94%   |
| Toshiba                 | 1         | 0.97%   |
| Panasonic               | 1         | 0.97%   |
| NEC Computers           | 1         | 0.97%   |
| HannStar                | 1         | 0.97%   |
| Goldstar                | 1         | 0.97%   |
| CSO                     | 1         | 0.97%   |
| CPT                     | 1         | 0.97%   |
| Apple                   | 1         | 0.97%   |
| Ancor Communications    | 1         | 0.97%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 2         | 1.94%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 1.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 1.94%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 1.94%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 1.94%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch              | 1         | 0.97%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.97%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                          | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC5643 1280x800 300x190mm 14.0-inch     | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch     | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch    | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch    | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch   | 1         | 0.97%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 0.97%   |
| PANDA LCD Monitor NCP002B 1920x1080 310x170mm 13.9-inch                  | 1         | 0.97%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 0.97%   |
| NEC Computers LCD1970NX NEC6662 1280x1024 380x300mm 19.1-inch            | 1         | 0.97%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch              | 1         | 0.97%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 0.97%   |
| LG Philips LCD Monitor LPL0301 1280x800 330x210mm 15.4-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD06FF 1920x1080 340x190mm 15.3-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD062E 1920x1080 340x190mm 15.3-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD060A 1920x1080 290x170mm 13.2-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD05EE 2560x1440 310x170mm 13.9-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 0.97%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD0303 1600x900 380x210mm 17.1-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 0.97%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 0.97%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 340x190mm 15.3-inch                 | 1         | 0.97%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                  | 1         | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 41        | 39.81%  |
| 1366x768 (WXGA)   | 29        | 28.16%  |
| 1280x800 (WXGA)   | 6         | 5.83%   |
| 1600x900 (HD+)    | 5         | 4.85%   |
| 1024x600          | 4         | 3.88%   |
| 2560x1440 (QHD)   | 3         | 2.91%   |
| 1440x900 (WXGA+)  | 3         | 2.91%   |
| 3840x2160 (4K)    | 2         | 1.94%   |
| 1280x1024 (SXGA)  | 2         | 1.94%   |
| 3200x1800 (QHD+)  | 1         | 0.97%   |
| 2880x1620         | 1         | 0.97%   |
| 2560x1080         | 1         | 0.97%   |
| 2520x1680         | 1         | 0.97%   |
| 2240x1400         | 1         | 0.97%   |
| 2160x1440         | 1         | 0.97%   |
| 1920x540          | 1         | 0.97%   |
| 1920x1200 (WUXGA) | 1         | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 43        | 41.75%  |
| 13     | 26        | 25.24%  |
| 17     | 7         | 6.8%    |
| 14     | 5         | 4.85%   |
| 11     | 5         | 4.85%   |
| 10     | 5         | 4.85%   |
| 12     | 3         | 2.91%   |
| 21     | 2         | 1.94%   |
| 54     | 1         | 0.97%   |
| 34     | 1         | 0.97%   |
| 31     | 1         | 0.97%   |
| 27     | 1         | 0.97%   |
| 23     | 1         | 0.97%   |
| 19     | 1         | 0.97%   |
| 16     | 1         | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 64        | 62.14%  |
| 201-300     | 25        | 24.27%  |
| 351-400     | 7         | 6.8%    |
| 501-600     | 2         | 1.94%   |
| 401-500     | 2         | 1.94%   |
| 701-800     | 1         | 0.97%   |
| 601-700     | 1         | 0.97%   |
| 1001-1500   | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 80        | 82.47%  |
| 16/10 | 12        | 12.37%  |
| 5/4   | 2         | 2.06%   |
| 3/2   | 2         | 2.06%   |
| 21/9  | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 37        | 35.92%  |
| 81-90          | 24        | 23.3%   |
| 101-110        | 7         | 6.8%    |
| 71-80          | 6         | 5.83%   |
| 51-60          | 5         | 4.85%   |
| 41-50          | 5         | 4.85%   |
| 121-130        | 4         | 3.88%   |
| 61-70          | 3         | 2.91%   |
| 201-250        | 3         | 2.91%   |
| 131-140        | 3         | 2.91%   |
| 351-500        | 2         | 1.94%   |
| More than 1000 | 1         | 0.97%   |
| 301-350        | 1         | 0.97%   |
| 151-200        | 1         | 0.97%   |
| 141-150        | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 40.78%  |
| 101-120       | 32        | 31.07%  |
| 51-100        | 14        | 13.59%  |
| 161-240       | 13        | 12.62%  |
| More than 240 | 2         | 1.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 97        | 72.39%  |
| 0     | 28        | 20.9%   |
| 2     | 9         | 6.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 67        | 30.59%  |
| Realtek Semiconductor             | 61        | 27.85%  |
| Qualcomm Atheros                  | 37        | 16.89%  |
| Broadcom                          | 14        | 6.39%   |
| Marvell Technology Group          | 10        | 4.57%   |
| TP-Link                           | 4         | 1.83%   |
| Ralink Technology                 | 4         | 1.83%   |
| Samsung Electronics               | 2         | 0.91%   |
| Ralink                            | 2         | 0.91%   |
| Fibocom                           | 2         | 0.91%   |
| Ericsson Business Mobile Networks | 2         | 0.91%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.46%   |
| Realtek                           | 1         | 0.46%   |
| Nvidia                            | 1         | 0.46%   |
| Mercucys                          | 1         | 0.46%   |
| MediaTek                          | 1         | 0.46%   |
| JMicron Technology                | 1         | 0.46%   |
| Huawei Technologies               | 1         | 0.46%   |
| Dell                              | 1         | 0.46%   |
| D-Link                            | 1         | 0.46%   |
| BUFFALO                           | 1         | 0.46%   |
| Attansic                          | 1         | 0.46%   |
| Atheros                           | 1         | 0.46%   |
| Arduino SA                        | 1         | 0.46%   |
| 3Com                              | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 15.59%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.28%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 2.28%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.9%    |
| Intel Wireless 7265                                               | 5         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.52%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.14%   |
| Intel Wireless 8260                                               | 3         | 1.14%   |
| Intel Wireless 3165                                               | 3         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.76%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 2         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.76%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.76%   |
| Intel Wireless-AC 9260                                            | 2         | 0.76%   |
| Intel Wireless 7260                                               | 2         | 0.76%   |
| Intel WiFi Link 5100                                              | 2         | 0.76%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection         | 2         | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.76%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 2         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 45%     |
| Qualcomm Atheros      | 32        | 22.86%  |
| Realtek Semiconductor | 22        | 15.71%  |
| Broadcom              | 8         | 5.71%   |
| TP-Link               | 4         | 2.86%   |
| Ralink Technology     | 4         | 2.86%   |
| Ralink                | 2         | 1.43%   |
| Mercucys              | 1         | 0.71%   |
| MediaTek              | 1         | 0.71%   |
| D-Link                | 1         | 0.71%   |
| BUFFALO               | 1         | 0.71%   |
| Atheros               | 1         | 0.71%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 13        | 9.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 7         | 4.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 4.17%   |
| Intel Wireless 8265 / 8275                                          | 6         | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 5         | 3.47%   |
| Intel Wireless 7265                                                 | 5         | 3.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 5         | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 4         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 4         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                 | 4         | 2.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 4         | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 4         | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 3         | 2.08%   |
| Intel Wireless 8260                                                 | 3         | 2.08%   |
| Intel Wireless 3165                                                 | 3         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 3         | 2.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 2         | 1.39%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 2         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                          | 2         | 1.39%   |
| Realtek Realtek Bluetooth 4.2 Adapter                               | 2         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 2         | 1.39%   |
| Intel Wireless-AC 9260                                              | 2         | 1.39%   |
| Intel Wireless 7260                                                 | 2         | 1.39%   |
| Intel WiFi Link 5100                                                | 2         | 1.39%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection           | 2         | 1.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 2         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                 | 2         | 1.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1         | 0.69%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1         | 0.69%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                     | 1         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 1         | 0.69%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                             | 1         | 0.69%   |
| Ralink RT3572 Wireless Adapter                                      | 1         | 0.69%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1         | 0.69%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                   | 1         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                     | 1         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                           | 1         | 0.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                           | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 50        | 46.3%   |
| Intel                            | 23        | 21.3%   |
| Qualcomm Atheros                 | 10        | 9.26%   |
| Marvell Technology Group         | 10        | 9.26%   |
| Broadcom                         | 7         | 6.48%   |
| Samsung Electronics              | 2         | 1.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |
| Realtek                          | 1         | 0.93%   |
| Nvidia                           | 1         | 0.93%   |
| JMicron Technology               | 1         | 0.93%   |
| Attansic                         | 1         | 0.93%   |
| 3Com                             | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 37.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 6.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 5.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.85%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.85%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 1.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.93%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.93%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.93%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.93%   |
| Intel PRO/100 VM Network Connection                               | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.93%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 0.93%   |
| Intel 82801CAM (ICH3) PRO/100 VM (KM) Ethernet Controller         | 1         | 0.93%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 122       | 51.26%  |
| Ethernet | 105       | 44.12%  |
| Unknown  | 6         | 2.52%   |
| Modem    | 5         | 2.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 53.37%  |
| Ethernet | 74        | 45.4%   |
| Unknown  | 2         | 1.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 80.16%  |
| 1     | 25        | 19.84%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 97.64%  |
| Yes  | 3         | 2.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 46.51%  |
| Realtek Semiconductor           | 8         | 9.3%    |
| Qualcomm Atheros Communications | 8         | 9.3%    |
| Broadcom                        | 5         | 5.81%   |
| Realtek                         | 3         | 3.49%   |
| Lite-On Technology              | 3         | 3.49%   |
| IMC Networks                    | 3         | 3.49%   |
| Foxconn / Hon Hai               | 3         | 3.49%   |
| ASUSTek Computer                | 3         | 3.49%   |
| Alps Electric                   | 3         | 3.49%   |
| Hewlett-Packard                 | 2         | 2.33%   |
| Apple                           | 2         | 2.33%   |
| Ralink                          | 1         | 1.16%   |
| Opticis                         | 1         | 1.16%   |
| Dell                            | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 19.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 6.98%   |
| Intel AX201 Bluetooth                                       | 6         | 6.98%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 4.65%   |
| Intel AX200 Bluetooth                                       | 4         | 4.65%   |
| Realtek  Bluetooth Adapter                                  | 3         | 3.49%   |
| Realtek Bluetooth Radio                                     | 3         | 3.49%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 3.49%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 3         | 3.49%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 2.33%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 2         | 2.33%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 2.33%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.33%   |
| Realtek Bluetooth Radio                                     | 1         | 1.16%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.16%   |
| Qualcomm Atheros  QCA9565 Bluetooth 4.0 + HS Adapter        | 1         | 1.16%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.16%   |
| Opticis Bluetooth Radio                                     | 1         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.16%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 1.16%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 1.16%   |
| Foxconn / Hon Hai Wireless_Device                           | 1         | 1.16%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.16%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3012 Bluetooth Adapter | 1         | 1.16%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.16%   |
| Broadcom Broadcom Bluetooth 4.0                             | 1         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth Module                        | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.16%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.16%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.16%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.16%   |
| Apple Bluetooth Host Controller                             | 1         | 1.16%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 1.16%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.16%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)             | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 67.39%  |
| AMD                              | 32        | 23.19%  |
| Nvidia                           | 7         | 5.07%   |
| Lenovo                           | 2         | 1.45%   |
| Texas Instruments                | 1         | 0.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.72%   |
| ESS Technology                   | 1         | 0.72%   |
| Creative Technology              | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 11.05%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 9.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 6.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 4.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 3.49%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.33%   |
| AMD FCH Azalia Controller                                                                         | 4         | 2.33%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.74%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 1.16%   |
| Lenovo Realtek USB Audio                                                                          | 2         | 1.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.16%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.16%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 1.16%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 1.16%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.16%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.16%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.58%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.58%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.58%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 1         | 0.58%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 22.56%  |
| SK hynix            | 28        | 21.05%  |
| Unknown             | 19        | 14.29%  |
| Kingston            | 17        | 12.78%  |
| Micron Technology   | 13        | 9.77%   |
| Unknown             | 4         | 3.01%   |
| Elpida              | 3         | 2.26%   |
| A-DATA Technology   | 3         | 2.26%   |
| 48spaces            | 3         | 2.26%   |
| Transcend           | 2         | 1.5%    |
| Ramaxel Technology  | 2         | 1.5%    |
| Crucial             | 2         | 1.5%    |
| Corsair             | 2         | 1.5%    |
| Unknown (0x0809)    | 1         | 0.75%   |
| Silicon Power       | 1         | 0.75%   |
| GeIL                | 1         | 0.75%   |
| Apacer              | 1         | 0.75%   |
| AMD                 | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 2.78%   |
| Unknown                                                                   | 4         | 2.78%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 2.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 2.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 2.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 2.08%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 2.08%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 3         | 2.08%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 2         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 2         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.39%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 1.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 2         | 1.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.39%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 1.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 2         | 1.39%   |
| Kingston RAM 9905700-011.A00G 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.39%   |
| Unknown RAM Module 512MB SODIMM DRAM                                      | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 0.69%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                               | 1         | 0.69%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 1         | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 0.69%   |
| Unknown RAM Module 256MB SODIMM DRAM                                      | 1         | 0.69%   |
| Unknown RAM Module 256MB SODIMM DDR 100MT/s                               | 1         | 0.69%   |
| Unknown RAM Module 2560MB SODIMM DDR                                      | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR 800MT/s                              | 1         | 0.69%   |
| Unknown RAM Module 128MB SODIMM DRAM                                      | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266(3.8ns)MT/s                     | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM RAM                                      | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                     | 1         | 0.69%   |
| Unknown RAM Module 1024MB SODIMM DDR                                      | 1         | 0.69%   |
| Unknown (0x0809) RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.69%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s                            | 1         | 0.69%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                         | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 40.71%  |
| DDR3    | 34        | 30.09%  |
| DDR2    | 12        | 10.62%  |
| LPDDR3  | 6         | 5.31%   |
| DDR     | 5         | 4.42%   |
| SDRAM   | 3         | 2.65%   |
| DRAM    | 3         | 2.65%   |
| Unknown | 2         | 1.77%   |
| RAM     | 1         | 0.88%   |
| LPDDR5  | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 92.04%  |
| Row Of Chips | 7         | 6.19%   |
| DIMM         | 1         | 0.88%   |
| Chip         | 1         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 44        | 34.11%  |
| 4096  | 36        | 27.91%  |
| 2048  | 26        | 20.16%  |
| 1024  | 8         | 6.2%    |
| 16384 | 6         | 4.65%   |
| 512   | 4         | 3.1%    |
| 256   | 2         | 1.55%   |
| 32768 | 1         | 0.78%   |
| 2560  | 1         | 0.78%   |
| 128   | 1         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 15.25%  |
| 3200    | 17        | 14.41%  |
| 2667    | 16        | 13.56%  |
| 2400    | 12        | 10.17%  |
| 1333    | 11        | 9.32%   |
| Unknown | 10        | 8.47%   |
| 667     | 9         | 7.63%   |
| 800     | 6         | 5.08%   |
| 1867    | 5         | 4.24%   |
| 2133    | 4         | 3.39%   |
| 1067    | 3         | 2.54%   |
| 6400    | 1         | 0.85%   |
| 2933    | 1         | 0.85%   |
| 2048    | 1         | 0.85%   |
| 1334    | 1         | 0.85%   |
| 975     | 1         | 0.85%   |
| 266     | 1         | 0.85%   |
| 100     | 1         | 0.85%   |

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
| Chicony Electronics                    | 25        | 25%     |
| IMC Networks                           | 14        | 14%     |
| Realtek Semiconductor                  | 10        | 10%     |
| Microdia                               | 8         | 8%      |
| Acer                                   | 7         | 7%      |
| Suyin                                  | 5         | 5%      |
| Quanta                                 | 4         | 4%      |
| Lite-On Technology                     | 4         | 4%      |
| ALi                                    | 4         | 4%      |
| Syntek                                 | 3         | 3%      |
| Sunplus Innovation Technology          | 2         | 2%      |
| Silicon Motion                         | 2         | 2%      |
| ShineTech                              | 2         | 2%      |
| DigiTech                               | 2         | 2%      |
| Z-Star Microelectronics                | 1         | 1%      |
| SunplusIT                              | 1         | 1%      |
| Sonix Technology                       | 1         | 1%      |
| Ricoh                                  | 1         | 1%      |
| Luxvisions Innotech Limited            | 1         | 1%      |
| Intel                                  | 1         | 1%      |
| Denron                                 | 1         | 1%      |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 9         | 8.82%   |
| Microdia Integrated_Webcam_HD                       | 5         | 4.9%    |
| IMC Networks Integrated Camera                      | 5         | 4.9%    |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 2.94%   |
| Quanta VGA WebCam                                   | 3         | 2.94%   |
| ALi Gateway Webcam                                  | 3         | 2.94%   |
| Acer Lenovo EasyCamera                              | 3         | 2.94%   |
| Syntek EasyCamera                                   | 2         | 1.96%   |
| Silicon Motion WebCam SCX Series                    | 2         | 1.96%   |
| ShineTech HD Camera                                 | 2         | 1.96%   |
| Realtek Integrated Webcam                           | 2         | 1.96%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.96%   |
| Microdia Integrated Webcam                          | 2         | 1.96%   |
| Lite-On Integrated Camera                           | 2         | 1.96%   |
| Lite-On HP HD Camera                                | 2         | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.96%   |
| IMC Networks EasyCamera                             | 2         | 1.96%   |
| DigiTech WebCam SCB-0350M                           | 2         | 1.96%   |
| Z-Star Webcam                                       | 1         | 0.98%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.98%   |
| Suyin USB 2.0 UVC 1.3M WebCam                       | 1         | 0.98%   |
| Suyin HP Webcam                                     | 1         | 0.98%   |
| Suyin HD WebCam                                     | 1         | 0.98%   |
| Suyin HD Video WebCam                               | 1         | 0.98%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 0.98%   |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 0.98%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.98%   |
| Sunplus HD WebCam                                   | 1         | 0.98%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.98%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 0.98%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.98%   |
| Realtek USB Webcam                                  | 1         | 0.98%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.98%   |
| Realtek Integrated_Webcam_8M                        | 1         | 0.98%   |
| Quanta Realtek DMFT - RGB                           | 1         | 0.98%   |
| Microdia Integrated Webcam HD                       | 1         | 0.98%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.98%   |
| Intel WiMAX Connection 2400m                        | 1         | 0.98%   |
| IMC Networks UVC VGA Webcam                         | 1         | 0.98%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 0.98%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 32.14%  |
| Synaptics                  | 9         | 32.14%  |
| STMicroelectronics         | 3         | 10.71%  |
| Shenzhen Goodix Technology | 3         | 10.71%  |
| AuthenTec                  | 2         | 7.14%   |
| Upek                       | 1         | 3.57%   |
| Broadcom                   | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 17.86%  |
| STMicroelectronics Fingerprint Reader                                        | 3         | 10.71%  |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 10.71%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 7.14%   |
| AuthenTec AES1600                                                            | 2         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 3.57%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 3.57%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.57%   |
| Unknown                                                                      | 1         | 3.57%   |

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
| 1     | 47        | 34.06%  |
| 2     | 33        | 23.91%  |
| 0     | 19        | 13.77%  |
| 4     | 18        | 13.04%  |
| 3     | 16        | 11.59%  |
| 9     | 1         | 0.72%   |
| 8     | 1         | 0.72%   |
| 7     | 1         | 0.72%   |
| 6     | 1         | 0.72%   |
| 5     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 64        | 29.09%  |
| Net/wireless             | 39        | 17.73%  |
| Bluetooth                | 28        | 12.73%  |
| Card reader              | 27        | 12.27%  |
| Fingerprint reader       | 24        | 10.91%  |
| Firewire controller      | 12        | 5.45%   |
| Sound                    | 7         | 3.18%   |
| Graphics card            | 6         | 2.73%   |
| Storage                  | 5         | 2.27%   |
| Network                  | 4         | 1.82%   |
| Modem                    | 3         | 1.36%   |
| Storage/ata              | 1         | 0.45%   |

