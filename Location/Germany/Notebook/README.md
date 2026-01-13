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

Total: 669

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Deciso        | Netboard A20                | [7e9773146f](https://bsd-hardware.info/?probe=7e9773146f) | Dec 29, 2025 |
| Lenovo        | ThinkPad T420 4180W1A       | [0dadb9555c](https://bsd-hardware.info/?probe=0dadb9555c) | Dec 27, 2025 |
| Apple         | MacBookAir7,2               | [f94a1abe6d](https://bsd-hardware.info/?probe=f94a1abe6d) | Dec 25, 2025 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [b3d69c9aa9](https://bsd-hardware.info/?probe=b3d69c9aa9) | Dec 25, 2025 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [537990517b](https://bsd-hardware.info/?probe=537990517b) | Dec 21, 2025 |
| Deciso        | NetBoard-A10                | [1afa4d67cd](https://bsd-hardware.info/?probe=1afa4d67cd) | Dec 14, 2025 |
| Apple         | PowerBook6,8                | [6141d3968e](https://bsd-hardware.info/?probe=6141d3968e) | Dec 14, 2025 |
| Apple         | PowerBook6,8                | [7e623a9032](https://bsd-hardware.info/?probe=7e623a9032) | Dec 14, 2025 |
| Apple         | PowerBook6,8                | [d7fbfee97f](https://bsd-hardware.info/?probe=d7fbfee97f) | Dec 14, 2025 |
| Deciso        | NetBoard-A10                | [aae23bbb2f](https://bsd-hardware.info/?probe=aae23bbb2f) | Dec 10, 2025 |
| Apple         | PowerBook6,8                | [7138e42cc5](https://bsd-hardware.info/?probe=7138e42cc5) | Dec 01, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b8f03172e5](https://bsd-hardware.info/?probe=b8f03172e5) | Nov 29, 2025 |
| Dell          | Precision M4600             | [a6449e24ba](https://bsd-hardware.info/?probe=a6449e24ba) | Nov 20, 2025 |
| Deciso        | NetBoard-A20                | [8eabf4ecbe](https://bsd-hardware.info/?probe=8eabf4ecbe) | Nov 19, 2025 |
| Dell          | Precision 7510              | [e304ad6b53](https://bsd-hardware.info/?probe=e304ad6b53) | Nov 10, 2025 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [0eb4c268ce](https://bsd-hardware.info/?probe=0eb4c268ce) | Nov 06, 2025 |
| Acer          | Aspire One 721              | [0eaa05c265](https://bsd-hardware.info/?probe=0eaa05c265) | Nov 04, 2025 |
| Lenovo        | ThinkPad E590 20NB001AGE    | [619b6e28d5](https://bsd-hardware.info/?probe=619b6e28d5) | Nov 04, 2025 |
| Lenovo        | ThinkPad E590 20NB001AGE    | [f70a4e5f88](https://bsd-hardware.info/?probe=f70a4e5f88) | Nov 03, 2025 |
| Deciso        | NetBoard-A10                | [b4e4804f13](https://bsd-hardware.info/?probe=b4e4804f13) | Nov 01, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | [9138026580](https://bsd-hardware.info/?probe=9138026580) | Oct 23, 2025 |
| Lenovo        | ThinkPad Edge E531 68856... | [82e3af4243](https://bsd-hardware.info/?probe=82e3af4243) | Oct 15, 2025 |
| Lenovo        | ThinkPad X260 20F5S4Y80V    | [5e6a9e1927](https://bsd-hardware.info/?probe=5e6a9e1927) | Oct 15, 2025 |
| Deciso        | NetBoard-A20                | [b7c5de7267](https://bsd-hardware.info/?probe=b7c5de7267) | Oct 15, 2025 |
| Dell          | XPS 15 9560                 | [edd7a79478](https://bsd-hardware.info/?probe=edd7a79478) | Oct 05, 2025 |
| Dell          | XPS 15 9560                 | [f7eea5acab](https://bsd-hardware.info/?probe=f7eea5acab) | Sep 28, 2025 |
| SZ Reachin... | DreamQuest Pro Plus         | [e8d1ba986d](https://bsd-hardware.info/?probe=e8d1ba986d) | Sep 27, 2025 |
| Deciso        | Netboard A20                | [4f4b1784b9](https://bsd-hardware.info/?probe=4f4b1784b9) | Sep 22, 2025 |
| Unknown       | Unknown                     | [7acbb22a0b](https://bsd-hardware.info/?probe=7acbb22a0b) | Sep 18, 2025 |
| Lenovo        | ThinkPad E590 20NB0016SP    | [1411669996](https://bsd-hardware.info/?probe=1411669996) | Sep 16, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [be8b97c582](https://bsd-hardware.info/?probe=be8b97c582) | Sep 09, 2025 |
| Lenovo        | ThinkPad T580 20LAS1KA00    | [89a15e05f2](https://bsd-hardware.info/?probe=89a15e05f2) | Sep 09, 2025 |
| Deciso        | NetBoard-A10                | [32d12bb63e](https://bsd-hardware.info/?probe=32d12bb63e) | Sep 08, 2025 |
| Dell          | XPS 15 9560                 | [04d327f554](https://bsd-hardware.info/?probe=04d327f554) | Aug 29, 2025 |
| Unknown       | Unknown                     | [380533dd40](https://bsd-hardware.info/?probe=380533dd40) | Aug 28, 2025 |
| Fujitsu       | LIFEBOOK A530               | [4a3ab3d46c](https://bsd-hardware.info/?probe=4a3ab3d46c) | Aug 28, 2025 |
| Dell          | XPS 15 9560                 | [19f12b8a48](https://bsd-hardware.info/?probe=19f12b8a48) | Aug 26, 2025 |
| Dell          | XPS 15 9560                 | [dd423a0dd3](https://bsd-hardware.info/?probe=dd423a0dd3) | Aug 25, 2025 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [27f17a9a16](https://bsd-hardware.info/?probe=27f17a9a16) | Aug 12, 2025 |
| Dell          | Latitude E6400              | [4094f1a022](https://bsd-hardware.info/?probe=4094f1a022) | Aug 02, 2025 |
| Acer          | Aspire V3-571G              | [6e28f345f2](https://bsd-hardware.info/?probe=6e28f345f2) | Jul 30, 2025 |
| Fujitsu Si... | CELSIUS H270                | [17532c205c](https://bsd-hardware.info/?probe=17532c205c) | Jul 30, 2025 |
| Lenovo        | ThinkPad T530 2394CTO       | [b94dd608c7](https://bsd-hardware.info/?probe=b94dd608c7) | Jul 29, 2025 |
| Lenovo        | ThinkPad T420 4236C92       | [6557f903e8](https://bsd-hardware.info/?probe=6557f903e8) | Jul 22, 2025 |
| Dell          | Latitude 7280               | [01a83f46f7](https://bsd-hardware.info/?probe=01a83f46f7) | Jul 22, 2025 |
| Lenovo        | ThinkPad T420 4236C92       | [07ef4aef0f](https://bsd-hardware.info/?probe=07ef4aef0f) | Jul 22, 2025 |
| Dell          | XPS 9320                    | [6fce7f517f](https://bsd-hardware.info/?probe=6fce7f517f) | Jul 18, 2025 |
| Lenovo        | IdeaPadFlex 15 20309        | [d8fcb45611](https://bsd-hardware.info/?probe=d8fcb45611) | Jul 16, 2025 |
| Unknown       | Unknown                     | [94e7ba6834](https://bsd-hardware.info/?probe=94e7ba6834) | Jul 13, 2025 |
| Dell          | Latitude 7280               | [818f642604](https://bsd-hardware.info/?probe=818f642604) | Jul 09, 2025 |
| Deciso        | Netboard A20                | [437e0aaef5](https://bsd-hardware.info/?probe=437e0aaef5) | Jun 28, 2025 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [50b9580d13](https://bsd-hardware.info/?probe=50b9580d13) | Jun 16, 2025 |
| Apple         | MacBookAir7,2               | [90aebce5fd](https://bsd-hardware.info/?probe=90aebce5fd) | May 30, 2025 |
| Apple         | MacBookAir7,2               | [90d94c1634](https://bsd-hardware.info/?probe=90d94c1634) | May 30, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [572b1054a6](https://bsd-hardware.info/?probe=572b1054a6) | May 14, 2025 |
| Lenovo        | ThinkPad X230 2325A39       | [41db2b37f5](https://bsd-hardware.info/?probe=41db2b37f5) | May 01, 2025 |
| Lenovo        | ThinkPad Edge E545 20B20... | [4e2ea48556](https://bsd-hardware.info/?probe=4e2ea48556) | May 01, 2025 |
| Panasonic     | CF-C1BD06EFG                | [72af222238](https://bsd-hardware.info/?probe=72af222238) | May 01, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | [7f491a1236](https://bsd-hardware.info/?probe=7f491a1236) | Apr 27, 2025 |
| Lenovo        | ThinkPad Edge E540 20C60... | [8334cd4f0e](https://bsd-hardware.info/?probe=8334cd4f0e) | Apr 26, 2025 |
| Deciso        | NetBoard-A10 Gen.3          | [4c33946a20](https://bsd-hardware.info/?probe=4c33946a20) | Apr 19, 2025 |
| Apple         | MacBookPro13,1              | [595cae3f15](https://bsd-hardware.info/?probe=595cae3f15) | Apr 13, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [34d7a9fb56](https://bsd-hardware.info/?probe=34d7a9fb56) | Apr 01, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M3C... | [c97f313465](https://bsd-hardware.info/?probe=c97f313465) | Mar 25, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | [d0e4fd1ff7](https://bsd-hardware.info/?probe=d0e4fd1ff7) | Mar 22, 2025 |
| Fujitsu       | LIFEBOOK U745               | [51a0ad3f62](https://bsd-hardware.info/?probe=51a0ad3f62) | Mar 14, 2025 |
| Lenovo        | ThinkPad X201 3323K2M       | [152f2fe4d7](https://bsd-hardware.info/?probe=152f2fe4d7) | Mar 11, 2025 |
| Dell          | Inspiron One 2310           | [13c9c06011](https://bsd-hardware.info/?probe=13c9c06011) | Mar 11, 2025 |
| Sony          | SVE1511A1EW                 | [9cfe39bf5c](https://bsd-hardware.info/?probe=9cfe39bf5c) | Mar 09, 2025 |
| Lenovo        | ThinkPad X230 2325G70       | [51f976c6eb](https://bsd-hardware.info/?probe=51f976c6eb) | Mar 09, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [3b96741510](https://bsd-hardware.info/?probe=3b96741510) | Mar 07, 2025 |
| HUAWEI        | MACHR-WX9                   | [b5535a2385](https://bsd-hardware.info/?probe=b5535a2385) | Mar 05, 2025 |
| Lenovo        | ThinkPad T490 20N3S51700    | [1252e6de60](https://bsd-hardware.info/?probe=1252e6de60) | Feb 27, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [dfb99d90dc](https://bsd-hardware.info/?probe=dfb99d90dc) | Feb 17, 2025 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [3837e6f88b](https://bsd-hardware.info/?probe=3837e6f88b) | Feb 11, 2025 |
| Deciso        | NetBoard-A20                | [d19ffbe6b1](https://bsd-hardware.info/?probe=d19ffbe6b1) | Feb 09, 2025 |
| Deciso        | NetBoard-A20                | [2cc69c2963](https://bsd-hardware.info/?probe=2cc69c2963) | Feb 05, 2025 |
| Acer          | TravelMate P648-G3-M        | [a36092b332](https://bsd-hardware.info/?probe=a36092b332) | Feb 04, 2025 |
| HP            | ZBook 15u G2                | [a1ca48576f](https://bsd-hardware.info/?probe=a1ca48576f) | Jan 31, 2025 |
| Lenovo        | ThinkPad Edge E335 33557... | [883ca16dc9](https://bsd-hardware.info/?probe=883ca16dc9) | Jan 30, 2025 |
| Lenovo        | ThinkPad Edge E335 33557... | [02ed9624d3](https://bsd-hardware.info/?probe=02ed9624d3) | Jan 30, 2025 |
| HUAWEI        | EUL-WX9                     | [7f7d2f3ca5](https://bsd-hardware.info/?probe=7f7d2f3ca5) | Jan 21, 2025 |
| Deciso        | NetBoard-A20                | [ae68d72ef1](https://bsd-hardware.info/?probe=ae68d72ef1) | Jan 20, 2025 |
| Deciso        | NetBoard-A10_Gen.3          | [e73a3a31fd](https://bsd-hardware.info/?probe=e73a3a31fd) | Jan 17, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | [a87754674c](https://bsd-hardware.info/?probe=a87754674c) | Jan 15, 2025 |
| Gigabyte      | A5 K1                       | [a275684fd0](https://bsd-hardware.info/?probe=a275684fd0) | Jan 14, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 21G2... | [cf293b34e1](https://bsd-hardware.info/?probe=cf293b34e1) | Jan 14, 2025 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS2... | [74c4c50b03](https://bsd-hardware.info/?probe=74c4c50b03) | Jan 13, 2025 |
| HP            | ZBook 14                    | [4fe5ab3a38](https://bsd-hardware.info/?probe=4fe5ab3a38) | Jan 12, 2025 |
| Deciso        | NetBoard-A20                | [c58a65e032](https://bsd-hardware.info/?probe=c58a65e032) | Jan 12, 2025 |
| Apple         | MacBookAir6,2               | [916585cf8f](https://bsd-hardware.info/?probe=916585cf8f) | Jan 07, 2025 |
| Acer          | AO532h                      | [00b8f9da06](https://bsd-hardware.info/?probe=00b8f9da06) | Jan 06, 2025 |
| Deciso        | NetBoard-A10                | [3ce7f19f0b](https://bsd-hardware.info/?probe=3ce7f19f0b) | Jan 02, 2025 |
| Deciso        | OPNsense Appliance          | [5185740988](https://bsd-hardware.info/?probe=5185740988) | Dec 24, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [9f6f476877](https://bsd-hardware.info/?probe=9f6f476877) | Dec 14, 2024 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [08608b8653](https://bsd-hardware.info/?probe=08608b8653) | Dec 10, 2024 |
| Unknown       | Unknown                     | [0fa7499053](https://bsd-hardware.info/?probe=0fa7499053) | Dec 09, 2024 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [4e006e39f5](https://bsd-hardware.info/?probe=4e006e39f5) | Dec 06, 2024 |
| Dell          | Latitude 5591               | [fd917cf2f0](https://bsd-hardware.info/?probe=fd917cf2f0) | Dec 04, 2024 |
| HP            | 250 G3                      | [102fa9b597](https://bsd-hardware.info/?probe=102fa9b597) | Dec 04, 2024 |
| Dell          | Latitude E6540              | [7e1c664559](https://bsd-hardware.info/?probe=7e1c664559) | Dec 03, 2024 |
| Dell          | Latitude 5591               | [9515359a66](https://bsd-hardware.info/?probe=9515359a66) | Dec 03, 2024 |
| Fujitsu       | LIFEBOOK U727               | [804be89553](https://bsd-hardware.info/?probe=804be89553) | Dec 02, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [c97d6bf769](https://bsd-hardware.info/?probe=c97d6bf769) | Nov 29, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | [2bd04e188a](https://bsd-hardware.info/?probe=2bd04e188a) | Nov 29, 2024 |
| Framework     | Laptop 13 (Intel Core Ul... | [41ab1da986](https://bsd-hardware.info/?probe=41ab1da986) | Nov 29, 2024 |
| Deciso        | NetBoard-A20                | [5ab919a780](https://bsd-hardware.info/?probe=5ab919a780) | Nov 25, 2024 |
| Deciso        | NetBoard-A20                | [3ec1ba816d](https://bsd-hardware.info/?probe=3ec1ba816d) | Nov 22, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [8b34dd537f](https://bsd-hardware.info/?probe=8b34dd537f) | Nov 13, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [aa3a0567b3](https://bsd-hardware.info/?probe=aa3a0567b3) | Nov 07, 2024 |
| Deciso        | NetBoard-A20                | [6161c59ddd](https://bsd-hardware.info/?probe=6161c59ddd) | Nov 04, 2024 |
| Deciso        | NetBoard-A20                | [48f5da11ca](https://bsd-hardware.info/?probe=48f5da11ca) | Nov 02, 2024 |
| Seco          | UDOO x86                    | [16eb7b7498](https://bsd-hardware.info/?probe=16eb7b7498) | Nov 02, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [42d346a4b2](https://bsd-hardware.info/?probe=42d346a4b2) | Oct 31, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [0f2bd2dd8a](https://bsd-hardware.info/?probe=0f2bd2dd8a) | Oct 30, 2024 |
| HP            | Pavilion Notebook           | [4609004e3e](https://bsd-hardware.info/?probe=4609004e3e) | Oct 30, 2024 |
| Schenker      | SLIM15 SSL15L19             | [e2f93ce841](https://bsd-hardware.info/?probe=e2f93ce841) | Oct 28, 2024 |
| Deciso        | NetBoard-A20                | [503208f52b](https://bsd-hardware.info/?probe=503208f52b) | Oct 25, 2024 |
| Deciso        | NetBoard-A20                | [8bede3f5d2](https://bsd-hardware.info/?probe=8bede3f5d2) | Oct 25, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [bd9a89adda](https://bsd-hardware.info/?probe=bd9a89adda) | Oct 24, 2024 |
| HP            | EliteBook 840 G3            | [4e4e2da2fc](https://bsd-hardware.info/?probe=4e4e2da2fc) | Oct 14, 2024 |
| Unknown       | Unknown                     | [52b783d430](https://bsd-hardware.info/?probe=52b783d430) | Oct 01, 2024 |
| Apple         | MacBookPro11,1              | [b9eba86e8e](https://bsd-hardware.info/?probe=b9eba86e8e) | Sep 29, 2024 |
| Acer          | Aspire VN7-571G             | [e67b6464df](https://bsd-hardware.info/?probe=e67b6464df) | Sep 29, 2024 |
| Framework     | Laptop                      | [db5ecf38bc](https://bsd-hardware.info/?probe=db5ecf38bc) | Sep 25, 2024 |
| NEC Comput... | PC-LL750HS6R                | [edd3f8e3e6](https://bsd-hardware.info/?probe=edd3f8e3e6) | Sep 23, 2024 |
| Dell          | Latitude 5591               | [7f45ab1b0c](https://bsd-hardware.info/?probe=7f45ab1b0c) | Sep 21, 2024 |
| Micro Comp... | Venus series                | [ccd74590c5](https://bsd-hardware.info/?probe=ccd74590c5) | Sep 20, 2024 |
| Dell          | Latitude E6540              | [e8bdb7007b](https://bsd-hardware.info/?probe=e8bdb7007b) | Sep 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8657f5a0d9](https://bsd-hardware.info/?probe=8657f5a0d9) | Sep 19, 2024 |
| Unknown       | Unknown                     | [74eaa92b4b](https://bsd-hardware.info/?probe=74eaa92b4b) | Sep 17, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [f2a74cd513](https://bsd-hardware.info/?probe=f2a74cd513) | Sep 17, 2024 |
| Unknown       | Unknown                     | [7bf84c291d](https://bsd-hardware.info/?probe=7bf84c291d) | Sep 14, 2024 |
| Lenovo        | ThinkPad T580 20L90024GE    | [5fcf7e4608](https://bsd-hardware.info/?probe=5fcf7e4608) | Sep 01, 2024 |
| HP            | EliteBook 840 G1            | [d2acf5ba58](https://bsd-hardware.info/?probe=d2acf5ba58) | Aug 27, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [beffed77d6](https://bsd-hardware.info/?probe=beffed77d6) | Aug 26, 2024 |
| Unknown       | Unknown                     | [d5ae4936d4](https://bsd-hardware.info/?probe=d5ae4936d4) | Aug 24, 2024 |
| Acer          | TravelMate P653-MG          | [dc474eaaca](https://bsd-hardware.info/?probe=dc474eaaca) | Aug 16, 2024 |
| Fujitsu       | LIFEBOOK U727               | [d3eb2cd128](https://bsd-hardware.info/?probe=d3eb2cd128) | Aug 14, 2024 |
| Apple         | MacBookAir7,2               | [a7587990e0](https://bsd-hardware.info/?probe=a7587990e0) | Aug 11, 2024 |
| Deciso        | Netboard A20                | [2d3c497337](https://bsd-hardware.info/?probe=2d3c497337) | Aug 07, 2024 |
| Lenovo        | ThinkPad T580 20LAS1KA00    | [7809ec60bf](https://bsd-hardware.info/?probe=7809ec60bf) | Jul 28, 2024 |
| Fujitsu       | LIFEBOOK U727               | [9987b28027](https://bsd-hardware.info/?probe=9987b28027) | Jul 24, 2024 |
| Deciso        | NetBoard-A10_Gen.3          | [8bae65bb0d](https://bsd-hardware.info/?probe=8bae65bb0d) | Jul 24, 2024 |
| Google        | Akemi                       | [039591ce70](https://bsd-hardware.info/?probe=039591ce70) | Jul 23, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS2... | [bf0783a496](https://bsd-hardware.info/?probe=bf0783a496) | Jul 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [3183ea3c76](https://bsd-hardware.info/?probe=3183ea3c76) | Jul 20, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [0232a3609d](https://bsd-hardware.info/?probe=0232a3609d) | Jul 12, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3f63a359bd](https://bsd-hardware.info/?probe=3f63a359bd) | Jul 12, 2024 |
| HP            | EliteBook 820 G1            | [0de2223643](https://bsd-hardware.info/?probe=0de2223643) | Jul 11, 2024 |
| IGEL Techn... | H830C                       | [8f800ac3ac](https://bsd-hardware.info/?probe=8f800ac3ac) | Jun 25, 2024 |
| Acer          | Aspire V3-372               | [aa282936fa](https://bsd-hardware.info/?probe=aa282936fa) | Jun 22, 2024 |
| Deciso        | Netboard A20                | [e8bddba50c](https://bsd-hardware.info/?probe=e8bddba50c) | Jun 20, 2024 |
| Micro Comp... | Venus series                | [4194358814](https://bsd-hardware.info/?probe=4194358814) | Jun 17, 2024 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | [e41fe01667](https://bsd-hardware.info/?probe=e41fe01667) | Jun 16, 2024 |
| Deciso        | Netboard A20                | [c9880ca7ee](https://bsd-hardware.info/?probe=c9880ca7ee) | Jun 12, 2024 |
| Acer          | TravelMate P653-MG          | [f00a8363c2](https://bsd-hardware.info/?probe=f00a8363c2) | Jun 05, 2024 |
| Lenovo        | ThinkPad T470 20HD000EMX    | [40ab3ce43b](https://bsd-hardware.info/?probe=40ab3ce43b) | Jun 03, 2024 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [b11a20d476](https://bsd-hardware.info/?probe=b11a20d476) | Jun 02, 2024 |
| Micro Comp... | Venus series                | [474260b268](https://bsd-hardware.info/?probe=474260b268) | Jun 01, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | [f65532b888](https://bsd-hardware.info/?probe=f65532b888) | Jun 01, 2024 |
| TUXEDO        | Pulse 15 Gen1               | [76cd424940](https://bsd-hardware.info/?probe=76cd424940) | May 31, 2024 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [e8b73c0891](https://bsd-hardware.info/?probe=e8b73c0891) | May 29, 2024 |
| ASUSTek       | N50Vc                       | [69d37366c1](https://bsd-hardware.info/?probe=69d37366c1) | May 27, 2024 |
| Lenovo        | ThinkPad YOGA260 20FES2X... | [e49d3164c9](https://bsd-hardware.info/?probe=e49d3164c9) | May 26, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | [0ce512e3ba](https://bsd-hardware.info/?probe=0ce512e3ba) | May 25, 2024 |
| Unknown       | Unknown                     | [483c709b6c](https://bsd-hardware.info/?probe=483c709b6c) | May 17, 2024 |
| Apple         | MacBookPro5,5               | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| HP            | 255 G8 Notebook PC          | [4878c18c8a](https://bsd-hardware.info/?probe=4878c18c8a) | May 01, 2024 |
| Deciso        | Netboard A20                | [c04565ec24](https://bsd-hardware.info/?probe=c04565ec24) | Apr 30, 2024 |
| System76      | Pangolin                    | [d47c9a5d44](https://bsd-hardware.info/?probe=d47c9a5d44) | Apr 26, 2024 |
| Lenovo        | ThinkPad T400 6474E18       | [fcd3339ec5](https://bsd-hardware.info/?probe=fcd3339ec5) | Apr 21, 2024 |
| Deciso        | NetBoard-A20                | [82519e798c](https://bsd-hardware.info/?probe=82519e798c) | Apr 18, 2024 |
| Unknown       | Unknown                     | [5886bb9659](https://bsd-hardware.info/?probe=5886bb9659) | Apr 18, 2024 |
| Lenovo        | ThinkPad T460 20FMA09CGE    | [c7219eb82e](https://bsd-hardware.info/?probe=c7219eb82e) | Apr 15, 2024 |
| Deciso        | NetBoard-A20                | [f6d9d3eaf2](https://bsd-hardware.info/?probe=f6d9d3eaf2) | Apr 03, 2024 |
| Apple         | MacBookAir7,2               | [a596a6f2fc](https://bsd-hardware.info/?probe=a596a6f2fc) | Mar 30, 2024 |
| Shuttle       | DS77U                       | [b065bf5918](https://bsd-hardware.info/?probe=b065bf5918) | Mar 27, 2024 |
| Fujitsu       | LIFEBOOK U727               | [76e6dff995](https://bsd-hardware.info/?probe=76e6dff995) | Mar 27, 2024 |
| Apple         | MacBookAir7,2               | [a5003ca56a](https://bsd-hardware.info/?probe=a5003ca56a) | Mar 25, 2024 |
| Deciso        | DEC2700 - OPNsense Appli... | [7617a6faa1](https://bsd-hardware.info/?probe=7617a6faa1) | Mar 19, 2024 |
| Dell          | Latitude D830               | [832440d0c3](https://bsd-hardware.info/?probe=832440d0c3) | Mar 17, 2024 |
| Google        | Cave                        | [d9df48c781](https://bsd-hardware.info/?probe=d9df48c781) | Mar 16, 2024 |
| Apple         | MacBookAir7,2               | [58cc0f695b](https://bsd-hardware.info/?probe=58cc0f695b) | Mar 14, 2024 |
| TULPAR        | A5 V20.3                    | [476d91b2cf](https://bsd-hardware.info/?probe=476d91b2cf) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [4b52e91e24](https://bsd-hardware.info/?probe=4b52e91e24) | Mar 13, 2024 |
| Acer          | Aspire V5-573G              | [59445c5f19](https://bsd-hardware.info/?probe=59445c5f19) | Mar 12, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0ceb5cfbf8](https://bsd-hardware.info/?probe=0ceb5cfbf8) | Mar 10, 2024 |
| Deciso        | NetBoard-A20                | [2e0ce432cb](https://bsd-hardware.info/?probe=2e0ce432cb) | Mar 07, 2024 |
| Deciso        | NetBoard-A20                | [7c73382c9d](https://bsd-hardware.info/?probe=7c73382c9d) | Feb 26, 2024 |
| Dell          | Latitude E5510              | [4155c54a6c](https://bsd-hardware.info/?probe=4155c54a6c) | Feb 19, 2024 |
| Dell          | Latitude E5510              | [1bc1ac66c3](https://bsd-hardware.info/?probe=1bc1ac66c3) | Feb 18, 2024 |
| Deciso        | NetBoard-A10                | [8403713b4f](https://bsd-hardware.info/?probe=8403713b4f) | Feb 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [2a4911715a](https://bsd-hardware.info/?probe=2a4911715a) | Feb 07, 2024 |
| Apple         | MacBookPro11,1              | [c77173c2f3](https://bsd-hardware.info/?probe=c77173c2f3) | Feb 04, 2024 |
| Deciso        | NetBoard-A10                | [118bac872e](https://bsd-hardware.info/?probe=118bac872e) | Feb 03, 2024 |
| Apple         | MacBookPro8,2               | [95f19036db](https://bsd-hardware.info/?probe=95f19036db) | Feb 03, 2024 |
| TUXEDO        | Aura 15 Gen1                | [4768e0001d](https://bsd-hardware.info/?probe=4768e0001d) | Feb 01, 2024 |
| Dell          | Precision M4700             | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Unknown       | Unknown                     | [6fe553c729](https://bsd-hardware.info/?probe=6fe553c729) | Jan 21, 2024 |
| Unknown       | Unknown                     | [e85605ed72](https://bsd-hardware.info/?probe=e85605ed72) | Jan 21, 2024 |
| Apple         | MacBookAir4,1               | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude E7450              | [f2216c5d0f](https://bsd-hardware.info/?probe=f2216c5d0f) | Jan 21, 2024 |
| BESSTAR Te... | U820                        | [9d1b8fbbd5](https://bsd-hardware.info/?probe=9d1b8fbbd5) | Jan 18, 2024 |
| BESSTAR Te... | U820                        | [7e38f4e795](https://bsd-hardware.info/?probe=7e38f4e795) | Jan 18, 2024 |
| Apple         | MacBookAir4,1               | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| Unknown       | Unknown                     | [4b22a105d7](https://bsd-hardware.info/?probe=4b22a105d7) | Jan 11, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [0f475f8e5d](https://bsd-hardware.info/?probe=0f475f8e5d) | Jan 10, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b21d0ae92](https://bsd-hardware.info/?probe=6b21d0ae92) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Unknown       | Unknown                     | [c1d43f83f4](https://bsd-hardware.info/?probe=c1d43f83f4) | Jan 02, 2024 |
| HP            | EliteBook 2540p             | [c915c03729](https://bsd-hardware.info/?probe=c915c03729) | Dec 30, 2023 |
| Deciso        | NetBoard-A10                | [66f7dd1f06](https://bsd-hardware.info/?probe=66f7dd1f06) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [b6c3c05155](https://bsd-hardware.info/?probe=b6c3c05155) | Dec 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8LW00    | [32c06c5669](https://bsd-hardware.info/?probe=32c06c5669) | Dec 23, 2023 |
| CSL-Comput... | C15 v3                      | [dd93594896](https://bsd-hardware.info/?probe=dd93594896) | Dec 16, 2023 |
| Dell          | XPS 13 9370                 | [b6845a3e54](https://bsd-hardware.info/?probe=b6845a3e54) | Dec 15, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c197b26909](https://bsd-hardware.info/?probe=c197b26909) | Dec 14, 2023 |
| Dell          | Latitude E6540              | [77a9b10ab9](https://bsd-hardware.info/?probe=77a9b10ab9) | Dec 13, 2023 |
| HP            | EliteBook 840 G6            | [7476cc6440](https://bsd-hardware.info/?probe=7476cc6440) | Dec 06, 2023 |
| Apple         | MacBookAir7,2               | [3784a39a41](https://bsd-hardware.info/?probe=3784a39a41) | Dec 06, 2023 |
| Wortmann      | TERRA_MOBILE_1541           | [63f1a71855](https://bsd-hardware.info/?probe=63f1a71855) | Dec 04, 2023 |
| Unknown       | Unknown                     | [7d3416a30f](https://bsd-hardware.info/?probe=7d3416a30f) | Nov 30, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [e98e7bcab5](https://bsd-hardware.info/?probe=e98e7bcab5) | Nov 29, 2023 |
| Unknown       | Unknown                     | [55339dbfab](https://bsd-hardware.info/?probe=55339dbfab) | Nov 26, 2023 |
| Unknown       | Unknown                     | [ff855b549e](https://bsd-hardware.info/?probe=ff855b549e) | Nov 20, 2023 |
| Panasonic     | CF-31-5                     | [8771ab6139](https://bsd-hardware.info/?probe=8771ab6139) | Nov 18, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [9061ad4228](https://bsd-hardware.info/?probe=9061ad4228) | Nov 17, 2023 |
| Dell          | Inspiron 1525               | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Unknown       | Unknown                     | [61c7e94f23](https://bsd-hardware.info/?probe=61c7e94f23) | Nov 06, 2023 |
| Unknown       | Unknown                     | [316be7bb33](https://bsd-hardware.info/?probe=316be7bb33) | Nov 06, 2023 |
| Dell          | Latitude E6540              | [a26912fd0d](https://bsd-hardware.info/?probe=a26912fd0d) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [4f9885c454](https://bsd-hardware.info/?probe=4f9885c454) | Nov 05, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [a9448cf3b5](https://bsd-hardware.info/?probe=a9448cf3b5) | Nov 04, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [19514dd0bd](https://bsd-hardware.info/?probe=19514dd0bd) | Nov 03, 2023 |
| Lenovo        | ThinkPad X230 23205UG       | [f204abc5fc](https://bsd-hardware.info/?probe=f204abc5fc) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [09cf753c7a](https://bsd-hardware.info/?probe=09cf753c7a) | Oct 26, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [7a57e0a112](https://bsd-hardware.info/?probe=7a57e0a112) | Oct 21, 2023 |
| Unknown       | Unknown                     | [363b63c1a1](https://bsd-hardware.info/?probe=363b63c1a1) | Oct 18, 2023 |
| ASUSTek       | N552VX                      | [f927cf5ba4](https://bsd-hardware.info/?probe=f927cf5ba4) | Oct 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | [72a9b731f6](https://bsd-hardware.info/?probe=72a9b731f6) | Oct 14, 2023 |
| Deciso        | Netboard A20                | [879efbe255](https://bsd-hardware.info/?probe=879efbe255) | Oct 14, 2023 |
| Lenovo        | ThinkPad X250 20CM004VFR    | [e4ab2acd8d](https://bsd-hardware.info/?probe=e4ab2acd8d) | Oct 11, 2023 |
| Unknown       | Unknown                     | [57e5ab8786](https://bsd-hardware.info/?probe=57e5ab8786) | Oct 08, 2023 |
| Unknown       | Unknown                     | [1f7ab105e3](https://bsd-hardware.info/?probe=1f7ab105e3) | Oct 08, 2023 |
| Dell          | Latitude 5591               | [8f6ca1e82a](https://bsd-hardware.info/?probe=8f6ca1e82a) | Oct 03, 2023 |
| Deciso        | NetBoard-A10                | [5524017014](https://bsd-hardware.info/?probe=5524017014) | Oct 01, 2023 |
| Unknown       | Unknown                     | [7cfd3d40eb](https://bsd-hardware.info/?probe=7cfd3d40eb) | Sep 30, 2023 |
| Dell          | Latitude 5591               | [c30943def8](https://bsd-hardware.info/?probe=c30943def8) | Sep 28, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b31f8c12f8](https://bsd-hardware.info/?probe=b31f8c12f8) | Sep 24, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [de1bdf0601](https://bsd-hardware.info/?probe=de1bdf0601) | Sep 21, 2023 |
| Apple         | MacBookPro11,1              | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Alienware     | m15                         | [609d2ce1ce](https://bsd-hardware.info/?probe=609d2ce1ce) | Sep 14, 2023 |
| Deciso        | NetBoard-A10                | [0068732d33](https://bsd-hardware.info/?probe=0068732d33) | Sep 13, 2023 |
| HP            | ProBook 4530s               | [0b47c15c42](https://bsd-hardware.info/?probe=0b47c15c42) | Sep 12, 2023 |
| HP            | ProBook 4530s               | [4b6daa1f1c](https://bsd-hardware.info/?probe=4b6daa1f1c) | Sep 12, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| Deciso        | NetBoard-A10                | [f95d1da00c](https://bsd-hardware.info/?probe=f95d1da00c) | Sep 01, 2023 |
| Dell          | Latitude 5591               | [972da999fb](https://bsd-hardware.info/?probe=972da999fb) | Aug 18, 2023 |
| Dell          | Latitude 5591               | [a599361016](https://bsd-hardware.info/?probe=a599361016) | Aug 13, 2023 |
| Unknown       | Unknown                     | [09d17597cf](https://bsd-hardware.info/?probe=09d17597cf) | Aug 01, 2023 |
| Unknown       | Unknown                     | [2a2e7a98e3](https://bsd-hardware.info/?probe=2a2e7a98e3) | Aug 01, 2023 |
| Deciso        | NetBoard-A10                | [65667b2f29](https://bsd-hardware.info/?probe=65667b2f29) | Aug 01, 2023 |
| Deciso        | NetBoard-A20                | [9bd5d8fd54](https://bsd-hardware.info/?probe=9bd5d8fd54) | Jul 31, 2023 |
| Deciso        | NetBoard-A10                | [42fcdacbf7](https://bsd-hardware.info/?probe=42fcdacbf7) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | [f3aa06579e](https://bsd-hardware.info/?probe=f3aa06579e) | Jul 20, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Deciso        | NetBoard-A10                | [535720220a](https://bsd-hardware.info/?probe=535720220a) | Jul 13, 2023 |
| Tactus        | GeoBook 140                 | [4b7383c876](https://bsd-hardware.info/?probe=4b7383c876) | Jul 11, 2023 |
| Lenovo        | ThinkPad X250 20CLS13Q06    | [c318ab3cc7](https://bsd-hardware.info/?probe=c318ab3cc7) | Jul 09, 2023 |
| Unknown       | Unknown                     | [3725d44c33](https://bsd-hardware.info/?probe=3725d44c33) | Jul 01, 2023 |
| Deciso        | NetBoard-A10                | [2eff359d8f](https://bsd-hardware.info/?probe=2eff359d8f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Dell          | Latitude E6520              | [98868960d5](https://bsd-hardware.info/?probe=98868960d5) | Jun 18, 2023 |
| Samsung       | NC210/NC110                 | [06f5a9210b](https://bsd-hardware.info/?probe=06f5a9210b) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| Lenovo        | ThinkPad T530 2429AP0       | [ddf37e7b17](https://bsd-hardware.info/?probe=ddf37e7b17) | Jun 13, 2023 |
| Samsung       | NC210/NC110                 | [dad27d6099](https://bsd-hardware.info/?probe=dad27d6099) | Jun 13, 2023 |
| HP            | 15                          | [4664b4c93f](https://bsd-hardware.info/?probe=4664b4c93f) | Jun 11, 2023 |
| Toshiba       | Satellite C70-B             | [cf9ed85e65](https://bsd-hardware.info/?probe=cf9ed85e65) | Jun 05, 2023 |
| Toshiba       | Satellite C70-B             | [fc66ebba25](https://bsd-hardware.info/?probe=fc66ebba25) | Jun 05, 2023 |
| Deciso        | NetBoard-A10                | [ab3919bc32](https://bsd-hardware.info/?probe=ab3919bc32) | Jun 04, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad T560 20FJS03Q00    | [a2110471aa](https://bsd-hardware.info/?probe=a2110471aa) | May 18, 2023 |
| Deciso        | NetBoard-A10                | [37ee98e0b6](https://bsd-hardware.info/?probe=37ee98e0b6) | May 09, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Deciso        | NetBoard-A10                | [79c36f752c](https://bsd-hardware.info/?probe=79c36f752c) | Apr 28, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Dell          | Latitude 7280               | [254acb5df8](https://bsd-hardware.info/?probe=254acb5df8) | Apr 20, 2023 |
| Lenovo        | ThinkPad X201 3626WNP       | [d642970071](https://bsd-hardware.info/?probe=d642970071) | Apr 19, 2023 |
| Unknown       | Unknown                     | [c221bccd5d](https://bsd-hardware.info/?probe=c221bccd5d) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| IGEL Techn... | M340C                       | [6c8b2b7af7](https://bsd-hardware.info/?probe=6c8b2b7af7) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| ASUSTek       | G750JS                      | [bb6117addd](https://bsd-hardware.info/?probe=bb6117addd) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6d9c564a33](https://bsd-hardware.info/?probe=6d9c564a33) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Acer          | Aspire V3-112P              | [104c10f9b0](https://bsd-hardware.info/?probe=104c10f9b0) | Mar 14, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [1a2543f92f](https://bsd-hardware.info/?probe=1a2543f92f) | Mar 06, 2023 |
| Deciso        | NetBoard-A10                | [ca59a5e6f4](https://bsd-hardware.info/?probe=ca59a5e6f4) | Feb 28, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [63b73012e6](https://bsd-hardware.info/?probe=63b73012e6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Shuttle       | DS437T                      | [9a16ad9fec](https://bsd-hardware.info/?probe=9a16ad9fec) | Feb 12, 2023 |
| Alienware     | m15                         | [3ab3e4b671](https://bsd-hardware.info/?probe=3ab3e4b671) | Feb 12, 2023 |
| MSI           | GF76 12UE                   | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [8cb09e34ec](https://bsd-hardware.info/?probe=8cb09e34ec) | Feb 04, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS04200    | [3178015cd3](https://bsd-hardware.info/?probe=3178015cd3) | Feb 02, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1603f38c4c](https://bsd-hardware.info/?probe=1603f38c4c) | Jan 28, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | XPS 13 9310                 | [7319560506](https://bsd-hardware.info/?probe=7319560506) | Jan 24, 2023 |
| Medion        | S14409                      | [9a44efb64c](https://bsd-hardware.info/?probe=9a44efb64c) | Jan 23, 2023 |
| Lenovo        | ThinkPad T440p 20AN007FG... | [0883806434](https://bsd-hardware.info/?probe=0883806434) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Deciso        | NetBoard-A10                | [624bfd62b5](https://bsd-hardware.info/?probe=624bfd62b5) | Jan 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [ced6c29193](https://bsd-hardware.info/?probe=ced6c29193) | Jan 14, 2023 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Deciso        | NetBoard-A10                | [b09ff8826c](https://bsd-hardware.info/?probe=b09ff8826c) | Dec 26, 2022 |
| Tactus        | GeoFlex 110                 | [955c355b47](https://bsd-hardware.info/?probe=955c355b47) | Dec 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [b38d32b139](https://bsd-hardware.info/?probe=b38d32b139) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [af2a9d1a42](https://bsd-hardware.info/?probe=af2a9d1a42) | Dec 20, 2022 |
| Unknown       | Unknown                     | [364b3758b6](https://bsd-hardware.info/?probe=364b3758b6) | Dec 20, 2022 |
| Acer          | Swift SF114-34              | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
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
| Apple         | MacBookAir4,1               | [6eada6e49e](https://bsd-hardware.info/?probe=6eada6e49e) | Aug 28, 2021 |
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
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [dab0ca2417](https://bsd-hardware.info/?probe=dab0ca2417) | Jun 01, 2021 |
| Unknown       | Unknown                     | [1f2d078d2e](https://bsd-hardware.info/?probe=1f2d078d2e) | Jun 01, 2021 |
| Deciso        | Netboard A20                | [f4a0f0941b](https://bsd-hardware.info/?probe=f4a0f0941b) | May 26, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [96cc0c27b0](https://bsd-hardware.info/?probe=96cc0c27b0) | May 25, 2021 |
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
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [9e58a182a8](https://bsd-hardware.info/?probe=9e58a182a8) | Jan 16, 2021 |
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
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | [a6b923675d](https://bsd-hardware.info/?probe=a6b923675d) | Dec 07, 2020 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 27        | 4.84%   |
| helloSystem 0.4.0    | 14        | 2.51%   |
| helloSystem 0.7.0    | 13        | 2.33%   |
| FreeBSD 14.0         | 13        | 2.33%   |
| OpenBSD 6.8          | 12        | 2.15%   |
| helloSystem 0.5.0    | 12        | 2.15%   |
| helloSystem 0.8.0    | 11        | 1.97%   |
| helloSystem 0.9.0    | 10        | 1.79%   |
| FreeBSD 12.2         | 10        | 1.79%   |
| OPNsense 24.10       | 8         | 1.43%   |
| OpenBSD 7.0          | 8         | 1.43%   |
| FreeBSD 14.0-CURRENT | 7         | 1.25%   |
| FreeBSD 13.2         | 7         | 1.25%   |
| FreeBSD 13.0-p4      | 7         | 1.25%   |
| OPNsense 23.1.11     | 6         | 1.08%   |
| OpenBSD 7.2          | 6         | 1.08%   |
| OpenBSD 6.9          | 6         | 1.08%   |
| NomadBSD 5806f915    | 6         | 1.08%   |
| NetBSD 10.1          | 6         | 1.08%   |
| helloSystem 0.6.0    | 6         | 1.08%   |
| GhostBSD 22.01.12    | 6         | 1.08%   |
| FreeBSD 14.2         | 6         | 1.08%   |
| FreeBSD 12.1-p10     | 6         | 1.08%   |
| OPNsense 24.7.4      | 5         | 0.9%    |
| OPNsense 21.7.6      | 5         | 0.9%    |
| OpenBSD 6.7          | 5         | 0.9%    |
| GhostBSD 21.08.27    | 5         | 0.9%    |
| GhostBSD 20.04.02    | 5         | 0.9%    |
| FreeBSD 14.1         | 5         | 0.9%    |
| FreeBSD 13.0-CURRENT | 5         | 0.9%    |
| FreeBSD 13.0         | 5         | 0.9%    |
| FreeBSD 12.2-p2      | 5         | 0.9%    |
| FreeBSD 12.1-STABLE  | 5         | 0.9%    |
| OPNsense 24.7.10     | 4         | 0.72%   |
| OPNsense 24.10.1     | 4         | 0.72%   |
| OPNsense 21.1.2      | 4         | 0.72%   |
| OpenBSD 7.8          | 4         | 0.72%   |
| NomadBSD 1.4         | 4         | 0.72%   |
| FreeBSD 15.0-CURRENT | 4         | 0.72%   |
| FreeBSD 13.1-p5      | 4         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 156       | 32.84%  |
| OPNsense    | 111       | 23.37%  |
| helloSystem | 91        | 19.16%  |
| OpenBSD     | 47        | 9.89%   |
| GhostBSD    | 36        | 7.58%   |
| NomadBSD    | 21        | 4.42%   |
| NetBSD      | 9         | 1.89%   |
| FuryBSD     | 2         | 0.42%   |
| MidnightBSD | 1         | 0.21%   |
| HardenedBSD | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 445       | 97.37%  |
| i386   | 9         | 1.97%   |
| macppc | 3         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Console       | 147       | 30.37%  |
| helloDesktop  | 104       | 21.49%  |
| XFCE          | 53        | 10.95%  |
| MATE          | 42        | 8.68%   |
| KDE5          | 33        | 6.82%   |
| fvwm          | 26        | 5.37%   |
| GNOME         | 20        | 4.13%   |
| Openbox       | 17        | 3.51%   |
| TWM           | 16        | 3.31%   |
| i3            | 5         | 1.03%   |
| AwesomeWM     | 5         | 1.03%   |
| IceWM         | 2         | 0.41%   |
| Cinnamon      | 2         | 0.41%   |
| WindowMaker   | 1         | 0.21%   |
| Picom         | 1         | 0.21%   |
| LXQt          | 1         | 0.21%   |
| LXDE          | 1         | 0.21%   |
| KDE6          | 1         | 0.21%   |
| KDE           | 1         | 0.21%   |
| JWM           | 1         | 0.21%   |
| iwm           | 1         | 0.21%   |
| herbstluftwm  | 1         | 0.21%   |
| Enlightenment | 1         | 0.21%   |
| Compton       | 1         | 0.21%   |
| CDE           | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 302       | 65.51%  |
| Console | 148       | 32.1%   |
| Wayland | 11        | 2.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 225       | 46.78%  |
| SLiM    | 125       | 25.99%  |
| LightDM | 49        | 10.19%  |
| SDDM    | 47        | 9.77%   |
| XDM     | 18        | 3.74%   |
| GDM     | 11        | 2.29%   |
| Ly      | 6         | 1.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 205       | 42.36%  |
| de_DE            | 87        | 17.98%  |
| C                | 87        | 17.98%  |
| en_US            | 77        | 15.91%  |
| de               | 8         | 1.65%   |
| en_GB            | 7         | 1.45%   |
| de_DE.ISO8859-1  | 3         | 0.62%   |
| pl_PL            | 2         | 0.41%   |
| fr_FR            | 2         | 0.41%   |
| de_DE.ISO8859-15 | 2         | 0.41%   |
| it_IT            | 1         | 0.21%   |
| en_IE            | 1         | 0.21%   |
| en_CA            | 1         | 0.21%   |
| en               | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 387       | 83.41%  |
| BIOS | 77        | 16.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 270       | 56.84%  |
| Ufs    | 122       | 25.68%  |
| Ffs    | 47        | 9.89%   |
| Cd9660 | 36        | 7.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 426       | 92.41%  |
| MBR     | 30        | 6.51%   |
| Unknown | 5         | 1.08%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 153       | 33.48%  |
| Deciso                           | 55        | 12.04%  |
| Dell                             | 46        | 10.07%  |
| Apple                            | 30        | 6.56%   |
| Hewlett-Packard                  | 29        | 6.35%   |
| Acer                             | 22        | 4.81%   |
| Unknown                          | 18        | 3.94%   |
| Fujitsu                          | 15        | 3.28%   |
| ASUSTek Computer                 | 11        | 2.41%   |
| TUXEDO                           | 10        | 2.19%   |
| Sony                             | 4         | 0.88%   |
| Shuttle                          | 4         | 0.88%   |
| Notebook                         | 4         | 0.88%   |
| Schenker                         | 3         | 0.66%   |
| Panasonic                        | 3         | 0.66%   |
| MSI                              | 3         | 0.66%   |
| HUAWEI                           | 3         | 0.66%   |
| Google                           | 3         | 0.66%   |
| Gigabyte Technology              | 3         | 0.66%   |
| Framework                        | 3         | 0.66%   |
| Toshiba                          | 2         | 0.44%   |
| Tactus                           | 2         | 0.44%   |
| Samsung Electronics              | 2         | 0.44%   |
| Micro Computer (HK) Tech Limited | 2         | 0.44%   |
| Medion                           | 2         | 0.44%   |
| IGEL Technology                  | 2         | 0.44%   |
| IBM                              | 2         | 0.44%   |
| BESSTAR Tech                     | 2         | 0.44%   |
| Wortmann AG                      | 1         | 0.22%   |
| TULPAR                           | 1         | 0.22%   |
| SZ ReachingTech Limited          | 1         | 0.22%   |
| System76                         | 1         | 0.22%   |
| Seco                             | 1         | 0.22%   |
| Packard Bell                     | 1         | 0.22%   |
| NEC Computers                    | 1         | 0.22%   |
| MiTAC                            | 1         | 0.22%   |
| Intel                            | 1         | 0.22%   |
| Insyde                           | 1         | 0.22%   |
| HKC                              | 1         | 0.22%   |
| Hampoo                           | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 19        | 4.16%   |
| Deciso NetBoard-A10                  | 15        | 3.28%   |
| Deciso NetBoard-A20                  | 13        | 2.84%   |
| Deciso Netboard A20                  | 12        | 2.63%   |
| Deciso NetBoard-A10_Gen.3            | 8         | 1.75%   |
| Apple MacBookAir7,2                  | 5         | 1.09%   |
| Dell Latitude E6540                  | 4         | 0.88%   |
| Deciso DEC2700 - OPNsense Appliance  | 4         | 0.88%   |
| Apple MacBookAir5,1                  | 4         | 0.88%   |
| Dell Latitude 7280                   | 3         | 0.66%   |
| TUXEDO Pulse 15 Gen1                 | 2         | 0.44%   |
| TUXEDO Pulse 14 Gen1                 | 2         | 0.44%   |
| Shuttle DS437                        | 2         | 0.44%   |
| Panasonic CF-C1BD06EFG               | 2         | 0.44%   |
| Micro (HK) Tech Limited Venus series | 2         | 0.44%   |
| Lenovo ThinkPad X260 20F5S1H800      | 2         | 0.44%   |
| Lenovo ThinkPad X260 20F5A28AUK      | 2         | 0.44%   |
| Lenovo ThinkPad X230 232578G         | 2         | 0.44%   |
| Lenovo ThinkPad T580 20LAS1KA00      | 2         | 0.44%   |
| Lenovo ThinkPad T410s 291245G        | 2         | 0.44%   |
| Lenovo ThinkPad E490 20N8CTO1WW      | 2         | 0.44%   |
| HP ZBook 15 G4                       | 2         | 0.44%   |
| HP 255 G8 Notebook PC                | 2         | 0.44%   |
| Google Akemi                         | 2         | 0.44%   |
| Gigabyte GB-BSi5A-6200               | 2         | 0.44%   |
| Dell XPS 15 9560                     | 2         | 0.44%   |
| Dell Latitude E6500                  | 2         | 0.44%   |
| Dell Latitude E6330                  | 2         | 0.44%   |
| Dell Latitude 5591                   | 2         | 0.44%   |
| Deciso OPNsense Appliance            | 2         | 0.44%   |
| BESSTAR Tech U820                    | 2         | 0.44%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 2         | 0.44%   |
| Apple PowerBook6,8                   | 2         | 0.44%   |
| Apple MacBookPro11,1                 | 2         | 0.44%   |
| Apple MacBook5,1                     | 2         | 0.44%   |
| Wortmann AG TERRA_MOBILE_1541        | 1         | 0.22%   |
| TUXEDO Pulse 15 Gen2                 | 1         | 0.22%   |
| TUXEDO N13xWU                        | 1         | 0.22%   |
| TUXEDO InfinityBook S 15 Gen6        | 1         | 0.22%   |
| TUXEDO InfinityBook Pro 14 Gen6      | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 129       | 28.23%  |
| Dell Latitude                 | 29        | 6.35%   |
| Deciso NetBoard-A10           | 24        | 5.25%   |
| Unknown                       | 19        | 4.16%   |
| Fujitsu LIFEBOOK              | 14        | 3.06%   |
| Deciso NetBoard-A20           | 13        | 2.84%   |
| Deciso Netboard               | 12        | 2.63%   |
| Acer Aspire                   | 10        | 2.19%   |
| HP EliteBook                  | 9         | 1.97%   |
| Lenovo IdeaPad                | 7         | 1.53%   |
| Dell XPS                      | 7         | 1.53%   |
| TUXEDO Pulse                  | 5         | 1.09%   |
| Dell Precision                | 5         | 1.09%   |
| Dell Inspiron                 | 5         | 1.09%   |
| Apple MacBookAir7             | 5         | 1.09%   |
| Acer TravelMate               | 5         | 1.09%   |
| HP ZBook                      | 4         | 0.88%   |
| Deciso DEC2700                | 4         | 0.88%   |
| Apple MacBookAir5             | 4         | 0.88%   |
| Lenovo ThinkBook              | 3         | 0.66%   |
| Lenovo Legion                 | 3         | 0.66%   |
| HP Laptop                     | 3         | 0.66%   |
| Framework Laptop              | 3         | 0.66%   |
| Apple PowerBook6              | 3         | 0.66%   |
| Apple MacBookPro11            | 3         | 0.66%   |
| TUXEDO InfinityBook           | 2         | 0.44%   |
| Toshiba Satellite             | 2         | 0.44%   |
| Shuttle DS437                 | 2         | 0.44%   |
| Panasonic CF-C1BD06EFG        | 2         | 0.44%   |
| Micro (HK) Tech Limited Venus | 2         | 0.44%   |
| IBM ThinkPad                  | 2         | 0.44%   |
| HP ProBook                    | 2         | 0.44%   |
| HP Compaq                     | 2         | 0.44%   |
| HP 255                        | 2         | 0.44%   |
| Google Akemi                  | 2         | 0.44%   |
| Gigabyte GB-BSi5A-6200        | 2         | 0.44%   |
| Deciso OPNsense               | 2         | 0.44%   |
| BESSTAR Tech U820             | 2         | 0.44%   |
| ASUS TUF                      | 2         | 0.44%   |
| Apple MacBookPro8             | 2         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 60        | 13.13%  |
| 2019    | 40        | 8.75%   |
| 2022    | 36        | 7.88%   |
| 2020    | 35        | 7.66%   |
| 2013    | 30        | 6.56%   |
| 2017    | 29        | 6.35%   |
| 2016    | 29        | 6.35%   |
| 2018    | 28        | 6.13%   |
| 2011    | 26        | 5.69%   |
| 2012    | 24        | 5.25%   |
| 2014    | 21        | 4.6%    |
| 2010    | 21        | 4.6%    |
| 2015    | 16        | 3.5%    |
| 2023    | 14        | 3.06%   |
| 2008    | 12        | 2.63%   |
| 2024    | 10        | 2.19%   |
| 2009    | 9         | 1.97%   |
| 2007    | 5         | 1.09%   |
| Unknown | 5         | 1.09%   |
| 2025    | 2         | 0.44%   |
| 2003    | 2         | 0.44%   |
| 2006    | 1         | 0.22%   |
| 2005    | 1         | 0.22%   |
| 2002    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 457       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 453       | 99.12%  |
| Yes  | 4         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 173       | 37.61%  |
| 16.01-24.0  | 120       | 26.09%  |
| 4.01-8.0    | 80        | 17.39%  |
| 32.01-64.0  | 42        | 9.13%   |
| 2.01-3.0    | 15        | 3.26%   |
| 3.01-4.0    | 7         | 1.52%   |
| 64.01-256.0 | 6         | 1.3%    |
| 1.01-2.0    | 6         | 1.3%    |
| 24.01-32.0  | 5         | 1.09%   |
| 0.51-1.0    | 3         | 0.65%   |
| 0.01-0.5    | 2         | 0.43%   |
| 0           | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 247       | 52.78%  |
| 0.51-1.0   | 140       | 29.91%  |
| 1.01-2.0   | 45        | 9.62%   |
| 2.01-3.0   | 12        | 2.56%   |
| Unknown    | 11        | 2.35%   |
| 4.01-8.0   | 6         | 1.28%   |
| 3.01-4.0   | 3         | 0.64%   |
| 0          | 2         | 0.43%   |
| 24.01-32.0 | 1         | 0.21%   |
| 16.01-24.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 309       | 64.92%  |
| 0      | 81        | 17.02%  |
| 2      | 77        | 16.18%  |
| 3      | 9         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 355       | 77.17%  |
| Yes       | 105       | 22.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 408       | 89.28%  |
| No        | 49        | 10.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 80.39%  |
| No        | 90        | 19.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 262       | 56.96%  |
| No        | 198       | 43.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 457       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 46        | 9.31%   |
| Munich            | 21        | 4.25%   |
| Frankfurt am Main | 17        | 3.44%   |
| Hamburg           | 16        | 3.24%   |
| Stuttgart         | 10        | 2.02%   |
| Cologne           | 10        | 2.02%   |
| Nuremberg         | 9         | 1.82%   |
| Essen             | 7         | 1.42%   |
| Aachen            | 7         | 1.42%   |
| Lübeck           | 6         | 1.21%   |
| Leipzig           | 6         | 1.21%   |
| Halle             | 6         | 1.21%   |
| Bedburg           | 6         | 1.21%   |
| Karlsruhe         | 5         | 1.01%   |
| Wuppertal         | 4         | 0.81%   |
| Mainz             | 4         | 0.81%   |
| Dresden           | 4         | 0.81%   |
| Darmstadt         | 4         | 0.81%   |
| Bielefeld         | 4         | 0.81%   |
| Wernigerode       | 3         | 0.61%   |
| Reutlingen        | 3         | 0.61%   |
| Oldenburg         | 3         | 0.61%   |
| Neuss             | 3         | 0.61%   |
| Neuengors         | 3         | 0.61%   |
| Münster          | 3         | 0.61%   |
| Markt Indersdorf  | 3         | 0.61%   |
| Ludwigsburg       | 3         | 0.61%   |
| Giessen           | 3         | 0.61%   |
| Erlangen          | 3         | 0.61%   |
| Bonn              | 3         | 0.61%   |
| Blomberg          | 3         | 0.61%   |
| Zwingenberg       | 2         | 0.4%    |
| Würzburg         | 2         | 0.4%    |
| Wissen            | 2         | 0.4%    |
| Wiesbaden         | 2         | 0.4%    |
| Regensburg        | 2         | 0.4%    |
| Ravensburg        | 2         | 0.4%    |
| Potsdam           | 2         | 0.4%    |
| Pleidelsheim      | 2         | 0.4%    |
| Offenburg         | 2         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 93        | 117    | 20.71%  |
| Transcend           | 53        | 64     | 11.8%   |
| Crucial             | 30        | 38     | 6.68%   |
| WDC                 | 28        | 33     | 6.24%   |
| SanDisk             | 28        | 30     | 6.24%   |
| Seagate             | 23        | 26     | 5.12%   |
| Kingston            | 20        | 24     | 4.45%   |
| Toshiba             | 18        | 43     | 4.01%   |
| Intenso             | 18        | 19     | 4.01%   |
| Apple               | 18        | 21     | 4.01%   |
| Intel               | 17        | 18     | 3.79%   |
| NVMe                | 15        | 26     | 3.34%   |
| Micron Technology   | 11        | 11     | 2.45%   |
| Hitachi             | 8         | 11     | 1.78%   |
| SK hynix            | 6         | 7      | 1.34%   |
| HGST                | 6         | 11     | 1.34%   |
| SPCC                | 4         | 5      | 0.89%   |
| OCZ                 | 4         | 7      | 0.89%   |
| KIOXIA              | 4         | 4      | 0.89%   |
| Hoodisk             | 4         | 4      | 0.89%   |
| Fujitsu             | 4         | 4      | 0.89%   |
| FORESEE             | 3         | 6      | 0.67%   |
| China               | 3         | 3      | 0.67%   |
| A-DATA Technology   | 3         | 4      | 0.67%   |
| Verbatim            | 2         | 4      | 0.45%   |
| PNY                 | 2         | 3      | 0.45%   |
| Phison              | 2         | 2      | 0.45%   |
| LITEON              | 2         | 2      | 0.45%   |
| Kston               | 2         | 2      | 0.45%   |
| Gigabyte Technology | 2         | 2      | 0.45%   |
| Dogfish             | 2         | 2      | 0.45%   |
| VICKTER             | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| Netac               | 1         | 1      | 0.22%   |
| MyDigitalSSD        | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| LITEONIT            | 1         | 1      | 0.22%   |
| Lenovo              | 1         | 1      | 0.22%   |
| Indilinx            | 1         | 3      | 0.22%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 13        | 2.8%    |
| Transcend TS256GMTE710T 256GB        | 10        | 2.15%   |
| Transcend TS256GMTE652T2 256GB       | 7         | 1.51%   |
| Transcend TS128GMTE110S 128GB        | 5         | 1.08%   |
| Samsung SSD 860 EVO 500GB            | 5         | 1.08%   |
| Samsung SSD 840 EVO 250GB            | 5         | 1.08%   |
| Crucial CT1000MX500SSD1 1TB          | 5         | 1.08%   |
| Transcend TS512GMTS952T2 512GB       | 4         | 0.86%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.86%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.86%   |
| Kingston SA400S37120G 120GB          | 4         | 0.86%   |
| Hoodisk SSD 128GB                    | 4         | 0.86%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.86%   |
| Apple SSD TS128E 121GB               | 4         | 0.86%   |
| Apple SSD SM0128G 121GB              | 4         | 0.86%   |
| Transcend TS240GMTS420S 240GB        | 3         | 0.65%   |
| SanDisk SSD PLUS 120GB               | 3         | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.65%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.65%   |
| NVMe WDC PC SN730 SDB 256GB          | 3         | 0.65%   |
| NVMe Samsung SSD 980 1TB             | 3         | 0.65%   |
| Intenso SSD 128GB                    | 3         | 0.65%   |
| Intel SSDSC2BF240A5L 240GB           | 3         | 0.65%   |
| FORESEE 64GB SSD                     | 3         | 0.65%   |
| Transcend TS64GSSD370S 64GB          | 2         | 0.43%   |
| Transcend TS120GSSD220S 120GB        | 2         | 0.43%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB | 2         | 0.43%   |
| Toshiba KXG60ZNV512G 512GB           | 2         | 0.43%   |
| SPCC Solid State Disk 1TB            | 2         | 0.43%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.43%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.43%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.43%   |
| SanDisk SSD PLUS 1000GB              | 2         | 0.43%   |
| SanDisk SDSSDP064G 64GB              | 2         | 0.43%   |
| Samsung SSD 970 EVO Plus 250GB       | 2         | 0.43%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.43%   |
| Samsung SSD 870 EVO 2TB              | 2         | 0.43%   |
| Samsung SSD 870 EVO 250GB            | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 27.71%  |
| WDC                 | 18        | 21     | 21.69%  |
| NVMe                | 11        | 21     | 13.25%  |
| Hitachi             | 8         | 11     | 9.64%   |
| Toshiba             | 7         | 8      | 8.43%   |
| HGST                | 6         | 11     | 7.23%   |
| Fujitsu             | 4         | 4      | 4.82%   |
| Samsung Electronics | 2         | 2      | 2.41%   |
| Intenso             | 2         | 2      | 2.41%   |
| Generic             | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 78     | 23.47%  |
| Transcend           | 30        | 37     | 10.83%  |
| SanDisk             | 28        | 30     | 10.11%  |
| Crucial             | 26        | 34     | 9.39%   |
| Apple               | 17        | 20     | 6.14%   |
| Kingston            | 16        | 20     | 5.78%   |
| Intenso             | 16        | 17     | 5.78%   |
| Intel               | 16        | 17     | 5.78%   |
| Micron Technology   | 6         | 6      | 2.17%   |
| WDC                 | 5         | 6      | 1.81%   |
| Toshiba             | 5         | 13     | 1.81%   |
| SK hynix            | 4         | 5      | 1.44%   |
| OCZ                 | 4         | 7      | 1.44%   |
| Hoodisk             | 4         | 4      | 1.44%   |
| SPCC                | 3         | 3      | 1.08%   |
| NVMe                | 3         | 3      | 1.08%   |
| FORESEE             | 3         | 6      | 1.08%   |
| China               | 3         | 3      | 1.08%   |
| Verbatim            | 2         | 4      | 0.72%   |
| PNY                 | 2         | 3      | 0.72%   |
| LITEON              | 2         | 2      | 0.72%   |
| Kston               | 2         | 2      | 0.72%   |
| Dogfish             | 2         | 2      | 0.72%   |
| A-DATA Technology   | 2         | 2      | 0.72%   |
| VICKTER             | 1         | 1      | 0.36%   |
| Patriot             | 1         | 1      | 0.36%   |
| Netac               | 1         | 1      | 0.36%   |
| MyDigitalSSD        | 1         | 1      | 0.36%   |
| Mushkin             | 1         | 1      | 0.36%   |
| LITEONIT            | 1         | 1      | 0.36%   |
| Indilinx            | 1         | 3      | 0.36%   |
| Hewlett-Packard     | 1         | 1      | 0.36%   |
| Corsair             | 1         | 1      | 0.36%   |
| Apacer              | 1         | 1      | 0.36%   |
| 2-Power             | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 253       | 337    | 60.53%  |
| NVMe | 87        | 124    | 20.81%  |
| HDD  | 78        | 108    | 18.66%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 315       | 445    | 78.36%  |
| NVMe | 87        | 124    | 21.64%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 272       | 360    | 81.19%  |
| 0.51-1.0   | 43        | 54     | 12.84%  |
| 1.01-2.0   | 18        | 29     | 5.37%   |
| 3.01-4.0   | 1         | 1      | 0.3%    |
| 4.01-10.0  | 1         | 1      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 188       | 39.17%  |
| 1-20           | 96        | 20%     |
| 251-500        | 92        | 19.17%  |
| 51-100         | 38        | 7.92%   |
| 501-1000       | 34        | 7.08%   |
| 21-50          | 19        | 3.96%   |
| 1001-2000      | 9         | 1.88%   |
| Unknown        | 3         | 0.63%   |
| More than 3000 | 1         | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 396       | 83.02%  |
| 21-50          | 33        | 6.92%   |
| 51-100         | 21        | 4.4%    |
| 101-250        | 17        | 3.56%   |
| 251-500        | 5         | 1.05%   |
| Unknown        | 3         | 0.63%   |
| More than 3000 | 1         | 0.21%   |
| 501-1000       | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba THNSNK256GVN8 M.2 2280 256GB         | 2         | 10     | 5%      |
| Micron Technology 1100 SATA 256GB            | 2         | 2      | 5%      |
| Intel SSDSC2KF256H6L 256GB                   | 2         | 2      | 5%      |
| Hitachi HTS545032B9A300 320GB                | 2         | 4      | 5%      |
| Hitachi HTS543225L9A300 250GB                | 2         | 2      | 5%      |
| HGST HTS541010A9E680 1TB                     | 2         | 3      | 5%      |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.5%    |
| WDC WD1600BEVS-07RST0 160GB                  | 1         | 1      | 2.5%    |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 1      | 2.5%    |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 2.5%    |
| Toshiba MK2018GAP 20GB                       | 1         | 1      | 2.5%    |
| SK hynix HFS256G39MND-2300A 256GB            | 1         | 1      | 2.5%    |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.5%    |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 2.5%    |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 2.5%    |
| Seagate ST9250410AS 250GB                    | 1         | 1      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 2.5%    |
| Seagate ST320LT007-9ZV142 320GB              | 1         | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 2.5%    |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 2.5%    |
| SanDisk SSD PLUS 1000GB                      | 1         | 1      | 2.5%    |
| SanDisk SSD P4 64GB                          | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 2.5%    |
| LITEONIT LCS-256M6S 256GB                    | 1         | 1      | 2.5%    |
| Kingston SV300S37A240G 240GB                 | 1         | 1      | 2.5%    |
| Kingston SNV425S264GB                        | 1         | 1      | 2.5%    |
| Intel SSDSC2BF180A4L 180GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS548040M9AT00 37GB                 | 1         | 1      | 2.5%    |
| Hitachi HTS545025B9SA02 250GB                | 1         | 2      | 2.5%    |
| Fujitsu MHW2160BH 160GB                      | 1         | 1      | 2.5%    |
| Crucial CT1000P1SSD8 1TB                     | 1         | 1      | 2.5%    |
| Corsair Force GT 120GB                       | 1         | 1      | 2.5%    |
| Apple SSD SM128C 121GB                       | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 17.5%   |
| Hitachi             | 6         | 9      | 15%     |
| WDC                 | 4         | 4      | 10%     |
| Toshiba             | 4         | 12     | 10%     |
| SanDisk             | 3         | 3      | 7.5%    |
| Intel               | 3         | 3      | 7.5%    |
| Micron Technology   | 2         | 2      | 5%      |
| Kingston            | 2         | 2      | 5%      |
| HGST                | 2         | 3      | 5%      |
| SK hynix            | 1         | 1      | 2.5%    |
| Samsung Electronics | 1         | 2      | 2.5%    |
| LITEONIT            | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| Corsair             | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 31.82%  |
| Hitachi | 6         | 9      | 27.27%  |
| WDC     | 4         | 4      | 18.18%  |
| Toshiba | 2         | 2      | 9.09%   |
| HGST    | 2         | 3      | 9.09%   |
| Fujitsu | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 26     | 55%     |
| SSD  | 17        | 26     | 42.5%   |
| NVMe | 1         | 1      | 2.5%    |

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
| Works    | 346       | 488    | 85.86%  |
| Malfunc  | 40        | 53     | 9.93%   |
| Detected | 17        | 28     | 4.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 285       | 55.23%  |
| Samsung Electronics              | 63        | 12.21%  |
| AMD                              | 39        | 7.56%   |
| Transcend                        | 37        | 7.17%   |
| SanDisk                          | 19        | 3.68%   |
| Toshiba                          | 11        | 2.13%   |
| Micron Technology                | 9         | 1.74%   |
| SK hynix                         | 7         | 1.36%   |
| Micron/Crucial Technology        | 7         | 1.36%   |
| Kingston Technology Company      | 7         | 1.36%   |
| Phison Electronics               | 6         | 1.16%   |
| KIOXIA                           | 6         | 1.16%   |
| Nvidia                           | 5         | 0.97%   |
| Marvell Technology Group         | 4         | 0.78%   |
| ADATA Technology                 | 3         | 0.58%   |
| Silicon Motion                   | 2         | 0.39%   |
| ULi Electronics                  | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Seagate Technology               | 1         | 0.19%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.19%   |
| Lenovo                           | 1         | 0.19%   |
| Apple                            | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 41        | 7.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 38        | 7.02%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 38        | 7.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 29        | 5.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 27        | 4.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 25        | 4.62%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                        | 21        | 3.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 3.33%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 15        | 2.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 2.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 2.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 11        | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 2.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 1.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.66%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 8         | 1.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 8         | 1.48%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 1.29%   |
| Toshiba XG5 NVMe SSD Controller                                                  | 6         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.92%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 4         | 0.74%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.74%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 4         | 0.74%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 4         | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 0.74%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 3         | 0.55%   |
| Sandisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 3         | 0.55%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.55%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                             | 3         | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 312       | 60.47%  |
| NVMe | 158       | 30.62%  |
| IDE  | 34        | 6.59%   |
| RAID | 12        | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 358       | 78.34%  |
| AMD     | 96        | 21.01%  |
| PowerPC | 3         | 0.66%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 30        | 6.52%   |
| AMD EPYC 3201 8-Core Processor          | 19        | 4.13%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 15        | 3.26%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 12        | 2.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 1.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 9         | 1.96%   |
| Intel CPU Version                       | 8         | 1.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 8         | 1.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 1.74%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 7         | 1.52%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 1.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 1.3%    |
| Intel Core i3-4005U CPU @ 1.70GHz       | 6         | 1.3%    |
| Intel Core 2 Duo                        | 6         | 1.3%    |
| AMD EPYC 3101 4-Core Processor          | 6         | 1.3%    |
| Intel Core i5-3317U CPU @ 1.70GHz       | 5         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 5         | 1.09%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 4         | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 4         | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 0.87%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 4         | 0.87%   |
| Intel Core i5-4250U CPU @ 1.30GHz       | 4         | 0.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 4         | 0.87%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 0.87%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 4         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 0.87%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 4         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 3         | 0.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 0.65%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 3         | 0.65%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 3         | 0.65%   |
| Intel Celeron CPU 1037U @ 1.80GHz       | 3         | 0.65%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 3         | 0.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 143       | 31.22%  |
| Intel Core i7        | 85        | 18.56%  |
| Other                | 38        | 8.3%    |
| AMD Ryzen Embedded   | 30        | 6.55%   |
| AMD EPYC             | 25        | 5.46%   |
| Intel Core i3        | 23        | 5.02%   |
| Intel Core 2 Duo     | 22        | 4.8%    |
| Intel Celeron        | 16        | 3.49%   |
| AMD Ryzen 7          | 15        | 3.28%   |
| AMD Ryzen 5          | 11        | 2.4%    |
| Intel Pentium        | 9         | 1.97%   |
| Intel Atom           | 6         | 1.31%   |
| Intel Xeon           | 4         | 0.87%   |
| AMD Ryzen 7 PRO      | 4         | 0.87%   |
| Intel Pentium M      | 3         | 0.66%   |
| Intel Genuine        | 3         | 0.66%   |
| Intel Pentium Silver | 2         | 0.44%   |
| Intel Core m3        | 2         | 0.44%   |
| Intel Core           | 2         | 0.44%   |
| AMD Ryzen 5 PRO      | 2         | 0.44%   |
| AMD E2               | 2         | 0.44%   |
| Intel Pentium Dual   | 1         | 0.22%   |
| Intel Pentium 4      | 1         | 0.22%   |
| Intel Core M         | 1         | 0.22%   |
| Intel Core 2 Solo    | 1         | 0.22%   |
| Intel Core 2         | 1         | 0.22%   |
| Intel Celeron M      | 1         | 0.22%   |
| Intel 686-class      | 1         | 0.22%   |
| AMD Ryzen 3          | 1         | 0.22%   |
| AMD GX               | 1         | 0.22%   |
| AMD A6               | 1         | 0.22%   |
| AMD A10              | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 213       | 46.2%   |
| 4       | 124       | 26.9%   |
| 8       | 47        | 10.2%   |
| Unknown | 24        | 5.21%   |
| 16      | 16        | 3.47%   |
| 1       | 14        | 3.04%   |
| 6       | 9         | 1.95%   |
| 12      | 8         | 1.74%   |
| 10      | 4         | 0.87%   |
| 11      | 1         | 0.22%   |
| 9       | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 443       | 96.51%  |
| Unknown | 9         | 1.96%   |
| 2       | 7         | 1.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 291       | 63.12%  |
| 1       | 136       | 29.5%   |
| Unknown | 34        | 7.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 69        | 15.03%  |
| Zen           | 56        | 12.2%   |
| Haswell       | 47        | 10.24%  |
| IvyBridge     | 42        | 9.15%   |
| SandyBridge   | 37        | 8.06%   |
| Unknown       | 36        | 7.84%   |
| Skylake       | 31        | 6.75%   |
| Broadwell     | 26        | 5.66%   |
| Penryn        | 25        | 5.45%   |
| Westmere      | 12        | 2.61%   |
| TigerLake     | 12        | 2.61%   |
| Silvermont    | 9         | 1.96%   |
| Core          | 9         | 1.96%   |
| Zen 2         | 8         | 1.74%   |
| Zen+          | 6         | 1.31%   |
| Bonnell       | 6         | 1.31%   |
| Zen 3         | 5         | 1.09%   |
| P6            | 4         | 0.87%   |
| Goldmont plus | 3         | 0.65%   |
| Goldmont      | 3         | 0.65%   |
| Puma          | 2         | 0.44%   |
| Piledriver    | 2         | 0.44%   |
| NetBurst      | 2         | 0.44%   |
| IceLake       | 2         | 0.44%   |
| Bobcat        | 2         | 0.44%   |
| K10           | 1         | 0.22%   |
| Geode         | 1         | 0.22%   |
| CometLake     | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 328       | 71.15%  |
| Nvidia                           | 77        | 16.7%   |
| AMD                              | 54        | 11.71%  |
| Trident Microsystems             | 1         | 0.22%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 42        | 8.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 7.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 6.74%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 26        | 5.47%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 18        | 3.79%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 16        | 3.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 2.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.53%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 12        | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 2.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.68%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 8         | 1.68%   |
| AMD Lucienne                                                                             | 7         | 1.47%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 6         | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.84%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 0.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.84%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 4         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.84%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.84%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 4         | 0.84%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 4         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.63%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 3         | 0.63%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 3         | 0.63%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 0.63%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 3         | 0.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.42%   |
| Nvidia NV34M [GeForce FX Go5200]                                                         | 2         | 0.42%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 2         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 245       | 53.38%  |
| Other                    | 57        | 12.42%  |
| Intel + Nvidia           | 44        | 9.59%   |
| 1 x AMD                  | 37        | 8.06%   |
| 1 x Nvidia               | 30        | 6.54%   |
| 2 x Intel                | 27        | 5.88%   |
| Intel + AMD              | 12        | 2.61%   |
| AMD + Nvidia             | 5         | 1.09%   |
| 1 x Trident Microsystems | 1         | 0.22%   |
| 1 x SiS                  | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 364       | 78.45%  |
| Unknown     | 75        | 16.16%  |
| Proprietary | 25        | 5.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 430       | 92.67%  |
| 0.01-0.5   | 14        | 3.02%   |
| 1.01-2.0   | 6         | 1.29%   |
| 7.01-8.0   | 5         | 1.08%   |
| 3.01-4.0   | 5         | 1.08%   |
| 0.51-1.0   | 3         | 0.65%   |
| 5.01-6.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 20.37%  |
| LG Display              | 53        | 19.63%  |
| BOE                     | 25        | 9.26%   |
| Chimei Innolux          | 23        | 8.52%   |
| Apple                   | 23        | 8.52%   |
| Samsung Electronics     | 16        | 5.93%   |
| Lenovo                  | 16        | 5.93%   |
| Dell                    | 8         | 2.96%   |
| Sharp                   | 7         | 2.59%   |
| Goldstar                | 5         | 1.85%   |
| InfoVision              | 4         | 1.48%   |
| AOC                     | 4         | 1.48%   |
| PANDA                   | 3         | 1.11%   |
| JDI                     | 3         | 1.11%   |
| BenQ                    | 3         | 1.11%   |
| Unknown                 | 3         | 1.11%   |
| LG Philips              | 2         | 0.74%   |
| Iiyama                  | 2         | 0.74%   |
| Hewlett-Packard         | 2         | 0.74%   |
| Ancor Communications    | 2         | 0.74%   |
| Unknown                 | 1         | 0.37%   |
| TRU                     | 1         | 0.37%   |
| Toshiba                 | 1         | 0.37%   |
| Quanta Display          | 1         | 0.37%   |
| Philips                 | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| LTM                     | 1         | 0.37%   |
| Eizo                    | 1         | 0.37%   |
| CSO                     | 1         | 0.37%   |
| CMT                     | 1         | 0.37%   |
| Chi Mei Optoelectronics | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 5         | 1.83%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 4         | 1.47%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 4         | 1.47%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 4         | 1.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 4         | 1.47%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 3         | 1.1%    |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 3         | 1.1%    |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 3         | 1.1%    |
| BOE LCD Monitor BOE05E0 1366x768 280x160mm 12.7-inch                 | 3         | 1.1%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch        | 3         | 1.1%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch       | 3         | 1.1%    |
| Apple Color LCD APPA01B 1440x900 290x180mm 13.4-inch                 | 3         | 1.1%    |
| Apple Color LCD APP9CDF 1440x900 290x180mm 13.4-inch                 | 3         | 1.1%    |
| Unknown                                                              | 3         | 1.1%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch              | 2         | 0.73%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch         | 2         | 0.73%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 2         | 0.73%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch         | 2         | 0.73%   |
| LG Display LCD Monitor LGD046D 1920x1080 310x170mm 13.9-inch         | 2         | 0.73%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 2         | 0.73%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 2         | 0.73%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 2         | 0.73%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 2         | 0.73%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 2         | 0.73%   |
| Lenovo LCD Monitor LEN40B0 1366x768 350x190mm 15.7-inch              | 2         | 0.73%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 2         | 0.73%   |
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 2         | 0.73%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                | 2         | 0.73%   |
| BOE LCD Monitor BOE08EE 1920x1080 310x170mm 13.9-inch                | 2         | 0.73%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO8074 1280x800 330x210mm 15.4-inch        | 2         | 0.73%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 2         | 0.73%   |
| Apple Color LCD APPA020 2560x1600 290x180mm 13.4-inch                | 2         | 0.73%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 2         | 0.73%   |
| AOC U3277WB AOC3277 3840x2160 700x390mm 31.5-inch                    | 2         | 0.73%   |
| Unknown LCD Monitor Sharp 3840x2160                                  | 1         | 0.37%   |
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 99        | 36.94%  |
| 1366x768 (WXGA)    | 67        | 25%     |
| 3840x2160 (4K)     | 16        | 5.97%   |
| 1280x800 (WXGA)    | 14        | 5.22%   |
| 1600x900 (HD+)     | 13        | 4.85%   |
| 1440x900 (WXGA+)   | 12        | 4.48%   |
| 1920x1200 (WUXGA)  | 11        | 4.1%    |
| 2560x1440 (QHD)    | 10        | 3.73%   |
| 2560x1600          | 5         | 1.87%   |
| 3000x2000          | 3         | 1.12%   |
| 2880x1800          | 3         | 1.12%   |
| 3200x1800 (QHD+)   | 2         | 0.75%   |
| 2256x1504          | 2         | 0.75%   |
| 1680x1050 (WSXGA+) | 2         | 0.75%   |
| 1024x768 (XGA)     | 2         | 0.75%   |
| 9600x2160          | 1         | 0.37%   |
| 720x1280           | 1         | 0.37%   |
| 3072x1920          | 1         | 0.37%   |
| 2560x1080          | 1         | 0.37%   |
| 2240x1400          | 1         | 0.37%   |
| 1920x540           | 1         | 0.37%   |
| 1280x1024 (SXGA)   | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 87        | 32.34%  |
| 15      | 75        | 27.88%  |
| 12      | 35        | 13.01%  |
| 14      | 13        | 4.83%   |
| 27      | 10        | 3.72%   |
| 24      | 10        | 3.72%   |
| 17      | 10        | 3.72%   |
| 11      | 10        | 3.72%   |
| Unknown | 6         | 2.23%   |
| 23      | 5         | 1.86%   |
| 32      | 3         | 1.12%   |
| 40      | 1         | 0.37%   |
| 39      | 1         | 0.37%   |
| 34      | 1         | 0.37%   |
| 26      | 1         | 0.37%   |
| 6       | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 128       | 47.94%  |
| 201-300     | 92        | 34.46%  |
| 501-600     | 23        | 8.61%   |
| 351-400     | 9         | 3.37%   |
| Unknown     | 6         | 2.25%   |
| 701-800     | 4         | 1.5%    |
| 801-900     | 2         | 0.75%   |
| 601-700     | 1         | 0.37%   |
| 401-500     | 1         | 0.37%   |
| 101-200     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 193       | 75.1%   |
| 16/10   | 46        | 17.9%   |
| 3/2     | 6         | 2.33%   |
| Unknown | 6         | 2.33%   |
| 4/3     | 4         | 1.56%   |
| 5/4     | 1         | 0.39%   |
| 21/9    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 84        | 31.11%  |
| 91-100         | 51        | 18.89%  |
| 61-70          | 34        | 12.59%  |
| 101-110        | 26        | 9.63%   |
| 71-80          | 15        | 5.56%   |
| 301-350        | 11        | 4.07%   |
| 201-250        | 11        | 4.07%   |
| 51-60          | 10        | 3.7%    |
| 121-130        | 9         | 3.33%   |
| Unknown        | 6         | 2.22%   |
| 251-300        | 5         | 1.85%   |
| 351-500        | 4         | 1.48%   |
| 501-1000       | 2         | 0.74%   |
| 1-40           | 1         | 0.37%   |
| 141-150        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 126       | 47.55%  |
| 101-120       | 46        | 17.36%  |
| 161-240       | 38        | 14.34%  |
| 51-100        | 32        | 12.08%  |
| More than 240 | 16        | 6.04%   |
| Unknown       | 6         | 2.26%   |
| 1-50          | 1         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 247       | 52.67%  |
| 0     | 197       | 42%     |
| 2     | 23        | 4.9%    |
| 3     | 2         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 340       | 46.38%  |
| Realtek Semiconductor             | 139       | 18.96%  |
| Broadcom                          | 58        | 7.91%   |
| AMD                               | 55        | 7.5%    |
| Qualcomm Atheros                  | 46        | 6.28%   |
| Sierra Wireless                   | 13        | 1.77%   |
| Ericsson Business Mobile Networks | 13        | 1.77%   |
| Ralink Technology                 | 9         | 1.23%   |
| Edimax Technology                 | 7         | 0.95%   |
| Google                            | 6         | 0.82%   |
| Nvidia                            | 5         | 0.68%   |
| Marvell Technology Group          | 4         | 0.55%   |
| Hewlett-Packard                   | 4         | 0.55%   |
| TP-Link                           | 3         | 0.41%   |
| Ralink                            | 3         | 0.41%   |
| MediaTek                          | 3         | 0.41%   |
| Dell                              | 3         | 0.41%   |
| ASUSTek Computer                  | 3         | 0.41%   |
| Apple                             | 3         | 0.41%   |
| Qualcomm Technologies             | 2         | 0.27%   |
| Huawei Technologies               | 2         | 0.27%   |
| ULi Electronics                   | 1         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.14%   |
| Samsung Electronics               | 1         | 0.14%   |
| Qualcomm Atheros Communications   | 1         | 0.14%   |
| National Semiconductor            | 1         | 0.14%   |
| Micro Star International          | 1         | 0.14%   |
| Mercucys                          | 1         | 0.14%   |
| Lenovo                            | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| Fibocom                           | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| Aquantia                          | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller      | 105       | 11.34%  |
| AMD XGMAC 10GbE Controller                                                  | 55        | 5.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 42        | 4.54%   |
| Intel I210 Gigabit Network Connection                                       | 37        | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 28        | 3.02%   |
| Intel Wireless 8265 / 8275                                                  | 24        | 2.59%   |
| Intel Wireless 7265                                                         | 23        | 2.48%   |
| Intel Wireless 8260                                                         | 22        | 2.38%   |
| Intel Wi-Fi 6 AX200                                                         | 19        | 2.05%   |
| Intel I211 Gigabit Network Connection                                       | 17        | 1.84%   |
| Intel Ethernet Connection I219-LM                                           | 17        | 1.84%   |
| Intel Centrino Ultimate-N 6300                                              | 17        | 1.84%   |
| Intel Wireless 7260                                                         | 16        | 1.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 14        | 1.51%   |
| Intel Ethernet Connection (4) I219-LM                                       | 13        | 1.4%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                   | 11        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                         | 11        | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                                       | 11        | 1.19%   |
| Intel Ethernet Connection I217-LM                                           | 10        | 1.08%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                | 10        | 1.08%   |
| Intel Ethernet Controller I226-V                                            | 9         | 0.97%   |
| Intel Ethernet Controller I225-V                                            | 9         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                    | 9         | 0.97%   |
| Sierra Wireless EM7455                                                      | 8         | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 8         | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 8         | 0.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                     | 8         | 0.86%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 8         | 0.86%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 8         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 7         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                                        | 7         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 6         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 6         | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 6         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 6         | 0.65%   |
| Intel Ethernet Connection I218-LM                                           | 6         | 0.65%   |
| Intel Centrino Advanced-N 6200                                              | 6         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 6         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 5         | 0.54%   |
| Intel Wireless 3165                                                         | 5         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 61.26%  |
| Broadcom                        | 44        | 10.65%  |
| Qualcomm Atheros                | 41        | 9.93%   |
| Realtek Semiconductor           | 32        | 7.75%   |
| Sierra Wireless                 | 9         | 2.18%   |
| Ralink Technology               | 9         | 2.18%   |
| Edimax Technology               | 7         | 1.69%   |
| TP-Link                         | 3         | 0.73%   |
| Ralink                          | 3         | 0.73%   |
| MediaTek                        | 3         | 0.73%   |
| ASUSTek Computer                | 3         | 0.73%   |
| Qualcomm Technologies           | 2         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| Micro Star International        | 1         | 0.24%   |
| Mercucys                        | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 6.73%   |
| Intel Wireless 8265 / 8275                                     | 24        | 5.77%   |
| Intel Wireless 7265                                            | 23        | 5.53%   |
| Intel Wireless 8260                                            | 22        | 5.29%   |
| Intel Wi-Fi 6 AX200                                            | 19        | 4.57%   |
| Intel Centrino Ultimate-N 6300                                 | 17        | 4.09%   |
| Intel Wireless 7260                                            | 16        | 3.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 11        | 2.64%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 2.64%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 10        | 2.4%    |
| Sierra Wireless EM7455                                         | 8         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.92%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 8         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 8         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 1.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 6         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.2%    |
| Intel Wireless 3165                                            | 5         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.2%    |
| Intel Centrino Advanced-N 6200                                 | 5         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.2%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 5         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.96%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.96%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.96%   |
| Intel WiFi Link 5100                                           | 3         | 0.72%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 0.72%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 3         | 0.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 234       | 49.68%  |
| Realtek Semiconductor    | 127       | 26.96%  |
| AMD                      | 55        | 11.68%  |
| Broadcom                 | 22        | 4.67%   |
| Qualcomm Atheros         | 10        | 2.12%   |
| Nvidia                   | 5         | 1.06%   |
| Google                   | 5         | 1.06%   |
| Marvell Technology Group | 4         | 0.85%   |
| Apple                    | 3         | 0.64%   |
| Samsung Electronics      | 1         | 0.21%   |
| National Semiconductor   | 1         | 0.21%   |
| Lenovo                   | 1         | 0.21%   |
| JMicron Technology       | 1         | 0.21%   |
| Huawei Technologies      | 1         | 0.21%   |
| Aquantia                 | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 105       | 22.06%  |
| AMD XGMAC 10GbE Controller                                             | 55        | 11.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 8.82%   |
| Intel I210 Gigabit Network Connection                                  | 37        | 7.77%   |
| Intel I211 Gigabit Network Connection                                  | 17        | 3.57%   |
| Intel Ethernet Connection I219-LM                                      | 17        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 14        | 2.94%   |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 2.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 2.31%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 2.1%    |
| Intel Ethernet Controller I226-V                                       | 9         | 1.89%   |
| Intel Ethernet Controller I225-V                                       | 9         | 1.89%   |
| Intel 82577LM Gigabit Network Connection                               | 9         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 1.47%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 1.26%   |
| Intel Ethernet Connection I219-V                                       | 5         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 1.05%   |
| Google Nexus/Pixel Device (tether)                                     | 5         | 1.05%   |
| Realtek USB 2.5GbE Controller                                          | 4         | 0.84%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.63%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.63%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 0.63%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 0.63%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                        | 3         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.42%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.42%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.42%   |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.42%   |
| Intel 82579V Gigabit Network Connection                                | 2         | 0.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 408       | 50.25%  |
| WiFi     | 369       | 45.44%  |
| Unknown  | 20        | 2.46%   |
| Modem    | 15        | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 293       | 56.45%  |
| WiFi     | 217       | 41.81%  |
| Unknown  | 8         | 1.54%   |
| Modem    | 1         | 0.19%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 302       | 65.8%   |
| 1     | 68        | 14.81%  |
| 6     | 37        | 8.06%   |
| 5     | 29        | 6.32%   |
| 3     | 14        | 3.05%   |
| 0     | 4         | 0.87%   |
| 9     | 2         | 0.44%   |
| 8     | 1         | 0.22%   |
| 7     | 1         | 0.22%   |
| 4     | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 385       | 83.15%  |
| Yes  | 78        | 16.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 146       | 55.3%   |
| Broadcom                        | 26        | 9.85%   |
| Apple                           | 25        | 9.47%   |
| Qualcomm Atheros Communications | 16        | 6.06%   |
| Realtek Semiconductor           | 14        | 5.3%    |
| Foxconn / Hon Hai               | 8         | 3.03%   |
| Lite-On Technology              | 6         | 2.27%   |
| Dell                            | 5         | 1.89%   |
| Cambridge Silicon Radio         | 4         | 1.52%   |
| IMC Networks                    | 3         | 1.14%   |
| Hewlett-Packard                 | 3         | 1.14%   |
| Alps Electric                   | 3         | 1.14%   |
| USI                             | 2         | 0.76%   |
| ASUSTek Computer                | 2         | 0.76%   |
| Askey Computer                  | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                   | 69        | 25.94%  |
| Intel AX200 Bluetooth                                | 19        | 7.14%   |
| Intel AX201 Bluetooth                                | 17        | 6.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)       | 12        | 4.51%   |
| Apple Bluetooth Host Controller                      | 12        | 4.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]           | 10        | 3.76%   |
| Broadcom BCM2045B (BDC-2.1)                          | 10        | 3.76%   |
| Intel AX210 Bluetooth                                | 9         | 3.38%   |
| Apple Broadcom Built-in Bluetooth                    | 8         | 3.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter             | 7         | 2.63%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                 | 6         | 2.26%   |
| Realtek Bluetooth Adapter                            | 5         | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                | 5         | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver        | 5         | 1.88%   |
| Intel Wireless-AC 3168 Bluetooth                     | 4         | 1.5%    |
| Intel AX211 Bluetooth                                | 4         | 1.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)  | 4         | 1.5%    |
| Realtek Bluetooth 4.2 Adapter                        | 3         | 1.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0               | 3         | 1.13%   |
| Lite-On Bluetooth USB Module                         | 3         | 1.13%   |
| Lite-On Atheros AR3012 Bluetooth                     | 3         | 1.13%   |
| Dell DW375 Bluetooth Module                          | 3         | 1.13%   |
| USI Qualcomm WCN685x Bluetooth Adapter               | 2         | 0.75%   |
| Realtek  Bluetooth 4.2 Adapter                       | 2         | 0.75%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1               | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                    | 2         | 0.75%   |
| IMC Networks Bluetooth Module                        | 2         | 0.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter         | 2         | 0.75%   |
| Foxconn / Hon Hai Bluetooth USB Module               | 2         | 0.75%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module          | 2         | 0.75%   |
| Alps Electric UGTZ4 Bluetooth                        | 2         | 0.75%   |
| Realtek RTL8821A Bluetooth                           | 1         | 0.38%   |
| Realtek RTL8723B Bluetooth                           | 1         | 0.38%   |
| Realtek Bluetooth Radio                              | 1         | 0.38%   |
| Realtek Bluetooth 4.0 + High Speed Chip              | 1         | 0.38%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE  | 1         | 0.38%   |
| Qualcomm Atheros Dell Wireless 1802 Bluetooth 4.0 LE | 1         | 0.38%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth        | 1         | 0.38%   |
| Qualcomm Atheros Bluetooth                           | 1         | 0.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter    | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 344       | 72.12%  |
| AMD                                          | 88        | 18.45%  |
| Nvidia                                       | 27        | 5.66%   |
| Lenovo                                       | 3         | 0.63%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.42%   |
| Realtek Semiconductor                        | 2         | 0.42%   |
| Logitech                                     | 2         | 0.42%   |
| ULi Electronics                              | 1         | 0.21%   |
| Texas Instruments                            | 1         | 0.21%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.21%   |
| Phison Electronics                           | 1         | 0.21%   |
| JMTek                                        | 1         | 0.21%   |
| Hewlett-Packard                              | 1         | 0.21%   |
| GN Netcom                                    | 1         | 0.21%   |
| Corsair                                      | 1         | 0.21%   |
| C-Media Electronics                          | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 63        | 10.79%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 57        | 9.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 45        | 7.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 5.65%   |
| Intel 8 Series HD Audio Controller                                                                | 32        | 5.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 5.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 4.45%   |
| Intel Broadwell-U Audio Controller                                                                | 26        | 4.45%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 18        | 3.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 2.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 16        | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 2.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 2.05%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.37%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 0.86%   |
| AMD Radeon High Definition Audio Controller                                                       | 5         | 0.86%   |
| AMD FCH Azalia Controller                                                                         | 5         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.68%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.68%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 4         | 0.68%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 3         | 0.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.51%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.51%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2         | 0.34%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.34%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.34%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 132       | 27.44%  |
| SK hynix                     | 82        | 17.05%  |
| Transcend                    | 50        | 10.4%   |
| Micron Technology            | 47        | 9.77%   |
| Kingston                     | 46        | 9.56%   |
| Unknown                      | 30        | 6.24%   |
| Crucial                      | 27        | 5.61%   |
| Unknown                      | 13        | 2.7%    |
| Ramaxel Technology           | 12        | 2.49%   |
| Corsair                      | 10        | 2.08%   |
| Elpida                       | 9         | 1.87%   |
| Nanya Technology             | 7         | 1.46%   |
| G.Skill                      | 5         | 1.04%   |
| A-DATA Technology            | 2         | 0.42%   |
| Unknown (ABCD)               | 1         | 0.21%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.21%   |
| Unknown (0x0E51)             | 1         | 0.21%   |
| Team                         | 1         | 0.21%   |
| Qimonda                      | 1         | 0.21%   |
| Patriot                      | 1         | 0.21%   |
| Avant                        | 1         | 0.21%   |
| ASint Technology             | 1         | 0.21%   |
| 48spaces                     | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s       | 32        | 6.46%   |
| Unknown                                                   | 13        | 2.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 10        | 2.02%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 9         | 1.82%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s     | 8         | 1.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 8         | 1.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 7         | 1.41%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s       | 6         | 1.21%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s              | 6         | 1.21%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 6         | 1.21%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 6         | 1.21%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 6         | 1.21%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s   | 6         | 1.21%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s   | 6         | 1.21%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s     | 5         | 1.01%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 5         | 1.01%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 5         | 1.01%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 5         | 1.01%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                | 5         | 1.01%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 4         | 0.81%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 4         | 0.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 4         | 0.81%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 4         | 0.81%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 4         | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s     | 4         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 0.81%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 4         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 3         | 0.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s    | 3         | 0.61%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 3         | 0.61%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s     | 3         | 0.61%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1600MT/s   | 3         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s               | 2         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s               | 2         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                        | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                | 2         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 2         | 0.4%    |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s        | 2         | 0.4%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s     | 2         | 0.4%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 185       | 44.15%  |
| DDR4    | 170       | 40.57%  |
| DDR2    | 24        | 5.73%   |
| LPDDR3  | 9         | 2.15%   |
| LPDDR5  | 7         | 1.67%   |
| LPDDR4  | 7         | 1.67%   |
| DDR5    | 5         | 1.19%   |
| DDR     | 5         | 1.19%   |
| Unknown | 3         | 0.72%   |
| SDRAM   | 2         | 0.48%   |
| RAM     | 1         | 0.24%   |
| DRAM    | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 392       | 93.56%  |
| Row Of Chips | 18        | 4.3%    |
| DIMM         | 4         | 0.95%   |
| Chip         | 4         | 0.95%   |
| Unknown      | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 178       | 39.73%  |
| 4096  | 123       | 27.46%  |
| 16384 | 60        | 13.39%  |
| 2048  | 59        | 13.17%  |
| 1024  | 12        | 2.68%   |
| 32768 | 11        | 2.46%   |
| 512   | 2         | 0.45%   |
| 256   | 2         | 0.45%   |
| 49152 | 1         | 0.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 131       | 29.77%  |
| 2667    | 71        | 16.14%  |
| 3200    | 48        | 10.91%  |
| 1333    | 37        | 8.41%   |
| 2400    | 28        | 6.36%   |
| 2133    | 21        | 4.77%   |
| 667     | 18        | 4.09%   |
| 1334    | 17        | 3.86%   |
| 1867    | 13        | 2.95%   |
| 800     | 10        | 2.27%   |
| Unknown | 9         | 2.05%   |
| 1067    | 8         | 1.82%   |
| 4267    | 6         | 1.36%   |
| 6400    | 5         | 1.14%   |
| 5600    | 5         | 1.14%   |
| 1066    | 5         | 1.14%   |
| 4000    | 2         | 0.45%   |
| 975     | 2         | 0.45%   |
| 533     | 2         | 0.45%   |
| 2933    | 1         | 0.23%   |
| 1639    | 1         | 0.23%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 93        | 36.05%  |
| Bison Electronics                      | 36        | 13.95%  |
| IMC Networks                           | 17        | 6.59%   |
| Realtek Semiconductor                  | 16        | 6.2%    |
| Microdia                               | 14        | 5.43%   |
| Sunplus Innovation Technology          | 12        | 4.65%   |
| Lite-On Technology                     | 12        | 4.65%   |
| Suyin                                  | 11        | 4.26%   |
| Apple                                  | 8         | 3.1%    |
| Syntek                                 | 6         | 2.33%   |
| Lenovo                                 | 5         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 1.94%   |
| Alcor Micro                            | 4         | 1.55%   |
| Quanta                                 | 3         | 1.16%   |
| Luxvisions Innotech Limited            | 3         | 1.16%   |
| Silicon Motion                         | 2         | 0.78%   |
| Ricoh                                  | 2         | 0.78%   |
| Tripath Technology                     | 1         | 0.39%   |
| SunplusIT                              | 1         | 0.39%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.39%   |
| Pixart Imaging                         | 1         | 0.39%   |
| Logitech                               | 1         | 0.39%   |
| Framework                              | 1         | 0.39%   |
| Dell                                   | 1         | 0.39%   |
| Cubeternet                             | 1         | 0.39%   |
| ALi                                    | 1         | 0.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony integrated camera                        | 42        | 16.15%  |
| Bison Integrated Camera                          | 17        | 6.54%   |
| IMC Networks Integrated Camera                   | 8         | 3.08%   |
| Chicony HD WebCam                                | 8         | 3.08%   |
| Lite-On Integrated Camera                        | 7         | 2.69%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 7         | 2.69%   |
| Chicony FJ Camera                                | 6         | 2.31%   |
| Bison SunplusIT Integrated Camera                | 6         | 2.31%   |
| Realtek USB 2.0 PC Camera                        | 5         | 1.92%   |
| Microdia Integrated Webcam                       | 5         | 1.92%   |
| Syntek Integrated Camera                         | 4         | 1.54%   |
| Sunplus Integrated_Webcam_HD                     | 4         | 1.54%   |
| Microdia Integrated_Webcam_HD                    | 4         | 1.54%   |
| Chicony Integrated Camera [ThinkPad]             | 4         | 1.54%   |
| Chicony HP HD Webcam [Fixed]                     | 4         | 1.54%   |
| Chicony Chicony USB2.0 Camera                    | 4         | 1.54%   |
| Bison ThinkPad Integrated Camera                 | 4         | 1.54%   |
| Apple FaceTime HD Camera (Built-in)              | 4         | 1.54%   |
| Suyin RGBIR Camera                               | 3         | 1.15%   |
| Lite-On Realtek PC Camera                        | 3         | 1.15%   |
| Chicony Integrated IR Camera                     | 3         | 1.15%   |
| Syntek Lenovo EasyCamera                         | 2         | 0.77%   |
| Realtek Laptop Camera                            | 2         | 0.77%   |
| Realtek Integrated_Webcam_HD                     | 2         | 0.77%   |
| Quanta HP TrueVision HD Camera                   | 2         | 0.77%   |
| Lite-On HP HD Webcam [Fixed]                     | 2         | 0.77%   |
| Lenovo Integrated Webcam [R5U877]                | 2         | 0.77%   |
| Lenovo Integrated Camera                         | 2         | 0.77%   |
| IMC Networks XHC Camera                          | 2         | 0.77%   |
| IMC Networks Realtek PC Camera                   | 2         | 0.77%   |
| IMC Networks EasyCamera                          | 2         | 0.77%   |
| Chicony Lenovo EasyCamera                        | 2         | 0.77%   |
| Chicony HD WebCam (Acer)                         | 2         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 0.77%   |
| Bison SunplusIT INC. Integrated Camera           | 2         | 0.77%   |
| Bison Lenovo Integrated Webcam                   | 2         | 0.77%   |
| Bison Lenovo EasyCamera                          | 2         | 0.77%   |
| Apple FaceTime HD Camera                         | 2         | 0.77%   |
| Apple FaceTime Camera                            | 2         | 0.77%   |
| Alcor Micro WebCam-HM1355                        | 2         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 34.02%  |
| Synaptics                  | 21        | 21.65%  |
| Upek                       | 12        | 12.37%  |
| Shenzhen Goodix Technology | 7         | 7.22%   |
| LighTuning Technology      | 7         | 7.22%   |
| AuthenTec                  | 7         | 7.22%   |
| Elan Microelectronics      | 3         | 3.09%   |
| Broadcom                   | 3         | 3.09%   |
| STMicroelectronics         | 2         | 2.06%   |
| Next Biometrics            | 1         | 1.03%   |
| FocalTech Systems          | 1         | 1.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 11        | 11.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 11        | 11.34%  |
| Validity Sensors Synaptics WBDI                                              | 9         | 9.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 7         | 7.22%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 5         | 5.15%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 5.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 5         | 5.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 3         | 3.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 3.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 3         | 3.09%   |
| Elan Fingerprint Sensor                                                      | 3         | 3.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 2.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 2.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 2.06%   |
| Synaptics WBDI                                                               | 2         | 2.06%   |
| STMicroelectronics Fingerprint Reader                                        | 2         | 2.06%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 2         | 2.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 2.06%   |
| AuthenTec AES2550 Fingerprint Sensor                                         | 2         | 2.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.06%   |
| Unknown                                                                      | 2         | 2.06%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 1.03%   |
| Upek TCS5B Fingerprint sensor                                                | 1         | 1.03%   |
| Synaptics UWP WBDI Device                                                    | 1         | 1.03%   |
| Synaptics TouchPad                                                           | 1         | 1.03%   |
| Next Biometrics NB-2020-U Fingerprint Reader                                 | 1         | 1.03%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 1.03%   |
| AuthenTec AES2660                                                            | 1         | 1.03%   |
| AuthenTec AES1660                                                            | 1         | 1.03%   |
| AuthenTec AES1600                                                            | 1         | 1.03%   |

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
| 1     | 134       | 28.15%  |
| 2     | 123       | 25.84%  |
| 0     | 99        | 20.8%   |
| 3     | 80        | 16.81%  |
| 4     | 26        | 5.46%   |
| 5     | 12        | 2.52%   |
| 7     | 1         | 0.21%   |
| 6     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 303       | 42.56%  |
| Bluetooth                | 102       | 14.33%  |
| Fingerprint reader       | 84        | 11.8%   |
| Net/wireless             | 74        | 10.39%  |
| Card reader              | 69        | 9.69%   |
| Firewire controller      | 27        | 3.79%   |
| Network                  | 15        | 2.11%   |
| Graphics card            | 10        | 1.4%    |
| Net/ethernet             | 8         | 1.12%   |
| Sound                    | 7         | 0.98%   |
| Storage                  | 5         | 0.7%    |
| Modem                    | 4         | 0.56%   |
| Storage/nvme             | 1         | 0.14%   |
| Storage/ide              | 1         | 0.14%   |
| Storage/ata              | 1         | 0.14%   |
| Dvb card                 | 1         | 0.14%   |

