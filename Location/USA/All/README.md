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

Total: 4943

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Unknown       | Unknown                     | Desktop     | [4277dc49d0](https://bsd-hardware.info/?probe=4277dc49d0) | May 04, 2023 |
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
| Dell          | 0KWVT8 A03                  | Desktop     | [05465e4575](https://bsd-hardware.info/?probe=05465e4575) | Apr 04, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [540417a54b](https://bsd-hardware.info/?probe=540417a54b) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6a4aceff9b](https://bsd-hardware.info/?probe=6a4aceff9b) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [3fdf1c8c26](https://bsd-hardware.info/?probe=3fdf1c8c26) | Apr 04, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [ece70e8117](https://bsd-hardware.info/?probe=ece70e8117) | Apr 04, 2023 |
| Protectli     | FW4C                        | Desktop     | [b0d1010d58](https://bsd-hardware.info/?probe=b0d1010d58) | Apr 04, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [43c6f94486](https://bsd-hardware.info/?probe=43c6f94486) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK U810               | Notebook    | [c7718b4aa3](https://bsd-hardware.info/?probe=c7718b4aa3) | Apr 03, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [d6a5747911](https://bsd-hardware.info/?probe=d6a5747911) | Apr 03, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [61ab7d478c](https://bsd-hardware.info/?probe=61ab7d478c) | Apr 03, 2023 |
| HP            | 81C6 MVB 0C                 | Server      | [65d2113596](https://bsd-hardware.info/?probe=65d2113596) | Apr 03, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [e0b56a9911](https://bsd-hardware.info/?probe=e0b56a9911) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1d4b3bd94f](https://bsd-hardware.info/?probe=1d4b3bd94f) | Apr 03, 2023 |
| HP            | 212B                        | Desktop     | [00c0cbbc9a](https://bsd-hardware.info/?probe=00c0cbbc9a) | Apr 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6b05bd9d53](https://bsd-hardware.info/?probe=6b05bd9d53) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0013b5dfa4](https://bsd-hardware.info/?probe=0013b5dfa4) | Apr 02, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ff7383d618](https://bsd-hardware.info/?probe=ff7383d618) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d4cc6cf349](https://bsd-hardware.info/?probe=d4cc6cf349) | Apr 02, 2023 |
| HP            | 82A2                        | Desktop     | [92fb7830a2](https://bsd-hardware.info/?probe=92fb7830a2) | Apr 02, 2023 |
| Lenovo        | ThinkPad T590 20N4001PUS    | Notebook    | [0b93ef8199](https://bsd-hardware.info/?probe=0b93ef8199) | Apr 02, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [0ce88445bf](https://bsd-hardware.info/?probe=0ce88445bf) | Apr 02, 2023 |
| Sun           | SUNW,T5140                  | Desktop     | [a285e4f43a](https://bsd-hardware.info/?probe=a285e4f43a) | Apr 02, 2023 |
| Protectli     | VP2410                      | Desktop     | [8eda4d8e3d](https://bsd-hardware.info/?probe=8eda4d8e3d) | Apr 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9bac0139f1](https://bsd-hardware.info/?probe=9bac0139f1) | Apr 01, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bd01e6e577](https://bsd-hardware.info/?probe=bd01e6e577) | Apr 01, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [b41b088f96](https://bsd-hardware.info/?probe=b41b088f96) | Apr 01, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [31ed779fdc](https://bsd-hardware.info/?probe=31ed779fdc) | Mar 31, 2023 |
| SolidRun      | CEX7 Platform               | Desktop     | [8e2e4d6686](https://bsd-hardware.info/?probe=8e2e4d6686) | Mar 31, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [99f769056a](https://bsd-hardware.info/?probe=99f769056a) | Mar 31, 2023 |
| HP            | 1495                        | Desktop     | [a916ab2122](https://bsd-hardware.info/?probe=a916ab2122) | Mar 31, 2023 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [1285cbe6ca](https://bsd-hardware.info/?probe=1285cbe6ca) | Mar 31, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [cc6e076383](https://bsd-hardware.info/?probe=cc6e076383) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | Notebook    | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [a71a4da74b](https://bsd-hardware.info/?probe=a71a4da74b) | Mar 31, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [c13f32c492](https://bsd-hardware.info/?probe=c13f32c492) | Mar 30, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [c654ef10d6](https://bsd-hardware.info/?probe=c654ef10d6) | Mar 30, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [27d9a92cda](https://bsd-hardware.info/?probe=27d9a92cda) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | Notebook    | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [44da021f65](https://bsd-hardware.info/?probe=44da021f65) | Mar 29, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [dc06ff6076](https://bsd-hardware.info/?probe=dc06ff6076) | Mar 29, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [06a2d12cbe](https://bsd-hardware.info/?probe=06a2d12cbe) | Mar 29, 2023 |
| Dell          | Latitude 5590               | Notebook    | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Supermicro    | C7SIM-Q                     | Desktop     | [47ce885e13](https://bsd-hardware.info/?probe=47ce885e13) | Mar 29, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [34ad91005f](https://bsd-hardware.info/?probe=34ad91005f) | Mar 29, 2023 |
| Google        | Stout                       | Notebook    | [d8346bb5da](https://bsd-hardware.info/?probe=d8346bb5da) | Mar 29, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [38a784fcd8](https://bsd-hardware.info/?probe=38a784fcd8) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [723e81c698](https://bsd-hardware.info/?probe=723e81c698) | Mar 29, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [3895705bbd](https://bsd-hardware.info/?probe=3895705bbd) | Mar 29, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [b2a2fc8fe6](https://bsd-hardware.info/?probe=b2a2fc8fe6) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [2c6fc04801](https://bsd-hardware.info/?probe=2c6fc04801) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [c6c33779dc](https://bsd-hardware.info/?probe=c6c33779dc) | Mar 29, 2023 |
| Supermicro    | X11SSL-F                    | Server      | [ac9e97cf34](https://bsd-hardware.info/?probe=ac9e97cf34) | Mar 28, 2023 |
| HP            | 18E7                        | Desktop     | [f83e0bbd69](https://bsd-hardware.info/?probe=f83e0bbd69) | Mar 28, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| Protectli     | FW4B                        | Desktop     | [17c0040b42](https://bsd-hardware.info/?probe=17c0040b42) | Mar 28, 2023 |
| Unknown       | Unknown                     | Firewall    | [c2c2b195e4](https://bsd-hardware.info/?probe=c2c2b195e4) | Mar 28, 2023 |
| Dell          | 0CNCJW A10                  | Server      | [f912d933df](https://bsd-hardware.info/?probe=f912d933df) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [b4805cd318](https://bsd-hardware.info/?probe=b4805cd318) | Mar 27, 2023 |
| HP            | 8054                        | Desktop     | [6c82269548](https://bsd-hardware.info/?probe=6c82269548) | Mar 27, 2023 |
| HP            | 213D A01                    | Desktop     | [d5efcf6e96](https://bsd-hardware.info/?probe=d5efcf6e96) | Mar 27, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [e5a3f523a6](https://bsd-hardware.info/?probe=e5a3f523a6) | Mar 27, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [1d0a4ac0a1](https://bsd-hardware.info/?probe=1d0a4ac0a1) | Mar 27, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [91759ff33b](https://bsd-hardware.info/?probe=91759ff33b) | Mar 27, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0eab0142d5](https://bsd-hardware.info/?probe=0eab0142d5) | Mar 26, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [06e3c70f23](https://bsd-hardware.info/?probe=06e3c70f23) | Mar 26, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [8f47736c3b](https://bsd-hardware.info/?probe=8f47736c3b) | Mar 26, 2023 |
| Dell          | 0C2GT0 A05                  | Server      | [2d32ae23e6](https://bsd-hardware.info/?probe=2d32ae23e6) | Mar 26, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [39410cb2dd](https://bsd-hardware.info/?probe=39410cb2dd) | Mar 26, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7652c9891e](https://bsd-hardware.info/?probe=7652c9891e) | Mar 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f07e9fd36c](https://bsd-hardware.info/?probe=f07e9fd36c) | Mar 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3f21567fdf](https://bsd-hardware.info/?probe=3f21567fdf) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [38a22651c6](https://bsd-hardware.info/?probe=38a22651c6) | Mar 26, 2023 |
| Lenovo        | 312D SDK0L22692 WIN 3306... | Mini pc     | [73519e765c](https://bsd-hardware.info/?probe=73519e765c) | Mar 26, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [3db3c8f002](https://bsd-hardware.info/?probe=3db3c8f002) | Mar 26, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [284c499b74](https://bsd-hardware.info/?probe=284c499b74) | Mar 26, 2023 |
| Unknown       | Unknown                     | Firewall    | [e17beb7d4c](https://bsd-hardware.info/?probe=e17beb7d4c) | Mar 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [2634ccb935](https://bsd-hardware.info/?probe=2634ccb935) | Mar 26, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [bc1cc29291](https://bsd-hardware.info/?probe=bc1cc29291) | Mar 26, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [2affd2540a](https://bsd-hardware.info/?probe=2affd2540a) | Mar 26, 2023 |
| CheckPoint    | T-110-00                    | Desktop     | [eecf6b8096](https://bsd-hardware.info/?probe=eecf6b8096) | Mar 25, 2023 |
| Protectli     | FW4B                        | Desktop     | [3c333bad9c](https://bsd-hardware.info/?probe=3c333bad9c) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [c7c5a8ae97](https://bsd-hardware.info/?probe=c7c5a8ae97) | Mar 25, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [312a9b3461](https://bsd-hardware.info/?probe=312a9b3461) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a46f77ccdc](https://bsd-hardware.info/?probe=a46f77ccdc) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b64571464f](https://bsd-hardware.info/?probe=b64571464f) | Mar 25, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [9aa3b17016](https://bsd-hardware.info/?probe=9aa3b17016) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| HP            | 8055                        | Desktop     | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [56c12d6bf6](https://bsd-hardware.info/?probe=56c12d6bf6) | Mar 24, 2023 |
| Dell          | Latitude 5500               | Notebook    | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [e9cbfc666b](https://bsd-hardware.info/?probe=e9cbfc666b) | Mar 24, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [e99acbbc10](https://bsd-hardware.info/?probe=e99acbbc10) | Mar 24, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [a46e065fac](https://bsd-hardware.info/?probe=a46e065fac) | Mar 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f294f7ae04](https://bsd-hardware.info/?probe=f294f7ae04) | Mar 23, 2023 |
| HP            | 3397                        | Desktop     | [a3a77965fc](https://bsd-hardware.info/?probe=a3a77965fc) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [bff3fc8a58](https://bsd-hardware.info/?probe=bff3fc8a58) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M910q 10MVCT... | Desktop     | [5459ed9c31](https://bsd-hardware.info/?probe=5459ed9c31) | Mar 22, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [7b22e68dea](https://bsd-hardware.info/?probe=7b22e68dea) | Mar 22, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [73ecb1afc1](https://bsd-hardware.info/?probe=73ecb1afc1) | Mar 22, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [e2d0aa1444](https://bsd-hardware.info/?probe=e2d0aa1444) | Mar 22, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [c2546b211b](https://bsd-hardware.info/?probe=c2546b211b) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| NF596         | 1.0                         | Desktop     | [9de0fd33a4](https://bsd-hardware.info/?probe=9de0fd33a4) | Mar 22, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [491f4cc780](https://bsd-hardware.info/?probe=491f4cc780) | Mar 22, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [1f8be65019](https://bsd-hardware.info/?probe=1f8be65019) | Mar 22, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [e1ee6d8a11](https://bsd-hardware.info/?probe=e1ee6d8a11) | Mar 22, 2023 |
| ASRockRack    | E3C236D2I                   | Desktop     | [e407119ecf](https://bsd-hardware.info/?probe=e407119ecf) | Mar 22, 2023 |
| Dell          | 081N4V A04                  | Server      | [d8a5f43d05](https://bsd-hardware.info/?probe=d8a5f43d05) | Mar 21, 2023 |
| ASRockRack    | E3C236D2I                   | Desktop     | [0854f96185](https://bsd-hardware.info/?probe=0854f96185) | Mar 21, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [e405ff5adf](https://bsd-hardware.info/?probe=e405ff5adf) | Mar 21, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [7bac9347ec](https://bsd-hardware.info/?probe=7bac9347ec) | Mar 21, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [8d84f81be3](https://bsd-hardware.info/?probe=8d84f81be3) | Mar 21, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [0fe355f959](https://bsd-hardware.info/?probe=0fe355f959) | Mar 21, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| Supermicro    | X11SSL-F                    | Server      | [1aab89d35b](https://bsd-hardware.info/?probe=1aab89d35b) | Mar 20, 2023 |
| Silicom       | 80300-0134-g01              | Desktop     | [3cd6c5ba13](https://bsd-hardware.info/?probe=3cd6c5ba13) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [10f3485393](https://bsd-hardware.info/?probe=10f3485393) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [91b5500917](https://bsd-hardware.info/?probe=91b5500917) | Mar 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [17f0f138ee](https://bsd-hardware.info/?probe=17f0f138ee) | Mar 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [da50d91be4](https://bsd-hardware.info/?probe=da50d91be4) | Mar 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [726abe2f1d](https://bsd-hardware.info/?probe=726abe2f1d) | Mar 19, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [317c44acd2](https://bsd-hardware.info/?probe=317c44acd2) | Mar 19, 2023 |
| Datto         | SSD                         | Desktop     | [40831257b2](https://bsd-hardware.info/?probe=40831257b2) | Mar 19, 2023 |
| HP            | 212B                        | Desktop     | [d4d93ad679](https://bsd-hardware.info/?probe=d4d93ad679) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [4e1fe3a676](https://bsd-hardware.info/?probe=4e1fe3a676) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| HP            | 18E7                        | Desktop     | [d3b280214a](https://bsd-hardware.info/?probe=d3b280214a) | Mar 18, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [c6ddfac225](https://bsd-hardware.info/?probe=c6ddfac225) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [705ac0b37f](https://bsd-hardware.info/?probe=705ac0b37f) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | Notebook    | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [dcab531d1e](https://bsd-hardware.info/?probe=dcab531d1e) | Mar 18, 2023 |
| Dell          | 03X6X0 A01                  | Server      | [6366bfde8d](https://bsd-hardware.info/?probe=6366bfde8d) | Mar 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| Protectli     | FW6                         | Desktop     | [f24f1a8a3e](https://bsd-hardware.info/?probe=f24f1a8a3e) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [daaa6c0069](https://bsd-hardware.info/?probe=daaa6c0069) | Mar 17, 2023 |
| Protectli     | FW4B                        | Desktop     | [fd65403ca2](https://bsd-hardware.info/?probe=fd65403ca2) | Mar 17, 2023 |
| HP            | 3397                        | Desktop     | [2851f91f5f](https://bsd-hardware.info/?probe=2851f91f5f) | Mar 17, 2023 |
| HP            | 8103 A01                    | Mini pc     | [5898916fc9](https://bsd-hardware.info/?probe=5898916fc9) | Mar 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [d0a9398982](https://bsd-hardware.info/?probe=d0a9398982) | Mar 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [19fc3562d9](https://bsd-hardware.info/?probe=19fc3562d9) | Mar 16, 2023 |
| Silicom       | 80300-0134-g01              | Desktop     | [228e446ed5](https://bsd-hardware.info/?probe=228e446ed5) | Mar 15, 2023 |
| Dell          | 0M9KCM A00                  | Desktop     | [27a1ab8450](https://bsd-hardware.info/?probe=27a1ab8450) | Mar 15, 2023 |
| HP            | 81B7                        | All in one  | [fa5eb6a694](https://bsd-hardware.info/?probe=fa5eb6a694) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Dell          | 078NPM A00                  | Desktop     | [234e8a451a](https://bsd-hardware.info/?probe=234e8a451a) | Mar 14, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [8025ea3b29](https://bsd-hardware.info/?probe=8025ea3b29) | Mar 14, 2023 |
| Protectli     | FW4C Ver                    | Desktop     | [6b260b1da3](https://bsd-hardware.info/?probe=6b260b1da3) | Mar 14, 2023 |
| Intel         | HURONRIVER                  | Desktop     | [06f89fc17d](https://bsd-hardware.info/?probe=06f89fc17d) | Mar 14, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [80e3f3f6cf](https://bsd-hardware.info/?probe=80e3f3f6cf) | Mar 14, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [4e27c68fa1](https://bsd-hardware.info/?probe=4e27c68fa1) | Mar 14, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [7db8571228](https://bsd-hardware.info/?probe=7db8571228) | Mar 13, 2023 |
| Google        | Panther                     | Desktop     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [51bc37434e](https://bsd-hardware.info/?probe=51bc37434e) | Mar 13, 2023 |
| Intel         | QHSW02                      | Desktop     | [ccfc6d4abf](https://bsd-hardware.info/?probe=ccfc6d4abf) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Intel         | QHSW02                      | Desktop     | [b56a128e7e](https://bsd-hardware.info/?probe=b56a128e7e) | Mar 13, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [f1dc71b749](https://bsd-hardware.info/?probe=f1dc71b749) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [49764ec5fa](https://bsd-hardware.info/?probe=49764ec5fa) | Mar 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [a8a9ed7f9e](https://bsd-hardware.info/?probe=a8a9ed7f9e) | Mar 13, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [8f819aa5b0](https://bsd-hardware.info/?probe=8f819aa5b0) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| HP            | 18E7                        | Desktop     | [a5f169c741](https://bsd-hardware.info/?probe=a5f169c741) | Mar 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [82ec8cfd3b](https://bsd-hardware.info/?probe=82ec8cfd3b) | Mar 13, 2023 |
| HP            | 1495                        | Desktop     | [840b4864ab](https://bsd-hardware.info/?probe=840b4864ab) | Mar 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bff43fa4b](https://bsd-hardware.info/?probe=1bff43fa4b) | Mar 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [2b318d15c4](https://bsd-hardware.info/?probe=2b318d15c4) | Mar 13, 2023 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [8b112aa100](https://bsd-hardware.info/?probe=8b112aa100) | Mar 13, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [a81fd51eee](https://bsd-hardware.info/?probe=a81fd51eee) | Mar 13, 2023 |
| HP            | 213D A01                    | Desktop     | [7021648a32](https://bsd-hardware.info/?probe=7021648a32) | Mar 13, 2023 |
| Lenovo        | SHARKBAY SDK0K17763 WIN ... | Desktop     | [c9279ce424](https://bsd-hardware.info/?probe=c9279ce424) | Mar 13, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [fe42d48be1](https://bsd-hardware.info/?probe=fe42d48be1) | Mar 13, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [8fb58149ab](https://bsd-hardware.info/?probe=8fb58149ab) | Mar 12, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [44f983da74](https://bsd-hardware.info/?probe=44f983da74) | Mar 12, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [8a41ff57c2](https://bsd-hardware.info/?probe=8a41ff57c2) | Mar 12, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [cdccf8cecb](https://bsd-hardware.info/?probe=cdccf8cecb) | Mar 12, 2023 |
| Supermicro    | X7DWE                       | Desktop     | [e40b569ff7](https://bsd-hardware.info/?probe=e40b569ff7) | Mar 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [12dbc1a2b3](https://bsd-hardware.info/?probe=12dbc1a2b3) | Mar 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bcd9058821](https://bsd-hardware.info/?probe=bcd9058821) | Mar 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d93ae717cc](https://bsd-hardware.info/?probe=d93ae717cc) | Mar 12, 2023 |
| ASRock        | 4X4-V1000                   | Desktop     | [f0582d78bf](https://bsd-hardware.info/?probe=f0582d78bf) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [38af3096a6](https://bsd-hardware.info/?probe=38af3096a6) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Dell          | 0KYJ8C A02                  | Desktop     | [53fa01007b](https://bsd-hardware.info/?probe=53fa01007b) | Mar 12, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [69db0ac0a4](https://bsd-hardware.info/?probe=69db0ac0a4) | Mar 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [83fa5b5a27](https://bsd-hardware.info/?probe=83fa5b5a27) | Mar 12, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [80dd48bca9](https://bsd-hardware.info/?probe=80dd48bca9) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| HP            | 802E                        | Desktop     | [914384fca0](https://bsd-hardware.info/?probe=914384fca0) | Mar 11, 2023 |
| HP            | 1495                        | Desktop     | [a8b5c70376](https://bsd-hardware.info/?probe=a8b5c70376) | Mar 11, 2023 |
| HP            | 1495                        | Desktop     | [f238006f2e](https://bsd-hardware.info/?probe=f238006f2e) | Mar 11, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [a4366e53ba](https://bsd-hardware.info/?probe=a4366e53ba) | Mar 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5cdfb9cc34](https://bsd-hardware.info/?probe=5cdfb9cc34) | Mar 10, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [37e1562772](https://bsd-hardware.info/?probe=37e1562772) | Mar 10, 2023 |
| GoWin Solu... | R86S                        | Desktop     | [b815ae3950](https://bsd-hardware.info/?probe=b815ae3950) | Mar 10, 2023 |
| Dell          | 03X6X0 A02                  | Server      | [a61aa56ca8](https://bsd-hardware.info/?probe=a61aa56ca8) | Mar 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fc6796cea](https://bsd-hardware.info/?probe=0fc6796cea) | Mar 10, 2023 |
| maiyunda      | www.maiyunda.com            | Desktop     | [e09800b936](https://bsd-hardware.info/?probe=e09800b936) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [e5a43dd311](https://bsd-hardware.info/?probe=e5a43dd311) | Mar 10, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0FH00    | Notebook    | [44a8bf8fbc](https://bsd-hardware.info/?probe=44a8bf8fbc) | Mar 10, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [904fde472a](https://bsd-hardware.info/?probe=904fde472a) | Mar 10, 2023 |
| Dell          | 07F37C A01                  | Desktop     | [6819027308](https://bsd-hardware.info/?probe=6819027308) | Mar 10, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [970f35af17](https://bsd-hardware.info/?probe=970f35af17) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [5082b8203b](https://bsd-hardware.info/?probe=5082b8203b) | Mar 09, 2023 |
| maiyunda      | www.maiyunda.com            | Desktop     | [8687dfb1bb](https://bsd-hardware.info/?probe=8687dfb1bb) | Mar 09, 2023 |
| Supermicro    | X11SPW-TF                   | Server      | [09e5fc33ad](https://bsd-hardware.info/?probe=09e5fc33ad) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [12ac44cbf7](https://bsd-hardware.info/?probe=12ac44cbf7) | Mar 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [486646710b](https://bsd-hardware.info/?probe=486646710b) | Mar 09, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [bfa33e378d](https://bsd-hardware.info/?probe=bfa33e378d) | Mar 09, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [df7a30fc45](https://bsd-hardware.info/?probe=df7a30fc45) | Mar 09, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [b6909ae507](https://bsd-hardware.info/?probe=b6909ae507) | Mar 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [61c0604160](https://bsd-hardware.info/?probe=61c0604160) | Mar 08, 2023 |
| PC Engines    | APU2                        | Desktop     | [bd7676affa](https://bsd-hardware.info/?probe=bd7676affa) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | Notebook    | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [34cf4827d7](https://bsd-hardware.info/?probe=34cf4827d7) | Mar 07, 2023 |
| Pegatron      | 2ACD                        | Desktop     | [7058138064](https://bsd-hardware.info/?probe=7058138064) | Mar 07, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [724809078f](https://bsd-hardware.info/?probe=724809078f) | Mar 07, 2023 |
| Supermicro    | X11SBA-LN4F                 | Server      | [1a107a7c43](https://bsd-hardware.info/?probe=1a107a7c43) | Mar 07, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [64d844777a](https://bsd-hardware.info/?probe=64d844777a) | Mar 07, 2023 |
| Dell          | 0RC130 A03                  | Server      | [f59f5613b3](https://bsd-hardware.info/?probe=f59f5613b3) | Mar 06, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [d0bf3eb35d](https://bsd-hardware.info/?probe=d0bf3eb35d) | Mar 06, 2023 |
| HP            | 1495                        | Desktop     | [4a91a0efd9](https://bsd-hardware.info/?probe=4a91a0efd9) | Mar 06, 2023 |
| HP            | 1495                        | Desktop     | [1379869eeb](https://bsd-hardware.info/?probe=1379869eeb) | Mar 06, 2023 |
| Supermicro    | X12SDV-8C-SPT8FA            | Server      | [1cfe8960a1](https://bsd-hardware.info/?probe=1cfe8960a1) | Mar 06, 2023 |
| Acer          | Veriton X2120G v1.0         | Desktop     | [f5acb2d032](https://bsd-hardware.info/?probe=f5acb2d032) | Mar 06, 2023 |
| Unknown       | N4000                       | Desktop     | [12afb5cc25](https://bsd-hardware.info/?probe=12afb5cc25) | Mar 06, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [98f6c8f34b](https://bsd-hardware.info/?probe=98f6c8f34b) | Mar 06, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [13e4d3ce10](https://bsd-hardware.info/?probe=13e4d3ce10) | Mar 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [dfa124b6f9](https://bsd-hardware.info/?probe=dfa124b6f9) | Mar 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [64513c0ff5](https://bsd-hardware.info/?probe=64513c0ff5) | Mar 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ebba69095d](https://bsd-hardware.info/?probe=ebba69095d) | Mar 05, 2023 |
| Dell          | 0D02VH A01                  | Desktop     | [0a9a676d17](https://bsd-hardware.info/?probe=0a9a676d17) | Mar 05, 2023 |
| Unknown       | YL-J3160L4                  | Desktop     | [f75fee2a2d](https://bsd-hardware.info/?probe=f75fee2a2d) | Mar 05, 2023 |
| Dell          | 0KV62T A02                  | Desktop     | [986f18fa08](https://bsd-hardware.info/?probe=986f18fa08) | Mar 05, 2023 |
| Supermicro    | X11SPW-TF                   | Server      | [5e615ed399](https://bsd-hardware.info/?probe=5e615ed399) | Mar 05, 2023 |
| Dell          | 08VT7V A05                  | Server      | [8783f6ce77](https://bsd-hardware.info/?probe=8783f6ce77) | Mar 05, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [8d278732dd](https://bsd-hardware.info/?probe=8d278732dd) | Mar 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9e37e0391](https://bsd-hardware.info/?probe=a9e37e0391) | Mar 04, 2023 |
| Dell          | 0W23H8 A03                  | Server      | [7e2a57616b](https://bsd-hardware.info/?probe=7e2a57616b) | Mar 04, 2023 |
| AZW           | GK55                        | Desktop     | [c22ee2e279](https://bsd-hardware.info/?probe=c22ee2e279) | Mar 03, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d8c78b92a7](https://bsd-hardware.info/?probe=d8c78b92a7) | Mar 03, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [b281eec189](https://bsd-hardware.info/?probe=b281eec189) | Mar 03, 2023 |
| Dell          | 0YDJK3 A10                  | Server      | [5d6babda3e](https://bsd-hardware.info/?probe=5d6babda3e) | Mar 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [822db616e5](https://bsd-hardware.info/?probe=822db616e5) | Mar 01, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [98096adfaa](https://bsd-hardware.info/?probe=98096adfaa) | Mar 01, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5b6dd24e9a](https://bsd-hardware.info/?probe=5b6dd24e9a) | Mar 01, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [2e40df5a32](https://bsd-hardware.info/?probe=2e40df5a32) | Mar 01, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [084e395665](https://bsd-hardware.info/?probe=084e395665) | Mar 01, 2023 |
| Supermicro    | X11SBA-LN4F                 | Server      | [1f530ffbc8](https://bsd-hardware.info/?probe=1f530ffbc8) | Mar 01, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [dd8749ed6a](https://bsd-hardware.info/?probe=dd8749ed6a) | Feb 28, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [72d45455a5](https://bsd-hardware.info/?probe=72d45455a5) | Feb 28, 2023 |
| HP            | 8522 A01                    | Mini pc     | [9cc3faa610](https://bsd-hardware.info/?probe=9cc3faa610) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | Notebook    | [0e051e7291](https://bsd-hardware.info/?probe=0e051e7291) | Feb 27, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [ffbb7e1a96](https://bsd-hardware.info/?probe=ffbb7e1a96) | Feb 27, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [1b11bb9003](https://bsd-hardware.info/?probe=1b11bb9003) | Feb 27, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [652b3323c6](https://bsd-hardware.info/?probe=652b3323c6) | Feb 27, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| HP            | 17E2                        | Mini pc     | [12fde81dce](https://bsd-hardware.info/?probe=12fde81dce) | Feb 27, 2023 |
| Intel         | HM570                       | Desktop     | [2588c37fc2](https://bsd-hardware.info/?probe=2588c37fc2) | Feb 27, 2023 |
| HP            | 2215                        | Desktop     | [33881e14ce](https://bsd-hardware.info/?probe=33881e14ce) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [55afde6894](https://bsd-hardware.info/?probe=55afde6894) | Feb 26, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [9d406d735e](https://bsd-hardware.info/?probe=9d406d735e) | Feb 26, 2023 |
| HP            | 1495                        | Desktop     | [70c761d6fe](https://bsd-hardware.info/?probe=70c761d6fe) | Feb 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [806efadc12](https://bsd-hardware.info/?probe=806efadc12) | Feb 26, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [efb350b5f2](https://bsd-hardware.info/?probe=efb350b5f2) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [62567aa5d4](https://bsd-hardware.info/?probe=62567aa5d4) | Feb 26, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [2e3026e0fd](https://bsd-hardware.info/?probe=2e3026e0fd) | Feb 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d558069dea](https://bsd-hardware.info/?probe=d558069dea) | Feb 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [f4b0301fe5](https://bsd-hardware.info/?probe=f4b0301fe5) | Feb 26, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [d13b4a674b](https://bsd-hardware.info/?probe=d13b4a674b) | Feb 26, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [263be0365a](https://bsd-hardware.info/?probe=263be0365a) | Feb 26, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005SU... | Notebook    | [7750c38cd0](https://bsd-hardware.info/?probe=7750c38cd0) | Feb 25, 2023 |
| Dell          | Latitude 5591               | Notebook    | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| Dell          | 0M877N A01                  | Server      | [cfae198d09](https://bsd-hardware.info/?probe=cfae198d09) | Feb 25, 2023 |

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
| OPNsense 23.1.11  | 106       | 2.74%   |
| OPNsense 21.7.7   | 90        | 2.33%   |
| OPNsense 22.7.10  | 82        | 2.12%   |
| OPNsense 23.1     | 80        | 2.07%   |
| OPNsense 21.7.3   | 77        | 1.99%   |
| OPNsense 23.1.7   | 69        | 1.79%   |
| OPNsense 21.7.1   | 69        | 1.79%   |
| OPNsense 23.1.1   | 68        | 1.76%   |
| OPNsense 22.1     | 68        | 1.76%   |
| OPNsense 21.1.5   | 67        | 1.73%   |
| helloSystem 0.7.0 | 66        | 1.71%   |
| OPNsense 23.1.5   | 65        | 1.68%   |
| OPNsense 22.7.4   | 65        | 1.68%   |
| OPNsense 22.1.10  | 64        | 1.66%   |
| OPNsense 20.7.8   | 61        | 1.58%   |
| OPNsense 21.1.4   | 60        | 1.55%   |
| FreeBSD 13.0      | 60        | 1.55%   |
| OPNsense 22.1.8   | 58        | 1.5%    |
| OPNsense 21.1.3   | 58        | 1.5%    |
| FreeBSD 13.1      | 56        | 1.45%   |
| OPNsense 23.1.9   | 54        | 1.4%    |
| OPNsense 23.1.6   | 54        | 1.4%    |
| OPNsense 21.1     | 51        | 1.32%   |
| OPNsense 22.7.9   | 50        | 1.29%   |
| OPNsense 22.7.6   | 50        | 1.29%   |
| OPNsense 21.1.8   | 50        | 1.29%   |
| OPNsense 23.7     | 48        | 1.24%   |
| helloSystem 0.8.0 | 47        | 1.22%   |
| OPNsense 22.7.8   | 45        | 1.16%   |
| OPNsense 22.7.2   | 45        | 1.16%   |
| helloSystem 0.8.1 | 44        | 1.14%   |
| OPNsense 22.7     | 43        | 1.11%   |
| OPNsense 22.1.6   | 42        | 1.09%   |
| OPNsense 22.1.4   | 42        | 1.09%   |
| OPNsense 22.1.2   | 42        | 1.09%   |
| OPNsense 21.1.7   | 42        | 1.09%   |
| OPNsense 21.1.1   | 42        | 1.09%   |
| helloSystem 0.5.0 | 42        | 1.09%   |
| OPNsense 22.7.11  | 41        | 1.06%   |
| OPNsense 22.7.7   | 40        | 1.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1771      | 62.73%  |
| FreeBSD     | 520       | 18.42%  |
| helloSystem | 246       | 8.71%   |
| OpenBSD     | 100       | 3.54%   |
| GhostBSD    | 58        | 2.05%   |
| NomadBSD    | 36        | 1.28%   |
| pfSense     | 18        | 0.64%   |
| FreeNAS     | 17        | 0.6%    |
| MidnightBSD | 15        | 0.53%   |
| TrueNAS     | 11        | 0.39%   |
| HardenedBSD | 9         | 0.32%   |
| NetBSD      | 7         | 0.25%   |
| DragonFly   | 6         | 0.21%   |
| FuryBSD     | 3         | 0.11%   |
| XigmaNAS    | 2         | 0.07%   |
| OS108       | 2         | 0.07%   |
| MyBee       | 1         | 0.04%   |
| ClonOS      | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2742      | 98%     |
| i386    | 29        | 1.04%   |
| arm64   | 23        | 0.82%   |
| powerpc | 3         | 0.11%   |
| sparc64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 2022      | 70.87%  |
| helloDesktop  | 264       | 9.25%   |
| XFCE          | 110       | 3.86%   |
| KDE5          | 83        | 2.91%   |
| MATE          | 80        | 2.8%    |
| fvwm          | 58        | 2.03%   |
| TWM           | 56        | 1.96%   |
| GNOME         | 49        | 1.72%   |
| Openbox       | 47        | 1.65%   |
| i3            | 30        | 1.05%   |
| Cinnamon      | 12        | 0.42%   |
| Enlightenment | 8         | 0.28%   |
| Fluxbox       | 6         | 0.21%   |
| LXQt          | 5         | 0.18%   |
| Lumina        | 5         | 0.18%   |
| AwesomeWM     | 3         | 0.11%   |
| Xfwm4         | 2         | 0.07%   |
| Picom         | 2         | 0.07%   |
| GNUstep       | 2         | 0.07%   |
| DWM           | 2         | 0.07%   |
| Window Maker  | 1         | 0.04%   |
| spectrwm      | 1         | 0.04%   |
| sdorfehs      | 1         | 0.04%   |
| LXDE          | 1         | 0.04%   |
| KDE           | 1         | 0.04%   |
| Compton       | 1         | 0.04%   |
| CDE           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2046      | 72.73%  |
| X11     | 760       | 27.02%  |
| Wayland | 7         | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2237      | 78.93%  |
| SLiM    | 344       | 12.14%  |
| LightDM | 93        | 3.28%   |
| SDDM    | 83        | 2.93%   |
| XDM     | 45        | 1.59%   |
| GDM     | 29        | 1.02%   |
| Ly      | 3         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 2085      | 72.8%   |
| en_US           | 409       | 14.28%  |
| C               | 316       | 11.03%  |
| en              | 33        | 1.15%   |
| fr_FR           | 6         | 0.21%   |
| fr              | 4         | 0.14%   |
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
| EFI  | 2413      | 84.88%  |
| BIOS | 430       | 15.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1445      | 50.07%  |
| Zfs     | 1250      | 43.31%  |
| Ffs     | 100       | 3.47%   |
| Cd9660  | 84        | 2.91%   |
| Hammer2 | 6         | 0.21%   |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2598      | 91.9%   |
| MBR     | 201       | 7.11%   |
| Unknown | 22        | 0.78%   |
| BSD     | 6         | 0.21%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 458       | 16.38%  |
| Hewlett-Packard     | 288       | 10.3%   |
| Lenovo              | 255       | 9.12%   |
| Supermicro          | 235       | 8.4%    |
| Unknown             | 218       | 7.8%    |
| Protectli           | 210       | 7.51%   |
| ASUSTek Computer    | 180       | 6.44%   |
| Intel               | 122       | 4.36%   |
| ASRock              | 99        | 3.54%   |
| Gigabyte Technology | 78        | 2.79%   |
| MSI                 | 70        | 2.5%    |
| Apple               | 48        | 1.72%   |
| AMI                 | 48        | 1.72%   |
| PC Engines          | 38        | 1.36%   |
| Acer                | 31        | 1.11%   |
| Techvision          | 22        | 0.79%   |
| Sophos              | 20        | 0.72%   |
| Deciso              | 19        | 0.68%   |
| AZW                 | 17        | 0.61%   |
| MW                  | 13        | 0.46%   |
| Google              | 12        | 0.43%   |
| CompuLab            | 12        | 0.43%   |
| Biostar             | 12        | 0.43%   |
| Toshiba             | 11        | 0.39%   |
| BESSTAR Tech        | 11        | 0.39%   |
| ASRockRack          | 11        | 0.39%   |
| System76            | 10        | 0.36%   |
| AWOW                | 10        | 0.36%   |
| Shuttle             | 9         | 0.32%   |
| Seeed Studio        | 9         | 0.32%   |
| Fujitsu             | 9         | 0.32%   |
| Foxconn             | 8         | 0.29%   |
| Hardkernel          | 7         | 0.25%   |
| Framework           | 7         | 0.25%   |
| CWWK                | 7         | 0.25%   |
| ZOTAC               | 6         | 0.21%   |
| Datto               | 6         | 0.21%   |
| Cisco Systems       | 6         | 0.21%   |
| CheckPoint          | 6         | 0.21%   |
| SeeedStudio         | 5         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 225       | 8.05%   |
| Protectli FW4B                      | 72        | 2.58%   |
| Supermicro Super Server             | 63        | 2.25%   |
| Protectli FW6                       | 59        | 2.11%   |
| AMI Aptio CRB                       | 43        | 1.54%   |
| Intel Q3XXG4-P V1.0                 | 39        | 1.39%   |
| HP t730 Thin Client                 | 26        | 0.93%   |
| HP t620 PLUS Quad Core TC           | 24        | 0.86%   |
| Dell OptiPlex 9020                  | 23        | 0.82%   |
| Techvision TVI7309X                 | 22        | 0.79%   |
| Dell OptiPlex 3020                  | 22        | 0.79%   |
| Supermicro X9SCL/X9SCM              | 21        | 0.75%   |
| Dell PowerEdge R210 II              | 21        | 0.75%   |
| ASUS All Series                     | 21        | 0.75%   |
| Supermicro X10SLH-N6-ST031          | 19        | 0.68%   |
| PC Engines APU2                     | 18        | 0.64%   |
| Dell OptiPlex 7010                  | 16        | 0.57%   |
| Protectli VP2410                    | 15        | 0.54%   |
| PC Engines apu4                     | 15        | 0.54%   |
| Protectli FW2B                      | 13        | 0.46%   |
| MW GMLK-2_5G4L                      | 13        | 0.46%   |
| Dell Wyse 5070 Extended Thin Client | 13        | 0.46%   |
| Dell OptiPlex 990                   | 13        | 0.46%   |
| CompuLab fitlet2                    | 12        | 0.43%   |
| Supermicro A1SAi                    | 11        | 0.39%   |
| HP EliteDesk 800 G1 SFF             | 11        | 0.39%   |
| Sophos XG                           | 10        | 0.36%   |
| Protectli FW4C                      | 10        | 0.36%   |
| Protectli FW1                       | 10        | 0.36%   |
| Dell OptiPlex 7040                  | 10        | 0.36%   |
| Deciso Netboard A20                 | 10        | 0.36%   |
| Intel Nobilis                       | 9         | 0.32%   |
| HP EliteDesk 800 G3 SFF             | 9         | 0.32%   |
| Dell PowerEdge R610                 | 9         | 0.32%   |
| Dell OptiPlex 9010                  | 9         | 0.32%   |
| Sophos SG                           | 8         | 0.29%   |
| HP ProDesk 600 G1 SFF               | 8         | 0.29%   |
| HP Compaq Elite 8300 SFF            | 8         | 0.29%   |
| Dell PowerEdge R630                 | 8         | 0.29%   |
| Dell OptiPlex 790                   | 8         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 225       | 8.05%   |
| Dell OptiPlex              | 182       | 6.51%   |
| Lenovo ThinkPad            | 141       | 5.04%   |
| Dell PowerEdge             | 116       | 4.15%   |
| Protectli FW4B             | 72        | 2.58%   |
| Supermicro Super           | 63        | 2.25%   |
| Lenovo ThinkCentre         | 63        | 2.25%   |
| Protectli FW6              | 59        | 2.11%   |
| HP EliteDesk               | 45        | 1.61%   |
| Dell Inspiron              | 45        | 1.61%   |
| AMI Aptio                  | 43        | 1.54%   |
| Intel Q3XXG4-P             | 40        | 1.43%   |
| Dell Latitude              | 38        | 1.36%   |
| Dell Precision             | 31        | 1.11%   |
| HP ProDesk                 | 30        | 1.07%   |
| ASUS ROG                   | 29        | 1.04%   |
| HP t730                    | 26        | 0.93%   |
| HP t620                    | 26        | 0.93%   |
| ASUS PRIME                 | 26        | 0.93%   |
| HP Compaq                  | 25        | 0.89%   |
| ASUS TUF                   | 24        | 0.86%   |
| HP Pavilion                | 23        | 0.82%   |
| Techvision TVI7309X        | 22        | 0.79%   |
| Supermicro X9SCL           | 21        | 0.75%   |
| HP ProLiant                | 21        | 0.75%   |
| ASUS All                   | 21        | 0.75%   |
| Supermicro X10SLH-N6-ST031 | 19        | 0.68%   |
| PC Engines APU2            | 18        | 0.64%   |
| Protectli VP2410           | 15        | 0.54%   |
| PC Engines apu4            | 15        | 0.54%   |
| ASRock X570                | 15        | 0.54%   |
| Dell Wyse                  | 14        | 0.5%    |
| Acer Aspire                | 14        | 0.5%    |
| Protectli FW2B             | 13        | 0.46%   |
| MW GMLK-2                  | 13        | 0.46%   |
| Lenovo IdeaPad             | 12        | 0.43%   |
| Dell XPS                   | 12        | 0.43%   |
| CompuLab fitlet2           | 12        | 0.43%   |
| Supermicro A1SAi           | 11        | 0.39%   |
| Deciso Netboard            | 11        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 372       | 13.3%   |
| 2019    | 276       | 9.87%   |
| 2020    | 247       | 8.83%   |
| 2022    | 240       | 8.58%   |
| 2021    | 227       | 8.12%   |
| 2016    | 197       | 7.05%   |
| 2014    | 187       | 6.69%   |
| 2013    | 169       | 6.04%   |
| 2011    | 162       | 5.79%   |
| 2015    | 154       | 5.51%   |
| 2017    | 147       | 5.26%   |
| 2012    | 140       | 5.01%   |
| 2010    | 70        | 2.5%    |
| 2009    | 46        | 1.65%   |
| 2008    | 41        | 1.47%   |
| 2023    | 38        | 1.36%   |
| Unknown | 38        | 1.36%   |
| 2007    | 22        | 0.79%   |
| 2006    | 15        | 0.54%   |
| 2004    | 4         | 0.14%   |
| 2005    | 1         | 0.04%   |
| 2003    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1769      | 63.27%  |
| Notebook       | 477       | 17.06%  |
| Server         | 286       | 10.23%  |
| Mini pc        | 197       | 7.05%   |
| Firewall       | 28        | 1%      |
| Convertible    | 19        | 0.68%   |
| System on chip | 13        | 0.46%   |
| All in one     | 7         | 0.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2686      | 96.07%  |
| Yes  | 110       | 3.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 1032      | 35.93%  |
| 16.01-24.0      | 697       | 24.27%  |
| 4.01-8.0        | 447       | 15.56%  |
| 32.01-64.0      | 351       | 12.22%  |
| 64.01-256.0     | 167       | 5.81%   |
| 2.01-3.0        | 60        | 2.09%   |
| 24.01-32.0      | 58        | 2.02%   |
| 3.01-4.0        | 30        | 1.04%   |
| 0.51-1.0        | 13        | 0.45%   |
| 1.01-2.0        | 9         | 0.31%   |
| 0.01-0.5        | 5         | 0.17%   |
| More than 256.0 | 3         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1284      | 43.87%  |
| 0.51-1.0    | 897       | 30.65%  |
| 1.01-2.0    | 427       | 14.59%  |
| 2.01-3.0    | 85        | 2.9%    |
| 4.01-8.0    | 70        | 2.39%   |
| 3.01-4.0    | 48        | 1.64%   |
| 8.01-16.0   | 38        | 1.3%    |
| 24.01-32.0  | 18        | 0.61%   |
| 16.01-24.0  | 18        | 0.61%   |
| 32.01-64.0  | 13        | 0.44%   |
| Unknown     | 12        | 0.41%   |
| 0           | 11        | 0.38%   |
| 64.01-256.0 | 6         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1979      | 68.45%  |
| 2      | 383       | 13.25%  |
| 0      | 256       | 8.86%   |
| 3      | 106       | 3.67%   |
| 4      | 45        | 1.56%   |
| 5      | 32        | 1.11%   |
| 6      | 23        | 0.8%    |
| 7      | 12        | 0.42%   |
| 14     | 8         | 0.28%   |
| 8      | 8         | 0.28%   |
| 10     | 7         | 0.24%   |
| 12     | 6         | 0.21%   |
| 9      | 6         | 0.21%   |
| 11     | 4         | 0.14%   |
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
| No        | 2214      | 78.32%  |
| Yes       | 613       | 21.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2685      | 96.03%  |
| No        | 111       | 3.97%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1868      | 66.15%  |
| Yes       | 956       | 33.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2155      | 76.45%  |
| Yes       | 664       | 23.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 2796      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Seattle        | 50        | 1.62%   |
| Brooklyn       | 46        | 1.49%   |
| Chicago        | 42        | 1.36%   |
| Denver         | 41        | 1.33%   |
| New York       | 40        | 1.29%   |
| Los Angeles    | 34        | 1.1%    |
| Portland       | 32        | 1.03%   |
| Dallas         | 30        | 0.97%   |
| Austin         | 28        | 0.91%   |
| San Francisco  | 22        | 0.71%   |
| Rochester      | 22        | 0.71%   |
| Columbus       | 22        | 0.71%   |
| Phoenix        | 21        | 0.68%   |
| Atlanta        | 21        | 0.68%   |
| Oakland        | 18        | 0.58%   |
| Springfield    | 17        | 0.55%   |
| Mountain View  | 17        | 0.55%   |
| Houston        | 16        | 0.52%   |
| Grand Rapids   | 16        | 0.52%   |
| San Jose       | 14        | 0.45%   |
| Omaha          | 14        | 0.45%   |
| Ypsilanti      | 13        | 0.42%   |
| Minneapolis    | 13        | 0.42%   |
| San Antonio    | 12        | 0.39%   |
| Salem          | 12        | 0.39%   |
| Philadelphia   | 12        | 0.39%   |
| Milwaukee      | 12        | 0.39%   |
| Las Vegas      | 12        | 0.39%   |
| Charlotte      | 12        | 0.39%   |
| Washington     | 11        | 0.36%   |
| Pittsburgh     | 11        | 0.36%   |
| Kansas City    | 11        | 0.36%   |
| Indianapolis   | 11        | 0.36%   |
| Fremont        | 11        | 0.36%   |
| Vienna         | 10        | 0.32%   |
| Salt Lake City | 10        | 0.32%   |
| Saint Paul     | 10        | 0.32%   |
| Raleigh        | 10        | 0.32%   |
| Orlando        | 10        | 0.32%   |
| Oklahoma City  | 10        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 533       | 1013   | 16.2%   |
| WDC                 | 409       | 1195   | 12.43%  |
| Seagate             | 295       | 790    | 8.97%   |
| Kingston            | 226       | 300    | 6.87%   |
| Crucial             | 157       | 245    | 4.77%   |
| SanDisk             | 150       | 191    | 4.56%   |
| Intel               | 144       | 274    | 4.38%   |
| Toshiba             | 112       | 201    | 3.4%    |
| Transcend           | 109       | 202    | 3.31%   |
| SK hynix            | 70        | 93     | 2.13%   |
| Hoodisk             | 68        | 92     | 2.07%   |
| Hitachi             | 68        | 162    | 2.07%   |
| A-DATA Technology   | 65        | 105    | 1.98%   |
| China               | 63        | 95     | 1.91%   |
| Protectli           | 59        | 93     | 1.79%   |
| PNY                 | 59        | 82     | 1.79%   |
| Phison              | 59        | 97     | 1.79%   |
| SPCC                | 45        | 85     | 1.37%   |
| HGST                | 40        | 125    | 1.22%   |
| Micron Technology   | 37        | 48     | 1.12%   |
| Hewlett-Packard     | 36        | 111    | 1.09%   |
| Dogfish             | 30        | 52     | 0.91%   |
| NVMe                | 25        | 33     | 0.76%   |
| BIWIN               | 25        | 40     | 0.76%   |
| FORESEE             | 23        | 33     | 0.7%    |
| OCZ                 | 21        | 32     | 0.64%   |
| Apple               | 21        | 25     | 0.64%   |
| Team                | 20        | 34     | 0.61%   |
| Apacer              | 17        | 21     | 0.52%   |
| KingSpec            | 15        | 19     | 0.46%   |
| Corsair             | 15        | 38     | 0.46%   |
| Mushkin             | 14        | 21     | 0.43%   |
| KIOXIA              | 13        | 19     | 0.4%    |
| Patriot             | 12        | 15     | 0.36%   |
| Silicon Motion      | 11        | 15     | 0.33%   |
| LITEON              | 11        | 17     | 0.33%   |
| Lexar               | 11        | 18     | 0.33%   |
| Zheino              | 10        | 18     | 0.3%    |
| Supermicro          | 10        | 10     | 0.3%    |
| OWC                 | 9         | 13     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB       | 32        | 0.89%   |
| Kingston SA400S37240G 240GB     | 32        | 0.89%   |
| Hoodisk SSD 32GB                | 28        | 0.77%   |
| Samsung SSD 970 EVO Plus 500GB  | 25        | 0.69%   |
| Kingston SUV500MS240G 240GB     | 24        | 0.66%   |
| Samsung SSD 860 EVO 500GB       | 23        | 0.64%   |
| Seagate ST500DM002-1BD142 496GB | 22        | 0.61%   |
| Kingston SA400S37120G 120GB     | 22        | 0.61%   |
| Kingston SUV500MS120G 120GB     | 21        | 0.58%   |
| Samsung SSD 860 EVO 1TB         | 20        | 0.55%   |
| PNY CS900 120GB SSD             | 20        | 0.55%   |
| Samsung SSD 850 EVO 500GB       | 19        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB    | 18        | 0.5%    |
| Samsung SSD 860 EVO 250GB       | 18        | 0.5%    |
| Protectli 120GB mSATA           | 18        | 0.5%    |
| BIWIN SSD 128GB                 | 18        | 0.5%    |
| Hoodisk SSD 128GB               | 17        | 0.47%   |
| Hoodisk SSD 64GB                | 16        | 0.44%   |
| Crucial CT500MX500SSD1 500GB    | 16        | 0.44%   |
| WDC WD800JD-75MSA3 80GB         | 15        | 0.42%   |
| Crucial CT250MX500SSD1 250GB    | 15        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB     | 15        | 0.42%   |
| SanDisk SSD PLUS 240GB          | 14        | 0.39%   |
| Samsung SSD 870 EVO 500GB       | 14        | 0.39%   |
| Phison Sabrent 512GB            | 14        | 0.39%   |
| Kingston SV300S37A120G 120GB    | 14        | 0.39%   |
| FORESEE 128GB SSD               | 14        | 0.39%   |
| Transcend TS256GMTS952T2 256GB  | 13        | 0.36%   |
| Samsung SSD 860 EVO M.2 250GB   | 13        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB        | 12        | 0.33%   |
| SPCC Solid State Disk 128GB     | 12        | 0.33%   |
| SanDisk SDSSDA120G 120GB        | 12        | 0.33%   |
| China SATA SSD 120GB            | 12        | 0.33%   |
| WDC WDS500G3X0C-00SJG0 500GB    | 11        | 0.3%    |
| WDC WD30EFRX-68EUZN0 3TB        | 11        | 0.3%    |
| Toshiba DT01ACA100 1TB          | 11        | 0.3%    |
| SanDisk SDSA6MM-016G-1006 16GB  | 11        | 0.3%    |
| Protectli 240GB mSATA           | 11        | 0.3%    |
| HP RAID 0 599GB                 | 11        | 0.3%    |
| Dogfish SSD 128GB               | 11        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 301       | 1002   | 34.4%   |
| Seagate                            | 282       | 759    | 32.23%  |
| Toshiba                            | 90        | 172    | 10.29%  |
| Hitachi                            | 67        | 161    | 7.66%   |
| HGST                               | 40        | 121    | 4.57%   |
| Hewlett-Packard                    | 23        | 74     | 2.63%   |
| NVMe                               | 16        | 20     | 1.83%   |
| Samsung Electronics                | 12        | 17     | 1.37%   |
| Apple                              | 9         | 10     | 1.03%   |
| Maxtor                             | 4         | 8      | 0.46%   |
| Fujitsu                            | 4         | 4      | 0.46%   |
| Lexar                              | 3         | 3      | 0.34%   |
| LSI                                | 2         | 7      | 0.23%   |
| HPE                                | 2         | 7      | 0.23%   |
| Adaptec                            | 2         | 2      | 0.23%   |
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
| Samsung Electronics | 347       | 677    | 18.33%  |
| Kingston            | 202       | 275    | 10.67%  |
| SanDisk             | 148       | 186    | 7.82%   |
| Crucial             | 131       | 202    | 6.92%   |
| Intel               | 106       | 219    | 5.6%    |
| Transcend           | 104       | 196    | 5.49%   |
| Hoodisk             | 67        | 91     | 3.54%   |
| China               | 62        | 94     | 3.28%   |
| Protectli           | 59        | 93     | 3.12%   |
| PNY                 | 55        | 78     | 2.91%   |
| A-DATA Technology   | 55        | 85     | 2.91%   |
| WDC                 | 47        | 85     | 2.48%   |
| SK hynix            | 39        | 53     | 2.06%   |
| SPCC                | 33        | 68     | 1.74%   |
| Dogfish             | 30        | 52     | 1.58%   |
| Phison              | 28        | 38     | 1.48%   |
| BIWIN               | 25        | 40     | 1.32%   |
| Micron Technology   | 24        | 30     | 1.27%   |
| FORESEE             | 23        | 33     | 1.22%   |
| OCZ                 | 21        | 32     | 1.11%   |
| Apacer              | 17        | 21     | 0.9%    |
| KingSpec            | 15        | 19     | 0.79%   |
| Team                | 12        | 25     | 0.63%   |
| Seagate             | 12        | 24     | 0.63%   |
| Corsair             | 12        | 17     | 0.63%   |
| Apple               | 12        | 15     | 0.63%   |
| Mushkin             | 11        | 17     | 0.58%   |
| Zheino              | 10        | 18     | 0.53%   |
| Toshiba             | 10        | 13     | 0.53%   |
| Supermicro          | 10        | 10     | 0.53%   |
| Patriot             | 10        | 13     | 0.53%   |
| OWC                 | 9         | 13     | 0.48%   |
| NVMe                | 9         | 11     | 0.48%   |
| LITEON              | 9         | 15     | 0.48%   |
| Innodisk            | 8         | 10     | 0.42%   |
| Plextor             | 7         | 12     | 0.37%   |
| LITEONIT            | 7         | 10     | 0.37%   |
| Lexar               | 7         | 14     | 0.37%   |
| Intenso             | 6         | 12     | 0.32%   |
| Hewlett-Packard     | 6         | 10     | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1706      | 3053   | 57.73%  |
| HDD  | 724       | 2401   | 24.5%   |
| NVMe | 525       | 882    | 17.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2208      | 5454   | 80.79%  |
| NVMe | 525       | 882    | 19.21%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1832      | 3195   | 71.73%  |
| 0.51-1.0   | 399       | 802    | 15.62%  |
| 1.01-2.0   | 135       | 370    | 5.29%   |
| 4.01-10.0  | 64        | 514    | 2.51%   |
| 2.01-3.0   | 53        | 213    | 2.08%   |
| 3.01-4.0   | 51        | 216    | 2%      |
| 10.01-20.0 | 19        | 140    | 0.74%   |
| 20.01-50.0 | 1         | 4      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1149      | 39.51%  |
| 251-500        | 537       | 18.47%  |
| 1-20           | 295       | 10.14%  |
| 51-100         | 284       | 9.77%   |
| 501-1000       | 276       | 9.49%   |
| 21-50          | 257       | 8.84%   |
| 1001-2000      | 65        | 2.24%   |
| More than 3000 | 24        | 0.83%   |
| Unknown        | 13        | 0.45%   |
| 2001-3000      | 8         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2603      | 90.04%  |
| 21-50          | 158       | 5.47%   |
| 51-100         | 60        | 2.08%   |
| 101-250        | 31        | 1.07%   |
| 251-500        | 13        | 0.45%   |
| Unknown        | 13        | 0.45%   |
| More than 3000 | 5         | 0.17%   |
| 501-1000       | 4         | 0.14%   |
| 2001-3000      | 2         | 0.07%   |
| 1001-2000      | 1         | 0.03%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 496GB       | 8         | 12     | 2.11%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.32%   |
| Apacer 16GB SATA Flash Drive          | 5         | 8      | 1.32%   |
| Kingston SV300S37A60G 64GB            | 4         | 4      | 1.05%   |
| Kingston SV300S37A120G 120GB          | 4         | 4      | 1.05%   |
| Kingston SMS200S3120G 120GB           | 4         | 4      | 1.05%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 7      | 1.05%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3         | 3      | 0.79%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3         | 15     | 0.79%   |
| SK hynix SC210 mSATA 256GB            | 3         | 4      | 0.79%   |
| Seagate ST3500418AS 500GB             | 3         | 10     | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 3      | 0.79%   |
| SanDisk SSD PLUS 240GB                | 3         | 4      | 0.79%   |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 0.79%   |
| WDC WD2001FASS-00W2B0 2TB             | 2         | 3      | 0.53%   |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.53%   |
| WDC WD1600AAJS-75M0A0 160GB           | 2         | 2      | 0.53%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.53%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.53%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.53%   |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.53%   |
| SK hynix SC308 SATA 128GB             | 2         | 3      | 0.53%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.53%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 3      | 0.53%   |
| Seagate ST3500413AS 500GB             | 2         | 10     | 0.53%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.53%   |
| Seagate ST2000DL001-9VT156 2TB        | 2         | 2      | 0.53%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 6      | 0.53%   |
| Samsung Electronics SSD 950 PRO 256GB | 2         | 2      | 0.53%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.53%   |
| MyDigitalSSD SB2 256GB                | 2         | 4      | 0.53%   |
| Kingston SUV400S37120G 120GB          | 2         | 3      | 0.53%   |
| Kingston SNS4151S316GD 16GB           | 2         | 4      | 0.53%   |
| Kingston SNS4151S316G 16GB            | 2         | 3      | 0.53%   |
| Kingston SMS200S360G 64GB             | 2         | 2      | 0.53%   |
| Intel SSDSC2BX200G4R 200GB            | 2         | 3      | 0.53%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.53%   |
| Hitachi HUA722020ALA331 2TB           | 2         | 4      | 0.53%   |
| Hitachi HUA722020ALA330 2TB           | 2         | 4      | 0.53%   |
| Hitachi HTS725032A9A364 320GB         | 2         | 2      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 137    | 21.47%  |
| WDC                 | 54        | 105    | 14.67%  |
| Kingston            | 28        | 32     | 7.61%   |
| Intel               | 28        | 35     | 7.61%   |
| Samsung Electronics | 24        | 35     | 6.52%   |
| Hitachi             | 23        | 30     | 6.25%   |
| Toshiba             | 21        | 30     | 5.71%   |
| Crucial             | 17        | 23     | 4.62%   |
| SanDisk             | 12        | 15     | 3.26%   |
| HGST                | 10        | 10     | 2.72%   |
| SK hynix            | 9         | 12     | 2.45%   |
| Apacer              | 8         | 11     | 2.17%   |
| OCZ                 | 4         | 4      | 1.09%   |
| Micron Technology   | 4         | 5      | 1.09%   |
| Phison              | 3         | 3      | 0.82%   |
| LITEON              | 3         | 4      | 0.82%   |
| HP Phison           | 3         | 3      | 0.82%   |
| Apple               | 3         | 3      | 0.82%   |
| SSSTC               | 2         | 2      | 0.54%   |
| SPCC                | 2         | 4      | 0.54%   |
| PNY                 | 2         | 2      | 0.54%   |
| Patriot             | 2         | 2      | 0.54%   |
| MyDigitalSSD        | 2         | 4      | 0.54%   |
| Maxtor              | 2         | 5      | 0.54%   |
| Corsair             | 2         | 2      | 0.54%   |
| A-DATA Technology   | 2         | 2      | 0.54%   |
| ZTC                 | 1         | 3      | 0.27%   |
| Wintec              | 1         | 1      | 0.27%   |
| WD MediaMax         | 1         | 3      | 0.27%   |
| VisionTek           | 1         | 1      | 0.27%   |
| Transcend           | 1         | 4      | 0.27%   |
| LITEONIT            | 1         | 3      | 0.27%   |
| KingSpec            | 1         | 1      | 0.27%   |
| KingDian            | 1         | 1      | 0.27%   |
| KeepData            | 1         | 1      | 0.27%   |
| INDMEM              | 1         | 1      | 0.27%   |
| IBM/Hitachi         | 1         | 1      | 0.27%   |
| HPE                 | 1         | 3      | 0.27%   |
| Hewlett-Packard     | 1         | 4      | 0.27%   |
| Fujitsu             | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 79        | 137    | 39.5%   |
| WDC                  | 53        | 104    | 26.5%   |
| Hitachi              | 23        | 30     | 11.5%   |
| Toshiba              | 19        | 28     | 9.5%    |
| HGST                 | 10        | 10     | 5%      |
| Samsung Electronics  | 5         | 6      | 2.5%    |
| Maxtor               | 2         | 5      | 1%      |
| Apple                | 2         | 2      | 1%      |
| WD MediaMax          | 1         | 3      | 0.5%    |
| IBM/Hitachi          | 1         | 1      | 0.5%    |
| HPE                  | 1         | 3      | 0.5%    |
| Hewlett-Packard      | 1         | 4      | 0.5%    |
| Fujitsu              | 1         | 1      | 0.5%    |
| ExcelStor Technology | 1         | 2      | 0.5%    |
| China                | 1         | 1      | 0.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 191       | 337    | 53.35%  |
| SSD  | 164       | 218    | 45.81%  |
| NVMe | 3         | 3      | 0.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 22.22%  |
| WDC WD3200L 320GB                            | 1         | 1      | 11.11%  |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 11.11%  |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 11.11%  |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 11.11%  |
| Samsung Electronics PM981 NVMe 256GB         | 1         | 1      | 11.11%  |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 11.11%  |
| Kingston SA2000M8500G 500GB                  | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 55.56%  |
| WDC                 | 1         | 1      | 11.11%  |
| SK hynix            | 1         | 1      | 11.11%  |
| Seagate             | 1         | 2      | 11.11%  |
| Kingston            | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2299      | 5608   | 83.84%  |
| Malfunc  | 351       | 558    | 12.8%   |
| Detected | 83        | 159    | 3.03%   |
| Failed   | 9         | 11     | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2171      | 61.48%  |
| AMD                                     | 443       | 12.55%  |
| Samsung Electronics                     | 218       | 6.17%   |
| Broadcom / LSI                          | 129       | 3.65%   |
| SanDisk                                 | 105       | 2.97%   |
| Phison Electronics                      | 55        | 1.56%   |
| ASMedia Technology                      | 52        | 1.47%   |
| Silicon Motion                          | 38        | 1.08%   |
| Marvell Technology Group                | 36        | 1.02%   |
| SK hynix                                | 33        | 0.93%   |
| Micron/Crucial Technology               | 24        | 0.68%   |
| Kingston Technology Company             | 24        | 0.68%   |
| Chelsio Communications                  | 22        | 0.62%   |
| Hewlett-Packard                         | 19        | 0.54%   |
| MAXIO Technology (Hangzhou)             | 16        | 0.45%   |
| Micron Technology                       | 15        | 0.42%   |
| JMicron Technology                      | 15        | 0.42%   |
| Nvidia                                  | 14        | 0.4%    |
| KIOXIA                                  | 14        | 0.4%    |
| Toshiba                                 | 11        | 0.31%   |
| Adaptec                                 | 10        | 0.28%   |
| ADATA Technology                        | 8         | 0.23%   |
| Silicon Image                           | 6         | 0.17%   |
| Seagate Technology                      | 6         | 0.17%   |
| Realtek Semiconductor                   | 6         | 0.17%   |
| Transcend                               | 5         | 0.14%   |
| Shenzhen Longsys Electronics            | 4         | 0.11%   |
| VIA Technologies                        | 3         | 0.08%   |
| Solid State Storage Technology          | 3         | 0.08%   |
| Lite-On Technology                      | 3         | 0.08%   |
| Union Memory (Shenzhen)                 | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.06%   |
| Shenzhen Unionmemory Information System | 2         | 0.06%   |
| Netac Technology                        | 2         | 0.06%   |
| Lenovo                                  | 2         | 0.06%   |
| HighPoint Technologies                  | 2         | 0.06%   |
| Dell                                    | 2         | 0.06%   |
| Broadcom                                | 2         | 0.06%   |
| Biwin Storage Technology                | 2         | 0.06%   |
| Innodisk                                | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 309       | 7.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 232       | 5.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 160       | 3.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 140       | 3.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 124       | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 116       | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 113       | 2.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 110       | 2.73%   |
| Intel SATA Controller [RAID mode]                                                | 80        | 1.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 77        | 1.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 77        | 1.91%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 63        | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 62        | 1.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 58        | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 57        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 55        | 1.37%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 46        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 46        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 45        | 1.12%   |
| AMD 400 Series Chipset SATA Controller                                           | 45        | 1.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 44        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 41        | 1.02%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 40        | 0.99%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 40        | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 37        | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 37        | 0.92%   |
| AMD FCH IDE Controller                                                           | 37        | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 36        | 0.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 36        | 0.9%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 35        | 0.87%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 35        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                           | 34        | 0.85%   |
| Samsung NVMe SSD Controller 980                                                  | 33        | 0.82%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 31        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 31        | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 31        | 0.77%   |
| Phison E12 NVMe Controller                                                       | 30        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 30        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 26        | 0.65%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 25        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2309      | 64.95%  |
| NVMe | 586       | 16.48%  |
| IDE  | 325       | 9.14%   |
| RAID | 217       | 6.1%    |
| SAS  | 77        | 2.17%   |
| SCSI | 41        | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2291      | 81.76%  |
| AMD      | 482       | 17.2%   |
| ARM      | 19        | 0.68%   |
| Unknown  | 5         | 0.18%   |
| IBM      | 2         | 0.07%   |
| NXP      | 1         | 0.04%   |
| Motorola | 1         | 0.04%   |
| i        | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron J4125 CPU @ 2.00GHz        | 82        | 2.88%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 76        | 2.67%   |
| Intel Celeron N5105 @ 2.00GHz            | 60        | 2.11%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 44        | 1.55%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 39        | 1.37%   |
| AMD GX-412TC SOC                         | 34        | 1.19%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 33        | 1.16%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 28        | 0.98%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 27        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 26        | 0.91%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 26        | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 25        | 0.88%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 25        | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 22        | 0.77%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 22        | 0.77%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 20        | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz        | 19        | 0.67%   |
| Intel Atom CPU D525 @ 1.80GHz            | 19        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 18        | 0.63%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 17        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 17        | 0.6%    |
| Intel Core i5-7500 CPU @ 3.40GHz         | 16        | 0.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 16        | 0.56%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 16        | 0.56%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 16        | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 15        | 0.53%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 14        | 0.49%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 14        | 0.49%   |
| Intel Core 2 Duo                         | 14        | 0.49%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 14        | 0.49%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 13        | 0.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 13        | 0.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 13        | 0.46%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 13        | 0.46%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 13        | 0.46%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 12        | 0.42%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 12        | 0.42%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 12        | 0.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 12        | 0.42%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 12        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 553       | 19.56%  |
| Intel Celeron           | 438       | 15.49%  |
| Intel Xeon              | 385       | 13.62%  |
| Intel Core i7           | 325       | 11.5%   |
| Intel Core i3           | 179       | 6.33%   |
| Intel Atom              | 137       | 4.85%   |
| Other                   | 126       | 4.46%   |
| AMD Ryzen 7             | 81        | 2.87%   |
| AMD GX                  | 72        | 2.55%   |
| Intel Pentium           | 65        | 2.3%    |
| AMD Ryzen 5             | 59        | 2.09%   |
| Intel Core 2 Duo        | 50        | 1.77%   |
| Intel Pentium Silver    | 28        | 0.99%   |
| AMD Ryzen 9             | 26        | 0.92%   |
| AMD FX                  | 23        | 0.81%   |
| AMD EPYC                | 22        | 0.78%   |
| AMD Ryzen 3             | 21        | 0.74%   |
| AMD A10                 | 19        | 0.67%   |
| ARM Cortex              | 18        | 0.64%   |
| Intel Core i9           | 12        | 0.42%   |
| Intel Core 2 Quad       | 12        | 0.42%   |
| AMD Ryzen 5 PRO         | 11        | 0.39%   |
| Intel Core 2            | 10        | 0.35%   |
| AMD Phenom II X4        | 10        | 0.35%   |
| AMD G                   | 10        | 0.35%   |
| AMD Athlon              | 10        | 0.35%   |
| AMD Ryzen Embedded      | 8         | 0.28%   |
| AMD A8                  | 8         | 0.28%   |
| AMD A6                  | 8         | 0.28%   |
| Intel Genuine           | 7         | 0.25%   |
| Intel Pentium 4         | 6         | 0.21%   |
| AMD Opteron             | 6         | 0.21%   |
| Intel Pentium Dual-Core | 5         | 0.18%   |
| AMD Ryzen Threadripper  | 5         | 0.18%   |
| AMD A4                  | 5         | 0.18%   |
| AMD Ryzen 7 PRO         | 4         | 0.14%   |
| AMD Phenom II X6        | 4         | 0.14%   |
| AMD E2                  | 4         | 0.14%   |
| AMD E1                  | 4         | 0.14%   |
| AMD E                   | 4         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1454      | 51.4%   |
| 2       | 680       | 24.04%  |
| 8       | 189       | 6.68%   |
| 6       | 136       | 4.81%   |
| 16      | 99        | 3.5%    |
| Unknown | 99        | 3.5%    |
| 12      | 88        | 3.11%   |
| 1       | 23        | 0.81%   |
| 24      | 18        | 0.64%   |
| 32      | 12        | 0.42%   |
| 10      | 9         | 0.32%   |
| 20      | 7         | 0.25%   |
| 48      | 3         | 0.11%   |
| 14      | 3         | 0.11%   |
| 64      | 2         | 0.07%   |
| 36      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 3       | 2         | 0.07%   |
| 40      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2645      | 94.4%   |
| 2       | 116       | 4.14%   |
| Unknown | 39        | 1.39%   |
| 8       | 1         | 0.04%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1548      | 54.97%  |
| 2       | 1158      | 41.12%  |
| Unknown | 109       | 3.87%   |
| 4       | 1         | 0.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 369       | 13.05%  |
| Haswell         | 320       | 11.32%  |
| Silvermont      | 257       | 9.09%   |
| IvyBridge       | 199       | 7.04%   |
| Skylake         | 181       | 6.4%    |
| SandyBridge     | 174       | 6.15%   |
| Unknown         | 172       | 6.08%   |
| Goldmont plus   | 129       | 4.56%   |
| Broadwell       | 114       | 4.03%   |
| Westmere        | 70        | 2.48%   |
| Goldmont        | 70        | 2.48%   |
| Zen+            | 63        | 2.23%   |
| Zen 2           | 63        | 2.23%   |
| Zen             | 57        | 2.02%   |
| Penryn          | 57        | 2.02%   |
| Zen 3           | 53        | 1.87%   |
| Bonnell         | 48        | 1.7%    |
| Nehalem         | 46        | 1.63%   |
| Core            | 45        | 1.59%   |
| Jaguar          | 44        | 1.56%   |
| CometLake       | 44        | 1.56%   |
| Puma            | 43        | 1.52%   |
| Steamroller     | 37        | 1.31%   |
| Piledriver      | 37        | 1.31%   |
| TigerLake       | 29        | 1.03%   |
| K10             | 24        | 0.85%   |
| Bobcat          | 22        | 0.78%   |
| Excavator       | 18        | 0.64%   |
| NetBurst        | 16        | 0.57%   |
| K8 Hammer       | 10        | 0.35%   |
| P6              | 5         | 0.18%   |
| K10 Llano       | 4         | 0.14%   |
| IceLake         | 4         | 0.14%   |
| Bulldozer       | 2         | 0.07%   |
| K8 & K10 hybrid | 1         | 0.04%   |
| Geode           | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1689      | 60.17%  |
| AMD                                          | 447       | 15.92%  |
| Nvidia                                       | 283       | 10.08%  |
| ASPEED Technology                            | 196       | 6.98%   |
| Matrox Electronics Systems                   | 186       | 6.63%   |
| XGI Technology (eXtreme Graphics Innovation) | 4         | 0.14%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 196       | 6.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 141       | 4.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 123       | 4.3%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 113       | 3.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 113       | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 109       | 3.81%   |
| Intel HD Graphics 530                                                                    | 99        | 3.46%   |
| Intel HD Graphics 620                                                                    | 77        | 2.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 76        | 2.66%   |
| Intel JasperLake [UHD Graphics]                                                          | 75        | 2.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 74        | 2.59%   |
| Intel UHD Graphics 620                                                                   | 54        | 1.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 54        | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 1.61%   |
| Intel HD Graphics 630                                                                    | 45        | 1.57%   |
| Matrox Electronics Systems G200eR2                                                       | 44        | 1.54%   |
| Intel HD Graphics 500                                                                    | 41        | 1.43%   |
| Intel HD Graphics 5500                                                                   | 39        | 1.36%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 36        | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 33        | 1.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 28        | 0.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 0.91%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 26        | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 26        | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 25        | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 25        | 0.87%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 25        | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 0.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 0.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 0.77%   |
| Intel HD Graphics 610                                                                    | 21        | 0.73%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 21        | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 0.7%    |
| AMD Renoir                                                                               | 20        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 0.63%   |
| AMD ES1000                                                                               | 18        | 0.63%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 16        | 0.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 0.52%   |
| Intel HD Graphics 6000                                                                   | 14        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1531      | 54.21%  |
| 1 x AMD         | 402       | 14.24%  |
| 1 x Nvidia      | 202       | 7.15%   |
| 1 x Matrox      | 184       | 6.52%   |
| 1 x ASPEED      | 183       | 6.48%   |
| Other           | 125       | 4.43%   |
| 2 x Intel       | 65        | 2.3%    |
| Intel + Nvidia  | 65        | 2.3%    |
| Intel + AMD     | 22        | 0.78%   |
| AMD + Nvidia    | 11        | 0.39%   |
| 2 x AMD         | 10        | 0.35%   |
| Intel + ASPEED  | 8         | 0.28%   |
| 1 x XGI         | 4         | 0.14%   |
| Nvidia + ASPEED | 4         | 0.14%   |
| 2 x Nvidia      | 3         | 0.11%   |
| 1 x SiS         | 2         | 0.07%   |
| AMD + ASPEED    | 2         | 0.07%   |
| AMD + Matrox    | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2511      | 89.3%   |
| Unknown     | 157       | 5.58%   |
| Proprietary | 144       | 5.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2572      | 91.11%  |
| 1.01-2.0   | 64        | 2.27%   |
| 0.01-0.5   | 55        | 1.95%   |
| 3.01-4.0   | 40        | 1.42%   |
| 0.51-1.0   | 30        | 1.06%   |
| 7.01-8.0   | 29        | 1.03%   |
| 5.01-6.0   | 19        | 0.67%   |
| 8.01-16.0  | 9         | 0.32%   |
| 2.01-3.0   | 4         | 0.14%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 67        | 10.52%  |
| LG Display              | 65        | 10.2%   |
| AU Optronics            | 63        | 9.89%   |
| Dell                    | 59        | 9.26%   |
| BOE                     | 48        | 7.54%   |
| Chimei Innolux          | 38        | 5.97%   |
| Goldstar                | 35        | 5.49%   |
| Acer                    | 33        | 5.18%   |
| Lenovo                  | 30        | 4.71%   |
| Hewlett-Packard         | 26        | 4.08%   |
| Apple                   | 22        | 3.45%   |
| Ancor Communications    | 22        | 3.45%   |
| ASUSTek Computer        | 10        | 1.57%   |
| Vizio                   | 9         | 1.41%   |
| Sharp                   | 9         | 1.41%   |
| AOC                     | 9         | 1.41%   |
| ViewSonic               | 8         | 1.26%   |
| Sceptre Tech            | 8         | 1.26%   |
| LG Electronics          | 7         | 1.1%    |
| Chi Mei Optoelectronics | 7         | 1.1%    |
| BenQ                    | 7         | 1.1%    |
| InfoVision              | 4         | 0.63%   |
| Sony                    | 3         | 0.47%   |
| Philips                 | 3         | 0.47%   |
| MSI                     | 3         | 0.47%   |
| LGD                     | 3         | 0.47%   |
| Lenovo Group Limited    | 3         | 0.47%   |
| Insignia                | 3         | 0.47%   |
| HannStar                | 3         | 0.47%   |
| Westinghouse            | 2         | 0.31%   |
| NEC Computers           | 2         | 0.31%   |
| LG Philips              | 2         | 0.31%   |
| IBM                     | 2         | 0.31%   |
| Unknown                 | 2         | 0.31%   |
| unknown                 | 1         | 0.16%   |
| Toshiba                 | 1         | 0.16%   |
| Tech Concepts           | 1         | 0.16%   |
| SHI                     | 1         | 0.16%   |
| SGT                     | 1         | 0.16%   |
| Seiko/Epson             | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                 | 7         | 1.06%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 6         | 0.91%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 5         | 0.76%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch        | 4         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 4         | 0.61%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 4         | 0.61%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 4         | 0.61%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 3         | 0.46%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 3         | 0.46%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 3         | 0.46%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 3         | 0.46%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch               | 3         | 0.46%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 3         | 0.46%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                     | 3         | 0.46%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                     | 3         | 0.46%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                 | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch      | 3         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch       | 3         | 0.46%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                  | 3         | 0.46%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch         | 3         | 0.46%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 3         | 0.46%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 3         | 0.46%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                     | 3         | 0.46%   |
| Sony TV SNY9C01 1360x768                                              | 2         | 0.3%    |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch        | 2         | 0.3%    |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch     | 2         | 0.3%    |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch   | 2         | 0.3%    |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch | 2         | 0.3%    |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch          | 2         | 0.3%    |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch           | 2         | 0.3%    |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 207       | 32.96%  |
| 1366x768 (WXGA)    | 124       | 19.75%  |
| 3840x2160 (4K)     | 42        | 6.69%   |
| 2560x1440 (QHD)    | 42        | 6.69%   |
| 1600x900 (HD+)     | 34        | 5.41%   |
| 1280x800 (WXGA)    | 26        | 4.14%   |
| 1920x1200 (WUXGA)  | 20        | 3.18%   |
| 1280x1024 (SXGA)   | 19        | 3.03%   |
| 1680x1050 (WSXGA+) | 17        | 2.71%   |
| 2560x1080          | 13        | 2.07%   |
| 3440x1440          | 12        | 1.91%   |
| 1440x900 (WXGA+)   | 12        | 1.91%   |
| 1360x768           | 8         | 1.27%   |
| 2256x1504          | 7         | 1.11%   |
| Unknown            | 7         | 1.11%   |
| 2560x1600          | 6         | 0.96%   |
| 1024x768 (XGA)     | 6         | 0.96%   |
| 1024x600           | 5         | 0.8%    |
| 3200x1800 (QHD+)   | 3         | 0.48%   |
| 3840x1600          | 2         | 0.32%   |
| 3840x1080          | 2         | 0.32%   |
| 1600x1200          | 2         | 0.32%   |
| 7040x1440          | 1         | 0.16%   |
| 5760x2160          | 1         | 0.16%   |
| 5760x1080          | 1         | 0.16%   |
| 4640x1080          | 1         | 0.16%   |
| 4480x1080          | 1         | 0.16%   |
| 3520x1080          | 1         | 0.16%   |
| 2880x1620          | 1         | 0.16%   |
| 2806x900           | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1920x1920          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1280x768           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 122       | 19.21%  |
| 13      | 106       | 16.69%  |
| 24      | 56        | 8.82%   |
| 27      | 49        | 7.72%   |
| Unknown | 42        | 6.61%   |
| 31      | 28        | 4.41%   |
| 19      | 26        | 4.09%   |
| 12      | 26        | 4.09%   |
| 17      | 24        | 3.78%   |
| 23      | 22        | 3.46%   |
| 11      | 22        | 3.46%   |
| 21      | 21        | 3.31%   |
| 14      | 20        | 3.15%   |
| 34      | 16        | 2.52%   |
| 22      | 9         | 1.42%   |
| 29      | 7         | 1.1%    |
| 20      | 5         | 0.79%   |
| 18      | 5         | 0.79%   |
| 64      | 4         | 0.63%   |
| 26      | 4         | 0.63%   |
| 42      | 2         | 0.31%   |
| 37      | 2         | 0.31%   |
| 35      | 2         | 0.31%   |
| 16      | 2         | 0.31%   |
| 10      | 2         | 0.31%   |
| 9       | 2         | 0.31%   |
| 54      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 49      | 1         | 0.16%   |
| 41      | 1         | 0.16%   |
| 39      | 1         | 0.16%   |
| 32      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 25      | 1         | 0.16%   |
| 8       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 201       | 32.26%  |
| 501-600     | 118       | 18.94%  |
| 201-300     | 107       | 17.17%  |
| 401-500     | 57        | 9.15%   |
| Unknown     | 42        | 6.74%   |
| 601-700     | 41        | 6.58%   |
| 351-400     | 22        | 3.53%   |
| 701-800     | 17        | 2.73%   |
| 1001-1500   | 7         | 1.12%   |
| 801-900     | 5         | 0.8%    |
| 101-200     | 3         | 0.48%   |
| 901-1000    | 3         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 417       | 70.2%   |
| 16/10   | 72        | 12.12%  |
| Unknown | 37        | 6.23%   |
| 21/9    | 25        | 4.21%   |
| 5/4     | 16        | 2.69%   |
| 3/2     | 12        | 2.02%   |
| 4/3     | 10        | 1.68%   |
| 6/5     | 3         | 0.51%   |
| 32/9    | 1         | 0.17%   |
| 1.00    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 106       | 16.77%  |
| 91-100         | 95        | 15.03%  |
| 201-250        | 88        | 13.92%  |
| 301-350        | 55        | 8.7%    |
| 351-500        | 50        | 7.91%   |
| Unknown        | 42        | 6.65%   |
| 151-200        | 31        | 4.91%   |
| 101-110        | 30        | 4.75%   |
| 61-70          | 27        | 4.27%   |
| 51-60          | 21        | 3.32%   |
| 251-300        | 20        | 3.16%   |
| 141-150        | 15        | 2.37%   |
| 121-130        | 15        | 2.37%   |
| 71-80          | 14        | 2.22%   |
| 501-1000       | 7         | 1.11%   |
| More than 1000 | 6         | 0.95%   |
| 1-40           | 3         | 0.47%   |
| 111-120        | 3         | 0.47%   |
| 41-50          | 2         | 0.32%   |
| 131-140        | 2         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 194       | 31.54%  |
| 121-160       | 166       | 26.99%  |
| 101-120       | 154       | 25.04%  |
| 161-240       | 44        | 7.15%   |
| Unknown       | 42        | 6.83%   |
| More than 240 | 12        | 1.95%   |
| 1-50          | 3         | 0.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2154      | 76.46%  |
| 1     | 590       | 20.94%  |
| 2     | 65        | 2.31%   |
| 3     | 7         | 0.25%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2252      | 57.54%  |
| Realtek Semiconductor           | 830       | 21.21%  |
| Broadcom                        | 285       | 7.28%   |
| Qualcomm Atheros                | 180       | 4.6%    |
| Mellanox Technologies           | 48        | 1.23%   |
| Ralink Technology               | 31        | 0.79%   |
| Chelsio Communications          | 25        | 0.64%   |
| IMC Networks                    | 19        | 0.49%   |
| AMD                             | 18        | 0.46%   |
| Marvell Technology Group        | 17        | 0.43%   |
| U-Blox                          | 16        | 0.41%   |
| Ralink                          | 15        | 0.38%   |
| TP-Link                         | 14        | 0.36%   |
| Edimax Technology               | 13        | 0.33%   |
| Solarflare Communications       | 12        | 0.31%   |
| Aquantia                        | 10        | 0.26%   |
| Google                          | 8         | 0.2%    |
| Novatel Wireless                | 7         | 0.18%   |
| NetGear                         | 7         | 0.18%   |
| MediaTek                        | 7         | 0.18%   |
| D-Link System                   | 7         | 0.18%   |
| Seeed Technology                | 6         | 0.15%   |
| Nvidia                          | 6         | 0.15%   |
| QLogic                          | 5         | 0.13%   |
| Emulex                          | 5         | 0.13%   |
| ASUSTek Computer                | 5         | 0.13%   |
| Apple                           | 5         | 0.13%   |
| Dell                            | 4         | 0.1%    |
| American Megatrends             | 4         | 0.1%    |
| Sierra Wireless                 | 3         | 0.08%   |
| Sequans Communications          | 3         | 0.08%   |
| Cisco Systems                   | 3         | 0.08%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 654       | 12.97%  |
| Intel I211 Gigabit Network Connection                                         | 316       | 6.27%   |
| Intel I210 Gigabit Network Connection                                         | 239       | 4.74%   |
| Intel I350 Gigabit Network Connection                                         | 211       | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 176       | 3.49%   |
| Intel Ethernet Controller I225-V                                              | 148       | 2.93%   |
| Intel 82574L Gigabit Network Connection                                       | 142       | 2.82%   |
| Intel Ethernet Connection I217-LM                                             | 115       | 2.28%   |
| Intel 82580 Gigabit Network Connection                                        | 88        | 1.74%   |
| Intel 82583V Gigabit Network Connection                                       | 85        | 1.69%   |
| Intel Wi-Fi 6 AX200                                                           | 76        | 1.51%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 75        | 1.49%   |
| Intel 82576 Gigabit Network Connection                                        | 74        | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                             | 72        | 1.43%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 72        | 1.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 71        | 1.41%   |
| Intel Ethernet Controller I226-V                                              | 69        | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                                         | 63        | 1.25%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 55        | 1.09%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 51        | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 49        | 0.97%   |
| Intel Wireless 8265 / 8275                                                    | 46        | 0.91%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 45        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 42        | 0.83%   |
| Intel Wireless 7260                                                           | 40        | 0.79%   |
| Intel Wireless 8260                                                           | 38        | 0.75%   |
| Intel Wireless 7265                                                           | 38        | 0.75%   |
| Intel Ethernet Connection I354                                                | 35        | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                         | 34        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                                          | 33        | 0.65%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 33        | 0.65%   |
| Intel Wireless 3165                                                           | 31        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 28        | 0.56%   |
| Intel Ethernet Controller X550                                                | 28        | 0.56%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 27        | 0.54%   |
| Intel Wireless-AC 9260                                                        | 24        | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 23        | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 22        | 0.44%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 22        | 0.44%   |
| Intel Ethernet Connection (7) I219-V                                          | 22        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 551       | 53.6%   |
| Qualcomm Atheros                | 154       | 14.98%  |
| Realtek Semiconductor           | 121       | 11.77%  |
| Broadcom                        | 77        | 7.49%   |
| Ralink Technology               | 31        | 3.02%   |
| IMC Networks                    | 19        | 1.85%   |
| Ralink                          | 15        | 1.46%   |
| TP-Link                         | 14        | 1.36%   |
| Edimax Technology               | 13        | 1.26%   |
| NetGear                         | 7         | 0.68%   |
| MediaTek                        | 7         | 0.68%   |
| ASUSTek Computer                | 5         | 0.49%   |
| Sierra Wireless                 | 2         | 0.19%   |
| Qualcomm Atheros Communications | 2         | 0.19%   |
| D-Link System                   | 2         | 0.19%   |
| D-Link                          | 2         | 0.19%   |
| Belkin Components               | 2         | 0.19%   |
| ZyXEL Communications            | 1         | 0.1%    |
| Marvell Technology Group        | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| AboCom Systems                  | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 76        | 7.31%   |
| Intel Wireless 8265 / 8275                                              | 46        | 4.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 4.04%   |
| Intel Wireless 7260                                                     | 40        | 3.85%   |
| Intel Wireless 8260                                                     | 38        | 3.66%   |
| Intel Wireless 7265                                                     | 38        | 3.66%   |
| Intel Wireless 3165                                                     | 31        | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 2.69%   |
| Intel Wireless-AC 9260                                                  | 24        | 2.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 23        | 2.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 22        | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 22        | 2.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 20        | 1.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.83%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                    | 19        | 1.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 1.54%   |
| Ralink RT5370 Wireless Adapter                                          | 15        | 1.44%   |
| Intel Wireless 3160                                                     | 15        | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 14        | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 13        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.25%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 13        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.06%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 10        | 0.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 10        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 9         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 7         | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2019      | 62.94%  |
| Realtek Semiconductor            | 774       | 24.13%  |
| Broadcom                         | 239       | 7.45%   |
| Qualcomm Atheros                 | 34        | 1.06%   |
| Chelsio Communications           | 22        | 0.69%   |
| AMD                              | 17        | 0.53%   |
| Marvell Technology Group         | 15        | 0.47%   |
| Solarflare Communications        | 12        | 0.37%   |
| Aquantia                         | 9         | 0.28%   |
| Novatel Wireless                 | 7         | 0.22%   |
| Nvidia                           | 6         | 0.19%   |
| QLogic                           | 5         | 0.16%   |
| Emulex                           | 5         | 0.16%   |
| D-Link System                    | 5         | 0.16%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 654       | 16.84%  |
| Intel I211 Gigabit Network Connection                                         | 316       | 8.14%   |
| Intel I210 Gigabit Network Connection                                         | 239       | 6.16%   |
| Intel I350 Gigabit Network Connection                                         | 211       | 5.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 176       | 4.53%   |
| Intel Ethernet Controller I225-V                                              | 148       | 3.81%   |
| Intel 82574L Gigabit Network Connection                                       | 142       | 3.66%   |
| Intel Ethernet Connection I217-LM                                             | 115       | 2.96%   |
| Intel 82580 Gigabit Network Connection                                        | 88        | 2.27%   |
| Intel 82583V Gigabit Network Connection                                       | 85        | 2.19%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 75        | 1.93%   |
| Intel 82576 Gigabit Network Connection                                        | 74        | 1.91%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 72        | 1.85%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 71        | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                             | 70        | 1.8%    |
| Intel Ethernet Controller I226-V                                              | 69        | 1.78%   |
| Intel Ethernet Connection (2) I219-LM                                         | 63        | 1.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 55        | 1.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 51        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 49        | 1.26%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 45        | 1.16%   |
| Intel Ethernet Connection I354                                                | 35        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                         | 34        | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                          | 33        | 0.85%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 33        | 0.85%   |
| Intel Ethernet Controller X550                                                | 28        | 0.72%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 22        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                          | 22        | 0.57%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 20        | 0.52%   |
| Intel Ethernet Connection X553 1GbE                                           | 20        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                       | 20        | 0.52%   |
| Intel 82575EB Gigabit Network Connection                                      | 18        | 0.46%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 17        | 0.44%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 17        | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                                         | 16        | 0.41%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 16        | 0.41%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 16        | 0.41%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 15        | 0.39%   |
| Intel Ethernet Controller I225-LM                                             | 15        | 0.39%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 15        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2685      | 71.41%  |
| WiFi     | 957       | 25.45%  |
| Unknown  | 83        | 2.21%   |
| Modem    | 35        | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2511      | 85.85%  |
| WiFi     | 405       | 13.85%  |
| Unknown  | 9         | 0.31%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 813       | 28.38%  |
| 4     | 568       | 19.83%  |
| 3     | 392       | 13.68%  |
| 1     | 355       | 12.39%  |
| 6     | 303       | 10.58%  |
| 5     | 215       | 7.5%    |
| 8     | 66        | 2.3%    |
| 7     | 60        | 2.09%   |
| 10    | 26        | 0.91%   |
| 0     | 25        | 0.87%   |
| 9     | 21        | 0.73%   |
| 11    | 6         | 0.21%   |
| 13    | 4         | 0.14%   |
| 16    | 3         | 0.1%    |
| 14    | 3         | 0.1%    |
| 12    | 3         | 0.1%    |
| 20    | 1         | 0.03%   |
| 15    | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2329      | 79.98%  |
| Yes  | 583       | 20.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 410       | 60.83%  |
| Broadcom                        | 51        | 7.57%   |
| Apple                           | 47        | 6.97%   |
| Realtek Semiconductor           | 44        | 6.53%   |
| Qualcomm Atheros Communications | 29        | 4.3%    |
| IMC Networks                    | 26        | 3.86%   |
| Cambridge Silicon Radio         | 14        | 2.08%   |
| ASUSTek Computer                | 12        | 1.78%   |
| Lite-On Technology              | 10        | 1.48%   |
| Dell                            | 8         | 1.19%   |
| Foxconn / Hon Hai               | 6         | 0.89%   |
| MediaTek                        | 5         | 0.74%   |
| Alps Electric                   | 4         | 0.59%   |
| Ralink                          | 2         | 0.3%    |
| TP-Link                         | 1         | 0.15%   |
| Taiyo Yuden                     | 1         | 0.15%   |
| Primax Electronics              | 1         | 0.15%   |
| Hewlett-Packard                 | 1         | 0.15%   |
| Esel International              | 1         | 0.15%   |
| Dynex                           | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 170       | 25.11%  |
| Intel AX200 Bluetooth                                       | 68        | 10.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 55        | 8.12%   |
| Intel AX201 Bluetooth                                       | 37        | 5.47%   |
| Intel Wireless-AC 3168 Bluetooth                            | 23        | 3.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 21        | 3.1%    |
| Intel AX210 Bluetooth                                       | 21        | 3.1%    |
| Apple Bluetooth Host Controller                             | 21        | 3.1%    |
| Realtek  Bluetooth 4.2 Adapter                              | 18        | 2.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 16        | 2.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 14        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 13        | 1.92%   |
| Realtek Bluetooth Adapter                                   | 11        | 1.62%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 11        | 1.62%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 11        | 1.62%   |
| Apple Broadcom Built-in Bluetooth                           | 10        | 1.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 9         | 1.33%   |
| IMC Networks Realtek Bluetooth Adapter                      | 8         | 1.18%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 7         | 1.03%   |
| Lite-On Bluetooth USB Module                                | 6         | 0.89%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 6         | 0.89%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 6         | 0.89%   |
| Realtek Bluetooth 4.2 Adapter                               | 5         | 0.74%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 0.74%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.74%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 0.59%   |
| MediaTek RZ608 Bluetooth Adapter                            | 4         | 0.59%   |
| Dell DW375 Bluetooth Module                                 | 4         | 0.59%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 0.44%   |
| Realtek Bluetooth 4.0 Adapter                               | 3         | 0.44%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3         | 0.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 0.44%   |
| ASUS USB-BT500                                              | 3         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.3%    |
| Ralink RT3290 Bluetooth                                     | 2         | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 2         | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.3%    |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 2         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1626      | 66.39%  |
| AMD                                          | 483       | 19.72%  |
| Nvidia                                       | 220       | 8.98%   |
| C-Media Electronics                          | 34        | 1.39%   |
| Creative Labs                                | 13        | 0.53%   |
| SteelSeries ApS                              | 6         | 0.24%   |
| Logitech                                     | 6         | 0.24%   |
| Texas Instruments                            | 5         | 0.2%    |
| Blue Microphones                             | 5         | 0.2%    |
| Realtek Semiconductor                        | 4         | 0.16%   |
| Corsair                                      | 3         | 0.12%   |
| Yamaha                                       | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.08%   |
| Razer USA                                    | 2         | 0.08%   |
| MosArt Semiconductor                         | 2         | 0.08%   |
| Lenovo                                       | 2         | 0.08%   |
| Google                                       | 2         | 0.08%   |
| Creative Technology                          | 2         | 0.08%   |
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
| Generalplus Technology                       | 1         | 0.04%   |
| Focusrite-Novation                           | 1         | 0.04%   |
| ESS Technology                               | 1         | 0.04%   |
| Dell                                         | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 165       | 5.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 149       | 4.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 133       | 4.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 126       | 4.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 122       | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 119       | 3.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 115       | 3.85%   |
| AMD FCH Azalia Controller                                                                         | 97        | 3.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 95        | 3.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 93        | 3.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 88        | 2.95%   |
| Intel Jasper Lake HD Audio                                                                        | 75        | 2.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 63        | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 59        | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 57        | 1.91%   |
| Intel 200 Series PCH HD Audio                                                                     | 57        | 1.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 56        | 1.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 56        | 1.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 53        | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 52        | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 1.57%   |
| Intel 8 Series HD Audio Controller                                                                | 47        | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 1.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 45        | 1.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 37        | 1.24%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 35        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 33        | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 31        | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 31        | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 25        | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21        | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 19        | 0.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 19        | 0.64%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 18        | 0.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 18        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 556       | 18.4%   |
| SK hynix                                | 482       | 15.95%  |
| Micron Technology                       | 320       | 10.59%  |
| Crucial                                 | 317       | 10.49%  |
| Kingston                                | 264       | 8.74%   |
| Unknown                                 | 251       | 8.31%   |
| G.Skill                                 | 141       | 4.67%   |
| Corsair                                 | 116       | 3.84%   |
| Unknown                                 | 77        | 2.55%   |
| Team                                    | 53        | 1.75%   |
| Transcend                               | 42        | 1.39%   |
| Unknown (ABCD)                          | 41        | 1.36%   |
| Ramaxel Technology                      | 36        | 1.19%   |
| A-DATA Technology                       | 33        | 1.09%   |
| Patriot                                 | 31        | 1.03%   |
| Nanya Technology                        | 31        | 1.03%   |
| PNY                                     | 24        | 0.79%   |
| Elpida                                  | 22        | 0.73%   |
| Kimtigo                                 | 18        | 0.6%    |
| TIMETEC                                 | 14        | 0.46%   |
| Toshiba                                 | 12        | 0.4%    |
| Super Talent                            | 11        | 0.36%   |
| Silicon Power                           | 11        | 0.36%   |
| Avant                                   | 11        | 0.36%   |
| Innodisk                                | 7         | 0.23%   |
| Sesame                                  | 6         | 0.2%    |
| SK_Hynix                                | 5         | 0.17%   |
| Silicon Power Computer & Communications | 5         | 0.17%   |
| GeIL                                    | 4         | 0.13%   |
| tigo                                    | 3         | 0.1%    |
| Ramsta                                  | 3         | 0.1%    |
| Patriot Memory (PDP Systems)            | 3         | 0.1%    |
| Neo Forza                               | 3         | 0.1%    |
| HPE                                     | 3         | 0.1%    |
| Hewlett-Packard                         | 3         | 0.1%    |
| Goldkey                                 | 3         | 0.1%    |
| Apacer                                  | 3         | 0.1%    |
| Wodposit                                | 2         | 0.07%   |
| Vasekey                                 | 2         | 0.07%   |
| Unknown (000000000A07)                  | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 77        | 2.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 38        | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 24        | 0.74%   |
| Unknown RAM Module 8GB 1600MT/s                                | 20        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 19        | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 17        | 0.53%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 17        | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 16        | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 16        | 0.5%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 16        | 0.5%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 15        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 15        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 14        | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 14        | 0.43%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s           | 14        | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 13        | 0.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 13        | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 13        | 0.4%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 12        | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 12        | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 12        | 0.37%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 12        | 0.37%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 11        | 0.34%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 11        | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 10        | 0.31%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s            | 10        | 0.31%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 10        | 0.31%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 10        | 0.31%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 10        | 0.31%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 10        | 0.31%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 10        | 0.31%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 9         | 0.28%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 9         | 0.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 9         | 0.28%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 9         | 0.28%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 9         | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 9         | 0.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 8         | 0.25%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s           | 8         | 0.25%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 8         | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1252      | 47.51%  |
| DDR4         | 1090      | 41.37%  |
| DDR2         | 100       | 3.8%    |
| LPDDR4       | 61        | 2.31%   |
| Unknown      | 59        | 2.24%   |
| SDRAM        | 22        | 0.83%   |
| LPDDR3       | 14        | 0.53%   |
| DDR          | 14        | 0.53%   |
| DDR5         | 13        | 0.49%   |
| LPDDR5       | 5         | 0.19%   |
| DRAM         | 3         | 0.11%   |
| SRAM         | 1         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1462      | 55.67%  |
| SODIMM       | 1060      | 40.37%  |
| Unknown      | 40        | 1.52%   |
| Row Of Chips | 39        | 1.49%   |
| Chip         | 11        | 0.42%   |
| FB-DIMM      | 9         | 0.34%   |
| RIMM         | 5         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1128      | 39.79%  |
| 4096   | 850       | 29.98%  |
| 16384  | 407       | 14.36%  |
| 2048   | 276       | 9.74%   |
| 32768  | 107       | 3.77%   |
| 1024   | 56        | 1.98%   |
| 512    | 7         | 0.25%   |
| 65536  | 2         | 0.07%   |
| 131072 | 1         | 0.04%   |
| 256    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 859       | 30.46%  |
| 2400    | 349       | 12.38%  |
| 1333    | 343       | 12.16%  |
| 2667    | 277       | 9.82%   |
| 3200    | 247       | 8.76%   |
| 2133    | 235       | 8.33%   |
| 800     | 68        | 2.41%   |
| 667     | 60        | 2.13%   |
| 2666    | 58        | 2.06%   |
| 1867    | 40        | 1.42%   |
| 1334    | 40        | 1.42%   |
| 1066    | 37        | 1.31%   |
| 1067    | 34        | 1.21%   |
| Unknown | 28        | 0.99%   |
| 3600    | 26        | 0.92%   |
| 3000    | 26        | 0.92%   |
| 2933    | 16        | 0.57%   |
| 4800    | 13        | 0.46%   |
| 1866    | 11        | 0.39%   |
| 533     | 11        | 0.39%   |
| 4267    | 8         | 0.28%   |
| 400     | 5         | 0.18%   |
| 6400    | 4         | 0.14%   |
| 975     | 4         | 0.14%   |
| 1200    | 3         | 0.11%   |
| 4266    | 2         | 0.07%   |
| 4000    | 2         | 0.07%   |
| 1400    | 2         | 0.07%   |
| 4133    | 1         | 0.04%   |
| 3733    | 1         | 0.04%   |
| 3534    | 1         | 0.04%   |
| 3333    | 1         | 0.04%   |
| 2866    | 1         | 0.04%   |
| 2048    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 1033    | 1         | 0.04%   |
| 266     | 1         | 0.04%   |
| 200     | 1         | 0.04%   |
| 166     | 1         | 0.04%   |

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
| Chicony Electronics                    | 98        | 26.13%  |
| Bison Electronics                      | 41        | 10.93%  |
| Microdia                               | 30        | 8%      |
| Realtek Semiconductor                  | 29        | 7.73%   |
| Sunplus Innovation Technology          | 26        | 6.93%   |
| Logitech                               | 25        | 6.67%   |
| IMC Networks                           | 25        | 6.67%   |
| Apple                                  | 15        | 4%      |
| Quanta                                 | 12        | 3.2%    |
| Suyin                                  | 10        | 2.67%   |
| Lite-On Technology                     | 9         | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) | 9         | 2.4%    |
| Luxvisions Innotech Limited            | 7         | 1.87%   |
| Syntek                                 | 6         | 1.6%    |
| Lenovo                                 | 6         | 1.6%    |
| Importek                               | 3         | 0.8%    |
| WCM_USB                                | 2         | 0.53%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.53%   |
| Ricoh                                  | 2         | 0.53%   |
| Primax Electronics                     | 2         | 0.53%   |
| OmniVision Technologies                | 2         | 0.53%   |
| Intel                                  | 2         | 0.53%   |
| Alcor Micro                            | 2         | 0.53%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| Xiongmai                               | 1         | 0.27%   |
| Supreme Electronics                    | 1         | 0.27%   |
| Silicon Motion                         | 1         | 0.27%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.27%   |
| Goodong Industry                       | 1         | 0.27%   |
| Generalplus Technology                 | 1         | 0.27%   |
| Arkmicro Technologies                  | 1         | 0.27%   |
| ARC International                      | 1         | 0.27%   |
| ALi                                    | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 31        | 8.16%   |
| Bison Integrated Camera                             | 22        | 5.79%   |
| Sunplus Integrated_Webcam_HD                        | 10        | 2.63%   |
| Realtek Integrated_Webcam_HD                        | 10        | 2.63%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 10        | 2.63%   |
| Apple FaceTime HD Camera                            | 10        | 2.63%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 2.37%   |
| Microdia Integrated Webcam                          | 8         | 2.11%   |
| Realtek USB 2.0 PC Camera                           | 7         | 1.84%   |
| Logitech HD Pro Webcam C920                         | 7         | 1.84%   |
| IMC Networks Integrated Camera                      | 7         | 1.84%   |
| Chicony Integrated Camera [ThinkPad]                | 7         | 1.84%   |
| Logitech Webcam C270                                | 6         | 1.58%   |
| Lite-On Integrated Camera                           | 6         | 1.58%   |
| Microdia Integrated_Webcam_HD                       | 5         | 1.32%   |
| Bison ThinkPad Integrated Camera                    | 5         | 1.32%   |
| Suyin Integrated_Webcam_HD                          | 4         | 1.05%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 1.05%   |
| Microdia Webcam Vitade AF                           | 4         | 1.05%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 1.05%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 1.05%   |
| IMC Networks Realtek PC Camera                      | 4         | 1.05%   |
| Chicony Integrated IR Camera                        | 4         | 1.05%   |
| Chicony HP TrueVision HD Camera                     | 4         | 1.05%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 1.05%   |
| Syntek EasyCamera                                   | 3         | 0.79%   |
| Sunplus HD WebCam                                   | 3         | 0.79%   |
| Realtek Laptop Camera                               | 3         | 0.79%   |
| Quanta HP Webcam                                    | 3         | 0.79%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.79%   |
| Luxvisions Innotech Limited Integrated Camera       | 3         | 0.79%   |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.79%   |
| Logitech BRIO Ultra HD Webcam                       | 3         | 0.79%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.79%   |
| IMC Networks EasyCamera                             | 3         | 0.79%   |
| Chicony thinkpad t430s camera                       | 3         | 0.79%   |
| Chicony HD WebCam                                   | 3         | 0.79%   |
| Chicony Chicony USB2.0 Camera                       | 3         | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.79%   |
| Bison SunplusIT Integrated Camera                   | 3         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 31        | 33.33%  |
| Synaptics                  | 18        | 19.35%  |
| Upek                       | 13        | 13.98%  |
| STMicroelectronics         | 11        | 11.83%  |
| Shenzhen Goodix Technology | 7         | 7.53%   |
| AuthenTec                  | 7         | 7.53%   |
| Elan Microelectronics      | 2         | 2.15%   |
| Samsung Electronics        | 1         | 1.08%   |
| LighTuning Technology      | 1         | 1.08%   |
| FocalTech Systems          | 1         | 1.08%   |
| Broadcom                   | 1         | 1.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 16        | 17.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 13        | 13.98%  |
| STMicroelectronics Fingerprint Reader                                        | 11        | 11.83%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 8         | 8.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 7         | 7.53%   |
| Shenzhen Goodix Fingerprint Reader                                           | 6         | 6.45%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 4.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 3.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 3.23%   |
| AuthenTec AES2810                                                            | 3         | 3.23%   |
| Elan Fingerprint Sensor                                                      | 2         | 2.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.15%   |
| AuthenTec AES1660                                                            | 2         | 2.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.08%   |
| Validity Sensors VFS491                                                      | 1         | 1.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.08%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.08%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.08%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 1.08%   |
| Synaptics WBDI                                                               | 1         | 1.08%   |
| Synaptics UWP WBDI                                                           | 1         | 1.08%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.08%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 1.08%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 1.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.08%   |

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
| 1     | 1142      | 39.56%  |
| 0     | 882       | 30.55%  |
| 2     | 565       | 19.57%  |
| 3     | 218       | 7.55%   |
| 4     | 60        | 2.08%   |
| 5     | 13        | 0.45%   |
| 6     | 5         | 0.17%   |
| 7     | 2         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1677      | 61.63%  |
| Bluetooth                | 285       | 10.47%  |
| Net/wireless             | 259       | 9.52%   |
| Card reader              | 133       | 4.89%   |
| Firewire controller      | 98        | 3.6%    |
| Fingerprint reader       | 79        | 2.9%    |
| Net/ethernet             | 50        | 1.84%   |
| Sound                    | 49        | 1.8%    |
| Network                  | 37        | 1.36%   |
| Graphics card            | 22        | 0.81%   |
| Storage                  | 11        | 0.4%    |
| Modem                    | 7         | 0.26%   |
| Storage/raid             | 6         | 0.22%   |
| Storage/ata              | 3         | 0.11%   |
| Dvb card                 | 3         | 0.11%   |
| Storage/ide              | 2         | 0.07%   |

