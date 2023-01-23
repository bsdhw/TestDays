FreeBSD - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for FreeBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/FreeBSD/Desktop/README.md) and [notebooks](/Dist/FreeBSD/Notebook/README.md).

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

Total: 3046

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Unknown       | AMD-GX3                     | Desktop     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [35e269ef1c](https://bsd-hardware.info/?probe=35e269ef1c) | Jan 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [b528c0bbe3](https://bsd-hardware.info/?probe=b528c0bbe3) | Jan 18, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [ed566c9a5c](https://bsd-hardware.info/?probe=ed566c9a5c) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [f7de27b0ca](https://bsd-hardware.info/?probe=f7de27b0ca) | Jan 18, 2023 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [cfb839082b](https://bsd-hardware.info/?probe=cfb839082b) | Jan 18, 2023 |
| Lenovo        | H30-05 90BJ0085SP           | Desktop     | [d491694079](https://bsd-hardware.info/?probe=d491694079) | Jan 18, 2023 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [9eee9cc526](https://bsd-hardware.info/?probe=9eee9cc526) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | Desktop     | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| HP            | 1998                        | Desktop     | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [7ef714a7f1](https://bsd-hardware.info/?probe=7ef714a7f1) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| AZW           | SEi                         | Mini pc     | [362a33bd50](https://bsd-hardware.info/?probe=362a33bd50) | Jan 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [864db5c1f9](https://bsd-hardware.info/?probe=864db5c1f9) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [07f15d0014](https://bsd-hardware.info/?probe=07f15d0014) | Jan 11, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [2428fe6bd3](https://bsd-hardware.info/?probe=2428fe6bd3) | Jan 10, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [470fa4f28a](https://bsd-hardware.info/?probe=470fa4f28a) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Supermicro    | X10DRL-i                    | Server      | [c0fa5bb871](https://bsd-hardware.info/?probe=c0fa5bb871) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | Desktop     | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [17f5e2e3d2](https://bsd-hardware.info/?probe=17f5e2e3d2) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [a1517b13f6](https://bsd-hardware.info/?probe=a1517b13f6) | Jan 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [409d119307](https://bsd-hardware.info/?probe=409d119307) | Jan 02, 2023 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [d66b90249d](https://bsd-hardware.info/?probe=d66b90249d) | Jan 02, 2023 |
| Alienware     | m15 R4                      | Notebook    | [1438237430](https://bsd-hardware.info/?probe=1438237430) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [ab7e64f657](https://bsd-hardware.info/?probe=ab7e64f657) | Dec 31, 2022 |
| Lenovo        | 30D9 SDK0J40700 WIN 3258... | Desktop     | [ac867149f2](https://bsd-hardware.info/?probe=ac867149f2) | Dec 31, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [956499202e](https://bsd-hardware.info/?probe=956499202e) | Dec 30, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d22c37fa81](https://bsd-hardware.info/?probe=d22c37fa81) | Dec 29, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5d14519e73](https://bsd-hardware.info/?probe=5d14519e73) | Dec 28, 2022 |
| MSI           | H270 GAMING M3              | Desktop     | [5dcdab1ee3](https://bsd-hardware.info/?probe=5dcdab1ee3) | Dec 28, 2022 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [07dc4a3178](https://bsd-hardware.info/?probe=07dc4a3178) | Dec 27, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [50c8cb79f7](https://bsd-hardware.info/?probe=50c8cb79f7) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [883dbf15e4](https://bsd-hardware.info/?probe=883dbf15e4) | Dec 25, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| Alienware     | m15 R4                      | Notebook    | [deaef8f0ef](https://bsd-hardware.info/?probe=deaef8f0ef) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [a2bc442acd](https://bsd-hardware.info/?probe=a2bc442acd) | Dec 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [009ef73bd1](https://bsd-hardware.info/?probe=009ef73bd1) | Dec 20, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8de4ff8626](https://bsd-hardware.info/?probe=8de4ff8626) | Dec 20, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b730e64d4a](https://bsd-hardware.info/?probe=b730e64d4a) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | Desktop     | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| ASRock        | B660M-ITX/ac                | Desktop     | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8f950de05](https://bsd-hardware.info/?probe=b8f950de05) | Dec 17, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7cf06451fd](https://bsd-hardware.info/?probe=7cf06451fd) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8d92a4e37e](https://bsd-hardware.info/?probe=8d92a4e37e) | Dec 17, 2022 |
| Lenovo        | B50-80 80EW                 | Notebook    | [e6778fa5fd](https://bsd-hardware.info/?probe=e6778fa5fd) | Dec 15, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [6fc0671dc6](https://bsd-hardware.info/?probe=6fc0671dc6) | Dec 14, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [617f431099](https://bsd-hardware.info/?probe=617f431099) | Dec 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [f51b401c31](https://bsd-hardware.info/?probe=f51b401c31) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [353c3d5cee](https://bsd-hardware.info/?probe=353c3d5cee) | Dec 12, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [64c92d49d9](https://bsd-hardware.info/?probe=64c92d49d9) | Dec 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [73cb5d86bc](https://bsd-hardware.info/?probe=73cb5d86bc) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [5274876096](https://bsd-hardware.info/?probe=5274876096) | Dec 11, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [0be43b76d1](https://bsd-hardware.info/?probe=0be43b76d1) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [6d10b2a0b4](https://bsd-hardware.info/?probe=6d10b2a0b4) | Dec 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [1d8397a653](https://bsd-hardware.info/?probe=1d8397a653) | Dec 10, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [2048ff5f71](https://bsd-hardware.info/?probe=2048ff5f71) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c30f53fc6d](https://bsd-hardware.info/?probe=c30f53fc6d) | Dec 09, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| HP            | 82A2                        | Desktop     | [c612b7e283](https://bsd-hardware.info/?probe=c612b7e283) | Dec 06, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [4130b19cfa](https://bsd-hardware.info/?probe=4130b19cfa) | Dec 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | Notebook    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [6fe2ba74b7](https://bsd-hardware.info/?probe=6fe2ba74b7) | Dec 01, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [087264570d](https://bsd-hardware.info/?probe=087264570d) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [1d61d0cf62](https://bsd-hardware.info/?probe=1d61d0cf62) | Nov 29, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [38d7f55ef7](https://bsd-hardware.info/?probe=38d7f55ef7) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [13e318fec2](https://bsd-hardware.info/?probe=13e318fec2) | Nov 29, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [378270eba0](https://bsd-hardware.info/?probe=378270eba0) | Nov 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [c93690c7ca](https://bsd-hardware.info/?probe=c93690c7ca) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [04a7f49322](https://bsd-hardware.info/?probe=04a7f49322) | Nov 27, 2022 |
| Shuttle       | FZ270                       | Desktop     | [10016f39b9](https://bsd-hardware.info/?probe=10016f39b9) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [675c9fdf94](https://bsd-hardware.info/?probe=675c9fdf94) | Nov 27, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [a337eb9e5f](https://bsd-hardware.info/?probe=a337eb9e5f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [192351ac6f](https://bsd-hardware.info/?probe=192351ac6f) | Nov 27, 2022 |
| Shuttle       | FH270                       | Desktop     | [3b68d89092](https://bsd-hardware.info/?probe=3b68d89092) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [5048d00fd8](https://bsd-hardware.info/?probe=5048d00fd8) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [60bdb57227](https://bsd-hardware.info/?probe=60bdb57227) | Nov 27, 2022 |
| Dell          | 0VRCY5 A14                  | Server      | [ebdca950cc](https://bsd-hardware.info/?probe=ebdca950cc) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [3ad7cec298](https://bsd-hardware.info/?probe=3ad7cec298) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6c2ef140be](https://bsd-hardware.info/?probe=6c2ef140be) | Nov 25, 2022 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [bcf17b19ec](https://bsd-hardware.info/?probe=bcf17b19ec) | Nov 25, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | Notebook    | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [d0009172b1](https://bsd-hardware.info/?probe=d0009172b1) | Nov 24, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [25cc0129d9](https://bsd-hardware.info/?probe=25cc0129d9) | Nov 24, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [0ed70ba3c3](https://bsd-hardware.info/?probe=0ed70ba3c3) | Nov 23, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [8ec61db3f0](https://bsd-hardware.info/?probe=8ec61db3f0) | Nov 22, 2022 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [e55eb53894](https://bsd-hardware.info/?probe=e55eb53894) | Nov 21, 2022 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [56bc3b04fd](https://bsd-hardware.info/?probe=56bc3b04fd) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| HP            | ProBook 4540s               | Notebook    | [6dce896f40](https://bsd-hardware.info/?probe=6dce896f40) | Nov 20, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| TOPFEEL       | H110D4-P1                   | Desktop     | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [436a2d30f6](https://bsd-hardware.info/?probe=436a2d30f6) | Nov 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [15657b37e2](https://bsd-hardware.info/?probe=15657b37e2) | Nov 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f4a8c42773](https://bsd-hardware.info/?probe=f4a8c42773) | Nov 15, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4c83122cc0](https://bsd-hardware.info/?probe=4c83122cc0) | Nov 14, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [15e38a5ca8](https://bsd-hardware.info/?probe=15e38a5ca8) | Nov 13, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b1175a4df](https://bsd-hardware.info/?probe=2b1175a4df) | Nov 13, 2022 |
| MSI           | H81M-P33                    | Desktop     | [98b0980231](https://bsd-hardware.info/?probe=98b0980231) | Nov 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [072f2a6c27](https://bsd-hardware.info/?probe=072f2a6c27) | Nov 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [ea99621380](https://bsd-hardware.info/?probe=ea99621380) | Nov 12, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Google        | Akemi                       | Notebook    | [2d8e99f0c2](https://bsd-hardware.info/?probe=2d8e99f0c2) | Nov 12, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [569d5b0cca](https://bsd-hardware.info/?probe=569d5b0cca) | Nov 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [87d7d4435b](https://bsd-hardware.info/?probe=87d7d4435b) | Nov 10, 2022 |
| HP            | 21B4 A01                    | Desktop     | [c064c50fea](https://bsd-hardware.info/?probe=c064c50fea) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [e5c599dfab](https://bsd-hardware.info/?probe=e5c599dfab) | Nov 09, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [62ab446b5d](https://bsd-hardware.info/?probe=62ab446b5d) | Nov 09, 2022 |
| HP            | 21B4 A01                    | Desktop     | [0a3ba5478b](https://bsd-hardware.info/?probe=0a3ba5478b) | Nov 09, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c32a7b407d](https://bsd-hardware.info/?probe=c32a7b407d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [127e0126d1](https://bsd-hardware.info/?probe=127e0126d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [9f15cb8acc](https://bsd-hardware.info/?probe=9f15cb8acc) | Nov 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [5807159f51](https://bsd-hardware.info/?probe=5807159f51) | Nov 08, 2022 |
| Google        | Zako                        | Desktop     | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [9c4be9deab](https://bsd-hardware.info/?probe=9c4be9deab) | Nov 07, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | Desktop     | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Acer          | RS880M05                    | Desktop     | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [750d2f53c7](https://bsd-hardware.info/?probe=750d2f53c7) | Nov 06, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [e427ea787e](https://bsd-hardware.info/?probe=e427ea787e) | Nov 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c6abe84145](https://bsd-hardware.info/?probe=c6abe84145) | Nov 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c4fd2595e6](https://bsd-hardware.info/?probe=c4fd2595e6) | Nov 06, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [1373bd7f3e](https://bsd-hardware.info/?probe=1373bd7f3e) | Nov 05, 2022 |
| HP            | ProBook 4540s               | Notebook    | [7596b602c6](https://bsd-hardware.info/?probe=7596b602c6) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [d5c5f30a2d](https://bsd-hardware.info/?probe=d5c5f30a2d) | Nov 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| Samsung       | 750TDA                      | Notebook    | [a880b1f616](https://bsd-hardware.info/?probe=a880b1f616) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [d7141b866c](https://bsd-hardware.info/?probe=d7141b866c) | Nov 02, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [bb0f8a5bfc](https://bsd-hardware.info/?probe=bb0f8a5bfc) | Oct 31, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [cce93ff157](https://bsd-hardware.info/?probe=cce93ff157) | Oct 30, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b67d6a7bb2](https://bsd-hardware.info/?probe=b67d6a7bb2) | Oct 30, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [8161bfd24d](https://bsd-hardware.info/?probe=8161bfd24d) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a0896f17e4](https://bsd-hardware.info/?probe=a0896f17e4) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [2776d8c350](https://bsd-hardware.info/?probe=2776d8c350) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [6911e08b7e](https://bsd-hardware.info/?probe=6911e08b7e) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [caad4323ba](https://bsd-hardware.info/?probe=caad4323ba) | Oct 23, 2022 |
| MSI           | H81M-P33                    | Desktop     | [626f503cad](https://bsd-hardware.info/?probe=626f503cad) | Oct 23, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b98739799](https://bsd-hardware.info/?probe=2b98739799) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [56dac6bc80](https://bsd-hardware.info/?probe=56dac6bc80) | Oct 23, 2022 |
| IBM           | 49Y6512                     | Server      | [1bc9e20b16](https://bsd-hardware.info/?probe=1bc9e20b16) | Oct 23, 2022 |
| Acer          | Revo RN86                   | Desktop     | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [348bef7dba](https://bsd-hardware.info/?probe=348bef7dba) | Oct 20, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [bc229efed9](https://bsd-hardware.info/?probe=bc229efed9) | Oct 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [20ff21d751](https://bsd-hardware.info/?probe=20ff21d751) | Oct 18, 2022 |
| Lenovo        | 30D0 NOK                    | Desktop     | [d1fab8bd54](https://bsd-hardware.info/?probe=d1fab8bd54) | Oct 18, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [0a8b1f727f](https://bsd-hardware.info/?probe=0a8b1f727f) | Oct 17, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [e057b613a0](https://bsd-hardware.info/?probe=e057b613a0) | Oct 17, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [22881028bc](https://bsd-hardware.info/?probe=22881028bc) | Oct 16, 2022 |
| TYAN Compu... | Intel 440BX/GX Rev. 4       | Desktop     | [8d99f317e4](https://bsd-hardware.info/?probe=8d99f317e4) | Oct 15, 2022 |
| Dell          | 0G1548 A00                  | Desktop     | [226af33d5b](https://bsd-hardware.info/?probe=226af33d5b) | Oct 15, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [06214241b3](https://bsd-hardware.info/?probe=06214241b3) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 23446FP       | Notebook    | [6b15856d20](https://bsd-hardware.info/?probe=6b15856d20) | Oct 15, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| IBM           | 49Y6512                     | Server      | [4471bf6465](https://bsd-hardware.info/?probe=4471bf6465) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10358c7207](https://bsd-hardware.info/?probe=10358c7207) | Oct 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b20b6c7997](https://bsd-hardware.info/?probe=b20b6c7997) | Oct 13, 2022 |
| IBM           | 49Y6512                     | Server      | [1ead286cbe](https://bsd-hardware.info/?probe=1ead286cbe) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | Notebook    | [df62882c3b](https://bsd-hardware.info/?probe=df62882c3b) | Oct 12, 2022 |
| HP            | 1589                        | Desktop     | [0696d30d3f](https://bsd-hardware.info/?probe=0696d30d3f) | Oct 12, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [c79fa6f001](https://bsd-hardware.info/?probe=c79fa6f001) | Oct 09, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [2bd1529913](https://bsd-hardware.info/?probe=2bd1529913) | Oct 07, 2022 |
| ASRockRack    | EP2C612D16FM                | Desktop     | [30a582fccb](https://bsd-hardware.info/?probe=30a582fccb) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [601029d3fc](https://bsd-hardware.info/?probe=601029d3fc) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ce9cfa77aa](https://bsd-hardware.info/?probe=ce9cfa77aa) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [f61208cfea](https://bsd-hardware.info/?probe=f61208cfea) | Oct 05, 2022 |
| HP            | Compaq 6735s                | Notebook    | [718126149c](https://bsd-hardware.info/?probe=718126149c) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [86289a60aa](https://bsd-hardware.info/?probe=86289a60aa) | Oct 05, 2022 |
| Acer          | TravelMate B115-M           | Notebook    | [9f4642f6a5](https://bsd-hardware.info/?probe=9f4642f6a5) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Dell          | Precision 5510              | Notebook    | [f69c9fb0ea](https://bsd-hardware.info/?probe=f69c9fb0ea) | Oct 04, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [459c674b3b](https://bsd-hardware.info/?probe=459c674b3b) | Oct 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [d89559e5c2](https://bsd-hardware.info/?probe=d89559e5c2) | Oct 03, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| IBM           | 9210MML                     | Desktop     | [a6e7d7483f](https://bsd-hardware.info/?probe=a6e7d7483f) | Oct 03, 2022 |
| HPE           | ProLiant ML30 Gen10         | Desktop     | [f1b45790d4](https://bsd-hardware.info/?probe=f1b45790d4) | Oct 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [0fcbdeeeb7](https://bsd-hardware.info/?probe=0fcbdeeeb7) | Oct 02, 2022 |
| HP            | 212B                        | Desktop     | [7bc6506336](https://bsd-hardware.info/?probe=7bc6506336) | Oct 01, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [f9851a3257](https://bsd-hardware.info/?probe=f9851a3257) | Oct 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [6f95477df3](https://bsd-hardware.info/?probe=6f95477df3) | Sep 30, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [8e658fe40f](https://bsd-hardware.info/?probe=8e658fe40f) | Sep 30, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [5fd9a63834](https://bsd-hardware.info/?probe=5fd9a63834) | Sep 30, 2022 |
| AMI           | MNHO-048                    | Desktop     | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [7e75a1888b](https://bsd-hardware.info/?probe=7e75a1888b) | Sep 27, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [b2024820d1](https://bsd-hardware.info/?probe=b2024820d1) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Pegatron      | H81-X1                      | Desktop     | [a27c76c490](https://bsd-hardware.info/?probe=a27c76c490) | Sep 25, 2022 |
| ASUSTek       | P9D-X Series                | Server      | [3494695f54](https://bsd-hardware.info/?probe=3494695f54) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [c947635b8f](https://bsd-hardware.info/?probe=c947635b8f) | Sep 25, 2022 |
| Gigabyte      | GB-BSi5A-6200               | Notebook    | [533c7f35f1](https://bsd-hardware.info/?probe=533c7f35f1) | Sep 25, 2022 |
| Supermicro    | X10SRi-FB                   | Server      | [59ff2014e5](https://bsd-hardware.info/?probe=59ff2014e5) | Sep 25, 2022 |
| Intel         | S1200SP H57532-210          | Server      | [ab6e70abca](https://bsd-hardware.info/?probe=ab6e70abca) | Sep 25, 2022 |
| Supermicro    | X8DT3                       | Server      | [eda1df037b](https://bsd-hardware.info/?probe=eda1df037b) | Sep 25, 2022 |
| Supermicro    | X7DB8                       | Desktop     | [6ebc173873](https://bsd-hardware.info/?probe=6ebc173873) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [8bbf714f6d](https://bsd-hardware.info/?probe=8bbf714f6d) | Sep 25, 2022 |
| Deciso        | Netboard A10 V2.1           | Desktop     | [60d4585ece](https://bsd-hardware.info/?probe=60d4585ece) | Sep 25, 2022 |
| IBM           | ThinkPad T40 23737CG        | Notebook    | [dfc9b64da2](https://bsd-hardware.info/?probe=dfc9b64da2) | Sep 25, 2022 |
| System76      | Gazelle                     | Notebook    | [d087321049](https://bsd-hardware.info/?probe=d087321049) | Sep 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [dbda136daa](https://bsd-hardware.info/?probe=dbda136daa) | Sep 24, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| System76      | Gazelle                     | Notebook    | [6d5d4f5021](https://bsd-hardware.info/?probe=6d5d4f5021) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | Desktop     | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| Acer          | Aspire E5-771               | Notebook    | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [10b85eccae](https://bsd-hardware.info/?probe=10b85eccae) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [322c8947b6](https://bsd-hardware.info/?probe=322c8947b6) | Sep 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [0307c109b5](https://bsd-hardware.info/?probe=0307c109b5) | Sep 19, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [1a9c6a10bd](https://bsd-hardware.info/?probe=1a9c6a10bd) | Sep 19, 2022 |
| HP            | 0B54h D                     | Desktop     | [a24f08281d](https://bsd-hardware.info/?probe=a24f08281d) | Sep 19, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [91e0f723ea](https://bsd-hardware.info/?probe=91e0f723ea) | Sep 18, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Lenovo        | ThinkPad L420 7829WDY       | Notebook    | [a697be2aa9](https://bsd-hardware.info/?probe=a697be2aa9) | Sep 16, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [ce024b9f84](https://bsd-hardware.info/?probe=ce024b9f84) | Sep 15, 2022 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [15a7e37cbf](https://bsd-hardware.info/?probe=15a7e37cbf) | Sep 15, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [2b4cf189e9](https://bsd-hardware.info/?probe=2b4cf189e9) | Sep 14, 2022 |
| Dell          | 0HJK12 A03                  | Server      | [96ad323ca0](https://bsd-hardware.info/?probe=96ad323ca0) | Sep 13, 2022 |
| Dell          | 0H5J4J A01                  | Server      | [acb91f797f](https://bsd-hardware.info/?probe=acb91f797f) | Sep 13, 2022 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [8e2f7792eb](https://bsd-hardware.info/?probe=8e2f7792eb) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f023ae7ed2](https://bsd-hardware.info/?probe=f023ae7ed2) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [baaf9cbda6](https://bsd-hardware.info/?probe=baaf9cbda6) | Sep 13, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [1cbbe33027](https://bsd-hardware.info/?probe=1cbbe33027) | Sep 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3b668ace72](https://bsd-hardware.info/?probe=3b668ace72) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62c287a993](https://bsd-hardware.info/?probe=62c287a993) | Sep 11, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [f91afdb2f3](https://bsd-hardware.info/?probe=f91afdb2f3) | Sep 09, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [860aea3ce4](https://bsd-hardware.info/?probe=860aea3ce4) | Sep 08, 2022 |
| Dell          | Precision 7540              | Notebook    | [f39c0f4d92](https://bsd-hardware.info/?probe=f39c0f4d92) | Sep 08, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [b0965df7e1](https://bsd-hardware.info/?probe=b0965df7e1) | Sep 08, 2022 |
| Dell          | Latitude 5310               | Notebook    | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| Dell          | Latitude E5470              | Notebook    | [9e798cbfc8](https://bsd-hardware.info/?probe=9e798cbfc8) | Sep 07, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7c6751649b](https://bsd-hardware.info/?probe=7c6751649b) | Sep 07, 2022 |
| Dell          | Vostro 5415                 | Notebook    | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | Precision 7550              | Notebook    | [d2bf200529](https://bsd-hardware.info/?probe=d2bf200529) | Sep 06, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [ec74af083f](https://bsd-hardware.info/?probe=ec74af083f) | Sep 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3f7258c807](https://bsd-hardware.info/?probe=3f7258c807) | Sep 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cced3168c8](https://bsd-hardware.info/?probe=cced3168c8) | Sep 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [61b82d5ebb](https://bsd-hardware.info/?probe=61b82d5ebb) | Sep 04, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [72757feb65](https://bsd-hardware.info/?probe=72757feb65) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [5d575c85d0](https://bsd-hardware.info/?probe=5d575c85d0) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Dell          | 0HYPX2 A00                  | Server      | [2779d78756](https://bsd-hardware.info/?probe=2779d78756) | Sep 01, 2022 |
| Dell          | 0MD99X A07                  | Server      | [3c8cc375dc](https://bsd-hardware.info/?probe=3c8cc375dc) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [4e58d828cc](https://bsd-hardware.info/?probe=4e58d828cc) | Sep 01, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [50fbb0435c](https://bsd-hardware.info/?probe=50fbb0435c) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [200b8d381e](https://bsd-hardware.info/?probe=200b8d381e) | Aug 31, 2022 |
| Dell          | 07T4MC A09                  | Desktop     | [ebc79d7728](https://bsd-hardware.info/?probe=ebc79d7728) | Aug 31, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [ac185c104b](https://bsd-hardware.info/?probe=ac185c104b) | Aug 31, 2022 |
| Intel         | X79 V2.72A                  | Desktop     | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Dell          | Latitude 7390               | Notebook    | [bc5eb8e237](https://bsd-hardware.info/?probe=bc5eb8e237) | Aug 29, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75ec0260f9](https://bsd-hardware.info/?probe=75ec0260f9) | Aug 28, 2022 |
| Dell          | Precision 7550              | Notebook    | [71f615178f](https://bsd-hardware.info/?probe=71f615178f) | Aug 27, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [10ca365b40](https://bsd-hardware.info/?probe=10ca365b40) | Aug 26, 2022 |
| Dell          | 07T4MC A00                  | Desktop     | [1060f1b6e3](https://bsd-hardware.info/?probe=1060f1b6e3) | Aug 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5684672f5a](https://bsd-hardware.info/?probe=5684672f5a) | Aug 26, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [a760a87c5d](https://bsd-hardware.info/?probe=a760a87c5d) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [0466d87f04](https://bsd-hardware.info/?probe=0466d87f04) | Aug 25, 2022 |
| HP            | ENVY Notebook               | Notebook    | [7e33273132](https://bsd-hardware.info/?probe=7e33273132) | Aug 25, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [eec9546431](https://bsd-hardware.info/?probe=eec9546431) | Aug 23, 2022 |
| Lenovo        | ThinkCentre M91p 4512A47    | Desktop     | [3556794570](https://bsd-hardware.info/?probe=3556794570) | Aug 23, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [cc2a81fc1b](https://bsd-hardware.info/?probe=cc2a81fc1b) | Aug 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [89535fc84c](https://bsd-hardware.info/?probe=89535fc84c) | Aug 21, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [ac2d88c2dd](https://bsd-hardware.info/?probe=ac2d88c2dd) | Aug 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b5786b8119](https://bsd-hardware.info/?probe=b5786b8119) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c146b538e1](https://bsd-hardware.info/?probe=c146b538e1) | Aug 20, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [560213a2d6](https://bsd-hardware.info/?probe=560213a2d6) | Aug 19, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [ce0d33d973](https://bsd-hardware.info/?probe=ce0d33d973) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | Notebook    | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [8de9fa2319](https://bsd-hardware.info/?probe=8de9fa2319) | Aug 18, 2022 |
| Google        | Peppy                       | Notebook    | [e2e0a1953d](https://bsd-hardware.info/?probe=e2e0a1953d) | Aug 18, 2022 |
| Intel         | S2600WTTR G92187-372        | Server      | [ce1988c8ff](https://bsd-hardware.info/?probe=ce1988c8ff) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [3208aefb72](https://bsd-hardware.info/?probe=3208aefb72) | Aug 17, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| Acer          | Aspire 4552G                | Notebook    | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Sony          | VGN-UX1XRN                  | Notebook    | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [dacea7c6be](https://bsd-hardware.info/?probe=dacea7c6be) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5d4af4fba9](https://bsd-hardware.info/?probe=5d4af4fba9) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [3d46e0eace](https://bsd-hardware.info/?probe=3d46e0eace) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [c961cea235](https://bsd-hardware.info/?probe=c961cea235) | Aug 13, 2022 |
| Fujitsu       | PRIMERGY RX200 S6           | Desktop     | [6884e940a1](https://bsd-hardware.info/?probe=6884e940a1) | Aug 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1292c617d2](https://bsd-hardware.info/?probe=1292c617d2) | Aug 13, 2022 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [5ceace59c1](https://bsd-hardware.info/?probe=5ceace59c1) | Aug 12, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [45e44ad953](https://bsd-hardware.info/?probe=45e44ad953) | Aug 10, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [efd9ee1d33](https://bsd-hardware.info/?probe=efd9ee1d33) | Aug 10, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| GVC           | DR 738                      | Desktop     | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Dell          | Inspiron 3581               | Notebook    | [f31cc32515](https://bsd-hardware.info/?probe=f31cc32515) | Aug 04, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [d5e9213bb5](https://bsd-hardware.info/?probe=d5e9213bb5) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0T    | Notebook    | [546fa8380b](https://bsd-hardware.info/?probe=546fa8380b) | Aug 01, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [13baedb59b](https://bsd-hardware.info/?probe=13baedb59b) | Jul 31, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| HP            | 1825                        | Desktop     | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| Dell          | Precision 5560              | Notebook    | [3dc82c6d91](https://bsd-hardware.info/?probe=3dc82c6d91) | Jul 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [6e31b5f45b](https://bsd-hardware.info/?probe=6e31b5f45b) | Jul 23, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | Studio XPS 1340             | Notebook    | [642da98e96](https://bsd-hardware.info/?probe=642da98e96) | Jul 21, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | Desktop     | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [9af051c79f](https://bsd-hardware.info/?probe=9af051c79f) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | Notebook    | [6c5c9eefc0](https://bsd-hardware.info/?probe=6c5c9eefc0) | Jul 17, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c78caf8215](https://bsd-hardware.info/?probe=c78caf8215) | Jul 16, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [978f01c546](https://bsd-hardware.info/?probe=978f01c546) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | Notebook    | [4067ce2036](https://bsd-hardware.info/?probe=4067ce2036) | Jul 16, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [fe84e9fda5](https://bsd-hardware.info/?probe=fe84e9fda5) | Jul 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [070ccc68f8](https://bsd-hardware.info/?probe=070ccc68f8) | Jul 15, 2022 |
| Acer          | Veriton X490G               | Desktop     | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Lenovo        | ThinkPad X260 20F6S0KA00    | Notebook    | [117014d55f](https://bsd-hardware.info/?probe=117014d55f) | Jul 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| Lenovo        | ThinkPad T495 20NJ0010PB    | Notebook    | [078888676a](https://bsd-hardware.info/?probe=078888676a) | Jul 13, 2022 |
| MouseCompu... | B360M                       | Desktop     | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [894b6f82cf](https://bsd-hardware.info/?probe=894b6f82cf) | Jul 13, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [b0311b8175](https://bsd-hardware.info/?probe=b0311b8175) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [7081ddd59c](https://bsd-hardware.info/?probe=7081ddd59c) | Jul 11, 2022 |
| Acer          | Veriton X490G               | Desktop     | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | Desktop     | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [7f4fa7f74d](https://bsd-hardware.info/?probe=7f4fa7f74d) | Jul 10, 2022 |
| Toshiba       | Satellite L305D             | Notebook    | [ed950787b0](https://bsd-hardware.info/?probe=ed950787b0) | Jul 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Intel         | NUC5PPYB                    | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [66543e9280](https://bsd-hardware.info/?probe=66543e9280) | Jul 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c41c8ff4f4](https://bsd-hardware.info/?probe=c41c8ff4f4) | Jul 07, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [7c34be7c2e](https://bsd-hardware.info/?probe=7c34be7c2e) | Jul 06, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [d9fd7e54cf](https://bsd-hardware.info/?probe=d9fd7e54cf) | Jul 06, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | Desktop     | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [584ecf8423](https://bsd-hardware.info/?probe=584ecf8423) | Jul 05, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [b697848727](https://bsd-hardware.info/?probe=b697848727) | Jul 05, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [886522d5e6](https://bsd-hardware.info/?probe=886522d5e6) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [81e9f8506f](https://bsd-hardware.info/?probe=81e9f8506f) | Jul 04, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [d82547b583](https://bsd-hardware.info/?probe=d82547b583) | Jul 04, 2022 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [a3cba2571b](https://bsd-hardware.info/?probe=a3cba2571b) | Jul 04, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [5777cb6dc6](https://bsd-hardware.info/?probe=5777cb6dc6) | Jul 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| MSI           | MS-B120                     | Mini pc     | [aa27c1dfd0](https://bsd-hardware.info/?probe=aa27c1dfd0) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [70aea59a1b](https://bsd-hardware.info/?probe=70aea59a1b) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [c285cb7899](https://bsd-hardware.info/?probe=c285cb7899) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| MSI           | B85M-E45                    | Desktop     | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| Lenovo        | ThinkPad X270 20HN001HUS    | Notebook    | [139e4817d7](https://bsd-hardware.info/?probe=139e4817d7) | Jun 21, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [ee4d6d5761](https://bsd-hardware.info/?probe=ee4d6d5761) | Jun 21, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [8ad937beaa](https://bsd-hardware.info/?probe=8ad937beaa) | Jun 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| HP            | 3031h                       | Desktop     | [96ecd77f94](https://bsd-hardware.info/?probe=96ecd77f94) | Jun 19, 2022 |
| HP            | 3031h                       | Desktop     | [4da4d936b8](https://bsd-hardware.info/?probe=4da4d936b8) | Jun 19, 2022 |
| Dell          | Latitude 5521               | Notebook    | [2c9d24a69e](https://bsd-hardware.info/?probe=2c9d24a69e) | Jun 19, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [6d4bc39638](https://bsd-hardware.info/?probe=6d4bc39638) | Jun 18, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Sony          | VGN-NS21M_S                 | Notebook    | [c9701a7ff5](https://bsd-hardware.info/?probe=c9701a7ff5) | Jun 18, 2022 |
| Intel         | NUC7i5BNB J31144-306        | Mini pc     | [66f9b621be](https://bsd-hardware.info/?probe=66f9b621be) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [3079ca74a6](https://bsd-hardware.info/?probe=3079ca74a6) | Jun 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b699c2a617](https://bsd-hardware.info/?probe=b699c2a617) | Jun 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [45083c3a78](https://bsd-hardware.info/?probe=45083c3a78) | Jun 15, 2022 |
| Dell          | Latitude E5420              | Notebook    | [524ab094e1](https://bsd-hardware.info/?probe=524ab094e1) | Jun 13, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [8825a49f37](https://bsd-hardware.info/?probe=8825a49f37) | Jun 13, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| Dell          | Latitude 7390               | Notebook    | [2b888ed291](https://bsd-hardware.info/?probe=2b888ed291) | Jun 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [387bf3d18f](https://bsd-hardware.info/?probe=387bf3d18f) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [edebcb2719](https://bsd-hardware.info/?probe=edebcb2719) | Jun 12, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| Dell          | 0804P1 A04                  | Server      | [c8ddb7dae6](https://bsd-hardware.info/?probe=c8ddb7dae6) | Jun 10, 2022 |
| Dell          | Latitude E5420              | Notebook    | [aca711c5ec](https://bsd-hardware.info/?probe=aca711c5ec) | Jun 09, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Precision M4800             | Notebook    | [4d77bb0082](https://bsd-hardware.info/?probe=4d77bb0082) | Jun 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [a3a9820968](https://bsd-hardware.info/?probe=a3a9820968) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 5410               | Notebook    | [3334ff3727](https://bsd-hardware.info/?probe=3334ff3727) | Jun 06, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [cb98f3014e](https://bsd-hardware.info/?probe=cb98f3014e) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | Aptio CRB SDK0E50515 STD    | Mini pc     | [260ae5b2fe](https://bsd-hardware.info/?probe=260ae5b2fe) | Jun 04, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude E5500              | Notebook    | [b1cb5de914](https://bsd-hardware.info/?probe=b1cb5de914) | Jun 03, 2022 |
| ASUSTek       | X441UV                      | Notebook    | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [1067f6ab27](https://bsd-hardware.info/?probe=1067f6ab27) | Jun 03, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29f1ef0cdc](https://bsd-hardware.info/?probe=29f1ef0cdc) | Jun 02, 2022 |
| Lenovo        | ThinkPad W520 4282AD4       | Notebook    | [40198abaa2](https://bsd-hardware.info/?probe=40198abaa2) | Jun 02, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [0cf6981a98](https://bsd-hardware.info/?probe=0cf6981a98) | Jun 02, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [1cc3d99da5](https://bsd-hardware.info/?probe=1cc3d99da5) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [a448570ff9](https://bsd-hardware.info/?probe=a448570ff9) | May 31, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [283a074737](https://bsd-hardware.info/?probe=283a074737) | May 31, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| GPD           | MicroPC                     | Notebook    | [0046ab7c9b](https://bsd-hardware.info/?probe=0046ab7c9b) | May 31, 2022 |
| NF-M2S        | ABIT                        | Desktop     | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [32854b73a5](https://bsd-hardware.info/?probe=32854b73a5) | May 30, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f39611345a](https://bsd-hardware.info/?probe=f39611345a) | May 30, 2022 |
| System76      | Galago Pro                  | Notebook    | [126ebc1522](https://bsd-hardware.info/?probe=126ebc1522) | May 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| Dell          | G5 5590                     | Notebook    | [86bac52410](https://bsd-hardware.info/?probe=86bac52410) | May 29, 2022 |
| Dell          | Latitude E6430              | Notebook    | [d7ced37bac](https://bsd-hardware.info/?probe=d7ced37bac) | May 29, 2022 |
| PC Engines    | APU3                        | Desktop     | [fca5a642c2](https://bsd-hardware.info/?probe=fca5a642c2) | May 28, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [cddd786b51](https://bsd-hardware.info/?probe=cddd786b51) | May 26, 2022 |
| HP            | 158A                        | Desktop     | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [37242aa9a3](https://bsd-hardware.info/?probe=37242aa9a3) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [c41aea0ea7](https://bsd-hardware.info/?probe=c41aea0ea7) | May 24, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [3dc5a6f7d2](https://bsd-hardware.info/?probe=3dc5a6f7d2) | May 24, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [727f9708b4](https://bsd-hardware.info/?probe=727f9708b4) | May 24, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [70871cf070](https://bsd-hardware.info/?probe=70871cf070) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| khadas        | edge-v                      | Desktop     | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | Desktop     | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [443b1d3c3e](https://bsd-hardware.info/?probe=443b1d3c3e) | May 22, 2022 |
| Dell          | Precision M4800             | Notebook    | [6a703b66f8](https://bsd-hardware.info/?probe=6a703b66f8) | May 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d5a0fd71f2](https://bsd-hardware.info/?probe=d5a0fd71f2) | May 22, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [2b93a0b59f](https://bsd-hardware.info/?probe=2b93a0b59f) | May 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [becc2fddbd](https://bsd-hardware.info/?probe=becc2fddbd) | May 22, 2022 |
| Intel         | NUC9i7QNB K49245-402        | Mini pc     | [92881489e1](https://bsd-hardware.info/?probe=92881489e1) | May 22, 2022 |
| Supermicro    | X9SRW-F                     | Server      | [89da730497](https://bsd-hardware.info/?probe=89da730497) | May 21, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| GVC           | DR 738                      | Desktop     | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [44abecc1ef](https://bsd-hardware.info/?probe=44abecc1ef) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [6ffa9529a3](https://bsd-hardware.info/?probe=6ffa9529a3) | May 20, 2022 |
| ASUSTek       | 1001P                       | Notebook    | [2820584223](https://bsd-hardware.info/?probe=2820584223) | May 20, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [819bed6cfb](https://bsd-hardware.info/?probe=819bed6cfb) | May 19, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Lenovo        | MAHOBAY 31900004 STD        | All in one  | [a9189728e3](https://bsd-hardware.info/?probe=a9189728e3) | May 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1c84f0f722](https://bsd-hardware.info/?probe=1c84f0f722) | May 19, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [f369e09063](https://bsd-hardware.info/?probe=f369e09063) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [d5a6eba10b](https://bsd-hardware.info/?probe=d5a6eba10b) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Lenovo        | ThinkPad L420 7854CTO       | Notebook    | [56cf502c2f](https://bsd-hardware.info/?probe=56cf502c2f) | May 18, 2022 |
| Lenovo        | ThinkPad T420s 41732AU      | Notebook    | [9d9ddcc409](https://bsd-hardware.info/?probe=9d9ddcc409) | May 18, 2022 |
| Lenovo        | ThinkPad X270 20HMCTO1WW    | Notebook    | [2d3de77101](https://bsd-hardware.info/?probe=2d3de77101) | May 18, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [86866ce217](https://bsd-hardware.info/?probe=86866ce217) | May 17, 2022 |
| Dell          | 04JN2K A12                  | Server      | [550e12f317](https://bsd-hardware.info/?probe=550e12f317) | May 17, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [311c32e56e](https://bsd-hardware.info/?probe=311c32e56e) | May 17, 2022 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [7189b48418](https://bsd-hardware.info/?probe=7189b48418) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Dell          | 07T4MC A11                  | Desktop     | [63d6080a31](https://bsd-hardware.info/?probe=63d6080a31) | May 17, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | Desktop     | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [6dc325b553](https://bsd-hardware.info/?probe=6dc325b553) | May 15, 2022 |
| ASRock        | E350M1                      | Desktop     | [1850fa38e0](https://bsd-hardware.info/?probe=1850fa38e0) | May 14, 2022 |
| ASRock        | E350M1                      | Desktop     | [4520b5034e](https://bsd-hardware.info/?probe=4520b5034e) | May 13, 2022 |
| MSI           | MS-7369                     | Desktop     | [c2c6bd80e8](https://bsd-hardware.info/?probe=c2c6bd80e8) | May 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [f3ab857e43](https://bsd-hardware.info/?probe=f3ab857e43) | May 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6a9177eef7](https://bsd-hardware.info/?probe=6a9177eef7) | May 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [11034dd80f](https://bsd-hardware.info/?probe=11034dd80f) | May 13, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [3a3729e497](https://bsd-hardware.info/?probe=3a3729e497) | May 12, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [46b11e5051](https://bsd-hardware.info/?probe=46b11e5051) | May 12, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [54a5041cdf](https://bsd-hardware.info/?probe=54a5041cdf) | May 12, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [991f67362f](https://bsd-hardware.info/?probe=991f67362f) | May 12, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [8cdb309c2e](https://bsd-hardware.info/?probe=8cdb309c2e) | May 11, 2022 |
| ASRock        | A320M Pro4-F                | Desktop     | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| Dell          | Latitude 2100               | Notebook    | [40406069ee](https://bsd-hardware.info/?probe=40406069ee) | May 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [5259bc1933](https://bsd-hardware.info/?probe=5259bc1933) | May 08, 2022 |
| Lenovo        | ThinkPad X250 20CLS02V00    | Notebook    | [7e2771b8f6](https://bsd-hardware.info/?probe=7e2771b8f6) | May 08, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [a69f0fefca](https://bsd-hardware.info/?probe=a69f0fefca) | May 07, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [331947afe1](https://bsd-hardware.info/?probe=331947afe1) | May 07, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [850df51257](https://bsd-hardware.info/?probe=850df51257) | May 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [659e98fd68](https://bsd-hardware.info/?probe=659e98fd68) | May 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [015bf0fea4](https://bsd-hardware.info/?probe=015bf0fea4) | May 06, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | Notebook    | [e99738632d](https://bsd-hardware.info/?probe=e99738632d) | May 06, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [407fc42fad](https://bsd-hardware.info/?probe=407fc42fad) | May 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | Vostro 5590                 | Notebook    | [1f23973fb4](https://bsd-hardware.info/?probe=1f23973fb4) | May 04, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [86ea07c719](https://bsd-hardware.info/?probe=86ea07c719) | May 03, 2022 |
| Acer          | Aspire ES1-132              | Notebook    | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [1fde9daf7d](https://bsd-hardware.info/?probe=1fde9daf7d) | May 01, 2022 |
| Dell          | Latitude E5570              | Notebook    | [c214ce4ab0](https://bsd-hardware.info/?probe=c214ce4ab0) | May 01, 2022 |
| Toshiba       | Satellite P25               | Notebook    | [6a920e9c8a](https://bsd-hardware.info/?probe=6a920e9c8a) | May 01, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| HP            | 8158 A01                    | Mini pc     | [de45e5a021](https://bsd-hardware.info/?probe=de45e5a021) | Apr 29, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7a212b5833](https://bsd-hardware.info/?probe=7a212b5833) | Apr 29, 2022 |
| HP            | 1495                        | Desktop     | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [336add4fcb](https://bsd-hardware.info/?probe=336add4fcb) | Apr 28, 2022 |
| Lenovo        | ThinkPad T470 20HES0ES1F    | Notebook    | [f1f0676663](https://bsd-hardware.info/?probe=f1f0676663) | Apr 28, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [34f2ba40e7](https://bsd-hardware.info/?probe=34f2ba40e7) | Apr 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0750e29d3c](https://bsd-hardware.info/?probe=0750e29d3c) | Apr 27, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [30e267dd51](https://bsd-hardware.info/?probe=30e267dd51) | Apr 27, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [b7c06932a3](https://bsd-hardware.info/?probe=b7c06932a3) | Apr 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | Desktop     | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Framework     | Laptop                      | Notebook    | [5d6cb039ea](https://bsd-hardware.info/?probe=5d6cb039ea) | Apr 25, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [09a475e0bc](https://bsd-hardware.info/?probe=09a475e0bc) | Apr 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [3834dccb1f](https://bsd-hardware.info/?probe=3834dccb1f) | Apr 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [86c4af7ca4](https://bsd-hardware.info/?probe=86c4af7ca4) | Apr 25, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [e588c93d54](https://bsd-hardware.info/?probe=e588c93d54) | Apr 24, 2022 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [fd100bcc6a](https://bsd-hardware.info/?probe=fd100bcc6a) | Apr 24, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | Latitude E6520              | Notebook    | [c4ae703add](https://bsd-hardware.info/?probe=c4ae703add) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [89fcee49d9](https://bsd-hardware.info/?probe=89fcee49d9) | Apr 22, 2022 |
| HP            | 2820h                       | Desktop     | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Lenovo        | B570 1068FQG                | Notebook    | [a0d1f01226](https://bsd-hardware.info/?probe=a0d1f01226) | Apr 22, 2022 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [947038b1f9](https://bsd-hardware.info/?probe=947038b1f9) | Apr 22, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [28c8d07136](https://bsd-hardware.info/?probe=28c8d07136) | Apr 22, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [dde6af4613](https://bsd-hardware.info/?probe=dde6af4613) | Apr 19, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [eb3d850e0a](https://bsd-hardware.info/?probe=eb3d850e0a) | Apr 17, 2022 |
| ASRockRack    | C3758D4I-4L                 | Desktop     | [0a550ec649](https://bsd-hardware.info/?probe=0a550ec649) | Apr 17, 2022 |
| ASRockRack    | C3758D4I-4L                 | Desktop     | [c1e6f095a8](https://bsd-hardware.info/?probe=c1e6f095a8) | Apr 17, 2022 |
| System76      | Lemur Pro                   | Notebook    | [bbeb7d48fa](https://bsd-hardware.info/?probe=bbeb7d48fa) | Apr 17, 2022 |
| Shuttle       | DS20U                       | Desktop     | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Shuttle       | SH570                       | Desktop     | [08e2af8890](https://bsd-hardware.info/?probe=08e2af8890) | Apr 16, 2022 |
| ASUSTek       | AT5NM10T-I                  | Desktop     | [211c3291dd](https://bsd-hardware.info/?probe=211c3291dd) | Apr 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [eda0880c67](https://bsd-hardware.info/?probe=eda0880c67) | Apr 15, 2022 |
| HP            | 86E9 A                      | Desktop     | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f6bc20d345](https://bsd-hardware.info/?probe=f6bc20d345) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [bb9129d4df](https://bsd-hardware.info/?probe=bb9129d4df) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [4cbd9f9314](https://bsd-hardware.info/?probe=4cbd9f9314) | Apr 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [eea29a3895](https://bsd-hardware.info/?probe=eea29a3895) | Apr 12, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [ecbb820987](https://bsd-hardware.info/?probe=ecbb820987) | Apr 12, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [e0f42a2bb2](https://bsd-hardware.info/?probe=e0f42a2bb2) | Apr 11, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Lenovo        | ThinkPad X201 3680MG1       | Notebook    | [a2b9975fe2](https://bsd-hardware.info/?probe=a2b9975fe2) | Apr 11, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | Notebook    | [edbde611c3](https://bsd-hardware.info/?probe=edbde611c3) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [7f156a0671](https://bsd-hardware.info/?probe=7f156a0671) | Apr 10, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [a006c9e999](https://bsd-hardware.info/?probe=a006c9e999) | Apr 10, 2022 |
| MSI           | H81M-P33                    | Desktop     | [52abbcbc5b](https://bsd-hardware.info/?probe=52abbcbc5b) | Apr 10, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [0cbb5faa2e](https://bsd-hardware.info/?probe=0cbb5faa2e) | Apr 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5d759d6436](https://bsd-hardware.info/?probe=5d759d6436) | Apr 10, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [de2cd29be6](https://bsd-hardware.info/?probe=de2cd29be6) | Apr 10, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [58223e52f7](https://bsd-hardware.info/?probe=58223e52f7) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 42872WU       | Notebook    | [3b7da460a2](https://bsd-hardware.info/?probe=3b7da460a2) | Apr 10, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [2a03c05cce](https://bsd-hardware.info/?probe=2a03c05cce) | Apr 10, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [fa4b6b0257](https://bsd-hardware.info/?probe=fa4b6b0257) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | Desktop     | [4436915ba0](https://bsd-hardware.info/?probe=4436915ba0) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-210         | Desktop     | [a01376dfc5](https://bsd-hardware.info/?probe=a01376dfc5) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | Desktop     | [85a5d08117](https://bsd-hardware.info/?probe=85a5d08117) | Apr 09, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [689ff6c484](https://bsd-hardware.info/?probe=689ff6c484) | Apr 09, 2022 |
| Lenovo        | ThinkPad T495 20NJ0000US    | Notebook    | [c626b32508](https://bsd-hardware.info/?probe=c626b32508) | Apr 09, 2022 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [b9a45002ae](https://bsd-hardware.info/?probe=b9a45002ae) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [68f10ed8de](https://bsd-hardware.info/?probe=68f10ed8de) | Apr 09, 2022 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [092643d1c3](https://bsd-hardware.info/?probe=092643d1c3) | Apr 09, 2022 |
| Intel         | DH61CR AAG14064-205         | Desktop     | [02b581994b](https://bsd-hardware.info/?probe=02b581994b) | Apr 08, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [7bc748ce7c](https://bsd-hardware.info/?probe=7bc748ce7c) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [840805d1fa](https://bsd-hardware.info/?probe=840805d1fa) | Apr 08, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [7e0964d31d](https://bsd-hardware.info/?probe=7e0964d31d) | Apr 08, 2022 |
| Dell          | 07YXFK A00                  | Server      | [de85a76391](https://bsd-hardware.info/?probe=de85a76391) | Apr 07, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [ee73e0cddb](https://bsd-hardware.info/?probe=ee73e0cddb) | Apr 07, 2022 |
| Dell          | 0RMRF7 A06                  | Server      | [3b18b65e78](https://bsd-hardware.info/?probe=3b18b65e78) | Apr 07, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [da64cbb0d1](https://bsd-hardware.info/?probe=da64cbb0d1) | Apr 07, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [d9ef1569d2](https://bsd-hardware.info/?probe=d9ef1569d2) | Apr 07, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [99343fc0da](https://bsd-hardware.info/?probe=99343fc0da) | Apr 06, 2022 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7db1501c5c](https://bsd-hardware.info/?probe=7db1501c5c) | Apr 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2d04e83ea4](https://bsd-hardware.info/?probe=2d04e83ea4) | Apr 06, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [5556bf474c](https://bsd-hardware.info/?probe=5556bf474c) | Apr 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [821456e342](https://bsd-hardware.info/?probe=821456e342) | Apr 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [6955791aa5](https://bsd-hardware.info/?probe=6955791aa5) | Apr 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [debc9ceac3](https://bsd-hardware.info/?probe=debc9ceac3) | Apr 06, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| Dell          | Precision M4800             | Notebook    | [7a7968204a](https://bsd-hardware.info/?probe=7a7968204a) | Apr 06, 2022 |
| Dell          | 07978V A08                  | Server      | [f315c33e95](https://bsd-hardware.info/?probe=f315c33e95) | Apr 06, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7eee3bb3d8](https://bsd-hardware.info/?probe=7eee3bb3d8) | Apr 06, 2022 |
| Timi          | TM1612                      | Notebook    | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [64d42b9c5f](https://bsd-hardware.info/?probe=64d42b9c5f) | Apr 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [1dd1823662](https://bsd-hardware.info/?probe=1dd1823662) | Apr 04, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| ASUSTek       | UX305UA                     | Notebook    | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| HP            | 212B                        | Desktop     | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [0c73871c49](https://bsd-hardware.info/?probe=0c73871c49) | Apr 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1043649da9](https://bsd-hardware.info/?probe=1043649da9) | Apr 03, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b0d11aabb7](https://bsd-hardware.info/?probe=b0d11aabb7) | Apr 03, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [dbaaa0dcda](https://bsd-hardware.info/?probe=dbaaa0dcda) | Apr 03, 2022 |
| VIT           | M2420                       | Notebook    | [108b4d79a6](https://bsd-hardware.info/?probe=108b4d79a6) | Apr 03, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [1868573e9a](https://bsd-hardware.info/?probe=1868573e9a) | Apr 02, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [cdd056df79](https://bsd-hardware.info/?probe=cdd056df79) | Mar 31, 2022 |
| HP            | 158A                        | Desktop     | [5d463584db](https://bsd-hardware.info/?probe=5d463584db) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5A28AUK    | Notebook    | [f53c625efd](https://bsd-hardware.info/?probe=f53c625efd) | Mar 30, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [0542f7a16d](https://bsd-hardware.info/?probe=0542f7a16d) | Mar 29, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [e363c95c1c](https://bsd-hardware.info/?probe=e363c95c1c) | Mar 29, 2022 |
| ASUSTek       | D700SA                      | Desktop     | [e0d66ad9cf](https://bsd-hardware.info/?probe=e0d66ad9cf) | Mar 28, 2022 |
| MSI           | H81M-P33                    | Desktop     | [823d2d7336](https://bsd-hardware.info/?probe=823d2d7336) | Mar 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [4e44bfd765](https://bsd-hardware.info/?probe=4e44bfd765) | Mar 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [51507583f6](https://bsd-hardware.info/?probe=51507583f6) | Mar 27, 2022 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [0a90b33ac1](https://bsd-hardware.info/?probe=0a90b33ac1) | Mar 26, 2022 |
| Deciso        | Netboard A20                | Notebook    | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Deciso        | Netboard A20                | Notebook    | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d9e74758f3](https://bsd-hardware.info/?probe=d9e74758f3) | Mar 24, 2022 |
| Lenovo        | ThinkPad R60e 0658W2M       | Notebook    | [315573b63e](https://bsd-hardware.info/?probe=315573b63e) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| Lenovo        | ThinkPad X230 2325BV9       | Notebook    | [d2a16f6102](https://bsd-hardware.info/?probe=d2a16f6102) | Mar 23, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [30432daccb](https://bsd-hardware.info/?probe=30432daccb) | Mar 23, 2022 |
| MSI           | MS-A6221 100                | Desktop     | [ba62f48990](https://bsd-hardware.info/?probe=ba62f48990) | Mar 23, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [693d365311](https://bsd-hardware.info/?probe=693d365311) | Mar 23, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [7c46c8e712](https://bsd-hardware.info/?probe=7c46c8e712) | Mar 23, 2022 |
| Gateway       | NV55C                       | Notebook    | [a63381d681](https://bsd-hardware.info/?probe=a63381d681) | Mar 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [6858ad2b12](https://bsd-hardware.info/?probe=6858ad2b12) | Mar 22, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4a9a28c612](https://bsd-hardware.info/?probe=4a9a28c612) | Mar 22, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [543bcf2d09](https://bsd-hardware.info/?probe=543bcf2d09) | Mar 22, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [6ceff4eca1](https://bsd-hardware.info/?probe=6ceff4eca1) | Mar 21, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9f760529c1](https://bsd-hardware.info/?probe=9f760529c1) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [c4ffde79eb](https://bsd-hardware.info/?probe=c4ffde79eb) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [7e1e137c8f](https://bsd-hardware.info/?probe=7e1e137c8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6a579dca44](https://bsd-hardware.info/?probe=6a579dca44) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [2aeeaaacfc](https://bsd-hardware.info/?probe=2aeeaaacfc) | Mar 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [4b6df22ff5](https://bsd-hardware.info/?probe=4b6df22ff5) | Mar 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d9421c2715](https://bsd-hardware.info/?probe=d9421c2715) | Mar 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [5a6cb7ab07](https://bsd-hardware.info/?probe=5a6cb7ab07) | Mar 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [12814be80b](https://bsd-hardware.info/?probe=12814be80b) | Mar 20, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [0dbac1ca61](https://bsd-hardware.info/?probe=0dbac1ca61) | Mar 19, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [054946738a](https://bsd-hardware.info/?probe=054946738a) | Mar 19, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a776ebf7f4](https://bsd-hardware.info/?probe=a776ebf7f4) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | Notebook    | [5ff92a5bb3](https://bsd-hardware.info/?probe=5ff92a5bb3) | Mar 19, 2022 |
| Toshiba       | Satellite Pro L40           | Notebook    | [71a7b43ec6](https://bsd-hardware.info/?probe=71a7b43ec6) | Mar 19, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [753af67ffa](https://bsd-hardware.info/?probe=753af67ffa) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [6d4ac7f6f5](https://bsd-hardware.info/?probe=6d4ac7f6f5) | Mar 18, 2022 |
| Lenovo        | ThinkPad T460s 20FAS4KH0... | Notebook    | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [3f94a005a7](https://bsd-hardware.info/?probe=3f94a005a7) | Mar 17, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [bb895c5df3](https://bsd-hardware.info/?probe=bb895c5df3) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [b137b25594](https://bsd-hardware.info/?probe=b137b25594) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [8bd2318fb6](https://bsd-hardware.info/?probe=8bd2318fb6) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| Gateway       | LT27                        | Notebook    | [6d1c6f8215](https://bsd-hardware.info/?probe=6d1c6f8215) | Mar 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [9e440b5500](https://bsd-hardware.info/?probe=9e440b5500) | Mar 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Supermicro    | X11SPA-TF                   | Server      | [ce8759e747](https://bsd-hardware.info/?probe=ce8759e747) | Mar 12, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e04a1b354c](https://bsd-hardware.info/?probe=e04a1b354c) | Mar 11, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [fbde5657e8](https://bsd-hardware.info/?probe=fbde5657e8) | Mar 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [ac59621182](https://bsd-hardware.info/?probe=ac59621182) | Mar 10, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [b4142103cb](https://bsd-hardware.info/?probe=b4142103cb) | Mar 10, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [be311b6a34](https://bsd-hardware.info/?probe=be311b6a34) | Mar 10, 2022 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [17b3590a3f](https://bsd-hardware.info/?probe=17b3590a3f) | Mar 08, 2022 |
| Dell          | G5 5590                     | Notebook    | [0871c1269b](https://bsd-hardware.info/?probe=0871c1269b) | Mar 07, 2022 |
| Cisco Syst... | UCSC-C3K-M4SRB 73-17622-... | Server      | [f168e21dd6](https://bsd-hardware.info/?probe=f168e21dd6) | Mar 07, 2022 |
| Intel         | DX79TO AAG28805-401         | Desktop     | [431b37f050](https://bsd-hardware.info/?probe=431b37f050) | Mar 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [20cdc9d999](https://bsd-hardware.info/?probe=20cdc9d999) | Mar 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f8801c62bc](https://bsd-hardware.info/?probe=f8801c62bc) | Mar 05, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0d2956a144](https://bsd-hardware.info/?probe=0d2956a144) | Mar 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [1daab68f1f](https://bsd-hardware.info/?probe=1daab68f1f) | Mar 04, 2022 |
| Intel         | D865PERL AAC27646-213       | Desktop     | [4e11b970ab](https://bsd-hardware.info/?probe=4e11b970ab) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| Framework     | Laptop                      | Notebook    | [1f58e0594f](https://bsd-hardware.info/?probe=1f58e0594f) | Mar 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f1d5448b3](https://bsd-hardware.info/?probe=3f1d5448b3) | Mar 01, 2022 |
| Supermicro    | A2SDi-LN4F                  | Desktop     | [b10f6655d9](https://bsd-hardware.info/?probe=b10f6655d9) | Mar 01, 2022 |
| Dell          | 0DNFFW A00                  | All in one  | [2db3ec9574](https://bsd-hardware.info/?probe=2db3ec9574) | Feb 27, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1JN0... | Notebook    | [cba9255f4a](https://bsd-hardware.info/?probe=cba9255f4a) | Feb 27, 2022 |
| Cisco Syst... | UCSC-C240-M4L 74-12420-0... | Server      | [5d94552e31](https://bsd-hardware.info/?probe=5d94552e31) | Feb 27, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c34e21ffd5](https://bsd-hardware.info/?probe=c34e21ffd5) | Feb 26, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [d45ca02f84](https://bsd-hardware.info/?probe=d45ca02f84) | Feb 24, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [7467d71c8d](https://bsd-hardware.info/?probe=7467d71c8d) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [fdde41404d](https://bsd-hardware.info/?probe=fdde41404d) | Feb 24, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [68f6eb4328](https://bsd-hardware.info/?probe=68f6eb4328) | Feb 23, 2022 |
| Shuttle       | FZ270                       | Desktop     | [7e0eb61342](https://bsd-hardware.info/?probe=7e0eb61342) | Feb 22, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [c1397b851e](https://bsd-hardware.info/?probe=c1397b851e) | Feb 22, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| ASRock        | A88M-G                      | Desktop     | [14fcd1e849](https://bsd-hardware.info/?probe=14fcd1e849) | Feb 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [f0e8e4a30a](https://bsd-hardware.info/?probe=f0e8e4a30a) | Feb 21, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [807a29112e](https://bsd-hardware.info/?probe=807a29112e) | Feb 19, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [0f3ee4caab](https://bsd-hardware.info/?probe=0f3ee4caab) | Feb 18, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [bc5296ee7d](https://bsd-hardware.info/?probe=bc5296ee7d) | Feb 16, 2022 |
| Cisco Syst... | UCSC-C3K-M4SRB 73-17622-... | Server      | [95c7aed281](https://bsd-hardware.info/?probe=95c7aed281) | Feb 16, 2022 |
| ASRockRack    | EPYC3101D4I-2T              | Desktop     | [e506cf84f4](https://bsd-hardware.info/?probe=e506cf84f4) | Feb 15, 2022 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [2b58423bfe](https://bsd-hardware.info/?probe=2b58423bfe) | Feb 15, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f1796d75ed](https://bsd-hardware.info/?probe=f1796d75ed) | Feb 14, 2022 |
| WOOKING       | X5                          | Notebook    | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [99f564e44a](https://bsd-hardware.info/?probe=99f564e44a) | Feb 14, 2022 |
| Biostar       | X470GTA                     | Desktop     | [b7fc5ef684](https://bsd-hardware.info/?probe=b7fc5ef684) | Feb 12, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [5b4505d25e](https://bsd-hardware.info/?probe=5b4505d25e) | Feb 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [42c29744d6](https://bsd-hardware.info/?probe=42c29744d6) | Feb 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1b042ff2e0](https://bsd-hardware.info/?probe=1b042ff2e0) | Feb 11, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [946c9acc2e](https://bsd-hardware.info/?probe=946c9acc2e) | Feb 11, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| HP            | 83E1                        | Desktop     | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | 1215B                       | Notebook    | [1ccf85f60d](https://bsd-hardware.info/?probe=1ccf85f60d) | Feb 10, 2022 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [8be9390356](https://bsd-hardware.info/?probe=8be9390356) | Feb 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [3c315d0c15](https://bsd-hardware.info/?probe=3c315d0c15) | Feb 09, 2022 |
| ASUSTek       | A9T                         | Notebook    | [2962e2b02f](https://bsd-hardware.info/?probe=2962e2b02f) | Feb 09, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ae4f0642fd](https://bsd-hardware.info/?probe=ae4f0642fd) | Feb 09, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [5063e8f546](https://bsd-hardware.info/?probe=5063e8f546) | Feb 08, 2022 |
| Dell          | 0654JC A01                  | Desktop     | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| HP            | 0B54h D                     | Desktop     | [c2b43efb8f](https://bsd-hardware.info/?probe=c2b43efb8f) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d38089ced](https://bsd-hardware.info/?probe=8d38089ced) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d04ab1a7bf](https://bsd-hardware.info/?probe=d04ab1a7bf) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [7987f643d7](https://bsd-hardware.info/?probe=7987f643d7) | Feb 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [12e979c82a](https://bsd-hardware.info/?probe=12e979c82a) | Feb 06, 2022 |
| HP            | 0B54h D                     | Desktop     | [1878f5822c](https://bsd-hardware.info/?probe=1878f5822c) | Feb 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b9ed6f82cc](https://bsd-hardware.info/?probe=b9ed6f82cc) | Feb 06, 2022 |
| HP            | ProLiant ML350p Gen8        | Desktop     | [b9e0021bfb](https://bsd-hardware.info/?probe=b9e0021bfb) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e41d9cff21](https://bsd-hardware.info/?probe=e41d9cff21) | Feb 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [049a615166](https://bsd-hardware.info/?probe=049a615166) | Feb 06, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [5afa08fe32](https://bsd-hardware.info/?probe=5afa08fe32) | Feb 06, 2022 |
| System76      | Lemur Pro                   | Notebook    | [713b33351f](https://bsd-hardware.info/?probe=713b33351f) | Feb 06, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [b6329aa072](https://bsd-hardware.info/?probe=b6329aa072) | Feb 06, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [3b3ff8b95d](https://bsd-hardware.info/?probe=3b3ff8b95d) | Feb 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [840c7f2142](https://bsd-hardware.info/?probe=840c7f2142) | Feb 05, 2022 |
| Gateway       | DX4870                      | Desktop     | [5035507c5c](https://bsd-hardware.info/?probe=5035507c5c) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [e23b3e314a](https://bsd-hardware.info/?probe=e23b3e314a) | Feb 05, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [f333ed9201](https://bsd-hardware.info/?probe=f333ed9201) | Feb 05, 2022 |
| Gateway       | DX4870                      | Desktop     | [1f31c4a99b](https://bsd-hardware.info/?probe=1f31c4a99b) | Feb 05, 2022 |
| ASUSTek       | P4P800-VM                   | Desktop     | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| Dell          | 05DN3X A00                  | Desktop     | [edef5c789d](https://bsd-hardware.info/?probe=edef5c789d) | Feb 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e660899158](https://bsd-hardware.info/?probe=e660899158) | Feb 03, 2022 |
| Dell          | Latitude E7450              | Notebook    | [8a3867f171](https://bsd-hardware.info/?probe=8a3867f171) | Feb 03, 2022 |
| Supermicro    | H11DSi                      | Server      | [4e41dc7f8b](https://bsd-hardware.info/?probe=4e41dc7f8b) | Feb 03, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [3debf6433b](https://bsd-hardware.info/?probe=3debf6433b) | Feb 02, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [c03bfe6a21](https://bsd-hardware.info/?probe=c03bfe6a21) | Feb 01, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [97ef0862c2](https://bsd-hardware.info/?probe=97ef0862c2) | Feb 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [cb0ebb96d5](https://bsd-hardware.info/?probe=cb0ebb96d5) | Feb 01, 2022 |
| Dell          | G3 3500                     | Notebook    | [536a7a1b38](https://bsd-hardware.info/?probe=536a7a1b38) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1GX0... | Notebook    | [556fcb7e5e](https://bsd-hardware.info/?probe=556fcb7e5e) | Jan 31, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [61e3f35ee8](https://bsd-hardware.info/?probe=61e3f35ee8) | Jan 31, 2022 |
| Dell          | 0D28YY A02                  | Desktop     | [8eb27db8c9](https://bsd-hardware.info/?probe=8eb27db8c9) | Jan 31, 2022 |
| Dell          | 0J37VM A01                  | Desktop     | [47061377bd](https://bsd-hardware.info/?probe=47061377bd) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | Notebook    | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Dell          | 0TK7TF A00                  | Desktop     | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| GPD           | G1621-02                    | Notebook    | [1970f517fd](https://bsd-hardware.info/?probe=1970f517fd) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| HP            | Notebook                    | Notebook    | [b0e0bc12c8](https://bsd-hardware.info/?probe=b0e0bc12c8) | Jan 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f47789d894](https://bsd-hardware.info/?probe=f47789d894) | Jan 29, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e0c2a150f7](https://bsd-hardware.info/?probe=e0c2a150f7) | Jan 29, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [37cc045649](https://bsd-hardware.info/?probe=37cc045649) | Jan 28, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7ef0e518f](https://bsd-hardware.info/?probe=c7ef0e518f) | Jan 27, 2022 |
| MSI           | GE76 Raider 10UG            | Notebook    | [b48b628936](https://bsd-hardware.info/?probe=b48b628936) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| Firefly       | ROC-RK3566-PC               | Soc         | [aac0cd5332](https://bsd-hardware.info/?probe=aac0cd5332) | Jan 27, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [652e2e284f](https://bsd-hardware.info/?probe=652e2e284f) | Jan 26, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b62251041b](https://bsd-hardware.info/?probe=b62251041b) | Jan 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4df3db0379](https://bsd-hardware.info/?probe=4df3db0379) | Jan 26, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [28f84e935f](https://bsd-hardware.info/?probe=28f84e935f) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [e54be582a7](https://bsd-hardware.info/?probe=e54be582a7) | Jan 25, 2022 |
| MSI           | GT75VR 7RF                  | Notebook    | [db276eaa53](https://bsd-hardware.info/?probe=db276eaa53) | Jan 25, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [acaa85b561](https://bsd-hardware.info/?probe=acaa85b561) | Jan 25, 2022 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [83d1798c6e](https://bsd-hardware.info/?probe=83d1798c6e) | Jan 24, 2022 |
| ASUSTek       | P5M2                        | Desktop     | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a90b68e57b](https://bsd-hardware.info/?probe=a90b68e57b) | Jan 23, 2022 |
| MSI           | H81M-P33                    | Desktop     | [9d6207401e](https://bsd-hardware.info/?probe=9d6207401e) | Jan 23, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [691f4c1a9a](https://bsd-hardware.info/?probe=691f4c1a9a) | Jan 23, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [082da3ef7f](https://bsd-hardware.info/?probe=082da3ef7f) | Jan 19, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [268e1621eb](https://bsd-hardware.info/?probe=268e1621eb) | Jan 18, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [61406080a7](https://bsd-hardware.info/?probe=61406080a7) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1763a44db9](https://bsd-hardware.info/?probe=1763a44db9) | Jan 18, 2022 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [2aea9384ac](https://bsd-hardware.info/?probe=2aea9384ac) | Jan 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [9f442754d0](https://bsd-hardware.info/?probe=9f442754d0) | Jan 17, 2022 |
| ASUSTek       | N50Vc                       | Notebook    | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [4cc0e9443d](https://bsd-hardware.info/?probe=4cc0e9443d) | Jan 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7307e3e0be](https://bsd-hardware.info/?probe=7307e3e0be) | Jan 16, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [d9f18d4d56](https://bsd-hardware.info/?probe=d9f18d4d56) | Jan 16, 2022 |
| Supermicro    | X8DTH                       | Server      | [2f589abf33](https://bsd-hardware.info/?probe=2f589abf33) | Jan 16, 2022 |
| Dell          | 0599V5 A06                  | Server      | [ba13bbecfd](https://bsd-hardware.info/?probe=ba13bbecfd) | Jan 16, 2022 |
| Dell          | 0599V5 A06                  | Server      | [5d84fb4075](https://bsd-hardware.info/?probe=5d84fb4075) | Jan 16, 2022 |
| Acer          | TravelMate 8481TG           | Notebook    | [fae71f7e35](https://bsd-hardware.info/?probe=fae71f7e35) | Jan 15, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8b55745b6f](https://bsd-hardware.info/?probe=8b55745b6f) | Jan 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [d09cf2e0a7](https://bsd-hardware.info/?probe=d09cf2e0a7) | Jan 14, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [280ea0618b](https://bsd-hardware.info/?probe=280ea0618b) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [825d20fcf7](https://bsd-hardware.info/?probe=825d20fcf7) | Jan 14, 2022 |
| Lenovo        | ThinkPad T460p 20FXS09D1... | Notebook    | [3ef1595af6](https://bsd-hardware.info/?probe=3ef1595af6) | Jan 13, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b953d9d2e6](https://bsd-hardware.info/?probe=b953d9d2e6) | Jan 13, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1d7c4c096e](https://bsd-hardware.info/?probe=1d7c4c096e) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [1527560bbd](https://bsd-hardware.info/?probe=1527560bbd) | Jan 11, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [0da2a93271](https://bsd-hardware.info/?probe=0da2a93271) | Jan 11, 2022 |
| Lenovo        | ThinkPad E480 20KN0048IA    | Notebook    | [1a2f28f5cc](https://bsd-hardware.info/?probe=1a2f28f5cc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Supermicro    | X7SBL                       | Desktop     | [c7d877a988](https://bsd-hardware.info/?probe=c7d877a988) | Jan 11, 2022 |
| Intel         | DH61CR AAG14064-210         | Desktop     | [15bb78bf9a](https://bsd-hardware.info/?probe=15bb78bf9a) | Jan 11, 2022 |
| Intel         | DQ35JO AAD82085-804         | Desktop     | [117b469a53](https://bsd-hardware.info/?probe=117b469a53) | Jan 11, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/FreeBSD/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.0         | 222       | 9.22%   |
| FreeBSD 13.1         | 195       | 8.1%    |
| FreeBSD 12.2         | 141       | 5.86%   |
| FreeBSD 14.0-CURRENT | 115       | 4.78%   |
| FreeBSD 12.2-p2      | 96        | 3.99%   |
| FreeBSD 13.0-p4      | 85        | 3.53%   |
| FreeBSD 12.1-p10     | 79        | 3.28%   |
| FreeBSD 13.0-p5      | 76        | 3.16%   |
| FreeBSD 13.0-STABLE  | 72        | 2.99%   |
| FreeBSD 12.1-p8      | 69        | 2.87%   |
| FreeBSD 13.1-p2      | 68        | 2.83%   |
| FreeBSD 13.0-CURRENT | 66        | 2.74%   |
| FreeBSD 12.1         | 58        | 2.41%   |
| FreeBSD 12.1-p5      | 55        | 2.29%   |
| FreeBSD 13.1-p5      | 53        | 2.2%    |
| FreeBSD 12.2-p3      | 52        | 2.16%   |
| FreeBSD 12.1-STABLE  | 49        | 2.04%   |
| FreeBSD 12.1-p7      | 48        | 1.99%   |
| FreeBSD 13.0-p3      | 47        | 1.95%   |
| FreeBSD 12.2-p4      | 47        | 1.95%   |
| FreeBSD 13.0-p7      | 44        | 1.83%   |
| FreeBSD 13.0-p11     | 37        | 1.54%   |
| FreeBSD 12.2-p6      | 35        | 1.45%   |
| FreeBSD 13.0-p2      | 33        | 1.37%   |
| FreeBSD 12.2-STABLE  | 32        | 1.33%   |
| FreeBSD 13.1-p1      | 28        | 1.16%   |
| FreeBSD 13.1-STABLE  | 25        | 1.04%   |
| FreeBSD 13.0-p6      | 25        | 1.04%   |
| FreeBSD 12.3         | 23        | 0.96%   |
| FreeBSD 13.0-p10     | 22        | 0.91%   |
| FreeBSD 12.1-p6      | 21        | 0.87%   |
| FreeBSD 13.1-p4      | 20        | 0.83%   |
| FreeBSD 12.2-p10     | 17        | 0.71%   |
| FreeBSD 12.1-p4      | 17        | 0.71%   |
| FreeBSD 12.3-p5      | 16        | 0.66%   |
| FreeBSD 12.1-p9      | 16        | 0.66%   |
| FreeBSD 13.1-p3      | 15        | 0.62%   |
| FreeBSD 12.1-p12     | 12        | 0.5%    |
| FreeBSD 12.2-p1      | 11        | 0.46%   |
| FreeBSD 13.0-RC2     | 9         | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| FreeBSD | 2006      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 1856      | 92.48%  |
| i386    | 69        | 3.44%   |
| arm64   | 67        | 3.34%   |
| arm     | 11        | 0.55%   |
| powerpc | 2         | 0.1%    |
| sparc64 | 1         | 0.05%   |
| riscv   | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 706       | 33.88%  |
| XFCE          | 332       | 15.93%  |
| KDE5          | 319       | 15.31%  |
| TWM           | 150       | 7.2%    |
| GNOME         | 139       | 6.67%   |
| MATE          | 116       | 5.57%   |
| i3            | 95        | 4.56%   |
| Openbox       | 54        | 2.59%   |
| Cinnamon      | 26        | 1.25%   |
| AwesomeWM     | 22        | 1.06%   |
| LXQt          | 20        | 0.96%   |
| Fluxbox       | 18        | 0.86%   |
| LXDE          | 15        | 0.72%   |
| Enlightenment | 15        | 0.72%   |
| Lumina        | 10        | 0.48%   |
| dwm           | 7         | 0.34%   |
| GNUstep       | 5         | 0.24%   |
| xfwm          | 4         | 0.19%   |
| CDE           | 4         | 0.19%   |
| spectrwm      | 3         | 0.14%   |
| Picom         | 3         | 0.14%   |
| X-Cinnamon    | 2         | 0.1%    |
| Window Maker  | 2         | 0.1%    |
| IceWM         | 2         | 0.1%    |
| helloDesktop  | 2         | 0.1%    |
| Compton       | 2         | 0.1%    |
| xinitrc       | 1         | 0.05%   |
| Xfwm4         | 1         | 0.05%   |
| sway          | 1         | 0.05%   |
| StumpWM       | 1         | 0.05%   |
| plasma        | 1         | 0.05%   |
| KWin          | 1         | 0.05%   |
| KDE           | 1         | 0.05%   |
| ctwm          | 1         | 0.05%   |
| bspwm         | 1         | 0.05%   |
| awesome       | 1         | 0.05%   |
| akonadi_newm  | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1245      | 60.97%  |
| Console | 763       | 37.37%  |
| Wayland | 34        | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1180      | 57.06%  |
| SDDM    | 309       | 14.94%  |
| SLiM    | 224       | 10.83%  |
| XDM     | 138       | 6.67%   |
| LightDM | 112       | 5.42%   |
| GDM     | 91        | 4.4%    |
| Ly      | 11        | 0.53%   |
| PCDM    | 2         | 0.1%    |
| WDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| C                | 800       | 37.95%  |
| Unknown          | 620       | 29.41%  |
| en_US            | 299       | 14.18%  |
| ru_RU            | 112       | 5.31%   |
| de_DE            | 41        | 1.94%   |
| fr_FR            | 32        | 1.52%   |
| en_GB            | 32        | 1.52%   |
| zh_CN            | 15        | 0.71%   |
| en_CA            | 14        | 0.66%   |
| pt_BR            | 11        | 0.52%   |
| uk_UA            | 9         | 0.43%   |
| ja_JP            | 9         | 0.43%   |
| es_ES            | 8         | 0.38%   |
| pl_PL            | 7         | 0.33%   |
| nb_NO            | 7         | 0.33%   |
| en_AU            | 7         | 0.33%   |
| en_IE            | 6         | 0.28%   |
| it_IT            | 5         | 0.24%   |
| ru_RU.KOI8-R     | 4         | 0.19%   |
| en_US.ISO8859-1  | 4         | 0.19%   |
| en_NZ            | 4         | 0.19%   |
| el_GR            | 4         | 0.19%   |
| fi_FI            | 3         | 0.14%   |
| es_AR            | 3         | 0.14%   |
| en_US.US-ASCII   | 3         | 0.14%   |
| de_DE.ISO8859-1  | 3         | 0.14%   |
| de_CH            | 3         | 0.14%   |
| cs_CZ            | 3         | 0.14%   |
| zh_TW            | 2         | 0.09%   |
| sv_SE            | 2         | 0.09%   |
| pt_PT            | 2         | 0.09%   |
| nl_NL            | 2         | 0.09%   |
| it_IT.ISO8859-15 | 2         | 0.09%   |
| en_SG            | 2         | 0.09%   |
| en_GB.US-ASCII   | 2         | 0.09%   |
| zh_CN.GB2312     | 1         | 0.05%   |
| sv_SE.US-ASCII   | 1         | 0.05%   |
| sl_SI            | 1         | 0.05%   |
| POSIX            | 1         | 0.05%   |
| no_NO.ISO8859-15 | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1232      | 60.78%  |
| BIOS | 795       | 39.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 1269      | 62.64%  |
| Ufs     | 754       | 37.22%  |
| Xfs     | 1         | 0.05%   |
| Nfs     | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1766      | 87.51%  |
| MBR     | 235       | 11.65%  |
| BSD     | 10        | 0.5%    |
| Unknown | 7         | 0.35%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 322       | 16.05%  |
| Dell                    | 297       | 14.81%  |
| ASUSTek Computer        | 257       | 12.81%  |
| Hewlett-Packard         | 169       | 8.42%   |
| Gigabyte Technology     | 118       | 5.88%   |
| ASRock                  | 93        | 4.64%   |
| MSI                     | 84        | 4.19%   |
| Unknown                 | 81        | 4.04%   |
| Supermicro              | 80        | 3.99%   |
| Intel                   | 77        | 3.84%   |
| Acer                    | 59        | 2.94%   |
| Apple                   | 39        | 1.94%   |
| Fujitsu                 | 27        | 1.35%   |
| Toshiba                 | 20        | 1%      |
| IBM                     | 18        | 0.9%    |
| Raspberry Pi Foundation | 15        | 0.75%   |
| Samsung Electronics     | 14        | 0.7%    |
| PC Engines              | 14        | 0.7%    |
| System76                | 13        | 0.65%   |
| ASRockRack              | 13        | 0.65%   |
| HUAWEI                  | 11        | 0.55%   |
| Google                  | 10        | 0.5%    |
| Sony                    | 9         | 0.45%   |
| HPE                     | 7         | 0.35%   |
| TUXEDO                  | 6         | 0.3%    |
| Sun Microsystems        | 6         | 0.3%    |
| Shuttle                 | 6         | 0.3%    |
| Notebook                | 5         | 0.25%   |
| Gateway                 | 5         | 0.25%   |
| Framework               | 5         | 0.25%   |
| Deciso                  | 5         | 0.25%   |
| Cisco Systems           | 5         | 0.25%   |
| Biostar                 | 5         | 0.25%   |
| Beckhoff Automation     | 5         | 0.25%   |
| AMI                     | 5         | 0.25%   |
| Wistron                 | 4         | 0.2%    |
| Pegatron                | 4         | 0.2%    |
| Panasonic               | 4         | 0.2%    |
| Foxconn                 | 4         | 0.2%    |
| BESSTAR Tech            | 4         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 84        | 4.19%   |
| ASUS All Series                  | 27        | 1.35%   |
| Supermicro Super Server          | 21        | 1.05%   |
| RPi Raspberry Pi                 | 14        | 0.7%    |
| Dell OEM-R 720xd                 | 13        | 0.65%   |
| HP ProLiant MicroServer Gen8     | 10        | 0.5%    |
| Intel Nobilis                    | 9         | 0.45%   |
| PC Engines APU2                  | 7         | 0.35%   |
| Dell PowerEdge R710              | 7         | 0.35%   |
| HP ProLiant MicroServer          | 6         | 0.3%    |
| ASUS TUF GAMING X570-PLUS        | 6         | 0.3%    |
| MSI MS-7C02                      | 5         | 0.25%   |
| Framework Laptop                 | 5         | 0.25%   |
| Dell OptiPlex 9020               | 5         | 0.25%   |
| Dell Latitude E7240              | 5         | 0.25%   |
| System76 Lemur Pro               | 4         | 0.2%    |
| Supermicro X9SCL/X9SCM           | 4         | 0.2%    |
| Sun Microsystems Sun Fire X4150  | 4         | 0.2%    |
| HPE ProLiant MicroServer Gen10   | 4         | 0.2%    |
| HP Z620 Workstation              | 4         | 0.2%    |
| HP EliteBook 840 G3              | 4         | 0.2%    |
| Gigabyte X570 I AORUS PRO WIFI   | 4         | 0.2%    |
| Gigabyte B450M DS3H              | 4         | 0.2%    |
| Fujitsu D3401-H2 S26361-D3401-H2 | 4         | 0.2%    |
| Dell PowerEdge T30               | 4         | 0.2%    |
| Dell PowerEdge R720              | 4         | 0.2%    |
| Dell PowerEdge R610              | 4         | 0.2%    |
| Dell OptiPlex 7040               | 4         | 0.2%    |
| Dell OptiPlex 3010               | 4         | 0.2%    |
| Dell Latitude E6430              | 4         | 0.2%    |
| ASRock Q1900B-ITX                | 4         | 0.2%    |
| Wistron ProLiant ML110 G6        | 3         | 0.15%   |
| Supermicro X7SPA-HF              | 3         | 0.15%   |
| Supermicro X10SLL-F              | 3         | 0.15%   |
| PC Engines apu4                  | 3         | 0.15%   |
| PC Engines APU                   | 3         | 0.15%   |
| MSI MS-7C37                      | 3         | 0.15%   |
| MSI MS-7817                      | 3         | 0.15%   |
| MSI MS-7693                      | 3         | 0.15%   |
| MSI MS-7522                      | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 233       | 11.62%  |
| Unknown            | 84        | 4.19%   |
| Dell Latitude      | 71        | 3.54%   |
| Dell PowerEdge     | 52        | 2.59%   |
| Dell Inspiron      | 45        | 2.24%   |
| Dell OptiPlex      | 39        | 1.94%   |
| ASUS PRIME         | 37        | 1.84%   |
| HP ProLiant        | 34        | 1.69%   |
| Acer Aspire        | 32        | 1.6%    |
| Dell Precision     | 31        | 1.55%   |
| Lenovo IdeaPad     | 27        | 1.35%   |
| ASUS All           | 27        | 1.35%   |
| HP Compaq          | 22        | 1.1%    |
| Supermicro Super   | 21        | 1.05%   |
| ASUS ROG           | 21        | 1.05%   |
| ASUS TUF           | 20        | 1%      |
| Dell XPS           | 17        | 0.85%   |
| RPi Raspberry      | 14        | 0.7%    |
| HP ProBook         | 14        | 0.7%    |
| HP EliteBook       | 14        | 0.7%    |
| Toshiba Satellite  | 13        | 0.65%   |
| Lenovo ThinkCentre | 13        | 0.65%   |
| Dell Vostro        | 13        | 0.65%   |
| Dell OEM-R         | 13        | 0.65%   |
| IBM System         | 11        | 0.55%   |
| ASRock X570        | 10        | 0.5%    |
| Intel Nobilis      | 9         | 0.45%   |
| Gigabyte X570      | 9         | 0.45%   |
| HP Pavilion        | 8         | 0.4%    |
| HP ENVY            | 8         | 0.4%    |
| HP EliteDesk       | 8         | 0.4%    |
| ASUS ZenBook       | 8         | 0.4%    |
| ASRock X370        | 8         | 0.4%    |
| PC Engines APU2    | 7         | 0.35%   |
| HPE ProLiant       | 7         | 0.35%   |
| HP Laptop          | 7         | 0.35%   |
| Gigabyte B450M     | 7         | 0.35%   |
| Fujitsu PRIMERGY   | 7         | 0.35%   |
| Lenovo Legion      | 6         | 0.3%    |
| IBM ThinkPad       | 6         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 234       | 11.67%  |
| 2019    | 227       | 11.32%  |
| 2018    | 185       | 9.22%   |
| 2021    | 162       | 8.08%   |
| 2011    | 137       | 6.83%   |
| 2013    | 125       | 6.23%   |
| 2014    | 116       | 5.78%   |
| 2017    | 112       | 5.58%   |
| 2015    | 109       | 5.43%   |
| 2012    | 101       | 5.03%   |
| 2016    | 95        | 4.74%   |
| 2010    | 91        | 4.54%   |
| Unknown | 74        | 3.69%   |
| 2009    | 60        | 2.99%   |
| 2008    | 57        | 2.84%   |
| 2022    | 52        | 2.59%   |
| 2007    | 31        | 1.55%   |
| 2006    | 16        | 0.8%    |
| 2005    | 6         | 0.3%    |
| 2004    | 6         | 0.3%    |
| 2003    | 5         | 0.25%   |
| 2002    | 4         | 0.2%    |
| 2001    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 880       | 43.87%  |
| Notebook       | 809       | 40.33%  |
| Server         | 171       | 8.52%   |
| Mini pc        | 57        | 2.84%   |
| System on chip | 47        | 2.34%   |
| Convertible    | 24        | 1.2%    |
| All in one     | 18        | 0.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1965      | 97.96%  |
| Yes  | 41        | 2.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 538       | 26.48%  |
| 16.01-24.0      | 497       | 24.46%  |
| 32.01-64.0      | 289       | 14.22%  |
| 4.01-8.0        | 267       | 13.14%  |
| 64.01-256.0     | 184       | 9.06%   |
| 2.01-3.0        | 79        | 3.89%   |
| 0.51-1.0        | 46        | 2.26%   |
| 24.01-32.0      | 45        | 2.21%   |
| 3.01-4.0        | 41        | 2.02%   |
| 1.01-2.0        | 17        | 0.84%   |
| 0.01-0.5        | 15        | 0.74%   |
| More than 256.0 | 13        | 0.64%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 0.01-0.5        | 697       | 33.45%  |
| 0.51-1.0        | 616       | 29.56%  |
| 1.01-2.0        | 357       | 17.13%  |
| 2.01-3.0        | 93        | 4.46%   |
| 4.01-8.0        | 80        | 3.84%   |
| 3.01-4.0        | 68        | 3.26%   |
| 8.01-16.0       | 50        | 2.4%    |
| 24.01-32.0      | 31        | 1.49%   |
| 0               | 27        | 1.3%    |
| 32.01-64.0      | 22        | 1.06%   |
| 16.01-24.0      | 22        | 1.06%   |
| 64.01-256.0     | 19        | 0.91%   |
| More than 256.0 | 1         | 0.05%   |
| Unknown         | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 972       | 46.75%  |
| 2      | 437       | 21.02%  |
| 3      | 181       | 8.71%   |
| 0      | 137       | 6.59%   |
| 4      | 122       | 5.87%   |
| 5      | 71        | 3.42%   |
| 6      | 50        | 2.41%   |
| 7      | 26        | 1.25%   |
| 8      | 18        | 0.87%   |
| 10     | 10        | 0.48%   |
| 14     | 9         | 0.43%   |
| 12     | 9         | 0.43%   |
| 11     | 8         | 0.38%   |
| 9      | 7         | 0.34%   |
| 18     | 3         | 0.14%   |
| 25     | 2         | 0.1%    |
| 23     | 2         | 0.1%    |
| 17     | 2         | 0.1%    |
| 16     | 2         | 0.1%    |
| 15     | 2         | 0.1%    |
| 13     | 2         | 0.1%    |
| 63     | 1         | 0.05%   |
| 58     | 1         | 0.05%   |
| 40     | 1         | 0.05%   |
| 28     | 1         | 0.05%   |
| 24     | 1         | 0.05%   |
| 21     | 1         | 0.05%   |
| 19     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1436      | 71.02%  |
| Yes       | 586       | 28.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1776      | 88.53%  |
| No        | 230       | 11.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1086      | 53.76%  |
| No        | 934       | 46.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1257      | 62.01%  |
| Yes       | 770       | 37.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 466       | 23.07%  |
| Russia      | 216       | 10.69%  |
| Germany     | 199       | 9.85%   |
| France      | 102       | 5.05%   |
| Canada      | 75        | 3.71%   |
| UK          | 74        | 3.66%   |
| Poland      | 66        | 3.27%   |
| Ukraine     | 47        | 2.33%   |
| Netherlands | 44        | 2.18%   |
| Brazil      | 44        | 2.18%   |
| Czechia     | 41        | 2.03%   |
| China       | 41        | 2.03%   |
| Australia   | 40        | 1.98%   |
| Japan       | 38        | 1.88%   |
| Switzerland | 35        | 1.73%   |
| Austria     | 33        | 1.63%   |
| Italy       | 30        | 1.49%   |
| Spain       | 28        | 1.39%   |
| Norway      | 26        | 1.29%   |
| Sweden      | 25        | 1.24%   |
| India       | 22        | 1.09%   |
| Finland     | 22        | 1.09%   |
| Indonesia   | 19        | 0.94%   |
| Romania     | 16        | 0.79%   |
| Thailand    | 15        | 0.74%   |
| Ireland     | 15        | 0.74%   |
| Greece      | 15        | 0.74%   |
| Portugal    | 13        | 0.64%   |
| Denmark     | 13        | 0.64%   |
| Belgium     | 13        | 0.64%   |
| Argentina   | 13        | 0.64%   |
| New Zealand | 12        | 0.59%   |
| Bulgaria    | 11        | 0.54%   |
| Hungary     | 10        | 0.5%    |
| Taiwan      | 8         | 0.4%    |
| Slovenia    | 8         | 0.4%    |
| Croatia     | 8         | 0.4%    |
| Singapore   | 7         | 0.35%   |
| Mexico      | 7         | 0.35%   |
| Serbia      | 6         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 81        | 3.77%   |
| Vienna        | 26        | 1.21%   |
| Brooklyn      | 26        | 1.21%   |
| Berlin        | 24        | 1.12%   |
| Kyiv          | 23        | 1.07%   |
| St Petersburg | 19        | 0.88%   |
| Paris         | 18        | 0.84%   |
| Gdynia        | 18        | 0.84%   |
| Warsaw        | 15        | 0.7%    |
| London        | 15        | 0.7%    |
| Grand Rapids  | 15        | 0.7%    |
| Chicago       | 15        | 0.7%    |
| Amsterdam     | 15        | 0.7%    |
| Sydney        | 14        | 0.65%   |
| Helsinki      | 14        | 0.65%   |
| Zurich        | 13        | 0.6%    |
| Prague        | 13        | 0.6%    |
| Yekaterinburg | 12        | 0.56%   |
| Tuklaty       | 12        | 0.56%   |
| Ludwigsburg   | 12        | 0.56%   |
| Krasnodar     | 11        | 0.51%   |
| Portland      | 10        | 0.47%   |
| Jakarta       | 10        | 0.47%   |
| Seattle       | 9         | 0.42%   |
| Oslo          | 9         | 0.42%   |
| Lexington     | 9         | 0.42%   |
| Dublin        | 9         | 0.42%   |
| Athens        | 9         | 0.42%   |
| Sofia         | 8         | 0.37%   |
| Shenzhen      | 8         | 0.37%   |
| Rochester     | 8         | 0.37%   |
| Poway         | 8         | 0.37%   |
| Novosibirsk   | 8         | 0.37%   |
| Montreal      | 8         | 0.37%   |
| Madrid        | 8         | 0.37%   |
| Singapore     | 7         | 0.33%   |
| Ozersk        | 7         | 0.33%   |
| Munich        | 7         | 0.33%   |
| Falkenstein   | 7         | 0.33%   |
| Bucharest     | 7         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 572       | 1620   | 19.79%  |
| Samsung Electronics | 489       | 904    | 16.92%  |
| Seagate             | 416       | 1078   | 14.39%  |
| Toshiba             | 189       | 407    | 6.54%   |
| Kingston            | 157       | 209    | 5.43%   |
| Crucial             | 155       | 230    | 5.36%   |
| Intel               | 118       | 221    | 4.08%   |
| Hitachi             | 93        | 258    | 3.22%   |
| SanDisk             | 83        | 115    | 2.87%   |
| HGST                | 81        | 275    | 2.8%    |
| A-DATA Technology   | 52        | 67     | 1.8%    |
| SK hynix            | 45        | 51     | 1.56%   |
| Transcend           | 40        | 52     | 1.38%   |
| Micron Technology   | 37        | 63     | 1.28%   |
| Hewlett-Packard     | 27        | 160    | 0.93%   |
| Phison              | 20        | 29     | 0.69%   |
| PNY                 | 16        | 27     | 0.55%   |
| OCZ                 | 16        | 20     | 0.55%   |
| SPCC                | 15        | 34     | 0.52%   |
| KIOXIA              | 14        | 14     | 0.48%   |
| Corsair             | 14        | 30     | 0.48%   |
| Apple               | 13        | 14     | 0.45%   |
| Silicon Motion      | 10        | 11     | 0.35%   |
| KingSpec            | 10        | 15     | 0.35%   |
| GOODRAM             | 10        | 20     | 0.35%   |
| Fujitsu             | 10        | 15     | 0.35%   |
| LITEON              | 9         | 13     | 0.31%   |
| OWC                 | 8         | 12     | 0.28%   |
| Maxtor              | 8         | 12     | 0.28%   |
| Plextor             | 7         | 13     | 0.24%   |
| Patriot             | 7         | 10     | 0.24%   |
| Gigabyte Technology | 7         | 9      | 0.24%   |
| China               | 7         | 8      | 0.24%   |
| Apacer              | 7         | 7      | 0.24%   |
| Mushkin             | 6         | 7      | 0.21%   |
| Intenso             | 6         | 7      | 0.21%   |
| Lenovo              | 5         | 5      | 0.17%   |
| Hikvision           | 5         | 5      | 0.17%   |
| LITEONIT            | 4         | 4      | 0.14%   |
| KIOXIA-EXCERIA      | 4         | 7      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 39        | 1.14%   |
| Samsung SSD 850 EVO 250GB          | 28        | 0.82%   |
| WDC WD40EFRX-68N32N0 4TB           | 22        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB     | 22        | 0.64%   |
| WDC WD30EFRX-68EUZN0 3TB           | 21        | 0.61%   |
| Kingston SA400S37120G 120GB        | 21        | 0.61%   |
| Samsung SSD 860 EVO 500GB          | 20        | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB           | 19        | 0.55%   |
| Samsung SSD 850 EVO 500GB          | 19        | 0.55%   |
| WDC WD800JD-75MSA3 80GB            | 17        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 17        | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB       | 17        | 0.5%    |
| Toshiba DT01ACA100 1TB             | 16        | 0.47%   |
| Seagate ST4000DM000-1F2168 4TB     | 16        | 0.47%   |
| Samsung SSD 860 EVO 250GB          | 16        | 0.47%   |
| Crucial CT500MX500SSD1 500GB       | 16        | 0.47%   |
| Crucial CT250MX500SSD1 250GB       | 16        | 0.47%   |
| Toshiba MQ01ABD100 1TB             | 15        | 0.44%   |
| Seagate ST1000LM035-1RK172 1TB     | 14        | 0.41%   |
| HGST HTS721010A9E630 1TB           | 14        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB     | 13        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB     | 13        | 0.38%   |
| Samsung SSD 860 EVO 1TB            | 13        | 0.38%   |
| Crucial CT240BX500SSD1 240GB       | 13        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB        | 13        | 0.38%   |
| WDC WD20EFRX-68EUZN0 2TB           | 12        | 0.35%   |
| Toshiba MQ01ABF050 500GB           | 12        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB     | 12        | 0.35%   |
| Seagate ST500DM002-1BD142 500GB    | 11        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB     | 11        | 0.32%   |
| Seagate ST1000LM048-2E7172 1TB     | 11        | 0.32%   |
| WDC WD40EFRX-68WT0N0 4TB           | 10        | 0.29%   |
| Seagate ST8000DM004-2CX188 8TB     | 10        | 0.29%   |
| Seagate ST4000VN008-2DR166 4TB     | 10        | 0.29%   |
| Seagate ST3500418AS 500GB          | 10        | 0.29%   |
| Samsung SSD 970 EVO 500GB          | 10        | 0.29%   |
| Samsung SSD 970 EVO 1TB            | 10        | 0.29%   |
| Samsung SSD 870 EVO 1TB            | 10        | 0.29%   |
| Samsung SSD 850 EVO 1TB            | 10        | 0.29%   |
| Kingston SV300S37A120G 120GB       | 10        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| WDC                  | 457       | 1398   | 35.18%  |
| Seagate              | 411       | 1067   | 31.64%  |
| Toshiba              | 155       | 357    | 11.93%  |
| Hitachi              | 92        | 254    | 7.08%   |
| HGST                 | 81        | 275    | 6.24%   |
| Samsung Electronics  | 46        | 73     | 3.54%   |
| Hewlett-Packard      | 15        | 136    | 1.15%   |
| Fujitsu              | 10        | 15     | 0.77%   |
| Maxtor               | 8         | 12     | 0.62%   |
| Apple                | 4         | 5      | 0.31%   |
| LSI                  | 3         | 6      | 0.23%   |
| IBM/Hitachi          | 2         | 2      | 0.15%   |
| HPE                  | 2         | 12     | 0.15%   |
| Dell                 | 2         | 5      | 0.15%   |
| Areca                | 2         | 3      | 0.15%   |
| Adaptec              | 2         | 12     | 0.15%   |
| WD MediaMax          | 1         | 2      | 0.08%   |
| SYNOLOGY             | 1         | 1      | 0.08%   |
| QUANTUM              | 1         | 2      | 0.08%   |
| NETAPP               | 1         | 2      | 0.08%   |
| MaxDigital           | 1         | 1      | 0.08%   |
| IBM                  | 1         | 1      | 0.08%   |
| ExcelStor Technology | 1         | 4      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 273       | 525    | 24.27%  |
| Kingston            | 136       | 178    | 12.09%  |
| Crucial             | 129       | 192    | 11.47%  |
| Intel               | 84        | 175    | 7.47%   |
| SanDisk             | 83        | 115    | 7.38%   |
| WDC                 | 64        | 108    | 5.69%   |
| A-DATA Technology   | 38        | 50     | 3.38%   |
| Transcend           | 35        | 45     | 3.11%   |
| Micron Technology   | 24        | 41     | 2.13%   |
| Toshiba             | 20        | 21     | 1.78%   |
| SK hynix            | 17        | 20     | 1.51%   |
| OCZ                 | 16        | 20     | 1.42%   |
| Hewlett-Packard     | 13        | 18     | 1.16%   |
| PNY                 | 11        | 21     | 0.98%   |
| SPCC                | 10        | 27     | 0.89%   |
| KingSpec            | 10        | 15     | 0.89%   |
| Corsair             | 10        | 13     | 0.89%   |
| Apple               | 9         | 9      | 0.8%    |
| OWC                 | 8         | 12     | 0.71%   |
| LITEON              | 8         | 12     | 0.71%   |
| Patriot             | 7         | 10     | 0.62%   |
| GOODRAM             | 7         | 16     | 0.62%   |
| China               | 7         | 8      | 0.62%   |
| Apacer              | 7         | 7      | 0.62%   |
| Intenso             | 6         | 7      | 0.53%   |
| Plextor             | 5         | 8      | 0.44%   |
| Gigabyte Technology | 5         | 6      | 0.44%   |
| Seagate             | 4         | 6      | 0.36%   |
| Phison              | 4         | 5      | 0.36%   |
| Mushkin             | 4         | 4      | 0.36%   |
| LITEONIT            | 4         | 4      | 0.36%   |
| Hoodisk             | 4         | 6      | 0.36%   |
| Zheino              | 3         | 4      | 0.27%   |
| Verbatim            | 3         | 3      | 0.27%   |
| Vaseky              | 3         | 3      | 0.27%   |
| Team                | 3         | 5      | 0.27%   |
| Supermicro          | 3         | 3      | 0.27%   |
| Lexar               | 3         | 9      | 0.27%   |
| Hikvision           | 3         | 3      | 0.27%   |
| Emtec               | 3         | 3      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1009      | 3645   | 40.64%  |
| SSD  | 973       | 1798   | 39.19%  |
| NVMe | 501       | 778    | 20.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1597      | 5443   | 76.12%  |
| NVMe | 501       | 778    | 23.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1160      | 2225   | 51.79%  |
| 0.51-1.0   | 492       | 957    | 21.96%  |
| 1.01-2.0   | 221       | 577    | 9.87%   |
| 3.01-4.0   | 134       | 574    | 5.98%   |
| 4.01-10.0  | 122       | 671    | 5.45%   |
| 2.01-3.0   | 79        | 279    | 3.53%   |
| 10.01-20.0 | 29        | 154    | 1.29%   |
| 20.01-50.0 | 3         | 6      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 636       | 30.56%  |
| 251-500        | 467       | 22.44%  |
| 501-1000       | 285       | 13.7%   |
| 51-100         | 226       | 10.86%  |
| 21-50          | 149       | 7.16%   |
| 1-20           | 113       | 5.43%   |
| 1001-2000      | 98        | 4.71%   |
| More than 3000 | 57        | 2.74%   |
| 2001-3000      | 27        | 1.3%    |
| Unknown        | 23        | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1481      | 71.1%   |
| 21-50          | 277       | 13.3%   |
| 51-100         | 109       | 5.23%   |
| 101-250        | 78        | 3.74%   |
| 251-500        | 41        | 1.97%   |
| 501-1000       | 32        | 1.54%   |
| Unknown        | 23        | 1.1%    |
| More than 3000 | 18        | 0.86%   |
| 1001-2000      | 12        | 0.58%   |
| 2001-3000      | 11        | 0.53%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB            | 6         | 18     | 1.38%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 6      | 1.38%   |
| Seagate ST3500413AS 500GB           | 6         | 9      | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 7      | 1.38%   |
| HGST HTS725050A7E630 500GB          | 6         | 14     | 1.38%   |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 12     | 1.15%   |
| Samsung Electronics SSD 870 EVO 1TB | 5         | 7      | 1.15%   |
| WDC WD40EFRX-68WT0N0 4TB            | 4         | 12     | 0.92%   |
| Seagate ST9500420AS 500GB           | 4         | 6      | 0.92%   |
| Samsung Electronics HD501LJ 500GB   | 4         | 6      | 0.92%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 0.69%   |
| Toshiba MQ01ABD100 1TB              | 3         | 3      | 0.69%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 6      | 0.69%   |
| Seagate ST380013AS 80GB             | 3         | 4      | 0.69%   |
| Seagate ST3500418AS 500GB           | 3         | 6      | 0.69%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 3      | 0.69%   |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 3      | 0.69%   |
| Samsung Electronics HD103UJ 1TB     | 3         | 6      | 0.69%   |
| Intel SSDSA2M080G2GC 80GB           | 3         | 3      | 0.69%   |
| HGST HTS721010A9E630 1TB            | 3         | 14     | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.46%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 2      | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 5      | 0.46%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 2         | 2      | 0.46%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 2      | 0.46%   |
| WDC WD2002FYPS-02W3B0 2TB           | 2         | 2      | 0.46%   |
| WDC WD2002FYPS-01U1B0 2TB           | 2         | 3      | 0.46%   |
| WDC WD2000FYYZ-01UL1B2 2TB          | 2         | 4      | 0.46%   |
| WDC WD2000FYYZ-01UL1B1 2TB          | 2         | 4      | 0.46%   |
| WDC WD15EADS-00P8B0 1.5TB           | 2         | 2      | 0.46%   |
| Toshiba MK3261GSYN 320GB            | 2         | 2      | 0.46%   |
| Toshiba MK2546GSX 250GB             | 2         | 2      | 0.46%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 0.46%   |
| Seagate ST9250827AS 250GB           | 2         | 3      | 0.46%   |
| Seagate ST9250315AS 250GB           | 2         | 2      | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.46%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 0.46%   |
| Seagate ST500DM002-1BC142 500GB     | 2         | 2      | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB      | 2         | 2      | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB      | 2         | 2      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 102       | 147    | 24.82%  |
| WDC                  | 94        | 180    | 22.87%  |
| Samsung Electronics  | 38        | 49     | 9.25%   |
| Hitachi              | 35        | 59     | 8.52%   |
| Toshiba              | 30        | 57     | 7.3%    |
| Intel                | 19        | 27     | 4.62%   |
| Kingston             | 14        | 15     | 3.41%   |
| HGST                 | 14        | 35     | 3.41%   |
| Crucial              | 10        | 16     | 2.43%   |
| SanDisk              | 7         | 9      | 1.7%    |
| A-DATA Technology    | 7         | 9      | 1.7%    |
| Micron Technology    | 6         | 11     | 1.46%   |
| Maxtor               | 5         | 9      | 1.22%   |
| SK hynix             | 4         | 6      | 0.97%   |
| Hewlett-Packard      | 4         | 7      | 0.97%   |
| OCZ                  | 3         | 4      | 0.73%   |
| Fujitsu              | 2         | 5      | 0.49%   |
| Corsair              | 2         | 4      | 0.49%   |
| Apple                | 2         | 2      | 0.49%   |
| Transcend            | 1         | 1      | 0.24%   |
| SSSTC                | 1         | 1      | 0.24%   |
| SPCC                 | 1         | 1      | 0.24%   |
| SMI                  | 1         | 1      | 0.24%   |
| Plextor              | 1         | 1      | 0.24%   |
| Phison               | 1         | 1      | 0.24%   |
| LITEON               | 1         | 1      | 0.24%   |
| Lexar                | 1         | 1      | 0.24%   |
| IBM/Hitachi          | 1         | 1      | 0.24%   |
| GK                   | 1         | 1      | 0.24%   |
| ExcelStor Technology | 1         | 2      | 0.24%   |
| Apacer               | 1         | 1      | 0.24%   |
| AMD                  | 1         | 2      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 101       | 146    | 33.33%  |
| WDC                  | 91        | 177    | 30.03%  |
| Hitachi              | 35        | 59     | 11.55%  |
| Toshiba              | 29        | 56     | 9.57%   |
| Samsung Electronics  | 20        | 26     | 6.6%    |
| HGST                 | 14        | 35     | 4.62%   |
| Maxtor               | 5         | 9      | 1.65%   |
| Hewlett-Packard      | 3         | 6      | 0.99%   |
| Fujitsu              | 2         | 5      | 0.66%   |
| IBM/Hitachi          | 1         | 1      | 0.33%   |
| ExcelStor Technology | 1         | 2      | 0.33%   |
| Apple                | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 282       | 523    | 72.68%  |
| SSD  | 102       | 139    | 26.29%  |
| NVMe | 4         | 4      | 1.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 14.29%  |
| Toshiba MG05ACA800E 8TB           | 1         | 1      | 14.29%  |
| SanDisk pSSD 16GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics HM250JI 250GB | 1         | 1      | 14.29%  |
| Maxtor 6E040L0 41GB               | 1         | 1      | 14.29%  |
| Hitachi HUS724040ALE641 4TB       | 1         | 14     | 14.29%  |
| Crucial M4-CT256M4SSD1 256GB      | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Maxtor              | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 14     | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1691      | 5307   | 79.28%  |
| Malfunc  | 373       | 666    | 17.49%  |
| Detected | 62        | 228    | 2.91%   |
| Failed   | 7         | 20     | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1346      | 51.28%  |
| AMD                              | 358       | 13.64%  |
| Samsung Electronics              | 216       | 8.23%   |
| Broadcom / LSI                   | 143       | 5.45%   |
| SanDisk                          | 83        | 3.16%   |
| ASMedia Technology               | 62        | 2.36%   |
| Marvell Technology Group         | 51        | 1.94%   |
| Silicon Motion                   | 33        | 1.26%   |
| Phison Electronics               | 31        | 1.18%   |
| SK hynix                         | 28        | 1.07%   |
| Nvidia                           | 27        | 1.03%   |
| Kingston Technology Company      | 24        | 0.91%   |
| JMicron Technology               | 23        | 0.88%   |
| Micron/Crucial Technology        | 21        | 0.8%    |
| Adaptec                          | 20        | 0.76%   |
| Toshiba                          | 19        | 0.72%   |
| Micron Technology                | 16        | 0.61%   |
| KIOXIA                           | 15        | 0.57%   |
| Hewlett-Packard                  | 15        | 0.57%   |
| ADATA Technology                 | 12        | 0.46%   |
| Silicon Image                    | 9         | 0.34%   |
| VIA Technologies                 | 7         | 0.27%   |
| Areca Technology                 | 7         | 0.27%   |
| Silicon Integrated Systems [SiS] | 6         | 0.23%   |
| Union Memory (Shenzhen)          | 5         | 0.19%   |
| Seagate Technology               | 5         | 0.19%   |
| Lite-On Technology               | 5         | 0.19%   |
| Chelsio Communications           | 5         | 0.19%   |
| 3ware                            | 5         | 0.19%   |
| Realtek Semiconductor            | 4         | 0.15%   |
| Transcend                        | 3         | 0.11%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| Lenovo                           | 3         | 0.11%   |
| Integrated Technology Express    | 3         | 0.11%   |
| Broadcom                         | 3         | 0.11%   |
| ULi Electronics                  | 2         | 0.08%   |
| Promise Technology               | 2         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.08%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 236       | 7.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 126       | 4.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 93        | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 89        | 2.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 73        | 2.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 69        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 67        | 2.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 66        | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 61        | 2%      |
| ASMedia ASM1062 Serial ATA Controller                                          | 57        | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 54        | 1.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 49        | 1.61%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 48        | 1.57%   |
| Unknown                                                                        | 45        | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                          | 39        | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 35        | 1.15%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 35        | 1.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 34        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 34        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 1.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 33        | 1.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 33        | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.05%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 31        | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 31        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 29        | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 28        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 28        | 0.92%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 28        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 27        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 27        | 0.88%   |
| Samsung NVMe SSD Controller 980                                                | 26        | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 26        | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 23        | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 22        | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 22        | 0.72%   |
| Phison E12 NVMe Controller                                                     | 21        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1473      | 56.2%   |
| NVMe | 530       | 20.22%  |
| IDE  | 318       | 12.13%  |
| RAID | 177       | 6.75%   |
| SAS  | 90        | 3.43%   |
| SCSI | 33        | 1.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 1508      | 74.95%  |
| AMD                | 416       | 20.68%  |
| ARM                | 67        | 3.33%   |
| Unknown            | 13        | 0.65%   |
| VIA                | 1         | 0.05%   |
| Sun                | 1         | 0.05%   |
| Rockchip           | 1         | 0.05%   |
| Research           | 1         | 0.05%   |
| Motorola           | 1         | 0.05%   |
| IBM                | 1         | 0.05%   |
| i                  | 1         | 0.05%   |
| Baikal Electronics | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Cortex-A72 r0p3                     | 24        | 1.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 21        | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 19        | 0.94%   |
| ARM Cortex-A53 r0p4                     | 19        | 0.94%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 18        | 0.89%   |
| Intel CPU Version                       | 16        | 0.79%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz     | 15        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 15        | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 14        | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 14        | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 13        | 0.64%   |
|                                         | 13        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 12        | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 11        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 11        | 0.54%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 11        | 0.54%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 11        | 0.54%   |
| AMD GX-412TC SOC                        | 11        | 0.54%   |
| AMD FX-8350 Eight-Core Processor        | 11        | 0.54%   |
| Intel Xeon                              | 10        | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 9         | 0.44%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 9         | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 0.44%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 9         | 0.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 9         | 0.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 0.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 9         | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 0.44%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 9         | 0.44%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 9         | 0.44%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 9         | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 8         | 0.4%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 8         | 0.4%    |
| Intel Core i7-3520M CPU @ 2.90GHz       | 8         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 394       | 19.54%  |
| Intel Core i7          | 352       | 17.46%  |
| Intel Xeon             | 234       | 11.61%  |
| Other                  | 110       | 5.46%   |
| Intel Core i3          | 91        | 4.51%   |
| AMD Ryzen 7            | 91        | 4.51%   |
| Intel Celeron          | 90        | 4.46%   |
| AMD Ryzen 5            | 70        | 3.47%   |
| Intel Core 2 Duo       | 68        | 3.37%   |
| ARM Cortex             | 61        | 3.03%   |
| Intel Atom             | 48        | 2.38%   |
| Intel Pentium          | 36        | 1.79%   |
| AMD Ryzen 9            | 30        | 1.49%   |
| AMD FX                 | 27        | 1.34%   |
| AMD Ryzen 3            | 23        | 1.14%   |
| AMD GX                 | 22        | 1.09%   |
| Intel Pentium 4        | 15        | 0.74%   |
| Intel Xeon Silver      | 14        | 0.69%   |
| Intel Core 2           | 13        | 0.64%   |
| AMD Ryzen 7 PRO        | 13        | 0.64%   |
| Intel Core 2 Quad      | 12        | 0.6%    |
| AMD Opteron            | 12        | 0.6%    |
| Intel Pentium M        | 11        | 0.55%   |
| AMD Ryzen 5 PRO        | 11        | 0.55%   |
| Intel Core i9          | 10        | 0.5%    |
| AMD Ryzen Threadripper | 9         | 0.45%   |
| AMD EPYC               | 9         | 0.45%   |
| Intel Pentium Silver   | 7         | 0.35%   |
| AMD Turion II Neo      | 7         | 0.35%   |
| AMD Athlon 64 X2       | 7         | 0.35%   |
| AMD A10                | 7         | 0.35%   |
| AMD Phenom II X6       | 6         | 0.3%    |
| AMD E                  | 6         | 0.3%    |
| AMD A8                 | 6         | 0.3%    |
| Intel Pentium Dual     | 5         | 0.25%   |
| AMD Phenom II X4       | 5         | 0.25%   |
| AMD Phenom             | 5         | 0.25%   |
| AMD Athlon             | 5         | 0.25%   |
| AMD A4                 | 5         | 0.25%   |
| Intel Pentium Gold     | 4         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 646       | 32.04%  |
| 2       | 563       | 27.93%  |
| Unknown | 197       | 9.77%   |
| 8       | 152       | 7.54%   |
| 16      | 127       | 6.3%    |
| 6       | 123       | 6.1%    |
| 12      | 78        | 3.87%   |
| 1       | 53        | 2.63%   |
| 24      | 28        | 1.39%   |
| 32      | 14        | 0.69%   |
| 10      | 12        | 0.6%    |
| 20      | 11        | 0.55%   |
| 64      | 3         | 0.15%   |
| 48      | 2         | 0.1%    |
| 14      | 2         | 0.1%    |
| 3       | 2         | 0.1%    |
| 128     | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 11      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1810      | 89.96%  |
| 2       | 125       | 6.21%   |
| Unknown | 76        | 3.78%   |
| 4       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1011      | 50.22%  |
| 1       | 778       | 38.65%  |
| Unknown | 224       | 11.13%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 288       | 14.3%   |
| Haswell         | 173       | 8.59%   |
| IvyBridge       | 169       | 8.39%   |
| SandyBridge     | 153       | 7.6%    |
| Unknown         | 135       | 6.7%    |
| Skylake         | 129       | 6.41%   |
| Zen 2           | 95        | 4.72%   |
| Broadwell       | 78        | 3.87%   |
| Penryn          | 75        | 3.72%   |
| Westmere        | 70        | 3.48%   |
| Core            | 64        | 3.18%   |
| Zen+            | 58        | 2.88%   |
| Silvermont      | 50        | 2.48%   |
| Zen             | 47        | 2.33%   |
| Bonnell         | 46        | 2.28%   |
| CometLake       | 45        | 2.23%   |
| Zen 3           | 44        | 2.18%   |
| K10             | 34        | 1.69%   |
| Piledriver      | 33        | 1.64%   |
| Nehalem         | 30        | 1.49%   |
| TigerLake       | 27        | 1.34%   |
| Puma            | 24        | 1.19%   |
| NetBurst        | 23        | 1.14%   |
| Goldmont plus   | 19        | 0.94%   |
| P6              | 17        | 0.84%   |
| Excavator       | 15        | 0.74%   |
| K8 Hammer       | 14        | 0.7%    |
| Goldmont        | 14        | 0.7%    |
| Bobcat          | 14        | 0.7%    |
| Jaguar          | 11        | 0.55%   |
| IceLake         | 8         | 0.4%    |
| Bulldozer       | 4         | 0.2%    |
| Steamroller     | 3         | 0.15%   |
| K8 & K10 hybrid | 2         | 0.1%    |
| Geode           | 2         | 0.1%    |
| K10 Llano       | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1012      | 47.76%  |
| Nvidia                                       | 476       | 22.46%  |
| AMD                                          | 415       | 19.58%  |
| Matrox Electronics Systems                   | 134       | 6.32%   |
| ASPEED Technology                            | 71        | 3.35%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.14%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.09%   |
| VIA Technologies                             | 2         | 0.09%   |
| S3 Graphics                                  | 2         | 0.09%   |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.05%   |
| Huawei Technologies                          | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 92        | 4.2%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 71        | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 3.06%   |
| Intel UHD Graphics 620                                                                   | 46        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 45        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 1.97%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 41        | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40        | 1.83%   |
| Intel HD Graphics 620                                                                    | 40        | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 1.69%   |
| Intel HD Graphics 530                                                                    | 35        | 1.6%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 34        | 1.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 34        | 1.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.51%   |
| AMD Renoir                                                                               | 33        | 1.51%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.42%   |
| Matrox Electronics Systems G200eR2                                                       | 29        | 1.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 1.19%   |
| Intel HD Graphics 630                                                                    | 26        | 1.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 1.19%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 25        | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25        | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 24        | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 23        | 1.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 0.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 20        | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 0.91%   |
| AMD ES1000                                                                               | 20        | 0.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 19        | 0.87%   |
| Matrox Electronics Systems MGA G200EH                                                    | 19        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 19        | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 17        | 0.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| 1 x Intel                                | 743       | 36.8%   |
| 1 x AMD                                  | 349       | 17.29%  |
| 1 x Nvidia                               | 307       | 15.21%  |
| Intel + Nvidia                           | 146       | 7.23%   |
| 1 x Matrox                               | 133       | 6.59%   |
| Other                                    | 105       | 5.2%    |
| 2 x Intel                                | 85        | 4.21%   |
| 1 x ASPEED                               | 64        | 3.17%   |
| Intel + AMD                              | 32        | 1.58%   |
| 2 x AMD                                  | 17        | 0.84%   |
| AMD + Nvidia                             | 12        | 0.59%   |
| 2 x Nvidia                               | 5         | 0.25%   |
| Nvidia + ASPEED                          | 5         | 0.25%   |
| 1 x SiS                                  | 3         | 0.15%   |
| 1 x XGI                                  | 2         | 0.1%    |
| 1 x VIA                                  | 2         | 0.1%    |
| 1 x S3 Graphics                          | 2         | 0.1%    |
| AMD + ASPEED                             | 2         | 0.1%    |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1         | 0.05%   |
| Nvidia + Huawei Technologies             | 1         | 0.05%   |
| Intel + Matrox                           | 1         | 0.05%   |
| Intel + ASPEED                           | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia                 | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1596      | 79.05%  |
| Proprietary | 307       | 15.21%  |
| Unknown     | 116       | 5.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1555      | 76.34%  |
| 1.01-2.0   | 133       | 6.53%   |
| 0.01-0.5   | 92        | 4.52%   |
| 0.51-1.0   | 83        | 4.07%   |
| 3.01-4.0   | 67        | 3.29%   |
| 7.01-8.0   | 54        | 2.65%   |
| 5.01-6.0   | 29        | 1.42%   |
| 2.01-3.0   | 12        | 0.59%   |
| 8.01-16.0  | 11        | 0.54%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 148       | 11.81%  |
| Samsung Electronics     | 141       | 11.25%  |
| LG Display              | 131       | 10.45%  |
| Dell                    | 105       | 8.38%   |
| BOE                     | 78        | 6.23%   |
| Chimei Innolux          | 76        | 6.07%   |
| Goldstar                | 61        | 4.87%   |
| Lenovo                  | 46        | 3.67%   |
| Hewlett-Packard         | 40        | 3.19%   |
| Acer                    | 40        | 3.19%   |
| AOC                     | 36        | 2.87%   |
| BenQ                    | 29        | 2.31%   |
| Philips                 | 28        | 2.23%   |
| Sharp                   | 25        | 2%      |
| Ancor Communications    | 25        | 2%      |
| Apple                   | 22        | 1.76%   |
| LG Electronics          | 17        | 1.36%   |
| Iiyama                  | 17        | 1.36%   |
| ViewSonic               | 15        | 1.2%    |
| Chi Mei Optoelectronics | 12        | 0.96%   |
| Sony                    | 11        | 0.88%   |
| InfoVision              | 10        | 0.8%    |
| Eizo                    | 10        | 0.8%    |
| Unknown                 | 9         | 0.72%   |
| NEC Computers           | 9         | 0.72%   |
| ASUSTek Computer        | 8         | 0.64%   |
| Sceptre Tech            | 7         | 0.56%   |
| PANDA                   | 7         | 0.56%   |
| LGD                     | 7         | 0.56%   |
| Toshiba                 | 6         | 0.48%   |
| Panasonic               | 5         | 0.4%    |
| LG Philips              | 5         | 0.4%    |
| JDI                     | 5         | 0.4%    |
| Idek Iiyama             | 5         | 0.4%    |
| HannStar                | 4         | 0.32%   |
| CSO                     | 4         | 0.32%   |
| CPT                     | 4         | 0.32%   |
| Mi                      | 3         | 0.24%   |
| Fujitsu Siemens         | 3         | 0.24%   |
| Vizio                   | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 10        | 0.77%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 6         | 0.46%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 5         | 0.38%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch           | 5         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 5         | 0.38%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch        | 5         | 0.38%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch | 4         | 0.31%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 4         | 0.31%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch         | 4         | 0.31%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch          | 4         | 0.31%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 4         | 0.31%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 4         | 0.31%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 4         | 0.31%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch              | 4         | 0.31%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 4         | 0.31%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 4         | 0.31%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 4         | 0.31%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch     | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch     | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch        | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch       | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 4         | 0.31%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                    | 4         | 0.31%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch          | 3         | 0.23%   |
| Sharp LCD Monitor SHP1449 1920x1080 290x170mm 13.2-inch              | 3         | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch    | 3         | 0.23%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch    | 3         | 0.23%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch              | 3         | 0.23%   |
| Philips LCD Monitor PHL08C3 1920x1080 600x340mm 27.2-inch            | 3         | 0.23%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch         | 3         | 0.23%   |
| LGD LCD Monitor 1920x1080                                            | 3         | 0.23%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch         | 3         | 0.23%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch          | 3         | 0.23%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch          | 3         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 521       | 42.46%  |
| 1366x768 (WXGA)    | 182       | 14.83%  |
| 3840x2160 (4K)     | 82        | 6.68%   |
| 2560x1440 (QHD)    | 72        | 5.87%   |
| 1600x900 (HD+)     | 56        | 4.56%   |
| 1920x1200 (WUXGA)  | 51        | 4.16%   |
| 1280x1024 (SXGA)   | 44        | 3.59%   |
| 1280x800 (WXGA)    | 33        | 2.69%   |
| 1680x1050 (WSXGA+) | 24        | 1.96%   |
| 1440x900 (WXGA+)   | 20        | 1.63%   |
| Unknown            | 20        | 1.63%   |
| 2560x1080          | 15        | 1.22%   |
| 1024x600           | 15        | 1.22%   |
| 3440x1440          | 14        | 1.14%   |
| 2560x1600          | 6         | 0.49%   |
| 2256x1504          | 6         | 0.49%   |
| 1024x768 (XGA)     | 6         | 0.49%   |
| 3200x1800 (QHD+)   | 5         | 0.41%   |
| 1600x1200          | 5         | 0.41%   |
| 3840x1080          | 4         | 0.33%   |
| 1920x540           | 4         | 0.33%   |
| 3840x1200          | 3         | 0.24%   |
| 3000x2000          | 3         | 0.24%   |
| 2880x1620          | 3         | 0.24%   |
| 2160x1440          | 3         | 0.24%   |
| 5760x1080          | 2         | 0.16%   |
| 2880x1800          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 1360x768           | 2         | 0.16%   |
| 1280x720 (HD)      | 2         | 0.16%   |
| 7680x2160          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 5760x1256          | 1         | 0.08%   |
| 5760x1200          | 1         | 0.08%   |
| 4480x1080          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3640x1920          | 1         | 0.08%   |
| 3600x1080          | 1         | 0.08%   |
| 3520x1200          | 1         | 0.08%   |
| 3520x1080          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 236       | 18.91%  |
| 15      | 218       | 17.47%  |
| Unknown | 111       | 8.89%   |
| 24      | 105       | 8.41%   |
| 27      | 101       | 8.09%   |
| 21      | 69        | 5.53%   |
| 23      | 65        | 5.21%   |
| 12      | 62        | 4.97%   |
| 17      | 45        | 3.61%   |
| 19      | 37        | 2.96%   |
| 31      | 27        | 2.16%   |
| 14      | 26        | 2.08%   |
| 22      | 17        | 1.36%   |
| 11      | 17        | 1.36%   |
| 34      | 16        | 1.28%   |
| 18      | 15        | 1.2%    |
| 10      | 11        | 0.88%   |
| 20      | 10        | 0.8%    |
| 29      | 7         | 0.56%   |
| 64      | 4         | 0.32%   |
| 26      | 4         | 0.32%   |
| 9       | 4         | 0.32%   |
| 46      | 3         | 0.24%   |
| 42      | 3         | 0.24%   |
| 40      | 3         | 0.24%   |
| 32      | 3         | 0.24%   |
| 25      | 3         | 0.24%   |
| 16      | 3         | 0.24%   |
| 54      | 2         | 0.16%   |
| 52      | 2         | 0.16%   |
| 49      | 2         | 0.16%   |
| 48      | 2         | 0.16%   |
| 43      | 2         | 0.16%   |
| 41      | 2         | 0.16%   |
| 39      | 2         | 0.16%   |
| 57      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 35      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 411       | 33.39%  |
| 501-600     | 256       | 20.8%   |
| 201-300     | 182       | 14.78%  |
| 401-500     | 124       | 10.07%  |
| Unknown     | 111       | 9.02%   |
| 351-400     | 46        | 3.74%   |
| 601-700     | 45        | 3.66%   |
| 701-800     | 20        | 1.62%   |
| 1001-1500   | 19        | 1.54%   |
| 901-1000    | 7         | 0.57%   |
| 801-900     | 6         | 0.49%   |
| 101-200     | 3         | 0.24%   |
| 1-100       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 826       | 71.76%  |
| 16/10   | 117       | 10.17%  |
| Unknown | 101       | 8.77%   |
| 5/4     | 35        | 3.04%   |
| 21/9    | 25        | 2.17%   |
| 3/2     | 19        | 1.65%   |
| 4/3     | 18        | 1.56%   |
| 6/5     | 3         | 0.26%   |
| 32/9    | 2         | 0.17%   |
| 3.18    | 1         | 0.09%   |
| 11/10   | 1         | 0.09%   |
| 1.96    | 1         | 0.09%   |
| 1.00    | 1         | 0.09%   |
| 0.46    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 210       | 16.94%  |
| 201-250        | 209       | 16.85%  |
| 91-100         | 167       | 13.47%  |
| Unknown        | 111       | 8.95%   |
| 301-350        | 107       | 8.63%   |
| 61-70          | 63        | 5.08%   |
| 101-110        | 56        | 4.52%   |
| 151-200        | 52        | 4.19%   |
| 351-500        | 51        | 4.11%   |
| 251-300        | 43        | 3.47%   |
| 71-80          | 42        | 3.39%   |
| 141-150        | 30        | 2.42%   |
| 121-130        | 28        | 2.26%   |
| 501-1000       | 19        | 1.53%   |
| 51-60          | 16        | 1.29%   |
| 41-50          | 13        | 1.05%   |
| More than 1000 | 12        | 0.97%   |
| 1-40           | 4         | 0.32%   |
| 111-120        | 4         | 0.32%   |
| 131-140        | 3         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 365       | 30.07%  |
| 121-160       | 332       | 27.35%  |
| 101-120       | 264       | 21.75%  |
| Unknown       | 111       | 9.14%   |
| 161-240       | 103       | 8.48%   |
| More than 240 | 29        | 2.39%   |
| 1-50          | 10        | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 971       | 47.41%  |
| 0     | 906       | 44.24%  |
| 2     | 157       | 7.67%   |
| 3     | 13        | 0.63%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1194      | 43.54%  |
| Realtek Semiconductor             | 750       | 27.35%  |
| Broadcom                          | 237       | 8.64%   |
| Qualcomm Atheros                  | 230       | 8.39%   |
| Marvell Technology Group          | 34        | 1.24%   |
| Ralink Technology                 | 31        | 1.13%   |
| TP-Link                           | 24        | 0.88%   |
| Ralink                            | 15        | 0.55%   |
| Edimax Technology                 | 14        | 0.51%   |
| Mellanox Technologies             | 13        | 0.47%   |
| Xiaomi                            | 10        | 0.36%   |
| MediaTek                          | 10        | 0.36%   |
| VIA Technologies                  | 9         | 0.33%   |
| Nvidia                            | 9         | 0.33%   |
| D-Link System                     | 9         | 0.33%   |
| Hewlett-Packard                   | 8         | 0.29%   |
| Aquantia                          | 8         | 0.29%   |
| Sierra Wireless                   | 7         | 0.26%   |
| Samsung Electronics               | 7         | 0.26%   |
| Ericsson Business Mobile Networks | 6         | 0.22%   |
| IBM                               | 5         | 0.18%   |
| Google                            | 5         | 0.18%   |
| Chelsio Communications            | 5         | 0.18%   |
| American Megatrends               | 5         | 0.18%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.15%   |
| Qualcomm                          | 4         | 0.15%   |
| Huawei Technologies               | 4         | 0.15%   |
| Emulex                            | 4         | 0.15%   |
| Dell                              | 4         | 0.15%   |
| D-Link                            | 4         | 0.15%   |
| Arduino SA                        | 4         | 0.15%   |
| Apple                             | 4         | 0.15%   |
| 3Com                              | 4         | 0.15%   |
| NetGear                           | 3         | 0.11%   |
| IMC Networks                      | 3         | 0.11%   |
| Cisco Systems                     | 3         | 0.11%   |
| AMD                               | 3         | 0.11%   |
| Solarflare Communications         | 2         | 0.07%   |
| QLogic                            | 2         | 0.07%   |
| Lenovo                            | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 564       | 16.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 115       | 3.41%   |
| Intel I211 Gigabit Network Connection                                         | 84        | 2.49%   |
| Intel Wireless 8265 / 8275                                                    | 80        | 2.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 78        | 2.32%   |
| Intel I210 Gigabit Network Connection                                         | 72        | 2.14%   |
| Intel Wi-Fi 6 AX200                                                           | 69        | 2.05%   |
| Intel 82574L Gigabit Network Connection                                       | 61        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 57        | 1.69%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 53        | 1.57%   |
| Intel Wireless 8260                                                           | 48        | 1.42%   |
| Intel Wireless 7265                                                           | 48        | 1.42%   |
| Intel I350 Gigabit Network Connection                                         | 48        | 1.42%   |
| Intel Ethernet Connection I217-LM                                             | 39        | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 37        | 1.1%    |
| Intel Wireless 7260                                                           | 36        | 1.07%   |
| Intel Wireless-AC 9260                                                        | 34        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                         | 31        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 29        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 29        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                             | 28        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 27        | 0.8%    |
| Intel 82579V Gigabit Network Connection                                       | 25        | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                          | 24        | 0.71%   |
| Intel Ethernet Connection I219-LM                                             | 23        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 23        | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                         | 22        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 22        | 0.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 22        | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 21        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                         | 21        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 20        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 20        | 0.59%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 20        | 0.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 19        | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 19        | 0.56%   |
| Intel Ethernet Controller I225-V                                              | 19        | 0.56%   |
| Intel Ethernet Connection (2) I219-V                                          | 19        | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 18        | 0.53%   |
| Intel Wireless 3165                                                           | 18        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 671       | 55.87%  |
| Qualcomm Atheros                      | 187       | 15.57%  |
| Realtek Semiconductor                 | 133       | 11.07%  |
| Broadcom                              | 85        | 7.08%   |
| Ralink Technology                     | 31        | 2.58%   |
| TP-Link                               | 24        | 2%      |
| Ralink                                | 15        | 1.25%   |
| Edimax Technology                     | 14        | 1.17%   |
| MediaTek                              | 9         | 0.75%   |
| Sierra Wireless                       | 5         | 0.42%   |
| D-Link                                | 4         | 0.33%   |
| NetGear                               | 3         | 0.25%   |
| IMC Networks                          | 3         | 0.25%   |
| Dell                                  | 3         | 0.25%   |
| D-Link System                         | 3         | 0.25%   |
| Atheros                               | 2         | 0.17%   |
| ASUSTek Computer                      | 2         | 0.17%   |
| AboCom Systems                        | 2         | 0.17%   |
| Sagem                                 | 1         | 0.08%   |
| Qualcomm Atheros Communications       | 1         | 0.08%   |
| Linksys                               | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 80        | 6.62%   |
| Intel Wi-Fi 6 AX200                                                     | 69        | 5.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 57        | 4.71%   |
| Intel Wireless 8260                                                     | 48        | 3.97%   |
| Intel Wireless 7265                                                     | 48        | 3.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 37        | 3.06%   |
| Intel Wireless 7260                                                     | 36        | 2.98%   |
| Intel Wireless-AC 9260                                                  | 34        | 2.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 29        | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 22        | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 1.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 20        | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 20        | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 1.49%   |
| Intel Wireless 3165                                                     | 18        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 1.41%   |
| Ralink RT5370 Wireless Adapter                                          | 15        | 1.24%   |
| Intel Centrino Ultimate-N 6300                                          | 15        | 1.24%   |
| Intel Wireless 3160                                                     | 14        | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.08%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 12        | 0.99%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 11        | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 11        | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 11        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 0.83%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 10        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 0.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 864       | 44.51%  |
| Realtek Semiconductor             | 684       | 35.24%  |
| Broadcom                          | 176       | 9.07%   |
| Qualcomm Atheros                  | 68        | 3.5%    |
| Marvell Technology Group          | 34        | 1.75%   |
| Xiaomi                            | 10        | 0.52%   |
| VIA Technologies                  | 9         | 0.46%   |
| Nvidia                            | 9         | 0.46%   |
| Aquantia                          | 8         | 0.41%   |
| Samsung Electronics               | 7         | 0.36%   |
| D-Link System                     | 6         | 0.31%   |
| IBM                               | 5         | 0.26%   |
| Chelsio Communications            | 5         | 0.26%   |
| American Megatrends               | 5         | 0.26%   |
| Qualcomm                          | 4         | 0.21%   |
| Google                            | 4         | 0.21%   |
| Emulex                            | 4         | 0.21%   |
| 3Com                              | 4         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.15%   |
| Cisco Systems                     | 3         | 0.15%   |
| Apple                             | 3         | 0.15%   |
| AMD                               | 3         | 0.15%   |
| Solarflare Communications         | 2         | 0.1%    |
| QLogic                            | 2         | 0.1%    |
| Lenovo                            | 2         | 0.1%    |
| JMicron Technology                | 2         | 0.1%    |
| ADMtek                            | 2         | 0.1%    |
| U.S. Robotics                     | 1         | 0.05%   |
| Tehuti Networks                   | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |
| Realtek                           | 1         | 0.05%   |
| OPPO Electronics                  | 1         | 0.05%   |
| National Semiconductor            | 1         | 0.05%   |
| MYRICOM                           | 1         | 0.05%   |
| Insyde Software                   | 1         | 0.05%   |
| Huawei Technologies               | 1         | 0.05%   |
| HMD Global                        | 1         | 0.05%   |
| Davicom Semiconductor             | 1         | 0.05%   |
| Amazon.com                        | 1         | 0.05%   |
| Accton Technology                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 564       | 27.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 115       | 5.53%   |
| Intel I211 Gigabit Network Connection                                         | 84        | 4.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 78        | 3.75%   |
| Intel I210 Gigabit Network Connection                                         | 72        | 3.46%   |
| Intel 82574L Gigabit Network Connection                                       | 61        | 2.93%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 53        | 2.55%   |
| Intel I350 Gigabit Network Connection                                         | 48        | 2.31%   |
| Intel Ethernet Connection I217-LM                                             | 39        | 1.88%   |
| Intel Ethernet Connection (2) I219-LM                                         | 31        | 1.49%   |
| Intel 82579V Gigabit Network Connection                                       | 25        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                             | 24        | 1.15%   |
| Intel Ethernet Connection (4) I219-V                                          | 24        | 1.15%   |
| Intel Ethernet Connection I219-LM                                             | 23        | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                                         | 22        | 1.06%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 22        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                                         | 21        | 1.01%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 20        | 0.96%   |
| Intel Ethernet Controller I225-V                                              | 19        | 0.91%   |
| Intel Ethernet Connection (2) I219-V                                          | 19        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                          | 17        | 0.82%   |
| Intel Ethernet Connection (7) I219-LM                                         | 15        | 0.72%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 14        | 0.67%   |
| Intel 82576 Gigabit Network Connection                                        | 14        | 0.67%   |
| Intel Ethernet Connection I218-LM                                             | 13        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 12        | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                          | 12        | 0.58%   |
| Intel 82577LM Gigabit Network Connection                                      | 12        | 0.58%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 11        | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 11        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 10        | 0.48%   |
| Intel Ethernet Controller X550                                                | 10        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 9         | 0.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 9         | 0.43%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 9         | 0.43%   |
| Intel Ethernet Connection I219-V                                              | 9         | 0.43%   |
| Intel Ethernet Connection (6) I219-V                                          | 9         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                             | 9         | 0.43%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 9         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 8         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1779      | 60.35%  |
| WiFi     | 1088      | 36.91%  |
| Unknown  | 42        | 1.42%   |
| Modem    | 39        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1610      | 67.99%  |
| WiFi     | 743       | 31.38%  |
| Unknown  | 10        | 0.42%   |
| Modem    | 5         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1048      | 51.8%   |
| 1     | 626       | 30.94%  |
| 4     | 107       | 5.29%   |
| 3     | 105       | 5.19%   |
| 0     | 81        | 4%      |
| 6     | 26        | 1.29%   |
| 5     | 17        | 0.84%   |
| 8     | 5         | 0.25%   |
| 7     | 5         | 0.25%   |
| 10    | 3         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1829      | 89.35%  |
| Yes  | 218       | 10.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 460       | 59.13%  |
| Broadcom                        | 52        | 6.68%   |
| Qualcomm Atheros Communications | 49        | 6.3%    |
| Realtek Semiconductor           | 41        | 5.27%   |
| Apple                           | 38        | 4.88%   |
| Cambridge Silicon Radio         | 27        | 3.47%   |
| IMC Networks                    | 21        | 2.7%    |
| Foxconn / Hon Hai               | 19        | 2.44%   |
| ASUSTek Computer                | 16        | 2.06%   |
| Lite-On Technology              | 14        | 1.8%    |
| Dell                            | 14        | 1.8%    |
| Hewlett-Packard                 | 10        | 1.29%   |
| Realtek                         | 6         | 0.77%   |
| MediaTek                        | 3         | 0.39%   |
| Alps Electric                   | 3         | 0.39%   |
| Toshiba                         | 1         | 0.13%   |
| Ralink                          | 1         | 0.13%   |
| Opticis                         | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| Creative Technology             | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 184       | 23.62%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 66        | 8.47%   |
| Intel AX200 Bluetooth                                       | 66        | 8.47%   |
| Intel AX201 Bluetooth                                       | 61        | 7.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 30        | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 27        | 3.47%   |
| Intel Wireless-AC 3168 Bluetooth                            | 22        | 2.82%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 20        | 2.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 17        | 2.18%   |
| Apple Bluetooth Host Controller                             | 17        | 2.18%   |
| Realtek  Bluetooth 4.2 Adapter                              | 14        | 1.8%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 13        | 1.67%   |
| Realtek  Bluetooth Adapter                                  | 11        | 1.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 11        | 1.41%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 10        | 1.28%   |
| Intel AX210 Bluetooth                                       | 9         | 1.16%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 8         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 7         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 7         | 0.9%    |
| Dell DW375 Bluetooth Module                                 | 7         | 0.9%    |
| Realtek Bluetooth Radio                                     | 6         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 6         | 0.77%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 6         | 0.77%   |
| Realtek Bluetooth Radio                                     | 5         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 5         | 0.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 5         | 0.64%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 0.64%   |
| Realtek  Bluetooth 4.0 Adapter                              | 4         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 4         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 0.51%   |
| IMC Networks Realtek Bluetooth Adapter                      | 4         | 0.51%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 4         | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                           | 4         | 0.51%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 3         | 0.39%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 0.39%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 0.39%   |
| Qualcomm Atheros Atheros AR9462 Bluetooth 3.0 + HS Adapter  | 3         | 0.39%   |
| MediaTek Wireless_Device                                    | 3         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1180      | 55.09%  |
| AMD                                             | 437       | 20.4%   |
| Nvidia                                          | 341       | 15.92%  |
| C-Media Electronics                             | 22        | 1.03%   |
| Logitech                                        | 17        | 0.79%   |
| Creative Labs                                   | 15        | 0.7%    |
| Lenovo                                          | 11        | 0.51%   |
| Texas Instruments                               | 10        | 0.47%   |
| Realtek Semiconductor                           | 10        | 0.47%   |
| Silicon Integrated Systems [SiS]                | 6         | 0.28%   |
| JMTek                                           | 6         | 0.28%   |
| GN Netcom                                       | 6         | 0.28%   |
| SteelSeries ApS                                 | 5         | 0.23%   |
| Kingston Technology                             | 5         | 0.23%   |
| Sony                                            | 4         | 0.19%   |
| Generalplus Technology                          | 4         | 0.19%   |
| Blue Microphones                                | 4         | 0.19%   |
| BEHRINGER International                         | 4         | 0.19%   |
| Thesycon Systemsoftware & Consulting            | 3         | 0.14%   |
| Plantronics                                     | 3         | 0.14%   |
| M-Audio                                         | 3         | 0.14%   |
| Focusrite-Novation                              | 3         | 0.14%   |
| Creative Technology                             | 3         | 0.14%   |
| ASUSTek Computer                                | 3         | 0.14%   |
| Yamaha                                          | 2         | 0.09%   |
| VIA Technologies                                | 2         | 0.09%   |
| Trust                                           | 2         | 0.09%   |
| Microsoft                                       | 2         | 0.09%   |
| Micro Star International                        | 2         | 0.09%   |
| FiiO Electronics Technology                     | 2         | 0.09%   |
| Cambridge Silicon Radio                         | 2         | 0.09%   |
| XMOS                                            | 1         | 0.05%   |
| ULi Electronics                                 | 1         | 0.05%   |
| Tenx Technology                                 | 1         | 0.05%   |
| Samsung Electronics                             | 1         | 0.05%   |
| ROCCAT                                          | 1         | 0.05%   |
| Razer USA                                       | 1         | 0.05%   |
| Micronas                                        | 1         | 0.05%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.05%   |
| iCreate Technologies                            | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 143       | 5.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 126       | 4.98%   |
| AMD Family 17h/19h HD Audio Controller                                     | 119       | 4.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 110       | 4.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 75        | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 74        | 2.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 65        | 2.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 64        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 60        | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 59        | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 55        | 2.18%   |
| Intel Broadwell-U Audio Controller                                         | 53        | 2.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 48        | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 48        | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 45        | 1.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 43        | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 43        | 1.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 42        | 1.66%   |
| Intel Haswell-ULT HD Audio Controller                                      | 38        | 1.5%    |
| Intel 8 Series HD Audio Controller                                         | 38        | 1.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 36        | 1.42%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 35        | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 34        | 1.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 32        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 31        | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 31        | 1.23%   |
| AMD FCH Azalia Controller                                                  | 29        | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.07%   |
| Intel 200 Series PCH HD Audio                                              | 27        | 1.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 26        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 25        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 25        | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                   | 24        | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 23        | 0.91%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 21        | 0.83%   |
| Nvidia High Definition Audio Controller                                    | 19        | 0.75%   |
| Nvidia GP108 High Definition Audio Controller                              | 19        | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 18        | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 18        | 0.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 18        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 456       | 20.7%   |
| SK hynix                     | 359       | 16.3%   |
| Kingston                     | 278       | 12.62%  |
| Unknown                      | 260       | 11.8%   |
| Micron Technology            | 195       | 8.85%   |
| Crucial                      | 141       | 6.4%    |
| Corsair                      | 127       | 5.76%   |
| G.Skill                      | 66        | 3%      |
| Unknown                      | 34        | 1.54%   |
| Ramaxel Technology           | 33        | 1.5%    |
| A-DATA Technology            | 32        | 1.45%   |
| Elpida                       | 22        | 1%      |
| Nanya Technology             | 19        | 0.86%   |
| Transcend                    | 15        | 0.68%   |
| Team                         | 14        | 0.64%   |
| Hewlett-Packard              | 13        | 0.59%   |
| Patriot                      | 12        | 0.54%   |
| Goodram                      | 12        | 0.54%   |
| Avant                        | 7         | 0.32%   |
| Unknown (ABCD)               | 6         | 0.27%   |
| Super Talent                 | 6         | 0.27%   |
| Smart                        | 6         | 0.27%   |
| PNY                          | 6         | 0.27%   |
| Neo Forza                    | 5         | 0.23%   |
| Goldkey                      | 5         | 0.23%   |
| Qimonda                      | 4         | 0.18%   |
| Patriot Memory (PDP Systems) | 4         | 0.18%   |
| AMD                          | 4         | 0.18%   |
| 48spaces                     | 4         | 0.18%   |
| HPE                          | 3         | 0.14%   |
| Apacer                       | 3         | 0.14%   |
| V-GeN                        | 2         | 0.09%   |
| V-Color                      | 2         | 0.09%   |
| Toshiba                      | 2         | 0.09%   |
| Tigo                         | 2         | 0.09%   |
| Silicon Power                | 2         | 0.09%   |
| PUSKILL                      | 2         | 0.09%   |
| KomputerBay                  | 2         | 0.09%   |
| Kllisre                      | 2         | 0.09%   |
| Kingmax                      | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 34        | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 18        | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 17        | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 16        | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 16        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 15        | 0.62%   |
| Samsung RAM M393B1G70QH0-YK0 8192MB DIMM DDR3 1600MT/s       | 15        | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 14        | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 12        | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 12        | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s        | 12        | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 11        | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 10        | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 10        | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 10        | 0.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s        | 10        | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 9         | 0.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 9         | 0.37%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 9         | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 9         | 0.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 8         | 0.33%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s        | 8         | 0.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 7         | 0.29%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 7         | 0.29%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s        | 7         | 0.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 7         | 0.29%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 6         | 0.25%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                         | 6         | 0.25%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 6         | 0.25%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 6         | 0.25%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 6         | 0.25%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s         | 6         | 0.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 6         | 0.25%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 6         | 0.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s        | 6         | 0.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 6         | 0.25%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 6         | 0.25%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 6         | 0.25%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 6         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 780       | 40.82%  |
| DDR3    | 775       | 40.55%  |
| DDR2    | 132       | 6.91%   |
| Unknown | 72        | 3.77%   |
| LPDDR3  | 44        | 2.3%    |
| SDRAM   | 33        | 1.73%   |
| DDR     | 33        | 1.73%   |
| LPDDR4  | 28        | 1.47%   |
| DRAM    | 7         | 0.37%   |
| LPDDR5  | 4         | 0.21%   |
| SRAM    | 1         | 0.05%   |
| RAM     | 1         | 0.05%   |
| DDR5    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 915       | 47.88%  |
| SODIMM       | 886       | 46.36%  |
| Row Of Chips | 68        | 3.56%   |
| Chip         | 25        | 1.31%   |
| FB-DIMM      | 6         | 0.31%   |
| Unknown      | 6         | 0.31%   |
| RIMM         | 5         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 731       | 34.86%  |
| 4096   | 551       | 26.28%  |
| 16384  | 337       | 16.07%  |
| 2048   | 271       | 12.92%  |
| 1024   | 89        | 4.24%   |
| 32768  | 80        | 3.81%   |
| 512    | 23        | 1.1%    |
| 256    | 5         | 0.24%   |
| 65536  | 3         | 0.14%   |
| 128    | 2         | 0.1%    |
| 131072 | 1         | 0.05%   |
| 2560   | 1         | 0.05%   |
| 64     | 1         | 0.05%   |
| 32     | 1         | 0.05%   |
| 8      | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 457       | 22.42%  |
| 1333    | 258       | 12.66%  |
| 3200    | 212       | 10.4%   |
| 2400    | 204       | 10.01%  |
| 2667    | 178       | 8.73%   |
| 2133    | 175       | 8.59%   |
| 667     | 79        | 3.88%   |
| 800     | 70        | 3.43%   |
| Unknown | 58        | 2.85%   |
| 1334    | 48        | 2.36%   |
| 2666    | 41        | 2.01%   |
| 1867    | 39        | 1.91%   |
| 1066    | 29        | 1.42%   |
| 1067    | 27        | 1.32%   |
| 533     | 26        | 1.28%   |
| 3000    | 18        | 0.88%   |
| 2933    | 18        | 0.88%   |
| 4267    | 14        | 0.69%   |
| 3600    | 13        | 0.64%   |
| 1866    | 11        | 0.54%   |
| 400     | 8         | 0.39%   |
| 975     | 6         | 0.29%   |
| 266     | 6         | 0.29%   |
| 6400    | 4         | 0.2%    |
| 4266    | 4         | 0.2%    |
| 3400    | 4         | 0.2%    |
| 2134    | 4         | 0.2%    |
| 2048    | 3         | 0.15%   |
| 333     | 3         | 0.15%   |
| 3534    | 2         | 0.1%    |
| 1639    | 2         | 0.1%    |
| 1332    | 2         | 0.1%    |
| 65535   | 1         | 0.05%   |
| 5200    | 1         | 0.05%   |
| 4800    | 1         | 0.05%   |
| 4133    | 1         | 0.05%   |
| 3500    | 1         | 0.05%   |
| 3066    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 1800    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 30.77%  |
| Hewlett-Packard     | 2         | 15.38%  |
| ELGIN               | 2         | 15.38%  |
| Seiko Epson         | 1         | 7.69%   |
| Samsung Electronics | 1         | 7.69%   |
| QinHeng Electronics | 1         | 7.69%   |
| Prolific Technology | 1         | 7.69%   |
| Canon               | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| ELGIN L42PRO                                                                               | 2         | 15.38%  |
| Seiko Epson Printer                                                                        | 1         | 7.69%   |
| Samsung ML-1610 Mono Laser Printer                                                         | 1         | 7.69%   |
| QinHeng CH340S                                                                             | 1         | 7.69%   |
| Prolific PL2305 Parallel Port                                                              | 1         | 7.69%   |
| HP LaserJet 1012                                                                           | 1         | 7.69%   |
| HP HP LaserJet M14-M17 Printer HP LEDM IPP Printer HP LEDM IPP Printer HP LEDM IPP Printer | 1         | 7.69%   |
| Canon LBP2900                                                                              | 1         | 7.69%   |
| Brother MFC-7360N                                                                          | 1         | 7.69%   |
| Brother HL-L5200DW series                                                                  | 1         | 7.69%   |
| Brother HL-2030 Laser Printer                                                              | 1         | 7.69%   |
| Brother HL-1430 Laser Printer                                                              | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 80%     |
| Hewlett-Packard | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 40%     |
| HP ScanJet 5300c/5370c  | 1         | 20%     |
| Canon CanoScan LIDE 25  | 1         | 20%     |
| Canon CanoScan LiDE 220 | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 206       | 28.93%  |
| IMC Networks                           | 74        | 10.39%  |
| Microdia                               | 68        | 9.55%   |
| Acer                                   | 62        | 8.71%   |
| Realtek Semiconductor                  | 56        | 7.87%   |
| Sunplus Innovation Technology          | 44        | 6.18%   |
| Logitech                               | 39        | 5.48%   |
| Suyin                                  | 22        | 3.09%   |
| Lite-On Technology                     | 22        | 3.09%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 1.97%   |
| Apple                                  | 12        | 1.69%   |
| Syntek                                 | 11        | 1.54%   |
| Quanta                                 | 11        | 1.54%   |
| Lenovo                                 | 8         | 1.12%   |
| Silicon Motion                         | 7         | 0.98%   |
| Z-Star Microelectronics                | 5         | 0.7%    |
| Luxvisions Innotech Limited            | 4         | 0.56%   |
| Importek                               | 4         | 0.56%   |
| ALi                                    | 4         | 0.56%   |
| Alcor Micro                            | 4         | 0.56%   |
| Ricoh                                  | 3         | 0.42%   |
| ARC International                      | 3         | 0.42%   |
| WCM_USB                                | 2         | 0.28%   |
| Unknown                                | 2         | 0.28%   |
| Sonix Technology                       | 2         | 0.28%   |
| ShineTech                              | 2         | 0.28%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.28%   |
| Primax Electronics                     | 2         | 0.28%   |
| Pixart Imaging                         | 2         | 0.28%   |
| OmniVision Technologies                | 2         | 0.28%   |
| Intel                                  | 2         | 0.28%   |
| Cubeternet                             | 2         | 0.28%   |
| YGTek                                  | 1         | 0.14%   |
| Valve Software                         | 1         | 0.14%   |
| SunplusIT                              | 1         | 0.14%   |
| Huawei Technologies                    | 1         | 0.14%   |
| Genesys Logic                          | 1         | 0.14%   |
| GEMBIRD                                | 1         | 0.14%   |
| DigiTech                               | 1         | 0.14%   |
| Aveo Technology                        | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 64        | 8.9%    |
| Acer Integrated Camera                    | 32        | 4.45%   |
| IMC Networks Integrated Camera            | 26        | 3.62%   |
| Realtek Integrated_Webcam_HD              | 21        | 2.92%   |
| Chicony HD WebCam                         | 20        | 2.78%   |
| Microdia Integrated Webcam                | 18        | 2.5%    |
| Microdia Integrated_Webcam_HD             | 16        | 2.23%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 15        | 2.09%   |
| Sunplus Integrated_Webcam_HD              | 14        | 1.95%   |
| Logitech Webcam C270                      | 13        | 1.81%   |
| Lite-On Integrated Camera                 | 13        | 1.81%   |
| IMC Networks USB2.0 HD UVC WebCam         | 11        | 1.53%   |
| Chicony Integrated Camera (1280x720@30)   | 11        | 1.53%   |
| Chicony Chicony USB2.0 Camera             | 11        | 1.53%   |
| Realtek Realtek USB2.0 PC Camera          | 10        | 1.39%   |
| IMC Networks EasyCamera                   | 9         | 1.25%   |
| Logitech HD Pro Webcam C920               | 8         | 1.11%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 7         | 0.97%   |
| Chicony ThinkPad T490 Webcam              | 7         | 0.97%   |
| Microdia Integrated Webcam HD             | 6         | 0.83%   |
| IMC Networks Integrated Webcam            | 6         | 0.83%   |
| Apple FaceTime HD Camera                  | 6         | 0.83%   |
| Acer SunplusIT Integrated Camera          | 6         | 0.83%   |
| Acer Lenovo EasyCamera                    | 6         | 0.83%   |
| Syntek EasyCamera                         | 5         | 0.7%    |
| Sunplus Laptop Integrated WebCam HD       | 5         | 0.7%    |
| Sunplus HD WebCam                         | 5         | 0.7%    |
| Lenovo Integrated Webcam [R5U877]         | 5         | 0.7%    |
| IMC Networks UVC VGA Webcam               | 5         | 0.7%    |
| Apple FaceTime HD Camera (Built-in)       | 5         | 0.7%    |
| Realtek Integrated Webcam                 | 4         | 0.56%   |
| Quanta HD WebCam                          | 4         | 0.56%   |
| Microdia Dell Laptop Integrated Webcam HD | 4         | 0.56%   |
| Lite-On HP HD Camera                      | 4         | 0.56%   |
| IMC Networks HD Camera                    | 4         | 0.56%   |
| Chicony USB2.0 VGA UVC WebCam             | 4         | 0.56%   |
| Chicony Integrated IR Camera              | 4         | 0.56%   |
| Chicony Integrated HP HD Webcam           | 4         | 0.56%   |
| Chicony Integrated Camera [ThinkPad]      | 4         | 0.56%   |
| Chicony HP HD Webcam [Fixed]              | 4         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 69        | 34.33%  |
| Synaptics                  | 51        | 25.37%  |
| Shenzhen Goodix Technology | 27        | 13.43%  |
| Upek                       | 17        | 8.46%   |
| STMicroelectronics         | 10        | 4.98%   |
| AuthenTec                  | 9         | 4.48%   |
| Broadcom                   | 8         | 3.98%   |
| LighTuning Technology      | 6         | 2.99%   |
| Samsung Electronics        | 1         | 0.5%    |
| Focal-systems.Corp         | 1         | 0.5%    |
| Elan Microelectronics      | 1         | 0.5%    |
| DigitalPersona             | 1         | 0.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 22        | 10.95%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 20        | 9.95%   |
| Validity Sensors Synaptics WBDI                                              | 17        | 8.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 17        | 8.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 16        | 7.96%   |
| Shenzhen Goodix Fingerprint Reader                                           | 15        | 7.46%   |
| STMicroelectronics Fingerprint Reader                                        | 10        | 4.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 9         | 4.48%   |
| Shenzhen Goodix  FingerPrint Device                                          | 9         | 4.48%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 3.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 7         | 3.48%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 6         | 2.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                    | 4         | 1.99%   |
| Unknown                                                                      | 4         | 1.99%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 3         | 1.49%   |
| Shenzhen Goodix FingerPrint                                                  | 3         | 1.49%   |
| LighTuning EgisTec EH575                                                     | 3         | 1.49%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 3         | 1.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 1.49%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 2         | 1%      |
| Validity Sensors VFS Fingerprint sensor                                      | 2         | 1%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 2         | 1%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 1%      |
| AuthenTec AES2810                                                            | 2         | 1%      |
| Validity Sensors VFS491                                                      | 1         | 0.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 0.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 0.5%    |
| Validity Sensors Fingerprint scanner                                         | 1         | 0.5%    |
| Synaptics  WBDI                                                              | 1         | 0.5%    |
| Synaptics product 0x00be                                                     | 1         | 0.5%    |
| Samsung Fingerprint Sensor Device - 730B                                     | 1         | 0.5%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 0.5%    |
| Focal-systems.Corp FocalTech Fingerprint reader                              | 1         | 0.5%    |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 0.5%    |
| DigitalPersona Fingerprint Reader                                            | 1         | 0.5%    |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 0.5%    |

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
| 1     | 662       | 31.84%  |
| 0     | 594       | 28.57%  |
| 2     | 467       | 22.46%  |
| 3     | 233       | 11.21%  |
| 4     | 91        | 4.38%   |
| 5     | 18        | 0.87%   |
| 6     | 11        | 0.53%   |
| 7     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1131      | 46.45%  |
| Bluetooth                | 324       | 13.31%  |
| Net/wireless             | 278       | 11.42%  |
| Card reader              | 223       | 9.16%   |
| Fingerprint reader       | 194       | 7.97%   |
| Firewire controller      | 145       | 5.95%   |
| Sound                    | 36        | 1.48%   |
| Net/ethernet             | 33        | 1.36%   |
| Network                  | 27        | 1.11%   |
| Storage                  | 20        | 0.82%   |
| Modem                    | 14        | 0.57%   |
| Dvb card                 | 5         | 0.21%   |
| Storage/ide              | 2         | 0.08%   |
| Storage/raid             | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Graphics card            | 1         | 0.04%   |

