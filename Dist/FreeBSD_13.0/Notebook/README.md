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

Total: 137

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | Aspire 4552G                | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-NS21M_S                 | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Dell          | Latitude 2100               | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Dell          | Vostro 5590                 | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Acer          | Aspire ES1-132              | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
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
| amd64 | 105       | 95.45%  |
| i386  | 5         | 4.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 29        | 26.36%  |
| KDE5          | 17        | 15.45%  |
| Console       | 15        | 13.64%  |
| TWM           | 12        | 10.91%  |
| i3            | 10        | 9.09%   |
| GNOME         | 9         | 8.18%   |
| MATE          | 8         | 7.27%   |
| Enlightenment | 3         | 2.73%   |
| Openbox       | 2         | 1.82%   |
| LXQt          | 1         | 0.91%   |
| GNUstep       | 1         | 0.91%   |
| Compton       | 1         | 0.91%   |
| Cinnamon      | 1         | 0.91%   |
| AwesomeWM     | 1         | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 94        | 85.45%  |
| Console | 15        | 13.64%  |
| Wayland | 1         | 0.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 50        | 45.45%  |
| SDDM    | 20        | 18.18%  |
| SLiM    | 11        | 10%     |
| LightDM | 11        | 10%     |
| GDM     | 10        | 9.09%   |
| XDM     | 6         | 5.45%   |
| WDM     | 1         | 0.91%   |
| Ly      | 1         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 78        | 70.91%  |
| Unknown         | 11        | 10%     |
| en_US           | 10        | 9.09%   |
| fr_FR           | 3         | 2.73%   |
| nb_NO           | 2         | 1.82%   |
| uk_UA           | 1         | 0.91%   |
| ru_RU           | 1         | 0.91%   |
| pl_PL           | 1         | 0.91%   |
| ja_JP           | 1         | 0.91%   |
| it_IT.ISO8859-1 | 1         | 0.91%   |
| en_GB           | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 79        | 71.17%  |
| BIOS | 32        | 28.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 72        | 64.86%  |
| Ufs  | 39        | 35.14%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 101       | 90.99%  |
| MBR  | 10        | 9.01%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 29.09%  |
| Dell                | 28        | 25.45%  |
| Hewlett-Packard     | 10        | 9.09%   |
| Acer                | 9         | 8.18%   |
| ASUSTek Computer    | 8         | 7.27%   |
| Toshiba             | 3         | 2.73%   |
| Samsung Electronics | 3         | 2.73%   |
| MSI                 | 3         | 2.73%   |
| Apple               | 3         | 2.73%   |
| System76            | 2         | 1.82%   |
| Notebook            | 2         | 1.82%   |
| Gateway             | 2         | 1.82%   |
| Sony                | 1         | 0.91%   |
| Pegatron            | 1         | 0.91%   |
| Google              | 1         | 0.91%   |
| Framework           | 1         | 0.91%   |
| Alienware           | 1         | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba TECRA M11                          | 1         | 0.91%   |
| Toshiba Satellite Pro T130                 | 1         | 0.91%   |
| Toshiba Satellite L50-C                    | 1         | 0.91%   |
| System76 Lemur Pro                         | 1         | 0.91%   |
| System76 Gazelle                           | 1         | 0.91%   |
| Sony VGN-NS21M_S                           | 1         | 0.91%   |
| Samsung NC10                               | 1         | 0.91%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.91%   |
| Samsung 300E5M/300E5L                      | 1         | 0.91%   |
| Pegatron T12Ah                             | 1         | 0.91%   |
| Notebook NL5xRU                            | 1         | 0.91%   |
| Notebook N7x0WU                            | 1         | 0.91%   |
| MSI Summit E13FlipEvo A11MT                | 1         | 0.91%   |
| MSI GS65 Stealth Thin 8RF                  | 1         | 0.91%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.91%   |
| Lenovo Z51-70 80K6                         | 1         | 0.91%   |
| Lenovo V145-15AST 81MT                     | 1         | 0.91%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.91%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.91%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.91%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.91%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.91%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.91%   |
| Lenovo ThinkPad T480s 20L8S1GX00           | 1         | 0.91%   |
| Lenovo ThinkPad T470 20HES0ES1F            | 1         | 0.91%   |
| Lenovo ThinkPad T440p 20AWS1JN00           | 1         | 0.91%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.91%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.91%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.91%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.91%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.91%   |
| Lenovo ThinkPad R60e 0658W2M               | 1         | 0.91%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.91%   |
| Lenovo ThinkPad Mini10 3507A31             | 1         | 0.91%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.91%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.91%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 0.91%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 0.91%   |
| Lenovo ThinkPad E14 20RAS0F600             | 1         | 0.91%   |
| Lenovo Rescuer-15ISK 80RQ                  | 1         | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 22        | 20%     |
| Dell Latitude        | 13        | 11.82%  |
| Dell Inspiron        | 9         | 8.18%   |
| Acer Aspire          | 6         | 5.45%   |
| Lenovo IdeaPad       | 4         | 3.64%   |
| HP Laptop            | 3         | 2.73%   |
| Dell Vostro          | 3         | 2.73%   |
| Toshiba Satellite    | 2         | 1.82%   |
| HP Compaq            | 2         | 1.82%   |
| Dell Precision       | 2         | 1.82%   |
| Toshiba TECRA        | 1         | 0.91%   |
| System76 Lemur       | 1         | 0.91%   |
| System76 Gazelle     | 1         | 0.91%   |
| Sony VGN-NS21M       | 1         | 0.91%   |
| Samsung NC10         | 1         | 0.91%   |
| Samsung 340XAA       | 1         | 0.91%   |
| Samsung 300E5M       | 1         | 0.91%   |
| Pegatron T12Ah       | 1         | 0.91%   |
| Notebook NL5xRU      | 1         | 0.91%   |
| Notebook N7x0WU      | 1         | 0.91%   |
| MSI Summit           | 1         | 0.91%   |
| MSI GS65             | 1         | 0.91%   |
| MSI GL65             | 1         | 0.91%   |
| Lenovo Z51-70        | 1         | 0.91%   |
| Lenovo V145-15AST    | 1         | 0.91%   |
| Lenovo Rescuer-15ISK | 1         | 0.91%   |
| Lenovo G580          | 1         | 0.91%   |
| Lenovo G505          | 1         | 0.91%   |
| Lenovo G40-70        | 1         | 0.91%   |
| HP Pavilion          | 1         | 0.91%   |
| HP Notebook          | 1         | 0.91%   |
| HP Mini              | 1         | 0.91%   |
| HP ENVY              | 1         | 0.91%   |
| HP EliteBook         | 1         | 0.91%   |
| Google Terra         | 1         | 0.91%   |
| Gateway NV55C        | 1         | 0.91%   |
| Gateway LT27         | 1         | 0.91%   |
| Framework Laptop     | 1         | 0.91%   |
| Dell XPS             | 1         | 0.91%   |
| ASUS VX7SX           | 1         | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 15        | 13.64%  |
| 2019 | 15        | 13.64%  |
| 2011 | 13        | 11.82%  |
| 2018 | 12        | 10.91%  |
| 2010 | 9         | 8.18%   |
| 2021 | 8         | 7.27%   |
| 2015 | 8         | 7.27%   |
| 2017 | 6         | 5.45%   |
| 2012 | 6         | 5.45%   |
| 2008 | 5         | 4.55%   |
| 2014 | 4         | 3.64%   |
| 2016 | 3         | 2.73%   |
| 2013 | 2         | 1.82%   |
| 2009 | 2         | 1.82%   |
| 2022 | 1         | 0.91%   |
| 2006 | 1         | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 110       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 98.18%  |
| Yes  | 2         | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 40        | 36.04%  |
| 16.01-24.0  | 26        | 23.42%  |
| 4.01-8.0    | 22        | 19.82%  |
| 2.01-3.0    | 7         | 6.31%   |
| 32.01-64.0  | 5         | 4.5%    |
| 24.01-32.0  | 4         | 3.6%    |
| 3.01-4.0    | 3         | 2.7%    |
| 64.01-256.0 | 2         | 1.8%    |
| 0.51-1.0    | 2         | 1.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 60        | 54.05%  |
| 0.51-1.0   | 35        | 31.53%  |
| 1.01-2.0   | 11        | 9.91%   |
| 2.01-3.0   | 2         | 1.8%    |
| 16.01-24.0 | 2         | 1.8%    |
| 4.01-8.0   | 1         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 78.18%  |
| 2      | 18        | 16.36%  |
| 3      | 4         | 3.64%   |
| 0      | 2         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 64.55%  |
| Yes       | 39        | 35.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 85.45%  |
| No        | 16        | 14.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 99.09%  |
| No        | 1         | 0.91%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 70%     |
| No        | 33        | 30%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 28        | 25.45%  |
| UK          | 8         | 7.27%   |
| Russia      | 6         | 5.45%   |
| Brazil      | 6         | 5.45%   |
| Germany     | 5         | 4.55%   |
| India       | 4         | 3.64%   |
| France      | 4         | 3.64%   |
| Australia   | 4         | 3.64%   |
| Switzerland | 3         | 2.73%   |
| Mexico      | 3         | 2.73%   |
| Japan       | 3         | 2.73%   |
| Czechia     | 3         | 2.73%   |
| Ukraine     | 2         | 1.82%   |
| Iran        | 2         | 1.82%   |
| China       | 2         | 1.82%   |
| Canada      | 2         | 1.82%   |
| Vietnam     | 1         | 0.91%   |
| Turkey      | 1         | 0.91%   |
| Thailand    | 1         | 0.91%   |
| Sweden      | 1         | 0.91%   |
| Spain       | 1         | 0.91%   |
| Qatar       | 1         | 0.91%   |
| Poland      | 1         | 0.91%   |
| Norway      | 1         | 0.91%   |
| New Zealand | 1         | 0.91%   |
| Netherlands | 1         | 0.91%   |
| Nepal       | 1         | 0.91%   |
| Namibia     | 1         | 0.91%   |
| Malaysia    | 1         | 0.91%   |
| Italy       | 1         | 0.91%   |
| Indonesia   | 1         | 0.91%   |
| Hungary     | 1         | 0.91%   |
| Guadeloupe  | 1         | 0.91%   |
| Finland     | 1         | 0.91%   |
| Colombia    | 1         | 0.91%   |
| Chile       | 1         | 0.91%   |
| Bulgaria    | 1         | 0.91%   |
| Austria     | 1         | 0.91%   |
| Armenia     | 1         | 0.91%   |
| Argentina   | 1         | 0.91%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 2         | 1.8%    |
| Zurich                    | 1         | 0.9%    |
| Yerevan                   | 1         | 0.9%    |
| Yekaterinburg             | 1         | 0.9%    |
| Weimar                    | 1         | 0.9%    |
| Wausau                    | 1         | 0.9%    |
| Vratsa                    | 1         | 0.9%    |
| Vadodara                  | 1         | 0.9%    |
| Vacaville                 | 1         | 0.9%    |
| Tyumen                    | 1         | 0.9%    |
| Tuklaty                   | 1         | 0.9%    |
| TatabÃ¡nya              | 1         | 0.9%    |
| SГЈo Paulo              | 1         | 0.9%    |
| SГЈo JosГ© dos Campos | 1         | 0.9%    |
| Sydney                    | 1         | 0.9%    |
| Swindon                   | 1         | 0.9%    |
| Sundebru                  | 1         | 0.9%    |
| Suginami-ku               | 1         | 0.9%    |
| St Petersburg             | 1         | 0.9%    |
| South Yarra               | 1         | 0.9%    |
| Sofia                     | 1         | 0.9%    |
| SarandГ«                | 1         | 0.9%    |
| San Vicent del Raspeig    | 1         | 0.9%    |
| San Diego                 | 1         | 0.9%    |
| San Benito                | 1         | 0.9%    |
| San Antonio               | 1         | 0.9%    |
| Rugby                     | 1         | 0.9%    |
| Rochester                 | 1         | 0.9%    |
| Rionegro                  | 1         | 0.9%    |
| Rennes                    | 1         | 0.9%    |
| Québec                   | 1         | 0.9%    |
| Prague                    | 1         | 0.9%    |
| Porto UniГЈo            | 1         | 0.9%    |
| Phoenix                   | 1         | 0.9%    |
| Otjiwarongo               | 1         | 0.9%    |
| Nunoa                     | 1         | 0.9%    |
| Nizhniy Novgorod          | 1         | 0.9%    |
| Niagara Falls             | 1         | 0.9%    |
| New Delhi                 | 1         | 0.9%    |
| Moscow                    | 1         | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 23     | 17.05%  |
| Samsung Electronics | 21        | 25     | 16.28%  |
| Toshiba             | 12        | 12     | 9.3%    |
| Seagate             | 12        | 12     | 9.3%    |
| Kingston            | 11        | 12     | 8.53%   |
| Crucial             | 11        | 12     | 8.53%   |
| Hitachi             | 7         | 7      | 5.43%   |
| SanDisk             | 5         | 6      | 3.88%   |
| Intel               | 4         | 4      | 3.1%    |
| SK hynix            | 3         | 3      | 2.33%   |
| Fujitsu             | 3         | 4      | 2.33%   |
| Phison              | 2         | 2      | 1.55%   |
| Micron Technology   | 2         | 2      | 1.55%   |
| HGST                | 2         | 2      | 1.55%   |
| Corsair             | 2         | 2      | 1.55%   |
| Transcend           | 1         | 1      | 0.78%   |
| TCSUNBOW            | 1         | 1      | 0.78%   |
| SSSTC               | 1         | 1      | 0.78%   |
| SPCC                | 1         | 1      | 0.78%   |
| PNY                 | 1         | 1      | 0.78%   |
| OWC                 | 1         | 1      | 0.78%   |
| KingSpec            | 1         | 1      | 0.78%   |
| Gigabyte Technology | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |
| Apacer              | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB       | 6         | 4.48%   |
| Toshiba MQ01ABD100 1TB             | 3         | 2.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 2.24%   |
| Samsung SSD 970 EVO 500GB          | 3         | 2.24%   |
| Kingston SA400S37240G 240GB        | 3         | 2.24%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 1.49%   |
| Kingston SA400S37120G 120GB        | 2         | 1.49%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 1         | 0.75%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.75%   |
| WDC WDS120G2G0B-00EPW0 120GB       | 1         | 0.75%   |
| WDC WDS100T2B0B-00YS70 1TB         | 1         | 0.75%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 0.75%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.75%   |
| WDC WD5000LPCX-35VHAT0 500GB       | 1         | 0.75%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 0.75%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 0.75%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.75%   |
| WDC WD2500BEVS-08VAT2 250GB        | 1         | 0.75%   |
| WDC WD20SPZX-22UA7T0 2TB           | 1         | 0.75%   |
| WDC WD1600BEVT-11ZCT0 160GB        | 1         | 0.75%   |
| WDC WD10SPZX-75Z10T1 1TB           | 1         | 0.75%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 0.75%   |
| WDC WD10SDRW-34A0XS0 1TB           | 1         | 0.75%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.75%   |
| WDC WD10JPLX-00MBPT1 1TB           | 1         | 0.75%   |
| WDC PC SN530 NVMe 512GB            | 1         | 0.75%   |
| WDC PC SN520 NVMe 256GB            | 1         | 0.75%   |
| Transcend TS240GMTS420S 240GB      | 1         | 0.75%   |
| Toshiba THNSNJ128GMCU 128GB        | 1         | 0.75%   |
| Toshiba THNSF5256GPUK 256GB        | 1         | 0.75%   |
| Toshiba MQ04ABF100 1TB             | 1         | 0.75%   |
| Toshiba MQ01ABF050 500GB           | 1         | 0.75%   |
| Toshiba MQ01ABD100V 1TB            | 1         | 0.75%   |
| Toshiba MK5061GSY 500GB            | 1         | 0.75%   |
| Toshiba MK2546GSX 250GB            | 1         | 0.75%   |
| Toshiba KXG50ZNV256G NVMe 256GB    | 1         | 0.75%   |
| Toshiba KBG30ZMT512G 512GB         | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 31.25%  |
| Seagate             | 12        | 12     | 25%     |
| Toshiba             | 8         | 8      | 16.67%  |
| Hitachi             | 7         | 7      | 14.58%  |
| Fujitsu             | 3         | 4      | 6.25%   |
| HGST                | 2         | 2      | 4.17%   |
| Samsung Electronics | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 11        | 12     | 20%     |
| Samsung Electronics | 9         | 9      | 16.36%  |
| Kingston            | 8         | 9      | 14.55%  |
| SanDisk             | 5         | 6      | 9.09%   |
| Intel               | 4         | 4      | 7.27%   |
| WDC                 | 3         | 3      | 5.45%   |
| SK hynix            | 2         | 2      | 3.64%   |
| Corsair             | 2         | 2      | 3.64%   |
| Transcend           | 1         | 1      | 1.82%   |
| Toshiba             | 1         | 1      | 1.82%   |
| TCSUNBOW            | 1         | 1      | 1.82%   |
| SSSTC               | 1         | 1      | 1.82%   |
| SPCC                | 1         | 1      | 1.82%   |
| Phison              | 1         | 1      | 1.82%   |
| OWC                 | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 1      | 1.82%   |
| Gigabyte Technology | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |
| Apacer              | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 53        | 58     | 42.06%  |
| HDD  | 47        | 50     | 37.3%   |
| NVMe | 26        | 30     | 20.63%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 108    | 77.97%  |
| NVMe | 26        | 30     | 22.03%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 76     | 69.79%  |
| 0.51-1.0   | 27        | 30     | 28.13%  |
| 1.01-2.0   | 2         | 2      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 47        | 42.34%  |
| 251-500    | 30        | 27.03%  |
| 501-1000   | 17        | 15.32%  |
| 51-100     | 9         | 8.11%   |
| 21-50      | 3         | 2.7%    |
| 1-20       | 3         | 2.7%    |
| 1001-2000  | 2         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 94        | 85.45%  |
| 21-50   | 9         | 8.18%   |
| 101-250 | 4         | 3.64%   |
| 51-100  | 3         | 2.73%   |

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
| Works   | 96        | 124    | 87.27%  |
| Malfunc | 14        | 14     | 12.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 86        | 68.8%   |
| Samsung Electronics         | 12        | 9.6%    |
| AMD                         | 12        | 9.6%    |
| Toshiba                     | 3         | 2.4%    |
| SanDisk                     | 3         | 2.4%    |
| Phison Electronics          | 2         | 1.6%    |
| Micron Technology           | 2         | 1.6%    |
| Kingston Technology Company | 2         | 1.6%    |
| SK hynix                    | 1         | 0.8%    |
| Nvidia                      | 1         | 0.8%    |
| Apple                       | 1         | 0.8%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 9.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 6.98%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 6.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 5.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 3.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 3.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 3.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.1%    |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.33%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.33%   |
| Unknown                                                                          | 3         | 2.33%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.55%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.78%   |
| Toshiba unknown                                                                  | 1         | 0.78%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.78%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 84        | 67.2%   |
| NVMe | 25        | 20%     |
| IDE  | 9         | 7.2%    |
| RAID | 7         | 5.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 87.27%  |
| AMD    | 14        | 12.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz        | 5         | 4.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 4         | 3.64%   |
| Intel CPU Version                        | 3         | 2.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 3         | 2.73%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 3         | 2.73%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 2.73%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 2         | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 1.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 2         | 1.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 1.82%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.82%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 2         | 1.82%   |
| Intel Processor 5Y70 CPU @ 1.10GHz       | 1         | 0.91%   |
| Intel Pentium M                          | 1         | 0.91%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz   | 1         | 0.91%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz   | 1         | 0.91%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 0.91%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 1         | 0.91%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 0.91%   |
| Intel Pentium 4                          | 1         | 0.91%   |
| Intel Genuine CPU                        | 1         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.91%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz       | 1         | 0.91%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.91%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 0.91%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 1         | 0.91%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.91%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 0.91%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 1         | 0.91%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 0.91%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.91%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 0.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 0.91%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz       | 1         | 0.91%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 38        | 34.55%  |
| Intel Core i7        | 22        | 20%     |
| Intel Core i3        | 9         | 8.18%   |
| Other                | 8         | 7.27%   |
| Intel Core 2 Duo     | 4         | 3.64%   |
| AMD Ryzen 7          | 4         | 3.64%   |
| Intel Pentium        | 3         | 2.73%   |
| Intel Celeron        | 3         | 2.73%   |
| Intel Atom           | 3         | 2.73%   |
| Intel Pentium Silver | 2         | 1.82%   |
| Intel Pentium Dual   | 2         | 1.82%   |
| AMD A4               | 2         | 1.82%   |
| Intel Pentium M      | 1         | 0.91%   |
| Intel Pentium 4      | 1         | 0.91%   |
| Intel Genuine        | 1         | 0.91%   |
| Intel Celeron M      | 1         | 0.91%   |
| AMD Ryzen 9          | 1         | 0.91%   |
| AMD Ryzen 5          | 1         | 0.91%   |
| AMD Ryzen 3          | 1         | 0.91%   |
| AMD E                | 1         | 0.91%   |
| AMD A6               | 1         | 0.91%   |
| AMD A12              | 1         | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 56        | 50.91%  |
| 4       | 33        | 30%     |
| Unknown | 6         | 5.45%   |
| 6       | 5         | 4.55%   |
| 1       | 4         | 3.64%   |
| 16      | 3         | 2.73%   |
| 8       | 2         | 1.82%   |
| 12      | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 99.09%  |
| 2      | 1         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 76        | 69.09%  |
| 1       | 27        | 24.55%  |
| Unknown | 7         | 6.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 25.45%  |
| SandyBridge   | 9         | 8.18%   |
| Haswell       | 9         | 8.18%   |
| Broadwell     | 7         | 6.36%   |
| Westmere      | 6         | 5.45%   |
| Bonnell       | 6         | 5.45%   |
| Skylake       | 5         | 4.55%   |
| Penryn        | 5         | 4.55%   |
| IvyBridge     | 5         | 4.55%   |
| Goldmont plus | 3         | 2.73%   |
| Excavator     | 3         | 2.73%   |
| Core          | 3         | 2.73%   |
| Zen+          | 2         | 1.82%   |
| Zen 2         | 2         | 1.82%   |
| TigerLake     | 2         | 1.82%   |
| Silvermont    | 2         | 1.82%   |
| CometLake     | 2         | 1.82%   |
| Unknown       | 2         | 1.82%   |
| Zen           | 1         | 0.91%   |
| P6            | 1         | 0.91%   |
| Nehalem       | 1         | 0.91%   |
| K10 Llano     | 1         | 0.91%   |
| K10           | 1         | 0.91%   |
| Jaguar        | 1         | 0.91%   |
| IceLake       | 1         | 0.91%   |
| Goldmont      | 1         | 0.91%   |
| Bobcat        | 1         | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 68.42%  |
| Nvidia | 24        | 18.05%  |
| AMD    | 18        | 13.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 9         | 6.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.67%   |
| Intel HD Graphics 5500                                                                   | 6         | 4.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 4.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.26%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 3.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.84%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 2.13%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.13%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.13%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 2.13%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.42%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.42%   |
| Intel HD Graphics 530                                                                    | 2         | 1.42%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.42%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.42%   |
| AMD Renoir                                                                               | 2         | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.71%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.71%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.71%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.71%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.71%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.71%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.71%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.71%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.71%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 50.91%  |
| Intel + Nvidia | 18        | 16.36%  |
| 2 x Intel      | 13        | 11.82%  |
| 1 x AMD        | 12        | 10.91%  |
| 1 x Nvidia     | 4         | 3.64%   |
| Intel + AMD    | 3         | 2.73%   |
| 2 x AMD        | 2         | 1.82%   |
| 2 x Nvidia     | 1         | 0.91%   |
| AMD + Nvidia   | 1         | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 98        | 89.09%  |
| Proprietary | 11        | 10%     |
| Unknown     | 1         | 0.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 98        | 89.09%  |
| 0.01-0.5   | 7         | 6.36%   |
| 5.01-6.0   | 1         | 0.91%   |
| 3.01-4.0   | 1         | 0.91%   |
| 2.01-3.0   | 1         | 0.91%   |
| 1.01-2.0   | 1         | 0.91%   |
| 0.51-1.0   | 1         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 24        | 26.97%  |
| BOE                  | 14        | 15.73%  |
| LG Display           | 13        | 14.61%  |
| Chimei Innolux       | 9         | 10.11%  |
| Sharp                | 5         | 5.62%   |
| Samsung Electronics  | 5         | 5.62%   |
| Lenovo               | 3         | 3.37%   |
| Toshiba              | 2         | 2.25%   |
| InfoVision           | 2         | 2.25%   |
| Hewlett-Packard      | 2         | 2.25%   |
| AOC                  | 2         | 2.25%   |
| Sceptre Tech         | 1         | 1.12%   |
| Iiyama               | 1         | 1.12%   |
| HannStar             | 1         | 1.12%   |
| Goldstar             | 1         | 1.12%   |
| CPT                  | 1         | 1.12%   |
| ASUSTek Computer     | 1         | 1.12%   |
| Ancor Communications | 1         | 1.12%   |
| AGO                  | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 3         | 3.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 2.25%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 1.12%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 1.12%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                | 1         | 1.12%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 1.12%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 1.12%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 1.12%   |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 1.12%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 1.12%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 1         | 1.12%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 1.12%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch                | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 1.12%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch            | 1         | 1.12%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 1.12%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.12%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 1.12%   |
| Hewlett-Packard 24ea HPN3393 1920x1080 530x300mm 24.0-inch             | 1         | 1.12%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch              | 1         | 1.12%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 1.12%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                   | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch        | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch       | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 35        | 41.18%  |
| 1366x768 (WXGA)   | 27        | 31.76%  |
| 1600x900 (HD+)    | 5         | 5.88%   |
| 3840x2160 (4K)    | 4         | 4.71%   |
| 1280x800 (WXGA)   | 4         | 4.71%   |
| 1024x600          | 3         | 3.53%   |
| 2560x1080         | 2         | 2.35%   |
| 1920x1200 (WUXGA) | 2         | 2.35%   |
| 1920x540          | 1         | 1.18%   |
| 1280x720 (HD)     | 1         | 1.18%   |
| 1024x768 (XGA)    | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 36        | 40.91%  |
| 13      | 24        | 27.27%  |
| 12      | 5         | 5.68%   |
| 14      | 4         | 4.55%   |
| 10      | 4         | 4.55%   |
| 24      | 3         | 3.41%   |
| 17      | 3         | 3.41%   |
| 27      | 2         | 2.27%   |
| 64      | 1         | 1.14%   |
| 49      | 1         | 1.14%   |
| 34      | 1         | 1.14%   |
| 31      | 1         | 1.14%   |
| 29      | 1         | 1.14%   |
| 23      | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 61.36%  |
| 201-300     | 19        | 21.59%  |
| 501-600     | 6         | 6.82%   |
| 351-400     | 3         | 3.41%   |
| 601-700     | 2         | 2.27%   |
| 1001-1500   | 2         | 2.27%   |
| 701-800     | 1         | 1.14%   |
| Unknown     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 67        | 84.81%  |
| 16/10   | 7         | 8.86%   |
| 4/3     | 2         | 2.53%   |
| 21/9    | 2         | 2.53%   |
| Unknown | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 30        | 34.09%  |
| 81-90          | 22        | 25%     |
| 101-110        | 7         | 7.95%   |
| 61-70          | 5         | 5.68%   |
| 71-80          | 4         | 4.55%   |
| 41-50          | 4         | 4.55%   |
| 201-250        | 4         | 4.55%   |
| 301-350        | 3         | 3.41%   |
| 121-130        | 3         | 3.41%   |
| More than 1000 | 2         | 2.27%   |
| 351-500        | 2         | 2.27%   |
| 111-120        | 1         | 1.14%   |
| Unknown        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 40.91%  |
| 101-120       | 30        | 34.09%  |
| 51-100        | 13        | 14.77%  |
| 161-240       | 4         | 4.55%   |
| More than 240 | 3         | 3.41%   |
| 1-50          | 1         | 1.14%   |
| Unknown       | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 70        | 63.64%  |
| 0     | 29        | 26.36%  |
| 2     | 10        | 9.09%   |
| 3     | 1         | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 63        | 35.39%  |
| Realtek Semiconductor    | 50        | 28.09%  |
| Qualcomm Atheros         | 31        | 17.42%  |
| Broadcom                 | 19        | 10.67%  |
| Samsung Electronics      | 3         | 1.69%   |
| Ralink Technology        | 2         | 1.12%   |
| Marvell Technology Group | 2         | 1.12%   |
| Edimax Technology        | 2         | 1.12%   |
| Xiaomi                   | 1         | 0.56%   |
| TP-Link                  | 1         | 0.56%   |
| Nvidia                   | 1         | 0.56%   |
| NetGear                  | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| dog hunter               | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 14.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 5.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 3.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 2.69%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.69%   |
| Intel Wireless 7265                                               | 6         | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 1.79%   |
| Intel Wireless 7260                                               | 4         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.35%   |
| Intel Wireless-AC 9260                                            | 3         | 1.35%   |
| Intel Wireless 8260                                               | 3         | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.9%    |
| Intel Wireless 3165                                               | 2         | 0.9%    |
| Intel Wireless 3160                                               | 2         | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.9%    |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.9%    |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.9%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 2         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.9%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.9%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 50%     |
| Qualcomm Atheros      | 23        | 19.17%  |
| Broadcom              | 16        | 13.33%  |
| Realtek Semiconductor | 15        | 12.5%   |
| Ralink Technology     | 2         | 1.67%   |
| Edimax Technology     | 2         | 1.67%   |
| TP-Link               | 1         | 0.83%   |
| NetGear               | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 4.96%   |
| Intel Wireless 8265 / 8275                                              | 6         | 4.96%   |
| Intel Wireless 7265                                                     | 6         | 4.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.31%   |
| Intel Wireless 7260                                                     | 4         | 3.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 3.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.48%   |
| Intel Wireless-AC 9260                                                  | 3         | 2.48%   |
| Intel Wireless 8260                                                     | 3         | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.65%   |
| Intel Wireless 3165                                                     | 2         | 1.65%   |
| Intel Wireless 3160                                                     | 2         | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.65%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.65%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.65%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.83%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 45.45%  |
| Intel                    | 27        | 27.27%  |
| Qualcomm Atheros         | 12        | 12.12%  |
| Broadcom                 | 8         | 8.08%   |
| Samsung Electronics      | 3         | 3.03%   |
| Marvell Technology Group | 2         | 2.02%   |
| Xiaomi                   | 1         | 1.01%   |
| Nvidia                   | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 33        | 33.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 12.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.03%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 2.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 2.02%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.02%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.02%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 2.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 2.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.01%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.01%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.01%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.01%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.01%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.01%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.01%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.01%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 52.88%  |
| Ethernet | 95        | 45.67%  |
| Unknown  | 2         | 0.96%   |
| Modem    | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 78        | 50.98%  |
| WiFi     | 75        | 49.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 93        | 84.55%  |
| 1     | 17        | 15.45%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 89.09%  |
| Yes  | 12        | 10.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 52%     |
| Qualcomm Atheros Communications | 11        | 14.67%  |
| Realtek Semiconductor           | 8         | 10.67%  |
| IMC Networks                    | 4         | 5.33%   |
| Broadcom                        | 4         | 5.33%   |
| ASUSTek Computer                | 2         | 2.67%   |
| Apple                           | 2         | 2.67%   |
| Toshiba                         | 1         | 1.33%   |
| Lite-On Technology              | 1         | 1.33%   |
| Hewlett-Packard                 | 1         | 1.33%   |
| Foxconn / Hon Hai               | 1         | 1.33%   |
| Dell                            | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 22.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 8%      |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 5         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 5.33%   |
| Intel AX201 Bluetooth                                       | 4         | 5.33%   |
| Realtek  Bluetooth Adapter                                  | 3         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.67%   |
| Intel AX210 Bluetooth                                       | 2         | 2.67%   |
| Intel AX200 Bluetooth                                       | 2         | 2.67%   |
| IMC Networks Bluetooth module                               | 2         | 2.67%   |
| Apple Bluetooth Host Controller                             | 2         | 2.67%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.33%   |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.33%   |
| IMC Networks Wireless_Device                                | 1         | 1.33%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.33%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.33%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.33%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.33%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.33%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.33%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 94        | 77.05%  |
| AMD                   | 15        | 12.3%   |
| Nvidia                | 11        | 9.02%   |
| Realtek Semiconductor | 1         | 0.82%   |
| Lenovo                | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 10.46%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 4.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 4.58%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 4.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 3.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 3.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.27%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.96%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.31%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.31%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.31%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.31%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.31%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Lenovo Lenovo ThinkPad OneLink Pro Dock                                                           | 1         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 28.89%  |
| SK hynix            | 35        | 25.93%  |
| Kingston            | 14        | 10.37%  |
| Unknown             | 9         | 6.67%   |
| Micron Technology   | 9         | 6.67%   |
| Crucial             | 9         | 6.67%   |
| Ramaxel Technology  | 5         | 3.7%    |
| Unknown             | 3         | 2.22%   |
| Smart               | 2         | 1.48%   |
| A-DATA Technology   | 2         | 1.48%   |
| Transcend           | 1         | 0.74%   |
| Teikon              | 1         | 0.74%   |
| Qimonda             | 1         | 0.74%   |
| PUSKILL             | 1         | 0.74%   |
| Neo Forza           | 1         | 0.74%   |
| Nanya Technology    | 1         | 0.74%   |
| Elpida              | 1         | 0.74%   |
| Corsair             | 1         | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 5         | 3.38%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 4         | 2.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 4         | 2.7%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 2.03%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 3         | 2.03%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 3         | 2.03%   |
| Unknown                                                 | 3         | 2.03%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 2         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 2         | 1.35%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 2         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 1.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 2         | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 1.35%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                  | 1         | 0.68%   |
| Unknown RAM PartNum 0 512MB Chip DDR2 533MT/s           | 1         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s             | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s              | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                   | 1         | 0.68%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 0.68%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s     | 1         | 0.68%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s  | 1         | 0.68%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s   | 1         | 0.68%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s   | 1         | 0.68%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.68%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s            | 1         | 0.68%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s            | 1         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 1         | 0.68%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.68%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s  | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 1         | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1         | 0.68%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s   | 1         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s  | 1         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2133MT/s  | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 42.48%  |
| DDR3    | 48        | 42.48%  |
| DDR2    | 8         | 7.08%   |
| LPDDR3  | 3         | 2.65%   |
| Unknown | 3         | 2.65%   |
| SDRAM   | 1         | 0.88%   |
| LPDDR4  | 1         | 0.88%   |
| DDR     | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 109       | 96.46%  |
| Row Of Chips | 2         | 1.77%   |
| Chip         | 1         | 0.88%   |
| Unknown      | 1         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 44        | 34.65%  |
| 8192  | 42        | 33.07%  |
| 2048  | 19        | 14.96%  |
| 16384 | 13        | 10.24%  |
| 1024  | 7         | 5.51%   |
| 32768 | 2         | 1.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 23.85%  |
| 2667    | 21        | 16.15%  |
| 2400    | 16        | 12.31%  |
| 2133    | 12        | 9.23%   |
| 3200    | 9         | 6.92%   |
| 1333    | 9         | 6.92%   |
| 1067    | 6         | 4.62%   |
| 1334    | 5         | 3.85%   |
| 667     | 5         | 3.85%   |
| 533     | 3         | 2.31%   |
| Unknown | 3         | 2.31%   |
| 1867    | 2         | 1.54%   |
| 975     | 2         | 1.54%   |
| 800     | 2         | 1.54%   |
| 4800    | 1         | 0.77%   |
| 4267    | 1         | 0.77%   |
| 1866    | 1         | 0.77%   |
| 1066    | 1         | 0.77%   |

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
| Chicony Electronics           | 22        | 26.51%  |
| Microdia                      | 11        | 13.25%  |
| IMC Networks                  | 11        | 13.25%  |
| Realtek Semiconductor         | 8         | 9.64%   |
| Suyin                         | 7         | 8.43%   |
| Sunplus Innovation Technology | 6         | 7.23%   |
| Acer                          | 5         | 6.02%   |
| Syntek                        | 2         | 2.41%   |
| Silicon Motion                | 2         | 2.41%   |
| Quanta                        | 2         | 2.41%   |
| ALi                           | 2         | 2.41%   |
| Z-Star Microelectronics       | 1         | 1.2%    |
| Luxvisions Innotech Limited   | 1         | 1.2%    |
| Lite-On Technology            | 1         | 1.2%    |
| Lenovo                        | 1         | 1.2%    |
| Importek                      | 1         | 1.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 6.02%   |
| Microdia Integrated Webcam                          | 4         | 4.82%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.61%   |
| IMC Networks Integrated Camera                      | 3         | 3.61%   |
| Chicony HD WebCam                                   | 3         | 3.61%   |
| Suyin 1.3M HD WebCam                                | 2         | 2.41%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.41%   |
| Silicon Motion Web Camera                           | 2         | 2.41%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.41%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.41%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 2         | 2.41%   |
| Chicony HP TrueVision HD Camera                     | 2         | 2.41%   |
| Chicony Chicony USB2.0 Camera                       | 2         | 2.41%   |
| ALi Gateway Webcam                                  | 2         | 2.41%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 1.2%    |
| Syntek Lenovo EasyCamera                            | 1         | 1.2%    |
| Syntek EasyCamera                                   | 1         | 1.2%    |
| Suyin Lenovo Integrated Webcam                      | 1         | 1.2%    |
| Suyin Integrated Camera                             | 1         | 1.2%    |
| Suyin HP Webcam-101                                 | 1         | 1.2%    |
| Suyin Asus Integrated Webcam                        | 1         | 1.2%    |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.2%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.2%    |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.2%    |
| Sunplus Integrated Camera                           | 1         | 1.2%    |
| Sunplus Dell HD Webcam                              | 1         | 1.2%    |
| Realtek USB 2 Webcam                                | 1         | 1.2%    |
| Realtek Realtek PC Camera                           | 1         | 1.2%    |
| Realtek Lenovo EasyCamera                           | 1         | 1.2%    |
| Realtek Integrated Webcam HD                        | 1         | 1.2%    |
| Realtek Integrated Webcam                           | 1         | 1.2%    |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1.2%    |
| Quanta VGA WebCam                                   | 1         | 1.2%    |
| Quanta HD Webcam                                    | 1         | 1.2%    |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.2%    |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.2%    |
| Microdia Integrated Webcam HD                       | 1         | 1.2%    |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.2%    |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.2%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.2%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 25%     |
| Synaptics                  | 4         | 25%     |
| Shenzhen Goodix Technology | 4         | 25%     |
| Upek                       | 1         | 6.25%   |
| LighTuning Technology      | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 12.5%   |
| Validity Sensors Synaptics WBDI                                              | 2         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 6.25%   |
| Shenzhen Goodix FingerPrint                                                  | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 6.25%   |

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
| 1     | 37        | 33.64%  |
| 2     | 32        | 29.09%  |
| 3     | 18        | 16.36%  |
| 0     | 15        | 13.64%  |
| 4     | 6         | 5.45%   |
| 6     | 1         | 0.91%   |
| 5     | 1         | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 74        | 40.88%  |
| Net/wireless             | 42        | 23.2%   |
| Bluetooth                | 20        | 11.05%  |
| Fingerprint reader       | 16        | 8.84%   |
| Card reader              | 15        | 8.29%   |
| Firewire controller      | 10        | 5.52%   |
| Storage/nvme             | 1         | 0.55%   |
| Storage                  | 1         | 0.55%   |
| Network                  | 1         | 0.55%   |
| Net/ethernet             | 1         | 0.55%   |

