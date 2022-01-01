FreeBSD 13.0 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_13.0/Desktop/README.md) and [notebooks](/Dist/FreeBSD_13.0/Notebook/README.md).

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

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [7782674614](https://bsd-hardware.info/?probe=7782674614) | Dec 31, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dd62d57a45](https://bsd-hardware.info/?probe=dd62d57a45) | Dec 29, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [62f424cac5](https://bsd-hardware.info/?probe=62f424cac5) | Dec 26, 2021 |
| Lenovo        | ThinkPad X380 Yoga S1 20... | Convertible | [c27ba488aa](https://bsd-hardware.info/?probe=c27ba488aa) | Dec 18, 2021 |
| Lenovo        | ThinkPad X380 Yoga S1 20... | Convertible | [92a28500da](https://bsd-hardware.info/?probe=92a28500da) | Dec 18, 2021 |
| Intel         | NUC7JYB J67970-400          | Mini pc     | [c55f468566](https://bsd-hardware.info/?probe=c55f468566) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | Desktop     | [8a9387c5da](https://bsd-hardware.info/?probe=8a9387c5da) | Dec 11, 2021 |
| ASUSTek       | ROG Maximus X FORMULA       | Desktop     | [9762ebd7c7](https://bsd-hardware.info/?probe=9762ebd7c7) | Dec 10, 2021 |
| MSI           | H81M-P33                    | Desktop     | [237b84b5fc](https://bsd-hardware.info/?probe=237b84b5fc) | Dec 09, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [3956ad0525](https://bsd-hardware.info/?probe=3956ad0525) | Dec 09, 2021 |
| ASUSTek       | P5B                         | Desktop     | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | Desktop     | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Samsung       | 530XBB                      | Notebook    | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [540d2ef68c](https://bsd-hardware.info/?probe=540d2ef68c) | Nov 29, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [91d67ba784](https://bsd-hardware.info/?probe=91d67ba784) | Nov 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [1827cc60df](https://bsd-hardware.info/?probe=1827cc60df) | Nov 23, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [e117631726](https://bsd-hardware.info/?probe=e117631726) | Nov 22, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [0ed5f516f4](https://bsd-hardware.info/?probe=0ed5f516f4) | Nov 21, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [73774ed18e](https://bsd-hardware.info/?probe=73774ed18e) | Nov 16, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [48c39762c6](https://bsd-hardware.info/?probe=48c39762c6) | Nov 14, 2021 |
| Dell          | G15 5510                    | Notebook    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| HP            | Compaq 6720s                | Notebook    | [06e31b2e77](https://bsd-hardware.info/?probe=06e31b2e77) | Nov 09, 2021 |
| HP            | Mini 110-1000               | Notebook    | [ef66d7a110](https://bsd-hardware.info/?probe=ef66d7a110) | Nov 09, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [6c875941b3](https://bsd-hardware.info/?probe=6c875941b3) | Nov 07, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cc8c604fa6](https://bsd-hardware.info/?probe=cc8c604fa6) | Nov 03, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [19a0911df6](https://bsd-hardware.info/?probe=19a0911df6) | Oct 31, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [a33aece313](https://bsd-hardware.info/?probe=a33aece313) | Oct 24, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [e26c6a355d](https://bsd-hardware.info/?probe=e26c6a355d) | Oct 24, 2021 |
| Lenovo        | G580 26897SJ                | Notebook    | [da14095fb7](https://bsd-hardware.info/?probe=da14095fb7) | Oct 20, 2021 |
| firefly       | roc-rk3399-pc-plus          | Desktop     | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| firefly       | roc-rk3399-pc-plus          | Desktop     | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9e9b5166bc](https://bsd-hardware.info/?probe=9e9b5166bc) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [da31eaf836](https://bsd-hardware.info/?probe=da31eaf836) | Oct 17, 2021 |
| MSI           | H81M-P33                    | Desktop     | [2e84516857](https://bsd-hardware.info/?probe=2e84516857) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [6ceda5d7b4](https://bsd-hardware.info/?probe=6ceda5d7b4) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [65954adbf3](https://bsd-hardware.info/?probe=65954adbf3) | Oct 10, 2021 |
| MSI           | H81M-P33                    | Desktop     | [592dbd7c17](https://bsd-hardware.info/?probe=592dbd7c17) | Oct 10, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [00efddc7e4](https://bsd-hardware.info/?probe=00efddc7e4) | Oct 10, 2021 |
| Framework     | Laptop                      | Notebook    | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [d65e453ea7](https://bsd-hardware.info/?probe=d65e453ea7) | Oct 03, 2021 |
| MSI           | H81M-P33                    | Desktop     | [fd498893fb](https://bsd-hardware.info/?probe=fd498893fb) | Oct 03, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [0bfcd11255](https://bsd-hardware.info/?probe=0bfcd11255) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [76866f2db7](https://bsd-hardware.info/?probe=76866f2db7) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [319470ebbd](https://bsd-hardware.info/?probe=319470ebbd) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | Notebook    | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [18cd64ae96](https://bsd-hardware.info/?probe=18cd64ae96) | Sep 26, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8a8d67b8b1](https://bsd-hardware.info/?probe=8a8d67b8b1) | Sep 26, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [fb056a1840](https://bsd-hardware.info/?probe=fb056a1840) | Sep 26, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [137654a2f8](https://bsd-hardware.info/?probe=137654a2f8) | Sep 24, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| Dell          | Latitude E7450              | Notebook    | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [6b68e14399](https://bsd-hardware.info/?probe=6b68e14399) | Sep 19, 2021 |
| MSI           | H81M-P33                    | Desktop     | [60ec488627](https://bsd-hardware.info/?probe=60ec488627) | Sep 19, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [c2d07d370e](https://bsd-hardware.info/?probe=c2d07d370e) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [392cf6ec24](https://bsd-hardware.info/?probe=392cf6ec24) | Sep 17, 2021 |
| firefly       | roc-rk3399-pc-plus          | Desktop     | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| firefly       | roc-rk3399-pc-plus          | Desktop     | [d05c3ba858](https://bsd-hardware.info/?probe=d05c3ba858) | Sep 15, 2021 |
| firefly       | roc-rk3399-pc-plus          | Desktop     | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [072047d3e5](https://bsd-hardware.info/?probe=072047d3e5) | Sep 12, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [4d1aa99478](https://bsd-hardware.info/?probe=4d1aa99478) | Sep 12, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a8feb1807d](https://bsd-hardware.info/?probe=a8feb1807d) | Sep 12, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8055702eac](https://bsd-hardware.info/?probe=8055702eac) | Sep 12, 2021 |
| ASUSTek       | TP300LD                     | Notebook    | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | Notebook    | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [5933c93a5b](https://bsd-hardware.info/?probe=5933c93a5b) | Sep 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1677cb485](https://bsd-hardware.info/?probe=b1677cb485) | Sep 05, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [33392e3299](https://bsd-hardware.info/?probe=33392e3299) | Sep 05, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ad52aa4ea5](https://bsd-hardware.info/?probe=ad52aa4ea5) | Sep 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | Notebook    | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [28bf815655](https://bsd-hardware.info/?probe=28bf815655) | Aug 30, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [1d408ec8df](https://bsd-hardware.info/?probe=1d408ec8df) | Aug 29, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [37fe7a021f](https://bsd-hardware.info/?probe=37fe7a021f) | Aug 29, 2021 |
| MSI           | H81M-P33                    | Desktop     | [90f439a559](https://bsd-hardware.info/?probe=90f439a559) | Aug 29, 2021 |
| Medion        | MS-7616                     | Desktop     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | Desktop     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| HP            | 18E6                        | All in one  | [20d70ad9ba](https://bsd-hardware.info/?probe=20d70ad9ba) | Aug 26, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [0b02720fcc](https://bsd-hardware.info/?probe=0b02720fcc) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [0db2178b94](https://bsd-hardware.info/?probe=0db2178b94) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [eee5ea8171](https://bsd-hardware.info/?probe=eee5ea8171) | Aug 22, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ceb4fcb174](https://bsd-hardware.info/?probe=ceb4fcb174) | Aug 22, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9fa08ee32f](https://bsd-hardware.info/?probe=9fa08ee32f) | Aug 15, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [3f15cbe8cc](https://bsd-hardware.info/?probe=3f15cbe8cc) | Aug 15, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8a9a281ee1](https://bsd-hardware.info/?probe=8a9a281ee1) | Aug 15, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [adf41eedab](https://bsd-hardware.info/?probe=adf41eedab) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [4dd5f1c0c6](https://bsd-hardware.info/?probe=4dd5f1c0c6) | Aug 12, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [1c835c20cb](https://bsd-hardware.info/?probe=1c835c20cb) | Aug 09, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [b972923c8d](https://bsd-hardware.info/?probe=b972923c8d) | Aug 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [5ae84c8d07](https://bsd-hardware.info/?probe=5ae84c8d07) | Aug 08, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [e51135c93a](https://bsd-hardware.info/?probe=e51135c93a) | Aug 08, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [048bfd8f45](https://bsd-hardware.info/?probe=048bfd8f45) | Aug 01, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [faeca32de9](https://bsd-hardware.info/?probe=faeca32de9) | Aug 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [062450ca66](https://bsd-hardware.info/?probe=062450ca66) | Aug 01, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | Notebook    | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [692320f986](https://bsd-hardware.info/?probe=692320f986) | Jul 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [ca4e2c4a94](https://bsd-hardware.info/?probe=ca4e2c4a94) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [d6feef8717](https://bsd-hardware.info/?probe=d6feef8717) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [9a3c3705d0](https://bsd-hardware.info/?probe=9a3c3705d0) | Jul 23, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [586c14dd63](https://bsd-hardware.info/?probe=586c14dd63) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [389bf7ae4b](https://bsd-hardware.info/?probe=389bf7ae4b) | Jul 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [fc6688138c](https://bsd-hardware.info/?probe=fc6688138c) | Jul 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | Notebook    | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [0d51f6e407](https://bsd-hardware.info/?probe=0d51f6e407) | Jul 19, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [d041bb0182](https://bsd-hardware.info/?probe=d041bb0182) | Jul 18, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9cdc6262f6](https://bsd-hardware.info/?probe=9cdc6262f6) | Jul 18, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [8f8cc52f23](https://bsd-hardware.info/?probe=8f8cc52f23) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [8315a3b948](https://bsd-hardware.info/?probe=8315a3b948) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [8780a9eb26](https://bsd-hardware.info/?probe=8780a9eb26) | Jul 17, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [fb1c3af983](https://bsd-hardware.info/?probe=fb1c3af983) | Jul 16, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [9d729e0508](https://bsd-hardware.info/?probe=9d729e0508) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5038f75992](https://bsd-hardware.info/?probe=5038f75992) | Jul 13, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [d859525592](https://bsd-hardware.info/?probe=d859525592) | Jul 11, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [708d1e2608](https://bsd-hardware.info/?probe=708d1e2608) | Jul 11, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | Notebook    | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [08641f83e8](https://bsd-hardware.info/?probe=08641f83e8) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9fe5dd4b75](https://bsd-hardware.info/?probe=9fe5dd4b75) | Jul 04, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [e85afd7989](https://bsd-hardware.info/?probe=e85afd7989) | Jul 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [e24689b692](https://bsd-hardware.info/?probe=e24689b692) | Jul 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [c62837354b](https://bsd-hardware.info/?probe=c62837354b) | Jul 04, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | Notebook    | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7360fb3199](https://bsd-hardware.info/?probe=7360fb3199) | Jul 03, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [2c38eae6bc](https://bsd-hardware.info/?probe=2c38eae6bc) | Jul 02, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [c339174f12](https://bsd-hardware.info/?probe=c339174f12) | Jul 02, 2021 |
| Samsung       | NC10                        | Notebook    | [d33644912a](https://bsd-hardware.info/?probe=d33644912a) | Jun 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c1a27ca913](https://bsd-hardware.info/?probe=c1a27ca913) | Jun 27, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [1e5ccb0c3c](https://bsd-hardware.info/?probe=1e5ccb0c3c) | Jun 27, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [96d46d6f38](https://bsd-hardware.info/?probe=96d46d6f38) | Jun 27, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| Toshiba       | PORTEGE X20W-D              | Convertible | [1e5dc453f6](https://bsd-hardware.info/?probe=1e5dc453f6) | Jun 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [ac70749f81](https://bsd-hardware.info/?probe=ac70749f81) | Jun 20, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [d6c3fe4058](https://bsd-hardware.info/?probe=d6c3fe4058) | Jun 20, 2021 |
| MSI           | H81M-P33                    | Desktop     | [2a26234f71](https://bsd-hardware.info/?probe=2a26234f71) | Jun 20, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | Notebook    | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | Notebook    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | Notebook    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | 00NH4P A09                  | Server      | [1098796c5f](https://bsd-hardware.info/?probe=1098796c5f) | Jun 14, 2021 |
| Raspberry ... | rpi                         | Desktop     | [692d412c0c](https://bsd-hardware.info/?probe=692d412c0c) | Jun 14, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c066194e27](https://bsd-hardware.info/?probe=c066194e27) | Jun 13, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [197b4515ad](https://bsd-hardware.info/?probe=197b4515ad) | Jun 13, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [4af3098758](https://bsd-hardware.info/?probe=4af3098758) | Jun 13, 2021 |
| MSI           | H81M-P33                    | Desktop     | [48d5da63d6](https://bsd-hardware.info/?probe=48d5da63d6) | Jun 13, 2021 |
| Unknown       | Unknown                     | Soc         | [ce45b72607](https://bsd-hardware.info/?probe=ce45b72607) | Jun 11, 2021 |
| Dell          | Latitude E4300              | Notebook    | [1150e00893](https://bsd-hardware.info/?probe=1150e00893) | Jun 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [84abffd607](https://bsd-hardware.info/?probe=84abffd607) | Jun 06, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [65893eaa25](https://bsd-hardware.info/?probe=65893eaa25) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [54636fa78f](https://bsd-hardware.info/?probe=54636fa78f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | Notebook    | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| Sony          | SVF1421DSGW                 | Notebook    | [64f3f02018](https://bsd-hardware.info/?probe=64f3f02018) | Jun 01, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [0b3c9a332d](https://bsd-hardware.info/?probe=0b3c9a332d) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a87473149b](https://bsd-hardware.info/?probe=a87473149b) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [82d464f2a8](https://bsd-hardware.info/?probe=82d464f2a8) | May 31, 2021 |
| System76      | Gazelle                     | Notebook    | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [f8036fdef4](https://bsd-hardware.info/?probe=f8036fdef4) | May 30, 2021 |
| MSI           | H81M-P33                    | Desktop     | [9ff6febdba](https://bsd-hardware.info/?probe=9ff6febdba) | May 30, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [aabcf92dd5](https://bsd-hardware.info/?probe=aabcf92dd5) | May 30, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [84a1925fc9](https://bsd-hardware.info/?probe=84a1925fc9) | May 29, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [331da3091c](https://bsd-hardware.info/?probe=331da3091c) | May 28, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [337a8b5a3d](https://bsd-hardware.info/?probe=337a8b5a3d) | May 28, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [20052b0d55](https://bsd-hardware.info/?probe=20052b0d55) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [2247c7130f](https://bsd-hardware.info/?probe=2247c7130f) | May 26, 2021 |
| HP            | 1790                        | Desktop     | [59e472fb01](https://bsd-hardware.info/?probe=59e472fb01) | May 24, 2021 |
| Lenovo        | ThinkPad X220 4291PU5       | Notebook    | [c6d626c350](https://bsd-hardware.info/?probe=c6d626c350) | May 24, 2021 |
| HP            | 1790                        | Desktop     | [3a4e33eb4d](https://bsd-hardware.info/?probe=3a4e33eb4d) | May 24, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| ASUSTek       | 1015PX                      | Notebook    | [c6e717c1e9](https://bsd-hardware.info/?probe=c6e717c1e9) | May 24, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [f035aab141](https://bsd-hardware.info/?probe=f035aab141) | May 24, 2021 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [4d15a3ffe3](https://bsd-hardware.info/?probe=4d15a3ffe3) | May 23, 2021 |
| Dell          | Latitude D620               | Notebook    | [1bd280a155](https://bsd-hardware.info/?probe=1bd280a155) | May 23, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [951c3e534c](https://bsd-hardware.info/?probe=951c3e534c) | May 23, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [d76f0d88b2](https://bsd-hardware.info/?probe=d76f0d88b2) | May 23, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9589f37f30](https://bsd-hardware.info/?probe=9589f37f30) | May 23, 2021 |
| MSI           | H81M-P33                    | Desktop     | [67ce92aee6](https://bsd-hardware.info/?probe=67ce92aee6) | May 23, 2021 |
| MSI           | H61I-E35/W8                 | Desktop     | [d07ad10827](https://bsd-hardware.info/?probe=d07ad10827) | May 22, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [80cf566074](https://bsd-hardware.info/?probe=80cf566074) | May 21, 2021 |
| Notebook      | N7x0WU                      | Notebook    | [70760365d0](https://bsd-hardware.info/?probe=70760365d0) | May 20, 2021 |
| Dell          | Latitude E6410              | Notebook    | [c0115917d2](https://bsd-hardware.info/?probe=c0115917d2) | May 19, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [89ca4554ca](https://bsd-hardware.info/?probe=89ca4554ca) | May 18, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [c9218ee21d](https://bsd-hardware.info/?probe=c9218ee21d) | May 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [3d35e6b890](https://bsd-hardware.info/?probe=3d35e6b890) | May 16, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [9e4c7bf061](https://bsd-hardware.info/?probe=9e4c7bf061) | May 16, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3f3f826118](https://bsd-hardware.info/?probe=3f3f826118) | May 16, 2021 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [a40e426983](https://bsd-hardware.info/?probe=a40e426983) | May 15, 2021 |
| Dell          | Latitude E5550              | Notebook    | [dca8ba9d37](https://bsd-hardware.info/?probe=dca8ba9d37) | May 13, 2021 |
| ASUSTek       | G750JM                      | Notebook    | [37be4ea27a](https://bsd-hardware.info/?probe=37be4ea27a) | May 13, 2021 |
| Lenovo        | 1037 NO DPK                 | Server      | [ffaa30bc08](https://bsd-hardware.info/?probe=ffaa30bc08) | May 12, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [0ab44e95df](https://bsd-hardware.info/?probe=0ab44e95df) | May 12, 2021 |
| EVGA          | X299 FTW K                  | Desktop     | [c4862c598a](https://bsd-hardware.info/?probe=c4862c598a) | May 11, 2021 |
| HP            | ProLiant BL460c G6          | Server      | [2b539fcf18](https://bsd-hardware.info/?probe=2b539fcf18) | May 11, 2021 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | Desktop     | [a9a897258e](https://bsd-hardware.info/?probe=a9a897258e) | May 11, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8d78068ca7](https://bsd-hardware.info/?probe=8d78068ca7) | May 09, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [add2c1bcba](https://bsd-hardware.info/?probe=add2c1bcba) | May 09, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [dfb015cf64](https://bsd-hardware.info/?probe=dfb015cf64) | May 09, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [cbfba11dfe](https://bsd-hardware.info/?probe=cbfba11dfe) | May 09, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6a9b635e7c](https://bsd-hardware.info/?probe=6a9b635e7c) | May 09, 2021 |
| Shuttle       | FH87                        | Desktop     | [bf5457ff02](https://bsd-hardware.info/?probe=bf5457ff02) | May 09, 2021 |
| Acer          | Predator PH517-61           | Notebook    | [9e03a76684](https://bsd-hardware.info/?probe=9e03a76684) | May 08, 2021 |
| Dell          | Latitude 5500               | Notebook    | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Toshiba       | TECRA M11                   | Notebook    | [6357d0d51f](https://bsd-hardware.info/?probe=6357d0d51f) | May 08, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [10af242f8b](https://bsd-hardware.info/?probe=10af242f8b) | May 07, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [b0b4ca9f27](https://bsd-hardware.info/?probe=b0b4ca9f27) | May 07, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [d5adf152a7](https://bsd-hardware.info/?probe=d5adf152a7) | May 05, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASRock        | Z170M Extreme4              | Desktop     | [e2d2bb7f28](https://bsd-hardware.info/?probe=e2d2bb7f28) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [4d7013aeab](https://bsd-hardware.info/?probe=4d7013aeab) | May 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [cbbf4f86cd](https://bsd-hardware.info/?probe=cbbf4f86cd) | May 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [7fc73d2db3](https://bsd-hardware.info/?probe=7fc73d2db3) | May 03, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [87c4175f48](https://bsd-hardware.info/?probe=87c4175f48) | May 03, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [ce8d45af17](https://bsd-hardware.info/?probe=ce8d45af17) | May 03, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7b8ebcef12](https://bsd-hardware.info/?probe=7b8ebcef12) | May 02, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7033f42e70](https://bsd-hardware.info/?probe=7033f42e70) | May 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [96111749b8](https://bsd-hardware.info/?probe=96111749b8) | May 02, 2021 |
| Lenovo        | ThinkPad T440p 20AW0049L... | Notebook    | [7660f9b6db](https://bsd-hardware.info/?probe=7660f9b6db) | May 02, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [d8ecc7077a](https://bsd-hardware.info/?probe=d8ecc7077a) | May 02, 2021 |
| GVC           | DR 738                      | Desktop     | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [2713d38658](https://bsd-hardware.info/?probe=2713d38658) | May 01, 2021 |
| Beckhoff A... | CB3056 G4                   | Desktop     | [120665d4d3](https://bsd-hardware.info/?probe=120665d4d3) | Apr 30, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [1653ea52ce](https://bsd-hardware.info/?probe=1653ea52ce) | Apr 29, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [14cf64712f](https://bsd-hardware.info/?probe=14cf64712f) | Apr 29, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [6ec28a973a](https://bsd-hardware.info/?probe=6ec28a973a) | Apr 28, 2021 |
| Dell          | Latitude E5420              | Notebook    | [32f03aa888](https://bsd-hardware.info/?probe=32f03aa888) | Apr 27, 2021 |
| Dell          | Latitude E5420              | Notebook    | [4b4cd45ac7](https://bsd-hardware.info/?probe=4b4cd45ac7) | Apr 26, 2021 |
| Dell          | Latitude E5420              | Notebook    | [6457b99e73](https://bsd-hardware.info/?probe=6457b99e73) | Apr 26, 2021 |
| Dell          | Precision 5510              | Notebook    | [063d746a48](https://bsd-hardware.info/?probe=063d746a48) | Apr 25, 2021 |
| Dell          | Precision 5510              | Notebook    | [6bb3b7aa11](https://bsd-hardware.info/?probe=6bb3b7aa11) | Apr 25, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [258ef16ace](https://bsd-hardware.info/?probe=258ef16ace) | Apr 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [39d9a85a18](https://bsd-hardware.info/?probe=39d9a85a18) | Apr 25, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e0660a37f5](https://bsd-hardware.info/?probe=e0660a37f5) | Apr 25, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [1ee72db86e](https://bsd-hardware.info/?probe=1ee72db86e) | Apr 25, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [c784e7b290](https://bsd-hardware.info/?probe=c784e7b290) | Apr 25, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [9a0602d408](https://bsd-hardware.info/?probe=9a0602d408) | Apr 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [2939c4cb17](https://bsd-hardware.info/?probe=2939c4cb17) | Apr 24, 2021 |
| Lenovo        | ThinkPad E14 20RAS0F600     | Notebook    | [94d082c57c](https://bsd-hardware.info/?probe=94d082c57c) | Apr 24, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [4f4a6b1ab0](https://bsd-hardware.info/?probe=4f4a6b1ab0) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [9cf9861053](https://bsd-hardware.info/?probe=9cf9861053) | Apr 23, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [5de4060089](https://bsd-hardware.info/?probe=5de4060089) | Apr 23, 2021 |
| Dell          | Precision 5520              | Notebook    | [7d5f7b5033](https://bsd-hardware.info/?probe=7d5f7b5033) | Apr 23, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [94b2e5d5ff](https://bsd-hardware.info/?probe=94b2e5d5ff) | Apr 23, 2021 |
| Alienware     | M15x                        | Notebook    | [0b60c1cb25](https://bsd-hardware.info/?probe=0b60c1cb25) | Apr 22, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Lenovo        | ThinkPad Edge E320 1298R... | Notebook    | [6a96e2c5b1](https://bsd-hardware.info/?probe=6a96e2c5b1) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [7c7573eb45](https://bsd-hardware.info/?probe=7c7573eb45) | Apr 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6251043541](https://bsd-hardware.info/?probe=6251043541) | Apr 22, 2021 |
| Lenovo        | ThinkPad X270 20HMS0NS00    | Notebook    | [72fb01f474](https://bsd-hardware.info/?probe=72fb01f474) | Apr 22, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a932c6d687](https://bsd-hardware.info/?probe=a932c6d687) | Apr 21, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [92d895d2d4](https://bsd-hardware.info/?probe=92d895d2d4) | Apr 21, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [66eee76b50](https://bsd-hardware.info/?probe=66eee76b50) | Apr 21, 2021 |
| HP            | 8430 1000                   | All in one  | [0d21e083f4](https://bsd-hardware.info/?probe=0d21e083f4) | Apr 20, 2021 |
| Dell          | Latitude 5580               | Notebook    | [f967516613](https://bsd-hardware.info/?probe=f967516613) | Apr 20, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [c98cb0e438](https://bsd-hardware.info/?probe=c98cb0e438) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [3a656ded12](https://bsd-hardware.info/?probe=3a656ded12) | Apr 19, 2021 |
| Dell          | Latitude E6440              | Notebook    | [68f57531cb](https://bsd-hardware.info/?probe=68f57531cb) | Apr 19, 2021 |
| System76      | Lemur Pro                   | Notebook    | [0bd96ef663](https://bsd-hardware.info/?probe=0bd96ef663) | Apr 19, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [418cc1382c](https://bsd-hardware.info/?probe=418cc1382c) | Apr 18, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [be1821da8a](https://bsd-hardware.info/?probe=be1821da8a) | Apr 18, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3a81fe2ee4](https://bsd-hardware.info/?probe=3a81fe2ee4) | Apr 18, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [ce7b152e96](https://bsd-hardware.info/?probe=ce7b152e96) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| ASUSTek       | Q500A                       | Notebook    | [c52b593262](https://bsd-hardware.info/?probe=c52b593262) | Apr 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [9dfe1dae23](https://bsd-hardware.info/?probe=9dfe1dae23) | Apr 16, 2021 |
| ASRock        | AM1H-ITX                    | Desktop     | [917ee44fe9](https://bsd-hardware.info/?probe=917ee44fe9) | Apr 15, 2021 |
| Beckhoff A... | CB3163 G5                   | Desktop     | [25df932cdf](https://bsd-hardware.info/?probe=25df932cdf) | Apr 14, 2021 |
| Beckhoff A... | CX51x0 G2                   | Desktop     | [ab8247d8b5](https://bsd-hardware.info/?probe=ab8247d8b5) | Apr 14, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [270bd22b8d](https://bsd-hardware.info/?probe=270bd22b8d) | Apr 14, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [431eaac648](https://bsd-hardware.info/?probe=431eaac648) | Apr 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9050866fb2](https://bsd-hardware.info/?probe=9050866fb2) | Apr 12, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 162       | 90%     |
| arm64 | 11        | 6.11%   |
| i386  | 6         | 3.33%   |
| arm   | 1         | 0.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 55        | 30.56%  |
| XFCE          | 30        | 16.67%  |
| KDE5          | 29        | 16.11%  |
| TWM           | 16        | 8.89%   |
| GNOME         | 15        | 8.33%   |
| MATE          | 10        | 5.56%   |
| i3            | 8         | 4.44%   |
| Openbox       | 7         | 3.89%   |
| LXQt          | 2         | 1.11%   |
| Enlightenment | 2         | 1.11%   |
| Cinnamon      | 2         | 1.11%   |
| AwesomeWM     | 2         | 1.11%   |
| GNUstep       | 1         | 0.56%   |
| Fluxbox       | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 124       | 68.89%  |
| Console | 54        | 30%     |
| Wayland | 2         | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 103       | 57.22%  |
| SDDM    | 30        | 16.67%  |
| SLiM    | 15        | 8.33%   |
| GDM     | 15        | 8.33%   |
| LightDM | 10        | 5.56%   |
| XDM     | 6         | 3.33%   |
| Ly      | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 127       | 70.56%  |
| en_US           | 15        | 8.33%   |
| Unknown         | 13        | 7.22%   |
| ru_RU           | 5         | 2.78%   |
| de_DE           | 5         | 2.78%   |
| fr_FR           | 4         | 2.22%   |
| nb_NO           | 3         | 1.67%   |
| en_GB           | 2         | 1.11%   |
| uk_UA           | 1         | 0.56%   |
| pt_PT           | 1         | 0.56%   |
| pl_PL           | 1         | 0.56%   |
| ja_JP           | 1         | 0.56%   |
| it_IT.ISO8859-1 | 1         | 0.56%   |
| es_ES           | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 123       | 67.21%  |
| BIOS | 60        | 32.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 118       | 65.56%  |
| Ufs  | 62        | 34.44%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 161       | 89.44%  |
| MBR  | 19        | 10.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 32        | 17.78%  |
| Dell                    | 31        | 17.22%  |
| ASUSTek Computer        | 24        | 13.33%  |
| Hewlett-Packard         | 13        | 7.22%   |
| Gigabyte Technology     | 12        | 6.67%   |
| Unknown                 | 11        | 6.11%   |
| ASRock                  | 9         | 5%      |
| MSI                     | 7         | 3.89%   |
| Acer                    | 5         | 2.78%   |
| Apple                   | 4         | 2.22%   |
| Toshiba                 | 3         | 1.67%   |
| Intel                   | 3         | 1.67%   |
| Cisco Systems           | 3         | 1.67%   |
| Beckhoff Automation     | 3         | 1.67%   |
| System76                | 2         | 1.11%   |
| Samsung Electronics     | 2         | 1.11%   |
| Raspberry Pi Foundation | 2         | 1.11%   |
| Pegatron                | 2         | 1.11%   |
| Notebook                | 2         | 1.11%   |
| Wistron                 | 1         | 0.56%   |
| Shuttle                 | 1         | 0.56%   |
| Medion                  | 1         | 0.56%   |
| GVC                     | 1         | 0.56%   |
| Google                  | 1         | 0.56%   |
| Fujitsu                 | 1         | 0.56%   |
| Framework               | 1         | 0.56%   |
| firefly                 | 1         | 0.56%   |
| EVGA                    | 1         | 0.56%   |
| Alienware               | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 11        | 6.11%   |
| ASUS All Series                            | 3         | 1.67%   |
| Dell OptiPlex 7040                         | 2         | 1.11%   |
| Cisco Systems UCSC-C240-M4L                | 2         | 1.11%   |
| Beckhoff Automation Industrial PC          | 2         | 1.11%   |
| ASUS TUF GAMING X570-PLUS                  | 2         | 1.11%   |
| ASUS P5Q-E                                 | 2         | 1.11%   |
| ASRock B450M Pro4                          | 2         | 1.11%   |
| Wistron ProLiant ML110 G6                  | 1         | 0.56%   |
| Toshiba TECRA M11                          | 1         | 0.56%   |
| Toshiba Satellite L50-C                    | 1         | 0.56%   |
| Toshiba PORTEGE X20W-D                     | 1         | 0.56%   |
| System76 Lemur Pro                         | 1         | 0.56%   |
| System76 Gazelle                           | 1         | 0.56%   |
| Shuttle SH87R                              | 1         | 0.56%   |
| Samsung NC10                               | 1         | 0.56%   |
| Samsung 300E5M/300E5L                      | 1         | 0.56%   |
| RPi rpi                                    | 1         | 0.56%   |
| RPi Raspberry Pi                           | 1         | 0.56%   |
| Pegatron T12Ah                             | 1         | 0.56%   |
| Pegatron SAISHIAT2                         | 1         | 0.56%   |
| Notebook NL5xRU                            | 1         | 0.56%   |
| Notebook N7x0WU                            | 1         | 0.56%   |
| MSI MS-7C80                                | 1         | 0.56%   |
| MSI MS-7C02                                | 1         | 0.56%   |
| MSI MS-7B09                                | 1         | 0.56%   |
| MSI MS-7817                                | 1         | 0.56%   |
| MSI MS-7677                                | 1         | 0.56%   |
| MSI GS65 Stealth Thin 8RF                  | 1         | 0.56%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.56%   |
| Medion MS-7616                             | 1         | 0.56%   |
| Lenovo Z51-70 80K6                         | 1         | 0.56%   |
| Lenovo Yoga 720-15IKB 80X7                 | 1         | 0.56%   |
| Lenovo ThinkStation P720 30BAS1HX00        | 1         | 0.56%   |
| Lenovo ThinkPad X380 Yoga S1 20LJS1FD01    | 1         | 0.56%   |
| Lenovo ThinkPad X380 Yoga 20LH000NPG       | 1         | 0.56%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.56%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.56%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.56%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.56%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.56%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.56%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.56%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.56%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.56%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.56%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.56%   |
| Lenovo ThinkPad R60e 0658W2M               | 1         | 0.56%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.56%   |
| Lenovo ThinkPad Mini10 3507A31             | 1         | 0.56%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.56%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.56%   |
| Lenovo ThinkPad E490 20N8CTO1WW            | 1         | 0.56%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE       | 1         | 0.56%   |
| Lenovo ThinkPad E14 20RAS0F600             | 1         | 0.56%   |
| Lenovo Rescuer-15ISK 80RQ                  | 1         | 0.56%   |
| Lenovo IdeaPad 330-15IGM 81D1              | 1         | 0.56%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.56%   |
| Lenovo IdeaPad 320-15AST 80XV              | 1         | 0.56%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 21        | 11.67%  |
| Unknown                        | 11        | 6.11%   |
| Dell Latitude                  | 10        | 5.56%   |
| Dell Inspiron                  | 9         | 5%      |
| Lenovo IdeaPad                 | 4         | 2.22%   |
| Dell Precision                 | 3         | 1.67%   |
| ASUS TUF                       | 3         | 1.67%   |
| ASUS ROG                       | 3         | 1.67%   |
| ASUS All                       | 3         | 1.67%   |
| Acer Aspire                    | 3         | 1.67%   |
| HP ProLiant                    | 2         | 1.11%   |
| HP Laptop                      | 2         | 1.11%   |
| HP Compaq                      | 2         | 1.11%   |
| Gigabyte X570                  | 2         | 1.11%   |
| Dell XPS                       | 2         | 1.11%   |
| Dell Vostro                    | 2         | 1.11%   |
| Dell PowerEdge                 | 2         | 1.11%   |
| Dell OptiPlex                  | 2         | 1.11%   |
| Cisco Systems UCSC-C240-M4L    | 2         | 1.11%   |
| Beckhoff Automation Industrial | 2         | 1.11%   |
| ASUS P5Q-E                     | 2         | 1.11%   |
| ASRock X570                    | 2         | 1.11%   |
| ASRock B450M                   | 2         | 1.11%   |
| Wistron ProLiant               | 1         | 0.56%   |
| Toshiba TECRA                  | 1         | 0.56%   |
| Toshiba Satellite              | 1         | 0.56%   |
| Toshiba PORTEGE                | 1         | 0.56%   |
| System76 Lemur                 | 1         | 0.56%   |
| System76 Gazelle               | 1         | 0.56%   |
| Shuttle SH87R                  | 1         | 0.56%   |
| Samsung NC10                   | 1         | 0.56%   |
| Samsung 300E5M                 | 1         | 0.56%   |
| RPi rpi                        | 1         | 0.56%   |
| RPi Raspberry                  | 1         | 0.56%   |
| Pegatron T12Ah                 | 1         | 0.56%   |
| Pegatron SAISHIAT2             | 1         | 0.56%   |
| Notebook NL5xRU                | 1         | 0.56%   |
| Notebook N7x0WU                | 1         | 0.56%   |
| MSI MS-7C80                    | 1         | 0.56%   |
| MSI MS-7C02                    | 1         | 0.56%   |
| MSI MS-7B09                    | 1         | 0.56%   |
| MSI MS-7817                    | 1         | 0.56%   |
| MSI MS-7677                    | 1         | 0.56%   |
| MSI GS65                       | 1         | 0.56%   |
| MSI GL65                       | 1         | 0.56%   |
| Medion MS-7616                 | 1         | 0.56%   |
| Lenovo Z51-70                  | 1         | 0.56%   |
| Lenovo Yoga                    | 1         | 0.56%   |
| Lenovo ThinkStation            | 1         | 0.56%   |
| Lenovo Rescuer-15ISK           | 1         | 0.56%   |
| Lenovo G580                    | 1         | 0.56%   |
| Lenovo G505                    | 1         | 0.56%   |
| Lenovo G40-70                  | 1         | 0.56%   |
| Intel NUC7CJYS                 | 1         | 0.56%   |
| Intel NUC5i3RYB                | 1         | 0.56%   |
| Intel NUC5CPYB                 | 1         | 0.56%   |
| HP Z220                        | 1         | 0.56%   |
| HP Pavilion                    | 1         | 0.56%   |
| HP Mini                        | 1         | 0.56%   |
| HP ENVY                        | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 32        | 17.78%  |
| 2019    | 28        | 15.56%  |
| 2018    | 23        | 12.78%  |
| 2021    | 16        | 8.89%   |
| 2012    | 11        | 6.11%   |
| 2015    | 10        | 5.56%   |
| 2011    | 10        | 5.56%   |
| Unknown | 10        | 5.56%   |
| 2013    | 8         | 4.44%   |
| 2016    | 6         | 3.33%   |
| 2008    | 6         | 3.33%   |
| 2017    | 5         | 2.78%   |
| 2014    | 4         | 2.22%   |
| 2009    | 4         | 2.22%   |
| 2010    | 3         | 1.67%   |
| 2006    | 2         | 1.11%   |
| 2007    | 1         | 0.56%   |
| 2005    | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 88        | 48.89%  |
| Desktop        | 67        | 37.22%  |
| System on chip | 8         | 4.44%   |
| Server         | 6         | 3.33%   |
| Convertible    | 5         | 2.78%   |
| Mini pc        | 3         | 1.67%   |
| All in one     | 3         | 1.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 178       | 98.89%  |
| Yes  | 2         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 55        | 30.56%  |
| 16.01-24.0      | 40        | 22.22%  |
| 4.01-8.0        | 26        | 14.44%  |
| 32.01-64.0      | 19        | 10.56%  |
| 64.01-256.0     | 16        | 8.89%   |
| 2.01-3.0        | 9         | 5%      |
| 3.01-4.0        | 4         | 2.22%   |
| 24.01-32.0      | 4         | 2.22%   |
| 0.51-1.0        | 4         | 2.22%   |
| More than 256.0 | 1         | 0.56%   |
| 1.01-2.0        | 1         | 0.56%   |
| 0.01-0.5        | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 79        | 43.65%  |
| 0.51-1.0   | 55        | 30.39%  |
| 1.01-2.0   | 25        | 13.81%  |
| 3.01-4.0   | 6         | 3.31%   |
| 2.01-3.0   | 5         | 2.76%   |
| 4.01-8.0   | 3         | 1.66%   |
| 16.01-24.0 | 3         | 1.66%   |
| 0          | 3         | 1.66%   |
| 24.01-32.0 | 1         | 0.55%   |
| 8.01-16.0  | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 53.55%  |
| 2      | 33        | 18.03%  |
| 3      | 14        | 7.65%   |
| 0      | 13        | 7.1%    |
| 4      | 7         | 3.83%   |
| 5      | 6         | 3.28%   |
| 6      | 4         | 2.19%   |
| 7      | 3         | 1.64%   |
| 12     | 2         | 1.09%   |
| 14     | 1         | 0.55%   |
| 13     | 1         | 0.55%   |
| 9      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 68.51%  |
| Yes       | 57        | 31.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 85%     |
| No        | 27        | 15%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 67.22%  |
| No        | 59        | 32.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 53.33%  |
| Yes       | 84        | 46.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 49        | 27.22%  |
| Russia      | 20        | 11.11%  |
| Germany     | 14        | 7.78%   |
| UK          | 10        | 5.56%   |
| Netherlands | 7         | 3.89%   |
| France      | 6         | 3.33%   |
| Brazil      | 5         | 2.78%   |
| Switzerland | 4         | 2.22%   |
| Czechia     | 4         | 2.22%   |
| Australia   | 4         | 2.22%   |
| Ukraine     | 3         | 1.67%   |
| Poland      | 3         | 1.67%   |
| Mexico      | 3         | 1.67%   |
| Japan       | 3         | 1.67%   |
| India       | 3         | 1.67%   |
| Canada      | 3         | 1.67%   |
| Thailand    | 2         | 1.11%   |
| Spain       | 2         | 1.11%   |
| Norway      | 2         | 1.11%   |
| New Zealand | 2         | 1.11%   |
| Iran        | 2         | 1.11%   |
| Guadeloupe  | 2         | 1.11%   |
| Finland     | 2         | 1.11%   |
| Colombia    | 2         | 1.11%   |
| Bulgaria    | 2         | 1.11%   |
| Vietnam     | 1         | 0.56%   |
| Turkey      | 1         | 0.56%   |
| Sweden      | 1         | 0.56%   |
| Slovakia    | 1         | 0.56%   |
| Romania     | 1         | 0.56%   |
| Qatar       | 1         | 0.56%   |
| Portugal    | 1         | 0.56%   |
| Nepal       | 1         | 0.56%   |
| Namibia     | 1         | 0.56%   |
| Malaysia    | 1         | 0.56%   |
| Lithuania   | 1         | 0.56%   |
| Italy       | 1         | 0.56%   |
| Ireland     | 1         | 0.56%   |
| Hungary     | 1         | 0.56%   |
| Guatemala   | 1         | 0.56%   |
| Denmark     | 1         | 0.56%   |
| China       | 1         | 0.56%   |
| Chile       | 1         | 0.56%   |
| Austria     | 1         | 0.56%   |
| Argentina   | 1         | 0.56%   |
| Albania     | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Lexington              | 5         | 2.75%   |
| Seattle                | 4         | 2.2%    |
| Moscow                 | 3         | 1.65%   |
| Lübeck                | 3         | 1.65%   |
| Alphen aan den Rijn    | 3         | 1.65%   |
| Yekaterinburg          | 2         | 1.1%    |
| Tehran                 | 2         | 1.1%    |
| Sofia                  | 2         | 1.1%    |
| Salem                  | 2         | 1.1%    |
| Redmond                | 2         | 1.1%    |
| Ozersk                 | 2         | 1.1%    |
| Minneapolis            | 2         | 1.1%    |
| Menlo Park             | 2         | 1.1%    |
| Melbourne              | 2         | 1.1%    |
| Le Gosier              | 2         | 1.1%    |
| Kyiv                   | 2         | 1.1%    |
| Kirkland               | 2         | 1.1%    |
| Irkutsk                | 2         | 1.1%    |
| Helsinki               | 2         | 1.1%    |
| Chelyabinsk            | 2         | 1.1%    |
| Berlin                 | 2         | 1.1%    |
| Zurich                 | 1         | 0.55%   |
| Wenatchee              | 1         | 0.55%   |
| Weimar                 | 1         | 0.55%   |
| Wausau                 | 1         | 0.55%   |
| Warsaw                 | 1         | 0.55%   |
| Vostochnoe Degunino    | 1         | 0.55%   |
| Vilnius                | 1         | 0.55%   |
| Vancouver              | 1         | 0.55%   |
| Valladolid             | 1         | 0.55%   |
| Vadodara               | 1         | 0.55%   |
| Vacaville              | 1         | 0.55%   |
| Ufa                    | 1         | 0.55%   |
| Tyumen                 | 1         | 0.55%   |
| Tuklaty                | 1         | 0.55%   |
| Tuddal                 | 1         | 0.55%   |
| Trang                  | 1         | 0.55%   |
| The Bronx              | 1         | 0.55%   |
| Teteghem               | 1         | 0.55%   |
| Tatab??nya             | 1         | 0.55%   |
| São Paulo             | 1         | 0.55%   |
| São José dos Campos  | 1         | 0.55%   |
| Sydney                 | 1         | 0.55%   |
| Sundebru               | 1         | 0.55%   |
| Suginami-ku            | 1         | 0.55%   |
| Stuttgart              | 1         | 0.55%   |
| St. Catharines         | 1         | 0.55%   |
| South Yarra            | 1         | 0.55%   |
| Scottsdale             | 1         | 0.55%   |
| Sarandë               | 1         | 0.55%   |
| San Vicent del Raspeig | 1         | 0.55%   |
| San Diego              | 1         | 0.55%   |
| San Antonio            | 1         | 0.55%   |
| Rugby                  | 1         | 0.55%   |
| Rostov-on-Don          | 1         | 0.55%   |
| Rochester              | 1         | 0.55%   |
| Rionegro               | 1         | 0.55%   |
| Rennes                 | 1         | 0.55%   |
| Prague                 | 1         | 0.55%   |
| Porto União           | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 75     | 16.87%  |
| Seagate             | 40        | 110    | 16.06%  |
| WDC                 | 35        | 96     | 14.06%  |
| Toshiba             | 22        | 30     | 8.84%   |
| Kingston            | 22        | 24     | 8.84%   |
| Crucial             | 15        | 16     | 6.02%   |
| Hitachi             | 9         | 18     | 3.61%   |
| Intel               | 8         | 9      | 3.21%   |
| SanDisk             | 6         | 6      | 2.41%   |
| HGST                | 6         | 8      | 2.41%   |
| A-DATA Technology   | 6         | 6      | 2.41%   |
| SK Hynix            | 4         | 4      | 1.61%   |
| Phison              | 3         | 3      | 1.2%    |
| Fujitsu             | 3         | 4      | 1.2%    |
| Corsair             | 3         | 3      | 1.2%    |
| PNY                 | 2         | 2      | 0.8%    |
| PLEXTOR             | 2         | 2      | 0.8%    |
| Micron Technology   | 2         | 2      | 0.8%    |
| LITEONIT            | 2         | 2      | 0.8%    |
| Lenovo              | 2         | 2      | 0.8%    |
| VMware              | 1         | 1      | 0.4%    |
| Verbatim            | 1         | 1      | 0.4%    |
| TCSUNBOW            | 1         | 1      | 0.4%    |
| SPCC                | 1         | 1      | 0.4%    |
| Smartbuy            | 1         | 1      | 0.4%    |
| Silicon Motion      | 1         | 1      | 0.4%    |
| OWC                 | 1         | 1      | 0.4%    |
| MAXTOR              | 1         | 1      | 0.4%    |
| KIOXIA              | 1         | 1      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| KingDian            | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 2      | 0.4%    |
| Gigabyte Technology | 1         | 1      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB        | 5         | 1.73%   |
| Crucial CT500MX500SSD1 500GB       | 5         | 1.73%   |
| Seagate ST4000DM000-1F2168 4TB     | 4         | 1.38%   |
| Samsung SSD 970 EVO Plus 250GB     | 4         | 1.38%   |
| Kingston SA400S37240G 240GB        | 4         | 1.38%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.04%   |
| Toshiba DT01ACA100 1TB             | 3         | 1.04%   |
| Seagate ST1000LM048-2E7172 1TB     | 3         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.04%   |
| Samsung SSD 970 EVO 500GB          | 3         | 1.04%   |
| Samsung SSD 860 EVO 500GB          | 3         | 1.04%   |
| Samsung MZVLB256HBHQ-000L7 256GB   | 3         | 1.04%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.69%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.69%   |
| Toshiba MG04SCA20EN 2TB            | 2         | 0.69%   |
| Seagate ST8000VN004-2M2101 8TB     | 2         | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.69%   |
| Seagate ST2000NM0023 2TB           | 2         | 0.69%   |
| Seagate ST1000NM0023 1TB           | 2         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB       | 2         | 0.69%   |
| Samsung SSD 860 EVO 1TB            | 2         | 0.69%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.69%   |
| Kingston SVP200S37A60G 64GB        | 2         | 0.69%   |
| Kingston SMS200S3120G 120GB        | 2         | 0.69%   |
| HGST HTS725032A7E630 320GB         | 2         | 0.69%   |
| Crucial CT120BX500SSD1 120GB       | 2         | 0.69%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB       | 1         | 0.35%   |
| WDC WDS250G2B0A 250GB              | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.35%   |
| WDC WDS120G2G0B-00EPW0 120GB       | 1         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB       | 1         | 0.35%   |
| WDC WDS100T2B0B-00YS70 1TB         | 1         | 0.35%   |
| WDC WD80EMAZ-00WJTA0 8TB           | 1         | 0.35%   |
| WDC WD80EFZX-68UW8N0 8TB           | 1         | 0.35%   |
| WDC WD80EFAX-68LHPN0 8TB           | 1         | 0.35%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 0.35%   |
| WDC WD6003FZBX-00K5WB0 6TB         | 1         | 0.35%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.35%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 0.35%   |
| WDC WD5000AAKX-083CA0 500GB        | 1         | 0.35%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.35%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1         | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 0.35%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 0.35%   |
| WDC WD30EZRX-00AZ6B0 3TB           | 1         | 0.35%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.35%   |
| WDC WD2500BEVT-08A23T1 250GB       | 1         | 0.35%   |
| WDC WD2500BEVS-08VAT2 250GB        | 1         | 0.35%   |
| WDC WD20SPZX-22UA7T0 2TB           | 1         | 0.35%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 0.35%   |
| WDC WD1600BEVT-11ZCT0 160GB        | 1         | 0.35%   |
| WDC WD120EMFZ-11A6JA0 12TB         | 1         | 0.35%   |
| WDC WD120EMAZ-11BLFA0 12TB         | 1         | 0.35%   |
| WDC WD10SPZX-75Z10T1 1TB           | 1         | 0.35%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 0.35%   |
| WDC WD10SDRW-34A0XS0 1TB           | 1         | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 0.35%   |
| WDC WD10JPLX-00MBPT1 1TB           | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 109    | 37.14%  |
| WDC                 | 25        | 84     | 23.81%  |
| Toshiba             | 19        | 27     | 18.1%   |
| Hitachi             | 9         | 18     | 8.57%   |
| HGST                | 6         | 8      | 5.71%   |
| Fujitsu             | 3         | 4      | 2.86%   |
| Samsung Electronics | 2         | 3      | 1.9%    |
| MAXTOR              | 1         | 1      | 0.95%   |
| Hewlett-Packard     | 1         | 2      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 40     | 21.9%   |
| Kingston            | 19        | 21     | 18.1%   |
| Crucial             | 15        | 16     | 14.29%  |
| Intel               | 7         | 8      | 6.67%   |
| WDC                 | 6         | 7      | 5.71%   |
| SanDisk             | 6         | 6      | 5.71%   |
| A-DATA Technology   | 5         | 5      | 4.76%   |
| SK Hynix            | 3         | 3      | 2.86%   |
| Micron Technology   | 2         | 2      | 1.9%    |
| LITEONIT            | 2         | 2      | 1.9%    |
| Corsair             | 2         | 2      | 1.9%    |
| VMware              | 1         | 1      | 0.95%   |
| Verbatim            | 1         | 1      | 0.95%   |
| Toshiba             | 1         | 1      | 0.95%   |
| TCSUNBOW            | 1         | 1      | 0.95%   |
| SPCC                | 1         | 1      | 0.95%   |
| Smartbuy            | 1         | 1      | 0.95%   |
| PNY                 | 1         | 1      | 0.95%   |
| PLEXTOR             | 1         | 1      | 0.95%   |
| OWC                 | 1         | 1      | 0.95%   |
| Lenovo              | 1         | 1      | 0.95%   |
| KingSpec            | 1         | 1      | 0.95%   |
| KingDian            | 1         | 1      | 0.95%   |
| Intenso             | 1         | 1      | 0.95%   |
| Gigabyte Technology | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 90        | 256    | 40.36%  |
| SSD  | 89        | 127    | 39.91%  |
| NVMe | 44        | 55     | 19.73%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 383    | 77.2%   |
| NVMe | 44        | 55     | 22.8%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 149    | 53.57%  |
| 0.51-1.0   | 49        | 94     | 25%     |
| 1.01-2.0   | 13        | 29     | 6.63%   |
| 3.01-4.0   | 9         | 30     | 4.59%   |
| 4.01-10.0  | 9         | 44     | 4.59%   |
| 2.01-3.0   | 8         | 23     | 4.08%   |
| 10.01-20.0 | 3         | 14     | 1.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 33.33%  |
| 251-500        | 38        | 21.11%  |
| 501-1000       | 21        | 11.67%  |
| 51-100         | 19        | 10.56%  |
| 21-50          | 14        | 7.78%   |
| 1-20           | 13        | 7.22%   |
| 1001-2000      | 8         | 4.44%   |
| More than 3000 | 3         | 1.67%   |
| 2001-3000      | 3         | 1.67%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 155       | 86.11%  |
| 21-50          | 10        | 5.56%   |
| 51-100         | 5         | 2.78%   |
| 101-250        | 4         | 2.22%   |
| More than 3000 | 2         | 1.11%   |
| 251-500        | 2         | 1.11%   |
| 1001-2000      | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB                     | 1         | 1      | 2.94%   |
| WDC WD7500BPVT-80HXZT3 752GB                     | 1         | 1      | 2.94%   |
| WDC WD5000BEVT-75A0RT0 500GB                     | 1         | 1      | 2.94%   |
| WDC WD5000AAKX-083CA0 500GB                      | 1         | 1      | 2.94%   |
| WDC WD3200BPVT-75ZEST0 320GB                     | 1         | 1      | 2.94%   |
| WDC WD2500BEVT-08A23T1 250GB                     | 1         | 1      | 2.94%   |
| WDC WD20EARX-00PASB0 2TB                         | 1         | 1      | 2.94%   |
| WDC WD10EADS-00P8B0 1TB                          | 1         | 1      | 2.94%   |
| Toshiba THNSNK512GVN8 512GB                      | 1         | 1      | 2.94%   |
| Toshiba MQ02ABD100H 1TB                          | 1         | 1      | 2.94%   |
| Toshiba MK3261GSYN 320GB                         | 1         | 1      | 2.94%   |
| Seagate ST96812AS 64GB                           | 1         | 4      | 2.94%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 2.94%   |
| Seagate ST9250827AS 250GB                        | 1         | 1      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.94%   |
| Seagate ST380013AS 80GB                          | 1         | 2      | 2.94%   |
| Seagate ST3250620AS 250GB                        | 1         | 1      | 2.94%   |
| Seagate ST31500341AS 1.5TB                       | 1         | 1      | 2.94%   |
| Seagate ST31000524AS 1TB                         | 1         | 1      | 2.94%   |
| Seagate ST1000LM014-1EJ164 1TB                   | 1         | 1      | 2.94%   |
| Samsung Electronics SSD PM841 2.5-inch 7mm 256GB | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 840 EVO 120GB            | 1         | 1      | 2.94%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.94%   |
| PLEXTOR PX-128M5S 128GB                          | 1         | 1      | 2.94%   |
| MAXTOR STM3160815AS 160GB                        | 1         | 1      | 2.94%   |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 2.94%   |
| Intel SSDSC2BB120G6R 120GB                       | 1         | 1      | 2.94%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 2.94%   |
| Hitachi HTS543225A7A384 250GB                    | 1         | 1      | 2.94%   |
| Hitachi HTS541612J9SA00 120GB                    | 1         | 1      | 2.94%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 2.94%   |
| HGST HDN726060ALE614 6TB                         | 1         | 2      | 2.94%   |
| Crucial CT250MX200SSD1 250GB                     | 1         | 1      | 2.94%   |
| Corsair Force 3 SSD 180GB                        | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 8      | 22.58%  |
| Seagate             | 7         | 13     | 22.58%  |
| Hitachi             | 4         | 4      | 12.9%   |
| Toshiba             | 3         | 3      | 9.68%   |
| Samsung Electronics | 3         | 3      | 9.68%   |
| Intel               | 2         | 2      | 6.45%   |
| PLEXTOR             | 1         | 1      | 3.23%   |
| MAXTOR              | 1         | 1      | 3.23%   |
| HGST                | 1         | 2      | 3.23%   |
| Crucial             | 1         | 1      | 3.23%   |
| Corsair             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 13     | 31.82%  |
| WDC                 | 6         | 7      | 27.27%  |
| Hitachi             | 4         | 4      | 18.18%  |
| Toshiba             | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 4.55%   |
| MAXTOR              | 1         | 1      | 4.55%   |
| HGST                | 1         | 2      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 30     | 68.97%  |
| SSD  | 9         | 9      | 31.03%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 150       | 390    | 81.97%  |
| Malfunc  | 28        | 39     | 15.3%   |
| Detected | 5         | 9      | 2.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 122       | 55.45%  |
| AMD                              | 30        | 13.64%  |
| Samsung Electronics              | 23        | 10.45%  |
| Broadcom / LSI                   | 6         | 2.73%   |
| ASMedia Technology               | 6         | 2.73%   |
| Phison Electronics               | 5         | 2.27%   |
| Sandisk                          | 4         | 1.82%   |
| Marvell Technology Group         | 4         | 1.82%   |
| VMware                           | 2         | 0.91%   |
| Toshiba                          | 2         | 0.91%   |
| Nvidia                           | 2         | 0.91%   |
| Kingston Technology Company      | 2         | 0.91%   |
| JMicron Technology               | 2         | 0.91%   |
| SK Hynix                         | 1         | 0.45%   |
| Silicon Motion                   | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Seagate Technology               | 1         | 0.45%   |
| Lite-On Technology               | 1         | 0.45%   |
| Lenovo                           | 1         | 0.45%   |
| KIOXIA                           | 1         | 0.45%   |
| Hewlett-Packard                  | 1         | 0.45%   |
| Apple                            | 1         | 0.45%   |
| ADATA Technology                 | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 10.93%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 4.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 3.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 3.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.83%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 2.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.43%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 1.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.62%   |
| Unknown                                                                          | 4         | 1.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.21%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 1.21%   |
| VMware SATA AHCI controller                                                      | 2         | 0.81%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.81%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.81%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.81%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.81%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 2         | 0.81%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.81%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.81%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 2         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.81%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 0.81%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 0.81%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2         | 0.81%   |
| VMware PVSCSI SCSI Controller                                                    | 1         | 0.4%    |
| Toshiba unknown                                                                  | 1         | 0.4%    |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.4%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.4%    |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.4%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.4%    |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 0.4%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 1         | 0.4%    |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                             | 1         | 0.4%    |
| Lite-On M8Pe Series NVMe SSD                                                     | 1         | 0.4%    |
| Lenovo unknown                                                                   | 1         | 0.4%    |
| KIOXIA unknown                                                                   | 1         | 0.4%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.4%    |
| Intel SSD 660P Series                                                            | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 134       | 61.47%  |
| NVMe | 44        | 20.18%  |
| IDE  | 22        | 10.09%  |
| RAID | 13        | 5.96%   |
| SAS  | 5         | 2.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 137       | 76.11%  |
| AMD     | 31        | 17.22%  |
| ARM     | 8         | 4.44%   |
| Unknown | 3         | 1.67%   |
| Unknown | 1         | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                      | 6         | 3.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 2.22%   |
| AMD Ryzen 7 2700 Eight-Core Processor    | 4         | 2.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 3         | 1.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 3         | 1.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 3         | 1.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 3         | 1.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 1.67%   |
|                                          | 3         | 1.67%   |
| Intel CPU Version                        | 2         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 1.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 2         | 1.11%   |
| Intel Core i7-4510U CPU @ 2.00GHz        | 2         | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 1.11%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 2         | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 2         | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 2         | 1.11%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 2         | 1.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.11%   |
| Intel Core i3-4005U CPU @ 1.70GHz        | 2         | 1.11%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 2         | 1.11%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 2         | 1.11%   |
| Unknown Implementer Processor r0p0       | 1         | 0.56%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz     | 1         | 0.56%   |
| Intel Xeon CPU X5650 @ 2.67GHz           | 1         | 0.56%   |
| Intel Xeon CPU X3440 @ 2.53GHz           | 1         | 0.56%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 1         | 0.56%   |
| Intel Xeon CPU E5520 @ 2.27GHz           | 1         | 0.56%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz      | 1         | 0.56%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz      | 1         | 0.56%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz      | 1         | 0.56%   |
| Intel Xeon CPU E3-1275 v5 @ 3.60GHz      | 1         | 0.56%   |
| Intel Processor 5Y70 CPU @ 1.10GHz       | 1         | 0.56%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 0.56%   |
| Intel Pentium M                          | 1         | 0.56%   |
| Intel Pentium II                         | 1         | 0.56%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz   | 1         | 0.56%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 0.56%   |
| Intel Pentium CPU G630T @ 2.30GHz        | 1         | 0.56%   |
| Intel Pentium CPU G3420 @ 3.20GHz        | 1         | 0.56%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 1         | 0.56%   |
| Intel Pentium CPU G2020 @ 2.90GHz        | 1         | 0.56%   |
| Intel Pentium 4 CPU                      | 1         | 0.56%   |
| Intel Pentium 4                          | 1         | 0.56%   |
| Intel Genuine CPU                        | 1         | 0.56%   |
| Intel Core i9-9900X CPU @ 3.50GHz        | 1         | 0.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz        | 1         | 0.56%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz       | 1         | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 1         | 0.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 1         | 0.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.56%   |
| Intel Core i7-4790S CPU @ 3.20GHz        | 1         | 0.56%   |
| Intel Core i7-4770T CPU @ 2.50GHz        | 1         | 0.56%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz       | 1         | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 1         | 0.56%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 1         | 0.56%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.56%   |
| Intel Core i7-3610QE CPU @ 2.30GHz       | 1         | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 42        | 23.33%  |
| Intel Core i7          | 36        | 20%     |
| Intel Core i3          | 11        | 6.11%   |
| AMD Ryzen 7            | 10        | 5.56%   |
| Other                  | 9         | 5%      |
| Intel Xeon             | 8         | 4.44%   |
| Intel Celeron          | 8         | 4.44%   |
| ARM Cortex             | 8         | 4.44%   |
| Intel Pentium          | 6         | 3.33%   |
| Intel Core 2 Duo       | 6         | 3.33%   |
| AMD Ryzen 9            | 6         | 3.33%   |
| Intel Atom             | 5         | 2.78%   |
| AMD Ryzen 5            | 4         | 2.22%   |
| Intel Pentium 4        | 2         | 1.11%   |
| AMD Ryzen 3            | 2         | 1.11%   |
| AMD A4                 | 2         | 1.11%   |
| Intel Xeon Silver      | 1         | 0.56%   |
| Intel Pentium Silver   | 1         | 0.56%   |
| Intel Pentium M        | 1         | 0.56%   |
| Intel Pentium Dual     | 1         | 0.56%   |
| Intel Genuine          | 1         | 0.56%   |
| Intel Core i9          | 1         | 0.56%   |
| Intel Core 2 Quad      | 1         | 0.56%   |
| Intel Core 2           | 1         | 0.56%   |
| Intel Celeron M        | 1         | 0.56%   |
| AMD Ryzen Threadripper | 1         | 0.56%   |
| AMD FX                 | 1         | 0.56%   |
| AMD Athlon X4          | 1         | 0.56%   |
| AMD Athlon             | 1         | 0.56%   |
| AMD A6                 | 1         | 0.56%   |
| AMD A12                | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 60        | 33.33%  |
| 4       | 57        | 31.67%  |
| Unknown | 21        | 11.67%  |
| 16      | 10        | 5.56%   |
| 6       | 8         | 4.44%   |
| 8       | 6         | 3.33%   |
| 12      | 5         | 2.78%   |
| 1       | 5         | 2.78%   |
| 24      | 4         | 2.22%   |
| 32      | 2         | 1.11%   |
| 20      | 1         | 0.56%   |
| 10      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 165       | 91.67%  |
| Unknown | 9         | 5%      |
| 2       | 6         | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 98        | 54.44%  |
| 1       | 58        | 32.22%  |
| Unknown | 24        | 13.33%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 16.67%  |
| Haswell       | 17        | 9.44%   |
| Skylake       | 13        | 7.22%   |
| Unknown       | 13        | 7.22%   |
| SandyBridge   | 12        | 6.67%   |
| Westmere      | 10        | 5.56%   |
| IvyBridge     | 10        | 5.56%   |
| Zen+          | 7         | 3.89%   |
| Broadwell     | 7         | 3.89%   |
| Zen 2         | 6         | 3.33%   |
| Penryn        | 6         | 3.33%   |
| Zen           | 5         | 2.78%   |
| Silvermont    | 5         | 2.78%   |
| Bonnell       | 5         | 2.78%   |
| Zen 3         | 4         | 2.22%   |
| Nehalem       | 4         | 2.22%   |
| Core          | 4         | 2.22%   |
| Goldmont plus | 3         | 1.67%   |
| Excavator     | 3         | 1.67%   |
| CometLake     | 3         | 1.67%   |
| Piledriver    | 2         | 1.11%   |
| P6            | 2         | 1.11%   |
| NetBurst      | 2         | 1.11%   |
| Jaguar        | 2         | 1.11%   |
| IceLake       | 2         | 1.11%   |
| TigerLake     | 1         | 0.56%   |
| K10 Llano     | 1         | 0.56%   |
| Goldmont      | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 106       | 53.81%  |
| Nvidia                               | 51        | 25.89%  |
| AMD                                  | 30        | 15.23%  |
| Matrox Electronics Systems           | 7         | 3.55%   |
| VMware                               | 2         | 1.02%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.39%   |
| Intel HD Graphics 620                                                                    | 8         | 3.9%    |
| Intel HD Graphics 530                                                                    | 7         | 3.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 3.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.93%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.93%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.44%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.95%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.46%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.98%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.98%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.98%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.98%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.98%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.98%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.98%   |
| Intel HD Graphics 630                                                                    | 2         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.98%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.98%   |
| AMD Renoir                                                                               | 2         | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.98%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 0.98%   |
| Unknown                                                                                  | 2         | 0.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.49%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.49%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.49%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.49%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.49%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.49%   |
| Nvidia MCP7A [GeForce 9400]                                                              | 1         | 0.49%   |
| Nvidia GT218 [NVS 300]                                                                   | 1         | 0.49%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.49%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.49%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.49%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.49%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.49%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 71        | 39.44%  |
| 1 x Nvidia                               | 28        | 15.56%  |
| 1 x AMD                                  | 22        | 12.22%  |
| Intel + Nvidia                           | 20        | 11.11%  |
| Other                                    | 10        | 5.56%   |
| 2 x Intel                                | 10        | 5.56%   |
| 1 x Matrox                               | 7         | 3.89%   |
| Intel + AMD                              | 4         | 2.22%   |
| 2 x AMD                                  | 3         | 1.67%   |
| 1 x VMware                               | 2         | 1.11%   |
| 2 x Nvidia                               | 1         | 0.56%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.56%   |
| AMD + Nvidia                             | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 143       | 79.44%  |
| Proprietary | 26        | 14.44%  |
| Unknown     | 11        | 6.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 81.67%  |
| 0.01-0.5   | 7         | 3.89%   |
| 7.01-8.0   | 6         | 3.33%   |
| 3.01-4.0   | 6         | 3.33%   |
| 1.01-2.0   | 6         | 3.33%   |
| 5.01-6.0   | 3         | 1.67%   |
| 0.51-1.0   | 3         | 1.67%   |
| 2.01-3.0   | 1         | 0.56%   |
| 8.01-16.0  | 1         | 0.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 17        | 14.05%  |
| BOE                  | 14        | 11.57%  |
| LG Display           | 13        | 10.74%  |
| Samsung Electronics  | 11        | 9.09%   |
| Goldstar             | 9         | 7.44%   |
| Dell                 | 9         | 7.44%   |
| Chimei Innolux       | 6         | 4.96%   |
| Sharp                | 5         | 4.13%   |
| Ancor Communications | 5         | 4.13%   |
| Hewlett-Packard      | 4         | 3.31%   |
| AOC                  | 4         | 3.31%   |
| Lenovo               | 3         | 2.48%   |
| InfoVision           | 3         | 2.48%   |
| Sceptre Tech         | 2         | 1.65%   |
| Iiyama               | 2         | 1.65%   |
| BenQ                 | 2         | 1.65%   |
| Acer                 | 2         | 1.65%   |
| Toshiba              | 1         | 0.83%   |
| Philips              | 1         | 0.83%   |
| LG Electronics       | 1         | 0.83%   |
| HannStar             | 1         | 0.83%   |
| Eizo                 | 1         | 0.83%   |
| CPT                  | 1         | 0.83%   |
| CKL                  | 1         | 0.83%   |
| ASUSTek Computer     | 1         | 0.83%   |
| Apple                | 1         | 0.83%   |
| AGO                  | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 1.63%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 1.63%   |
| Toshiba TV TSB0108 1360x768 480x270mm 21.7-inch                        | 1         | 0.81%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 0.81%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 0.81%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                | 1         | 0.81%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.81%   |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 0.81%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 0.81%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch          | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0236 2560x1600 640x400mm 29.7-inch   | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1         | 0.81%   |
| Samsung Electronics S24E510C SAM0C61 1920x1080 520x300mm 23.6-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1210x680mm 54.6-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1020x570mm 46.0-inch | 1         | 0.81%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch     | 1         | 0.81%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 510x290mm 23.1-inch                | 1         | 0.81%   |
| Philips LCD Monitor PHLC050 1366x768 410x230mm 18.5-inch               | 1         | 0.81%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 0.81%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch                | 1         | 0.81%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 0.81%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 0.81%   |
| InfoVision LCD Monitor IVO0536 1920x1080 290x170mm 13.2-inch           | 1         | 0.81%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch            | 1         | 0.81%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 0.81%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                  | 1         | 0.81%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                  | 1         | 0.81%   |
| Hewlett-Packard Z24nf HWP3209 1920x1080 530x300mm 24.0-inch            | 1         | 0.81%   |
| Hewlett-Packard LCD Monitor HPN401E 1920x1080 480x270mm 21.7-inch      | 1         | 0.81%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x290mm 23.1-inch      | 1         | 0.81%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 0.81%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x130mm 10.1-inch               | 1         | 0.81%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                   | 1         | 0.81%   |
| Goldstar W2052 GSM4E88 1680x1050 470x300mm 22.0-inch                   | 1         | 0.81%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch            | 1         | 0.81%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1         | 0.81%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch             | 1         | 0.81%   |
| Goldstar LG TV GSMC0A0 3840x2160                                       | 1         | 0.81%   |
| Goldstar LG FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch              | 1         | 0.81%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch                 | 1         | 0.81%   |
| Goldstar 22EA53 GSM59A4 1920x1080 480x270mm 21.7-inch                  | 1         | 0.81%   |
| Eizo CS2420 ENC2741 1920x1200 520x330mm 24.2-inch                      | 1         | 0.81%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                  | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 44.44%  |
| 1366x768 (WXGA)    | 22        | 18.8%   |
| 3840x2160 (4K)     | 12        | 10.26%  |
| 1920x1200 (WUXGA)  | 7         | 5.98%   |
| 1600x900 (HD+)     | 5         | 4.27%   |
| 1280x800 (WXGA)    | 4         | 3.42%   |
| 2560x1440 (QHD)    | 3         | 2.56%   |
| 2560x1600          | 2         | 1.71%   |
| 2560x1080          | 2         | 1.71%   |
| 1680x1050 (WSXGA+) | 2         | 1.71%   |
| 1024x600           | 2         | 1.71%   |
| 1920x540           | 1         | 0.85%   |
| 1280x720 (HD)      | 1         | 0.85%   |
| 1280x1024 (SXGA)   | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 26.89%  |
| 13      | 18        | 15.13%  |
| 24      | 10        | 8.4%    |
| 27      | 8         | 6.72%   |
| 23      | 6         | 5.04%   |
| 21      | 6         | 5.04%   |
| 12      | 6         | 5.04%   |
| Unknown | 6         | 5.04%   |
| 14      | 4         | 3.36%   |
| 31      | 3         | 2.52%   |
| 17      | 3         | 2.52%   |
| 10      | 3         | 2.52%   |
| 29      | 2         | 1.68%   |
| 19      | 2         | 1.68%   |
| 18      | 2         | 1.68%   |
| 54      | 1         | 0.84%   |
| 52      | 1         | 0.84%   |
| 49      | 1         | 0.84%   |
| 46      | 1         | 0.84%   |
| 34      | 1         | 0.84%   |
| 32      | 1         | 0.84%   |
| 22      | 1         | 0.84%   |
| 20      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 37.61%  |
| 501-600     | 22        | 18.8%   |
| 201-300     | 19        | 16.24%  |
| 401-500     | 11        | 9.4%    |
| Unknown     | 6         | 5.13%   |
| 601-700     | 5         | 4.27%   |
| 351-400     | 4         | 3.42%   |
| 1001-1500   | 4         | 3.42%   |
| 701-800     | 2         | 1.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 86        | 78.9%   |
| 16/10   | 12        | 11.01%  |
| Unknown | 5         | 4.59%   |
| 4/3     | 2         | 1.83%   |
| 21/9    | 2         | 1.83%   |
| 5/4     | 1         | 0.92%   |
| 3/2     | 1         | 0.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 26        | 21.85%  |
| 201-250        | 18        | 15.13%  |
| 81-90          | 15        | 12.61%  |
| 301-350        | 9         | 7.56%   |
| 101-110        | 7         | 5.88%   |
| 61-70          | 6         | 5.04%   |
| 351-500        | 6         | 5.04%   |
| Unknown        | 6         | 5.04%   |
| 71-80          | 5         | 4.2%    |
| 251-300        | 5         | 4.2%    |
| More than 1000 | 3         | 2.52%   |
| 41-50          | 3         | 2.52%   |
| 151-200        | 3         | 2.52%   |
| 121-130        | 3         | 2.52%   |
| 141-150        | 2         | 1.68%   |
| 111-120        | 1         | 0.84%   |
| 501-1000       | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 32        | 27.35%  |
| 121-160       | 31        | 26.5%   |
| 101-120       | 31        | 26.5%   |
| 161-240       | 10        | 8.55%   |
| Unknown       | 6         | 5.13%   |
| More than 240 | 4         | 3.42%   |
| 1-50          | 3         | 2.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 88        | 48.89%  |
| 0     | 74        | 41.11%  |
| 2     | 16        | 8.89%   |
| 3     | 2         | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 99        | 39.13%  |
| Realtek Semiconductor             | 78        | 30.83%  |
| Qualcomm Atheros                  | 33        | 13.04%  |
| Broadcom                          | 21        | 8.3%    |
| Ralink Technology                 | 3         | 1.19%   |
| Edimax Technology                 | 3         | 1.19%   |
| Nvidia                            | 2         | 0.79%   |
| Mellanox Technologies             | 2         | 0.79%   |
| Marvell Technology Group          | 2         | 0.79%   |
| Xiaomi                            | 1         | 0.4%    |
| Sundance Technology Inc / IC Plus | 1         | 0.4%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.4%    |
| Samsung Electronics               | 1         | 0.4%    |
| Ralink                            | 1         | 0.4%    |
| Qualcomm                          | 1         | 0.4%    |
| NetGear                           | 1         | 0.4%    |
| IMC Networks                      | 1         | 0.4%    |
| dog hunter                        | 1         | 0.4%    |
| ADMtek                            | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 59        | 19.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 3.28%   |
| Intel Wireless 8265 / 8275                                                    | 9         | 2.95%   |
| Intel I211 Gigabit Network Connection                                         | 9         | 2.95%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 2.62%   |
| Intel Wireless 7265                                                           | 7         | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 1.97%   |
| Intel Wireless-AC 9260                                                        | 6         | 1.97%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4         | 1.31%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.31%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3         | 0.98%   |
| Intel Wireless 3160                                                           | 3         | 0.98%   |
| Intel I350 Gigabit Network Connection                                         | 3         | 0.98%   |
| Intel I210 Gigabit Network Connection                                         | 3         | 0.98%   |
| Intel Ethernet Connection I217-LM                                             | 3         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 0.98%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 3         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.66%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.66%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 0.66%   |
| Intel Wireless 8260                                                           | 2         | 0.66%   |
| Intel Wireless 7260                                                           | 2         | 0.66%   |
| Intel Wireless 3165                                                           | 2         | 0.66%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 2         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.66%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.66%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 0.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.66%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 0.66%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.33%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1         | 0.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.33%   |
| Realtek Realtek Bluetooth Adapter                                             | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 51.52%  |
| Qualcomm Atheros      | 25        | 18.94%  |
| Realtek Semiconductor | 16        | 12.12%  |
| Broadcom              | 14        | 10.61%  |
| Ralink Technology     | 3         | 2.27%   |
| Edimax Technology     | 3         | 2.27%   |
| Ralink                | 1         | 0.76%   |
| NetGear               | 1         | 0.76%   |
| IMC Networks          | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 9         | 6.77%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 6.02%   |
| Intel Wireless 7265                                                     | 7         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 4.51%   |
| Intel Wireless-AC 9260                                                  | 6         | 4.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 3.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2.26%   |
| Intel Wireless 3160                                                     | 3         | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.26%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 3         | 2.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.5%    |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.5%    |
| Intel Wireless 8260                                                     | 2         | 1.5%    |
| Intel Wireless 7260                                                     | 2         | 1.5%    |
| Intel Wireless 3165                                                     | 2         | 1.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.5%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.5%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.5%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.75%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 0.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.75%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.75%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.75%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.75%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.75%   |
| Intel WiFi Link 5100                                                    | 1         | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.75%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.75%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.75%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 1         | 0.75%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                    | 1         | 0.75%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.75%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.75%   |
| Broadcom BCM4311 802.11a/b/g                                            | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 70        | 43.21%  |
| Intel                             | 61        | 37.65%  |
| Qualcomm Atheros                  | 11        | 6.79%   |
| Broadcom                          | 10        | 6.17%   |
| Nvidia                            | 2         | 1.23%   |
| Marvell Technology Group          | 2         | 1.23%   |
| Xiaomi                            | 1         | 0.62%   |
| Sundance Technology Inc / IC Plus | 1         | 0.62%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.62%   |
| Samsung Electronics               | 1         | 0.62%   |
| Qualcomm                          | 1         | 0.62%   |
| ADMtek                            | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 59        | 35.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 5.99%   |
| Intel I211 Gigabit Network Connection                                         | 9         | 5.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7         | 4.19%   |
| Intel 82574L Gigabit Network Connection                                       | 6         | 3.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 2.4%    |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3         | 1.8%    |
| Intel I350 Gigabit Network Connection                                         | 3         | 1.8%    |
| Intel I210 Gigabit Network Connection                                         | 3         | 1.8%    |
| Intel Ethernet Connection I217-LM                                             | 3         | 1.8%    |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 1.2%    |
| Nvidia MCP79 Ethernet                                                         | 2         | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                         | 2         | 1.2%    |
| Intel Ethernet Connection (3) I218-LM                                         | 2         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 1.2%    |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 1.2%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.6%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.6%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 1         | 0.6%    |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 1         | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 0.6%    |
| Intel Ethernet Controller I225-V                                              | 1         | 0.6%    |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.6%    |
| Intel Ethernet Connection (3) I219-LM                                         | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.6%    |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.6%    |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.6%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.6%    |
| Intel 82562GT 10/100 Network Connection                                       | 1         | 0.6%    |
| Broadcom NetXtreme II BCM57711E 10-Gigabit PCIe                               | 1         | 0.6%    |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 0.6%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 1         | 0.6%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 1         | 0.6%    |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                       | 1         | 0.6%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                      | 1         | 0.6%    |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 1         | 0.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 1         | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 1         | 0.6%    |
| ADMtek NC100 Network Everywhere Fast Ethernet 10/100                          | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 154       | 54.8%   |
| WiFi     | 122       | 43.42%  |
| Unknown  | 4         | 1.42%   |
| Modem    | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 142       | 63.39%  |
| WiFi     | 82        | 36.61%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 110       | 61.11%  |
| 1     | 50        | 27.78%  |
| 0     | 10        | 5.56%   |
| 4     | 5         | 2.78%   |
| 3     | 5         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 154       | 85.08%  |
| Yes  | 27        | 14.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 58.33%  |
| Qualcomm Atheros Communications | 10        | 11.9%   |
| Realtek Semiconductor           | 6         | 7.14%   |
| Broadcom                        | 5         | 5.95%   |
| Apple                           | 4         | 4.76%   |
| IMC Networks                    | 2         | 2.38%   |
| ASUSTek Computer                | 2         | 2.38%   |
| VMware                          | 1         | 1.19%   |
| Lite-On Technology              | 1         | 1.19%   |
| Hewlett-Packard                 | 1         | 1.19%   |
| Foxconn / Hon Hai               | 1         | 1.19%   |
| Dell                            | 1         | 1.19%   |
| Cambridge Silicon Radio         | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 19        | 22.62%  |
| Intel AX200 Bluetooth                                       | 8         | 9.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 6         | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 7.14%   |
| Intel AX201 Bluetooth                                       | 5         | 5.95%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 4         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 3.57%   |
| Apple Bluetooth Host Controller                             | 3         | 3.57%   |
| Realtek  Bluetooth Adapter                                  | 2         | 2.38%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.38%   |
| VMware Virtual Bluetooth Adapter                            | 1         | 1.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1.19%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.19%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.19%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.19%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.19%   |
| Intel AX210 Bluetooth                                       | 1         | 1.19%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.19%   |
| IMC Networks Bluetooth Module                               | 1         | 1.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.19%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.19%   |
| Dell DW375 Bluetooth Module                                 | 1         | 1.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.19%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.19%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1.19%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1.19%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.19%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.19%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1.19%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1.19%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 120       | 60.3%   |
| AMD                                  | 35        | 17.59%  |
| Nvidia                               | 31        | 15.58%  |
| VMware                               | 1         | 0.5%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.5%    |
| Texas Instruments                    | 1         | 0.5%    |
| SteelSeries ApS                      | 1         | 0.5%    |
| Silicon Integrated Systems [SiS]     | 1         | 0.5%    |
| Realtek Semiconductor                | 1         | 0.5%    |
| Logitech                             | 1         | 0.5%    |
| Lenovo                               | 1         | 0.5%    |
| Ensoniq                              | 1         | 0.5%    |
| Creative Labs                        | 1         | 0.5%    |
| Corsair                              | 1         | 0.5%    |
| C-Media Electronics                  | 1         | 0.5%    |
| BEHRINGER International              | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                     | Computers | Percent |
|-----------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                           | 17        | 7.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                | 11        | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                       | 9         | 3.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                       | 9         | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                                  | 9         | 3.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                       | 9         | 3.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                          | 7         | 2.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                                   | 7         | 2.95%   |
| Intel Broadwell-U Audio Controller                                                                        | 7         | 2.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                           | 7         | 2.95%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                                       | 7         | 2.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                                | 7         | 2.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                                   | 6         | 2.53%   |
| AMD Starship/Matisse HD Audio Controller                                                                  | 6         | 2.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                              | 5         | 2.11%   |
| Intel Haswell-ULT HD Audio Controller                                                                     | 4         | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                                    | 4         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                                | 4         | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                            | 4         | 1.69%   |
| Intel 8 Series HD Audio Controller                                                                        | 4         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                        | 4         | 1.69%   |
| AMD FCH Azalia Controller                                                                                 | 4         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                            | 3         | 1.27%   |
| Nvidia High Definition Audio Controller                                                                   | 3         | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                                                             | 3         | 1.27%   |
| Nvidia GF119 HDMI Audio Controller                                                                        | 3         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                                 | 3         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                              | 3         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                          | 3         | 1.27%   |
| Nvidia TU116 High Definition Audio Controller                                                             | 2         | 0.84%   |
| Nvidia TU104 HD Audio Controller                                                                          | 2         | 0.84%   |
| Nvidia MCP79 High Definition Audio                                                                        | 2         | 0.84%   |
| Nvidia GT216 HDMI Audio Controller                                                                        | 2         | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                                                             | 2         | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                                 | 2         | 0.84%   |
| Intel CM238 HD Audio Controller                                                                           | 2         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller         | 2         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                                | 2         | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                         | 2         | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                          | 2         | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                            | 2         | 0.84%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                                | 2         | 0.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                       | 2         | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                                   | 2         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                                                  | 2         | 0.84%   |
| AMD High Definition Audio Controller                                                                      | 2         | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                              | 2         | 0.84%   |
| VMware HD Audio Controller                                                                                | 1         | 0.42%   |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                        | 1         | 0.42%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                         | 1         | 0.42%   |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                           | 1         | 0.42%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                         | 1         | 0.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                           | 1         | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                                     | 1         | 0.42%   |
| Nvidia GF116 High Definition Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GF110 High Definition Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GF108 High Definition Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GF100 High Definition Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GA104 High Definition Audio Controller                                                             | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 21.81%  |
| SK Hynix            | 31        | 16.49%  |
| Kingston            | 24        | 12.77%  |
| Unknown             | 21        | 11.17%  |
| Crucial             | 19        | 10.11%  |
| Micron Technology   | 14        | 7.45%   |
| Corsair             | 11        | 5.85%   |
| Ramaxel Technology  | 6         | 3.19%   |
| G.Skill             | 3         | 1.6%    |
| A-DATA Technology   | 3         | 1.6%    |
| Team                | 2         | 1.06%   |
| Smart               | 2         | 1.06%   |
| Unknown             | 2         | 1.06%   |
| Transcend           | 1         | 0.53%   |
| Teikon              | 1         | 0.53%   |
| Silicon Power       | 1         | 0.53%   |
| Qimonda             | 1         | 0.53%   |
| PUSKILL             | 1         | 0.53%   |
| Neo Forza           | 1         | 0.53%   |
| GOODRAM             | 1         | 0.53%   |
| Elpida              | 1         | 0.53%   |
| AMD                 | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.99%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.49%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 3         | 1.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1%      |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s              | 2         | 1%      |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1%      |
| SK Hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1%      |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 1%      |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s          | 2         | 1%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 2         | 1%      |
| Unknown                                                          | 2         | 1%      |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1067MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 400MT/s                              | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1332MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                          | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM 400MT/s                              | 1         | 0.5%    |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                       | 1         | 0.5%    |
| Unknown RAM 2G-08-10-12-1333 2GB DIMM DDR3 1333MT/s              | 1         | 0.5%    |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.5%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.5%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 1         | 0.5%    |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.5%    |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.5%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.5%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.5%    |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 1         | 0.5%    |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 0.5%    |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.5%    |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.5%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.5%    |
| SK Hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 44.64%  |
| DDR3    | 67        | 39.88%  |
| DDR2    | 8         | 4.76%   |
| DDR     | 5         | 2.98%   |
| Unknown | 5         | 2.98%   |
| LPDDR3  | 4         | 2.38%   |
| SDRAM   | 3         | 1.79%   |
| LPDDR4  | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 62.28%  |
| DIMM         | 59        | 35.33%  |
| Row Of Chips | 3         | 1.8%    |
| Unknown      | 1         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 36.11%  |
| 4096  | 49        | 27.22%  |
| 2048  | 25        | 13.89%  |
| 16384 | 24        | 13.33%  |
| 32768 | 9         | 5%      |
| 1024  | 8         | 4.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 25.84%  |
| 2400    | 21        | 11.8%   |
| 2667    | 20        | 11.24%  |
| 1333    | 19        | 10.67%  |
| 2133    | 18        | 10.11%  |
| 3200    | 13        | 7.3%    |
| 1067    | 7         | 3.93%   |
| 667     | 5         | 2.81%   |
| 2933    | 4         | 2.25%   |
| 800     | 4         | 2.25%   |
| 3000    | 3         | 1.69%   |
| 1334    | 3         | 1.69%   |
| Unknown | 3         | 1.69%   |
| 975     | 2         | 1.12%   |
| 533     | 2         | 1.12%   |
| 400     | 2         | 1.12%   |
| 4267    | 1         | 0.56%   |
| 3600    | 1         | 0.56%   |
| 2666    | 1         | 0.56%   |
| 1866    | 1         | 0.56%   |
| 1332    | 1         | 0.56%   |
| 1066    | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                                                        | 1         | 33.33%  |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 33.33%  |
| Canon LBP2900                                                                              | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 20        | 27.4%   |
| IMC Networks                  | 10        | 13.7%   |
| Realtek Semiconductor         | 8         | 10.96%  |
| Microdia                      | 7         | 9.59%   |
| Suyin                         | 6         | 8.22%   |
| Sunplus Innovation Technology | 6         | 8.22%   |
| Logitech                      | 3         | 4.11%   |
| Acer                          | 3         | 4.11%   |
| Syntek                        | 2         | 2.74%   |
| Z-Star Microelectronics       | 1         | 1.37%   |
| Valve Software                | 1         | 1.37%   |
| Silicon Motion                | 1         | 1.37%   |
| Quanta                        | 1         | 1.37%   |
| Luxvisions Innotech Limited   | 1         | 1.37%   |
| Lite-On Technology            | 1         | 1.37%   |
| Lenovo                        | 1         | 1.37%   |
| Importek                      | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 4         | 5.48%   |
| Chicony Integrated Camera                           | 4         | 5.48%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.74%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.74%   |
| Microdia Integrated Webcam                          | 2         | 2.74%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.74%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 2         | 2.74%   |
| Chicony HD WebCam                                   | 2         | 2.74%   |
| Chicony EasyCamera                                  | 2         | 2.74%   |
| Chicony Chicony USB2.0 Camera                       | 2         | 2.74%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 1.37%   |
| Valve Software 3D Camera                            | 1         | 1.37%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.37%   |
| Syntek EasyCamera                                   | 1         | 1.37%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 1.37%   |
| Suyin Integrated Camera                             | 1         | 1.37%   |
| Suyin HP Webcam-101                                 | 1         | 1.37%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.37%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.37%   |
| Suyin 1.3M HD WebCam                                | 1         | 1.37%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.37%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.37%   |
| Sunplus Integrated Camera                           | 1         | 1.37%   |
| Sunplus Dell HD Webcam                              | 1         | 1.37%   |
| Silicon Motion Web Camera                           | 1         | 1.37%   |
| Realtek USB 2 Webcam                                | 1         | 1.37%   |
| Realtek Realtek PC Camera                           | 1         | 1.37%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.37%   |
| Realtek Integrated Webcam HD                        | 1         | 1.37%   |
| Realtek Integrated Webcam                           | 1         | 1.37%   |
| Realtek HP 2.0MP High Definition Webcam             | 1         | 1.37%   |
| Quanta HD Webcam                                    | 1         | 1.37%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.37%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.37%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.37%   |
| Microdia Integrated Webcam HD                       | 1         | 1.37%   |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.37%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.37%   |
| Logitech Webcam C270                                | 1         | 1.37%   |
| Logitech HD Webcam C615                             | 1         | 1.37%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.37%   |
| Lite-On HP TrueVision HD Camera                     | 1         | 1.37%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.37%   |
| Importek Webcam-101                                 | 1         | 1.37%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.37%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.37%   |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.37%   |
| IMC Networks EasyCamera                             | 1         | 1.37%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.37%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.37%   |
| Chicony Realtek DMFT - RGB                          | 1         | 1.37%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.37%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.37%   |
| Chicony HP Universal Camera                         | 1         | 1.37%   |
| Chicony HP TrueVision HD Camera                     | 1         | 1.37%   |
| Chicony Chicony USB 2.0 Camera                      | 1         | 1.37%   |
| Acer Lenovo Integrated Webcam                       | 1         | 1.37%   |
| Acer Lenovo EasyCamera                              | 1         | 1.37%   |
| Acer Integrated Camera                              | 1         | 1.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 28.57%  |
| Synaptics                  | 4         | 28.57%  |
| Shenzhen Goodix Technology | 3         | 21.43%  |
| Upek                       | 1         | 7.14%   |
| Broadcom                   | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 3         | 21.43%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 7.14%   |
| Synaptics  WBDI                                                              | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 7.14%   |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                                                  | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 7.14%   |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 65        | 36.11%  |
| 0     | 49        | 27.22%  |
| 2     | 38        | 21.11%  |
| 3     | 19        | 10.56%  |
| 4     | 7         | 3.89%   |
| 6     | 1         | 0.56%   |
| 5     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 99        | 44.2%   |
| Net/wireless             | 45        | 20.09%  |
| Bluetooth                | 27        | 12.05%  |
| Card reader              | 15        | 6.7%    |
| Firewire controller      | 14        | 6.25%   |
| Fingerprint reader       | 14        | 6.25%   |
| Sound                    | 3         | 1.34%   |
| Network                  | 2         | 0.89%   |
| Net/ethernet             | 2         | 0.89%   |
| Storage/nvme             | 1         | 0.45%   |
| Storage/ide              | 1         | 0.45%   |
| Storage                  | 1         | 0.45%   |

