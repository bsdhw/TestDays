BSD in China - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in China.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/China/Desktop/README.md) and [notebooks](/Location/China/Notebook/README.md).

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

Total: 288

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | Vostro 5470                 | Notebook    | [56472e8f51](https://bsd-hardware.info/?probe=56472e8f51) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [ba78787dff](https://bsd-hardware.info/?probe=ba78787dff) | Dec 29, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [06457349dc](https://bsd-hardware.info/?probe=06457349dc) | Dec 22, 2023 |
| Google        | Kohaku                      | Notebook    | [0b945d8f38](https://bsd-hardware.info/?probe=0b945d8f38) | Dec 15, 2023 |
| Intel         | SKYBAY                      | Desktop     | [6ad2ae72f1](https://bsd-hardware.info/?probe=6ad2ae72f1) | Dec 13, 2023 |
| MECHREVO      | F7BSC V1.0                  | Mini pc     | [d1104aa676](https://bsd-hardware.info/?probe=d1104aa676) | Dec 05, 2023 |
| Intel         | H81U                        | Notebook    | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [4017ce5221](https://bsd-hardware.info/?probe=4017ce5221) | Nov 29, 2023 |
| Supermicro    | X9SCL-II/X9SCM-II           | Desktop     | [34833316ac](https://bsd-hardware.info/?probe=34833316ac) | Nov 27, 2023 |
| Google        | Kohaku                      | Notebook    | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | Notebook    | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| Silicom       | 80300-0214-G16 R310         | Desktop     | [34382c8f4b](https://bsd-hardware.info/?probe=34382c8f4b) | Nov 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [456d5ad8bf](https://bsd-hardware.info/?probe=456d5ad8bf) | Nov 05, 2023 |
| YanRay Tec... | B1904                       | Desktop     | [7d194ae12b](https://bsd-hardware.info/?probe=7d194ae12b) | Oct 28, 2023 |
| MECHREVO      | Unknown                     | Desktop     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8f62c35aa0](https://bsd-hardware.info/?probe=8f62c35aa0) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | Desktop     | [da1e562510](https://bsd-hardware.info/?probe=da1e562510) | Oct 10, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | Desktop     | [d7cf15da0c](https://bsd-hardware.info/?probe=d7cf15da0c) | Oct 09, 2023 |
| Timi          | A34R                        | Notebook    | [3cd3f35eaa](https://bsd-hardware.info/?probe=3cd3f35eaa) | Oct 07, 2023 |
| Timi          | A34R                        | Notebook    | [03f00603f7](https://bsd-hardware.info/?probe=03f00603f7) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [c54bad3277](https://bsd-hardware.info/?probe=c54bad3277) | Oct 04, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN         | Mini pc     | [a7b161ff5e](https://bsd-hardware.info/?probe=a7b161ff5e) | Oct 01, 2023 |
| Biostar       | A55MLC2                     | Desktop     | [fac0f247d0](https://bsd-hardware.info/?probe=fac0f247d0) | Sep 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [93c70115bd](https://bsd-hardware.info/?probe=93c70115bd) | Aug 19, 2023 |
| Intel         | SKYBAY                      | Desktop     | [53fb653186](https://bsd-hardware.info/?probe=53fb653186) | Aug 18, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2f6574d368](https://bsd-hardware.info/?probe=2f6574d368) | Aug 08, 2023 |
| HP            | 82C0                        | Mini pc     | [6ad9c871cb](https://bsd-hardware.info/?probe=6ad9c871cb) | Aug 07, 2023 |
| HP            | 82C0                        | Mini pc     | [124e7b14df](https://bsd-hardware.info/?probe=124e7b14df) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [75e009424e](https://bsd-hardware.info/?probe=75e009424e) | Aug 07, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5db7e9b7a1](https://bsd-hardware.info/?probe=5db7e9b7a1) | Aug 05, 2023 |
| Intel         | SKYBAY                      | Desktop     | [fde75b4094](https://bsd-hardware.info/?probe=fde75b4094) | Aug 04, 2023 |
| HP            | 82C0                        | Mini pc     | [be2c1dd2f5](https://bsd-hardware.info/?probe=be2c1dd2f5) | Aug 03, 2023 |
| HP            | 82C0                        | Mini pc     | [6fa14d3439](https://bsd-hardware.info/?probe=6fa14d3439) | Aug 03, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | Notebook    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| AZW           | EQ                          | Desktop     | [a581a63aae](https://bsd-hardware.info/?probe=a581a63aae) | Jul 29, 2023 |
| AZW           | EQ                          | Desktop     | [1feeda5ce9](https://bsd-hardware.info/?probe=1feeda5ce9) | Jul 29, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [ce1aade2c0](https://bsd-hardware.info/?probe=ce1aade2c0) | Jul 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [3ca61a6a18](https://bsd-hardware.info/?probe=3ca61a6a18) | Jul 24, 2023 |
| AZW           | EQ                          | Desktop     | [7d2884120c](https://bsd-hardware.info/?probe=7d2884120c) | Jul 23, 2023 |
| NEC Comput... | IS8XM                       | Desktop     | [9f50189f65](https://bsd-hardware.info/?probe=9f50189f65) | Jul 22, 2023 |
| OEM           | ITX-SC3 V1.1                | Desktop     | [a58b6ba2d4](https://bsd-hardware.info/?probe=a58b6ba2d4) | Jul 18, 2023 |
| OEM           | ITX-SC3 V1.1                | Desktop     | [7c550acc8c](https://bsd-hardware.info/?probe=7c550acc8c) | Jul 18, 2023 |
| Dell          | 01F7TF A03                  | Server      | [6d9d222d88](https://bsd-hardware.info/?probe=6d9d222d88) | Jul 18, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [f734b93999](https://bsd-hardware.info/?probe=f734b93999) | Jul 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [ff4dbbacdf](https://bsd-hardware.info/?probe=ff4dbbacdf) | Jul 15, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | Notebook    | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c5d9c5da3](https://bsd-hardware.info/?probe=4c5d9c5da3) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4841a6b1d2](https://bsd-hardware.info/?probe=4841a6b1d2) | Jun 14, 2023 |
| WlanCN        | 6000 Series                 | Desktop     | [d2e71531b6](https://bsd-hardware.info/?probe=d2e71531b6) | Jun 05, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [dc65d735c8](https://bsd-hardware.info/?probe=dc65d735c8) | Jun 04, 2023 |
| Panasonic     | CF-NX1GDHYS                 | Notebook    | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| NORCO         | HB133                       | Desktop     | [1d59c53b9b](https://bsd-hardware.info/?probe=1d59c53b9b) | May 25, 2023 |
| DS            | FJ04D JHS60K                | Desktop     | [7561a5e28b](https://bsd-hardware.info/?probe=7561a5e28b) | May 11, 2023 |
| Colorful T... | C.J1900A-BTC PLUS V20       | Desktop     | [07add98717](https://bsd-hardware.info/?probe=07add98717) | May 03, 2023 |
| Colorful T... | C.J1900A-BTC PLUS V20       | Desktop     | [b718c75566](https://bsd-hardware.info/?probe=b718c75566) | May 01, 2023 |
| HP            | Unknown                     | Notebook    | [e2aa3620b4](https://bsd-hardware.info/?probe=e2aa3620b4) | Apr 23, 2023 |
| Dell          | 0569RT A04                  | Server      | [cff2ebd06b](https://bsd-hardware.info/?probe=cff2ebd06b) | Apr 23, 2023 |
| Dell          | 0VTC0D A02                  | Desktop     | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [941c021569](https://bsd-hardware.info/?probe=941c021569) | Apr 18, 2023 |
| Lenovo        | YangTianM6880N              | Desktop     | [a567c3062c](https://bsd-hardware.info/?probe=a567c3062c) | Apr 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4ae38adc2a](https://bsd-hardware.info/?probe=4ae38adc2a) | Apr 13, 2023 |
| YENTEK        | ITX-B75R1                   | Desktop     | [7443f81ab1](https://bsd-hardware.info/?probe=7443f81ab1) | Apr 10, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| YENTEK        | ITX-B75R1                   | Desktop     | [3cab1716e0](https://bsd-hardware.info/?probe=3cab1716e0) | Apr 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [0976c12353](https://bsd-hardware.info/?probe=0976c12353) | Apr 03, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [6e8443e9f4](https://bsd-hardware.info/?probe=6e8443e9f4) | Apr 01, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Google        | Kohaku                      | Notebook    | [88491d298e](https://bsd-hardware.info/?probe=88491d298e) | Mar 12, 2023 |
| Dell          | 0KYJ8C A02                  | Desktop     | [ea8759f206](https://bsd-hardware.info/?probe=ea8759f206) | Mar 09, 2023 |
| Lenovo        | ThinkPad X230 2324A14       | Notebook    | [124b3bdb95](https://bsd-hardware.info/?probe=124b3bdb95) | Mar 08, 2023 |
| Acer          | TravelMate TX50-G2          | Notebook    | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [815cd70e71](https://bsd-hardware.info/?probe=815cd70e71) | Feb 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [866ff788f9](https://bsd-hardware.info/?probe=866ff788f9) | Feb 23, 2023 |
| Lenovo        | SHARKBAY SDK0A46860 WIN     | Desktop     | [4cd5bcdfed](https://bsd-hardware.info/?probe=4cd5bcdfed) | Feb 18, 2023 |
| Dell          | 0KYJ8C A02                  | Desktop     | [854d373499](https://bsd-hardware.info/?probe=854d373499) | Feb 16, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c176577762](https://bsd-hardware.info/?probe=c176577762) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [b5e972d19a](https://bsd-hardware.info/?probe=b5e972d19a) | Jan 24, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e4c2272546](https://bsd-hardware.info/?probe=e4c2272546) | Jan 15, 2023 |
| Dell          | 0KYJ8C A02                  | Desktop     | [490f20c93d](https://bsd-hardware.info/?probe=490f20c93d) | Dec 21, 2022 |
| Dell          | 0VD50G A01                  | Server      | [07852bf200](https://bsd-hardware.info/?probe=07852bf200) | Dec 19, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [108c9de5cc](https://bsd-hardware.info/?probe=108c9de5cc) | Dec 18, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [c0c4fa9349](https://bsd-hardware.info/?probe=c0c4fa9349) | Dec 02, 2022 |
| HASEE Comp... | N95XKP6                     | Notebook    | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| ASUSTek       | PRIME H310T2 R2.0           | All in one  | [d1cc7c07e0](https://bsd-hardware.info/?probe=d1cc7c07e0) | Dec 02, 2022 |
| Acidanther... | MacBookPro15,1              | Notebook    | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| TOPFEEL       | H110D4-P1                   | Desktop     | [90b1dfc430](https://bsd-hardware.info/?probe=90b1dfc430) | Nov 19, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7282ce8fe2](https://bsd-hardware.info/?probe=7282ce8fe2) | Nov 19, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [7691355396](https://bsd-hardware.info/?probe=7691355396) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| ONDA          | N78G5D3 Ver:5.00            | Desktop     | [009bc44d12](https://bsd-hardware.info/?probe=009bc44d12) | Nov 07, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [2e9c3b7368](https://bsd-hardware.info/?probe=2e9c3b7368) | Nov 04, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [17f444775b](https://bsd-hardware.info/?probe=17f444775b) | Oct 28, 2022 |
| Centerm       | GA690-2 2                   | Desktop     | [9d6c3d67cd](https://bsd-hardware.info/?probe=9d6c3d67cd) | Oct 28, 2022 |
| Google        | Edgar                       | Notebook    | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| Lenovo        | XiaoXinPro-13API 2019 81... | Notebook    | [dfa08657fd](https://bsd-hardware.info/?probe=dfa08657fd) | Oct 16, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [59c41dcd31](https://bsd-hardware.info/?probe=59c41dcd31) | Oct 11, 2022 |
| AMD           | Inagua CRB                  | Desktop     | [ff4eccae8a](https://bsd-hardware.info/?probe=ff4eccae8a) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [a5cbd6786d](https://bsd-hardware.info/?probe=a5cbd6786d) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [f31f4c00cd](https://bsd-hardware.info/?probe=f31f4c00cd) | Oct 08, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [130a05a115](https://bsd-hardware.info/?probe=130a05a115) | Oct 07, 2022 |
| Dell          | 0MFXTY A02                  | Server      | [6484798368](https://bsd-hardware.info/?probe=6484798368) | Sep 29, 2022 |
| Dell          | 0MFXTY A02                  | Server      | [901ca48f69](https://bsd-hardware.info/?probe=901ca48f69) | Sep 28, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [12493c3802](https://bsd-hardware.info/?probe=12493c3802) | Sep 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [199ad16750](https://bsd-hardware.info/?probe=199ad16750) | Sep 21, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [431ad10ab2](https://bsd-hardware.info/?probe=431ad10ab2) | Sep 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [8de53ac515](https://bsd-hardware.info/?probe=8de53ac515) | Sep 17, 2022 |
| Dell          | 0KYJ8C A02                  | Desktop     | [7e8d44c688](https://bsd-hardware.info/?probe=7e8d44c688) | Sep 10, 2022 |
| Dell          | Latitude 5310               | Notebook    | [6edf4d34fe](https://bsd-hardware.info/?probe=6edf4d34fe) | Sep 07, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [df57940ad5](https://bsd-hardware.info/?probe=df57940ad5) | Sep 03, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [9941ee7afb](https://bsd-hardware.info/?probe=9941ee7afb) | Sep 03, 2022 |
| Lenovo        | YangTianM6880N              | Desktop     | [f675498946](https://bsd-hardware.info/?probe=f675498946) | Sep 02, 2022 |
| Unknown       | DTB1168                     | Desktop     | [e924ba2a44](https://bsd-hardware.info/?probe=e924ba2a44) | Sep 01, 2022 |
| WlanCN        | 6000 Series                 | Desktop     | [7fda15ca84](https://bsd-hardware.info/?probe=7fda15ca84) | Aug 25, 2022 |
| Acer          | Aspire 4552G                | Notebook    | [a8f8e41c91](https://bsd-hardware.info/?probe=a8f8e41c91) | Aug 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [3efcb47333](https://bsd-hardware.info/?probe=3efcb47333) | Jul 31, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | Desktop     | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [b2aa5f61e2](https://bsd-hardware.info/?probe=b2aa5f61e2) | Jul 11, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Lenovo        | 300e 81FY                   | Convertible | [eb136e5d7e](https://bsd-hardware.info/?probe=eb136e5d7e) | Jun 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [0f45bdf1ec](https://bsd-hardware.info/?probe=0f45bdf1ec) | Jun 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [ccc77e76e0](https://bsd-hardware.info/?probe=ccc77e76e0) | Jun 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [57a6f58607](https://bsd-hardware.info/?probe=57a6f58607) | Jun 09, 2022 |
| ASUSTek       | X441UV                      | Notebook    | [c8906b438b](https://bsd-hardware.info/?probe=c8906b438b) | Jun 03, 2022 |
| Unknown       | Unknown                     | All in one  | [732a9df612](https://bsd-hardware.info/?probe=732a9df612) | May 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3ff577e111](https://bsd-hardware.info/?probe=3ff577e111) | May 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [9e2f16664a](https://bsd-hardware.info/?probe=9e2f16664a) | May 26, 2022 |
| Dell          | Latitude 5520               | Notebook    | [cbc2c03fa1](https://bsd-hardware.info/?probe=cbc2c03fa1) | May 20, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [214f7d6461](https://bsd-hardware.info/?probe=214f7d6461) | May 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [d9c28e14df](https://bsd-hardware.info/?probe=d9c28e14df) | May 13, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [b54df77b59](https://bsd-hardware.info/?probe=b54df77b59) | May 07, 2022 |
| Lenovo        | B470 HuronRiver Platform    | Notebook    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| OEM           | B85 JHS359                  | Desktop     | [c5d29cc6b3](https://bsd-hardware.info/?probe=c5d29cc6b3) | May 03, 2022 |
| Dell          | Latitude 5290               | Notebook    | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | Notebook    | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [d259128717](https://bsd-hardware.info/?probe=d259128717) | Apr 16, 2022 |
| Panasonic     | CF-B11JWCYS                 | Notebook    | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [9642cf3129](https://bsd-hardware.info/?probe=9642cf3129) | Mar 30, 2022 |
| ASRock        | Q1900M                      | Desktop     | [e2473b7f22](https://bsd-hardware.info/?probe=e2473b7f22) | Mar 29, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [97f4960723](https://bsd-hardware.info/?probe=97f4960723) | Mar 28, 2022 |
| Unknown       | J3160-4L                    | Desktop     | [e2717ea0eb](https://bsd-hardware.info/?probe=e2717ea0eb) | Mar 24, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [859a429ad0](https://bsd-hardware.info/?probe=859a429ad0) | Mar 24, 2022 |
| HASEE Comp... | CW35S                       | Notebook    | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d08da1541a](https://bsd-hardware.info/?probe=d08da1541a) | Mar 14, 2022 |
| Lenovo        | IdeaCentre B545 10100       | Desktop     | [2f13d4a946](https://bsd-hardware.info/?probe=2f13d4a946) | Mar 12, 2022 |
| ASUSTek       | TUF GAMING X570-PRO         | Desktop     | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [ce3fedcbaf](https://bsd-hardware.info/?probe=ce3fedcbaf) | Mar 07, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b54ace2a34](https://bsd-hardware.info/?probe=b54ace2a34) | Mar 03, 2022 |
| WOOKING       | X5                          | Notebook    | [1099e6c574](https://bsd-hardware.info/?probe=1099e6c574) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [e4f43cfcad](https://bsd-hardware.info/?probe=e4f43cfcad) | Feb 10, 2022 |
| Intel         | X58                         | Desktop     | [f7075908f6](https://bsd-hardware.info/?probe=f7075908f6) | Feb 09, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [8eda642f6a](https://bsd-hardware.info/?probe=8eda642f6a) | Jan 04, 2022 |
| Dell          | 0H9KW5 A00                  | Desktop     | [e962ca25b3](https://bsd-hardware.info/?probe=e962ca25b3) | Dec 28, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [7a8a66430a](https://bsd-hardware.info/?probe=7a8a66430a) | Dec 13, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [0215354bfc](https://bsd-hardware.info/?probe=0215354bfc) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | Notebook    | [f3c014b120](https://bsd-hardware.info/?probe=f3c014b120) | Dec 12, 2021 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [990e05c219](https://bsd-hardware.info/?probe=990e05c219) | Dec 11, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [e115f87ef7](https://bsd-hardware.info/?probe=e115f87ef7) | Nov 30, 2021 |
| Sony          | SVP13225SCBI                | Notebook    | [03ef84679c](https://bsd-hardware.info/?probe=03ef84679c) | Nov 27, 2021 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [f9af97f07a](https://bsd-hardware.info/?probe=f9af97f07a) | Nov 24, 2021 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [fdeae82fab](https://bsd-hardware.info/?probe=fdeae82fab) | Nov 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [08f546f789](https://bsd-hardware.info/?probe=08f546f789) | Nov 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [d958c5d8f1](https://bsd-hardware.info/?probe=d958c5d8f1) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ddfd14ef31](https://bsd-hardware.info/?probe=ddfd14ef31) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ad4f0d967d](https://bsd-hardware.info/?probe=ad4f0d967d) | Nov 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [d3e799d3a6](https://bsd-hardware.info/?probe=d3e799d3a6) | Nov 13, 2021 |
| Unknown       | YL-SKUL6-7 Series           | Desktop     | [8c72c2f429](https://bsd-hardware.info/?probe=8c72c2f429) | Nov 12, 2021 |
| GuoGuang      | IC2M1028V-6                 | Desktop     | [1aa8bbd5b2](https://bsd-hardware.info/?probe=1aa8bbd5b2) | Nov 07, 2021 |
| Toshiba       | Satellite Pro L510          | Notebook    | [52ce915b05](https://bsd-hardware.info/?probe=52ce915b05) | Nov 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e54d79065e](https://bsd-hardware.info/?probe=e54d79065e) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a71d3392eb](https://bsd-hardware.info/?probe=a71d3392eb) | Nov 02, 2021 |
| Lenovo        | 3136 SDK0J40697 WIN         | Mini pc     | [bfc921bfbb](https://bsd-hardware.info/?probe=bfc921bfbb) | Oct 29, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | Desktop     | [9b545faf66](https://bsd-hardware.info/?probe=9b545faf66) | Oct 28, 2021 |
| Dell          | 04JN2K A09                  | Server      | [89d5f99632](https://bsd-hardware.info/?probe=89d5f99632) | Oct 27, 2021 |
| Lenovo        | SHARKBAY SDK0A46860 PRO     | Desktop     | [f269216a0d](https://bsd-hardware.info/?probe=f269216a0d) | Oct 27, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8ad7b068f4](https://bsd-hardware.info/?probe=8ad7b068f4) | Oct 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c520513abd](https://bsd-hardware.info/?probe=c520513abd) | Oct 26, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony          | SVS1511AJB                  | Notebook    | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [f9c5120643](https://bsd-hardware.info/?probe=f9c5120643) | Oct 22, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Dell          | 0DR845                      | Desktop     | [d8324d1639](https://bsd-hardware.info/?probe=d8324d1639) | Oct 21, 2021 |
| HP            | 3398                        | Desktop     | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| Supermicro    | X10SRA                      | Server      | [e1eba3b8f0](https://bsd-hardware.info/?probe=e1eba3b8f0) | Oct 09, 2021 |
| ASUSTek       | F83VD                       | Notebook    | [5f2df13f5b](https://bsd-hardware.info/?probe=5f2df13f5b) | Oct 06, 2021 |
| Supermicro    | X10SL7-F                    | Server      | [d26ebdbb9f](https://bsd-hardware.info/?probe=d26ebdbb9f) | Oct 04, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [84f06376e2](https://bsd-hardware.info/?probe=84f06376e2) | Oct 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2d13da6566](https://bsd-hardware.info/?probe=2d13da6566) | Sep 23, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4f5dd7630a](https://bsd-hardware.info/?probe=4f5dd7630a) | Sep 23, 2021 |
| NEC Comput... | SHARKBAY                    | Desktop     | [24229ed11f](https://bsd-hardware.info/?probe=24229ed11f) | Sep 22, 2021 |
| CNCTION-IA... | Unknown                     | Desktop     | [aad95eb2bf](https://bsd-hardware.info/?probe=aad95eb2bf) | Sep 21, 2021 |
| YANYU         | ITX-N29 VER:1.5 baytrail    | Desktop     | [c851a73aa5](https://bsd-hardware.info/?probe=c851a73aa5) | Sep 20, 2021 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [bd5b726e52](https://bsd-hardware.info/?probe=bd5b726e52) | Sep 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [0da457285c](https://bsd-hardware.info/?probe=0da457285c) | Aug 23, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [3063e4b82f](https://bsd-hardware.info/?probe=3063e4b82f) | Aug 21, 2021 |
| Lenovo        | ZhaoYang K4e-IML 81VQ       | Notebook    | [cd3ac84240](https://bsd-hardware.info/?probe=cd3ac84240) | Aug 21, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [cce0d947f1](https://bsd-hardware.info/?probe=cce0d947f1) | Aug 20, 2021 |
| PAIQ          | EC3-BT19D4L A1              | Desktop     | [1a438c7632](https://bsd-hardware.info/?probe=1a438c7632) | Aug 19, 2021 |
| CNCTION-IA... | Unknown                     | Desktop     | [7763f089a3](https://bsd-hardware.info/?probe=7763f089a3) | Aug 17, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [f523f4f6c9](https://bsd-hardware.info/?probe=f523f4f6c9) | Aug 10, 2021 |
| NEC Comput... | PC-VK17HBBCD                | Notebook    | [1e23da04c0](https://bsd-hardware.info/?probe=1e23da04c0) | Aug 08, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [dc1e25a4e0](https://bsd-hardware.info/?probe=dc1e25a4e0) | Aug 07, 2021 |
| Lenovo        | ThinkPad X230 23062S2       | Notebook    | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [bf56b2a81a](https://bsd-hardware.info/?probe=bf56b2a81a) | Aug 05, 2021 |
| Lenovo        | NOK                         | Desktop     | [de711c244f](https://bsd-hardware.info/?probe=de711c244f) | Aug 05, 2021 |
| Supermicro    | X10SL7-F                    | Server      | [50e9da16d7](https://bsd-hardware.info/?probe=50e9da16d7) | Aug 04, 2021 |
| Lenovo        | NOK                         | Desktop     | [5bd27802f0](https://bsd-hardware.info/?probe=5bd27802f0) | Aug 04, 2021 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [73a22d60fc](https://bsd-hardware.info/?probe=73a22d60fc) | Jul 30, 2021 |
| GuoGuang      | IC2M1028V-6                 | Desktop     | [9bfe0dca00](https://bsd-hardware.info/?probe=9bfe0dca00) | Jul 21, 2021 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [b0da42c20d](https://bsd-hardware.info/?probe=b0da42c20d) | Jul 18, 2021 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [e71b6ac13d](https://bsd-hardware.info/?probe=e71b6ac13d) | Jul 10, 2021 |
| Gigabyte      | GA-6UPCP2/4/5               | Server      | [f1e7cb51d7](https://bsd-hardware.info/?probe=f1e7cb51d7) | Jul 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [58f03a472f](https://bsd-hardware.info/?probe=58f03a472f) | Jul 03, 2021 |
| Lenovo        | Rescuer-15ISK 80RQ          | Notebook    | [46d0d10dd8](https://bsd-hardware.info/?probe=46d0d10dd8) | Jul 03, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [b8712916f2](https://bsd-hardware.info/?probe=b8712916f2) | Jun 29, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [0b0951a048](https://bsd-hardware.info/?probe=0b0951a048) | Jun 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [8fe29978c3](https://bsd-hardware.info/?probe=8fe29978c3) | Jun 22, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | Notebook    | [2b05811c5f](https://bsd-hardware.info/?probe=2b05811c5f) | Jun 18, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [2268ef2689](https://bsd-hardware.info/?probe=2268ef2689) | Jun 18, 2021 |
| Lenovo        | ThinkPad T430 2349GCU       | Notebook    | [ca15c7d742](https://bsd-hardware.info/?probe=ca15c7d742) | Jun 13, 2021 |
| Protectli     | FW6                         | Desktop     | [7fe94af21a](https://bsd-hardware.info/?probe=7fe94af21a) | Jun 11, 2021 |
| CNCTION-IA... | Unknown                     | Desktop     | [ff1a657505](https://bsd-hardware.info/?probe=ff1a657505) | Jun 08, 2021 |
| Colorful Y... | C.J1900A-BTC PLUS YV20      | Desktop     | [c0b3c87810](https://bsd-hardware.info/?probe=c0b3c87810) | Jun 04, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [39b99e57af](https://bsd-hardware.info/?probe=39b99e57af) | Jun 01, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [63a3fc3982](https://bsd-hardware.info/?probe=63a3fc3982) | May 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [def6a6516d](https://bsd-hardware.info/?probe=def6a6516d) | Apr 30, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [acc8b02e3b](https://bsd-hardware.info/?probe=acc8b02e3b) | Apr 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4993ad0feb](https://bsd-hardware.info/?probe=4993ad0feb) | Apr 25, 2021 |
| Notebook      | W65KJ1_KK1                  | Notebook    | [d4d0b819bc](https://bsd-hardware.info/?probe=d4d0b819bc) | Apr 24, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [d902b4ebd8](https://bsd-hardware.info/?probe=d902b4ebd8) | Apr 24, 2021 |
| Dell          | Latitude E5570              | Notebook    | [da926f1065](https://bsd-hardware.info/?probe=da926f1065) | Apr 11, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [2338aa8fff](https://bsd-hardware.info/?probe=2338aa8fff) | Apr 03, 2021 |
| Colorful T... | C.Q1900M PRO V20            | Desktop     | [5283765cbe](https://bsd-hardware.info/?probe=5283765cbe) | Apr 03, 2021 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [3623b04225](https://bsd-hardware.info/?probe=3623b04225) | Mar 31, 2021 |
| HP            | ProLiant DL320e Gen8 v2     | Server      | [065e6c08fd](https://bsd-hardware.info/?probe=065e6c08fd) | Mar 28, 2021 |
| ASUSTek       | X540UP                      | Notebook    | [a9c4506364](https://bsd-hardware.info/?probe=a9c4506364) | Mar 28, 2021 |
| Dell          | 018D1Y A00                  | Desktop     | [13754ed4ee](https://bsd-hardware.info/?probe=13754ed4ee) | Mar 23, 2021 |
| Dell          | 0YXT71 A00                  | Desktop     | [cb3d9f12c6](https://bsd-hardware.info/?probe=cb3d9f12c6) | Mar 20, 2021 |
| Lenovo        | ThinkPad E460 20ETA00DCD    | Notebook    | [0a6985f078](https://bsd-hardware.info/?probe=0a6985f078) | Mar 13, 2021 |
| Dell          | 0W2PJY A01                  | Desktop     | [f162510a27](https://bsd-hardware.info/?probe=f162510a27) | Mar 12, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [d598cc6240](https://bsd-hardware.info/?probe=d598cc6240) | Mar 11, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [19923e24d6](https://bsd-hardware.info/?probe=19923e24d6) | Mar 10, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b03cb1f957](https://bsd-hardware.info/?probe=b03cb1f957) | Mar 05, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d129752b43](https://bsd-hardware.info/?probe=d129752b43) | Mar 04, 2021 |
| Dell          | Precision 3541              | Notebook    | [d07a4dc2c7](https://bsd-hardware.info/?probe=d07a4dc2c7) | Mar 04, 2021 |
| Dell          | 0W2PJY A01                  | Desktop     | [d8c2f0b19f](https://bsd-hardware.info/?probe=d8c2f0b19f) | Mar 04, 2021 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [9a23dee2ea](https://bsd-hardware.info/?probe=9a23dee2ea) | Mar 01, 2021 |
| Lenovo        | ThinkPad T470p 20J6A012C... | Notebook    | [cbaa19611e](https://bsd-hardware.info/?probe=cbaa19611e) | Feb 24, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [b8e35aacdb](https://bsd-hardware.info/?probe=b8e35aacdb) | Feb 22, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [aa98e655f3](https://bsd-hardware.info/?probe=aa98e655f3) | Feb 20, 2021 |
| Lenovo        | ThinkPad E420 1141A83       | Notebook    | [a48872901d](https://bsd-hardware.info/?probe=a48872901d) | Feb 20, 2021 |
| Gigabyte      | GA-870-UD3P                 | Desktop     | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 018D1Y A00                  | Desktop     | [a54f14d773](https://bsd-hardware.info/?probe=a54f14d773) | Feb 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [22af66ce96](https://bsd-hardware.info/?probe=22af66ce96) | Feb 18, 2021 |
| Google        | Guado                       | Desktop     | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [5068d55701](https://bsd-hardware.info/?probe=5068d55701) | Feb 16, 2021 |
| HP            | 8768 A                      | Desktop     | [f2be4b7b65](https://bsd-hardware.info/?probe=f2be4b7b65) | Feb 16, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [419b61f1d8](https://bsd-hardware.info/?probe=419b61f1d8) | Feb 15, 2021 |
| ASUSTek       | EX-B85M-V                   | Desktop     | [54c319f2c0](https://bsd-hardware.info/?probe=54c319f2c0) | Feb 15, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [62d7379d24](https://bsd-hardware.info/?probe=62d7379d24) | Feb 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [bc823e0dfc](https://bsd-hardware.info/?probe=bc823e0dfc) | Feb 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [5550236531](https://bsd-hardware.info/?probe=5550236531) | Feb 08, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [12e20c2cb0](https://bsd-hardware.info/?probe=12e20c2cb0) | Jan 23, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [dad5d994a0](https://bsd-hardware.info/?probe=dad5d994a0) | Jan 20, 2021 |
| Lenovo        | ThinkPad T580 20L9000ECD    | Notebook    | [771d8ead80](https://bsd-hardware.info/?probe=771d8ead80) | Nov 10, 2020 |
| Unknown       | Raspberry Pi                | Soc         | [cd269c4db1](https://bsd-hardware.info/?probe=cd269c4db1) | Nov 01, 2020 |
| ASRock        | A320M-ITX                   | Desktop     | [7fab9dd55a](https://bsd-hardware.info/?probe=7fab9dd55a) | Oct 31, 2020 |
| HP            | 213D A01                    | Desktop     | [b081e36525](https://bsd-hardware.info/?probe=b081e36525) | Oct 31, 2020 |
| Lenovo        | ThinkPad SL410 28747GC      | Notebook    | [3b62dd9788](https://bsd-hardware.info/?probe=3b62dd9788) | Jul 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [f9ed1dce06](https://bsd-hardware.info/?probe=f9ed1dce06) | Jul 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 20        | 8.55%   |
| helloSystem 0.8.0    | 10        | 4.27%   |
| helloSystem 0.5.0    | 9         | 3.85%   |
| FreeBSD 13.1         | 9         | 3.85%   |
| OPNsense 21.7.1      | 8         | 3.42%   |
| helloSystem 0.8.1    | 8         | 3.42%   |
| FreeBSD 13.2         | 8         | 3.42%   |
| OPNsense 23.1.11     | 6         | 2.56%   |
| OPNsense 21.1.7      | 6         | 2.56%   |
| OPNsense 21.7.3      | 5         | 2.14%   |
| helloSystem 0.6.0    | 5         | 2.14%   |
| helloSystem 0.4.0    | 5         | 2.14%   |
| FreeBSD 14.0-CURRENT | 5         | 2.14%   |
| FreeBSD 13.1-p2      | 5         | 2.14%   |
| FreeBSD 12.2         | 5         | 2.14%   |
| OPNsense 21.7.5      | 4         | 1.71%   |
| OPNsense 21.7.2      | 4         | 1.71%   |
| OPNsense 21.1        | 4         | 1.71%   |
| FreeBSD 14.0         | 4         | 1.71%   |
| OPNsense 23.1.5      | 3         | 1.28%   |
| OPNsense 23.1.1      | 3         | 1.28%   |
| OPNsense 22.7.5      | 3         | 1.28%   |
| OPNsense 21.1.6      | 3         | 1.28%   |
| OPNsense 21.1.3      | 3         | 1.28%   |
| OPNsense 21.1.1      | 3         | 1.28%   |
| GhostBSD 21.08.27    | 3         | 1.28%   |
| FreeBSD 13.0-p4      | 3         | 1.28%   |
| OPNsense 23.7.9      | 2         | 0.85%   |
| OPNsense 23.7.7      | 2         | 0.85%   |
| OPNsense 23.7.5      | 2         | 0.85%   |
| OPNsense 23.7.1      | 2         | 0.85%   |
| OPNsense 23.1.7      | 2         | 0.85%   |
| OPNsense 22.7.9      | 2         | 0.85%   |
| OPNsense 22.7.4      | 2         | 0.85%   |
| OPNsense 22.7.2      | 2         | 0.85%   |
| OPNsense 22.1.8      | 2         | 0.85%   |
| OPNsense 22.1.4      | 2         | 0.85%   |
| OPNsense 22.1.2      | 2         | 0.85%   |
| OPNsense 22.1.10     | 2         | 0.85%   |
| OPNsense 21.7.4      | 2         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 74        | 37.37%  |
| FreeBSD     | 58        | 29.29%  |
| helloSystem | 56        | 28.28%  |
| OpenBSD     | 3         | 1.52%   |
| NomadBSD    | 3         | 1.52%   |
| GhostBSD    | 3         | 1.52%   |
| NetBSD      | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 191       | 97.95%  |
| arm64   | 3         | 1.54%   |
| powerpc | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 89        | 44.06%  |
| helloDesktop | 57        | 28.22%  |
| XFCE         | 15        | 7.43%   |
| KDE5         | 14        | 6.93%   |
| TWM          | 6         | 2.97%   |
| i3           | 5         | 2.48%   |
| GNOME        | 5         | 2.48%   |
| MATE         | 4         | 1.98%   |
| Openbox      | 3         | 1.49%   |
| GNUstep      | 1         | 0.5%    |
| fvwm         | 1         | 0.5%    |
| DWM          | 1         | 0.5%    |
| AwesomeWM    | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 106       | 53.81%  |
| Console | 90        | 45.69%  |
| Wayland | 1         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 104       | 52%     |
| SLiM    | 67        | 33.5%   |
| SDDM    | 14        | 7%      |
| LightDM | 7         | 3.5%    |
| GDM     | 5         | 2.5%    |
| XDM     | 3         | 1.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 90        | 44.12%  |
| en_US        | 50        | 24.51%  |
| C            | 34        | 16.67%  |
| zh_CN        | 25        | 12.25%  |
| fr_FR        | 2         | 0.98%   |
| en           | 2         | 0.98%   |
| zh_CN.GB2312 | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 171       | 86.8%   |
| BIOS | 26        | 13.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 91        | 45.05%  |
| Ufs    | 84        | 41.58%  |
| Cd9660 | 24        | 11.88%  |
| Ffs    | 3         | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 179       | 90.86%  |
| MBR     | 15        | 7.61%   |
| Unknown | 3         | 1.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 39        | 20%     |
| Unknown                    | 28        | 14.36%  |
| Dell                       | 21        | 10.77%  |
| Hewlett-Packard            | 12        | 6.15%   |
| ASUSTek Computer           | 10        | 5.13%   |
| Intel                      | 6         | 3.08%   |
| Gigabyte Technology        | 6         | 3.08%   |
| MSI                        | 5         | 2.56%   |
| Supermicro                 | 4         | 2.05%   |
| Google                     | 4         | 2.05%   |
| ShenZhen MinWin Technology | 3         | 1.54%   |
| NEC Computers              | 3         | 1.54%   |
| AMI                        | 3         | 1.54%   |
| Timi                       | 2         | 1.03%   |
| Techvision                 | 2         | 1.03%   |
| Sony                       | 2         | 1.03%   |
| Panasonic                  | 2         | 1.03%   |
| PAIQ                       | 2         | 1.03%   |
| OEM                        | 2         | 1.03%   |
| Notebook                   | 2         | 1.03%   |
| MECHREVO S1 Series         | 2         | 1.03%   |
| MECHREVO                   | 2         | 1.03%   |
| HUAWEI                     | 2         | 1.03%   |
| HASEE Computer             | 2         | 1.03%   |
| Colorful Technology        | 2         | 1.03%   |
| ASRock                     | 2         | 1.03%   |
| Acer                       | 2         | 1.03%   |
| YENTEK                     | 1         | 0.51%   |
| YANYU                      | 1         | 0.51%   |
| YanRay Technology          | 1         | 0.51%   |
| WOOKING                    | 1         | 0.51%   |
| WlanCN                     | 1         | 0.51%   |
| Toshiba                    | 1         | 0.51%   |
| TOPFEEL                    | 1         | 0.51%   |
| Silicom                    | 1         | 0.51%   |
| Samsung Electronics        | 1         | 0.51%   |
| Protectli                  | 1         | 0.51%   |
| ONDA                       | 1         | 0.51%   |
| NORCO                      | 1         | 0.51%   |
| MAXSUN                     | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 31        | 15.9%   |
| ShenZhen MinWin MW-NANO-APL-4L             | 3         | 1.54%   |
| AMI Aptio CRB                              | 3         | 1.54%   |
| Techvision TVI7309X                        | 2         | 1.03%   |
| PAIQ EC3-BT19D4L                           | 2         | 1.03%   |
| MECHREVO S1 Series S1 Series               | 2         | 1.03%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 2         | 1.03%   |
| HP ProLiant DL320e Gen8 v2                 | 2         | 1.03%   |
| Google Kohaku                              | 2         | 1.03%   |
| YENTEK ITX-B75R1                           | 1         | 0.51%   |
| YANYU ITX-N29 VER:1.5 baytrail             | 1         | 0.51%   |
| YanRay B1904                               | 1         | 0.51%   |
| WOOKING X5                                 | 1         | 0.51%   |
| WlanCN 6000 Series                         | 1         | 0.51%   |
| Toshiba Satellite Pro L510                 | 1         | 0.51%   |
| TOPFEEL Topone series                      | 1         | 0.51%   |
| Timi RedmiBook Pro 15                      | 1         | 0.51%   |
| Timi A34R                                  | 1         | 0.51%   |
| Supermicro X10SRA                          | 1         | 0.51%   |
| Supermicro X10SL7-F                        | 1         | 0.51%   |
| Supermicro Super Server                    | 1         | 0.51%   |
| Supermicro NS-EI36S                        | 1         | 0.51%   |
| Sony SVS1511AJB                            | 1         | 0.51%   |
| Sony SVP13225SCBI                          | 1         | 0.51%   |
| Silicom 6200                               | 1         | 0.51%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV   | 1         | 0.51%   |
| Protectli FW6                              | 1         | 0.51%   |
| Panasonic CF-NX1GDHYS                      | 1         | 0.51%   |
| Panasonic CF-B11JWCYS                      | 1         | 0.51%   |
| ONDA N78G5D3 Ver:5.00                      | 1         | 0.51%   |
| OEM ITX-SC3                                | 1         | 0.51%   |
| OEM B85 JHS359                             | 1         | 0.51%   |
| Notebook W65KJ1_KK1                        | 1         | 0.51%   |
| Notebook W650DC,DD                         | 1         | 0.51%   |
| NORCO HB133                                | 1         | 0.51%   |
| NEC Computers SHARKBAY                     | 1         | 0.51%   |
| NEC Computers PC-VK17HBBCD                 | 1         | 0.51%   |
| NEC Computers PC-MC32MBZCEECH              | 1         | 0.51%   |
| MSI MS-7C82                                | 1         | 0.51%   |
| MSI MS-7C37                                | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 31        | 15.9%   |
| Lenovo ThinkPad                | 20        | 10.26%  |
| Dell PowerEdge                 | 5         | 2.56%   |
| Dell Precision                 | 4         | 2.05%   |
| Dell Latitude                  | 4         | 2.05%   |
| ShenZhen MinWin MW-NANO-APL-4L | 3         | 1.54%   |
| Dell OptiPlex                  | 3         | 1.54%   |
| Dell Inspiron                  | 3         | 1.54%   |
| AMI Aptio                      | 3         | 1.54%   |
| Techvision TVI7309X            | 2         | 1.03%   |
| PAIQ EC3-BT19D4L               | 2         | 1.03%   |
| MECHREVO S1 Series S1          | 2         | 1.03%   |
| Lenovo ThinkCentre             | 2         | 1.03%   |
| Lenovo SHARKBAY                | 2         | 1.03%   |
| HP ProLiant                    | 2         | 1.03%   |
| HP ProBook                     | 2         | 1.03%   |
| Google Kohaku                  | 2         | 1.03%   |
| Dell Vostro                    | 2         | 1.03%   |
| ASUS TUF                       | 2         | 1.03%   |
| YENTEK ITX-B75R1               | 1         | 0.51%   |
| YANYU ITX-N29                  | 1         | 0.51%   |
| YanRay B1904                   | 1         | 0.51%   |
| WOOKING X5                     | 1         | 0.51%   |
| WlanCN 6000                    | 1         | 0.51%   |
| Toshiba Satellite              | 1         | 0.51%   |
| TOPFEEL Topone                 | 1         | 0.51%   |
| Timi RedmiBook                 | 1         | 0.51%   |
| Timi A34R                      | 1         | 0.51%   |
| Supermicro X10SRA              | 1         | 0.51%   |
| Supermicro X10SL7-F            | 1         | 0.51%   |
| Supermicro Super               | 1         | 0.51%   |
| Supermicro NS-EI36S            | 1         | 0.51%   |
| Sony SVS1511AJB                | 1         | 0.51%   |
| Sony SVP13225SCBI              | 1         | 0.51%   |
| Silicom 6200                   | 1         | 0.51%   |
| Samsung 3570R                  | 1         | 0.51%   |
| Protectli FW6                  | 1         | 0.51%   |
| Panasonic CF-NX1GDHYS          | 1         | 0.51%   |
| Panasonic CF-B11JWCYS          | 1         | 0.51%   |
| ONDA N78G5D3                   | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 24        | 12.31%  |
| 2019    | 23        | 11.79%  |
| 2022    | 20        | 10.26%  |
| 2017    | 18        | 9.23%   |
| 2012    | 17        | 8.72%   |
| 2018    | 16        | 8.21%   |
| 2020    | 13        | 6.67%   |
| 2013    | 12        | 6.15%   |
| 2023    | 11        | 5.64%   |
| 2016    | 8         | 4.1%    |
| 2015    | 8         | 4.1%    |
| 2014    | 7         | 3.59%   |
| 2011    | 6         | 3.08%   |
| 2010    | 4         | 2.05%   |
| Unknown | 3         | 1.54%   |
| 2009    | 2         | 1.03%   |
| 2008    | 2         | 1.03%   |
| 2007    | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 93        | 47.69%  |
| Notebook       | 79        | 40.51%  |
| Server         | 11        | 5.64%   |
| Mini pc        | 8         | 4.1%    |
| All in one     | 2         | 1.03%   |
| System on chip | 1         | 0.51%   |
| Convertible    | 1         | 0.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 190       | 97.44%  |
| Yes  | 5         | 2.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 74        | 37.56%  |
| 4.01-8.0    | 44        | 22.34%  |
| 16.01-24.0  | 40        | 20.3%   |
| 32.01-64.0  | 17        | 8.63%   |
| 2.01-3.0    | 11        | 5.58%   |
| 24.01-32.0  | 5         | 2.54%   |
| 0.51-1.0    | 3         | 1.52%   |
| 64.01-256.0 | 2         | 1.02%   |
| 1.01-2.0    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 112       | 57.14%  |
| 0.51-1.0 | 53        | 27.04%  |
| 1.01-2.0 | 25        | 12.76%  |
| 3.01-4.0 | 2         | 1.02%   |
| 2.01-3.0 | 2         | 1.02%   |
| 0        | 1         | 0.51%   |
| Unknown  | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 127       | 62.56%  |
| 2      | 34        | 16.75%  |
| 0      | 30        | 14.78%  |
| 3      | 7         | 3.45%   |
| 5      | 3         | 1.48%   |
| 12     | 1         | 0.49%   |
| 4      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 82.74%  |
| Yes       | 34        | 17.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 89.23%  |
| No        | 21        | 10.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 52.31%  |
| No        | 93        | 47.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 57.95%  |
| Yes       | 82        | 42.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| China   | 195       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Shenzhen              | 22        | 10.53%  |
| Beijing               | 21        | 10.05%  |
| Shanghai              | 20        | 9.57%   |
| Chengdu               | 13        | 6.22%   |
| Guangzhou             | 12        | 5.74%   |
| Zhengzhou             | 9         | 4.31%   |
| Hangzhou              | 8         | 3.83%   |
| Jinrongjie            | 7         | 3.35%   |
| Xi'an                 | 6         | 2.87%   |
| Chongqing             | 5         | 2.39%   |
| Wuhan                 | 3         | 1.44%   |
| Nanjing               | 3         | 1.44%   |
| Yuzhong Chengguanzhen | 2         | 0.96%   |
| Yancheng              | 2         | 0.96%   |
| Xiamen                | 2         | 0.96%   |
| Suzhou                | 2         | 0.96%   |
| Songjiang             | 2         | 0.96%   |
| Qiqihar               | 2         | 0.96%   |
| Qinnan                | 2         | 0.96%   |
| Qingdao               | 2         | 0.96%   |
| Ningbo                | 2         | 0.96%   |
| Linyi                 | 2         | 0.96%   |
| Jiangbei              | 2         | 0.96%   |
| Dongguan              | 2         | 0.96%   |
| Changzhou             | 2         | 0.96%   |
| Changchun             | 2         | 0.96%   |
| Baiyun                | 2         | 0.96%   |
| Zhumadian             | 1         | 0.48%   |
| Zhongshan             | 1         | 0.48%   |
| Zhaoqing              | 1         | 0.48%   |
| Zhangjiakou           | 1         | 0.48%   |
| Yuefeng               | 1         | 0.48%   |
| Yichun                | 1         | 0.48%   |
| Yangpu                | 1         | 0.48%   |
| Xicheng District      | 1         | 0.48%   |
| Wuxi                  | 1         | 0.48%   |
| Wenzhou               | 1         | 0.48%   |
| Weifang               | 1         | 0.48%   |
| Tongshan              | 1         | 0.48%   |
| Tongchuanshi          | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 47     | 15.14%  |
| Seagate             | 27        | 44     | 12.39%  |
| WDC                 | 26        | 43     | 11.93%  |
| Intel               | 17        | 21     | 7.8%    |
| Toshiba             | 13        | 14     | 5.96%   |
| SanDisk             | 10        | 12     | 4.59%   |
| Kingston            | 8         | 9      | 3.67%   |
| HGST                | 6         | 11     | 2.75%   |
| Hitachi             | 5         | 6      | 2.29%   |
| Silicon Motion      | 4         | 5      | 1.83%   |
| FORESEE             | 4         | 4      | 1.83%   |
| China               | 4         | 7      | 1.83%   |
| Transcend           | 3         | 4      | 1.38%   |
| SK hynix            | 3         | 3      | 1.38%   |
| Plextor             | 3         | 4      | 1.38%   |
| Netac               | 3         | 3      | 1.38%   |
| Lenovo              | 3         | 3      | 1.38%   |
| KIOXIA-EXCERIA      | 3         | 6      | 1.38%   |
| Hikvision           | 3         | 3      | 1.38%   |
| Crucial             | 3         | 4      | 1.38%   |
| Micron Technology   | 2         | 3      | 0.92%   |
| KIOXIA              | 2         | 2      | 0.92%   |
| KingSpec            | 2         | 2      | 0.92%   |
| Hewlett-Packard     | 2         | 2      | 0.92%   |
| faspeed             | 2         | 2      | 0.92%   |
| Colorful            | 2         | 2      | 0.92%   |
| A-DATA Technology   | 2         | 3      | 0.92%   |
| UMIS                | 1         | 1      | 0.46%   |
| Topmore             | 1         | 1      | 0.46%   |
| tigo                | 1         | 1      | 0.46%   |
| SSSTC               | 1         | 1      | 0.46%   |
| SemsoTai            | 1         | 1      | 0.46%   |
| Ramsta              | 1         | 1      | 0.46%   |
| Pioneer             | 1         | 1      | 0.46%   |
| Phison              | 1         | 1      | 0.46%   |
| ORICO               | 1         | 1      | 0.46%   |
| NVMe                | 1         | 2      | 0.46%   |
| LITEONIT            | 1         | 1      | 0.46%   |
| Lexar               | 1         | 1      | 0.46%   |
| Hoodisk             | 1         | 2      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Seagate ST1000DM003-1SB102 1TB  | 4         | 1.66%   |
| Seagate ST500DM002-1BD142 500GB | 3         | 1.24%   |
| Samsung SSD 870 EVO 1TB         | 3         | 1.24%   |
| Samsung SSD 860 EVO 500GB       | 3         | 1.24%   |
| WDC WD5000LPCX-00VHAT0 500GB    | 2         | 0.83%   |
| Toshiba MQ04ABF100 1TB          | 2         | 0.83%   |
| Seagate ST2000LM007-1R8174 2TB  | 2         | 0.83%   |
| Seagate ST1000LM048-2E7172 1TB  | 2         | 0.83%   |
| Seagate ST1000DM010-2EP102 1TB  | 2         | 0.83%   |
| SanDisk SSD U100 24GB           | 2         | 0.83%   |
| Samsung SSD 970 EVO Plus 1TB    | 2         | 0.83%   |
| Samsung SSD 850 EVO 120GB       | 2         | 0.83%   |
| Samsung MZVL21T0HCLR-00BL7 1TB  | 2         | 0.83%   |
| Samsung HM320II 320GB           | 2         | 0.83%   |
| Netac SSD 120GB                 | 2         | 0.83%   |
| KIOXIA-EXCERIA SATA SSD 480GB   | 2         | 0.83%   |
| Kingston SSDNow V Series 64GB   | 2         | 0.83%   |
| Kingston SA400S37240G 240GB     | 2         | 0.83%   |
| Intel SSDSA2SH032G1GN 32GB      | 2         | 0.83%   |
| Intel SSDSA2CW120G3 120GB       | 2         | 0.83%   |
| Hikvision HS-SSD-C2000ECO 1024G | 2         | 0.83%   |
| HGST HTS725050A7E630 500GB      | 2         | 0.83%   |
| HGST HTS541010B7E610 1TB        | 2         | 0.83%   |
| FORESEE P900F256GB              | 2         | 0.83%   |
| WDC WUH721414ALE6L4 14TB        | 1         | 0.41%   |
| WDC WDS500G2B0C-00PXH0 500GB    | 1         | 0.41%   |
| WDC WDS500G1B0C-00S6U0 500GB    | 1         | 0.41%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1         | 0.41%   |
| WDC WDS120G2G0B-00EPW0 120GB    | 1         | 0.41%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 1         | 0.41%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1         | 0.41%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1         | 0.41%   |
| WDC WD5000LPCX-24C6HT0 500GB    | 1         | 0.41%   |
| WDC WD5000AAKX-083CA0 500GB     | 1         | 0.41%   |
| WDC WD40NPZZ-00A9JT0 4TB        | 1         | 0.41%   |
| WDC WD40EZAZ-00ZGHB0 4TB        | 1         | 0.41%   |
| WDC WD4005FZBX-00K5WB0 4TB      | 1         | 0.41%   |
| WDC WD3200BPVT-75ZEST0 320GB    | 1         | 0.41%   |
| WDC WD3200AAJS-00L7A0 320GB     | 1         | 0.41%   |
| WDC WD30EZRZ-00WN9B0 3TB        | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 44     | 39.13%  |
| WDC                 | 20        | 32     | 28.99%  |
| Toshiba             | 7         | 7      | 10.14%  |
| HGST                | 6         | 11     | 8.7%    |
| Hitachi             | 5         | 6      | 7.25%   |
| Samsung Electronics | 3         | 5      | 4.35%   |
| Hewlett-Packard     | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 18     | 16.5%   |
| Intel               | 14        | 18     | 13.59%  |
| SanDisk             | 9         | 11     | 8.74%   |
| Kingston            | 7         | 8      | 6.8%    |
| Toshiba             | 4         | 4      | 3.88%   |
| China               | 4         | 7      | 3.88%   |
| Transcend           | 3         | 4      | 2.91%   |
| Netac               | 3         | 3      | 2.91%   |
| Lenovo              | 3         | 3      | 2.91%   |
| KIOXIA-EXCERIA      | 3         | 6      | 2.91%   |
| WDC                 | 2         | 2      | 1.94%   |
| Plextor             | 2         | 2      | 1.94%   |
| Micron Technology   | 2         | 3      | 1.94%   |
| KingSpec            | 2         | 2      | 1.94%   |
| FORESEE             | 2         | 2      | 1.94%   |
| Faspeed             | 2         | 2      | 1.94%   |
| A-DATA Technology   | 2         | 3      | 1.94%   |
| tigo                | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 1      | 0.97%   |
| SemsoTai            | 1         | 1      | 0.97%   |
| Ramsta              | 1         | 1      | 0.97%   |
| Phison              | 1         | 1      | 0.97%   |
| ORICO               | 1         | 1      | 0.97%   |
| NVMe                | 1         | 1      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| Lexar               | 1         | 1      | 0.97%   |
| Hoodisk             | 1         | 2      | 0.97%   |
| Hewlett-Packard     | 1         | 1      | 0.97%   |
| FREEBSD             | 1         | 1      | 0.97%   |
| Fanxiang            | 1         | 2      | 0.97%   |
| Crucial             | 1         | 1      | 0.97%   |
| Colorful            | 1         | 1      | 0.97%   |
| Centerm             | 1         | 1      | 0.97%   |
| BR                  | 1         | 1      | 0.97%   |
| BORY                | 1         | 1      | 0.97%   |
| BIWIN               | 1         | 3      | 0.97%   |
| Apple               | 1         | 1      | 0.97%   |
| Apacer              | 1         | 1      | 0.97%   |
| aigo                | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 97        | 124    | 46.63%  |
| HDD  | 62        | 106    | 29.81%  |
| NVMe | 49        | 67     | 23.56%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 139       | 230    | 73.94%  |
| NVMe | 49        | 67     | 26.06%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 111       | 157    | 67.68%  |
| 0.51-1.0   | 35        | 40     | 21.34%  |
| 1.01-2.0   | 10        | 11     | 6.1%    |
| 3.01-4.0   | 3         | 5      | 1.83%   |
| 2.01-3.0   | 2         | 3      | 1.22%   |
| 10.01-20.0 | 2         | 12     | 1.22%   |
| 4.01-10.0  | 1         | 2      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 55        | 27.09%  |
| 101-250    | 48        | 23.65%  |
| 251-500    | 41        | 20.2%   |
| 21-50      | 20        | 9.85%   |
| 51-100     | 18        | 8.87%   |
| 501-1000   | 11        | 5.42%   |
| 1001-2000  | 8         | 3.94%   |
| Unknown    | 2         | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 172       | 86%     |
| 21-50   | 16        | 8%      |
| 51-100  | 5         | 2.5%    |
| 251-500 | 3         | 1.5%    |
| 101-250 | 2         | 1%      |
| Unknown | 2         | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-083CA0 500GB       | 1         | 1      | 4%      |
| WDC WD1600AAJS-22L7A0 160GB       | 1         | 1      | 4%      |
| WDC WD10SPZX-60Z10T0 1TB          | 1         | 1      | 4%      |
| WDC WD10EJRX-89N74Y0 1TB          | 1         | 1      | 4%      |
| Toshiba MQ02ABF050H-SSHD-8GB      | 1         | 1      | 4%      |
| SK hynix HFS064G3AMNB-2220A 64GB  | 1         | 1      | 4%      |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 4%      |
| Seagate ST3320418AS 320GB         | 1         | 2      | 4%      |
| Seagate ST320LT007-9ZV142 320GB   | 1         | 1      | 4%      |
| Seagate ST31500541AS 1.5TB        | 1         | 1      | 4%      |
| Seagate ST31000528AS 1TB          | 1         | 1      | 4%      |
| Samsung Electronics HM250HI 250GB | 1         | 1      | 4%      |
| Intel SSDSA2M160G2GC 160GB        | 1         | 2      | 4%      |
| Intel SSDSA2M120G2GC 120GB        | 1         | 1      | 4%      |
| Intel SSDPEKKW256G7 256GB         | 1         | 1      | 4%      |
| Hitachi HTS725050A7E630 500GB     | 1         | 1      | 4%      |
| Hitachi HTS723232A7A364 320GB     | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB        | 1         | 5      | 4%      |
| Fanxiang S101-240GB               | 1         | 1      | 4%      |
| Colorful SL500 640GB              | 1         | 1      | 4%      |
| China XJH-32GB                    | 1         | 1      | 4%      |
| China JWX 16GB MSATA              | 1         | 2      | 4%      |
| Centerm SSD 8GB                   | 1         | 1      | 4%      |
| BORY M500 16G                     | 1         | 1      | 4%      |
| BIWIN SSD 32GB                    | 1         | 3      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 20%     |
| WDC                 | 4         | 4      | 16%     |
| Intel               | 3         | 4      | 12%     |
| Hitachi             | 2         | 2      | 8%      |
| China               | 2         | 3      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| HGST                | 1         | 5      | 4%      |
| Fanxiang            | 1         | 1      | 4%      |
| Colorful            | 1         | 1      | 4%      |
| Centerm             | 1         | 1      | 4%      |
| BORY                | 1         | 1      | 4%      |
| BIWIN               | 1         | 3      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 35.71%  |
| WDC                 | 4         | 4      | 28.57%  |
| Hitachi             | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| HGST                | 1         | 5      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 19     | 56%     |
| SSD  | 10        | 14     | 40%     |
| NVMe | 1         | 1      | 4%      |

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
| Works    | 152       | 259    | 84.44%  |
| Malfunc  | 25        | 34     | 13.89%  |
| Detected | 3         | 4      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 150       | 63.83%  |
| Samsung Electronics                     | 17        | 7.23%   |
| AMD                                     | 16        | 6.81%   |
| SanDisk                                 | 10        | 4.26%   |
| Silicon Motion                          | 6         | 2.55%   |
| INNOGRIT                                | 4         | 1.7%    |
| Broadcom / LSI                          | 4         | 1.7%    |
| Shenzhen Longsys Electronics            | 3         | 1.28%   |
| MAXIO Technology (Hangzhou)             | 3         | 1.28%   |
| Marvell Technology Group                | 3         | 1.28%   |
| KIOXIA                                  | 3         | 1.28%   |
| Solid State Storage Technology          | 2         | 0.85%   |
| SK hynix                                | 2         | 0.85%   |
| Nvidia                                  | 2         | 0.85%   |
| Micron/Crucial Technology               | 2         | 0.85%   |
| Unknown                                 | 2         | 0.85%   |
| Toshiba                                 | 1         | 0.43%   |
| Shenzhen Unionmemory Information System | 1         | 0.43%   |
| Lite-On Technology                      | 1         | 0.43%   |
| Kingston Technology Company             | 1         | 0.43%   |
| JMicron Technology                      | 1         | 0.43%   |
| ASMedia Technology                      | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 7.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 13        | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 12        | 4.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 3.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 3.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.31%   |
| Unknown                                                                        | 6         | 2.31%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.92%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 1.54%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 1.54%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.15%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 3         | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.15%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 3         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.15%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.15%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 0.77%   |
| Shenzhen Longsys unknown                                                       | 2         | 0.77%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 0.77%   |
| Nvidia MCP61 IDE                                                               | 2         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 150       | 64.38%  |
| NVMe | 55        | 23.61%  |
| IDE  | 19        | 8.15%   |
| RAID | 7         | 3%      |
| SAS  | 2         | 0.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 167       | 85.64%  |
| AMD     | 24        | 12.31%  |
| ARM     | 2         | 1.03%   |
| Unknown | 2         | 1.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU J1900 @ 1.99GHz             | 12        | 6.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 3.08%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 5         | 2.56%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 4         | 2.05%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz           | 3         | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.54%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 3         | 1.54%   |
| Intel Celeron N5105 @ 2.00GHz                 | 3         | 1.54%   |
| Intel Celeron CPU J3455 @ 1.50GHz             | 3         | 1.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.54%   |
| Intel Pentium CPU G3260T @ 2.90GHz            | 2         | 1.03%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2         | 1.03%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 1.03%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 2         | 1.03%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.03%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.03%   |
| Intel Core i3-10105 CPU @ 3.70GHz             | 2         | 1.03%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 2         | 1.03%   |
| ARM Cortex-A53 r0p4                           | 2         | 1.03%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 1.03%   |
| AMD Ryzen 7 7840H w/ Radeon 780M Graphics     | 2         | 1.03%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.03%   |
|                                               | 2         | 1.03%   |
| Intel Xeon Silver 4210R CPU @ 2.40GHz         | 1         | 0.51%   |
| Intel Xeon E-2334 CPU @ 3.40GHz               | 1         | 0.51%   |
| Intel Xeon E-2314 CPU @ 2.80GHz               | 1         | 0.51%   |
| Intel Xeon CPU X5647 @ 2.93GHz                | 1         | 0.51%   |
| Intel Xeon CPU E5-2676 v3 @ 2.40GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz           | 1         | 0.51%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 0.51%   |
| Intel Xeon CPU E3-1535M v6 @ 3.10GHz          | 1         | 0.51%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1         | 0.51%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.51%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz           | 1         | 0.51%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 22.56%  |
| Intel Celeron           | 36        | 18.46%  |
| Intel Core i7           | 22        | 11.28%  |
| Intel Xeon              | 16        | 8.21%   |
| Intel Core i3           | 16        | 8.21%   |
| Other                   | 12        | 6.15%   |
| Intel Pentium           | 8         | 4.1%    |
| Intel Atom              | 8         | 4.1%    |
| AMD Ryzen 5             | 7         | 3.59%   |
| AMD Ryzen 7             | 5         | 2.56%   |
| Intel Core 2 Duo        | 3         | 1.54%   |
| ARM Cortex              | 2         | 1.03%   |
| AMD Ryzen 9             | 2         | 1.03%   |
| AMD G                   | 2         | 1.03%   |
| AMD Athlon II X4        | 2         | 1.03%   |
| Intel Xeon Silver       | 1         | 0.51%   |
| Intel Pentium Dual-Core | 1         | 0.51%   |
| Intel Genuine           | 1         | 0.51%   |
| Intel Core 2 Quad       | 1         | 0.51%   |
| Intel Celeron Dual-Core | 1         | 0.51%   |
| AMD Ryzen 3             | 1         | 0.51%   |
| AMD Phenom II X4        | 1         | 0.51%   |
| AMD GX                  | 1         | 0.51%   |
| AMD Athlon X2           | 1         | 0.51%   |
| AMD A10                 | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 90        | 46.15%  |
| 2       | 71        | 36.41%  |
| 6       | 8         | 4.1%    |
| 16      | 6         | 3.08%   |
| 8       | 6         | 3.08%   |
| 12      | 4         | 2.05%   |
| Unknown | 4         | 2.05%   |
| 24      | 2         | 1.03%   |
| 10      | 2         | 1.03%   |
| 20      | 1         | 0.51%   |
| 1       | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 190       | 97.44%  |
| Unknown | 4         | 2.05%   |
| 2       | 1         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 98        | 50.26%  |
| 2       | 92        | 47.18%  |
| Unknown | 5         | 2.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 38        | 19.49%  |
| Haswell       | 18        | 9.23%   |
| Silvermont    | 16        | 8.21%   |
| IvyBridge     | 16        | 8.21%   |
| Skylake       | 15        | 7.69%   |
| Unknown       | 14        | 7.18%   |
| SandyBridge   | 11        | 5.64%   |
| CometLake     | 7         | 3.59%   |
| TigerLake     | 6         | 3.08%   |
| Penryn        | 6         | 3.08%   |
| Goldmont plus | 6         | 3.08%   |
| Goldmont      | 6         | 3.08%   |
| Bonnell       | 6         | 3.08%   |
| Zen 2         | 5         | 2.56%   |
| K10           | 4         | 2.05%   |
| Broadwell     | 4         | 2.05%   |
| Zen+          | 3         | 1.54%   |
| Zen           | 3         | 1.54%   |
| Westmere      | 3         | 1.54%   |
| Zen 3         | 2         | 1.03%   |
| Bobcat        | 2         | 1.03%   |
| Piledriver    | 1         | 0.51%   |
| K10 Llano     | 1         | 0.51%   |
| Jaguar        | 1         | 0.51%   |
| Core          | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 138       | 62.44%  |
| Nvidia                     | 44        | 19.91%  |
| AMD                        | 28        | 12.67%  |
| Matrox Electronics Systems | 8         | 3.62%   |
| ASPEED Technology          | 3         | 1.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 5.86%   |
| Intel HD Graphics 620                                                                    | 9         | 4.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.7%    |
| Intel UHD Graphics 620                                                                   | 6         | 2.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 2.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.8%    |
| Intel HD Graphics 530                                                                    | 4         | 1.8%    |
| Intel HD Graphics 500                                                                    | 4         | 1.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 1.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.8%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.35%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 1.35%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 3         | 1.35%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.35%   |
| Intel HD Graphics 630                                                                    | 3         | 1.35%   |
| Intel HD Graphics 610                                                                    | 3         | 1.35%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.35%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 3         | 1.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.35%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.35%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.9%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.9%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 0.9%    |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.9%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.9%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.9%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 51.79%  |
| Intel + Nvidia | 24        | 12.31%  |
| 1 x Nvidia     | 19        | 9.74%   |
| 1 x AMD        | 19        | 9.74%   |
| 1 x Matrox     | 8         | 4.1%    |
| Intel + AMD    | 7         | 3.59%   |
| Other          | 6         | 3.08%   |
| 2 x Intel      | 6         | 3.08%   |
| 1 x ASPEED     | 3         | 1.54%   |
| 2 x AMD        | 1         | 0.51%   |
| AMD + Nvidia   | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 164       | 84.1%   |
| Proprietary | 19        | 9.74%   |
| Unknown     | 12        | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 87.76%  |
| 0.01-0.5   | 7         | 3.57%   |
| 1.01-2.0   | 5         | 2.55%   |
| 0.51-1.0   | 5         | 2.55%   |
| 7.01-8.0   | 4         | 2.04%   |
| 5.01-6.0   | 1         | 0.51%   |
| 3.01-4.0   | 1         | 0.51%   |
| 8.01-16.0  | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 13.75%  |
| Chimei Innolux          | 9         | 11.25%  |
| BOE                     | 8         | 10%     |
| AU Optronics            | 8         | 10%     |
| Dell                    | 6         | 7.5%    |
| Lenovo                  | 4         | 5%      |
| AOC                     | 4         | 5%      |
| Samsung Electronics     | 3         | 3.75%   |
| CSO                     | 3         | 3.75%   |
| Philips                 | 2         | 2.5%    |
| PANDA                   | 2         | 2.5%    |
| Chi Mei Optoelectronics | 2         | 2.5%    |
| BenQ                    | 2         | 2.5%    |
| ZL_                     | 1         | 1.25%   |
| ViewSonic               | 1         | 1.25%   |
| TMX                     | 1         | 1.25%   |
| Panasonic               | 1         | 1.25%   |
| Mi                      | 1         | 1.25%   |
| LGD                     | 1         | 1.25%   |
| HPN                     | 1         | 1.25%   |
| Hewlett-Packard         | 1         | 1.25%   |
| Haier                   | 1         | 1.25%   |
| GRR                     | 1         | 1.25%   |
| Daewoo                  | 1         | 1.25%   |
| CND                     | 1         | 1.25%   |
| CAN                     | 1         | 1.25%   |
| Apple                   | 1         | 1.25%   |
| Acer                    | 1         | 1.25%   |
| Unknown                 | 1         | 1.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch               | 2         | 2.5%    |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 2.5%    |
| ZL_ zhuoyue-HDMI ZL_2716 2560x1440 600x330mm 27.0-inch                | 1         | 1.25%   |
| ViewSonic VX2880-4K-HDU VSCA33A 3840x2160 630x360mm 28.6-inch         | 1         | 1.25%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x170mm 13.9-inch  | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 290x170mm 13.2-inch | 1         | 1.25%   |
| Samsung Electronics LCD Monitor SDC324D 1366x768 310x170mm 13.9-inch  | 1         | 1.25%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                 | 1         | 1.25%   |
| Philips 190V PHL0081 1440x900 400x250mm 18.6-inch                     | 1         | 1.25%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch           | 1         | 1.25%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                  | 1         | 1.25%   |
| LGD LCD Monitor 3840x1080                                             | 1         | 1.25%   |
| LG Display LCD Monitor LGD05F1 1920x1080 310x170mm 13.9-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD05CF 1920x1080 340x190mm 15.3-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD04B6 1366x768 310x170mm 13.9-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD04AF 1366x768 340x190mm 15.3-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0362 1600x900 310x170mm 13.9-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch          | 1         | 1.25%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 1         | 1.25%   |
| LG Display LCD Monitor LGD01E6 1366x768 310x170mm 13.9-inch           | 1         | 1.25%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 1         | 1.25%   |
| Lenovo L197 Wide LEN1152 1440x900 410x260mm 19.1-inch                 | 1         | 1.25%   |
| HPN LCD Monitor OMEN 25i                                              | 1         | 1.25%   |
| Hewlett-Packard LCD Monitor Inc. OMEN 25i                             | 1         | 1.25%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch              | 1         | 1.25%   |
| GRR GRC GRR2400 1920x1080 520x310mm 23.8-inch                         | 1         | 1.25%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 1         | 1.25%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                     | 1         | 1.25%   |
| Dell S2240M DELD055 1920x1080 480x270mm 21.7-inch                     | 1         | 1.25%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 1         | 1.25%   |
| Dell P2415Q DELA0C0 3840x2160 530x300mm 24.0-inch                     | 1         | 1.25%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1         | 1.25%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                     | 1         | 1.25%   |
| CSO LCD Monitor CSO1408 3120x2080 300x200mm 14.2-inch                 | 1         | 1.25%   |
| CSO LCD Monitor CSO1404 1920x1200 300x190mm 14.0-inch                 | 1         | 1.25%   |
| CSO LCD Monitor CSO076D 2560x1600 290x180mm 13.4-inch                 | 1         | 1.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 31        | 39.74%  |
| 1366x768 (WXGA)    | 20        | 25.64%  |
| 3840x2160 (4K)     | 5         | 6.41%   |
| 2560x1440 (QHD)    | 4         | 5.13%   |
| 1600x900 (HD+)     | 3         | 3.85%   |
| 1440x900 (WXGA+)   | 3         | 3.85%   |
| 2560x1600          | 2         | 2.56%   |
| 1280x1024 (SXGA)   | 2         | 2.56%   |
| 3840x1080          | 1         | 1.28%   |
| 3200x2000          | 1         | 1.28%   |
| 3120x2080          | 1         | 1.28%   |
| 2880x1800          | 1         | 1.28%   |
| 2560x1080          | 1         | 1.28%   |
| 1920x1200 (WUXGA)  | 1         | 1.28%   |
| 1680x1050 (WSXGA+) | 1         | 1.28%   |
| Unknown            | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 25        | 32.47%  |
| 15      | 18        | 23.38%  |
| 27      | 5         | 6.49%   |
| 24      | 5         | 6.49%   |
| 23      | 4         | 5.19%   |
| 21      | 3         | 3.9%    |
| 19      | 3         | 3.9%    |
| 12      | 3         | 3.9%    |
| 14      | 2         | 2.6%    |
| 54      | 1         | 1.3%    |
| 29      | 1         | 1.3%    |
| 28      | 1         | 1.3%    |
| 22      | 1         | 1.3%    |
| 18      | 1         | 1.3%    |
| 17      | 1         | 1.3%    |
| 16      | 1         | 1.3%    |
| 11      | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 48.05%  |
| 501-600     | 14        | 18.18%  |
| 201-300     | 12        | 15.58%  |
| 401-500     | 6         | 7.79%   |
| 351-400     | 4         | 5.19%   |
| 601-700     | 2         | 2.6%    |
| 1001-1500   | 1         | 1.3%    |
| Unknown     | 1         | 1.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 63        | 82.89%  |
| 16/10   | 9         | 11.84%  |
| 5/4     | 1         | 1.32%   |
| 3/2     | 1         | 1.32%   |
| 21/9    | 1         | 1.32%   |
| Unknown | 1         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 22        | 28.57%  |
| 91-100         | 15        | 19.48%  |
| 201-250        | 12        | 15.58%  |
| 301-350        | 6         | 7.79%   |
| 151-200        | 5         | 6.49%   |
| 71-80          | 4         | 5.19%   |
| 61-70          | 3         | 3.9%    |
| 101-110        | 3         | 3.9%    |
| 111-120        | 2         | 2.6%    |
| More than 1000 | 1         | 1.3%    |
| 51-60          | 1         | 1.3%    |
| 351-500        | 1         | 1.3%    |
| 121-130        | 1         | 1.3%    |
| Unknown        | 1         | 1.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 27        | 35.06%  |
| 101-120       | 19        | 24.68%  |
| 51-100        | 19        | 24.68%  |
| 161-240       | 8         | 10.39%  |
| More than 240 | 3         | 3.9%    |
| Unknown       | 1         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 108       | 54.82%  |
| 1     | 87        | 44.16%  |
| 2     | 2         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 135       | 51.72%  |
| Realtek Semiconductor    | 86        | 32.95%  |
| Qualcomm Atheros         | 17        | 6.51%   |
| Broadcom                 | 15        | 5.75%   |
| Xiaomi                   | 1         | 0.38%   |
| Ralink Technology        | 1         | 0.38%   |
| Qualcomm                 | 1         | 0.38%   |
| OPPO Electronics         | 1         | 0.38%   |
| Mellanox Technologies    | 1         | 0.38%   |
| Marvell Technology Group | 1         | 0.38%   |
| Edimax Technology        | 1         | 0.38%   |
| Apple                    | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 20.75%  |
| Intel I211 Gigabit Network Connection                             | 18        | 5.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 2.83%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.52%   |
| Intel I350 Gigabit Network Connection                             | 7         | 2.2%    |
| Intel 82583V Gigabit Network Connection                           | 7         | 2.2%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 7         | 2.2%    |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.89%   |
| Intel Ethernet Controller I226-V                                  | 6         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.57%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.57%   |
| Intel I210 Gigabit Network Connection                             | 5         | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 1.57%   |
| Intel Wireless 7260                                               | 4         | 1.26%   |
| Intel Wireless 3165                                               | 4         | 1.26%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.26%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.94%   |
| Intel Wireless 8260                                               | 3         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.94%   |
| Intel 82576 Gigabit Network Connection                            | 3         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.63%   |
| Intel Wireless-AC 9260                                            | 2         | 0.63%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 2         | 0.63%   |
| Intel Ethernet Connection X553 1GbE                               | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 69        | 63.89%  |
| Qualcomm Atheros      | 16        | 14.81%  |
| Realtek Semiconductor | 15        | 13.89%  |
| Broadcom              | 6         | 5.56%   |
| Ralink Technology     | 1         | 0.93%   |
| Edimax Technology     | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                      | 8         | 7.34%   |
| Intel Wi-Fi 6 AX201                                             | 6         | 5.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)  | 5         | 4.59%   |
| Intel Wi-Fi 6 AX200                                             | 5         | 4.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                | 5         | 4.59%   |
| Intel Wireless 7260                                             | 4         | 3.67%   |
| Intel Wireless 3165                                             | 4         | 3.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                 | 4         | 3.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 4         | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                    | 4         | 3.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 3         | 2.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter      | 3         | 2.75%   |
| Intel Wireless 8260                                             | 3         | 2.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                          | 3         | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                 | 3         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 1.83%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 2         | 1.83%   |
| Realtek RTL8188EE Wireless Network Adapter                      | 2         | 1.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 2         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                | 2         | 1.83%   |
| Intel Wireless-AC 9260                                          | 2         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                  | 2         | 1.83%   |
| Intel Centrino Wireless-N 2200                                  | 2         | 1.83%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                    | 2         | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                | 2         | 1.83%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2         | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter             | 2         | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                 | 1         | 0.92%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                          | 1         | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 1         | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 0.92%   |
| Ralink RT5370 Wireless Adapter                                  | 1         | 0.92%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter      | 1         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)  | 1         | 0.92%   |
| Intel Wireless 7265                                             | 1         | 0.92%   |
| Intel Wireless 3160                                             | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 92        | 48.17%  |
| Realtek Semiconductor    | 80        | 41.88%  |
| Broadcom                 | 10        | 5.24%   |
| Qualcomm Atheros         | 4         | 2.09%   |
| Xiaomi                   | 1         | 0.52%   |
| Qualcomm                 | 1         | 0.52%   |
| OPPO Electronics         | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| Apple                    | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 31.73%  |
| Intel I211 Gigabit Network Connection                             | 18        | 8.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.33%   |
| Intel I350 Gigabit Network Connection                             | 7         | 3.37%   |
| Intel 82583V Gigabit Network Connection                           | 7         | 3.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 7         | 3.37%   |
| Intel Ethernet Controller I226-V                                  | 6         | 2.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.4%    |
| Intel I210 Gigabit Network Connection                             | 5         | 2.4%    |
| Intel Ethernet Controller I225-V                                  | 4         | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.92%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.92%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.44%   |
| Intel 82576 Gigabit Network Connection                            | 3         | 1.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.96%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 2         | 0.96%   |
| Intel Ethernet Connection X553 1GbE                               | 2         | 0.96%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2         | 0.96%   |
| Intel 82575EB Gigabit Network Connection                          | 2         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.48%   |
| Qualcomm FP3                                                      | 1         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.48%   |
| OPPO PGCM10 RNDIS Control RNDIS Ethernet Data                     | 1         | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.48%   |
| Intel Ethernet Connection X553 10 GbE SFP+                        | 1         | 0.48%   |
| Intel Ethernet Connection X552 10 GbE SFP+                        | 1         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.48%   |
| Intel Ethernet Connection (5) I219-V                              | 1         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 174       | 62.82%  |
| WiFi     | 102       | 36.82%  |
| Unknown  | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 157       | 74.06%  |
| WiFi     | 55        | 25.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 103       | 52.55%  |
| 1     | 38        | 19.39%  |
| 6     | 18        | 9.18%   |
| 4     | 18        | 9.18%   |
| 5     | 6         | 3.06%   |
| 8     | 3         | 1.53%   |
| 7     | 3         | 1.53%   |
| 3     | 3         | 1.53%   |
| 0     | 3         | 1.53%   |
| 10    | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 167       | 83.08%  |
| Yes  | 34        | 16.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 67.07%  |
| Broadcom                        | 5         | 6.1%    |
| Realtek Semiconductor           | 4         | 4.88%   |
| Qualcomm Atheros Communications | 4         | 4.88%   |
| Lite-On Technology              | 3         | 3.66%   |
| Cambridge Silicon Radio         | 3         | 3.66%   |
| Apple                           | 3         | 3.66%   |
| Foxconn / Hon Hai               | 2         | 2.44%   |
| Skylight Digital                | 1         | 1.22%   |
| IMC Networks                    | 1         | 1.22%   |
| Alps Electric                   | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 21        | 25.61%  |
| Intel AX201 Bluetooth                                       | 13        | 15.85%  |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 5         | 6.1%    |
| Intel AX200 Bluetooth                                       | 5         | 6.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 5         | 6.1%    |
| Intel AX210 Bluetooth                                       | 3         | 3.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 3.66%   |
| Apple Bluetooth Host Controller                             | 3         | 3.66%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.44%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 1         | 1.22%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.22%   |
| Realtek Bluetooth Adapter                                   | 1         | 1.22%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 1.22%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.22%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 1.22%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 1.22%   |
| Lite-On BCM43142A0 Bluetooth Module                         | 1         | 1.22%   |
| Intel AX211 Bluetooth                                       | 1         | 1.22%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.22%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.22%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth                  | 1         | 1.22%   |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 140       | 74.87%  |
| AMD                    | 23        | 12.3%   |
| Nvidia                 | 22        | 11.76%  |
| Generalplus Technology | 1         | 0.53%   |
| C-Media Electronics    | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 9.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 7.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 4.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 4.27%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 3.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 3.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.9%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.9%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 1.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.42%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 1.42%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.42%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.42%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.42%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.42%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.95%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.95%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.95%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 62        | 28.05%  |
| Kingston            | 34        | 15.38%  |
| SK hynix            | 32        | 14.48%  |
| Micron Technology   | 21        | 9.5%    |
| Unknown             | 20        | 9.05%   |
| Unknown             | 11        | 4.98%   |
| A-DATA Technology   | 10        | 4.52%   |
| Ramaxel Technology  | 5         | 2.26%   |
| Crucial             | 4         | 1.81%   |
| Nanya Technology    | 3         | 1.36%   |
| Corsair             | 3         | 1.36%   |
| Transcend           | 2         | 0.9%    |
| Team                | 2         | 0.9%    |
| G.Skill             | 2         | 0.9%    |
| Elpida              | 2         | 0.9%    |
| Unknown (8AFD)      | 1         | 0.45%   |
| Unknown (08B5)      | 1         | 0.45%   |
| SemsoTai            | 1         | 0.45%   |
| Ramsta              | 1         | 0.45%   |
| Lenovo              | 1         | 0.45%   |
| KingTiger           | 1         | 0.45%   |
| Innodisk            | 1         | 0.45%   |
| GeIL                | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown                                                     | 11        | 4.68%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s      | 5         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 1.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 4         | 1.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 1.28%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s       | 3         | 1.28%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s     | 3         | 1.28%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 3         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR3 800MT/s                  | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 2         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                    | 2         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.85%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s         | 2         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s       | 2         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.85%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s         | 2         | 0.85%   |
| Micron RAM Module 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.85%   |
| Kingston RAM KHX3200C16FB/8G 8GB SODIMM DDR4 2400MT/s       | 2         | 0.85%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s        | 2         | 0.85%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.85%   |
| Unknown RAM XinJuHuo 8GB SODIMM DDR3 1600MT/s               | 1         | 0.43%   |
| Unknown RAM TMKS8G68ALFBCH-266 8192MB SODIMM DDR4 2400MT/s  | 1         | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                  | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                     | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM SDRAM                           | 1         | 0.43%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                    | 1         | 0.43%   |
| Unknown RAM IM38GS48A16-BBBHB0 8GB DIMM DDR3 1600MT/s       | 1         | 0.43%   |
| Unknown (8AFD) RAM SED2666S1908 8GB SODIMM DDR4 2667MT/s    | 1         | 0.43%   |
| Unknown (08B5) RAM IM416GU8N24 16384MB SODIMM DDR4 2400MT/s | 1         | 0.43%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s        | 1         | 0.43%   |
| Transcend RAM JM1600KSH-8G 8192MB SODIMM DDR3 1333MT/s      | 1         | 0.43%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2133MT/s          | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 46.52%  |
| DDR3    | 78        | 41.71%  |
| LPDDR3  | 5         | 2.67%   |
| Unknown | 5         | 2.67%   |
| LPDDR4  | 4         | 2.14%   |
| DDR2    | 4         | 2.14%   |
| DDR5    | 3         | 1.6%    |
| SDRAM   | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 54.55%  |
| DIMM         | 67        | 35.83%  |
| Row Of Chips | 13        | 6.95%   |
| Unknown      | 3         | 1.6%    |
| RIMM         | 1         | 0.53%   |
| Chip         | 1         | 0.53%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 80        | 38.46%  |
| 4096  | 66        | 31.73%  |
| 2048  | 31        | 14.9%   |
| 16384 | 25        | 12.02%  |
| 1024  | 4         | 1.92%   |
| 32768 | 2         | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 47        | 22.6%   |
| 2133    | 29        | 13.94%  |
| 2400    | 26        | 12.5%   |
| 1333    | 25        | 12.02%  |
| 2667    | 23        | 11.06%  |
| 3200    | 18        | 8.65%   |
| 800     | 9         | 4.33%   |
| 1334    | 7         | 3.37%   |
| 2666    | 4         | 1.92%   |
| 4267    | 3         | 1.44%   |
| 1067    | 3         | 1.44%   |
| Unknown | 3         | 1.44%   |
| 4800    | 2         | 0.96%   |
| 2933    | 2         | 0.96%   |
| 1867    | 2         | 0.96%   |
| 667     | 2         | 0.96%   |
| 5600    | 1         | 0.48%   |
| 1066    | 1         | 0.48%   |
| 533     | 1         | 0.48%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 30%     |
| Bison Electronics                      | 11        | 15.71%  |
| Realtek Semiconductor                  | 7         | 10%     |
| Sunplus Innovation Technology          | 4         | 5.71%   |
| IMC Networks                           | 4         | 5.71%   |
| Syntek                                 | 3         | 4.29%   |
| Microdia                               | 3         | 4.29%   |
| Quanta                                 | 2         | 2.86%   |
| Luxvisions Innotech Limited            | 2         | 2.86%   |
| Logitech                               | 2         | 2.86%   |
| Lite-On Technology                     | 2         | 2.86%   |
| Z-Star Microelectronics                | 1         | 1.43%   |
| Silicon Motion                         | 1         | 1.43%   |
| Qtech                                  | 1         | 1.43%   |
| Lenovo                                 | 1         | 1.43%   |
| Importek                               | 1         | 1.43%   |
| Genesys Logic                          | 1         | 1.43%   |
| Foxconn / Hon Hai                      | 1         | 1.43%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.43%   |
| ALi                                    | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 8         | 10.81%  |
| Realtek Integrated_Webcam_HD                         | 3         | 4.05%   |
| Chicony USB2.0 VGA UVC WebCam                        | 3         | 4.05%   |
| Chicony Lenovo EasyCamera                            | 3         | 4.05%   |
| Bison ThinkPad Integrated Camera                     | 3         | 4.05%   |
| Bison Integrated Camera                              | 3         | 4.05%   |
| Syntek Lenovo EasyCamera                             | 2         | 2.7%    |
| Sunplus XiaoMi USB 2.0 Webcam                        | 2         | 2.7%    |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.7%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 2.7%    |
| IMC Networks Integrated Camera                       | 2         | 2.7%    |
| Chicony Realtek DMFT RGB                             | 2         | 2.7%    |
| Chicony Integrated IR Camera                         | 2         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)              | 2         | 2.7%    |
| Chicony 8M Camera                                    | 2         | 2.7%    |
| Chicony 720p HD Camera                               | 2         | 2.7%    |
| Bison Lenovo Integrated Webcam                       | 2         | 2.7%    |
| Z-Star Lenovo USB 2.0 UVC Camera                     | 1         | 1.35%   |
| Syntek Integrated Camera                             | 1         | 1.35%   |
| Silicon Motion Realtek USB 2.0 PC Camera             | 1         | 1.35%   |
| Realtek USB 2.0 PC Camera                            | 1         | 1.35%   |
| Realtek Integrated Webcam                            | 1         | 1.35%   |
| Realtek HD WebCam                                    | 1         | 1.35%   |
| Realtek Front Camera                                 | 1         | 1.35%   |
| Quanta Realtek DMFT RGB                              | 1         | 1.35%   |
| Quanta ov9734_techfront_camera                       | 1         | 1.35%   |
| Qtech USB Camera                                     | 1         | 1.35%   |
| Microdia Laptop_Integrated_Webcam_0.3M               | 1         | 1.35%   |
| Microdia Integrated_Webcam_HD                        | 1         | 1.35%   |
| Microdia Camera                                      | 1         | 1.35%   |
| Logitech Webcam C170                                 | 1         | 1.35%   |
| Logitech C670i FHD Webcam                            | 1         | 1.35%   |
| Lite-On Integrated Camera                            | 1         | 1.35%   |
| Lite-On HP HD Camera                                 | 1         | 1.35%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.35%   |
| Importek USB 2.0 Camera                              | 1         | 1.35%   |
| IMC Networks Realtek PC Camera                       | 1         | 1.35%   |
| IMC Networks Integrated Webcam                       | 1         | 1.35%   |
| Genesys Logic Camera                                 | 1         | 1.35%   |
| Foxconn / Hon Hai USB2.0 Camera                      | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Synaptics                  | 5         | 29.41%  |
| Shenzhen Goodix Technology | 2         | 11.76%  |
| Upek                       | 1         | 5.88%   |
| Fingerprint Cards          | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                                            | 4         | 23.53%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 11.76%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 11.76%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 11.76%  |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 11.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 5.88%   |
| Fingerprint Cards FPC Fingerprint Reader                                   | 1         | 5.88%   |

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
| 1     | 67        | 33.84%  |
| 0     | 56        | 28.28%  |
| 2     | 43        | 21.72%  |
| 3     | 23        | 11.62%  |
| 4     | 9         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 130       | 56.03%  |
| Bluetooth                | 30        | 12.93%  |
| Net/wireless             | 25        | 10.78%  |
| Card reader              | 20        | 8.62%   |
| Fingerprint reader       | 17        | 7.33%   |
| Sound                    | 5         | 2.16%   |
| Net/ethernet             | 4         | 1.72%   |
| Network                  | 1         | 0.43%   |

