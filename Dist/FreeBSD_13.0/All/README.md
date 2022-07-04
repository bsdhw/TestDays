FreeBSD 13.0 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD_13.0/Desktop/README.md) and [notebooks](/Dist/FreeBSD_13.0/Notebook/README.md).

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

Total: 282

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 04JN2K A12                  | Server      | [550e12f317](https://bsd-hardware.info/?probe=550e12f317) | May 17, 2022 |
| Dell          | Latitude 2100               | Notebook    | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Dell          | Vostro 5590                 | Notebook    | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Acer          | Aspire ES1-132              | Notebook    | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| HP            | 2820h                       | Desktop     | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| ASUSTek       | D700SA                      | Desktop     | [e0d66ad9cf](https://bsd-hardware.info/?probe=e0d66ad9cf) | Mar 28, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d9e74758f3](https://bsd-hardware.info/?probe=d9e74758f3) | Mar 24, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Gateway       | NV55C                       | Notebook    | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [543bcf2d09](https://bsd-hardware.info/?probe=543bcf2d09) | Mar 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Gateway       | LT27                        | Notebook    | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [fbde5657e8](https://bsd-hardware.info/?probe=fbde5657e8) | Mar 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f8801c62bc](https://bsd-hardware.info/?probe=f8801c62bc) | Mar 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f1d5448b3](https://bsd-hardware.info/?probe=3f1d5448b3) | Mar 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | Notebook    | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [d45ca02f84](https://bsd-hardware.info/?probe=d45ca02f84) | Feb 24, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [7467d71c8d](https://bsd-hardware.info/?probe=7467d71c8d) | Feb 24, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| Cisco Syst... | UCSC-C3K-M4SRB 73-17622-... | Server      | [95c7aed281](https://bsd-hardware.info/?probe=95c7aed281) | Feb 16, 2022 |
| Biostar       | X470GTA                     | Desktop     | [b7fc5ef684](https://bsd-hardware.info/?probe=b7fc5ef684) | Feb 12, 2022 |
| ASUSTek       | 1215B                       | Notebook    | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Supermicro    | H11DSi                      | Server      | [4e41dc7f8b](https://bsd-hardware.info/?probe=4e41dc7f8b) | Feb 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | Notebook    | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| HP            | Notebook                    | Notebook    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4df3db0379](https://bsd-hardware.info/?probe=4df3db0379) | Jan 26, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [e95a3dd5ec](https://bsd-hardware.info/?probe=e95a3dd5ec) | Jan 10, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [c87969f2d8](https://bsd-hardware.info/?probe=c87969f2d8) | Jan 09, 2022 |
| ASRock        | Z170M Extreme4              | Desktop     | [c518ded272](https://bsd-hardware.info/?probe=c518ded272) | Jan 09, 2022 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [1b3588ab2f](https://bsd-hardware.info/?probe=1b3588ab2f) | Jan 08, 2022 |
| Dell          | Latitude E5450              | Notebook    | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
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
| Supermicro    | X7SPA-HF                    | Desktop     | [0ed5f516f4](https://bsd-hardware.info/?probe=0ed5f516f4) | Nov 21, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [8ebeac18ca](https://bsd-hardware.info/?probe=8ebeac18ca) | Nov 19, 2021 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [73774ed18e](https://bsd-hardware.info/?probe=73774ed18e) | Nov 16, 2021 |
| Dell          | G15 5510                    | Notebook    | [e9d432bc06](https://bsd-hardware.info/?probe=e9d432bc06) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [91750755e4](https://bsd-hardware.info/?probe=91750755e4) | Nov 12, 2021 |
| HP            | Compaq 6720s                | Notebook    | [06e31b2e77](https://bsd-hardware.info/?probe=06e31b2e77) | Nov 09, 2021 |
| HP            | Mini 110-1000               | Notebook    | [ef66d7a110](https://bsd-hardware.info/?probe=ef66d7a110) | Nov 09, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cc8c604fa6](https://bsd-hardware.info/?probe=cc8c604fa6) | Nov 03, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [eb5c495379](https://bsd-hardware.info/?probe=eb5c495379) | Oct 30, 2021 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [ced0819a8e](https://bsd-hardware.info/?probe=ced0819a8e) | Oct 24, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [e26c6a355d](https://bsd-hardware.info/?probe=e26c6a355d) | Oct 24, 2021 |
| Lenovo        | G580 26897SJ                | Notebook    | [da14095fb7](https://bsd-hardware.info/?probe=da14095fb7) | Oct 20, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [da31eaf836](https://bsd-hardware.info/?probe=da31eaf836) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [6ceda5d7b4](https://bsd-hardware.info/?probe=6ceda5d7b4) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Framework     | Laptop                      | Notebook    | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [76866f2db7](https://bsd-hardware.info/?probe=76866f2db7) | Oct 01, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [319470ebbd](https://bsd-hardware.info/?probe=319470ebbd) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | Notebook    | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [137654a2f8](https://bsd-hardware.info/?probe=137654a2f8) | Sep 24, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| Dell          | Latitude E7450              | Notebook    | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [d05c3ba858](https://bsd-hardware.info/?probe=d05c3ba858) | Sep 15, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [072047d3e5](https://bsd-hardware.info/?probe=072047d3e5) | Sep 12, 2021 |
| ASUSTek       | TP300LD                     | Notebook    | [e9d8f7de51](https://bsd-hardware.info/?probe=e9d8f7de51) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | Notebook    | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [30424125f5](https://bsd-hardware.info/?probe=30424125f5) | Sep 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [76da651584](https://bsd-hardware.info/?probe=76da651584) | Sep 08, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Apple         | MacBookPro5,1               | Notebook    | [2cba98f24b](https://bsd-hardware.info/?probe=2cba98f24b) | Sep 04, 2021 |
| Dell          | Latitude E6530              | Notebook    | [8dbff835d2](https://bsd-hardware.info/?probe=8dbff835d2) | Sep 02, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [28bf815655](https://bsd-hardware.info/?probe=28bf815655) | Aug 30, 2021 |
| Medion        | MS-7616                     | Desktop     | [98f0e21e6c](https://bsd-hardware.info/?probe=98f0e21e6c) | Aug 26, 2021 |
| Medion        | MS-7616                     | Desktop     | [663b50102d](https://bsd-hardware.info/?probe=663b50102d) | Aug 26, 2021 |
| HP            | 18E6                        | All in one  | [20d70ad9ba](https://bsd-hardware.info/?probe=20d70ad9ba) | Aug 26, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [0b02720fcc](https://bsd-hardware.info/?probe=0b02720fcc) | Aug 23, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [adf41eedab](https://bsd-hardware.info/?probe=adf41eedab) | Aug 13, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [4dd5f1c0c6](https://bsd-hardware.info/?probe=4dd5f1c0c6) | Aug 12, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [1c835c20cb](https://bsd-hardware.info/?probe=1c835c20cb) | Aug 09, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | Notebook    | [c3aa245b5d](https://bsd-hardware.info/?probe=c3aa245b5d) | Jul 27, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [38910aa754](https://bsd-hardware.info/?probe=38910aa754) | Jul 25, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [d6feef8717](https://bsd-hardware.info/?probe=d6feef8717) | Jul 23, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [9a3c3705d0](https://bsd-hardware.info/?probe=9a3c3705d0) | Jul 23, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [586c14dd63](https://bsd-hardware.info/?probe=586c14dd63) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [389bf7ae4b](https://bsd-hardware.info/?probe=389bf7ae4b) | Jul 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [fc6688138c](https://bsd-hardware.info/?probe=fc6688138c) | Jul 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89a9db74f9](https://bsd-hardware.info/?probe=89a9db74f9) | Jul 21, 2021 |
| Lenovo        | ThinkPad T410 2516DCU       | Notebook    | [04b19bd02a](https://bsd-hardware.info/?probe=04b19bd02a) | Jul 21, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [0d51f6e407](https://bsd-hardware.info/?probe=0d51f6e407) | Jul 19, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [8f8cc52f23](https://bsd-hardware.info/?probe=8f8cc52f23) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [8315a3b948](https://bsd-hardware.info/?probe=8315a3b948) | Jul 17, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [8780a9eb26](https://bsd-hardware.info/?probe=8780a9eb26) | Jul 17, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [fb1c3af983](https://bsd-hardware.info/?probe=fb1c3af983) | Jul 16, 2021 |
| Cisco Syst... | UCSC-C240-M3L 74-10443-0... | Desktop     | [9d729e0508](https://bsd-hardware.info/?probe=9d729e0508) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5038f75992](https://bsd-hardware.info/?probe=5038f75992) | Jul 13, 2021 |
| Lenovo        | ThinkPad X230 2325A95       | Notebook    | [94d66a0677](https://bsd-hardware.info/?probe=94d66a0677) | Jul 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [08641f83e8](https://bsd-hardware.info/?probe=08641f83e8) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9fe5dd4b75](https://bsd-hardware.info/?probe=9fe5dd4b75) | Jul 04, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [e85afd7989](https://bsd-hardware.info/?probe=e85afd7989) | Jul 04, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | Notebook    | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [7360fb3199](https://bsd-hardware.info/?probe=7360fb3199) | Jul 03, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [2c38eae6bc](https://bsd-hardware.info/?probe=2c38eae6bc) | Jul 02, 2021 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [c339174f12](https://bsd-hardware.info/?probe=c339174f12) | Jul 02, 2021 |
| Samsung       | NC10                        | Notebook    | [d33644912a](https://bsd-hardware.info/?probe=d33644912a) | Jun 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c1a27ca913](https://bsd-hardware.info/?probe=c1a27ca913) | Jun 27, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| Toshiba       | PORTEGE X20W-D              | Convertible | [1e5dc453f6](https://bsd-hardware.info/?probe=1e5dc453f6) | Jun 25, 2021 |
| Lenovo        | ThinkPad T420 4236NHG       | Notebook    | [ea00bc1f1f](https://bsd-hardware.info/?probe=ea00bc1f1f) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | Notebook    | [8c78180ff9](https://bsd-hardware.info/?probe=8c78180ff9) | Jun 20, 2021 |
| HP            | ENVY x2 Detachable PC 13    | Notebook    | [2e7a8b5be3](https://bsd-hardware.info/?probe=2e7a8b5be3) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | 00NH4P A09                  | Server      | [1098796c5f](https://bsd-hardware.info/?probe=1098796c5f) | Jun 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [692d412c0c](https://bsd-hardware.info/?probe=692d412c0c) | Jun 14, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c066194e27](https://bsd-hardware.info/?probe=c066194e27) | Jun 13, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Unknown       | Unknown                     | Soc         | [ce45b72607](https://bsd-hardware.info/?probe=ce45b72607) | Jun 11, 2021 |
| Dell          | Latitude E4300              | Notebook    | [1150e00893](https://bsd-hardware.info/?probe=1150e00893) | Jun 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [9a7adb8860](https://bsd-hardware.info/?probe=9a7adb8860) | Jun 06, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Lenovo        | ThinkPad T420 4237A12       | Notebook    | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| Sony          | SVF1421DSGW                 | Notebook    | [64f3f02018](https://bsd-hardware.info/?probe=64f3f02018) | Jun 01, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [0b3c9a332d](https://bsd-hardware.info/?probe=0b3c9a332d) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a87473149b](https://bsd-hardware.info/?probe=a87473149b) | May 31, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [82d464f2a8](https://bsd-hardware.info/?probe=82d464f2a8) | May 31, 2021 |
| System76      | Gazelle                     | Notebook    | [f9c37f2c8d](https://bsd-hardware.info/?probe=f9c37f2c8d) | May 30, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [9dd5a9eeef](https://bsd-hardware.info/?probe=9dd5a9eeef) | May 30, 2021 |
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
| MSI           | H61I-E35/W8                 | Desktop     | [d07ad10827](https://bsd-hardware.info/?probe=d07ad10827) | May 22, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [80cf566074](https://bsd-hardware.info/?probe=80cf566074) | May 21, 2021 |
| Notebook      | N7x0WU                      | Notebook    | [70760365d0](https://bsd-hardware.info/?probe=70760365d0) | May 20, 2021 |
| Dell          | Latitude E6410              | Notebook    | [c0115917d2](https://bsd-hardware.info/?probe=c0115917d2) | May 19, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [89ca4554ca](https://bsd-hardware.info/?probe=89ca4554ca) | May 18, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [c9218ee21d](https://bsd-hardware.info/?probe=c9218ee21d) | May 17, 2021 |
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
| Supermicro    | X7SPA-HF                    | Desktop     | [418cc1382c](https://bsd-hardware.info/?probe=418cc1382c) | Apr 18, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [be1821da8a](https://bsd-hardware.info/?probe=be1821da8a) | Apr 18, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3a81fe2ee4](https://bsd-hardware.info/?probe=3a81fe2ee4) | Apr 18, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [ce7b152e96](https://bsd-hardware.info/?probe=ce7b152e96) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 197       | 91.2%   |
| arm64 | 11        | 5.09%   |
| i386  | 7         | 3.24%   |
| arm   | 1         | 0.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 66        | 30.41%  |
| XFCE          | 43        | 19.82%  |
| KDE5          | 30        | 13.82%  |
| GNOME         | 19        | 8.76%   |
| TWM           | 18        | 8.29%   |
| MATE          | 12        | 5.53%   |
| i3            | 10        | 4.61%   |
| Openbox       | 7         | 3.23%   |
| Enlightenment | 3         | 1.38%   |
| LXQt          | 2         | 0.92%   |
| Cinnamon      | 2         | 0.92%   |
| AwesomeWM     | 2         | 0.92%   |
| GNUstep       | 1         | 0.46%   |
| Fluxbox       | 1         | 0.46%   |
| Compton       | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 149       | 68.66%  |
| Console | 65        | 29.95%  |
| Wayland | 3         | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 122       | 56.22%  |
| SDDM    | 31        | 14.29%  |
| SLiM    | 18        | 8.29%   |
| GDM     | 18        | 8.29%   |
| LightDM | 15        | 6.91%   |
| XDM     | 11        | 5.07%   |
| WDM     | 1         | 0.46%   |
| Ly      | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 156       | 72.22%  |
| en_US           | 18        | 8.33%   |
| Unknown         | 15        | 6.94%   |
| fr_FR           | 6         | 2.78%   |
| ru_RU           | 5         | 2.31%   |
| de_DE           | 5         | 2.31%   |
| nb_NO           | 3         | 1.39%   |
| en_GB           | 2         | 0.93%   |
| uk_UA           | 1         | 0.46%   |
| pt_PT           | 1         | 0.46%   |
| pl_PL           | 1         | 0.46%   |
| ja_JP           | 1         | 0.46%   |
| it_IT.ISO8859-1 | 1         | 0.46%   |
| es_ES           | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 145       | 66.21%  |
| BIOS | 74        | 33.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 143       | 65.9%   |
| Ufs  | 74        | 34.1%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 194       | 89.4%   |
| MBR  | 23        | 10.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 37        | 17.13%  |
| Dell                    | 37        | 17.13%  |
| ASUSTek Computer        | 29        | 13.43%  |
| Hewlett-Packard         | 17        | 7.87%   |
| Gigabyte Technology     | 12        | 5.56%   |
| ASRock                  | 11        | 5.09%   |
| MSI                     | 9         | 4.17%   |
| Unknown                 | 9         | 4.17%   |
| Acer                    | 8         | 3.7%    |
| Toshiba                 | 4         | 1.85%   |
| Raspberry Pi Foundation | 4         | 1.85%   |
| Intel                   | 4         | 1.85%   |
| Cisco Systems           | 4         | 1.85%   |
| Apple                   | 4         | 1.85%   |
| Beckhoff Automation     | 3         | 1.39%   |
| System76                | 2         | 0.93%   |
| Supermicro              | 2         | 0.93%   |
| Samsung Electronics     | 2         | 0.93%   |
| Pegatron                | 2         | 0.93%   |
| Notebook                | 2         | 0.93%   |
| Gateway                 | 2         | 0.93%   |
| Wistron                 | 1         | 0.46%   |
| Shuttle                 | 1         | 0.46%   |
| Medion                  | 1         | 0.46%   |
| Huanan                  | 1         | 0.46%   |
| GVC                     | 1         | 0.46%   |
| Google                  | 1         | 0.46%   |
| Fujitsu                 | 1         | 0.46%   |
| Framework               | 1         | 0.46%   |
| Firefly                 | 1         | 0.46%   |
| EVGA                    | 1         | 0.46%   |
| Biostar                 | 1         | 0.46%   |
| Alienware               | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 9         | 4.17%   |
| RPi Raspberry Pi                           | 4         | 1.85%   |
| ASUS All Series                            | 3         | 1.39%   |
| Dell OptiPlex 7040                         | 2         | 0.93%   |
| Cisco Systems UCSC-C240-M4L                | 2         | 0.93%   |
| Beckhoff Automation Industrial PC          | 2         | 0.93%   |
| ASUS TUF GAMING X570-PLUS                  | 2         | 0.93%   |
| ASRock B450M Pro4                          | 2         | 0.93%   |
| Wistron ProLiant ML110 G6                  | 1         | 0.46%   |
| Toshiba TECRA M11                          | 1         | 0.46%   |
| Toshiba Satellite Pro T130                 | 1         | 0.46%   |
| Toshiba Satellite L50-C                    | 1         | 0.46%   |
| Toshiba PORTEGE X20W-D                     | 1         | 0.46%   |
| System76 Lemur Pro                         | 1         | 0.46%   |
| System76 Gazelle                           | 1         | 0.46%   |
| Supermicro X7SPA-HF                        | 1         | 0.46%   |
| Supermicro Super Server                    | 1         | 0.46%   |
| Shuttle SH87R                              | 1         | 0.46%   |
| Samsung NC10                               | 1         | 0.46%   |
| Samsung 300E5M/300E5L                      | 1         | 0.46%   |
| Pegatron T12Ah                             | 1         | 0.46%   |
| Pegatron SAISHIAT2                         | 1         | 0.46%   |
| Notebook NL5xRU                            | 1         | 0.46%   |
| Notebook N7x0WU                            | 1         | 0.46%   |
| MSI Summit E13FlipEvo A11MT                | 1         | 0.46%   |
| MSI MS-7C80                                | 1         | 0.46%   |
| MSI MS-7C39                                | 1         | 0.46%   |
| MSI MS-7C02                                | 1         | 0.46%   |
| MSI MS-7B09                                | 1         | 0.46%   |
| MSI MS-7817                                | 1         | 0.46%   |
| MSI MS-7677                                | 1         | 0.46%   |
| MSI GS65 Stealth Thin 8RF                  | 1         | 0.46%   |
| MSI GL65 Leopard 10SFSK                    | 1         | 0.46%   |
| Medion MS-7616                             | 1         | 0.46%   |
| Lenovo Z51-70 80K6                         | 1         | 0.46%   |
| Lenovo Yoga 720-15IKB 80X7                 | 1         | 0.46%   |
| Lenovo V145-15AST 81MT                     | 1         | 0.46%   |
| Lenovo ThinkStation P720 30BAS1HX00        | 1         | 0.46%   |
| Lenovo ThinkPad X380 Yoga S1 20LJS1FD01    | 1         | 0.46%   |
| Lenovo ThinkPad X380 Yoga 20LH000NPG       | 1         | 0.46%   |
| Lenovo ThinkPad X270 20HMS0NS00            | 1         | 0.46%   |
| Lenovo ThinkPad X270 20HMCTO1WW            | 1         | 0.46%   |
| Lenovo ThinkPad X230 2325A95               | 1         | 0.46%   |
| Lenovo ThinkPad X220 4291PU5               | 1         | 0.46%   |
| Lenovo ThinkPad X220 4291ON5               | 1         | 0.46%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LES2RG1A     | 1         | 0.46%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 0.46%   |
| Lenovo ThinkPad T480s 20L8S1GX00           | 1         | 0.46%   |
| Lenovo ThinkPad T470 20HES0ES1F            | 1         | 0.46%   |
| Lenovo ThinkPad T440p 20AWS1JN00           | 1         | 0.46%   |
| Lenovo ThinkPad T440p 20AW0049LL           | 1         | 0.46%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 0.46%   |
| Lenovo ThinkPad T420 4236NHG               | 1         | 0.46%   |
| Lenovo ThinkPad T410 2516DCU               | 1         | 0.46%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0AA00      | 1         | 0.46%   |
| Lenovo ThinkPad R60e 0658W2M               | 1         | 0.46%   |
| Lenovo ThinkPad P73 20QRCTO1WW             | 1         | 0.46%   |
| Lenovo ThinkPad Mini10 3507A31             | 1         | 0.46%   |
| Lenovo ThinkPad Edge E320 1298RJ1          | 1         | 0.46%   |
| Lenovo ThinkPad E490 20N9001SBR            | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 25        | 11.57%  |
| Dell Latitude                  | 13        | 6.02%   |
| Dell Inspiron                  | 9         | 4.17%   |
| Unknown                        | 9         | 4.17%   |
| Acer Aspire                    | 5         | 2.31%   |
| RPi Raspberry                  | 4         | 1.85%   |
| Lenovo IdeaPad                 | 4         | 1.85%   |
| ASUS ROG                       | 4         | 1.85%   |
| HP ProLiant                    | 3         | 1.39%   |
| HP Laptop                      | 3         | 1.39%   |
| HP Compaq                      | 3         | 1.39%   |
| Dell Vostro                    | 3         | 1.39%   |
| Dell Precision                 | 3         | 1.39%   |
| Dell PowerEdge                 | 3         | 1.39%   |
| Dell OptiPlex                  | 3         | 1.39%   |
| ASUS TUF                       | 3         | 1.39%   |
| ASUS All                       | 3         | 1.39%   |
| Toshiba Satellite              | 2         | 0.93%   |
| Gigabyte X570                  | 2         | 0.93%   |
| Dell XPS                       | 2         | 0.93%   |
| Cisco Systems UCSC-C240-M4L    | 2         | 0.93%   |
| Beckhoff Automation Industrial | 2         | 0.93%   |
| ASUS PRIME                     | 2         | 0.93%   |
| ASUS P5K                       | 2         | 0.93%   |
| ASUS ASUS                      | 2         | 0.93%   |
| ASRock X570                    | 2         | 0.93%   |
| ASRock B450M                   | 2         | 0.93%   |
| Wistron ProLiant               | 1         | 0.46%   |
| Toshiba TECRA                  | 1         | 0.46%   |
| Toshiba PORTEGE                | 1         | 0.46%   |
| System76 Lemur                 | 1         | 0.46%   |
| System76 Gazelle               | 1         | 0.46%   |
| Supermicro X7SPA-HF            | 1         | 0.46%   |
| Supermicro Super               | 1         | 0.46%   |
| Shuttle SH87R                  | 1         | 0.46%   |
| Samsung NC10                   | 1         | 0.46%   |
| Samsung 300E5M                 | 1         | 0.46%   |
| Pegatron T12Ah                 | 1         | 0.46%   |
| Pegatron SAISHIAT2             | 1         | 0.46%   |
| Notebook NL5xRU                | 1         | 0.46%   |
| Notebook N7x0WU                | 1         | 0.46%   |
| MSI Summit                     | 1         | 0.46%   |
| MSI MS-7C80                    | 1         | 0.46%   |
| MSI MS-7C39                    | 1         | 0.46%   |
| MSI MS-7C02                    | 1         | 0.46%   |
| MSI MS-7B09                    | 1         | 0.46%   |
| MSI MS-7817                    | 1         | 0.46%   |
| MSI MS-7677                    | 1         | 0.46%   |
| MSI GS65                       | 1         | 0.46%   |
| MSI GL65                       | 1         | 0.46%   |
| Medion MS-7616                 | 1         | 0.46%   |
| Lenovo Z51-70                  | 1         | 0.46%   |
| Lenovo Yoga                    | 1         | 0.46%   |
| Lenovo V145-15AST              | 1         | 0.46%   |
| Lenovo ThinkStation            | 1         | 0.46%   |
| Lenovo Rescuer-15ISK           | 1         | 0.46%   |
| Lenovo G580                    | 1         | 0.46%   |
| Lenovo G505                    | 1         | 0.46%   |
| Lenovo G40-70                  | 1         | 0.46%   |
| Intel NUC8i7HNK                | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 30        | 13.89%  |
| 2018    | 26        | 12.04%  |
| 2019    | 25        | 11.57%  |
| 2021    | 23        | 10.65%  |
| 2011    | 17        | 7.87%   |
| 2015    | 14        | 6.48%   |
| 2012    | 11        | 5.09%   |
| 2010    | 11        | 5.09%   |
| 2017    | 10        | 4.63%   |
| Unknown | 10        | 4.63%   |
| 2016    | 8         | 3.7%    |
| 2013    | 8         | 3.7%    |
| 2014    | 7         | 3.24%   |
| 2008    | 7         | 3.24%   |
| 2009    | 4         | 1.85%   |
| 2006    | 3         | 1.39%   |
| 2022    | 1         | 0.46%   |
| 2005    | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 107       | 49.54%  |
| Desktop        | 76        | 35.19%  |
| System on chip | 11        | 5.09%   |
| Server         | 9         | 4.17%   |
| Convertible    | 6         | 2.78%   |
| Mini pc        | 4         | 1.85%   |
| All in one     | 3         | 1.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 214       | 99.07%  |
| Yes  | 2         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 62        | 28.57%  |
| 16.01-24.0      | 48        | 22.12%  |
| 4.01-8.0        | 34        | 15.67%  |
| 32.01-64.0      | 21        | 9.68%   |
| 64.01-256.0     | 20        | 9.22%   |
| 2.01-3.0        | 11        | 5.07%   |
| 24.01-32.0      | 6         | 2.76%   |
| 0.51-1.0        | 6         | 2.76%   |
| 3.01-4.0        | 5         | 2.3%    |
| More than 256.0 | 2         | 0.92%   |
| 1.01-2.0        | 1         | 0.46%   |
| 0.01-0.5        | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 96        | 44.24%  |
| 0.51-1.0   | 64        | 29.49%  |
| 1.01-2.0   | 29        | 13.36%  |
| 3.01-4.0   | 7         | 3.23%   |
| 2.01-3.0   | 7         | 3.23%   |
| 0          | 5         | 2.3%    |
| 4.01-8.0   | 4         | 1.84%   |
| 16.01-24.0 | 3         | 1.38%   |
| 24.01-32.0 | 1         | 0.46%   |
| 8.01-16.0  | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 119       | 54.09%  |
| 2      | 42        | 19.09%  |
| 3      | 17        | 7.73%   |
| 0      | 14        | 6.36%   |
| 4      | 8         | 3.64%   |
| 5      | 6         | 2.73%   |
| 7      | 4         | 1.82%   |
| 6      | 4         | 1.82%   |
| 14     | 2         | 0.91%   |
| 12     | 2         | 0.91%   |
| 13     | 1         | 0.45%   |
| 9      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 69.12%  |
| Yes       | 67        | 30.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 85.19%  |
| No        | 32        | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 66.67%  |
| No        | 72        | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 53.24%  |
| Yes       | 101       | 46.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 60        | 27.78%  |
| Russia      | 23        | 10.65%  |
| Germany     | 17        | 7.87%   |
| UK          | 14        | 6.48%   |
| Netherlands | 7         | 3.24%   |
| France      | 7         | 3.24%   |
| Canada      | 7         | 3.24%   |
| Brazil      | 7         | 3.24%   |
| Australia   | 5         | 2.31%   |
| Switzerland | 4         | 1.85%   |
| India       | 4         | 1.85%   |
| Czechia     | 4         | 1.85%   |
| Ukraine     | 3         | 1.39%   |
| Spain       | 3         | 1.39%   |
| Poland      | 3         | 1.39%   |
| Mexico      | 3         | 1.39%   |
| Japan       | 3         | 1.39%   |
| Bulgaria    | 3         | 1.39%   |
| Vietnam     | 2         | 0.93%   |
| Thailand    | 2         | 0.93%   |
| Norway      | 2         | 0.93%   |
| New Zealand | 2         | 0.93%   |
| Iran        | 2         | 0.93%   |
| Hungary     | 2         | 0.93%   |
| Guadeloupe  | 2         | 0.93%   |
| Finland     | 2         | 0.93%   |
| Colombia    | 2         | 0.93%   |
| Turkey      | 1         | 0.46%   |
| Sweden      | 1         | 0.46%   |
| Slovakia    | 1         | 0.46%   |
| Romania     | 1         | 0.46%   |
| Qatar       | 1         | 0.46%   |
| Portugal    | 1         | 0.46%   |
| Nepal       | 1         | 0.46%   |
| Namibia     | 1         | 0.46%   |
| Malaysia    | 1         | 0.46%   |
| Lithuania   | 1         | 0.46%   |
| Italy       | 1         | 0.46%   |
| Ireland     | 1         | 0.46%   |
| Indonesia   | 1         | 0.46%   |
| Guatemala   | 1         | 0.46%   |
| Denmark     | 1         | 0.46%   |
| China       | 1         | 0.46%   |
| Chile       | 1         | 0.46%   |
| Austria     | 1         | 0.46%   |
| Armenia     | 1         | 0.46%   |
| Argentina   | 1         | 0.46%   |
| Albania     | 1         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lexington                 | 6         | 2.75%   |
| Moscow                    | 5         | 2.29%   |
| Sofia                     | 3         | 1.38%   |
| Menlo Park                | 3         | 1.38%   |
| LГјbeck                 | 3         | 1.38%   |
| Berlin                    | 3         | 1.38%   |
| Alphen aan den Rijn       | 3         | 1.38%   |
| Yekaterinburg             | 2         | 0.92%   |
| Tehran                    | 2         | 0.92%   |
| Seattle                   | 2         | 0.92%   |
| Salem                     | 2         | 0.92%   |
| Redmond                   | 2         | 0.92%   |
| Québec                   | 2         | 0.92%   |
| Ozersk                    | 2         | 0.92%   |
| Minneapolis               | 2         | 0.92%   |
| Melbourne                 | 2         | 0.92%   |
| Le Gosier                 | 2         | 0.92%   |
| Kyiv                      | 2         | 0.92%   |
| Irkutsk                   | 2         | 0.92%   |
| Helsinki                  | 2         | 0.92%   |
| Glasgow                   | 2         | 0.92%   |
| Chelyabinsk               | 2         | 0.92%   |
| Zurich                    | 1         | 0.46%   |
| Yerevan                   | 1         | 0.46%   |
| Wenatchee                 | 1         | 0.46%   |
| Weimar                    | 1         | 0.46%   |
| Wausau                    | 1         | 0.46%   |
| Warsaw                    | 1         | 0.46%   |
| Vratsa                    | 1         | 0.46%   |
| Vostochnoe Degunino       | 1         | 0.46%   |
| Vilnius                   | 1         | 0.46%   |
| Vancouver                 | 1         | 0.46%   |
| Valladolid                | 1         | 0.46%   |
| Vadodara                  | 1         | 0.46%   |
| Vacaville                 | 1         | 0.46%   |
| Ufa                       | 1         | 0.46%   |
| Tyumen                    | 1         | 0.46%   |
| Tuklaty                   | 1         | 0.46%   |
| Tuddal                    | 1         | 0.46%   |
| Trang                     | 1         | 0.46%   |
| Toronto                   | 1         | 0.46%   |
| The Bronx                 | 1         | 0.46%   |
| Teteghem                  | 1         | 0.46%   |
| TatabÃ¡nya              | 1         | 0.46%   |
| SГЈo Paulo              | 1         | 0.46%   |
| SГЈo JosГ© dos Campos | 1         | 0.46%   |
| Sydney                    | 1         | 0.46%   |
| Swindon                   | 1         | 0.46%   |
| Sundebru                  | 1         | 0.46%   |
| Suginami-ku               | 1         | 0.46%   |
| Stuttgart                 | 1         | 0.46%   |
| St. Catharines            | 1         | 0.46%   |
| St Petersburg             | 1         | 0.46%   |
| South Yarra               | 1         | 0.46%   |
| Scottsdale                | 1         | 0.46%   |
| SarandГ«                | 1         | 0.46%   |
| Sao Vicente               | 1         | 0.46%   |
| Sao Paulo                 | 1         | 0.46%   |
| San Vicent del Raspeig    | 1         | 0.46%   |
| San Diego                 | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 78     | 17.67%  |
| Seagate             | 48        | 124    | 16%     |
| WDC                 | 40        | 84     | 13.33%  |
| Toshiba             | 27        | 35     | 9%      |
| Kingston            | 25        | 27     | 8.33%   |
| Crucial             | 19        | 21     | 6.33%   |
| Hitachi             | 11        | 26     | 3.67%   |
| Intel               | 10        | 12     | 3.33%   |
| HGST                | 8         | 11     | 2.67%   |
| A-DATA Technology   | 7         | 7      | 2.33%   |
| SanDisk             | 6         | 7      | 2%      |
| SK hynix            | 4         | 4      | 1.33%   |
| Phison              | 4         | 4      | 1.33%   |
| Micron Technology   | 4         | 4      | 1.33%   |
| Corsair             | 4         | 4      | 1.33%   |
| Fujitsu             | 3         | 4      | 1%      |
| PNY                 | 2         | 2      | 0.67%   |
| Plextor             | 2         | 3      | 0.67%   |
| LITEONIT            | 2         | 2      | 0.67%   |
| Lenovo              | 2         | 2      | 0.67%   |
| Verbatim            | 1         | 1      | 0.33%   |
| Transcend           | 1         | 1      | 0.33%   |
| TCSUNBOW            | 1         | 1      | 0.33%   |
| SSSTC               | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| Smartbuy            | 1         | 1      | 0.33%   |
| Silicon Motion      | 1         | 1      | 0.33%   |
| Patriot             | 1         | 1      | 0.33%   |
| OWC                 | 1         | 1      | 0.33%   |
| Maxtor              | 1         | 1      | 0.33%   |
| KIOXIA              | 1         | 1      | 0.33%   |
| KingSpec            | 1         | 1      | 0.33%   |
| KingDian            | 1         | 1      | 0.33%   |
| Intenso             | 1         | 1      | 0.33%   |
| Hewlett-Packard     | 1         | 2      | 0.33%   |
| Goodram             | 1         | 1      | 0.33%   |
| Gigabyte Technology | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |
| Apacer              | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 6         | 1.74%   |
| Kingston SA400S37120G 120GB        | 6         | 1.74%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 1.74%   |
| Toshiba DT01ACA100 1TB             | 5         | 1.45%   |
| Seagate ST4000DM000-1F2168 4TB     | 4         | 1.16%   |
| Samsung SSD 970 EVO Plus 250GB     | 4         | 1.16%   |
| Samsung SSD 970 EVO 500GB          | 4         | 1.16%   |
| Toshiba MQ01ABD100 1TB             | 3         | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB     | 3         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.87%   |
| Samsung SSD 970 EVO Plus 1TB       | 3         | 0.87%   |
| Samsung SSD 860 EVO 500GB          | 3         | 0.87%   |
| Samsung MZVLB256HBHQ-000L7 256GB   | 3         | 0.87%   |
| Crucial CT120BX500SSD1 120GB       | 3         | 0.87%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.58%   |
| WDC WD80EFAX-68LHPN0 8TB           | 2         | 0.58%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.58%   |
| Toshiba MG04SCA20EN 2TB            | 2         | 0.58%   |
| Seagate ST8000VN004-2M2101 8TB     | 2         | 0.58%   |
| Seagate ST4000VN000-1H4168 4TB     | 2         | 0.58%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.58%   |
| Seagate ST2000NM0023 2TB           | 2         | 0.58%   |
| Seagate ST16000NM001G-2KK103 16TB  | 2         | 0.58%   |
| Seagate ST1000NM0023 1TB           | 2         | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.58%   |
| Samsung SSD 960 EVO 500GB          | 2         | 0.58%   |
| Samsung SSD 870 EVO 1TB            | 2         | 0.58%   |
| Samsung SSD 860 QVO 1TB            | 2         | 0.58%   |
| Samsung SSD 860 EVO 1TB            | 2         | 0.58%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.58%   |
| Kingston SVP200S37A60G 64GB        | 2         | 0.58%   |
| Kingston SMS200S3120G 120GB        | 2         | 0.58%   |
| HGST HTS725032A7E630 320GB         | 2         | 0.58%   |
| HGST HTS721010A9E630 1TB           | 2         | 0.58%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.58%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 1         | 0.29%   |
| WDC WDS500G2B0B-00YS70 500GB       | 1         | 0.29%   |
| WDC WDS250G2B0A 250GB              | 1         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.29%   |
| WDC WDS120G2G0B-00EPW0 120GB       | 1         | 0.29%   |
| WDC WDS120G2G0A-00JH30 120GB       | 1         | 0.29%   |
| WDC WDS100T2B0B-00YS70 1TB         | 1         | 0.29%   |
| WDC WD80EMAZ-00WJTA0 8TB           | 1         | 0.29%   |
| WDC WD80EFZX-68UW8N0 8TB           | 1         | 0.29%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 0.29%   |
| WDC WD6003FZBX-00K5WB0 6TB         | 1         | 0.29%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 0.29%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 0.29%   |
| WDC WD5000AAKX-083CA0 500GB        | 1         | 0.29%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 1         | 0.29%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 1         | 0.29%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 0.29%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 0.29%   |
| WDC WD30EZRX-00AZ6B0 3TB           | 1         | 0.29%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.29%   |
| WDC WD2500BEVT-08A23T1 250GB       | 1         | 0.29%   |
| WDC WD2500BEVS-08VAT2 250GB        | 1         | 0.29%   |
| WDC WD20SPZX-22UA7T0 2TB           | 1         | 0.29%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 123    | 36.72%  |
| WDC                 | 30        | 72     | 23.44%  |
| Toshiba             | 22        | 30     | 17.19%  |
| Hitachi             | 11        | 26     | 8.59%   |
| HGST                | 8         | 11     | 6.25%   |
| Samsung Electronics | 5         | 6      | 3.91%   |
| Fujitsu             | 3         | 4      | 2.34%   |
| Maxtor              | 1         | 1      | 0.78%   |
| Hewlett-Packard     | 1         | 2      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 21.14%  |
| Kingston            | 22        | 24     | 17.89%  |
| Crucial             | 19        | 21     | 15.45%  |
| Intel               | 9         | 11     | 7.32%   |
| WDC                 | 6         | 7      | 4.88%   |
| SanDisk             | 6         | 7      | 4.88%   |
| A-DATA Technology   | 5         | 5      | 4.07%   |
| SK hynix            | 3         | 3      | 2.44%   |
| Corsair             | 3         | 3      | 2.44%   |
| Toshiba             | 2         | 2      | 1.63%   |
| Micron Technology   | 2         | 2      | 1.63%   |
| LITEONIT            | 2         | 2      | 1.63%   |
| Verbatim            | 1         | 1      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| TCSUNBOW            | 1         | 1      | 0.81%   |
| SSSTC               | 1         | 1      | 0.81%   |
| SPCC                | 1         | 1      | 0.81%   |
| Smartbuy            | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| Plextor             | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| OWC                 | 1         | 1      | 0.81%   |
| Lenovo              | 1         | 1      | 0.81%   |
| KingSpec            | 1         | 1      | 0.81%   |
| KingDian            | 1         | 1      | 0.81%   |
| Intenso             | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |
| Apacer              | 1         | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 108       | 275    | 40.3%   |
| SSD  | 106       | 140    | 39.55%  |
| NVMe | 54        | 66     | 20.15%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 177       | 415    | 76.62%  |
| NVMe | 54        | 66     | 23.38%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 176    | 52.99%  |
| 0.51-1.0   | 61        | 88     | 26.07%  |
| 1.01-2.0   | 16        | 34     | 6.84%   |
| 4.01-10.0  | 11        | 55     | 4.7%    |
| 3.01-4.0   | 10        | 20     | 4.27%   |
| 2.01-3.0   | 8         | 23     | 3.42%   |
| 10.01-20.0 | 4         | 19     | 1.71%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 75        | 34.56%  |
| 251-500        | 47        | 21.66%  |
| 501-1000       | 28        | 12.9%   |
| 51-100         | 22        | 10.14%  |
| 21-50          | 17        | 7.83%   |
| 1-20           | 12        | 5.53%   |
| 1001-2000      | 9         | 4.15%   |
| More than 3000 | 3         | 1.38%   |
| 2001-3000      | 3         | 1.38%   |
| Unknown        | 1         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 189       | 87.5%   |
| 21-50          | 12        | 5.56%   |
| 51-100         | 5         | 2.31%   |
| 101-250        | 4         | 1.85%   |
| More than 3000 | 2         | 0.93%   |
| 251-500        | 2         | 0.93%   |
| 1001-2000      | 1         | 0.46%   |
| Unknown        | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS120G2G0A-00JH30 120GB                     | 1         | 1      | 2.5%    |
| WDC WD7500BPVT-80HXZT3 752GB                     | 1         | 1      | 2.5%    |
| WDC WD5000BEVT-75A0RT0 500GB                     | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-083CA0 500GB                      | 1         | 1      | 2.5%    |
| WDC WD3200BPVT-75ZEST0 320GB                     | 1         | 1      | 2.5%    |
| WDC WD2500BEVT-08A23T1 250GB                     | 1         | 1      | 2.5%    |
| WDC WD20EARX-00PASB0 2TB                         | 1         | 1      | 2.5%    |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.5%    |
| WDC WD10EADS-00P8B0 1TB                          | 1         | 1      | 2.5%    |
| Toshiba THNSNK512GVN8 512GB                      | 1         | 1      | 2.5%    |
| Toshiba MQ02ABD100H 1TB                          | 1         | 1      | 2.5%    |
| Toshiba MK3261GSYN 320GB                         | 1         | 1      | 2.5%    |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 2.5%    |
| Seagate ST96812AS 64GB                           | 1         | 4      | 2.5%    |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 2.5%    |
| Seagate ST9250827AS 250GB                        | 1         | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 2.5%    |
| Seagate ST500DM002-1BC142 500GB                  | 1         | 1      | 2.5%    |
| Seagate ST380013AS 80GB                          | 1         | 2      | 2.5%    |
| Seagate ST3750528AS 752GB                        | 1         | 1      | 2.5%    |
| Seagate ST3250620AS 250GB                        | 1         | 1      | 2.5%    |
| Seagate ST31500341AS 1.5TB                       | 1         | 1      | 2.5%    |
| Seagate ST31000524AS 1TB                         | 1         | 1      | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 2.5%    |
| Seagate ST1000LM014-1EJ164 1TB                   | 1         | 1      | 2.5%    |
| Samsung Electronics SSD PM841 2.5-inch 7mm 256GB | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 840 EVO 120GB            | 1         | 1      | 2.5%    |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.5%    |
| Plextor PX-128M5S 128GB                          | 1         | 1      | 2.5%    |
| Maxtor STM3160815AS 160GB                        | 1         | 1      | 2.5%    |
| Intel SSDSCKKF256G8H 256GB                       | 1         | 1      | 2.5%    |
| Intel SSDSC2BB120G6R 120GB                       | 1         | 1      | 2.5%    |
| Intel SSDSC2BB012T7 1.2TB                        | 1         | 2      | 2.5%    |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 2.5%    |
| Hitachi HTS543225A7A384 250GB                    | 1         | 1      | 2.5%    |
| Hitachi HTS541612J9SA00 120GB                    | 1         | 1      | 2.5%    |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 2.5%    |
| HGST HDN726060ALE614 6TB                         | 1         | 2      | 2.5%    |
| Crucial CT250MX200SSD1 250GB                     | 1         | 1      | 2.5%    |
| Corsair Force 3 SSD 180GB                        | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 16     | 27.03%  |
| WDC                 | 8         | 9      | 21.62%  |
| Hitachi             | 4         | 4      | 10.81%  |
| Toshiba             | 3         | 3      | 8.11%   |
| Samsung Electronics | 3         | 3      | 8.11%   |
| Intel               | 3         | 4      | 8.11%   |
| SSSTC               | 1         | 1      | 2.7%    |
| Plextor             | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |
| HGST                | 1         | 2      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| Corsair             | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 16     | 38.46%  |
| WDC                 | 7         | 8      | 26.92%  |
| Hitachi             | 4         | 4      | 15.38%  |
| Toshiba             | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| HGST                | 1         | 2      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 34     | 68.57%  |
| SSD  | 11        | 12     | 31.43%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 181       | 426    | 82.27%  |
| Malfunc  | 34        | 46     | 15.45%  |
| Detected | 5         | 9      | 2.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 145       | 54.72%  |
| AMD                              | 38        | 14.34%  |
| Samsung Electronics              | 28        | 10.57%  |
| Broadcom / LSI                   | 8         | 3.02%   |
| ASMedia Technology               | 7         | 2.64%   |
| Marvell Technology Group         | 6         | 2.26%   |
| Phison Electronics               | 5         | 1.89%   |
| SanDisk                          | 4         | 1.51%   |
| Toshiba                          | 3         | 1.13%   |
| Silicon Motion                   | 2         | 0.75%   |
| Nvidia                           | 2         | 0.75%   |
| Micron Technology                | 2         | 0.75%   |
| Kingston Technology Company      | 2         | 0.75%   |
| JMicron Technology               | 2         | 0.75%   |
| ADATA Technology                 | 2         | 0.75%   |
| SK hynix                         | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] | 1         | 0.38%   |
| Seagate Technology               | 1         | 0.38%   |
| Lite-On Technology               | 1         | 0.38%   |
| Lenovo                           | 1         | 0.38%   |
| KIOXIA                           | 1         | 0.38%   |
| Hewlett-Packard                  | 1         | 0.38%   |
| Apple                            | 1         | 0.38%   |
| Adaptec                          | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 10.51%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 6.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 4.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 3.39%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 2.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 2.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.69%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 1.69%   |
| Unknown                                                                          | 5         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.36%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.36%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 1.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 1.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.68%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.68%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.68%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 2         | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.68%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.68%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 2         | 0.68%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                           | 2         | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 0.68%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 2         | 0.68%   |
| AMD FCH IDE Controller                                                           | 2         | 0.68%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 0.68%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 0.34%   |
| Toshiba unknown                                                                  | 1         | 0.34%   |
| Toshiba BG3 NVMe SSD Controller                                                  | 1         | 0.34%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] RAID bus controller 180 SATA/PATA  [SiS]        | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.34%   |
| Seagate FireCuda 530 SSD                                                         | 1         | 0.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.34%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.34%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 160       | 61.3%   |
| NVMe | 53        | 20.31%  |
| IDE  | 27        | 10.34%  |
| RAID | 16        | 6.13%   |
| SAS  | 4         | 1.53%   |
| SCSI | 1         | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 164       | 75.58%  |
| AMD     | 40        | 18.43%  |
| ARM     | 10        | 4.61%   |
| Unknown | 3         | 1.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz            | 5         | 2.3%    |
| ARM Cortex-A72 r0p3                          | 5         | 2.3%    |
| Intel Core i5-8350U CPU @ 1.70GHz            | 4         | 1.84%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 4         | 1.84%   |
| AMD Ryzen 7 2700 Eight-Core Processor        | 4         | 1.84%   |
| Intel CPU Version                            | 3         | 1.38%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 3         | 1.38%   |
| Intel Core i7-6700 CPU @ 3.40GHz             | 3         | 1.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 3         | 1.38%   |
| Intel Core i5-4300M CPU @ 2.60GHz            | 3         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 3         | 1.38%   |
| ARM Cortex-A53 r0p4                          | 3         | 1.38%   |
|                                              | 3         | 1.38%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 2         | 0.92%   |
| Intel Pentium 4                              | 2         | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 2         | 0.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 2         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 0.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 0.92%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 2         | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 2         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.92%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 2         | 0.92%   |
| AMD Ryzen 9 5950X 16-Core Processor          | 2         | 0.92%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 2         | 0.92%   |
| AMD Ryzen 9 3900X 12-Core Processor          | 2         | 0.92%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics  | 2         | 0.92%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.92%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz         | 1         | 0.46%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz         | 1         | 0.46%   |
| Intel Xeon CPU X5650 @ 2.67GHz               | 1         | 0.46%   |
| Intel Xeon CPU X3440 @ 2.53GHz               | 1         | 0.46%   |
| Intel Xeon CPU X3430 @ 2.40GHz               | 1         | 0.46%   |
| Intel Xeon CPU E5520 @ 2.27GHz               | 1         | 0.46%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz          | 1         | 0.46%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz          | 1         | 0.46%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz          | 1         | 0.46%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz          | 1         | 0.46%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz          | 1         | 0.46%   |
| Intel Xeon CPU E3-1275 v5 @ 3.60GHz          | 1         | 0.46%   |
| Intel Processor 5Y70 CPU @ 1.10GHz           | 1         | 0.46%   |
| Intel Pentium M                              | 1         | 0.46%   |
| Intel Pentium II                             | 1         | 0.46%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz       | 1         | 0.46%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 0.46%   |
| Intel Pentium CPU N4200 @ 1.10GHz            | 1         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.46%   |
| Intel Pentium CPU G630T @ 2.30GHz            | 1         | 0.46%   |
| Intel Pentium CPU G3420 @ 3.20GHz            | 1         | 0.46%   |
| Intel Pentium CPU G3220 @ 3.00GHz            | 1         | 0.46%   |
| Intel Pentium CPU G2030 @ 3.00GHz            | 1         | 0.46%   |
| Intel Pentium CPU G2020 @ 2.90GHz            | 1         | 0.46%   |
| Intel Pentium 4 CPU 3.40GHz                  | 1         | 0.46%   |
| Intel Pentium 4 CPU                          | 1         | 0.46%   |
| Intel Genuine CPU                            | 1         | 0.46%   |
| Intel Core i9-9900X CPU @ 3.50GHz            | 1         | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 1         | 0.46%   |
| Intel Core i7-8705G CPU @ 3.10GHz            | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 50        | 23.04%  |
| Intel Core i7          | 39        | 17.97%  |
| Intel Core i3          | 12        | 5.53%   |
| AMD Ryzen 7            | 11        | 5.07%   |
| Other                  | 10        | 4.61%   |
| Intel Xeon             | 10        | 4.61%   |
| ARM Cortex             | 10        | 4.61%   |
| Intel Pentium          | 9         | 4.15%   |
| Intel Celeron          | 9         | 4.15%   |
| AMD Ryzen 9            | 8         | 3.69%   |
| Intel Core 2 Duo       | 7         | 3.23%   |
| Intel Atom             | 6         | 2.76%   |
| Intel Pentium 4        | 4         | 1.84%   |
| AMD Ryzen 5            | 4         | 1.84%   |
| AMD Ryzen 3            | 3         | 1.38%   |
| Intel Xeon Silver      | 2         | 0.92%   |
| Intel Pentium Silver   | 2         | 0.92%   |
| Intel Core 2 Quad      | 2         | 0.92%   |
| AMD A6                 | 2         | 0.92%   |
| AMD A4                 | 2         | 0.92%   |
| Intel Pentium M        | 1         | 0.46%   |
| Intel Pentium Dual     | 1         | 0.46%   |
| Intel Genuine          | 1         | 0.46%   |
| Intel Core i9          | 1         | 0.46%   |
| Intel Core 2           | 1         | 0.46%   |
| Intel Celeron M        | 1         | 0.46%   |
| AMD Turion II Neo      | 1         | 0.46%   |
| AMD Ryzen Threadripper | 1         | 0.46%   |
| AMD FX                 | 1         | 0.46%   |
| AMD EPYC               | 1         | 0.46%   |
| AMD E                  | 1         | 0.46%   |
| AMD Athlon X4          | 1         | 0.46%   |
| AMD Athlon             | 1         | 0.46%   |
| AMD A12                | 1         | 0.46%   |
| AMD A10                | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 72        | 33.33%  |
| 4       | 70        | 32.41%  |
| Unknown | 23        | 10.65%  |
| 16      | 12        | 5.56%   |
| 6       | 9         | 4.17%   |
| 8       | 7         | 3.24%   |
| 1       | 6         | 2.78%   |
| 12      | 5         | 2.31%   |
| 24      | 4         | 1.85%   |
| 32      | 3         | 1.39%   |
| 20      | 2         | 0.93%   |
| 64      | 1         | 0.46%   |
| 28      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 197       | 90.78%  |
| 2       | 10        | 4.61%   |
| Unknown | 10        | 4.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 114       | 52.78%  |
| 1       | 76        | 35.19%  |
| Unknown | 26        | 12.04%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 17.13%  |
| Haswell       | 19        | 8.8%    |
| Skylake       | 14        | 6.48%   |
| Unknown       | 14        | 6.48%   |
| SandyBridge   | 12        | 5.56%   |
| IvyBridge     | 12        | 5.56%   |
| Westmere      | 11        | 5.09%   |
| Broadwell     | 10        | 4.63%   |
| Zen+          | 9         | 4.17%   |
| Zen 2         | 7         | 3.24%   |
| Penryn        | 7         | 3.24%   |
| Bonnell       | 7         | 3.24%   |
| Core          | 6         | 2.78%   |
| Zen 3         | 5         | 2.31%   |
| Zen           | 5         | 2.31%   |
| Silvermont    | 5         | 2.31%   |
| Goldmont plus | 5         | 2.31%   |
| Nehalem       | 4         | 1.85%   |
| Excavator     | 4         | 1.85%   |
| CometLake     | 4         | 1.85%   |
| Piledriver    | 3         | 1.39%   |
| NetBurst      | 3         | 1.39%   |
| TigerLake     | 2         | 0.93%   |
| P6            | 2         | 0.93%   |
| Jaguar        | 2         | 0.93%   |
| IceLake       | 2         | 0.93%   |
| Goldmont      | 2         | 0.93%   |
| K10 Llano     | 1         | 0.46%   |
| K10           | 1         | 0.46%   |
| Bobcat        | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 129       | 55.13%  |
| Nvidia                               | 53        | 22.65%  |
| AMD                                  | 41        | 17.52%  |
| Matrox Electronics Systems           | 9         | 3.85%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.43%   |
| ASPEED Technology                    | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 10        | 4.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.69%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.28%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.87%   |
| Intel HD Graphics 530                                                                    | 7         | 2.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 2.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.46%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 2.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.64%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.64%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.23%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.23%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.23%   |
| Intel HD Graphics 630                                                                    | 3         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.82%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.82%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.82%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.82%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.82%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.82%   |
| AMD Renoir                                                                               | 2         | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.82%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.82%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.41%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.41%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.41%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.41%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.41%   |
| Nvidia MCP7A [GeForce 9400]                                                              | 1         | 0.41%   |
| Nvidia GT218 [NVS 300]                                                                   | 1         | 0.41%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.41%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.41%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.41%   |
| Nvidia GP107GL [Quadro P600]                                                             | 1         | 0.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.41%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.41%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 88        | 40.74%  |
| 1 x Nvidia                               | 29        | 13.43%  |
| 1 x AMD                                  | 29        | 13.43%  |
| Intel + Nvidia                           | 21        | 9.72%   |
| Other                                    | 13        | 6.02%   |
| 2 x Intel                                | 13        | 6.02%   |
| 1 x Matrox                               | 9         | 4.17%   |
| Intel + AMD                              | 6         | 2.78%   |
| 2 x AMD                                  | 4         | 1.85%   |
| 2 x Nvidia                               | 1         | 0.46%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.46%   |
| AMD + Nvidia                             | 1         | 0.46%   |
| AMD + ASPEED                             | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 174       | 80.56%  |
| Proprietary | 28        | 12.96%  |
| Unknown     | 14        | 6.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 179       | 82.87%  |
| 1.01-2.0   | 8         | 3.7%    |
| 0.01-0.5   | 8         | 3.7%    |
| 3.01-4.0   | 7         | 3.24%   |
| 7.01-8.0   | 6         | 2.78%   |
| 5.01-6.0   | 3         | 1.39%   |
| 0.51-1.0   | 3         | 1.39%   |
| 2.01-3.0   | 1         | 0.46%   |
| 8.01-16.0  | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 23        | 15.97%  |
| BOE                  | 15        | 10.42%  |
| LG Display           | 14        | 9.72%   |
| Samsung Electronics  | 12        | 8.33%   |
| Dell                 | 11        | 7.64%   |
| Goldstar             | 9         | 6.25%   |
| Chimei Innolux       | 9         | 6.25%   |
| Sharp                | 6         | 4.17%   |
| Hewlett-Packard      | 5         | 3.47%   |
| Ancor Communications | 5         | 3.47%   |
| Lenovo               | 4         | 2.78%   |
| AOC                  | 4         | 2.78%   |
| InfoVision           | 3         | 2.08%   |
| Iiyama               | 3         | 2.08%   |
| Acer                 | 3         | 2.08%   |
| Toshiba              | 2         | 1.39%   |
| Sceptre Tech         | 2         | 1.39%   |
| Philips              | 2         | 1.39%   |
| BenQ                 | 2         | 1.39%   |
| ASUSTek Computer     | 2         | 1.39%   |
| Panasonic            | 1         | 0.69%   |
| LG Electronics       | 1         | 0.69%   |
| HannStar             | 1         | 0.69%   |
| Eizo                 | 1         | 0.69%   |
| CPT                  | 1         | 0.69%   |
| CKL                  | 1         | 0.69%   |
| Apple                | 1         | 0.69%   |
| AGO                  | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 1.37%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 1.37%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.68%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 0.68%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.68%   |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 0.68%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 0.68%   |
| Sceptre Tech Sceptre E20 SPT080D 1600x900 410x280mm 19.5-inch          | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0236 2560x1600 640x400mm 29.7-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1         | 0.68%   |
| Samsung Electronics S24E510C SAM0C61 1920x1080 520x300mm 23.6-inch     | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 1020x570mm 46.0-inch | 1         | 0.68%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch     | 1         | 0.68%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 510x290mm 23.1-inch                | 1         | 0.68%   |
| Philips LCD Monitor PHLC050 1366x768 410x230mm 18.5-inch               | 1         | 0.68%   |
| Philips 190S PHL083F 1280x1024 380x300mm 19.1-inch                     | 1         | 0.68%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                      | 1         | 0.68%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.68%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0314 1366x768 290x160mm 13.0-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD02D9 1920x1080 340x190mm 15.3-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD0214 1600x900 350x190mm 15.7-inch            | 1         | 0.68%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1         | 0.68%   |
| Lenovo LCD Monitor LEN40C1 1280x720 220x130mm 10.1-inch                | 1         | 0.68%   |
| Lenovo LCD Monitor LEN4040 1024x768 300x230mm 14.9-inch                | 1         | 0.68%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 0.68%   |
| InfoVision LCD Monitor IVO0536 1920x1080 290x170mm 13.2-inch           | 1         | 0.68%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x160mm 13.0-inch            | 1         | 0.68%   |
| InfoVision LCD Monitor IVO04E5 1366x768 280x160mm 12.7-inch            | 1         | 0.68%   |
| Iiyama PLX2483H IVM6114 1920x1080 530x300mm 24.0-inch                  | 1         | 0.68%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                   | 1         | 0.68%   |
| Iiyama PL2209HD IVM560B 1920x1080 480x270mm 21.7-inch                  | 1         | 0.68%   |
| Hewlett-Packard Z24nf HWP3209 1920x1080 530x300mm 24.0-inch            | 1         | 0.68%   |
| Hewlett-Packard LCD Monitor HPN401E 1920x1080 480x270mm 21.7-inch      | 1         | 0.68%   |
| Hewlett-Packard HPQ 800 AIO HWP1080 1920x1080 510x290mm 23.1-inch      | 1         | 0.68%   |
| Hewlett-Packard 24xw HWP3256 1920x1080 530x300mm 24.0-inch             | 1         | 0.68%   |
| Hewlett-Packard 24ea HPN3393 1920x1080 530x300mm 24.0-inch             | 1         | 0.68%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch              | 1         | 0.68%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                   | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 43.17%  |
| 1366x768 (WXGA)    | 28        | 20.14%  |
| 3840x2160 (4K)     | 12        | 8.63%   |
| 1920x1200 (WUXGA)  | 9         | 6.47%   |
| 1600x900 (HD+)     | 7         | 5.04%   |
| 1280x800 (WXGA)    | 4         | 2.88%   |
| 2560x1440 (QHD)    | 3         | 2.16%   |
| 1280x1024 (SXGA)   | 3         | 2.16%   |
| 1024x600           | 3         | 2.16%   |
| 2560x1600          | 2         | 1.44%   |
| 2560x1080          | 2         | 1.44%   |
| 1680x1050 (WSXGA+) | 2         | 1.44%   |
| 1280x720 (HD)      | 2         | 1.44%   |
| 1920x540           | 1         | 0.72%   |
| 1024x768 (XGA)     | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 25.35%  |
| 13      | 26        | 18.31%  |
| 24      | 13        | 9.15%   |
| 27      | 8         | 5.63%   |
| 23      | 8         | 5.63%   |
| 21      | 6         | 4.23%   |
| 12      | 6         | 4.23%   |
| Unknown | 6         | 4.23%   |
| 19      | 5         | 3.52%   |
| 31      | 4         | 2.82%   |
| 14      | 4         | 2.82%   |
| 10      | 4         | 2.82%   |
| 29      | 3         | 2.11%   |
| 17      | 3         | 2.11%   |
| 18      | 2         | 1.41%   |
| 64      | 1         | 0.7%    |
| 52      | 1         | 0.7%    |
| 49      | 1         | 0.7%    |
| 46      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 32      | 1         | 0.7%    |
| 22      | 1         | 0.7%    |
| 20      | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 54        | 38.57%  |
| 501-600     | 27        | 19.29%  |
| 201-300     | 22        | 15.71%  |
| 401-500     | 12        | 8.57%   |
| 601-700     | 7         | 5%      |
| 351-400     | 6         | 4.29%   |
| Unknown     | 6         | 4.29%   |
| 1001-1500   | 4         | 2.86%   |
| 701-800     | 2         | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 79.07%  |
| 16/10   | 14        | 10.85%  |
| Unknown | 5         | 3.88%   |
| 5/4     | 3         | 2.33%   |
| 4/3     | 2         | 1.55%   |
| 21/9    | 2         | 1.55%   |
| 3/2     | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 29        | 20.42%  |
| 201-250        | 23        | 16.2%   |
| 81-90          | 22        | 15.49%  |
| 301-350        | 9         | 6.34%   |
| 351-500        | 8         | 5.63%   |
| 101-110        | 8         | 5.63%   |
| 71-80          | 6         | 4.23%   |
| 61-70          | 6         | 4.23%   |
| 151-200        | 6         | 4.23%   |
| Unknown        | 6         | 4.23%   |
| 251-300        | 5         | 3.52%   |
| 41-50          | 4         | 2.82%   |
| More than 1000 | 3         | 2.11%   |
| 121-130        | 3         | 2.11%   |
| 141-150        | 2         | 1.41%   |
| 111-120        | 1         | 0.7%    |
| 501-1000       | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 30%     |
| 101-120       | 37        | 26.43%  |
| 121-160       | 36        | 25.71%  |
| 161-240       | 11        | 7.86%   |
| Unknown       | 6         | 4.29%   |
| More than 240 | 4         | 2.86%   |
| 1-50          | 4         | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 105       | 48.39%  |
| 0     | 91        | 41.94%  |
| 2     | 19        | 8.76%   |
| 3     | 2         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 114       | 37.87%  |
| Realtek Semiconductor             | 93        | 30.9%   |
| Qualcomm Atheros                  | 37        | 12.29%  |
| Broadcom                          | 26        | 8.64%   |
| Ralink Technology                 | 4         | 1.33%   |
| Samsung Electronics               | 3         | 1%      |
| Marvell Technology Group          | 3         | 1%      |
| Edimax Technology                 | 3         | 1%      |
| Nvidia                            | 2         | 0.66%   |
| Mellanox Technologies             | 2         | 0.66%   |
| Cisco Systems                     | 2         | 0.66%   |
| Xiaomi                            | 1         | 0.33%   |
| TP-Link                           | 1         | 0.33%   |
| Sundance Technology Inc / IC Plus | 1         | 0.33%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.33%   |
| Ralink                            | 1         | 0.33%   |
| Qualcomm                          | 1         | 0.33%   |
| NetGear                           | 1         | 0.33%   |
| MediaTek                          | 1         | 0.33%   |
| IMC Networks                      | 1         | 0.33%   |
| dog hunter                        | 1         | 0.33%   |
| Apple                             | 1         | 0.33%   |
| ADMtek                            | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 71        | 19.14%  |
| Intel Wireless 8265 / 8275                                                    | 12        | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11        | 2.96%   |
| Intel I211 Gigabit Network Connection                                         | 9         | 2.43%   |
| Intel Wireless 7265                                                           | 8         | 2.16%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8         | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 7         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 6         | 1.62%   |
| Intel Wireless-AC 9260                                                        | 6         | 1.62%   |
| Intel Ethernet Connection (4) I219-LM                                         | 5         | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4         | 1.08%   |
| Intel Wireless 7260                                                           | 4         | 1.08%   |
| Intel I350 Gigabit Network Connection                                         | 4         | 1.08%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 1.08%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 1.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 1.08%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 4         | 1.08%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3         | 0.81%   |
| Ralink RT5370 Wireless Adapter                                                | 3         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 0.81%   |
| Intel Wireless 8260                                                           | 3         | 0.81%   |
| Intel Wireless 3160                                                           | 3         | 0.81%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.81%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                | 3         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2         | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 0.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.54%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 2         | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2         | 0.54%   |
| Intel Wireless 3165                                                           | 2         | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.54%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.54%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.54%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 0.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.54%   |
| Cisco Systems VIC Ethernet NIC                                                | 2         | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.54%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 0.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.54%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 0.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 51.59%  |
| Qualcomm Atheros      | 26        | 16.56%  |
| Realtek Semiconductor | 22        | 14.01%  |
| Broadcom              | 17        | 10.83%  |
| Ralink Technology     | 4         | 2.55%   |
| Edimax Technology     | 3         | 1.91%   |
| TP-Link               | 1         | 0.64%   |
| Ralink                | 1         | 0.64%   |
| NetGear               | 1         | 0.64%   |
| IMC Networks          | 1         | 0.64%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 12        | 7.59%   |
| Intel Wireless 7265                                                     | 8         | 5.06%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 5.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 4.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.8%    |
| Intel Wireless-AC 9260                                                  | 6         | 3.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 2.53%   |
| Intel Wireless 7260                                                     | 4         | 2.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.53%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 1.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.9%    |
| Intel Wireless 8260                                                     | 3         | 1.9%    |
| Intel Wireless 3160                                                     | 3         | 1.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.9%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 3         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.27%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.27%   |
| Intel Wireless 3165                                                     | 2         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.27%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.63%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.63%   |
| Realtek Realtek Bluetooth Adapter                                       | 1         | 0.63%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC                    | 1         | 0.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.63%   |
| Ralink RT2500 Wireless 802.11bg                                         | 1         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.63%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.63%   |
| Intel WiFi Link 5100                                                    | 1         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.63%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.63%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.63%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.63%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 84        | 42.21%  |
| Intel                             | 70        | 35.18%  |
| Qualcomm Atheros                  | 15        | 7.54%   |
| Broadcom                          | 14        | 7.04%   |
| Samsung Electronics               | 3         | 1.51%   |
| Marvell Technology Group          | 3         | 1.51%   |
| Nvidia                            | 2         | 1.01%   |
| Cisco Systems                     | 2         | 1.01%   |
| Xiaomi                            | 1         | 0.5%    |
| Sundance Technology Inc / IC Plus | 1         | 0.5%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.5%    |
| Qualcomm                          | 1         | 0.5%    |
| Apple                             | 1         | 0.5%    |
| ADMtek                            | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 71        | 34.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 11        | 5.34%   |
| Intel I211 Gigabit Network Connection                                         | 9         | 4.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8         | 3.88%   |
| Intel Ethernet Connection (4) I219-LM                                         | 5         | 2.43%   |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 2.43%   |
| Intel I350 Gigabit Network Connection                                         | 4         | 1.94%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 1.94%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.94%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.94%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 1.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3         | 1.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 1.46%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.97%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.97%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2         | 0.97%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.97%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.97%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 0.97%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.97%   |
| Cisco Systems VIC Ethernet NIC                                                | 2         | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.97%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.49%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                    | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.49%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                    | 1         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 1         | 0.49%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1         | 0.49%   |
| Intel Ethernet Controller I225-V                                              | 1         | 0.49%   |
| Intel Ethernet Connection I219-LM                                             | 1         | 0.49%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 0.49%   |
| Intel Ethernet Connection (6) I219-LM                                         | 1         | 0.49%   |
| Intel Ethernet Connection (3) I219-LM                                         | 1         | 0.49%   |
| Intel Ethernet Connection (3) I218-V                                          | 1         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                          | 1         | 0.49%   |
| Intel Ethernet Connection (12) I219-V                                         | 1         | 0.49%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.49%   |
| Intel 82573L Gigabit Ethernet Controller                                      | 1         | 0.49%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 1         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                                      | 1         | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 1         | 0.49%   |
| Intel 82562GT 10/100 Network Connection                                       | 1         | 0.49%   |
| Broadcom NetXtreme II BCM57711E 10-Gigabit PCIe                               | 1         | 0.49%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 1         | 0.49%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 185       | 54.9%   |
| WiFi     | 145       | 43.03%  |
| Unknown  | 6         | 1.78%   |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 164       | 63.32%  |
| WiFi     | 95        | 36.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 132       | 60.83%  |
| 1     | 59        | 27.19%  |
| 0     | 12        | 5.53%   |
| 4     | 7         | 3.23%   |
| 3     | 7         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 190       | 87.56%  |
| Yes  | 27        | 12.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 58%     |
| Qualcomm Atheros Communications | 10        | 10%     |
| Realtek Semiconductor           | 9         | 9%      |
| Broadcom                        | 5         | 5%      |
| IMC Networks                    | 4         | 4%      |
| Apple                           | 4         | 4%      |
| Cambridge Silicon Radio         | 3         | 3%      |
| ASUSTek Computer                | 2         | 2%      |
| Toshiba                         | 1         | 1%      |
| Lite-On Technology              | 1         | 1%      |
| Hewlett-Packard                 | 1         | 1%      |
| Foxconn / Hon Hai               | 1         | 1%      |
| Dell                            | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 23%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 8%      |
| Intel AX200 Bluetooth                                       | 8         | 8%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 6         | 6%      |
| Intel AX201 Bluetooth                                       | 5         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 4%      |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 4         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 4%      |
| Realtek  Bluetooth Adapter                                  | 3         | 3%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 3%      |
| Apple Bluetooth Host Controller                             | 3         | 3%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2%      |
| Intel AX210 Bluetooth                                       | 2         | 2%      |
| IMC Networks Bluetooth module                               | 2         | 2%      |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 1%      |
| Realtek  Bluetooth 4.0 Adapter                              | 1         | 1%      |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1%      |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 1%      |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1%      |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1%      |
| IMC Networks Wireless_Device                                | 1         | 1%      |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1%      |
| Dell DW375 Bluetooth Module                                 | 1         | 1%      |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1%      |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1%      |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 1%      |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 1%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 144       | 61.02%  |
| AMD                                             | 44        | 18.64%  |
| Nvidia                                          | 32        | 13.56%  |
| Logitech                                        | 2         | 0.85%   |
| Creative Labs                                   | 2         | 0.85%   |
| C-Media Electronics                             | 2         | 0.85%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.42%   |
| Texas Instruments                               | 1         | 0.42%   |
| SteelSeries ApS                                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.42%   |
| Realtek Semiconductor                           | 1         | 0.42%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.42%   |
| Lenovo                                          | 1         | 0.42%   |
| Ensoniq                                         | 1         | 0.42%   |
| Corsair                                         | 1         | 0.42%   |
| BEHRINGER International                         | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                     | Computers | Percent |
|-----------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                           | 21        | 7.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                                | 12        | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                                       | 10        | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                                       | 10        | 3.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                                  | 10        | 3.51%   |
| AMD Family 17h/19h HD Audio Controller                                                                    | 10        | 3.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                                   | 9         | 3.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                       | 9         | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                          | 8         | 2.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                                   | 8         | 2.81%   |
| Intel Broadwell-U Audio Controller                                                                        | 8         | 2.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                            | 7         | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                           | 7         | 2.46%   |
| AMD Starship/Matisse HD Audio Controller                                                                  | 7         | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                                | 7         | 2.46%   |
| Intel Haswell-ULT HD Audio Controller                                                                     | 5         | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                              | 5         | 1.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                              | 5         | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                        | 5         | 1.75%   |
| AMD FCH Azalia Controller                                                                                 | 5         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                                    | 4         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                                | 4         | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                        | 4         | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                          | 4         | 1.4%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                              | 4         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                            | 3         | 1.05%   |
| Nvidia High Definition Audio Controller                                                                   | 3         | 1.05%   |
| Nvidia GP108 High Definition Audio Controller                                                             | 3         | 1.05%   |
| Nvidia GF119 HDMI Audio Controller                                                                        | 3         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                                 | 3         | 1.05%   |
| Intel CM238 HD Audio Controller                                                                           | 3         | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                       | 3         | 1.05%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                                   | 3         | 1.05%   |
| AMD High Definition Audio Controller                                                                      | 3         | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                                                             | 2         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                                                          | 2         | 0.7%    |
| Nvidia MCP79 High Definition Audio                                                                        | 2         | 0.7%    |
| Nvidia GT216 HDMI Audio Controller                                                                        | 2         | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                                                             | 2         | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                                     | 2         | 0.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                               | 2         | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                                 | 2         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                         | 2         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller         | 2         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                                | 2         | 0.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                         | 2         | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                          | 2         | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                            | 2         | 0.7%    |
| Intel 200 Series PCH HD Audio                                                                             | 2         | 0.7%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                                | 2         | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                                   | 2         | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                                                  | 2         | 0.7%    |
| Thesycon Systemsoftware & Consulting Topping DX3 Pro Audio Control                                        | 1         | 0.35%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                         | 1         | 0.35%   |
| SteelSeries ApS Arctis Pro Wireless Arctis Pro Wireless Chat Arctis Pro Wireless Game Arctis Pro Wireless | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                           | 1         | 0.35%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                                                         | 1         | 0.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                           | 1         | 0.35%   |
| Nvidia GF116 High Definition Audio Controller                                                             | 1         | 0.35%   |
| Nvidia GF110 High Definition Audio Controller                                                             | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 52        | 22.51%  |
| SK hynix            | 42        | 18.18%  |
| Unknown             | 31        | 13.42%  |
| Kingston            | 25        | 10.82%  |
| Crucial             | 21        | 9.09%   |
| Micron Technology   | 17        | 7.36%   |
| Corsair             | 11        | 4.76%   |
| Ramaxel Technology  | 6         | 2.6%    |
| A-DATA Technology   | 5         | 2.16%   |
| G.Skill             | 4         | 1.73%   |
| Team                | 2         | 0.87%   |
| Smart               | 2         | 0.87%   |
| Goodram             | 2         | 0.87%   |
| Transcend           | 1         | 0.43%   |
| Teikon              | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| Qimonda             | 1         | 0.43%   |
| PUSKILL             | 1         | 0.43%   |
| Neo Forza           | 1         | 0.43%   |
| Nanya Technology    | 1         | 0.43%   |
| Kreton              | 1         | 0.43%   |
| GeIL                | 1         | 0.43%   |
| Elpida              | 1         | 0.43%   |
| AMD                 | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 31        | 12.5%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.21%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 3         | 1.21%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.21%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 3         | 1.21%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s              | 2         | 0.81%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.81%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.81%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.81%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s          | 2         | 0.81%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s              | 1         | 0.4%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.4%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 1         | 0.4%    |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.4%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.4%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.4%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.4%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.4%    |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.4%    |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.4%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2133MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2133MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.4%    |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s            | 1         | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.4%    |
| SK hynix RAM HMA81GR7CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 1         | 0.4%    |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.4%    |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.4%    |
| Silicon Power RAM DCLT4GN128O 4GB DIMM DDR3 1333MT/s             | 1         | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.4%    |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 0.4%    |
| Samsung RAM Module 2GB SODIMM 667MT/s                            | 1         | 0.4%    |
| Samsung RAM Module 16GB DIMM DDR3 1600MT/s                       | 1         | 0.4%    |
| Samsung RAM M473B5273DH0-YK0 4GB SODIMM DDR3 1333MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5673DZ1-CF8 2GB SODIMM DDR3 1066MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s            | 1         | 0.4%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 92        | 45.1%   |
| DDR3    | 78        | 38.24%  |
| DDR2    | 12        | 5.88%   |
| Unknown | 7         | 3.43%   |
| LPDDR3  | 5         | 2.45%   |
| DDR     | 5         | 2.45%   |
| SDRAM   | 3         | 1.47%   |
| LPDDR4  | 2         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 123       | 60.29%  |
| DIMM         | 74        | 36.27%  |
| Row Of Chips | 5         | 2.45%   |
| Chip         | 1         | 0.49%   |
| Unknown      | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 35.29%  |
| 4096  | 59        | 26.7%   |
| 16384 | 33        | 14.93%  |
| 2048  | 31        | 14.03%  |
| 1024  | 11        | 4.98%   |
| 32768 | 9         | 4.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 22.77%  |
| 2400    | 28        | 12.5%   |
| 2667    | 24        | 10.71%  |
| 2133    | 24        | 10.71%  |
| 1333    | 20        | 8.93%   |
| 3200    | 19        | 8.48%   |
| 1067    | 9         | 4.02%   |
| 800     | 9         | 4.02%   |
| 667     | 6         | 2.68%   |
| 1334    | 5         | 2.23%   |
| 3000    | 4         | 1.79%   |
| 2933    | 3         | 1.34%   |
| 2666    | 3         | 1.34%   |
| 533     | 3         | 1.34%   |
| Unknown | 3         | 1.34%   |
| 4267    | 2         | 0.89%   |
| 1867    | 2         | 0.89%   |
| 975     | 2         | 0.89%   |
| 400     | 2         | 0.89%   |
| 4800    | 1         | 0.45%   |
| 3600    | 1         | 0.45%   |
| 1866    | 1         | 0.45%   |
| 1332    | 1         | 0.45%   |
| 1066    | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                                                        | 1         | 33.33%  |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 33.33%  |
| Canon LBP2900                                                                              | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 24        | 26.37%  |
| IMC Networks                  | 13        | 14.29%  |
| Microdia                      | 11        | 12.09%  |
| Realtek Semiconductor         | 9         | 9.89%   |
| Suyin                         | 7         | 7.69%   |
| Sunplus Innovation Technology | 6         | 6.59%   |
| Acer                          | 5         | 5.49%   |
| Logitech                      | 3         | 3.3%    |
| Syntek                        | 2         | 2.2%    |
| Quanta                        | 2         | 2.2%    |
| Lite-On Technology            | 2         | 2.2%    |
| Z-Star Microelectronics       | 1         | 1.1%    |
| Valve Software                | 1         | 1.1%    |
| Silicon Motion                | 1         | 1.1%    |
| Luxvisions Innotech Limited   | 1         | 1.1%    |
| Lenovo                        | 1         | 1.1%    |
| Importek                      | 1         | 1.1%    |
| ALi                           | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 5         | 5.49%   |
| Chicony Integrated Camera                           | 5         | 5.49%   |
| Microdia Integrated Webcam                          | 4         | 4.4%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.3%    |
| Chicony HD WebCam                                   | 3         | 3.3%    |
| Suyin 1.3M HD WebCam                                | 2         | 2.2%    |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.2%    |
| Realtek Integrated_Webcam_HD                        | 2         | 2.2%    |
| Microdia Integrated_Webcam_HD                       | 2         | 2.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 2         | 2.2%    |
| Chicony HP TrueVision HD Camera                     | 2         | 2.2%    |
| Chicony EasyCamera                                  | 2         | 2.2%    |
| Chicony Chicony USB2.0 Camera                       | 2         | 2.2%    |
| Z-Star Namuga 1.3M Webcam                           | 1         | 1.1%    |
| Valve Software 3D Camera                            | 1         | 1.1%    |
| Syntek Lenovo EasyCamera                            | 1         | 1.1%    |
| Syntek EasyCamera                                   | 1         | 1.1%    |
| Suyin Lenovo Integrated Webcam                      | 1         | 1.1%    |
| Suyin Integrated Camera                             | 1         | 1.1%    |
| Suyin HP Webcam-101                                 | 1         | 1.1%    |
| Suyin Asus Integrated Webcam                        | 1         | 1.1%    |
| Suyin Acer Crystal Eye webcam                       | 1         | 1.1%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.1%    |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 1.1%    |
| Sunplus Integrated Camera                           | 1         | 1.1%    |
| Sunplus Dell HD Webcam                              | 1         | 1.1%    |
| Silicon Motion Web Camera                           | 1         | 1.1%    |
| Realtek USB 2 Webcam                                | 1         | 1.1%    |
| Realtek Realtek PC Camera                           | 1         | 1.1%    |
| Realtek Lenovo EasyCamera                           | 1         | 1.1%    |
| Realtek Integrated Webcam HD                        | 1         | 1.1%    |
| Realtek Integrated Webcam                           | 1         | 1.1%    |
| Realtek HP 2.0MP High Definition Webcam             | 1         | 1.1%    |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1.1%    |
| Quanta VGA WebCam                                   | 1         | 1.1%    |
| Quanta HD Webcam                                    | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.1%    |
| Microdia Integrated Webcam HD                       | 1         | 1.1%    |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.1%    |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.1%    |
| Logitech Webcam C270                                | 1         | 1.1%    |
| Logitech HD Webcam C615                             | 1         | 1.1%    |
| Logitech HD Pro Webcam C920                         | 1         | 1.1%    |
| Lite-On Integrated Camera                           | 1         | 1.1%    |
| Lite-On HP TrueVision HD Camera                     | 1         | 1.1%    |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 1.1%    |
| Importek Webcam-101                                 | 1         | 1.1%    |
| IMC Networks UVC VGA Webcam                         | 1         | 1.1%    |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.1%    |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.1%    |
| IMC Networks USB2.0 UVC 2M WebCam                   | 1         | 1.1%    |
| IMC Networks EasyCamera                             | 1         | 1.1%    |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.1%    |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 1.1%    |
| Chicony Sonix ST50220 USB Video Camera              | 1         | 1.1%    |
| Chicony Realtek DMFT - RGB                          | 1         | 1.1%    |
| Chicony Lenovo EasyCamera                           | 1         | 1.1%    |
| Chicony HP Wide Vision HD Camera                    | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 30%     |
| Synaptics                  | 6         | 30%     |
| Shenzhen Goodix Technology | 4         | 20%     |
| Upek                       | 1         | 5%      |
| LighTuning Technology      | 1         | 5%      |
| Broadcom                   | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 4         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 15%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 5%      |
| Synaptics  WBDI                                                              | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 5%      |
| Shenzhen Goodix  FingerPrint Device                                          | 1         | 5%      |
| Shenzhen Goodix FingerPrint                                                  | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 5%      |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 74        | 34.1%   |
| 0     | 59        | 27.19%  |
| 2     | 48        | 22.12%  |
| 3     | 24        | 11.06%  |
| 4     | 9         | 4.15%   |
| 5     | 2         | 0.92%   |
| 6     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 119       | 43.75%  |
| Net/wireless             | 54        | 19.85%  |
| Bluetooth                | 31        | 11.4%   |
| Fingerprint reader       | 20        | 7.35%   |
| Card reader              | 18        | 6.62%   |
| Firewire controller      | 16        | 5.88%   |
| Net/ethernet             | 5         | 1.84%   |
| Sound                    | 3         | 1.1%    |
| Network                  | 3         | 1.1%    |
| Storage/nvme             | 1         | 0.37%   |
| Storage/ide              | 1         | 0.37%   |
| Storage                  | 1         | 0.37%   |

