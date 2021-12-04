FreeBSD 13.0 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 83        | 95.4%   |
| i386  | 4         | 4.6%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 17        | 19.54%  |
| KDE5          | 16        | 18.39%  |
| Console       | 12        | 13.79%  |
| TWM           | 11        | 12.64%  |
| i3            | 8         | 9.2%    |
| GNOME         | 8         | 9.2%    |
| MATE          | 7         | 8.05%   |
| Openbox       | 2         | 2.3%    |
| Enlightenment | 2         | 2.3%    |
| LXQt          | 1         | 1.15%   |
| GNUstep       | 1         | 1.15%   |
| Cinnamon      | 1         | 1.15%   |
| AwesomeWM     | 1         | 1.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 75        | 86.21%  |
| Console | 11        | 12.64%  |
| Wayland | 1         | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 42        | 48.28%  |
| SDDM    | 20        | 22.99%  |
| GDM     | 9         | 10.34%  |
| SLiM    | 7         | 8.05%   |
| LightDM | 5         | 5.75%   |
| XDM     | 3         | 3.45%   |
| Ly      | 1         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| C               | 60        | 68.97%  |
| Unknown         | 9         | 10.34%  |
| en_US           | 8         | 9.2%    |
| nb_NO           | 2         | 2.3%    |
| fr_FR           | 2         | 2.3%    |
| uk_UA           | 1         | 1.15%   |
| ru_RU           | 1         | 1.15%   |
| pl_PL           | 1         | 1.15%   |
| ja_JP           | 1         | 1.15%   |
| it_IT.ISO8859-1 | 1         | 1.15%   |
| en_GB           | 1         | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 64        | 72.73%  |
| BIOS | 24        | 27.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 55        | 63.22%  |
| Ufs  | 32        | 36.78%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 79        | 90.8%   |
| MBR  | 8         | 9.2%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 31.03%  |
| Dell                | 24        | 27.59%  |
| Hewlett-Packard     | 8         | 9.2%    |
| ASUSTek Computer    | 6         | 6.9%    |
| Acer                | 5         | 5.75%   |
| Apple               | 3         | 3.45%   |
| Toshiba             | 2         | 2.3%    |
| System76            | 2         | 2.3%    |
| Samsung Electronics | 2         | 2.3%    |
| Notebook            | 2         | 2.3%    |
| MSI                 | 2         | 2.3%    |
| Pegatron            | 1         | 1.15%   |
| Google              | 1         | 1.15%   |
| Framework           | 1         | 1.15%   |
| Alienware           | 1         | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba TECRA M11                          | 1         | 1.15%   |
| Toshiba Satellite L50-C                    | 1         | 1.15%   |
| System76 Lemur Pro                         | 1         | 1.15%   |
| System76 Gazelle                           | 1         | 1.15%   |
| Samsung NC10                               | 1         | 1.15%   |
| Samsung 300E5M/300E5L                      | 1         | 1.15%   |
| Pegatron T12Ah                             | 1         | 1.15%   |
| Notebook NL5xRU                            | 1         | 1.15%   |
| Notebook N7x0WU                            | 1         | 1.15%   |
| MSI GS65 Stealth Thin 8RF                  | 1         | 1.15%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 1.15%   |
| Lenovo Z51-70 80K6                         | 1         | 1.15%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 1.15%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 1.15%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 1.15%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 1.15%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 1.15%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 1.15%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 1.15%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 1.15%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 1.15%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 1.15%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 1.15%   |
| Lenovo ThinkPad R60e 0658W2M               | 1         | 1.15%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 1.15%   |
| Lenovo ThinkPad Mini10 3507A31             | 1         | 1.15%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 1.15%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 1.15%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 1.15%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 1.15%   |
| Lenovo ThinkPad E14 20RAS0F600             | 1         | 1.15%   |
| Lenovo Rescuer-15ISK 80RQ                  | 1         | 1.15%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 1.15%   |
| Lenovo IdeaPad 320-15AST 80XV              | 1         | 1.15%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 1.15%   |
| Lenovo G580 26897SJ                        | 1         | 1.15%   |
| Lenovo G505 20240                          | 1         | 1.15%   |
| Lenovo G40-70 20369                        | 1         | 1.15%   |
| HP Pavilion Laptop 15-cc0xx                | 1         | 1.15%   |
| HP Mini 110-1000                           | 1         | 1.15%   |
| HP Laptop 17-by0xxx                        | 1         | 1.15%   |
| HP Laptop 15s-du1xxx                       | 1         | 1.15%   |
| HP ENVY x2 Detachable PC 13                | 1         | 1.15%   |
| HP EliteBook 840 G3                        | 1         | 1.15%   |
| HP Compaq Presario CQ71                    | 1         | 1.15%   |
| HP Compaq 6720s                            | 1         | 1.15%   |
| Google Terra                               | 1         | 1.15%   |
| Framework Laptop                           | 1         | 1.15%   |
| Dell XPS 15 9500                           | 1         | 1.15%   |
| Dell Vostro 5568                           | 1         | 1.15%   |
| Dell Vostro 5481                           | 1         | 1.15%   |
| Dell Precision 5520                        | 1         | 1.15%   |
| Dell Precision 5510                        | 1         | 1.15%   |
| Dell Latitude E7450                        | 1         | 1.15%   |
| Dell Latitude E6530                        | 1         | 1.15%   |
| Dell Latitude E6440                        | 1         | 1.15%   |
| Dell Latitude E6410                        | 1         | 1.15%   |
| Dell Latitude E5550                        | 1         | 1.15%   |
| Dell Latitude E5420                        | 1         | 1.15%   |
| Dell Latitude E4300                        | 1         | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 19        | 21.84%  |
| Dell Latitude        | 10        | 11.49%  |
| Dell Inspiron        | 9         | 10.34%  |
| Lenovo IdeaPad       | 3         | 3.45%   |
| Acer Aspire          | 3         | 3.45%   |
| HP Laptop            | 2         | 2.3%    |
| HP Compaq            | 2         | 2.3%    |
| Dell Vostro          | 2         | 2.3%    |
| Dell Precision       | 2         | 2.3%    |
| Toshiba TECRA        | 1         | 1.15%   |
| Toshiba Satellite    | 1         | 1.15%   |
| System76 Lemur       | 1         | 1.15%   |
| System76 Gazelle     | 1         | 1.15%   |
| Samsung NC10         | 1         | 1.15%   |
| Samsung 300E5M       | 1         | 1.15%   |
| Pegatron T12Ah       | 1         | 1.15%   |
| Notebook NL5xRU      | 1         | 1.15%   |
| Notebook N7x0WU      | 1         | 1.15%   |
| MSI GS65             | 1         | 1.15%   |
| MSI GL65             | 1         | 1.15%   |
| Lenovo Z51-70        | 1         | 1.15%   |
| Lenovo Rescuer-15ISK | 1         | 1.15%   |
| Lenovo G580          | 1         | 1.15%   |
| Lenovo G505          | 1         | 1.15%   |
| Lenovo G40-70        | 1         | 1.15%   |
| HP Pavilion          | 1         | 1.15%   |
| HP Mini              | 1         | 1.15%   |
| HP ENVY              | 1         | 1.15%   |
| HP EliteBook         | 1         | 1.15%   |
| Google Terra         | 1         | 1.15%   |
| Framework Laptop     | 1         | 1.15%   |
| Dell XPS             | 1         | 1.15%   |
| ASUS VX7SX           | 1         | 1.15%   |
| ASUS TP300LD         | 1         | 1.15%   |
| ASUS Q500A           | 1         | 1.15%   |
| ASUS G750JM          | 1         | 1.15%   |
| ASUS ASUS            | 1         | 1.15%   |
| ASUS 1015PX          | 1         | 1.15%   |
| Apple MacBookPro6    | 1         | 1.15%   |
| Apple MacBookPro5    | 1         | 1.15%   |
| Apple MacBookPro13   | 1         | 1.15%   |
| Alienware M15x       | 1         | 1.15%   |
| Acer Predator        | 1         | 1.15%   |
| Acer Nitro           | 1         | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 18        | 20.69%  |
| 2020 | 16        | 18.39%  |
| 2018 | 9         | 10.34%  |
| 2012 | 7         | 8.05%   |
| 2021 | 6         | 6.9%    |
| 2015 | 5         | 5.75%   |
| 2011 | 5         | 5.75%   |
| 2013 | 4         | 4.6%    |
| 2017 | 3         | 3.45%   |
| 2010 | 3         | 3.45%   |
| 2009 | 3         | 3.45%   |
| 2008 | 3         | 3.45%   |
| 2016 | 2         | 2.3%    |
| 2014 | 2         | 2.3%    |
| 2006 | 1         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 87        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 97.7%   |
| Yes  | 2         | 2.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 35        | 40.23%  |
| 16.01-24.0  | 22        | 25.29%  |
| 4.01-8.0    | 14        | 16.09%  |
| 32.01-64.0  | 4         | 4.6%    |
| 2.01-3.0    | 4         | 4.6%    |
| 3.01-4.0    | 2         | 2.3%    |
| 24.01-32.0  | 2         | 2.3%    |
| 64.01-256.0 | 2         | 2.3%    |
| 0.51-1.0    | 2         | 2.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 44        | 50.57%  |
| 0.51-1.0   | 30        | 34.48%  |
| 1.01-2.0   | 9         | 10.34%  |
| 16.01-24.0 | 2         | 2.3%    |
| 4.01-8.0   | 1         | 1.15%   |
| 2.01-3.0   | 1         | 1.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 77.01%  |
| 2      | 14        | 16.09%  |
| 3      | 4         | 4.6%    |
| 0      | 2         | 2.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 62.07%  |
| Yes       | 33        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 85.06%  |
| No        | 13        | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 70.11%  |
| No        | 26        | 29.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 21        | 24.14%  |
| UK          | 6         | 6.9%    |
| Brazil      | 5         | 5.75%   |
| Germany     | 4         | 4.6%    |
| Switzerland | 3         | 3.45%   |
| Russia      | 3         | 3.45%   |
| Mexico      | 3         | 3.45%   |
| Japan       | 3         | 3.45%   |
| India       | 3         | 3.45%   |
| France      | 3         | 3.45%   |
| Czechia     | 3         | 3.45%   |
| Australia   | 3         | 3.45%   |
| Ukraine     | 2         | 2.3%    |
| Iran        | 2         | 2.3%    |
| Thailand    | 1         | 1.15%   |
| Sweden      | 1         | 1.15%   |
| Spain       | 1         | 1.15%   |
| Qatar       | 1         | 1.15%   |
| Poland      | 1         | 1.15%   |
| Norway      | 1         | 1.15%   |
| New Zealand | 1         | 1.15%   |
| Netherlands | 1         | 1.15%   |
| Nepal       | 1         | 1.15%   |
| Namibia     | 1         | 1.15%   |
| Malaysia    | 1         | 1.15%   |
| Italy       | 1         | 1.15%   |
| Hungary     | 1         | 1.15%   |
| Guadeloupe  | 1         | 1.15%   |
| Finland     | 1         | 1.15%   |
| Colombia    | 1         | 1.15%   |
| China       | 1         | 1.15%   |
| Chile       | 1         | 1.15%   |
| Canada      | 1         | 1.15%   |
| Bulgaria    | 1         | 1.15%   |
| Austria     | 1         | 1.15%   |
| Argentina   | 1         | 1.15%   |
| Albania     | 1         | 1.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Tehran                 | 2         | 2.3%    |
| Zurich                 | 1         | 1.15%   |
| Yekaterinburg          | 1         | 1.15%   |
| Weimar                 | 1         | 1.15%   |
| Wausau                 | 1         | 1.15%   |
| Vadodara               | 1         | 1.15%   |
| Vacaville              | 1         | 1.15%   |
| Tyumen                 | 1         | 1.15%   |
| Tuklaty                | 1         | 1.15%   |
| Tatab??nya             | 1         | 1.15%   |
| São Paulo             | 1         | 1.15%   |
| São José dos Campos  | 1         | 1.15%   |
| Sydney                 | 1         | 1.15%   |
| Sundebru               | 1         | 1.15%   |
| Suginami-ku            | 1         | 1.15%   |
| South Yarra            | 1         | 1.15%   |
| Sofia                  | 1         | 1.15%   |
| Sarandë               | 1         | 1.15%   |
| San Vicent del Raspeig | 1         | 1.15%   |
| San Diego              | 1         | 1.15%   |
| San Antonio            | 1         | 1.15%   |
| Rugby                  | 1         | 1.15%   |
| Rochester              | 1         | 1.15%   |
| Rionegro               | 1         | 1.15%   |
| Rennes                 | 1         | 1.15%   |
| Prague                 | 1         | 1.15%   |
| Porto União           | 1         | 1.15%   |
| Phoenix                | 1         | 1.15%   |
| Otjiwarongo            | 1         | 1.15%   |
| Nunoa                  | 1         | 1.15%   |
| Niagara Falls          | 1         | 1.15%   |
| New Delhi              | 1         | 1.15%   |
| Montserrat             | 1         | 1.15%   |
| Monterrey              | 1         | 1.15%   |
| Minot                  | 1         | 1.15%   |
| Midvale                | 1         | 1.15%   |
| Melbourne              | 1         | 1.15%   |
| Lübeck                | 1         | 1.15%   |
| Lyon                   | 1         | 1.15%   |
| Linz                   | 1         | 1.15%   |
| Lexington              | 1         | 1.15%   |
| Leicester              | 1         | 1.15%   |
| Le Gosier              | 1         | 1.15%   |
| Kyiv                   | 1         | 1.15%   |
| Kolkata                | 1         | 1.15%   |
| Klobuck                | 1         | 1.15%   |
| Kathmandu              | 1         | 1.15%   |
| Kaiserslautern         | 1         | 1.15%   |
| Juiz de Fora           | 1         | 1.15%   |
| Jilin City             | 1         | 1.15%   |
| Hoerby                 | 1         | 1.15%   |
| Helsinki               | 1         | 1.15%   |
| Hat Yai                | 1         | 1.15%   |
| Harrison               | 1         | 1.15%   |
| Guadalajara            | 1         | 1.15%   |
| Gloucester             | 1         | 1.15%   |
| Glasgow                | 1         | 1.15%   |
| Gallatin               | 1         | 1.15%   |
| Gallarate              | 1         | 1.15%   |
| Fujinomiya             | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 17.65%  |
| Samsung Electronics | 17        | 21     | 16.67%  |
| Seagate             | 10        | 10     | 9.8%    |
| Kingston            | 10        | 11     | 9.8%    |
| Toshiba             | 9         | 9      | 8.82%   |
| Crucial             | 9         | 10     | 8.82%   |
| Hitachi             | 6         | 6      | 5.88%   |
| SanDisk             | 5         | 5      | 4.9%    |
| Fujitsu             | 3         | 4      | 2.94%   |
| SK Hynix            | 2         | 2      | 1.96%   |
| Intel               | 2         | 2      | 1.96%   |
| HGST                | 2         | 2      | 1.96%   |
| TCSUNBOW            | 1         | 1      | 0.98%   |
| SPCC                | 1         | 1      | 0.98%   |
| PNY                 | 1         | 1      | 0.98%   |
| Phison              | 1         | 1      | 0.98%   |
| OWC                 | 1         | 1      | 0.98%   |
| KingSpec            | 1         | 1      | 0.98%   |
| Gigabyte Technology | 1         | 1      | 0.98%   |
| Corsair             | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB         | 5         | 4.67%   |
| Toshiba MQ01ABD100 1TB               | 3         | 2.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 2.8%    |
| Samsung SSD 970 EVO 500GB            | 2         | 1.87%   |
| Kingston SA400S37240G 240GB          | 2         | 1.87%   |
| Kingston SA400S37120G 120GB          | 2         | 1.87%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.93%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.93%   |
| WDC WDS120G2G0B-00EPW0 120GB         | 1         | 0.93%   |
| WDC WDS100T2B0B-00YS70 1TB           | 1         | 0.93%   |
| WDC WD7500BPVT-80HXZT3 752GB         | 1         | 0.93%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.93%   |
| WDC WD5000BEVT-75A0RT0 500GB         | 1         | 0.93%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 0.93%   |
| WDC WD2500BEVS-08VAT2 250GB          | 1         | 0.93%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.93%   |
| WDC WD1600BEVT-11ZCT0 160GB          | 1         | 0.93%   |
| WDC WD10SPZX-75Z10T1 1TB             | 1         | 0.93%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.93%   |
| WDC WD10SDRW-34A0XS0 1TB             | 1         | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.93%   |
| WDC WD10JPLX-00MBPT1 1TB             | 1         | 0.93%   |
| WDC PC SN530 NVMe 512GB              | 1         | 0.93%   |
| WDC PC SN520 NVMe 256GB              | 1         | 0.93%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.93%   |
| Toshiba MQ01ABD100V 1TB              | 1         | 0.93%   |
| Toshiba MK5061GSY 500GB              | 1         | 0.93%   |
| Toshiba MK2546GSX 250GB              | 1         | 0.93%   |
| Toshiba KXG50ZNV256G NVMe 256GB      | 1         | 0.93%   |
| Toshiba KBG30ZMT512G 512GB           | 1         | 0.93%   |
| TCSUNBOW X3 480GB                    | 1         | 0.93%   |
| SPCC SPCCSolidStateDisk 256GB        | 1         | 0.93%   |
| SK Hynix SC308 SATA 256GB            | 1         | 0.93%   |
| SK Hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.93%   |
| Seagate ST9500420AS 500GB            | 1         | 0.93%   |
| Seagate ST500LX003-1AC15G 500GB      | 1         | 0.93%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 0.93%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.93%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 0.93%   |
| SanDisk SSD PLUS 120GB               | 1         | 0.93%   |
| SanDisk SDSSDP256G 256GB             | 1         | 0.93%   |
| SanDisk SDSSDH3 1T02 1TB             | 1         | 0.93%   |
| SanDisk SDSSDA120G 120GB             | 1         | 0.93%   |
| SanDisk SD9SN8W512G 512GB            | 1         | 0.93%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB | 1         | 0.93%   |
| Samsung SSD 970 PRO 1TB              | 1         | 0.93%   |
| Samsung SSD 970 EVO Plus 250GB       | 1         | 0.93%   |
| Samsung SSD 970 EVO Plus 1TB         | 1         | 0.93%   |
| Samsung SSD 860 EVO M.2 1TB          | 1         | 0.93%   |
| Samsung SSD 860 EVO 500GB            | 1         | 0.93%   |
| Samsung SSD 850 EVO 250GB            | 1         | 0.93%   |
| Samsung PM981a NVMe 512GB            | 1         | 0.93%   |
| Samsung MZVLW256HEHP-000L7 256GB     | 1         | 0.93%   |
| Samsung MZVLB512HBJQ-000H1 512GB     | 1         | 0.93%   |
| Samsung MZVLB256HBHQ-000L7 256GB     | 1         | 0.93%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 1         | 0.93%   |
| Samsung MZNTY256HDHP-000L2 256GB     | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 27.5%   |
| Seagate             | 10        | 10     | 25%     |
| Toshiba             | 7         | 7      | 17.5%   |
| Hitachi             | 6         | 6      | 15%     |
| Fujitsu             | 3         | 4      | 7.5%    |
| HGST                | 2         | 2      | 5%      |
| Samsung Electronics | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 10     | 21.95%  |
| Samsung Electronics | 7         | 7      | 17.07%  |
| Kingston            | 7         | 8      | 17.07%  |
| SanDisk             | 5         | 5      | 12.2%   |
| WDC                 | 3         | 3      | 7.32%   |
| Intel               | 2         | 2      | 4.88%   |
| TCSUNBOW            | 1         | 1      | 2.44%   |
| SPCC                | 1         | 1      | 2.44%   |
| SK Hynix            | 1         | 1      | 2.44%   |
| OWC                 | 1         | 1      | 2.44%   |
| KingSpec            | 1         | 1      | 2.44%   |
| Gigabyte Technology | 1         | 1      | 2.44%   |
| Corsair             | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 40        | 43     | 40%     |
| HDD  | 39        | 42     | 39%     |
| NVMe | 21        | 25     | 21%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 73        | 85     | 77.66%  |
| NVMe | 21        | 25     | 22.34%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 58     | 68.83%  |
| 0.51-1.0   | 22        | 25     | 28.57%  |
| 1.01-2.0   | 2         | 2      | 2.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 37        | 42.53%  |
| 251-500    | 26        | 29.89%  |
| 501-1000   | 12        | 13.79%  |
| 51-100     | 6         | 6.9%    |
| 1-20       | 3         | 3.45%   |
| 1001-2000  | 2         | 2.3%    |
| 21-50      | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 74        | 85.06%  |
| 21-50   | 6         | 6.9%    |
| 101-250 | 4         | 4.6%    |
| 51-100  | 3         | 3.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-80HXZT3 752GB                     | 1         | 1      | 9.09%   |
| WDC WD5000BEVT-75A0RT0 500GB                     | 1         | 1      | 9.09%   |
| WDC WD3200BPVT-75ZEST0 320GB                     | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 9.09%   |
| Seagate ST1000LM014-1EJ164 1TB                   | 1         | 1      | 9.09%   |
| Samsung Electronics SSD PM841 2.5-inch 7mm 256GB | 1         | 1      | 9.09%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 9.09%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 9.09%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 9.09%   |
| Hitachi HTS543225A7A384 250GB                    | 1         | 1      | 9.09%   |
| Hitachi HTS541612J9SA00 120GB                    | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 27.27%  |
| Hitachi             | 3         | 3      | 27.27%  |
| Seagate             | 2         | 2      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Intel               | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 33.33%  |
| Hitachi             | 3         | 3      | 33.33%  |
| Seagate             | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

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
| Works   | 76        | 99     | 87.36%  |
| Malfunc | 11        | 11     | 12.64%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 70        | 70%     |
| Samsung Electronics         | 10        | 10%     |
| AMD                         | 8         | 8%      |
| Sandisk                     | 3         | 3%      |
| Toshiba                     | 2         | 2%      |
| Phison Electronics          | 2         | 2%      |
| Kingston Technology Company | 2         | 2%      |
| SK Hynix                    | 1         | 1%      |
| Nvidia                      | 1         | 1%      |
| Apple                       | 1         | 1%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9         | 8.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 8.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 6.73%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 6.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 5.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 4.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 4.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.88%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.92%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.92%   |
| Toshiba unknown                                                                  | 1         | 0.96%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.96%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.96%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.96%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.96%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.96%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.96%   |
| Apple S3X NVMe Controller                                                        | 1         | 0.96%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1         | 0.96%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.96%   |
| Unknown                                                                          | 1         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 65        | 65%     |
| NVMe | 20        | 20%     |
| IDE  | 9         | 9%      |
| RAID | 6         | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 89.66%  |
| AMD    | 9         | 10.34%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz      | 4         | 4.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz      | 3         | 3.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz      | 3         | 3.45%   |
| Intel CPU Version                      | 2         | 2.3%    |
| Intel Core i7-9750H CPU @ 2.60GHz      | 2         | 2.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz      | 2         | 2.3%    |
| Intel Core i7-7500U CPU @ 2.70GHz      | 2         | 2.3%    |
| Intel Core i7-4510U CPU @ 2.00GHz      | 2         | 2.3%    |
| Intel Core i7-10750H CPU @ 2.60GHz     | 2         | 2.3%    |
| Intel Core i7-10510U CPU @ 1.80GHz     | 2         | 2.3%    |
| Intel Core i5-4300M CPU @ 2.60GHz      | 2         | 2.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz     | 2         | 2.3%    |
| Intel Core i3-4005U CPU @ 1.70GHz      | 2         | 2.3%    |
| Intel Processor 5Y70 CPU @ 1.10GHz     | 1         | 1.15%   |
| Intel Pentium M                        | 1         | 1.15%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz | 1         | 1.15%   |
| Intel Pentium CPU N3700 @ 1.60GHz      | 1         | 1.15%   |
| Intel Genuine CPU                      | 1         | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz      | 1         | 1.15%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz     | 1         | 1.15%   |
| Intel Core i7-6600U CPU @ 2.60GHz      | 1         | 1.15%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz     | 1         | 1.15%   |
| Intel Core i7-3632QM CPU @ 2.20GHz     | 1         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz     | 1         | 1.15%   |
| Intel Core i7-2670QM CPU @ 2.20GHz     | 1         | 1.15%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz     | 1         | 1.15%   |
| Intel Core i7 CPU M 620 @ 2.67GHz      | 1         | 1.15%   |
| Intel Core i5-9300H CPU @ 2.40GHz      | 1         | 1.15%   |
| Intel Core i5-8365U CPU @ 1.60GHz      | 1         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz      | 1         | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 1         | 1.15%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 1         | 1.15%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz     | 1         | 1.15%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz     | 1         | 1.15%   |
| Intel Core i5-6287U CPU @ 3.10GHz      | 1         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 1         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 1.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 1         | 1.15%   |
| Intel Core i5-2540M CPU @ 2.60GHz      | 1         | 1.15%   |
| Intel Core i5-2450M CPU @ 2.50GHz      | 1         | 1.15%   |
| Intel Core i5-2430M CPU @ 2.40GH       | 1         | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz      | 1         | 1.15%   |
| Intel Core i5-10310U CPU @ 1.70GHz     | 1         | 1.15%   |
| Intel Core i5 CPU M 560 @ 2.67GHz      | 1         | 1.15%   |
| Intel Core i5 CPU M 560 @ 2.67GH       | 1         | 1.15%   |
| Intel Core i3-8130U CPU @ 2.20GHz      | 1         | 1.15%   |
| Intel Core i3-6006U CPU @ 2.00GHz      | 1         | 1.15%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 1         | 1.15%   |
| Intel Core i3-3227U CPU @ 1.90GHz      | 1         | 1.15%   |
| Intel Core i3-2330M CPU @ 2.20GHz      | 1         | 1.15%   |
| Intel Core i3 CPU M 380 @ 2.53GH       | 1         | 1.15%   |
| Intel Core i3 CPU M 330 @ 2.13GHz      | 1         | 1.15%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz   | 1         | 1.15%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz   | 1         | 1.15%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 1         | 1.15%   |
| Intel Core 2 Duo                       | 1         | 1.15%   |
| Intel Celeron M CPU                    | 1         | 1.15%   |
| Intel Celeron CPU N3160 @ 1.60GHz      | 1         | 1.15%   |
| Intel Atom CPU N570 @ 1.66GHz          | 1         | 1.15%   |
| Intel Atom CPU N270 @ 1.60GHz          | 1         | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 32        | 36.78%  |
| Intel Core i7      | 21        | 24.14%  |
| Intel Core i3      | 9         | 10.34%  |
| Other              | 5         | 5.75%   |
| Intel Core 2 Duo   | 4         | 4.6%    |
| AMD Ryzen 7        | 3         | 3.45%   |
| Intel Atom         | 2         | 2.3%    |
| AMD A4             | 2         | 2.3%    |
| Intel Pentium M    | 1         | 1.15%   |
| Intel Pentium Dual | 1         | 1.15%   |
| Intel Pentium      | 1         | 1.15%   |
| Intel Genuine      | 1         | 1.15%   |
| Intel Celeron M    | 1         | 1.15%   |
| Intel Celeron      | 1         | 1.15%   |
| AMD Ryzen 5        | 1         | 1.15%   |
| AMD Ryzen 3        | 1         | 1.15%   |
| AMD A12            | 1         | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 44        | 50.57%  |
| 4       | 26        | 29.89%  |
| 6       | 5         | 5.75%   |
| Unknown | 5         | 5.75%   |
| 1       | 3         | 3.45%   |
| 16      | 2         | 2.3%    |
| 12      | 1         | 1.15%   |
| 8       | 1         | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 98.85%  |
| 2      | 1         | 1.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 66        | 75.86%  |
| 1       | 15        | 17.24%  |
| Unknown | 6         | 6.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 23        | 26.44%  |
| SandyBridge | 9         | 10.34%  |
| Haswell     | 7         | 8.05%   |
| Broadwell   | 6         | 6.9%    |
| Westmere    | 5         | 5.75%   |
| Skylake     | 5         | 5.75%   |
| IvyBridge   | 5         | 5.75%   |
| Penryn      | 4         | 4.6%    |
| Bonnell     | 4         | 4.6%    |
| Zen 2       | 2         | 2.3%    |
| Silvermont  | 2         | 2.3%    |
| Excavator   | 2         | 2.3%    |
| Core        | 2         | 2.3%    |
| CometLake   | 2         | 2.3%    |
| Zen+        | 1         | 1.15%   |
| Zen         | 1         | 1.15%   |
| TigerLake   | 1         | 1.15%   |
| P6          | 1         | 1.15%   |
| Nehalem     | 1         | 1.15%   |
| K10 Llano   | 1         | 1.15%   |
| Jaguar      | 1         | 1.15%   |
| IceLake     | 1         | 1.15%   |
| Unknown     | 1         | 1.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 67.59%  |
| Nvidia | 23        | 21.3%   |
| AMD    | 12        | 11.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.02%   |
| Intel HD Graphics 620                                                                    | 7         | 6.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 5.26%   |
| Intel HD Graphics 5500                                                                   | 5         | 4.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 4.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 3.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 3.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.75%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.75%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.75%   |
| Intel HD Graphics 530                                                                    | 2         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.75%   |
| AMD Renoir                                                                               | 2         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.88%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.88%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.88%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.88%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.88%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.88%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.88%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.88%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.88%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 1         | 0.88%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.88%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.88%   |
| Nvidia G98M [GeForce G 103M]                                                             | 1         | 0.88%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.88%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.88%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 0.88%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.88%   |
| Intel Iris Graphics 550                                                                  | 1         | 0.88%   |
| Intel HD Graphics 630                                                                    | 1         | 0.88%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.88%   |
| AMD Venus XTX [Radeon HD 8890M / R9 M275X/M375X]                                         | 1         | 0.88%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 0.88%   |
| AMD SuperSumo [Radeon HD 6480G]                                                          | 1         | 0.88%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 1         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.88%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 1         | 0.88%   |
| AMD Lucienne                                                                             | 1         | 0.88%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 0.88%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 50.57%  |
| Intel + Nvidia | 17        | 19.54%  |
| 2 x Intel      | 9         | 10.34%  |
| 1 x AMD        | 8         | 9.2%    |
| 1 x Nvidia     | 4         | 4.6%    |
| Intel + AMD    | 2         | 2.3%    |
| 2 x Nvidia     | 1         | 1.15%   |
| 2 x AMD        | 1         | 1.15%   |
| AMD + Nvidia   | 1         | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 76        | 87.36%  |
| Proprietary | 10        | 11.49%  |
| Unknown     | 1         | 1.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 89.66%  |
| 0.01-0.5   | 5         | 5.75%   |
| 5.01-6.0   | 1         | 1.15%   |
| 3.01-4.0   | 1         | 1.15%   |
| 2.01-3.0   | 1         | 1.15%   |
| 0.51-1.0   | 1         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 16        | 22.54%  |
| BOE                  | 13        | 18.31%  |
| LG Display           | 12        | 16.9%   |
| Chimei Innolux       | 6         | 8.45%   |
| Samsung Electronics  | 5         | 7.04%   |
| Sharp                | 4         | 5.63%   |
| Lenovo               | 3         | 4.23%   |
| InfoVision           | 2         | 2.82%   |
| AOC                  | 2         | 2.82%   |
| Toshiba              | 1         | 1.41%   |
| Sceptre Tech         | 1         | 1.41%   |
| Hewlett-Packard      | 1         | 1.41%   |
| HannStar             | 1         | 1.41%   |
| Goldstar             | 1         | 1.41%   |
| CPT                  | 1         | 1.41%   |
| Ancor Communications | 1         | 1.41%   |
| AGO                  | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 2.82%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 2.82%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1         | 1.41%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 1.41%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 1.41%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 1.41%   |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 1.41%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 1.41%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1210x680mm 54.6-inch | 1         | 1.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 1.41%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 1.41%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 1.41%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 1.41%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 1.41%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 1.41%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch                | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 1.41%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 1.41%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch            | 1         | 1.41%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 1.41%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 1.41%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x130mm 10.1-inch               | 1         | 1.41%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 1.41%   |
| CPT LCD Monitor CPT04C4 1024x600 230x140mm 10.6-inch                   | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch        | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 340x190mm 15.3-inch       | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch       | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch       | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1372 1920x1080 290x170mm 13.2-inch       | 1         | 1.41%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch       | 1         | 1.41%   |
| BOE LCD Monitor BOE0806 1920x1080 310x170mm 13.9-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE07BD 1920x1080 310x170mm 13.9-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE07A3 1920x1080 340x190mm 15.3-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE0729 1920x1080 340x190mm 15.3-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE06E2 1920x1080 310x170mm 13.9-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE06CB 1920x1080 340x190mm 15.3-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE06A4 1366x768 340x190mm 15.3-inch                   | 1         | 1.41%   |
| BOE LCD Monitor BOE069B 1600x900 380x210mm 17.1-inch                   | 1         | 1.41%   |
| BOE LCD Monitor BOE0690 1920x1080 340x190mm 15.3-inch                  | 1         | 1.41%   |
| BOE LCD Monitor BOE0620 1366x768 340x190mm 15.3-inch                   | 1         | 1.41%   |
| BOE LCD Monitor BOE05F0 1366x768 310x170mm 13.9-inch                   | 1         | 1.41%   |
| BOE LCD Monitor BOE05BC 1366x768 340x190mm 15.3-inch                   | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch          | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO5544 1280x800 300x190mm 14.0-inch          | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO5024 1280x800 290x180mm 13.4-inch          | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO423D 1920x1080 310x170mm 13.9-inch         | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch          | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch          | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 380x210mm 17.1-inch         | 1         | 1.41%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 1         | 1.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 29        | 42.65%  |
| 1366x768 (WXGA)   | 19        | 27.94%  |
| 3840x2160 (4K)    | 4         | 5.88%   |
| 1600x900 (HD+)    | 4         | 5.88%   |
| 1280x800 (WXGA)   | 4         | 5.88%   |
| 2560x1080         | 2         | 2.94%   |
| 1024x600          | 2         | 2.94%   |
| 1920x540          | 1         | 1.47%   |
| 1920x1200 (WUXGA) | 1         | 1.47%   |
| 1280x720 (HD)     | 1         | 1.47%   |
| 1024x768 (XGA)    | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 30        | 42.86%  |
| 13      | 16        | 22.86%  |
| 12      | 5         | 7.14%   |
| 14      | 4         | 5.71%   |
| 17      | 3         | 4.29%   |
| 10      | 3         | 4.29%   |
| 27      | 2         | 2.86%   |
| 54      | 1         | 1.43%   |
| 49      | 1         | 1.43%   |
| 34      | 1         | 1.43%   |
| 31      | 1         | 1.43%   |
| 29      | 1         | 1.43%   |
| 24      | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 60%     |
| 201-300     | 16        | 22.86%  |
| 501-600     | 3         | 4.29%   |
| 351-400     | 3         | 4.29%   |
| 601-700     | 2         | 2.86%   |
| 1001-1500   | 2         | 2.86%   |
| 701-800     | 1         | 1.43%   |
| Unknown     | 1         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 53        | 82.81%  |
| 16/10   | 6         | 9.38%   |
| 4/3     | 2         | 3.13%   |
| 21/9    | 2         | 3.13%   |
| Unknown | 1         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 25        | 35.71%  |
| 81-90          | 15        | 21.43%  |
| 101-110        | 6         | 8.57%   |
| 61-70          | 5         | 7.14%   |
| 71-80          | 3         | 4.29%   |
| 41-50          | 3         | 4.29%   |
| 301-350        | 3         | 4.29%   |
| 121-130        | 3         | 4.29%   |
| More than 1000 | 2         | 2.86%   |
| 351-500        | 2         | 2.86%   |
| 201-250        | 1         | 1.43%   |
| 111-120        | 1         | 1.43%   |
| Unknown        | 1         | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 44.29%  |
| 101-120       | 22        | 31.43%  |
| 51-100        | 9         | 12.86%  |
| More than 240 | 3         | 4.29%   |
| 161-240       | 3         | 4.29%   |
| 1-50          | 1         | 1.43%   |
| Unknown       | 1         | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 64.37%  |
| 0     | 23        | 26.44%  |
| 2     | 7         | 8.05%   |
| 3     | 1         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 52        | 36.36%  |
| Realtek Semiconductor    | 42        | 29.37%  |
| Qualcomm Atheros         | 24        | 16.78%  |
| Broadcom                 | 15        | 10.49%  |
| Ralink Technology        | 2         | 1.4%    |
| Edimax Technology        | 2         | 1.4%    |
| Xiaomi                   | 1         | 0.7%    |
| Samsung Electronics      | 1         | 0.7%    |
| Nvidia                   | 1         | 0.7%    |
| NetGear                  | 1         | 0.7%    |
| Marvell Technology Group | 1         | 0.7%    |
| dog hunter               | 1         | 0.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 28        | 15.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 5.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.84%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.84%   |
| Intel Wireless 7265                                                     | 5         | 2.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 2.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.7%    |
| Intel Wireless-AC 9260                                                  | 3         | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 1.14%   |
| Intel Wireless 8260                                                     | 2         | 1.14%   |
| Intel Wireless 7260                                                     | 2         | 1.14%   |
| Intel Wireless 3165                                                     | 2         | 1.14%   |
| Intel Wireless 3160                                                     | 2         | 1.14%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.14%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                    | 2         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 1.14%   |
| Intel 82577LC Gigabit Network Connection                                | 2         | 1.14%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.14%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.57%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.57%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 1         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.57%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.57%   |
| Nvidia MCP79 Ethernet                                                   | 1         | 0.57%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 1         | 0.57%   |
| Intel WiFi Link 5100                                                    | 1         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.57%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                       | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                    | 1         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 50.52%  |
| Qualcomm Atheros      | 18        | 18.56%  |
| Broadcom              | 13        | 13.4%   |
| Realtek Semiconductor | 12        | 12.37%  |
| Ralink Technology     | 2         | 2.06%   |
| Edimax Technology     | 2         | 2.06%   |
| NetGear               | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 5.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 5.1%    |
| Intel Wireless 8265 / 8275                                              | 5         | 5.1%    |
| Intel Wireless 7265                                                     | 5         | 5.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 5.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 3.06%   |
| Intel Wireless-AC 9260                                                  | 3         | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 3.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 3.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 2.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 2.04%   |
| Intel Wireless 8260                                                     | 2         | 2.04%   |
| Intel Wireless 7260                                                     | 2         | 2.04%   |
| Intel Wireless 3165                                                     | 2         | 2.04%   |
| Intel Wireless 3160                                                     | 2         | 2.04%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 2.04%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 2.04%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 2.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.02%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.02%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.02%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 1.02%   |
| Intel WiFi Link 5100                                                    | 1         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 1.02%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.02%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.02%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 1.02%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 1.02%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 1.02%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.02%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 1.02%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 37        | 48.05%  |
| Intel                    | 22        | 28.57%  |
| Qualcomm Atheros         | 9         | 11.69%  |
| Broadcom                 | 5         | 6.49%   |
| Xiaomi                   | 1         | 1.3%    |
| Samsung Electronics      | 1         | 1.3%    |
| Nvidia                   | 1         | 1.3%    |
| Marvell Technology Group | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 36.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 11.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 6.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 2.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.6%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.6%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.6%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.6%    |
| Intel 82577LC Gigabit Network Connection                          | 2         | 2.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.3%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.3%    |
| Intel 82562GT 10/100 Network Connection                           | 1         | 1.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.3%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 1.3%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 1.3%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 53.66%  |
| Ethernet | 75        | 45.73%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 52.31%  |
| WiFi     | 62        | 47.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 83.91%  |
| 1     | 14        | 16.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 87.36%  |
| Yes  | 11        | 12.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 53.33%  |
| Qualcomm Atheros Communications | 9         | 15%     |
| Realtek Semiconductor           | 5         | 8.33%   |
| Broadcom                        | 4         | 6.67%   |
| IMC Networks                    | 2         | 3.33%   |
| ASUSTek Computer                | 2         | 3.33%   |
| Apple                           | 2         | 3.33%   |
| Lite-On Technology              | 1         | 1.67%   |
| Hewlett-Packard                 | 1         | 1.67%   |
| Foxconn / Hon Hai               | 1         | 1.67%   |
| Dell                            | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 15        | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 6.67%   |
| Intel AX201 Bluetooth                                       | 4         | 6.67%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 3         | 5%      |
| Realtek  Bluetooth Adapter                                  | 2         | 3.33%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 3.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 3.33%   |
| Intel AX200 Bluetooth                                       | 2         | 3.33%   |
| Apple Bluetooth Host Controller                             | 2         | 3.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.67%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.67%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.67%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.67%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.67%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.67%   |
| Intel AX210 Bluetooth                                       | 1         | 1.67%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.67%   |
| IMC Networks Bluetooth Module                               | 1         | 1.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.67%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.67%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.67%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.67%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.67%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.67%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 77        | 77%     |
| Nvidia                | 11        | 11%     |
| AMD                   | 10        | 10%     |
| Realtek Semiconductor | 1         | 1%      |
| Lenovo                | 1         | 1%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 9.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 7.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.92%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 4.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 4.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 3.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 3.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 3.28%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.28%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 4         | 3.28%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.46%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.64%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                 | 1         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.82%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.82%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.82%   |
| Lenovo Lenovo ThinkPad OneLink Pro Dock                                                           | 1         | 0.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.82%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.82%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 1         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.82%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.82%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.82%   |
| Unknown                                                                                           | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 26.67%  |
| SK Hynix            | 26        | 24.76%  |
| Kingston            | 13        | 12.38%  |
| Crucial             | 8         | 7.62%   |
| Micron Technology   | 7         | 6.67%   |
| Unknown             | 6         | 5.71%   |
| Ramaxel Technology  | 5         | 4.76%   |
| Smart               | 2         | 1.9%    |
| A-DATA Technology   | 2         | 1.9%    |
| Transcend           | 1         | 0.95%   |
| Teikon              | 1         | 0.95%   |
| Qimonda             | 1         | 0.95%   |
| PUSKILL             | 1         | 0.95%   |
| Neo Forza           | 1         | 0.95%   |
| Elpida              | 1         | 0.95%   |
| Corsair             | 1         | 0.95%   |
| Unknown             | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 4         | 3.6%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.7%    |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s    | 3         | 2.7%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.8%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 1.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.8%    |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                    | 1         | 0.9%    |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 0.9%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s               | 1         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2                        | 1         | 0.9%    |
| Unknown RAM Module 2GB SODIMM 667MT/s                     | 1         | 0.9%    |
| Unknown RAM Module 1GB SODIMM DDR2                        | 1         | 0.9%    |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s       | 1         | 0.9%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s    | 1         | 0.9%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s     | 1         | 0.9%    |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s     | 1         | 0.9%    |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s      | 1         | 0.9%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 0.9%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s              | 1         | 0.9%    |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s      | 1         | 0.9%    |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.9%    |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.9%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 0.9%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 1         | 0.9%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s               | 1         | 0.9%    |
| Samsung RAM Module 2GB SODIMM 667MT/s                     | 1         | 0.9%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s     | 1         | 0.9%    |
| Samsung RAM M471B5673DZ1-CF8 2GB SODIMM DDR3 1066MT/s     | 1         | 0.9%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 1         | 0.9%    |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s     | 1         | 0.9%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 1         | 0.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s     | 1         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 0.9%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 0.9%    |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 1866MT/s     | 1         | 0.9%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s    | 1         | 0.9%    |
| Samsung RAM M471A2K43EB1-CTD 16GB SODIMM DDR4 2667MT/s    | 1         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s     | 1         | 0.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s     | 1         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 0.9%    |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1600MT/s           | 1         | 0.9%    |
| Samsung RAM K4E6E304ED 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s      | 1         | 0.9%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s   | 1         | 0.9%    |
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s   | 1         | 0.9%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 1         | 0.9%    |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2133MT/s  | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 38        | 42.7%   |
| DDR3    | 38        | 42.7%   |
| DDR2    | 6         | 6.74%   |
| LPDDR3  | 3         | 3.37%   |
| Unknown | 2         | 2.25%   |
| SDRAM   | 1         | 1.12%   |
| DDR     | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 97.73%  |
| Row Of Chips | 1         | 1.14%   |
| Unknown      | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 36        | 36.73%  |
| 4096  | 32        | 32.65%  |
| 2048  | 15        | 15.31%  |
| 16384 | 9         | 9.18%   |
| 1024  | 4         | 4.08%   |
| 32768 | 2         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 26.8%   |
| 2667    | 17        | 17.53%  |
| 2400    | 11        | 11.34%  |
| 2133    | 9         | 9.28%   |
| 1333    | 8         | 8.25%   |
| 3200    | 6         | 6.19%   |
| 1067    | 5         | 5.15%   |
| 667     | 4         | 4.12%   |
| 1334    | 3         | 3.09%   |
| 975     | 2         | 2.06%   |
| Unknown | 2         | 2.06%   |
| 1866    | 1         | 1.03%   |
| 1066    | 1         | 1.03%   |
| 800     | 1         | 1.03%   |
| 533     | 1         | 1.03%   |

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
| Chicony Electronics           | 17        | 26.98%  |
| IMC Networks                  | 9         | 14.29%  |
| Realtek Semiconductor         | 7         | 11.11%  |
| Microdia                      | 7         | 11.11%  |
| Suyin                         | 6         | 9.52%   |
| Sunplus Innovation Technology | 6         | 9.52%   |
| Acer                          | 3         | 4.76%   |
| Syntek                        | 2         | 3.17%   |
| Z-Star Microelectronics       | 1         | 1.59%   |
| Silicon Motion                | 1         | 1.59%   |
| Quanta                        | 1         | 1.59%   |
| Luxvisions Innotech Limited   | 1         | 1.59%   |
| Lenovo                        | 1         | 1.59%   |
| Importek                      | 1         | 1.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 4         | 6.35%   |
| IMC Networks Integrated Camera                      | 3         | 4.76%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 3.17%   |
| Realtek Integrated_Webcam_HD                        | 2         | 3.17%   |
| Microdia Integrated Webcam                          | 2         | 3.17%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 3.17%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 2         | 3.17%   |
| Chicony HD WebCam                                   | 2         | 3.17%   |
| Chicony Chicony USB2.0 Camera                       | 2         | 3.17%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 1.59%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.59%   |
| Syntek EasyCamera                                   | 1         | 1.59%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 1.59%   |
| Suyin Integrated Camera                             | 1         | 1.59%   |
| Suyin HP Webcam-101                                 | 1         | 1.59%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.59%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.59%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.59%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.59%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.59%   |
| Sunplus Integrated Camera                           | 1         | 1.59%   |
| Sunplus Dell HD Webcam                              | 1         | 1.59%   |
| Silicon Motion Web Camera                           | 1         | 1.59%   |
| Realtek USB 2 Webcam                                | 1         | 1.59%   |
| Realtek Realtek PC Camera                           | 1         | 1.59%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.59%   |
| Realtek Integrated Webcam HD                        | 1         | 1.59%   |
| Realtek Integrated Webcam                           | 1         | 1.59%   |
| Quanta HD Webcam                                    | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.59%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.59%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.59%   |
| Microdia Integrated Webcam HD                       | 1         | 1.59%   |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.59%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.59%   |
| Importek Webcam-101                                 | 1         | 1.59%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.59%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.59%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.59%   |
| IMC Networks EasyCamera                             | 1         | 1.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.59%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.59%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.59%   |
| Chicony HP Universal Camera                         | 1         | 1.59%   |
| Chicony HP TrueVision HD Camera                     | 1         | 1.59%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 1.59%   |
| Acer Lenovo Integrated Webcam                       | 1         | 1.59%   |
| Acer Lenovo EasyCamera                              | 1         | 1.59%   |
| Acer Integrated Camera                              | 1         | 1.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 27.27%  |
| Shenzhen Goodix Technology | 3         | 27.27%  |
| Validity Sensors           | 2         | 18.18%  |
| Upek                       | 1         | 9.09%   |
| Broadcom                   | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 9.09%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 9.09%   |
| Shenzhen Goodix FingerPrint                                                  | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 9.09%   |

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
| 1     | 32        | 36.78%  |
| 2     | 24        | 27.59%  |
| 3     | 16        | 18.39%  |
| 0     | 9         | 10.34%  |
| 4     | 5         | 5.75%   |
| 6     | 1         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 61        | 40.94%  |
| Net/wireless             | 34        | 22.82%  |
| Bluetooth                | 18        | 12.08%  |
| Card reader              | 13        | 8.72%   |
| Fingerprint reader       | 11        | 7.38%   |
| Firewire controller      | 9         | 6.04%   |
| Storage/nvme             | 1         | 0.67%   |
| Storage                  | 1         | 0.67%   |
| Net/ethernet             | 1         | 0.67%   |

