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
| Toshiba       | Satellite L955              | [08a58feb06](https://bsd-hardware.info/?probe=08a58feb06) | Apr 13, 2025 |
| Toshiba       | NB300                       | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
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
| amd64 | 105       | 93.75%  |
| i386  | 7         | 6.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 29        | 25.89%  |
| KDE5          | 18        | 16.07%  |
| Console       | 15        | 13.39%  |
| TWM           | 13        | 11.61%  |
| i3            | 10        | 8.93%   |
| GNOME         | 9         | 8.04%   |
| MATE          | 8         | 7.14%   |
| Enlightenment | 3         | 2.68%   |
| Openbox       | 2         | 1.79%   |
| LXQt          | 1         | 0.89%   |
| GNUstep       | 1         | 0.89%   |
| Compton       | 1         | 0.89%   |
| Cinnamon      | 1         | 0.89%   |
| AwesomeWM     | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 96        | 85.71%  |
| Console | 15        | 13.39%  |
| Wayland | 1         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 51        | 45.54%  |
| SDDM    | 20        | 17.86%  |
| SLiM    | 11        | 9.82%   |
| LightDM | 11        | 9.82%   |
| GDM     | 11        | 9.82%   |
| XDM     | 6         | 5.36%   |
| WDM     | 1         | 0.89%   |
| Ly      | 1         | 0.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 80        | 71.43%  |
| Unknown         | 11        | 9.82%   |
| en_US           | 10        | 8.93%   |
| fr_FR           | 3         | 2.68%   |
| nb_NO           | 2         | 1.79%   |
| uk_UA           | 1         | 0.89%   |
| ru_RU           | 1         | 0.89%   |
| pl_PL           | 1         | 0.89%   |
| ja_JP           | 1         | 0.89%   |
| it_IT.ISO8859-1 | 1         | 0.89%   |
| en_GB           | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 79        | 69.91%  |
| BIOS | 34        | 30.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 72        | 63.72%  |
| Ufs  | 41        | 36.28%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 102       | 90.27%  |
| MBR  | 11        | 9.73%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 28.57%  |
| Dell                | 28        | 25%     |
| Hewlett-Packard     | 10        | 8.93%   |
| Acer                | 9         | 8.04%   |
| ASUSTek Computer    | 8         | 7.14%   |
| Toshiba             | 5         | 4.46%   |
| Samsung Electronics | 3         | 2.68%   |
| MSI                 | 3         | 2.68%   |
| Apple               | 3         | 2.68%   |
| System76            | 2         | 1.79%   |
| Notebook            | 2         | 1.79%   |
| Gateway             | 2         | 1.79%   |
| Sony                | 1         | 0.89%   |
| Pegatron            | 1         | 0.89%   |
| Google              | 1         | 0.89%   |
| Framework           | 1         | 0.89%   |
| Alienware           | 1         | 0.89%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba TECRA M11                          | 1         | 0.89%   |
| Toshiba Satellite Pro T130                 | 1         | 0.89%   |
| Toshiba Satellite L955                     | 1         | 0.89%   |
| Toshiba Satellite L50-C                    | 1         | 0.89%   |
| Toshiba NB300                              | 1         | 0.89%   |
| System76 Lemur Pro                         | 1         | 0.89%   |
| System76 Gazelle                           | 1         | 0.89%   |
| Sony VGN-NS21M_S                           | 1         | 0.89%   |
| Samsung NC10                               | 1         | 0.89%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.89%   |
| Samsung 300E5M/300E5L                      | 1         | 0.89%   |
| Pegatron T12Ah                             | 1         | 0.89%   |
| Notebook NL5xRU                            | 1         | 0.89%   |
| Notebook N7x0WU                            | 1         | 0.89%   |
| MSI Summit E13FlipEvo A11MT                | 1         | 0.89%   |
| MSI GS65 Stealth Thin 8RF                  | 1         | 0.89%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.89%   |
| Lenovo Z51-70 80K6                         | 1         | 0.89%   |
| Lenovo V145-15AST 81MT                     | 1         | 0.89%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.89%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.89%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.89%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.89%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.89%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.89%   |
| Lenovo ThinkPad T480s 20L8S1GX00           | 1         | 0.89%   |
| Lenovo ThinkPad T470 20HES0ES1F            | 1         | 0.89%   |
| Lenovo ThinkPad T440p 20AWS1JN00           | 1         | 0.89%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.89%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.89%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.89%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.89%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.89%   |
| Lenovo ThinkPad R60e 0658W2M               | 1         | 0.89%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.89%   |
| Lenovo ThinkPad Mini10 3507A31             | 1         | 0.89%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.89%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.89%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 0.89%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 0.89%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 22        | 19.64%  |
| Dell Latitude        | 13        | 11.61%  |
| Dell Inspiron        | 9         | 8.04%   |
| Acer Aspire          | 6         | 5.36%   |
| Lenovo IdeaPad       | 4         | 3.57%   |
| Toshiba Satellite    | 3         | 2.68%   |
| HP Laptop            | 3         | 2.68%   |
| Dell Vostro          | 3         | 2.68%   |
| HP Compaq            | 2         | 1.79%   |
| Dell Precision       | 2         | 1.79%   |
| Toshiba TECRA        | 1         | 0.89%   |
| Toshiba NB300        | 1         | 0.89%   |
| System76 Lemur       | 1         | 0.89%   |
| System76 Gazelle     | 1         | 0.89%   |
| Sony VGN-NS21M       | 1         | 0.89%   |
| Samsung NC10         | 1         | 0.89%   |
| Samsung 340XAA       | 1         | 0.89%   |
| Samsung 300E5M       | 1         | 0.89%   |
| Pegatron T12Ah       | 1         | 0.89%   |
| Notebook NL5xRU      | 1         | 0.89%   |
| Notebook N7x0WU      | 1         | 0.89%   |
| MSI Summit           | 1         | 0.89%   |
| MSI GS65             | 1         | 0.89%   |
| MSI GL65             | 1         | 0.89%   |
| Lenovo Z51-70        | 1         | 0.89%   |
| Lenovo V145-15AST    | 1         | 0.89%   |
| Lenovo Rescuer-15ISK | 1         | 0.89%   |
| Lenovo G580          | 1         | 0.89%   |
| Lenovo G505          | 1         | 0.89%   |
| Lenovo G40-70        | 1         | 0.89%   |
| HP Pavilion          | 1         | 0.89%   |
| HP Notebook          | 1         | 0.89%   |
| HP Mini              | 1         | 0.89%   |
| HP ENVY              | 1         | 0.89%   |
| HP EliteBook         | 1         | 0.89%   |
| Google Terra         | 1         | 0.89%   |
| Gateway NV55C        | 1         | 0.89%   |
| Gateway LT27         | 1         | 0.89%   |
| Framework Laptop     | 1         | 0.89%   |
| Dell XPS             | 1         | 0.89%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 16        | 14.29%  |
| 2019 | 14        | 12.5%   |
| 2011 | 13        | 11.61%  |
| 2010 | 10        | 8.93%   |
| 2018 | 9         | 8.04%   |
| 2017 | 8         | 7.14%   |
| 2021 | 7         | 6.25%   |
| 2012 | 7         | 6.25%   |
| 2015 | 6         | 5.36%   |
| 2014 | 5         | 4.46%   |
| 2008 | 5         | 4.46%   |
| 2016 | 4         | 3.57%   |
| 2013 | 4         | 3.57%   |
| 2009 | 2         | 1.79%   |
| 2022 | 1         | 0.89%   |
| 2006 | 1         | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 112       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 98.21%  |
| Yes  | 2         | 1.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 40        | 35.4%   |
| 16.01-24.0  | 26        | 23.01%  |
| 4.01-8.0    | 23        | 20.35%  |
| 2.01-3.0    | 8         | 7.08%   |
| 32.01-64.0  | 5         | 4.42%   |
| 24.01-32.0  | 4         | 3.54%   |
| 3.01-4.0    | 3         | 2.65%   |
| 64.01-256.0 | 2         | 1.77%   |
| 0.51-1.0    | 2         | 1.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 62        | 54.87%  |
| 0.51-1.0   | 35        | 30.97%  |
| 1.01-2.0   | 11        | 9.73%   |
| 2.01-3.0   | 2         | 1.77%   |
| 16.01-24.0 | 2         | 1.77%   |
| 4.01-8.0   | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 78.57%  |
| 2      | 18        | 16.07%  |
| 3      | 4         | 3.57%   |
| 0      | 2         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 64.29%  |
| Yes       | 40        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 85.71%  |
| No        | 16        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 68.75%  |
| No        | 35        | 31.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 29        | 25.89%  |
| UK          | 8         | 7.14%   |
| Russia      | 6         | 5.36%   |
| Brazil      | 6         | 5.36%   |
| Germany     | 5         | 4.46%   |
| France      | 5         | 4.46%   |
| India       | 4         | 3.57%   |
| Australia   | 4         | 3.57%   |
| Switzerland | 3         | 2.68%   |
| Mexico      | 3         | 2.68%   |
| Japan       | 3         | 2.68%   |
| Czechia     | 3         | 2.68%   |
| Ukraine     | 2         | 1.79%   |
| Iran        | 2         | 1.79%   |
| China       | 2         | 1.79%   |
| Canada      | 2         | 1.79%   |
| Vietnam     | 1         | 0.89%   |
| Turkey      | 1         | 0.89%   |
| Thailand    | 1         | 0.89%   |
| Sweden      | 1         | 0.89%   |
| Spain       | 1         | 0.89%   |
| Qatar       | 1         | 0.89%   |
| Poland      | 1         | 0.89%   |
| Norway      | 1         | 0.89%   |
| New Zealand | 1         | 0.89%   |
| Netherlands | 1         | 0.89%   |
| Nepal       | 1         | 0.89%   |
| Namibia     | 1         | 0.89%   |
| Malaysia    | 1         | 0.89%   |
| Italy       | 1         | 0.89%   |
| Indonesia   | 1         | 0.89%   |
| Hungary     | 1         | 0.89%   |
| Guadeloupe  | 1         | 0.89%   |
| Finland     | 1         | 0.89%   |
| Colombia    | 1         | 0.89%   |
| Chile       | 1         | 0.89%   |
| Bulgaria    | 1         | 0.89%   |
| Austria     | 1         | 0.89%   |
| Armenia     | 1         | 0.89%   |
| Argentina   | 1         | 0.89%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Tehran                    | 2         | 1.77%   |
| Zurich                    | 1         | 0.88%   |
| Yerevan                   | 1         | 0.88%   |
| Yekaterinburg             | 1         | 0.88%   |
| Weimar                    | 1         | 0.88%   |
| Wausau                    | 1         | 0.88%   |
| Vratsa                    | 1         | 0.88%   |
| Vadodara                  | 1         | 0.88%   |
| Vacaville                 | 1         | 0.88%   |
| Tyumen                    | 1         | 0.88%   |
| Tuklaty                   | 1         | 0.88%   |
| TatabÃ¡nya              | 1         | 0.88%   |
| SГЈo Paulo              | 1         | 0.88%   |
| SГЈo JosГ© dos Campos | 1         | 0.88%   |
| Sydney                    | 1         | 0.88%   |
| Swindon                   | 1         | 0.88%   |
| Sundebru                  | 1         | 0.88%   |
| Suginami-ku               | 1         | 0.88%   |
| St Petersburg             | 1         | 0.88%   |
| South Yarra               | 1         | 0.88%   |
| Sofia                     | 1         | 0.88%   |
| Seattle                   | 1         | 0.88%   |
| SarandГ«                | 1         | 0.88%   |
| San Vicent del Raspeig    | 1         | 0.88%   |
| San Diego                 | 1         | 0.88%   |
| San Benito                | 1         | 0.88%   |
| San Antonio               | 1         | 0.88%   |
| Rugby                     | 1         | 0.88%   |
| Roubaix                   | 1         | 0.88%   |
| Rochester                 | 1         | 0.88%   |
| Rionegro                  | 1         | 0.88%   |
| Rennes                    | 1         | 0.88%   |
| Québec                   | 1         | 0.88%   |
| Prague                    | 1         | 0.88%   |
| Porto UniГЈo            | 1         | 0.88%   |
| Phoenix                   | 1         | 0.88%   |
| Otjiwarongo               | 1         | 0.88%   |
| Nunoa                     | 1         | 0.88%   |
| Nizhniy Novgorod          | 1         | 0.88%   |
| Niagara Falls             | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 23     | 16.79%  |
| Samsung Electronics | 21        | 25     | 16.03%  |
| Toshiba             | 13        | 13     | 9.92%   |
| Seagate             | 12        | 12     | 9.16%   |
| Kingston            | 11        | 12     | 8.4%    |
| Crucial             | 11        | 12     | 8.4%    |
| Hitachi             | 8         | 8      | 6.11%   |
| SanDisk             | 5         | 6      | 3.82%   |
| Intel               | 4         | 4      | 3.05%   |
| SK hynix            | 3         | 3      | 2.29%   |
| Fujitsu             | 3         | 4      | 2.29%   |
| Phison              | 2         | 2      | 1.53%   |
| Micron Technology   | 2         | 2      | 1.53%   |
| HGST                | 2         | 2      | 1.53%   |
| Corsair             | 2         | 2      | 1.53%   |
| Transcend           | 1         | 1      | 0.76%   |
| TCSUNBOW            | 1         | 1      | 0.76%   |
| SSSTC               | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| PNY                 | 1         | 1      | 0.76%   |
| OWC                 | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB       | 6         | 4.41%   |
| Toshiba MQ01ABD100 1TB             | 3         | 2.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 2.21%   |
| Samsung SSD 970 EVO 500GB          | 3         | 2.21%   |
| Kingston SA400S37240G 240GB        | 3         | 2.21%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 1.47%   |
| Kingston SA400S37120G 120GB        | 2         | 1.47%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 1         | 0.74%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.74%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.74%   |
| WDC WDS120G2G0B-00EPW0 120GB       | 1         | 0.74%   |
| WDC WDS100T2B0B-00YS70 1TB         | 1         | 0.74%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 0.74%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.74%   |
| WDC WD5000LPCX-35VHAT0 500GB       | 1         | 0.74%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 0.74%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 0.74%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.74%   |
| WDC WD2500BEVS-08VAT2 250GB        | 1         | 0.74%   |
| WDC WD20SPZX-22UA7T0 2TB           | 1         | 0.74%   |
| WDC WD1600BEVT-11ZCT0 160GB        | 1         | 0.74%   |
| WDC WD10SPZX-75Z10T1 1TB           | 1         | 0.74%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 0.74%   |
| WDC WD10SDRW-34A0XS0 1TB           | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.74%   |
| WDC WD10JPLX-00MBPT1 1TB           | 1         | 0.74%   |
| WDC PC SN530 NVMe 512GB            | 1         | 0.74%   |
| WDC PC SN520 NVMe 256GB            | 1         | 0.74%   |
| Transcend TS240GMTS420S 240GB      | 1         | 0.74%   |
| Toshiba THNSNJ128GMCU 128GB        | 1         | 0.74%   |
| Toshiba THNSF5256GPUK 256GB        | 1         | 0.74%   |
| Toshiba MQ04ABF100 1TB             | 1         | 0.74%   |
| Toshiba MQ01ABF050 500GB           | 1         | 0.74%   |
| Toshiba MQ01ABD100V 1TB            | 1         | 0.74%   |
| Toshiba MK5061GSY 500GB            | 1         | 0.74%   |
| Toshiba MK2555GSX 250GB            | 1         | 0.74%   |
| Toshiba MK2546GSX 250GB            | 1         | 0.74%   |
| Toshiba KXG50ZNV256G NVMe 256GB    | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 30%     |
| Seagate             | 12        | 12     | 24%     |
| Toshiba             | 9         | 9      | 18%     |
| Hitachi             | 8         | 8      | 16%     |
| Fujitsu             | 3         | 4      | 6%      |
| HGST                | 2         | 2      | 4%      |
| Samsung Electronics | 1         | 1      | 2%      |

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
| SSD  | 53        | 58     | 41.41%  |
| HDD  | 49        | 52     | 38.28%  |
| NVMe | 26        | 30     | 20.31%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 110    | 78.33%  |
| NVMe | 26        | 30     | 21.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 77     | 69.39%  |
| 0.51-1.0   | 28        | 31     | 28.57%  |
| 1.01-2.0   | 2         | 2      | 2.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 48        | 42.48%  |
| 251-500    | 30        | 26.55%  |
| 501-1000   | 18        | 15.93%  |
| 51-100     | 9         | 7.96%   |
| 21-50      | 3         | 2.65%   |
| 1-20       | 3         | 2.65%   |
| 1001-2000  | 2         | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 96        | 85.71%  |
| 21-50   | 9         | 8.04%   |
| 101-250 | 4         | 3.57%   |
| 51-100  | 3         | 2.68%   |

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
| Works   | 98        | 126    | 87.5%   |
| Malfunc | 14        | 14     | 12.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 88        | 69.29%  |
| Samsung Electronics         | 12        | 9.45%   |
| AMD                         | 12        | 9.45%   |
| Toshiba                     | 3         | 2.36%   |
| SanDisk                     | 3         | 2.36%   |
| Phison Electronics          | 2         | 1.57%   |
| Micron Technology           | 2         | 1.57%   |
| Kingston Technology Company | 2         | 1.57%   |
| SK hynix                    | 1         | 0.79%   |
| Nvidia                      | 1         | 0.79%   |
| Apple                       | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 9.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 6.87%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 6.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 6.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 5.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 4.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 3.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 3.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 3.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 2.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.29%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.53%   |
| Toshiba XG5 NVMe SSD Controller                                                  | 1         | 0.76%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.76%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                   | 1         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 1         | 0.76%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                            | 1         | 0.76%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.76%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 1         | 0.76%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 0.76%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 1         | 0.76%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD [E8]                              | 1         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 86        | 67.72%  |
| NVMe | 25        | 19.69%  |
| IDE  | 9         | 7.09%   |
| RAID | 7         | 5.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 87.5%   |
| AMD    | 14        | 12.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz        | 5         | 4.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 4         | 3.57%   |
| Intel CPU Version                        | 3         | 2.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 3         | 2.68%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 3         | 2.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 2.68%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 2         | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 1.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 1.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 2         | 1.79%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 2         | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 1.79%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 1.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.79%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 2         | 1.79%   |
| Intel Processor 5Y70 CPU @ 1.10GHz       | 1         | 0.89%   |
| Intel Pentium M                          | 1         | 0.89%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz   | 1         | 0.89%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz   | 1         | 0.89%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 0.89%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 1         | 0.89%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 0.89%   |
| Intel Pentium 4                          | 1         | 0.89%   |
| Intel Genuine CPU                        | 1         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.89%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz       | 1         | 0.89%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.89%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 1         | 0.89%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.89%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 0.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 1         | 0.89%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.89%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 1         | 0.89%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 1         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 1         | 0.89%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz       | 1         | 0.89%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz       | 1         | 0.89%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 39        | 34.82%  |
| Intel Core i7        | 22        | 19.64%  |
| Other                | 9         | 8.04%   |
| Intel Core i3        | 9         | 8.04%   |
| Intel Core 2 Duo     | 4         | 3.57%   |
| AMD Ryzen 7          | 4         | 3.57%   |
| Intel Pentium        | 3         | 2.68%   |
| Intel Celeron        | 3         | 2.68%   |
| Intel Atom           | 3         | 2.68%   |
| Intel Pentium Silver | 2         | 1.79%   |
| Intel Pentium Dual   | 2         | 1.79%   |
| AMD A4               | 2         | 1.79%   |
| Intel Pentium M      | 1         | 0.89%   |
| Intel Pentium 4      | 1         | 0.89%   |
| Intel Genuine        | 1         | 0.89%   |
| Intel Celeron M      | 1         | 0.89%   |
| AMD Ryzen 9          | 1         | 0.89%   |
| AMD Ryzen 5          | 1         | 0.89%   |
| AMD Ryzen 3          | 1         | 0.89%   |
| AMD E                | 1         | 0.89%   |
| AMD A6               | 1         | 0.89%   |
| AMD A12              | 1         | 0.89%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 57        | 50.89%  |
| 4       | 33        | 29.46%  |
| Unknown | 6         | 5.36%   |
| 6       | 5         | 4.46%   |
| 1       | 5         | 4.46%   |
| 16      | 3         | 2.68%   |
| 8       | 2         | 1.79%   |
| 12      | 1         | 0.89%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 111       | 99.11%  |
| 2      | 1         | 0.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 78        | 69.64%  |
| 1       | 27        | 24.11%  |
| Unknown | 7         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 25%     |
| SandyBridge   | 9         | 8.04%   |
| Haswell       | 9         | 8.04%   |
| Broadwell     | 7         | 6.25%   |
| Bonnell       | 7         | 6.25%   |
| Westmere      | 6         | 5.36%   |
| IvyBridge     | 6         | 5.36%   |
| Skylake       | 5         | 4.46%   |
| Penryn        | 5         | 4.46%   |
| Goldmont plus | 3         | 2.68%   |
| Excavator     | 3         | 2.68%   |
| Core          | 3         | 2.68%   |
| Zen+          | 2         | 1.79%   |
| Zen 2         | 2         | 1.79%   |
| TigerLake     | 2         | 1.79%   |
| Silvermont    | 2         | 1.79%   |
| CometLake     | 2         | 1.79%   |
| Unknown       | 2         | 1.79%   |
| Zen           | 1         | 0.89%   |
| P6            | 1         | 0.89%   |
| Nehalem       | 1         | 0.89%   |
| K10 Llano     | 1         | 0.89%   |
| K10           | 1         | 0.89%   |
| Jaguar        | 1         | 0.89%   |
| IceLake       | 1         | 0.89%   |
| Goldmont      | 1         | 0.89%   |
| Bobcat        | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 93        | 68.89%  |
| Nvidia | 24        | 17.78%  |
| AMD    | 18        | 13.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 9         | 6.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 4.2%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 6         | 4.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.8%    |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 2.1%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 2.1%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 3         | 2.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.1%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.4%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2         | 1.4%    |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 2         | 1.4%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.4%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.4%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.7%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.7%    |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.7%    |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.7%    |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.7%    |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.7%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 50.89%  |
| Intel + Nvidia | 18        | 16.07%  |
| 2 x Intel      | 14        | 12.5%   |
| 1 x AMD        | 12        | 10.71%  |
| 1 x Nvidia     | 4         | 3.57%   |
| Intel + AMD    | 3         | 2.68%   |
| 2 x AMD        | 2         | 1.79%   |
| 2 x Nvidia     | 1         | 0.89%   |
| AMD + Nvidia   | 1         | 0.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 91.07%  |
| Proprietary | 9         | 8.04%   |
| Unknown     | 1         | 0.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 89.29%  |
| 0.01-0.5   | 7         | 6.25%   |
| 5.01-6.0   | 1         | 0.89%   |
| 3.01-4.0   | 1         | 0.89%   |
| 2.01-3.0   | 1         | 0.89%   |
| 1.01-2.0   | 1         | 0.89%   |
| 0.51-1.0   | 1         | 0.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 24        | 26.37%  |
| BOE                  | 14        | 15.38%  |
| LG Display           | 13        | 14.29%  |
| Chimei Innolux       | 10        | 10.99%  |
| Samsung Electronics  | 6         | 6.59%   |
| Sharp                | 5         | 5.49%   |
| Lenovo               | 3         | 3.3%    |
| Toshiba              | 2         | 2.2%    |
| InfoVision           | 2         | 2.2%    |
| Hewlett-Packard      | 2         | 2.2%    |
| AOC                  | 2         | 2.2%    |
| Sceptre Tech         | 1         | 1.1%    |
| Iiyama               | 1         | 1.1%    |
| HannStar             | 1         | 1.1%    |
| Goldstar             | 1         | 1.1%    |
| CPT                  | 1         | 1.1%    |
| ASUSTek Computer     | 1         | 1.1%    |
| Ancor Communications | 1         | 1.1%    |
| AGO                  | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 3         | 3.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 2.2%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 2.2%    |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                        | 1         | 1.1%    |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 1.1%    |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                | 1         | 1.1%    |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 1.1%    |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 1.1%    |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 1.1%    |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 1.1%    |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 1.1%    |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 1.1%    |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD0214 1600x900 340x190mm 15.3-inch            | 1         | 1.1%    |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch                | 1         | 1.1%    |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 1.1%    |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 1.1%    |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch            | 1         | 1.1%    |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 1.1%    |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 1.1%    |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 1.1%    |
| Hewlett-Packard 24ea HPN3393 1920x1080 530x300mm 24.0-inch             | 1         | 1.1%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch              | 1         | 1.1%    |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 1.1%    |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                   | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch        | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 34        | 39.08%  |
| 1366x768 (WXGA)   | 28        | 32.18%  |
| 1600x900 (HD+)    | 5         | 5.75%   |
| 3840x2160 (4K)    | 4         | 4.6%    |
| 1280x800 (WXGA)   | 4         | 4.6%    |
| 1024x600          | 4         | 4.6%    |
| 2560x1080         | 2         | 2.3%    |
| 1920x1200 (WUXGA) | 2         | 2.3%    |
| 2560x1440 (QHD)   | 1         | 1.15%   |
| 1920x540          | 1         | 1.15%   |
| 1280x720 (HD)     | 1         | 1.15%   |
| 1024x768 (XGA)    | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 37        | 41.11%  |
| 13      | 24        | 26.67%  |
| 12      | 5         | 5.56%   |
| 10      | 5         | 5.56%   |
| 14      | 4         | 4.44%   |
| 24      | 3         | 3.33%   |
| 17      | 3         | 3.33%   |
| 27      | 2         | 2.22%   |
| 64      | 1         | 1.11%   |
| 49      | 1         | 1.11%   |
| 40      | 1         | 1.11%   |
| 34      | 1         | 1.11%   |
| 29      | 1         | 1.11%   |
| 23      | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 61.11%  |
| 201-300     | 20        | 22.22%  |
| 501-600     | 6         | 6.67%   |
| 351-400     | 3         | 3.33%   |
| 1001-1500   | 2         | 2.22%   |
| 801-900     | 1         | 1.11%   |
| 701-800     | 1         | 1.11%   |
| 601-700     | 1         | 1.11%   |
| Unknown     | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 69        | 85.19%  |
| 16/10   | 7         | 8.64%   |
| 4/3     | 2         | 2.47%   |
| 21/9    | 2         | 2.47%   |
| Unknown | 1         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 30        | 33.33%  |
| 81-90          | 22        | 24.44%  |
| 101-110        | 8         | 8.89%   |
| 61-70          | 5         | 5.56%   |
| 41-50          | 5         | 5.56%   |
| 71-80          | 4         | 4.44%   |
| 201-250        | 4         | 4.44%   |
| 301-350        | 3         | 3.33%   |
| 121-130        | 3         | 3.33%   |
| More than 1000 | 2         | 2.22%   |
| 351-500        | 1         | 1.11%   |
| 111-120        | 1         | 1.11%   |
| 501-1000       | 1         | 1.11%   |
| Unknown        | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 40%     |
| 101-120       | 31        | 34.44%  |
| 51-100        | 13        | 14.44%  |
| 161-240       | 4         | 4.44%   |
| More than 240 | 3         | 3.33%   |
| 1-50          | 2         | 2.22%   |
| Unknown       | 1         | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 64.29%  |
| 0     | 29        | 25.89%  |
| 2     | 10        | 8.93%   |
| 3     | 1         | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 63        | 34.62%  |
| Realtek Semiconductor    | 52        | 28.57%  |
| Qualcomm Atheros         | 33        | 18.13%  |
| Broadcom                 | 19        | 10.44%  |
| Samsung Electronics      | 3         | 1.65%   |
| Ralink Technology        | 2         | 1.1%    |
| Marvell Technology Group | 2         | 1.1%    |
| Edimax Technology        | 2         | 1.1%    |
| Xiaomi                   | 1         | 0.55%   |
| TP-Link                  | 1         | 0.55%   |
| Nvidia                   | 1         | 0.55%   |
| NetGear                  | 1         | 0.55%   |
| MediaTek                 | 1         | 0.55%   |
| dog hunter               | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 14.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 5.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 3.08%   |
| Intel Wireless 8265 / 8275                                             | 6         | 2.64%   |
| Intel Wireless 7265                                                    | 6         | 2.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 2.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 1.76%   |
| Intel Wireless 7260                                                    | 4         | 1.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 1.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 1.32%   |
| Intel Wireless 8260                                                    | 3         | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 1.32%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.88%   |
| Intel Wireless 3165                                                    | 2         | 0.88%   |
| Intel Wireless 3160                                                    | 2         | 0.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.88%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.88%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 0.88%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 2         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 48.78%  |
| Qualcomm Atheros      | 24        | 19.51%  |
| Realtek Semiconductor | 16        | 13.01%  |
| Broadcom              | 16        | 13.01%  |
| Ralink Technology     | 2         | 1.63%   |
| Edimax Technology     | 2         | 1.63%   |
| TP-Link               | 1         | 0.81%   |
| NetGear               | 1         | 0.81%   |
| MediaTek              | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 5.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 5.65%   |
| Intel Wireless 8265 / 8275                                              | 6         | 4.84%   |
| Intel Wireless 7265                                                     | 6         | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 4.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.23%   |
| Intel Wireless 7260                                                     | 4         | 3.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.42%   |
| Intel Wireless 8260                                                     | 3         | 2.42%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.61%   |
| Intel Wireless 3165                                                     | 2         | 1.61%   |
| Intel Wireless 3160                                                     | 2         | 1.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.61%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.61%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.81%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.81%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.81%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 46        | 45.54%  |
| Intel                    | 27        | 26.73%  |
| Qualcomm Atheros         | 13        | 12.87%  |
| Broadcom                 | 8         | 7.92%   |
| Samsung Electronics      | 3         | 2.97%   |
| Marvell Technology Group | 2         | 1.98%   |
| Xiaomi                   | 1         | 0.99%   |
| Nvidia                   | 1         | 0.99%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 32.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 12.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 4.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 2.97%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.97%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 1.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 1.98%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 1.98%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.98%   |
| Intel 82577LC Gigabit Network Connection                               | 2         | 1.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.98%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.99%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.99%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.99%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.99%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.99%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.99%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.99%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.99%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.99%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.99%   |
| Intel 82562GT 10/100 Network Connection                                | 1         | 0.99%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.99%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 0.99%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express               | 1         | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 0.99%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 53.3%   |
| Ethernet | 97        | 45.75%  |
| Modem    | 1         | 0.47%   |
| Unknown  | 1         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 78        | 50.32%  |
| WiFi     | 77        | 49.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 95        | 84.82%  |
| 1     | 17        | 15.18%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 88.39%  |
| Yes  | 13        | 11.61%  |

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
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 5.33%   |
| Intel AX201 Bluetooth                                       | 4         | 5.33%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 4%      |
| Realtek Bluetooth Adapter                                   | 3         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.67%   |
| Intel AX210 Bluetooth                                       | 2         | 2.67%   |
| Intel AX200 Bluetooth                                       | 2         | 2.67%   |
| IMC Networks Bluetooth module                               | 2         | 2.67%   |
| Apple Bluetooth Host Controller                             | 2         | 2.67%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.33%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.33%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.33%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.33%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 1.33%   |
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
| Intel                 | 96        | 77.42%  |
| AMD                   | 15        | 12.1%   |
| Nvidia                | 11        | 8.87%   |
| Realtek Semiconductor | 1         | 0.81%   |
| Lenovo                | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 10.32%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 5.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 5.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 4.52%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 4.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.52%   |
| AMD Ryzen HD Audio Controller                                                                     | 6         | 3.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.58%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.94%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3         | 1.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.94%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.29%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.29%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.29%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.65%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Lenovo ThinkPad OneLink Pro Dock                                                                  | 1         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 29.2%   |
| SK hynix            | 35        | 25.55%  |
| Kingston            | 14        | 10.22%  |
| Unknown             | 10        | 7.3%    |
| Micron Technology   | 9         | 6.57%   |
| Crucial             | 9         | 6.57%   |
| Ramaxel Technology  | 5         | 3.65%   |
| Unknown             | 3         | 2.19%   |
| Smart               | 2         | 1.46%   |
| A-DATA Technology   | 2         | 1.46%   |
| Transcend           | 1         | 0.73%   |
| Teikon              | 1         | 0.73%   |
| Qimonda             | 1         | 0.73%   |
| PUSKILL             | 1         | 0.73%   |
| Neo Forza           | 1         | 0.73%   |
| Nanya Technology    | 1         | 0.73%   |
| Elpida              | 1         | 0.73%   |
| Corsair             | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 5         | 3.31%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 4         | 2.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s   | 4         | 2.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 1.99%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 3         | 1.99%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 3         | 1.99%   |
| Unknown                                                 | 3         | 1.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 2         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 2         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 1.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 2         | 1.32%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s   | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 1.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 2         | 1.32%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 1.32%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                  | 1         | 0.66%   |
| Unknown RAM PartNum 0 512MB Chip DDR2 533MT/s           | 1         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s             | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s              | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                   | 1         | 0.66%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 0.66%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s     | 1         | 0.66%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s  | 1         | 0.66%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s   | 1         | 0.66%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s   | 1         | 0.66%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 0.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s            | 1         | 0.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s            | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 1         | 0.66%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.66%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s  | 1         | 0.66%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s  | 1         | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s  | 1         | 0.66%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 533MT/s   | 1         | 0.66%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s  | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 42.61%  |
| DDR4    | 48        | 41.74%  |
| DDR2    | 9         | 7.83%   |
| LPDDR3  | 3         | 2.61%   |
| Unknown | 2         | 1.74%   |
| SDRAM   | 1         | 0.87%   |
| LPDDR4  | 1         | 0.87%   |
| DDR5    | 1         | 0.87%   |
| DDR     | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 96.52%  |
| Row Of Chips | 2         | 1.74%   |
| Chip         | 1         | 0.87%   |
| Unknown      | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 44        | 33.33%  |
| 8192  | 41        | 31.06%  |
| 2048  | 21        | 15.91%  |
| 16384 | 17        | 12.88%  |
| 1024  | 7         | 5.3%    |
| 32768 | 2         | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 23.48%  |
| 2400    | 18        | 13.64%  |
| 2667    | 17        | 12.88%  |
| 3200    | 14        | 10.61%  |
| 2133    | 10        | 7.58%   |
| 1333    | 9         | 6.82%   |
| 1067    | 6         | 4.55%   |
| 667     | 6         | 4.55%   |
| 1334    | 5         | 3.79%   |
| 1867    | 3         | 2.27%   |
| 533     | 3         | 2.27%   |
| Unknown | 3         | 2.27%   |
| 975     | 2         | 1.52%   |
| 800     | 2         | 1.52%   |
| 4800    | 1         | 0.76%   |
| 4267    | 1         | 0.76%   |
| 1066    | 1         | 0.76%   |

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
| Chicony Electronics           | 22        | 25.88%  |
| Microdia                      | 11        | 12.94%  |
| IMC Networks                  | 11        | 12.94%  |
| Suyin                         | 8         | 9.41%   |
| Realtek Semiconductor         | 8         | 9.41%   |
| Sunplus Innovation Technology | 6         | 7.06%   |
| Bison Electronics             | 5         | 5.88%   |
| Syntek                        | 2         | 2.35%   |
| Silicon Motion                | 2         | 2.35%   |
| Quanta                        | 2         | 2.35%   |
| Importek                      | 2         | 2.35%   |
| ALi                           | 2         | 2.35%   |
| Z-Star Microelectronics       | 1         | 1.18%   |
| Luxvisions Innotech Limited   | 1         | 1.18%   |
| Lite-On Technology            | 1         | 1.18%   |
| Lenovo                        | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 5         | 5.88%   |
| Microdia Integrated Webcam                | 4         | 4.71%   |
| IMC Networks Integrated Camera            | 3         | 3.53%   |
| Chicony HD WebCam                         | 3         | 3.53%   |
| Suyin 1.3M HD WebCam                      | 2         | 2.35%   |
| Sunplus Integrated_Webcam_HD              | 2         | 2.35%   |
| Silicon Motion Realtek DMFT RGB           | 2         | 2.35%   |
| Microdia Integrated_Webcam_HD             | 2         | 2.35%   |
| IMC Networks Realtek PC Camera            | 2         | 2.35%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 2         | 2.35%   |
| Chicony HP TrueVision HD Camera           | 2         | 2.35%   |
| ALi Gateway Webcam                        | 2         | 2.35%   |
| Z-Star Namuga 1.3M Webcam                 | 1         | 1.18%   |
| Syntek Lenovo EasyCamera                  | 1         | 1.18%   |
| Syntek EasyCamera                         | 1         | 1.18%   |
| Suyin USB 2.0 Camera                      | 1         | 1.18%   |
| Suyin Lenovo Integrated Webcam            | 1         | 1.18%   |
| Suyin Integrated Camera                   | 1         | 1.18%   |
| Suyin HP Webcam-101                       | 1         | 1.18%   |
| Suyin Asus Integrated Webcam              | 1         | 1.18%   |
| Suyin Acer Crystal Eye webcam             | 1         | 1.18%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 1         | 1.18%   |
| Sunplus Laptop Integrated Webcam HD       | 1         | 1.18%   |
| Sunplus Integrated Camera                 | 1         | 1.18%   |
| Sunplus Dell HD Webcam                    | 1         | 1.18%   |
| Realtek USB 2.0 Webcam                    | 1         | 1.18%   |
| Realtek PC Camera                         | 1         | 1.18%   |
| Realtek Lenovo EasyCamera                 | 1         | 1.18%   |
| Realtek Integrated_Webcam_HD              | 1         | 1.18%   |
| Realtek Integrated Webcam HD              | 1         | 1.18%   |
| Realtek Integrated Webcam                 | 1         | 1.18%   |
| Realtek Dell EasyCamera                   | 1         | 1.18%   |
| Realtek Acer 640 x 480 laptop camera      | 1         | 1.18%   |
| Quanta VGA WebCam                         | 1         | 1.18%   |
| Quanta HD Webcam                          | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_2M      | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_0.3M    | 1         | 1.18%   |
| Microdia Integrated Webcam HD             | 1         | 1.18%   |
| Microdia Dell Laptop Integrated Webcam HD | 1         | 1.18%   |
| Microdia Dell Integrated HD Webcam        | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 22.22%  |
| Synaptics                  | 4         | 22.22%  |
| Shenzhen Goodix Technology | 4         | 22.22%  |
| Elan Microelectronics      | 2         | 11.11%  |
| Upek                       | 1         | 5.56%   |
| LighTuning Technology      | 1         | 5.56%   |
| Broadcom                   | 1         | 5.56%   |
| AuthenTec                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 11.11%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 2         | 11.11%  |
| Elan Fingerprint Sensor                                                      | 2         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| AuthenTec AES1660                                                            | 1         | 5.56%   |

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
| 1     | 36        | 32.14%  |
| 2     | 33        | 29.46%  |
| 3     | 19        | 16.96%  |
| 0     | 16        | 14.29%  |
| 4     | 6         | 5.36%   |
| 6     | 1         | 0.89%   |
| 5     | 1         | 0.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 75        | 40.54%  |
| Net/wireless             | 43        | 23.24%  |
| Bluetooth                | 20        | 10.81%  |
| Fingerprint reader       | 18        | 9.73%   |
| Card reader              | 16        | 8.65%   |
| Firewire controller      | 10        | 5.41%   |
| Storage/nvme             | 1         | 0.54%   |
| Storage                  | 1         | 0.54%   |
| Net/ethernet             | 1         | 0.54%   |

