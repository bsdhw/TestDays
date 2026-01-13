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

Total: 284

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Toshiba       | Satellite L955              | Notebook    | [08a58feb06](https://bsd-hardware.info/?probe=08a58feb06) | Apr 13, 2025 |
| Shuttle       | DS20U                       | Desktop     | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| Acer          | Aspire 4552G                | Notebook    | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [070ccc68f8](https://bsd-hardware.info/?probe=070ccc68f8) | Jul 15, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [7f4fa7f74d](https://bsd-hardware.info/?probe=7f4fa7f74d) | Jul 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
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
| MSI           | H81M-P33                    | Desktop     | [da31eaf836](https://bsd-hardware.info/?probe=da31eaf836) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [6ceda5d7b4](https://bsd-hardware.info/?probe=6ceda5d7b4) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d6c59472e5](https://bsd-hardware.info/?probe=d6c59472e5) | Oct 15, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Framework     | Laptop                      | Notebook    | [1e67a5d922](https://bsd-hardware.info/?probe=1e67a5d922) | Oct 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [1c4cf7c21c](https://bsd-hardware.info/?probe=1c4cf7c21c) | Sep 30, 2021 |
| Apple         | MacBookPro13,2              | Notebook    | [0bf74dea55](https://bsd-hardware.info/?probe=0bf74dea55) | Sep 30, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| Dell          | Latitude E7450              | Notebook    | [4f1e40ad63](https://bsd-hardware.info/?probe=4f1e40ad63) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [22c1aefeab](https://bsd-hardware.info/?probe=22c1aefeab) | Sep 19, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [ef8eafa662](https://bsd-hardware.info/?probe=ef8eafa662) | Sep 18, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
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
| Raspberry ... | Raspberry Pi                | Soc         | [951c3e534c](https://bsd-hardware.info/?probe=951c3e534c) | May 23, 2021 |
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
| Unknown       | Unknown                     | Desktop     | [9ff0fb7df4](https://bsd-hardware.info/?probe=9ff0fb7df4) | May 01, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [2713d38658](https://bsd-hardware.info/?probe=2713d38658) | May 01, 2021 |
| Beckhoff A... | CB3056 G4                   | Desktop     | [120665d4d3](https://bsd-hardware.info/?probe=120665d4d3) | Apr 30, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [47221a4d1d](https://bsd-hardware.info/?probe=47221a4d1d) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [91418a4965](https://bsd-hardware.info/?probe=91418a4965) | Apr 30, 2021 |
| Dell          | 0FJ030                      | Desktop     | [7bee24ee8a](https://bsd-hardware.info/?probe=7bee24ee8a) | Apr 30, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [1653ea52ce](https://bsd-hardware.info/?probe=1653ea52ce) | Apr 29, 2021 |
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
| MSI           | H81M-P33                    | Desktop     | [be1821da8a](https://bsd-hardware.info/?probe=be1821da8a) | Apr 18, 2021 |
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 202       | 90.18%  |
| arm64 | 12        | 5.36%   |
| i386  | 9         | 4.02%   |
| arm   | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 67        | 29.78%  |
| XFCE          | 44        | 19.56%  |
| KDE5          | 33        | 14.67%  |
| TWM           | 20        | 8.89%   |
| GNOME         | 19        | 8.44%   |
| MATE          | 13        | 5.78%   |
| i3            | 10        | 4.44%   |
| Openbox       | 7         | 3.11%   |
| Enlightenment | 3         | 1.33%   |
| LXQt          | 2         | 0.89%   |
| Cinnamon      | 2         | 0.89%   |
| AwesomeWM     | 2         | 0.89%   |
| GNUstep       | 1         | 0.44%   |
| Fluxbox       | 1         | 0.44%   |
| Compton       | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 155       | 68.89%  |
| Console | 67        | 29.78%  |
| Wayland | 3         | 1.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 125       | 55.56%  |
| SDDM    | 32        | 14.22%  |
| GDM     | 20        | 8.89%   |
| SLiM    | 19        | 8.44%   |
| LightDM | 16        | 7.11%   |
| XDM     | 11        | 4.89%   |
| WDM     | 1         | 0.44%   |
| Ly      | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| C               | 163       | 72.77%  |
| en_US           | 18        | 8.04%   |
| Unknown         | 15        | 6.7%    |
| fr_FR           | 6         | 2.68%   |
| ru_RU           | 5         | 2.23%   |
| de_DE           | 5         | 2.23%   |
| nb_NO           | 3         | 1.34%   |
| en_GB           | 2         | 0.89%   |
| zh_TW           | 1         | 0.45%   |
| uk_UA           | 1         | 0.45%   |
| pt_PT           | 1         | 0.45%   |
| pl_PL           | 1         | 0.45%   |
| ja_JP           | 1         | 0.45%   |
| it_IT.ISO8859-1 | 1         | 0.45%   |
| es_ES           | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 148       | 65.2%   |
| BIOS | 79        | 34.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 146       | 64.89%  |
| Ufs  | 79        | 35.11%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 200       | 88.89%  |
| MBR  | 25        | 11.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 37        | 16.52%  |
| Dell                    | 37        | 16.52%  |
| ASUSTek Computer        | 28        | 12.5%   |
| Hewlett-Packard         | 17        | 7.59%   |
| Gigabyte Technology     | 12        | 5.36%   |
| ASRock                  | 12        | 5.36%   |
| MSI                     | 10        | 4.46%   |
| Acer                    | 9         | 4.02%   |
| Unknown                 | 9         | 4.02%   |
| Toshiba                 | 6         | 2.68%   |
| Raspberry Pi Foundation | 6         | 2.68%   |
| Intel                   | 4         | 1.79%   |
| Cisco Systems           | 4         | 1.79%   |
| Apple                   | 4         | 1.79%   |
| Samsung Electronics     | 3         | 1.34%   |
| Beckhoff Automation     | 3         | 1.34%   |
| System76                | 2         | 0.89%   |
| Supermicro              | 2         | 0.89%   |
| Shuttle                 | 2         | 0.89%   |
| Pegatron                | 2         | 0.89%   |
| Notebook                | 2         | 0.89%   |
| Gateway                 | 2         | 0.89%   |
| Wistron                 | 1         | 0.45%   |
| Sony                    | 1         | 0.45%   |
| Medion                  | 1         | 0.45%   |
| Huanan                  | 1         | 0.45%   |
| Google                  | 1         | 0.45%   |
| Fujitsu                 | 1         | 0.45%   |
| Framework               | 1         | 0.45%   |
| Firefly                 | 1         | 0.45%   |
| EVGA                    | 1         | 0.45%   |
| Biostar                 | 1         | 0.45%   |
| Alienware               | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 9         | 4.02%   |
| RPi Raspberry Pi                  | 6         | 2.68%   |
| ASUS All Series                   | 3         | 1.34%   |
| MSI MS-7817                       | 2         | 0.89%   |
| Dell OptiPlex 7040                | 2         | 0.89%   |
| Cisco Systems UCSC-C240-M4L       | 2         | 0.89%   |
| Beckhoff Automation Industrial PC | 2         | 0.89%   |
| ASUS TUF GAMING X570-PLUS         | 2         | 0.89%   |
| ASRock B450M Pro4                 | 2         | 0.89%   |
| Wistron ProLiant ML110 G6         | 1         | 0.45%   |
| Toshiba TECRA M11                 | 1         | 0.45%   |
| Toshiba Satellite Pro T130        | 1         | 0.45%   |
| Toshiba Satellite L955            | 1         | 0.45%   |
| Toshiba Satellite L50-C           | 1         | 0.45%   |
| Toshiba PORTEGE X20W-D            | 1         | 0.45%   |
| Toshiba NB300                     | 1         | 0.45%   |
| System76 Lemur Pro                | 1         | 0.45%   |
| System76 Gazelle                  | 1         | 0.45%   |
| Supermicro X7SPA-HF               | 1         | 0.45%   |
| Supermicro Super Server           | 1         | 0.45%   |
| Sony VGN-NS21M_S                  | 1         | 0.45%   |
| Shuttle SH87R                     | 1         | 0.45%   |
| Shuttle DS20U                     | 1         | 0.45%   |
| Samsung NC10                      | 1         | 0.45%   |
| Samsung 340XAA/350XAA/550XAA      | 1         | 0.45%   |
| Samsung 300E5M/300E5L             | 1         | 0.45%   |
| Pegatron T12Ah                    | 1         | 0.45%   |
| Pegatron SAISHIAT2                | 1         | 0.45%   |
| Notebook NL5xRU                   | 1         | 0.45%   |
| Notebook N7x0WU                   | 1         | 0.45%   |
| MSI Summit E13FlipEvo A11MT       | 1         | 0.45%   |
| MSI MS-7C80                       | 1         | 0.45%   |
| MSI MS-7C39                       | 1         | 0.45%   |
| MSI MS-7C02                       | 1         | 0.45%   |
| MSI MS-7B09                       | 1         | 0.45%   |
| MSI MS-7677                       | 1         | 0.45%   |
| MSI GS65 Stealth Thin 8RF         | 1         | 0.45%   |
| MSI GL65 Leopard 10SFSK           | 1         | 0.45%   |
| Medion MS-7616                    | 1         | 0.45%   |
| Lenovo Z51-70 80K6                | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo ThinkPad                | 25        | 11.16%  |
| Dell Latitude                  | 13        | 5.8%    |
| Dell Inspiron                  | 9         | 4.02%   |
| Unknown                        | 9         | 4.02%   |
| RPi Raspberry                  | 6         | 2.68%   |
| Acer Aspire                    | 6         | 2.68%   |
| Lenovo IdeaPad                 | 4         | 1.79%   |
| ASUS ROG                       | 4         | 1.79%   |
| Toshiba Satellite              | 3         | 1.34%   |
| HP ProLiant                    | 3         | 1.34%   |
| HP Laptop                      | 3         | 1.34%   |
| HP Compaq                      | 3         | 1.34%   |
| Dell Vostro                    | 3         | 1.34%   |
| Dell Precision                 | 3         | 1.34%   |
| Dell PowerEdge                 | 3         | 1.34%   |
| Dell OptiPlex                  | 3         | 1.34%   |
| ASUS TUF                       | 3         | 1.34%   |
| ASUS All                       | 3         | 1.34%   |
| MSI MS-7817                    | 2         | 0.89%   |
| Gigabyte X570                  | 2         | 0.89%   |
| Dell XPS                       | 2         | 0.89%   |
| Cisco Systems UCSC-C240-M4L    | 2         | 0.89%   |
| Beckhoff Automation Industrial | 2         | 0.89%   |
| ASUS PRIME                     | 2         | 0.89%   |
| ASUS P5K                       | 2         | 0.89%   |
| ASUS ASUS                      | 2         | 0.89%   |
| ASRock X570                    | 2         | 0.89%   |
| ASRock B450M                   | 2         | 0.89%   |
| Wistron ProLiant               | 1         | 0.45%   |
| Toshiba TECRA                  | 1         | 0.45%   |
| Toshiba PORTEGE                | 1         | 0.45%   |
| Toshiba NB300                  | 1         | 0.45%   |
| System76 Lemur                 | 1         | 0.45%   |
| System76 Gazelle               | 1         | 0.45%   |
| Supermicro X7SPA-HF            | 1         | 0.45%   |
| Supermicro Super               | 1         | 0.45%   |
| Sony VGN-NS21M                 | 1         | 0.45%   |
| Shuttle SH87R                  | 1         | 0.45%   |
| Shuttle DS20U                  | 1         | 0.45%   |
| Samsung NC10                   | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 32        | 14.29%  |
| 2018    | 24        | 10.71%  |
| 2021    | 23        | 10.27%  |
| 2019    | 20        | 8.93%   |
| 2011    | 16        | 7.14%   |
| 2010    | 15        | 6.7%    |
| 2017    | 12        | 5.36%   |
| 2012    | 12        | 5.36%   |
| 2008    | 12        | 5.36%   |
| 2015    | 11        | 4.91%   |
| Unknown | 11        | 4.91%   |
| 2013    | 10        | 4.46%   |
| 2016    | 8         | 3.57%   |
| 2014    | 8         | 3.57%   |
| 2009    | 5         | 2.23%   |
| 2006    | 3         | 1.34%   |
| 2022    | 1         | 0.45%   |
| 2005    | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 112       | 50%     |
| Desktop        | 78        | 34.82%  |
| System on chip | 12        | 5.36%   |
| Server         | 9         | 4.02%   |
| Convertible    | 6         | 2.68%   |
| Mini pc        | 4         | 1.79%   |
| All in one     | 3         | 1.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 99.11%  |
| Yes  | 2         | 0.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 63        | 28%     |
| 16.01-24.0      | 48        | 21.33%  |
| 4.01-8.0        | 38        | 16.89%  |
| 32.01-64.0      | 22        | 9.78%   |
| 64.01-256.0     | 21        | 9.33%   |
| 2.01-3.0        | 12        | 5.33%   |
| 24.01-32.0      | 6         | 2.67%   |
| 0.51-1.0        | 6         | 2.67%   |
| 3.01-4.0        | 5         | 2.22%   |
| More than 256.0 | 2         | 0.89%   |
| 1.01-2.0        | 1         | 0.44%   |
| 0.01-0.5        | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 102       | 45.33%  |
| 0.51-1.0   | 65        | 28.89%  |
| 1.01-2.0   | 29        | 12.89%  |
| 2.01-3.0   | 8         | 3.56%   |
| 3.01-4.0   | 7         | 3.11%   |
| 0          | 5         | 2.22%   |
| 4.01-8.0   | 4         | 1.78%   |
| 16.01-24.0 | 3         | 1.33%   |
| 24.01-32.0 | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 54.82%  |
| 2      | 42        | 18.42%  |
| 3      | 18        | 7.89%   |
| 0      | 14        | 6.14%   |
| 4      | 8         | 3.51%   |
| 5      | 6         | 2.63%   |
| 7      | 4         | 1.75%   |
| 6      | 4         | 1.75%   |
| 14     | 2         | 0.88%   |
| 12     | 2         | 0.88%   |
| 13     | 1         | 0.44%   |
| 9      | 1         | 0.44%   |
| 8      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 68.89%  |
| Yes       | 70        | 31.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 85.27%  |
| No        | 33        | 14.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 67.41%  |
| No        | 73        | 32.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 121       | 54.02%  |
| Yes       | 103       | 45.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 61        | 27.23%  |
| Russia      | 24        | 10.71%  |
| Germany     | 17        | 7.59%   |
| UK          | 14        | 6.25%   |
| France      | 9         | 4.02%   |
| Brazil      | 8         | 3.57%   |
| Netherlands | 7         | 3.13%   |
| Canada      | 7         | 3.13%   |
| Australia   | 5         | 2.23%   |
| Switzerland | 4         | 1.79%   |
| India       | 4         | 1.79%   |
| Czechia     | 4         | 1.79%   |
| Ukraine     | 3         | 1.34%   |
| Spain       | 3         | 1.34%   |
| Poland      | 3         | 1.34%   |
| Mexico      | 3         | 1.34%   |
| Japan       | 3         | 1.34%   |
| Bulgaria    | 3         | 1.34%   |
| Vietnam     | 2         | 0.89%   |
| Turkey      | 2         | 0.89%   |
| Thailand    | 2         | 0.89%   |
| Norway      | 2         | 0.89%   |
| New Zealand | 2         | 0.89%   |
| Iran        | 2         | 0.89%   |
| Hungary     | 2         | 0.89%   |
| Guadeloupe  | 2         | 0.89%   |
| Finland     | 2         | 0.89%   |
| Colombia    | 2         | 0.89%   |
| China       | 2         | 0.89%   |
| Taiwan      | 1         | 0.45%   |
| Sweden      | 1         | 0.45%   |
| Slovakia    | 1         | 0.45%   |
| Romania     | 1         | 0.45%   |
| Qatar       | 1         | 0.45%   |
| Portugal    | 1         | 0.45%   |
| Nepal       | 1         | 0.45%   |
| Namibia     | 1         | 0.45%   |
| Malaysia    | 1         | 0.45%   |
| Lithuania   | 1         | 0.45%   |
| Italy       | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Moscow              | 6         | 2.65%   |
| Lexington           | 6         | 2.65%   |
| Sofia               | 3         | 1.33%   |
| Seattle             | 3         | 1.33%   |
| Menlo Park          | 3         | 1.33%   |
| LГјbeck           | 3         | 1.33%   |
| Berlin              | 3         | 1.33%   |
| Alphen aan den Rijn | 3         | 1.33%   |
| Yekaterinburg       | 2         | 0.88%   |
| Tehran              | 2         | 0.88%   |
| Salem               | 2         | 0.88%   |
| Redmond             | 2         | 0.88%   |
| Québec             | 2         | 0.88%   |
| Ozersk              | 2         | 0.88%   |
| Minneapolis         | 2         | 0.88%   |
| Melbourne           | 2         | 0.88%   |
| Le Gosier           | 2         | 0.88%   |
| Kyiv                | 2         | 0.88%   |
| Istanbul            | 2         | 0.88%   |
| Irkutsk             | 2         | 0.88%   |
| Helsinki            | 2         | 0.88%   |
| Glasgow             | 2         | 0.88%   |
| Chelyabinsk         | 2         | 0.88%   |
| Zurich              | 1         | 0.44%   |
| Yerevan             | 1         | 0.44%   |
| Wenatchee           | 1         | 0.44%   |
| Weimar              | 1         | 0.44%   |
| Wausau              | 1         | 0.44%   |
| Warsaw              | 1         | 0.44%   |
| Vratsa              | 1         | 0.44%   |
| Vostochnoe Degunino | 1         | 0.44%   |
| Vilnius             | 1         | 0.44%   |
| Vancouver           | 1         | 0.44%   |
| Valladolid          | 1         | 0.44%   |
| Vadodara            | 1         | 0.44%   |
| Vacaville           | 1         | 0.44%   |
| Ufa                 | 1         | 0.44%   |
| Tyumen              | 1         | 0.44%   |
| Tuklaty             | 1         | 0.44%   |
| Tuddal              | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 78     | 17.04%  |
| Seagate             | 49        | 126    | 15.76%  |
| WDC                 | 43        | 87     | 13.83%  |
| Toshiba             | 29        | 43     | 9.32%   |
| Kingston            | 26        | 29     | 8.36%   |
| Crucial             | 20        | 22     | 6.43%   |
| Hitachi             | 12        | 27     | 3.86%   |
| Intel               | 11        | 13     | 3.54%   |
| HGST                | 8         | 11     | 2.57%   |
| A-DATA Technology   | 7         | 7      | 2.25%   |
| SanDisk             | 6         | 7      | 1.93%   |
| Micron Technology   | 5         | 6      | 1.61%   |
| SK hynix            | 4         | 4      | 1.29%   |
| Phison              | 4         | 4      | 1.29%   |
| Corsair             | 4         | 4      | 1.29%   |
| Fujitsu             | 3         | 4      | 0.96%   |
| PNY                 | 2         | 2      | 0.64%   |
| Plextor             | 2         | 3      | 0.64%   |
| LITEONIT            | 2         | 2      | 0.64%   |
| Lenovo              | 2         | 2      | 0.64%   |
| Verbatim            | 1         | 1      | 0.32%   |
| Transcend           | 1         | 1      | 0.32%   |
| TCSUNBOW            | 1         | 1      | 0.32%   |
| SSSTC               | 1         | 1      | 0.32%   |
| SPCC                | 1         | 1      | 0.32%   |
| Smartbuy            | 1         | 1      | 0.32%   |
| Silicon Motion      | 1         | 1      | 0.32%   |
| Patriot             | 1         | 1      | 0.32%   |
| OWC                 | 1         | 1      | 0.32%   |
| Maxtor              | 1         | 1      | 0.32%   |
| KIOXIA              | 1         | 1      | 0.32%   |
| KingSpec            | 1         | 1      | 0.32%   |
| KingDian            | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| Hewlett-Packard     | 1         | 2      | 0.32%   |
| Goodram             | 1         | 1      | 0.32%   |
| Gigabyte Technology | 1         | 1      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |
| Apacer              | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 6         | 1.69%   |
| Kingston SA400S37120G 120GB        | 6         | 1.69%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 1.69%   |
| Toshiba DT01ACA100 1TB             | 5         | 1.4%    |
| Seagate ST4000DM000-1F2168 4TB     | 4         | 1.12%   |
| Samsung SSD 970 EVO Plus 250GB     | 4         | 1.12%   |
| Samsung SSD 970 EVO 500GB          | 4         | 1.12%   |
| Toshiba MQ01ABD100 1TB             | 3         | 0.84%   |
| Seagate ST1000LM048-2E7172 1TB     | 3         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.84%   |
| Samsung SSD 970 EVO Plus 1TB       | 3         | 0.84%   |
| Samsung SSD 860 EVO 500GB          | 3         | 0.84%   |
| Samsung MZVLB256HBHQ-000L7 256GB   | 3         | 0.84%   |
| Crucial CT120BX500SSD1 120GB       | 3         | 0.84%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 2         | 0.56%   |
| WDC WD80EFAX-68LHPN0 8TB           | 2         | 0.56%   |
| WDC WD20EFRX-68EUZN0 1TB           | 2         | 0.56%   |
| Toshiba MG04SCA20EN 2TB            | 2         | 0.56%   |
| Seagate ST8000VN004-2M2101 8TB     | 2         | 0.56%   |
| Seagate ST4000VN000-1H4168 4TB     | 2         | 0.56%   |
| Seagate ST4000DM004-2CV104 4TB     | 2         | 0.56%   |
| Seagate ST2000NM0023 2TB           | 2         | 0.56%   |
| Seagate ST16000NM001G-2KK103 16TB  | 2         | 0.56%   |
| Seagate ST1000NM0023 1TB           | 2         | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.56%   |
| Samsung SSD 960 EVO 500GB          | 2         | 0.56%   |
| Samsung SSD 870 EVO 1TB            | 2         | 0.56%   |
| Samsung SSD 860 QVO 1TB            | 2         | 0.56%   |
| Samsung SSD 860 EVO 1TB            | 2         | 0.56%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.56%   |
| Kingston SVP200S37A60G 64GB        | 2         | 0.56%   |
| Kingston SMS200S3120G 120GB        | 2         | 0.56%   |
| HGST HTS725032A7E630 320GB         | 2         | 0.56%   |
| HGST HTS721010A9E630 1TB           | 2         | 0.56%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.56%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 1         | 0.28%   |
| WDC WDS500G2B0B-00YS70 500GB       | 1         | 0.28%   |
| WDC WDS250G2B0A 250GB              | 1         | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 125    | 35.82%  |
| WDC                 | 32        | 74     | 23.88%  |
| Toshiba             | 24        | 38     | 17.91%  |
| Hitachi             | 12        | 27     | 8.96%   |
| HGST                | 8         | 11     | 5.97%   |
| Samsung Electronics | 5         | 6      | 3.73%   |
| Fujitsu             | 3         | 4      | 2.24%   |
| Maxtor              | 1         | 1      | 0.75%   |
| Hewlett-Packard     | 1         | 2      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 20.47%  |
| Kingston            | 22        | 24     | 17.32%  |
| Crucial             | 20        | 22     | 15.75%  |
| Intel               | 10        | 12     | 7.87%   |
| WDC                 | 7         | 8      | 5.51%   |
| SanDisk             | 6         | 7      | 4.72%   |
| A-DATA Technology   | 5         | 5      | 3.94%   |
| SK hynix            | 3         | 3      | 2.36%   |
| Micron Technology   | 3         | 4      | 2.36%   |
| Corsair             | 3         | 3      | 2.36%   |
| Toshiba             | 2         | 2      | 1.57%   |
| LITEONIT            | 2         | 2      | 1.57%   |
| Verbatim            | 1         | 1      | 0.79%   |
| Transcend           | 1         | 1      | 0.79%   |
| TCSUNBOW            | 1         | 1      | 0.79%   |
| SSSTC               | 1         | 1      | 0.79%   |
| SPCC                | 1         | 1      | 0.79%   |
| Smartbuy            | 1         | 1      | 0.79%   |
| PNY                 | 1         | 1      | 0.79%   |
| Plextor             | 1         | 1      | 0.79%   |
| Phison              | 1         | 1      | 0.79%   |
| Patriot             | 1         | 1      | 0.79%   |
| OWC                 | 1         | 1      | 0.79%   |
| Lenovo              | 1         | 1      | 0.79%   |
| KingSpec            | 1         | 1      | 0.79%   |
| KingDian            | 1         | 1      | 0.79%   |
| Intenso             | 1         | 1      | 0.79%   |
| Gigabyte Technology | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |
| Apacer              | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 114       | 288    | 40.86%  |
| SSD  | 110       | 145    | 39.43%  |
| NVMe | 55        | 68     | 19.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 185       | 433    | 77.08%  |
| NVMe | 55        | 68     | 22.92%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 129       | 182    | 52.87%  |
| 0.51-1.0   | 64        | 93     | 26.23%  |
| 1.01-2.0   | 16        | 32     | 6.56%   |
| 3.01-4.0   | 12        | 29     | 4.92%   |
| 4.01-10.0  | 11        | 55     | 4.51%   |
| 2.01-3.0   | 8         | 23     | 3.28%   |
| 10.01-20.0 | 4         | 19     | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 34.22%  |
| 251-500        | 48        | 21.33%  |
| 501-1000       | 30        | 13.33%  |
| 51-100         | 23        | 10.22%  |
| 21-50          | 18        | 8%      |
| 1-20           | 12        | 5.33%   |
| 1001-2000      | 10        | 4.44%   |
| More than 3000 | 3         | 1.33%   |
| 2001-3000      | 3         | 1.33%   |
| Unknown        | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 194       | 86.61%  |
| 21-50          | 14        | 6.25%   |
| 51-100         | 5         | 2.23%   |
| 101-250        | 4         | 1.79%   |
| More than 3000 | 2         | 0.89%   |
| 251-500        | 2         | 0.89%   |
| 1001-2000      | 1         | 0.45%   |
| 501-1000       | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 188       | 438    | 82.46%  |
| Malfunc  | 34        | 46     | 14.91%  |
| Detected | 6         | 17     | 2.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 151       | 54.91%  |
| AMD                              | 39        | 14.18%  |
| Samsung Electronics              | 28        | 10.18%  |
| Broadcom / LSI                   | 9         | 3.27%   |
| ASMedia Technology               | 8         | 2.91%   |
| Marvell Technology Group         | 6         | 2.18%   |
| Phison Electronics               | 5         | 1.82%   |
| SanDisk                          | 4         | 1.45%   |
| Toshiba                          | 3         | 1.09%   |
| Kingston Technology Company      | 3         | 1.09%   |
| Silicon Motion                   | 2         | 0.73%   |
| Nvidia                           | 2         | 0.73%   |
| Micron Technology                | 2         | 0.73%   |
| JMicron Technology               | 2         | 0.73%   |
| ADATA Technology                 | 2         | 0.73%   |
| SK hynix                         | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] | 1         | 0.36%   |
| Seagate Technology               | 1         | 0.36%   |
| Lite-On Technology               | 1         | 0.36%   |
| Lenovo                           | 1         | 0.36%   |
| KIOXIA                           | 1         | 0.36%   |
| Hewlett-Packard                  | 1         | 0.36%   |
| Apple                            | 1         | 0.36%   |
| Adaptec                          | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 10.16%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 5.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 4.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 3.28%   |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 2.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 8         | 2.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 2.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 2.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 6         | 1.97%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.31%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 1.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.31%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 0.98%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.98%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 3         | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2         | 0.66%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 2         | 0.66%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.66%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.66%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.66%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                            | 2         | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                               | 2         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.66%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.66%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 167       | 61.85%  |
| NVMe | 54        | 20%     |
| IDE  | 27        | 10%     |
| RAID | 16        | 5.93%   |
| SAS  | 5         | 1.85%   |
| SCSI | 1         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 170       | 75.89%  |
| AMD     | 41        | 18.3%   |
| ARM     | 10        | 4.46%   |
| Unknown | 3         | 1.34%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                          | 6         | 2.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 5         | 2.23%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 4         | 1.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 4         | 1.79%   |
| AMD Ryzen 7 2700 Eight-Core Processor        | 4         | 1.79%   |
| Intel CPU Version                            | 3         | 1.34%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 3         | 1.34%   |
| Intel Core i7-6700 CPU @ 3.40GHz             | 3         | 1.34%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 3         | 1.34%   |
| Intel Core i5-4300M CPU @ 2.60GHz            | 3         | 1.34%   |
| Intel Core i5-2520M CPU @ 2.50GHz            | 3         | 1.34%   |
| ARM Cortex-A53 r0p4                          | 3         | 1.34%   |
|                                              | 3         | 1.34%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 2         | 0.89%   |
| Intel Pentium 4                              | 2         | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 0.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 2         | 0.89%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 2         | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 2         | 0.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 2         | 0.89%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 2         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 2         | 0.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.89%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz        | 2         | 0.89%   |
| AMD Ryzen 9 5950X 16-Core Processor          | 2         | 0.89%   |
| AMD Ryzen 9 5900X 12-Core Processor          | 2         | 0.89%   |
| AMD Ryzen 9 3900X 12-Core Processor          | 2         | 0.89%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics  | 2         | 0.89%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.89%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz         | 1         | 0.45%   |
| Intel Xeon Silver 4208 CPU @ 2.10GHz         | 1         | 0.45%   |
| Intel Xeon CPU X5650 @ 2.67GHz               | 1         | 0.45%   |
| Intel Xeon CPU X3440 @ 2.53GHz               | 1         | 0.45%   |
| Intel Xeon CPU X3430 @ 2.40GHz               | 1         | 0.45%   |
| Intel Xeon CPU E5520 @ 2.27GHz               | 1         | 0.45%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz          | 1         | 0.45%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz          | 1         | 0.45%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz          | 1         | 0.45%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz          | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 51        | 22.77%  |
| Intel Core i7          | 39        | 17.41%  |
| Other                  | 12        | 5.36%   |
| Intel Core i3          | 12        | 5.36%   |
| Intel Xeon             | 11        | 4.91%   |
| Intel Celeron          | 11        | 4.91%   |
| AMD Ryzen 7            | 11        | 4.91%   |
| ARM Cortex             | 10        | 4.46%   |
| Intel Pentium          | 9         | 4.02%   |
| AMD Ryzen 9            | 8         | 3.57%   |
| Intel Core 2 Duo       | 7         | 3.13%   |
| Intel Atom             | 6         | 2.68%   |
| Intel Pentium 4        | 4         | 1.79%   |
| AMD Ryzen 5            | 4         | 1.79%   |
| AMD Ryzen 3            | 3         | 1.34%   |
| Intel Xeon Silver      | 2         | 0.89%   |
| Intel Pentium Silver   | 2         | 0.89%   |
| Intel Pentium Dual     | 2         | 0.89%   |
| Intel Core 2 Quad      | 2         | 0.89%   |
| AMD A6                 | 2         | 0.89%   |
| AMD A4                 | 2         | 0.89%   |
| Intel Pentium M        | 1         | 0.45%   |
| Intel Genuine          | 1         | 0.45%   |
| Intel Core i9          | 1         | 0.45%   |
| Intel Core 2           | 1         | 0.45%   |
| Intel Celeron M        | 1         | 0.45%   |
| AMD Turion II Neo      | 1         | 0.45%   |
| AMD Ryzen Threadripper | 1         | 0.45%   |
| AMD FX                 | 1         | 0.45%   |
| AMD EPYC               | 1         | 0.45%   |
| AMD E                  | 1         | 0.45%   |
| AMD Athlon X4          | 1         | 0.45%   |
| AMD Athlon             | 1         | 0.45%   |
| AMD A12                | 1         | 0.45%   |
| AMD A10                | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 76        | 33.93%  |
| 4       | 71        | 31.7%   |
| Unknown | 25        | 11.16%  |
| 16      | 12        | 5.36%   |
| 6       | 9         | 4.02%   |
| 8       | 7         | 3.13%   |
| 1       | 7         | 3.13%   |
| 12      | 5         | 2.23%   |
| 24      | 4         | 1.79%   |
| 32      | 3         | 1.34%   |
| 20      | 2         | 0.89%   |
| 64      | 1         | 0.45%   |
| 28      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 204       | 91.07%  |
| 2       | 10        | 4.46%   |
| Unknown | 10        | 4.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 117       | 52.23%  |
| 1       | 79        | 35.27%  |
| Unknown | 28        | 12.5%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 39        | 17.41%  |
| Haswell       | 19        | 8.48%   |
| Unknown       | 15        | 6.7%    |
| Skylake       | 14        | 6.25%   |
| IvyBridge     | 14        | 6.25%   |
| SandyBridge   | 12        | 5.36%   |
| Westmere      | 11        | 4.91%   |
| Broadwell     | 10        | 4.46%   |
| Zen+          | 9         | 4.02%   |
| Bonnell       | 8         | 3.57%   |
| Zen 2         | 7         | 3.13%   |
| Penryn        | 7         | 3.13%   |
| Core          | 7         | 3.13%   |
| Zen 3         | 5         | 2.23%   |
| Zen           | 5         | 2.23%   |
| Silvermont    | 5         | 2.23%   |
| Goldmont plus | 5         | 2.23%   |
| Nehalem       | 4         | 1.79%   |
| Excavator     | 4         | 1.79%   |
| CometLake     | 4         | 1.79%   |
| Piledriver    | 3         | 1.34%   |
| NetBurst      | 3         | 1.34%   |
| TigerLake     | 2         | 0.89%   |
| P6            | 2         | 0.89%   |
| K10           | 2         | 0.89%   |
| Jaguar        | 2         | 0.89%   |
| IceLake       | 2         | 0.89%   |
| Goldmont      | 2         | 0.89%   |
| K10 Llano     | 1         | 0.45%   |
| Bobcat        | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 134       | 55.6%   |
| Nvidia                               | 54        | 22.41%  |
| AMD                                  | 42        | 17.43%  |
| Matrox Electronics Systems           | 9         | 3.73%   |
| NVidia / SGS Thomson (Joint Venture) | 1         | 0.41%   |
| ASPEED Technology                    | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 10        | 3.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.59%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 8         | 3.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.19%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 7         | 2.79%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.39%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 1.99%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 5         | 1.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.99%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.59%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.2%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.2%    |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 3         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.8%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 0.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.8%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 2         | 0.8%    |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 2         | 0.8%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.8%    |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.8%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 91        | 40.63%  |
| 1 x Nvidia                               | 30        | 13.39%  |
| 1 x AMD                                  | 30        | 13.39%  |
| Intel + Nvidia                           | 21        | 9.38%   |
| 2 x Intel                                | 15        | 6.7%    |
| Other                                    | 14        | 6.25%   |
| 1 x Matrox                               | 9         | 4.02%   |
| Intel + AMD                              | 6         | 2.68%   |
| 2 x AMD                                  | 4         | 1.79%   |
| 2 x Nvidia                               | 1         | 0.45%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.45%   |
| AMD + Nvidia                             | 1         | 0.45%   |
| AMD + ASPEED                             | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 183       | 81.7%   |
| Proprietary | 26        | 11.61%  |
| Unknown     | 15        | 6.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 185       | 82.59%  |
| 0.01-0.5   | 9         | 4.02%   |
| 3.01-4.0   | 8         | 3.57%   |
| 1.01-2.0   | 8         | 3.57%   |
| 7.01-8.0   | 6         | 2.68%   |
| 5.01-6.0   | 3         | 1.34%   |
| 0.51-1.0   | 3         | 1.34%   |
| 2.01-3.0   | 1         | 0.45%   |
| 8.01-16.0  | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 24        | 16.11%  |
| BOE                  | 15        | 10.07%  |
| LG Display           | 14        | 9.4%    |
| Samsung Electronics  | 13        | 8.72%   |
| Dell                 | 11        | 7.38%   |
| Chimei Innolux       | 10        | 6.71%   |
| Goldstar             | 9         | 6.04%   |
| Sharp                | 6         | 4.03%   |
| Ancor Communications | 6         | 4.03%   |
| Hewlett-Packard      | 5         | 3.36%   |
| Lenovo               | 4         | 2.68%   |
| AOC                  | 4         | 2.68%   |
| Philips              | 3         | 2.01%   |
| InfoVision           | 3         | 2.01%   |
| Iiyama               | 3         | 2.01%   |
| Acer                 | 3         | 2.01%   |
| Toshiba              | 2         | 1.34%   |
| Sceptre Tech         | 2         | 1.34%   |
| BenQ                 | 2         | 1.34%   |
| ASUSTek Computer     | 2         | 1.34%   |
| Panasonic            | 1         | 0.67%   |
| LG Electronics       | 1         | 0.67%   |
| HannStar             | 1         | 0.67%   |
| Eizo                 | 1         | 0.67%   |
| CPT                  | 1         | 0.67%   |
| CKL                  | 1         | 0.67%   |
| Apple                | 1         | 0.67%   |
| AGO                  | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 3         | 1.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 2         | 1.32%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                      | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 340x190mm 15.3-inch         | 2         | 1.32%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                        | 1         | 0.66%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 0.66%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 290x180mm 13.4-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP14D1 1920x1200 340x210mm 15.7-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP1476 3840x2160 350x190mm 15.7-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP1451 1920x1080 280x160mm 12.7-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP143E 3840x2160 350x190mm 15.7-inch                | 1         | 0.66%   |
| Sharp HDMI SHP1177 1920x1080 1100x620mm 49.7-inch                      | 1         | 0.66%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1         | 0.66%   |
| Sceptre Tech Sceptre J20 SPT080D 1600x900 440x230mm 19.5-inch          | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch   | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM0236 2560x1600 640x400mm 29.7-inch   | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1         | 0.66%   |
| Samsung Electronics S24E510C SAM0C61 1920x1080 520x300mm 23.6-inch     | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 310x170mm 13.9-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch  | 1         | 0.66%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch     | 1         | 0.66%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 510x290mm 23.1-inch                | 1         | 0.66%   |
| Philips LCD Monitor PHLC050 1366x768 410x230mm 18.5-inch               | 1         | 0.66%   |
| Philips 215i PHLC05A 1920x1080 470x260mm 21.1-inch                     | 1         | 0.66%   |
| Philips 190S PHL083F 1280x1024 380x300mm 19.1-inch                     | 1         | 0.66%   |
| Panasonic TV MEIC136 1280x720 698x392mm 31.5-inch                      | 1         | 0.66%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD03D3 1600x900 310x170mm 13.9-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 60        | 41.96%  |
| 1366x768 (WXGA)    | 30        | 20.98%  |
| 3840x2160 (4K)     | 12        | 8.39%   |
| 1920x1200 (WUXGA)  | 9         | 6.29%   |
| 1600x900 (HD+)     | 7         | 4.9%    |
| 2560x1440 (QHD)    | 4         | 2.8%    |
| 1280x800 (WXGA)    | 4         | 2.8%    |
| 1024x600           | 4         | 2.8%    |
| 1280x1024 (SXGA)   | 3         | 2.1%    |
| 2560x1600          | 2         | 1.4%    |
| 2560x1080          | 2         | 1.4%    |
| 1680x1050 (WSXGA+) | 2         | 1.4%    |
| 1280x720 (HD)      | 2         | 1.4%    |
| 1920x540           | 1         | 0.7%    |
| 1024x768 (XGA)     | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 38        | 25.85%  |
| 13      | 26        | 17.69%  |
| 24      | 14        | 9.52%   |
| 27      | 8         | 5.44%   |
| 23      | 8         | 5.44%   |
| 21      | 7         | 4.76%   |
| 12      | 6         | 4.08%   |
| Unknown | 6         | 4.08%   |
| 19      | 5         | 3.4%    |
| 10      | 5         | 3.4%    |
| 14      | 4         | 2.72%   |
| 31      | 3         | 2.04%   |
| 29      | 3         | 2.04%   |
| 17      | 3         | 2.04%   |
| 18      | 2         | 1.36%   |
| 64      | 1         | 0.68%   |
| 52      | 1         | 0.68%   |
| 49      | 1         | 0.68%   |
| 46      | 1         | 0.68%   |
| 40      | 1         | 0.68%   |
| 34      | 1         | 0.68%   |
| 32      | 1         | 0.68%   |
| 22      | 1         | 0.68%   |
| 20      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 38.62%  |
| 501-600     | 28        | 19.31%  |
| 201-300     | 23        | 15.86%  |
| 401-500     | 13        | 8.97%   |
| 601-700     | 6         | 4.14%   |
| 351-400     | 6         | 4.14%   |
| Unknown     | 6         | 4.14%   |
| 1001-1500   | 4         | 2.76%   |
| 701-800     | 2         | 1.38%   |
| 801-900     | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 106       | 79.7%   |
| 16/10   | 14        | 10.53%  |
| Unknown | 5         | 3.76%   |
| 5/4     | 3         | 2.26%   |
| 4/3     | 2         | 1.5%    |
| 21/9    | 2         | 1.5%    |
| 3/2     | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 30        | 20.41%  |
| 201-250        | 24        | 16.33%  |
| 81-90          | 22        | 14.97%  |
| 301-350        | 9         | 6.12%   |
| 101-110        | 9         | 6.12%   |
| 351-500        | 7         | 4.76%   |
| 151-200        | 7         | 4.76%   |
| 71-80          | 6         | 4.08%   |
| 61-70          | 6         | 4.08%   |
| Unknown        | 6         | 4.08%   |
| 41-50          | 5         | 3.4%    |
| 251-300        | 5         | 3.4%    |
| More than 1000 | 3         | 2.04%   |
| 121-130        | 3         | 2.04%   |
| 141-150        | 2         | 1.36%   |
| 501-1000       | 2         | 1.36%   |
| 111-120        | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 29.66%  |
| 101-120       | 40        | 27.59%  |
| 121-160       | 36        | 24.83%  |
| 161-240       | 11        | 7.59%   |
| Unknown       | 6         | 4.14%   |
| 1-50          | 5         | 3.45%   |
| More than 240 | 4         | 2.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 48.89%  |
| 0     | 93        | 41.33%  |
| 2     | 20        | 8.89%   |
| 3     | 2         | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 115       | 36.39%  |
| Realtek Semiconductor             | 97        | 30.7%   |
| Qualcomm Atheros                  | 43        | 13.61%  |
| Broadcom                          | 28        | 8.86%   |
| Samsung Electronics               | 4         | 1.27%   |
| Ralink Technology                 | 4         | 1.27%   |
| Marvell Technology Group          | 4         | 1.27%   |
| Edimax Technology                 | 3         | 0.95%   |
| Nvidia                            | 2         | 0.63%   |
| Mellanox Technologies             | 2         | 0.63%   |
| Cisco Systems                     | 2         | 0.63%   |
| Xiaomi                            | 1         | 0.32%   |
| TP-Link                           | 1         | 0.32%   |
| Sundance Technology Inc / IC Plus | 1         | 0.32%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.32%   |
| Ralink                            | 1         | 0.32%   |
| Qualcomm                          | 1         | 0.32%   |
| NetGear                           | 1         | 0.32%   |
| MediaTek                          | 1         | 0.32%   |
| IMC Networks                      | 1         | 0.32%   |
| dog hunter                        | 1         | 0.32%   |
| Apple                             | 1         | 0.32%   |
| ADMtek                            | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 71        | 18.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 13        | 3.36%   |
| Intel Wireless 8265 / 8275                                             | 12        | 3.1%    |
| Intel I211 Gigabit Network Connection                                  | 10        | 2.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 8         | 2.07%   |
| Intel Wireless 7265                                                    | 8         | 2.07%   |
| Intel Wi-Fi 6 AX200                                                    | 8         | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6         | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 1.03%   |
| Intel Wireless 7260                                                    | 4         | 1.03%   |
| Intel I350 Gigabit Network Connection                                  | 4         | 1.03%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 1.03%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.03%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                         | 3         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.78%   |
| Intel Wireless 8260                                                    | 3         | 0.78%   |
| Intel Wireless 3160                                                    | 3         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.78%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 3         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 81        | 49.39%  |
| Qualcomm Atheros      | 31        | 18.9%   |
| Realtek Semiconductor | 23        | 14.02%  |
| Broadcom              | 17        | 10.37%  |
| Ralink Technology     | 4         | 2.44%   |
| Edimax Technology     | 3         | 1.83%   |
| TP-Link               | 1         | 0.61%   |
| Ralink                | 1         | 0.61%   |
| NetGear               | 1         | 0.61%   |
| MediaTek              | 1         | 0.61%   |
| IMC Networks          | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 12        | 7.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 4.85%   |
| Intel Wireless 7265                                            | 8         | 4.85%   |
| Intel Wi-Fi 6 AX200                                            | 8         | 4.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 4.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 3.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 6         | 3.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 2.42%   |
| Intel Wireless 7260                                            | 4         | 2.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 2.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 2.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.82%   |
| Ralink RT5370 Wireless Adapter                                 | 3         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.82%   |
| Intel Wireless 8260                                            | 3         | 1.82%   |
| Intel Wireless 3160                                            | 3         | 1.82%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.82%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.21%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.21%   |
| Intel Wireless 3165                                            | 2         | 1.21%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.21%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.21%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 1.21%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.21%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 2         | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.21%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 88        | 42.11%  |
| Intel                             | 71        | 33.97%  |
| Qualcomm Atheros                  | 16        | 7.66%   |
| Broadcom                          | 16        | 7.66%   |
| Samsung Electronics               | 4         | 1.91%   |
| Marvell Technology Group          | 4         | 1.91%   |
| Nvidia                            | 2         | 0.96%   |
| Cisco Systems                     | 2         | 0.96%   |
| Xiaomi                            | 1         | 0.48%   |
| Sundance Technology Inc / IC Plus | 1         | 0.48%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.48%   |
| Qualcomm                          | 1         | 0.48%   |
| Apple                             | 1         | 0.48%   |
| ADMtek                            | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 71        | 32.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 13        | 5.99%   |
| Intel I211 Gigabit Network Connection                                         | 10        | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 8         | 3.69%   |
| Intel Ethernet Connection (4) I219-LM                                         | 5         | 2.3%    |
| Intel Ethernet Connection (2) I219-LM                                         | 5         | 2.3%    |
| Intel I350 Gigabit Network Connection                                         | 4         | 1.84%   |
| Intel I210 Gigabit Network Connection                                         | 4         | 1.84%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.84%   |
| Intel Ethernet Connection (2) I219-V                                          | 4         | 1.84%   |
| Intel 82574L Gigabit Network Connection                                       | 4         | 1.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 3         | 1.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 1.38%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 1.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2         | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                         | 2         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.92%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.92%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 2         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.92%   |
| Intel Ethernet Connection (10) I219-LM                                        | 2         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 0.92%   |
| Intel 82577LC Gigabit Network Connection                                      | 2         | 0.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2         | 0.92%   |
| Cisco Systems VIC Ethernet NIC                                                | 2         | 0.92%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.92%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 2         | 0.92%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                          | 1         | 0.46%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY    | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                     | 1         | 0.46%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.46%   |
| Qualcomm FP3                                                                  | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                     | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 192       | 55.01%  |
| WiFi     | 152       | 43.55%  |
| Unknown  | 4         | 1.15%   |
| Modem    | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 166       | 62.64%  |
| WiFi     | 99        | 37.36%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 138       | 61.33%  |
| 1     | 59        | 26.22%  |
| 0     | 13        | 5.78%   |
| 3     | 8         | 3.56%   |
| 4     | 7         | 3.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 196       | 87.11%  |
| Yes  | 29        | 12.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 56.86%  |
| Qualcomm Atheros Communications | 11        | 10.78%  |
| Realtek Semiconductor           | 9         | 8.82%   |
| Broadcom                        | 5         | 4.9%    |
| IMC Networks                    | 4         | 3.92%   |
| Apple                           | 4         | 3.92%   |
| Cambridge Silicon Radio         | 3         | 2.94%   |
| Lite-On Technology              | 2         | 1.96%   |
| ASUSTek Computer                | 2         | 1.96%   |
| Toshiba                         | 1         | 0.98%   |
| Hewlett-Packard                 | 1         | 0.98%   |
| Foxconn / Hon Hai               | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 22.55%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 7.84%   |
| Intel AX200 Bluetooth                                       | 8         | 7.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 6         | 5.88%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 4.9%    |
| Intel AX201 Bluetooth                                       | 5         | 4.9%    |
| Realtek  Bluetooth 4.2 Adapter                              | 4         | 3.92%   |
| Intel Wireless-AC 3168 Bluetooth                            | 4         | 3.92%   |
| Realtek Bluetooth Adapter                                   | 3         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.94%   |
| Apple Bluetooth Host Controller                             | 3         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.96%   |
| Intel AX210 Bluetooth                                       | 2         | 1.96%   |
| IMC Networks Bluetooth module                               | 2         | 1.96%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 0.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.98%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.98%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.98%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.98%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.98%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.98%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.98%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.98%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.98%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.98%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 0.98%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.98%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 0.98%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.98%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 0.98%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 0.98%   |
| ASUS BT-270 Bluetooth Adapter                               | 1         | 0.98%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 0.98%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 150       | 61.48%  |
| AMD                                             | 45        | 18.44%  |
| Nvidia                                          | 33        | 13.52%  |
| Logitech                                        | 2         | 0.82%   |
| Creative Labs                                   | 2         | 0.82%   |
| C-Media Electronics                             | 2         | 0.82%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.41%   |
| Texas Instruments                               | 1         | 0.41%   |
| SteelSeries ApS                                 | 1         | 0.41%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.41%   |
| Realtek Semiconductor                           | 1         | 0.41%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.41%   |
| Lenovo                                          | 1         | 0.41%   |
| Ensoniq                                         | 1         | 0.41%   |
| Corsair                                         | 1         | 0.41%   |
| BEHRINGER International                         | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 22        | 7.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 3.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 3.4%    |
| AMD Ryzen HD Audio Controller                                              | 10        | 3.4%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9         | 3.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 2.72%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 2.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8         | 2.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 2.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.7%    |
| AMD FCH Azalia Controller                                                  | 5         | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.36%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 4         | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.36%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.02%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.02%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.02%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.02%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.02%   |
| AMD High Definition Audio Controller                                       | 3         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.68%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 22.69%  |
| SK hynix            | 43        | 18.07%  |
| Unknown             | 30        | 12.61%  |
| Kingston            | 26        | 10.92%  |
| Crucial             | 21        | 8.82%   |
| Micron Technology   | 17        | 7.14%   |
| Corsair             | 11        | 4.62%   |
| Ramaxel Technology  | 6         | 2.52%   |
| A-DATA Technology   | 5         | 2.1%    |
| G.Skill             | 4         | 1.68%   |
| Unknown             | 4         | 1.68%   |
| Team                | 2         | 0.84%   |
| Smart               | 2         | 0.84%   |
| GOODRAM             | 2         | 0.84%   |
| Transcend           | 1         | 0.42%   |
| Teikon              | 1         | 0.42%   |
| Silicon Power       | 1         | 0.42%   |
| Qimonda             | 1         | 0.42%   |
| PUSKILL             | 1         | 0.42%   |
| Neo Forza           | 1         | 0.42%   |
| Nanya Technology    | 1         | 0.42%   |
| Kreton              | 1         | 0.42%   |
| GeIL                | 1         | 0.42%   |
| Elpida              | 1         | 0.42%   |
| AMD                 | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 5         | 1.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 4         | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s   | 4         | 1.54%   |
| Unknown                                                 | 4         | 1.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 3         | 1.15%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 3         | 1.15%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 3         | 1.15%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 3         | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 1.15%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s   | 3         | 1.15%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 2         | 0.77%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 2         | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2                      | 2         | 0.77%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                | 2         | 0.77%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s      | 2         | 0.77%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.77%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s  | 2         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s  | 2         | 0.77%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 2         | 0.77%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.77%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 2         | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 2         | 0.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 0.77%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s | 2         | 0.77%   |
| Crucial RAM CT8G4SFS824A.C8BD1 8GB SODIMM DDR4 2400MT/s | 2         | 0.77%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s | 2         | 0.77%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 2         | 0.77%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                  | 1         | 0.38%   |
| Unknown RAM PartNum 0 512MB Chip DDR2 533MT/s           | 1         | 0.38%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1067MT/s               | 1         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s             | 1         | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1         | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1         | 0.38%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1         | 0.38%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s              | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 94        | 44.55%  |
| DDR3    | 81        | 38.39%  |
| DDR2    | 14        | 6.64%   |
| Unknown | 6         | 2.84%   |
| LPDDR3  | 5         | 2.37%   |
| DDR     | 5         | 2.37%   |
| SDRAM   | 3         | 1.42%   |
| LPDDR4  | 2         | 0.95%   |
| DDR5    | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 61.14%  |
| DIMM         | 75        | 35.55%  |
| Row Of Chips | 5         | 2.37%   |
| Chip         | 1         | 0.47%   |
| Unknown      | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 33.62%  |
| 4096  | 61        | 26.29%  |
| 16384 | 36        | 15.52%  |
| 2048  | 34        | 14.66%  |
| 1024  | 12        | 5.17%   |
| 32768 | 11        | 4.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 52        | 22.41%  |
| 2400    | 30        | 12.93%  |
| 3200    | 29        | 12.5%   |
| 2667    | 21        | 9.05%   |
| 1333    | 20        | 8.62%   |
| 2133    | 19        | 8.19%   |
| 800     | 9         | 3.88%   |
| 1067    | 8         | 3.45%   |
| 667     | 7         | 3.02%   |
| 3000    | 5         | 2.16%   |
| 1334    | 5         | 2.16%   |
| 533     | 4         | 1.72%   |
| Unknown | 4         | 1.72%   |
| 2933    | 3         | 1.29%   |
| 1867    | 3         | 1.29%   |
| 4267    | 2         | 0.86%   |
| 2666    | 2         | 0.86%   |
| 975     | 2         | 0.86%   |
| 400     | 2         | 0.86%   |
| 4800    | 1         | 0.43%   |
| 3600    | 1         | 0.43%   |
| 1866    | 1         | 0.43%   |
| 1332    | 1         | 0.43%   |
| 1066    | 1         | 0.43%   |

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
| Chicony Electronics           | 24        | 25.26%  |
| IMC Networks                  | 13        | 13.68%  |
| Microdia                      | 11        | 11.58%  |
| Realtek Semiconductor         | 9         | 9.47%   |
| Suyin                         | 8         | 8.42%   |
| Sunplus Innovation Technology | 6         | 6.32%   |
| Bison Electronics             | 5         | 5.26%   |
| Logitech                      | 3         | 3.16%   |
| Syntek                        | 2         | 2.11%   |
| Silicon Motion                | 2         | 2.11%   |
| Quanta                        | 2         | 2.11%   |
| Lite-On Technology            | 2         | 2.11%   |
| Importek                      | 2         | 2.11%   |
| ALi                           | 2         | 2.11%   |
| Z-Star Microelectronics       | 1         | 1.05%   |
| Valve Software                | 1         | 1.05%   |
| Luxvisions Innotech Limited   | 1         | 1.05%   |
| Lenovo                        | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera           | 5         | 5.26%   |
| Chicony Integrated Camera                | 5         | 5.26%   |
| Microdia Integrated Webcam               | 4         | 4.21%   |
| Chicony HD WebCam                        | 3         | 3.16%   |
| Suyin 1.3M HD WebCam                     | 2         | 2.11%   |
| Sunplus Integrated_Webcam_HD             | 2         | 2.11%   |
| Silicon Motion Realtek DMFT RGB          | 2         | 2.11%   |
| Microdia Integrated_Webcam_HD            | 2         | 2.11%   |
| IMC Networks Realtek PC Camera           | 2         | 2.11%   |
| Chicony Realtek DMFT RGB                 | 2         | 2.11%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 2         | 2.11%   |
| Chicony HP TrueVision HD Camera          | 2         | 2.11%   |
| Chicony EasyCamera                       | 2         | 2.11%   |
| ALi Gateway Webcam                       | 2         | 2.11%   |
| Z-Star Namuga 1.3M Webcam                | 1         | 1.05%   |
| Valve Software 3D Camera                 | 1         | 1.05%   |
| Syntek Lenovo EasyCamera                 | 1         | 1.05%   |
| Syntek EasyCamera                        | 1         | 1.05%   |
| Suyin USB 2.0 Camera                     | 1         | 1.05%   |
| Suyin Lenovo Integrated Webcam           | 1         | 1.05%   |
| Suyin Integrated Camera                  | 1         | 1.05%   |
| Suyin HP Webcam-101                      | 1         | 1.05%   |
| Suyin Asus Integrated Webcam             | 1         | 1.05%   |
| Suyin Acer Crystal Eye webcam            | 1         | 1.05%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 1.05%   |
| Sunplus Laptop Integrated Webcam HD      | 1         | 1.05%   |
| Sunplus Integrated Camera                | 1         | 1.05%   |
| Sunplus Dell HD Webcam                   | 1         | 1.05%   |
| Realtek USB 2.0 Webcam                   | 1         | 1.05%   |
| Realtek PC Camera                        | 1         | 1.05%   |
| Realtek Lenovo EasyCamera                | 1         | 1.05%   |
| Realtek Integrated_Webcam_HD             | 1         | 1.05%   |
| Realtek Integrated Webcam HD             | 1         | 1.05%   |
| Realtek Integrated Webcam                | 1         | 1.05%   |
| Realtek HP 2.0MP High Definition Webcam  | 1         | 1.05%   |
| Realtek Dell EasyCamera                  | 1         | 1.05%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 1.05%   |
| Quanta VGA WebCam                        | 1         | 1.05%   |
| Quanta HD Webcam                         | 1         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 1.05%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 27.27%  |
| Synaptics                  | 6         | 27.27%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Elan Microelectronics      | 2         | 9.09%   |
| Upek                       | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Broadcom                   | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                              | 4         | 18.18%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 3         | 13.64%  |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 13.64%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 9.09%   |
| Elan Fingerprint Sensor                                                      | 2         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 4.55%   |
| Synaptics WBDI                                                               | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 4.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 4.55%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.55%   |
| AuthenTec AES1660                                                            | 1         | 4.55%   |

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
| 1     | 76        | 33.78%  |
| 0     | 62        | 27.56%  |
| 2     | 50        | 22.22%  |
| 3     | 25        | 11.11%  |
| 4     | 9         | 4%      |
| 5     | 2         | 0.89%   |
| 6     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 123       | 43.77%  |
| Net/wireless             | 56        | 19.93%  |
| Bluetooth                | 31        | 11.03%  |
| Fingerprint reader       | 22        | 7.83%   |
| Card reader              | 19        | 6.76%   |
| Firewire controller      | 17        | 6.05%   |
| Net/ethernet             | 5         | 1.78%   |
| Sound                    | 3         | 1.07%   |
| Network                  | 2         | 0.71%   |
| Storage/nvme             | 1         | 0.36%   |
| Storage/ide              | 1         | 0.36%   |
| Storage                  | 1         | 0.36%   |

