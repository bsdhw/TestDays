BSD in Canada - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Canada/Desktop/README.md) and [notebooks](/Location/Canada/Notebook/README.md).

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

Total: 783

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 0GU083 A00                  | Desktop     | [1286478dc2](https://bsd-hardware.info/?probe=1286478dc2) | Oct 01, 2023 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [9a73be8c9c](https://bsd-hardware.info/?probe=9a73be8c9c) | Sep 30, 2023 |
| HP            | 82B4                        | Desktop     | [60d259ab3f](https://bsd-hardware.info/?probe=60d259ab3f) | Sep 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [df07570acc](https://bsd-hardware.info/?probe=df07570acc) | Sep 28, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [0f20928f2d](https://bsd-hardware.info/?probe=0f20928f2d) | Sep 28, 2023 |
| HP            | 18E5                        | Desktop     | [9c21b6e355](https://bsd-hardware.info/?probe=9c21b6e355) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [05f45ba264](https://bsd-hardware.info/?probe=05f45ba264) | Sep 25, 2023 |
| HP            | 18E5                        | Desktop     | [02b94adef6](https://bsd-hardware.info/?probe=02b94adef6) | Sep 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [5a0b8eb786](https://bsd-hardware.info/?probe=5a0b8eb786) | Sep 21, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| CncTion       | Jasper-4L B0                | Desktop     | [96f81e84f6](https://bsd-hardware.info/?probe=96f81e84f6) | Sep 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7b6014f65f](https://bsd-hardware.info/?probe=7b6014f65f) | Sep 18, 2023 |
| CncTion       | Jasper-4L B0                | Desktop     | [4254b5eac8](https://bsd-hardware.info/?probe=4254b5eac8) | Sep 17, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [b6763a8d49](https://bsd-hardware.info/?probe=b6763a8d49) | Sep 17, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | Notebook    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [28f5d3aea6](https://bsd-hardware.info/?probe=28f5d3aea6) | Sep 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fccf590d4](https://bsd-hardware.info/?probe=0fccf590d4) | Sep 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c53ad8bea](https://bsd-hardware.info/?probe=7c53ad8bea) | Sep 10, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5695984890](https://bsd-hardware.info/?probe=5695984890) | Sep 10, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7e4ea56868](https://bsd-hardware.info/?probe=7e4ea56868) | Sep 10, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [ee34cb0b60](https://bsd-hardware.info/?probe=ee34cb0b60) | Sep 10, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [93234978cf](https://bsd-hardware.info/?probe=93234978cf) | Sep 09, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [34a855cc56](https://bsd-hardware.info/?probe=34a855cc56) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [19711ca08b](https://bsd-hardware.info/?probe=19711ca08b) | Sep 06, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [c06ec95a55](https://bsd-hardware.info/?probe=c06ec95a55) | Sep 06, 2023 |
| Shuttle       | DS67U                       | Notebook    | [55c2922a25](https://bsd-hardware.info/?probe=55c2922a25) | Sep 04, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7209f86fed](https://bsd-hardware.info/?probe=7209f86fed) | Sep 04, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [a1c29072ea](https://bsd-hardware.info/?probe=a1c29072ea) | Sep 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [70992eb19b](https://bsd-hardware.info/?probe=70992eb19b) | Sep 02, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [77b461d3ad](https://bsd-hardware.info/?probe=77b461d3ad) | Sep 02, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [383445ee26](https://bsd-hardware.info/?probe=383445ee26) | Sep 01, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [04de7aa059](https://bsd-hardware.info/?probe=04de7aa059) | Sep 01, 2023 |
| Dell          | 042P49 A01                  | Desktop     | [a06ab2449f](https://bsd-hardware.info/?probe=a06ab2449f) | Aug 26, 2023 |
| PC Engines    | APU2                        | Desktop     | [ed6839f08c](https://bsd-hardware.info/?probe=ed6839f08c) | Aug 26, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [46499d5075](https://bsd-hardware.info/?probe=46499d5075) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [6619af0a29](https://bsd-hardware.info/?probe=6619af0a29) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [aad81c60fa](https://bsd-hardware.info/?probe=aad81c60fa) | Aug 25, 2023 |
| Datto         | Unknown                     | Notebook    | [418eab5eaa](https://bsd-hardware.info/?probe=418eab5eaa) | Aug 23, 2023 |
| Dell          | 0KHP4K A03                  | Desktop     | [c54db98574](https://bsd-hardware.info/?probe=c54db98574) | Aug 22, 2023 |
| Dell          | 0KHP4K A03                  | Desktop     | [dd1ad7af32](https://bsd-hardware.info/?probe=dd1ad7af32) | Aug 22, 2023 |
| Protectli     | VP2420                      | Desktop     | [c033157bb2](https://bsd-hardware.info/?probe=c033157bb2) | Aug 22, 2023 |
| Lenovo        | ThinkCentre M90p 3853RN9    | Desktop     | [818c1b5f31](https://bsd-hardware.info/?probe=818c1b5f31) | Aug 20, 2023 |
| AZW           | SER                         | Mini pc     | [db297e2cda](https://bsd-hardware.info/?probe=db297e2cda) | Aug 20, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [8f26de2199](https://bsd-hardware.info/?probe=8f26de2199) | Aug 19, 2023 |
| Star Labs     | Lite                        | Notebook    | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [7ea90d38d1](https://bsd-hardware.info/?probe=7ea90d38d1) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [08061905f7](https://bsd-hardware.info/?probe=08061905f7) | Aug 15, 2023 |
| Dell          | 00VTMF A01                  | Desktop     | [399fe2224c](https://bsd-hardware.info/?probe=399fe2224c) | Aug 13, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [0fd996a147](https://bsd-hardware.info/?probe=0fd996a147) | Aug 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a22e406f7c](https://bsd-hardware.info/?probe=a22e406f7c) | Aug 10, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [c693116826](https://bsd-hardware.info/?probe=c693116826) | Aug 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0c9251a971](https://bsd-hardware.info/?probe=0c9251a971) | Aug 09, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Protectli     | VP2420                      | Desktop     | [2ec2033d58](https://bsd-hardware.info/?probe=2ec2033d58) | Aug 01, 2023 |
| AZW           | SER                         | Mini pc     | [287fdf7e70](https://bsd-hardware.info/?probe=287fdf7e70) | Jul 30, 2023 |
| HP            | 2AF7                        | Desktop     | [fc495dc6c7](https://bsd-hardware.info/?probe=fc495dc6c7) | Jul 29, 2023 |
| AZW           | U59                         | Desktop     | [1862cfda96](https://bsd-hardware.info/?probe=1862cfda96) | Jul 23, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [8c9dfc9396](https://bsd-hardware.info/?probe=8c9dfc9396) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [b96b847399](https://bsd-hardware.info/?probe=b96b847399) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3e853472dc](https://bsd-hardware.info/?probe=3e853472dc) | Jul 19, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [738b473ab6](https://bsd-hardware.info/?probe=738b473ab6) | Jul 18, 2023 |
| Intel         | DQ67EP AAG12529-308         | Desktop     | [f58fdceed1](https://bsd-hardware.info/?probe=f58fdceed1) | Jul 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [cfdbed124e](https://bsd-hardware.info/?probe=cfdbed124e) | Jul 17, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [e1647604a7](https://bsd-hardware.info/?probe=e1647604a7) | Jul 15, 2023 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [499e5b7941](https://bsd-hardware.info/?probe=499e5b7941) | Jul 14, 2023 |
| HP            | 2AF7                        | Desktop     | [a983dd41d6](https://bsd-hardware.info/?probe=a983dd41d6) | Jul 13, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6db56ee0ef](https://bsd-hardware.info/?probe=6db56ee0ef) | Jul 13, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [80546fd9e6](https://bsd-hardware.info/?probe=80546fd9e6) | Jul 12, 2023 |
| AZW           | U59                         | Desktop     | [20a3b64ecd](https://bsd-hardware.info/?probe=20a3b64ecd) | Jul 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bbef95a882](https://bsd-hardware.info/?probe=bbef95a882) | Jul 08, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [933187d501](https://bsd-hardware.info/?probe=933187d501) | Jul 08, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [76cfc2c80e](https://bsd-hardware.info/?probe=76cfc2c80e) | Jul 07, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [e36e748937](https://bsd-hardware.info/?probe=e36e748937) | Jul 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [9d6fef9445](https://bsd-hardware.info/?probe=9d6fef9445) | Jul 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [1ef9818928](https://bsd-hardware.info/?probe=1ef9818928) | Jun 27, 2023 |
| HP            | 1495                        | Desktop     | [564ff2ef77](https://bsd-hardware.info/?probe=564ff2ef77) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M55 880894U     | Desktop     | [e406083f25](https://bsd-hardware.info/?probe=e406083f25) | Jun 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [0b667bc4e7](https://bsd-hardware.info/?probe=0b667bc4e7) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [278b419d40](https://bsd-hardware.info/?probe=278b419d40) | Jun 17, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [39e7195baf](https://bsd-hardware.info/?probe=39e7195baf) | Jun 15, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [3484cbbf9f](https://bsd-hardware.info/?probe=3484cbbf9f) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [080be9d6f5](https://bsd-hardware.info/?probe=080be9d6f5) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [88a421e275](https://bsd-hardware.info/?probe=88a421e275) | Jun 10, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [48833ba1a3](https://bsd-hardware.info/?probe=48833ba1a3) | Jun 08, 2023 |
| Protectli     | VP2420                      | Desktop     | [45e550e09f](https://bsd-hardware.info/?probe=45e550e09f) | Jun 07, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0754642fe6](https://bsd-hardware.info/?probe=0754642fe6) | Jun 07, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f0f13f5cea](https://bsd-hardware.info/?probe=f0f13f5cea) | Jun 06, 2023 |
| Unknown       | Unknown                     | Firewall    | [f971e964cd](https://bsd-hardware.info/?probe=f971e964cd) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [a7a24624d7](https://bsd-hardware.info/?probe=a7a24624d7) | Jun 05, 2023 |
| Supermicro    | X10SL7-F                    | Server      | [7dbcaa598b](https://bsd-hardware.info/?probe=7dbcaa598b) | Jun 04, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [5fc38b17d3](https://bsd-hardware.info/?probe=5fc38b17d3) | Jun 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5be94420c2](https://bsd-hardware.info/?probe=5be94420c2) | Jun 02, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ed0c6cf73c](https://bsd-hardware.info/?probe=ed0c6cf73c) | May 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [88e6cd10c6](https://bsd-hardware.info/?probe=88e6cd10c6) | May 27, 2023 |
| Protectli     | FW4B                        | Desktop     | [c5c9276f48](https://bsd-hardware.info/?probe=c5c9276f48) | May 27, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [860479dab3](https://bsd-hardware.info/?probe=860479dab3) | May 21, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [cc4c36977f](https://bsd-hardware.info/?probe=cc4c36977f) | May 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c258ecb4bc](https://bsd-hardware.info/?probe=c258ecb4bc) | May 13, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [432b2a27c3](https://bsd-hardware.info/?probe=432b2a27c3) | May 13, 2023 |
| ZOTAC         | ZBOX-CI325NANO              | Mini pc     | [f64e789401](https://bsd-hardware.info/?probe=f64e789401) | May 11, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [dcea67b6a6](https://bsd-hardware.info/?probe=dcea67b6a6) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | Notebook    | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | Desktop     | [b0c462fbd5](https://bsd-hardware.info/?probe=b0c462fbd5) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [73f9fac4f8](https://bsd-hardware.info/?probe=73f9fac4f8) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| AZW           | SER                         | Mini pc     | [d3d9ba6f52](https://bsd-hardware.info/?probe=d3d9ba6f52) | Apr 30, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| Dell          | 00NH4P A03                  | Server      | [85fb3b322e](https://bsd-hardware.info/?probe=85fb3b322e) | Apr 29, 2023 |
| iBASE         | Mi956                       | Desktop     | [e2c1e52a68](https://bsd-hardware.info/?probe=e2c1e52a68) | Apr 29, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8acf41eb6b](https://bsd-hardware.info/?probe=8acf41eb6b) | Apr 28, 2023 |
| iBASE         | Mi956                       | Desktop     | [cb08976732](https://bsd-hardware.info/?probe=cb08976732) | Apr 27, 2023 |
| Intel         | CRESCENTBAY                 | Desktop     | [b32c8cbec8](https://bsd-hardware.info/?probe=b32c8cbec8) | Apr 27, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [8476daf227](https://bsd-hardware.info/?probe=8476daf227) | Apr 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dcacaf8c50](https://bsd-hardware.info/?probe=dcacaf8c50) | Apr 26, 2023 |
| HP            | 1998                        | Desktop     | [41b5bbe52c](https://bsd-hardware.info/?probe=41b5bbe52c) | Apr 26, 2023 |
| Protectli     | FW4B                        | Desktop     | [111e2f7b3b](https://bsd-hardware.info/?probe=111e2f7b3b) | Apr 25, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [89f1d3809e](https://bsd-hardware.info/?probe=89f1d3809e) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [389267d68d](https://bsd-hardware.info/?probe=389267d68d) | Apr 24, 2023 |
| Lenovo        | ThinkCentre M57p 6073ATU    | Desktop     | [b1e7583e6b](https://bsd-hardware.info/?probe=b1e7583e6b) | Apr 24, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [cfd318affb](https://bsd-hardware.info/?probe=cfd318affb) | Apr 23, 2023 |
| BYTENUC       | AZ51                        | Mini pc     | [0743e8fcc3](https://bsd-hardware.info/?probe=0743e8fcc3) | Apr 22, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [24379ebf10](https://bsd-hardware.info/?probe=24379ebf10) | Apr 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cf533da9bf](https://bsd-hardware.info/?probe=cf533da9bf) | Apr 16, 2023 |
| Pegatron      | 2A72h                       | Desktop     | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| iBASE         | Mi956                       | Desktop     | [0d4d63b29b](https://bsd-hardware.info/?probe=0d4d63b29b) | Apr 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [d2f19cb660](https://bsd-hardware.info/?probe=d2f19cb660) | Apr 13, 2023 |
| HP            | 3397                        | Desktop     | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [ce3072c27a](https://bsd-hardware.info/?probe=ce3072c27a) | Apr 05, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [9418e51f7e](https://bsd-hardware.info/?probe=9418e51f7e) | Apr 03, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [3bb60897ff](https://bsd-hardware.info/?probe=3bb60897ff) | Apr 01, 2023 |
| Alienware     | 049PDM A00                  | Desktop     | [139d115cdb](https://bsd-hardware.info/?probe=139d115cdb) | Mar 29, 2023 |
| Lenovo        | ThinkCentre M58 7360EUU     | Desktop     | [b86ffef220](https://bsd-hardware.info/?probe=b86ffef220) | Mar 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Acer          | WG43M                       | Desktop     | [c8f2a03a08](https://bsd-hardware.info/?probe=c8f2a03a08) | Mar 27, 2023 |
| Acer          | WG43M                       | Desktop     | [5e154dc7cf](https://bsd-hardware.info/?probe=5e154dc7cf) | Mar 26, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [735a5cc6a2](https://bsd-hardware.info/?probe=735a5cc6a2) | Mar 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| HP            | 1497                        | Desktop     | [08daaf3be1](https://bsd-hardware.info/?probe=08daaf3be1) | Mar 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8de4b8231a](https://bsd-hardware.info/?probe=8de4b8231a) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [fc6a7ebc91](https://bsd-hardware.info/?probe=fc6a7ebc91) | Mar 25, 2023 |
| eMachines     | eM350                       | Notebook    | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| HP            | 1497                        | Desktop     | [e98b5284d9](https://bsd-hardware.info/?probe=e98b5284d9) | Mar 25, 2023 |
| Alienware     | 14                          | Notebook    | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | Notebook    | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [55c708e91a](https://bsd-hardware.info/?probe=55c708e91a) | Mar 24, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| Dell          | Edge Gateway 5100           | Mini pc     | [7cb4288db0](https://bsd-hardware.info/?probe=7cb4288db0) | Mar 23, 2023 |
| Dell          | 00NH4P A03                  | Server      | [0d29dd3a66](https://bsd-hardware.info/?probe=0d29dd3a66) | Mar 20, 2023 |
| HP            | ProBook 640 G3              | Notebook    | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
| HP            | 1632                        | Desktop     | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| AWOW          | PC BOX                      | Mini pc     | [fcbdcaff04](https://bsd-hardware.info/?probe=fcbdcaff04) | Mar 16, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | Desktop     | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [898095b140](https://bsd-hardware.info/?probe=898095b140) | Mar 09, 2023 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [6a15f7d4a1](https://bsd-hardware.info/?probe=6a15f7d4a1) | Mar 09, 2023 |
| Intel         | S1200RP_SE G62252-406       | Server      | [2b2b508432](https://bsd-hardware.info/?probe=2b2b508432) | Mar 05, 2023 |
| Dell          | 0M877N A02                  | Server      | [a69882ae55](https://bsd-hardware.info/?probe=a69882ae55) | Mar 02, 2023 |
| Arctic Wol... | AWN101                      | Desktop     | [e0f187e449](https://bsd-hardware.info/?probe=e0f187e449) | Mar 01, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [22a1b812f8](https://bsd-hardware.info/?probe=22a1b812f8) | Mar 01, 2023 |
| Dell          | 0M877N A01                  | Server      | [8037b5a26c](https://bsd-hardware.info/?probe=8037b5a26c) | Feb 27, 2023 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [40d63fc1f7](https://bsd-hardware.info/?probe=40d63fc1f7) | Feb 27, 2023 |
| Dell          | 01TKCC A01                  | Desktop     | [42da900d88](https://bsd-hardware.info/?probe=42da900d88) | Feb 26, 2023 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [c3864d9d51](https://bsd-hardware.info/?probe=c3864d9d51) | Feb 26, 2023 |
| AZW           | U59                         | Desktop     | [a4e906c608](https://bsd-hardware.info/?probe=a4e906c608) | Feb 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [d690aee80e](https://bsd-hardware.info/?probe=d690aee80e) | Feb 26, 2023 |
| AZW           | U59                         | Desktop     | [4dad05a05a](https://bsd-hardware.info/?probe=4dad05a05a) | Feb 24, 2023 |
| AZW           | U59                         | Desktop     | [638aa3ff8e](https://bsd-hardware.info/?probe=638aa3ff8e) | Feb 24, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [50f39ca7e0](https://bsd-hardware.info/?probe=50f39ca7e0) | Feb 20, 2023 |
| Apple         | PowerMac3,6                 | Desktop     | [f31181f95c](https://bsd-hardware.info/?probe=f31181f95c) | Feb 20, 2023 |
| Gigabyte      | GB-BSi3A-6100               | Notebook    | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | Notebook    | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [fd90fc5154](https://bsd-hardware.info/?probe=fd90fc5154) | Feb 18, 2023 |
| ASUSTek       | PRIME H310M-C R2.0          | Desktop     | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| Dell          | 0M877N A02                  | Server      | [94d00881ba](https://bsd-hardware.info/?probe=94d00881ba) | Feb 17, 2023 |
| Dell          | 0MFXTY A02                  | Server      | [706029e578](https://bsd-hardware.info/?probe=706029e578) | Feb 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f3c3e6ecb5](https://bsd-hardware.info/?probe=f3c3e6ecb5) | Feb 16, 2023 |
| MiTAC         | UltraPoint                  | Desktop     | [00e52df710](https://bsd-hardware.info/?probe=00e52df710) | Feb 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [547c79f551](https://bsd-hardware.info/?probe=547c79f551) | Feb 13, 2023 |
| HP            | 212B                        | Desktop     | [0e13beb9f6](https://bsd-hardware.info/?probe=0e13beb9f6) | Feb 12, 2023 |
| Dell          | 0M877N A02                  | Server      | [36e51fcc8b](https://bsd-hardware.info/?probe=36e51fcc8b) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [f69bff2d41](https://bsd-hardware.info/?probe=f69bff2d41) | Feb 12, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [60f03e1dec](https://bsd-hardware.info/?probe=60f03e1dec) | Feb 12, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [c9c53f2141](https://bsd-hardware.info/?probe=c9c53f2141) | Feb 12, 2023 |
| iBASE         | Mi956                       | Desktop     | [86d20c1bc0](https://bsd-hardware.info/?probe=86d20c1bc0) | Feb 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [3f0d4c3ced](https://bsd-hardware.info/?probe=3f0d4c3ced) | Feb 10, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [5c2047356d](https://bsd-hardware.info/?probe=5c2047356d) | Feb 08, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0587338e57](https://bsd-hardware.info/?probe=0587338e57) | Feb 08, 2023 |
| Dell          | 0F3KHR A02                  | Desktop     | [98c9324352](https://bsd-hardware.info/?probe=98c9324352) | Feb 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| Supermicro    | X9SCL/X9SCM                 | Desktop     | [1022faa668](https://bsd-hardware.info/?probe=1022faa668) | Feb 01, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [8597f8bbcc](https://bsd-hardware.info/?probe=8597f8bbcc) | Jan 31, 2023 |
| Dell          | 0J3C2F A01                  | Desktop     | [93a87b6106](https://bsd-hardware.info/?probe=93a87b6106) | Jan 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [b8efd7453b](https://bsd-hardware.info/?probe=b8efd7453b) | Jan 29, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [e00d33f978](https://bsd-hardware.info/?probe=e00d33f978) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [87e25e2abd](https://bsd-hardware.info/?probe=87e25e2abd) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [cde064f460](https://bsd-hardware.info/?probe=cde064f460) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [76840aba40](https://bsd-hardware.info/?probe=76840aba40) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [14089c4ab4](https://bsd-hardware.info/?probe=14089c4ab4) | Jan 21, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [b0fe0783d5](https://bsd-hardware.info/?probe=b0fe0783d5) | Jan 21, 2023 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [629c2e1a21](https://bsd-hardware.info/?probe=629c2e1a21) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [32ebc1c99d](https://bsd-hardware.info/?probe=32ebc1c99d) | Jan 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [c3281eb186](https://bsd-hardware.info/?probe=c3281eb186) | Jan 18, 2023 |
| HP            | 83F2                        | Desktop     | [a7230c1af5](https://bsd-hardware.info/?probe=a7230c1af5) | Jan 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [0049fd4cfc](https://bsd-hardware.info/?probe=0049fd4cfc) | Jan 17, 2023 |
| HP            | 83F2                        | Desktop     | [912de3c81d](https://bsd-hardware.info/?probe=912de3c81d) | Jan 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [23d2c64af3](https://bsd-hardware.info/?probe=23d2c64af3) | Jan 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [429659b071](https://bsd-hardware.info/?probe=429659b071) | Jan 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [7ba28d1e6b](https://bsd-hardware.info/?probe=7ba28d1e6b) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [917972b6ae](https://bsd-hardware.info/?probe=917972b6ae) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [bd60eadfc4](https://bsd-hardware.info/?probe=bd60eadfc4) | Jan 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [a21b21b82f](https://bsd-hardware.info/?probe=a21b21b82f) | Jan 12, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| HP            | 2000                        | Notebook    | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [b19ed4597a](https://bsd-hardware.info/?probe=b19ed4597a) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6347de602a](https://bsd-hardware.info/?probe=6347de602a) | Jan 07, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | Notebook    | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [4e8b83804d](https://bsd-hardware.info/?probe=4e8b83804d) | Jan 06, 2023 |
| Supermicro    | X10DRL-i                    | Server      | [c0fa5bb871](https://bsd-hardware.info/?probe=c0fa5bb871) | Jan 06, 2023 |
| MSI           | MEG Z690 UNIFY-X            | Desktop     | [e70cd80d11](https://bsd-hardware.info/?probe=e70cd80d11) | Jan 05, 2023 |
| Protectli     | VP2410 10                   | Desktop     | [81c02d080f](https://bsd-hardware.info/?probe=81c02d080f) | Jan 05, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [219200b0b6](https://bsd-hardware.info/?probe=219200b0b6) | Jan 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [4730790da9](https://bsd-hardware.info/?probe=4730790da9) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [3d2465f9f9](https://bsd-hardware.info/?probe=3d2465f9f9) | Jan 03, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9dd29daa88](https://bsd-hardware.info/?probe=9dd29daa88) | Jan 02, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [a9bbb3592c](https://bsd-hardware.info/?probe=a9bbb3592c) | Jan 02, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b6ec2e7e28](https://bsd-hardware.info/?probe=b6ec2e7e28) | Dec 31, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [cac58d91b6](https://bsd-hardware.info/?probe=cac58d91b6) | Dec 31, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [910c2bba4a](https://bsd-hardware.info/?probe=910c2bba4a) | Dec 31, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [5d287163c9](https://bsd-hardware.info/?probe=5d287163c9) | Dec 29, 2022 |
| HP            | 1998                        | Desktop     | [afc7de60e3](https://bsd-hardware.info/?probe=afc7de60e3) | Dec 28, 2022 |
| ASRock        | N3710-NUC IPC               | Desktop     | [80c809e992](https://bsd-hardware.info/?probe=80c809e992) | Dec 24, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cde7bad6c3](https://bsd-hardware.info/?probe=cde7bad6c3) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b8c89bdca8](https://bsd-hardware.info/?probe=b8c89bdca8) | Dec 22, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [b0d1792185](https://bsd-hardware.info/?probe=b0d1792185) | Dec 21, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [0eea35e069](https://bsd-hardware.info/?probe=0eea35e069) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f876d5d5b1](https://bsd-hardware.info/?probe=f876d5d5b1) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [3d77f833b0](https://bsd-hardware.info/?probe=3d77f833b0) | Dec 19, 2022 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [1f1de1d49c](https://bsd-hardware.info/?probe=1f1de1d49c) | Dec 18, 2022 |
| PC Engines    | APU                         | Desktop     | [19786edc61](https://bsd-hardware.info/?probe=19786edc61) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d9376f2f63](https://bsd-hardware.info/?probe=d9376f2f63) | Dec 16, 2022 |
| HP            | 1495                        | Desktop     | [04bd0455f2](https://bsd-hardware.info/?probe=04bd0455f2) | Dec 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e44f465325](https://bsd-hardware.info/?probe=e44f465325) | Dec 14, 2022 |
| HP            | 1495                        | Desktop     | [23f8aeada7](https://bsd-hardware.info/?probe=23f8aeada7) | Dec 14, 2022 |
| Dell          | 0TY019 A02                  | Server      | [a12907d76a](https://bsd-hardware.info/?probe=a12907d76a) | Dec 12, 2022 |
| HP            | 2000                        | Notebook    | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| HP            | 1495                        | Desktop     | [3eab39d89f](https://bsd-hardware.info/?probe=3eab39d89f) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [07fbfad254](https://bsd-hardware.info/?probe=07fbfad254) | Dec 09, 2022 |
| Sophos        | SG                          | Firewall    | [a3b0edbd3c](https://bsd-hardware.info/?probe=a3b0edbd3c) | Dec 09, 2022 |
| HP            | 3397                        | Desktop     | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | Desktop     | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| Dell          | 0TY019 A02                  | Server      | [84b683ec0b](https://bsd-hardware.info/?probe=84b683ec0b) | Dec 08, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [27dea9bcb5](https://bsd-hardware.info/?probe=27dea9bcb5) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [15b2363325](https://bsd-hardware.info/?probe=15b2363325) | Dec 05, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [250b12c3f2](https://bsd-hardware.info/?probe=250b12c3f2) | Dec 05, 2022 |
| Panasonic     | CF-54-1                     | Notebook    | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cfaeaeb2f2](https://bsd-hardware.info/?probe=cfaeaeb2f2) | Nov 29, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [e8e158f783](https://bsd-hardware.info/?probe=e8e158f783) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [512a05eefb](https://bsd-hardware.info/?probe=512a05eefb) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5f0b8df8d0](https://bsd-hardware.info/?probe=5f0b8df8d0) | Nov 27, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [34dd85f78d](https://bsd-hardware.info/?probe=34dd85f78d) | Nov 26, 2022 |
| CompuLab      | fit-PC3                     | Mini pc     | [54a64a269c](https://bsd-hardware.info/?probe=54a64a269c) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [222e69ff59](https://bsd-hardware.info/?probe=222e69ff59) | Nov 26, 2022 |
| Protectli     | FW6                         | Desktop     | [74510f3177](https://bsd-hardware.info/?probe=74510f3177) | Nov 25, 2022 |
| HP            | 8055                        | Desktop     | [ace4570d15](https://bsd-hardware.info/?probe=ace4570d15) | Nov 25, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [7258992b77](https://bsd-hardware.info/?probe=7258992b77) | Nov 24, 2022 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [e0f08b66c2](https://bsd-hardware.info/?probe=e0f08b66c2) | Nov 21, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | Notebook    | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7c7a121711](https://bsd-hardware.info/?probe=7c7a121711) | Nov 18, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [5875ecec9f](https://bsd-hardware.info/?probe=5875ecec9f) | Nov 18, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| AZW           | U59                         | Desktop     | [25e1349c5f](https://bsd-hardware.info/?probe=25e1349c5f) | Nov 17, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [269f915ce2](https://bsd-hardware.info/?probe=269f915ce2) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [bb9cf416c4](https://bsd-hardware.info/?probe=bb9cf416c4) | Nov 11, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | Notebook    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| ASUSTek       | P8H77-I                     | Desktop     | [04ea3cc97d](https://bsd-hardware.info/?probe=04ea3cc97d) | Nov 09, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [32331d772c](https://bsd-hardware.info/?probe=32331d772c) | Nov 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a84d0a0380](https://bsd-hardware.info/?probe=a84d0a0380) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Datto         | SSD                         | Desktop     | [235483110d](https://bsd-hardware.info/?probe=235483110d) | Nov 05, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [871a5c449f](https://bsd-hardware.info/?probe=871a5c449f) | Nov 01, 2022 |
| Dell          | 09T7VV A02                  | Server      | [6e89de5b97](https://bsd-hardware.info/?probe=6e89de5b97) | Nov 01, 2022 |
| Cisco         | ASA5512 A0                  | Desktop     | [5758027775](https://bsd-hardware.info/?probe=5758027775) | Oct 31, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | Notebook    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | Notebook    | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [6dda683e10](https://bsd-hardware.info/?probe=6dda683e10) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| HP            | 18E4                        | Desktop     | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [c3f0ae254e](https://bsd-hardware.info/?probe=c3f0ae254e) | Oct 17, 2022 |
| Yanling       | YL-KBR6L Ver:1.00           | Desktop     | [b4e02e3f51](https://bsd-hardware.info/?probe=b4e02e3f51) | Oct 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [00b5fa7a4e](https://bsd-hardware.info/?probe=00b5fa7a4e) | Oct 13, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [edead8a3ae](https://bsd-hardware.info/?probe=edead8a3ae) | Oct 11, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [ce728798a1](https://bsd-hardware.info/?probe=ce728798a1) | Oct 07, 2022 |
| Sophos        | XG                          | Firewall    | [cf528e776d](https://bsd-hardware.info/?probe=cf528e776d) | Oct 05, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [79060c241b](https://bsd-hardware.info/?probe=79060c241b) | Oct 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [3590d4504c](https://bsd-hardware.info/?probe=3590d4504c) | Oct 02, 2022 |
| MSI           | GL65 Leopard 10SFSK         | Notebook    | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Intel         | S1200RP_SE G62252-406       | Server      | [4763fe7595](https://bsd-hardware.info/?probe=4763fe7595) | Sep 30, 2022 |
| Intel         | H81U                        | Notebook    | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33b252016c](https://bsd-hardware.info/?probe=33b252016c) | Sep 26, 2022 |
| Acer          | Swift SF313-52              | Notebook    | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| ShenZhen M... | MW-GMLK-2.5G6L              | Desktop     | [a1a2cbc6c9](https://bsd-hardware.info/?probe=a1a2cbc6c9) | Sep 20, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [22f23ccfa5](https://bsd-hardware.info/?probe=22f23ccfa5) | Sep 17, 2022 |
| Google        | Peppy                       | Notebook    | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [21e7190ff2](https://bsd-hardware.info/?probe=21e7190ff2) | Sep 11, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [3c152ae7bd](https://bsd-hardware.info/?probe=3c152ae7bd) | Sep 11, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [89b185547b](https://bsd-hardware.info/?probe=89b185547b) | Sep 10, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [a854e50942](https://bsd-hardware.info/?probe=a854e50942) | Sep 06, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [860518eb18](https://bsd-hardware.info/?probe=860518eb18) | Sep 04, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [b53e1d28cd](https://bsd-hardware.info/?probe=b53e1d28cd) | Sep 04, 2022 |
| Intel         | DQ67EP AAG12529-307         | Desktop     | [1fb1fd6705](https://bsd-hardware.info/?probe=1fb1fd6705) | Sep 03, 2022 |
| Supermicro    | M11SDV-8C-LN4FA             | Desktop     | [2e4b87acd2](https://bsd-hardware.info/?probe=2e4b87acd2) | Sep 03, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [b3a1456bb4](https://bsd-hardware.info/?probe=b3a1456bb4) | Aug 29, 2022 |
| HP            | 8103 A01                    | Mini pc     | [de20688262](https://bsd-hardware.info/?probe=de20688262) | Aug 27, 2022 |
| Dell          | 09T7VV A07                  | Server      | [0325ade874](https://bsd-hardware.info/?probe=0325ade874) | Aug 23, 2022 |
| Gigabyte      | MBHM87P-00                  | Desktop     | [9fa5160871](https://bsd-hardware.info/?probe=9fa5160871) | Aug 22, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04df24b0b8](https://bsd-hardware.info/?probe=04df24b0b8) | Aug 20, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [9fc4b3c63e](https://bsd-hardware.info/?probe=9fc4b3c63e) | Aug 17, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [753f277d5c](https://bsd-hardware.info/?probe=753f277d5c) | Aug 16, 2022 |
| AZW           | Green G1                    | Desktop     | [4bccb24702](https://bsd-hardware.info/?probe=4bccb24702) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a21172360d](https://bsd-hardware.info/?probe=a21172360d) | Aug 15, 2022 |
| Dell          | 04Y8V0 A02                  | Desktop     | [6acccc63ff](https://bsd-hardware.info/?probe=6acccc63ff) | Aug 15, 2022 |
| Lenovo        | 3111 SDK0J40705 WIN 3425... | Desktop     | [6927813b1d](https://bsd-hardware.info/?probe=6927813b1d) | Aug 13, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [236cd1ee65](https://bsd-hardware.info/?probe=236cd1ee65) | Aug 08, 2022 |
| Biostar       | TA880GU3+                   | Desktop     | [8b0c8541b3](https://bsd-hardware.info/?probe=8b0c8541b3) | Aug 06, 2022 |
| MSI           | 785GT-E63                   | Desktop     | [8c307fb033](https://bsd-hardware.info/?probe=8c307fb033) | Aug 03, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [83bbf8e819](https://bsd-hardware.info/?probe=83bbf8e819) | Aug 03, 2022 |
| Intel         | H81U                        | Notebook    | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Intel         | H81U                        | Notebook    | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [860b06cb6b](https://bsd-hardware.info/?probe=860b06cb6b) | Aug 01, 2022 |
| HP            | 8055                        | Desktop     | [6a8a361dae](https://bsd-hardware.info/?probe=6a8a361dae) | Jul 31, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [900c62c2ba](https://bsd-hardware.info/?probe=900c62c2ba) | Jul 30, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [27b986a422](https://bsd-hardware.info/?probe=27b986a422) | Jul 30, 2022 |
| HP            | 8055                        | Desktop     | [41d802a80a](https://bsd-hardware.info/?probe=41d802a80a) | Jul 29, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [7be6ba0021](https://bsd-hardware.info/?probe=7be6ba0021) | Jul 29, 2022 |
| HP            | 18E9                        | Desktop     | [56460b095e](https://bsd-hardware.info/?probe=56460b095e) | Jul 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Unknown       | Unknown                     | Firewall    | [15c779bfe1](https://bsd-hardware.info/?probe=15c779bfe1) | Jul 27, 2022 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1ed99ad502](https://bsd-hardware.info/?probe=1ed99ad502) | Jul 20, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [7ca3d2715c](https://bsd-hardware.info/?probe=7ca3d2715c) | Jul 19, 2022 |
| Lenovo        | ThinkCentre M91 4518E4U     | Desktop     | [8dd1034cfa](https://bsd-hardware.info/?probe=8dd1034cfa) | Jul 16, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [7530b2fc5f](https://bsd-hardware.info/?probe=7530b2fc5f) | Jul 15, 2022 |
| AZW           | Green G1                    | Desktop     | [9a2120ae5a](https://bsd-hardware.info/?probe=9a2120ae5a) | Jul 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [bd1a86e875](https://bsd-hardware.info/?probe=bd1a86e875) | Jul 10, 2022 |
| Datto         | SSD                         | Desktop     | [639d28d449](https://bsd-hardware.info/?probe=639d28d449) | Jul 08, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a945073364](https://bsd-hardware.info/?probe=a945073364) | Jul 07, 2022 |
| Protectli     | FW6                         | Desktop     | [e82838534b](https://bsd-hardware.info/?probe=e82838534b) | Jul 06, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [ac861b1ee3](https://bsd-hardware.info/?probe=ac861b1ee3) | Jun 25, 2022 |
| Protectli     | FW6 Ver                     | Desktop     | [598ecb5457](https://bsd-hardware.info/?probe=598ecb5457) | Jun 25, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [a6a5de19ae](https://bsd-hardware.info/?probe=a6a5de19ae) | Jun 23, 2022 |
| HP            | 82A2                        | Desktop     | [77c244bd43](https://bsd-hardware.info/?probe=77c244bd43) | Jun 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a57a2f609c](https://bsd-hardware.info/?probe=a57a2f609c) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| HP            | 1998                        | Desktop     | [1bb67075dd](https://bsd-hardware.info/?probe=1bb67075dd) | Jun 12, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5054729300](https://bsd-hardware.info/?probe=5054729300) | Jun 11, 2022 |
| HP            | 1998                        | Desktop     | [54a6daf0a6](https://bsd-hardware.info/?probe=54a6daf0a6) | Jun 11, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [26cd129290](https://bsd-hardware.info/?probe=26cd129290) | Jun 06, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [f3c197bdfb](https://bsd-hardware.info/?probe=f3c197bdfb) | Jun 04, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8e8ef96421](https://bsd-hardware.info/?probe=8e8ef96421) | Jun 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dce99bec81](https://bsd-hardware.info/?probe=dce99bec81) | Jun 03, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8ca71ddf4d](https://bsd-hardware.info/?probe=8ca71ddf4d) | Jun 02, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [cc70f5d86f](https://bsd-hardware.info/?probe=cc70f5d86f) | Jun 01, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [9d5edd9fa9](https://bsd-hardware.info/?probe=9d5edd9fa9) | May 29, 2022 |
| Dell          | 0M3F6C A01                  | Desktop     | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [c956536edd](https://bsd-hardware.info/?probe=c956536edd) | May 23, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [6d7475e9c9](https://bsd-hardware.info/?probe=6d7475e9c9) | May 22, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [963fa158b5](https://bsd-hardware.info/?probe=963fa158b5) | May 22, 2022 |
| Sophos        | SG                          | Firewall    | [9f76b20afd](https://bsd-hardware.info/?probe=9f76b20afd) | May 22, 2022 |
| Dell          | Studio 1747                 | Notebook    | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [5d31f6f5a8](https://bsd-hardware.info/?probe=5d31f6f5a8) | May 19, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [1014f7f61c](https://bsd-hardware.info/?probe=1014f7f61c) | May 18, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [b74299204a](https://bsd-hardware.info/?probe=b74299204a) | May 18, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [9ec22ea24c](https://bsd-hardware.info/?probe=9ec22ea24c) | May 17, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c7af1dd7bf](https://bsd-hardware.info/?probe=c7af1dd7bf) | May 16, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [30cfcd5004](https://bsd-hardware.info/?probe=30cfcd5004) | May 15, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [44ab2d6faa](https://bsd-hardware.info/?probe=44ab2d6faa) | May 14, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [9af60bd6e4](https://bsd-hardware.info/?probe=9af60bd6e4) | May 14, 2022 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [fd066b2db9](https://bsd-hardware.info/?probe=fd066b2db9) | May 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [0958a64385](https://bsd-hardware.info/?probe=0958a64385) | May 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [0d62d4e3cd](https://bsd-hardware.info/?probe=0d62d4e3cd) | May 09, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [daed3f9401](https://bsd-hardware.info/?probe=daed3f9401) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [cf2f288b93](https://bsd-hardware.info/?probe=cf2f288b93) | May 04, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| HP            | 1495                        | Desktop     | [6e0f1cc72e](https://bsd-hardware.info/?probe=6e0f1cc72e) | Apr 29, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [586d311314](https://bsd-hardware.info/?probe=586d311314) | Apr 28, 2022 |
| HP            | 1998                        | Desktop     | [1244e0583b](https://bsd-hardware.info/?probe=1244e0583b) | Apr 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3d5defed1](https://bsd-hardware.info/?probe=b3d5defed1) | Apr 26, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [2a9ac1e6ee](https://bsd-hardware.info/?probe=2a9ac1e6ee) | Apr 23, 2022 |
| Sophos        | SG                          | Firewall    | [cbd2585bf3](https://bsd-hardware.info/?probe=cbd2585bf3) | Apr 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [4166c67369](https://bsd-hardware.info/?probe=4166c67369) | Apr 20, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [01945539d9](https://bsd-hardware.info/?probe=01945539d9) | Apr 17, 2022 |
| Sophos        | SG                          | Firewall    | [ed297e4274](https://bsd-hardware.info/?probe=ed297e4274) | Apr 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [979e868c51](https://bsd-hardware.info/?probe=979e868c51) | Apr 16, 2022 |
| Dell          | 0DXJD9 A01                  | Desktop     | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [29be552d6a](https://bsd-hardware.info/?probe=29be552d6a) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [1173feae11](https://bsd-hardware.info/?probe=1173feae11) | Apr 13, 2022 |
| Alienware     | 049PDM A00                  | Desktop     | [6dac56f3bb](https://bsd-hardware.info/?probe=6dac56f3bb) | Apr 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [641d1574ce](https://bsd-hardware.info/?probe=641d1574ce) | Apr 11, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| HP            | 8103 A01                    | Mini pc     | [1fa67a8d17](https://bsd-hardware.info/?probe=1fa67a8d17) | Apr 04, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [e79f120d82](https://bsd-hardware.info/?probe=e79f120d82) | Apr 01, 2022 |
| Dell          | 081N4V A06                  | Server      | [700e5de168](https://bsd-hardware.info/?probe=700e5de168) | Apr 01, 2022 |
| PC Engines    | APU                         | Desktop     | [e266947055](https://bsd-hardware.info/?probe=e266947055) | Mar 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [ef1a743845](https://bsd-hardware.info/?probe=ef1a743845) | Mar 28, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1176fca4ab](https://bsd-hardware.info/?probe=1176fca4ab) | Mar 27, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [fb186da68e](https://bsd-hardware.info/?probe=fb186da68e) | Mar 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [d0e7b62eda](https://bsd-hardware.info/?probe=d0e7b62eda) | Mar 25, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [cf576c571d](https://bsd-hardware.info/?probe=cf576c571d) | Mar 22, 2022 |
| HP            | 213D A01                    | Desktop     | [6baba4f9c1](https://bsd-hardware.info/?probe=6baba4f9c1) | Mar 20, 2022 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [3727ba82af](https://bsd-hardware.info/?probe=3727ba82af) | Mar 19, 2022 |
| ASUSTek       | ET2411_W8                   | All in one  | [b95da98f21](https://bsd-hardware.info/?probe=b95da98f21) | Mar 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [f22a45488b](https://bsd-hardware.info/?probe=f22a45488b) | Mar 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a5fd383c40](https://bsd-hardware.info/?probe=a5fd383c40) | Mar 14, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [6024b9491d](https://bsd-hardware.info/?probe=6024b9491d) | Mar 06, 2022 |
| MSI           | MS-7388                     | Desktop     | [ad8209dbdb](https://bsd-hardware.info/?probe=ad8209dbdb) | Mar 05, 2022 |
| MSI           | MS-7388                     | Desktop     | [a59bca8bde](https://bsd-hardware.info/?probe=a59bca8bde) | Mar 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a6abb45607](https://bsd-hardware.info/?probe=a6abb45607) | Mar 04, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [589f10057f](https://bsd-hardware.info/?probe=589f10057f) | Mar 01, 2022 |
| Intel         | H81U                        | Notebook    | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Dell          | 0GDJXY A00                  | All in one  | [e14fd85d4a](https://bsd-hardware.info/?probe=e14fd85d4a) | Feb 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6b2550968e](https://bsd-hardware.info/?probe=6b2550968e) | Feb 23, 2022 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [5f4e1c30b8](https://bsd-hardware.info/?probe=5f4e1c30b8) | Feb 19, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b69015f0e0](https://bsd-hardware.info/?probe=b69015f0e0) | Feb 16, 2022 |
| PC Engines    | apu4                        | Desktop     | [09f27a0f23](https://bsd-hardware.info/?probe=09f27a0f23) | Feb 14, 2022 |
| Protectli     | FW6                         | Desktop     | [d33b2f1244](https://bsd-hardware.info/?probe=d33b2f1244) | Feb 13, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [04bee98c7e](https://bsd-hardware.info/?probe=04bee98c7e) | Feb 12, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [bd63b06ea9](https://bsd-hardware.info/?probe=bd63b06ea9) | Feb 11, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [12ccb8699b](https://bsd-hardware.info/?probe=12ccb8699b) | Feb 08, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [0d3b560aad](https://bsd-hardware.info/?probe=0d3b560aad) | Feb 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [3dabf0503d](https://bsd-hardware.info/?probe=3dabf0503d) | Feb 08, 2022 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [53abdfa3b1](https://bsd-hardware.info/?probe=53abdfa3b1) | Feb 07, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [1dafdcc71a](https://bsd-hardware.info/?probe=1dafdcc71a) | Feb 05, 2022 |
| Supermicro    | H11DSi                      | Server      | [4e41dc7f8b](https://bsd-hardware.info/?probe=4e41dc7f8b) | Feb 03, 2022 |
| ASRock        | J4105M                      | Desktop     | [09b9d104b9](https://bsd-hardware.info/?probe=09b9d104b9) | Feb 03, 2022 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [342915fccd](https://bsd-hardware.info/?probe=342915fccd) | Feb 03, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [07d565ad8c](https://bsd-hardware.info/?probe=07d565ad8c) | Feb 02, 2022 |
| Dell          | 00NH4P A03                  | Server      | [1fe915b90a](https://bsd-hardware.info/?probe=1fe915b90a) | Feb 01, 2022 |
| ASRock        | J3455B-ITX                  | Desktop     | [83975bd2b1](https://bsd-hardware.info/?probe=83975bd2b1) | Jan 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ff629a490d](https://bsd-hardware.info/?probe=ff629a490d) | Jan 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b17ef7a18](https://bsd-hardware.info/?probe=4b17ef7a18) | Jan 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4df3db0379](https://bsd-hardware.info/?probe=4df3db0379) | Jan 26, 2022 |
| Sophos        | SG                          | Firewall    | [3c6601bf94](https://bsd-hardware.info/?probe=3c6601bf94) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [5ea082ddf9](https://bsd-hardware.info/?probe=5ea082ddf9) | Jan 13, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | Notebook    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| ASUSTek       | P8Z68-M PRO                 | Desktop     | [a0885f4f44](https://bsd-hardware.info/?probe=a0885f4f44) | Jan 10, 2022 |
| Dell          | 0DT021 A02                  | Server      | [d1fdef3d4d](https://bsd-hardware.info/?probe=d1fdef3d4d) | Jan 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7863226bbe](https://bsd-hardware.info/?probe=7863226bbe) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [ded64258b4](https://bsd-hardware.info/?probe=ded64258b4) | Jan 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d607c1d19](https://bsd-hardware.info/?probe=8d607c1d19) | Jan 03, 2022 |
| Toshiba       | TECRA Z40-B                 | Notebook    | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [c183bdd5af](https://bsd-hardware.info/?probe=c183bdd5af) | Jan 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [4848e4009f](https://bsd-hardware.info/?probe=4848e4009f) | Jan 01, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [7d47d0db05](https://bsd-hardware.info/?probe=7d47d0db05) | Dec 30, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [c3884fac44](https://bsd-hardware.info/?probe=c3884fac44) | Dec 30, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [bde74629f9](https://bsd-hardware.info/?probe=bde74629f9) | Dec 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [f4648747b0](https://bsd-hardware.info/?probe=f4648747b0) | Dec 22, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [839eed529d](https://bsd-hardware.info/?probe=839eed529d) | Dec 21, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| HP            | 8103 A01                    | Mini pc     | [0138a82561](https://bsd-hardware.info/?probe=0138a82561) | Dec 18, 2021 |
| Quanta        | 2AC7 011                    | Desktop     | [1a831a1d34](https://bsd-hardware.info/?probe=1a831a1d34) | Dec 18, 2021 |
| HP            | 843B                        | Desktop     | [f0d279747f](https://bsd-hardware.info/?probe=f0d279747f) | Dec 13, 2021 |
| HP            | 843B                        | Desktop     | [56400d3999](https://bsd-hardware.info/?probe=56400d3999) | Dec 13, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [624041b5db](https://bsd-hardware.info/?probe=624041b5db) | Dec 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [79d9964300](https://bsd-hardware.info/?probe=79d9964300) | Dec 02, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [ccfb8336a0](https://bsd-hardware.info/?probe=ccfb8336a0) | Dec 01, 2021 |
| HP            | 843B                        | Desktop     | [404224439d](https://bsd-hardware.info/?probe=404224439d) | Nov 29, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [7154bea350](https://bsd-hardware.info/?probe=7154bea350) | Nov 27, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [dc9d060c7f](https://bsd-hardware.info/?probe=dc9d060c7f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [49a0a07721](https://bsd-hardware.info/?probe=49a0a07721) | Nov 25, 2021 |
| Supermicro    | X12SCZ-TLN4FA               | Server      | [3debb4fe22](https://bsd-hardware.info/?probe=3debb4fe22) | Nov 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [f922794063](https://bsd-hardware.info/?probe=f922794063) | Nov 22, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1802f6c891](https://bsd-hardware.info/?probe=1802f6c891) | Nov 21, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a26bc8f2b3](https://bsd-hardware.info/?probe=a26bc8f2b3) | Nov 14, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [817cb3e603](https://bsd-hardware.info/?probe=817cb3e603) | Nov 12, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [970387f9d9](https://bsd-hardware.info/?probe=970387f9d9) | Nov 09, 2021 |
| Protectli     | FW6E                        | Desktop     | [ebe5b24dee](https://bsd-hardware.info/?probe=ebe5b24dee) | Nov 08, 2021 |
| Protectli     | FW6E                        | Desktop     | [6c12084410](https://bsd-hardware.info/?probe=6c12084410) | Nov 07, 2021 |
| Unknown       | Unknown                     | Firewall    | [053ec385f8](https://bsd-hardware.info/?probe=053ec385f8) | Nov 04, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [99b5ab3e42](https://bsd-hardware.info/?probe=99b5ab3e42) | Nov 04, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [bf37ad85e7](https://bsd-hardware.info/?probe=bf37ad85e7) | Nov 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [579cf2ac1a](https://bsd-hardware.info/?probe=579cf2ac1a) | Oct 31, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7abc8386ec](https://bsd-hardware.info/?probe=7abc8386ec) | Oct 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| HP            | 843B                        | Desktop     | [9761f29b5e](https://bsd-hardware.info/?probe=9761f29b5e) | Oct 25, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [c3d6cddf87](https://bsd-hardware.info/?probe=c3d6cddf87) | Oct 25, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5c8f3708b1](https://bsd-hardware.info/?probe=5c8f3708b1) | Oct 21, 2021 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [93f9e34d05](https://bsd-hardware.info/?probe=93f9e34d05) | Oct 19, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [77101a00b3](https://bsd-hardware.info/?probe=77101a00b3) | Oct 11, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [3ce8481842](https://bsd-hardware.info/?probe=3ce8481842) | Oct 10, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [cc419789f8](https://bsd-hardware.info/?probe=cc419789f8) | Oct 08, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [00bafc5f7c](https://bsd-hardware.info/?probe=00bafc5f7c) | Oct 03, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [0cc0d2dcb1](https://bsd-hardware.info/?probe=0cc0d2dcb1) | Oct 01, 2021 |
| HP            | 1495                        | Desktop     | [36a5bc62bf](https://bsd-hardware.info/?probe=36a5bc62bf) | Sep 27, 2021 |
| SeeedStudi... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [01e33c8399](https://bsd-hardware.info/?probe=01e33c8399) | Sep 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [ca41aa2f67](https://bsd-hardware.info/?probe=ca41aa2f67) | Sep 23, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [dec23f7ff8](https://bsd-hardware.info/?probe=dec23f7ff8) | Sep 23, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [8dc995488e](https://bsd-hardware.info/?probe=8dc995488e) | Sep 13, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [3b709e37c2](https://bsd-hardware.info/?probe=3b709e37c2) | Sep 12, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1feb22dc52](https://bsd-hardware.info/?probe=1feb22dc52) | Sep 12, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [0e81fce9eb](https://bsd-hardware.info/?probe=0e81fce9eb) | Sep 10, 2021 |
| HP            | 212B                        | Desktop     | [d3894b9f37](https://bsd-hardware.info/?probe=d3894b9f37) | Sep 10, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [df08c4e6d3](https://bsd-hardware.info/?probe=df08c4e6d3) | Sep 09, 2021 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [c64c51359c](https://bsd-hardware.info/?probe=c64c51359c) | Sep 09, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [e960bc2548](https://bsd-hardware.info/?probe=e960bc2548) | Sep 01, 2021 |
| Gigabyte      | H61N-USB3                   | Desktop     | [3dca10264a](https://bsd-hardware.info/?probe=3dca10264a) | Aug 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [70dc185964](https://bsd-hardware.info/?probe=70dc185964) | Aug 25, 2021 |
| HP            | 1589                        | Desktop     | [4d51cc9c4b](https://bsd-hardware.info/?probe=4d51cc9c4b) | Aug 24, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [da3e8986a3](https://bsd-hardware.info/?probe=da3e8986a3) | Aug 22, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [75f3efc215](https://bsd-hardware.info/?probe=75f3efc215) | Aug 18, 2021 |
| Supermicro    | X11SSW-F                    | Server      | [766c25105d](https://bsd-hardware.info/?probe=766c25105d) | Aug 17, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [bd94ad09ef](https://bsd-hardware.info/?probe=bd94ad09ef) | Aug 12, 2021 |
| Lenovo        | ThinkCentre M58e 7268A9U    | Desktop     | [94201b7633](https://bsd-hardware.info/?probe=94201b7633) | Aug 10, 2021 |
| HP            | Notebook                    | Notebook    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | Notebook    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [6da61be169](https://bsd-hardware.info/?probe=6da61be169) | Aug 08, 2021 |
| ZOTAC         | Board                       | Mini pc     | [e441e5484c](https://bsd-hardware.info/?probe=e441e5484c) | Aug 08, 2021 |
| IBM           | 00Y8494                     | Server      | [92ed5993f4](https://bsd-hardware.info/?probe=92ed5993f4) | Aug 07, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [535b577563](https://bsd-hardware.info/?probe=535b577563) | Aug 03, 2021 |
| HP            | ProLiant ML150 G6           | Desktop     | [783c2ba254](https://bsd-hardware.info/?probe=783c2ba254) | Aug 02, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [b434d9bfb8](https://bsd-hardware.info/?probe=b434d9bfb8) | Aug 02, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [4d118404a8](https://bsd-hardware.info/?probe=4d118404a8) | Jul 29, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [1c3ec31075](https://bsd-hardware.info/?probe=1c3ec31075) | Jul 28, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [fc13802cd3](https://bsd-hardware.info/?probe=fc13802cd3) | Jul 19, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [5697d53687](https://bsd-hardware.info/?probe=5697d53687) | Jul 19, 2021 |
| IBM           | 00Y8494                     | Server      | [76a17b83e5](https://bsd-hardware.info/?probe=76a17b83e5) | Jul 19, 2021 |
| Lenovo        | SHARKBAY 0C48431 PRO        | Desktop     | [0a1fa8924e](https://bsd-hardware.info/?probe=0a1fa8924e) | Jul 17, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [b86c2cfc99](https://bsd-hardware.info/?probe=b86c2cfc99) | Jul 16, 2021 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [4bd9c0bbb8](https://bsd-hardware.info/?probe=4bd9c0bbb8) | Jul 11, 2021 |
| PC Engines    | apu4                        | Desktop     | [51163b13ef](https://bsd-hardware.info/?probe=51163b13ef) | Jul 11, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [59a1b5f761](https://bsd-hardware.info/?probe=59a1b5f761) | Jul 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f07b30b043](https://bsd-hardware.info/?probe=f07b30b043) | Jul 03, 2021 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d4f6eea56a](https://bsd-hardware.info/?probe=d4f6eea56a) | Jun 27, 2021 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [a326fd4061](https://bsd-hardware.info/?probe=a326fd4061) | Jun 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ef7104e237](https://bsd-hardware.info/?probe=ef7104e237) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX H370-I GAMING     | Desktop     | [d2dd261a2a](https://bsd-hardware.info/?probe=d2dd261a2a) | Jun 20, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [6aa5f8046e](https://bsd-hardware.info/?probe=6aa5f8046e) | Jun 19, 2021 |
| Dell          | Inspiron 15-7579            | Notebook    | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| Shuttle       | FS110                       | Desktop     | [9b4093c9a1](https://bsd-hardware.info/?probe=9b4093c9a1) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | Notebook    | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [34df628c87](https://bsd-hardware.info/?probe=34df628c87) | Jun 14, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [83cf0bb0fb](https://bsd-hardware.info/?probe=83cf0bb0fb) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [459bf008e9](https://bsd-hardware.info/?probe=459bf008e9) | Jun 12, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [d09c80b4d4](https://bsd-hardware.info/?probe=d09c80b4d4) | Jun 11, 2021 |
| HP            | 805D                        | Desktop     | [dc4e61ecd4](https://bsd-hardware.info/?probe=dc4e61ecd4) | Jun 07, 2021 |
| HP            | 8523 A01                    | Mini pc     | [d563d65a91](https://bsd-hardware.info/?probe=d563d65a91) | Jun 05, 2021 |
| HP            | 1998                        | Desktop     | [2806e1e8cf](https://bsd-hardware.info/?probe=2806e1e8cf) | Jun 05, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95a281e2f8](https://bsd-hardware.info/?probe=95a281e2f8) | Jun 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [65dd81d59e](https://bsd-hardware.info/?probe=65dd81d59e) | Jun 02, 2021 |
| HP            | 8103 A01                    | Mini pc     | [93a434d951](https://bsd-hardware.info/?probe=93a434d951) | Jun 01, 2021 |
| Apple         | PowerBook5,2                | Notebook    | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [1cd4e4b333](https://bsd-hardware.info/?probe=1cd4e4b333) | May 28, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5d64699270](https://bsd-hardware.info/?probe=5d64699270) | May 28, 2021 |
| HP            | 8103 A01                    | Mini pc     | [df43b9c68e](https://bsd-hardware.info/?probe=df43b9c68e) | May 26, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [fbfd0e7969](https://bsd-hardware.info/?probe=fbfd0e7969) | May 21, 2021 |
| Protectli     | FW4B Ver                    | Desktop     | [7e013ea910](https://bsd-hardware.info/?probe=7e013ea910) | May 20, 2021 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [e6a555b397](https://bsd-hardware.info/?probe=e6a555b397) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [f90e5f9566](https://bsd-hardware.info/?probe=f90e5f9566) | May 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e67de92cb9](https://bsd-hardware.info/?probe=e67de92cb9) | May 14, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [273e379d9f](https://bsd-hardware.info/?probe=273e379d9f) | May 14, 2021 |
| Shuttle       | FS110                       | Desktop     | [e39173782f](https://bsd-hardware.info/?probe=e39173782f) | May 08, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [1f78fbb36c](https://bsd-hardware.info/?probe=1f78fbb36c) | May 08, 2021 |
| Dell          | Latitude 3440               | Notebook    | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5a128dd6a3](https://bsd-hardware.info/?probe=5a128dd6a3) | Apr 22, 2021 |
| HP            | 8523 A01                    | Mini pc     | [dde68fc65d](https://bsd-hardware.info/?probe=dde68fc65d) | Apr 22, 2021 |
| HP            | 18E7                        | Desktop     | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7a6f106b0e](https://bsd-hardware.info/?probe=7a6f106b0e) | Apr 18, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [cd0467031a](https://bsd-hardware.info/?probe=cd0467031a) | Apr 17, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [5a1a372153](https://bsd-hardware.info/?probe=5a1a372153) | Apr 16, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [31a9bf167b](https://bsd-hardware.info/?probe=31a9bf167b) | Apr 16, 2021 |
| Dell          | 051FJ8 A01                  | Desktop     | [351b13fd3b](https://bsd-hardware.info/?probe=351b13fd3b) | Apr 15, 2021 |
| ASRock        | J4105M                      | Desktop     | [69165e1573](https://bsd-hardware.info/?probe=69165e1573) | Apr 13, 2021 |
| HP            | 8523 A01                    | Mini pc     | [f4e8e7e7e8](https://bsd-hardware.info/?probe=f4e8e7e7e8) | Apr 11, 2021 |
| HP            | 1495                        | Desktop     | [5aca6c03c1](https://bsd-hardware.info/?probe=5aca6c03c1) | Apr 09, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [5950dfc99a](https://bsd-hardware.info/?probe=5950dfc99a) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [0e814e53e9](https://bsd-hardware.info/?probe=0e814e53e9) | Apr 09, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [817ec0a0da](https://bsd-hardware.info/?probe=817ec0a0da) | Apr 09, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [6f4f9fb14e](https://bsd-hardware.info/?probe=6f4f9fb14e) | Apr 07, 2021 |
| Dell          | 072XWF A01                  | Server      | [77f48d8337](https://bsd-hardware.info/?probe=77f48d8337) | Apr 07, 2021 |
| Dell          | Latitude 3440               | Notebook    | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| HP            | 2AF7                        | Desktop     | [acd341147c](https://bsd-hardware.info/?probe=acd341147c) | Apr 03, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [39d86447b4](https://bsd-hardware.info/?probe=39d86447b4) | Mar 31, 2021 |
| Dell          | 0TTDMJ A00                  | Desktop     | [b5c0428c8a](https://bsd-hardware.info/?probe=b5c0428c8a) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [6af0a9bc78](https://bsd-hardware.info/?probe=6af0a9bc78) | Mar 30, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [aaf140005c](https://bsd-hardware.info/?probe=aaf140005c) | Mar 30, 2021 |
| AMI           | Cherry Trail CR             | Desktop     | [636dfb334b](https://bsd-hardware.info/?probe=636dfb334b) | Mar 29, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [bb65d06888](https://bsd-hardware.info/?probe=bb65d06888) | Mar 28, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [a48a515986](https://bsd-hardware.info/?probe=a48a515986) | Mar 24, 2021 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [a951f7ffe4](https://bsd-hardware.info/?probe=a951f7ffe4) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | 0M9KCM A00                  | Desktop     | [7280d52eff](https://bsd-hardware.info/?probe=7280d52eff) | Mar 23, 2021 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [061ad76c0e](https://bsd-hardware.info/?probe=061ad76c0e) | Mar 20, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [03935b2745](https://bsd-hardware.info/?probe=03935b2745) | Mar 20, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [27cb6a75c8](https://bsd-hardware.info/?probe=27cb6a75c8) | Mar 19, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8964a02114](https://bsd-hardware.info/?probe=8964a02114) | Mar 15, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [b13ee482e8](https://bsd-hardware.info/?probe=b13ee482e8) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e9ca160a2d](https://bsd-hardware.info/?probe=e9ca160a2d) | Mar 11, 2021 |
| Shuttle       | FS110                       | Desktop     | [fc31311d01](https://bsd-hardware.info/?probe=fc31311d01) | Mar 10, 2021 |
| Unknown       | Unknown                     | Firewall    | [7b7714416c](https://bsd-hardware.info/?probe=7b7714416c) | Mar 09, 2021 |
| Alienware     | 14                          | Notebook    | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Supermicro    | A2SDi-TP8F                  | Desktop     | [c30d805062](https://bsd-hardware.info/?probe=c30d805062) | Mar 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [c7b0539b99](https://bsd-hardware.info/?probe=c7b0539b99) | Mar 02, 2021 |
| IBM           | 94Y7614                     | Server      | [7515ccaa7a](https://bsd-hardware.info/?probe=7515ccaa7a) | Mar 01, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [48dfa4a5f6](https://bsd-hardware.info/?probe=48dfa4a5f6) | Mar 01, 2021 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [fc4265eb19](https://bsd-hardware.info/?probe=fc4265eb19) | Feb 24, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [9d35f9e853](https://bsd-hardware.info/?probe=9d35f9e853) | Feb 24, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [dbf040e5a8](https://bsd-hardware.info/?probe=dbf040e5a8) | Feb 22, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [11d6c98009](https://bsd-hardware.info/?probe=11d6c98009) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | Notebook    | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Protectli     | FW6                         | Desktop     | [b656792690](https://bsd-hardware.info/?probe=b656792690) | Feb 20, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cfd1824b40](https://bsd-hardware.info/?probe=cfd1824b40) | Feb 18, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [4c7959ac6e](https://bsd-hardware.info/?probe=4c7959ac6e) | Feb 17, 2021 |
| Gigabyte      | MRZNVMS-00                  | Desktop     | [b51cb672a4](https://bsd-hardware.info/?probe=b51cb672a4) | Feb 12, 2021 |
| Lenovo        | ThinkPad T410 253722U       | Notebook    | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3402eabdbf](https://bsd-hardware.info/?probe=3402eabdbf) | Feb 09, 2021 |
| Intel         | H81U                        | Notebook    | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [5a5119a395](https://bsd-hardware.info/?probe=5a5119a395) | Feb 06, 2021 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [9b50d422e3](https://bsd-hardware.info/?probe=9b50d422e3) | Feb 04, 2021 |
| Supermicro    | X8DT6                       | Server      | [6acb4d8445](https://bsd-hardware.info/?probe=6acb4d8445) | Feb 04, 2021 |
| HP            | 0AECh D                     | Desktop     | [6dde87584c](https://bsd-hardware.info/?probe=6dde87584c) | Feb 04, 2021 |
| HP            | 829A                        | Mini pc     | [ede207c6df](https://bsd-hardware.info/?probe=ede207c6df) | Feb 04, 2021 |
| PC Engines    | apu4                        | Desktop     | [18dfb34a97](https://bsd-hardware.info/?probe=18dfb34a97) | Feb 04, 2021 |
| HP            | 3397                        | Desktop     | [cda4af23ee](https://bsd-hardware.info/?probe=cda4af23ee) | Feb 03, 2021 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [0a48224f4b](https://bsd-hardware.info/?probe=0a48224f4b) | Feb 03, 2021 |
| HP            | 3397                        | Desktop     | [65f1db2a70](https://bsd-hardware.info/?probe=65f1db2a70) | Feb 03, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [efe09d459a](https://bsd-hardware.info/?probe=efe09d459a) | Jan 31, 2021 |
| Dell          | 086HF8 A08                  | Server      | [1d5c769e0f](https://bsd-hardware.info/?probe=1d5c769e0f) | Jan 31, 2021 |
| HP            | 82B4                        | Desktop     | [faf58d8f87](https://bsd-hardware.info/?probe=faf58d8f87) | Jan 30, 2021 |
| Lenovo        | 30D9 No DPK                 | Desktop     | [12056c71ad](https://bsd-hardware.info/?probe=12056c71ad) | Jan 30, 2021 |
| PC Engines    | APU2                        | Desktop     | [7e96c61bf9](https://bsd-hardware.info/?probe=7e96c61bf9) | Jan 30, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [0147020401](https://bsd-hardware.info/?probe=0147020401) | Jan 30, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [65bde09c13](https://bsd-hardware.info/?probe=65bde09c13) | Jan 26, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [0a4d4fc896](https://bsd-hardware.info/?probe=0a4d4fc896) | Jan 25, 2021 |
| Dell          | 086HF8 A08                  | Server      | [f2eb601b2a](https://bsd-hardware.info/?probe=f2eb601b2a) | Jan 25, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [e8496a6202](https://bsd-hardware.info/?probe=e8496a6202) | Jan 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [da6e3cd1a6](https://bsd-hardware.info/?probe=da6e3cd1a6) | Jan 23, 2021 |
| Supermicro    | X8DT6                       | Server      | [b24cc06305](https://bsd-hardware.info/?probe=b24cc06305) | Jan 22, 2021 |
| PC Engines    | APU2                        | Desktop     | [3d536a42eb](https://bsd-hardware.info/?probe=3d536a42eb) | Jan 21, 2021 |
| PC Engines    | APU2                        | Desktop     | [043446a653](https://bsd-hardware.info/?probe=043446a653) | Jan 21, 2021 |
| Shuttle       | FS110                       | Desktop     | [fed17a1f77](https://bsd-hardware.info/?probe=fed17a1f77) | Jan 21, 2021 |
| Supermicro    | X8DTH                       | Server      | [9ea2aeeb86](https://bsd-hardware.info/?probe=9ea2aeeb86) | Jan 20, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7cda964f76](https://bsd-hardware.info/?probe=7cda964f76) | Jan 20, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [1cc5f6a07b](https://bsd-hardware.info/?probe=1cc5f6a07b) | Jan 20, 2021 |
| Dell          | 086HF8 A08                  | Server      | [b087a1d9d2](https://bsd-hardware.info/?probe=b087a1d9d2) | Jan 20, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [8c55004504](https://bsd-hardware.info/?probe=8c55004504) | Jan 19, 2021 |
| Intel         | S1200RP_SE G62252-406       | Server      | [49ad4461dc](https://bsd-hardware.info/?probe=49ad4461dc) | Jan 16, 2021 |
| Supermicro    | C7Z170-OCEB                 | Server      | [9f6632de8b](https://bsd-hardware.info/?probe=9f6632de8b) | Jan 10, 2021 |
| Supermicro    | X7SLA                       | Desktop     | [2d31f38bf0](https://bsd-hardware.info/?probe=2d31f38bf0) | Jan 10, 2021 |
| Supermicro    | X7SPA-HF                    | Desktop     | [834cb6c68a](https://bsd-hardware.info/?probe=834cb6c68a) | Jan 10, 2021 |
| Alienware     | 14                          | Notebook    | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | Notebook    | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| MSI           | X58 Pro-E                   | Desktop     | [bd108f94d5](https://bsd-hardware.info/?probe=bd108f94d5) | Jan 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| HP            | 212B                        | Desktop     | [7fe9d2c508](https://bsd-hardware.info/?probe=7fe9d2c508) | Dec 18, 2020 |
| Dell          | 0GM819                      | Desktop     | [adc8eb1931](https://bsd-hardware.info/?probe=adc8eb1931) | Dec 18, 2020 |
| HP            | 805D                        | Desktop     | [dc62857275](https://bsd-hardware.info/?probe=dc62857275) | Dec 17, 2020 |
| Supermicro    | X8STi                       | Desktop     | [80c2762cfb](https://bsd-hardware.info/?probe=80c2762cfb) | Dec 16, 2020 |
| ASRockRack    | D1541D4U-2O8R               | Desktop     | [d59d8a3b6d](https://bsd-hardware.info/?probe=d59d8a3b6d) | Dec 16, 2020 |
| Supermicro    | X11SSH-F                    | Desktop     | [ebb920c0c4](https://bsd-hardware.info/?probe=ebb920c0c4) | Dec 16, 2020 |
| MSI           | X99S SLI PLUS               | Desktop     | [9b2421d9d5](https://bsd-hardware.info/?probe=9b2421d9d5) | Nov 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [002b408f7e](https://bsd-hardware.info/?probe=002b408f7e) | Nov 18, 2020 |
| Lenovo        | ThinkPad T440 20B7S0A800    | Notebook    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fd37374e7b](https://bsd-hardware.info/?probe=fd37374e7b) | Nov 11, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | Notebook    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [714b6539cf](https://bsd-hardware.info/?probe=714b6539cf) | Nov 07, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9f871ab960](https://bsd-hardware.info/?probe=9f871ab960) | Nov 01, 2020 |
| Intel         | X79 V2.81A                  | Desktop     | [d5b4cdf28a](https://bsd-hardware.info/?probe=d5b4cdf28a) | Oct 30, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [59c940d739](https://bsd-hardware.info/?probe=59c940d739) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8552669e76](https://bsd-hardware.info/?probe=8552669e76) | Oct 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [50966c2f83](https://bsd-hardware.info/?probe=50966c2f83) | Oct 30, 2020 |
| Dell          | 0YFVT1 A06                  | Server      | [fca49dda17](https://bsd-hardware.info/?probe=fca49dda17) | Oct 29, 2020 |
| ADI Engine... | RCC-VE                      | Desktop     | [30440abc03](https://bsd-hardware.info/?probe=30440abc03) | Oct 29, 2020 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [c41d989a06](https://bsd-hardware.info/?probe=c41d989a06) | Oct 28, 2020 |
| IBM           | Board                       | Desktop     | [11b0b7012f](https://bsd-hardware.info/?probe=11b0b7012f) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [a92c08a920](https://bsd-hardware.info/?probe=a92c08a920) | Oct 21, 2020 |
| IBM           | Board                       | Desktop     | [80d5f15a63](https://bsd-hardware.info/?probe=80d5f15a63) | Oct 21, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | Notebook    | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | Notebook    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | Notebook    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| MSI           | MS-7250                     | Desktop     | [41e2d9dab3](https://bsd-hardware.info/?probe=41e2d9dab3) | Sep 04, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| HP            | 3031h                       | Desktop     | [1f2695b3a7](https://bsd-hardware.info/?probe=1f2695b3a7) | Aug 25, 2020 |
| Acer          | AOD270                      | Notebook    | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [49e01a949b](https://bsd-hardware.info/?probe=49e01a949b) | Jul 29, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [0f7697b73a](https://bsd-hardware.info/?probe=0f7697b73a) | May 28, 2020 |
| Dell          | 0T10XW A02                  | Desktop     | [81f39f3061](https://bsd-hardware.info/?probe=81f39f3061) | May 28, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | Notebook    | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | Notebook    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | Notebook    | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Canada/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 23.1.11  | 17        | 2.63%   |
| OpenBSD 7.2       | 17        | 2.63%   |
| helloSystem 0.7.0 | 17        | 2.63%   |
| OPNsense 23.1     | 14        | 2.17%   |
| OPNsense 22.7.10  | 14        | 2.17%   |
| OpenBSD 7.3       | 14        | 2.17%   |
| OpenBSD 7.1       | 13        | 2.01%   |
| OPNsense 23.7.3   | 12        | 1.86%   |
| OPNsense 23.1.6   | 12        | 1.86%   |
| OPNsense 23.1.1   | 12        | 1.86%   |
| OPNsense 22.1.10  | 12        | 1.86%   |
| OPNsense 21.1.4   | 12        | 1.86%   |
| OPNsense 21.1     | 12        | 1.86%   |
| helloSystem 0.8.1 | 12        | 1.86%   |
| helloSystem 0.5.0 | 11        | 1.7%    |
| OPNsense 23.7.1   | 10        | 1.55%   |
| OPNsense 23.1.9   | 10        | 1.55%   |
| OPNsense 22.7.8   | 10        | 1.55%   |
| OPNsense 22.7.4   | 10        | 1.55%   |
| OPNsense 22.1.7   | 10        | 1.55%   |
| OPNsense 22.1.6   | 10        | 1.55%   |
| OPNsense 21.1.3   | 10        | 1.55%   |
| FreeBSD 13.1-p5   | 10        | 1.55%   |
| OPNsense 22.7     | 9         | 1.39%   |
| OPNsense 22.1     | 9         | 1.39%   |
| OPNsense 21.1.6   | 9         | 1.39%   |
| OpenBSD 7.0       | 9         | 1.39%   |
| OpenBSD 6.9       | 9         | 1.39%   |
| FreeBSD 12.2      | 9         | 1.39%   |
| OPNsense 22.1.8   | 8         | 1.24%   |
| OPNsense 21.7.7   | 8         | 1.24%   |
| OPNsense 21.7.1   | 8         | 1.24%   |
| OPNsense 21.1.5   | 8         | 1.24%   |
| OpenBSD 6.8       | 8         | 1.24%   |
| helloSystem 0.8.0 | 8         | 1.24%   |
| OPNsense 22.7.9   | 7         | 1.08%   |
| OPNsense 21.7     | 7         | 1.08%   |
| FreeBSD 13.1      | 7         | 1.08%   |
| FreeBSD 13.0      | 7         | 1.08%   |
| OPNsense 22.7.11  | 6         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 270       | 59.73%  |
| FreeBSD     | 91        | 20.13%  |
| helloSystem | 51        | 11.28%  |
| OpenBSD     | 25        | 5.53%   |
| GhostBSD    | 7         | 1.55%   |
| FreeNAS     | 3         | 0.66%   |
| TrueNAS     | 2         | 0.44%   |
| pfSense     | 1         | 0.22%   |
| NetBSD      | 1         | 0.22%   |
| MyBee       | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 441       | 98.22%  |
| i386   | 5         | 1.11%   |
| macppc | 2         | 0.45%   |
| arm64  | 1         | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 310       | 67.1%   |
| helloDesktop | 69        | 14.94%  |
| XFCE         | 19        | 4.11%   |
| KDE5         | 14        | 3.03%   |
| fvwm         | 12        | 2.6%    |
| MATE         | 9         | 1.95%   |
| GNOME        | 7         | 1.52%   |
| TWM          | 5         | 1.08%   |
| Openbox      | 4         | 0.87%   |
| Cinnamon     | 3         | 0.65%   |
| LXQt         | 2         | 0.43%   |
| i3           | 2         | 0.43%   |
| X-Cinnamon   | 1         | 0.22%   |
| Window Maker | 1         | 0.22%   |
| LXDE         | 1         | 0.22%   |
| Lumina       | 1         | 0.22%   |
| Fluxbox      | 1         | 0.22%   |
| DWM          | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 310       | 69.04%  |
| X11     | 136       | 30.29%  |
| Wayland | 3         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 352       | 77.53%  |
| SLiM    | 56        | 12.33%  |
| SDDM    | 17        | 3.74%   |
| LightDM | 12        | 2.64%   |
| XDM     | 10        | 2.2%    |
| GDM     | 6         | 1.32%   |
| Ly      | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 320       | 70.33%  |
| en_US   | 66        | 14.51%  |
| C       | 46        | 10.11%  |
| en_CA   | 11        | 2.42%   |
| fr_FR   | 5         | 1.1%    |
| en      | 3         | 0.66%   |
| fr      | 2         | 0.44%   |
| fr_CA   | 1         | 0.22%   |
| en_NL   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 373       | 82.16%  |
| BIOS | 81        | 17.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 224       | 48.28%  |
| Zfs     | 191       | 41.16%  |
| Ffs     | 25        | 5.39%   |
| Cd9660  | 23        | 4.96%   |
| Unknown | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 409       | 91.09%  |
| MBR     | 36        | 8.02%   |
| Unknown | 4         | 0.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 58        | 12.92%  |
| Lenovo                         | 52        | 11.58%  |
| Hewlett-Packard                | 50        | 11.14%  |
| ASUSTek Computer               | 44        | 9.8%    |
| Unknown                        | 29        | 6.46%   |
| Intel                          | 28        | 6.24%   |
| Supermicro                     | 23        | 5.12%   |
| Protectli                      | 21        | 4.68%   |
| Gigabyte Technology            | 15        | 3.34%   |
| ASRock                         | 13        | 2.9%    |
| MSI                            | 12        | 2.67%   |
| Techvision                     | 10        | 2.23%   |
| Acer                           | 10        | 2.23%   |
| AZW                            | 7         | 1.56%   |
| AMI                            | 7         | 1.56%   |
| PC Engines                     | 6         | 1.34%   |
| ZOTAC                          | 5         | 1.11%   |
| AWOW                           | 5         | 1.11%   |
| Apple                          | 5         | 1.11%   |
| Toshiba                        | 3         | 0.67%   |
| Panasonic                      | 3         | 0.67%   |
| IBM                            | 3         | 0.67%   |
| Sophos                         | 2         | 0.45%   |
| Shuttle                        | 2         | 0.45%   |
| MW                             | 2         | 0.45%   |
| Matsushita Electric Industrial | 2         | 0.45%   |
| Google                         | 2         | 0.45%   |
| Datto                          | 2         | 0.45%   |
| CncTion                        | 2         | 0.45%   |
| ASRockRack                     | 2         | 0.45%   |
| Alienware                      | 2         | 0.45%   |
| Yanling                        | 1         | 0.22%   |
| Star Labs                      | 1         | 0.22%   |
| ShenZhen MinWin Technology     | 1         | 0.22%   |
| SeeedStudio                    | 1         | 0.22%   |
| ReachingTech                   | 1         | 0.22%   |
| Raspberry Pi Foundation        | 1         | 0.22%   |
| Quanta                         | 1         | 0.22%   |
| Pegatron                       | 1         | 0.22%   |
| MiTAC                          | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 30        | 6.68%   |
| Protectli FW4B                     | 11        | 2.45%   |
| Techvision TVI7309X                | 10        | 2.23%   |
| Protectli FW6                      | 6         | 1.34%   |
| Intel Q3XXG4-P V1.0                | 6         | 1.34%   |
| Supermicro Super Server            | 5         | 1.11%   |
| AWOW PC BOX                        | 5         | 1.11%   |
| Intel NDISB533                     | 4         | 0.89%   |
| HP EliteDesk 800 G1 SFF            | 4         | 0.89%   |
| Dell OptiPlex 9010                 | 4         | 0.89%   |
| AZW U59                            | 4         | 0.89%   |
| AMI Aptio CRB                      | 4         | 0.89%   |
| PC Engines APU2                    | 3         | 0.67%   |
| Intel H81U                         | 3         | 0.67%   |
| HP Z440 Workstation                | 3         | 0.67%   |
| HP t730 Thin Client                | 3         | 0.67%   |
| HP Compaq 8200 Elite SFF PC        | 3         | 0.67%   |
| HP Compaq 6200 Pro MT PC           | 3         | 0.67%   |
| Dell OptiPlex 7010                 | 3         | 0.67%   |
| ASUS All Series                    | 3         | 0.67%   |
| ZOTAC ZBOX-CI323NANO               | 2         | 0.45%   |
| Supermicro X8STi                   | 2         | 0.45%   |
| Supermicro SYS-E300-9A             | 2         | 0.45%   |
| Protectli VP2420                   | 2         | 0.45%   |
| PC Engines apu4                    | 2         | 0.45%   |
| MW GMLK-2_5G4L                     | 2         | 0.45%   |
| MSI MS-7A40                        | 2         | 0.45%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2         | 0.45%   |
| Intel CRESCENTBAY                  | 2         | 0.45%   |
| HP Compaq Elite 8300 SFF           | 2         | 0.45%   |
| HP 500-459                         | 2         | 0.45%   |
| Dell Precision WorkStation T3500   | 2         | 0.45%   |
| Dell Precision Tower 5810          | 2         | 0.45%   |
| Dell PowerEdge R210 II             | 2         | 0.45%   |
| Dell PowerEdge R210                | 2         | 0.45%   |
| Dell OptiPlex 7060                 | 2         | 0.45%   |
| Dell OptiPlex 7050                 | 2         | 0.45%   |
| Dell OptiPlex 7020                 | 2         | 0.45%   |
| Dell OptiPlex 3060                 | 2         | 0.45%   |
| Dell OptiPlex 3020                 | 2         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 30        | 6.68%   |
| Dell OptiPlex          | 26        | 5.79%   |
| Lenovo ThinkCentre     | 25        | 5.57%   |
| Lenovo ThinkPad        | 24        | 5.35%   |
| Dell PowerEdge         | 12        | 2.67%   |
| Protectli FW4B         | 11        | 2.45%   |
| Techvision TVI7309X    | 10        | 2.23%   |
| HP Compaq              | 10        | 2.23%   |
| ASUS PRIME             | 9         | 2%      |
| HP EliteDesk           | 8         | 1.78%   |
| HP ProDesk             | 7         | 1.56%   |
| Acer Aspire            | 7         | 1.56%   |
| Protectli FW6          | 6         | 1.34%   |
| Intel Q3XXG4-P         | 6         | 1.34%   |
| Dell Precision         | 6         | 1.34%   |
| Dell Inspiron          | 6         | 1.34%   |
| ASUS ROG               | 6         | 1.34%   |
| Supermicro Super       | 5         | 1.11%   |
| AWOW PC                | 5         | 1.11%   |
| Intel NDISB533         | 4         | 0.89%   |
| AZW U59                | 4         | 0.89%   |
| AMI Aptio              | 4         | 0.89%   |
| PC Engines APU2        | 3         | 0.67%   |
| Intel H81U             | 3         | 0.67%   |
| HP Z440                | 3         | 0.67%   |
| HP t730                | 3         | 0.67%   |
| HP ProLiant            | 3         | 0.67%   |
| HP Pavilion            | 3         | 0.67%   |
| Dell Latitude          | 3         | 0.67%   |
| ASUS TUF               | 3         | 0.67%   |
| ASUS All               | 3         | 0.67%   |
| ASRock B450M           | 3         | 0.67%   |
| ZOTAC ZBOX-CI323NANO   | 2         | 0.45%   |
| Toshiba Satellite      | 2         | 0.45%   |
| Supermicro X8STi       | 2         | 0.45%   |
| Supermicro SYS-E300-9A | 2         | 0.45%   |
| Protectli VP2420       | 2         | 0.45%   |
| PC Engines apu4        | 2         | 0.45%   |
| MW GMLK-2              | 2         | 0.45%   |
| MSI MS-7A40            | 2         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 59        | 13.14%  |
| 2022    | 47        | 10.47%  |
| 2020    | 43        | 9.58%   |
| 2014    | 35        | 7.8%    |
| 2016    | 30        | 6.68%   |
| 2019    | 29        | 6.46%   |
| 2011    | 27        | 6.01%   |
| 2010    | 26        | 5.79%   |
| 2021    | 25        | 5.57%   |
| 2015    | 24        | 5.35%   |
| 2013    | 24        | 5.35%   |
| 2012    | 22        | 4.9%    |
| 2017    | 17        | 3.79%   |
| 2009    | 13        | 2.9%    |
| 2023    | 11        | 2.45%   |
| 2008    | 8         | 1.78%   |
| Unknown | 4         | 0.89%   |
| 2007    | 2         | 0.45%   |
| 2006    | 2         | 0.45%   |
| 2002    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 296       | 65.92%  |
| Notebook       | 81        | 18.04%  |
| Mini pc        | 35        | 7.8%    |
| Server         | 29        | 6.46%   |
| Firewall       | 4         | 0.89%   |
| All in one     | 3         | 0.67%   |
| System on chip | 1         | 0.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 437       | 97.33%  |
| Yes  | 12        | 2.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 169       | 36.9%   |
| 16.01-24.0      | 100       | 21.83%  |
| 4.01-8.0        | 80        | 17.47%  |
| 32.01-64.0      | 48        | 10.48%  |
| 64.01-256.0     | 22        | 4.8%    |
| 2.01-3.0        | 14        | 3.06%   |
| 3.01-4.0        | 11        | 2.4%    |
| 24.01-32.0      | 7         | 1.53%   |
| 1.01-2.0        | 3         | 0.66%   |
| 0.51-1.0        | 3         | 0.66%   |
| More than 256.0 | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 227       | 49.35%  |
| 0.51-1.0    | 140       | 30.43%  |
| 1.01-2.0    | 55        | 11.96%  |
| 2.01-3.0    | 10        | 2.17%   |
| 4.01-8.0    | 8         | 1.74%   |
| 3.01-4.0    | 7         | 1.52%   |
| 0           | 4         | 0.87%   |
| 24.01-32.0  | 3         | 0.65%   |
| 64.01-256.0 | 2         | 0.43%   |
| 8.01-16.0   | 2         | 0.43%   |
| 32.01-64.0  | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 320       | 69.57%  |
| 2      | 63        | 13.7%   |
| 0      | 36        | 7.83%   |
| 3      | 19        | 4.13%   |
| 4      | 9         | 1.96%   |
| 13     | 2         | 0.43%   |
| 7      | 2         | 0.43%   |
| 5      | 2         | 0.43%   |
| 58     | 1         | 0.22%   |
| 40     | 1         | 0.22%   |
| 25     | 1         | 0.22%   |
| 16     | 1         | 0.22%   |
| 14     | 1         | 0.22%   |
| 10     | 1         | 0.22%   |
| 6      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 354       | 77.63%  |
| Yes       | 102       | 22.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 438       | 97.33%  |
| No        | 12        | 2.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 294       | 64.76%  |
| Yes       | 160       | 35.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 334       | 73.89%  |
| Yes       | 118       | 26.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 449       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 57        | 11.38%  |
| Toronto           | 44        | 8.78%   |
| Calgary           | 30        | 5.99%   |
| Victoria          | 19        | 3.79%   |
| Ottawa            | 19        | 3.79%   |
| Edmonton          | 19        | 3.79%   |
| Vancouver         | 15        | 2.99%   |
| Saint-Laurent     | 14        | 2.79%   |
| Winnipeg          | 12        | 2.4%    |
| Brampton          | 11        | 2.2%    |
| Surrey            | 10        | 2%      |
| Kitchener         | 10        | 2%      |
| QuГ©bec         | 6         | 1.2%    |
| Québec           | 6         | 1.2%    |
| Scarborough       | 5         | 1%      |
| Regina            | 5         | 1%      |
| Moncton           | 5         | 1%      |
| London            | 5         | 1%      |
| Laval             | 5         | 1%      |
| Cambridge         | 5         | 1%      |
| St. Jean Baptiste | 4         | 0.8%    |
| St. Albert        | 4         | 0.8%    |
| Saskatoon         | 4         | 0.8%    |
| Sainte-Julie      | 4         | 0.8%    |
| Peterborough      | 4         | 0.8%    |
| North Vancouver   | 4         | 0.8%    |
| Kingston          | 4         | 0.8%    |
| Gatineau          | 4         | 0.8%    |
| Burnaby           | 4         | 0.8%    |
| Windsor           | 3         | 0.6%    |
| Sherwood Park     | 3         | 0.6%    |
| Sarnia            | 3         | 0.6%    |
| QuÃ©bec         | 3         | 0.6%    |
| Pierrefonds       | 3         | 0.6%    |
| Oshawa            | 3         | 0.6%    |
| Oakville          | 3         | 0.6%    |
| Nanaimo           | 3         | 0.6%    |
| Mississauga       | 3         | 0.6%    |
| Maple Ridge       | 3         | 0.6%    |
| Longueuil         | 3         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 81        | 135    | 15.61%  |
| WDC                 | 74        | 203    | 14.26%  |
| Kingston            | 58        | 76     | 11.18%  |
| Seagate             | 55        | 127    | 10.6%   |
| Intel               | 25        | 38     | 4.82%   |
| Crucial             | 19        | 29     | 3.66%   |
| A-DATA Technology   | 19        | 34     | 3.66%   |
| Toshiba             | 16        | 30     | 3.08%   |
| SanDisk             | 15        | 19     | 2.89%   |
| Hitachi             | 15        | 58     | 2.89%   |
| Patriot             | 10        | 11     | 1.93%   |
| SPCC                | 9         | 10     | 1.73%   |
| Dogfish             | 9         | 22     | 1.73%   |
| SK hynix            | 7         | 9      | 1.35%   |
| Micron Technology   | 7         | 12     | 1.35%   |
| FORESEE             | 7         | 21     | 1.35%   |
| Transcend           | 6         | 7      | 1.16%   |
| OCZ                 | 6         | 10     | 1.16%   |
| Hewlett-Packard     | 6         | 6      | 1.16%   |
| Hoodisk             | 5         | 6      | 0.96%   |
| HGST                | 5         | 75     | 0.96%   |
| Protectli           | 4         | 5      | 0.77%   |
| Phison              | 4         | 5      | 0.77%   |
| NVMe                | 4         | 5      | 0.77%   |
| Mushkin             | 4         | 5      | 0.77%   |
| BIWIN               | 4         | 6      | 0.77%   |
| PNY                 | 3         | 4      | 0.58%   |
| Lexar               | 3         | 4      | 0.58%   |
| China               | 3         | 6      | 0.58%   |
| VisionTek           | 2         | 6      | 0.39%   |
| Timetec             | 2         | 3      | 0.39%   |
| Team                | 2         | 5      | 0.39%   |
| Silicon Motion      | 2         | 2      | 0.39%   |
| Netac               | 2         | 2      | 0.39%   |
| HPE                 | 2         | 9      | 0.39%   |
| Gigastone           | 2         | 3      | 0.39%   |
| Fujitsu             | 2         | 2      | 0.39%   |
| Corsair             | 2         | 4      | 0.39%   |
| Apacer              | 2         | 2      | 0.39%   |
| ZTC                 | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB     | 17        | 3%      |
| Kingston SA400S37120G 120GB     | 12        | 2.12%   |
| Samsung SSD 850 EVO 250GB       | 7         | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB  | 6         | 1.06%   |
| FORESEE 128GB SSD               | 6         | 1.06%   |
| Seagate ST500DM002-1BD142 500GB | 5         | 0.88%   |
| Seagate ST2000DM008-2FR102 2TB  | 5         | 0.88%   |
| Samsung SSD 860 EVO 500GB       | 5         | 0.88%   |
| Samsung SSD 840 EVO 120GB       | 5         | 0.88%   |
| Dogfish SSD 128GB               | 5         | 0.88%   |
| SPCC Solid State Disk 256GB     | 4         | 0.71%   |
| Samsung SSD 970 EVO Plus 1TB    | 4         | 0.71%   |
| Samsung SSD 850 EVO 500GB       | 4         | 0.71%   |
| BIWIN SSD 128GB                 | 4         | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB    | 3         | 0.53%   |
| WDC WD20EZRX-00DC0B0 2TB        | 3         | 0.53%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3         | 0.53%   |
| Transcend TS256GMSA230S 256GB   | 3         | 0.53%   |
| Toshiba DT01ACA100 1TB          | 3         | 0.53%   |
| Seagate ST3500413AS 500GB       | 3         | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB  | 3         | 0.53%   |
| SanDisk SD6SB1M064G1022I 64GB   | 3         | 0.53%   |
| Samsung SSD 980 1TB             | 3         | 0.53%   |
| Samsung SSD 970 EVO Plus 250GB  | 3         | 0.53%   |
| Samsung SSD 870 EVO 500GB       | 3         | 0.53%   |
| Samsung SSD 850 PRO 256GB       | 3         | 0.53%   |
| Kingston SUV500MS120G 120GB     | 3         | 0.53%   |
| Intel SSDSA2CW120G3 120GB       | 3         | 0.53%   |
| Crucial CT240BX500SSD1 240GB    | 3         | 0.53%   |
| A-DATA SU800 256GB              | 3         | 0.53%   |
| A-DATA SU655 120GB              | 3         | 0.53%   |
| WDC WD7500BPKX-00HPJT0 752GB    | 2         | 0.35%   |
| WDC WD6400AAKS-22A7B2 640GB     | 2         | 0.35%   |
| WDC WD40EFRX-68WT0N0 4TB        | 2         | 0.35%   |
| WDC WD40EFRX-68N32N0 4TB        | 2         | 0.35%   |
| WDC WD30EFRX-68EUZN0 3TB        | 2         | 0.35%   |
| WDC WD120EDAZ-11F3RA0 12TB      | 2         | 0.35%   |
| WDC WD10JPLX-00MBPT0 1TB        | 2         | 0.35%   |
| WDC WD10EZEX-22MFCA0 1TB        | 2         | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB        | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 53        | 170    | 35.33%  |
| Seagate             | 53        | 125    | 35.33%  |
| Hitachi             | 15        | 58     | 10%     |
| Toshiba             | 13        | 25     | 8.67%   |
| HGST                | 5         | 75     | 3.33%   |
| NVMe                | 2         | 3      | 1.33%   |
| Hewlett-Packard     | 2         | 2      | 1.33%   |
| Fujitsu             | 2         | 2      | 1.33%   |
| Samsung Electronics | 1         | 1      | 0.67%   |
| OPENBSD             | 1         | 1      | 0.67%   |
| Lexar               | 1         | 1      | 0.67%   |
| HPT                 | 1         | 1      | 0.67%   |
| HPE                 | 1         | 5      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 102    | 19.87%  |
| Kingston            | 55        | 67     | 18.21%  |
| Intel               | 22        | 35     | 7.28%   |
| A-DATA Technology   | 18        | 33     | 5.96%   |
| Crucial             | 16        | 24     | 5.3%    |
| SanDisk             | 15        | 19     | 4.97%   |
| WDC                 | 12        | 14     | 3.97%   |
| Dogfish             | 9         | 22     | 2.98%   |
| SPCC                | 7         | 8      | 2.32%   |
| Patriot             | 7         | 8      | 2.32%   |
| FORESEE             | 7         | 21     | 2.32%   |
| Transcend           | 6         | 7      | 1.99%   |
| OCZ                 | 6         | 10     | 1.99%   |
| Micron Technology   | 5         | 9      | 1.66%   |
| Hoodisk             | 5         | 6      | 1.66%   |
| Protectli           | 4         | 5      | 1.32%   |
| Mushkin             | 4         | 5      | 1.32%   |
| BIWIN               | 4         | 6      | 1.32%   |
| PNY                 | 3         | 4      | 0.99%   |
| China               | 3         | 6      | 0.99%   |
| VisionTek           | 2         | 6      | 0.66%   |
| SK hynix            | 2         | 2      | 0.66%   |
| Seagate             | 2         | 2      | 0.66%   |
| Netac               | 2         | 2      | 0.66%   |
| Lexar               | 2         | 3      | 0.66%   |
| Hewlett-Packard     | 2         | 2      | 0.66%   |
| Gigastone           | 2         | 3      | 0.66%   |
| Corsair             | 2         | 4      | 0.66%   |
| Apacer              | 2         | 2      | 0.66%   |
| ZTC                 | 1         | 1      | 0.33%   |
| walram              | 1         | 1      | 0.33%   |
| Toshiba             | 1         | 1      | 0.33%   |
| Timetec             | 1         | 1      | 0.33%   |
| Star Drive          | 1         | 1      | 0.33%   |
| SATADOM             | 1         | 2      | 0.33%   |
| Phison              | 1         | 1      | 0.33%   |
| NVMe                | 1         | 1      | 0.33%   |
| LITEON              | 1         | 1      | 0.33%   |
| Kston               | 1         | 2      | 0.33%   |
| KingDian            | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 276       | 459    | 58.35%  |
| HDD  | 127       | 469    | 26.85%  |
| NVMe | 70        | 107    | 14.8%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 370       | 928    | 84.09%  |
| NVMe | 70        | 107    | 15.91%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 302       | 509    | 71.06%  |
| 0.51-1.0   | 64        | 129    | 15.06%  |
| 1.01-2.0   | 27        | 69     | 6.35%   |
| 3.01-4.0   | 12        | 111    | 2.82%   |
| 4.01-10.0  | 9         | 57     | 2.12%   |
| 2.01-3.0   | 6         | 27     | 1.41%   |
| 10.01-20.0 | 5         | 26     | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 187       | 39.45%  |
| 251-500        | 72        | 15.19%  |
| 51-100         | 57        | 12.03%  |
| 1-20           | 56        | 11.81%  |
| 21-50          | 49        | 10.34%  |
| 501-1000       | 35        | 7.38%   |
| 1001-2000      | 11        | 2.32%   |
| Unknown        | 4         | 0.84%   |
| More than 3000 | 3         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 405       | 86.72%  |
| 21-50     | 36        | 7.71%   |
| 51-100    | 11        | 2.36%   |
| 101-250   | 4         | 0.86%   |
| Unknown   | 4         | 0.86%   |
| 501-1000  | 3         | 0.64%   |
| 251-500   | 2         | 0.43%   |
| 1001-2000 | 2         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB                | 2         | 8      | 2.86%   |
| VisionTek mSATA 120GB                      | 2         | 6      | 2.86%   |
| Toshiba MQ01ABD075 752GB                   | 2         | 2      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB            | 2         | 4      | 2.86%   |
| Seagate ST3500413AS 500GB                  | 2         | 4      | 2.86%   |
| Patriot Burst Elite 120GB                  | 2         | 2      | 2.86%   |
| Kingston SNS4151S316GD 16GB                | 2         | 3      | 2.86%   |
| Dogfish SSD 128GB                          | 2         | 4      | 2.86%   |
| WDC WDS200T2B0A 2TB                        | 1         | 1      | 1.43%   |
| WDC WD7500BPKX-00HPJT0 752GB               | 1         | 6      | 1.43%   |
| WDC WD6400BEVT-22A0RT0 640GB               | 1         | 1      | 1.43%   |
| WDC WD50EFRX-68L0BN1 5TB                   | 1         | 1      | 1.43%   |
| WDC WD5003AZEX-00K1GA0 500GB               | 1         | 1      | 1.43%   |
| WDC WD40EFRX-68WT0N0 4TB                   | 1         | 2      | 1.43%   |
| WDC WD30EZRX-22D8PB0 3TB                   | 1         | 1      | 1.43%   |
| WDC WD2500AAKX-001CA0 250GB                | 1         | 1      | 1.43%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1         | 2      | 1.43%   |
| walram SSD 120G                            | 1         | 1      | 1.43%   |
| Toshiba MK1665GSX 160GB                    | 1         | 1      | 1.43%   |
| Toshiba DT01ACA100 1TB                     | 1         | 3      | 1.43%   |
| SPCC Solid State Disk 128GB                | 1         | 1      | 1.43%   |
| Seagate ST9500420AS 500GB                  | 1         | 2      | 1.43%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 1.43%   |
| Seagate ST3250318AS 250GB                  | 1         | 1      | 1.43%   |
| Seagate ST3200822AS 200GB                  | 1         | 1      | 1.43%   |
| Seagate ST3160815AS 160GB                  | 1         | 1      | 1.43%   |
| Seagate ST31500341AS 1.5TB                 | 1         | 2      | 1.43%   |
| Seagate ST3120026A 120GB                   | 1         | 1      | 1.43%   |
| Seagate ST31000520AS 1TB                   | 1         | 1      | 1.43%   |
| Seagate ST2000DL003-9VT166 2TB             | 1         | 4      | 1.43%   |
| Seagate ST1000DM003-1CH162 1TB             | 1         | 2      | 1.43%   |
| Samsung Electronics SSD 970 EVO 2TB        | 1         | 2      | 1.43%   |
| Samsung Electronics SSD 870 EVO 250GB      | 1         | 4      | 1.43%   |
| Samsung Electronics SSD 860 EVO 1TB        | 1         | 3      | 1.43%   |
| Patriot Pyro SE 120GB                      | 1         | 1      | 1.43%   |
| OCZ VERTEX 32GB                            | 1         | 4      | 1.43%   |
| Mushkin MKNSSDEC512GB                      | 1         | 2      | 1.43%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1         | 4      | 1.43%   |
| Kingston SV300S37A60G 64GB                 | 1         | 2      | 1.43%   |
| Kingston SV300S37A120G 120GB               | 1         | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 24     | 19.12%  |
| WDC                 | 11        | 24     | 16.18%  |
| Hitachi             | 7         | 20     | 10.29%  |
| Kingston            | 6         | 8      | 8.82%   |
| Intel               | 5         | 6      | 7.35%   |
| Toshiba             | 4         | 6      | 5.88%   |
| Patriot             | 3         | 3      | 4.41%   |
| A-DATA Technology   | 3         | 8      | 4.41%   |
| VisionTek           | 2         | 6      | 2.94%   |
| Samsung Electronics | 2         | 9      | 2.94%   |
| HGST                | 2         | 3      | 2.94%   |
| Dogfish             | 2         | 4      | 2.94%   |
| walram              | 1         | 1      | 1.47%   |
| SPCC                | 1         | 1      | 1.47%   |
| OCZ                 | 1         | 4      | 1.47%   |
| Mushkin             | 1         | 2      | 1.47%   |
| Micron Technology   | 1         | 4      | 1.47%   |
| HP Phison           | 1         | 1      | 1.47%   |
| Crucial             | 1         | 1      | 1.47%   |
| Apacer              | 1         | 1      | 1.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 24     | 36.11%  |
| WDC     | 10        | 23     | 27.78%  |
| Hitachi | 7         | 20     | 19.44%  |
| Toshiba | 4         | 6      | 11.11%  |
| HGST    | 2         | 3      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 76     | 50%     |
| SSD  | 32        | 58     | 48.48%  |
| NVMe | 1         | 2      | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB                         | 1         | 1      | 25%     |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 25%     |
| SanDisk pSSD 256GB                               | 1         | 1      | 25%     |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |
| SanDisk             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 370       | 881    | 82.22%  |
| Malfunc  | 64        | 136    | 14.22%  |
| Detected | 12        | 14     | 2.67%   |
| Failed   | 4         | 4      | 0.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 364       | 65.59%  |
| AMD                                     | 56        | 10.09%  |
| Samsung Electronics                     | 26        | 4.68%   |
| SanDisk                                 | 18        | 3.24%   |
| Broadcom / LSI                          | 16        | 2.88%   |
| Nvidia                                  | 7         | 1.26%   |
| MAXIO Technology (Hangzhou)             | 7         | 1.26%   |
| ASMedia Technology                      | 7         | 1.26%   |
| Marvell Technology Group                | 6         | 1.08%   |
| SK hynix                                | 5         | 0.9%    |
| Silicon Motion                          | 5         | 0.9%    |
| Kingston Technology Company             | 5         | 0.9%    |
| Phison Electronics                      | 4         | 0.72%   |
| Micron/Crucial Technology               | 4         | 0.72%   |
| Chelsio Communications                  | 4         | 0.72%   |
| VIA Technologies                        | 3         | 0.54%   |
| Toshiba                                 | 3         | 0.54%   |
| JMicron Technology                      | 3         | 0.54%   |
| Silicon Image                           | 2         | 0.36%   |
| Micron Technology                       | 2         | 0.36%   |
| Hewlett-Packard                         | 2         | 0.36%   |
| Shenzhen Unionmemory Information System | 1         | 0.18%   |
| Realtek Semiconductor                   | 1         | 0.18%   |
| Netac Technology                        | 1         | 0.18%   |
| HighPoint Technologies                  | 1         | 0.18%   |
| Dell                                    | 1         | 0.18%   |
| ADATA Technology                        | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 39        | 6.2%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 29        | 4.61%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 25        | 3.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 24        | 3.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 17        | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 17        | 2.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 15        | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 2.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 2.07%   |
| AMD 400 Series Chipset SATA Controller                                           | 13        | 2.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 1.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 1.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 11        | 1.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 10        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.43%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 7         | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 1.11%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 0.95%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 6         | 0.95%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 6         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 0.95%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 6         | 0.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.79%   |
| Intel Elkhart Lake SATA AHCI                                                     | 5         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 0.79%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 5         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 0.64%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                               | 4         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 0.64%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.64%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 0.64%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 4         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 374       | 67.63%  |
| NVMe | 80        | 14.47%  |
| IDE  | 60        | 10.85%  |
| RAID | 21        | 3.8%    |
| SAS  | 11        | 1.99%   |
| SCSI | 7         | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 385       | 85.18%  |
| AMD     | 64        | 14.16%  |
| Unknown | 2         | 0.44%   |
| ARM     | 1         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron N5105 @ 2.00GHz            | 21        | 4.57%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 12        | 2.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 9         | 1.96%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 8         | 1.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 7         | 1.52%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 7         | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 6         | 1.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 1.3%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 6         | 1.3%    |
| Intel Celeron CPU J3455E @ 1.50GHz       | 5         | 1.09%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5         | 1.09%   |
| AMD GX-412TC SOC                         | 5         | 1.09%   |
| Intel Xeon                               | 4         | 0.87%   |
| Intel Core i5-4570TE CPU @ 2.70GHz       | 4         | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 4         | 0.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 4         | 0.87%   |
| Intel Core i3-2100 CPU @ 3.10GHz         | 4         | 0.87%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 3         | 0.65%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 3         | 0.65%   |
| Intel Pentium CPU G4560 @ 3.50GHz        | 3         | 0.65%   |
| Intel N100                               | 3         | 0.65%   |
| Intel Core i7-9700K CPU @ 3.60GHz        | 3         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.65%   |
| Intel Core i5-8500 CPU @ 3.00GHz         | 3         | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 3         | 0.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 0.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 3         | 0.65%   |
| Intel Core i3-4010U CPU @ 1.70GHz        | 3         | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 3         | 0.65%   |
| Intel Celeron J6413 @ 1.80GHz            | 3         | 0.65%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 3         | 0.65%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.65%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 2         | 0.43%   |
| Intel Xeon CPU E5645 @ 2.40GHz           | 2         | 0.43%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz      | 2         | 0.43%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz      | 2         | 0.43%   |
| Intel CPU Version                        | 2         | 0.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 2         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 114       | 24.95%  |
| Intel Celeron           | 82        | 17.94%  |
| Intel Xeon              | 48        | 10.5%   |
| Intel Core i7           | 41        | 8.97%   |
| Intel Core i3           | 36        | 7.88%   |
| Other                   | 23        | 5.03%   |
| Intel Atom              | 17        | 3.72%   |
| Intel Core 2 Duo        | 10        | 2.19%   |
| Intel Pentium           | 8         | 1.75%   |
| AMD Ryzen 5             | 8         | 1.75%   |
| AMD GX                  | 7         | 1.53%   |
| AMD FX                  | 7         | 1.53%   |
| AMD Ryzen 9             | 6         | 1.31%   |
| AMD Ryzen 7             | 6         | 1.31%   |
| Intel Pentium Dual-Core | 5         | 1.09%   |
| Intel Pentium Silver    | 4         | 0.88%   |
| Intel Core 2 Quad       | 3         | 0.66%   |
| AMD EPYC                | 3         | 0.66%   |
| AMD Athlon 64 X2        | 3         | 0.66%   |
| Intel Pentium 4         | 2         | 0.44%   |
| AMD Ryzen Embedded      | 2         | 0.44%   |
| AMD Ryzen 5 PRO         | 2         | 0.44%   |
| AMD Ryzen 3             | 2         | 0.44%   |
| AMD Opteron             | 2         | 0.44%   |
| AMD G                   | 2         | 0.44%   |
| AMD Athlon II X2        | 2         | 0.44%   |
| Intel Genuine           | 1         | 0.22%   |
| Intel Core 2            | 1         | 0.22%   |
| ARM Cortex              | 1         | 0.22%   |
| AMD Phenom II X6        | 1         | 0.22%   |
| AMD Phenom              | 1         | 0.22%   |
| AMD E1                  | 1         | 0.22%   |
| AMD E                   | 1         | 0.22%   |
| AMD Athlon Dual Core    | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |
| AMD A6                  | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |
| AMD A10                 | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 221       | 48.68%  |
| 2       | 130       | 28.63%  |
| 6       | 26        | 5.73%   |
| 8       | 19        | 4.19%   |
| 12      | 15        | 3.3%    |
| Unknown | 15        | 3.3%    |
| 16      | 9         | 1.98%   |
| 32      | 5         | 1.1%    |
| 10      | 4         | 0.88%   |
| 24      | 3         | 0.66%   |
| 1       | 2         | 0.44%   |
| 64      | 1         | 0.22%   |
| 20      | 1         | 0.22%   |
| 11      | 1         | 0.22%   |
| 5       | 1         | 0.22%   |
| 3       | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 429       | 94.91%  |
| 2       | 16        | 3.54%   |
| Unknown | 7         | 1.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 260       | 57.78%  |
| 2       | 174       | 38.67%  |
| Unknown | 16        | 3.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 60        | 13.07%  |
| Unknown       | 51        | 11.11%  |
| KabyLake      | 46        | 10.02%  |
| IvyBridge     | 37        | 8.06%   |
| Silvermont    | 29        | 6.32%   |
| SandyBridge   | 28        | 6.1%    |
| Skylake       | 27        | 5.88%   |
| Penryn        | 19        | 4.14%   |
| Broadwell     | 17        | 3.7%    |
| Goldmont      | 16        | 3.49%   |
| Westmere      | 15        | 3.27%   |
| Goldmont plus | 15        | 3.27%   |
| Zen+          | 9         | 1.96%   |
| Piledriver    | 9         | 1.96%   |
| Nehalem       | 9         | 1.96%   |
| CometLake     | 8         | 1.74%   |
| Zen           | 7         | 1.53%   |
| Bonnell       | 7         | 1.53%   |
| Zen 3         | 6         | 1.31%   |
| Puma          | 5         | 1.09%   |
| K10           | 5         | 1.09%   |
| Jaguar        | 5         | 1.09%   |
| Core          | 5         | 1.09%   |
| Zen 2         | 4         | 0.87%   |
| TigerLake     | 4         | 0.87%   |
| K8 Hammer     | 4         | 0.87%   |
| Steamroller   | 3         | 0.65%   |
| Bobcat        | 3         | 0.65%   |
| NetBurst      | 2         | 0.44%   |
| P6            | 1         | 0.22%   |
| IceLake       | 1         | 0.22%   |
| Excavator     | 1         | 0.22%   |
| Bulldozer     | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 300       | 66.52%  |
| AMD                        | 57        | 12.64%  |
| Nvidia                     | 55        | 12.2%   |
| Matrox Electronics Systems | 21        | 4.66%   |
| ASPEED Technology          | 17        | 3.77%   |
| Silicon Motion             | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33        | 7.16%   |
| Intel JasperLake [UHD Graphics]                                                          | 27        | 5.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 4.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 4.12%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 17        | 3.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 16        | 3.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 3.04%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 13        | 2.82%   |
| Intel HD Graphics 530                                                                    | 13        | 2.82%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.6%    |
| Intel HD Graphics 500                                                                    | 11        | 2.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.39%   |
| Intel HD Graphics 620                                                                    | 10        | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.95%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 1.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 1.52%   |
| Intel HD Graphics 630                                                                    | 6         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.3%    |
| Intel UHD Graphics 620                                                                   | 5         | 1.08%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5         | 1.08%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 5         | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.87%   |
| Matrox Electronics Systems G200eR2                                                       | 4         | 0.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.87%   |
| Intel HD Graphics 610                                                                    | 4         | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.87%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3         | 0.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.65%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 3         | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.65%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 0.65%   |
| AMD ES1000                                                                               | 3         | 0.65%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.43%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.43%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.43%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 273       | 60%     |
| 1 x AMD            | 50        | 10.99%  |
| 1 x Nvidia         | 46        | 10.11%  |
| 1 x Matrox         | 21        | 4.62%   |
| Other              | 17        | 3.74%   |
| 2 x Intel          | 16        | 3.52%   |
| 1 x ASPEED         | 16        | 3.52%   |
| Intel + Nvidia     | 8         | 1.76%   |
| 2 x AMD            | 3         | 0.66%   |
| Intel + AMD        | 2         | 0.44%   |
| 1 x Silicon Motion | 1         | 0.22%   |
| AMD + Nvidia       | 1         | 0.22%   |
| AMD + ASPEED       | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 408       | 89.67%  |
| Proprietary | 28        | 6.15%   |
| Unknown     | 19        | 4.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 405       | 89.4%   |
| 1.01-2.0   | 13        | 2.87%   |
| 0.51-1.0   | 11        | 2.43%   |
| 3.01-4.0   | 8         | 1.77%   |
| 0.01-0.5   | 6         | 1.32%   |
| 7.01-8.0   | 4         | 0.88%   |
| 5.01-6.0   | 3         | 0.66%   |
| 8.01-16.0  | 2         | 0.44%   |
| 2.01-3.0   | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 12        | 11.01%  |
| Dell                    | 11        | 10.09%  |
| Samsung Electronics     | 10        | 9.17%   |
| LG Display              | 10        | 9.17%   |
| Chimei Innolux          | 9         | 8.26%   |
| Lenovo                  | 6         | 5.5%    |
| BOE                     | 6         | 5.5%    |
| BenQ                    | 6         | 5.5%    |
| AU Optronics            | 6         | 5.5%    |
| Acer                    | 4         | 3.67%   |
| Sony                    | 3         | 2.75%   |
| LG Electronics          | 3         | 2.75%   |
| Chi Mei Optoelectronics | 3         | 2.75%   |
| ASUSTek Computer        | 3         | 2.75%   |
| AOC                     | 3         | 2.75%   |
| Toshiba                 | 2         | 1.83%   |
| Hewlett-Packard         | 2         | 1.83%   |
| Apple                   | 2         | 1.83%   |
| Ancor Communications    | 2         | 1.83%   |
| ViewSonic               | 1         | 0.92%   |
| Videoseven              | 1         | 0.92%   |
| RTK                     | 1         | 0.92%   |
| LTV                     | 1         | 0.92%   |
| Insignia                | 1         | 0.92%   |
| HKC                     | 1         | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2         | 1.77%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2         | 1.77%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 2         | 1.77%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2         | 1.77%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 1.77%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch       | 2         | 1.77%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch         | 2         | 1.77%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1         | 0.88%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1         | 0.88%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1         | 0.88%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 0.88%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1         | 0.88%   |
| RTK CPL AIO PC RTK2482 1920x1080 510x280mm 22.9-inch                   | 1         | 0.88%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1         | 0.88%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1         | 0.88%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1         | 0.88%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 0.88%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 0.88%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch            | 1         | 0.88%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch           | 1         | 0.88%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1         | 0.88%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                | 1         | 0.88%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 0.88%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                | 1         | 0.88%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1         | 0.88%   |
| HKC 27E6QC HKC274F 2560x1440 600x330mm 27.0-inch                       | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 44.44%  |
| 1366x768 (WXGA)    | 18        | 16.67%  |
| 3840x2160 (4K)     | 8         | 7.41%   |
| 1600x900 (HD+)     | 6         | 5.56%   |
| 2560x1440 (QHD)    | 4         | 3.7%    |
| 1280x800 (WXGA)    | 4         | 3.7%    |
| 1680x1050 (WSXGA+) | 3         | 2.78%   |
| 3440x1440          | 2         | 1.85%   |
| 2560x1080          | 2         | 1.85%   |
| 1920x1200 (WUXGA)  | 2         | 1.85%   |
| 1440x900 (WXGA+)   | 2         | 1.85%   |
| 1280x1024 (SXGA)   | 2         | 1.85%   |
| Unknown            | 2         | 1.85%   |
| 7680x2160          | 1         | 0.93%   |
| 2256x1504          | 1         | 0.93%   |
| 1600x1200          | 1         | 0.93%   |
| 1280x854           | 1         | 0.93%   |
| 1024x768 (XGA)     | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 18        | 16.36%  |
| 24      | 13        | 11.82%  |
| 15      | 13        | 11.82%  |
| 27      | 11        | 10%     |
| 21      | 8         | 7.27%   |
| 12      | 7         | 6.36%   |
| Unknown | 7         | 6.36%   |
| 23      | 5         | 4.55%   |
| 19      | 5         | 4.55%   |
| 34      | 4         | 3.64%   |
| 22      | 4         | 3.64%   |
| 54      | 3         | 2.73%   |
| 14      | 3         | 2.73%   |
| 31      | 2         | 1.82%   |
| 17      | 2         | 1.82%   |
| 74      | 1         | 0.91%   |
| 36      | 1         | 0.91%   |
| 20      | 1         | 0.91%   |
| 18      | 1         | 0.91%   |
| 11      | 1         | 0.91%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 29        | 26.61%  |
| 301-350     | 26        | 23.85%  |
| 401-500     | 16        | 14.68%  |
| 201-300     | 16        | 14.68%  |
| Unknown     | 7         | 6.42%   |
| 701-800     | 5         | 4.59%   |
| 351-400     | 4         | 3.67%   |
| 1001-1500   | 3         | 2.75%   |
| 601-700     | 2         | 1.83%   |
| 1501-2000   | 1         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 79        | 74.53%  |
| 16/10   | 11        | 10.38%  |
| Unknown | 7         | 6.6%    |
| 21/9    | 4         | 3.77%   |
| 5/4     | 2         | 1.89%   |
| 3/2     | 2         | 1.89%   |
| 4/3     | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 26        | 23.85%  |
| 81-90          | 16        | 14.68%  |
| 301-350        | 11        | 10.09%  |
| 61-70          | 7         | 6.42%   |
| 101-110        | 7         | 6.42%   |
| 91-100         | 7         | 6.42%   |
| Unknown        | 7         | 6.42%   |
| 351-500        | 6         | 5.5%    |
| 151-200        | 6         | 5.5%    |
| More than 1000 | 4         | 3.67%   |
| 71-80          | 4         | 3.67%   |
| 251-300        | 3         | 2.75%   |
| 121-130        | 2         | 1.83%   |
| 51-60          | 1         | 0.92%   |
| 141-150        | 1         | 0.92%   |
| 501-1000       | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 44        | 40%     |
| 101-120 | 29        | 26.36%  |
| 121-160 | 20        | 18.18%  |
| 161-240 | 9         | 8.18%   |
| Unknown | 7         | 6.36%   |
| 1-50    | 1         | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 327       | 71.87%  |
| 1     | 118       | 25.93%  |
| 2     | 10        | 2.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 350       | 54.77%  |
| Realtek Semiconductor             | 162       | 25.35%  |
| Broadcom                          | 45        | 7.04%   |
| Qualcomm Atheros                  | 29        | 4.54%   |
| Chelsio Communications            | 6         | 0.94%   |
| MediaTek                          | 5         | 0.78%   |
| Marvell Technology Group          | 4         | 0.63%   |
| Solarflare Communications         | 3         | 0.47%   |
| Ralink                            | 3         | 0.47%   |
| Mellanox Technologies             | 3         | 0.47%   |
| Sierra Wireless                   | 2         | 0.31%   |
| Nvidia                            | 2         | 0.31%   |
| IBM                               | 2         | 0.31%   |
| Ericsson Business Mobile Networks | 2         | 0.31%   |
| Apple                             | 2         | 0.31%   |
| 3Com                              | 2         | 0.31%   |
| TP-Link                           | 1         | 0.16%   |
| Ralink Technology                 | 1         | 0.16%   |
| Qualcomm Atheros Communications   | 1         | 0.16%   |
| QLogic                            | 1         | 0.16%   |
| NetGear                           | 1         | 0.16%   |
| Linksys                           | 1         | 0.16%   |
| JMicron Technology                | 1         | 0.16%   |
| Insyde Software                   | 1         | 0.16%   |
| IMC Networks                      | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Google                            | 1         | 0.16%   |
| D-Link System                     | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |
| Aquantia                          | 1         | 0.16%   |
| American Megatrends               | 1         | 0.16%   |
| AMD                               | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 133       | 16.5%   |
| Intel I211 Gigabit Network Connection                                         | 39        | 4.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 34        | 4.22%   |
| Intel 82574L Gigabit Network Connection                                       | 28        | 3.47%   |
| Intel I210 Gigabit Network Connection                                         | 23        | 2.85%   |
| Intel Ethernet Controller I225-V                                              | 23        | 2.85%   |
| Intel Ethernet Connection I217-LM                                             | 23        | 2.85%   |
| Intel I350 Gigabit Network Connection                                         | 22        | 2.73%   |
| Intel Ethernet Controller I226-V                                              | 18        | 2.23%   |
| Intel 82576 Gigabit Network Connection                                        | 15        | 1.86%   |
| Intel Wireless 7265                                                           | 13        | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                             | 11        | 1.36%   |
| Intel 82583V Gigabit Network Connection                                       | 11        | 1.36%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11        | 1.36%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 1.12%   |
| Intel Wireless 8260                                                           | 9         | 1.12%   |
| Intel Ethernet Connection I219-LM                                             | 9         | 1.12%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 9         | 1.12%   |
| Intel Wireless 3165                                                           | 8         | 0.99%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 0.99%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 0.99%   |
| Intel Wireless 7260                                                           | 7         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 0.87%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 0.74%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5         | 0.62%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 5         | 0.62%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.62%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 0.5%    |
| Intel Wireless 3160                                                           | 4         | 0.5%    |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 4         | 0.5%    |
| Intel Ethernet Controller X550                                                | 4         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.5%    |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 4         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.5%    |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.5%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 62.42%  |
| Qualcomm Atheros                | 21        | 12.73%  |
| Realtek Semiconductor           | 16        | 9.7%    |
| Broadcom                        | 8         | 4.85%   |
| MediaTek                        | 5         | 3.03%   |
| Ralink                          | 3         | 1.82%   |
| TP-Link                         | 1         | 0.61%   |
| Sierra Wireless                 | 1         | 0.61%   |
| Ralink Technology               | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| NetGear                         | 1         | 0.61%   |
| Marvell Technology Group        | 1         | 0.61%   |
| Linksys                         | 1         | 0.61%   |
| IMC Networks                    | 1         | 0.61%   |
| D-Link                          | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 13        | 7.74%   |
| Intel Wireless 8260                                                     | 9         | 5.36%   |
| Intel Wireless 3165                                                     | 8         | 4.76%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.76%   |
| Intel Wireless 7260                                                     | 7         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 4.17%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 2.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.38%   |
| Intel Wireless 3160                                                     | 4         | 2.38%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 4         | 2.38%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 2.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.79%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.19%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.19%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.19%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.19%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 0.6%    |
| Sierra Wireless EM7455                                                  | 1         | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 302       | 56.77%  |
| Realtek Semiconductor     | 157       | 29.51%  |
| Broadcom                  | 37        | 6.95%   |
| Qualcomm Atheros          | 11        | 2.07%   |
| Chelsio Communications    | 4         | 0.75%   |
| Solarflare Communications | 3         | 0.56%   |
| Marvell Technology Group  | 3         | 0.56%   |
| Nvidia                    | 2         | 0.38%   |
| Apple                     | 2         | 0.38%   |
| 3Com                      | 2         | 0.38%   |
| QLogic                    | 1         | 0.19%   |
| JMicron Technology        | 1         | 0.19%   |
| Insyde Software           | 1         | 0.19%   |
| ICS Advent                | 1         | 0.19%   |
| Google                    | 1         | 0.19%   |
| D-Link System             | 1         | 0.19%   |
| Aquantia                  | 1         | 0.19%   |
| American Megatrends       | 1         | 0.19%   |
| AMD                       | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 133       | 21.38%  |
| Intel I211 Gigabit Network Connection                                         | 39        | 6.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 34        | 5.47%   |
| Intel 82574L Gigabit Network Connection                                       | 28        | 4.5%    |
| Intel I210 Gigabit Network Connection                                         | 23        | 3.7%    |
| Intel Ethernet Controller I225-V                                              | 23        | 3.7%    |
| Intel Ethernet Connection I217-LM                                             | 23        | 3.7%    |
| Intel I350 Gigabit Network Connection                                         | 22        | 3.54%   |
| Intel Ethernet Controller I226-V                                              | 18        | 2.89%   |
| Intel 82576 Gigabit Network Connection                                        | 15        | 2.41%   |
| Realtek RTL8125 2.5GbE Controller                                             | 11        | 1.77%   |
| Intel 82583V Gigabit Network Connection                                       | 11        | 1.77%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11        | 1.77%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 1.45%   |
| Intel Ethernet Connection I219-LM                                             | 9         | 1.45%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 9         | 1.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 1.13%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 5         | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.8%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.8%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 0.8%    |
| Intel Ethernet Controller X550                                                | 4         | 0.64%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.64%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.64%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 0.64%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 0.64%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 4         | 0.64%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 3         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3         | 0.48%   |
| Intel Ethernet Connection I354                                                | 3         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.48%   |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.48%   |
| Intel Ethernet Connection (2) I218-LM                                         | 3         | 0.48%   |
| Intel Ethernet Connection (11) I219-LM                                        | 3         | 0.48%   |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 438       | 71.34%  |
| WiFi     | 160       | 26.06%  |
| Unknown  | 12        | 1.95%   |
| Modem    | 4         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 407       | 84.62%  |
| WiFi     | 74        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 155       | 33.92%  |
| 4     | 78        | 17.07%  |
| 3     | 76        | 16.63%  |
| 1     | 60        | 13.13%  |
| 5     | 33        | 7.22%   |
| 6     | 31        | 6.78%   |
| 8     | 8         | 1.75%   |
| 7     | 6         | 1.31%   |
| 0     | 4         | 0.88%   |
| 10    | 2         | 0.44%   |
| 9     | 2         | 0.44%   |
| 14    | 1         | 0.22%   |
| 12    | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 397       | 85.75%  |
| Yes  | 66        | 14.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 61.34%  |
| Cambridge Silicon Radio         | 9         | 7.56%   |
| Realtek Semiconductor           | 6         | 5.04%   |
| IMC Networks                    | 5         | 4.2%    |
| Foxconn / Hon Hai               | 5         | 4.2%    |
| Broadcom                        | 5         | 4.2%    |
| Qualcomm Atheros Communications | 4         | 3.36%   |
| Apple                           | 3         | 2.52%   |
| Lite-On Technology              | 2         | 1.68%   |
| ASUSTek Computer                | 2         | 1.68%   |
| Alps Electric                   | 2         | 1.68%   |
| Toshiba                         | 1         | 0.84%   |
| MediaTek                        | 1         | 0.84%   |
| Hewlett-Packard                 | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 37        | 30.83%  |
| Intel AX201 Bluetooth                                       | 13        | 10.83%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 7.5%    |
| Intel AX200 Bluetooth                                       | 8         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 5%      |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 4.17%   |
| Realtek Bluetooth Adapter                                   | 3         | 2.5%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 2.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.67%   |
| Intel Wireless Bluetooth                                    | 2         | 1.67%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 2         | 1.67%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 2         | 1.67%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.67%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 1.67%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 0.83%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.83%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.83%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.83%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.83%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.83%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.83%   |
| Intel AX210 Bluetooth                                       | 1         | 0.83%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 0.83%   |
| IMC Networks Bluetooth                                      | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.83%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.83%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.83%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 0.83%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.83%   |
| Apple Bluetooth Host Controller                             | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 293       | 68.46%  |
| AMD                                          | 61        | 14.25%  |
| Nvidia                                       | 46        | 10.75%  |
| C-Media Electronics                          | 7         | 1.64%   |
| KTMicro                                      | 4         | 0.93%   |
| Logitech                                     | 3         | 0.7%    |
| Texas Instruments                            | 2         | 0.47%   |
| ASUSTek Computer                             | 2         | 0.47%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.23%   |
| Yamaha                                       | 1         | 0.23%   |
| XMOS                                         | 1         | 0.23%   |
| SteelSeries ApS                              | 1         | 0.23%   |
| Plantronics                                  | 1         | 0.23%   |
| MosArt Semiconductor                         | 1         | 0.23%   |
| Micro Star International                     | 1         | 0.23%   |
| Generalplus Technology                       | 1         | 0.23%   |
| Elgato Systems                               | 1         | 0.23%   |
| Creative Labs                                | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 31        | 6.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 5.91%   |
| Intel Jasper Lake HD Audio                                                                        | 27        | 5.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 5.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 4.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 3.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 3.35%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.38%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.18%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.98%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 5         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.98%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 5         | 0.98%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.98%   |
| KTMicro KT USB Audio                                                                              | 4         | 0.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.79%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.59%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 86        | 17.44%  |
| Samsung Electronics          | 76        | 15.42%  |
| Kingston                     | 70        | 14.2%   |
| Unknown                      | 43        | 8.72%   |
| Micron Technology            | 39        | 7.91%   |
| Crucial                      | 34        | 6.9%    |
| Corsair                      | 33        | 6.69%   |
| G.Skill                      | 28        | 5.68%   |
| Unknown                      | 16        | 3.25%   |
| A-DATA Technology            | 9         | 1.83%   |
| Unknown (ABCD)               | 8         | 1.62%   |
| Ramaxel Technology           | 7         | 1.42%   |
| Apacer                       | 5         | 1.01%   |
| Transcend                    | 4         | 0.81%   |
| Team                         | 4         | 0.81%   |
| Patriot                      | 4         | 0.81%   |
| Nanya Technology             | 4         | 0.81%   |
| Unknown (0x0C26)             | 3         | 0.61%   |
| Timetec                      | 3         | 0.61%   |
| OCZ                          | 3         | 0.61%   |
| Avant                        | 2         | 0.41%   |
| V-Color                      | 1         | 0.2%    |
| Unknown (0x0DD5)             | 1         | 0.2%    |
| Toshiba                      | 1         | 0.2%    |
| Teikon                       | 1         | 0.2%    |
| Silicon Power                | 1         | 0.2%    |
| PNY                          | 1         | 0.2%    |
| Patriot Memory (PDP Systems) | 1         | 0.2%    |
| Lexar Co Limited             | 1         | 0.2%    |
| Elpida                       | 1         | 0.2%    |
| Cors                         | 1         | 0.2%    |
| AMD                          | 1         | 0.2%    |
| 0C26000000AD                 | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 16        | 3.02%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 7         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 0.94%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s          | 5         | 0.94%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 5         | 0.94%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 5         | 0.94%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 4         | 0.75%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 4         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.75%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s          | 4         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 3         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 3         | 0.57%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3         | 0.57%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 3         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.57%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s         | 3         | 0.57%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 3         | 0.57%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s           | 3         | 0.57%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 3         | 0.57%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 3         | 0.57%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s          | 3         | 0.57%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s       | 3         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.38%   |
| Unknown RAM Module 8GB 1600MT/s                              | 2         | 0.38%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                    | 2         | 0.38%   |
| Unknown RAM Module 1GB SODIMM DDR2                           | 2         | 0.38%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s           | 2         | 0.38%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 2         | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.38%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 2         | 0.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.38%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2         | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.38%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 2         | 0.38%   |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s         | 2         | 0.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 0.38%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s         | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 204       | 47.44%  |
| DDR4    | 161       | 37.44%  |
| DDR2    | 19        | 4.42%   |
| Unknown | 15        | 3.49%   |
| LPDDR4  | 12        | 2.79%   |
| SDRAM   | 7         | 1.63%   |
| DDR5    | 7         | 1.63%   |
| LPDDR3  | 2         | 0.47%   |
| DDR     | 2         | 0.47%   |
| LPDDR5  | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 232       | 54.59%  |
| SODIMM       | 178       | 41.88%  |
| Row Of Chips | 5         | 1.18%   |
| RIMM         | 3         | 0.71%   |
| Unknown      | 3         | 0.71%   |
| FB-DIMM      | 2         | 0.47%   |
| Chip         | 2         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 158       | 33.69%  |
| 8192  | 157       | 33.48%  |
| 16384 | 62        | 13.22%  |
| 2048  | 62        | 13.22%  |
| 1024  | 16        | 3.41%   |
| 32768 | 11        | 2.35%   |
| 512   | 3         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 138       | 29.87%  |
| 1333    | 65        | 14.07%  |
| 3200    | 46        | 9.96%   |
| 2400    | 46        | 9.96%   |
| 2667    | 43        | 9.31%   |
| 2133    | 29        | 6.28%   |
| 1067    | 14        | 3.03%   |
| 800     | 13        | 2.81%   |
| 2666    | 10        | 2.16%   |
| Unknown | 10        | 2.16%   |
| 667     | 9         | 1.95%   |
| 4800    | 6         | 1.3%    |
| 1334    | 6         | 1.3%    |
| 3000    | 5         | 1.08%   |
| 1066    | 4         | 0.87%   |
| 3600    | 3         | 0.65%   |
| 1867    | 3         | 0.65%   |
| 6400    | 2         | 0.43%   |
| 4267    | 2         | 0.43%   |
| 1866    | 2         | 0.43%   |
| 400     | 2         | 0.43%   |
| 5200    | 1         | 0.22%   |
| 3400    | 1         | 0.22%   |
| 533     | 1         | 0.22%   |
| 333     | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| HP LaserJet 2200                   | 1         | 20%     |
| HP Color LaserJet CP1215           | 1         | 20%     |
| Brother HL-L5200DW series          | 1         | 20%     |
| Brother HL-L2300D series           | 1         | 20%     |

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
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 19        | 34.55%  |
| Microdia                      | 6         | 10.91%  |
| Bison Electronics             | 6         | 10.91%  |
| Realtek Semiconductor         | 5         | 9.09%   |
| Logitech                      | 3         | 5.45%   |
| Lite-On Technology            | 3         | 5.45%   |
| IMC Networks                  | 3         | 5.45%   |
| Syntek                        | 2         | 3.64%   |
| Sunplus Innovation Technology | 2         | 3.64%   |
| Suyin                         | 1         | 1.82%   |
| Quanta                        | 1         | 1.82%   |
| Luxvisions Innotech Limited   | 1         | 1.82%   |
| Lenovo                        | 1         | 1.82%   |
| ALi                           | 1         | 1.82%   |
| Alcor Micro                   | 1         | 1.82%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 5         | 9.09%   |
| Bison Integrated Camera                       | 4         | 7.27%   |
| Lite-On Integrated Camera                     | 3         | 5.45%   |
| Chicony HD Webcam                             | 3         | 5.45%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.82%   |
| Syntek ASUS USB2.0 camera                     | 1         | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.82%   |
| Sunplus ASUS Webcam                           | 1         | 1.82%   |
| Realtek USB 2.0 PC Camera                     | 1         | 1.82%   |
| Realtek PC Camera                             | 1         | 1.82%   |
| Realtek Integrated Webcam HD                  | 1         | 1.82%   |
| Realtek Integrated Webcam                     | 1         | 1.82%   |
| Realtek HD Webcam - Realtek                   | 1         | 1.82%   |
| Quanta Realtek PC Camera                      | 1         | 1.82%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_2M          | 1         | 1.82%   |
| Microdia JOYACCESS JA-Webcam                  | 1         | 1.82%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.82%   |
| Microdia Integrated Webcam HD                 | 1         | 1.82%   |
| Microdia Integrated Webcam                    | 1         | 1.82%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.82%   |
| Logitech Webcam C310                          | 1         | 1.82%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.82%   |
| Logitech BRIO Ultra HD Webcam                 | 1         | 1.82%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.82%   |
| IMC Networks UVC VGA Webcam                   | 1         | 1.82%   |
| IMC Networks Integrated Webcam                | 1         | 1.82%   |
| IMC Networks Integrated Camera                | 1         | 1.82%   |
| Chicony WebCam                                | 1         | 1.82%   |
| Chicony VGA 24fps UVC Webcam                  | 1         | 1.82%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 1.82%   |
| Chicony TOSHIBA Web Camera - FHD              | 1         | 1.82%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.82%   |
| Chicony Integrated Camera [ThinkPad]          | 1         | 1.82%   |
| Chicony HP HD Camera                          | 1         | 1.82%   |
| Chicony HP 0.3MP Webcam                       | 1         | 1.82%   |
| Chicony FJ Camera                             | 1         | 1.82%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 1.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 47.06%  |
| Upek                       | 2         | 11.76%  |
| Synaptics                  | 2         | 11.76%  |
| LighTuning Technology      | 2         | 11.76%  |
| AuthenTec                  | 2         | 11.76%  |
| Shenzhen Goodix Technology | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 17.65%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 11.76%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 1         | 5.88%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.88%   |
| AuthenTec AES2660                                      | 1         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.88%   |

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
| 1     | 232       | 49.57%  |
| 0     | 123       | 26.28%  |
| 2     | 71        | 15.17%  |
| 3     | 30        | 6.41%   |
| 4     | 10        | 2.14%   |
| 5     | 2         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 289       | 64.51%  |
| Bluetooth                | 51        | 11.38%  |
| Net/wireless             | 32        | 7.14%   |
| Card reader              | 20        | 4.46%   |
| Firewire controller      | 15        | 3.35%   |
| Fingerprint reader       | 13        | 2.9%    |
| Net/ethernet             | 8         | 1.79%   |
| Sound                    | 6         | 1.34%   |
| Network                  | 6         | 1.34%   |
| Graphics card            | 3         | 0.67%   |
| Storage/raid             | 2         | 0.45%   |
| Storage                  | 2         | 0.45%   |
| Storage/ata              | 1         | 0.22%   |

