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

Total: 836

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T450 20BU000GUS    | [e1d99a4966](https://bsd-hardware.info/?probe=e1d99a4966) | Feb 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [5306df5921](https://bsd-hardware.info/?probe=5306df5921) | Feb 12, 2024 |
| Dell          | Latitude 7490               | [32828d5d84](https://bsd-hardware.info/?probe=32828d5d84) | Feb 10, 2024 |
| Panasonic     | CF-52VDA131M                | [1ebdac9598](https://bsd-hardware.info/?probe=1ebdac9598) | Feb 07, 2024 |
| Dell          | XPS 15 9530                 | [f9481e59b6](https://bsd-hardware.info/?probe=f9481e59b6) | Feb 01, 2024 |
| Panasonic     | CFSX4-1                     | [d998c9373a](https://bsd-hardware.info/?probe=d998c9373a) | Jan 25, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [fcc009f8ba](https://bsd-hardware.info/?probe=fcc009f8ba) | Jan 15, 2024 |
| Dell          | Latitude 7490               | [e2c44b78da](https://bsd-hardware.info/?probe=e2c44b78da) | Jan 14, 2024 |
| Dell          | Latitude 7490               | [ed2a38e9f5](https://bsd-hardware.info/?probe=ed2a38e9f5) | Jan 13, 2024 |
| Dell          | Latitude E5420              | [eabdd44efe](https://bsd-hardware.info/?probe=eabdd44efe) | Jan 13, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [79707e220e](https://bsd-hardware.info/?probe=79707e220e) | Jan 11, 2024 |
| Dell          | Inspiron 14-3452            | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| Dell          | Inspiron 5555               | [1449593b79](https://bsd-hardware.info/?probe=1449593b79) | Jan 07, 2024 |
| Dell          | XPS 15 9530                 | [13f09671ce](https://bsd-hardware.info/?probe=13f09671ce) | Jan 07, 2024 |
| ASUSTek       | X551MA                      | [63dc88d57d](https://bsd-hardware.info/?probe=63dc88d57d) | Jan 06, 2024 |
| ASUSTek       | X551MA                      | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| HP            | Laptop 15t-dy100            | [61130d2b74](https://bsd-hardware.info/?probe=61130d2b74) | Jan 03, 2024 |
| Lenovo        | ThinkPad T490s 20NX000MU... | [1271688c43](https://bsd-hardware.info/?probe=1271688c43) | Jan 02, 2024 |
| Panasonic     | CFSX4-1                     | [e54393775b](https://bsd-hardware.info/?probe=e54393775b) | Dec 29, 2023 |
| Deciso        | Netboard A20                | [c545672f6f](https://bsd-hardware.info/?probe=c545672f6f) | Dec 28, 2023 |
| Apple         | MacBookAir6,2               | [47fdb04811](https://bsd-hardware.info/?probe=47fdb04811) | Dec 25, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [278ab700ae](https://bsd-hardware.info/?probe=278ab700ae) | Dec 24, 2023 |
| Dell          | Latitude E7240              | [f2229124bf](https://bsd-hardware.info/?probe=f2229124bf) | Dec 22, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Apple         | PowerBook3,5                | [53313e58d8](https://bsd-hardware.info/?probe=53313e58d8) | Dec 20, 2023 |
| Dell          | Latitude E7240              | [7d5e8bcb8a](https://bsd-hardware.info/?probe=7d5e8bcb8a) | Dec 19, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YV... | [10fb96c00d](https://bsd-hardware.info/?probe=10fb96c00d) | Dec 18, 2023 |
| Lenovo        | ThinkPad P1 20MD002MUS      | [c0dcfec41d](https://bsd-hardware.info/?probe=c0dcfec41d) | Dec 16, 2023 |
| Google        | Lindar rev3                 | [2e748fc42c](https://bsd-hardware.info/?probe=2e748fc42c) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [a7fcca51be](https://bsd-hardware.info/?probe=a7fcca51be) | Dec 13, 2023 |
| Dell          | Inspiron 5559               | [09f5b25e72](https://bsd-hardware.info/?probe=09f5b25e72) | Dec 12, 2023 |
| Deciso        | NetBoard-A20                | [06e5f53429](https://bsd-hardware.info/?probe=06e5f53429) | Dec 10, 2023 |
| Google        | Parrot                      | [c10a95cbcc](https://bsd-hardware.info/?probe=c10a95cbcc) | Dec 10, 2023 |
| Google        | Parrot                      | [3a69ea2682](https://bsd-hardware.info/?probe=3a69ea2682) | Dec 10, 2023 |
| Sony          | VJS122C11L                  | [7d100c8e2c](https://bsd-hardware.info/?probe=7d100c8e2c) | Dec 06, 2023 |
| Dell          | Inspiron 7558               | [b34a8742d5](https://bsd-hardware.info/?probe=b34a8742d5) | Nov 26, 2023 |
| Dell          | Latitude E5540              | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| Dell          | Inspiron 7558               | [aad8d359f3](https://bsd-hardware.info/?probe=aad8d359f3) | Nov 24, 2023 |
| Google        | Dragonair                   | [713cf1bc38](https://bsd-hardware.info/?probe=713cf1bc38) | Nov 24, 2023 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| Dell          | Latitude E5440              | [629fba28cc](https://bsd-hardware.info/?probe=629fba28cc) | Nov 23, 2023 |
| Acer          | JM11-MS                     | [0490895189](https://bsd-hardware.info/?probe=0490895189) | Nov 23, 2023 |
| Dell          | XPS 13 9360                 | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| HP            | Notebook                    | [c583c221c7](https://bsd-hardware.info/?probe=c583c221c7) | Nov 17, 2023 |
| HP            | Notebook                    | [5d2df329aa](https://bsd-hardware.info/?probe=5d2df329aa) | Nov 17, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| Dell          | G5 5505                     | [088aea32c0](https://bsd-hardware.info/?probe=088aea32c0) | Nov 15, 2023 |
| Panasonic     | CFSX4-1                     | [f0f418db58](https://bsd-hardware.info/?probe=f0f418db58) | Nov 11, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP00    | [5eb914094b](https://bsd-hardware.info/?probe=5eb914094b) | Nov 09, 2023 |
| Gateway       | NV79                        | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Lenovo        | ThinkPad T480 20L5000WUS    | [4dcf84c76c](https://bsd-hardware.info/?probe=4dcf84c76c) | Oct 31, 2023 |
| Panasonic     | CFSX4-1                     | [32b7f19d78](https://bsd-hardware.info/?probe=32b7f19d78) | Oct 30, 2023 |
| Panasonic     | CFSX4-1                     | [522298f90a](https://bsd-hardware.info/?probe=522298f90a) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| IBM           | ThinkPad R51 2889W11        | [26d2e55032](https://bsd-hardware.info/?probe=26d2e55032) | Oct 28, 2023 |
| Lenovo        | ThinkPad T490 20N3X50500    | [364c7828be](https://bsd-hardware.info/?probe=364c7828be) | Oct 24, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [e4b35a3ff6](https://bsd-hardware.info/?probe=e4b35a3ff6) | Oct 21, 2023 |
| Dell          | Latitude 5490               | [eeab525ffd](https://bsd-hardware.info/?probe=eeab525ffd) | Oct 20, 2023 |
| Panasonic     | CFSX4-1                     | [d3ad63aa13](https://bsd-hardware.info/?probe=d3ad63aa13) | Oct 19, 2023 |
| Dell          | Inspiron 5559               | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| IBM           | ThinkPad R51 2889W11        | [45836fafc3](https://bsd-hardware.info/?probe=45836fafc3) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Dell          | Precision 7550              | [a21e06c16c](https://bsd-hardware.info/?probe=a21e06c16c) | Oct 11, 2023 |
| Deciso        | NetBoard-A20                | [ddffd0a126](https://bsd-hardware.info/?probe=ddffd0a126) | Oct 10, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [36daf066ca](https://bsd-hardware.info/?probe=36daf066ca) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [ac6742bd0f](https://bsd-hardware.info/?probe=ac6742bd0f) | Oct 07, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2AD0... | [3e15173331](https://bsd-hardware.info/?probe=3e15173331) | Oct 07, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [88e8c64b6f](https://bsd-hardware.info/?probe=88e8c64b6f) | Oct 04, 2023 |
| Google        | Auron_Paine                 | [d202b4dd6f](https://bsd-hardware.info/?probe=d202b4dd6f) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [1c44cf70e8](https://bsd-hardware.info/?probe=1c44cf70e8) | Oct 02, 2023 |
| Google        | Auron_Paine                 | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| Deciso        | Netboard A20                | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| Panasonic     | CFSX4-1                     | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Panasonic     | CFSX4-1                     | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| GPU Compan... | GWTC116-2                   | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [252fc12d3b](https://bsd-hardware.info/?probe=252fc12d3b) | Sep 09, 2023 |
| HP            | Pavilion g7                 | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [00dd1bd84e](https://bsd-hardware.info/?probe=00dd1bd84e) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| HP            | EliteBook 8540w             | [5e44dfed67](https://bsd-hardware.info/?probe=5e44dfed67) | Sep 01, 2023 |
| Panasonic     | CFSX4-1                     | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| Acer          | Aspire A515-55              | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| Deciso        | NetBoard-A20                | [0119402f80](https://bsd-hardware.info/?probe=0119402f80) | Aug 30, 2023 |
| Dell          | Latitude E4310              | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Dell          | Latitude 7280               | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| Dell          | Inspiron 15-7568            | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Acer          | Aspire A315-59              | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| Apple         | MacBookPro11,1              | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Apple         | MacBookPro9,2               | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| Dell          | Inspiron 3180               | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Deciso        | Netboard A20                | [9030d92418](https://bsd-hardware.info/?probe=9030d92418) | Jul 25, 2023 |
| Panasonic     | CFSX4-1                     | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| Toshiba       | Satellite L655              | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| 10ZiG Tech... | 5900q                       | [3c3668fcd2](https://bsd-hardware.info/?probe=3c3668fcd2) | Jul 14, 2023 |
| HP            | Laptop 14-cf2xxx            | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Getac         | F110G2                      | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Deciso        | Netboard A20                | [dd0a39a4d0](https://bsd-hardware.info/?probe=dd0a39a4d0) | Jul 05, 2023 |
| Unknown       | Unknown                     | [ae2bb37185](https://bsd-hardware.info/?probe=ae2bb37185) | Jul 03, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| Unknown       | Unknown                     | [e218344894](https://bsd-hardware.info/?probe=e218344894) | Jun 15, 2023 |
| Panasonic     | CFSX4-1                     | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Dell          | Inspiron 3180               | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| Dell          | Inspiron 5559               | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Deciso        | Netboard A20                | [eb03ae7215](https://bsd-hardware.info/?probe=eb03ae7215) | Jun 05, 2023 |
| Unknown       | Unknown                     | [a243045cc3](https://bsd-hardware.info/?probe=a243045cc3) | Jun 04, 2023 |
| Dell          | G5 5505                     | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| Dell          | G5 5505                     | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| Dell          | Inspiron 5559               | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Acer          | Nitro AN515-42              | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Dell          | Inspiron 5559               | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Dell          | Inspiron 5559               | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | ProBook 455 G3              | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Valve         | Jupiter                     | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| Panasonic     | CF-30KAPAXAM                | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Dell          | Inspiron 5559               | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| Panasonic     | CF-30KAPAXAM                | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| Apple         | MacBookPro11,5              | [45bffd3275](https://bsd-hardware.info/?probe=45bffd3275) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| Dell          | Latitude E5570              | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| Apple         | MacBookPro8,3               | [08e155a558](https://bsd-hardware.info/?probe=08e155a558) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| Deciso        | NetBoard-A20                | [3d0f6b629d](https://bsd-hardware.info/?probe=3d0f6b629d) | Apr 25, 2023 |
| Google        | Peppy                       | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
| HP            | Pavilion 17                 | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| HP            | Laptop 14-dk1xxx            | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Toshiba       | PORTEGE R700                | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| Unknown       | Unknown                     | [5bfbfb213e](https://bsd-hardware.info/?probe=5bfbfb213e) | Apr 09, 2023 |
| Dell          | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Fujitsu       | LIFEBOOK U810               | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Google        | Stout                       | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| Dell          | Inspiron 5559               | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Nitro AN515-53              | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| HP            | Pavilion TS Sleekbook 14    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Dell          | Inspiron 7520               | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| ASUSTek       | X541SA                      | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005SU... | [7750c38cd0](https://bsd-hardware.info/?probe=7750c38cd0) | Feb 25, 2023 |
| Dell          | Latitude 5591               | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| HP            | ZBook 15 G3                 | [ff6ddb74bb](https://bsd-hardware.info/?probe=ff6ddb74bb) | Feb 21, 2023 |
| Lenovo        | ThinkPad W520 427638U       | [baa0e928a8](https://bsd-hardware.info/?probe=baa0e928a8) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| Google        | Lulu                        | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Deciso        | OPNsense Appliance          | [1eda4c5b48](https://bsd-hardware.info/?probe=1eda4c5b48) | Feb 15, 2023 |
| Panasonic     | CF-30KAPAXAM                | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| HP            | Laptop 14-df0xxx            | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| HP            | Pavilion dv6                | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| Panasonic     | CF-30KAPAXAM                | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| HP            | Victus by Gaming Laptop ... | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Google        | Kefka                       | [83771661c6](https://bsd-hardware.info/?probe=83771661c6) | Jan 27, 2023 |
| Deciso        | Netboard A20                | [07de4617d2](https://bsd-hardware.info/?probe=07de4617d2) | Jan 26, 2023 |
| Deciso        | NetBoard-A20                | [0a40a0b8e2](https://bsd-hardware.info/?probe=0a40a0b8e2) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | [211bc64e5e](https://bsd-hardware.info/?probe=211bc64e5e) | Jan 24, 2023 |
| Dell          | Latitude 5580               | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| Apple         | MacBookPro9,2               | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Datto         | 1000                        | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| Acer          | TravelMate B311-31          | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Datto         | Unknown                     | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| Datto         | 1000                        | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Apple         | MacBookAir7,2               | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| Unknown       | Unknown                     | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| Dell          | Latitude E6420              | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Datto         | 1000                        | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| Dell          | Inspiron 5558               | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Deciso        | OPNsense Appliance          | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| Deciso        | OPNsense Appliance          | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Google        | Peppy                       | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Deciso        | OPNsense Appliance          | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| Dell          | Precision M4800             | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| DFI           | BE17X(170/171/173)          | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Google        | Lick                        | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Google        | Lick                        | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Dell          | Latitude E7240              | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Deciso        | Netboard A20                | [0320675a86](https://bsd-hardware.info/?probe=0320675a86) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Samsung       | 750TDA                      | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7708c4bb19](https://bsd-hardware.info/?probe=7708c4bb19) | Nov 02, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [22d3fc953a](https://bsd-hardware.info/?probe=22d3fc953a) | Nov 01, 2022 |
| Dell          | Latitude 5591               | [40957fa567](https://bsd-hardware.info/?probe=40957fa567) | Oct 31, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Lenovo        | ThinkPad T420s 4174DL7      | [82d774e711](https://bsd-hardware.info/?probe=82d774e711) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| Dell          | Latitude 5591               | [04f53f51c8](https://bsd-hardware.info/?probe=04f53f51c8) | Oct 12, 2022 |
| Dell          | Latitude 5591               | [eda94b6c48](https://bsd-hardware.info/?probe=eda94b6c48) | Oct 11, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Lenovo        | ThinkPad X270 20HMS04P00    | [7647b7a0b2](https://bsd-hardware.info/?probe=7647b7a0b2) | Oct 07, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | [627206d154](https://bsd-hardware.info/?probe=627206d154) | Oct 04, 2022 |
| Dell          | Precision M4800             | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| Lenovo        | ThinkPad W530 2436CTO       | [6515a18552](https://bsd-hardware.info/?probe=6515a18552) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| System76      | Gazelle                     | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| System76      | Gazelle                     | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| Deciso        | Netboard A20                | [388e27791d](https://bsd-hardware.info/?probe=388e27791d) | Sep 23, 2022 |
| Toshiba       | PORTEGE R700                | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Deciso        | Netboard A20                | [8af40be425](https://bsd-hardware.info/?probe=8af40be425) | Sep 13, 2022 |
| Dell          | XPS M1330                   | [d84548dd9b](https://bsd-hardware.info/?probe=d84548dd9b) | Sep 11, 2022 |
| Dell          | Precision 7540              | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| Dell          | Precision 7550              | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Valve         | Jupiter                     | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Dell          | Precision 7550              | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| Unknown       | Unknown                     | [1dfb3adb6b](https://bsd-hardware.info/?probe=1dfb3adb6b) | Aug 20, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| Lenovo        | ThinkPad 11e 4th Gen 20H... | [ba1ea734b1](https://bsd-hardware.info/?probe=ba1ea734b1) | Aug 19, 2022 |
| Deciso        | NetBoard-A20                | [7ec18da9e4](https://bsd-hardware.info/?probe=7ec18da9e4) | Aug 19, 2022 |
| Google        | Peppy                       | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Dell          | Studio 1537                 | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| HP            | Victus by Gaming Laptop ... | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Deciso        | NetBoard-A10                | [9d82dae644](https://bsd-hardware.info/?probe=9d82dae644) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | [cdc6bc6ef8](https://bsd-hardware.info/?probe=cdc6bc6ef8) | Aug 03, 2022 |
| Dell          | Inspiron 5559               | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Dell          | Precision 5560              | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Deciso        | Netboard A20                | [2bc988b18a](https://bsd-hardware.info/?probe=2bc988b18a) | Jul 18, 2022 |
| Dell          | Inspiron 15-3567            | [15c5d9fdd9](https://bsd-hardware.info/?probe=15c5d9fdd9) | Jul 17, 2022 |
| Deciso        | Netboard A20                | [a4be4171b6](https://bsd-hardware.info/?probe=a4be4171b6) | Jul 17, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Apple         | MacBookAir5,2               | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Deciso        | Netboard A20                | [743b330db3](https://bsd-hardware.info/?probe=743b330db3) | Jul 12, 2022 |
| Toshiba       | Satellite L305D             | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Toshiba       | Satellite L305D             | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Dell          | Latitude E6420              | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Unknown       | Unknown                     | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| Dell          | XPS 13 7390                 | [3c2e2da462](https://bsd-hardware.info/?probe=3c2e2da462) | Jul 02, 2022 |
| Dell          | XPS 13 7390                 | [b870cd3698](https://bsd-hardware.info/?probe=b870cd3698) | Jul 01, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Unknown       | Unknown                     | [d9e6e5b83a](https://bsd-hardware.info/?probe=d9e6e5b83a) | Jun 29, 2022 |
| Deciso        | NetBoard-A10                | [ace8b06cd3](https://bsd-hardware.info/?probe=ace8b06cd3) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo        | ThinkPad A485 20MU000VUS    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| Dell          | Precision M4800             | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| Dell          | Latitude E5500              | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| GPD           | MicroPC                     | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
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
| Framework     | Laptop                      | [9c201bb573](https://bsd-hardware.info/?probe=9c201bb573) | Jan 01, 2022 |
| Deciso        | DEC2700 - OPNsense Appli... | [30590e8ccf](https://bsd-hardware.info/?probe=30590e8ccf) | Dec 31, 2021 |
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
| Valve         | Jupiter                     | [e5aca4b7d0](https://bsd-hardware.info/?probe=e5aca4b7d0) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [efdfee9023](https://bsd-hardware.info/?probe=efdfee9023) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| HP            | Stream Notebook PC 11       | [c8ea8a4c4f](https://bsd-hardware.info/?probe=c8ea8a4c4f) | Sep 30, 2021 |
| HP            | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [76ea6529ac](https://bsd-hardware.info/?probe=76ea6529ac) | Sep 26, 2021 |
| System76      | Darter Pro                  | [f99c9f56b7](https://bsd-hardware.info/?probe=f99c9f56b7) | Sep 25, 2021 |
| Lenovo        | ThinkPad T410 2518C5U       | [e937639adc](https://bsd-hardware.info/?probe=e937639adc) | Sep 25, 2021 |
| Dell          | Precision 7710              | [f0bebc2b21](https://bsd-hardware.info/?probe=f0bebc2b21) | Sep 23, 2021 |
| System76      | Galago Pro                  | [ebe0575f31](https://bsd-hardware.info/?probe=ebe0575f31) | Sep 23, 2021 |
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
| Dell          | Inspiron 3521               | [b3569ebb39](https://bsd-hardware.info/?probe=b3569ebb39) | Feb 11, 2021 |
| Lenovo        | ThinkPad L512 25975XU       | [b4d22f4179](https://bsd-hardware.info/?probe=b4d22f4179) | Feb 10, 2021 |
| Lenovo        | 20QD0000US                  | [8d1c80c2cb](https://bsd-hardware.info/?probe=8d1c80c2cb) | Feb 09, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [55debb2f24](https://bsd-hardware.info/?probe=55debb2f24) | Feb 08, 2021 |
| Lenovo        | 20QD0000US                  | [77e80759a0](https://bsd-hardware.info/?probe=77e80759a0) | Feb 08, 2021 |
| System76      | Galago Pro                  | [8f39c38e2e](https://bsd-hardware.info/?probe=8f39c38e2e) | Feb 08, 2021 |
| Chuwi         | CoreBox X                   | [2e51dfe463](https://bsd-hardware.info/?probe=2e51dfe463) | Feb 07, 2021 |
| Chuwi         | CoreBox X                   | [be6f23d3ed](https://bsd-hardware.info/?probe=be6f23d3ed) | Feb 07, 2021 |
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
| HP            | EliteBook 820 G1            | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Lenovo        | ThinkPad T60 87445BU        | [37a42caa92](https://bsd-hardware.info/?probe=37a42caa92) | Jul 30, 2020 |
| HP            | Laptop 15-bs0xx             | [4cfc4cff49](https://bsd-hardware.info/?probe=4cfc4cff49) | Jul 28, 2020 |
| Dell          | Inspiron 3521               | [300cbce244](https://bsd-hardware.info/?probe=300cbce244) | Jul 26, 2020 |
| Timi          | RedmiBook 14 II             | [a7bf2669ce](https://bsd-hardware.info/?probe=a7bf2669ce) | Jul 24, 2020 |
| Dell          | Precision M4800             | [bbd03815ce](https://bsd-hardware.info/?probe=bbd03815ce) | Jul 20, 2020 |
| Toshiba       | Satellite C655D             | [191b32d117](https://bsd-hardware.info/?probe=191b32d117) | Jul 17, 2020 |
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

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 33        | 5.02%   |
| helloSystem 0.7.0    | 31        | 4.72%   |
| FreeBSD 13.0         | 28        | 4.26%   |
| FreeBSD 13.1         | 25        | 3.81%   |
| helloSystem 0.8.0    | 22        | 3.35%   |
| helloSystem 0.5.0    | 20        | 3.04%   |
| FreeBSD 13.2         | 18        | 2.74%   |
| OpenBSD 6.9          | 14        | 2.13%   |
| OpenBSD 6.8          | 14        | 2.13%   |
| helloSystem 0.4.0    | 14        | 2.13%   |
| FreeBSD 14.0-CURRENT | 14        | 2.13%   |
| GhostBSD 20.04.02    | 13        | 1.98%   |
| FreeBSD 12.1-p8      | 12        | 1.83%   |
| FreeBSD 13.0-p4      | 11        | 1.67%   |
| helloSystem 0.9.0    | 10        | 1.52%   |
| FreeBSD 12.2         | 10        | 1.52%   |
| OpenBSD 7.2          | 9         | 1.37%   |
| OpenBSD 7.0          | 8         | 1.22%   |
| FreeBSD 14.0         | 8         | 1.22%   |
| FreeBSD 13.1-p7      | 8         | 1.22%   |
| FreeBSD 13.1-p5      | 8         | 1.22%   |
| OpenBSD 7.4          | 7         | 1.07%   |
| helloSystem 0.6.0    | 7         | 1.07%   |
| GhostBSD 21.08.27    | 7         | 1.07%   |
| FreeBSD 12.2-p2      | 7         | 1.07%   |
| OpenBSD 6.7          | 6         | 0.91%   |
| NomadBSD 5806f915    | 6         | 0.91%   |
| NomadBSD 1.3.2       | 6         | 0.91%   |
| FreeBSD 13.0-STABLE  | 6         | 0.91%   |
| FreeBSD 13.0-p2      | 6         | 0.91%   |
| FreeBSD 12.2-p3      | 6         | 0.91%   |
| OpenBSD 7.3          | 5         | 0.76%   |
| helloSystem 0.8.2    | 5         | 0.76%   |
| GhostBSD 23.10.1     | 5         | 0.76%   |
| FreeBSD 13.1-p2      | 5         | 0.76%   |
| FreeBSD 13.0-p11     | 5         | 0.76%   |
| FreeBSD 12.2-p4      | 5         | 0.76%   |
| FreeBSD 12.1-p10     | 5         | 0.76%   |
| FreeBSD 12.1         | 5         | 0.76%   |
| OPNsense 21.7.7      | 4         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 235       | 42.11%  |
| helloSystem | 136       | 24.37%  |
| OpenBSD     | 63        | 11.29%  |
| OPNsense    | 50        | 8.96%   |
| GhostBSD    | 43        | 7.71%   |
| NomadBSD    | 17        | 3.05%   |
| HardenedBSD | 4         | 0.72%   |
| NetBSD      | 3         | 0.54%   |
| MidnightBSD | 3         | 0.54%   |
| DragonFly   | 3         | 0.54%   |
| FuryBSD     | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 522       | 95.78%  |
| i386   | 21        | 3.85%   |
| macppc | 1         | 0.18%   |
| arm64  | 1         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| helloDesktop  | 151       | 26.26%  |
| Console       | 76        | 13.22%  |
| XFCE          | 70        | 12.17%  |
| MATE          | 54        | 9.39%   |
| KDE5          | 50        | 8.7%    |
| fvwm          | 38        | 6.61%   |
| GNOME         | 28        | 4.87%   |
| TWM           | 27        | 4.7%    |
| Openbox       | 25        | 4.35%   |
| i3            | 20        | 3.48%   |
| Cinnamon      | 6         | 1.04%   |
| LXQt          | 5         | 0.87%   |
| Fluxbox       | 5         | 0.87%   |
| Enlightenment | 4         | 0.7%    |
| AwesomeWM     | 3         | 0.52%   |
| Lumina        | 2         | 0.35%   |
| GNUstep       | 2         | 0.35%   |
| DWM           | 2         | 0.35%   |
| Xfwm4         | 1         | 0.17%   |
| wlroots       | 1         | 0.17%   |
| spectrwm      | 1         | 0.17%   |
| sdorfehs      | 1         | 0.17%   |
| LXDE          | 1         | 0.17%   |
| Compton       | 1         | 0.17%   |
| CDE           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 459       | 83.15%  |
| Console | 85        | 15.4%   |
| Wayland | 8         | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 212       | 37.19%  |
| SLiM    | 195       | 34.21%  |
| LightDM | 66        | 11.58%  |
| SDDM    | 51        | 8.95%   |
| XDM     | 23        | 4.04%   |
| GDM     | 20        | 3.51%   |
| Ly      | 3         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| Unknown         | 196       | 34.33%  |
| en_US           | 195       | 34.15%  |
| C               | 156       | 27.32%  |
| en              | 17        | 2.98%   |
| en_US.US-ASCII  | 2         | 0.35%   |
| fr_FR           | 1         | 0.18%   |
| es_CO           | 1         | 0.18%   |
| en_US.ISO8859-1 | 1         | 0.18%   |
| en_GB           | 1         | 0.18%   |
| de_DE           | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 422       | 76.17%  |
| BIOS | 132       | 23.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 320       | 56.94%  |
| Ufs     | 130       | 23.13%  |
| Ffs     | 63        | 11.21%  |
| Cd9660  | 46        | 8.19%   |
| Hammer2 | 3         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 478       | 86.28%  |
| MBR     | 66        | 11.91%  |
| Unknown | 6         | 1.08%   |
| BSD     | 4         | 0.72%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 187       | 34.44%  |
| Dell                | 108       | 19.89%  |
| Hewlett-Packard     | 62        | 11.42%  |
| Apple               | 31        | 5.71%   |
| ASUSTek Computer    | 22        | 4.05%   |
| Deciso              | 19        | 3.5%    |
| Acer                | 19        | 3.5%    |
| Toshiba             | 13        | 2.39%   |
| Google              | 12        | 2.21%   |
| System76            | 10        | 1.84%   |
| Framework           | 7         | 1.29%   |
| Unknown             | 6         | 1.1%    |
| Panasonic           | 4         | 0.74%   |
| MSI                 | 4         | 0.74%   |
| Datto               | 4         | 0.74%   |
| Sony                | 3         | 0.55%   |
| IBM                 | 3         | 0.55%   |
| Gateway             | 3         | 0.55%   |
| Valve               | 2         | 0.37%   |
| TUXEDO              | 2         | 0.37%   |
| Timi                | 2         | 0.37%   |
| Samsung Electronics | 2         | 0.37%   |
| LG Electronics      | 2         | 0.37%   |
| GPU Company         | 2         | 0.37%   |
| DFI                 | 2         | 0.37%   |
| Razer               | 1         | 0.18%   |
| Notebook            | 1         | 0.18%   |
| MOTILE              | 1         | 0.18%   |
| IGEL Technology     | 1         | 0.18%   |
| GPD                 | 1         | 0.18%   |
| Gigabyte Technology | 1         | 0.18%   |
| Getac               | 1         | 0.18%   |
| Fujitsu             | 1         | 0.18%   |
| Eluktronics         | 1         | 0.18%   |
| Chuwi               | 1         | 0.18%   |
| Alienware           | 1         | 0.18%   |
| 10ZiG Technology    | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Deciso Netboard A20                 | 10        | 1.84%   |
| Unknown                             | 8         | 1.47%   |
| Framework Laptop                    | 7         | 1.29%   |
| Dell Inspiron 3521                  | 5         | 0.92%   |
| Deciso NetBoard-A20                 | 5         | 0.92%   |
| Lenovo ThinkPad X220 4286CTO        | 4         | 0.74%   |
| HP Pavilion dv6                     | 4         | 0.74%   |
| Dell Latitude E7240                 | 4         | 0.74%   |
| Dell Latitude E6420                 | 4         | 0.74%   |
| Apple MacBookPro9,2                 | 4         | 0.74%   |
| HP 2000                             | 3         | 0.55%   |
| Google Peppy                        | 3         | 0.55%   |
| Dell Latitude E5420                 | 3         | 0.55%   |
| Dell Latitude 7490                  | 3         | 0.55%   |
| Datto 1000                          | 3         | 0.55%   |
| Apple MacBookPro8,3                 | 3         | 0.55%   |
| Apple MacBookPro6,2                 | 3         | 0.55%   |
| Valve Jupiter                       | 2         | 0.37%   |
| TUXEDO Pulse 15 Gen1                | 2         | 0.37%   |
| Toshiba PORTEGE R700                | 2         | 0.37%   |
| System76 Kudu                       | 2         | 0.37%   |
| System76 Gazelle                    | 2         | 0.37%   |
| System76 Galago Pro                 | 2         | 0.37%   |
| System76 Bonobo Extreme             | 2         | 0.37%   |
| Lenovo ThinkPad X250 20CLS1WP01     | 2         | 0.37%   |
| Lenovo ThinkPad X220 Tablet 42962WU | 2         | 0.37%   |
| Lenovo ThinkPad X220 42872WU        | 2         | 0.37%   |
| Lenovo ThinkPad W530 2436CTO        | 2         | 0.37%   |
| Lenovo ThinkPad T60 20076PU         | 2         | 0.37%   |
| Lenovo ThinkPad T430s 2352CTO       | 2         | 0.37%   |
| Lenovo ThinkPad 13 20GJCTO1WW       | 2         | 0.37%   |
| Lenovo IdeaPad Slim 9 14ITL5 82D2   | 2         | 0.37%   |
| Lenovo IdeaPad 330-15IKB 81DE       | 2         | 0.37%   |
| Lenovo Flex 2-15 20405              | 2         | 0.37%   |
| HP ZBook 15 G3                      | 2         | 0.37%   |
| HP Pavilion 17                      | 2         | 0.37%   |
| DFI BE17X(170/171/173)              | 2         | 0.37%   |
| Dell XPS 15 9530                    | 2         | 0.37%   |
| Dell XPS 13 9360                    | 2         | 0.37%   |
| Dell Precision M4800                | 2         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 157       | 28.91%  |
| Dell Latitude       | 47        | 8.66%   |
| Dell Inspiron       | 30        | 5.52%   |
| HP Pavilion         | 16        | 2.95%   |
| Lenovo IdeaPad      | 15        | 2.76%   |
| Dell Precision      | 13        | 2.39%   |
| Toshiba Satellite   | 10        | 1.84%   |
| HP Laptop           | 10        | 1.84%   |
| Dell XPS            | 10        | 1.84%   |
| Deciso Netboard     | 10        | 1.84%   |
| Acer Aspire         | 8         | 1.47%   |
| Unknown             | 8         | 1.47%   |
| HP ProBook          | 7         | 1.29%   |
| HP EliteBook        | 7         | 1.29%   |
| Framework Laptop    | 7         | 1.29%   |
| Deciso NetBoard-A20 | 5         | 0.92%   |
| ASUS VivoBook       | 5         | 0.92%   |
| Apple MacBookPro9   | 5         | 0.92%   |
| Lenovo Legion       | 4         | 0.74%   |
| Apple MacBookPro8   | 4         | 0.74%   |
| Acer Nitro          | 4         | 0.74%   |
| Lenovo Yoga         | 3         | 0.55%   |
| Lenovo Flex         | 3         | 0.55%   |
| IBM ThinkPad        | 3         | 0.55%   |
| HP ZBook            | 3         | 0.55%   |
| HP OMEN             | 3         | 0.55%   |
| HP ENVY             | 3         | 0.55%   |
| HP 2000             | 3         | 0.55%   |
| Google Peppy        | 3         | 0.55%   |
| Datto 1000          | 3         | 0.55%   |
| Apple MacBookPro6   | 3         | 0.55%   |
| Apple MacBookPro11  | 3         | 0.55%   |
| Valve Jupiter       | 2         | 0.37%   |
| TUXEDO Pulse        | 2         | 0.37%   |
| Toshiba PORTEGE     | 2         | 0.37%   |
| System76 Kudu       | 2         | 0.37%   |
| System76 Gazelle    | 2         | 0.37%   |
| System76 Galago     | 2         | 0.37%   |
| System76 Bonobo     | 2         | 0.37%   |
| HP Stream           | 2         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 68        | 12.52%  |
| 2021    | 57        | 10.5%   |
| 2011    | 47        | 8.66%   |
| 2013    | 41        | 7.55%   |
| 2018    | 38        | 7%      |
| 2019    | 36        | 6.63%   |
| 2016    | 36        | 6.63%   |
| 2015    | 36        | 6.63%   |
| 2022    | 33        | 6.08%   |
| 2012    | 23        | 4.24%   |
| 2014    | 22        | 4.05%   |
| 2017    | 19        | 3.5%    |
| 2010    | 19        | 3.5%    |
| 2009    | 17        | 3.13%   |
| 2023    | 13        | 2.39%   |
| 2008    | 13        | 2.39%   |
| 2007    | 11        | 2.03%   |
| 2006    | 7         | 1.29%   |
| 2005    | 2         | 0.37%   |
| 2004    | 2         | 0.37%   |
| Unknown | 2         | 0.37%   |
| 2002    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 543       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 524       | 96.5%   |
| Yes  | 19        | 3.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 193       | 34.71%  |
| 16.01-24.0  | 148       | 26.62%  |
| 4.01-8.0    | 107       | 19.24%  |
| 32.01-64.0  | 40        | 7.19%   |
| 2.01-3.0    | 20        | 3.6%    |
| 3.01-4.0    | 19        | 3.42%   |
| 64.01-256.0 | 12        | 2.16%   |
| 24.01-32.0  | 7         | 1.26%   |
| 1.01-2.0    | 4         | 0.72%   |
| 0.51-1.0    | 4         | 0.72%   |
| 0.01-0.5    | 2         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Notebooks | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 271       | 48.74%  |
| 0.51-1.0    | 174       | 31.29%  |
| 1.01-2.0    | 62        | 11.15%  |
| 2.01-3.0    | 20        | 3.6%    |
| 8.01-16.0   | 8         | 1.44%   |
| 0           | 7         | 1.26%   |
| 4.01-8.0    | 4         | 0.72%   |
| 3.01-4.0    | 3         | 0.54%   |
| Unknown     | 3         | 0.54%   |
| 16.01-24.0  | 2         | 0.36%   |
| 24.01-32.0  | 1         | 0.18%   |
| 64.01-256.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 418       | 74.51%  |
| 2      | 80        | 14.26%  |
| 0      | 49        | 8.73%   |
| 3      | 13        | 2.32%   |
| 4      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 387       | 70.75%  |
| Yes       | 160       | 29.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 450       | 82.87%  |
| No        | 93        | 17.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 507       | 93.03%  |
| No        | 38        | 6.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 366       | 66.67%  |
| No        | 183       | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 543       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Brooklyn      | 22        | 3.79%   |
| Seattle       | 14        | 2.41%   |
| Portland      | 13        | 2.24%   |
| Los Angeles   | 11        | 1.9%    |
| New York      | 10        | 1.72%   |
| Chicago       | 9         | 1.55%   |
| Sun Prairie   | 6         | 1.03%   |
| Washington    | 5         | 0.86%   |
| Fayetteville  | 5         | 0.86%   |
| Charlotte     | 5         | 0.86%   |
| Vienna        | 4         | 0.69%   |
| San Antonio   | 4         | 0.69%   |
| Rochester     | 4         | 0.69%   |
| Queens        | 4         | 0.69%   |
| Las Vegas     | 4         | 0.69%   |
| Lafayette     | 4         | 0.69%   |
| Indian Trail  | 4         | 0.69%   |
| Harrisburg    | 4         | 0.69%   |
| Frisco        | 4         | 0.69%   |
| Denver        | 4         | 0.69%   |
| Dallas        | 4         | 0.69%   |
| Whittier      | 3         | 0.52%   |
| Springfield   | 3         | 0.52%   |
| San Jose      | 3         | 0.52%   |
| San Francisco | 3         | 0.52%   |
| Roswell       | 3         | 0.52%   |
| Richmond      | 3         | 0.52%   |
| Redmond       | 3         | 0.52%   |
| Phoenix       | 3         | 0.52%   |
| Omaha         | 3         | 0.52%   |
| Oklahoma City | 3         | 0.52%   |
| Midvale       | 3         | 0.52%   |
| Madison       | 3         | 0.52%   |
| Houston       | 3         | 0.52%   |
| Glendale      | 3         | 0.52%   |
| Eugene        | 3         | 0.52%   |
| Dublin        | 3         | 0.52%   |
| Berkeley      | 3         | 0.52%   |
| Atlanta       | 3         | 0.52%   |
| Apex          | 3         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 105       | 128    | 17.86%  |
| WDC                 | 74        | 79     | 12.59%  |
| Seagate             | 38        | 41     | 6.46%   |
| Toshiba             | 37        | 50     | 6.29%   |
| Crucial             | 36        | 57     | 6.12%   |
| SanDisk             | 34        | 44     | 5.78%   |
| Transcend           | 28        | 54     | 4.76%   |
| Kingston            | 25        | 28     | 4.25%   |
| Intel               | 19        | 22     | 3.23%   |
| NVMe                | 18        | 23     | 3.06%   |
| SK hynix            | 17        | 17     | 2.89%   |
| Hitachi             | 15        | 17     | 2.55%   |
| PNY                 | 14        | 21     | 2.38%   |
| Apple               | 12        | 12     | 2.04%   |
| Micron Technology   | 10        | 12     | 1.7%    |
| HGST                | 9         | 10     | 1.53%   |
| SPCC                | 8         | 8      | 1.36%   |
| OWC                 | 8         | 9      | 1.36%   |
| Phison              | 7         | 14     | 1.19%   |
| Corsair             | 6         | 6      | 1.02%   |
| A-DATA Technology   | 6         | 9      | 1.02%   |
| KIOXIA              | 5         | 5      | 0.85%   |
| KingSpec            | 5         | 5      | 0.85%   |
| Mushkin             | 4         | 4      | 0.68%   |
| Fujitsu             | 4         | 4      | 0.68%   |
| Zheino              | 3         | 6      | 0.51%   |
| SSSTC               | 3         | 3      | 0.51%   |
| Lexar               | 3         | 8      | 0.51%   |
| Team                | 2         | 3      | 0.34%   |
| Patriot             | 2         | 2      | 0.34%   |
| OCZ                 | 2         | 2      | 0.34%   |
| Netac               | 2         | 2      | 0.34%   |
| MyDigitalSSD        | 2         | 2      | 0.34%   |
| LITEONIT            | 2         | 2      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| Hewlett-Packard     | 2         | 2      | 0.34%   |
| China               | 2         | 2      | 0.34%   |
| BIWIN               | 2         | 3      | 0.34%   |
| ZTC                 | 1         | 1      | 0.17%   |
| T-FORCE             | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB       | 13        | 2.16%   |
| Kingston SA400S37240G 240GB          | 9         | 1.5%    |
| Crucial CT500MX500SSD1 500GB         | 9         | 1.5%    |
| Samsung SSD 850 EVO 250GB            | 6         | 1%      |
| Crucial CT1000MX500SSD1 1TB          | 6         | 1%      |
| WDC WDS500G3X0C-00SJG0 500GB         | 5         | 0.83%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 0.83%   |
| SanDisk SSD PLUS 240GB               | 5         | 0.83%   |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.83%   |
| NVMe WDC PC SN730 SDB 512GB          | 5         | 0.83%   |
| WDC WDBNCE5000PNC 500GB              | 4         | 0.66%   |
| Transcend TS128GMTS430S 128GB        | 4         | 0.66%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.66%   |
| Toshiba MQ01ABD100 1TB               | 4         | 0.66%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.66%   |
| Samsung SSD 860 EVO 1TB              | 4         | 0.66%   |
| Samsung SSD 850 PRO 512GB            | 4         | 0.66%   |
| Crucial CT120BX500SSD1 120GB         | 4         | 0.66%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 3         | 0.5%    |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.5%    |
| Samsung SSD 850 EVO 1TB              | 3         | 0.5%    |
| Samsung MZVLW256HEHP-000L7 256GB     | 3         | 0.5%    |
| Samsung MZVLB512HBJQ-000L7 512GB     | 3         | 0.5%    |
| Samsung MZVLB1T0HBLR-000L2 1TB       | 3         | 0.5%    |
| Samsung MZNLN256HCHP-000L7 256GB     | 3         | 0.5%    |
| PNY CS900 240GB SSD                  | 3         | 0.5%    |
| PNY CS900 1TB SSD                    | 3         | 0.5%    |
| Phison PCIe SSD 512GB                | 3         | 0.5%    |
| Intel SSDPEKKF256G8L 256GB           | 3         | 0.5%    |
| Hitachi HTS547550A9E384 500GB        | 3         | 0.5%    |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.33%   |
| WDC WD1600BEVT-75ZCT2 160GB          | 2         | 0.33%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.33%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.33%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 2         | 0.33%   |
| WDC PC SN730 NVMe 1024GB             | 2         | 0.33%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB | 2         | 0.33%   |
| Transcend TS256GMTE652T2 256GB       | 2         | 0.33%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 44     | 27.04%  |
| Seagate             | 37        | 40     | 23.27%  |
| Toshiba             | 27        | 39     | 16.98%  |
| NVMe                | 15        | 18     | 9.43%   |
| Hitachi             | 15        | 17     | 9.43%   |
| HGST                | 9         | 10     | 5.66%   |
| Fujitsu             | 4         | 4      | 2.52%   |
| Apple               | 3         | 3      | 1.89%   |
| Samsung Electronics | 2         | 3      | 1.26%   |
| OPENBSD             | 1         | 1      | 0.63%   |
| IBM/Hitachi         | 1         | 1      | 0.63%   |
| Generic             | 1         | 1      | 0.63%   |
| General             | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 64        | 71     | 20.85%  |
| SanDisk             | 34        | 44     | 11.07%  |
| Crucial             | 31        | 45     | 10.1%   |
| Transcend           | 24        | 50     | 7.82%   |
| Kingston            | 20        | 22     | 6.51%   |
| PNY                 | 14        | 21     | 4.56%   |
| WDC                 | 12        | 12     | 3.91%   |
| Intel               | 11        | 13     | 3.58%   |
| SK hynix            | 10        | 10     | 3.26%   |
| Apple               | 9         | 9      | 2.93%   |
| OWC                 | 8         | 9      | 2.61%   |
| SPCC                | 7         | 7      | 2.28%   |
| Corsair             | 6         | 6      | 1.95%   |
| KingSpec            | 5         | 5      | 1.63%   |
| A-DATA Technology   | 5         | 5      | 1.63%   |
| NVMe                | 4         | 4      | 1.3%    |
| Zheino              | 3         | 6      | 0.98%   |
| Mushkin             | 3         | 3      | 0.98%   |
| Lexar               | 3         | 8      | 0.98%   |
| Toshiba             | 2         | 2      | 0.65%   |
| Team                | 2         | 3      | 0.65%   |
| SSSTC               | 2         | 2      | 0.65%   |
| Phison              | 2         | 2      | 0.65%   |
| Patriot             | 2         | 2      | 0.65%   |
| OCZ                 | 2         | 2      | 0.65%   |
| Netac               | 2         | 2      | 0.65%   |
| MyDigitalSSD        | 2         | 2      | 0.65%   |
| Micron Technology   | 2         | 2      | 0.65%   |
| LITEONIT            | 2         | 2      | 0.65%   |
| Hewlett-Packard     | 2         | 2      | 0.65%   |
| China               | 2         | 2      | 0.65%   |
| BIWIN               | 2         | 3      | 0.65%   |
| ZTC                 | 1         | 1      | 0.33%   |
| Seagate             | 1         | 1      | 0.33%   |
| Plextor             | 1         | 1      | 0.33%   |
| Pioneer             | 1         | 1      | 0.33%   |
| Intenso             | 1         | 1      | 0.33%   |
| FLEXXON             | 1         | 5      | 0.33%   |
| Dogfish             | 1         | 2      | 0.33%   |
| Dell                | 1         | 2      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 276       | 392    | 50.46%  |
| HDD  | 156       | 182    | 28.52%  |
| NVMe | 115       | 165    | 21.02%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 411       | 574    | 78.14%  |
| NVMe | 115       | 165    | 21.86%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 313       | 417    | 71.79%  |
| 0.51-1.0   | 107       | 138    | 24.54%  |
| 1.01-2.0   | 15        | 18     | 3.44%   |
| 2.01-3.0   | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 186       | 32.75%  |
| 251-500    | 141       | 24.82%  |
| 1-20       | 99        | 17.43%  |
| 501-1000   | 64        | 11.27%  |
| 51-100     | 38        | 6.69%   |
| 21-50      | 21        | 3.7%    |
| 1001-2000  | 15        | 2.64%   |
| Unknown    | 3         | 0.53%   |
| 2001-3000  | 1         | 0.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 484       | 85.06%  |
| 21-50    | 50        | 8.79%   |
| 51-100   | 16        | 2.81%   |
| 101-250  | 13        | 2.28%   |
| Unknown  | 3         | 0.53%   |
| 251-500  | 2         | 0.35%   |
| 501-1000 | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                              | Notebooks | Drives | Percent |
|----------------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB                    | 4         | 4      | 5.48%   |
| SSSTC CVB-8D128-HP 128GB                           | 2         | 2      | 2.74%   |
| Seagate ST95005620AS 500GB                         | 2         | 2      | 2.74%   |
| SanDisk SSD PLUS 240GB                             | 2         | 2      | 2.74%   |
| WDC WD5000LPCX-75VHAT0 500GB                       | 1         | 1      | 1.37%   |
| WDC WD3200BPVT-75ZEST0 320GB                       | 1         | 1      | 1.37%   |
| WDC WD3200BPVT-75JJ5T0 320GB                       | 1         | 1      | 1.37%   |
| WDC WD3200BEKT-60V5T1 320GB                        | 1         | 1      | 1.37%   |
| WDC WD30PURZ-85AKKY0 3TB                           | 1         | 1      | 1.37%   |
| WDC WD1600BEKT-66F3T2 160GB                        | 1         | 1      | 1.37%   |
| Toshiba MQ04ABF100 1TB                             | 1         | 1      | 1.37%   |
| Toshiba MQ01ACF032 320GB                           | 1         | 3      | 1.37%   |
| Toshiba MQ01ABF050 500GB                           | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD100 1TB                             | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD075 752GB                           | 1         | 1      | 1.37%   |
| Toshiba MK7559GSXF 752GB                           | 1         | 1      | 1.37%   |
| Toshiba MK5061GSYN 500GB                           | 1         | 1      | 1.37%   |
| Toshiba MK3265GSXN 320GB                           | 1         | 5      | 1.37%   |
| Toshiba MK3261GSYN 320GB                           | 1         | 1      | 1.37%   |
| Toshiba MK1637GSX 160GB                            | 1         | 3      | 1.37%   |
| SK hynix SC401 SATA 256GB                          | 1         | 1      | 1.37%   |
| SK hynix SC210 mSATA 256GB                         | 1         | 1      | 1.37%   |
| Seagate ST96023AS 58GB                             | 1         | 1      | 1.37%   |
| Seagate ST9500420AS 500GB                          | 1         | 1      | 1.37%   |
| Seagate ST9320423AS 320GB                          | 1         | 1      | 1.37%   |
| Seagate ST750LM022 HN-M750MBB 752GB                | 1         | 1      | 1.37%   |
| Seagate ST500LT012-9WS142 500GB                    | 1         | 1      | 1.37%   |
| Seagate ST500LT012-1DG142 500GB                    | 1         | 1      | 1.37%   |
| Seagate ST500LM000-SSHD-8GB                        | 1         | 1      | 1.37%   |
| Seagate ST500LM000-1EJ162 500GB                    | 1         | 1      | 1.37%   |
| Seagate ST320LT007-9ZV142 320GB                    | 1         | 1      | 1.37%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                 | 1         | 1      | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB                     | 1         | 2      | 1.37%   |
| SanDisk SD5SG2128G1052E 128GB                      | 1         | 1      | 1.37%   |
| Samsung Electronics SSD UM410 Series 2.5-inch 16GB | 1         | 1      | 1.37%   |
| Samsung Electronics SSD PM851 mSATA 256GB          | 1         | 1      | 1.37%   |
| Samsung Electronics SSD PM810 2.5-inch 128GB       | 1         | 1      | 1.37%   |
| Samsung Electronics SSD 870 EVO 2TB                | 1         | 1      | 1.37%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB       | 1         | 1      | 1.37%   |
| Samsung Electronics HS08XJC 80GB                   | 1         | 1      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 23.29%  |
| Toshiba             | 10        | 18     | 13.7%   |
| Samsung Electronics | 7         | 8      | 9.59%   |
| Hitachi             | 7         | 8      | 9.59%   |
| WDC                 | 6         | 6      | 8.22%   |
| Kingston            | 5         | 5      | 6.85%   |
| HGST                | 4         | 4      | 5.48%   |
| SanDisk             | 3         | 3      | 4.11%   |
| Intel               | 3         | 3      | 4.11%   |
| SSSTC               | 2         | 2      | 2.74%   |
| SK hynix            | 2         | 2      | 2.74%   |
| Apple               | 2         | 2      | 2.74%   |
| Patriot             | 1         | 1      | 1.37%   |
| KingSpec            | 1         | 1      | 1.37%   |
| IBM/Hitachi         | 1         | 1      | 1.37%   |
| Crucial             | 1         | 1      | 1.37%   |
| Corsair             | 1         | 1      | 1.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 18     | 35.42%  |
| Toshiba             | 10        | 18     | 20.83%  |
| Hitachi             | 7         | 8      | 14.58%  |
| WDC                 | 6         | 6      | 12.5%   |
| HGST                | 4         | 4      | 8.33%   |
| Samsung Electronics | 2         | 3      | 4.17%   |
| IBM/Hitachi         | 1         | 1      | 2.08%   |
| Apple               | 1         | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 59     | 65.75%  |
| SSD  | 25        | 25     | 34.25%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model             | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SanDisk pSSD 16GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 424       | 626    | 81.54%  |
| Malfunc  | 73        | 84     | 14.04%  |
| Detected | 22        | 28     | 4.23%   |
| Failed   | 1         | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 370       | 61.87%  |
| AMD                                     | 70        | 11.71%  |
| Samsung Electronics                     | 55        | 9.2%    |
| SanDisk                                 | 28        | 4.68%   |
| Micron Technology                       | 11        | 1.84%   |
| Toshiba                                 | 9         | 1.51%   |
| SK hynix                                | 9         | 1.51%   |
| KIOXIA                                  | 7         | 1.17%   |
| Phison Electronics                      | 6         | 1%      |
| Kingston Technology Company             | 5         | 0.84%   |
| Transcend                               | 4         | 0.67%   |
| Micron/Crucial Technology               | 4         | 0.67%   |
| Silicon Motion                          | 3         | 0.5%    |
| Nvidia                                  | 3         | 0.5%    |
| Union Memory (Shenzhen)                 | 2         | 0.33%   |
| Realtek Semiconductor                   | 2         | 0.33%   |
| Lenovo                                  | 2         | 0.33%   |
| JMicron Technology                      | 2         | 0.33%   |
| Solid State Storage Technology          | 1         | 0.17%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.17%   |
| Shenzhen Unionmemory Information System | 1         | 0.17%   |
| Marvell Technology Group                | 1         | 0.17%   |
| Lite-On Technology                      | 1         | 0.17%   |
| ADATA Technology                        | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 58        | 8.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 54        | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 44        | 6.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 38        | 5.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 32        | 4.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 24        | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 22        | 3.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 18        | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 18        | 2.78%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 17        | 2.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 2.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 15        | 2.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 2.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 2.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 1.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 10        | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 8         | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 6         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.77%   |
| AMD FCH IDE Controller                                                           | 5         | 0.77%   |
| Toshiba XG5 NVMe SSD Controller                                                  | 4         | 0.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 0.62%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.62%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 4         | 0.62%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 0.62%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 4         | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.62%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 3         | 0.46%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 3         | 0.46%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 0.46%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 0.46%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 3         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 392       | 63.53%  |
| NVMe | 142       | 23.01%  |
| IDE  | 59        | 9.56%   |
| RAID | 24        | 3.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 451       | 82.75%  |
| AMD     | 92        | 16.88%  |
| ARM     | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz       | 16        | 2.91%   |
| AMD EPYC 3201 8-Core Processor          | 12        | 2.18%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 11        | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 1.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 7         | 1.27%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 7         | 1.27%   |
| Intel Core 2 Duo                        | 7         | 1.27%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 6         | 1.09%   |
| Intel Core i3-3227U CPU @ 1.90GHz       | 6         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 6         | 1.09%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 0.91%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 5         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 0.91%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.91%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 5         | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 5         | 0.91%   |
| Intel CPU Version                       | 4         | 0.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.73%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 0.73%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 0.73%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 4         | 0.73%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 4         | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 0.73%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz      | 4         | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 0.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 0.73%   |
| AMD EPYC 3101 4-Core Processor          | 4         | 0.73%   |
| Intel Pentium M processor               | 3         | 0.55%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 3         | 0.55%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 0.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 0.55%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 3         | 0.55%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 3         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 151       | 27.61%  |
| Intel Core i7          | 131       | 23.95%  |
| Other                  | 45        | 8.23%   |
| Intel Core 2 Duo       | 32        | 5.85%   |
| Intel Celeron          | 31        | 5.67%   |
| Intel Core i3          | 27        | 4.94%   |
| AMD EPYC               | 16        | 2.93%   |
| AMD Ryzen 7            | 14        | 2.56%   |
| AMD Ryzen 5            | 9         | 1.65%   |
| Intel Pentium          | 7         | 1.28%   |
| Intel Core 2           | 6         | 1.1%    |
| AMD A10                | 6         | 1.1%    |
| Intel Genuine          | 5         | 0.91%   |
| Intel Atom             | 5         | 0.91%   |
| Intel Xeon             | 4         | 0.73%   |
| Intel Pentium M        | 4         | 0.73%   |
| Intel Core i9          | 4         | 0.73%   |
| AMD Ryzen Embedded     | 4         | 0.73%   |
| AMD Ryzen 7 PRO        | 4         | 0.73%   |
| AMD Ryzen 5 PRO        | 4         | 0.73%   |
| AMD Ryzen 3            | 4         | 0.73%   |
| AMD GX                 | 3         | 0.55%   |
| AMD A6                 | 3         | 0.55%   |
| Intel Pentium Silver   | 2         | 0.37%   |
| Intel Pentium 4        | 2         | 0.37%   |
| AMD Phenom II          | 2         | 0.37%   |
| AMD E1                 | 2         | 0.37%   |
| AMD E                  | 2         | 0.37%   |
| AMD C-50               | 2         | 0.37%   |
| AMD A8                 | 2         | 0.37%   |
| Intel Pentium Dual     | 1         | 0.18%   |
| Intel Mobile Pentium 4 | 1         | 0.18%   |
| Intel Mobile Celeron   | 1         | 0.18%   |
| Intel Core m3          | 1         | 0.18%   |
| Intel Core 2 Extreme   | 1         | 0.18%   |
| ARM Cortex             | 1         | 0.18%   |
| AMD Turion 64 Mobile   | 1         | 0.18%   |
| AMD Ryzen 9            | 1         | 0.18%   |
| AMD E2                 | 1         | 0.18%   |
| AMD C-60               | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 250       | 45.54%  |
| 4       | 161       | 29.33%  |
| Unknown | 40        | 7.29%   |
| 8       | 39        | 7.1%    |
| 6       | 20        | 3.64%   |
| 1       | 14        | 2.55%   |
| 16      | 12        | 2.19%   |
| 12      | 9         | 1.64%   |
| 20      | 3         | 0.55%   |
| 10      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 527       | 96.7%   |
| Unknown | 10        | 1.83%   |
| 2       | 8         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 346       | 63.02%  |
| 1       | 154       | 28.05%  |
| Unknown | 49        | 8.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 93        | 17.06%  |
| IvyBridge       | 53        | 9.72%   |
| SandyBridge     | 46        | 8.44%   |
| Haswell         | 43        | 7.89%   |
| Skylake         | 33        | 6.06%   |
| Broadwell       | 27        | 4.95%   |
| Westmere        | 26        | 4.77%   |
| Zen             | 23        | 4.22%   |
| Core            | 22        | 4.04%   |
| Penryn          | 20        | 3.67%   |
| Unknown         | 19        | 3.49%   |
| TigerLake       | 18        | 3.3%    |
| Zen+            | 14        | 2.57%   |
| Zen 2           | 13        | 2.39%   |
| Silvermont      | 12        | 2.2%    |
| Goldmont plus   | 11        | 2.02%   |
| Bonnell         | 8         | 1.47%   |
| Bobcat          | 7         | 1.28%   |
| IceLake         | 6         | 1.1%    |
| Excavator       | 6         | 1.1%    |
| CometLake       | 6         | 1.1%    |
| P6              | 5         | 0.92%   |
| Zen 3           | 4         | 0.73%   |
| Jaguar          | 4         | 0.73%   |
| Goldmont        | 4         | 0.73%   |
| Puma            | 3         | 0.55%   |
| Piledriver      | 3         | 0.55%   |
| NetBurst        | 3         | 0.55%   |
| Nehalem         | 3         | 0.55%   |
| K10             | 3         | 0.55%   |
| Steamroller     | 2         | 0.37%   |
| K8 Hammer       | 2         | 0.37%   |
| K10 Llano       | 2         | 0.37%   |
| K8 & K10 hybrid | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 409       | 67.83%  |
| AMD                              | 100       | 16.58%  |
| Nvidia                           | 93        | 15.42%  |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 49        | 7.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 6.96%   |
| Intel UHD Graphics 620                                                                   | 25        | 3.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 3.96%   |
| Intel HD Graphics 5500                                                                   | 23        | 3.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 3.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 3.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 2.53%   |
| Intel HD Graphics 620                                                                    | 15        | 2.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 2.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 2.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 2.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 2.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 1.9%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 12        | 1.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 10        | 1.58%   |
| Intel HD Graphics 530                                                                    | 10        | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.58%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.42%   |
| Intel HD Graphics 630                                                                    | 7         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.95%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.79%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 5         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.79%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.63%   |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.47%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 3         | 0.47%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.47%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.47%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 0.47%   |
| Intel HD Graphics 500                                                                    | 3         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 303       | 55.29%  |
| 1 x AMD        | 75        | 13.69%  |
| Intel + Nvidia | 57        | 10.4%   |
| 2 x Intel      | 37        | 6.75%   |
| 1 x Nvidia     | 31        | 5.66%   |
| Other          | 19        | 3.47%   |
| Intel + AMD    | 13        | 2.37%   |
| AMD + Nvidia   | 7         | 1.28%   |
| 2 x AMD        | 5         | 0.91%   |
| 1 x SiS        | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 476       | 86.86%  |
| Proprietary | 37        | 6.75%   |
| Unknown     | 35        | 6.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 481       | 86.67%  |
| 0.01-0.5   | 33        | 5.95%   |
| 1.01-2.0   | 16        | 2.88%   |
| 3.01-4.0   | 9         | 1.62%   |
| 0.51-1.0   | 8         | 1.44%   |
| 5.01-6.0   | 6         | 1.08%   |
| 7.01-8.0   | 1         | 0.18%   |
| 2.01-3.0   | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 73        | 18.62%  |
| LG Display              | 70        | 17.86%  |
| BOE                     | 54        | 13.78%  |
| Chimei Innolux          | 42        | 10.71%  |
| Samsung Electronics     | 39        | 9.95%   |
| Lenovo                  | 24        | 6.12%   |
| Apple                   | 16        | 4.08%   |
| Sharp                   | 8         | 2.04%   |
| Chi Mei Optoelectronics | 8         | 2.04%   |
| InfoVision              | 5         | 1.28%   |
| Hewlett-Packard         | 5         | 1.28%   |
| Dell                    | 5         | 1.28%   |
| Sceptre Tech            | 4         | 1.02%   |
| LGD                     | 3         | 0.77%   |
| BenQ                    | 3         | 0.77%   |
| Ancor Communications    | 3         | 0.77%   |
| Vizio                   | 2         | 0.51%   |
| LG Philips              | 2         | 0.51%   |
| IBM                     | 2         | 0.51%   |
| HannStar                | 2         | 0.51%   |
| AOC                     | 2         | 0.51%   |
| Acer                    | 2         | 0.51%   |
| Toshiba                 | 1         | 0.26%   |
| Tech Concepts           | 1         | 0.26%   |
| Sony                    | 1         | 0.26%   |
| Seiko/Epson             | 1         | 0.26%   |
| Quanta Display          | 1         | 0.26%   |
| PANDA                   | 1         | 0.26%   |
| Panasonic               | 1         | 0.26%   |
| LG Electronics          | 1         | 0.26%   |
| Lenovo Group Limited    | 1         | 0.26%   |
| HJW                     | 1         | 0.26%   |
| Goldstar                | 1         | 0.26%   |
| CTO                     | 1         | 0.26%   |
| CSO                     | 1         | 0.26%   |
| BOE Technology Group    | 1         | 0.26%   |
| ASUSTek Computer        | 1         | 0.26%   |
| Aosiman                 | 1         | 0.26%   |
| AGO                     | 1         | 0.26%   |
| Unknown                 | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 7         | 1.78%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                    | 7         | 1.78%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 5         | 1.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch     | 4         | 1.02%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 4         | 1.02%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 4         | 1.02%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 4         | 1.02%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch           | 3         | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 3         | 0.76%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 3         | 0.76%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 3         | 0.76%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 3         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 3         | 0.76%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                     | 3         | 0.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch           | 3         | 0.76%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 3         | 0.76%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch           | 3         | 0.76%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3157 1440x900 330x210mm 15.4-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch    | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch    | 2         | 0.51%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch              | 2         | 0.51%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch              | 2         | 0.51%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch              | 2         | 0.51%   |
| InfoVision LCD Monitor IVO048E 1366x768 260x140mm 11.6-inch              | 2         | 0.51%   |
| InfoVision LCD Monitor IVO0489 1366x768 260x140mm 11.6-inch              | 2         | 0.51%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                    | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 2         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 2         | 0.51%   |
| BOE LCD Monitor BOE0731 1366x768 260x140mm 11.6-inch                     | 2         | 0.51%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 2         | 0.51%   |
| BOE LCD Monitor BOE06CB 1920x1080 340x190mm 15.3-inch                    | 2         | 0.51%   |
| BOE LCD Monitor BOE0630 1920x1080 340x190mm 15.3-inch                    | 2         | 0.51%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 129       | 33.51%  |
| 1920x1080 (FHD)    | 123       | 31.95%  |
| 1600x900 (HD+)     | 27        | 7.01%   |
| 1280x800 (WXGA)    | 24        | 6.23%   |
| 3840x2160 (4K)     | 13        | 3.38%   |
| 2560x1440 (QHD)    | 13        | 3.38%   |
| 1920x1200 (WUXGA)  | 9         | 2.34%   |
| 2256x1504          | 7         | 1.82%   |
| 1440x900 (WXGA+)   | 7         | 1.82%   |
| 2560x1080          | 4         | 1.04%   |
| 1024x600           | 4         | 1.04%   |
| 3200x1800 (QHD+)   | 3         | 0.78%   |
| 2560x1600          | 3         | 0.78%   |
| 1680x1050 (WSXGA+) | 3         | 0.78%   |
| 3440x1440          | 2         | 0.52%   |
| 1280x1024 (SXGA)   | 2         | 0.52%   |
| 1024x768 (XGA)     | 2         | 0.52%   |
| Unknown            | 2         | 0.52%   |
| 7040x1440          | 1         | 0.26%   |
| 5760x2160          | 1         | 0.26%   |
| 4480x1080          | 1         | 0.26%   |
| 3840x1600          | 1         | 0.26%   |
| 1400x1050          | 1         | 0.26%   |
| 1360x768           | 1         | 0.26%   |
| 1280x854           | 1         | 0.26%   |
| 1280x768           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 136       | 35.05%  |
| 13      | 117       | 30.15%  |
| 12      | 29        | 7.47%   |
| 11      | 23        | 5.93%   |
| 17      | 19        | 4.9%    |
| 14      | 16        | 4.12%   |
| 27      | 10        | 2.58%   |
| Unknown | 8         | 2.06%   |
| 24      | 6         | 1.55%   |
| 29      | 3         | 0.77%   |
| 23      | 3         | 0.77%   |
| 19      | 3         | 0.77%   |
| 64      | 2         | 0.52%   |
| 34      | 2         | 0.52%   |
| 31      | 2         | 0.52%   |
| 26      | 2         | 0.52%   |
| 10      | 2         | 0.52%   |
| 37      | 1         | 0.26%   |
| 35      | 1         | 0.26%   |
| 16      | 1         | 0.26%   |
| 9       | 1         | 0.26%   |
| 8       | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 218       | 56.33%  |
| 201-300     | 106       | 27.39%  |
| 351-400     | 20        | 5.17%   |
| 501-600     | 19        | 4.91%   |
| Unknown     | 8         | 2.07%   |
| 601-700     | 6         | 1.55%   |
| 801-900     | 2         | 0.52%   |
| 701-800     | 2         | 0.52%   |
| 401-500     | 2         | 0.52%   |
| 101-200     | 2         | 0.52%   |
| 1001-1500   | 2         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 289       | 78.53%  |
| 16/10   | 43        | 11.68%  |
| 3/2     | 14        | 3.8%    |
| Unknown | 8         | 2.17%   |
| 21/9    | 7         | 1.9%    |
| 4/3     | 4         | 1.09%   |
| 5/4     | 2         | 0.54%   |
| 6/5     | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 116       | 29.82%  |
| 91-100         | 103       | 26.48%  |
| 101-110        | 33        | 8.48%   |
| 61-70          | 30        | 7.71%   |
| 51-60          | 22        | 5.66%   |
| 121-130        | 16        | 4.11%   |
| 71-80          | 14        | 3.6%    |
| 301-350        | 14        | 3.6%    |
| 201-250        | 8         | 2.06%   |
| Unknown        | 8         | 2.06%   |
| 351-500        | 5         | 1.29%   |
| 111-120        | 4         | 1.03%   |
| 151-200        | 3         | 0.77%   |
| 131-140        | 3         | 0.77%   |
| More than 1000 | 2         | 0.51%   |
| 41-50          | 2         | 0.51%   |
| 1-40           | 2         | 0.51%   |
| 251-300        | 2         | 0.51%   |
| 141-150        | 1         | 0.26%   |
| 501-1000       | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 171       | 44.19%  |
| 101-120       | 120       | 31.01%  |
| 51-100        | 41        | 10.59%  |
| 161-240       | 34        | 8.79%   |
| More than 240 | 13        | 3.36%   |
| Unknown       | 8         | 2.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 377       | 67.93%  |
| 0     | 142       | 25.59%  |
| 2     | 34        | 6.13%   |
| 4     | 1         | 0.18%   |
| 3     | 1         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 386       | 47.6%   |
| Realtek Semiconductor            | 200       | 24.66%  |
| Qualcomm Atheros                 | 77        | 9.49%   |
| Broadcom                         | 63        | 7.77%   |
| AMD                              | 20        | 2.47%   |
| Edimax Technology                | 10        | 1.23%   |
| TP-Link                          | 7         | 0.86%   |
| Marvell Technology Group         | 7         | 0.86%   |
| Ralink                           | 5         | 0.62%   |
| NetGear                          | 5         | 0.62%   |
| Google                           | 5         | 0.62%   |
| Ralink Technology                | 4         | 0.49%   |
| Nvidia                           | 3         | 0.37%   |
| Sierra Wireless                  | 2         | 0.25%   |
| Novatel Wireless                 | 2         | 0.25%   |
| MediaTek                         | 2         | 0.25%   |
| ASUSTek Computer                 | 2         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| Samsung Electronics              | 1         | 0.12%   |
| Qualcomm                         | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| Kinesis                          | 1         | 0.12%   |
| dog hunter                       | 1         | 0.12%   |
| Dell                             | 1         | 0.12%   |
| D-Link System                    | 1         | 0.12%   |
| D-Link                           | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 123       | 11.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 54        | 5.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 43        | 4.05%   |
| Intel Wireless 7260                                                    | 35        | 3.29%   |
| Intel Wireless 8265 / 8275                                             | 34        | 3.2%    |
| Intel Wireless 8260                                                    | 25        | 2.35%   |
| Intel Wi-Fi 6 AX200                                                    | 24        | 2.26%   |
| Intel Wireless 7265                                                    | 23        | 2.16%   |
| Intel I210 Gigabit Network Connection                                  | 19        | 1.79%   |
| AMD XGMAC 10GbE Controller                                             | 19        | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 1.13%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.13%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 1.13%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 1.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 11        | 1.03%   |
| Intel Wireless 3165                                                    | 11        | 1.03%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 11        | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 10        | 0.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 10        | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 10        | 0.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 10        | 0.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 10        | 0.94%   |
| Intel Wireless 3160                                                    | 9         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 0.85%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 9         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                               | 9         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 8         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 8         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.66%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 7         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 339       | 61.08%  |
| Qualcomm Atheros      | 65        | 11.71%  |
| Realtek Semiconductor | 62        | 11.17%  |
| Broadcom              | 50        | 9.01%   |
| Edimax Technology     | 10        | 1.8%    |
| TP-Link               | 7         | 1.26%   |
| Ralink                | 5         | 0.9%    |
| NetGear               | 5         | 0.9%    |
| Ralink Technology     | 4         | 0.72%   |
| MediaTek              | 2         | 0.36%   |
| ASUSTek Computer      | 2         | 0.36%   |
| Sierra Wireless       | 1         | 0.18%   |
| Dell                  | 1         | 0.18%   |
| D-Link System         | 1         | 0.18%   |
| D-Link                | 1         | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 7.65%   |
| Intel Wireless 7260                                                     | 35        | 6.23%   |
| Intel Wireless 8265 / 8275                                              | 34        | 6.05%   |
| Intel Wireless 8260                                                     | 25        | 4.45%   |
| Intel Wi-Fi 6 AX200                                                     | 24        | 4.27%   |
| Intel Wireless 7265                                                     | 23        | 4.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 2.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 2.14%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 2.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 1.96%   |
| Intel Wireless 3165                                                     | 11        | 1.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 11        | 1.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 1.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 10        | 1.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 10        | 1.78%   |
| Intel Wireless 3160                                                     | 9         | 1.6%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 9         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.42%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.07%   |
| Intel WiFi Link 5100                                                    | 6         | 1.07%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.07%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 5         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.89%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 5         | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.89%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.89%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 4         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 218       | 45.42%  |
| Realtek Semiconductor            | 172       | 35.83%  |
| Broadcom                         | 34        | 7.08%   |
| AMD                              | 19        | 3.96%   |
| Qualcomm Atheros                 | 18        | 3.75%   |
| Marvell Technology Group         | 7         | 1.46%   |
| Nvidia                           | 3         | 0.63%   |
| Novatel Wireless                 | 2         | 0.42%   |
| Google                           | 2         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Samsung Electronics              | 1         | 0.21%   |
| Qualcomm                         | 1         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.21%   |
| Lenovo                           | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 123       | 25.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 54        | 11.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 43        | 8.88%   |
| Intel I210 Gigabit Network Connection                                  | 19        | 3.93%   |
| AMD XGMAC 10GbE Controller                                             | 19        | 3.93%   |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 3.51%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 2.48%   |
| Intel 82577LM Gigabit Network Connection                               | 12        | 2.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 2.27%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 1.86%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 1.86%   |
| Intel 82566MM Gigabit Network Connection                               | 9         | 1.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 1.86%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 1.45%   |
| Intel Ethernet Connection I219-V                                       | 5         | 1.03%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.83%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 4         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.62%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.62%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 3         | 0.62%   |
| Intel 82573L Gigabit Ethernet Controller                               | 3         | 0.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 3         | 0.62%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 3         | 0.62%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2         | 0.41%   |
| Novatel Wireless USB800 RNDIS Control RNDIS Ethernet Data              | 2         | 0.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 2         | 0.41%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                                   | 2         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 507       | 52.05%  |
| Ethernet | 450       | 46.2%   |
| Modem    | 10        | 1.03%   |
| Unknown  | 7         | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 363       | 53.94%  |
| Ethernet | 310       | 46.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 396       | 72.53%  |
| 1     | 107       | 19.6%   |
| 6     | 18        | 3.3%    |
| 3     | 17        | 3.11%   |
| 5     | 4         | 0.73%   |
| 0     | 4         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 499       | 89.75%  |
| Yes  | 57        | 10.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 217       | 58.49%  |
| Broadcom                        | 45        | 12.13%  |
| Apple                           | 30        | 8.09%   |
| Realtek Semiconductor           | 22        | 5.93%   |
| Qualcomm Atheros Communications | 16        | 4.31%   |
| IMC Networks                    | 13        | 3.5%    |
| Dell                            | 9         | 2.43%   |
| Foxconn / Hon Hai               | 8         | 2.16%   |
| Alps Electric                   | 4         | 1.08%   |
| Lite-On Technology              | 2         | 0.54%   |
| Taiyo Yuden                     | 1         | 0.27%   |
| Ralink                          | 1         | 0.27%   |
| Hewlett-Packard                 | 1         | 0.27%   |
| Esel International              | 1         | 0.27%   |
| ASUSTek Computer                | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 109       | 29.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 26        | 6.97%   |
| Intel AX201 Bluetooth                                       | 25        | 6.7%    |
| Intel AX200 Bluetooth                                       | 23        | 6.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 17        | 4.56%   |
| Apple Bluetooth Host Controller                             | 14        | 3.75%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 12        | 3.22%   |
| Realtek  Bluetooth 4.2 Adapter                              | 9         | 2.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 9         | 2.41%   |
| Intel AX210 Bluetooth                                       | 9         | 2.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 8         | 2.14%   |
| Intel AX211 Bluetooth                                       | 7         | 1.88%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 7         | 1.88%   |
| Apple Broadcom Built-in Bluetooth                           | 7         | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 6         | 1.61%   |
| IMC Networks Realtek Bluetooth Adapter                      | 6         | 1.61%   |
| Apple Built-in iSight (no firmware loaded)                  | 6         | 1.61%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 1.34%   |
| Dell DW375 Bluetooth Module                                 | 5         | 1.34%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.8%    |
| Realtek Bluetooth Adapter                                   | 3         | 0.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 3         | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 3         | 0.8%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.54%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.54%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 0.54%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 0.54%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 2         | 0.54%   |
| IMC Networks Bluetooth module                               | 2         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 2         | 0.54%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 0.54%   |
| Alps Electric BCM2046 Bluetooth Device                      | 2         | 0.54%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                     | 1         | 0.27%   |
| Realtek Wireless Bluetooth Adapter                          | 1         | 0.27%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.27%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE                 | 1         | 0.27%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.27%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 442       | 72.34%  |
| AMD                              | 104       | 17.02%  |
| Nvidia                           | 47        | 7.69%   |
| Realtek Semiconductor            | 3         | 0.49%   |
| C-Media Electronics              | 3         | 0.49%   |
| Texas Instruments                | 2         | 0.33%   |
| CMX Systems                      | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Logitech                         | 1         | 0.16%   |
| Lenovo                           | 1         | 0.16%   |
| JMTek                            | 1         | 0.16%   |
| ESS Technology                   | 1         | 0.16%   |
| Creative Technology              | 1         | 0.16%   |
| Cambridge Silicon Radio          | 1         | 0.16%   |
| Blue Microphones                 | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 63        | 8.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 56        | 7.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 42        | 5.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 28        | 3.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 3.65%   |
| Intel Broadwell-U Audio Controller                                                                | 27        | 3.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 3.38%   |
| Intel 8 Series HD Audio Controller                                                                | 24        | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 2.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 20        | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 2.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 2.3%    |
| AMD FCH Azalia Controller                                                                         | 17        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 2.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 1.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 1.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 1.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 1.22%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.81%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.54%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 167       | 27.97%  |
| SK hynix            | 135       | 22.61%  |
| Micron Technology   | 64        | 10.72%  |
| Crucial             | 44        | 7.37%   |
| Unknown             | 36        | 6.03%   |
| Kingston            | 22        | 3.69%   |
| Transcend           | 20        | 3.35%   |
| Elpida              | 16        | 2.68%   |
| Unknown             | 15        | 2.51%   |
| Ramaxel Technology  | 12        | 2.01%   |
| Nanya Technology    | 9         | 1.51%   |
| A-DATA Technology   | 9         | 1.51%   |
| G.Skill             | 8         | 1.34%   |
| PNY                 | 7         | 1.17%   |
| Avant               | 5         | 0.84%   |
| Team                | 4         | 0.67%   |
| Unknown (ABCD)      | 3         | 0.5%    |
| Goldkey             | 3         | 0.5%    |
| Corsair             | 3         | 0.5%    |
| Super Talent        | 2         | 0.34%   |
| Sesame              | 2         | 0.34%   |
| Timetec             | 1         | 0.17%   |
| Swissbit            | 1         | 0.17%   |
| Silicon Power       | 1         | 0.17%   |
| PKI/Kingston        | 1         | 0.17%   |
| Patriot             | 1         | 0.17%   |
| Neo Forza           | 1         | 0.17%   |
| Golden Empire       | 1         | 0.17%   |
| Gold Key            | 1         | 0.17%   |
| Apacer              | 1         | 0.17%   |
| 4ea5                | 1         | 0.17%   |
| 09490000802C        | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 2.33%   |
| Unknown                                                          | 15        | 2.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 8         | 1.24%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 1.24%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 1.09%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 7         | 1.09%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 1.09%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.09%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.93%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 6         | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.93%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 6         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 5         | 0.78%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s              | 5         | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.78%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.78%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 4         | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 4         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.62%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.62%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 4         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 3         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.47%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 3         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.47%   |
| Transcend RAM TS1GLH64V6B 8GB SODIMM DDR4 1333MT/s               | 3         | 0.47%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.47%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.47%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s          | 3         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 231       | 46.86%  |
| DDR4    | 180       | 36.51%  |
| DDR2    | 36        | 7.3%    |
| LPDDR4  | 13        | 2.64%   |
| LPDDR3  | 11        | 2.23%   |
| DDR5    | 6         | 1.22%   |
| DDR     | 6         | 1.22%   |
| LPDDR5  | 5         | 1.01%   |
| SDRAM   | 2         | 0.41%   |
| Unknown | 2         | 0.41%   |
| SRAM    | 1         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 460       | 92.18%  |
| Row Of Chips | 22        | 4.41%   |
| Chip         | 10        | 2%      |
| Unknown      | 6         | 1.2%    |
| DIMM         | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 208       | 37.01%  |
| 4096  | 173       | 30.78%  |
| 2048  | 87        | 15.48%  |
| 16384 | 54        | 9.61%   |
| 1024  | 22        | 3.91%   |
| 32768 | 15        | 2.67%   |
| 512   | 2         | 0.36%   |
| 256   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 140       | 25.5%   |
| 2667    | 81        | 14.75%  |
| 1333    | 64        | 11.66%  |
| 2400    | 49        | 8.93%   |
| 3200    | 41        | 7.47%   |
| 1334    | 36        | 6.56%   |
| 2133    | 32        | 5.83%   |
| 667     | 24        | 4.37%   |
| 1067    | 14        | 2.55%   |
| 1867    | 12        | 2.19%   |
| Unknown | 10        | 1.82%   |
| 800     | 7         | 1.28%   |
| 4267    | 6         | 1.09%   |
| 4800    | 5         | 0.91%   |
| 533     | 5         | 0.91%   |
| 975     | 4         | 0.73%   |
| 6400    | 3         | 0.55%   |
| 4266    | 3         | 0.55%   |
| 3733    | 3         | 0.55%   |
| 1200    | 3         | 0.55%   |
| 5600    | 1         | 0.18%   |
| 2666    | 1         | 0.18%   |
| 2048    | 1         | 0.18%   |
| 1596    | 1         | 0.18%   |
| 1066    | 1         | 0.18%   |
| 200     | 1         | 0.18%   |
| 166     | 1         | 0.18%   |

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
| Chicony Electronics                    | 97        | 26.58%  |
| Bison Electronics                      | 50        | 13.7%   |
| Microdia                               | 33        | 9.04%   |
| Realtek Semiconductor                  | 32        | 8.77%   |
| Sunplus Innovation Technology          | 28        | 7.67%   |
| IMC Networks                           | 27        | 7.4%    |
| Apple                                  | 12        | 3.29%   |
| Quanta                                 | 11        | 3.01%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.01%   |
| Suyin                                  | 10        | 2.74%   |
| Lite-On Technology                     | 10        | 2.74%   |
| Luxvisions Innotech Limited            | 8         | 2.19%   |
| Syntek                                 | 6         | 1.64%   |
| Lenovo                                 | 5         | 1.37%   |
| Importek                               | 4         | 1.1%    |
| Primax Electronics                     | 3         | 0.82%   |
| Alcor Micro                            | 3         | 0.82%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.55%   |
| Ricoh                                  | 2         | 0.55%   |
| OmniVision Technologies                | 2         | 0.55%   |
| Logitech                               | 2         | 0.55%   |
| Intel                                  | 2         | 0.55%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| Supreme Electronics                    | 1         | 0.27%   |
| Silicon Motion                         | 1         | 0.27%   |
| Goodong Industry                       | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 32        | 8.7%    |
| Bison Integrated Camera                             | 27        | 7.34%   |
| Sunplus Integrated_Webcam_HD                        | 14        | 3.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 11        | 2.99%   |
| Microdia Integrated_Webcam_HD                       | 10        | 2.72%   |
| IMC Networks Integrated Camera                      | 10        | 2.72%   |
| Realtek Integrated_Webcam_HD                        | 9         | 2.45%   |
| Microdia Integrated Webcam                          | 9         | 2.45%   |
| Apple FaceTime HD Camera                            | 9         | 2.45%   |
| Realtek USB 2.0 PC Camera                           | 8         | 2.17%   |
| Chicony Integrated Camera (1280x720@30)             | 8         | 2.17%   |
| Lite-On Integrated Camera                           | 7         | 1.9%    |
| Chicony Integrated Camera [ThinkPad]                | 7         | 1.9%    |
| Bison ThinkPad Integrated Camera                    | 6         | 1.63%   |
| Bison SunplusIT Integrated Camera                   | 5         | 1.36%   |
| Suyin Integrated_Webcam_HD                          | 4         | 1.09%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 1.09%   |
| Quanta HP TrueVision HD Camera                      | 4         | 1.09%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 1.09%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 1.09%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 1.09%   |
| IMC Networks Realtek PC Camera                      | 4         | 1.09%   |
| Chicony Integrated IR Camera                        | 4         | 1.09%   |
| Chicony HP TrueVision HD Camera                     | 4         | 1.09%   |
| Chicony HD WebCam                                   | 4         | 1.09%   |
| Bison Lenovo Integrated Webcam                      | 4         | 1.09%   |
| Syntek EasyCamera                                   | 3         | 0.82%   |
| Sunplus HD WebCam                                   | 3         | 0.82%   |
| Realtek Laptop Camera                               | 3         | 0.82%   |
| Realtek Integrated Webcam HD                        | 3         | 0.82%   |
| Quanta HP Webcam                                    | 3         | 0.82%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.82%   |
| IMC Networks EasyCamera                             | 3         | 0.82%   |
| Chicony thinkpad t430s camera                       | 3         | 0.82%   |
| Chicony Chicony USB2.0 Camera                       | 3         | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.82%   |
| Syntek Lenovo EasyCamera                            | 2         | 0.54%   |
| Sunplus Dell E5570 integrated webcam                | 2         | 0.54%   |
| Realtek USB Camera                                  | 2         | 0.54%   |
| Realtek USB 2.0 Webcam                              | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 34        | 33.33%  |
| Synaptics                  | 21        | 20.59%  |
| Upek                       | 14        | 13.73%  |
| STMicroelectronics         | 12        | 11.76%  |
| Shenzhen Goodix Technology | 7         | 6.86%   |
| AuthenTec                  | 7         | 6.86%   |
| Elan Microelectronics      | 2         | 1.96%   |
| Broadcom                   | 2         | 1.96%   |
| Samsung Electronics        | 1         | 0.98%   |
| LighTuning Technology      | 1         | 0.98%   |
| FocalTech Systems          | 1         | 0.98%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 17        | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 14        | 13.73%  |
| STMicroelectronics Fingerprint Reader                                        | 12        | 11.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 10        | 9.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 10        | 9.8%    |
| Shenzhen Goodix Fingerprint Reader                                           | 6         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 5         | 4.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 2.94%   |
| Validity Sensors Synaptics WBDI                                              | 3         | 2.94%   |
| AuthenTec AES2810                                                            | 3         | 2.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 1.96%   |
| Elan Fingerprint Sensor                                                      | 2         | 1.96%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 1.96%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 1.96%   |
| AuthenTec AES1660                                                            | 2         | 1.96%   |
| Validity Sensors VFS491                                                      | 1         | 0.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 0.98%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.98%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.98%   |
| Synaptics WBDI                                                               | 1         | 0.98%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 0.98%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 0.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 0.98%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 0.98%   |

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
| 2     | 177       | 31.05%  |
| 1     | 172       | 30.18%  |
| 3     | 92        | 16.14%  |
| 0     | 82        | 14.39%  |
| 4     | 34        | 5.96%   |
| 5     | 10        | 1.75%   |
| 6     | 3         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 375       | 42.86%  |
| Bluetooth                | 143       | 16.34%  |
| Net/wireless             | 95        | 10.86%  |
| Fingerprint reader       | 86        | 9.83%   |
| Card reader              | 81        | 9.26%   |
| Firewire controller      | 39        | 4.46%   |
| Sound                    | 14        | 1.6%    |
| Storage                  | 11        | 1.26%   |
| Graphics card            | 11        | 1.26%   |
| Modem                    | 8         | 0.91%   |
| Network                  | 5         | 0.57%   |
| Net/ethernet             | 3         | 0.34%   |
| Storage/ata              | 2         | 0.23%   |
| Storage/ide              | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |

