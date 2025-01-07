BSD in France - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 1043

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| AZW           | EQ                          | Desktop     | [79c6c2f2fb](https://bsd-hardware.info/?probe=79c6c2f2fb) | Jan 05, 2025 |
| ASUSTek       | P8Z77-V                     | Desktop     | [d3e6e71d15](https://bsd-hardware.info/?probe=d3e6e71d15) | Jan 03, 2025 |
| Techvision    | TVI7309X B0                 | Desktop     | [e3b91fef39](https://bsd-hardware.info/?probe=e3b91fef39) | Jan 02, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c6697164fc](https://bsd-hardware.info/?probe=c6697164fc) | Jan 02, 2025 |
| ASUSTek       | P8Z77-V                     | Desktop     | [657957bf41](https://bsd-hardware.info/?probe=657957bf41) | Jan 02, 2025 |
| PICO PC       | MNHO-113                    | Desktop     | [9ac6a7a9ad](https://bsd-hardware.info/?probe=9ac6a7a9ad) | Jan 02, 2025 |
| ASUSTek       | P8Z77-V                     | Desktop     | [ae387d9e4c](https://bsd-hardware.info/?probe=ae387d9e4c) | Dec 29, 2024 |
| Intel         | NUC11ATBC2 M53055-500       | Mini pc     | [691fb927f2](https://bsd-hardware.info/?probe=691fb927f2) | Dec 28, 2024 |
| NF533MS       | 1.0                         | Desktop     | [3f9b4a5c4f](https://bsd-hardware.info/?probe=3f9b4a5c4f) | Dec 28, 2024 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [f28edc2c8b](https://bsd-hardware.info/?probe=f28edc2c8b) | Dec 28, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [51514fe0c0](https://bsd-hardware.info/?probe=51514fe0c0) | Dec 28, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [7d9a498768](https://bsd-hardware.info/?probe=7d9a498768) | Dec 28, 2024 |
| ASUSTek       | P8Z77-V                     | Desktop     | [548a9b376e](https://bsd-hardware.info/?probe=548a9b376e) | Dec 28, 2024 |
| Supermicro    | X10SDE-DF                   | Desktop     | [ce805c4c07](https://bsd-hardware.info/?probe=ce805c4c07) | Dec 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [846b02424a](https://bsd-hardware.info/?probe=846b02424a) | Dec 25, 2024 |
| PC Engines    | apu4                        | Desktop     | [c9b7343baf](https://bsd-hardware.info/?probe=c9b7343baf) | Dec 25, 2024 |
| HUAWEI        | KPL-W0X                     | Notebook    | [ac7b8b09f0](https://bsd-hardware.info/?probe=ac7b8b09f0) | Dec 24, 2024 |
| Unknown       | QDNV01                      | Desktop     | [fcdc78df83](https://bsd-hardware.info/?probe=fcdc78df83) | Dec 24, 2024 |
| PC Engines    | apu4                        | Desktop     | [c41bf918c5](https://bsd-hardware.info/?probe=c41bf918c5) | Dec 22, 2024 |
| Supermicro    | X10SDE-DF                   | Desktop     | [d625d92899](https://bsd-hardware.info/?probe=d625d92899) | Dec 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [19ffcf2c92](https://bsd-hardware.info/?probe=19ffcf2c92) | Dec 20, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [aa6a6969b9](https://bsd-hardware.info/?probe=aa6a6969b9) | Dec 12, 2024 |
| PC Engines    | APU2                        | Desktop     | [dfc440d7ec](https://bsd-hardware.info/?probe=dfc440d7ec) | Dec 11, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cfc56b5602](https://bsd-hardware.info/?probe=cfc56b5602) | Dec 11, 2024 |
| ASUSTek       | P5KR                        | Desktop     | [9ee55170f1](https://bsd-hardware.info/?probe=9ee55170f1) | Dec 11, 2024 |
| ASUSTek       | P5KR                        | Desktop     | [8b47c8c93a](https://bsd-hardware.info/?probe=8b47c8c93a) | Dec 10, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [2e959ea19a](https://bsd-hardware.info/?probe=2e959ea19a) | Dec 09, 2024 |
| HP            | 8055                        | Desktop     | [21547fc9c7](https://bsd-hardware.info/?probe=21547fc9c7) | Dec 09, 2024 |
| Deciso        | Netboard A20                | Notebook    | [7a9c98faa1](https://bsd-hardware.info/?probe=7a9c98faa1) | Dec 08, 2024 |
| Alienware     | m15 R6                      | Notebook    | [9060b1741b](https://bsd-hardware.info/?probe=9060b1741b) | Dec 08, 2024 |
| Notebook      | N7x0WU                      | Notebook    | [d9312fac72](https://bsd-hardware.info/?probe=d9312fac72) | Dec 05, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [b75044f43a](https://bsd-hardware.info/?probe=b75044f43a) | Dec 04, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a6e076d9f](https://bsd-hardware.info/?probe=1a6e076d9f) | Dec 02, 2024 |
| Supermicro    | X11SPM-F                    | Server      | [3fdfe4a819](https://bsd-hardware.info/?probe=3fdfe4a819) | Dec 01, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [cae7ae1e3f](https://bsd-hardware.info/?probe=cae7ae1e3f) | Nov 30, 2024 |
| Dell          | Precision 7730              | Notebook    | [57ea84435b](https://bsd-hardware.info/?probe=57ea84435b) | Nov 29, 2024 |
| Protectli     | V1410                       | Desktop     | [2d61c7d7cf](https://bsd-hardware.info/?probe=2d61c7d7cf) | Nov 23, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [f4ba847672](https://bsd-hardware.info/?probe=f4ba847672) | Nov 18, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | Notebook    | [3fa8964010](https://bsd-hardware.info/?probe=3fa8964010) | Nov 18, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [4e7ca33867](https://bsd-hardware.info/?probe=4e7ca33867) | Nov 17, 2024 |
| Unknown       | Unknown                     | Desktop     | [a1a22fe34f](https://bsd-hardware.info/?probe=a1a22fe34f) | Nov 17, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [317947a879](https://bsd-hardware.info/?probe=317947a879) | Nov 16, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [4b237d329e](https://bsd-hardware.info/?probe=4b237d329e) | Nov 15, 2024 |
| Dell          | Precision M4800             | Notebook    | [437d5c965b](https://bsd-hardware.info/?probe=437d5c965b) | Nov 15, 2024 |
| Unknown       | QDNV01                      | Desktop     | [2cf695cde4](https://bsd-hardware.info/?probe=2cf695cde4) | Nov 15, 2024 |
| Dell          | Precision M4800             | Notebook    | [b586c78d26](https://bsd-hardware.info/?probe=b586c78d26) | Nov 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [6a968626a1](https://bsd-hardware.info/?probe=6a968626a1) | Nov 15, 2024 |
| Unknown       | Unknown                     | Desktop     | [87f9bf6741](https://bsd-hardware.info/?probe=87f9bf6741) | Nov 15, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [e883cc34cb](https://bsd-hardware.info/?probe=e883cc34cb) | Nov 11, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [270b6ddde9](https://bsd-hardware.info/?probe=270b6ddde9) | Nov 09, 2024 |
| Protectli     | V1410                       | Desktop     | [271becd723](https://bsd-hardware.info/?probe=271becd723) | Nov 08, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [298cce5e54](https://bsd-hardware.info/?probe=298cce5e54) | Nov 08, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [e8605e6681](https://bsd-hardware.info/?probe=e8605e6681) | Nov 07, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [45f3b7828e](https://bsd-hardware.info/?probe=45f3b7828e) | Nov 04, 2024 |
| Sony          | SVS1312J3EW                 | Notebook    | [3451ac064b](https://bsd-hardware.info/?probe=3451ac064b) | Nov 02, 2024 |
| Acer          | Veriton X490G               | Desktop     | [37ea6d5ae6](https://bsd-hardware.info/?probe=37ea6d5ae6) | Nov 02, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [b140c0e1d4](https://bsd-hardware.info/?probe=b140c0e1d4) | Nov 01, 2024 |
| ASUSTek       | PRIME B650M-K               | Desktop     | [9a4c1afe1d](https://bsd-hardware.info/?probe=9a4c1afe1d) | Oct 31, 2024 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [9fb0e16856](https://bsd-hardware.info/?probe=9fb0e16856) | Oct 31, 2024 |
| Lanner Ele... | NCA-1515A-EK6               | Desktop     | [54bd081ba6](https://bsd-hardware.info/?probe=54bd081ba6) | Oct 30, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [304412fe81](https://bsd-hardware.info/?probe=304412fe81) | Oct 29, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e11b852da6](https://bsd-hardware.info/?probe=e11b852da6) | Oct 28, 2024 |
| Supermicro    | X7SLA                       | Desktop     | [af00bda6c0](https://bsd-hardware.info/?probe=af00bda6c0) | Oct 28, 2024 |
| Sony          | SVS1312J3EW                 | Notebook    | [c96da35c3f](https://bsd-hardware.info/?probe=c96da35c3f) | Oct 28, 2024 |
| Shenzhen M... | AHWSA                       | Desktop     | [c43c16b255](https://bsd-hardware.info/?probe=c43c16b255) | Oct 26, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [128ada95fb](https://bsd-hardware.info/?probe=128ada95fb) | Oct 23, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ca9079b911](https://bsd-hardware.info/?probe=ca9079b911) | Oct 22, 2024 |
| HP            | 1495                        | Desktop     | [0cea5d989a](https://bsd-hardware.info/?probe=0cea5d989a) | Oct 22, 2024 |
| Unknown       | Unknown                     | Notebook    | [43c3d622d9](https://bsd-hardware.info/?probe=43c3d622d9) | Oct 21, 2024 |
| TB            | WTR R1                      | Desktop     | [6b88b2d0ec](https://bsd-hardware.info/?probe=6b88b2d0ec) | Oct 19, 2024 |
| Acer          | Veriton X490G               | Desktop     | [e5d4238378](https://bsd-hardware.info/?probe=e5d4238378) | Oct 17, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [13e4335b5e](https://bsd-hardware.info/?probe=13e4335b5e) | Oct 15, 2024 |
| Lenovo        | ThinkSystem ST50 V2 7D8J... | Desktop     | [9664ad9928](https://bsd-hardware.info/?probe=9664ad9928) | Oct 14, 2024 |
| HP            | 1495                        | Desktop     | [47ab18f751](https://bsd-hardware.info/?probe=47ab18f751) | Oct 14, 2024 |
| ZOTAC         | NM10                        | Desktop     | [da50004d4b](https://bsd-hardware.info/?probe=da50004d4b) | Oct 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [f3d5c45acc](https://bsd-hardware.info/?probe=f3d5c45acc) | Oct 12, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [2472627731](https://bsd-hardware.info/?probe=2472627731) | Oct 10, 2024 |
| Gigabyte      | AORUS 16X ASG               | Notebook    | [0a05bfa1e3](https://bsd-hardware.info/?probe=0a05bfa1e3) | Oct 08, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [97e0c04743](https://bsd-hardware.info/?probe=97e0c04743) | Oct 07, 2024 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [b1c8dd5749](https://bsd-hardware.info/?probe=b1c8dd5749) | Oct 04, 2024 |
| Intel         | JSL MRD                     | Desktop     | [1cf806399f](https://bsd-hardware.info/?probe=1cf806399f) | Oct 04, 2024 |
| HP            | 8591                        | Desktop     | [353f0a785f](https://bsd-hardware.info/?probe=353f0a785f) | Oct 03, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [b4f6d6a1f9](https://bsd-hardware.info/?probe=b4f6d6a1f9) | Oct 03, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [56d22f4ec1](https://bsd-hardware.info/?probe=56d22f4ec1) | Oct 03, 2024 |
| Dell          | 0TP412                      | Desktop     | [3bf5e8b493](https://bsd-hardware.info/?probe=3bf5e8b493) | Sep 30, 2024 |
| HP            | 8592                        | Desktop     | [7be46d228b](https://bsd-hardware.info/?probe=7be46d228b) | Sep 29, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [e3f2347749](https://bsd-hardware.info/?probe=e3f2347749) | Sep 29, 2024 |
| Sony          | VGN-FZ19VN                  | Notebook    | [a5e398c41f](https://bsd-hardware.info/?probe=a5e398c41f) | Sep 28, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [3cac5e22e2](https://bsd-hardware.info/?probe=3cac5e22e2) | Sep 28, 2024 |
| HP            | 8591                        | Desktop     | [f2bd252152](https://bsd-hardware.info/?probe=f2bd252152) | Sep 27, 2024 |
| Fujitsu       | D3375-A1 S26361-D3375-A1... | Server      | [1854fbf430](https://bsd-hardware.info/?probe=1854fbf430) | Sep 27, 2024 |
| Unknown       | Unknown                     | Desktop     | [61a1f4c2c6](https://bsd-hardware.info/?probe=61a1f4c2c6) | Sep 26, 2024 |
| Dell          | System XPS L702X            | Notebook    | [5a0e1971a2](https://bsd-hardware.info/?probe=5a0e1971a2) | Sep 26, 2024 |
| BOSGAME       | DNB10M                      | Desktop     | [bad0ba33fc](https://bsd-hardware.info/?probe=bad0ba33fc) | Sep 24, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [4ca237f74c](https://bsd-hardware.info/?probe=4ca237f74c) | Sep 24, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [47d4fe3720](https://bsd-hardware.info/?probe=47d4fe3720) | Sep 23, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [213143884b](https://bsd-hardware.info/?probe=213143884b) | Sep 21, 2024 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [777503efcf](https://bsd-hardware.info/?probe=777503efcf) | Sep 21, 2024 |
| Unknown       | Unknown                     | Desktop     | [5d67218293](https://bsd-hardware.info/?probe=5d67218293) | Sep 19, 2024 |
| PC Engines    | APU2                        | Desktop     | [c37f7801e3](https://bsd-hardware.info/?probe=c37f7801e3) | Sep 19, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [5d6734e438](https://bsd-hardware.info/?probe=5d6734e438) | Sep 18, 2024 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [b73c537570](https://bsd-hardware.info/?probe=b73c537570) | Sep 18, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [a57569240a](https://bsd-hardware.info/?probe=a57569240a) | Sep 17, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [ca3ea4135e](https://bsd-hardware.info/?probe=ca3ea4135e) | Sep 11, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [5c1dfe489a](https://bsd-hardware.info/?probe=5c1dfe489a) | Sep 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [aad1ef7c1a](https://bsd-hardware.info/?probe=aad1ef7c1a) | Sep 07, 2024 |
| Protectli     | FW6 Ver                     | Desktop     | [c24161a3c6](https://bsd-hardware.info/?probe=c24161a3c6) | Sep 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [b79e59a32d](https://bsd-hardware.info/?probe=b79e59a32d) | Sep 04, 2024 |
| Unknown       | Unknown                     | Desktop     | [56945d515b](https://bsd-hardware.info/?probe=56945d515b) | Sep 02, 2024 |
| PC Engines    | APU2                        | Desktop     | [4743399bdd](https://bsd-hardware.info/?probe=4743399bdd) | Sep 02, 2024 |
| Protectli     | V1410                       | Desktop     | [bbe0e6538e](https://bsd-hardware.info/?probe=bbe0e6538e) | Aug 31, 2024 |
| TB            | WTR R1                      | Desktop     | [2a27292fe0](https://bsd-hardware.info/?probe=2a27292fe0) | Aug 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [9b4ba9b33f](https://bsd-hardware.info/?probe=9b4ba9b33f) | Aug 27, 2024 |
| Unknown       | QDNV01                      | Desktop     | [b8dbac11c3](https://bsd-hardware.info/?probe=b8dbac11c3) | Aug 26, 2024 |
| Unknown       | QDNV01                      | Desktop     | [28f44cfb5f](https://bsd-hardware.info/?probe=28f44cfb5f) | Aug 22, 2024 |
| PICO PC       | MNHO-113                    | Desktop     | [30cc7bad16](https://bsd-hardware.info/?probe=30cc7bad16) | Aug 20, 2024 |
| PICO PC       | MNHO-113                    | Desktop     | [365c21102e](https://bsd-hardware.info/?probe=365c21102e) | Aug 20, 2024 |
| ASUSTek       | P11C-M-10G-2T Series        | Desktop     | [905a642ee4](https://bsd-hardware.info/?probe=905a642ee4) | Aug 18, 2024 |
| SJRC          | ADLN-6L                     | Desktop     | [8b46918510](https://bsd-hardware.info/?probe=8b46918510) | Aug 15, 2024 |
| Protectli     | V1410                       | Desktop     | [fd2d9e9396](https://bsd-hardware.info/?probe=fd2d9e9396) | Aug 15, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [d2e93eb2d7](https://bsd-hardware.info/?probe=d2e93eb2d7) | Aug 11, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fb46302147](https://bsd-hardware.info/?probe=fb46302147) | Aug 11, 2024 |
| Dell          | 07WP95 A02                  | Desktop     | [0475c7970c](https://bsd-hardware.info/?probe=0475c7970c) | Aug 11, 2024 |
| HP            | 8062                        | Desktop     | [b862eb308f](https://bsd-hardware.info/?probe=b862eb308f) | Aug 10, 2024 |
| TB            | WTR R1                      | Desktop     | [f096c6e244](https://bsd-hardware.info/?probe=f096c6e244) | Aug 10, 2024 |
| TB            | WTR R1                      | Desktop     | [5edd4a709c](https://bsd-hardware.info/?probe=5edd4a709c) | Aug 10, 2024 |
| PC Engines    | apu4                        | Desktop     | [561ce5e0bb](https://bsd-hardware.info/?probe=561ce5e0bb) | Aug 10, 2024 |
| Unknown       | QDNV01                      | Desktop     | [b1c461dcf2](https://bsd-hardware.info/?probe=b1c461dcf2) | Aug 09, 2024 |
| Protectli     | V1410                       | Desktop     | [9017db7df0](https://bsd-hardware.info/?probe=9017db7df0) | Aug 06, 2024 |
| Protectli     | V1410                       | Desktop     | [1d2e227469](https://bsd-hardware.info/?probe=1d2e227469) | Aug 05, 2024 |
| Impact Tec... | ITIUM 6050                  | Desktop     | [e3b7ac42b8](https://bsd-hardware.info/?probe=e3b7ac42b8) | Aug 02, 2024 |
| Intel         | QHSW02                      | Desktop     | [f1a8a972fc](https://bsd-hardware.info/?probe=f1a8a972fc) | Jul 28, 2024 |
| Unknown       | Unknown                     | Notebook    | [462a87d038](https://bsd-hardware.info/?probe=462a87d038) | Jul 24, 2024 |
| Unknown       | Unknown                     | Notebook    | [341bc14d4f](https://bsd-hardware.info/?probe=341bc14d4f) | Jul 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [bc07108ffa](https://bsd-hardware.info/?probe=bc07108ffa) | Jul 21, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [ec791ad8a1](https://bsd-hardware.info/?probe=ec791ad8a1) | Jul 21, 2024 |
| Intel         | JSL MRD                     | Desktop     | [defd2c363f](https://bsd-hardware.info/?probe=defd2c363f) | Jul 21, 2024 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [80ae54023f](https://bsd-hardware.info/?probe=80ae54023f) | Jul 17, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [7947827711](https://bsd-hardware.info/?probe=7947827711) | Jul 08, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ccbdbce9f9](https://bsd-hardware.info/?probe=ccbdbce9f9) | Jul 06, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [41adaa07be](https://bsd-hardware.info/?probe=41adaa07be) | Jun 30, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [9834762b2e](https://bsd-hardware.info/?probe=9834762b2e) | Jun 23, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [a6261fd253](https://bsd-hardware.info/?probe=a6261fd253) | Jun 20, 2024 |
| Dell          | 0KC9NP A01                  | Desktop     | [bb7ac1fa79](https://bsd-hardware.info/?probe=bb7ac1fa79) | Jun 19, 2024 |
| BESSTAR Te... | GB7                         | Mini pc     | [0ecfb11818](https://bsd-hardware.info/?probe=0ecfb11818) | Jun 18, 2024 |
| Intel(R) C... | NUC6CAYH                    | Mini pc     | [dbe33d4967](https://bsd-hardware.info/?probe=dbe33d4967) | Jun 18, 2024 |
| Supermicro    | X11SSL-F                    | Server      | [4f59953655](https://bsd-hardware.info/?probe=4f59953655) | Jun 15, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8788f8a710](https://bsd-hardware.info/?probe=8788f8a710) | Jun 10, 2024 |
| Unknown       | QDNV01                      | Desktop     | [61d644c0b5](https://bsd-hardware.info/?probe=61d644c0b5) | Jun 09, 2024 |
| Notebook      | W740SU                      | Notebook    | [31be7db967](https://bsd-hardware.info/?probe=31be7db967) | Jun 09, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [01c3366bfb](https://bsd-hardware.info/?probe=01c3366bfb) | Jun 07, 2024 |
| Dell          | Precision 7520              | Notebook    | [48232bd1d6](https://bsd-hardware.info/?probe=48232bd1d6) | Jun 06, 2024 |
| Notebook      | N7x0WU                      | Notebook    | [61e6b811dd](https://bsd-hardware.info/?probe=61e6b811dd) | Jun 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [f07fafed9c](https://bsd-hardware.info/?probe=f07fafed9c) | Jun 04, 2024 |
| Intel         | S2600WT2R                   | Desktop     | [406818a434](https://bsd-hardware.info/?probe=406818a434) | Jun 03, 2024 |
| ADI Engine... | RCC-VE                      | Desktop     | [5a7f42f7bd](https://bsd-hardware.info/?probe=5a7f42f7bd) | Jun 03, 2024 |
| ADI Engine... | RCC-VE                      | Desktop     | [d2148f30f0](https://bsd-hardware.info/?probe=d2148f30f0) | May 29, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [29c6cd2aaf](https://bsd-hardware.info/?probe=29c6cd2aaf) | May 24, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [05a5e8f221](https://bsd-hardware.info/?probe=05a5e8f221) | May 23, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [8e32e2a7e9](https://bsd-hardware.info/?probe=8e32e2a7e9) | May 22, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [d6a82de164](https://bsd-hardware.info/?probe=d6a82de164) | May 22, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [18e5e61859](https://bsd-hardware.info/?probe=18e5e61859) | May 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [f1d0a3a306](https://bsd-hardware.info/?probe=f1d0a3a306) | May 18, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [0eaf743c54](https://bsd-hardware.info/?probe=0eaf743c54) | May 07, 2024 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [42edfcecd6](https://bsd-hardware.info/?probe=42edfcecd6) | May 06, 2024 |
| Unknown       | QDNV01                      | Desktop     | [8b77bdf0b8](https://bsd-hardware.info/?probe=8b77bdf0b8) | May 04, 2024 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [708617284b](https://bsd-hardware.info/?probe=708617284b) | May 03, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [a9ec0cba48](https://bsd-hardware.info/?probe=a9ec0cba48) | May 02, 2024 |
| Dell          | Latitude 7490               | Notebook    | [e55889ef1e](https://bsd-hardware.info/?probe=e55889ef1e) | May 02, 2024 |
| HP            | 8062                        | Desktop     | [2669931060](https://bsd-hardware.info/?probe=2669931060) | May 01, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [26a2dbed23](https://bsd-hardware.info/?probe=26a2dbed23) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [126d9918f3](https://bsd-hardware.info/?probe=126d9918f3) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [5bb2644b89](https://bsd-hardware.info/?probe=5bb2644b89) | Apr 28, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [2b066c44b9](https://bsd-hardware.info/?probe=2b066c44b9) | Apr 26, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [a206641c60](https://bsd-hardware.info/?probe=a206641c60) | Apr 26, 2024 |
| Dell          | 03X6X0 A07                  | Server      | [fcb58713da](https://bsd-hardware.info/?probe=fcb58713da) | Apr 24, 2024 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [d76cb40918](https://bsd-hardware.info/?probe=d76cb40918) | Apr 23, 2024 |
| Lenovo        | ThinkPad X220 429135G       | Notebook    | [b681d0b406](https://bsd-hardware.info/?probe=b681d0b406) | Apr 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [ff6d7d0ae2](https://bsd-hardware.info/?probe=ff6d7d0ae2) | Apr 22, 2024 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [8baf9d0ad0](https://bsd-hardware.info/?probe=8baf9d0ad0) | Apr 21, 2024 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [909b53a869](https://bsd-hardware.info/?probe=909b53a869) | Apr 19, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [fc810b38b1](https://bsd-hardware.info/?probe=fc810b38b1) | Apr 16, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| Dell          | Latitude 7490               | Notebook    | [38f6023f20](https://bsd-hardware.info/?probe=38f6023f20) | Apr 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [a4dc0d0ac8](https://bsd-hardware.info/?probe=a4dc0d0ac8) | Apr 13, 2024 |
| Unknown       | Unknown                     | Mini pc     | [c064a21fb3](https://bsd-hardware.info/?probe=c064a21fb3) | Apr 12, 2024 |
| ASRock        | H470M-ITX/ac                | Desktop     | [800c9334a3](https://bsd-hardware.info/?probe=800c9334a3) | Apr 08, 2024 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [02c2198de1](https://bsd-hardware.info/?probe=02c2198de1) | Apr 01, 2024 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7c4f577a86](https://bsd-hardware.info/?probe=7c4f577a86) | Apr 01, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [0b84a8b2a6](https://bsd-hardware.info/?probe=0b84a8b2a6) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [111422d451](https://bsd-hardware.info/?probe=111422d451) | Mar 28, 2024 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [c27c12203e](https://bsd-hardware.info/?probe=c27c12203e) | Mar 23, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [8bcd2d01e2](https://bsd-hardware.info/?probe=8bcd2d01e2) | Mar 16, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [172b87ed37](https://bsd-hardware.info/?probe=172b87ed37) | Mar 15, 2024 |
| Lenovo        | ThinkPad X220 429147U       | Notebook    | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| Gowin Solu... | GW-MB-U01                   | Desktop     | [94b9cc89bc](https://bsd-hardware.info/?probe=94b9cc89bc) | Mar 11, 2024 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [0111e4442e](https://bsd-hardware.info/?probe=0111e4442e) | Mar 11, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [106656a8a2](https://bsd-hardware.info/?probe=106656a8a2) | Mar 10, 2024 |
| GoWin Solu... | R86S                        | Desktop     | [254e4c652c](https://bsd-hardware.info/?probe=254e4c652c) | Mar 10, 2024 |
| HP            | 3031h                       | Desktop     | [cf973d0c2d](https://bsd-hardware.info/?probe=cf973d0c2d) | Mar 10, 2024 |
| ASUSTek       | P8P67                       | Desktop     | [1971d6c84c](https://bsd-hardware.info/?probe=1971d6c84c) | Feb 27, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [ec927cc965](https://bsd-hardware.info/?probe=ec927cc965) | Feb 27, 2024 |
| HP            | 8350                        | Desktop     | [0b372c4754](https://bsd-hardware.info/?probe=0b372c4754) | Feb 24, 2024 |
| Supermicro    | X7SPA-HF                    | Desktop     | [da90600890](https://bsd-hardware.info/?probe=da90600890) | Feb 23, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8f8526d883](https://bsd-hardware.info/?probe=8f8526d883) | Feb 22, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [28e6ba3f75](https://bsd-hardware.info/?probe=28e6ba3f75) | Feb 22, 2024 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [57e899e0d6](https://bsd-hardware.info/?probe=57e899e0d6) | Feb 20, 2024 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [b2803a2372](https://bsd-hardware.info/?probe=b2803a2372) | Feb 20, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [5a03257c9a](https://bsd-hardware.info/?probe=5a03257c9a) | Feb 19, 2024 |
| Dell          | Precision 7520              | Notebook    | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Dell          | Latitude E6430              | Notebook    | [1f9f417c2f](https://bsd-hardware.info/?probe=1f9f417c2f) | Feb 18, 2024 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [ca7e1f0fae](https://bsd-hardware.info/?probe=ca7e1f0fae) | Feb 12, 2024 |
| Intel         | JSL MRD                     | Desktop     | [373f1bfecf](https://bsd-hardware.info/?probe=373f1bfecf) | Feb 10, 2024 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b3e9bf8bcd](https://bsd-hardware.info/?probe=b3e9bf8bcd) | Feb 10, 2024 |
| Lenovo        | ThinkCentre M91p 7052C1G    | Desktop     | [3aeb926332](https://bsd-hardware.info/?probe=3aeb926332) | Feb 08, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [1b2b064c64](https://bsd-hardware.info/?probe=1b2b064c64) | Feb 08, 2024 |
| Supermicro    | X11SSL-CF                   | Server      | [8fcaaf3025](https://bsd-hardware.info/?probe=8fcaaf3025) | Feb 07, 2024 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [d118552b57](https://bsd-hardware.info/?probe=d118552b57) | Feb 03, 2024 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a531acf3f8](https://bsd-hardware.info/?probe=a531acf3f8) | Feb 02, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [58701df17a](https://bsd-hardware.info/?probe=58701df17a) | Feb 01, 2024 |
| Dell          | 04MFRM A02                  | Desktop     | [d5eb2fb3f3](https://bsd-hardware.info/?probe=d5eb2fb3f3) | Feb 01, 2024 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [e253bc0eb8](https://bsd-hardware.info/?probe=e253bc0eb8) | Feb 01, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [c8d68d0eec](https://bsd-hardware.info/?probe=c8d68d0eec) | Feb 01, 2024 |
| Acer          | TravelMate P645-SG          | Notebook    | [5765a3732f](https://bsd-hardware.info/?probe=5765a3732f) | Jan 31, 2024 |
| Acer          | TravelMate P645-SG          | Notebook    | [32dc9a4b1b](https://bsd-hardware.info/?probe=32dc9a4b1b) | Jan 31, 2024 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [a1fc491614](https://bsd-hardware.info/?probe=a1fc491614) | Jan 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [4331604969](https://bsd-hardware.info/?probe=4331604969) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [d4be439e34](https://bsd-hardware.info/?probe=d4be439e34) | Jan 24, 2024 |
| ASRock        | B660M-STX                   | Desktop     | [5ee66bbf7a](https://bsd-hardware.info/?probe=5ee66bbf7a) | Jan 23, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9c3c718fd6](https://bsd-hardware.info/?probe=9c3c718fd6) | Jan 22, 2024 |
| Intel         | D33217GKE G76540-205        | Desktop     | [a4e9b38ce9](https://bsd-hardware.info/?probe=a4e9b38ce9) | Jan 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [86b81c8374](https://bsd-hardware.info/?probe=86b81c8374) | Jan 19, 2024 |
| Dell          | Precision 7510              | Notebook    | [b5d52d8750](https://bsd-hardware.info/?probe=b5d52d8750) | Jan 16, 2024 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [d81973c8bc](https://bsd-hardware.info/?probe=d81973c8bc) | Jan 16, 2024 |
| Lenovo        | ThinkSystem ST50 V2 7D8J... | Desktop     | [8e68864915](https://bsd-hardware.info/?probe=8e68864915) | Jan 15, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [626aa9d90b](https://bsd-hardware.info/?probe=626aa9d90b) | Jan 14, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ded0ee10a9](https://bsd-hardware.info/?probe=ded0ee10a9) | Jan 14, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [cd134cd4b9](https://bsd-hardware.info/?probe=cd134cd4b9) | Jan 13, 2024 |
| PC Engines    | APU2                        | Desktop     | [3c3e3a1426](https://bsd-hardware.info/?probe=3c3e3a1426) | Jan 10, 2024 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a09dcb6d22](https://bsd-hardware.info/?probe=a09dcb6d22) | Jan 09, 2024 |
| HP            | Pavilion g7                 | Notebook    | [25ccdb00f6](https://bsd-hardware.info/?probe=25ccdb00f6) | Jan 09, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [69d3170ffd](https://bsd-hardware.info/?probe=69d3170ffd) | Jan 08, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [36ab1d27f9](https://bsd-hardware.info/?probe=36ab1d27f9) | Jan 07, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [965838c7b3](https://bsd-hardware.info/?probe=965838c7b3) | Jan 06, 2024 |
| Intel         | JSL MRD                     | Desktop     | [6405a13f96](https://bsd-hardware.info/?probe=6405a13f96) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [77d8cc2e7c](https://bsd-hardware.info/?probe=77d8cc2e7c) | Jan 02, 2024 |
| Dell          | Vostro V130                 | Notebook    | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [fe3a4e49ee](https://bsd-hardware.info/?probe=fe3a4e49ee) | Dec 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [f93ba42c7a](https://bsd-hardware.info/?probe=f93ba42c7a) | Dec 28, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [00abf2f109](https://bsd-hardware.info/?probe=00abf2f109) | Dec 27, 2023 |
| AZW           | Green G5                    | Desktop     | [a088cebb95](https://bsd-hardware.info/?probe=a088cebb95) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [f712f3c6c0](https://bsd-hardware.info/?probe=f712f3c6c0) | Dec 25, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [76495a4c85](https://bsd-hardware.info/?probe=76495a4c85) | Dec 22, 2023 |
| Lenovo        | ThinkSystem ST50 V2 7D8J... | Desktop     | [a5eedba370](https://bsd-hardware.info/?probe=a5eedba370) | Dec 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ad0f62cef1](https://bsd-hardware.info/?probe=ad0f62cef1) | Dec 18, 2023 |
| Intel         | JSL MRD                     | Desktop     | [29c4bae1f4](https://bsd-hardware.info/?probe=29c4bae1f4) | Dec 17, 2023 |
| ASRock        | IMB-181-L                   | Desktop     | [a81eb6eadf](https://bsd-hardware.info/?probe=a81eb6eadf) | Dec 15, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [306f9c1b03](https://bsd-hardware.info/?probe=306f9c1b03) | Dec 14, 2023 |
| Intel         | Luna Pier CRB Revision D    | Desktop     | [44215d3b22](https://bsd-hardware.info/?probe=44215d3b22) | Dec 13, 2023 |
| Intel         | Luna Pier CRB Revision D    | Desktop     | [e47e6d56e8](https://bsd-hardware.info/?probe=e47e6d56e8) | Dec 13, 2023 |
| Dell          | Latitude 7414               | Notebook    | [2d57c22982](https://bsd-hardware.info/?probe=2d57c22982) | Dec 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a6175a2d93](https://bsd-hardware.info/?probe=a6175a2d93) | Dec 05, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4c1bc19902](https://bsd-hardware.info/?probe=4c1bc19902) | Dec 03, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [ea8b5e1c14](https://bsd-hardware.info/?probe=ea8b5e1c14) | Dec 03, 2023 |
| Intel         | QHSW02                      | Desktop     | [00af22bad5](https://bsd-hardware.info/?probe=00af22bad5) | Dec 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [906bc578c7](https://bsd-hardware.info/?probe=906bc578c7) | Nov 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [933b042721](https://bsd-hardware.info/?probe=933b042721) | Nov 29, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ec250e722a](https://bsd-hardware.info/?probe=ec250e722a) | Nov 29, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6ae043723c](https://bsd-hardware.info/?probe=6ae043723c) | Nov 26, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bed6c30cd](https://bsd-hardware.info/?probe=1bed6c30cd) | Nov 22, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a37a33268d](https://bsd-hardware.info/?probe=a37a33268d) | Nov 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fb283e956a](https://bsd-hardware.info/?probe=fb283e956a) | Nov 21, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [2049a0d3db](https://bsd-hardware.info/?probe=2049a0d3db) | Nov 21, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [87466d5ec0](https://bsd-hardware.info/?probe=87466d5ec0) | Nov 21, 2023 |
| ASRock        | H470M-ITX/ac                | Desktop     | [e54ba21f70](https://bsd-hardware.info/?probe=e54ba21f70) | Nov 20, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [07766d29fd](https://bsd-hardware.info/?probe=07766d29fd) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [96562d6513](https://bsd-hardware.info/?probe=96562d6513) | Nov 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [5caaad73bd](https://bsd-hardware.info/?probe=5caaad73bd) | Nov 19, 2023 |
| MSI           | B560-A PRO                  | Desktop     | [cf9b5a14ce](https://bsd-hardware.info/?probe=cf9b5a14ce) | Nov 19, 2023 |
| Dell          | Latitude 5440               | Notebook    | [9daa44aacf](https://bsd-hardware.info/?probe=9daa44aacf) | Nov 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [8f162077aa](https://bsd-hardware.info/?probe=8f162077aa) | Nov 18, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [23b537c7a3](https://bsd-hardware.info/?probe=23b537c7a3) | Nov 16, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [823bdd1b43](https://bsd-hardware.info/?probe=823bdd1b43) | Nov 10, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3c3b2abb3d](https://bsd-hardware.info/?probe=3c3b2abb3d) | Nov 09, 2023 |
| Dell          | Precision 7560              | Notebook    | [a0e5297849](https://bsd-hardware.info/?probe=a0e5297849) | Nov 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [33d0fdd5bc](https://bsd-hardware.info/?probe=33d0fdd5bc) | Nov 07, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [36a87f24f7](https://bsd-hardware.info/?probe=36a87f24f7) | Nov 06, 2023 |
| Shuttle       | NC10U                       | Desktop     | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [7c9445a8f2](https://bsd-hardware.info/?probe=7c9445a8f2) | Oct 30, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [ff58ecae1d](https://bsd-hardware.info/?probe=ff58ecae1d) | Oct 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c2a5fe4d38](https://bsd-hardware.info/?probe=c2a5fe4d38) | Oct 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [04349022d0](https://bsd-hardware.info/?probe=04349022d0) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [d78f6f9dd2](https://bsd-hardware.info/?probe=d78f6f9dd2) | Oct 25, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [31fff3e92b](https://bsd-hardware.info/?probe=31fff3e92b) | Oct 21, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [30726f25a0](https://bsd-hardware.info/?probe=30726f25a0) | Oct 21, 2023 |
| Lenovo        | ThinkSystem ST50 V2 7D8J... | Desktop     | [b8cb4d78ac](https://bsd-hardware.info/?probe=b8cb4d78ac) | Oct 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0f3cd5aa25](https://bsd-hardware.info/?probe=0f3cd5aa25) | Oct 13, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [3842802079](https://bsd-hardware.info/?probe=3842802079) | Oct 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [814bbea3a1](https://bsd-hardware.info/?probe=814bbea3a1) | Oct 11, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [2ff1690bcd](https://bsd-hardware.info/?probe=2ff1690bcd) | Oct 05, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [c4dfb2a41b](https://bsd-hardware.info/?probe=c4dfb2a41b) | Oct 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0718d64bf8](https://bsd-hardware.info/?probe=0718d64bf8) | Oct 04, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [25fecdaad5](https://bsd-hardware.info/?probe=25fecdaad5) | Oct 03, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [dfb45f6202](https://bsd-hardware.info/?probe=dfb45f6202) | Sep 30, 2023 |
| Intel         | D33217GKE G76540-205        | Desktop     | [faef2ab5c6](https://bsd-hardware.info/?probe=faef2ab5c6) | Sep 28, 2023 |
| ASRock        | B760M-HDV/M.2 D4            | Desktop     | [886dc0272b](https://bsd-hardware.info/?probe=886dc0272b) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [312bc5d526](https://bsd-hardware.info/?probe=312bc5d526) | Sep 23, 2023 |
| Dell          | 0KP561                      | Desktop     | [cf15aea783](https://bsd-hardware.info/?probe=cf15aea783) | Sep 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [39e1d38287](https://bsd-hardware.info/?probe=39e1d38287) | Sep 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8229339c2f](https://bsd-hardware.info/?probe=8229339c2f) | Sep 12, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [f5f0e573fe](https://bsd-hardware.info/?probe=f5f0e573fe) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7af171368a](https://bsd-hardware.info/?probe=7af171368a) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [2cfdb7cfa9](https://bsd-hardware.info/?probe=2cfdb7cfa9) | Sep 08, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [d331bd9a11](https://bsd-hardware.info/?probe=d331bd9a11) | Sep 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [cbde759aa2](https://bsd-hardware.info/?probe=cbde759aa2) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [22ec8197cc](https://bsd-hardware.info/?probe=22ec8197cc) | Sep 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [516b89740b](https://bsd-hardware.info/?probe=516b89740b) | Sep 06, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [7c08d4cfb1](https://bsd-hardware.info/?probe=7c08d4cfb1) | Sep 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1bde5a65b6](https://bsd-hardware.info/?probe=1bde5a65b6) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [e4f0ac6bb9](https://bsd-hardware.info/?probe=e4f0ac6bb9) | Sep 03, 2023 |
| Lenovo        | ThinkPad X260 20F6006XUK    | Notebook    | [4bce25bd89](https://bsd-hardware.info/?probe=4bce25bd89) | Sep 03, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d4a4a46409](https://bsd-hardware.info/?probe=d4a4a46409) | Aug 31, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [bf4ed827a5](https://bsd-hardware.info/?probe=bf4ed827a5) | Aug 31, 2023 |
| HP            | 802F                        | Desktop     | [1f64f7e11f](https://bsd-hardware.info/?probe=1f64f7e11f) | Aug 30, 2023 |
| Getac         | V110G2                      | Notebook    | [884803a6bd](https://bsd-hardware.info/?probe=884803a6bd) | Aug 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66f982c40b](https://bsd-hardware.info/?probe=66f982c40b) | Aug 23, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [dcfa60a51c](https://bsd-hardware.info/?probe=dcfa60a51c) | Aug 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9e31a91e15](https://bsd-hardware.info/?probe=9e31a91e15) | Aug 16, 2023 |
| Lenovo        | ThinkPad T460p 20FXS06A1... | Notebook    | [378d093019](https://bsd-hardware.info/?probe=378d093019) | Aug 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bacf5acda2](https://bsd-hardware.info/?probe=bacf5acda2) | Aug 15, 2023 |
| Protectli     | VP2420                      | Desktop     | [53aac49eee](https://bsd-hardware.info/?probe=53aac49eee) | Aug 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [4176afcb0d](https://bsd-hardware.info/?probe=4176afcb0d) | Aug 13, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | Notebook    | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [418b98798e](https://bsd-hardware.info/?probe=418b98798e) | Aug 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [60d49b408a](https://bsd-hardware.info/?probe=60d49b408a) | Aug 09, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [891072999f](https://bsd-hardware.info/?probe=891072999f) | Aug 07, 2023 |
| HP            | 0AACh                       | Desktop     | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [0b5f437319](https://bsd-hardware.info/?probe=0b5f437319) | Aug 06, 2023 |
| Dell          | 0KP561                      | Desktop     | [bff2760640](https://bsd-hardware.info/?probe=bff2760640) | Aug 06, 2023 |
| Dell          | 07WP95 A02                  | Desktop     | [4213eff742](https://bsd-hardware.info/?probe=4213eff742) | Aug 05, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [f809d834df](https://bsd-hardware.info/?probe=f809d834df) | Aug 03, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Intel         | NUC11TNBi3 M11908-404       | Mini pc     | [54ab213a82](https://bsd-hardware.info/?probe=54ab213a82) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [dc86bf45ba](https://bsd-hardware.info/?probe=dc86bf45ba) | Jul 30, 2023 |
| AZW           | Green G5                    | Desktop     | [97f934a02c](https://bsd-hardware.info/?probe=97f934a02c) | Jul 25, 2023 |
| Intel         | SKYBAY                      | Desktop     | [0c64b8a9be](https://bsd-hardware.info/?probe=0c64b8a9be) | Jul 24, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [c4a85b9853](https://bsd-hardware.info/?probe=c4a85b9853) | Jul 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [0a4400e550](https://bsd-hardware.info/?probe=0a4400e550) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [916b2426e2](https://bsd-hardware.info/?probe=916b2426e2) | Jul 14, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5f5422b060](https://bsd-hardware.info/?probe=5f5422b060) | Jul 08, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [838746c38c](https://bsd-hardware.info/?probe=838746c38c) | Jul 01, 2023 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [6823b41760](https://bsd-hardware.info/?probe=6823b41760) | Jun 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [05925afd0a](https://bsd-hardware.info/?probe=05925afd0a) | Jun 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [74d372e7a4](https://bsd-hardware.info/?probe=74d372e7a4) | Jun 19, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c15bb7d984](https://bsd-hardware.info/?probe=c15bb7d984) | Jun 18, 2023 |
| Unknown       | ITX-M41E                    | Desktop     | [2e8c62d163](https://bsd-hardware.info/?probe=2e8c62d163) | Jun 16, 2023 |
| Unknown       | ITX-M41E                    | Desktop     | [671e67a42d](https://bsd-hardware.info/?probe=671e67a42d) | Jun 16, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [83c176517e](https://bsd-hardware.info/?probe=83c176517e) | Jun 11, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [1c8e1c1e80](https://bsd-hardware.info/?probe=1c8e1c1e80) | Jun 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [422b9d51a7](https://bsd-hardware.info/?probe=422b9d51a7) | Jun 06, 2023 |
| HP            | 3398                        | Desktop     | [980c0fc5a8](https://bsd-hardware.info/?probe=980c0fc5a8) | Jun 04, 2023 |
| Intel         | SKYBAY                      | Desktop     | [afe36b0540](https://bsd-hardware.info/?probe=afe36b0540) | Jun 04, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [d7f48dc5e3](https://bsd-hardware.info/?probe=d7f48dc5e3) | Jun 01, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3eebac6c6a](https://bsd-hardware.info/?probe=3eebac6c6a) | Jun 01, 2023 |
| ASRock        | H470M-ITX/ac                | Desktop     | [50b2ac1b5f](https://bsd-hardware.info/?probe=50b2ac1b5f) | Jun 01, 2023 |
| HP            | 212B                        | Desktop     | [4623e0c5b4](https://bsd-hardware.info/?probe=4623e0c5b4) | May 31, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b560671947](https://bsd-hardware.info/?probe=b560671947) | May 30, 2023 |
| Acer          | EG43M                       | Desktop     | [d58b8c242d](https://bsd-hardware.info/?probe=d58b8c242d) | May 29, 2023 |
| Unknown       | Unknown                     | Firewall    | [0183a5030d](https://bsd-hardware.info/?probe=0183a5030d) | May 29, 2023 |
| Dell          | System XPS L702X            | Notebook    | [f56d7090f9](https://bsd-hardware.info/?probe=f56d7090f9) | May 28, 2023 |
| YENTEK        | R250                        | Desktop     | [33ba1ec16a](https://bsd-hardware.info/?probe=33ba1ec16a) | May 26, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [05bd720b57](https://bsd-hardware.info/?probe=05bd720b57) | May 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [6ec9e0f7ab](https://bsd-hardware.info/?probe=6ec9e0f7ab) | May 25, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0c5fd49340](https://bsd-hardware.info/?probe=0c5fd49340) | May 25, 2023 |
| Dell          | System XPS L702X            | Notebook    | [857016be75](https://bsd-hardware.info/?probe=857016be75) | May 24, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b5f17b6bf8](https://bsd-hardware.info/?probe=b5f17b6bf8) | May 23, 2023 |
| Intel         | JSL MRD                     | Desktop     | [d1525b459c](https://bsd-hardware.info/?probe=d1525b459c) | May 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [93b82a3fdd](https://bsd-hardware.info/?probe=93b82a3fdd) | May 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6c9384395e](https://bsd-hardware.info/?probe=6c9384395e) | May 19, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [313796fd3e](https://bsd-hardware.info/?probe=313796fd3e) | May 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b39ccff319](https://bsd-hardware.info/?probe=b39ccff319) | May 15, 2023 |
| Alienware     | 17 R4                       | Notebook    | [df734c8e64](https://bsd-hardware.info/?probe=df734c8e64) | May 14, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [47800f4d42](https://bsd-hardware.info/?probe=47800f4d42) | May 14, 2023 |
| HP            | 802F                        | Desktop     | [fdf293f78f](https://bsd-hardware.info/?probe=fdf293f78f) | May 14, 2023 |
| PC Engines    | APU3                        | Desktop     | [2e7b6f8719](https://bsd-hardware.info/?probe=2e7b6f8719) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [769820bf96](https://bsd-hardware.info/?probe=769820bf96) | May 11, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [afbb775351](https://bsd-hardware.info/?probe=afbb775351) | May 10, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [ff40ba0d4c](https://bsd-hardware.info/?probe=ff40ba0d4c) | May 09, 2023 |
| Notebook      | N7x0WU                      | Notebook    | [7a646e185a](https://bsd-hardware.info/?probe=7a646e185a) | May 09, 2023 |
| PC Engines    | apu4                        | Desktop     | [3ce8b4290e](https://bsd-hardware.info/?probe=3ce8b4290e) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [73fa910249](https://bsd-hardware.info/?probe=73fa910249) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [f061353360](https://bsd-hardware.info/?probe=f061353360) | Apr 26, 2023 |
| ASRock        | H110M-ITX                   | Desktop     | [ed0c2c1af7](https://bsd-hardware.info/?probe=ed0c2c1af7) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7891ca8e09](https://bsd-hardware.info/?probe=7891ca8e09) | Apr 23, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [60f61f7ecb](https://bsd-hardware.info/?probe=60f61f7ecb) | Apr 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [5cd7c515c9](https://bsd-hardware.info/?probe=5cd7c515c9) | Apr 21, 2023 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [2701240671](https://bsd-hardware.info/?probe=2701240671) | Apr 21, 2023 |
| Dell          | Latitude 7410               | Notebook    | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Intel         | SKYBAY                      | Desktop     | [99dc2ee0d7](https://bsd-hardware.info/?probe=99dc2ee0d7) | Apr 18, 2023 |
| Deciso        | Netboard A10                | Desktop     | [d9bdae8a74](https://bsd-hardware.info/?probe=d9bdae8a74) | Apr 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [841a3fbc71](https://bsd-hardware.info/?probe=841a3fbc71) | Apr 10, 2023 |
| Kontron       | KT780/ATX 61810000          | Desktop     | [c7251f0149](https://bsd-hardware.info/?probe=c7251f0149) | Apr 10, 2023 |
| Intel         | SKYBAY                      | Desktop     | [39c55b0bdc](https://bsd-hardware.info/?probe=39c55b0bdc) | Apr 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0d8abb3ec9](https://bsd-hardware.info/?probe=0d8abb3ec9) | Apr 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [23e6ec0d94](https://bsd-hardware.info/?probe=23e6ec0d94) | Apr 05, 2023 |
| PC Engines    | APU2                        | Desktop     | [a6397d6f8f](https://bsd-hardware.info/?probe=a6397d6f8f) | Apr 02, 2023 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [2a7e5e0e71](https://bsd-hardware.info/?probe=2a7e5e0e71) | Apr 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [488b22a700](https://bsd-hardware.info/?probe=488b22a700) | Apr 01, 2023 |
| Intel         | SKYBAY                      | Desktop     | [bdce1ddf3e](https://bsd-hardware.info/?probe=bdce1ddf3e) | Apr 01, 2023 |
| MSI           | H81I                        | Desktop     | [b9d5bf4907](https://bsd-hardware.info/?probe=b9d5bf4907) | Apr 01, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [33ca458105](https://bsd-hardware.info/?probe=33ca458105) | Mar 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [9696e7d17f](https://bsd-hardware.info/?probe=9696e7d17f) | Mar 29, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7945f26073](https://bsd-hardware.info/?probe=7945f26073) | Mar 25, 2023 |
| Intel         | H81U                        | Notebook    | [af9a6469c9](https://bsd-hardware.info/?probe=af9a6469c9) | Mar 24, 2023 |
| Acer          | Revo 70                     | Desktop     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| MSI           | H81I                        | Desktop     | [4983a6a077](https://bsd-hardware.info/?probe=4983a6a077) | Mar 22, 2023 |
| HP            | 805A                        | Desktop     | [d90c74af40](https://bsd-hardware.info/?probe=d90c74af40) | Mar 21, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| MSI           | H81I                        | Desktop     | [a1981bf557](https://bsd-hardware.info/?probe=a1981bf557) | Mar 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [03cf8c47dc](https://bsd-hardware.info/?probe=03cf8c47dc) | Mar 17, 2023 |
| YENTEK        | R250                        | Desktop     | [fc42406b39](https://bsd-hardware.info/?probe=fc42406b39) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [25256b1698](https://bsd-hardware.info/?probe=25256b1698) | Mar 14, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [bc21ae472e](https://bsd-hardware.info/?probe=bc21ae472e) | Mar 13, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | Notebook    | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [ad6f854637](https://bsd-hardware.info/?probe=ad6f854637) | Mar 12, 2023 |
| Supermicro    | X11SSL-F                    | Server      | [c9ddd32406](https://bsd-hardware.info/?probe=c9ddd32406) | Mar 12, 2023 |
| Dell          | 07WP95 A02                  | Desktop     | [f45a92348a](https://bsd-hardware.info/?probe=f45a92348a) | Mar 12, 2023 |
| Dell          | Precision 7720              | Notebook    | [01f5f21b76](https://bsd-hardware.info/?probe=01f5f21b76) | Mar 12, 2023 |
| HP            | 3398                        | Desktop     | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3548f4efa2](https://bsd-hardware.info/?probe=3548f4efa2) | Mar 11, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [88de48013c](https://bsd-hardware.info/?probe=88de48013c) | Mar 10, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495 20NKS0HN1N    | Notebook    | [af190c38e9](https://bsd-hardware.info/?probe=af190c38e9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | Notebook    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [223879138d](https://bsd-hardware.info/?probe=223879138d) | Mar 10, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [e70d97f7d6](https://bsd-hardware.info/?probe=e70d97f7d6) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [8b3ad4e8b9](https://bsd-hardware.info/?probe=8b3ad4e8b9) | Mar 09, 2023 |
| Dell          | Latitude D620               | Notebook    | [d42a8ee079](https://bsd-hardware.info/?probe=d42a8ee079) | Mar 09, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [98fe8cc428](https://bsd-hardware.info/?probe=98fe8cc428) | Mar 09, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [3c5f826544](https://bsd-hardware.info/?probe=3c5f826544) | Mar 07, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2a6207fb45](https://bsd-hardware.info/?probe=2a6207fb45) | Mar 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8d052cbf4c](https://bsd-hardware.info/?probe=8d052cbf4c) | Mar 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8e9e9d3ce2](https://bsd-hardware.info/?probe=8e9e9d3ce2) | Mar 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Intel         | D510MO AAE76523-403         | Desktop     | [0da634580f](https://bsd-hardware.info/?probe=0da634580f) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| HP            | 1496                        | Desktop     | [f2acf09862](https://bsd-hardware.info/?probe=f2acf09862) | Mar 02, 2023 |
| HP            | 212B                        | Desktop     | [185934706d](https://bsd-hardware.info/?probe=185934706d) | Mar 02, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [9fa1054078](https://bsd-hardware.info/?probe=9fa1054078) | Mar 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6d1d3ded0d](https://bsd-hardware.info/?probe=6d1d3ded0d) | Feb 28, 2023 |
| HP            | 8055                        | Desktop     | [faadcd3e41](https://bsd-hardware.info/?probe=faadcd3e41) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [2ab690000c](https://bsd-hardware.info/?probe=2ab690000c) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [ae0dc68ba6](https://bsd-hardware.info/?probe=ae0dc68ba6) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [aef791947c](https://bsd-hardware.info/?probe=aef791947c) | Feb 23, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [3dae7e3ebb](https://bsd-hardware.info/?probe=3dae7e3ebb) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6669622646](https://bsd-hardware.info/?probe=6669622646) | Feb 23, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [d23ae47425](https://bsd-hardware.info/?probe=d23ae47425) | Feb 23, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fb908ee344](https://bsd-hardware.info/?probe=fb908ee344) | Feb 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3e1b050969](https://bsd-hardware.info/?probe=3e1b050969) | Feb 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d23b2cfe5a](https://bsd-hardware.info/?probe=d23b2cfe5a) | Feb 17, 2023 |
| HP            | 198E                        | Desktop     | [1f9a7e4f9b](https://bsd-hardware.info/?probe=1f9a7e4f9b) | Feb 17, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0f589ba9bf](https://bsd-hardware.info/?probe=0f589ba9bf) | Feb 16, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [95a8784d4a](https://bsd-hardware.info/?probe=95a8784d4a) | Feb 16, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [ffc9e123b4](https://bsd-hardware.info/?probe=ffc9e123b4) | Feb 14, 2023 |
| Dell          | OptiPlex 9020               | Desktop     | [0c8a5f8dfa](https://bsd-hardware.info/?probe=0c8a5f8dfa) | Feb 13, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [ba1b9f0010](https://bsd-hardware.info/?probe=ba1b9f0010) | Feb 12, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [4c4e675427](https://bsd-hardware.info/?probe=4c4e675427) | Feb 10, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [e376971bd6](https://bsd-hardware.info/?probe=e376971bd6) | Feb 09, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [5462140da0](https://bsd-hardware.info/?probe=5462140da0) | Feb 05, 2023 |
| HP            | 8350                        | Desktop     | [9ec1605295](https://bsd-hardware.info/?probe=9ec1605295) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [6096b00a0c](https://bsd-hardware.info/?probe=6096b00a0c) | Jan 29, 2023 |
| AMD           | Larne CRB                   | Desktop     | [8b9a301b47](https://bsd-hardware.info/?probe=8b9a301b47) | Jan 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [d36217b166](https://bsd-hardware.info/?probe=d36217b166) | Jan 26, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [0c75494953](https://bsd-hardware.info/?probe=0c75494953) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [dcc804a61f](https://bsd-hardware.info/?probe=dcc804a61f) | Jan 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9dd8d0184f](https://bsd-hardware.info/?probe=9dd8d0184f) | Jan 22, 2023 |
| Dell          | Precision 5540              | Notebook    | [683769b797](https://bsd-hardware.info/?probe=683769b797) | Jan 19, 2023 |
| Dell          | PowerEdge R710              | Desktop     | [720e99b25e](https://bsd-hardware.info/?probe=720e99b25e) | Jan 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7cbcb5b513](https://bsd-hardware.info/?probe=7cbcb5b513) | Jan 12, 2023 |
| Lenovo        | 3138                        | Desktop     | [14876c7561](https://bsd-hardware.info/?probe=14876c7561) | Jan 12, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [4014cc42ed](https://bsd-hardware.info/?probe=4014cc42ed) | Jan 08, 2023 |
| Lenovo        | ThinkStation D20 415575G    | Desktop     | [0a15d989e3](https://bsd-hardware.info/?probe=0a15d989e3) | Jan 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [0d13116822](https://bsd-hardware.info/?probe=0d13116822) | Jan 06, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3ff47d2ce0](https://bsd-hardware.info/?probe=3ff47d2ce0) | Jan 06, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [a9b3805c0b](https://bsd-hardware.info/?probe=a9b3805c0b) | Jan 01, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [334575b738](https://bsd-hardware.info/?probe=334575b738) | Dec 31, 2022 |
| Unknown       | Unknown                     | Firewall    | [72eaa7a90f](https://bsd-hardware.info/?probe=72eaa7a90f) | Dec 30, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [41094c24b2](https://bsd-hardware.info/?probe=41094c24b2) | Dec 27, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [d62deb9883](https://bsd-hardware.info/?probe=d62deb9883) | Dec 26, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [33c59c687d](https://bsd-hardware.info/?probe=33c59c687d) | Dec 24, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [7bd99b62ab](https://bsd-hardware.info/?probe=7bd99b62ab) | Dec 19, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [c233fa7d25](https://bsd-hardware.info/?probe=c233fa7d25) | Dec 18, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [abe21b9c9e](https://bsd-hardware.info/?probe=abe21b9c9e) | Dec 18, 2022 |
| MSI           | MS-98C8                     | Desktop     | [a6e45c8e5f](https://bsd-hardware.info/?probe=a6e45c8e5f) | Dec 17, 2022 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [11d5b82cdd](https://bsd-hardware.info/?probe=11d5b82cdd) | Dec 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [ce2b20b3a9](https://bsd-hardware.info/?probe=ce2b20b3a9) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0Y40... | Notebook    | [7463e05c88](https://bsd-hardware.info/?probe=7463e05c88) | Dec 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [342c99d07d](https://bsd-hardware.info/?probe=342c99d07d) | Dec 10, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbdd023e9](https://bsd-hardware.info/?probe=dbbdd023e9) | Dec 08, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [7bc1746333](https://bsd-hardware.info/?probe=7bc1746333) | Dec 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c953c78309](https://bsd-hardware.info/?probe=c953c78309) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [7f6194b56e](https://bsd-hardware.info/?probe=7f6194b56e) | Dec 07, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [218e00e7ea](https://bsd-hardware.info/?probe=218e00e7ea) | Dec 05, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [90279b62b7](https://bsd-hardware.info/?probe=90279b62b7) | Dec 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [54e89ef90b](https://bsd-hardware.info/?probe=54e89ef90b) | Dec 04, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [9497657cb2](https://bsd-hardware.info/?probe=9497657cb2) | Dec 04, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ddeb9befdf](https://bsd-hardware.info/?probe=ddeb9befdf) | Dec 03, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6a1a5865cb](https://bsd-hardware.info/?probe=6a1a5865cb) | Nov 30, 2022 |
| Panasonic     | CF-31-5                     | Notebook    | [7047afaaf4](https://bsd-hardware.info/?probe=7047afaaf4) | Nov 30, 2022 |
| Supermicro    | X10SRG-F                    | Desktop     | [66b7819b2a](https://bsd-hardware.info/?probe=66b7819b2a) | Nov 27, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [787a2db2cd](https://bsd-hardware.info/?probe=787a2db2cd) | Nov 26, 2022 |
| Dell          | 0W13NR A07                  | Server      | [c5b09b219b](https://bsd-hardware.info/?probe=c5b09b219b) | Nov 24, 2022 |
| Medion        | E15415                      | Notebook    | [e467080570](https://bsd-hardware.info/?probe=e467080570) | Nov 13, 2022 |
| Shuttle       | FS35V5                      | Mini pc     | [8b634987b4](https://bsd-hardware.info/?probe=8b634987b4) | Nov 13, 2022 |
| HP            | 806A                        | Desktop     | [9567b6949c](https://bsd-hardware.info/?probe=9567b6949c) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4adc5f7629](https://bsd-hardware.info/?probe=4adc5f7629) | Nov 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [47efa8b4bc](https://bsd-hardware.info/?probe=47efa8b4bc) | Nov 06, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [0312c464c4](https://bsd-hardware.info/?probe=0312c464c4) | Nov 05, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [655a9e7af2](https://bsd-hardware.info/?probe=655a9e7af2) | Nov 04, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [9c133326c9](https://bsd-hardware.info/?probe=9c133326c9) | Nov 03, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [14f174bd7c](https://bsd-hardware.info/?probe=14f174bd7c) | Oct 26, 2022 |
| Intel         | H81U                        | Notebook    | [b0e1f80338](https://bsd-hardware.info/?probe=b0e1f80338) | Oct 24, 2022 |
| Dell          | Precision M4500             | Notebook    | [66ded228ea](https://bsd-hardware.info/?probe=66ded228ea) | Oct 20, 2022 |
| ASUSTek       | E35M1-I DELUXE              | Desktop     | [2fdf1c6db6](https://bsd-hardware.info/?probe=2fdf1c6db6) | Oct 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e67cb3a0c5](https://bsd-hardware.info/?probe=e67cb3a0c5) | Oct 14, 2022 |
| HP            | 260 G3 DM                   | Desktop     | [3ad5292d71](https://bsd-hardware.info/?probe=3ad5292d71) | Oct 13, 2022 |
| HP            | Compaq nw8440 (RND39ET)     | Desktop     | [55bef385e3](https://bsd-hardware.info/?probe=55bef385e3) | Oct 13, 2022 |
| Intel         | H81U                        | Notebook    | [9b212d2264](https://bsd-hardware.info/?probe=9b212d2264) | Oct 13, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [5f271a82bf](https://bsd-hardware.info/?probe=5f271a82bf) | Oct 11, 2022 |
| Dell          | 0WC7KF A00                  | All in one  | [0f87a99ca7](https://bsd-hardware.info/?probe=0f87a99ca7) | Oct 11, 2022 |
| Lenovo        | 316E NOK                    | Mini pc     | [2a7c8f55cb](https://bsd-hardware.info/?probe=2a7c8f55cb) | Oct 10, 2022 |
| Clevo         | R130T                       | Desktop     | [6f8a6bf77c](https://bsd-hardware.info/?probe=6f8a6bf77c) | Oct 10, 2022 |
| Soekris En... | net6501                     | Desktop     | [1cb23f6bda](https://bsd-hardware.info/?probe=1cb23f6bda) | Oct 08, 2022 |
| Soekris En... | net6501                     | Desktop     | [03ee772b1f](https://bsd-hardware.info/?probe=03ee772b1f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [442a743538](https://bsd-hardware.info/?probe=442a743538) | Oct 08, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [31ce3d5e46](https://bsd-hardware.info/?probe=31ce3d5e46) | Oct 07, 2022 |
| Intel         | CRESCENTBAY                 | Desktop     | [36fb81bec0](https://bsd-hardware.info/?probe=36fb81bec0) | Oct 07, 2022 |
| PC Engines    | apu1                        | Desktop     | [1a8ff34d31](https://bsd-hardware.info/?probe=1a8ff34d31) | Oct 06, 2022 |
| Toshiba       | NB300                       | Notebook    | [c18ae50101](https://bsd-hardware.info/?probe=c18ae50101) | Oct 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e83d522905](https://bsd-hardware.info/?probe=e83d522905) | Oct 03, 2022 |
| Dell          | Precision M4500             | Notebook    | [6b987b43b1](https://bsd-hardware.info/?probe=6b987b43b1) | Oct 03, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [d3c50c8d60](https://bsd-hardware.info/?probe=d3c50c8d60) | Oct 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [16f6784862](https://bsd-hardware.info/?probe=16f6784862) | Sep 27, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b8db4655e5](https://bsd-hardware.info/?probe=b8db4655e5) | Sep 26, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [ae535b0b49](https://bsd-hardware.info/?probe=ae535b0b49) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8f4900d0e6](https://bsd-hardware.info/?probe=8f4900d0e6) | Sep 25, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [59886931c5](https://bsd-hardware.info/?probe=59886931c5) | Sep 24, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5029142d61](https://bsd-hardware.info/?probe=5029142d61) | Sep 22, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [1a754b2a9e](https://bsd-hardware.info/?probe=1a754b2a9e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | Desktop     | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [77727b5832](https://bsd-hardware.info/?probe=77727b5832) | Sep 14, 2022 |
| PC Engines    | APU2                        | Desktop     | [95ae240b55](https://bsd-hardware.info/?probe=95ae240b55) | Sep 13, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [130de630ad](https://bsd-hardware.info/?probe=130de630ad) | Sep 10, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4db37ff154](https://bsd-hardware.info/?probe=4db37ff154) | Sep 07, 2022 |
| AMD           | Larne CRB                   | Desktop     | [787a51fa78](https://bsd-hardware.info/?probe=787a51fa78) | Sep 03, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [525631a32f](https://bsd-hardware.info/?probe=525631a32f) | Aug 28, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d346cf971a](https://bsd-hardware.info/?probe=d346cf971a) | Aug 15, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [ab6603e750](https://bsd-hardware.info/?probe=ab6603e750) | Aug 13, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [649021e20c](https://bsd-hardware.info/?probe=649021e20c) | Aug 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [870dface68](https://bsd-hardware.info/?probe=870dface68) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [81441a97b2](https://bsd-hardware.info/?probe=81441a97b2) | Aug 06, 2022 |
| HP            | 3397                        | Desktop     | [6111a627d6](https://bsd-hardware.info/?probe=6111a627d6) | Aug 05, 2022 |
| AMD           | Larne CRB                   | Desktop     | [db094f95af](https://bsd-hardware.info/?probe=db094f95af) | Aug 04, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ac69a3ecef](https://bsd-hardware.info/?probe=ac69a3ecef) | Aug 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1b794b3563](https://bsd-hardware.info/?probe=1b794b3563) | Aug 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ac2fc150b](https://bsd-hardware.info/?probe=5ac2fc150b) | Aug 02, 2022 |
| HP            | 3397                        | Desktop     | [dac75fec6e](https://bsd-hardware.info/?probe=dac75fec6e) | Jul 31, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [0eaaa31106](https://bsd-hardware.info/?probe=0eaaa31106) | Jul 31, 2022 |
| Dell          | 0RH817 A00                  | Server      | [7d7740d447](https://bsd-hardware.info/?probe=7d7740d447) | Jul 30, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | Desktop     | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| AMD           | Larne CRB                   | Desktop     | [794541e833](https://bsd-hardware.info/?probe=794541e833) | Jul 29, 2022 |
| Dell          | 0M877N A02                  | Server      | [c1623d6f23](https://bsd-hardware.info/?probe=c1623d6f23) | Jul 26, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [81586f6d39](https://bsd-hardware.info/?probe=81586f6d39) | Jul 22, 2022 |
| Dell          | 0G7WYD A01                  | Server      | [ce43e9f067](https://bsd-hardware.info/?probe=ce43e9f067) | Jul 22, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [59c576a4ba](https://bsd-hardware.info/?probe=59c576a4ba) | Jul 22, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [3fe3a46a7a](https://bsd-hardware.info/?probe=3fe3a46a7a) | Jul 21, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [bbca74a96f](https://bsd-hardware.info/?probe=bbca74a96f) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [070ccc68f8](https://bsd-hardware.info/?probe=070ccc68f8) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [9e54e446ef](https://bsd-hardware.info/?probe=9e54e446ef) | Jul 14, 2022 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [d43e397f02](https://bsd-hardware.info/?probe=d43e397f02) | Jul 10, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [dca437b993](https://bsd-hardware.info/?probe=dca437b993) | Jul 01, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [6ce39c5e61](https://bsd-hardware.info/?probe=6ce39c5e61) | Jun 27, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ab2f42b567](https://bsd-hardware.info/?probe=ab2f42b567) | Jun 26, 2022 |
| Dell          | 0M877N A02                  | Server      | [c6f1ccfe6d](https://bsd-hardware.info/?probe=c6f1ccfe6d) | Jun 22, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | Desktop     | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [25d5a77b59](https://bsd-hardware.info/?probe=25d5a77b59) | Jun 17, 2022 |
| HP            | 86E9 A                      | Desktop     | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Alienware     | M18xR2                      | Notebook    | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4e0a906acb](https://bsd-hardware.info/?probe=4e0a906acb) | Jun 11, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [776a4892d0](https://bsd-hardware.info/?probe=776a4892d0) | Jun 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [56111732fd](https://bsd-hardware.info/?probe=56111732fd) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [aeec87e07f](https://bsd-hardware.info/?probe=aeec87e07f) | Jun 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [18215740d1](https://bsd-hardware.info/?probe=18215740d1) | Jun 05, 2022 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [f3ad761457](https://bsd-hardware.info/?probe=f3ad761457) | Jun 04, 2022 |
| Dell          | Latitude 7490               | Notebook    | [22224f46f4](https://bsd-hardware.info/?probe=22224f46f4) | Jun 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [138e9fdeb4](https://bsd-hardware.info/?probe=138e9fdeb4) | May 31, 2022 |
| Gigabyte      | Z690I AORUS ULTRA           | Desktop     | [9bacfc2b0e](https://bsd-hardware.info/?probe=9bacfc2b0e) | May 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [115de395dd](https://bsd-hardware.info/?probe=115de395dd) | May 17, 2022 |
| TUXEDO        | InfinityBook13V3            | Notebook    | [fd081a3636](https://bsd-hardware.info/?probe=fd081a3636) | May 17, 2022 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e8d2744812](https://bsd-hardware.info/?probe=e8d2744812) | May 12, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASRock        | A320M Pro4-F                | Desktop     | [f307756ddf](https://bsd-hardware.info/?probe=f307756ddf) | May 11, 2022 |
| Intel         | H81U                        | Notebook    | [550699602e](https://bsd-hardware.info/?probe=550699602e) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [6cf944b0ef](https://bsd-hardware.info/?probe=6cf944b0ef) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cf58c679ef](https://bsd-hardware.info/?probe=cf58c679ef) | May 08, 2022 |
| Intel         | H81U                        | Notebook    | [04646d1cc7](https://bsd-hardware.info/?probe=04646d1cc7) | May 05, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [5f9e266167](https://bsd-hardware.info/?probe=5f9e266167) | May 04, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7d4dd8ba29](https://bsd-hardware.info/?probe=7d4dd8ba29) | May 04, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [3481513b0f](https://bsd-hardware.info/?probe=3481513b0f) | May 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0d5b872ec1](https://bsd-hardware.info/?probe=0d5b872ec1) | May 02, 2022 |
| Dell          | Latitude 7490               | Notebook    | [03c97fe4d9](https://bsd-hardware.info/?probe=03c97fe4d9) | May 02, 2022 |
| Dell          | Precision 7730              | Notebook    | [bdb3e3d4ce](https://bsd-hardware.info/?probe=bdb3e3d4ce) | Apr 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [1586880dd7](https://bsd-hardware.info/?probe=1586880dd7) | Apr 30, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [86ade7ce4b](https://bsd-hardware.info/?probe=86ade7ce4b) | Apr 30, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [8fce57c9e4](https://bsd-hardware.info/?probe=8fce57c9e4) | Apr 25, 2022 |
| ASUSTek       | P5KR                        | Desktop     | [cf745ca0da](https://bsd-hardware.info/?probe=cf745ca0da) | Apr 23, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [875d6b2da3](https://bsd-hardware.info/?probe=875d6b2da3) | Apr 22, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [a278852381](https://bsd-hardware.info/?probe=a278852381) | Apr 21, 2022 |
| Dell          | 06JWJY A01                  | Desktop     | [16f4cc5d53](https://bsd-hardware.info/?probe=16f4cc5d53) | Apr 20, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [ab8aea2f5c](https://bsd-hardware.info/?probe=ab8aea2f5c) | Apr 17, 2022 |
| Dell          | Latitude E5450              | Notebook    | [ca5eb083f9](https://bsd-hardware.info/?probe=ca5eb083f9) | Apr 16, 2022 |
| Deciso        | Netboard A10                | Desktop     | [6e0b916230](https://bsd-hardware.info/?probe=6e0b916230) | Apr 16, 2022 |
| HP            | 86E9 A                      | Desktop     | [be43a8efde](https://bsd-hardware.info/?probe=be43a8efde) | Apr 14, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [4b981630d7](https://bsd-hardware.info/?probe=4b981630d7) | Apr 13, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [06720f3c57](https://bsd-hardware.info/?probe=06720f3c57) | Apr 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [e6ba291c2d](https://bsd-hardware.info/?probe=e6ba291c2d) | Apr 12, 2022 |
| Jetway        | 1.0                         | Desktop     | [ac2ab09363](https://bsd-hardware.info/?probe=ac2ab09363) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e208e9425](https://bsd-hardware.info/?probe=4e208e9425) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ded0d1a114](https://bsd-hardware.info/?probe=ded0d1a114) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [14a6449380](https://bsd-hardware.info/?probe=14a6449380) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [50833ab257](https://bsd-hardware.info/?probe=50833ab257) | Apr 07, 2022 |
| Sophos        | XG                          | Firewall    | [c98fff0cf2](https://bsd-hardware.info/?probe=c98fff0cf2) | Apr 06, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e44ebcb340](https://bsd-hardware.info/?probe=e44ebcb340) | Apr 06, 2022 |
| Deciso        | Netboard A20                | Notebook    | [0829d5a85d](https://bsd-hardware.info/?probe=0829d5a85d) | Apr 06, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [35dcbd74e9](https://bsd-hardware.info/?probe=35dcbd74e9) | Apr 05, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [946c8fd467](https://bsd-hardware.info/?probe=946c8fd467) | Apr 04, 2022 |
| PC Engines    | APU2                        | Desktop     | [5eb2e04d11](https://bsd-hardware.info/?probe=5eb2e04d11) | Apr 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [43cbc2ef2c](https://bsd-hardware.info/?probe=43cbc2ef2c) | Apr 02, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [c83fab9193](https://bsd-hardware.info/?probe=c83fab9193) | Apr 01, 2022 |
| Unknown       | Unknown                     | Firewall    | [b5c3949db8](https://bsd-hardware.info/?probe=b5c3949db8) | Mar 29, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [7a991e2f31](https://bsd-hardware.info/?probe=7a991e2f31) | Mar 24, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [acb99d63ce](https://bsd-hardware.info/?probe=acb99d63ce) | Mar 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [05a81cb5d5](https://bsd-hardware.info/?probe=05a81cb5d5) | Mar 22, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [483cf54bfc](https://bsd-hardware.info/?probe=483cf54bfc) | Mar 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d0946bc53f](https://bsd-hardware.info/?probe=d0946bc53f) | Mar 21, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d2ecb6259c](https://bsd-hardware.info/?probe=d2ecb6259c) | Mar 20, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [a4a1c8e5ca](https://bsd-hardware.info/?probe=a4a1c8e5ca) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b23ab09f52](https://bsd-hardware.info/?probe=b23ab09f52) | Mar 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [545e5ebfc9](https://bsd-hardware.info/?probe=545e5ebfc9) | Mar 18, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [b137b25594](https://bsd-hardware.info/?probe=b137b25594) | Mar 15, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [b652261bda](https://bsd-hardware.info/?probe=b652261bda) | Mar 14, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0a2a94839d](https://bsd-hardware.info/?probe=0a2a94839d) | Mar 13, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [e5c8017afb](https://bsd-hardware.info/?probe=e5c8017afb) | Mar 12, 2022 |
| Supermicro    | X11SDV-8C-TLN2F             | Server      | [e1fceaabc0](https://bsd-hardware.info/?probe=e1fceaabc0) | Mar 08, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3b77055bd4](https://bsd-hardware.info/?probe=3b77055bd4) | Mar 07, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [0051c86e4c](https://bsd-hardware.info/?probe=0051c86e4c) | Mar 07, 2022 |
| AAEON         | UP-CHT01 V0.4               | Desktop     | [9aaa7c7a32](https://bsd-hardware.info/?probe=9aaa7c7a32) | Mar 05, 2022 |
| Protectli     | VP2410                      | Desktop     | [1f650fc994](https://bsd-hardware.info/?probe=1f650fc994) | Mar 05, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [d73d3760ce](https://bsd-hardware.info/?probe=d73d3760ce) | Mar 04, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [a3611d42bc](https://bsd-hardware.info/?probe=a3611d42bc) | Mar 04, 2022 |
| PC Engines    | apu1                        | Desktop     | [177dc1fbc8](https://bsd-hardware.info/?probe=177dc1fbc8) | Mar 03, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [43bfceb19d](https://bsd-hardware.info/?probe=43bfceb19d) | Mar 02, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [4367711bff](https://bsd-hardware.info/?probe=4367711bff) | Mar 01, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0314f9200](https://bsd-hardware.info/?probe=b0314f9200) | Feb 26, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [7b19f71ce1](https://bsd-hardware.info/?probe=7b19f71ce1) | Feb 26, 2022 |
| PC Engines    | apu1                        | Desktop     | [d904aa7790](https://bsd-hardware.info/?probe=d904aa7790) | Feb 24, 2022 |
| Intel         | CARLOW                      | Desktop     | [d46b68cc28](https://bsd-hardware.info/?probe=d46b68cc28) | Feb 23, 2022 |
| HP            | 8169                        | Desktop     | [f449b4cd6c](https://bsd-hardware.info/?probe=f449b4cd6c) | Feb 23, 2022 |
| Dell          | 0W13NR A07                  | Server      | [22846d44fb](https://bsd-hardware.info/?probe=22846d44fb) | Feb 22, 2022 |
| Dell          | 0TY019 A00                  | Server      | [5f750e021e](https://bsd-hardware.info/?probe=5f750e021e) | Feb 20, 2022 |
| Intel         | CARLOW                      | Desktop     | [b64bf97293](https://bsd-hardware.info/?probe=b64bf97293) | Feb 19, 2022 |
| Dell          | 0782GW A00                  | Desktop     | [ef5cc6be72](https://bsd-hardware.info/?probe=ef5cc6be72) | Feb 17, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [18576ef86c](https://bsd-hardware.info/?probe=18576ef86c) | Feb 17, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [fbc24f90e5](https://bsd-hardware.info/?probe=fbc24f90e5) | Feb 17, 2022 |
| MSI           | MS-7253                     | Desktop     | [c4e971ea82](https://bsd-hardware.info/?probe=c4e971ea82) | Feb 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [df529a84b9](https://bsd-hardware.info/?probe=df529a84b9) | Feb 16, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [1e8904f4fc](https://bsd-hardware.info/?probe=1e8904f4fc) | Feb 15, 2022 |
| AMD           | X64                         | Desktop     | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [ee3a7740ec](https://bsd-hardware.info/?probe=ee3a7740ec) | Feb 13, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b77b926f9b](https://bsd-hardware.info/?probe=b77b926f9b) | Feb 13, 2022 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [09a6920a4f](https://bsd-hardware.info/?probe=09a6920a4f) | Feb 12, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [61c103f80d](https://bsd-hardware.info/?probe=61c103f80d) | Feb 11, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [4d8f19ba12](https://bsd-hardware.info/?probe=4d8f19ba12) | Feb 11, 2022 |
| Sophos        | XG                          | Firewall    | [31a8174933](https://bsd-hardware.info/?probe=31a8174933) | Feb 10, 2022 |
| Sophos        | XG                          | Firewall    | [365e4cfbea](https://bsd-hardware.info/?probe=365e4cfbea) | Feb 08, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [8342bcccf5](https://bsd-hardware.info/?probe=8342bcccf5) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [91b1ec3b93](https://bsd-hardware.info/?probe=91b1ec3b93) | Feb 06, 2022 |
| Deciso        | NetBoard-A20                | Notebook    | [a6b7d2d5e8](https://bsd-hardware.info/?probe=a6b7d2d5e8) | Feb 06, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [2accc42e21](https://bsd-hardware.info/?probe=2accc42e21) | Feb 06, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [9213769810](https://bsd-hardware.info/?probe=9213769810) | Feb 05, 2022 |
| BESSTAR Te... | GB7                         | Mini pc     | [00cabbe0bf](https://bsd-hardware.info/?probe=00cabbe0bf) | Feb 05, 2022 |
| Dell          | 0W13NR A07                  | Server      | [1582d0700a](https://bsd-hardware.info/?probe=1582d0700a) | Feb 03, 2022 |
| Deciso        | Netboard A20                | Notebook    | [8cd43fcfd1](https://bsd-hardware.info/?probe=8cd43fcfd1) | Feb 03, 2022 |
| Intel         | SKYBAY                      | Desktop     | [95c3231a3a](https://bsd-hardware.info/?probe=95c3231a3a) | Feb 03, 2022 |
| MSI           | MS-9A45 0A                  | Desktop     | [cfbfdf0e55](https://bsd-hardware.info/?probe=cfbfdf0e55) | Jan 31, 2022 |
| ASUSTek       | 1015PEM                     | Notebook    | [efea0efb2b](https://bsd-hardware.info/?probe=efea0efb2b) | Jan 31, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [ccda2302cf](https://bsd-hardware.info/?probe=ccda2302cf) | Jan 30, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [9dc53740a9](https://bsd-hardware.info/?probe=9dc53740a9) | Jan 29, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| AMD           | Larne CRB                   | Desktop     | [c6a85da1d5](https://bsd-hardware.info/?probe=c6a85da1d5) | Jan 28, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7a5d842d33](https://bsd-hardware.info/?probe=7a5d842d33) | Jan 27, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f1c7ee0712](https://bsd-hardware.info/?probe=f1c7ee0712) | Jan 26, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [5c58d01f2d](https://bsd-hardware.info/?probe=5c58d01f2d) | Jan 25, 2022 |
| RUNING        | B75M INTEL H3V              | Desktop     | [9a060df0a2](https://bsd-hardware.info/?probe=9a060df0a2) | Jan 23, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [cd745d6377](https://bsd-hardware.info/?probe=cd745d6377) | Jan 23, 2022 |
| AMD           | Larne CRB                   | Desktop     | [6c37b91111](https://bsd-hardware.info/?probe=6c37b91111) | Jan 22, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [b01e6eb706](https://bsd-hardware.info/?probe=b01e6eb706) | Jan 22, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3dead218e1](https://bsd-hardware.info/?probe=3dead218e1) | Jan 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [6baaab27fd](https://bsd-hardware.info/?probe=6baaab27fd) | Jan 15, 2022 |
| MSI           | MS-98C8                     | Desktop     | [0102557f05](https://bsd-hardware.info/?probe=0102557f05) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [7062b84459](https://bsd-hardware.info/?probe=7062b84459) | Jan 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [1ff4a66d03](https://bsd-hardware.info/?probe=1ff4a66d03) | Jan 12, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [42eb986a58](https://bsd-hardware.info/?probe=42eb986a58) | Jan 11, 2022 |
| Dell          | Latitude E5450              | Notebook    | [a05fbe1c26](https://bsd-hardware.info/?probe=a05fbe1c26) | Jan 05, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c2ef231757](https://bsd-hardware.info/?probe=c2ef231757) | Jan 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [6aeb9adadb](https://bsd-hardware.info/?probe=6aeb9adadb) | Dec 31, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [b6139f57b9](https://bsd-hardware.info/?probe=b6139f57b9) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | Notebook    | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8c3181ee8d](https://bsd-hardware.info/?probe=8c3181ee8d) | Dec 29, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [07221fc111](https://bsd-hardware.info/?probe=07221fc111) | Dec 28, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cdb5578df8](https://bsd-hardware.info/?probe=cdb5578df8) | Dec 27, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [62b94dd372](https://bsd-hardware.info/?probe=62b94dd372) | Dec 21, 2021 |
| Samsung       | R720                        | Notebook    | [620195d4aa](https://bsd-hardware.info/?probe=620195d4aa) | Dec 20, 2021 |
| HP            | Compaq 15                   | Notebook    | [1e8b1ce39b](https://bsd-hardware.info/?probe=1e8b1ce39b) | Dec 20, 2021 |
| Supermicro    | X11SSL-F                    | Server      | [a5a440a7a7](https://bsd-hardware.info/?probe=a5a440a7a7) | Dec 20, 2021 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [124ac672b0](https://bsd-hardware.info/?probe=124ac672b0) | Dec 20, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [4147a5824d](https://bsd-hardware.info/?probe=4147a5824d) | Dec 16, 2021 |
| HP            | ProBook 650 G5              | Notebook    | [d4ffc24c6f](https://bsd-hardware.info/?probe=d4ffc24c6f) | Dec 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [225298bcd6](https://bsd-hardware.info/?probe=225298bcd6) | Dec 12, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [26220d3f14](https://bsd-hardware.info/?probe=26220d3f14) | Dec 09, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [eb69e83fbf](https://bsd-hardware.info/?probe=eb69e83fbf) | Dec 09, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [61312aa506](https://bsd-hardware.info/?probe=61312aa506) | Nov 30, 2021 |
| Dell          | VEP-4600-V930 034R2CA03     | Desktop     | [313d1b7032](https://bsd-hardware.info/?probe=313d1b7032) | Nov 25, 2021 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [9e7a72d920](https://bsd-hardware.info/?probe=9e7a72d920) | Nov 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [16206960c4](https://bsd-hardware.info/?probe=16206960c4) | Nov 24, 2021 |
| HP            | 3031h                       | Desktop     | [056352a663](https://bsd-hardware.info/?probe=056352a663) | Nov 21, 2021 |
| RUNING        | B75M INTEL H3V              | Desktop     | [5cfcc8c5f8](https://bsd-hardware.info/?probe=5cfcc8c5f8) | Nov 13, 2021 |
| HP            | 3031h                       | Desktop     | [d63bbcfceb](https://bsd-hardware.info/?probe=d63bbcfceb) | Oct 31, 2021 |
| HP            | 3031h                       | Desktop     | [c5e39a5e6d](https://bsd-hardware.info/?probe=c5e39a5e6d) | Oct 31, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e2db09bacb](https://bsd-hardware.info/?probe=e2db09bacb) | Oct 30, 2021 |
| ASRockRack    | C3558D4I-4L                 | Desktop     | [dfba84ce5a](https://bsd-hardware.info/?probe=dfba84ce5a) | Oct 29, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e2167afc3b](https://bsd-hardware.info/?probe=e2167afc3b) | Oct 25, 2021 |
| BESSTAR Te... | VB9                         | All in one  | [ac1f5a3339](https://bsd-hardware.info/?probe=ac1f5a3339) | Oct 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3f5b148e23](https://bsd-hardware.info/?probe=3f5b148e23) | Oct 22, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [6f019f05b6](https://bsd-hardware.info/?probe=6f019f05b6) | Oct 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [4b8fb7992f](https://bsd-hardware.info/?probe=4b8fb7992f) | Oct 16, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [c5226ff226](https://bsd-hardware.info/?probe=c5226ff226) | Oct 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [e53866a5d9](https://bsd-hardware.info/?probe=e53866a5d9) | Oct 11, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [be9d90602d](https://bsd-hardware.info/?probe=be9d90602d) | Oct 11, 2021 |
| Dell          | 04JN2K A04                  | Server      | [f529f87cea](https://bsd-hardware.info/?probe=f529f87cea) | Oct 11, 2021 |
| Dell          | 0V52N7 A00                  | Server      | [4ad37c1848](https://bsd-hardware.info/?probe=4ad37c1848) | Oct 10, 2021 |
| Google        | Terra                       | Notebook    | [9ba239a4a3](https://bsd-hardware.info/?probe=9ba239a4a3) | Oct 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [2fd62acb45](https://bsd-hardware.info/?probe=2fd62acb45) | Oct 10, 2021 |
| Lenovo        | 3138                        | Desktop     | [8b5cf892d0](https://bsd-hardware.info/?probe=8b5cf892d0) | Oct 04, 2021 |
| Lenovo        | ThinkPad X220 4290W42       | Notebook    | [8be5183e21](https://bsd-hardware.info/?probe=8be5183e21) | Sep 25, 2021 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [88b86ecf8b](https://bsd-hardware.info/?probe=88b86ecf8b) | Sep 25, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [5b7623f03b](https://bsd-hardware.info/?probe=5b7623f03b) | Sep 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [1b8ce81945](https://bsd-hardware.info/?probe=1b8ce81945) | Sep 19, 2021 |
| MSI           | P65 Creator 8RE             | Notebook    | [2684b5021c](https://bsd-hardware.info/?probe=2684b5021c) | Sep 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [8611fbfd97](https://bsd-hardware.info/?probe=8611fbfd97) | Sep 14, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [5f78c3411f](https://bsd-hardware.info/?probe=5f78c3411f) | Sep 13, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [cfc7818691](https://bsd-hardware.info/?probe=cfc7818691) | Sep 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [d5750a95a4](https://bsd-hardware.info/?probe=d5750a95a4) | Sep 08, 2021 |
| Packard Be... | imedia S2110A               | Desktop     | [d62a38660c](https://bsd-hardware.info/?probe=d62a38660c) | Sep 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [29cfd33c5e](https://bsd-hardware.info/?probe=29cfd33c5e) | Sep 06, 2021 |
| ASUSTek       | P8B-X series                | Server      | [1e7d58cd40](https://bsd-hardware.info/?probe=1e7d58cd40) | Aug 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d028fc63d4](https://bsd-hardware.info/?probe=d028fc63d4) | Aug 29, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [827c50f77b](https://bsd-hardware.info/?probe=827c50f77b) | Aug 28, 2021 |
| Dell          | 0G3HR7 A00                  | Desktop     | [7f75f30b75](https://bsd-hardware.info/?probe=7f75f30b75) | Aug 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [76f004bd26](https://bsd-hardware.info/?probe=76f004bd26) | Aug 26, 2021 |
| PC Engines    | APU2                        | Desktop     | [0a35da2af7](https://bsd-hardware.info/?probe=0a35da2af7) | Aug 24, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3e088c942b](https://bsd-hardware.info/?probe=3e088c942b) | Aug 22, 2021 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [51b5325c85](https://bsd-hardware.info/?probe=51b5325c85) | Aug 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [1dd499d54c](https://bsd-hardware.info/?probe=1dd499d54c) | Aug 12, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [11526a150b](https://bsd-hardware.info/?probe=11526a150b) | Aug 10, 2021 |
| Shuttle       | FS61                        | Desktop     | [b1fbaa8a6b](https://bsd-hardware.info/?probe=b1fbaa8a6b) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bb65c30be3](https://bsd-hardware.info/?probe=bb65c30be3) | Aug 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [9e0c8e8024](https://bsd-hardware.info/?probe=9e0c8e8024) | Aug 07, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [5f9c53366b](https://bsd-hardware.info/?probe=5f9c53366b) | Aug 05, 2021 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [b9ef180b73](https://bsd-hardware.info/?probe=b9ef180b73) | Aug 04, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [3ff984316b](https://bsd-hardware.info/?probe=3ff984316b) | Aug 04, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [2ce00e9f6b](https://bsd-hardware.info/?probe=2ce00e9f6b) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2a1251b320](https://bsd-hardware.info/?probe=2a1251b320) | Aug 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [34d448e1d1](https://bsd-hardware.info/?probe=34d448e1d1) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [846b6cca20](https://bsd-hardware.info/?probe=846b6cca20) | Jul 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [8aaf18daa1](https://bsd-hardware.info/?probe=8aaf18daa1) | Jul 28, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [d15eff8bcc](https://bsd-hardware.info/?probe=d15eff8bcc) | Jul 21, 2021 |
| ASRock        | D1800B-ITX                  | Desktop     | [4831cc5183](https://bsd-hardware.info/?probe=4831cc5183) | Jul 21, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [2484df8d38](https://bsd-hardware.info/?probe=2484df8d38) | Jul 18, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [0a3b5c9c27](https://bsd-hardware.info/?probe=0a3b5c9c27) | Jul 12, 2021 |
| HP            | 2B4B                        | Desktop     | [456625c82f](https://bsd-hardware.info/?probe=456625c82f) | Jul 04, 2021 |
| Notebook      | W510LU                      | Notebook    | [3d6de69bda](https://bsd-hardware.info/?probe=3d6de69bda) | Jul 02, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [1e66c42238](https://bsd-hardware.info/?probe=1e66c42238) | Jul 02, 2021 |
| Shuttle       | NC10U                       | Desktop     | [5d2d20dd04](https://bsd-hardware.info/?probe=5d2d20dd04) | Jul 02, 2021 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [7ae63d4c6c](https://bsd-hardware.info/?probe=7ae63d4c6c) | Jun 27, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [661d3349cb](https://bsd-hardware.info/?probe=661d3349cb) | Jun 26, 2021 |
| Dell          | Vostro 5481                 | Notebook    | [bb318fbc50](https://bsd-hardware.info/?probe=bb318fbc50) | Jun 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [95b0c9a6a3](https://bsd-hardware.info/?probe=95b0c9a6a3) | Jun 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [6ea6f6ffe7](https://bsd-hardware.info/?probe=6ea6f6ffe7) | Jun 20, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [8f336c0fa3](https://bsd-hardware.info/?probe=8f336c0fa3) | Jun 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [dc619f203f](https://bsd-hardware.info/?probe=dc619f203f) | Jun 19, 2021 |
| ASRock        | H110M-ITX                   | Desktop     | [124c75ba7c](https://bsd-hardware.info/?probe=124c75ba7c) | Jun 17, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [007ce2b6ce](https://bsd-hardware.info/?probe=007ce2b6ce) | Jun 17, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [e6cbfc417b](https://bsd-hardware.info/?probe=e6cbfc417b) | Jun 10, 2021 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [e54175f99f](https://bsd-hardware.info/?probe=e54175f99f) | Jun 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [b60f4a19ee](https://bsd-hardware.info/?probe=b60f4a19ee) | Jun 06, 2021 |
| Dell          | 0TY019 A01                  | Server      | [411477e260](https://bsd-hardware.info/?probe=411477e260) | Jun 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [24f3dbd372](https://bsd-hardware.info/?probe=24f3dbd372) | Jun 04, 2021 |
| Shuttle       | FS35V5                      | Mini pc     | [bfd71efa3b](https://bsd-hardware.info/?probe=bfd71efa3b) | May 31, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [cec18015ba](https://bsd-hardware.info/?probe=cec18015ba) | May 30, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [193936b5ca](https://bsd-hardware.info/?probe=193936b5ca) | May 30, 2021 |
| Lenovo        | ThinkPad T450s 20BWS0L60... | Notebook    | [ac567bd12d](https://bsd-hardware.info/?probe=ac567bd12d) | May 28, 2021 |
| Lenovo        | ThinkPad A485 20MVS0FD00    | Notebook    | [2f1ba02130](https://bsd-hardware.info/?probe=2f1ba02130) | May 28, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [16f36a045f](https://bsd-hardware.info/?probe=16f36a045f) | May 26, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [7c8c842fa7](https://bsd-hardware.info/?probe=7c8c842fa7) | May 24, 2021 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [3e650be93d](https://bsd-hardware.info/?probe=3e650be93d) | May 24, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [aafc52d6a1](https://bsd-hardware.info/?probe=aafc52d6a1) | May 24, 2021 |
| Google        | Guado                       | Desktop     | [54f01f821d](https://bsd-hardware.info/?probe=54f01f821d) | May 21, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [c471a8f2fe](https://bsd-hardware.info/?probe=c471a8f2fe) | May 16, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [3468faf656](https://bsd-hardware.info/?probe=3468faf656) | May 07, 2021 |
| ASRockRack    | X470D4U                     | Desktop     | [421da89770](https://bsd-hardware.info/?probe=421da89770) | May 06, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87e5651fd1](https://bsd-hardware.info/?probe=87e5651fd1) | May 06, 2021 |
| PC Engines    | APU2                        | Desktop     | [c99a0b0e4d](https://bsd-hardware.info/?probe=c99a0b0e4d) | May 05, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [e930fac60b](https://bsd-hardware.info/?probe=e930fac60b) | May 05, 2021 |
| Supermicro    | X8STi                       | Desktop     | [c615ef1edf](https://bsd-hardware.info/?probe=c615ef1edf) | May 04, 2021 |
| ASUSTek       | Rampage II GENE             | Desktop     | [4eac97c85c](https://bsd-hardware.info/?probe=4eac97c85c) | May 04, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [7c642e5e7d](https://bsd-hardware.info/?probe=7c642e5e7d) | Apr 30, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [2e2e69cb9e](https://bsd-hardware.info/?probe=2e2e69cb9e) | Apr 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [4368de8d34](https://bsd-hardware.info/?probe=4368de8d34) | Apr 28, 2021 |
| PC Engines    | APU3                        | Desktop     | [1d6ca07c5a](https://bsd-hardware.info/?probe=1d6ca07c5a) | Apr 27, 2021 |
| PC Engines    | APU3                        | Desktop     | [8fc426b107](https://bsd-hardware.info/?probe=8fc426b107) | Apr 22, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e262812b4d](https://bsd-hardware.info/?probe=e262812b4d) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [2c985c22ef](https://bsd-hardware.info/?probe=2c985c22ef) | Apr 10, 2021 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [4ff3fa22ff](https://bsd-hardware.info/?probe=4ff3fa22ff) | Apr 07, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [354dc80671](https://bsd-hardware.info/?probe=354dc80671) | Apr 07, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7901474a09](https://bsd-hardware.info/?probe=7901474a09) | Apr 07, 2021 |
| PC Engines    | apu4                        | Desktop     | [160a01d9e1](https://bsd-hardware.info/?probe=160a01d9e1) | Apr 03, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [f3b6d4d5c4](https://bsd-hardware.info/?probe=f3b6d4d5c4) | Apr 03, 2021 |
| ASUSTek       | P8B-X series                | Server      | [f60388bf6a](https://bsd-hardware.info/?probe=f60388bf6a) | Apr 03, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [7031b0ed1e](https://bsd-hardware.info/?probe=7031b0ed1e) | Mar 31, 2021 |
| PC Engines    | APU2                        | Desktop     | [97554df75d](https://bsd-hardware.info/?probe=97554df75d) | Mar 30, 2021 |
| Lenovo        | ThinkPad X220 4290EE8       | Notebook    | [f46976d85d](https://bsd-hardware.info/?probe=f46976d85d) | Mar 29, 2021 |
| Lenovo        | ThinkPad T490 20N20009FR    | Notebook    | [e1f691ac78](https://bsd-hardware.info/?probe=e1f691ac78) | Mar 29, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [dec8aa97f5](https://bsd-hardware.info/?probe=dec8aa97f5) | Mar 26, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [83ed58b4d0](https://bsd-hardware.info/?probe=83ed58b4d0) | Mar 26, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [e789c55f2e](https://bsd-hardware.info/?probe=e789c55f2e) | Mar 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3cb0e979f8](https://bsd-hardware.info/?probe=3cb0e979f8) | Mar 26, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [0263b0e32e](https://bsd-hardware.info/?probe=0263b0e32e) | Mar 26, 2021 |
| Lenovo        | 3138                        | Desktop     | [f12dd68efb](https://bsd-hardware.info/?probe=f12dd68efb) | Mar 25, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [68354c00cf](https://bsd-hardware.info/?probe=68354c00cf) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [bef38bd379](https://bsd-hardware.info/?probe=bef38bd379) | Mar 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [650f6a1b70](https://bsd-hardware.info/?probe=650f6a1b70) | Mar 21, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [183ac9b791](https://bsd-hardware.info/?probe=183ac9b791) | Mar 17, 2021 |
| Dell          | Inspiron 7566               | Notebook    | [b4a35aa7b0](https://bsd-hardware.info/?probe=b4a35aa7b0) | Mar 17, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [c0df245c1b](https://bsd-hardware.info/?probe=c0df245c1b) | Mar 13, 2021 |
| SECO          | UDOO x86                    | Notebook    | [f8310915b6](https://bsd-hardware.info/?probe=f8310915b6) | Mar 13, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [565343b334](https://bsd-hardware.info/?probe=565343b334) | Mar 13, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [24b657e7ba](https://bsd-hardware.info/?probe=24b657e7ba) | Mar 12, 2021 |
| Dell          | 05XKKK A05                  | Server      | [d3fe07511a](https://bsd-hardware.info/?probe=d3fe07511a) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [bbcc01d2ce](https://bsd-hardware.info/?probe=bbcc01d2ce) | Mar 11, 2021 |
| MSI           | B360M BAZOOKA               | Desktop     | [17a763a917](https://bsd-hardware.info/?probe=17a763a917) | Mar 11, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [835842d361](https://bsd-hardware.info/?probe=835842d361) | Mar 10, 2021 |
| Lenovo        | ThinkPad T400 6475P1G       | Notebook    | [6a0907b5e8](https://bsd-hardware.info/?probe=6a0907b5e8) | Mar 06, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [17ed006376](https://bsd-hardware.info/?probe=17ed006376) | Mar 05, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [9468eeef92](https://bsd-hardware.info/?probe=9468eeef92) | Mar 04, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [fc655524ab](https://bsd-hardware.info/?probe=fc655524ab) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [de98cd5952](https://bsd-hardware.info/?probe=de98cd5952) | Mar 04, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [03c5808adf](https://bsd-hardware.info/?probe=03c5808adf) | Mar 04, 2021 |
| Dell          | Latitude 5280               | Notebook    | [b84364959d](https://bsd-hardware.info/?probe=b84364959d) | Mar 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [1f226262cc](https://bsd-hardware.info/?probe=1f226262cc) | Mar 04, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [e056f1c77c](https://bsd-hardware.info/?probe=e056f1c77c) | Mar 03, 2021 |
| HP            | 86E9 A                      | Desktop     | [215398b88f](https://bsd-hardware.info/?probe=215398b88f) | Feb 28, 2021 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | Notebook    | [9bdf9ecec8](https://bsd-hardware.info/?probe=9bdf9ecec8) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b1f1b3cd82](https://bsd-hardware.info/?probe=b1f1b3cd82) | Feb 22, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [929bda8001](https://bsd-hardware.info/?probe=929bda8001) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Acer          | EG43M                       | Desktop     | [22552918ee](https://bsd-hardware.info/?probe=22552918ee) | Feb 21, 2021 |
| Gigabyte      | P15FR7                      | Notebook    | [c65b4d297a](https://bsd-hardware.info/?probe=c65b4d297a) | Feb 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Supermicro    | X9DRT                       | Server      | [a3bcb2fcf1](https://bsd-hardware.info/?probe=a3bcb2fcf1) | Feb 18, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [261756a327](https://bsd-hardware.info/?probe=261756a327) | Feb 17, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5d39657098](https://bsd-hardware.info/?probe=5d39657098) | Feb 14, 2021 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [4f646f53e9](https://bsd-hardware.info/?probe=4f646f53e9) | Feb 14, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | Notebook    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ba7f82b343](https://bsd-hardware.info/?probe=ba7f82b343) | Feb 12, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [5781a8b561](https://bsd-hardware.info/?probe=5781a8b561) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| PC Engines    | APU                         | Desktop     | [282a9596c6](https://bsd-hardware.info/?probe=282a9596c6) | Feb 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Dell          | 0H28RR A02                  | Server      | [0bbf4a51bb](https://bsd-hardware.info/?probe=0bbf4a51bb) | Feb 10, 2021 |
| Dell          | 0H28RR A02                  | Server      | [eaac725443](https://bsd-hardware.info/?probe=eaac725443) | Feb 10, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Dell          | Latitude E6230              | Notebook    | [696e95fc08](https://bsd-hardware.info/?probe=696e95fc08) | Feb 10, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [94bcab24a8](https://bsd-hardware.info/?probe=94bcab24a8) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | Notebook    | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| PC Engines    | APU3                        | Desktop     | [e21438c3cc](https://bsd-hardware.info/?probe=e21438c3cc) | Feb 07, 2021 |
| Lenovo        | ThinkPad T420 42368A3       | Notebook    | [5d7840d28e](https://bsd-hardware.info/?probe=5d7840d28e) | Feb 07, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| MSI           | Z77A-G41                    | Desktop     | [35bae50659](https://bsd-hardware.info/?probe=35bae50659) | Feb 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [8ef7071a3f](https://bsd-hardware.info/?probe=8ef7071a3f) | Feb 04, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [857c5aade9](https://bsd-hardware.info/?probe=857c5aade9) | Feb 04, 2021 |
| CompuLab      | fitlet2                     | Mini pc     | [7ff0034c98](https://bsd-hardware.info/?probe=7ff0034c98) | Feb 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [b005d61a99](https://bsd-hardware.info/?probe=b005d61a99) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [f66ccf2f33](https://bsd-hardware.info/?probe=f66ccf2f33) | Feb 03, 2021 |
| MSI           | MS-9A45 0A                  | Desktop     | [c384535b6f](https://bsd-hardware.info/?probe=c384535b6f) | Feb 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a7494d60a5](https://bsd-hardware.info/?probe=a7494d60a5) | Jan 31, 2021 |
| Dell          | 0JD6X3 A05                  | Server      | [27a3bb8503](https://bsd-hardware.info/?probe=27a3bb8503) | Jan 31, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [c8af335c01](https://bsd-hardware.info/?probe=c8af335c01) | Jan 29, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [dae16641bb](https://bsd-hardware.info/?probe=dae16641bb) | Jan 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c4d549584](https://bsd-hardware.info/?probe=4c4d549584) | Jan 22, 2021 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [80edc8dae6](https://bsd-hardware.info/?probe=80edc8dae6) | Jan 22, 2021 |
| PC Engines    | apu4                        | Desktop     | [3507544d2e](https://bsd-hardware.info/?probe=3507544d2e) | Jan 20, 2021 |
| Lenovo        | ThinkPad P50 20EQS0U60C     | Notebook    | [d8cf9e878e](https://bsd-hardware.info/?probe=d8cf9e878e) | Jan 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [f7c32488e9](https://bsd-hardware.info/?probe=f7c32488e9) | Jan 15, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [06cbb5cd5f](https://bsd-hardware.info/?probe=06cbb5cd5f) | Jan 15, 2021 |
| Dell          | Latitude 5280               | Notebook    | [c9bfb73262](https://bsd-hardware.info/?probe=c9bfb73262) | Jan 15, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Lenovo        | ThinkCentre M93p 10A8S0C... | Desktop     | [36ef631bfe](https://bsd-hardware.info/?probe=36ef631bfe) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| ASUSTek       | X102BA                      | Notebook    | [893b9111c6](https://bsd-hardware.info/?probe=893b9111c6) | Dec 27, 2020 |
| Gigabyte      | X79-UD3                     | Desktop     | [a8baf509d9](https://bsd-hardware.info/?probe=a8baf509d9) | Dec 26, 2020 |
| Apple         | PowerBook5,8                | Notebook    | [96f550a537](https://bsd-hardware.info/?probe=96f550a537) | Dec 24, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d13e0a1749](https://bsd-hardware.info/?probe=d13e0a1749) | Dec 15, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [2544123f79](https://bsd-hardware.info/?probe=2544123f79) | Dec 06, 2020 |
| Dell          | Latitude 5280               | Notebook    | [d1be72cc7e](https://bsd-hardware.info/?probe=d1be72cc7e) | Nov 21, 2020 |
| Dell          | Latitude 5280               | Notebook    | [fd4e8756b4](https://bsd-hardware.info/?probe=fd4e8756b4) | Nov 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9b6b24708e](https://bsd-hardware.info/?probe=9b6b24708e) | Nov 03, 2020 |
| Dell          | 03X6X0 A03                  | Server      | [7d7b8ca054](https://bsd-hardware.info/?probe=7d7b8ca054) | Oct 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7c8972f650](https://bsd-hardware.info/?probe=7c8972f650) | Oct 29, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [1d5bd18d14](https://bsd-hardware.info/?probe=1d5bd18d14) | Oct 29, 2020 |
| Supermicro    | X8STi                       | Desktop     | [1b64902781](https://bsd-hardware.info/?probe=1b64902781) | Oct 26, 2020 |
| AZW           | Z83 II                      | Desktop     | [9416876f20](https://bsd-hardware.info/?probe=9416876f20) | Oct 24, 2020 |
| AZW           | Z83 II                      | Desktop     | [19b1b4d85d](https://bsd-hardware.info/?probe=19b1b4d85d) | Oct 24, 2020 |
| Intel         | D2500HN                     | Desktop     | [6dbc4dfa33](https://bsd-hardware.info/?probe=6dbc4dfa33) | Oct 21, 2020 |
| PC Engines    | APU2                        | Desktop     | [d1ca549fe7](https://bsd-hardware.info/?probe=d1ca549fe7) | Oct 21, 2020 |
| Lenovo        | ThinkPad X230 2325AJ9       | Notebook    | [176044b6b8](https://bsd-hardware.info/?probe=176044b6b8) | Oct 21, 2020 |
| Lenovo        | ThinkPad S5-S540 20B3001... | Notebook    | [7e6cb69989](https://bsd-hardware.info/?probe=7e6cb69989) | Oct 21, 2020 |
| ZOTAC         | XXXXXX                      | Desktop     | [0f8960bdd3](https://bsd-hardware.info/?probe=0f8960bdd3) | Oct 21, 2020 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [1b1327ac93](https://bsd-hardware.info/?probe=1b1327ac93) | Oct 21, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.8.1 | 21        | 2.43%   |
| OpenBSD 6.8       | 16        | 1.85%   |
| FreeBSD 13.1      | 15        | 1.73%   |
| OPNsense 21.1.5   | 14        | 1.62%   |
| OPNsense 21.7.7   | 13        | 1.5%    |
| OPNsense 23.7.10  | 12        | 1.39%   |
| OPNsense 23.1.11  | 12        | 1.39%   |
| OPNsense 22.1     | 12        | 1.39%   |
| OPNsense 23.1.1   | 11        | 1.27%   |
| helloSystem 0.7.0 | 11        | 1.27%   |
| helloSystem 0.4.0 | 11        | 1.27%   |
| OPNsense 23.1.5   | 10        | 1.16%   |
| OPNsense 22.1.6   | 10        | 1.16%   |
| OPNsense 22.1.10  | 10        | 1.16%   |
| OpenBSD 7.1       | 10        | 1.16%   |
| NomadBSD 1.3.2    | 10        | 1.16%   |
| GhostBSD 20.04.02 | 10        | 1.16%   |
| OPNsense 24.7.8   | 9         | 1.04%   |
| OPNsense 24.7.7   | 9         | 1.04%   |
| OPNsense 24.7.6   | 9         | 1.04%   |
| OPNsense 24.7.5   | 9         | 1.04%   |
| OPNsense 24.7.11  | 9         | 1.04%   |
| OPNsense 24.7.1   | 9         | 1.04%   |
| OPNsense 23.1.7   | 9         | 1.04%   |
| OPNsense 21.7.1   | 9         | 1.04%   |
| OPNsense 21.1     | 9         | 1.04%   |
| FreeBSD 13.1-p7   | 9         | 1.04%   |
| FreeBSD 13.0      | 9         | 1.04%   |
| OPNsense 23.7.12  | 8         | 0.92%   |
| OPNsense 23.7.11  | 8         | 0.92%   |
| OPNsense 22.7.9   | 8         | 0.92%   |
| OPNsense 22.7.4   | 8         | 0.92%   |
| OPNsense 22.7     | 8         | 0.92%   |
| OPNsense 22.1.1   | 8         | 0.92%   |
| OPNsense 21.1.3   | 8         | 0.92%   |
| FreeBSD 14.1-p6   | 8         | 0.92%   |
| FreeBSD 14.0-p6   | 8         | 0.92%   |
| FreeBSD 12.1-p8   | 8         | 0.92%   |
| OPNsense 24.7.4   | 7         | 0.81%   |
| OPNsense 24.1.10  | 7         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 335       | 50.68%  |
| FreeBSD     | 166       | 25.11%  |
| helloSystem | 54        | 8.17%   |
| OpenBSD     | 45        | 6.81%   |
| NomadBSD    | 22        | 3.33%   |
| GhostBSD    | 19        | 2.87%   |
| NetBSD      | 11        | 1.66%   |
| TrueNAS     | 5         | 0.76%   |
| HardenedBSD | 2         | 0.3%    |
| FuryBSD     | 1         | 0.15%   |
| FreeNAS     | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 635       | 98.45%  |
| i386   | 6         | 0.93%   |
| arm64  | 3         | 0.47%   |
| macppc | 1         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 399       | 59.46%  |
| helloDesktop  | 76        | 11.33%  |
| XFCE          | 51        | 7.6%    |
| KDE5          | 29        | 4.32%   |
| MATE          | 22        | 3.28%   |
| Openbox       | 20        | 2.98%   |
| fvwm          | 19        | 2.83%   |
| TWM           | 14        | 2.09%   |
| GNOME         | 14        | 2.09%   |
| i3            | 8         | 1.19%   |
| AwesomeWM     | 4         | 0.6%    |
| xinitrc       | 3         | 0.45%   |
| LXDE          | 3         | 0.45%   |
| X-Cinnamon    | 1         | 0.15%   |
| WindowMaker   | 1         | 0.15%   |
| sway          | 1         | 0.15%   |
| LXQt          | 1         | 0.15%   |
| iwm           | 1         | 0.15%   |
| Enlightenment | 1         | 0.15%   |
| Cinnamon      | 1         | 0.15%   |
| Budgie        | 1         | 0.15%   |
| Blackbox      | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 407       | 62.81%  |
| X11     | 237       | 36.57%  |
| Wayland | 4         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 471       | 71.47%  |
| SLiM    | 97        | 14.72%  |
| SDDM    | 35        | 5.31%   |
| LightDM | 32        | 4.86%   |
| XDM     | 17        | 2.58%   |
| GDM     | 7         | 1.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 421       | 63.31%  |
| fr_FR           | 86        | 12.93%  |
| C               | 72        | 10.83%  |
| en_US           | 69        | 10.38%  |
| fr              | 3         | 0.45%   |
| en_GB           | 3         | 0.45%   |
| de_DE           | 3         | 0.45%   |
| en_US.ISO8859-1 | 2         | 0.3%    |
| ja_JP           | 1         | 0.15%   |
| it_IT           | 1         | 0.15%   |
| fr_FR.UTF8      | 1         | 0.15%   |
| fr_FR.US-ASCII  | 1         | 0.15%   |
| es_ES           | 1         | 0.15%   |
| en              | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 537       | 82.11%  |
| BIOS | 117       | 17.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 310       | 46.76%  |
| Ufs    | 286       | 43.14%  |
| Ffs    | 45        | 6.79%   |
| Cd9660 | 22        | 3.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 579       | 88.67%  |
| MBR     | 68        | 10.41%  |
| Unknown | 4         | 0.61%   |
| BSD     | 2         | 0.31%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 85        | 13.18%  |
| ASUSTek Computer                     | 70        | 10.85%  |
| Lenovo                               | 68        | 10.54%  |
| Intel                                | 60        | 9.3%    |
| Unknown                              | 56        | 8.68%   |
| Hewlett-Packard                      | 44        | 6.82%   |
| Gigabyte Technology                  | 23        | 3.57%   |
| PC Engines                           | 22        | 3.41%   |
| ASRock                               | 18        | 2.79%   |
| Supermicro                           | 16        | 2.48%   |
| Fujitsu                              | 16        | 2.48%   |
| Apple                                | 14        | 2.17%   |
| MSI                                  | 13        | 2.02%   |
| AMI                                  | 13        | 2.02%   |
| Deciso                               | 9         | 1.4%    |
| Techvision                           | 8         | 1.24%   |
| Acer                                 | 8         | 1.24%   |
| MW                                   | 6         | 0.93%   |
| Protectli                            | 5         | 0.78%   |
| BESSTAR Tech                         | 5         | 0.78%   |
| Shuttle                              | 4         | 0.62%   |
| ZOTAC                                | 3         | 0.47%   |
| TUXEDO                               | 3         | 0.47%   |
| Toshiba                              | 3         | 0.47%   |
| Sony                                 | 3         | 0.47%   |
| Raspberry Pi Foundation              | 3         | 0.47%   |
| Notebook                             | 3         | 0.47%   |
| AZW                                  | 3         | 0.47%   |
| Alienware                            | 3         | 0.47%   |
| Advantech                            | 3         | 0.47%   |
| TB                                   | 2         | 0.31%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.31%   |
| Samsung Electronics                  | 2         | 0.31%   |
| RUNING                               | 2         | 0.31%   |
| HUAWEI                               | 2         | 0.31%   |
| Gowin Solution                       | 2         | 0.31%   |
| Google                               | 2         | 0.31%   |
| Clevo                                | 2         | 0.31%   |
| AWOW                                 | 2         | 0.31%   |
| ASRockRack                           | 2         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 57        | 8.84%   |
| Intel Q3XXG4-P V1.0                   | 18        | 2.79%   |
| PC Engines APU2                       | 12        | 1.86%   |
| AMI Aptio CRB                         | 10        | 1.55%   |
| Techvision TVI7309X                   | 8         | 1.24%   |
| Fujitsu FUTRO S920                    | 8         | 1.24%   |
| MW GMLK-2_5G4L                        | 6         | 0.93%   |
| Intel CRESCENTBAY                     | 5         | 0.78%   |
| Dell OptiPlex 9020                    | 5         | 0.78%   |
| ASUS All Series                       | 5         | 0.78%   |
| Supermicro Super Server               | 4         | 0.62%   |
| PC Engines APU3                       | 4         | 0.62%   |
| Intel Jasper Lake Client Platform     | 4         | 0.62%   |
| Intel H81U                            | 4         | 0.62%   |
| Deciso NetBoard-A20                   | 4         | 0.62%   |
| Apple MacBookAir6,2                   | 4         | 0.62%   |
| RPi Raspberry Pi                      | 3         | 0.47%   |
| PC Engines apu4                       | 3         | 0.47%   |
| HP ProLiant MicroServer Gen8          | 3         | 0.47%   |
| Dell Precision M4500                  | 3         | 0.47%   |
| Dell PowerEdge R710                   | 3         | 0.47%   |
| Dell OptiPlex 3020                    | 3         | 0.47%   |
| Deciso Netboard A20                   | 3         | 0.47%   |
| Advantech DTADB                       | 3         | 0.47%   |
| TUXEDO InfinityBook13V3               | 2         | 0.31%   |
| Toshiba PORTEGE Z930                  | 2         | 0.31%   |
| TB WTR R1                             | 2         | 0.31%   |
| Supermicro SYS-E300-9D-8CN8TP         | 2         | 0.31%   |
| Shuttle XS35V5                        | 2         | 0.31%   |
| RUNING B75M INTEL H3V                 | 2         | 0.31%   |
| PC Engines apu1                       | 2         | 0.31%   |
| Lenovo ThinkSystem ST50 V2 7D8JCTO1WW | 2         | 0.31%   |
| Lenovo ThinkCentre M93p 10AAS4EN00    | 2         | 0.31%   |
| Lenovo ThinkCentre M720q 10T8SD6H00   | 2         | 0.31%   |
| Intel QHSW02                          | 2         | 0.31%   |
| Intel NUC11TNHi3                      | 2         | 0.31%   |
| Intel AmITX-SL-G                      | 2         | 0.31%   |
| HUAWEI KPL-W0X                        | 2         | 0.31%   |
| HP EliteDesk 800 G2 DM 35W            | 2         | 0.31%   |
| Gigabyte X570 I AORUS PRO WIFI        | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 57        | 8.84%   |
| Lenovo ThinkPad         | 42        | 6.51%   |
| Dell OptiPlex           | 29        | 4.5%    |
| Intel Q3XXG4-P          | 18        | 2.79%   |
| Dell PowerEdge          | 17        | 2.64%   |
| Dell Latitude           | 16        | 2.48%   |
| ASUS PRIME              | 15        | 2.33%   |
| Lenovo ThinkCentre      | 14        | 2.17%   |
| Dell Precision          | 13        | 2.02%   |
| PC Engines APU2         | 12        | 1.86%   |
| HP Compaq               | 10        | 1.55%   |
| AMI Aptio               | 10        | 1.55%   |
| Fujitsu FUTRO           | 9         | 1.4%    |
| Techvision TVI7309X     | 8         | 1.24%   |
| HP ProLiant             | 7         | 1.09%   |
| MW GMLK-2               | 6         | 0.93%   |
| Intel CRESCENTBAY       | 5         | 0.78%   |
| HP ProDesk              | 5         | 0.78%   |
| HP EliteBook            | 5         | 0.78%   |
| Deciso Netboard         | 5         | 0.78%   |
| ASUS All                | 5         | 0.78%   |
| Supermicro Super        | 4         | 0.62%   |
| PC Engines APU3         | 4         | 0.62%   |
| Intel Jasper            | 4         | 0.62%   |
| Intel H81U              | 4         | 0.62%   |
| HP EliteDesk            | 4         | 0.62%   |
| Deciso NetBoard-A20     | 4         | 0.62%   |
| Apple MacBookAir6       | 4         | 0.62%   |
| Acer Aspire             | 4         | 0.62%   |
| RPi Raspberry           | 3         | 0.47%   |
| PC Engines apu4         | 3         | 0.47%   |
| Lenovo ThinkSystem      | 3         | 0.47%   |
| Lenovo Legion           | 3         | 0.47%   |
| Fujitsu ESPRIMO         | 3         | 0.47%   |
| Dell Vostro             | 3         | 0.47%   |
| ASUS TUF                | 3         | 0.47%   |
| Advantech DTADB         | 3         | 0.47%   |
| TUXEDO InfinityBook13V3 | 2         | 0.31%   |
| Toshiba PORTEGE         | 2         | 0.31%   |
| TB WTR                  | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2016    | 63        | 9.77%   |
| 2019    | 59        | 9.15%   |
| 2018    | 55        | 8.53%   |
| 2021    | 53        | 8.22%   |
| 2022    | 49        | 7.6%    |
| 2020    | 48        | 7.44%   |
| 2014    | 45        | 6.98%   |
| 2023    | 37        | 5.74%   |
| 2013    | 35        | 5.43%   |
| 2017    | 31        | 4.81%   |
| 2012    | 31        | 4.81%   |
| 2015    | 29        | 4.5%    |
| 2011    | 26        | 4.03%   |
| 2010    | 20        | 3.1%    |
| 2024    | 18        | 2.79%   |
| 2008    | 13        | 2.02%   |
| Unknown | 13        | 2.02%   |
| 2009    | 11        | 1.71%   |
| 2007    | 7         | 1.09%   |
| 2006    | 2         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 380       | 58.91%  |
| Notebook       | 173       | 26.82%  |
| Mini pc        | 52        | 8.06%   |
| Server         | 29        | 4.5%    |
| System on chip | 3         | 0.47%   |
| Firewall       | 3         | 0.47%   |
| All in one     | 3         | 0.47%   |
| Convertible    | 2         | 0.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 617       | 95.66%  |
| Yes  | 28        | 4.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 235       | 35.66%  |
| 16.01-24.0      | 148       | 22.46%  |
| 4.01-8.0        | 133       | 20.18%  |
| 32.01-64.0      | 60        | 9.1%    |
| 64.01-256.0     | 30        | 4.55%   |
| 2.01-3.0        | 26        | 3.95%   |
| 3.01-4.0        | 9         | 1.37%   |
| 24.01-32.0      | 7         | 1.06%   |
| 1.01-2.0        | 6         | 0.91%   |
| 0.51-1.0        | 3         | 0.46%   |
| More than 256.0 | 2         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 333       | 50.3%   |
| 0.51-1.0    | 195       | 29.46%  |
| 1.01-2.0    | 67        | 10.12%  |
| 2.01-3.0    | 22        | 3.32%   |
| 4.01-8.0    | 12        | 1.81%   |
| Unknown     | 11        | 1.66%   |
| 8.01-16.0   | 7         | 1.06%   |
| 3.01-4.0    | 5         | 0.76%   |
| 32.01-64.0  | 3         | 0.45%   |
| 24.01-32.0  | 2         | 0.3%    |
| 64.01-256.0 | 2         | 0.3%    |
| 0           | 2         | 0.3%    |
| 16.01-24.0  | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 405       | 60.36%  |
| 0      | 108       | 16.1%   |
| 2      | 98        | 14.61%  |
| 3      | 31        | 4.62%   |
| 4      | 12        | 1.79%   |
| 5      | 7         | 1.04%   |
| 6      | 5         | 0.75%   |
| 25     | 2         | 0.3%    |
| 10     | 1         | 0.15%   |
| 8      | 1         | 0.15%   |
| 7      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 550       | 84.49%  |
| Yes       | 101       | 15.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 614       | 95.05%  |
| No        | 32        | 4.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 363       | 55.85%  |
| Yes       | 287       | 44.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 459       | 70.4%   |
| Yes       | 193       | 29.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 645       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Paris                 | 132       | 17.93%  |
| Bordeaux              | 13        | 1.77%   |
| Lyon                  | 10        | 1.36%   |
| Toulouse              | 9         | 1.22%   |
| Lille                 | 8         | 1.09%   |
| Colombes              | 8         | 1.09%   |
| Strasbourg            | 7         | 0.95%   |
| Saint-Denis           | 7         | 0.95%   |
| Roubaix               | 7         | 0.95%   |
| Franconville          | 7         | 0.95%   |
| Urcuit                | 6         | 0.82%   |
| Rosny-sous-Bois       | 6         | 0.82%   |
| Noisy-le-Grand        | 6         | 0.82%   |
| Marseille             | 6         | 0.82%   |
| Dijon                 | 6         | 0.82%   |
| Soisy-sur-Seine       | 5         | 0.68%   |
| Rennes                | 5         | 0.68%   |
| Noyon                 | 5         | 0.68%   |
| Melun                 | 5         | 0.68%   |
| Mâcon                | 5         | 0.68%   |
| Fontenay-sous-Bois    | 5         | 0.68%   |
| Courbevoie            | 5         | 0.68%   |
| Argenteuil            | 5         | 0.68%   |
| Agen                  | 5         | 0.68%   |
| Villeurbanne          | 4         | 0.54%   |
| Rillieux-la-Pape      | 4         | 0.54%   |
| Grenoble              | 4         | 0.54%   |
| Colmar                | 4         | 0.54%   |
| Clermont-Ferrand      | 4         | 0.54%   |
| Champigny-sur-Marne   | 4         | 0.54%   |
| Boulogne-Billancourt  | 4         | 0.54%   |
| Vauvillers            | 3         | 0.41%   |
| Vaulx-en-Velin        | 3         | 0.41%   |
| Thionville            | 3         | 0.41%   |
| Sarcelles             | 3         | 0.41%   |
| Saint-Herblain        | 3         | 0.41%   |
| Saint-Germain-en-Laye | 3         | 0.41%   |
| Orléans              | 3         | 0.41%   |
| Nice                  | 3         | 0.41%   |
| Nantes                | 3         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 94        | 153    | 13.53%  |
| Seagate             | 73        | 115    | 10.5%   |
| Crucial             | 67        | 101    | 9.64%   |
| WDC                 | 66        | 126    | 9.5%    |
| Kingston            | 52        | 84     | 7.48%   |
| Toshiba             | 33        | 58     | 4.75%   |
| China               | 32        | 47     | 4.6%    |
| Transcend           | 30        | 46     | 4.32%   |
| SanDisk             | 25        | 38     | 3.6%    |
| Intel               | 22        | 31     | 3.17%   |
| Phison              | 14        | 16     | 2.01%   |
| Micron Technology   | 13        | 21     | 1.87%   |
| HGST                | 13        | 21     | 1.87%   |
| PNY                 | 11        | 21     | 1.58%   |
| Hoodisk             | 11        | 13     | 1.58%   |
| SK hynix            | 9         | 10     | 1.29%   |
| Apple               | 9         | 12     | 1.29%   |
| Hitachi             | 8         | 8      | 1.15%   |
| NVMe                | 7         | 7      | 1.01%   |
| Innodisk            | 7         | 7      | 1.01%   |
| Hewlett-Packard     | 6         | 17     | 0.86%   |
| FORESEE             | 6         | 10     | 0.86%   |
| Corsair             | 6         | 10     | 0.86%   |
| Fujitsu             | 5         | 6      | 0.72%   |
| OCZ                 | 4         | 5      | 0.58%   |
| Maxtor              | 3         | 4      | 0.43%   |
| LITEON              | 3         | 4      | 0.43%   |
| LDLC                | 3         | 3      | 0.43%   |
| Generic             | 3         | 3      | 0.43%   |
| Fanxiang            | 3         | 3      | 0.43%   |
| Dell                | 3         | 48     | 0.43%   |
| A-DATA Technology   | 3         | 4      | 0.43%   |
| TEXTORM             | 2         | 2      | 0.29%   |
| SPCC                | 2         | 2      | 0.29%   |
| Silicon Motion      | 2         | 2      | 0.29%   |
| ShiJi               | 2         | 3      | 0.29%   |
| Pccooler            | 2         | 2      | 0.29%   |
| Patriot             | 2         | 2      | 0.29%   |
| OPENBSD             | 2         | 3      | 0.29%   |
| NETAPP              | 2         | 4      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB          | 10        | 1.34%   |
| Kingston SA400S37240G 240GB        | 9         | 1.21%   |
| Crucial CT250MX500SSD1 250GB       | 9         | 1.21%   |
| Phison SATA SSD 16GB               | 8         | 1.08%   |
| China MSATA 32GB SSD               | 7         | 0.94%   |
| PNY CS900 120GB SSD                | 6         | 0.81%   |
| Kingston SV300S37A120G 120GB       | 6         | 0.81%   |
| Crucial CT1000P1SSD8 1TB           | 6         | 0.81%   |
| China SATA SSD 16GB                | 6         | 0.81%   |
| Transcend TS256GMTS952T2 256GB     | 5         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 0.67%   |
| Samsung SSD 860 EVO 1TB            | 5         | 0.67%   |
| Hoodisk SSD 32GB                   | 5         | 0.67%   |
| Crucial CT500MX500SSD1 500GB       | 5         | 0.67%   |
| Crucial CT240BX500SSD1 240GB       | 5         | 0.67%   |
| Crucial CT120BX500SSD1 120GB       | 5         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB       | 4         | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB           | 4         | 0.54%   |
| SanDisk SSD PLUS 120GB             | 4         | 0.54%   |
| Micron 1100 SATA 256GB             | 4         | 0.54%   |
| Kingston SUV500MS120G 120GB        | 4         | 0.54%   |
| FORESEE 64GB SSD                   | 4         | 0.54%   |
| Crucial M4-CT128M4SSD2 128GB       | 4         | 0.54%   |
| Crucial CT1000BX500SSD1 1TB        | 4         | 0.54%   |
| China MSATA 64GB SSD               | 4         | 0.54%   |
| Apple SSD SD0128F 121GB            | 4         | 0.54%   |
| Transcend TS128GSSD420K 128GB      | 3         | 0.4%    |
| Transcend TS128GMSA230S 128GB      | 3         | 0.4%    |
| Seagate ST3500418AS 500GB          | 3         | 0.4%    |
| Seagate ST1000NM0033-9ZM173 1TB    | 3         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB     | 3         | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.4%    |
| Samsung SSD 860 EVO 250GB          | 3         | 0.4%    |
| Samsung SSD 850 EVO 500GB          | 3         | 0.4%    |
| Samsung SSD 850 EVO 1TB            | 3         | 0.4%    |
| Kingston SV300S37A240G 240GB       | 3         | 0.4%    |
| Kingston SA400S37120G 120GB        | 3         | 0.4%    |
| Intel SSDSA2CT040G3 40GB           | 3         | 0.4%    |
| Hoodisk SSD 64GB                   | 3         | 0.4%    |
| HGST HUS724020ALA640 2TB           | 3         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 111    | 32.26%  |
| WDC                 | 55        | 108    | 25.35%  |
| Toshiba             | 26        | 45     | 11.98%  |
| HGST                | 13        | 21     | 5.99%   |
| Samsung Electronics | 9         | 16     | 4.15%   |
| Hitachi             | 8         | 8      | 3.69%   |
| NVMe                | 5         | 5      | 2.3%    |
| Fujitsu             | 5         | 6      | 2.3%    |
| Maxtor              | 3         | 4      | 1.38%   |
| Hewlett-Packard     | 3         | 7      | 1.38%   |
| Generic             | 3         | 3      | 1.38%   |
| Dell                | 3         | 48     | 1.38%   |
| OPENBSD             | 2         | 3      | 0.92%   |
| NETAPP              | 2         | 4      | 0.92%   |
| LSI                 | 2         | 2      | 0.92%   |
| Apple               | 2         | 4      | 0.92%   |
| SABRENT             | 1         | 1      | 0.46%   |
| Lexar               | 1         | 2      | 0.46%   |
| LDLC F6+            | 1         | 1      | 0.46%   |
| External            | 1         | 1      | 0.46%   |
| ASMT                | 1         | 1      | 0.46%   |
| ASMedia             | 1         | 1      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 96     | 16.1%   |
| Crucial             | 47        | 62     | 12.21%  |
| Kingston            | 45        | 74     | 11.69%  |
| China               | 32        | 47     | 8.31%   |
| Transcend           | 27        | 42     | 7.01%   |
| SanDisk             | 25        | 38     | 6.49%   |
| Intel               | 15        | 19     | 3.9%    |
| Hoodisk             | 11        | 13     | 2.86%   |
| PNY                 | 10        | 19     | 2.6%    |
| WDC                 | 9         | 14     | 2.34%   |
| Phison              | 8         | 9      | 2.08%   |
| Micron Technology   | 7         | 13     | 1.82%   |
| Innodisk            | 7         | 7      | 1.82%   |
| Apple               | 7         | 8      | 1.82%   |
| Toshiba             | 6         | 11     | 1.56%   |
| FORESEE             | 6         | 10     | 1.56%   |
| Hewlett-Packard     | 5         | 10     | 1.3%    |
| Corsair             | 5         | 6      | 1.3%    |
| SK hynix            | 4         | 4      | 1.04%   |
| OCZ                 | 4         | 5      | 1.04%   |
| LITEON              | 3         | 4      | 0.78%   |
| A-DATA Technology   | 3         | 4      | 0.78%   |
| TEXTORM             | 2         | 2      | 0.52%   |
| SPCC                | 2         | 2      | 0.52%   |
| ShiJi               | 2         | 3      | 0.52%   |
| Pccooler            | 2         | 2      | 0.52%   |
| NVMe                | 2         | 2      | 0.52%   |
| Integral            | 2         | 2      | 0.52%   |
| Apacer              | 2         | 2      | 0.52%   |
| VICKTER             | 1         | 1      | 0.26%   |
| VICK                | 1         | 2      | 0.26%   |
| Vaseky              | 1         | 4      | 0.26%   |
| TCSUNBOW            | 1         | 3      | 0.26%   |
| Supermicro          | 1         | 1      | 0.26%   |
| Silicon Power       | 1         | 2      | 0.26%   |
| SHAREVDI            | 1         | 1      | 0.26%   |
| Seagate             | 1         | 2      | 0.26%   |
| Protectli           | 1         | 1      | 0.26%   |
| Patriot             | 1         | 1      | 0.26%   |
| LITEONIT            | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 357       | 570    | 56.4%   |
| HDD  | 181       | 402    | 28.59%  |
| NVMe | 95        | 152    | 15.01%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 483       | 972    | 83.56%  |
| NVMe | 95        | 152    | 16.44%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 405       | 707    | 72.97%  |
| 0.51-1.0   | 90        | 138    | 16.22%  |
| 1.01-2.0   | 39        | 84     | 7.03%   |
| 4.01-10.0  | 9         | 17     | 1.62%   |
| 3.01-4.0   | 7         | 16     | 1.26%   |
| 2.01-3.0   | 5         | 10     | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 255       | 38.23%  |
| 251-500        | 100       | 14.99%  |
| 1-20           | 96        | 14.39%  |
| 21-50          | 68        | 10.19%  |
| 501-1000       | 63        | 9.45%   |
| 51-100         | 49        | 7.35%   |
| 1001-2000      | 18        | 2.7%    |
| More than 3000 | 8         | 1.2%    |
| 2001-3000      | 7         | 1.05%   |
| Unknown        | 3         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 561       | 85%     |
| 21-50          | 44        | 6.67%   |
| 101-250        | 22        | 3.33%   |
| 251-500        | 11        | 1.67%   |
| 51-100         | 11        | 1.67%   |
| 501-1000       | 4         | 0.61%   |
| More than 3000 | 3         | 0.45%   |
| Unknown        | 3         | 0.45%   |
| 1001-2000      | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB       | 3         | 4      | 3.57%   |
| Kingston SV300S37A120G 120GB       | 3         | 4      | 3.57%   |
| WDC WD3200BPVT-80JJ5T0 320GB       | 2         | 2      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 4      | 2.38%   |
| Seagate ST1000NM0011 1TB           | 2         | 3      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 3      | 2.38%   |
| Samsung Electronics HD501LJ 500GB  | 2         | 2      | 2.38%   |
| WDC WD6400BPVT-22HXZT3 640GB       | 1         | 1      | 1.19%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1         | 1      | 1.19%   |
| WDC WD5002ABYS-18B1B0 500GB        | 1         | 1      | 1.19%   |
| WDC WD30EFRX-68AX9N0 3TB           | 1         | 4      | 1.19%   |
| WDC WD2500BEVS-60UST0 250GB        | 1         | 1      | 1.19%   |
| WDC WD20EZRX-00D8PB0 2TB           | 1         | 1      | 1.19%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1         | 1      | 1.19%   |
| WDC WD15EADS-00P8B0 1.5TB          | 1         | 1      | 1.19%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.19%   |
| WDC WD10EZEX-60M2NA0 1TB           | 1         | 1      | 1.19%   |
| WDC WD10EZEX-08WN4A0 1TB           | 1         | 1      | 1.19%   |
| WDC WD10EAVS-00D7B0 1TB            | 1         | 1      | 1.19%   |
| WDC WD10EARS-00Y5B1 1TB            | 1         | 1      | 1.19%   |
| WDC WD1001FAES-75W7A0 1TB          | 1         | 1      | 1.19%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 1.19%   |
| Toshiba MQ01ABD050 500GB           | 1         | 2      | 1.19%   |
| Toshiba MK5065GSX 500GB            | 1         | 1      | 1.19%   |
| Toshiba MK3261GSY 320GB            | 1         | 1      | 1.19%   |
| Toshiba MK1629GSGF 160GB           | 1         | 3      | 1.19%   |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 1.19%   |
| TEXTORM BM5 480GB                  | 1         | 1      | 1.19%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 1.19%   |
| Seagate ST9320423AS 320GB          | 1         | 3      | 1.19%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 1.19%   |
| Seagate ST500VT000-1DK142 500GB    | 1         | 1      | 1.19%   |
| Seagate ST500LM000-SSHD-8GB        | 1         | 2      | 1.19%   |
| Seagate ST380013AS 80GB            | 1         | 2      | 1.19%   |
| Seagate ST3250620AS 250GB          | 1         | 1      | 1.19%   |
| Seagate ST3250312AS 250GB          | 1         | 1      | 1.19%   |
| Seagate ST320LT012-9WS14C 320GB    | 1         | 7      | 1.19%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 1.19%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 1.19%   |
| Seagate ST3160023AS 160GB          | 1         | 1      | 1.19%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 23     | 23.75%  |
| Seagate             | 19        | 34     | 23.75%  |
| Samsung Electronics | 7         | 16     | 8.75%   |
| Toshiba             | 6         | 9      | 7.5%    |
| Kingston            | 6         | 9      | 7.5%    |
| SanDisk             | 3         | 3      | 3.75%   |
| HGST                | 3         | 4      | 3.75%   |
| A-DATA Technology   | 3         | 4      | 3.75%   |
| Micron Technology   | 2         | 2      | 2.5%    |
| Maxtor              | 2         | 2      | 2.5%    |
| Intel               | 2         | 2      | 2.5%    |
| Hitachi             | 2         | 2      | 2.5%    |
| Crucial             | 2         | 2      | 2.5%    |
| TEXTORM             | 1         | 1      | 1.25%   |
| OCZ                 | 1         | 2      | 1.25%   |
| Innodisk            | 1         | 1      | 1.25%   |
| Corsair             | 1         | 2      | 1.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 34     | 37.25%  |
| WDC                 | 16        | 19     | 31.37%  |
| Toshiba             | 6         | 9      | 11.76%  |
| Samsung Electronics | 3         | 5      | 5.88%   |
| HGST                | 3         | 4      | 5.88%   |
| Maxtor              | 2         | 2      | 3.92%   |
| Hitachi             | 2         | 2      | 3.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 75     | 61.84%  |
| SSD  | 29        | 43     | 38.16%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Supermicro SSD 16GB       | 1         | 1      | 33.33%  |
| Kingston SMS200S360G 64GB | 1         | 1      | 33.33%  |
| Hoodisk SSD 64GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor     | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| Supermicro | 1         | 1      | 33.33%  |
| Kingston   | 1         | 1      | 33.33%  |
| Hoodisk    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 487       | 970    | 82.96%  |
| Malfunc  | 75        | 118    | 12.78%  |
| Detected | 22        | 33     | 3.75%   |
| Failed   | 3         | 3      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 482       | 60.63%  |
| AMD                            | 101       | 12.7%   |
| Samsung Electronics            | 40        | 5.03%   |
| Micron/Crucial Technology      | 26        | 3.27%   |
| Broadcom / LSI                 | 19        | 2.39%   |
| Silicon Motion                 | 12        | 1.51%   |
| SanDisk                        | 12        | 1.51%   |
| Phison Electronics             | 11        | 1.38%   |
| ASMedia Technology             | 11        | 1.38%   |
| Marvell Technology Group       | 10        | 1.26%   |
| Kingston Technology Company    | 9         | 1.13%   |
| Micron Technology              | 8         | 1.01%   |
| MAXIO Technology (Hangzhou)    | 8         | 1.01%   |
| SK hynix                       | 7         | 0.88%   |
| Toshiba                        | 5         | 0.63%   |
| Hewlett-Packard                | 5         | 0.63%   |
| Transcend                      | 4         | 0.5%    |
| Realtek Semiconductor          | 4         | 0.5%    |
| Nvidia                         | 4         | 0.5%    |
| Seagate Technology             | 3         | 0.38%   |
| JMicron Technology             | 3         | 0.38%   |
| VIA Technologies               | 2         | 0.25%   |
| KIOXIA                         | 2         | 0.25%   |
| Chelsio Communications         | 2         | 0.25%   |
| Solid State Storage Technology | 1         | 0.13%   |
| Silicon Image                  | 1         | 0.13%   |
| Shenzhen Longsys Electronics   | 1         | 0.13%   |
| Integrated Technology Express  | 1         | 0.13%   |
| Hosin Global Electronics       | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 67        | 7.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 31        | 3.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 30        | 3.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 29        | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 26        | 2.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 2.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 2.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 19        | 2.14%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 17        | 1.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 15        | 1.69%   |
| Intel SATA Controller [RAID mode]                                                | 15        | 1.69%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 15        | 1.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 14        | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 14        | 1.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 12        | 1.35%   |
| AMD FCH SATA Controller [IDE mode]                                               | 12        | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 11        | 1.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 11        | 1.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 10        | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 9         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.01%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 9         | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 8         | 0.9%    |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 8         | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                           | 8         | 0.9%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 7         | 0.79%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 7         | 0.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 7         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 0.79%   |
| AMD 400 Series Chipset SATA Controller                                           | 7         | 0.79%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 6         | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 518       | 64.75%  |
| NVMe | 154       | 19.25%  |
| IDE  | 67        | 8.38%   |
| RAID | 45        | 5.63%   |
| SAS  | 10        | 1.25%   |
| SCSI | 6         | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 532       | 82.23%  |
| AMD     | 111       | 17.16%  |
| ARM     | 3         | 0.46%   |
| PowerPC | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                         | 19        | 2.91%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 17        | 2.6%    |
| Intel N100                               | 13        | 1.99%   |
| Intel Celeron N5105 @ 2.00GHz            | 12        | 1.84%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 9         | 1.38%   |
| Intel Core i3-4010U CPU @ 1.70GHz        | 8         | 1.23%   |
| Intel Core i5-6500T CPU @ 2.50GHz        | 7         | 1.07%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 6         | 0.92%   |
| Intel Core i5-4300Y CPU @ 1.60GHz        | 6         | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 6         | 0.92%   |
| AMD GX-415GA SOC with Radeon HD Graphics | 6         | 0.92%   |
| Intel Core i5-5250U CPU @ 1.60GHz        | 5         | 0.77%   |
| Intel Core i3-8100T CPU @ 3.10GHz        | 5         | 0.77%   |
| Intel Celeron CPU N3160 @ 1.60GHz        | 5         | 0.77%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 5         | 0.77%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 4         | 0.61%   |
| Intel N95                                | 4         | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 4         | 0.61%   |
| Intel Core i5-9500 CPU @ 3.00GHz         | 4         | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 4         | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 4         | 0.61%   |
| Intel Core i5-4590T CPU @ 2.00GHz        | 4         | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 4         | 0.61%   |
| Intel Core i5-4250U CPU @ 1.30GHz        | 4         | 0.61%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 4         | 0.61%   |
| Intel Atom CPU D525 @ 1.80GHz            | 4         | 0.61%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 4         | 0.61%   |
| AMD EPYC 3201 8-Core Processor           | 4         | 0.61%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz     | 3         | 0.46%   |
| Intel Xeon                               | 3         | 0.46%   |
| Intel Pentium CPU @ 2.00GHz              | 3         | 0.46%   |
| Intel Core i7-9700 CPU @ 3.00GHz         | 3         | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 3         | 0.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 3         | 0.46%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 3         | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 3         | 0.46%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz        | 3         | 0.46%   |
| Intel Core i5-2500K CPU @ 3.30GHz        | 3         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 132       | 20.25%  |
| Intel Celeron           | 86        | 13.19%  |
| Intel Core i7           | 74        | 11.35%  |
| Intel Core i3           | 62        | 9.51%   |
| Other                   | 49        | 7.52%   |
| Intel Xeon              | 49        | 7.52%   |
| Intel Atom              | 32        | 4.91%   |
| AMD GX                  | 32        | 4.91%   |
| AMD Ryzen 5             | 18        | 2.76%   |
| AMD Ryzen 7             | 17        | 2.61%   |
| Intel Core 2 Duo        | 14        | 2.15%   |
| Intel Pentium           | 12        | 1.84%   |
| Intel Core 2 Quad       | 7         | 1.07%   |
| AMD EPYC                | 7         | 1.07%   |
| Intel Pentium Gold      | 4         | 0.61%   |
| Intel Core i9           | 4         | 0.61%   |
| AMD Ryzen 7 PRO         | 4         | 0.61%   |
| Intel Xeon Silver       | 3         | 0.46%   |
| Intel 686-class         | 3         | 0.46%   |
| ARM Cortex              | 3         | 0.46%   |
| AMD Opteron             | 3         | 0.46%   |
| AMD G                   | 3         | 0.46%   |
| AMD A8                  | 3         | 0.46%   |
| Intel Pentium Silver    | 2         | 0.31%   |
| Intel Core 2            | 2         | 0.31%   |
| AMD Ryzen 3             | 2         | 0.31%   |
| AMD E1                  | 2         | 0.31%   |
| AMD E                   | 2         | 0.31%   |
| AMD Athlon 64 X2        | 2         | 0.31%   |
| AMD Athlon              | 2         | 0.31%   |
| AMD A4                  | 2         | 0.31%   |
| AMD A10                 | 2         | 0.31%   |
| Intel Pentium M         | 1         | 0.15%   |
| Intel Pentium Dual-Core | 1         | 0.15%   |
| Intel Pentium Dual      | 1         | 0.15%   |
| Intel Genuine           | 1         | 0.15%   |
| Intel Core M            | 1         | 0.15%   |
| AMD Ryzen 9             | 1         | 0.15%   |
| AMD Ryzen 5 PRO         | 1         | 0.15%   |
| AMD Phenom II X4        | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 286       | 43.87%  |
| 2       | 209       | 32.06%  |
| 8       | 36        | 5.52%   |
| 6       | 33        | 5.06%   |
| Unknown | 31        | 4.75%   |
| 12      | 20        | 3.07%   |
| 16      | 19        | 2.91%   |
| 10      | 6         | 0.92%   |
| 32      | 4         | 0.61%   |
| 1       | 3         | 0.46%   |
| 64      | 2         | 0.31%   |
| 24      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |
| 3       | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 615       | 95.35%  |
| Unknown | 17        | 2.64%   |
| 2       | 11        | 1.71%   |
| 4       | 2         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 337       | 51.85%  |
| 2       | 281       | 43.23%  |
| Unknown | 32        | 4.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 84        | 12.92%  |
| Unknown       | 80        | 12.31%  |
| Haswell       | 73        | 11.23%  |
| IvyBridge     | 48        | 7.38%   |
| Skylake       | 45        | 6.92%   |
| SandyBridge   | 39        | 6%      |
| Silvermont    | 35        | 5.38%   |
| Puma          | 24        | 3.69%   |
| Broadwell     | 23        | 3.54%   |
| Penryn        | 20        | 3.08%   |
| Goldmont plus | 19        | 2.92%   |
| Goldmont      | 15        | 2.31%   |
| Bonnell       | 14        | 2.15%   |
| Zen 3         | 13        | 2%      |
| Zen 2         | 13        | 2%      |
| Westmere      | 13        | 2%      |
| Zen           | 12        | 1.85%   |
| Jaguar        | 12        | 1.85%   |
| Core          | 11        | 1.69%   |
| CometLake     | 10        | 1.54%   |
| Zen+          | 8         | 1.23%   |
| TigerLake     | 8         | 1.23%   |
| Nehalem       | 7         | 1.08%   |
| Piledriver    | 6         | 0.92%   |
| Bobcat        | 6         | 0.92%   |
| K10           | 3         | 0.46%   |
| Excavator     | 3         | 0.46%   |
| Steamroller   | 2         | 0.31%   |
| K10 Llano     | 2         | 0.31%   |
| P6            | 1         | 0.15%   |
| K8 Hammer     | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 415       | 66.08%  |
| AMD                        | 87        | 13.85%  |
| Nvidia                     | 78        | 12.42%  |
| Matrox Electronics Systems | 27        | 4.3%    |
| ASPEED Technology          | 21        | 3.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 3.91%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 3.75%   |
| Intel HD Graphics 530                                                                    | 23        | 3.59%   |
| Intel JasperLake [UHD Graphics]                                                          | 21        | 3.28%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 21        | 3.28%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 20        | 3.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 2.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 2.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 2.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 2.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 2.5%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 13        | 2.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 13        | 2.03%   |
| Intel HD Graphics 620                                                                    | 13        | 2.03%   |
| Intel HD Graphics 5500                                                                   | 13        | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 2.03%   |
| Intel HD Graphics 630                                                                    | 10        | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.25%   |
| Intel Haswell-ULT Integrated Graphics Controller [HD Graphics]                           | 8         | 1.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.09%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7         | 1.09%   |
| Intel UHD Graphics 620                                                                   | 6         | 0.94%   |
| Intel HD Graphics 510                                                                    | 6         | 0.94%   |
| Intel HD Graphics 500                                                                    | 6         | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 0.94%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 6         | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.78%   |
| Matrox Electronics Systems MGA G200EH                                                    | 5         | 0.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 0.78%   |
| Intel HD Graphics 6000                                                                   | 5         | 0.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.78%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 5         | 0.78%   |
| AMD ES1000                                                                               | 5         | 0.78%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 4         | 0.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 368       | 56.62%  |
| 1 x AMD                  | 81        | 12.46%  |
| Other                    | 52        | 8%      |
| 1 x Nvidia               | 50        | 7.69%   |
| 1 x Matrox               | 27        | 4.15%   |
| Intel + Nvidia           | 25        | 3.85%   |
| 1 x ASPEED               | 20        | 3.08%   |
| 2 x Intel                | 19        | 2.92%   |
| 2 x AMD                  | 2         | 0.31%   |
| Intel + AMD              | 2         | 0.31%   |
| 2 x Nvidia               | 1         | 0.15%   |
| Nvidia + ASPEED          | 1         | 0.15%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.15%   |
| AMD + Nvidia             | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 549       | 84.46%  |
| Unknown     | 65        | 10%     |
| Proprietary | 36        | 5.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 580       | 89.64%  |
| 0.51-1.0   | 16        | 2.47%   |
| 7.01-8.0   | 12        | 1.85%   |
| 0.01-0.5   | 12        | 1.85%   |
| 1.01-2.0   | 10        | 1.55%   |
| 5.01-6.0   | 8         | 1.24%   |
| 3.01-4.0   | 5         | 0.77%   |
| 8.01-16.0  | 2         | 0.31%   |
| 2.01-3.0   | 1         | 0.15%   |
| 16.01-24.0 | 1         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 12.5%   |
| LG Display              | 19        | 8.8%    |
| Samsung Electronics     | 18        | 8.33%   |
| Dell                    | 18        | 8.33%   |
| Chimei Innolux          | 17        | 7.87%   |
| BOE                     | 13        | 6.02%   |
| Iiyama                  | 12        | 5.56%   |
| Apple                   | 12        | 5.56%   |
| Goldstar                | 8         | 3.7%    |
| Hewlett-Packard         | 7         | 3.24%   |
| BenQ                    | 6         | 2.78%   |
| ViewSonic               | 5         | 2.31%   |
| Idek Iiyama             | 5         | 2.31%   |
| Chi Mei Optoelectronics | 5         | 2.31%   |
| Acer                    | 5         | 2.31%   |
| Philips                 | 4         | 1.85%   |
| AOC                     | 4         | 1.85%   |
| Sharp                   | 3         | 1.39%   |
| Lenovo                  | 3         | 1.39%   |
| CSO                     | 3         | 1.39%   |
| Ancor Communications    | 3         | 1.39%   |
| LGD                     | 2         | 0.93%   |
| HUAWEI                  | 2         | 0.93%   |
| Unknown                 | 1         | 0.46%   |
| Toshiba                 | 1         | 0.46%   |
| Sony                    | 1         | 0.46%   |
| PRI                     | 1         | 0.46%   |
| PKB                     | 1         | 0.46%   |
| Packard Bell            | 1         | 0.46%   |
| Nvidia                  | 1         | 0.46%   |
| LG Electronics          | 1         | 0.46%   |
| Lenovo Group Limited    | 1         | 0.46%   |
| IBM                     | 1         | 0.46%   |
| CPT                     | 1         | 0.46%   |
| CKL                     | 1         | 0.46%   |
| BOE Technology Group    | 1         | 0.46%   |
| ASUSTek Computer        | 1         | 0.46%   |
| Unknown                 | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BenQ EW3270U BNQ7950 3840x2160 700x390mm 31.5-inch                       | 4         | 1.85%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 4         | 1.85%   |
| Goldstar 24GM77 GSM5A91 1920x1080 530x300mm 24.0-inch                    | 3         | 1.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 3         | 1.39%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch            | 2         | 0.93%   |
| Philips PHL 241B8Q PHL0929 1920x1080 530x300mm 24.0-inch                 | 2         | 0.93%   |
| LGD LCD Monitor 1600x900                                                 | 2         | 0.93%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 0.93%   |
| Iiyama PL2474H IVM6146 1920x1080 520x290mm 23.4-inch                     | 2         | 0.93%   |
| Iiyama PL2474H IVM6137 1920x1080 520x290mm 23.4-inch                     | 2         | 0.93%   |
| Idek Iiyama LCD Monitor PLX2783H 1920x1080                               | 2         | 0.93%   |
| HUAWEI AD80HW HWV2402 1920x1080 530x300mm 24.0-inch                      | 2         | 0.93%   |
| Dell SE2417HGX DELD0F7 1920x1080 520x290mm 23.4-inch                     | 2         | 0.93%   |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                        | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 280x160mm 12.7-inch         | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 0.93%   |
| BOE LCD Monitor BOE0700 1920x1080 340x190mm 15.3-inch                    | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 310x170mm 13.9-inch           | 2         | 0.93%   |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                    | 2         | 0.93%   |
| AOC 24G1WG4 AOC2401 1920x1080 520x290mm 23.4-inch                        | 2         | 0.93%   |
| Acer V223HQ ACR0070 1920x1080 470x270mm 21.3-inch                        | 2         | 0.93%   |
| ViewSonic VA2403-FHD VSCF136 1920x1080 520x290mm 23.4-inch               | 1         | 0.46%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 480x270mm 21.7-inch               | 1         | 0.46%   |
| ViewSonic VA1916w-6 VSCF91F 1440x900 410x260mm 19.1-inch                 | 1         | 0.46%   |
| Unknown LCD Monitor Sharp 3840x2160                                      | 1         | 0.46%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                          | 1         | 0.46%   |
| Sony TV  *00 SNYF903 3840x2160 950x540mm 43.0-inch                       | 1         | 0.46%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch                  | 1         | 0.46%   |
| Sharp LCD Monitor SHP1416 1366x768 310x170mm 13.9-inch                   | 1         | 0.46%   |
| Sharp LCD Monitor SHP13F9 3200x1800 350x190mm 15.7-inch                  | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch      | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 3520x1200                     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544E 1024x600 220x130mm 10.1-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch    | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 42.93%  |
| 1366x768 (WXGA)    | 36        | 17.56%  |
| 2560x1440 (QHD)    | 12        | 5.85%   |
| 3840x2160 (4K)     | 11        | 5.37%   |
| 1600x900 (HD+)     | 10        | 4.88%   |
| 1440x900 (WXGA+)   | 9         | 4.39%   |
| 1680x1050 (WSXGA+) | 7         | 3.41%   |
| 1280x1024 (SXGA)   | 7         | 3.41%   |
| 1280x800 (WXGA)    | 5         | 2.44%   |
| 1920x1200 (WUXGA)  | 4         | 1.95%   |
| 2560x1600          | 3         | 1.46%   |
| 1024x600           | 3         | 1.46%   |
| 2880x1800          | 2         | 0.98%   |
| 2560x1080          | 2         | 0.98%   |
| 3520x1200          | 1         | 0.49%   |
| 3200x1800 (QHD+)   | 1         | 0.49%   |
| 1920x540           | 1         | 0.49%   |
| 1440x960           | 1         | 0.49%   |
| 1400x1050          | 1         | 0.49%   |
| Unknown            | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 44        | 20.75%  |
| 15      | 35        | 16.51%  |
| Unknown | 21        | 9.91%   |
| 24      | 15        | 7.08%   |
| 23      | 15        | 7.08%   |
| 12      | 15        | 7.08%   |
| 27      | 11        | 5.19%   |
| 21      | 10        | 4.72%   |
| 17      | 10        | 4.72%   |
| 19      | 9         | 4.25%   |
| 31      | 5         | 2.36%   |
| 14      | 4         | 1.89%   |
| 11      | 3         | 1.42%   |
| 10      | 3         | 1.42%   |
| 52      | 2         | 0.94%   |
| 22      | 2         | 0.94%   |
| 43      | 1         | 0.47%   |
| 42      | 1         | 0.47%   |
| 40      | 1         | 0.47%   |
| 28      | 1         | 0.47%   |
| 26      | 1         | 0.47%   |
| 20      | 1         | 0.47%   |
| 18      | 1         | 0.47%   |
| 9       | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 32.38%  |
| 201-300     | 40        | 19.05%  |
| 501-600     | 38        | 18.1%   |
| Unknown     | 21        | 10%     |
| 401-500     | 20        | 9.52%   |
| 351-400     | 11        | 5.24%   |
| 601-700     | 7         | 3.33%   |
| 1001-1500   | 2         | 0.95%   |
| 901-1000    | 2         | 0.95%   |
| 801-900     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 71.94%  |
| 16/10   | 22        | 11.22%  |
| Unknown | 19        | 9.69%   |
| 5/4     | 7         | 3.57%   |
| 3/2     | 5         | 2.55%   |
| 4/3     | 1         | 0.51%   |
| 21/9    | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 43        | 20.38%  |
| 201-250        | 35        | 16.59%  |
| 91-100         | 29        | 13.74%  |
| Unknown        | 21        | 9.95%   |
| 61-70          | 15        | 7.11%   |
| 151-200        | 13        | 6.16%   |
| 301-350        | 12        | 5.69%   |
| 121-130        | 7         | 3.32%   |
| 351-500        | 5         | 2.37%   |
| 101-110        | 5         | 2.37%   |
| 71-80          | 4         | 1.9%    |
| 41-50          | 4         | 1.9%    |
| 251-300        | 4         | 1.9%    |
| 141-150        | 4         | 1.9%    |
| 51-60          | 3         | 1.42%   |
| 501-1000       | 3         | 1.42%   |
| More than 1000 | 2         | 0.95%   |
| 111-120        | 2         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 70        | 33.49%  |
| 51-100        | 53        | 25.36%  |
| 101-120       | 48        | 22.97%  |
| Unknown       | 21        | 10.05%  |
| 161-240       | 11        | 5.26%   |
| More than 240 | 4         | 1.91%   |
| 1-50          | 2         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 440       | 67.07%  |
| 1     | 195       | 29.73%  |
| 2     | 18        | 2.74%   |
| 3     | 3         | 0.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 465       | 50%     |
| Realtek Semiconductor             | 232       | 24.95%  |
| Broadcom                          | 69        | 7.42%   |
| Qualcomm Atheros                  | 58        | 6.24%   |
| Mellanox Technologies             | 9         | 0.97%   |
| AMD                               | 8         | 0.86%   |
| TP-Link                           | 6         | 0.65%   |
| Marvell Technology Group          | 6         | 0.65%   |
| D-Link System                     | 6         | 0.65%   |
| Ralink Technology                 | 5         | 0.54%   |
| MediaTek                          | 5         | 0.54%   |
| IMC Networks                      | 5         | 0.54%   |
| Sierra Wireless                   | 4         | 0.43%   |
| Xiaomi                            | 3         | 0.32%   |
| VIA Technologies                  | 3         | 0.32%   |
| Ralink                            | 3         | 0.32%   |
| Qualcomm                          | 3         | 0.32%   |
| Nvidia                            | 3         | 0.32%   |
| Huawei Technologies               | 3         | 0.32%   |
| Edimax Technology                 | 3         | 0.32%   |
| Dell                              | 3         | 0.32%   |
| Chelsio Communications            | 3         | 0.32%   |
| Apple                             | 3         | 0.32%   |
| Samsung Electronics               | 2         | 0.22%   |
| Qualcomm Atheros Communications   | 2         | 0.22%   |
| QLogic                            | 2         | 0.22%   |
| Emulex                            | 2         | 0.22%   |
| Aquantia                          | 2         | 0.22%   |
| American Megatrends               | 2         | 0.22%   |
| 3Com                              | 2         | 0.22%   |
| Silicom                           | 1         | 0.11%   |
| Sagem                             | 1         | 0.11%   |
| National Semiconductor            | 1         | 0.11%   |
| Mobile                            | 1         | 0.11%   |
| Microchip Technology              | 1         | 0.11%   |
| Hewlett-Packard                   | 1         | 0.11%   |
| Ericsson Business Mobile Networks | 1         | 0.11%   |
| Accton Technology                 | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 183       | 15.53%  |
| Intel I211 Gigabit Network Connection                                         | 71        | 6.03%   |
| Intel I210 Gigabit Network Connection                                         | 36        | 3.06%   |
| Intel Ethernet Controller I226-V                                              | 32        | 2.72%   |
| Intel Ethernet Controller I225-V                                              | 31        | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 29        | 2.46%   |
| Intel 82574L Gigabit Network Connection                                       | 27        | 2.29%   |
| Intel I350 Gigabit Network Connection                                         | 23        | 1.95%   |
| Realtek RTL8125 2.5GbE Controller                                             | 20        | 1.7%    |
| Intel Ethernet Connection I217-LM                                             | 20        | 1.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 18        | 1.53%   |
| Intel Wi-Fi 6 AX200                                                           | 15        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                                         | 15        | 1.27%   |
| Intel Wireless 8265 / 8275                                                    | 14        | 1.19%   |
| Intel Wireless 7265                                                           | 14        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 10        | 0.85%   |
| Intel Wireless 8260                                                           | 10        | 0.85%   |
| Intel Wireless 7260                                                           | 10        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 10        | 0.85%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10        | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 9         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                          | 9         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 9         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 0.68%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 8         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 8         | 0.68%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 0.68%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 0.68%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 8         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7         | 0.59%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 7         | 0.59%   |
| Intel Wireless 3165                                                           | 7         | 0.59%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 7         | 0.59%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 7         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 7         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                         | 7         | 0.59%   |
| Intel 82579V Gigabit Network Connection                                       | 7         | 0.59%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 7         | 0.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 7         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 169       | 54.34%  |
| Qualcomm Atheros                | 50        | 16.08%  |
| Realtek Semiconductor           | 37        | 11.9%   |
| Broadcom                        | 21        | 6.75%   |
| TP-Link                         | 6         | 1.93%   |
| Ralink Technology               | 5         | 1.61%   |
| MediaTek                        | 5         | 1.61%   |
| IMC Networks                    | 5         | 1.61%   |
| Ralink                          | 3         | 0.96%   |
| Edimax Technology               | 3         | 0.96%   |
| Qualcomm Atheros Communications | 2         | 0.64%   |
| Dell                            | 2         | 0.64%   |
| Sierra Wireless                 | 1         | 0.32%   |
| Sagem                           | 1         | 0.32%   |
| Accton Technology               | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 15        | 4.78%   |
| Intel Wireless 8265 / 8275                                     | 14        | 4.46%   |
| Intel Wireless 7265                                            | 14        | 4.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 3.18%   |
| Intel Wireless 8260                                            | 10        | 3.18%   |
| Intel Wireless 7260                                            | 10        | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 3.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 8         | 2.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 2.23%   |
| Intel Wireless 3165                                            | 7         | 2.23%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 7         | 2.23%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 7         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 1.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6         | 1.91%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.91%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 1.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5         | 1.59%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 5         | 1.59%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 0.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 3         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.96%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3         | 0.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 0.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.64%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.64%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 2         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 396       | 54.7%   |
| Realtek Semiconductor    | 215       | 29.7%   |
| Broadcom                 | 50        | 6.91%   |
| Qualcomm Atheros         | 12        | 1.66%   |
| AMD                      | 8         | 1.1%    |
| Marvell Technology Group | 6         | 0.83%   |
| D-Link System            | 6         | 0.83%   |
| Xiaomi                   | 3         | 0.41%   |
| VIA Technologies         | 3         | 0.41%   |
| Qualcomm                 | 3         | 0.41%   |
| Nvidia                   | 3         | 0.41%   |
| Samsung Electronics      | 2         | 0.28%   |
| QLogic                   | 2         | 0.28%   |
| Emulex                   | 2         | 0.28%   |
| Chelsio Communications   | 2         | 0.28%   |
| Aquantia                 | 2         | 0.28%   |
| Apple                    | 2         | 0.28%   |
| American Megatrends      | 2         | 0.28%   |
| 3Com                     | 2         | 0.28%   |
| Silicom                  | 1         | 0.14%   |
| National Semiconductor   | 1         | 0.14%   |
| Mobile                   | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 183       | 21.76%  |
| Intel I211 Gigabit Network Connection                                         | 71        | 8.44%   |
| Intel I210 Gigabit Network Connection                                         | 36        | 4.28%   |
| Intel Ethernet Controller I226-V                                              | 32        | 3.8%    |
| Intel Ethernet Controller I225-V                                              | 31        | 3.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 29        | 3.45%   |
| Intel 82574L Gigabit Network Connection                                       | 27        | 3.21%   |
| Intel I350 Gigabit Network Connection                                         | 23        | 2.73%   |
| Realtek RTL8125 2.5GbE Controller                                             | 20        | 2.38%   |
| Intel Ethernet Connection I217-LM                                             | 20        | 2.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 18        | 2.14%   |
| Intel Ethernet Connection (2) I219-LM                                         | 15        | 1.78%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10        | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                          | 9         | 1.07%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 8         | 0.95%   |
| Intel 82576 Gigabit Network Connection                                        | 8         | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 8         | 0.95%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 8         | 0.95%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 7         | 0.83%   |
| Intel Ethernet Connection (7) I219-LM                                         | 7         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                         | 7         | 0.83%   |
| Intel 82579V Gigabit Network Connection                                       | 7         | 0.83%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 7         | 0.83%   |
| AMD XGMAC 10GbE Controller                                                    | 7         | 0.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 6         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                                          | 6         | 0.71%   |
| Intel Ethernet Connection (2) I219-V                                          | 6         | 0.71%   |
| Intel Ethernet Connection (11) I219-V                                         | 6         | 0.71%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 6         | 0.71%   |
| Realtek USB 2.5GbE Controller                                                 | 5         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 0.59%   |
| Intel Ethernet Controller I225-LM                                             | 5         | 0.59%   |
| Intel Ethernet Connection X553 1GbE                                           | 5         | 0.59%   |
| Intel Ethernet Connection I219-LM                                             | 5         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                          | 5         | 0.59%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 5         | 0.59%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 4         | 0.48%   |
| Intel Ethernet Controller X550                                                | 4         | 0.48%   |
| Intel Ethernet Connection X553 10 GbE SFP+                                    | 4         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 614       | 66.52%  |
| WiFi     | 286       | 30.99%  |
| Unknown  | 19        | 2.06%   |
| Modem    | 4         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 550       | 83.59%  |
| WiFi     | 108       | 16.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 235       | 35.99%  |
| 1     | 117       | 17.92%  |
| 4     | 111       | 17%     |
| 3     | 86        | 13.17%  |
| 6     | 38        | 5.82%   |
| 5     | 33        | 5.05%   |
| 8     | 10        | 1.53%   |
| 7     | 6         | 0.92%   |
| 9     | 5         | 0.77%   |
| 0     | 5         | 0.77%   |
| 12    | 2         | 0.31%   |
| 10    | 2         | 0.31%   |
| 14    | 1         | 0.15%   |
| 13    | 1         | 0.15%   |
| 11    | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 518       | 76.51%  |
| Yes  | 159       | 23.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 123       | 62.76%  |
| Realtek Semiconductor           | 16        | 8.16%   |
| Apple                           | 12        | 6.12%   |
| Broadcom                        | 10        | 5.1%    |
| IMC Networks                    | 8         | 4.08%   |
| Qualcomm Atheros Communications | 6         | 3.06%   |
| Cambridge Silicon Radio         | 4         | 2.04%   |
| MediaTek                        | 3         | 1.53%   |
| Foxconn / Hon Hai               | 3         | 1.53%   |
| Dell                            | 3         | 1.53%   |
| Hewlett-Packard                 | 2         | 1.02%   |
| TP-Link                         | 1         | 0.51%   |
| Sino Wealth Electronic          | 1         | 0.51%   |
| HTC (High Tech Computer)        | 1         | 0.51%   |
| Creative Technology             | 1         | 0.51%   |
| ASUSTek Computer                | 1         | 0.51%   |
| AMPAK Technology                | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 43        | 21.94%  |
| Intel AX201 Bluetooth                                                | 18        | 9.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 17        | 8.67%   |
| Intel AX200 Bluetooth                                                | 13        | 6.63%   |
| Realtek Bluetooth Adapter                                            | 12        | 6.12%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 8         | 4.08%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 6         | 3.06%   |
| Intel AX211 Bluetooth                                                | 6         | 3.06%   |
| Intel AX210 Bluetooth                                                | 6         | 3.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5         | 2.55%   |
| Apple Bluetooth Host Controller                                      | 5         | 2.55%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                          | 4         | 2.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4         | 2.04%   |
| Apple Broadcom Built-in Bluetooth                                    | 4         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 3         | 1.53%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 2         | 1.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 2         | 1.02%   |
| Foxconn / Hon Hai Bluetooth USB Module                               | 2         | 1.02%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                          | 2         | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 1.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 2         | 1.02%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.02%   |
| TP-Link Bluetooth 5.0 USB Adapter                                    | 1         | 0.51%   |
| Sino Wealth Electronic RK Bluetooth Keyboar                          | 1         | 0.51%   |
| Realtek Bluetooth 5.1 Adapter                                        | 1         | 0.51%   |
| Realtek Bluetooth 4.0 Adapter                                        | 1         | 0.51%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                               | 1         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 1         | 0.51%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth                        | 1         | 0.51%   |
| Qualcomm Atheros Dell Wireless 1601 Bluetooth Device                 | 1         | 0.51%   |
| Qualcomm Atheros Bluetooth                                           | 1         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1         | 0.51%   |
| MediaTek Wireless_Device                                             | 1         | 0.51%   |
| MediaTek RZ608 Bluetooth Adapter                                     | 1         | 0.51%   |
| MediaTek Bluetooth Adapter                                           | 1         | 0.51%   |
| IMC Networks Realtek Bluetooth Adapter                               | 1         | 0.51%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS                     | 1         | 0.51%   |
| IMC Networks MediaTek Bluetooth Adapter                              | 1         | 0.51%   |
| IMC Networks Bluetooth Radio                                         | 1         | 0.51%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 413       | 68.38%  |
| AMD                                          | 91        | 15.07%  |
| Nvidia                                       | 57        | 9.44%   |
| GN Netcom                                    | 6         | 0.99%   |
| C-Media Electronics                          | 6         | 0.99%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.83%   |
| Logitech                                     | 4         | 0.66%   |
| Lenovo                                       | 3         | 0.5%    |
| Texas Instruments                            | 2         | 0.33%   |
| Kingston Technology                          | 2         | 0.33%   |
| Focusrite-Novation                           | 2         | 0.33%   |
| Creative Labs                                | 2         | 0.33%   |
| ASUSTek Computer                             | 2         | 0.33%   |
| VIA Technologies                             | 1         | 0.17%   |
| Sony                                         | 1         | 0.17%   |
| MOONDROP                                     | 1         | 0.17%   |
| Micronas                                     | 1         | 0.17%   |
| Mark of the Unicorn                          | 1         | 0.17%   |
| iCreate Technologies                         | 1         | 0.17%   |
| Giga-Byte Technology                         | 1         | 0.17%   |
| ESS Technology                               | 1         | 0.17%   |
| DSEA A/S                                     | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series HD Audio Controller                                                                | 33        | 4.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 4.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 4.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 3.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 28        | 3.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 24        | 3.27%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 23        | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 22        | 3%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 3%      |
| Intel Jasper Lake HD Audio                                                                        | 19        | 2.59%   |
| AMD FCH Azalia Controller                                                                         | 19        | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 2.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 18        | 2.46%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 2.46%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 18        | 2.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 2.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 1.91%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 1.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 1.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.09%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 0.82%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 5         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.55%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 135       | 21.19%  |
| SK hynix            | 92        | 14.44%  |
| Crucial             | 59        | 9.26%   |
| Kingston            | 58        | 9.11%   |
| Micron Technology   | 53        | 8.32%   |
| Unknown             | 52        | 8.16%   |
| Corsair             | 52        | 8.16%   |
| G.Skill             | 35        | 5.49%   |
| Unknown             | 13        | 2.04%   |
| Transcend           | 12        | 1.88%   |
| Nanya Technology    | 11        | 1.73%   |
| Elpida              | 10        | 1.57%   |
| Unknown (ABCD)      | 7         | 1.1%    |
| Kimtigo             | 5         | 0.78%   |
| A-DATA Technology   | 5         | 0.78%   |
| Ramaxel Technology  | 4         | 0.63%   |
| Wodposit            | 3         | 0.47%   |
| ATP                 | 3         | 0.47%   |
| Patriot             | 2         | 0.31%   |
| Hewlett-Packard     | 2         | 0.31%   |
| Avant               | 2         | 0.31%   |
| Atermiter           | 2         | 0.31%   |
| Apacer              | 2         | 0.31%   |
| 48spaces            | 2         | 0.31%   |
| V-Color             | 1         | 0.16%   |
| Unknown (0x0C6E)    | 1         | 0.16%   |
| Unknown (0x0080)    | 1         | 0.16%   |
| Unknown (0B38)      | 1         | 0.16%   |
| Toshiba             | 1         | 0.16%   |
| Teikon              | 1         | 0.16%   |
| TakeMS              | 1         | 0.16%   |
| SHARETRONIC         | 1         | 0.16%   |
| OCZ                 | 1         | 0.16%   |
| Lexar Co Limited    | 1         | 0.16%   |
| Kllisre             | 1         | 0.16%   |
| KingFast            | 1         | 0.16%   |
| Kembona             | 1         | 0.16%   |
| Goldenmars          | 1         | 0.16%   |
| CSX                 | 1         | 0.16%   |
| 2B0B00000000        | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 13        | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 9         | 1.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 8         | 1.18%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 7         | 1.03%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 6         | 0.89%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 6         | 0.89%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s          | 6         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 5         | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 0.74%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 4         | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 4         | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 4         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 4         | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 4         | 0.59%   |
| Samsung RAM M393A4K40CB2-CTD 32GB DIMM DDR4 2667MT/s           | 4         | 0.59%   |
| Kingston RAM KHX1600C9S3L/4G 4GB SODIMM DDR3 1600MT/s          | 4         | 0.59%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 4         | 0.59%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 3         | 0.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 3         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                    | 3         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 3         | 0.44%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 3         | 0.44%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 3         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s         | 3         | 0.44%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 3         | 0.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 3         | 0.44%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s            | 3         | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.44%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2400MT/s         | 3         | 0.44%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 1600MT/s            | 3         | 0.44%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 3         | 0.44%   |
| Samsung RAM 53D512M64D4RQ-046 4GB Row Of Chips LPDDR4 3200MT/s | 3         | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 3         | 0.44%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                 | 3         | 0.44%   |
| Corsair RAM CMSX16GX5M1A4800C40 16GB SODIMM DDR5 4800MT/s      | 3         | 0.44%   |
| Corsair RAM CMSX16GX4M1A3200C22 16GB SODIMM DDR4 3200MT/s      | 3         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 243       | 42.93%  |
| DDR4    | 237       | 41.87%  |
| DDR2    | 25        | 4.42%   |
| DDR5    | 19        | 3.36%   |
| LPDDR4  | 14        | 2.47%   |
| Unknown | 14        | 2.47%   |
| LPDDR3  | 7         | 1.24%   |
| LPDDR5  | 5         | 0.88%   |
| SDRAM   | 2         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 305       | 53.6%   |
| DIMM         | 238       | 41.83%  |
| Row Of Chips | 18        | 3.16%   |
| Unknown      | 4         | 0.7%    |
| Chip         | 3         | 0.53%   |
| FB-DIMM      | 1         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 205       | 33.55%  |
| 4096  | 194       | 31.75%  |
| 16384 | 99        | 16.2%   |
| 2048  | 71        | 11.62%  |
| 32768 | 22        | 3.6%    |
| 1024  | 16        | 2.62%   |
| 49152 | 2         | 0.33%   |
| 32767 | 2         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 161       | 27.06%  |
| 3200    | 84        | 14.12%  |
| 1333    | 77        | 12.94%  |
| 2400    | 66        | 11.09%  |
| 2667    | 56        | 9.41%   |
| 2133    | 38        | 6.39%   |
| 800     | 18        | 3.03%   |
| 4800    | 13        | 2.18%   |
| 1334    | 13        | 2.18%   |
| 2666    | 12        | 2.02%   |
| 667     | 12        | 2.02%   |
| 5600    | 6         | 1.01%   |
| 6400    | 5         | 0.84%   |
| 1867    | 5         | 0.84%   |
| Unknown | 5         | 0.84%   |
| 1066    | 4         | 0.67%   |
| 1067    | 3         | 0.5%    |
| 5200    | 2         | 0.34%   |
| 4267    | 2         | 0.34%   |
| 3600    | 2         | 0.34%   |
| 975     | 2         | 0.34%   |
| 533     | 2         | 0.34%   |
| 3000    | 1         | 0.17%   |
| 2933    | 1         | 0.17%   |
| 1866    | 1         | 0.17%   |
| 1400    | 1         | 0.17%   |
| 1332    | 1         | 0.17%   |
| 1200    | 1         | 0.17%   |
| 400     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Dymo-CoStar | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson Printer                  | 1         | 33.33%  |
| Dymo-CoStar LabelWriter 450          | 1         | 33.33%  |
| Dymo-CoStar DYMO LabelWriter 450 DUO | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 50%     |
| Canon CanoScan 9000F   | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 28.57%  |
| Sunplus Innovation Technology          | 12        | 9.02%   |
| Microdia                               | 12        | 9.02%   |
| Bison Electronics                      | 11        | 8.27%   |
| Realtek Semiconductor                  | 10        | 7.52%   |
| IMC Networks                           | 10        | 7.52%   |
| Logitech                               | 7         | 5.26%   |
| Syntek                                 | 5         | 3.76%   |
| Lite-On Technology                     | 5         | 3.76%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.76%   |
| ARC International                      | 4         | 3.01%   |
| Quanta                                 | 3         | 2.26%   |
| Suyin                                  | 2         | 1.5%    |
| Alcor Micro                            | 2         | 1.5%    |
| Z-Star Microelectronics                | 1         | 0.75%   |
| ValueHD                                | 1         | 0.75%   |
| SIMPLO Technology                      | 1         | 0.75%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.75%   |
| Novatek Microelectronics               | 1         | 0.75%   |
| Foxconn / Hon Hai                      | 1         | 0.75%   |
| Apple                                  | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 14        | 10.45%  |
| Bison Integrated Camera                               | 7         | 5.22%   |
| Microdia Integrated_Webcam_HD                         | 6         | 4.48%   |
| Sunplus Integrated_Webcam_HD                          | 5         | 3.73%   |
| Logitech Webcam C270                                  | 5         | 3.73%   |
| Syntek Integrated Camera                              | 4         | 2.99%   |
| Realtek Integrated_Webcam_HD                          | 4         | 2.99%   |
| Microdia Integrated Webcam                            | 4         | 2.99%   |
| Chicony HD WebCam                                     | 4         | 2.99%   |
| ARC International Camera                              | 4         | 2.99%   |
| Lite-On Integrated Camera                             | 3         | 2.24%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 3         | 2.24%   |
| Realtek USB Camera                                    | 2         | 1.49%   |
| Logitech C922 Pro Stream Webcam                       | 2         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 2         | 1.49%   |
| IMC Networks Realtek PC Camera                        | 2         | 1.49%   |
| IMC Networks Integrated Camera                        | 2         | 1.49%   |
| IMC Networks EasyCamera                               | 2         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD                       | 2         | 1.49%   |
| Chicony Realtek DMFT RGB                              | 2         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam   | 2         | 1.49%   |
| Bison SunplusIT Integrated Camera                     | 2         | 1.49%   |
| Z-Star Webcam                                         | 1         | 0.75%   |
| ValueHD HD Camera                                     | 1         | 0.75%   |
| Syntek Lenovo EasyCamera                              | 1         | 0.75%   |
| Suyin USB 2.0 Camera                                  | 1         | 0.75%   |
| Suyin Laptop_Integrated_Webcam_FHD                    | 1         | 0.75%   |
| Sunplus Laptop_Integrated_Webcam_HD                   | 1         | 0.75%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 0.75%   |
| Sunplus Integrated_Webcam_FHD                         | 1         | 0.75%   |
| Sunplus Integrated HD Webcam                          | 1         | 0.75%   |
| Sunplus Hy HD Camera                                  | 1         | 0.75%   |
| Sunplus Dell Integrated Webcam                        | 1         | 0.75%   |
| Sunplus Asus Webcam                                   | 1         | 0.75%   |
| SIMPLO USB 2.0 Camera                                 | 1         | 0.75%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 0.75%   |
| Realtek USB 2.0 PC Camera                             | 1         | 0.75%   |
| Realtek Lenovo EasyCamera                             | 1         | 0.75%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 0.75%   |
| Realtek Integrated Webcam HD                          | 1         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 32.5%   |
| Synaptics                  | 8         | 20%     |
| AuthenTec                  | 6         | 15%     |
| Elan Microelectronics      | 4         | 10%     |
| Shenzhen Goodix Technology | 3         | 7.5%    |
| LighTuning Technology      | 3         | 7.5%    |
| Upek                       | 2         | 5%      |
| Broadcom                   | 1         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 6         | 15%     |
| Elan Fingerprint Sensor                                                      | 4         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 7.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 7.5%    |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 7.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 5%      |
| Validity Sensors Synaptics WBDI                                              | 2         | 5%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 2         | 5%      |
| AuthenTec AES2810                                                            | 2         | 5%      |
| AuthenTec AES1660                                                            | 2         | 5%      |
| Validity Sensors VFS491                                                      | 1         | 2.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 2.5%    |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 2.5%    |
| Synaptics UWP WBDI Device                                                    | 1         | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 2.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.5%    |
| AuthenTec AES2550 Fingerprint Sensor                                         | 1         | 2.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.5%    |

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
| 1     | 287       | 42.58%  |
| 0     | 171       | 25.37%  |
| 2     | 126       | 18.69%  |
| 3     | 57        | 8.46%   |
| 4     | 25        | 3.71%   |
| 6     | 4         | 0.59%   |
| 5     | 3         | 0.45%   |
| 7     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 423       | 57.47%  |
| Bluetooth                | 93        | 12.64%  |
| Net/wireless             | 80        | 10.87%  |
| Card reader              | 38        | 5.16%   |
| Fingerprint reader       | 32        | 4.35%   |
| Firewire controller      | 26        | 3.53%   |
| Sound                    | 11        | 1.49%   |
| Net/ethernet             | 11        | 1.49%   |
| Graphics card            | 8         | 1.09%   |
| Storage                  | 6         | 0.82%   |
| Storage/raid             | 3         | 0.41%   |
| Network                  | 3         | 0.41%   |
| Storage/ata              | 1         | 0.14%   |
| Modem                    | 1         | 0.14%   |

