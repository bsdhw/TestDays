BSD in USA - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for BSD in USA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/USA/Desktop/README.md) and [notebooks](/Location/USA/Notebook/README.md).

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

Total: 5229

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Google        | Auron_Paine                 | Notebook    | [021624028a](https://bsd-hardware.info/?probe=021624028a) | Oct 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7a6b97e997](https://bsd-hardware.info/?probe=7a6b97e997) | Oct 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [da12fe3c05](https://bsd-hardware.info/?probe=da12fe3c05) | Oct 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6975204e47](https://bsd-hardware.info/?probe=6975204e47) | Oct 01, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [f97e242e6b](https://bsd-hardware.info/?probe=f97e242e6b) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [b5caabfd31](https://bsd-hardware.info/?probe=b5caabfd31) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [7a1378a001](https://bsd-hardware.info/?probe=7a1378a001) | Oct 01, 2023 |
| Win elemen... | M600                        | Desktop     | [93cc6a1173](https://bsd-hardware.info/?probe=93cc6a1173) | Oct 01, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [604bce28c1](https://bsd-hardware.info/?probe=604bce28c1) | Sep 30, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [fc2ba7c8d8](https://bsd-hardware.info/?probe=fc2ba7c8d8) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [abc175c93b](https://bsd-hardware.info/?probe=abc175c93b) | Sep 30, 2023 |
| Win elemen... | M600                        | Desktop     | [5b7606e786](https://bsd-hardware.info/?probe=5b7606e786) | Sep 30, 2023 |
| Acer          | F672CR R01-B1               | Desktop     | [2008598c7e](https://bsd-hardware.info/?probe=2008598c7e) | Sep 29, 2023 |
| Deciso        | Netboard A20                | Notebook    | [3877143e37](https://bsd-hardware.info/?probe=3877143e37) | Sep 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [cda7be3da8](https://bsd-hardware.info/?probe=cda7be3da8) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [6ed3c7314d](https://bsd-hardware.info/?probe=6ed3c7314d) | Sep 29, 2023 |
| HP            | 0B54h D                     | Desktop     | [55122a1908](https://bsd-hardware.info/?probe=55122a1908) | Sep 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0f1805a40e](https://bsd-hardware.info/?probe=0f1805a40e) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d86474bd03](https://bsd-hardware.info/?probe=d86474bd03) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [57577a5f14](https://bsd-hardware.info/?probe=57577a5f14) | Sep 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [8a4596eefa](https://bsd-hardware.info/?probe=8a4596eefa) | Sep 27, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [86abd76c4e](https://bsd-hardware.info/?probe=86abd76c4e) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | Notebook    | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [9ca318e043](https://bsd-hardware.info/?probe=9ca318e043) | Sep 27, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [0c56aeb6b5](https://bsd-hardware.info/?probe=0c56aeb6b5) | Sep 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d7cdc9b73e](https://bsd-hardware.info/?probe=d7cdc9b73e) | Sep 26, 2023 |
| HP            | 8055                        | Desktop     | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [3c10d0b8ed](https://bsd-hardware.info/?probe=3c10d0b8ed) | Sep 26, 2023 |
| HPE           | ProLiant DL20 Gen10         | Server      | [bc62c36654](https://bsd-hardware.info/?probe=bc62c36654) | Sep 25, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [231aedbf9e](https://bsd-hardware.info/?probe=231aedbf9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a77db6c46a](https://bsd-hardware.info/?probe=a77db6c46a) | Sep 25, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [6153909c9e](https://bsd-hardware.info/?probe=6153909c9e) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [5232e5837b](https://bsd-hardware.info/?probe=5232e5837b) | Sep 25, 2023 |
| CncTion       | N4505-4L B0                 | Desktop     | [5880a22b30](https://bsd-hardware.info/?probe=5880a22b30) | Sep 25, 2023 |
| Protectli     | VP4630                      | Desktop     | [d5c0fe73ef](https://bsd-hardware.info/?probe=d5c0fe73ef) | Sep 24, 2023 |
| MSI           | H81M-P33                    | Desktop     | [971f3fdba1](https://bsd-hardware.info/?probe=971f3fdba1) | Sep 24, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [6538212bd6](https://bsd-hardware.info/?probe=6538212bd6) | Sep 24, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f7aee1db53](https://bsd-hardware.info/?probe=f7aee1db53) | Sep 24, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [be147f7ff1](https://bsd-hardware.info/?probe=be147f7ff1) | Sep 24, 2023 |
| Protectli     | VP2420                      | Desktop     | [8644c80a4a](https://bsd-hardware.info/?probe=8644c80a4a) | Sep 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [d8ccddab5a](https://bsd-hardware.info/?probe=d8ccddab5a) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e1ef4a73c](https://bsd-hardware.info/?probe=3e1ef4a73c) | Sep 23, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [8386219e8f](https://bsd-hardware.info/?probe=8386219e8f) | Sep 22, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [5478cff8a7](https://bsd-hardware.info/?probe=5478cff8a7) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [423687627b](https://bsd-hardware.info/?probe=423687627b) | Sep 21, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [eae9f87345](https://bsd-hardware.info/?probe=eae9f87345) | Sep 20, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [398d7a6f26](https://bsd-hardware.info/?probe=398d7a6f26) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [6ee2f45613](https://bsd-hardware.info/?probe=6ee2f45613) | Sep 20, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [34bffe0ed1](https://bsd-hardware.info/?probe=34bffe0ed1) | Sep 20, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [60a616adf4](https://bsd-hardware.info/?probe=60a616adf4) | Sep 20, 2023 |
| HP            | 8522 A01                    | Mini pc     | [dd5d9863aa](https://bsd-hardware.info/?probe=dd5d9863aa) | Sep 19, 2023 |
| Shenzhen M... | RPBNB                       | Desktop     | [07698e61c2](https://bsd-hardware.info/?probe=07698e61c2) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ed7bef076e](https://bsd-hardware.info/?probe=ed7bef076e) | Sep 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7c6f946c9b](https://bsd-hardware.info/?probe=7c6f946c9b) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [0fe1aab1d8](https://bsd-hardware.info/?probe=0fe1aab1d8) | Sep 19, 2023 |
| Protectli     | VP2420                      | Desktop     | [c4599cac13](https://bsd-hardware.info/?probe=c4599cac13) | Sep 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [0a9c074970](https://bsd-hardware.info/?probe=0a9c074970) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5e7775568c](https://bsd-hardware.info/?probe=5e7775568c) | Sep 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [815d9f2867](https://bsd-hardware.info/?probe=815d9f2867) | Sep 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [e6e705b7cf](https://bsd-hardware.info/?probe=e6e705b7cf) | Sep 18, 2023 |
| Advantech     | NAMB-3250 A102-1            | Desktop     | [143c5f73fc](https://bsd-hardware.info/?probe=143c5f73fc) | Sep 17, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [35fbb60b50](https://bsd-hardware.info/?probe=35fbb60b50) | Sep 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [31455b0d33](https://bsd-hardware.info/?probe=31455b0d33) | Sep 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [31cf5dc87d](https://bsd-hardware.info/?probe=31cf5dc87d) | Sep 16, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [a054400ef6](https://bsd-hardware.info/?probe=a054400ef6) | Sep 16, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1f54d2bb5b](https://bsd-hardware.info/?probe=1f54d2bb5b) | Sep 16, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [a2d011d2d7](https://bsd-hardware.info/?probe=a2d011d2d7) | Sep 16, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d36ff6181c](https://bsd-hardware.info/?probe=d36ff6181c) | Sep 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3fcc5727d3](https://bsd-hardware.info/?probe=3fcc5727d3) | Sep 15, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6fc18e3db7](https://bsd-hardware.info/?probe=6fc18e3db7) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0c65fb5e8c](https://bsd-hardware.info/?probe=0c65fb5e8c) | Sep 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [9790cd72bc](https://bsd-hardware.info/?probe=9790cd72bc) | Sep 15, 2023 |
| Dell          | OptiPlex 3020               | Desktop     | [dfb6cce27d](https://bsd-hardware.info/?probe=dfb6cce27d) | Sep 14, 2023 |
| ASRock        | J1900D2Y                    | Desktop     | [2084583d47](https://bsd-hardware.info/?probe=2084583d47) | Sep 14, 2023 |
| ASRock        | J3455M                      | Desktop     | [f9809dfb0f](https://bsd-hardware.info/?probe=f9809dfb0f) | Sep 13, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [03a8809fe4](https://bsd-hardware.info/?probe=03a8809fe4) | Sep 13, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [7ba189ff8a](https://bsd-hardware.info/?probe=7ba189ff8a) | Sep 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5dee3a945f](https://bsd-hardware.info/?probe=5dee3a945f) | Sep 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [9fee6e83fc](https://bsd-hardware.info/?probe=9fee6e83fc) | Sep 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [ae320bd7de](https://bsd-hardware.info/?probe=ae320bd7de) | Sep 13, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [f3594b1f7c](https://bsd-hardware.info/?probe=f3594b1f7c) | Sep 13, 2023 |
| HP            | 212B                        | Desktop     | [3370718b29](https://bsd-hardware.info/?probe=3370718b29) | Sep 13, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [984a64677e](https://bsd-hardware.info/?probe=984a64677e) | Sep 13, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b0cd1ce0f4](https://bsd-hardware.info/?probe=b0cd1ce0f4) | Sep 13, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [54b04ea958](https://bsd-hardware.info/?probe=54b04ea958) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [89a601d720](https://bsd-hardware.info/?probe=89a601d720) | Sep 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7923196f55](https://bsd-hardware.info/?probe=7923196f55) | Sep 11, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [8b541c71a9](https://bsd-hardware.info/?probe=8b541c71a9) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [6610a56ab4](https://bsd-hardware.info/?probe=6610a56ab4) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [ccc62ac366](https://bsd-hardware.info/?probe=ccc62ac366) | Sep 10, 2023 |
| Intel         | NUC5i5MYBE H47797-205       | Mini pc     | [5ef436c661](https://bsd-hardware.info/?probe=5ef436c661) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [525ed7878c](https://bsd-hardware.info/?probe=525ed7878c) | Sep 10, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [0131f46755](https://bsd-hardware.info/?probe=0131f46755) | Sep 10, 2023 |
| AZW           | EQ                          | Desktop     | [c6f83de1e4](https://bsd-hardware.info/?probe=c6f83de1e4) | Sep 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [57a847859f](https://bsd-hardware.info/?probe=57a847859f) | Sep 10, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b7e0d87f47](https://bsd-hardware.info/?probe=b7e0d87f47) | Sep 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c2378b3e83](https://bsd-hardware.info/?probe=c2378b3e83) | Sep 10, 2023 |
| Unknown       | QGLK03                      | Desktop     | [42ea8dfb44](https://bsd-hardware.info/?probe=42ea8dfb44) | Sep 10, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [52764da7d8](https://bsd-hardware.info/?probe=52764da7d8) | Sep 10, 2023 |
| Supermicro    | X10SLM-F                    | Desktop     | [332a3f8516](https://bsd-hardware.info/?probe=332a3f8516) | Sep 09, 2023 |
| Supermicro    | X8DTH-i/6/iF/6F             | Desktop     | [df114e1b94](https://bsd-hardware.info/?probe=df114e1b94) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [8579d5fa0d](https://bsd-hardware.info/?probe=8579d5fa0d) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [7ea278ed7a](https://bsd-hardware.info/?probe=7ea278ed7a) | Sep 09, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [331f3de91a](https://bsd-hardware.info/?probe=331f3de91a) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [ee507594a0](https://bsd-hardware.info/?probe=ee507594a0) | Sep 09, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [252fc12d3b](https://bsd-hardware.info/?probe=252fc12d3b) | Sep 09, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d197cf04](https://bsd-hardware.info/?probe=07d197cf04) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e51c11ed2](https://bsd-hardware.info/?probe=2e51c11ed2) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [480823e372](https://bsd-hardware.info/?probe=480823e372) | Sep 08, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [122601f717](https://bsd-hardware.info/?probe=122601f717) | Sep 08, 2023 |
| AZW           | MINI S 10                   | Desktop     | [4580cb5481](https://bsd-hardware.info/?probe=4580cb5481) | Sep 08, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [aaeb12b1c6](https://bsd-hardware.info/?probe=aaeb12b1c6) | Sep 08, 2023 |
| Protectli     | VP2420                      | Desktop     | [2a8eb1b056](https://bsd-hardware.info/?probe=2a8eb1b056) | Sep 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [fa747c859f](https://bsd-hardware.info/?probe=fa747c859f) | Sep 08, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [a3e54e7628](https://bsd-hardware.info/?probe=a3e54e7628) | Sep 08, 2023 |
| HP            | 8158 A01                    | Mini pc     | [ae22c1bea5](https://bsd-hardware.info/?probe=ae22c1bea5) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [eff74e8df0](https://bsd-hardware.info/?probe=eff74e8df0) | Sep 07, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [7c0acfa5b9](https://bsd-hardware.info/?probe=7c0acfa5b9) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [94d9b19ade](https://bsd-hardware.info/?probe=94d9b19ade) | Sep 07, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b5aa3f010f](https://bsd-hardware.info/?probe=b5aa3f010f) | Sep 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [12145f939b](https://bsd-hardware.info/?probe=12145f939b) | Sep 07, 2023 |
| Dell          | 0KM5PX A01                  | Server      | [67f910daa9](https://bsd-hardware.info/?probe=67f910daa9) | Sep 06, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [4397f70291](https://bsd-hardware.info/?probe=4397f70291) | Sep 06, 2023 |
| AZW           | MINI S 10                   | Desktop     | [2daf516a05](https://bsd-hardware.info/?probe=2daf516a05) | Sep 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0b7d85b124](https://bsd-hardware.info/?probe=0b7d85b124) | Sep 06, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | Notebook    | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [3af68f2594](https://bsd-hardware.info/?probe=3af68f2594) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ec3e0338eb](https://bsd-hardware.info/?probe=ec3e0338eb) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [84d768ee15](https://bsd-hardware.info/?probe=84d768ee15) | Sep 05, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3fb536ecce](https://bsd-hardware.info/?probe=3fb536ecce) | Sep 05, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [67e9eafa7e](https://bsd-hardware.info/?probe=67e9eafa7e) | Sep 05, 2023 |
| Dell          | 0X3D66 A02                  | Server      | [8dcfb77863](https://bsd-hardware.info/?probe=8dcfb77863) | Sep 05, 2023 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [e92272bb87](https://bsd-hardware.info/?probe=e92272bb87) | Sep 05, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [bff90e93d0](https://bsd-hardware.info/?probe=bff90e93d0) | Sep 05, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [00dd1bd84e](https://bsd-hardware.info/?probe=00dd1bd84e) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [a4796e8170](https://bsd-hardware.info/?probe=a4796e8170) | Sep 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [8cc0358a69](https://bsd-hardware.info/?probe=8cc0358a69) | Sep 04, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [dd32d9d4e1](https://bsd-hardware.info/?probe=dd32d9d4e1) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [7d95befe6e](https://bsd-hardware.info/?probe=7d95befe6e) | Sep 04, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [1b07865ce7](https://bsd-hardware.info/?probe=1b07865ce7) | Sep 04, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [58e061f420](https://bsd-hardware.info/?probe=58e061f420) | Sep 03, 2023 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fe53c55492](https://bsd-hardware.info/?probe=fe53c55492) | Sep 03, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b47290007a](https://bsd-hardware.info/?probe=b47290007a) | Sep 03, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ef4604a40f](https://bsd-hardware.info/?probe=ef4604a40f) | Sep 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8d37c44440](https://bsd-hardware.info/?probe=8d37c44440) | Sep 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| AAEON         | FWS-2363 V1.0               | Desktop     | [098bc5466b](https://bsd-hardware.info/?probe=098bc5466b) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [1ae33cfe72](https://bsd-hardware.info/?probe=1ae33cfe72) | Sep 02, 2023 |
| ASRock        | J3455M                      | Desktop     | [762d4d9370](https://bsd-hardware.info/?probe=762d4d9370) | Sep 02, 2023 |
| Dell          | 0XCR8D A00                  | Desktop     | [b89126c9d9](https://bsd-hardware.info/?probe=b89126c9d9) | Sep 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [b63ded7b81](https://bsd-hardware.info/?probe=b63ded7b81) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [94487109c2](https://bsd-hardware.info/?probe=94487109c2) | Sep 01, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [708af02c7b](https://bsd-hardware.info/?probe=708af02c7b) | Sep 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [5e44dfed67](https://bsd-hardware.info/?probe=5e44dfed67) | Sep 01, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [9e6cb6fe25](https://bsd-hardware.info/?probe=9e6cb6fe25) | Sep 01, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [525a1718ff](https://bsd-hardware.info/?probe=525a1718ff) | Sep 01, 2023 |
| Shuttle       | FS77U                       | Desktop     | [149a8a1437](https://bsd-hardware.info/?probe=149a8a1437) | Sep 01, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [8f54654916](https://bsd-hardware.info/?probe=8f54654916) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [d9f360b4fe](https://bsd-hardware.info/?probe=d9f360b4fe) | Aug 31, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [2557e04cf5](https://bsd-hardware.info/?probe=2557e04cf5) | Aug 31, 2023 |
| Intel         | NUC8i7HNB J68197-602        | Mini pc     | [f2806a3c65](https://bsd-hardware.info/?probe=f2806a3c65) | Aug 31, 2023 |
| Biostar       | A68N-5545                   | Desktop     | [b2a1070e2d](https://bsd-hardware.info/?probe=b2a1070e2d) | Aug 31, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [363a27fb74](https://bsd-hardware.info/?probe=363a27fb74) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [97975e788b](https://bsd-hardware.info/?probe=97975e788b) | Aug 30, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0119402f80](https://bsd-hardware.info/?probe=0119402f80) | Aug 30, 2023 |
| Infoblox      | IB-810                      | Desktop     | [34c0fa6bec](https://bsd-hardware.info/?probe=34c0fa6bec) | Aug 30, 2023 |
| Supermicro    | X12SDV-8C-SPT8FA            | Server      | [c46557f737](https://bsd-hardware.info/?probe=c46557f737) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [259a7ec99d](https://bsd-hardware.info/?probe=259a7ec99d) | Aug 30, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [20946147de](https://bsd-hardware.info/?probe=20946147de) | Aug 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [8cfa60050b](https://bsd-hardware.info/?probe=8cfa60050b) | Aug 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [c8b4f33fb1](https://bsd-hardware.info/?probe=c8b4f33fb1) | Aug 30, 2023 |
| Biostar       | A68N-5545                   | Desktop     | [c90edbc46a](https://bsd-hardware.info/?probe=c90edbc46a) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Supermicro    | X9DRD-iF                    | Desktop     | [be36f2fe2b](https://bsd-hardware.info/?probe=be36f2fe2b) | Aug 28, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e0d13077ea](https://bsd-hardware.info/?probe=e0d13077ea) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a84c23941d](https://bsd-hardware.info/?probe=a84c23941d) | Aug 27, 2023 |
| Protectli     | FW6                         | Desktop     | [37b744ff79](https://bsd-hardware.info/?probe=37b744ff79) | Aug 27, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c858f191cf](https://bsd-hardware.info/?probe=c858f191cf) | Aug 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2e9a066a01](https://bsd-hardware.info/?probe=2e9a066a01) | Aug 27, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [9898ae1ead](https://bsd-hardware.info/?probe=9898ae1ead) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0bb56ff672](https://bsd-hardware.info/?probe=0bb56ff672) | Aug 27, 2023 |
| HP            | 8103 A01                    | Mini pc     | [484d82cac6](https://bsd-hardware.info/?probe=484d82cac6) | Aug 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | Desktop     | [21e958a05d](https://bsd-hardware.info/?probe=21e958a05d) | Aug 26, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [bf289c5941](https://bsd-hardware.info/?probe=bf289c5941) | Aug 26, 2023 |
| HP            | 8299                        | Desktop     | [77a077cb11](https://bsd-hardware.info/?probe=77a077cb11) | Aug 26, 2023 |
| Pegatron      | 2ACD                        | Desktop     | [c20fcb2b2f](https://bsd-hardware.info/?probe=c20fcb2b2f) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c8e95f3772](https://bsd-hardware.info/?probe=c8e95f3772) | Aug 26, 2023 |
| Supermicro    | X10DRi-LN4+                 | Server      | [4978b62b97](https://bsd-hardware.info/?probe=4978b62b97) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f1a43ebe23](https://bsd-hardware.info/?probe=f1a43ebe23) | Aug 24, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [8d7f83c319](https://bsd-hardware.info/?probe=8d7f83c319) | Aug 24, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [9e555f0b24](https://bsd-hardware.info/?probe=9e555f0b24) | Aug 24, 2023 |
| Dell          | Latitude 7490               | Notebook    | [0b05de2297](https://bsd-hardware.info/?probe=0b05de2297) | Aug 24, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [d07ade15d2](https://bsd-hardware.info/?probe=d07ade15d2) | Aug 23, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [005e9c7b4c](https://bsd-hardware.info/?probe=005e9c7b4c) | Aug 23, 2023 |
| AZW           | EQ                          | Desktop     | [a43bd92291](https://bsd-hardware.info/?probe=a43bd92291) | Aug 23, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | Desktop     | [1fcc80636d](https://bsd-hardware.info/?probe=1fcc80636d) | Aug 22, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [962bf51507](https://bsd-hardware.info/?probe=962bf51507) | Aug 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ff55eb5161](https://bsd-hardware.info/?probe=ff55eb5161) | Aug 22, 2023 |
| Protectli     | FW4B                        | Desktop     | [6041b7e153](https://bsd-hardware.info/?probe=6041b7e153) | Aug 21, 2023 |
| Intel         | JSL MRD                     | Desktop     | [0f3ef76fb8](https://bsd-hardware.info/?probe=0f3ef76fb8) | Aug 21, 2023 |
| Cisco         | ASA5525 A0                  | Desktop     | [7c88ca29f7](https://bsd-hardware.info/?probe=7c88ca29f7) | Aug 21, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [e8eef1fb22](https://bsd-hardware.info/?probe=e8eef1fb22) | Aug 21, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [3941ce5fae](https://bsd-hardware.info/?probe=3941ce5fae) | Aug 21, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [c03bc6fa91](https://bsd-hardware.info/?probe=c03bc6fa91) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [0d69491bdd](https://bsd-hardware.info/?probe=0d69491bdd) | Aug 21, 2023 |
| MSI           | MEG X570 ACE                | Desktop     | [913cc77381](https://bsd-hardware.info/?probe=913cc77381) | Aug 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [e57d2d76d2](https://bsd-hardware.info/?probe=e57d2d76d2) | Aug 21, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [cf30fa594f](https://bsd-hardware.info/?probe=cf30fa594f) | Aug 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [e6bfadb400](https://bsd-hardware.info/?probe=e6bfadb400) | Aug 21, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [3194978ea5](https://bsd-hardware.info/?probe=3194978ea5) | Aug 20, 2023 |
| Dell          | 0D7449 A01                  | Server      | [33c9f97cb9](https://bsd-hardware.info/?probe=33c9f97cb9) | Aug 20, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [2beb3e34d8](https://bsd-hardware.info/?probe=2beb3e34d8) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [70c65a5a34](https://bsd-hardware.info/?probe=70c65a5a34) | Aug 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3296816fc1](https://bsd-hardware.info/?probe=3296816fc1) | Aug 20, 2023 |
| ASRock        | H110M-STX                   | Desktop     | [5c819b9ff1](https://bsd-hardware.info/?probe=5c819b9ff1) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [8b49278bbd](https://bsd-hardware.info/?probe=8b49278bbd) | Aug 19, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [c9c0312302](https://bsd-hardware.info/?probe=c9c0312302) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1bc7f67754](https://bsd-hardware.info/?probe=1bc7f67754) | Aug 18, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [b200aabc73](https://bsd-hardware.info/?probe=b200aabc73) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [f7c887c84f](https://bsd-hardware.info/?probe=f7c887c84f) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [e982da98d2](https://bsd-hardware.info/?probe=e982da98d2) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| MSI           | MS-7721                     | Desktop     | [678c81c8c1](https://bsd-hardware.info/?probe=678c81c8c1) | Aug 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [3521bed0e8](https://bsd-hardware.info/?probe=3521bed0e8) | Aug 18, 2023 |
| Unknown       | QSKL01                      | Desktop     | [b768029249](https://bsd-hardware.info/?probe=b768029249) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [c50e637bc2](https://bsd-hardware.info/?probe=c50e637bc2) | Aug 18, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [71fff01c39](https://bsd-hardware.info/?probe=71fff01c39) | Aug 18, 2023 |
| Protectli     | FW4B                        | Desktop     | [880c0c7069](https://bsd-hardware.info/?probe=880c0c7069) | Aug 18, 2023 |
| HP            | 1495                        | Desktop     | [556a339a7e](https://bsd-hardware.info/?probe=556a339a7e) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [a574d1cce5](https://bsd-hardware.info/?probe=a574d1cce5) | Aug 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [20348d2f47](https://bsd-hardware.info/?probe=20348d2f47) | Aug 17, 2023 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [6b85b4a31c](https://bsd-hardware.info/?probe=6b85b4a31c) | Aug 16, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [fcb3075158](https://bsd-hardware.info/?probe=fcb3075158) | Aug 16, 2023 |
| Dell          | 0F9NPY A00                  | Server      | [bc1b3da23f](https://bsd-hardware.info/?probe=bc1b3da23f) | Aug 16, 2023 |
| Dell          | 05KX61 A02                  | Server      | [2fe3211471](https://bsd-hardware.info/?probe=2fe3211471) | Aug 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [e457a41b4a](https://bsd-hardware.info/?probe=e457a41b4a) | Aug 16, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [3b5ddbcb06](https://bsd-hardware.info/?probe=3b5ddbcb06) | Aug 16, 2023 |
| CncTion       | J4125-4L-I225               | Desktop     | [269cfa2253](https://bsd-hardware.info/?probe=269cfa2253) | Aug 16, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [f710821a92](https://bsd-hardware.info/?probe=f710821a92) | Aug 16, 2023 |
| HP            | 18E7                        | Desktop     | [3c24defdf8](https://bsd-hardware.info/?probe=3c24defdf8) | Aug 16, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [9a8ad54cd3](https://bsd-hardware.info/?probe=9a8ad54cd3) | Aug 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [fc152ce8d4](https://bsd-hardware.info/?probe=fc152ce8d4) | Aug 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [86c4d1f8cf](https://bsd-hardware.info/?probe=86c4d1f8cf) | Aug 15, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [30c58f7403](https://bsd-hardware.info/?probe=30c58f7403) | Aug 15, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [be7bd4b126](https://bsd-hardware.info/?probe=be7bd4b126) | Aug 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [c11fdc1cf9](https://bsd-hardware.info/?probe=c11fdc1cf9) | Aug 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [99fd3696dd](https://bsd-hardware.info/?probe=99fd3696dd) | Aug 15, 2023 |
| AZW           | EQ                          | Desktop     | [5393736ae4](https://bsd-hardware.info/?probe=5393736ae4) | Aug 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [dbbd82bd80](https://bsd-hardware.info/?probe=dbbd82bd80) | Aug 15, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [472c17f992](https://bsd-hardware.info/?probe=472c17f992) | Aug 15, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [aba7b573c1](https://bsd-hardware.info/?probe=aba7b573c1) | Aug 14, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [169da97c61](https://bsd-hardware.info/?probe=169da97c61) | Aug 14, 2023 |
| Protectli     | FW4B                        | Desktop     | [417b740320](https://bsd-hardware.info/?probe=417b740320) | Aug 14, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [c09110c605](https://bsd-hardware.info/?probe=c09110c605) | Aug 13, 2023 |
| Protectli     | VP2420                      | Desktop     | [b4bed593e9](https://bsd-hardware.info/?probe=b4bed593e9) | Aug 13, 2023 |
| Protectli     | VP2420                      | Desktop     | [b81c163920](https://bsd-hardware.info/?probe=b81c163920) | Aug 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2529ce32a7](https://bsd-hardware.info/?probe=2529ce32a7) | Aug 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [80fbf43a6c](https://bsd-hardware.info/?probe=80fbf43a6c) | Aug 13, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fbb75a1ace](https://bsd-hardware.info/?probe=fbb75a1ace) | Aug 13, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c7b0e4ca6c](https://bsd-hardware.info/?probe=c7b0e4ca6c) | Aug 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [245d908d1a](https://bsd-hardware.info/?probe=245d908d1a) | Aug 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [fecdfd45c7](https://bsd-hardware.info/?probe=fecdfd45c7) | Aug 13, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [9d53e56e92](https://bsd-hardware.info/?probe=9d53e56e92) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [deb4e10cd2](https://bsd-hardware.info/?probe=deb4e10cd2) | Aug 13, 2023 |
| Supermicro    | X11SSH-F                    | Desktop     | [947caf3be1](https://bsd-hardware.info/?probe=947caf3be1) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [e21c4e8012](https://bsd-hardware.info/?probe=e21c4e8012) | Aug 13, 2023 |
| Unknown       | YL-E3854L4-V2               | Desktop     | [2b24029c25](https://bsd-hardware.info/?probe=2b24029c25) | Aug 12, 2023 |
| HP            | 8265                        | Desktop     | [cefac793c7](https://bsd-hardware.info/?probe=cefac793c7) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [41f42269dc](https://bsd-hardware.info/?probe=41f42269dc) | Aug 12, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [edc2f0f879](https://bsd-hardware.info/?probe=edc2f0f879) | Aug 12, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [519987ec57](https://bsd-hardware.info/?probe=519987ec57) | Aug 12, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [2ee5b48d5c](https://bsd-hardware.info/?probe=2ee5b48d5c) | Aug 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [e310e0d309](https://bsd-hardware.info/?probe=e310e0d309) | Aug 11, 2023 |
| HP            | 8054                        | Desktop     | [05cae0efcc](https://bsd-hardware.info/?probe=05cae0efcc) | Aug 11, 2023 |
| HP            | 8055                        | Desktop     | [d686196496](https://bsd-hardware.info/?probe=d686196496) | Aug 11, 2023 |
| HP            | 1495                        | Desktop     | [7591160534](https://bsd-hardware.info/?probe=7591160534) | Aug 11, 2023 |
| Shuttle       | FH270                       | Desktop     | [8b697be8be](https://bsd-hardware.info/?probe=8b697be8be) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [fdd28fbae2](https://bsd-hardware.info/?probe=fdd28fbae2) | Aug 10, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4b0b4b88a7](https://bsd-hardware.info/?probe=4b0b4b88a7) | Aug 10, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [d4b7006d24](https://bsd-hardware.info/?probe=d4b7006d24) | Aug 10, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [4f4c550075](https://bsd-hardware.info/?probe=4f4c550075) | Aug 10, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | Desktop     | [6a275811b8](https://bsd-hardware.info/?probe=6a275811b8) | Aug 10, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [a66d0c2283](https://bsd-hardware.info/?probe=a66d0c2283) | Aug 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [877307aa80](https://bsd-hardware.info/?probe=877307aa80) | Aug 09, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [76abf23a1f](https://bsd-hardware.info/?probe=76abf23a1f) | Aug 08, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [c0884d7f16](https://bsd-hardware.info/?probe=c0884d7f16) | Aug 08, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [211a64ef6e](https://bsd-hardware.info/?probe=211a64ef6e) | Aug 08, 2023 |
| Dell          | 00NH4P A07                  | Server      | [be1b164954](https://bsd-hardware.info/?probe=be1b164954) | Aug 08, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c54bdb8e4b](https://bsd-hardware.info/?probe=c54bdb8e4b) | Aug 08, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [87810aceef](https://bsd-hardware.info/?probe=87810aceef) | Aug 08, 2023 |
| PC Engines    | apu4                        | Desktop     | [bb7ad49154](https://bsd-hardware.info/?probe=bb7ad49154) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d880905ae7](https://bsd-hardware.info/?probe=d880905ae7) | Aug 07, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [2a8896bb78](https://bsd-hardware.info/?probe=2a8896bb78) | Aug 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5b58edb60b](https://bsd-hardware.info/?probe=5b58edb60b) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [16e7763338](https://bsd-hardware.info/?probe=16e7763338) | Aug 07, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [19e34e504c](https://bsd-hardware.info/?probe=19e34e504c) | Aug 07, 2023 |
| PC Engines    | apu4                        | Desktop     | [57e0cc469e](https://bsd-hardware.info/?probe=57e0cc469e) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [c05ddd6998](https://bsd-hardware.info/?probe=c05ddd6998) | Aug 07, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [4836027efd](https://bsd-hardware.info/?probe=4836027efd) | Aug 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ec37cc1ba1](https://bsd-hardware.info/?probe=ec37cc1ba1) | Aug 07, 2023 |
| Dell          | 01G5C3 A02                  | Server      | [da26fc11fd](https://bsd-hardware.info/?probe=da26fc11fd) | Aug 07, 2023 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Mini pc     | [6a45c89f9c](https://bsd-hardware.info/?probe=6a45c89f9c) | Aug 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [21c932d1ca](https://bsd-hardware.info/?probe=21c932d1ca) | Aug 06, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [415f49b491](https://bsd-hardware.info/?probe=415f49b491) | Aug 06, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [d2ba7bbf34](https://bsd-hardware.info/?probe=d2ba7bbf34) | Aug 06, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [d203b32a8f](https://bsd-hardware.info/?probe=d203b32a8f) | Aug 06, 2023 |
| Supermicro    | X12SDV-4C-SP6F              | Desktop     | [5a87146725](https://bsd-hardware.info/?probe=5a87146725) | Aug 06, 2023 |
| Supermicro    | X10DRI-TB                   | Server      | [d4e7a4dde7](https://bsd-hardware.info/?probe=d4e7a4dde7) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1f7493ada9](https://bsd-hardware.info/?probe=1f7493ada9) | Aug 06, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [46b9ec2e56](https://bsd-hardware.info/?probe=46b9ec2e56) | Aug 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5bd8b552e6](https://bsd-hardware.info/?probe=5bd8b552e6) | Aug 06, 2023 |
| Acer          | Aspire TC-330               | Desktop     | [4d3de96309](https://bsd-hardware.info/?probe=4d3de96309) | Aug 05, 2023 |
| HP            | 843F                        | Desktop     | [d192efba82](https://bsd-hardware.info/?probe=d192efba82) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [0f6e0d9566](https://bsd-hardware.info/?probe=0f6e0d9566) | Aug 05, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [8446d61b81](https://bsd-hardware.info/?probe=8446d61b81) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [36d63888b2](https://bsd-hardware.info/?probe=36d63888b2) | Aug 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [bee8eb05f2](https://bsd-hardware.info/?probe=bee8eb05f2) | Aug 04, 2023 |
| Intel         | S2600GZ G29051-355          | Server      | [33697196aa](https://bsd-hardware.info/?probe=33697196aa) | Aug 04, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [1c593bf547](https://bsd-hardware.info/?probe=1c593bf547) | Aug 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [4a2c98005b](https://bsd-hardware.info/?probe=4a2c98005b) | Aug 04, 2023 |
| Protectli     | VP4650                      | Desktop     | [94d2d08a9d](https://bsd-hardware.info/?probe=94d2d08a9d) | Aug 04, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [da7d5e31aa](https://bsd-hardware.info/?probe=da7d5e31aa) | Aug 03, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [2bef587ef1](https://bsd-hardware.info/?probe=2bef587ef1) | Aug 03, 2023 |
| Dell          | 0G7MDY A12                  | Server      | [3caa904aa3](https://bsd-hardware.info/?probe=3caa904aa3) | Aug 03, 2023 |
| Dell          | 0G7MDY A12                  | Server      | [4dfb2ccae6](https://bsd-hardware.info/?probe=4dfb2ccae6) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [803f6b50b3](https://bsd-hardware.info/?probe=803f6b50b3) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [91dd6813a1](https://bsd-hardware.info/?probe=91dd6813a1) | Aug 03, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [d896138d30](https://bsd-hardware.info/?probe=d896138d30) | Aug 03, 2023 |
| HP            | 1495                        | Desktop     | [551688d163](https://bsd-hardware.info/?probe=551688d163) | Aug 03, 2023 |
| Shuttle       | FH270                       | Desktop     | [92c45a20de](https://bsd-hardware.info/?probe=92c45a20de) | Aug 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e0a72a6c82](https://bsd-hardware.info/?probe=e0a72a6c82) | Aug 02, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [249d4620d2](https://bsd-hardware.info/?probe=249d4620d2) | Aug 02, 2023 |
| ASRock        | B660-ITX                    | Desktop     | [c218c3c4d4](https://bsd-hardware.info/?probe=c218c3c4d4) | Aug 02, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [3d653ab54c](https://bsd-hardware.info/?probe=3d653ab54c) | Aug 02, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [3962253bda](https://bsd-hardware.info/?probe=3962253bda) | Aug 02, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [54388809cd](https://bsd-hardware.info/?probe=54388809cd) | Aug 02, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro    | X7SPA-H                     | Desktop     | [de44613a90](https://bsd-hardware.info/?probe=de44613a90) | Aug 01, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [bdb1c85615](https://bsd-hardware.info/?probe=bdb1c85615) | Aug 01, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [9cf0b7fe7c](https://bsd-hardware.info/?probe=9cf0b7fe7c) | Aug 01, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [1421e45cea](https://bsd-hardware.info/?probe=1421e45cea) | Aug 01, 2023 |
| AZW           | EQ                          | Desktop     | [24d56ab18f](https://bsd-hardware.info/?probe=24d56ab18f) | Aug 01, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [f26504cb5b](https://bsd-hardware.info/?probe=f26504cb5b) | Jul 31, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c045012233](https://bsd-hardware.info/?probe=c045012233) | Jul 31, 2023 |
| Sophos        | XG                          | Firewall    | [629bf7a092](https://bsd-hardware.info/?probe=629bf7a092) | Jul 31, 2023 |
| Protectli     | FW6                         | Desktop     | [aa7b970016](https://bsd-hardware.info/?probe=aa7b970016) | Jul 31, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [1d6213fd35](https://bsd-hardware.info/?probe=1d6213fd35) | Jul 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [9c27c27611](https://bsd-hardware.info/?probe=9c27c27611) | Jul 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [a2dbe84ed3](https://bsd-hardware.info/?probe=a2dbe84ed3) | Jul 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [591f8397a9](https://bsd-hardware.info/?probe=591f8397a9) | Jul 30, 2023 |
| Sophos        | XG                          | Firewall    | [a6fc41a58b](https://bsd-hardware.info/?probe=a6fc41a58b) | Jul 30, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [72abf8e420](https://bsd-hardware.info/?probe=72abf8e420) | Jul 30, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [c453573c71](https://bsd-hardware.info/?probe=c453573c71) | Jul 30, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [38310a9c5e](https://bsd-hardware.info/?probe=38310a9c5e) | Jul 30, 2023 |
| HP            | 213D A01                    | Desktop     | [802a71b9f6](https://bsd-hardware.info/?probe=802a71b9f6) | Jul 29, 2023 |
| Sophos        | SG                          | Firewall    | [07e908538b](https://bsd-hardware.info/?probe=07e908538b) | Jul 29, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [fc2a96cc75](https://bsd-hardware.info/?probe=fc2a96cc75) | Jul 29, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [71b3719bfe](https://bsd-hardware.info/?probe=71b3719bfe) | Jul 29, 2023 |
| Cisco Syst... | ENCS5412/K9 M3              | Server      | [4a34cf5294](https://bsd-hardware.info/?probe=4a34cf5294) | Jul 29, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a1380ccfe1](https://bsd-hardware.info/?probe=a1380ccfe1) | Jul 29, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ce83168854](https://bsd-hardware.info/?probe=ce83168854) | Jul 29, 2023 |
| Cisco Syst... | ENCS5412/K9 M3              | Server      | [2be0baa769](https://bsd-hardware.info/?probe=2be0baa769) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [06e6afb4f1](https://bsd-hardware.info/?probe=06e6afb4f1) | Jul 28, 2023 |
| HP            | 18E4                        | Desktop     | [6a0ce7d626](https://bsd-hardware.info/?probe=6a0ce7d626) | Jul 28, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [74ef7a9db3](https://bsd-hardware.info/?probe=74ef7a9db3) | Jul 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [088f599199](https://bsd-hardware.info/?probe=088f599199) | Jul 28, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [1595ce505c](https://bsd-hardware.info/?probe=1595ce505c) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [836d435712](https://bsd-hardware.info/?probe=836d435712) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [6d6a8cb863](https://bsd-hardware.info/?probe=6d6a8cb863) | Jul 28, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [fccf22f7a7](https://bsd-hardware.info/?probe=fccf22f7a7) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d078811ba](https://bsd-hardware.info/?probe=9d078811ba) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbb7d95d59](https://bsd-hardware.info/?probe=dbb7d95d59) | Jul 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [7841057467](https://bsd-hardware.info/?probe=7841057467) | Jul 27, 2023 |
| Protectli     | VP2420                      | Desktop     | [87d17e77a8](https://bsd-hardware.info/?probe=87d17e77a8) | Jul 26, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e266a42fa5](https://bsd-hardware.info/?probe=e266a42fa5) | Jul 26, 2023 |
| CONTEC        | G1/EMB-CV1/iD2550           | Desktop     | [34f5c817fb](https://bsd-hardware.info/?probe=34f5c817fb) | Jul 26, 2023 |
| HP            | 17E2                        | Mini pc     | [61d1f4cd45](https://bsd-hardware.info/?probe=61d1f4cd45) | Jul 25, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [e97b5d9219](https://bsd-hardware.info/?probe=e97b5d9219) | Jul 25, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [103e75cb64](https://bsd-hardware.info/?probe=103e75cb64) | Jul 25, 2023 |
| Deciso        | Netboard A20                | Notebook    | [9030d92418](https://bsd-hardware.info/?probe=9030d92418) | Jul 25, 2023 |
| HP            | 339A                        | Desktop     | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | Desktop     | [11ee31d0b3](https://bsd-hardware.info/?probe=11ee31d0b3) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [461ad23cc9](https://bsd-hardware.info/?probe=461ad23cc9) | Jul 24, 2023 |
| HP            | 1495                        | Desktop     | [3ddc49b877](https://bsd-hardware.info/?probe=3ddc49b877) | Jul 24, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [1ac1ddd084](https://bsd-hardware.info/?probe=1ac1ddd084) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [bbae253aa2](https://bsd-hardware.info/?probe=bbae253aa2) | Jul 23, 2023 |
| HP            | 1495                        | Desktop     | [9de7021e50](https://bsd-hardware.info/?probe=9de7021e50) | Jul 23, 2023 |
| Protectli     | VP2420                      | Desktop     | [7f388b0128](https://bsd-hardware.info/?probe=7f388b0128) | Jul 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [14b1509851](https://bsd-hardware.info/?probe=14b1509851) | Jul 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [7b725a65c4](https://bsd-hardware.info/?probe=7b725a65c4) | Jul 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [877ddd1995](https://bsd-hardware.info/?probe=877ddd1995) | Jul 23, 2023 |
| Premio        | BlueCat XMB3 00C            | Desktop     | [974c8673b7](https://bsd-hardware.info/?probe=974c8673b7) | Jul 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a2f320b278](https://bsd-hardware.info/?probe=a2f320b278) | Jul 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [4d91799b3c](https://bsd-hardware.info/?probe=4d91799b3c) | Jul 23, 2023 |
| PC Engines    | APU2                        | Desktop     | [e02df69b63](https://bsd-hardware.info/?probe=e02df69b63) | Jul 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb0affa930](https://bsd-hardware.info/?probe=fb0affa930) | Jul 23, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [26d7c98e18](https://bsd-hardware.info/?probe=26d7c98e18) | Jul 22, 2023 |
| Acer          | Spin SP314-21               | Convertible | [375c9f30cd](https://bsd-hardware.info/?probe=375c9f30cd) | Jul 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [36ccde4a75](https://bsd-hardware.info/?probe=36ccde4a75) | Jul 22, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [89f4d8e6a0](https://bsd-hardware.info/?probe=89f4d8e6a0) | Jul 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [267063ed35](https://bsd-hardware.info/?probe=267063ed35) | Jul 22, 2023 |
| HP            | ProBook x360 11 G7 Educa... | Convertible | [22e1b9f0d5](https://bsd-hardware.info/?probe=22e1b9f0d5) | Jul 22, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [db56801c55](https://bsd-hardware.info/?probe=db56801c55) | Jul 21, 2023 |
| Unknown       | QGLK03                      | Desktop     | [d7396cc0e8](https://bsd-hardware.info/?probe=d7396cc0e8) | Jul 21, 2023 |
| Shuttle       | FX48 V10                    | Desktop     | [c0ac40d196](https://bsd-hardware.info/?probe=c0ac40d196) | Jul 21, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [67080aeb1d](https://bsd-hardware.info/?probe=67080aeb1d) | Jul 20, 2023 |
| HPE           | ProLiant DL360 Gen10        | Server      | [115edf7c58](https://bsd-hardware.info/?probe=115edf7c58) | Jul 20, 2023 |
| HP            | 3397                        | Desktop     | [c6d7ddd8e8](https://bsd-hardware.info/?probe=c6d7ddd8e8) | Jul 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5b3f040896](https://bsd-hardware.info/?probe=5b3f040896) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [b7f28022b2](https://bsd-hardware.info/?probe=b7f28022b2) | Jul 19, 2023 |
| HP            | 1495                        | Desktop     | [174216c4d3](https://bsd-hardware.info/?probe=174216c4d3) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fe07363baa](https://bsd-hardware.info/?probe=fe07363baa) | Jul 18, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [13985f2c0c](https://bsd-hardware.info/?probe=13985f2c0c) | Jul 18, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [b5f034579d](https://bsd-hardware.info/?probe=b5f034579d) | Jul 17, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [aeb5bc8b52](https://bsd-hardware.info/?probe=aeb5bc8b52) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [826ba238d8](https://bsd-hardware.info/?probe=826ba238d8) | Jul 16, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [0273f2f271](https://bsd-hardware.info/?probe=0273f2f271) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [93dd663d57](https://bsd-hardware.info/?probe=93dd663d57) | Jul 16, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [82bc9b32bd](https://bsd-hardware.info/?probe=82bc9b32bd) | Jul 16, 2023 |
| HP            | 8103 A01                    | Mini pc     | [17401bacdc](https://bsd-hardware.info/?probe=17401bacdc) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0b045dfd2](https://bsd-hardware.info/?probe=a0b045dfd2) | Jul 15, 2023 |
| HP            | 1495                        | Desktop     | [7756cc81eb](https://bsd-hardware.info/?probe=7756cc81eb) | Jul 15, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [62035a5d06](https://bsd-hardware.info/?probe=62035a5d06) | Jul 15, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5f7014bcb6](https://bsd-hardware.info/?probe=5f7014bcb6) | Jul 15, 2023 |
| PC Engines    | APU2                        | Desktop     | [167d51d317](https://bsd-hardware.info/?probe=167d51d317) | Jul 14, 2023 |
| 10ZiG Tech... | 5900q                       | Notebook    | [3c3668fcd2](https://bsd-hardware.info/?probe=3c3668fcd2) | Jul 14, 2023 |
| HP            | 8055                        | Desktop     | [1274fc1b5e](https://bsd-hardware.info/?probe=1274fc1b5e) | Jul 14, 2023 |
| Protectli     | VP2420                      | Desktop     | [26957c4a08](https://bsd-hardware.info/?probe=26957c4a08) | Jul 14, 2023 |
| Sophos        | SG                          | Firewall    | [61bd0223ab](https://bsd-hardware.info/?probe=61bd0223ab) | Jul 14, 2023 |
| HP            | 8299                        | Desktop     | [5874bc1020](https://bsd-hardware.info/?probe=5874bc1020) | Jul 14, 2023 |
| Protectli     | FW6                         | Desktop     | [f337c2d283](https://bsd-hardware.info/?probe=f337c2d283) | Jul 13, 2023 |
| PC Engines    | APU2                        | Desktop     | [a1af1a8c1d](https://bsd-hardware.info/?probe=a1af1a8c1d) | Jul 13, 2023 |
| ASUSTek       | STRIX H270I GAMING          | Desktop     | [f1899c02c1](https://bsd-hardware.info/?probe=f1899c02c1) | Jul 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [88fae8d98c](https://bsd-hardware.info/?probe=88fae8d98c) | Jul 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1516e2960a](https://bsd-hardware.info/?probe=1516e2960a) | Jul 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [32b118286e](https://bsd-hardware.info/?probe=32b118286e) | Jul 13, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [91965a9c00](https://bsd-hardware.info/?probe=91965a9c00) | Jul 13, 2023 |
| Dell          | 0RC130 A03                  | Server      | [01cb31f643](https://bsd-hardware.info/?probe=01cb31f643) | Jul 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [c580a701d0](https://bsd-hardware.info/?probe=c580a701d0) | Jul 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4ec99c1909](https://bsd-hardware.info/?probe=4ec99c1909) | Jul 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e735a2b8f](https://bsd-hardware.info/?probe=7e735a2b8f) | Jul 12, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [d13984b682](https://bsd-hardware.info/?probe=d13984b682) | Jul 12, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3658cb969a](https://bsd-hardware.info/?probe=3658cb969a) | Jul 11, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [63f0cba062](https://bsd-hardware.info/?probe=63f0cba062) | Jul 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe3184dd5b](https://bsd-hardware.info/?probe=fe3184dd5b) | Jul 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [a24f2cca34](https://bsd-hardware.info/?probe=a24f2cca34) | Jul 10, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [153d52d1c3](https://bsd-hardware.info/?probe=153d52d1c3) | Jul 10, 2023 |
| PC Engines    | apu4                        | Desktop     | [8f0a65309f](https://bsd-hardware.info/?probe=8f0a65309f) | Jul 10, 2023 |
| HP            | 8299                        | Desktop     | [9cfe218328](https://bsd-hardware.info/?probe=9cfe218328) | Jul 10, 2023 |
| PC Engines    | apu4                        | Desktop     | [b82b8da585](https://bsd-hardware.info/?probe=b82b8da585) | Jul 10, 2023 |
| AZW           | EQ                          | Desktop     | [46754d358b](https://bsd-hardware.info/?probe=46754d358b) | Jul 10, 2023 |
| AZW           | EQ                          | Desktop     | [3f38b7c248](https://bsd-hardware.info/?probe=3f38b7c248) | Jul 10, 2023 |
| Protectli     | VP2420                      | Desktop     | [83135eaeca](https://bsd-hardware.info/?probe=83135eaeca) | Jul 10, 2023 |
| HP            | 802E                        | Desktop     | [298896b37a](https://bsd-hardware.info/?probe=298896b37a) | Jul 09, 2023 |
| Unknown       | QCML03                      | Desktop     | [63a27fdd5b](https://bsd-hardware.info/?probe=63a27fdd5b) | Jul 09, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [bbfc2c35b1](https://bsd-hardware.info/?probe=bbfc2c35b1) | Jul 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f0de15f4e2](https://bsd-hardware.info/?probe=f0de15f4e2) | Jul 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3bb3ebc39d](https://bsd-hardware.info/?probe=3bb3ebc39d) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [87bb7727a2](https://bsd-hardware.info/?probe=87bb7727a2) | Jul 09, 2023 |
| Getac         | F110G2                      | Notebook    | [b7b9efc38d](https://bsd-hardware.info/?probe=b7b9efc38d) | Jul 09, 2023 |
| Seeed Stud... | ODYSSEY-TGL-A               | Desktop     | [264f689c35](https://bsd-hardware.info/?probe=264f689c35) | Jul 09, 2023 |
| Supermicro    | X10SDV-TLN4F                | Server      | [46021c73ca](https://bsd-hardware.info/?probe=46021c73ca) | Jul 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [7395b234bc](https://bsd-hardware.info/?probe=7395b234bc) | Jul 09, 2023 |
| Sophos        | XG                          | Firewall    | [4c98fc4092](https://bsd-hardware.info/?probe=4c98fc4092) | Jul 09, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [b121db09fb](https://bsd-hardware.info/?probe=b121db09fb) | Jul 09, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [f5844f1fbd](https://bsd-hardware.info/?probe=f5844f1fbd) | Jul 09, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [75f3eb7e81](https://bsd-hardware.info/?probe=75f3eb7e81) | Jul 08, 2023 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | Notebook    | [80ac9dddda](https://bsd-hardware.info/?probe=80ac9dddda) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [80eb767d39](https://bsd-hardware.info/?probe=80eb767d39) | Jul 08, 2023 |
| HP            | 3397                        | Desktop     | [3d32ba4cd9](https://bsd-hardware.info/?probe=3d32ba4cd9) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [a780f8f8ad](https://bsd-hardware.info/?probe=a780f8f8ad) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [273d642ff6](https://bsd-hardware.info/?probe=273d642ff6) | Jul 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [b07e2a5b47](https://bsd-hardware.info/?probe=b07e2a5b47) | Jul 08, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [2100c4c1d0](https://bsd-hardware.info/?probe=2100c4c1d0) | Jul 07, 2023 |
| HP            | 1495                        | Desktop     | [3e7cdee510](https://bsd-hardware.info/?probe=3e7cdee510) | Jul 07, 2023 |
| Lenovo        | ThinkCentre M81 7518E1U     | Desktop     | [2c818e6169](https://bsd-hardware.info/?probe=2c818e6169) | Jul 06, 2023 |
| AZW           | EQ                          | Desktop     | [158f9680b5](https://bsd-hardware.info/?probe=158f9680b5) | Jul 06, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [fd8e3ee5d6](https://bsd-hardware.info/?probe=fd8e3ee5d6) | Jul 06, 2023 |
| HP            | 8265                        | Desktop     | [c0f867283f](https://bsd-hardware.info/?probe=c0f867283f) | Jul 06, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [45dd8f839f](https://bsd-hardware.info/?probe=45dd8f839f) | Jul 06, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [9e3b26b01b](https://bsd-hardware.info/?probe=9e3b26b01b) | Jul 06, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [6a32c3663b](https://bsd-hardware.info/?probe=6a32c3663b) | Jul 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [4060a343aa](https://bsd-hardware.info/?probe=4060a343aa) | Jul 05, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [a97b53bcf5](https://bsd-hardware.info/?probe=a97b53bcf5) | Jul 05, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [2ac2980803](https://bsd-hardware.info/?probe=2ac2980803) | Jul 05, 2023 |
| Protectli     | FW4B                        | Desktop     | [b73a26aa23](https://bsd-hardware.info/?probe=b73a26aa23) | Jul 05, 2023 |
| Deciso        | Netboard A20                | Notebook    | [dd0a39a4d0](https://bsd-hardware.info/?probe=dd0a39a4d0) | Jul 05, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [529a30afc2](https://bsd-hardware.info/?probe=529a30afc2) | Jul 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8a446692ce](https://bsd-hardware.info/?probe=8a446692ce) | Jul 04, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5838cc1cac](https://bsd-hardware.info/?probe=5838cc1cac) | Jul 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [37fd6c7e30](https://bsd-hardware.info/?probe=37fd6c7e30) | Jul 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [dc56a8a565](https://bsd-hardware.info/?probe=dc56a8a565) | Jul 04, 2023 |
| Dell          | 0W3F1J A00                  | Mini pc     | [09f34d5436](https://bsd-hardware.info/?probe=09f34d5436) | Jul 04, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [d1662eef0f](https://bsd-hardware.info/?probe=d1662eef0f) | Jul 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2e4b44e8af](https://bsd-hardware.info/?probe=2e4b44e8af) | Jul 04, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [d919ca6b12](https://bsd-hardware.info/?probe=d919ca6b12) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e212a51c70](https://bsd-hardware.info/?probe=e212a51c70) | Jul 03, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [3b591d1374](https://bsd-hardware.info/?probe=3b591d1374) | Jul 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [ae2bb37185](https://bsd-hardware.info/?probe=ae2bb37185) | Jul 03, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c265c181c2](https://bsd-hardware.info/?probe=c265c181c2) | Jul 03, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [4a7a333c20](https://bsd-hardware.info/?probe=4a7a333c20) | Jul 02, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [a096236226](https://bsd-hardware.info/?probe=a096236226) | Jul 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [71edaf952e](https://bsd-hardware.info/?probe=71edaf952e) | Jul 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [98254451c1](https://bsd-hardware.info/?probe=98254451c1) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [977d44457e](https://bsd-hardware.info/?probe=977d44457e) | Jul 02, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [f5160f6455](https://bsd-hardware.info/?probe=f5160f6455) | Jul 02, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [d8f6429e70](https://bsd-hardware.info/?probe=d8f6429e70) | Jul 02, 2023 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [496439b2aa](https://bsd-hardware.info/?probe=496439b2aa) | Jul 02, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [6c7703d57f](https://bsd-hardware.info/?probe=6c7703d57f) | Jul 02, 2023 |
| Gigabyte      | MSQ87TN-00                  | Desktop     | [276b7100a2](https://bsd-hardware.info/?probe=276b7100a2) | Jul 01, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [7cce12e9cf](https://bsd-hardware.info/?probe=7cce12e9cf) | Jul 01, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [997c72b98d](https://bsd-hardware.info/?probe=997c72b98d) | Jul 01, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [61c7be6541](https://bsd-hardware.info/?probe=61c7be6541) | Jul 01, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | Notebook    | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [0e1a626160](https://bsd-hardware.info/?probe=0e1a626160) | Jun 30, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b6cfa09740](https://bsd-hardware.info/?probe=b6cfa09740) | Jun 30, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [5c6f36540d](https://bsd-hardware.info/?probe=5c6f36540d) | Jun 29, 2023 |
| Protectli     | VP2420                      | Desktop     | [950ff902c2](https://bsd-hardware.info/?probe=950ff902c2) | Jun 29, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [5b272b02cb](https://bsd-hardware.info/?probe=5b272b02cb) | Jun 29, 2023 |
| HP            | 8055                        | Desktop     | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [0cdc2b47b2](https://bsd-hardware.info/?probe=0cdc2b47b2) | Jun 29, 2023 |
| HP            | 8595                        | Desktop     | [e1a82ff0c5](https://bsd-hardware.info/?probe=e1a82ff0c5) | Jun 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [41e020bc03](https://bsd-hardware.info/?probe=41e020bc03) | Jun 29, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [4053bc358e](https://bsd-hardware.info/?probe=4053bc358e) | Jun 29, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [d5a7320a8a](https://bsd-hardware.info/?probe=d5a7320a8a) | Jun 28, 2023 |
| Dell          | 03X6X0 A00                  | Server      | [88c047f069](https://bsd-hardware.info/?probe=88c047f069) | Jun 28, 2023 |
| HP            | 339A                        | Desktop     | [b08e1fc092](https://bsd-hardware.info/?probe=b08e1fc092) | Jun 27, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [30240eb64b](https://bsd-hardware.info/?probe=30240eb64b) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | Desktop     | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [bc448a4c10](https://bsd-hardware.info/?probe=bc448a4c10) | Jun 27, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [489b7b6bae](https://bsd-hardware.info/?probe=489b7b6bae) | Jun 26, 2023 |
| Lenovo        | ThinkPad T440p 20AW000BU... | Notebook    | [9a7628d17b](https://bsd-hardware.info/?probe=9a7628d17b) | Jun 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [cd3b925f27](https://bsd-hardware.info/?probe=cd3b925f27) | Jun 26, 2023 |
| Gigabyte      | C1037UN                     | Desktop     | [fccc3f4b80](https://bsd-hardware.info/?probe=fccc3f4b80) | Jun 26, 2023 |
| AZW           | EQ                          | Desktop     | [c410cd5c1c](https://bsd-hardware.info/?probe=c410cd5c1c) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [dc937eee63](https://bsd-hardware.info/?probe=dc937eee63) | Jun 25, 2023 |
| MSI           | H81M-P33                    | Desktop     | [80bd24461a](https://bsd-hardware.info/?probe=80bd24461a) | Jun 25, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [e368d55893](https://bsd-hardware.info/?probe=e368d55893) | Jun 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [483865aca5](https://bsd-hardware.info/?probe=483865aca5) | Jun 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [32e290d370](https://bsd-hardware.info/?probe=32e290d370) | Jun 25, 2023 |
| HP            | 8103 A01                    | Mini pc     | [feb4e78649](https://bsd-hardware.info/?probe=feb4e78649) | Jun 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c72cc8a340](https://bsd-hardware.info/?probe=c72cc8a340) | Jun 24, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [6210e8f0bc](https://bsd-hardware.info/?probe=6210e8f0bc) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [93213fc931](https://bsd-hardware.info/?probe=93213fc931) | Jun 24, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [fdf31a6e78](https://bsd-hardware.info/?probe=fdf31a6e78) | Jun 23, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [a931ed9f0a](https://bsd-hardware.info/?probe=a931ed9f0a) | Jun 23, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [b6916f61a8](https://bsd-hardware.info/?probe=b6916f61a8) | Jun 23, 2023 |
| AZW           | EQ                          | Desktop     | [8a85da80b2](https://bsd-hardware.info/?probe=8a85da80b2) | Jun 23, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [bc8c23b6ff](https://bsd-hardware.info/?probe=bc8c23b6ff) | Jun 22, 2023 |
| NetGear       | ReadyNAS 3130               | Firewall    | [7fa1d24d06](https://bsd-hardware.info/?probe=7fa1d24d06) | Jun 22, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [b7ca7c7195](https://bsd-hardware.info/?probe=b7ca7c7195) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [f73625157c](https://bsd-hardware.info/?probe=f73625157c) | Jun 22, 2023 |
| Protectli     | VP2410                      | Desktop     | [94e2177a56](https://bsd-hardware.info/?probe=94e2177a56) | Jun 22, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [7d3a60d628](https://bsd-hardware.info/?probe=7d3a60d628) | Jun 22, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [ed967db034](https://bsd-hardware.info/?probe=ed967db034) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [178a67ff39](https://bsd-hardware.info/?probe=178a67ff39) | Jun 21, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [572c03a709](https://bsd-hardware.info/?probe=572c03a709) | Jun 21, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [f094606e8f](https://bsd-hardware.info/?probe=f094606e8f) | Jun 21, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [8f550b0d75](https://bsd-hardware.info/?probe=8f550b0d75) | Jun 21, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [efc396837c](https://bsd-hardware.info/?probe=efc396837c) | Jun 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [12d57aa9d9](https://bsd-hardware.info/?probe=12d57aa9d9) | Jun 21, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [a09d71cc14](https://bsd-hardware.info/?probe=a09d71cc14) | Jun 21, 2023 |
| HP            | 802E                        | Desktop     | [595a5d4f60](https://bsd-hardware.info/?probe=595a5d4f60) | Jun 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [d0c184ae86](https://bsd-hardware.info/?probe=d0c184ae86) | Jun 20, 2023 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [18f6f78915](https://bsd-hardware.info/?probe=18f6f78915) | Jun 19, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1fa198f78d](https://bsd-hardware.info/?probe=1fa198f78d) | Jun 19, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [e8c8da464a](https://bsd-hardware.info/?probe=e8c8da464a) | Jun 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [1b3b10c231](https://bsd-hardware.info/?probe=1b3b10c231) | Jun 19, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [9e864bfe3b](https://bsd-hardware.info/?probe=9e864bfe3b) | Jun 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b0659ff5bf](https://bsd-hardware.info/?probe=b0659ff5bf) | Jun 18, 2023 |
| Dell          | 07F37C A01                  | Desktop     | [16e5a062a2](https://bsd-hardware.info/?probe=16e5a062a2) | Jun 18, 2023 |
| Dell          | 05KX61 A02                  | Server      | [7131f9450f](https://bsd-hardware.info/?probe=7131f9450f) | Jun 18, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [31c6e3d0b1](https://bsd-hardware.info/?probe=31c6e3d0b1) | Jun 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [705c750691](https://bsd-hardware.info/?probe=705c750691) | Jun 17, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [72ac0afa21](https://bsd-hardware.info/?probe=72ac0afa21) | Jun 16, 2023 |
| HP            | 83E9                        | Desktop     | [23ec260317](https://bsd-hardware.info/?probe=23ec260317) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [a6d5232f75](https://bsd-hardware.info/?probe=a6d5232f75) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [06754d9e71](https://bsd-hardware.info/?probe=06754d9e71) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [e218344894](https://bsd-hardware.info/?probe=e218344894) | Jun 15, 2023 |
| Panasonic     | CFSX4-1                     | Notebook    | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [8586467924](https://bsd-hardware.info/?probe=8586467924) | Jun 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [3274745a08](https://bsd-hardware.info/?probe=3274745a08) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [355639e85e](https://bsd-hardware.info/?probe=355639e85e) | Jun 14, 2023 |
| Dell          | 0VWT90 A00                  | Server      | [884ea7a785](https://bsd-hardware.info/?probe=884ea7a785) | Jun 14, 2023 |
| Protectli     | VP2420                      | Desktop     | [82ecf3a046](https://bsd-hardware.info/?probe=82ecf3a046) | Jun 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6e8e70ddc2](https://bsd-hardware.info/?probe=6e8e70ddc2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [c19a29f083](https://bsd-hardware.info/?probe=c19a29f083) | Jun 13, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [33b64d3084](https://bsd-hardware.info/?probe=33b64d3084) | Jun 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [0dc0eab687](https://bsd-hardware.info/?probe=0dc0eab687) | Jun 13, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [751e307940](https://bsd-hardware.info/?probe=751e307940) | Jun 13, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Dell          | 0VWT90 A00                  | Server      | [1860066c89](https://bsd-hardware.info/?probe=1860066c89) | Jun 12, 2023 |
| HP            | 213D A01                    | Desktop     | [2a6603c79a](https://bsd-hardware.info/?probe=2a6603c79a) | Jun 12, 2023 |
| Intel         | NUC11PABi5 M68265-500       | Mini pc     | [1db246e3ab](https://bsd-hardware.info/?probe=1db246e3ab) | Jun 12, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [9f14962984](https://bsd-hardware.info/?probe=9f14962984) | Jun 11, 2023 |
| MSI           | H81M-P33                    | Desktop     | [3d9a05635f](https://bsd-hardware.info/?probe=3d9a05635f) | Jun 11, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b8f3eeed4b](https://bsd-hardware.info/?probe=b8f3eeed4b) | Jun 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9c888141fb](https://bsd-hardware.info/?probe=9c888141fb) | Jun 11, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [3f8a97d0e7](https://bsd-hardware.info/?probe=3f8a97d0e7) | Jun 11, 2023 |
| Supermicro    | X11SBA-LN4FA                | Server      | [be7bf70aff](https://bsd-hardware.info/?probe=be7bf70aff) | Jun 11, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [39eba90e6a](https://bsd-hardware.info/?probe=39eba90e6a) | Jun 10, 2023 |
| Dell          | Inspiron 3180               | Notebook    | [cb769078b4](https://bsd-hardware.info/?probe=cb769078b4) | Jun 10, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [8bedc249ea](https://bsd-hardware.info/?probe=8bedc249ea) | Jun 10, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [c80bb80e8f](https://bsd-hardware.info/?probe=c80bb80e8f) | Jun 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ffeca6e776](https://bsd-hardware.info/?probe=ffeca6e776) | Jun 10, 2023 |
| Gigabyte      | C1037UN                     | Desktop     | [d8f7cea73b](https://bsd-hardware.info/?probe=d8f7cea73b) | Jun 10, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [ec04f3f6d5](https://bsd-hardware.info/?probe=ec04f3f6d5) | Jun 10, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [af56081a76](https://bsd-hardware.info/?probe=af56081a76) | Jun 10, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [6cc2f54681](https://bsd-hardware.info/?probe=6cc2f54681) | Jun 10, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [7d23d1c91f](https://bsd-hardware.info/?probe=7d23d1c91f) | Jun 09, 2023 |
| PC Engines    | APU2                        | Desktop     | [24545e8f90](https://bsd-hardware.info/?probe=24545e8f90) | Jun 09, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [e42082ba89](https://bsd-hardware.info/?probe=e42082ba89) | Jun 09, 2023 |
| MSI           | MS-7360                     | Desktop     | [f54096f3e5](https://bsd-hardware.info/?probe=f54096f3e5) | Jun 08, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [7ffef5814d](https://bsd-hardware.info/?probe=7ffef5814d) | Jun 07, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [54c23902c7](https://bsd-hardware.info/?probe=54c23902c7) | Jun 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [e50d3f9b86](https://bsd-hardware.info/?probe=e50d3f9b86) | Jun 06, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [0b9ad8d7d8](https://bsd-hardware.info/?probe=0b9ad8d7d8) | Jun 06, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [fe5f99c4b0](https://bsd-hardware.info/?probe=fe5f99c4b0) | Jun 06, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [eb7049ca10](https://bsd-hardware.info/?probe=eb7049ca10) | Jun 06, 2023 |
| HP            | 843F                        | Desktop     | [57b6c258ad](https://bsd-hardware.info/?probe=57b6c258ad) | Jun 06, 2023 |
| Lenovo        | ThinkPad T500 2082BNU       | Notebook    | [dedd066084](https://bsd-hardware.info/?probe=dedd066084) | Jun 06, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [e07bfb044b](https://bsd-hardware.info/?probe=e07bfb044b) | Jun 06, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [03e1e6d302](https://bsd-hardware.info/?probe=03e1e6d302) | Jun 05, 2023 |
| Deciso        | Netboard A20                | Notebook    | [eb03ae7215](https://bsd-hardware.info/?probe=eb03ae7215) | Jun 05, 2023 |
| HP            | 212B                        | Desktop     | [4db61072c4](https://bsd-hardware.info/?probe=4db61072c4) | Jun 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [e137b3e686](https://bsd-hardware.info/?probe=e137b3e686) | Jun 05, 2023 |
| HP            | 339A                        | Desktop     | [74f857c400](https://bsd-hardware.info/?probe=74f857c400) | Jun 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [88598bfbf5](https://bsd-hardware.info/?probe=88598bfbf5) | Jun 04, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [fac0ed387e](https://bsd-hardware.info/?probe=fac0ed387e) | Jun 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3c76deca15](https://bsd-hardware.info/?probe=3c76deca15) | Jun 04, 2023 |
| HP            | 802E                        | Desktop     | [2af6f8a101](https://bsd-hardware.info/?probe=2af6f8a101) | Jun 04, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [cf05481728](https://bsd-hardware.info/?probe=cf05481728) | Jun 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [a243045cc3](https://bsd-hardware.info/?probe=a243045cc3) | Jun 04, 2023 |
| HP            | 805A                        | Desktop     | [3ad8551330](https://bsd-hardware.info/?probe=3ad8551330) | Jun 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [0f5b2ad316](https://bsd-hardware.info/?probe=0f5b2ad316) | Jun 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [ffb4544d8c](https://bsd-hardware.info/?probe=ffb4544d8c) | Jun 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [a42fcbbc12](https://bsd-hardware.info/?probe=a42fcbbc12) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [538e16bf08](https://bsd-hardware.info/?probe=538e16bf08) | Jun 03, 2023 |
| Dell          | G5 5505                     | Notebook    | [5a3c1f19a0](https://bsd-hardware.info/?probe=5a3c1f19a0) | Jun 03, 2023 |
| AAEON         | FWS-2360 V1.0               | Desktop     | [bcb707d6d0](https://bsd-hardware.info/?probe=bcb707d6d0) | Jun 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [2702f3486a](https://bsd-hardware.info/?probe=2702f3486a) | Jun 02, 2023 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [4cada5d71b](https://bsd-hardware.info/?probe=4cada5d71b) | Jun 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [09b74995b7](https://bsd-hardware.info/?probe=09b74995b7) | Jun 02, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [2348a2736e](https://bsd-hardware.info/?probe=2348a2736e) | Jun 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [a3bc187a6b](https://bsd-hardware.info/?probe=a3bc187a6b) | Jun 02, 2023 |
| Dell          | G5 5505                     | Notebook    | [1b10aecc38](https://bsd-hardware.info/?probe=1b10aecc38) | Jun 02, 2023 |
| HP            | 805A                        | Desktop     | [b50fd38c94](https://bsd-hardware.info/?probe=b50fd38c94) | Jun 01, 2023 |
| Advantech     | FWA-1320 A103               | Server      | [0b78bc1741](https://bsd-hardware.info/?probe=0b78bc1741) | Jun 01, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ef66603fb9](https://bsd-hardware.info/?probe=ef66603fb9) | Jun 01, 2023 |
| ASRock        | FM2A78M-ITX+                | Desktop     | [aecc8b1372](https://bsd-hardware.info/?probe=aecc8b1372) | Jun 01, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [c40e01cab3](https://bsd-hardware.info/?probe=c40e01cab3) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [330c08c388](https://bsd-hardware.info/?probe=330c08c388) | Jun 01, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [53cf3cea13](https://bsd-hardware.info/?probe=53cf3cea13) | Jun 01, 2023 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [8b0669a87d](https://bsd-hardware.info/?probe=8b0669a87d) | May 31, 2023 |
| HP            | 802E                        | Desktop     | [2b1f2776cd](https://bsd-hardware.info/?probe=2b1f2776cd) | May 31, 2023 |
| Gigabyte      | C1037UN                     | Desktop     | [7502577edc](https://bsd-hardware.info/?probe=7502577edc) | May 31, 2023 |
| CWWK          | CW-AD4L-N V1                | Desktop     | [d5a2882e49](https://bsd-hardware.info/?probe=d5a2882e49) | May 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [f6643f3b06](https://bsd-hardware.info/?probe=f6643f3b06) | May 31, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c7f2f78173](https://bsd-hardware.info/?probe=c7f2f78173) | May 31, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [d186c4c443](https://bsd-hardware.info/?probe=d186c4c443) | May 30, 2023 |
| Gigabyte      | C1037UN                     | Desktop     | [79e0162b9c](https://bsd-hardware.info/?probe=79e0162b9c) | May 30, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [b264e962d0](https://bsd-hardware.info/?probe=b264e962d0) | May 30, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [7d2e30807a](https://bsd-hardware.info/?probe=7d2e30807a) | May 30, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [21bad05407](https://bsd-hardware.info/?probe=21bad05407) | May 29, 2023 |
| Intel         | SKYBAY                      | Desktop     | [86747c5b22](https://bsd-hardware.info/?probe=86747c5b22) | May 29, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [a12b5d1715](https://bsd-hardware.info/?probe=a12b5d1715) | May 29, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [23cad3f06e](https://bsd-hardware.info/?probe=23cad3f06e) | May 28, 2023 |
| Intel         | JSL MRD                     | Desktop     | [6fa703d206](https://bsd-hardware.info/?probe=6fa703d206) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28c84f71fd](https://bsd-hardware.info/?probe=28c84f71fd) | May 28, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [cf8b2af78b](https://bsd-hardware.info/?probe=cf8b2af78b) | May 28, 2023 |
| Intel         | JSL MRD                     | Desktop     | [fc7970abd1](https://bsd-hardware.info/?probe=fc7970abd1) | May 28, 2023 |
| PC Engines    | APU2                        | Desktop     | [4c27451012](https://bsd-hardware.info/?probe=4c27451012) | May 28, 2023 |
| PC Engines    | APU2                        | Desktop     | [6b276a70c5](https://bsd-hardware.info/?probe=6b276a70c5) | May 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [3560dcfedc](https://bsd-hardware.info/?probe=3560dcfedc) | May 27, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [2caaa9f6cf](https://bsd-hardware.info/?probe=2caaa9f6cf) | May 27, 2023 |
| ASRock        | H270M-ITX/ac                | Desktop     | [69aaebd77e](https://bsd-hardware.info/?probe=69aaebd77e) | May 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [0918049f45](https://bsd-hardware.info/?probe=0918049f45) | May 27, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [d8496263d4](https://bsd-hardware.info/?probe=d8496263d4) | May 27, 2023 |
| Intel         | S1200KP AAG34877-201        | Desktop     | [5bf84ec376](https://bsd-hardware.info/?probe=5bf84ec376) | May 27, 2023 |
| Protectli     | FW6                         | Desktop     | [f7626db73e](https://bsd-hardware.info/?probe=f7626db73e) | May 27, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [dbda738a56](https://bsd-hardware.info/?probe=dbda738a56) | May 27, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [d0d211e4e7](https://bsd-hardware.info/?probe=d0d211e4e7) | May 27, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [b6b902639c](https://bsd-hardware.info/?probe=b6b902639c) | May 27, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [8ba976666f](https://bsd-hardware.info/?probe=8ba976666f) | May 27, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8514299fe4](https://bsd-hardware.info/?probe=8514299fe4) | May 26, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [adc687fcfe](https://bsd-hardware.info/?probe=adc687fcfe) | May 26, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [19c6226530](https://bsd-hardware.info/?probe=19c6226530) | May 26, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [acdcef4b1c](https://bsd-hardware.info/?probe=acdcef4b1c) | May 26, 2023 |
| Protectli     | VP2420                      | Desktop     | [2b716b3dd3](https://bsd-hardware.info/?probe=2b716b3dd3) | May 26, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [90b4ae806f](https://bsd-hardware.info/?probe=90b4ae806f) | May 25, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [3797f9d0a9](https://bsd-hardware.info/?probe=3797f9d0a9) | May 24, 2023 |
| HP            | 8299                        | Desktop     | [14a7b5fc70](https://bsd-hardware.info/?probe=14a7b5fc70) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9d20f955e](https://bsd-hardware.info/?probe=a9d20f955e) | May 24, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [572d966731](https://bsd-hardware.info/?probe=572d966731) | May 24, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9a2c066dfa](https://bsd-hardware.info/?probe=9a2c066dfa) | May 23, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | Notebook    | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [eba55377e0](https://bsd-hardware.info/?probe=eba55377e0) | May 22, 2023 |
| Supermicro    | X8SIL                       | Desktop     | [21823c6dbd](https://bsd-hardware.info/?probe=21823c6dbd) | May 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [b5e5e8e2cc](https://bsd-hardware.info/?probe=b5e5e8e2cc) | May 21, 2023 |
| MSI           | H81M-P33                    | Desktop     | [cadb0f588f](https://bsd-hardware.info/?probe=cadb0f588f) | May 21, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4a55c4a669](https://bsd-hardware.info/?probe=4a55c4a669) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f2fb56c7dc](https://bsd-hardware.info/?probe=f2fb56c7dc) | May 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a87acae699](https://bsd-hardware.info/?probe=a87acae699) | May 21, 2023 |
| HP            | ProBook 455 G3              | Notebook    | [b6a6c91115](https://bsd-hardware.info/?probe=b6a6c91115) | May 21, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0S300     | Notebook    | [44d30cfcf6](https://bsd-hardware.info/?probe=44d30cfcf6) | May 21, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7c28bf2d83](https://bsd-hardware.info/?probe=7c28bf2d83) | May 20, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [9d1ee9fb7c](https://bsd-hardware.info/?probe=9d1ee9fb7c) | May 20, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [5576c293d8](https://bsd-hardware.info/?probe=5576c293d8) | May 20, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [0c153dcf2d](https://bsd-hardware.info/?probe=0c153dcf2d) | May 20, 2023 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [4528db7fba](https://bsd-hardware.info/?probe=4528db7fba) | May 20, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [186e5d4e15](https://bsd-hardware.info/?probe=186e5d4e15) | May 19, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bf9eb20343](https://bsd-hardware.info/?probe=bf9eb20343) | May 19, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [484774ff19](https://bsd-hardware.info/?probe=484774ff19) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [7be0869603](https://bsd-hardware.info/?probe=7be0869603) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [ef56a2bd17](https://bsd-hardware.info/?probe=ef56a2bd17) | May 19, 2023 |
| HP            | 18E7                        | Desktop     | [477f3d4c80](https://bsd-hardware.info/?probe=477f3d4c80) | May 19, 2023 |
| Shuttle       | FH270                       | Desktop     | [95b532312a](https://bsd-hardware.info/?probe=95b532312a) | May 18, 2023 |
| Supermicro    | X7SBL                       | Desktop     | [b5ba4ba0e8](https://bsd-hardware.info/?probe=b5ba4ba0e8) | May 18, 2023 |
| Protectli     | FW4C                        | Desktop     | [a8252edc71](https://bsd-hardware.info/?probe=a8252edc71) | May 18, 2023 |
| HP            | 8299                        | Desktop     | [6d2f149a51](https://bsd-hardware.info/?probe=6d2f149a51) | May 18, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [73335cbb47](https://bsd-hardware.info/?probe=73335cbb47) | May 17, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [62910ad9d9](https://bsd-hardware.info/?probe=62910ad9d9) | May 17, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c4546c2b83](https://bsd-hardware.info/?probe=c4546c2b83) | May 17, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2f5ff5fa71](https://bsd-hardware.info/?probe=2f5ff5fa71) | May 17, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [12b0e44025](https://bsd-hardware.info/?probe=12b0e44025) | May 17, 2023 |
| Dell          | 03X6X0 A03                  | Server      | [b2287aeafe](https://bsd-hardware.info/?probe=b2287aeafe) | May 17, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [39516c2e91](https://bsd-hardware.info/?probe=39516c2e91) | May 16, 2023 |
| Dell          | 0XN8Y6 A09                  | Server      | [f130e8ac22](https://bsd-hardware.info/?probe=f130e8ac22) | May 16, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [9c08a669ab](https://bsd-hardware.info/?probe=9c08a669ab) | May 16, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [75a9fd684a](https://bsd-hardware.info/?probe=75a9fd684a) | May 16, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ed8e952359](https://bsd-hardware.info/?probe=ed8e952359) | May 16, 2023 |
| MSI           | H81TI                       | Desktop     | [798ddd2aa1](https://bsd-hardware.info/?probe=798ddd2aa1) | May 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dca662fc41](https://bsd-hardware.info/?probe=dca662fc41) | May 16, 2023 |
| Dell          | 0D7449 A01                  | Server      | [9e81eed411](https://bsd-hardware.info/?probe=9e81eed411) | May 16, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [27be69ed61](https://bsd-hardware.info/?probe=27be69ed61) | May 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bc475b9528](https://bsd-hardware.info/?probe=bc475b9528) | May 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [ea9ff40bdb](https://bsd-hardware.info/?probe=ea9ff40bdb) | May 14, 2023 |
| ASRock        | 4X4-V1000                   | Desktop     | [189073c58e](https://bsd-hardware.info/?probe=189073c58e) | May 14, 2023 |
| HP            | 8054                        | Desktop     | [1ffc97728a](https://bsd-hardware.info/?probe=1ffc97728a) | May 14, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [cb87f3725f](https://bsd-hardware.info/?probe=cb87f3725f) | May 14, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [895dfa9596](https://bsd-hardware.info/?probe=895dfa9596) | May 14, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ebf1ee8152](https://bsd-hardware.info/?probe=ebf1ee8152) | May 14, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [2bf04b4cf1](https://bsd-hardware.info/?probe=2bf04b4cf1) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ae7796a444](https://bsd-hardware.info/?probe=ae7796a444) | May 14, 2023 |
| Protectli     | FW1 Ver                     | Desktop     | [824016ccf0](https://bsd-hardware.info/?probe=824016ccf0) | May 14, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [71ad6e7c1c](https://bsd-hardware.info/?probe=71ad6e7c1c) | May 14, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [4222f2f8a5](https://bsd-hardware.info/?probe=4222f2f8a5) | May 13, 2023 |
| Unknown       | N4000                       | Desktop     | [48742290f1](https://bsd-hardware.info/?probe=48742290f1) | May 13, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [b22c9a0cdf](https://bsd-hardware.info/?probe=b22c9a0cdf) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [00a94d98fb](https://bsd-hardware.info/?probe=00a94d98fb) | May 13, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [362cbefc66](https://bsd-hardware.info/?probe=362cbefc66) | May 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3e685e1db0](https://bsd-hardware.info/?probe=3e685e1db0) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e9d95aed5](https://bsd-hardware.info/?probe=2e9d95aed5) | May 13, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [1daa68fb84](https://bsd-hardware.info/?probe=1daa68fb84) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a477479a00](https://bsd-hardware.info/?probe=a477479a00) | May 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [de9fcd9543](https://bsd-hardware.info/?probe=de9fcd9543) | May 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [71e4a5f1ec](https://bsd-hardware.info/?probe=71e4a5f1ec) | May 13, 2023 |
| BCM Advanc... | MX81HV/MX81H 10             | Desktop     | [f58c8bdd86](https://bsd-hardware.info/?probe=f58c8bdd86) | May 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [ac2a74785a](https://bsd-hardware.info/?probe=ac2a74785a) | May 13, 2023 |
| Biostar       | H61MGC                      | Desktop     | [001611da7e](https://bsd-hardware.info/?probe=001611da7e) | May 12, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [fc9a0ecef6](https://bsd-hardware.info/?probe=fc9a0ecef6) | May 12, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5dadf3509b](https://bsd-hardware.info/?probe=5dadf3509b) | May 12, 2023 |
| JHZD          | BQM5                        | Desktop     | [6b32c22615](https://bsd-hardware.info/?probe=6b32c22615) | May 12, 2023 |
| JHZD          | BQM5                        | Desktop     | [fbbaf0b924](https://bsd-hardware.info/?probe=fbbaf0b924) | May 11, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [fc8375381d](https://bsd-hardware.info/?probe=fc8375381d) | May 11, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [1e9cfaf845](https://bsd-hardware.info/?probe=1e9cfaf845) | May 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [834174a5a8](https://bsd-hardware.info/?probe=834174a5a8) | May 11, 2023 |
| HP            | 1588h                       | Desktop     | [f1d543fb77](https://bsd-hardware.info/?probe=f1d543fb77) | May 11, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [f76a340f4a](https://bsd-hardware.info/?probe=f76a340f4a) | May 11, 2023 |
| Protectli     | FW6                         | Desktop     | [37432c6de1](https://bsd-hardware.info/?probe=37432c6de1) | May 10, 2023 |
| Intel         | NUC11PHBi7 M26151-405       | Mini pc     | [89cd98c281](https://bsd-hardware.info/?probe=89cd98c281) | May 10, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [89abd9548b](https://bsd-hardware.info/?probe=89abd9548b) | May 10, 2023 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [42b97c3277](https://bsd-hardware.info/?probe=42b97c3277) | May 10, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [72cdd452c8](https://bsd-hardware.info/?probe=72cdd452c8) | May 10, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [3359e9a10e](https://bsd-hardware.info/?probe=3359e9a10e) | May 10, 2023 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [df84be1ef9](https://bsd-hardware.info/?probe=df84be1ef9) | May 10, 2023 |
| ASUSTek       | P10S-E Series               | Desktop     | [37451da8a7](https://bsd-hardware.info/?probe=37451da8a7) | May 08, 2023 |
| HP            | 8103 A01                    | Mini pc     | [7fcf1a72ee](https://bsd-hardware.info/?probe=7fcf1a72ee) | May 08, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [bb96adbb13](https://bsd-hardware.info/?probe=bb96adbb13) | May 08, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [d5fa48cd90](https://bsd-hardware.info/?probe=d5fa48cd90) | May 07, 2023 |
| MSI           | H81M-P33                    | Desktop     | [55cfed4de4](https://bsd-hardware.info/?probe=55cfed4de4) | May 07, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [0cb51a327e](https://bsd-hardware.info/?probe=0cb51a327e) | May 07, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7e41914431](https://bsd-hardware.info/?probe=7e41914431) | May 07, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | Desktop     | [733c921923](https://bsd-hardware.info/?probe=733c921923) | May 07, 2023 |
| Sophos        | SG                          | Firewall    | [19b5a03391](https://bsd-hardware.info/?probe=19b5a03391) | May 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9ae7407dc4](https://bsd-hardware.info/?probe=9ae7407dc4) | May 07, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a583770abc](https://bsd-hardware.info/?probe=a583770abc) | May 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [f2ea102ee1](https://bsd-hardware.info/?probe=f2ea102ee1) | May 06, 2023 |
| ASRock        | X570 PG Velocita            | Desktop     | [46925c3dda](https://bsd-hardware.info/?probe=46925c3dda) | May 06, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [1c918b79b0](https://bsd-hardware.info/?probe=1c918b79b0) | May 06, 2023 |
| AZW           | MINI S 10                   | Desktop     | [123024f70d](https://bsd-hardware.info/?probe=123024f70d) | May 06, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [dfb339020a](https://bsd-hardware.info/?probe=dfb339020a) | May 06, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [85256a78f6](https://bsd-hardware.info/?probe=85256a78f6) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [2002ddd198](https://bsd-hardware.info/?probe=2002ddd198) | May 05, 2023 |
| Protectli     | VP2420                      | Desktop     | [3fcbd494fc](https://bsd-hardware.info/?probe=3fcbd494fc) | May 05, 2023 |
| Supermicro    | X11SCV-Q                    | Desktop     | [7a6949713d](https://bsd-hardware.info/?probe=7a6949713d) | May 05, 2023 |
| CWWK          | MINIPC-G12                  | Desktop     | [f2ab15324b](https://bsd-hardware.info/?probe=f2ab15324b) | May 05, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [bdd112ce9b](https://bsd-hardware.info/?probe=bdd112ce9b) | May 05, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [982f87fd4d](https://bsd-hardware.info/?probe=982f87fd4d) | May 05, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [ba619e879e](https://bsd-hardware.info/?probe=ba619e879e) | May 04, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [a1274a9d0c](https://bsd-hardware.info/?probe=a1274a9d0c) | May 04, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [38f47bf53f](https://bsd-hardware.info/?probe=38f47bf53f) | May 04, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [5e30b0e6b1](https://bsd-hardware.info/?probe=5e30b0e6b1) | May 04, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [797f0c4b0e](https://bsd-hardware.info/?probe=797f0c4b0e) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [c430ceb253](https://bsd-hardware.info/?probe=c430ceb253) | May 04, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [baaf2935c4](https://bsd-hardware.info/?probe=baaf2935c4) | May 04, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [31c9c606ab](https://bsd-hardware.info/?probe=31c9c606ab) | May 04, 2023 |
| Unknown       | QSKL01                      | Desktop     | [4277dc49d0](https://bsd-hardware.info/?probe=4277dc49d0) | May 04, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [45bffd3275](https://bsd-hardware.info/?probe=45bffd3275) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| Sophos        | XG                          | Firewall    | [cda12ab89f](https://bsd-hardware.info/?probe=cda12ab89f) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| HP            | 82B4                        | Desktop     | [1bcefd3823](https://bsd-hardware.info/?probe=1bcefd3823) | May 02, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [e1628ea30a](https://bsd-hardware.info/?probe=e1628ea30a) | May 02, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [83ccb5ff07](https://bsd-hardware.info/?probe=83ccb5ff07) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3f089673e0](https://bsd-hardware.info/?probe=3f089673e0) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [396d7f268c](https://bsd-hardware.info/?probe=396d7f268c) | May 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [a59b6fc6dc](https://bsd-hardware.info/?probe=a59b6fc6dc) | Apr 30, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [2cc6521d1f](https://bsd-hardware.info/?probe=2cc6521d1f) | Apr 30, 2023 |
| Dell          | 0FF3FN A00                  | Desktop     | [717b46840a](https://bsd-hardware.info/?probe=717b46840a) | Apr 30, 2023 |
| Dell          | 0H634K A00                  | Desktop     | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [50836a160a](https://bsd-hardware.info/?probe=50836a160a) | Apr 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e28acf1164](https://bsd-hardware.info/?probe=e28acf1164) | Apr 30, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [33d1b6e2d2](https://bsd-hardware.info/?probe=33d1b6e2d2) | Apr 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b0d9eaaceb](https://bsd-hardware.info/?probe=b0d9eaaceb) | Apr 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b922b7925](https://bsd-hardware.info/?probe=2b922b7925) | Apr 30, 2023 |
| HP            | 83E1                        | Desktop     | [d3e5e9a563](https://bsd-hardware.info/?probe=d3e5e9a563) | Apr 30, 2023 |
| HP            | 8103 A01                    | Mini pc     | [51ec1cdb56](https://bsd-hardware.info/?probe=51ec1cdb56) | Apr 29, 2023 |
| Dell          | Latitude E5570              | Notebook    | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [ad97036f62](https://bsd-hardware.info/?probe=ad97036f62) | Apr 29, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [dbdb6539fb](https://bsd-hardware.info/?probe=dbdb6539fb) | Apr 29, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [29ecd63e1e](https://bsd-hardware.info/?probe=29ecd63e1e) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | Desktop     | [9495b45b30](https://bsd-hardware.info/?probe=9495b45b30) | Apr 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [b980175f4f](https://bsd-hardware.info/?probe=b980175f4f) | Apr 28, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [f6200a69eb](https://bsd-hardware.info/?probe=f6200a69eb) | Apr 28, 2023 |
| NCR           | Richmond BIOS.6.0           | Desktop     | [e41e1e5c70](https://bsd-hardware.info/?probe=e41e1e5c70) | Apr 28, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [ef3774c8f2](https://bsd-hardware.info/?probe=ef3774c8f2) | Apr 28, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [95a05a3e59](https://bsd-hardware.info/?probe=95a05a3e59) | Apr 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [8b2758be02](https://bsd-hardware.info/?probe=8b2758be02) | Apr 27, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [08e155a558](https://bsd-hardware.info/?probe=08e155a558) | Apr 27, 2023 |
| Dell          | 081N4V A05                  | Server      | [e5f9ddcee3](https://bsd-hardware.info/?probe=e5f9ddcee3) | Apr 27, 2023 |
| HP            | 8299                        | Desktop     | [f26926526d](https://bsd-hardware.info/?probe=f26926526d) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [9d15e108e6](https://bsd-hardware.info/?probe=9d15e108e6) | Apr 27, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8a4ea432e6](https://bsd-hardware.info/?probe=8a4ea432e6) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| Acer          | Spin SP314-21               | Convertible | [f5debc3ef8](https://bsd-hardware.info/?probe=f5debc3ef8) | Apr 27, 2023 |
| HP            | 83EE                        | Desktop     | [b5a00cabd1](https://bsd-hardware.info/?probe=b5a00cabd1) | Apr 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [ece1b6bacb](https://bsd-hardware.info/?probe=ece1b6bacb) | Apr 26, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [acb9ca23c8](https://bsd-hardware.info/?probe=acb9ca23c8) | Apr 26, 2023 |
| HP            | 859B                        | Desktop     | [357ef27be4](https://bsd-hardware.info/?probe=357ef27be4) | Apr 26, 2023 |
| HP            | 82B4                        | Desktop     | [58c58b6a82](https://bsd-hardware.info/?probe=58c58b6a82) | Apr 26, 2023 |
| HP            | 8056                        | Desktop     | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| AZW           | EQ                          | Desktop     | [8dd15b5070](https://bsd-hardware.info/?probe=8dd15b5070) | Apr 26, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6efffdce00](https://bsd-hardware.info/?probe=6efffdce00) | Apr 25, 2023 |
| ASUSTek       | P10S-E Series               | Desktop     | [e6d1a90732](https://bsd-hardware.info/?probe=e6d1a90732) | Apr 25, 2023 |
| HP            | 83E1                        | Desktop     | [865bd9b84e](https://bsd-hardware.info/?probe=865bd9b84e) | Apr 25, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [3d0f6b629d](https://bsd-hardware.info/?probe=3d0f6b629d) | Apr 25, 2023 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [b56e27db28](https://bsd-hardware.info/?probe=b56e27db28) | Apr 25, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [2d4f063c9f](https://bsd-hardware.info/?probe=2d4f063c9f) | Apr 25, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [601f819826](https://bsd-hardware.info/?probe=601f819826) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cf0771c3a2](https://bsd-hardware.info/?probe=cf0771c3a2) | Apr 25, 2023 |
| Supermicro    | X11SDV-4C-TP8F-01           | Desktop     | [02d2e2ea42](https://bsd-hardware.info/?probe=02d2e2ea42) | Apr 25, 2023 |
| HP            | 18E7                        | Desktop     | [777359d3c1](https://bsd-hardware.info/?probe=777359d3c1) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d3373e972b](https://bsd-hardware.info/?probe=d3373e972b) | Apr 24, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [39d17845fb](https://bsd-hardware.info/?probe=39d17845fb) | Apr 24, 2023 |
| AZW           | EQ                          | Desktop     | [fe3205803d](https://bsd-hardware.info/?probe=fe3205803d) | Apr 24, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [9678198b3b](https://bsd-hardware.info/?probe=9678198b3b) | Apr 24, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [280ab26f33](https://bsd-hardware.info/?probe=280ab26f33) | Apr 24, 2023 |
| Google        | Peppy                       | Notebook    | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
| Supermicro    | A1SRi-2758F                 | Desktop     | [750e44f983](https://bsd-hardware.info/?probe=750e44f983) | Apr 24, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [b3a756536a](https://bsd-hardware.info/?probe=b3a756536a) | Apr 23, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6df7a17ff2](https://bsd-hardware.info/?probe=6df7a17ff2) | Apr 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [37564b68c3](https://bsd-hardware.info/?probe=37564b68c3) | Apr 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d44a98739c](https://bsd-hardware.info/?probe=d44a98739c) | Apr 23, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [463567a3e6](https://bsd-hardware.info/?probe=463567a3e6) | Apr 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dab120ab36](https://bsd-hardware.info/?probe=dab120ab36) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [50ff0c14dd](https://bsd-hardware.info/?probe=50ff0c14dd) | Apr 22, 2023 |
| PC Engines    | apu1                        | Desktop     | [9838a040ba](https://bsd-hardware.info/?probe=9838a040ba) | Apr 22, 2023 |
| PC Engines    | apu1                        | Desktop     | [6e3df79f6d](https://bsd-hardware.info/?probe=6e3df79f6d) | Apr 22, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [631a166cee](https://bsd-hardware.info/?probe=631a166cee) | Apr 22, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [f241a78410](https://bsd-hardware.info/?probe=f241a78410) | Apr 22, 2023 |
| HP            | 82B4                        | Desktop     | [35360c7568](https://bsd-hardware.info/?probe=35360c7568) | Apr 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [66614019db](https://bsd-hardware.info/?probe=66614019db) | Apr 22, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [9b975ac704](https://bsd-hardware.info/?probe=9b975ac704) | Apr 22, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [8e138145ca](https://bsd-hardware.info/?probe=8e138145ca) | Apr 22, 2023 |
| HP            | Pavilion 17                 | Notebook    | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| PC Engines    | APU                         | Desktop     | [c4238a76d1](https://bsd-hardware.info/?probe=c4238a76d1) | Apr 21, 2023 |
| PC Engines    | APU                         | Desktop     | [ae3ce982fe](https://bsd-hardware.info/?probe=ae3ce982fe) | Apr 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [e17bcecec8](https://bsd-hardware.info/?probe=e17bcecec8) | Apr 21, 2023 |
| HP            | 83F2                        | Desktop     | [1ff683e02b](https://bsd-hardware.info/?probe=1ff683e02b) | Apr 20, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [6f85c5453c](https://bsd-hardware.info/?probe=6f85c5453c) | Apr 20, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [5e94539f7f](https://bsd-hardware.info/?probe=5e94539f7f) | Apr 20, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [94507dfaf6](https://bsd-hardware.info/?probe=94507dfaf6) | Apr 20, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [24162b26be](https://bsd-hardware.info/?probe=24162b26be) | Apr 20, 2023 |
| Dell          | 081N4V A05                  | Server      | [8189917b77](https://bsd-hardware.info/?probe=8189917b77) | Apr 20, 2023 |
| PC Engines    | APU3                        | Desktop     | [110d848c38](https://bsd-hardware.info/?probe=110d848c38) | Apr 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [d727bd2723](https://bsd-hardware.info/?probe=d727bd2723) | Apr 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3852dcb332](https://bsd-hardware.info/?probe=3852dcb332) | Apr 19, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [d89f79132d](https://bsd-hardware.info/?probe=d89f79132d) | Apr 19, 2023 |
| HP            | 8299                        | Desktop     | [a9e845749a](https://bsd-hardware.info/?probe=a9e845749a) | Apr 19, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c626643f89](https://bsd-hardware.info/?probe=c626643f89) | Apr 18, 2023 |
| HP            | 8055                        | Desktop     | [83ecb873fe](https://bsd-hardware.info/?probe=83ecb873fe) | Apr 18, 2023 |
| AZW           | EQ                          | Desktop     | [c9fe4601ec](https://bsd-hardware.info/?probe=c9fe4601ec) | Apr 18, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [464059d8b1](https://bsd-hardware.info/?probe=464059d8b1) | Apr 18, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [73ccbd2631](https://bsd-hardware.info/?probe=73ccbd2631) | Apr 18, 2023 |
| Acer          | Spin SP314-21               | Convertible | [820e7da3c8](https://bsd-hardware.info/?probe=820e7da3c8) | Apr 18, 2023 |
| PC Engines    | APU2                        | Desktop     | [5d714a9c0d](https://bsd-hardware.info/?probe=5d714a9c0d) | Apr 18, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [d03887218d](https://bsd-hardware.info/?probe=d03887218d) | Apr 18, 2023 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [3608477e76](https://bsd-hardware.info/?probe=3608477e76) | Apr 16, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e285cc821f](https://bsd-hardware.info/?probe=e285cc821f) | Apr 16, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b79bdd39da](https://bsd-hardware.info/?probe=b79bdd39da) | Apr 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e6734bf5e3](https://bsd-hardware.info/?probe=e6734bf5e3) | Apr 16, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4110309ccc](https://bsd-hardware.info/?probe=4110309ccc) | Apr 16, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [773b28fbc7](https://bsd-hardware.info/?probe=773b28fbc7) | Apr 16, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [a9c8c58abc](https://bsd-hardware.info/?probe=a9c8c58abc) | Apr 16, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [19b7b614dc](https://bsd-hardware.info/?probe=19b7b614dc) | Apr 15, 2023 |
| ASUSTek       | P5BV-E                      | Desktop     | [f134ff34ba](https://bsd-hardware.info/?probe=f134ff34ba) | Apr 15, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3b0562fe2a](https://bsd-hardware.info/?probe=3b0562fe2a) | Apr 15, 2023 |
| Supermicro    | X11SSQ-L-DE05BA             | Server      | [dcbd42abdd](https://bsd-hardware.info/?probe=dcbd42abdd) | Apr 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [4127e0b00d](https://bsd-hardware.info/?probe=4127e0b00d) | Apr 15, 2023 |
| Protectli     | FW6                         | Desktop     | [15753be1b9](https://bsd-hardware.info/?probe=15753be1b9) | Apr 15, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [e665283e47](https://bsd-hardware.info/?probe=e665283e47) | Apr 15, 2023 |
| ASRockRack    | C226M WS                    | Desktop     | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [57a82eb257](https://bsd-hardware.info/?probe=57a82eb257) | Apr 14, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [1b2a188c77](https://bsd-hardware.info/?probe=1b2a188c77) | Apr 14, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [3958a90c04](https://bsd-hardware.info/?probe=3958a90c04) | Apr 13, 2023 |
| Lenovo        | ThinkPad R61 89208RU        | Notebook    | [e892cdffee](https://bsd-hardware.info/?probe=e892cdffee) | Apr 13, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [93632f99ad](https://bsd-hardware.info/?probe=93632f99ad) | Apr 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [e2b6422180](https://bsd-hardware.info/?probe=e2b6422180) | Apr 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f54d0b103e](https://bsd-hardware.info/?probe=f54d0b103e) | Apr 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [3f95d84c6f](https://bsd-hardware.info/?probe=3f95d84c6f) | Apr 13, 2023 |
| ECS           | Z77H2-AX                    | Desktop     | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [bee20c6a4c](https://bsd-hardware.info/?probe=bee20c6a4c) | Apr 12, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [128489e571](https://bsd-hardware.info/?probe=128489e571) | Apr 12, 2023 |
| HP            | 212B                        | Desktop     | [0fb2a36b23](https://bsd-hardware.info/?probe=0fb2a36b23) | Apr 12, 2023 |
| Acer          | Spin SP314-21               | Convertible | [a5ee042606](https://bsd-hardware.info/?probe=a5ee042606) | Apr 12, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6622d21ee9](https://bsd-hardware.info/?probe=6622d21ee9) | Apr 12, 2023 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [a3dbe88338](https://bsd-hardware.info/?probe=a3dbe88338) | Apr 11, 2023 |
| Supermicro    | C7SIM-Q                     | Desktop     | [dca54cc956](https://bsd-hardware.info/?probe=dca54cc956) | Apr 11, 2023 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [f7bcf353a9](https://bsd-hardware.info/?probe=f7bcf353a9) | Apr 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f44190a72a](https://bsd-hardware.info/?probe=f44190a72a) | Apr 11, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [c9d3e3ccd9](https://bsd-hardware.info/?probe=c9d3e3ccd9) | Apr 11, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [14e9a37e55](https://bsd-hardware.info/?probe=14e9a37e55) | Apr 11, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [9e860251ae](https://bsd-hardware.info/?probe=9e860251ae) | Apr 10, 2023 |
| Dell          | 04JGCK A01                  | Desktop     | [5eb06957e2](https://bsd-hardware.info/?probe=5eb06957e2) | Apr 10, 2023 |
| Dell          | 04JGCK A01                  | Desktop     | [43e509c47b](https://bsd-hardware.info/?probe=43e509c47b) | Apr 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [5bfbfb213e](https://bsd-hardware.info/?probe=5bfbfb213e) | Apr 09, 2023 |
| MSI           | H81M-P33                    | Desktop     | [90ab4216eb](https://bsd-hardware.info/?probe=90ab4216eb) | Apr 09, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [62358071bf](https://bsd-hardware.info/?probe=62358071bf) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a06682a305](https://bsd-hardware.info/?probe=a06682a305) | Apr 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [689c25b4f6](https://bsd-hardware.info/?probe=689c25b4f6) | Apr 09, 2023 |
| HP            | 212B                        | Desktop     | [6dc537109d](https://bsd-hardware.info/?probe=6dc537109d) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0e9cae4351](https://bsd-hardware.info/?probe=0e9cae4351) | Apr 09, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b288c3264c](https://bsd-hardware.info/?probe=b288c3264c) | Apr 09, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [6b448c285b](https://bsd-hardware.info/?probe=6b448c285b) | Apr 08, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [c4cb33b0a1](https://bsd-hardware.info/?probe=c4cb33b0a1) | Apr 08, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7525421240](https://bsd-hardware.info/?probe=7525421240) | Apr 08, 2023 |
| Dell          | 084XW4 A05                  | Server      | [4300ecfb51](https://bsd-hardware.info/?probe=4300ecfb51) | Apr 08, 2023 |
| Dell          | Latitude 7300               | Notebook    | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| HP            | 83EF                        | Desktop     | [56fd6177cd](https://bsd-hardware.info/?probe=56fd6177cd) | Apr 07, 2023 |
| HP            | 83F2                        | Desktop     | [40a4bc3252](https://bsd-hardware.info/?probe=40a4bc3252) | Apr 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6acbfb84ea](https://bsd-hardware.info/?probe=6acbfb84ea) | Apr 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [83b404b047](https://bsd-hardware.info/?probe=83b404b047) | Apr 06, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ea48bd3665](https://bsd-hardware.info/?probe=ea48bd3665) | Apr 06, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [bae6bb22e0](https://bsd-hardware.info/?probe=bae6bb22e0) | Apr 06, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [00cc70100d](https://bsd-hardware.info/?probe=00cc70100d) | Apr 06, 2023 |
| Fujitsu       | LIFEBOOK U810               | Notebook    | [3073cd605c](https://bsd-hardware.info/?probe=3073cd605c) | Apr 06, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [eb5e28d965](https://bsd-hardware.info/?probe=eb5e28d965) | Apr 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e06c6010d](https://bsd-hardware.info/?probe=3e06c6010d) | Apr 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 23.1.11  | 111       | 2.72%   |
| OPNsense 21.7.7   | 90        | 2.2%    |
| OPNsense 22.7.10  | 82        | 2.01%   |
| OPNsense 23.1     | 80        | 1.96%   |
| OPNsense 21.7.3   | 77        | 1.88%   |
| OPNsense 23.1.7   | 69        | 1.69%   |
| OPNsense 21.7.1   | 69        | 1.69%   |
| OPNsense 23.1.1   | 68        | 1.66%   |
| OPNsense 22.1     | 68        | 1.66%   |
| OPNsense 21.1.5   | 67        | 1.64%   |
| OPNsense 22.1.10  | 66        | 1.62%   |
| helloSystem 0.7.0 | 66        | 1.62%   |
| OPNsense 23.1.5   | 65        | 1.59%   |
| OPNsense 22.7.4   | 65        | 1.59%   |
| OPNsense 20.7.8   | 61        | 1.49%   |
| OPNsense 21.1.4   | 60        | 1.47%   |
| FreeBSD 13.0      | 60        | 1.47%   |
| OPNsense 22.1.8   | 58        | 1.42%   |
| OPNsense 21.1.3   | 58        | 1.42%   |
| OPNsense 23.7.1   | 57        | 1.4%    |
| FreeBSD 13.1      | 56        | 1.37%   |
| OPNsense 23.1.9   | 54        | 1.32%   |
| OPNsense 23.1.6   | 54        | 1.32%   |
| helloSystem 0.8.1 | 53        | 1.3%    |
| OPNsense 23.7.3   | 52        | 1.27%   |
| OPNsense 21.1     | 51        | 1.25%   |
| OPNsense 22.7.9   | 50        | 1.22%   |
| OPNsense 22.7.6   | 50        | 1.22%   |
| OPNsense 21.1.8   | 50        | 1.22%   |
| OPNsense 23.7     | 48        | 1.17%   |
| helloSystem 0.8.0 | 48        | 1.17%   |
| OPNsense 22.7.8   | 45        | 1.1%    |
| OPNsense 22.7.2   | 45        | 1.1%    |
| OPNsense 22.7.11  | 43        | 1.05%   |
| OPNsense 22.7     | 43        | 1.05%   |
| OPNsense 22.1.6   | 42        | 1.03%   |
| OPNsense 22.1.4   | 42        | 1.03%   |
| OPNsense 22.1.2   | 42        | 1.03%   |
| OPNsense 21.1.7   | 42        | 1.03%   |
| OPNsense 21.1.1   | 42        | 1.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1874      | 63.14%  |
| FreeBSD     | 535       | 18.03%  |
| helloSystem | 263       | 8.86%   |
| OpenBSD     | 103       | 3.47%   |
| GhostBSD    | 61        | 2.06%   |
| NomadBSD    | 37        | 1.25%   |
| pfSense     | 18        | 0.61%   |
| FreeNAS     | 17        | 0.57%   |
| MidnightBSD | 16        | 0.54%   |
| TrueNAS     | 11        | 0.37%   |
| NetBSD      | 9         | 0.3%    |
| HardenedBSD | 9         | 0.3%    |
| DragonFly   | 6         | 0.2%    |
| FuryBSD     | 3         | 0.1%    |
| XigmaNAS    | 2         | 0.07%   |
| OS108       | 2         | 0.07%   |
| MyBee       | 1         | 0.03%   |
| ClonOS      | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2885      | 98.06%  |
| i386    | 29        | 0.99%   |
| arm64   | 23        | 0.78%   |
| powerpc | 3         | 0.1%    |
| sparc64 | 1         | 0.03%   |
| evbarm  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 2132      | 71.11%  |
| helloDesktop  | 283       | 9.44%   |
| XFCE          | 112       | 3.74%   |
| MATE          | 87        | 2.9%    |
| KDE5          | 83        | 2.77%   |
| fvwm          | 58        | 1.93%   |
| TWM           | 56        | 1.87%   |
| GNOME         | 51        | 1.7%    |
| Openbox       | 49        | 1.63%   |
| i3            | 32        | 1.07%   |
| Cinnamon      | 12        | 0.4%    |
| Enlightenment | 8         | 0.27%   |
| LXQt          | 6         | 0.2%    |
| Fluxbox       | 6         | 0.2%    |
| Lumina        | 5         | 0.17%   |
| AwesomeWM     | 3         | 0.1%    |
| Xfwm4         | 2         | 0.07%   |
| Picom         | 2         | 0.07%   |
| GNUstep       | 2         | 0.07%   |
| DWM           | 2         | 0.07%   |
| Window Maker  | 1         | 0.03%   |
| spectrwm      | 1         | 0.03%   |
| sdorfehs      | 1         | 0.03%   |
| LXDE          | 1         | 0.03%   |
| KDE           | 1         | 0.03%   |
| Compton       | 1         | 0.03%   |
| CDE           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2156      | 72.89%  |
| X11     | 795       | 26.88%  |
| Wayland | 7         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2353      | 78.99%  |
| SLiM    | 361       | 12.12%  |
| LightDM | 100       | 3.36%   |
| SDDM    | 84        | 2.82%   |
| XDM     | 46        | 1.54%   |
| GDM     | 32        | 1.07%   |
| Ly      | 3         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 2195      | 72.9%   |
| en_US           | 429       | 14.25%  |
| C               | 332       | 11.03%  |
| en              | 34        | 1.13%   |
| fr_FR           | 6         | 0.2%    |
| fr              | 4         | 0.13%   |
| ru_RU           | 2         | 0.07%   |
| en_US.US-ASCII  | 2         | 0.07%   |
| en_US.ISO8859-1 | 2         | 0.07%   |
| en_GB           | 2         | 0.07%   |
| es_CO           | 1         | 0.03%   |
| en_US.utf-8     | 1         | 0.03%   |
| de_DE           | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2550      | 85.34%  |
| BIOS | 438       | 14.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1500      | 49.47%  |
| Zfs     | 1333      | 43.96%  |
| Ffs     | 103       | 3.4%    |
| Cd9660  | 89        | 2.94%   |
| Hammer2 | 6         | 0.2%    |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2740      | 92.19%  |
| MBR     | 202       | 6.8%    |
| Unknown | 23        | 0.77%   |
| BSD     | 7         | 0.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 478       | 16.26%  |
| Hewlett-Packard         | 297       | 10.1%   |
| Lenovo                  | 272       | 9.25%   |
| Supermicro              | 241       | 8.2%    |
| Unknown                 | 237       | 8.06%   |
| Protectli               | 222       | 7.55%   |
| ASUSTek Computer        | 183       | 6.22%   |
| Intel                   | 127       | 4.32%   |
| ASRock                  | 102       | 3.47%   |
| Gigabyte Technology     | 84        | 2.86%   |
| MSI                     | 77        | 2.62%   |
| AMI                     | 53        | 1.8%    |
| Apple                   | 48        | 1.63%   |
| PC Engines              | 39        | 1.33%   |
| Acer                    | 34        | 1.16%   |
| Techvision              | 25        | 0.85%   |
| Sophos                  | 20        | 0.68%   |
| Deciso                  | 20        | 0.68%   |
| AZW                     | 19        | 0.65%   |
| MW                      | 14        | 0.48%   |
| Google                  | 13        | 0.44%   |
| Biostar                 | 13        | 0.44%   |
| Toshiba                 | 12        | 0.41%   |
| CompuLab                | 12        | 0.41%   |
| CWWK                    | 11        | 0.37%   |
| BESSTAR Tech            | 11        | 0.37%   |
| ASRockRack              | 11        | 0.37%   |
| System76                | 10        | 0.34%   |
| AWOW                    | 10        | 0.34%   |
| Shuttle                 | 9         | 0.31%   |
| Seeed Studio            | 9         | 0.31%   |
| Fujitsu                 | 9         | 0.31%   |
| Foxconn                 | 8         | 0.27%   |
| Hardkernel              | 7         | 0.24%   |
| Framework               | 7         | 0.24%   |
| ZOTAC                   | 6         | 0.2%    |
| Raspberry Pi Foundation | 6         | 0.2%    |
| HPE                     | 6         | 0.2%    |
| Datto                   | 6         | 0.2%    |
| Cisco Systems           | 6         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 244       | 8.3%    |
| Protectli FW4B                      | 74        | 2.52%   |
| Supermicro Super Server             | 64        | 2.18%   |
| Protectli FW6                       | 61        | 2.07%   |
| AMI Aptio CRB                       | 48        | 1.63%   |
| Intel Q3XXG4-P V1.0                 | 40        | 1.36%   |
| HP t730 Thin Client                 | 27        | 0.92%   |
| Techvision TVI7309X                 | 25        | 0.85%   |
| HP t620 PLUS Quad Core TC           | 24        | 0.82%   |
| Dell OptiPlex 9020                  | 24        | 0.82%   |
| Dell OptiPlex 3020                  | 24        | 0.82%   |
| ASUS All Series                     | 23        | 0.78%   |
| Dell PowerEdge R210 II              | 22        | 0.75%   |
| Supermicro X9SCL/X9SCM              | 21        | 0.71%   |
| Supermicro X10SLH-N6-ST031          | 19        | 0.65%   |
| PC Engines APU2                     | 19        | 0.65%   |
| Dell OptiPlex 7010                  | 18        | 0.61%   |
| Protectli VP2410                    | 15        | 0.51%   |
| PC Engines apu4                     | 15        | 0.51%   |
| MW GMLK-2_5G4L                      | 14        | 0.48%   |
| Protectli FW2B                      | 13        | 0.44%   |
| Dell Wyse 5070 Extended Thin Client | 13        | 0.44%   |
| Dell OptiPlex 990                   | 13        | 0.44%   |
| Protectli FW4C                      | 12        | 0.41%   |
| Dell OptiPlex 7040                  | 12        | 0.41%   |
| CompuLab fitlet2                    | 12        | 0.41%   |
| Supermicro A1SAi                    | 11        | 0.37%   |
| Protectli VP2420                    | 11        | 0.37%   |
| Protectli FW1                       | 11        | 0.37%   |
| HP EliteDesk 800 G1 SFF             | 11        | 0.37%   |
| Sophos XG                           | 10        | 0.34%   |
| HP EliteDesk 800 G3 SFF             | 10        | 0.34%   |
| Deciso Netboard A20                 | 10        | 0.34%   |
| Intel Nobilis                       | 9         | 0.31%   |
| Dell PowerEdge R610                 | 9         | 0.31%   |
| Dell OptiPlex 9010                  | 9         | 0.31%   |
| Dell OptiPlex 790                   | 9         | 0.31%   |
| Dell OptiPlex 3040                  | 9         | 0.31%   |
| Supermicro HYVE-ZEUS                | 8         | 0.27%   |
| Sophos SG                           | 8         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 244       | 8.3%    |
| Dell OptiPlex              | 194       | 6.6%    |
| Lenovo ThinkPad            | 149       | 5.07%   |
| Dell PowerEdge             | 120       | 4.08%   |
| Protectli FW4B             | 74        | 2.52%   |
| Lenovo ThinkCentre         | 69        | 2.35%   |
| Supermicro Super           | 64        | 2.18%   |
| Protectli FW6              | 61        | 2.07%   |
| AMI Aptio                  | 48        | 1.63%   |
| HP EliteDesk               | 47        | 1.6%    |
| Dell Inspiron              | 46        | 1.56%   |
| Intel Q3XXG4-P             | 41        | 1.39%   |
| Dell Latitude              | 41        | 1.39%   |
| Dell Precision             | 31        | 1.05%   |
| HP ProDesk                 | 30        | 1.02%   |
| ASUS ROG                   | 29        | 0.99%   |
| HP t730                    | 27        | 0.92%   |
| HP t620                    | 26        | 0.88%   |
| ASUS PRIME                 | 26        | 0.88%   |
| Techvision TVI7309X        | 25        | 0.85%   |
| HP Compaq                  | 25        | 0.85%   |
| ASUS TUF                   | 25        | 0.85%   |
| HP Pavilion                | 24        | 0.82%   |
| ASUS All                   | 23        | 0.78%   |
| Supermicro X9SCL           | 21        | 0.71%   |
| HP ProLiant                | 21        | 0.71%   |
| Supermicro X10SLH-N6-ST031 | 19        | 0.65%   |
| PC Engines APU2            | 19        | 0.65%   |
| Acer Aspire                | 16        | 0.54%   |
| Protectli VP2410           | 15        | 0.51%   |
| PC Engines apu4            | 15        | 0.51%   |
| Lenovo IdeaPad             | 15        | 0.51%   |
| ASRock X570                | 15        | 0.51%   |
| MW GMLK-2                  | 14        | 0.48%   |
| Dell Wyse                  | 14        | 0.48%   |
| Protectli FW2B             | 13        | 0.44%   |
| Protectli FW4C             | 12        | 0.41%   |
| Dell XPS                   | 12        | 0.41%   |
| CompuLab fitlet2           | 12        | 0.41%   |
| Supermicro A1SAi           | 11        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 379       | 12.89%  |
| 2019    | 287       | 9.76%   |
| 2022    | 269       | 9.15%   |
| 2020    | 251       | 8.54%   |
| 2021    | 245       | 8.33%   |
| 2016    | 211       | 7.18%   |
| 2014    | 194       | 6.6%    |
| 2013    | 175       | 5.95%   |
| 2011    | 166       | 5.65%   |
| 2015    | 161       | 5.48%   |
| 2017    | 151       | 5.14%   |
| 2012    | 143       | 4.86%   |
| 2010    | 73        | 2.48%   |
| 2023    | 61        | 2.07%   |
| 2009    | 47        | 1.6%    |
| 2008    | 43        | 1.46%   |
| Unknown | 39        | 1.33%   |
| 2007    | 22        | 0.75%   |
| 2006    | 15        | 0.51%   |
| 2004    | 4         | 0.14%   |
| 2005    | 1         | 0.03%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1867      | 63.5%   |
| Notebook       | 502       | 17.07%  |
| Server         | 293       | 9.97%   |
| Mini pc        | 210       | 7.14%   |
| Firewall       | 28        | 0.95%   |
| Convertible    | 19        | 0.65%   |
| System on chip | 14        | 0.48%   |
| All in one     | 7         | 0.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2828      | 96.19%  |
| Yes  | 112       | 3.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 1082      | 35.82%  |
| 16.01-24.0      | 746       | 24.69%  |
| 4.01-8.0        | 462       | 15.29%  |
| 32.01-64.0      | 376       | 12.45%  |
| 64.01-256.0     | 172       | 5.69%   |
| 2.01-3.0        | 63        | 2.09%   |
| 24.01-32.0      | 58        | 1.92%   |
| 3.01-4.0        | 31        | 1.03%   |
| 0.51-1.0        | 13        | 0.43%   |
| 1.01-2.0        | 9         | 0.3%    |
| 0.01-0.5        | 5         | 0.17%   |
| More than 256.0 | 4         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1337      | 43.47%  |
| 0.51-1.0    | 954       | 31.01%  |
| 1.01-2.0    | 457       | 14.86%  |
| 2.01-3.0    | 89        | 2.89%   |
| 4.01-8.0    | 70        | 2.28%   |
| 3.01-4.0    | 48        | 1.56%   |
| 8.01-16.0   | 40        | 1.3%    |
| 24.01-32.0  | 18        | 0.59%   |
| 16.01-24.0  | 18        | 0.59%   |
| 32.01-64.0  | 14        | 0.46%   |
| Unknown     | 14        | 0.46%   |
| 0           | 11        | 0.36%   |
| 64.01-256.0 | 6         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2084      | 68.53%  |
| 2      | 400       | 13.15%  |
| 0      | 275       | 9.04%   |
| 3      | 108       | 3.55%   |
| 4      | 48        | 1.58%   |
| 5      | 33        | 1.09%   |
| 6      | 24        | 0.79%   |
| 7      | 13        | 0.43%   |
| 8      | 9         | 0.3%    |
| 14     | 8         | 0.26%   |
| 10     | 7         | 0.23%   |
| 12     | 6         | 0.2%    |
| 9      | 6         | 0.2%    |
| 11     | 4         | 0.13%   |
| 21     | 2         | 0.07%   |
| 18     | 2         | 0.07%   |
| 17     | 2         | 0.07%   |
| 58     | 1         | 0.03%   |
| 40     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |
| 26     | 1         | 0.03%   |
| 22     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 16     | 1         | 0.03%   |
| 15     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2335      | 78.59%  |
| Yes       | 636       | 21.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2817      | 95.82%  |
| No        | 123       | 4.18%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1966      | 66.24%  |
| Yes       | 1002      | 33.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2263      | 76.35%  |
| Yes       | 701       | 23.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 2940      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Seattle       | 52        | 1.59%   |
| Brooklyn      | 46        | 1.41%   |
| New York      | 45        | 1.38%   |
| Chicago       | 44        | 1.35%   |
| Denver        | 43        | 1.32%   |
| Los Angeles   | 35        | 1.07%   |
| Portland      | 33        | 1.01%   |
| Dallas        | 31        | 0.95%   |
| Austin        | 30        | 0.92%   |
| San Francisco | 24        | 0.74%   |
| Rochester     | 22        | 0.67%   |
| Columbus      | 22        | 0.67%   |
| Atlanta       | 22        | 0.67%   |
| Phoenix       | 21        | 0.64%   |
| Oakland       | 18        | 0.55%   |
| Grand Rapids  | 18        | 0.55%   |
| Springfield   | 17        | 0.52%   |
| Mountain View | 17        | 0.52%   |
| Houston       | 16        | 0.49%   |
| San Jose      | 15        | 0.46%   |
| Ypsilanti     | 14        | 0.43%   |
| Orlando       | 14        | 0.43%   |
| Omaha         | 14        | 0.43%   |
| Las Vegas     | 14        | 0.43%   |
| Philadelphia  | 13        | 0.4%    |
| Minneapolis   | 13        | 0.4%    |
| Kansas City   | 13        | 0.4%    |
| Charlotte     | 13        | 0.4%    |
| San Antonio   | 12        | 0.37%   |
| Salem         | 12        | 0.37%   |
| Raleigh       | 12        | 0.37%   |
| Pittsburgh    | 12        | 0.37%   |
| Oklahoma City | 12        | 0.37%   |
| Milwaukee     | 12        | 0.37%   |
| Jacksonville  | 12        | 0.37%   |
| Washington    | 11        | 0.34%   |
| Saint Paul    | 11        | 0.34%   |
| Indianapolis  | 11        | 0.34%   |
| Fremont       | 11        | 0.34%   |
| Bothell       | 11        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 555       | 1069   | 16.12%  |
| WDC                 | 420       | 1255   | 12.2%   |
| Seagate             | 302       | 808    | 8.77%   |
| Kingston            | 236       | 318    | 6.86%   |
| Crucial             | 170       | 268    | 4.94%   |
| Intel               | 153       | 291    | 4.45%   |
| SanDisk             | 152       | 198    | 4.42%   |
| Toshiba             | 117       | 208    | 3.4%    |
| Transcend           | 116       | 217    | 3.37%   |
| SK hynix            | 72        | 99     | 2.09%   |
| Hoodisk             | 71        | 99     | 2.06%   |
| Hitachi             | 70        | 164    | 2.03%   |
| China               | 68        | 102    | 1.98%   |
| A-DATA Technology   | 68        | 108    | 1.98%   |
| PNY                 | 63        | 89     | 1.83%   |
| Protectli           | 62        | 96     | 1.8%    |
| Phison              | 62        | 100    | 1.8%    |
| SPCC                | 50        | 91     | 1.45%   |
| HGST                | 40        | 126    | 1.16%   |
| Hewlett-Packard     | 38        | 115    | 1.1%    |
| Micron Technology   | 37        | 49     | 1.07%   |
| Dogfish             | 31        | 53     | 0.9%    |
| BIWIN               | 27        | 43     | 0.78%   |
| NVMe                | 26        | 36     | 0.76%   |
| Team                | 24        | 41     | 0.7%    |
| FORESEE             | 24        | 36     | 0.7%    |
| OCZ                 | 22        | 33     | 0.64%   |
| Apple               | 22        | 26     | 0.64%   |
| Apacer              | 17        | 23     | 0.49%   |
| Corsair             | 16        | 41     | 0.46%   |
| KingSpec            | 15        | 19     | 0.44%   |
| Silicon Motion      | 14        | 19     | 0.41%   |
| Mushkin             | 14        | 21     | 0.41%   |
| KIOXIA              | 14        | 20     | 0.41%   |
| Patriot             | 12        | 15     | 0.35%   |
| Fanxiang            | 12        | 15     | 0.35%   |
| LITEON              | 11        | 17     | 0.32%   |
| Lexar               | 11        | 18     | 0.32%   |
| Zheino              | 10        | 18     | 0.29%   |
| Supermicro          | 10        | 10     | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB     | 34        | 0.9%    |
| Samsung SSD 850 EVO 250GB       | 32        | 0.85%   |
| Hoodisk SSD 32GB                | 29        | 0.77%   |
| Samsung SSD 970 EVO Plus 500GB  | 26        | 0.69%   |
| Samsung SSD 860 EVO 500GB       | 25        | 0.66%   |
| Kingston SUV500MS240G 240GB     | 24        | 0.64%   |
| Seagate ST500DM002-1BD142 500GB | 22        | 0.58%   |
| Kingston SA400S37120G 120GB     | 22        | 0.58%   |
| Samsung SSD 860 EVO 1TB         | 21        | 0.56%   |
| Kingston SUV500MS120G 120GB     | 21        | 0.56%   |
| PNY CS900 120GB SSD             | 20        | 0.53%   |
| Crucial CT500MX500SSD1 500GB    | 20        | 0.53%   |
| Samsung SSD 860 EVO 250GB       | 19        | 0.5%    |
| Samsung SSD 850 EVO 500GB       | 19        | 0.5%    |
| Protectli 120GB mSATA           | 19        | 0.5%    |
| Hoodisk SSD 128GB               | 19        | 0.5%    |
| BIWIN SSD 128GB                 | 19        | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB    | 18        | 0.48%   |
| Hoodisk SSD 64GB                | 16        | 0.42%   |
| WDC WD800JD-75MSA3 80GB         | 15        | 0.4%    |
| SanDisk SSD PLUS 240GB          | 15        | 0.4%    |
| Samsung SSD 870 EVO 500GB       | 15        | 0.4%    |
| Kingston SV300S37A120G 120GB    | 15        | 0.4%    |
| FORESEE 128GB SSD               | 15        | 0.4%    |
| Crucial CT250MX500SSD1 250GB    | 15        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB     | 15        | 0.4%    |
| Phison Sabrent 1TB              | 14        | 0.37%   |
| Transcend TS256GMTS952T2 256GB  | 13        | 0.34%   |
| SPCC Solid State Disk 128GB     | 13        | 0.34%   |
| Samsung SSD 860 EVO M.2 250GB   | 13        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB        | 12        | 0.32%   |
| SanDisk SDSSDA120G 120GB        | 12        | 0.32%   |
| China SATA SSD 120GB            | 12        | 0.32%   |
| WDC WDS500G3X0C-00SJG0 500GB    | 11        | 0.29%   |
| WDC WD30EFRX-68EUZN0 3TB        | 11        | 0.29%   |
| Toshiba DT01ACA100 1TB          | 11        | 0.29%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 11        | 0.29%   |
| Protectli 240GB mSATA           | 11        | 0.29%   |
| HP RAID 0 599GB                 | 11        | 0.29%   |
| Dogfish SSD 128GB               | 11        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 309       | 1058   | 34.49%  |
| Seagate                            | 288       | 774    | 32.14%  |
| Toshiba                            | 92        | 175    | 10.27%  |
| Hitachi                            | 69        | 163    | 7.7%    |
| HGST                               | 40        | 122    | 4.46%   |
| Hewlett-Packard                    | 23        | 74     | 2.57%   |
| NVMe                               | 17        | 23     | 1.9%    |
| Samsung Electronics                | 12        | 17     | 1.34%   |
| Apple                              | 10        | 11     | 1.12%   |
| Maxtor                             | 5         | 9      | 0.56%   |
| Fujitsu                            | 4         | 4      | 0.45%   |
| Lexar                              | 3         | 3      | 0.33%   |
| LSI                                | 2         | 8      | 0.22%   |
| HPE                                | 2         | 7      | 0.22%   |
| Adaptec                            | 2         | 2      | 0.22%   |
| WD MediaMax                        | 1         | 3      | 0.11%   |
| QUANTUM                            | 1         | 2      | 0.11%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.11%   |
| OPENBSD                            | 1         | 1      | 0.11%   |
| NETAPP                             | 1         | 2      | 0.11%   |
| Memorex                            | 1         | 1      | 0.11%   |
| MaxDigital                         | 1         | 1      | 0.11%   |
| MARVELL                            | 1         | 1      | 0.11%   |
| IBM/Hitachi                        | 1         | 1      | 0.11%   |
| IBM-ESXS                           | 1         | 1      | 0.11%   |
| IBM-207x                           | 1         | 1      | 0.11%   |
| HPT                                | 1         | 8      | 0.11%   |
| Generic                            | 1         | 1      | 0.11%   |
| General                            | 1         | 1      | 0.11%   |
| ExcelStor Technology               | 1         | 4      | 0.11%   |
| Dell                               | 1         | 3      | 0.11%   |
| China                              | 1         | 1      | 0.11%   |
| ASMT                               | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 361       | 717    | 18.23%  |
| Kingston            | 210       | 291    | 10.61%  |
| SanDisk             | 150       | 192    | 7.58%   |
| Crucial             | 139       | 216    | 7.02%   |
| Transcend           | 111       | 211    | 5.61%   |
| Intel               | 110       | 230    | 5.56%   |
| Hoodisk             | 70        | 98     | 3.54%   |
| China               | 67        | 101    | 3.38%   |
| Protectli           | 62        | 96     | 3.13%   |
| PNY                 | 59        | 85     | 2.98%   |
| A-DATA Technology   | 58        | 88     | 2.93%   |
| WDC                 | 48        | 86     | 2.42%   |
| SK hynix            | 39        | 54     | 1.97%   |
| SPCC                | 37        | 73     | 1.87%   |
| Dogfish             | 31        | 53     | 1.57%   |
| Phison              | 28        | 38     | 1.41%   |
| BIWIN               | 27        | 43     | 1.36%   |
| Micron Technology   | 24        | 31     | 1.21%   |
| FORESEE             | 24        | 36     | 1.21%   |
| OCZ                 | 22        | 33     | 1.11%   |
| Apacer              | 17        | 23     | 0.86%   |
| KingSpec            | 15        | 19     | 0.76%   |
| Seagate             | 13        | 27     | 0.66%   |
| Corsair             | 13        | 18     | 0.66%   |
| Team                | 12        | 27     | 0.61%   |
| Apple               | 12        | 15     | 0.61%   |
| Toshiba             | 11        | 15     | 0.56%   |
| Mushkin             | 11        | 17     | 0.56%   |
| Zheino              | 10        | 18     | 0.51%   |
| Supermicro          | 10        | 10     | 0.51%   |
| Patriot             | 10        | 13     | 0.51%   |
| OWC                 | 9         | 13     | 0.45%   |
| NVMe                | 9         | 11     | 0.45%   |
| LITEON              | 9         | 15     | 0.45%   |
| Innodisk            | 8         | 10     | 0.4%    |
| Plextor             | 7         | 12     | 0.35%   |
| LITEONIT            | 7         | 10     | 0.35%   |
| Lexar               | 7         | 14     | 0.35%   |
| Hewlett-Packard     | 7         | 12     | 0.35%   |
| Intenso             | 6         | 12     | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1781      | 3227   | 57.56%  |
| HDD  | 743       | 2484   | 24.01%  |
| NVMe | 570       | 950    | 18.42%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2298      | 5711   | 80.13%  |
| NVMe | 570       | 950    | 19.87%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1909      | 3370   | 71.9%   |
| 0.51-1.0   | 416       | 838    | 15.67%  |
| 1.01-2.0   | 145       | 396    | 5.46%   |
| 4.01-10.0  | 64        | 534    | 2.41%   |
| 3.01-4.0   | 51        | 223    | 1.92%   |
| 2.01-3.0   | 50        | 202    | 1.88%   |
| 10.01-20.0 | 19        | 144    | 0.72%   |
| 20.01-50.0 | 1         | 4      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1214      | 39.71%  |
| 251-500        | 567       | 18.55%  |
| 1-20           | 305       | 9.98%   |
| 51-100         | 295       | 9.65%   |
| 501-1000       | 293       | 9.58%   |
| 21-50          | 267       | 8.73%   |
| 1001-2000      | 70        | 2.29%   |
| More than 3000 | 25        | 0.82%   |
| Unknown        | 13        | 0.43%   |
| 2001-3000      | 8         | 0.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2741      | 90.02%  |
| 21-50          | 167       | 5.48%   |
| 51-100         | 63        | 2.07%   |
| 101-250        | 31        | 1.02%   |
| 251-500        | 14        | 0.46%   |
| Unknown        | 13        | 0.43%   |
| 501-1000       | 6         | 0.2%    |
| More than 3000 | 5         | 0.16%   |
| 2001-3000      | 2         | 0.07%   |
| 1001-2000      | 2         | 0.07%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 8         | 12     | 2.01%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.26%   |
| Kingston SV300S37A120G 120GB          | 5         | 5      | 1.26%   |
| Apacer 16GB SATA Flash Drive          | 5         | 9      | 1.26%   |
| SanDisk SSD PLUS 240GB                | 4         | 5      | 1.01%   |
| Kingston SV300S37A60G 64GB            | 4         | 4      | 1.01%   |
| Kingston SMS200S3120G 120GB           | 4         | 4      | 1.01%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 7      | 1.01%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3         | 3      | 0.75%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3         | 15     | 0.75%   |
| SK hynix SC210 mSATA 256GB            | 3         | 4      | 0.75%   |
| Seagate ST3500418AS 500GB             | 3         | 10     | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 3      | 0.75%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 7      | 0.75%   |
| Kingston SNS4151S316GD 16GB           | 3         | 5      | 0.75%   |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 0.75%   |
| WDC WD5003ABYX-18WERA0 500GB          | 2         | 5      | 0.5%    |
| WDC WD20EARS-00MVWB0 2TB              | 2         | 2      | 0.5%    |
| WDC WD2001FASS-00W2B0 2TB             | 2         | 3      | 0.5%    |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.5%    |
| WDC WD1600AAJS-75M0A0 160GB           | 2         | 2      | 0.5%    |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.5%    |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.5%    |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.5%    |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.5%    |
| SK hynix SC308 SATA 128GB             | 2         | 3      | 0.5%    |
| Seagate ST95005620AS 500GB            | 2         | 2      | 0.5%    |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.5%    |
| Seagate ST500LT012-1DG142 500GB       | 2         | 3      | 0.5%    |
| Seagate ST3500413AS 500GB             | 2         | 10     | 0.5%    |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.5%    |
| Seagate ST2000DL001-9VT156 2TB        | 2         | 2      | 0.5%    |
| Samsung Electronics SSD 950 PRO 256GB | 2         | 2      | 0.5%    |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.5%    |
| MyDigitalSSD SB2 256GB                | 2         | 4      | 0.5%    |
| Kingston SUV400S37120G 120GB          | 2         | 3      | 0.5%    |
| Kingston SNS4151S316G 16GB            | 2         | 3      | 0.5%    |
| Kingston SMS200S360G 64GB             | 2         | 2      | 0.5%    |
| Kingston SA400S37240G 240GB           | 2         | 2      | 0.5%    |
| Intel SSDSC2BX200G4R 200GB            | 2         | 3      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 142    | 21.09%  |
| WDC                 | 60        | 115    | 15.63%  |
| Kingston            | 31        | 35     | 8.07%   |
| Intel               | 28        | 35     | 7.29%   |
| Samsung Electronics | 25        | 38     | 6.51%   |
| Hitachi             | 23        | 30     | 5.99%   |
| Toshiba             | 21        | 30     | 5.47%   |
| Crucial             | 18        | 26     | 4.69%   |
| SanDisk             | 13        | 16     | 3.39%   |
| HGST                | 10        | 10     | 2.6%    |
| SK hynix            | 9         | 12     | 2.34%   |
| Apacer              | 8         | 12     | 2.08%   |
| OCZ                 | 4         | 4      | 1.04%   |
| Micron Technology   | 4         | 5      | 1.04%   |
| HP Phison           | 4         | 4      | 1.04%   |
| Phison              | 3         | 3      | 0.78%   |
| Maxtor              | 3         | 6      | 0.78%   |
| LITEON              | 3         | 4      | 0.78%   |
| Apple               | 3         | 3      | 0.78%   |
| SSSTC               | 2         | 2      | 0.52%   |
| SPCC                | 2         | 4      | 0.52%   |
| PNY                 | 2         | 2      | 0.52%   |
| Patriot             | 2         | 2      | 0.52%   |
| MyDigitalSSD        | 2         | 4      | 0.52%   |
| Corsair             | 2         | 2      | 0.52%   |
| A-DATA Technology   | 2         | 2      | 0.52%   |
| ZTC                 | 1         | 3      | 0.26%   |
| Wintec              | 1         | 1      | 0.26%   |
| WD MediaMax         | 1         | 3      | 0.26%   |
| VisionTek           | 1         | 1      | 0.26%   |
| Transcend           | 1         | 4      | 0.26%   |
| LITEONIT            | 1         | 3      | 0.26%   |
| KingSpec            | 1         | 1      | 0.26%   |
| KingDian            | 1         | 1      | 0.26%   |
| KeepData            | 1         | 1      | 0.26%   |
| INDMEM              | 1         | 1      | 0.26%   |
| IBM/Hitachi         | 1         | 1      | 0.26%   |
| HPE                 | 1         | 3      | 0.26%   |
| Hewlett-Packard     | 1         | 4      | 0.26%   |
| Fujitsu             | 1         | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 81        | 142    | 38.76%  |
| WDC                  | 59        | 114    | 28.23%  |
| Hitachi              | 23        | 30     | 11%     |
| Toshiba              | 19        | 28     | 9.09%   |
| HGST                 | 10        | 10     | 4.78%   |
| Samsung Electronics  | 5         | 6      | 2.39%   |
| Maxtor               | 3         | 6      | 1.44%   |
| Apple                | 2         | 2      | 0.96%   |
| WD MediaMax          | 1         | 3      | 0.48%   |
| IBM/Hitachi          | 1         | 1      | 0.48%   |
| HPE                  | 1         | 3      | 0.48%   |
| Hewlett-Packard      | 1         | 4      | 0.48%   |
| Fujitsu              | 1         | 1      | 0.48%   |
| ExcelStor Technology | 1         | 2      | 0.48%   |
| China                | 1         | 1      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 200       | 353    | 53.48%  |
| SSD  | 171       | 230    | 45.72%  |
| NVMe | 3         | 3      | 0.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 20%     |
| WDC WD3200L 320GB                            | 1         | 1      | 10%     |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 10%     |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 10%     |
| SanDisk pSSD 256GB                           | 1         | 1      | 10%     |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 10%     |
| Samsung Electronics PM981 NVMe 256GB         | 1         | 1      | 10%     |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 10%     |
| Kingston SA2000M8500G 500GB                  | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 50%     |
| WDC                 | 1         | 1      | 10%     |
| SK hynix            | 1         | 1      | 10%     |
| Seagate             | 1         | 2      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2414      | 5898   | 83.91%  |
| Malfunc  | 367       | 586    | 12.76%  |
| Detected | 86        | 165    | 2.99%   |
| Failed   | 10        | 12     | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2282      | 61.28%  |
| AMD                                     | 459       | 12.33%  |
| Samsung Electronics                     | 230       | 6.18%   |
| Broadcom / LSI                          | 133       | 3.57%   |
| SanDisk                                 | 110       | 2.95%   |
| Phison Electronics                      | 59        | 1.58%   |
| ASMedia Technology                      | 55        | 1.48%   |
| Silicon Motion                          | 46        | 1.24%   |
| Marvell Technology Group                | 37        | 0.99%   |
| SK hynix                                | 35        | 0.94%   |
| Micron/Crucial Technology               | 29        | 0.78%   |
| Kingston Technology Company             | 26        | 0.7%    |
| Chelsio Communications                  | 25        | 0.67%   |
| MAXIO Technology (Hangzhou)             | 19        | 0.51%   |
| Hewlett-Packard                         | 19        | 0.51%   |
| Micron Technology                       | 16        | 0.43%   |
| JMicron Technology                      | 16        | 0.43%   |
| KIOXIA                                  | 15        | 0.4%    |
| Nvidia                                  | 14        | 0.38%   |
| Toshiba                                 | 13        | 0.35%   |
| Adaptec                                 | 11        | 0.3%    |
| Realtek Semiconductor                   | 10        | 0.27%   |
| ADATA Technology                        | 8         | 0.21%   |
| Silicon Image                           | 6         | 0.16%   |
| Seagate Technology                      | 6         | 0.16%   |
| Transcend                               | 5         | 0.13%   |
| Shenzhen Longsys Electronics            | 4         | 0.11%   |
| VIA Technologies                        | 3         | 0.08%   |
| Solid State Storage Technology          | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.08%   |
| Lite-On Technology                      | 3         | 0.08%   |
| Union Memory (Shenzhen)                 | 2         | 0.05%   |
| Shenzhen Unionmemory Information System | 2         | 0.05%   |
| Netac Technology                        | 2         | 0.05%   |
| Lenovo                                  | 2         | 0.05%   |
| Hosin Global Electronics                | 2         | 0.05%   |
| HighPoint Technologies                  | 2         | 0.05%   |
| Dell                                    | 2         | 0.05%   |
| Broadcom                                | 2         | 0.05%   |
| Biwin Storage Technology                | 2         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 322       | 7.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 238       | 5.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 166       | 3.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 147       | 3.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 128       | 3.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 121       | 2.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 117       | 2.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 117       | 2.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 85        | 2.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 84        | 1.98%   |
| Intel SATA Controller [RAID mode]                                                | 81        | 1.91%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 72        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 65        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 60        | 1.42%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 59        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 57        | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 49        | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 47        | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                           | 47        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 46        | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 45        | 1.06%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 44        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 43        | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 41        | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 40        | 0.95%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 40        | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 39        | 0.92%   |
| AMD FCH IDE Controller                                                           | 38        | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 37        | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 37        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                           | 37        | 0.87%   |
| Samsung NVMe SSD Controller 980                                                  | 36        | 0.85%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 36        | 0.85%   |
| Phison E12 NVMe Controller                                                       | 32        | 0.76%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 32        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 32        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 32        | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 31        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 27        | 0.64%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 25        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2428      | 64.75%  |
| NVMe | 641       | 17.09%  |
| IDE  | 333       | 8.88%   |
| RAID | 222       | 5.92%   |
| SAS  | 81        | 2.16%   |
| SCSI | 45        | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2415      | 81.95%  |
| AMD      | 502       | 17.03%  |
| ARM      | 19        | 0.64%   |
| Unknown  | 5         | 0.17%   |
| IBM      | 2         | 0.07%   |
| NXP      | 1         | 0.03%   |
| Motorola | 1         | 0.03%   |
| i        | 1         | 0.03%   |
| Broadcom | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 85        | 2.84%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 77        | 2.57%   |
| Intel Celeron N5105 @ 2.00GHz            | 67        | 2.24%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 49        | 1.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 42        | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz        | 35        | 1.17%   |
| AMD GX-412TC SOC                         | 35        | 1.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 30        | 1%      |
| AMD RX-427BB with AMD Radeon R7 Graphics | 29        | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 27        | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz         | 26        | 0.87%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 25        | 0.84%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 25        | 0.84%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 23        | 0.77%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 22        | 0.73%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 22        | 0.73%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 21        | 0.7%    |
| Intel Atom CPU D525 @ 1.80GHz            | 19        | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 18        | 0.6%    |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 17        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 17        | 0.57%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 17        | 0.57%   |
| Intel Core i5-7500 CPU @ 3.40GHz         | 16        | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 16        | 0.53%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 16        | 0.53%   |
| Intel N100                               | 15        | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz         | 15        | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz        | 15        | 0.5%    |
| Intel Pentium Silver N6005 @ 2.00GHz     | 14        | 0.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 14        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 14        | 0.47%   |
| Intel Core 2 Duo                         | 14        | 0.47%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 14        | 0.47%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 13        | 0.43%   |
| Intel Pentium CPU J3710 @ 1.60GHz        | 13        | 0.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 13        | 0.43%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 13        | 0.43%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 13        | 0.43%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 13        | 0.43%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 13        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 582       | 19.58%  |
| Intel Celeron           | 470       | 15.81%  |
| Intel Xeon              | 397       | 13.36%  |
| Intel Core i7           | 335       | 11.27%  |
| Intel Core i3           | 183       | 6.16%   |
| Other                   | 149       | 5.01%   |
| Intel Atom              | 141       | 4.74%   |
| AMD Ryzen 7             | 86        | 2.89%   |
| AMD GX                  | 74        | 2.49%   |
| Intel Pentium           | 72        | 2.42%   |
| AMD Ryzen 5             | 64        | 2.15%   |
| Intel Core 2 Duo        | 51        | 1.72%   |
| Intel Pentium Silver    | 30        | 1.01%   |
| AMD Ryzen 9             | 26        | 0.87%   |
| AMD FX                  | 23        | 0.77%   |
| AMD EPYC                | 23        | 0.77%   |
| AMD Ryzen 3             | 21        | 0.71%   |
| AMD A10                 | 19        | 0.64%   |
| ARM Cortex              | 18        | 0.61%   |
| Intel Core i9           | 13        | 0.44%   |
| Intel Core 2 Quad       | 12        | 0.4%    |
| AMD Ryzen 5 PRO         | 11        | 0.37%   |
| Intel Core 2            | 10        | 0.34%   |
| AMD Phenom II X4        | 10        | 0.34%   |
| AMD G                   | 10        | 0.34%   |
| AMD Athlon              | 10        | 0.34%   |
| AMD Ryzen Embedded      | 9         | 0.3%    |
| AMD A8                  | 9         | 0.3%    |
| AMD A6                  | 8         | 0.27%   |
| Intel Genuine           | 7         | 0.24%   |
| Intel Pentium Dual-Core | 6         | 0.2%    |
| Intel Pentium 4         | 6         | 0.2%    |
| AMD Opteron             | 6         | 0.2%    |
| AMD Ryzen Threadripper  | 5         | 0.17%   |
| AMD Phenom II X6        | 5         | 0.17%   |
| AMD A4                  | 5         | 0.17%   |
| AMD Ryzen 7 PRO         | 4         | 0.13%   |
| AMD E2                  | 4         | 0.13%   |
| AMD E1                  | 4         | 0.13%   |
| AMD E                   | 4         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1537      | 51.66%  |
| 2       | 702       | 23.6%   |
| 8       | 197       | 6.62%   |
| 6       | 147       | 4.94%   |
| 16      | 105       | 3.53%   |
| Unknown | 103       | 3.46%   |
| 12      | 98        | 3.29%   |
| 1       | 23        | 0.77%   |
| 24      | 19        | 0.64%   |
| 32      | 12        | 0.4%    |
| 10      | 10        | 0.34%   |
| 20      | 7         | 0.24%   |
| 48      | 3         | 0.1%    |
| 14      | 3         | 0.1%    |
| 64      | 2         | 0.07%   |
| 36      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 3       | 2         | 0.07%   |
| 40      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2784      | 94.47%  |
| 2       | 121       | 4.11%   |
| Unknown | 40        | 1.36%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1648      | 55.66%  |
| 2       | 1199      | 40.49%  |
| Unknown | 113       | 3.82%   |
| 4       | 1         | 0.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 388       | 13.04%  |
| Haswell         | 330       | 11.09%  |
| Silvermont      | 272       | 9.14%   |
| Unknown         | 210       | 7.06%   |
| IvyBridge       | 208       | 6.99%   |
| Skylake         | 191       | 6.42%   |
| SandyBridge     | 180       | 6.05%   |
| Goldmont plus   | 133       | 4.47%   |
| Broadwell       | 116       | 3.9%    |
| Westmere        | 73        | 2.45%   |
| Goldmont        | 73        | 2.45%   |
| Zen 2           | 65        | 2.18%   |
| Zen+            | 64        | 2.15%   |
| Zen             | 60        | 2.02%   |
| Penryn          | 58        | 1.95%   |
| Zen 3           | 57        | 1.92%   |
| Nehalem         | 48        | 1.61%   |
| Bonnell         | 48        | 1.61%   |
| Core            | 47        | 1.58%   |
| CometLake       | 46        | 1.55%   |
| Jaguar          | 45        | 1.51%   |
| Puma            | 44        | 1.48%   |
| Steamroller     | 39        | 1.31%   |
| Piledriver      | 38        | 1.28%   |
| TigerLake       | 31        | 1.04%   |
| K10             | 25        | 0.84%   |
| Bobcat          | 22        | 0.74%   |
| Excavator       | 20        | 0.67%   |
| NetBurst        | 16        | 0.54%   |
| K8 Hammer       | 10        | 0.34%   |
| P6              | 5         | 0.17%   |
| IceLake         | 5         | 0.17%   |
| K10 Llano       | 4         | 0.13%   |
| Bulldozer       | 2         | 0.07%   |
| K8 & K10 hybrid | 1         | 0.03%   |
| Geode           | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1791      | 60.67%  |
| AMD                                          | 465       | 15.75%  |
| Nvidia                                       | 296       | 10.03%  |
| ASPEED Technology                            | 200       | 6.78%   |
| Matrox Electronics Systems                   | 193       | 6.54%   |
| XGI Technology (eXtreme Graphics Innovation) | 4         | 0.14%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 200       | 6.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 148       | 4.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 130       | 4.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 117       | 3.89%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 116       | 3.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 112       | 3.72%   |
| Intel HD Graphics 530                                                                    | 107       | 3.56%   |
| Intel JasperLake [UHD Graphics]                                                          | 86        | 2.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 83        | 2.76%   |
| Intel HD Graphics 620                                                                    | 79        | 2.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 79        | 2.63%   |
| Intel UHD Graphics 620                                                                   | 57        | 1.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 55        | 1.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 52        | 1.73%   |
| Intel HD Graphics 630                                                                    | 48        | 1.6%    |
| Matrox Electronics Systems G200eR2                                                       | 47        | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 1.56%   |
| Intel HD Graphics 500                                                                    | 43        | 1.43%   |
| Intel HD Graphics 5500                                                                   | 40        | 1.33%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 37        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 33        | 1.1%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 29        | 0.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 0.93%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 27        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 26        | 0.86%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 26        | 0.86%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 25        | 0.83%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 24        | 0.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 0.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 0.76%   |
| Intel HD Graphics 610                                                                    | 22        | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 0.7%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21        | 0.7%    |
| AMD Renoir                                                                               | 21        | 0.7%    |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 18        | 0.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 0.6%    |
| AMD ES1000                                                                               | 18        | 0.6%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 16        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1628      | 54.83%  |
| 1 x AMD         | 419       | 14.11%  |
| 1 x Nvidia      | 211       | 7.11%   |
| 1 x Matrox      | 191       | 6.43%   |
| 1 x ASPEED      | 186       | 6.26%   |
| Other           | 130       | 4.38%   |
| Intel + Nvidia  | 68        | 2.29%   |
| 2 x Intel       | 66        | 2.22%   |
| Intel + AMD     | 23        | 0.77%   |
| AMD + Nvidia    | 11        | 0.37%   |
| 2 x AMD         | 10        | 0.34%   |
| Intel + ASPEED  | 8         | 0.27%   |
| Nvidia + ASPEED | 5         | 0.17%   |
| 1 x XGI         | 4         | 0.13%   |
| 2 x Nvidia      | 3         | 0.1%    |
| 1 x SiS         | 3         | 0.1%    |
| AMD + ASPEED    | 2         | 0.07%   |
| AMD + Matrox    | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2641      | 89.31%  |
| Unknown     | 165       | 5.58%   |
| Proprietary | 151       | 5.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2708      | 91.24%  |
| 1.01-2.0   | 65        | 2.19%   |
| 0.01-0.5   | 56        | 1.89%   |
| 3.01-4.0   | 42        | 1.42%   |
| 7.01-8.0   | 31        | 1.04%   |
| 0.51-1.0   | 31        | 1.04%   |
| 5.01-6.0   | 20        | 0.67%   |
| 8.01-16.0  | 10        | 0.34%   |
| 2.01-3.0   | 4         | 0.13%   |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 71        | 10.57%  |
| Samsung Electronics     | 69        | 10.27%  |
| AU Optronics            | 69        | 10.27%  |
| Dell                    | 62        | 9.23%   |
| BOE                     | 50        | 7.44%   |
| Chimei Innolux          | 42        | 6.25%   |
| Goldstar                | 36        | 5.36%   |
| Acer                    | 34        | 5.06%   |
| Lenovo                  | 31        | 4.61%   |
| Hewlett-Packard         | 26        | 3.87%   |
| Apple                   | 22        | 3.27%   |
| Ancor Communications    | 22        | 3.27%   |
| AOC                     | 12        | 1.79%   |
| Vizio                   | 10        | 1.49%   |
| ASUSTek Computer        | 10        | 1.49%   |
| ViewSonic               | 9         | 1.34%   |
| Sharp                   | 9         | 1.34%   |
| Sceptre Tech            | 8         | 1.19%   |
| BenQ                    | 8         | 1.19%   |
| LG Electronics          | 7         | 1.04%   |
| Chi Mei Optoelectronics | 7         | 1.04%   |
| InfoVision              | 5         | 0.74%   |
| Sony                    | 3         | 0.45%   |
| Philips                 | 3         | 0.45%   |
| MSI                     | 3         | 0.45%   |
| LGD                     | 3         | 0.45%   |
| Lenovo Group Limited    | 3         | 0.45%   |
| Insignia                | 3         | 0.45%   |
| HannStar                | 3         | 0.45%   |
| Westinghouse            | 2         | 0.3%    |
| NEC Computers           | 2         | 0.3%    |
| LG Philips              | 2         | 0.3%    |
| IBM                     | 2         | 0.3%    |
| Unknown                 | 2         | 0.3%    |
| unknown                 | 1         | 0.15%   |
| Toshiba                 | 1         | 0.15%   |
| Tech Concepts           | 1         | 0.15%   |
| SHI                     | 1         | 0.15%   |
| SGT                     | 1         | 0.15%   |
| Seiko/Epson             | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 7         | 1.01%   |
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                 | 7         | 1.01%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 5         | 0.72%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 4         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 4         | 0.58%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 4         | 0.58%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 4         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 4         | 0.58%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3         | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 3         | 0.43%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 3         | 0.43%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 3         | 0.43%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 3         | 0.43%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 3         | 0.43%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 3         | 0.43%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                     | 3         | 0.43%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 3         | 0.43%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                 | 3         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 3         | 0.43%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                  | 3         | 0.43%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.43%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 3         | 0.43%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 3         | 0.43%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                     | 3         | 0.43%   |
| Sony TV SNY9C01 1360x768                                              | 2         | 0.29%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch        | 2         | 0.29%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 2         | 0.29%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch   | 2         | 0.29%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch     | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch  | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 2         | 0.29%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch | 2         | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch          | 2         | 0.29%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 0.29%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 2         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 221       | 33.33%  |
| 1366x768 (WXGA)    | 132       | 19.91%  |
| 3840x2160 (4K)     | 45        | 6.79%   |
| 2560x1440 (QHD)    | 44        | 6.64%   |
| 1600x900 (HD+)     | 36        | 5.43%   |
| 1280x800 (WXGA)    | 26        | 3.92%   |
| 1920x1200 (WUXGA)  | 24        | 3.62%   |
| 1280x1024 (SXGA)   | 20        | 3.02%   |
| 1680x1050 (WSXGA+) | 18        | 2.71%   |
| 2560x1080          | 13        | 1.96%   |
| 3440x1440          | 12        | 1.81%   |
| 1440x900 (WXGA+)   | 12        | 1.81%   |
| 1360x768           | 8         | 1.21%   |
| 2256x1504          | 7         | 1.06%   |
| Unknown            | 7         | 1.06%   |
| 2560x1600          | 6         | 0.9%    |
| 1024x768 (XGA)     | 6         | 0.9%    |
| 1024x600           | 5         | 0.75%   |
| 3200x1800 (QHD+)   | 3         | 0.45%   |
| 3840x1600          | 2         | 0.3%    |
| 3840x1080          | 2         | 0.3%    |
| 1600x1200          | 2         | 0.3%    |
| 7040x1440          | 1         | 0.15%   |
| 5760x2160          | 1         | 0.15%   |
| 5760x1080          | 1         | 0.15%   |
| 4640x1080          | 1         | 0.15%   |
| 4480x1080          | 1         | 0.15%   |
| 3520x1080          | 1         | 0.15%   |
| 2880x1620          | 1         | 0.15%   |
| 2806x900           | 1         | 0.15%   |
| 1920x540           | 1         | 0.15%   |
| 1920x1920          | 1         | 0.15%   |
| 1400x1050          | 1         | 0.15%   |
| 1280x768           | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 130       | 19.37%  |
| 13      | 113       | 16.84%  |
| 24      | 57        | 8.49%   |
| 27      | 53        | 7.9%    |
| Unknown | 42        | 6.26%   |
| 31      | 29        | 4.32%   |
| 17      | 27        | 4.02%   |
| 12      | 27        | 4.02%   |
| 19      | 26        | 3.87%   |
| 11      | 25        | 3.73%   |
| 23      | 24        | 3.58%   |
| 21      | 24        | 3.58%   |
| 14      | 21        | 3.13%   |
| 34      | 16        | 2.38%   |
| 22      | 9         | 1.34%   |
| 29      | 7         | 1.04%   |
| 20      | 6         | 0.89%   |
| 18      | 5         | 0.75%   |
| 64      | 4         | 0.6%    |
| 26      | 4         | 0.6%    |
| 42      | 2         | 0.3%    |
| 37      | 2         | 0.3%    |
| 35      | 2         | 0.3%    |
| 16      | 2         | 0.3%    |
| 10      | 2         | 0.3%    |
| 9       | 2         | 0.3%    |
| 54      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 43      | 1         | 0.15%   |
| 41      | 1         | 0.15%   |
| 39      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |
| 25      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 215       | 32.63%  |
| 501-600     | 125       | 18.97%  |
| 201-300     | 114       | 17.3%   |
| 401-500     | 61        | 9.26%   |
| 601-700     | 42        | 6.37%   |
| Unknown     | 42        | 6.37%   |
| 351-400     | 24        | 3.64%   |
| 701-800     | 17        | 2.58%   |
| 1001-1500   | 7         | 1.06%   |
| 801-900     | 5         | 0.76%   |
| 901-1000    | 4         | 0.61%   |
| 101-200     | 3         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 445       | 70.75%  |
| 16/10   | 75        | 11.92%  |
| Unknown | 38        | 6.04%   |
| 21/9    | 25        | 3.97%   |
| 5/4     | 17        | 2.7%    |
| 3/2     | 14        | 2.23%   |
| 4/3     | 10        | 1.59%   |
| 6/5     | 3         | 0.48%   |
| 32/9    | 1         | 0.16%   |
| 1.00    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 112       | 16.77%  |
| 91-100         | 100       | 14.97%  |
| 201-250        | 93        | 13.92%  |
| 301-350        | 59        | 8.83%   |
| 351-500        | 51        | 7.63%   |
| Unknown        | 42        | 6.29%   |
| 151-200        | 32        | 4.79%   |
| 101-110        | 31        | 4.64%   |
| 61-70          | 28        | 4.19%   |
| 51-60          | 24        | 3.59%   |
| 251-300        | 21        | 3.14%   |
| 121-130        | 17        | 2.54%   |
| 71-80          | 16        | 2.4%    |
| 141-150        | 16        | 2.4%    |
| 501-1000       | 8         | 1.2%    |
| More than 1000 | 6         | 0.9%    |
| 111-120        | 5         | 0.75%   |
| 1-40           | 3         | 0.45%   |
| 41-50          | 2         | 0.3%    |
| 131-140        | 2         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 203       | 31.18%  |
| 121-160       | 177       | 27.19%  |
| 101-120       | 164       | 25.19%  |
| 161-240       | 47        | 7.22%   |
| Unknown       | 42        | 6.45%   |
| More than 240 | 14        | 2.15%   |
| 1-50          | 4         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2266      | 76.48%  |
| 1     | 622       | 20.99%  |
| 2     | 67        | 2.26%   |
| 3     | 7         | 0.24%   |
| 4     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2377      | 57.89%  |
| Realtek Semiconductor           | 868       | 21.14%  |
| Broadcom                        | 293       | 7.14%   |
| Qualcomm Atheros                | 183       | 4.46%   |
| Mellanox Technologies           | 52        | 1.27%   |
| Ralink Technology               | 34        | 0.83%   |
| Chelsio Communications          | 28        | 0.68%   |
| IMC Networks                    | 22        | 0.54%   |
| AMD                             | 19        | 0.46%   |
| Marvell Technology Group        | 17        | 0.41%   |
| U-Blox                          | 16        | 0.39%   |
| Ralink                          | 15        | 0.37%   |
| TP-Link                         | 14        | 0.34%   |
| Edimax Technology               | 13        | 0.32%   |
| Solarflare Communications       | 12        | 0.29%   |
| Aquantia                        | 10        | 0.24%   |
| MediaTek                        | 8         | 0.19%   |
| Google                          | 8         | 0.19%   |
| D-Link System                   | 8         | 0.19%   |
| Novatel Wireless                | 7         | 0.17%   |
| NetGear                         | 7         | 0.17%   |
| Seeed Technology                | 6         | 0.15%   |
| Nvidia                          | 6         | 0.15%   |
| Emulex                          | 6         | 0.15%   |
| QLogic                          | 5         | 0.12%   |
| Dell                            | 5         | 0.12%   |
| ASUSTek Computer                | 5         | 0.12%   |
| Apple                           | 5         | 0.12%   |
| American Megatrends             | 4         | 0.1%    |
| Sierra Wireless                 | 3         | 0.07%   |
| Sequans Communications          | 3         | 0.07%   |
| Cisco Systems                   | 3         | 0.07%   |
| VIA Technologies                | 2         | 0.05%   |
| Qualcomm Atheros Communications | 2         | 0.05%   |
| Qualcomm                        | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)   | 2         | 0.05%   |
| Linksys                         | 2         | 0.05%   |
| Insyde Software                 | 2         | 0.05%   |
| D-Link                          | 2         | 0.05%   |
| Belkin Components               | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 683       | 12.94%  |
| Intel I211 Gigabit Network Connection                                         | 326       | 6.18%   |
| Intel I210 Gigabit Network Connection                                         | 247       | 4.68%   |
| Intel I350 Gigabit Network Connection                                         | 220       | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 181       | 3.43%   |
| Intel Ethernet Controller I225-V                                              | 164       | 3.11%   |
| Intel 82574L Gigabit Network Connection                                       | 145       | 2.75%   |
| Intel Ethernet Connection I217-LM                                             | 119       | 2.25%   |
| Intel Ethernet Controller I226-V                                              | 91        | 1.72%   |
| Intel 82580 Gigabit Network Connection                                        | 91        | 1.72%   |
| Intel 82583V Gigabit Network Connection                                       | 90        | 1.71%   |
| Intel Wi-Fi 6 AX200                                                           | 79        | 1.5%    |
| Intel 82576 Gigabit Network Connection                                        | 79        | 1.5%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 77        | 1.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 77        | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                             | 75        | 1.42%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 75        | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                                         | 66        | 1.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 55        | 1.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 52        | 0.99%   |
| Intel Wireless 8265 / 8275                                                    | 51        | 0.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 50        | 0.95%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 45        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 43        | 0.81%   |
| Intel Wireless 7260                                                           | 41        | 0.78%   |
| Intel Wireless 8260                                                           | 40        | 0.76%   |
| Intel Wireless 7265                                                           | 40        | 0.76%   |
| Intel Ethernet Connection I354                                                | 36        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                          | 35        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                         | 34        | 0.64%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 34        | 0.64%   |
| Intel Wireless 3165                                                           | 32        | 0.61%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 31        | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 29        | 0.55%   |
| Intel Ethernet Controller X550                                                | 29        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                          | 29        | 0.55%   |
| Intel Wireless-AC 9260                                                        | 24        | 0.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 24        | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 24        | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 22        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 584       | 54.17%  |
| Qualcomm Atheros                | 157       | 14.56%  |
| Realtek Semiconductor           | 126       | 11.69%  |
| Broadcom                        | 78        | 7.24%   |
| Ralink Technology               | 34        | 3.15%   |
| IMC Networks                    | 22        | 2.04%   |
| Ralink                          | 15        | 1.39%   |
| TP-Link                         | 14        | 1.3%    |
| Edimax Technology               | 13        | 1.21%   |
| MediaTek                        | 8         | 0.74%   |
| NetGear                         | 7         | 0.65%   |
| ASUSTek Computer                | 5         | 0.46%   |
| Sierra Wireless                 | 2         | 0.19%   |
| Qualcomm Atheros Communications | 2         | 0.19%   |
| D-Link System                   | 2         | 0.19%   |
| D-Link                          | 2         | 0.19%   |
| Belkin Components               | 2         | 0.19%   |
| ZyXEL Communications            | 1         | 0.09%   |
| Marvell Technology Group        | 1         | 0.09%   |
| Linksys                         | 1         | 0.09%   |
| Dell                            | 1         | 0.09%   |
| AboCom Systems                  | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 79        | 7.25%   |
| Intel Wireless 8265 / 8275                                              | 51        | 4.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 3.94%   |
| Intel Wireless 7260                                                     | 41        | 3.76%   |
| Intel Wireless 8260                                                     | 40        | 3.67%   |
| Intel Wireless 7265                                                     | 40        | 3.67%   |
| Intel Wireless 3165                                                     | 32        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 2.66%   |
| Intel Wireless-AC 9260                                                  | 24        | 2.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 24        | 2.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 24        | 2.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 22        | 2.02%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 22        | 2.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 20        | 1.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 17        | 1.56%   |
| Ralink RT5370 Wireless Adapter                                          | 16        | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 1.38%   |
| Intel Wireless 3160                                                     | 15        | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 14        | 1.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 14        | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 1.19%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 13        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 11        | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 0.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 10        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.83%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 9         | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 7         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2129      | 63.29%  |
| Realtek Semiconductor            | 807       | 23.99%  |
| Broadcom                         | 246       | 7.31%   |
| Qualcomm Atheros                 | 34        | 1.01%   |
| Chelsio Communications           | 25        | 0.74%   |
| AMD                              | 18        | 0.54%   |
| Marvell Technology Group         | 15        | 0.45%   |
| Solarflare Communications        | 12        | 0.36%   |
| Aquantia                         | 9         | 0.27%   |
| Novatel Wireless                 | 7         | 0.21%   |
| Nvidia                           | 6         | 0.18%   |
| Emulex                           | 6         | 0.18%   |
| D-Link System                    | 6         | 0.18%   |
| QLogic                           | 5         | 0.15%   |
| Apple                            | 4         | 0.12%   |
| American Megatrends              | 4         | 0.12%   |
| Google                           | 3         | 0.09%   |
| Cisco Systems                    | 3         | 0.09%   |
| VIA Technologies                 | 2         | 0.06%   |
| Qualcomm                         | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.06%   |
| Insyde Software                  | 2         | 0.06%   |
| 3Com                             | 2         | 0.06%   |
| Xiaomi                           | 1         | 0.03%   |
| TRENDnet                         | 1         | 0.03%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Silicom                          | 1         | 0.03%   |
| Samsung Electronics              | 1         | 0.03%   |
| Oracle/SUN                       | 1         | 0.03%   |
| National Semiconductor           | 1         | 0.03%   |
| MYRICOM                          | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| Amazon.com                       | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 683       | 16.81%  |
| Intel I211 Gigabit Network Connection                                         | 326       | 8.03%   |
| Intel I210 Gigabit Network Connection                                         | 247       | 6.08%   |
| Intel I350 Gigabit Network Connection                                         | 220       | 5.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 181       | 4.46%   |
| Intel Ethernet Controller I225-V                                              | 164       | 4.04%   |
| Intel 82574L Gigabit Network Connection                                       | 145       | 3.57%   |
| Intel Ethernet Connection I217-LM                                             | 119       | 2.93%   |
| Intel Ethernet Controller I226-V                                              | 91        | 2.24%   |
| Intel 82580 Gigabit Network Connection                                        | 91        | 2.24%   |
| Intel 82583V Gigabit Network Connection                                       | 90        | 2.22%   |
| Intel 82576 Gigabit Network Connection                                        | 79        | 1.94%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 77        | 1.9%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 77        | 1.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 75        | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                             | 72        | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                                         | 66        | 1.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 55        | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 52        | 1.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 50        | 1.23%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 45        | 1.11%   |
| Intel Ethernet Connection I354                                                | 36        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                          | 35        | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                                         | 34        | 0.84%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 34        | 0.84%   |
| Intel Ethernet Controller X550                                                | 29        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                          | 29        | 0.71%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 22        | 0.54%   |
| Intel Ethernet Connection X553 1GbE                                           | 21        | 0.52%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 20        | 0.49%   |
| Intel 82579V Gigabit Network Connection                                       | 20        | 0.49%   |
| Intel 82575EB Gigabit Network Connection                                      | 20        | 0.49%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 18        | 0.44%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 18        | 0.44%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 17        | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                         | 17        | 0.42%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 17        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 16        | 0.39%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 16        | 0.39%   |
| Intel Ethernet Controller I225-LM                                             | 16        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2817      | 71.44%  |
| WiFi     | 1003      | 25.44%  |
| Unknown  | 88        | 2.23%   |
| Modem    | 35        | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2632      | 85.9%   |
| WiFi     | 423       | 13.81%  |
| Unknown  | 9         | 0.29%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 850       | 28.23%  |
| 4     | 614       | 20.39%  |
| 3     | 410       | 13.62%  |
| 1     | 371       | 12.32%  |
| 6     | 317       | 10.53%  |
| 5     | 224       | 7.44%   |
| 8     | 66        | 2.19%   |
| 7     | 60        | 1.99%   |
| 0     | 28        | 0.93%   |
| 10    | 26        | 0.86%   |
| 9     | 22        | 0.73%   |
| 11    | 7         | 0.23%   |
| 13    | 4         | 0.13%   |
| 16    | 3         | 0.1%    |
| 14    | 3         | 0.1%    |
| 12    | 3         | 0.1%    |
| 15    | 2         | 0.07%   |
| 20    | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2443      | 79.73%  |
| Yes  | 621       | 20.27%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 438       | 61.43%  |
| Broadcom                        | 53        | 7.43%   |
| Realtek Semiconductor           | 47        | 6.59%   |
| Apple                           | 47        | 6.59%   |
| Qualcomm Atheros Communications | 31        | 4.35%   |
| IMC Networks                    | 27        | 3.79%   |
| Cambridge Silicon Radio         | 14        | 1.96%   |
| ASUSTek Computer                | 12        | 1.68%   |
| Lite-On Technology              | 10        | 1.4%    |
| Dell                            | 9         | 1.26%   |
| MediaTek                        | 6         | 0.84%   |
| Foxconn / Hon Hai               | 6         | 0.84%   |
| Alps Electric                   | 4         | 0.56%   |
| Ralink                          | 2         | 0.28%   |
| TP-Link                         | 1         | 0.14%   |
| Taiyo Yuden                     | 1         | 0.14%   |
| Primax Electronics              | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |
| Esel International              | 1         | 0.14%   |
| Dynex                           | 1         | 0.14%   |
| Corsair                         | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 181       | 25.28%  |
| Intel AX200 Bluetooth                                       | 71        | 9.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 60        | 8.38%   |
| Intel AX201 Bluetooth                                       | 40        | 5.59%   |
| Intel Wireless-AC 3168 Bluetooth                            | 25        | 3.49%   |
| Intel AX210 Bluetooth                                       | 22        | 3.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 21        | 2.93%   |
| Apple Bluetooth Host Controller                             | 21        | 2.93%   |
| Realtek  Bluetooth 4.2 Adapter                              | 18        | 2.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 16        | 2.23%   |
| Realtek Bluetooth Adapter                                   | 14        | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 14        | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 14        | 1.96%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 12        | 1.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 11        | 1.54%   |
| Apple Broadcom Built-in Bluetooth                           | 10        | 1.4%    |
| IMC Networks Realtek Bluetooth Adapter                      | 9         | 1.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 9         | 1.26%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 7         | 0.98%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 6         | 0.84%   |
| Lite-On Bluetooth USB Module                                | 6         | 0.84%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 6         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 6         | 0.84%   |
| Realtek Bluetooth 4.2 Adapter                               | 5         | 0.7%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.7%    |
| MediaTek RZ608 Bluetooth Adapter                            | 5         | 0.7%    |
| Dell DW375 Bluetooth Module                                 | 5         | 0.7%    |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 0.56%   |
| Intel Wireless Bluetooth                                    | 4         | 0.56%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.42%   |
| Realtek Bluetooth 4.0 Adapter                               | 3         | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3         | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.42%   |
| ASUS USB-BT500                                              | 3         | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.28%   |
| Ralink RT3290 Bluetooth                                     | 2         | 0.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 2         | 0.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1722      | 66.67%  |
| AMD                                          | 504       | 19.51%  |
| Nvidia                                       | 230       | 8.9%    |
| C-Media Electronics                          | 37        | 1.43%   |
| Creative Labs                                | 13        | 0.5%    |
| Texas Instruments                            | 6         | 0.23%   |
| SteelSeries ApS                              | 6         | 0.23%   |
| Logitech                                     | 6         | 0.23%   |
| Realtek Semiconductor                        | 5         | 0.19%   |
| Blue Microphones                             | 5         | 0.19%   |
| Creative Technology                          | 3         | 0.12%   |
| Corsair                                      | 3         | 0.12%   |
| Yamaha                                       | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.08%   |
| Razer USA                                    | 2         | 0.08%   |
| MosArt Semiconductor                         | 2         | 0.08%   |
| Lenovo                                       | 2         | 0.08%   |
| Google                                       | 2         | 0.08%   |
| Generalplus Technology                       | 2         | 0.08%   |
| CMX Systems                                  | 2         | 0.08%   |
| Cambridge Silicon Radio                      | 2         | 0.08%   |
| ASUSTek Computer                             | 2         | 0.08%   |
| Apple                                        | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| XMOS                                         | 1         | 0.04%   |
| VIA Technologies                             | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.04%   |
| Tenx Technology                              | 1         | 0.04%   |
| Quanta                                       | 1         | 0.04%   |
| Nektar                                       | 1         | 0.04%   |
| LG Electronics                               | 1         | 0.04%   |
| KORG                                         | 1         | 0.04%   |
| Kingston Technology                          | 1         | 0.04%   |
| JMTek                                        | 1         | 0.04%   |
| Hewlett-Packard                              | 1         | 0.04%   |
| Harman                                       | 1         | 0.04%   |
| Genesys Logic                                | 1         | 0.04%   |
| Focusrite-Novation                           | 1         | 0.04%   |
| ESS Technology                               | 1         | 0.04%   |
| Dell                                         | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 172       | 5.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 154       | 4.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 140       | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 130       | 4.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 127       | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 121       | 3.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 119       | 3.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 101       | 3.22%   |
| AMD FCH Azalia Controller                                                                         | 100       | 3.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 97        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 94        | 2.99%   |
| Intel Jasper Lake HD Audio                                                                        | 86        | 2.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 64        | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 64        | 2.04%   |
| Intel 200 Series PCH HD Audio                                                                     | 60        | 1.91%   |
| Intel Broadwell-U Audio Controller                                                                | 59        | 1.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 58        | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 58        | 1.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 55        | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 53        | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 49        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 48        | 1.53%   |
| Intel 8 Series HD Audio Controller                                                                | 48        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 48        | 1.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.24%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 36        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 34        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 33        | 1.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 32        | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 25        | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 24        | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 0.7%    |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 20        | 0.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 19        | 0.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 19        | 0.61%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 19        | 0.61%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 18        | 0.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 18        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 592       | 18.61%  |
| SK hynix                                | 506       | 15.91%  |
| Micron Technology                       | 337       | 10.59%  |
| Crucial                                 | 336       | 10.56%  |
| Kingston                                | 270       | 8.49%   |
| Unknown                                 | 258       | 8.11%   |
| G.Skill                                 | 147       | 4.62%   |
| Corsair                                 | 121       | 3.8%    |
| Unknown                                 | 87        | 2.73%   |
| Team                                    | 59        | 1.85%   |
| Unknown (ABCD)                          | 43        | 1.35%   |
| Transcend                               | 42        | 1.32%   |
| Ramaxel Technology                      | 37        | 1.16%   |
| A-DATA Technology                       | 37        | 1.16%   |
| Nanya Technology                        | 35        | 1.1%    |
| Patriot                                 | 31        | 0.97%   |
| PNY                                     | 25        | 0.79%   |
| Elpida                                  | 22        | 0.69%   |
| Kimtigo                                 | 20        | 0.63%   |
| TIMETEC                                 | 15        | 0.47%   |
| Toshiba                                 | 12        | 0.38%   |
| Silicon Power                           | 12        | 0.38%   |
| Avant                                   | 12        | 0.38%   |
| Super Talent                            | 11        | 0.35%   |
| Innodisk                                | 7         | 0.22%   |
| Silicon Power Computer & Communications | 6         | 0.19%   |
| Sesame                                  | 6         | 0.19%   |
| SK_Hynix                                | 5         | 0.16%   |
| HPE                                     | 4         | 0.13%   |
| GeIL                                    | 4         | 0.13%   |
| Wodposit                                | 3         | 0.09%   |
| tigo                                    | 3         | 0.09%   |
| Ramsta                                  | 3         | 0.09%   |
| Patriot Memory (PDP Systems)            | 3         | 0.09%   |
| Neo Forza                               | 3         | 0.09%   |
| Mushkin                                 | 3         | 0.09%   |
| Hewlett-Packard                         | 3         | 0.09%   |
| Goldkey                                 | 3         | 0.09%   |
| Apacer                                  | 3         | 0.09%   |
| Vasekey                                 | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 87        | 2.56%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 39        | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 24        | 0.71%   |
| Unknown RAM Module 8GB 1600MT/s                              | 20        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 20        | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 18        | 0.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 18        | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 16        | 0.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 16        | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 16        | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s          | 16        | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 16        | 0.47%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 16        | 0.47%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 15        | 0.44%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 14        | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 14        | 0.41%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s         | 14        | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 13        | 0.38%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 12        | 0.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 12        | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 12        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 12        | 0.35%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s        | 12        | 0.35%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s        | 12        | 0.35%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s        | 12        | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 11        | 0.32%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 11        | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 10        | 0.29%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s       | 10        | 0.29%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 10        | 0.29%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 10        | 0.29%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s        | 9         | 0.26%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 9         | 0.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 9         | 0.26%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s          | 9         | 0.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 9         | 0.26%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s               | 9         | 0.26%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s         | 9         | 0.26%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 9         | 0.26%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 8         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1303      | 46.97%  |
| DDR4         | 1151      | 41.49%  |
| DDR2         | 101       | 3.64%   |
| LPDDR4       | 68        | 2.45%   |
| Unknown      | 60        | 2.16%   |
| DDR5         | 29        | 1.05%   |
| SDRAM        | 23        | 0.83%   |
| LPDDR3       | 15        | 0.54%   |
| DDR          | 14        | 0.5%    |
| LPDDR5       | 5         | 0.18%   |
| DRAM         | 3         | 0.11%   |
| SRAM         | 1         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1524      | 55.1%   |
| SODIMM       | 1132      | 40.93%  |
| Row Of Chips | 43        | 1.55%   |
| Unknown      | 41        | 1.48%   |
| Chip         | 12        | 0.43%   |
| FB-DIMM      | 9         | 0.33%   |
| RIMM         | 5         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1198      | 40.05%  |
| 4096   | 880       | 29.42%  |
| 16384  | 435       | 14.54%  |
| 2048   | 287       | 9.6%    |
| 32768  | 120       | 4.01%   |
| 1024   | 60        | 2.01%   |
| 512    | 7         | 0.23%   |
| 65536  | 2         | 0.07%   |
| 131072 | 1         | 0.03%   |
| 256    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 897       | 30.15%  |
| 2400    | 369       | 12.4%   |
| 1333    | 356       | 11.97%  |
| 2667    | 289       | 9.71%   |
| 3200    | 271       | 9.11%   |
| 2133    | 241       | 8.1%    |
| 800     | 68        | 2.29%   |
| 667     | 62        | 2.08%   |
| 2666    | 61        | 2.05%   |
| 1867    | 44        | 1.48%   |
| 1334    | 44        | 1.48%   |
| 1066    | 38        | 1.28%   |
| 1067    | 36        | 1.21%   |
| Unknown | 30        | 1.01%   |
| 3600    | 28        | 0.94%   |
| 3000    | 27        | 0.91%   |
| 4800    | 25        | 0.84%   |
| 2933    | 16        | 0.54%   |
| 1866    | 12        | 0.4%    |
| 533     | 11        | 0.37%   |
| 4267    | 10        | 0.34%   |
| 400     | 5         | 0.17%   |
| 6400    | 4         | 0.13%   |
| 5600    | 4         | 0.13%   |
| 975     | 4         | 0.13%   |
| 4266    | 3         | 0.1%    |
| 1400    | 3         | 0.1%    |
| 1200    | 3         | 0.1%    |
| 4000    | 2         | 0.07%   |
| 4133    | 1         | 0.03%   |
| 3733    | 1         | 0.03%   |
| 3534    | 1         | 0.03%   |
| 3333    | 1         | 0.03%   |
| 2866    | 1         | 0.03%   |
| 2048    | 1         | 0.03%   |
| 1639    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 1033    | 1         | 0.03%   |
| 266     | 1         | 0.03%   |
| 200     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 28.57%  |
| Brother Industries    | 2         | 28.57%  |
| Prolific Technology   | 1         | 14.29%  |
| Lexmark International | 1         | 14.29%  |
| Apple                 | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                            | 1         | 12.5%   |
| Lexmark International Lexmark MS710 Print                                | 1         | 12.5%   |
| HP PNP Fax Null                                                          | 1         | 12.5%   |
| HP LaserJet 1012                                                         | 1         | 12.5%   |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 12.5%   |
| Brother MFC-L2685DW                                                      | 1         | 12.5%   |
| Brother MFC-J485DW                                                       | 1         | 12.5%   |
| Apple Gamesir-G3s 2.10                                                   | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 50%     |
| HP ScanJet 5300c/5370c                                                              | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 101       | 25.51%  |
| Bison Electronics                      | 43        | 10.86%  |
| Realtek Semiconductor                  | 33        | 8.33%   |
| Microdia                               | 31        | 7.83%   |
| Sunplus Innovation Technology          | 28        | 7.07%   |
| IMC Networks                           | 28        | 7.07%   |
| Logitech                               | 26        | 6.57%   |
| Apple                                  | 15        | 3.79%   |
| Quanta                                 | 12        | 3.03%   |
| Suyin                                  | 10        | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 2.53%   |
| Lite-On Technology                     | 9         | 2.27%   |
| Luxvisions Innotech Limited            | 8         | 2.02%   |
| Syntek                                 | 6         | 1.52%   |
| Lenovo                                 | 6         | 1.52%   |
| Primax Electronics                     | 3         | 0.76%   |
| Importek                               | 3         | 0.76%   |
| Alcor Micro                            | 3         | 0.76%   |
| WCM_USB                                | 2         | 0.51%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.51%   |
| Ricoh                                  | 2         | 0.51%   |
| OmniVision Technologies                | 2         | 0.51%   |
| Intel                                  | 2         | 0.51%   |
| Generalplus Technology                 | 2         | 0.51%   |
| Z-Star Microelectronics                | 1         | 0.25%   |
| Xiongmai                               | 1         | 0.25%   |
| Supreme Electronics                    | 1         | 0.25%   |
| Silicon Motion                         | 1         | 0.25%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.25%   |
| Goodong Industry                       | 1         | 0.25%   |
| Arkmicro Technologies                  | 1         | 0.25%   |
| ARC International                      | 1         | 0.25%   |
| ALi                                    | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 31        | 7.73%   |
| Bison Integrated Camera                             | 23        | 5.74%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 2.99%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 11        | 2.74%   |
| Realtek Integrated_Webcam_HD                        | 10        | 2.49%   |
| IMC Networks Integrated Camera                      | 10        | 2.49%   |
| Apple FaceTime HD Camera                            | 10        | 2.49%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 2.24%   |
| Realtek USB 2.0 PC Camera                           | 8         | 2%      |
| Microdia Integrated Webcam                          | 8         | 2%      |
| Logitech HD Pro Webcam C920                         | 7         | 1.75%   |
| Chicony Integrated Camera [ThinkPad]                | 7         | 1.75%   |
| Logitech Webcam C270                                | 6         | 1.5%    |
| Lite-On Integrated Camera                           | 6         | 1.5%    |
| Microdia Integrated_Webcam_HD                       | 5         | 1.25%   |
| Bison ThinkPad Integrated Camera                    | 5         | 1.25%   |
| Suyin Integrated_Webcam_HD                          | 4         | 1%      |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 1%      |
| Microdia Webcam Vitade AF                           | 4         | 1%      |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 1%      |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 1%      |
| Logitech BRIO Ultra HD Webcam                       | 4         | 1%      |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 1%      |
| IMC Networks Realtek PC Camera                      | 4         | 1%      |
| Chicony Integrated IR Camera                        | 4         | 1%      |
| Chicony HP TrueVision HD Camera                     | 4         | 1%      |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 1%      |
| Syntek EasyCamera                                   | 3         | 0.75%   |
| Sunplus HD WebCam                                   | 3         | 0.75%   |
| Realtek Laptop Camera                               | 3         | 0.75%   |
| Realtek Integrated Webcam HD                        | 3         | 0.75%   |
| Quanta HP Webcam                                    | 3         | 0.75%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.75%   |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.75%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.75%   |
| IMC Networks EasyCamera                             | 3         | 0.75%   |
| Chicony thinkpad t430s camera                       | 3         | 0.75%   |
| Chicony HD WebCam                                   | 3         | 0.75%   |
| Chicony Chicony USB2.0 Camera                       | 3         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 32        | 32.65%  |
| Synaptics                  | 19        | 19.39%  |
| Upek                       | 14        | 14.29%  |
| STMicroelectronics         | 12        | 12.24%  |
| Shenzhen Goodix Technology | 7         | 7.14%   |
| AuthenTec                  | 7         | 7.14%   |
| Elan Microelectronics      | 2         | 2.04%   |
| Broadcom                   | 2         | 2.04%   |
| Samsung Electronics        | 1         | 1.02%   |
| LighTuning Technology      | 1         | 1.02%   |
| FocalTech Systems          | 1         | 1.02%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 16        | 16.33%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 14        | 14.29%  |
| STMicroelectronics Fingerprint Reader                                        | 12        | 12.24%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 8         | 8.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 8         | 8.16%   |
| Shenzhen Goodix Fingerprint Reader                                           | 6         | 6.12%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 3.06%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 3.06%   |
| AuthenTec AES2810                                                            | 3         | 3.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 2.04%   |
| Elan Fingerprint Sensor                                                      | 2         | 2.04%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.04%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.04%   |
| AuthenTec AES1660                                                            | 2         | 2.04%   |
| Validity Sensors VFS491                                                      | 1         | 1.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.02%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.02%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.02%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 1.02%   |
| Synaptics WBDI                                                               | 1         | 1.02%   |
| Synaptics UWP WBDI                                                           | 1         | 1.02%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.02%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 1.02%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 1.02%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 1.02%   |

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
| 1     | 1214      | 40%     |
| 0     | 919       | 30.28%  |
| 2     | 596       | 19.64%  |
| 3     | 223       | 7.35%   |
| 4     | 63        | 2.08%   |
| 5     | 13        | 0.43%   |
| 6     | 5         | 0.16%   |
| 7     | 2         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1778      | 62.23%  |
| Bluetooth                | 300       | 10.5%   |
| Net/wireless             | 267       | 9.35%   |
| Card reader              | 135       | 4.73%   |
| Firewire controller      | 100       | 3.5%    |
| Fingerprint reader       | 83        | 2.91%   |
| Net/ethernet             | 51        | 1.79%   |
| Sound                    | 50        | 1.75%   |
| Network                  | 39        | 1.37%   |
| Graphics card            | 22        | 0.77%   |
| Storage                  | 11        | 0.39%   |
| Modem                    | 7         | 0.25%   |
| Storage/raid             | 6         | 0.21%   |
| Storage/ata              | 3         | 0.11%   |
| Dvb card                 | 3         | 0.11%   |
| Storage/ide              | 2         | 0.07%   |

