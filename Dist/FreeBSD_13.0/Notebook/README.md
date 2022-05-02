FreeBSD 13.0 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.0.

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

Total: 131

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | Laptop 15-dw1xxx            | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Acer          | Swift SF114-32              | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Gateway       | NV55C                       | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| Dell          | Latitude E7440              | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Acer          | Aspire A315-23              | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Gateway       | LT27                        | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Lenovo        | V145-15AST 81MT             | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| ASUSTek       | 1215B                       | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| HP            | Notebook                    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Dell          | Latitude E5450              | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| Samsung       | 530XBB                      | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [91d67ba784](https://bsd-hardware.info/?probe=91d67ba784) | Nov 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [1827cc60df](https://bsd-hardware.info/?probe=1827cc60df) | Nov 23, 2021 |
| Acer          | Aspire 5560                 | [e117631726](https://bsd-hardware.info/?probe=e117631726) | Nov 22, 2021 |
| HP            | Laptop 15s-du1xxx           | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | [73774ed18e](https://bsd-hardware.info/?probe=73774ed18e) | Nov 16, 2021 |
| Dell          | G15 5510                    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| HP            | Compaq 6720s                | [06e31b2e77](https://bsd-hardware.info/?probe=06e31b2e77) | Nov 09, 2021 |
| HP            | Mini 110-1000               | [ef66d7a110](https://bsd-hardware.info/?probe=ef66d7a110) | Nov 09, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Lenovo        | G580 26897SJ                | [da14095fb7](https://bsd-hardware.info/?probe=da14095fb7) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| Google        | Terra                       | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Framework     | Laptop                      | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| Dell          | Latitude E7450              | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| ASUSTek       | TP300LD                     | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Dell          | XPS 15 9500                 | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| Samsung       | 300E5M/300E5L               | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Lenovo        | G505 20240                  | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | [d6feef8717](https://bsd-hardware.info/?probe=d6feef8717) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | [9a3c3705d0](https://bsd-hardware.info/?probe=9a3c3705d0) | Jul 23, 2021 |
| Apple         | MacBookPro8,1               | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| Dell          | Inspiron 5758               | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| Dell          | Inspiron 3442               | [8f8cc52f23](https://bsd-hardware.info/?probe=8f8cc52f23) | Jul 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Dell          | Inspiron N5110              | [08641f83e8](https://bsd-hardware.info/?probe=08641f83e8) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Samsung       | NC10                        | [d33644912a](https://bsd-hardware.info/?probe=d33644912a) | Jun 28, 2021 |
| Dell          | Vostro 5481                 | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| Dell          | Inspiron 15-7579            | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | Latitude E4300              | [1150e00893](https://bsd-hardware.info/?probe=1150e00893) | Jun 10, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| Sony          | SVF1421DSGW                 | [64f3f02018](https://bsd-hardware.info/?probe=64f3f02018) | Jun 01, 2021 |
| System76      | Gazelle                     | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| Dell          | Vostro 5568                 | [84a1925fc9](https://bsd-hardware.info/?probe=84a1925fc9) | May 29, 2021 |
| Acer          | Nitro AN515-54              | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| Lenovo        | ThinkPad X220 4291PU5       | [c6d626c350](https://bsd-hardware.info/?probe=c6d626c350) | May 24, 2021 |
| Acer          | Aspire E5-571P              | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| ASUSTek       | 1015PX                      | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Dell          | Latitude D620               | [1bd280a155](https://bsd-hardware.info/?probe=1bd280a155) | May 23, 2021 |
| Notebook      | N7x0WU                      | [70760365d0](https://bsd-hardware.info/?probe=70760365d0) | May 20, 2021 |
| Dell          | Latitude E6410              | [c0115917d2](https://bsd-hardware.info/?probe=c0115917d2) | May 19, 2021 |
| Lenovo        | Z51-70 80K6                 | [89ca4554ca](https://bsd-hardware.info/?probe=89ca4554ca) | May 18, 2021 |
| MSI           | GL65 Leopard 10SFSK         | [a40e426983](https://bsd-hardware.info/?probe=a40e426983) | May 15, 2021 |
| Dell          | Latitude E5550              | [dca8ba9d37](https://bsd-hardware.info/?probe=dca8ba9d37) | May 13, 2021 |
| ASUSTek       | G750JM                      | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Apple         | MacBookPro6,2               | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| Notebook      | NL5xRU                      | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Acer          | Predator PH517-61           | [9e03a76684](https://bsd-hardware.info/?probe=9e03a76684) | May 08, 2021 |
| Dell          | Latitude 5500               | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Toshiba       | TECRA M11                   | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| HP            | Laptop 17-by0xxx            | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| Pegatron      | T12Ah                       | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| Lenovo        | ThinkPad T440p 20AW0049L... | [7660f9b6db](https://bsd-hardware.info/?probe=7660f9b6db) | May 02, 2021 |
| HP            | Laptop 17-by0xxx            | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| HP            | Laptop 17-by0xxx            | [14cf64712f](https://bsd-hardware.info/?probe=14cf64712f) | Apr 29, 2021 |
| Dell          | Latitude E5420              | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | Compaq Presario CQ71        | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| Dell          | Inspiron 3793               | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Dell          | Inspiron N5050              | [2939c4cb17](https://bsd-hardware.info/?probe=2939c4cb17) | Apr 24, 2021 |
| Lenovo        | ThinkPad E14 20RAS0F600     | [94d082c57c](https://bsd-hardware.info/?probe=94d082c57c) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| Toshiba       | Satellite L50-C             | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Dell          | Precision 5520              | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Alienware     | M15x                        | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Lenovo        | ThinkPad Edge E320 1298R... | [6a96e2c5b1](https://bsd-hardware.info/?probe=6a96e2c5b1) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | [7c7573eb45](https://bsd-hardware.info/?probe=7c7573eb45) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0NS00    | [72fb01f474](https://bsd-hardware.info/?probe=72fb01f474) | Apr 22, 2021 |
| HP            | EliteBook 840 G3            | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Dell          | Latitude 5580               | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| Dell          | Latitude E6440              | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| System76      | Lemur Pro                   | [0bd96ef663](https://bsd-hardware.info/?probe=0bd96ef663) | Apr 19, 2021 |
| ASUSTek       | Q500A                       | [c52b593262](https://bsd-hardware.info/?probe=c52b593262) | Apr 17, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Dell          | Inspiron 3521               | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 100       | 96.15%  |
| i386  | 4         | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 27        | 25.96%  |
| KDE5          | 16        | 15.38%  |
| Console       | 13        | 12.5%   |
| TWM           | 12        | 11.54%  |
| i3            | 10        | 9.62%   |
| GNOME         | 9         | 8.65%   |
| MATE          | 7         | 6.73%   |
| Enlightenment | 3         | 2.88%   |
| Openbox       | 2         | 1.92%   |
| LXQt          | 1         | 0.96%   |
| GNUstep       | 1         | 0.96%   |
| Compton       | 1         | 0.96%   |
| Cinnamon      | 1         | 0.96%   |
| AwesomeWM     | 1         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 90        | 86.54%  |
| Console | 13        | 12.5%   |
| Wayland | 1         | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 48        | 46.15%  |
| SDDM    | 20        | 19.23%  |
| LightDM | 10        | 9.62%   |
| SLiM    | 9         | 8.65%   |
| GDM     | 9         | 8.65%   |
| XDM     | 6         | 5.77%   |
| WDM     | 1         | 0.96%   |
| Ly      | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 72        | 69.23%  |
| Unknown         | 11        | 10.58%  |
| en_US           | 10        | 9.62%   |
| fr_FR           | 3         | 2.88%   |
| nb_NO           | 2         | 1.92%   |
| uk_UA           | 1         | 0.96%   |
| ru_RU           | 1         | 0.96%   |
| pl_PL           | 1         | 0.96%   |
| ja_JP           | 1         | 0.96%   |
| it_IT.ISO8859-1 | 1         | 0.96%   |
| en_GB           | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 76        | 72.38%  |
| BIOS | 29        | 27.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 67        | 63.81%  |
| Ufs  | 38        | 36.19%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 95        | 90.48%  |
| MBR  | 10        | 9.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 30.77%  |
| Dell                | 26        | 25%     |
| Hewlett-Packard     | 10        | 9.62%   |
| ASUSTek Computer    | 8         | 7.69%   |
| Acer                | 7         | 6.73%   |
| Toshiba             | 3         | 2.88%   |
| MSI                 | 3         | 2.88%   |
| Apple               | 3         | 2.88%   |
| System76            | 2         | 1.92%   |
| Samsung Electronics | 2         | 1.92%   |
| Notebook            | 2         | 1.92%   |
| Gateway             | 2         | 1.92%   |
| Pegatron            | 1         | 0.96%   |
| Google              | 1         | 0.96%   |
| Framework           | 1         | 0.96%   |
| Alienware           | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba TECRA M11                          | 1         | 0.96%   |
| Toshiba Satellite Pro T130                 | 1         | 0.96%   |
| Toshiba Satellite L50-C                    | 1         | 0.96%   |
| System76 Lemur Pro                         | 1         | 0.96%   |
| System76 Gazelle                           | 1         | 0.96%   |
| Samsung NC10                               | 1         | 0.96%   |
| Samsung 300E5M/300E5L                      | 1         | 0.96%   |
| Pegatron T12Ah                             | 1         | 0.96%   |
| Notebook NL5xRU                            | 1         | 0.96%   |
| Notebook N7x0WU                            | 1         | 0.96%   |
| MSI Summit E13FlipEvo A11MT                | 1         | 0.96%   |
| MSI GS65 Stealth Thin 8RF                  | 1         | 0.96%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.96%   |
| Lenovo Z51-70 80K6                         | 1         | 0.96%   |
| Lenovo V145-15AST 81MT                     | 1         | 0.96%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.96%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.96%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.96%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.96%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.96%   |
| Lenovo ThinkPad T480s 20L8S1GX00           | 1         | 0.96%   |
| Lenovo ThinkPad T470 20HES0ES1F            | 1         | 0.96%   |
| Lenovo ThinkPad T440p 20AWS1JN00           | 1         | 0.96%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.96%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.96%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.96%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.96%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.96%   |
| Lenovo ThinkPad R60e 0658W2M               | 1         | 0.96%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.96%   |
| Lenovo ThinkPad Mini10 3507A31             | 1         | 0.96%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.96%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.96%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 0.96%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 0.96%   |
| Lenovo ThinkPad E14 20RAS0F600             | 1         | 0.96%   |
| Lenovo Rescuer-15ISK 80RQ                  | 1         | 0.96%   |
| Lenovo IdeaPad 330-15IGM 81D1              | 1         | 0.96%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.96%   |
| Lenovo IdeaPad 320-15AST 80XV              | 1         | 0.96%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 0.96%   |
| Lenovo G580 26897SJ                        | 1         | 0.96%   |
| Lenovo G505 20240                          | 1         | 0.96%   |
| Lenovo G40-70 20369                        | 1         | 0.96%   |
| HP Pavilion Laptop 15-cc0xx                | 1         | 0.96%   |
| HP Notebook                                | 1         | 0.96%   |
| HP Mini 110-1000                           | 1         | 0.96%   |
| HP Laptop 17-by0xxx                        | 1         | 0.96%   |
| HP Laptop 15s-du1xxx                       | 1         | 0.96%   |
| HP Laptop 15-dw1xxx                        | 1         | 0.96%   |
| HP ENVY x2 Detachable PC 13                | 1         | 0.96%   |
| HP EliteBook 840 G3                        | 1         | 0.96%   |
| HP Compaq Presario CQ71                    | 1         | 0.96%   |
| HP Compaq 6720s                            | 1         | 0.96%   |
| Google Terra                               | 1         | 0.96%   |
| Gateway NV55C                              | 1         | 0.96%   |
| Gateway LT27                               | 1         | 0.96%   |
| Framework Laptop                           | 1         | 0.96%   |
| Dell XPS 15 9500                           | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 22        | 21.15%  |
| Dell Latitude        | 12        | 11.54%  |
| Dell Inspiron        | 9         | 8.65%   |
| Lenovo IdeaPad       | 4         | 3.85%   |
| Acer Aspire          | 4         | 3.85%   |
| HP Laptop            | 3         | 2.88%   |
| Toshiba Satellite    | 2         | 1.92%   |
| HP Compaq            | 2         | 1.92%   |
| Dell Vostro          | 2         | 1.92%   |
| Dell Precision       | 2         | 1.92%   |
| Toshiba TECRA        | 1         | 0.96%   |
| System76 Lemur       | 1         | 0.96%   |
| System76 Gazelle     | 1         | 0.96%   |
| Samsung NC10         | 1         | 0.96%   |
| Samsung 300E5M       | 1         | 0.96%   |
| Pegatron T12Ah       | 1         | 0.96%   |
| Notebook NL5xRU      | 1         | 0.96%   |
| Notebook N7x0WU      | 1         | 0.96%   |
| MSI Summit           | 1         | 0.96%   |
| MSI GS65             | 1         | 0.96%   |
| MSI GL65             | 1         | 0.96%   |
| Lenovo Z51-70        | 1         | 0.96%   |
| Lenovo V145-15AST    | 1         | 0.96%   |
| Lenovo Rescuer-15ISK | 1         | 0.96%   |
| Lenovo G580          | 1         | 0.96%   |
| Lenovo G505          | 1         | 0.96%   |
| Lenovo G40-70        | 1         | 0.96%   |
| HP Pavilion          | 1         | 0.96%   |
| HP Notebook          | 1         | 0.96%   |
| HP Mini              | 1         | 0.96%   |
| HP ENVY              | 1         | 0.96%   |
| HP EliteBook         | 1         | 0.96%   |
| Google Terra         | 1         | 0.96%   |
| Gateway NV55C        | 1         | 0.96%   |
| Gateway LT27         | 1         | 0.96%   |
| Framework Laptop     | 1         | 0.96%   |
| Dell XPS             | 1         | 0.96%   |
| ASUS VX7SX           | 1         | 0.96%   |
| ASUS TP300LD         | 1         | 0.96%   |
| ASUS ROG             | 1         | 0.96%   |
| ASUS Q500A           | 1         | 0.96%   |
| ASUS G750JM          | 1         | 0.96%   |
| ASUS ASUS            | 1         | 0.96%   |
| ASUS 1215B           | 1         | 0.96%   |
| ASUS 1015PX          | 1         | 0.96%   |
| Apple MacBookPro6    | 1         | 0.96%   |
| Apple MacBookPro5    | 1         | 0.96%   |
| Apple MacBookPro13   | 1         | 0.96%   |
| Alienware M15x       | 1         | 0.96%   |
| Acer Swift           | 1         | 0.96%   |
| Acer Predator        | 1         | 0.96%   |
| Acer Nitro           | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 14.42%  |
| 2020 | 14        | 13.46%  |
| 2011 | 12        | 11.54%  |
| 2018 | 11        | 10.58%  |
| 2021 | 8         | 7.69%   |
| 2015 | 8         | 7.69%   |
| 2010 | 8         | 7.69%   |
| 2012 | 6         | 5.77%   |
| 2017 | 5         | 4.81%   |
| 2014 | 4         | 3.85%   |
| 2008 | 4         | 3.85%   |
| 2016 | 3         | 2.88%   |
| 2013 | 2         | 1.92%   |
| 2009 | 2         | 1.92%   |
| 2022 | 1         | 0.96%   |
| 2006 | 1         | 0.96%   |

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
| No   | 102       | 98.08%  |
| Yes  | 2         | 1.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 39        | 37.14%  |
| 16.01-24.0  | 25        | 23.81%  |
| 4.01-8.0    | 19        | 18.1%   |
| 2.01-3.0    | 6         | 5.71%   |
| 32.01-64.0  | 5         | 4.76%   |
| 24.01-32.0  | 4         | 3.81%   |
| 3.01-4.0    | 3         | 2.86%   |
| 64.01-256.0 | 2         | 1.9%    |
| 0.51-1.0    | 2         | 1.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 55        | 52.38%  |
| 0.51-1.0   | 34        | 32.38%  |
| 1.01-2.0   | 11        | 10.48%  |
| 2.01-3.0   | 2         | 1.9%    |
| 16.01-24.0 | 2         | 1.9%    |
| 4.01-8.0   | 1         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 76.92%  |
| 2      | 18        | 17.31%  |
| 3      | 4         | 3.85%   |
| 0      | 2         | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 67        | 64.42%  |
| Yes       | 37        | 35.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 84.62%  |
| No        | 16        | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 99.04%  |
| No        | 1         | 0.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 71.15%  |
| No        | 30        | 28.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 27        | 25.96%  |
| UK          | 7         | 6.73%   |
| Russia      | 5         | 4.81%   |
| Germany     | 5         | 4.81%   |
| Brazil      | 5         | 4.81%   |
| India       | 4         | 3.85%   |
| France      | 4         | 3.85%   |
| Australia   | 4         | 3.85%   |
| Switzerland | 3         | 2.88%   |
| Mexico      | 3         | 2.88%   |
| Japan       | 3         | 2.88%   |
| Czechia     | 3         | 2.88%   |
| Ukraine     | 2         | 1.92%   |
| Iran        | 2         | 1.92%   |
| Canada      | 2         | 1.92%   |
| Vietnam     | 1         | 0.96%   |
| Thailand    | 1         | 0.96%   |
| Sweden      | 1         | 0.96%   |
| Spain       | 1         | 0.96%   |
| Qatar       | 1         | 0.96%   |
| Poland      | 1         | 0.96%   |
| Norway      | 1         | 0.96%   |
| New Zealand | 1         | 0.96%   |
| Netherlands | 1         | 0.96%   |
| Nepal       | 1         | 0.96%   |
| Namibia     | 1         | 0.96%   |
| Malaysia    | 1         | 0.96%   |
| Italy       | 1         | 0.96%   |
| Indonesia   | 1         | 0.96%   |
| Hungary     | 1         | 0.96%   |
| Guadeloupe  | 1         | 0.96%   |
| Finland     | 1         | 0.96%   |
| Colombia    | 1         | 0.96%   |
| China       | 1         | 0.96%   |
| Chile       | 1         | 0.96%   |
| Bulgaria    | 1         | 0.96%   |
| Austria     | 1         | 0.96%   |
| Armenia     | 1         | 0.96%   |
| Argentina   | 1         | 0.96%   |
| Albania     | 1         | 0.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 2         | 1.9%    |
| Zurich                    | 1         | 0.95%   |
| Yerevan                   | 1         | 0.95%   |
| Yekaterinburg             | 1         | 0.95%   |
| Weimar                    | 1         | 0.95%   |
| Wausau                    | 1         | 0.95%   |
| Vratsa                    | 1         | 0.95%   |
| Vadodara                  | 1         | 0.95%   |
| Vacaville                 | 1         | 0.95%   |
| Tyumen                    | 1         | 0.95%   |
| Tuklaty                   | 1         | 0.95%   |
| TatabÃ¡nya              | 1         | 0.95%   |
| SГЈo Paulo              | 1         | 0.95%   |
| SГЈo JosГ© dos Campos | 1         | 0.95%   |
| Sydney                    | 1         | 0.95%   |
| Swindon                   | 1         | 0.95%   |
| Sundebru                  | 1         | 0.95%   |
| Suginami-ku               | 1         | 0.95%   |
| St Petersburg             | 1         | 0.95%   |
| South Yarra               | 1         | 0.95%   |
| Sofia                     | 1         | 0.95%   |
| SarandГ«                | 1         | 0.95%   |
| San Vicent del Raspeig    | 1         | 0.95%   |
| San Diego                 | 1         | 0.95%   |
| San Benito                | 1         | 0.95%   |
| San Antonio               | 1         | 0.95%   |
| Rugby                     | 1         | 0.95%   |
| Rochester                 | 1         | 0.95%   |
| Rionegro                  | 1         | 0.95%   |
| Rennes                    | 1         | 0.95%   |
| Québec                   | 1         | 0.95%   |
| Prague                    | 1         | 0.95%   |
| Porto UniГЈo            | 1         | 0.95%   |
| Phoenix                   | 1         | 0.95%   |
| Otjiwarongo               | 1         | 0.95%   |
| Nunoa                     | 1         | 0.95%   |
| Nizhniy Novgorod          | 1         | 0.95%   |
| Niagara Falls             | 1         | 0.95%   |
| New Delhi                 | 1         | 0.95%   |
| Montserrat                | 1         | 0.95%   |
| Monterrey                 | 1         | 0.95%   |
| Minot                     | 1         | 0.95%   |
| Milwaukee                 | 1         | 0.95%   |
| Midvale                   | 1         | 0.95%   |
| Melbourne                 | 1         | 0.95%   |
| LГјbeck                 | 1         | 0.95%   |
| Lyon                      | 1         | 0.95%   |
| Linz                      | 1         | 0.95%   |
| Lexington                 | 1         | 0.95%   |
| Leicester                 | 1         | 0.95%   |
| Le Gosier                 | 1         | 0.95%   |
| Kyiv                      | 1         | 0.95%   |
| Kozhikode                 | 1         | 0.95%   |
| Kolkata                   | 1         | 0.95%   |
| Klobuck                   | 1         | 0.95%   |
| Kathmandu                 | 1         | 0.95%   |
| Kaiserslautern            | 1         | 0.95%   |
| Juiz de Fora              | 1         | 0.95%   |
| Jilin City                | 1         | 0.95%   |
| Jakarta                   | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 21     | 16.26%  |
| Samsung Electronics | 20        | 24     | 16.26%  |
| Toshiba             | 12        | 12     | 9.76%   |
| Seagate             | 12        | 12     | 9.76%   |
| Kingston            | 11        | 12     | 8.94%   |
| Crucial             | 10        | 11     | 8.13%   |
| Hitachi             | 7         | 7      | 5.69%   |
| SanDisk             | 5         | 6      | 4.07%   |
| SK Hynix            | 3         | 3      | 2.44%   |
| Fujitsu             | 3         | 4      | 2.44%   |
| Phison              | 2         | 2      | 1.63%   |
| Micron Technology   | 2         | 2      | 1.63%   |
| Intel               | 2         | 2      | 1.63%   |
| HGST                | 2         | 2      | 1.63%   |
| Corsair             | 2         | 2      | 1.63%   |
| Transcend           | 1         | 1      | 0.81%   |
| TCSUNBOW            | 1         | 1      | 0.81%   |
| SSSTC               | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| OWC                 | 1         | 1      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |
| Apacer              | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB         | 5         | 3.91%   |
| Toshiba MQ01ABD100 1TB               | 3         | 2.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 2.34%   |
| Samsung SSD 970 EVO 500GB            | 3         | 2.34%   |
| Kingston SA400S37240G 240GB          | 3         | 2.34%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.56%   |
| Kingston SA400S37120G 120GB          | 2         | 1.56%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.78%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.78%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.78%   |
| WDC WDS100T2B0B-00YS70 1TB           | 1         | 0.78%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.78%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.78%   |
| WDC WD5000BEVT-75A0RT0 500GB         | 1         | 0.78%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 0.78%   |
| WDC WD2500BEVS-08VAT2 250GB          | 1         | 0.78%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.78%   |
| WDC WD1600BEVT-11ZCT0 160GB          | 1         | 0.78%   |
| WDC WD10SPZX-75Z10T1 1TB             | 1         | 0.78%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.78%   |
| WDC WD10SDRW-34A0XS0 1TB             | 1         | 0.78%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.78%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.78%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.78%   |
| WDC WD10JPLX-00MBPT1 1TB             | 1         | 0.78%   |
| WDC PC SN530 NVMe 512GB              | 1         | 0.78%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.78%   |
| Transcend TS240GMTS420S 240GB        | 1         | 0.78%   |
| Toshiba THNSNJ128GMCU 128GB          | 1         | 0.78%   |
| Toshiba THNSF5256GPUK 256GB          | 1         | 0.78%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.78%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.78%   |
| Toshiba MQ01ABD100V 1TB              | 1         | 0.78%   |
| Toshiba MK5061GSY 500GB              | 1         | 0.78%   |
| Toshiba MK2546GSX 250GB              | 1         | 0.78%   |
| Toshiba KXG50ZNV256G NVMe 256GB      | 1         | 0.78%   |
| Toshiba KBG30ZMT512G 512GB           | 1         | 0.78%   |
| TCSUNBOW X3 480GB                    | 1         | 0.78%   |
| SSSTC CVB-8D128-HP 128GB             | 1         | 0.78%   |
| SPCC SPCCSolidStateDisk 256GB        | 1         | 0.78%   |
| SK Hynix SC308 SATA 256GB            | 1         | 0.78%   |
| SK Hynix HFS128G32TNF-N3A0A 128GB    | 1         | 0.78%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.78%   |
| Seagate ST9500420AS 500GB            | 1         | 0.78%   |
| Seagate ST500LX003-1AC15G 500GB      | 1         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 0.78%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 0.78%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.78%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.78%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 0.78%   |
| SanDisk SSD PLUS 120GB               | 1         | 0.78%   |
| SanDisk SDSSDP256G 256GB             | 1         | 0.78%   |
| SanDisk SDSSDH3 1T02 1TB             | 1         | 0.78%   |
| SanDisk SDSSDA120G 120GB             | 1         | 0.78%   |
| SanDisk SD9SN8W512G 512GB            | 1         | 0.78%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB | 1         | 0.78%   |
| Samsung SSD 970 PRO 1TB              | 1         | 0.78%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB         | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 14     | 28.26%  |
| Seagate             | 12        | 12     | 26.09%  |
| Toshiba             | 8         | 8      | 17.39%  |
| Hitachi             | 7         | 7      | 15.22%  |
| Fujitsu             | 3         | 4      | 6.52%   |
| HGST                | 2         | 2      | 4.35%   |
| Samsung Electronics | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 10        | 11     | 19.23%  |
| Samsung Electronics | 9         | 9      | 17.31%  |
| Kingston            | 8         | 9      | 15.38%  |
| SanDisk             | 5         | 6      | 9.62%   |
| WDC                 | 3         | 3      | 5.77%   |
| SK Hynix            | 2         | 2      | 3.85%   |
| Intel               | 2         | 2      | 3.85%   |
| Corsair             | 2         | 2      | 3.85%   |
| Transcend           | 1         | 1      | 1.92%   |
| Toshiba             | 1         | 1      | 1.92%   |
| TCSUNBOW            | 1         | 1      | 1.92%   |
| SSSTC               | 1         | 1      | 1.92%   |
| SPCC                | 1         | 1      | 1.92%   |
| Phison              | 1         | 1      | 1.92%   |
| OWC                 | 1         | 1      | 1.92%   |
| KingSpec            | 1         | 1      | 1.92%   |
| Gigabyte Technology | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |
| Apacer              | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 50        | 55     | 41.67%  |
| HDD  | 45        | 48     | 37.5%   |
| NVMe | 25        | 29     | 20.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 103    | 77.68%  |
| NVMe | 25        | 29     | 22.32%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 71     | 68.13%  |
| 0.51-1.0   | 27        | 30     | 29.67%  |
| 1.01-2.0   | 2         | 2      | 2.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 47        | 44.76%  |
| 251-500    | 27        | 25.71%  |
| 501-1000   | 17        | 16.19%  |
| 51-100     | 7         | 6.67%   |
| 1-20       | 3         | 2.86%   |
| 21-50      | 2         | 1.9%    |
| 1001-2000  | 2         | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 90        | 86.54%  |
| 21-50   | 7         | 6.73%   |
| 101-250 | 4         | 3.85%   |
| 51-100  | 3         | 2.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-80HXZT3 752GB                     | 1         | 1      | 7.14%   |
| WDC WD5000BEVT-75A0RT0 500GB                     | 1         | 1      | 7.14%   |
| WDC WD3200BPVT-75ZEST0 320GB                     | 1         | 1      | 7.14%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 7.14%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 7.14%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 7.14%   |
| Seagate ST1000LM014-1EJ164 1TB                   | 1         | 1      | 7.14%   |
| Samsung Electronics SSD PM841 2.5-inch 7mm 256GB | 1         | 1      | 7.14%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 7.14%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 7.14%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 7.14%   |
| Hitachi HTS543225A7A384 250GB                    | 1         | 1      | 7.14%   |
| Hitachi HTS541612J9SA00 120GB                    | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 28.57%  |
| Seagate             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| Samsung Electronics | 2         | 2      | 14.29%  |
| SSSTC               | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 3         | 3      | 27.27%  |
| Hitachi             | 3         | 3      | 27.27%  |
| Samsung Electronics | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 78.57%  |
| SSD  | 3         | 3      | 21.43%  |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 90        | 118    | 86.54%  |
| Malfunc | 14        | 14     | 13.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 81        | 68.64%  |
| Samsung Electronics         | 11        | 9.32%   |
| AMD                         | 11        | 9.32%   |
| Toshiba                     | 3         | 2.54%   |
| Sandisk                     | 3         | 2.54%   |
| Phison Electronics          | 2         | 1.69%   |
| Micron Technology           | 2         | 1.69%   |
| Kingston Technology Company | 2         | 1.69%   |
| SK Hynix                    | 1         | 0.85%   |
| Nvidia                      | 1         | 0.85%   |
| Apple                       | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 9.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 7.38%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 7.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 6.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 5.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 4.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 2.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.46%   |
| Unknown                                                                          | 3         | 2.46%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.64%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.64%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.82%   |
| Toshiba unknown                                                                  | 1         | 0.82%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.82%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.82%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.82%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.82%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.82%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.82%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.82%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.82%   |
| Apple S3X NVMe Controller                                                        | 1         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.82%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 0.82%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 78        | 66.1%   |
| NVMe | 24        | 20.34%  |
| IDE  | 9         | 7.63%   |
| RAID | 7         | 5.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 87.5%   |
| AMD    | 13        | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz        | 5         | 4.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 4         | 3.85%   |
| Intel CPU Version                        | 3         | 2.88%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 3         | 2.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 2.88%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 2         | 1.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 1.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 2         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 1.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 2         | 1.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 2         | 1.92%   |
| Intel Processor 5Y70 CPU @ 1.10GHz       | 1         | 0.96%   |
| Intel Pentium M                          | 1         | 0.96%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz   | 1         | 0.96%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 0.96%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 0.96%   |
| Intel Genuine CPU                        | 1         | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.96%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz       | 1         | 0.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.96%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 0.96%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 1         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 0.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 1         | 0.96%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 0.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.96%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 0.96%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 0.96%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz       | 1         | 0.96%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 1         | 0.96%   |
| Intel Core i5-6287U CPU @ 3.10GHz        | 1         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 1         | 0.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 1         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 1         | 0.96%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 1         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 1         | 0.96%   |
| Intel Core i5-2430M CPU @ 2.40GH         | 1         | 0.96%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 1         | 0.96%   |
| Intel Core i5-10310U CPU @ 1.70GHz       | 1         | 0.96%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 1         | 0.96%   |
| Intel Core i5 CPU M 560 @ 2.67GH         | 1         | 0.96%   |
| Intel Core i3-8130U CPU @ 2.20GHz        | 1         | 0.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz        | 1         | 0.96%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 1         | 0.96%   |
| Intel Core i3-3227U CPU @ 1.90GHz        | 1         | 0.96%   |
| Intel Core i3-2330M CPU @ 2.20GHz        | 1         | 0.96%   |
| Intel Core i3 CPU M 380 @ 2.53GH         | 1         | 0.96%   |
| Intel Core i3 CPU M 330 @ 2.13GHz        | 1         | 0.96%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz     | 1         | 0.96%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 1         | 0.96%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 1         | 0.96%   |
| Intel Core 2 Duo                         | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 38        | 36.54%  |
| Intel Core i7        | 21        | 20.19%  |
| Intel Core i3        | 9         | 8.65%   |
| Other                | 7         | 6.73%   |
| Intel Core 2 Duo     | 4         | 3.85%   |
| AMD Ryzen 7          | 4         | 3.85%   |
| Intel Atom           | 3         | 2.88%   |
| Intel Pentium Silver | 2         | 1.92%   |
| Intel Pentium        | 2         | 1.92%   |
| Intel Celeron        | 2         | 1.92%   |
| AMD A4               | 2         | 1.92%   |
| Intel Pentium M      | 1         | 0.96%   |
| Intel Pentium Dual   | 1         | 0.96%   |
| Intel Genuine        | 1         | 0.96%   |
| Intel Celeron M      | 1         | 0.96%   |
| AMD Ryzen 9          | 1         | 0.96%   |
| AMD Ryzen 5          | 1         | 0.96%   |
| AMD Ryzen 3          | 1         | 0.96%   |
| AMD E                | 1         | 0.96%   |
| AMD A6               | 1         | 0.96%   |
| AMD A12              | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 54        | 51.92%  |
| 4       | 31        | 29.81%  |
| 6       | 5         | 4.81%   |
| Unknown | 5         | 4.81%   |
| 16      | 3         | 2.88%   |
| 1       | 3         | 2.88%   |
| 8       | 2         | 1.92%   |
| 12      | 1         | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 103       | 99.04%  |
| 2      | 1         | 0.96%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 74        | 71.15%  |
| 1       | 24        | 23.08%  |
| Unknown | 6         | 5.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 25%     |
| SandyBridge   | 9         | 8.65%   |
| Haswell       | 9         | 8.65%   |
| Broadwell     | 7         | 6.73%   |
| Westmere      | 6         | 5.77%   |
| Skylake       | 5         | 4.81%   |
| Penryn        | 5         | 4.81%   |
| IvyBridge     | 5         | 4.81%   |
| Bonnell       | 5         | 4.81%   |
| Goldmont plus | 3         | 2.88%   |
| Excavator     | 3         | 2.88%   |
| Zen+          | 2         | 1.92%   |
| Zen 2         | 2         | 1.92%   |
| TigerLake     | 2         | 1.92%   |
| Silvermont    | 2         | 1.92%   |
| Core          | 2         | 1.92%   |
| CometLake     | 2         | 1.92%   |
| Unknown       | 2         | 1.92%   |
| Zen           | 1         | 0.96%   |
| P6            | 1         | 0.96%   |
| Nehalem       | 1         | 0.96%   |
| K10 Llano     | 1         | 0.96%   |
| Jaguar        | 1         | 0.96%   |
| IceLake       | 1         | 0.96%   |
| Bobcat        | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 68.25%  |
| Nvidia | 23        | 18.25%  |
| AMD    | 17        | 13.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 9         | 6.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 6.02%   |
| Intel HD Graphics 5500                                                                   | 6         | 4.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.01%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 3.01%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 3.01%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.5%    |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.5%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.5%    |
| Intel HD Graphics 530                                                                    | 2         | 1.5%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.5%    |
| AMD Renoir                                                                               | 2         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.75%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.75%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.75%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.75%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.75%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.75%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.75%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.75%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.75%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.75%   |
| Nvidia G98M [GeForce G 103M]                                                             | 1         | 0.75%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.75%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.75%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 0.75%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.75%   |
| Intel Iris Graphics 550                                                                  | 1         | 0.75%   |
| Intel HD Graphics 630                                                                    | 1         | 0.75%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.75%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.75%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                                         | 1         | 0.75%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 0.75%   |
| AMD SuperSumo [Radeon HD 6480G]                                                          | 1         | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.75%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.75%   |
| AMD Rembrandt [Radeon 680M]                                                              | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 54        | 51.92%  |
| Intel + Nvidia | 17        | 16.35%  |
| 2 x Intel      | 11        | 10.58%  |
| 1 x AMD        | 11        | 10.58%  |
| 1 x Nvidia     | 4         | 3.85%   |
| Intel + AMD    | 3         | 2.88%   |
| 2 x AMD        | 2         | 1.92%   |
| 2 x Nvidia     | 1         | 0.96%   |
| AMD + Nvidia   | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 93        | 89.42%  |
| Proprietary | 10        | 9.62%   |
| Unknown     | 1         | 0.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 89.42%  |
| 0.01-0.5   | 6         | 5.77%   |
| 5.01-6.0   | 1         | 0.96%   |
| 3.01-4.0   | 1         | 0.96%   |
| 2.01-3.0   | 1         | 0.96%   |
| 1.01-2.0   | 1         | 0.96%   |
| 0.51-1.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 23        | 26.14%  |
| BOE                  | 14        | 15.91%  |
| LG Display           | 13        | 14.77%  |
| Chimei Innolux       | 9         | 10.23%  |
| Sharp                | 5         | 5.68%   |
| Samsung Electronics  | 5         | 5.68%   |
| Lenovo               | 3         | 3.41%   |
| Toshiba              | 2         | 2.27%   |
| InfoVision           | 2         | 2.27%   |
| Hewlett-Packard      | 2         | 2.27%   |
| AOC                  | 2         | 2.27%   |
| Sceptre Tech         | 1         | 1.14%   |
| Iiyama               | 1         | 1.14%   |
| HannStar             | 1         | 1.14%   |
| Goldstar             | 1         | 1.14%   |
| CPT                  | 1         | 1.14%   |
| ASUSTek Computer     | 1         | 1.14%   |
| Ancor Communications | 1         | 1.14%   |
| AGO                  | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 2.27%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 2.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 2.27%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 1.14%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 1.14%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                | 1         | 1.14%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 1.14%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 1.14%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 1.14%   |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 1.14%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1210x680mm 54.6-inch | 1         | 1.14%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 1.14%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch                | 1         | 1.14%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 1.14%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 1.14%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch            | 1         | 1.14%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 1.14%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.14%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 1.14%   |
| Hewlett-Packard 24ea HPN3393 1920x1080 530x300mm 24.0-inch             | 1         | 1.14%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch              | 1         | 1.14%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 1.14%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                   | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1542 1366x768 340x190mm 15.3-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch        | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1372 1920x1080 290x170mm 13.2-inch       | 1         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch       | 1         | 1.14%   |
| BOE LCD Monitor BOE0806 1920x1080 310x170mm 13.9-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE07BD 1920x1080 310x170mm 13.9-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE0729 1920x1080 340x190mm 15.3-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE06E2 1920x1080 310x170mm 13.9-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE06CB 1920x1080 340x190mm 15.3-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                   | 1         | 1.14%   |
| BOE LCD Monitor BOE069B 1600x900 380x210mm 17.1-inch                   | 1         | 1.14%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                  | 1         | 1.14%   |
| BOE LCD Monitor BOE0620 1366x768 340x190mm 15.3-inch                   | 1         | 1.14%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                   | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 35        | 41.67%  |
| 1366x768 (WXGA)   | 26        | 30.95%  |
| 1600x900 (HD+)    | 5         | 5.95%   |
| 3840x2160 (4K)    | 4         | 4.76%   |
| 1280x800 (WXGA)   | 4         | 4.76%   |
| 1024x600          | 3         | 3.57%   |
| 2560x1080         | 2         | 2.38%   |
| 1920x1200 (WUXGA) | 2         | 2.38%   |
| 1920x540          | 1         | 1.19%   |
| 1280x720 (HD)     | 1         | 1.19%   |
| 1024x768 (XGA)    | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 35        | 40.23%  |
| 13      | 24        | 27.59%  |
| 12      | 5         | 5.75%   |
| 14      | 4         | 4.6%    |
| 10      | 4         | 4.6%    |
| 24      | 3         | 3.45%   |
| 17      | 3         | 3.45%   |
| 27      | 2         | 2.3%    |
| 54      | 1         | 1.15%   |
| 49      | 1         | 1.15%   |
| 34      | 1         | 1.15%   |
| 31      | 1         | 1.15%   |
| 29      | 1         | 1.15%   |
| 23      | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 60.92%  |
| 201-300     | 19        | 21.84%  |
| 501-600     | 6         | 6.9%    |
| 351-400     | 3         | 3.45%   |
| 601-700     | 2         | 2.3%    |
| 1001-1500   | 2         | 2.3%    |
| 701-800     | 1         | 1.15%   |
| Unknown     | 1         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 84.62%  |
| 16/10   | 7         | 8.97%   |
| 4/3     | 2         | 2.56%   |
| 21/9    | 2         | 2.56%   |
| Unknown | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 29        | 33.33%  |
| 81-90          | 22        | 25.29%  |
| 101-110        | 7         | 8.05%   |
| 61-70          | 5         | 5.75%   |
| 71-80          | 4         | 4.6%    |
| 41-50          | 4         | 4.6%    |
| 201-250        | 4         | 4.6%    |
| 301-350        | 3         | 3.45%   |
| 121-130        | 3         | 3.45%   |
| More than 1000 | 2         | 2.3%    |
| 351-500        | 2         | 2.3%    |
| 111-120        | 1         | 1.15%   |
| Unknown        | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 41.38%  |
| 101-120       | 29        | 33.33%  |
| 51-100        | 13        | 14.94%  |
| 161-240       | 4         | 4.6%    |
| More than 240 | 3         | 3.45%   |
| 1-50          | 1         | 1.15%   |
| Unknown       | 1         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 67        | 64.42%  |
| 0     | 26        | 25%     |
| 2     | 10        | 9.62%   |
| 3     | 1         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 61        | 36.75%  |
| Realtek Semiconductor    | 47        | 28.31%  |
| Qualcomm Atheros         | 28        | 16.87%  |
| Broadcom                 | 17        | 10.24%  |
| Samsung Electronics      | 2         | 1.2%    |
| Ralink Technology        | 2         | 1.2%    |
| Edimax Technology        | 2         | 1.2%    |
| Xiaomi                   | 1         | 0.6%    |
| TP-Link                  | 1         | 0.6%    |
| Nvidia                   | 1         | 0.6%    |
| NetGear                  | 1         | 0.6%    |
| MEDIATEK                 | 1         | 0.6%    |
| Marvell Technology Group | 1         | 0.6%    |
| dog hunter               | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 31        | 14.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 5.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.86%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.86%   |
| Intel Wireless 7265                                                     | 6         | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.9%    |
| Intel Wireless 7260                                                     | 4         | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 1.43%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.43%   |
| Intel Wireless 8260                                                     | 3         | 1.43%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 2         | 0.95%   |
| Intel Wireless 3165                                                     | 2         | 0.95%   |
| Intel Wireless 3160                                                     | 2         | 0.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.95%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.95%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.95%   |
| Intel 82577LC Gigabit Network Connection                                | 2         | 0.95%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 0.95%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.48%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.48%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.48%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 0.48%   |
| Intel WiMAX Connection 2400m                                            | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 50.88%  |
| Qualcomm Atheros      | 20        | 17.54%  |
| Realtek Semiconductor | 15        | 13.16%  |
| Broadcom              | 15        | 13.16%  |
| Ralink Technology     | 2         | 1.75%   |
| Edimax Technology     | 2         | 1.75%   |
| TP-Link               | 1         | 0.88%   |
| NetGear               | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 5.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 5.22%   |
| Intel Wireless 8265 / 8275                                              | 6         | 5.22%   |
| Intel Wireless 7265                                                     | 6         | 5.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.48%   |
| Intel Wireless 7260                                                     | 4         | 3.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.61%   |
| Intel Wireless-AC 9260                                                  | 3         | 2.61%   |
| Intel Wireless 8260                                                     | 3         | 2.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.74%   |
| Intel Wireless 3165                                                     | 2         | 1.74%   |
| Intel Wireless 3160                                                     | 2         | 1.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.74%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.74%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.74%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.87%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.87%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.87%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.87%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.87%   |
| Intel WiFi Link 5100                                                    | 1         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.87%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.87%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.87%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.87%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 0.87%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.87%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.87%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.87%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 45.65%  |
| Intel                    | 27        | 29.35%  |
| Qualcomm Atheros         | 12        | 13.04%  |
| Broadcom                 | 6         | 6.52%   |
| Samsung Electronics      | 2         | 2.17%   |
| Xiaomi                   | 1         | 1.09%   |
| Nvidia                   | 1         | 1.09%   |
| Marvell Technology Group | 1         | 1.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 33.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 11.96%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 3.26%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.26%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 2.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 2.17%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.17%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.17%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 2.17%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.09%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.09%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.09%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.09%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.09%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.09%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.09%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.09%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 53.06%  |
| Ethernet | 89        | 45.41%  |
| Unknown  | 2         | 1.02%   |
| Modem    | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 76        | 51.35%  |
| WiFi     | 72        | 48.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 83.65%  |
| 1     | 17        | 16.35%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 89.42%  |
| Yes  | 11        | 10.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 51.39%  |
| Qualcomm Atheros Communications | 10        | 13.89%  |
| Realtek Semiconductor           | 8         | 11.11%  |
| IMC Networks                    | 4         | 5.56%   |
| Broadcom                        | 4         | 5.56%   |
| ASUSTek Computer                | 2         | 2.78%   |
| Apple                           | 2         | 2.78%   |
| Toshiba                         | 1         | 1.39%   |
| Lite-On Technology              | 1         | 1.39%   |
| Hewlett-Packard                 | 1         | 1.39%   |
| Foxconn / Hon Hai               | 1         | 1.39%   |
| Dell                            | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 23.61%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 6.94%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 4         | 5.56%   |
| Intel AX201 Bluetooth                                       | 4         | 5.56%   |
| Realtek  Bluetooth Adapter                                  | 3         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 4.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.78%   |
| Intel AX210 Bluetooth                                       | 2         | 2.78%   |
| Intel AX200 Bluetooth                                       | 2         | 2.78%   |
| IMC Networks Bluetooth module                               | 2         | 2.78%   |
| Apple Bluetooth Host Controller                             | 2         | 2.78%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.39%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.39%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.39%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.39%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.39%   |
| IMC Networks Wireless_Device                                | 1         | 1.39%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.39%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.39%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.39%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.39%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.39%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 90        | 76.92%  |
| AMD                   | 14        | 11.97%  |
| Nvidia                | 11        | 9.4%    |
| Realtek Semiconductor | 1         | 0.85%   |
| Lenovo                | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 10.2%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 6.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 4.76%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 4.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 3.4%    |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 2.04%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.36%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.36%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.68%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Lenovo Lenovo ThinkPad OneLink Pro Dock                                                           | 1         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.68%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 1         | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.68%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 1         | 0.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.68%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.68%   |
| Unknown                                                                                           | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 28.35%  |
| SK Hynix            | 34        | 26.77%  |
| Kingston            | 14        | 11.02%  |
| Micron Technology   | 8         | 6.3%    |
| Crucial             | 8         | 6.3%    |
| Unknown             | 7         | 5.51%   |
| Ramaxel Technology  | 5         | 3.94%   |
| Unknown             | 3         | 2.36%   |
| Smart               | 2         | 1.57%   |
| A-DATA Technology   | 2         | 1.57%   |
| Transcend           | 1         | 0.79%   |
| Teikon              | 1         | 0.79%   |
| Qimonda             | 1         | 0.79%   |
| PUSKILL             | 1         | 0.79%   |
| Neo Forza           | 1         | 0.79%   |
| Nanya Technology    | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |
| Corsair             | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 2.88%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 4         | 2.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 4         | 2.88%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 2.16%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 3         | 2.16%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s          | 3         | 2.16%   |
| Unknown                                                        | 3         | 2.16%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.44%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 1.44%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 1.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.44%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                         | 1         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                     | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                          | 1         | 0.72%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 0.72%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s            | 1         | 0.72%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s         | 1         | 0.72%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 1         | 0.72%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s          | 1         | 0.72%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s           | 1         | 0.72%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.72%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 0.72%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s          | 1         | 0.72%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2133MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2133MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 0.72%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.72%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 1         | 0.72%   |
| SK Hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.72%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 0.72%   |
| Samsung RAM Module 2GB SODIMM 667MT/s                          | 1         | 0.72%   |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s               | 1         | 0.72%   |
| Samsung RAM M471B5673DZ1-CF8 2GB SODIMM DDR3 1066MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 0.72%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s          | 1         | 0.72%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 1866MT/s          | 1         | 0.72%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 42.99%  |
| DDR3    | 46        | 42.99%  |
| DDR2    | 6         | 5.61%   |
| LPDDR3  | 3         | 2.8%    |
| Unknown | 3         | 2.8%    |
| SDRAM   | 1         | 0.93%   |
| LPDDR4  | 1         | 0.93%   |
| DDR     | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 97.17%  |
| Row Of Chips | 2         | 1.89%   |
| Unknown      | 1         | 0.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 42        | 35%     |
| 8192  | 40        | 33.33%  |
| 2048  | 18        | 15%     |
| 16384 | 13        | 10.83%  |
| 1024  | 5         | 4.17%   |
| 32768 | 2         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 25.83%  |
| 2667    | 20        | 16.67%  |
| 2400    | 15        | 12.5%   |
| 2133    | 11        | 9.17%   |
| 1333    | 9         | 7.5%    |
| 3200    | 8         | 6.67%   |
| 1067    | 6         | 5%      |
| 1334    | 5         | 4.17%   |
| 667     | 5         | 4.17%   |
| 975     | 2         | 1.67%   |
| Unknown | 2         | 1.67%   |
| 4800    | 1         | 0.83%   |
| 4267    | 1         | 0.83%   |
| 1866    | 1         | 0.83%   |
| 1066    | 1         | 0.83%   |
| 800     | 1         | 0.83%   |
| 533     | 1         | 0.83%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 22        | 27.85%  |
| IMC Networks                  | 11        | 13.92%  |
| Microdia                      | 10        | 12.66%  |
| Suyin                         | 7         | 8.86%   |
| Realtek Semiconductor         | 7         | 8.86%   |
| Sunplus Innovation Technology | 6         | 7.59%   |
| Acer                          | 5         | 6.33%   |
| Syntek                        | 2         | 2.53%   |
| Quanta                        | 2         | 2.53%   |
| Z-Star Microelectronics       | 1         | 1.27%   |
| Silicon Motion                | 1         | 1.27%   |
| Luxvisions Innotech Limited   | 1         | 1.27%   |
| Lite-On Technology            | 1         | 1.27%   |
| Lenovo                        | 1         | 1.27%   |
| Importek                      | 1         | 1.27%   |
| ALi                           | 1         | 1.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 6.33%   |
| Microdia Integrated Webcam                          | 3         | 3.8%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.8%    |
| IMC Networks Integrated Camera                      | 3         | 3.8%    |
| Chicony HD WebCam                                   | 3         | 3.8%    |
| Suyin 1.3M HD WebCam                                | 2         | 2.53%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.53%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.53%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.53%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 2         | 2.53%   |
| Chicony HP TrueVision HD Camera                     | 2         | 2.53%   |
| Chicony Chicony USB2.0 Camera                       | 2         | 2.53%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 1.27%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.27%   |
| Syntek EasyCamera                                   | 1         | 1.27%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 1.27%   |
| Suyin Integrated Camera                             | 1         | 1.27%   |
| Suyin HP Webcam-101                                 | 1         | 1.27%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.27%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.27%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.27%   |
| Sunplus Integrated Camera                           | 1         | 1.27%   |
| Sunplus Dell HD Webcam                              | 1         | 1.27%   |
| Silicon Motion Web Camera                           | 1         | 1.27%   |
| Realtek USB 2 Webcam                                | 1         | 1.27%   |
| Realtek Realtek PC Camera                           | 1         | 1.27%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.27%   |
| Realtek Integrated Webcam HD                        | 1         | 1.27%   |
| Realtek Integrated Webcam                           | 1         | 1.27%   |
| Quanta VGA WebCam                                   | 1         | 1.27%   |
| Quanta HD Webcam                                    | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.27%   |
| Microdia Integrated Webcam HD                       | 1         | 1.27%   |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.27%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.27%   |
| Lite-On Integrated Camera                           | 1         | 1.27%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.27%   |
| Importek Webcam-101                                 | 1         | 1.27%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.27%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.27%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.27%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.27%   |
| IMC Networks EasyCamera                             | 1         | 1.27%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.27%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.27%   |
| Chicony Sonix ST50220 USB Video Camera              | 1         | 1.27%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.27%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.27%   |
| Chicony HP Universal Camera                         | 1         | 1.27%   |
| Chicony EasyCamera                                  | 1         | 1.27%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 1.27%   |
| ALi Gateway Webcam                                  | 1         | 1.27%   |
| Acer SunplusIT Integrated Camera                    | 1         | 1.27%   |
| Acer Lenovo Integrated Webcam                       | 1         | 1.27%   |
| Acer Lenovo EasyCamera                              | 1         | 1.27%   |
| Acer Integrated Camera                              | 1         | 1.27%   |
| Acer EasyCamera                                     | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 26.67%  |
| Synaptics                  | 4         | 26.67%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Upek                       | 1         | 6.67%   |
| LighTuning Technology      | 1         | 6.67%   |
| Broadcom                   | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 13.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 13.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 6.67%   |
| Shenzhen Goodix FingerPrint                                                  | 1         | 6.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 6.67%   |

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
| 1     | 36        | 34.62%  |
| 2     | 30        | 28.85%  |
| 3     | 18        | 17.31%  |
| 0     | 13        | 12.5%   |
| 4     | 6         | 5.77%   |
| 6     | 1         | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 71        | 41.28%  |
| Net/wireless             | 40        | 23.26%  |
| Bluetooth                | 19        | 11.05%  |
| Fingerprint reader       | 15        | 8.72%   |
| Card reader              | 14        | 8.14%   |
| Firewire controller      | 9         | 5.23%   |
| Storage/nvme             | 1         | 0.58%   |
| Storage                  | 1         | 0.58%   |
| Network                  | 1         | 0.58%   |
| Net/ethernet             | 1         | 0.58%   |

