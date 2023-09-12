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

Total: 761

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 23.1.11  | 17        | 2.7%    |
| OpenBSD 7.2       | 17        | 2.7%    |
| helloSystem 0.7.0 | 17        | 2.7%    |
| OPNsense 23.1     | 14        | 2.22%   |
| OPNsense 22.7.10  | 14        | 2.22%   |
| OpenBSD 7.3       | 14        | 2.22%   |
| OpenBSD 7.1       | 13        | 2.06%   |
| OPNsense 23.1.6   | 12        | 1.9%    |
| OPNsense 23.1.1   | 12        | 1.9%    |
| OPNsense 22.1.10  | 12        | 1.9%    |
| OPNsense 21.1.4   | 12        | 1.9%    |
| OPNsense 21.1     | 12        | 1.9%    |
| helloSystem 0.8.1 | 12        | 1.9%    |
| helloSystem 0.5.0 | 11        | 1.75%   |
| OPNsense 23.7.1   | 10        | 1.59%   |
| OPNsense 23.1.9   | 10        | 1.59%   |
| OPNsense 22.7.8   | 10        | 1.59%   |
| OPNsense 22.7.4   | 10        | 1.59%   |
| OPNsense 22.1.7   | 10        | 1.59%   |
| OPNsense 22.1.6   | 10        | 1.59%   |
| OPNsense 21.1.3   | 10        | 1.59%   |
| FreeBSD 13.1-p5   | 10        | 1.59%   |
| OPNsense 22.7     | 9         | 1.43%   |
| OPNsense 22.1     | 9         | 1.43%   |
| OPNsense 21.1.6   | 9         | 1.43%   |
| OpenBSD 7.0       | 9         | 1.43%   |
| OpenBSD 6.9       | 9         | 1.43%   |
| FreeBSD 12.2      | 9         | 1.43%   |
| OPNsense 22.1.8   | 8         | 1.27%   |
| OPNsense 21.7.7   | 8         | 1.27%   |
| OPNsense 21.7.1   | 8         | 1.27%   |
| OPNsense 21.1.5   | 8         | 1.27%   |
| OpenBSD 6.8       | 8         | 1.27%   |
| helloSystem 0.8.0 | 8         | 1.27%   |
| OPNsense 22.7.9   | 7         | 1.11%   |
| OPNsense 21.7     | 7         | 1.11%   |
| FreeBSD 13.1      | 7         | 1.11%   |
| FreeBSD 13.0      | 7         | 1.11%   |
| OPNsense 23.7.3   | 6         | 0.95%   |
| OPNsense 22.7.11  | 6         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 259       | 58.86%  |
| FreeBSD     | 91        | 20.68%  |
| helloSystem | 51        | 11.59%  |
| OpenBSD     | 25        | 5.68%   |
| GhostBSD    | 6         | 1.36%   |
| FreeNAS     | 3         | 0.68%   |
| TrueNAS     | 2         | 0.45%   |
| pfSense     | 1         | 0.23%   |
| NetBSD      | 1         | 0.23%   |
| MyBee       | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 429       | 98.17%  |
| i386   | 5         | 1.14%   |
| macppc | 2         | 0.46%   |
| arm64  | 1         | 0.23%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 299       | 66.44%  |
| helloDesktop | 69        | 15.33%  |
| XFCE         | 19        | 4.22%   |
| KDE5         | 14        | 3.11%   |
| fvwm         | 12        | 2.67%   |
| MATE         | 8         | 1.78%   |
| GNOME        | 7         | 1.56%   |
| TWM          | 5         | 1.11%   |
| Openbox      | 4         | 0.89%   |
| Cinnamon     | 3         | 0.67%   |
| LXQt         | 2         | 0.44%   |
| i3           | 2         | 0.44%   |
| X-Cinnamon   | 1         | 0.22%   |
| Window Maker | 1         | 0.22%   |
| LXDE         | 1         | 0.22%   |
| Lumina       | 1         | 0.22%   |
| Fluxbox      | 1         | 0.22%   |
| DWM          | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 299       | 68.42%  |
| X11     | 135       | 30.89%  |
| Wayland | 3         | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 341       | 77.15%  |
| SLiM    | 56        | 12.67%  |
| SDDM    | 17        | 3.85%   |
| LightDM | 11        | 2.49%   |
| XDM     | 10        | 2.26%   |
| GDM     | 6         | 1.36%   |
| Ly      | 1         | 0.23%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 309       | 69.75%  |
| en_US   | 65        | 14.67%  |
| C       | 46        | 10.38%  |
| en_CA   | 11        | 2.48%   |
| fr_FR   | 5         | 1.13%   |
| en      | 3         | 0.68%   |
| fr      | 2         | 0.45%   |
| fr_CA   | 1         | 0.23%   |
| en_NL   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 361       | 81.67%  |
| BIOS | 81        | 18.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 217       | 48.01%  |
| Zfs     | 186       | 41.15%  |
| Ffs     | 25        | 5.53%   |
| Cd9660  | 23        | 5.09%   |
| Unknown | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 397       | 90.85%  |
| MBR     | 36        | 8.24%   |
| Unknown | 4         | 0.92%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 57        | 13.04%  |
| Lenovo                         | 50        | 11.44%  |
| Hewlett-Packard                | 49        | 11.21%  |
| ASUSTek Computer               | 41        | 9.38%   |
| Intel                          | 28        | 6.41%   |
| Unknown                        | 27        | 6.18%   |
| Supermicro                     | 22        | 5.03%   |
| Protectli                      | 21        | 4.81%   |
| Gigabyte Technology            | 15        | 3.43%   |
| ASRock                         | 13        | 2.97%   |
| MSI                            | 12        | 2.75%   |
| Techvision                     | 10        | 2.29%   |
| Acer                           | 10        | 2.29%   |
| AZW                            | 7         | 1.6%    |
| PC Engines                     | 6         | 1.37%   |
| AMI                            | 6         | 1.37%   |
| ZOTAC                          | 5         | 1.14%   |
| AWOW                           | 5         | 1.14%   |
| Apple                          | 5         | 1.14%   |
| Toshiba                        | 3         | 0.69%   |
| Panasonic                      | 3         | 0.69%   |
| IBM                            | 3         | 0.69%   |
| Sophos                         | 2         | 0.46%   |
| Shuttle                        | 2         | 0.46%   |
| MW                             | 2         | 0.46%   |
| Matsushita Electric Industrial | 2         | 0.46%   |
| Google                         | 2         | 0.46%   |
| Datto                          | 2         | 0.46%   |
| ASRockRack                     | 2         | 0.46%   |
| Alienware                      | 2         | 0.46%   |
| Yanling                        | 1         | 0.23%   |
| Star Labs                      | 1         | 0.23%   |
| ShenZhen MinWin Technology     | 1         | 0.23%   |
| SeeedStudio                    | 1         | 0.23%   |
| ReachingTech                   | 1         | 0.23%   |
| Raspberry Pi Foundation        | 1         | 0.23%   |
| Quanta                         | 1         | 0.23%   |
| Pegatron                       | 1         | 0.23%   |
| MiTAC                          | 1         | 0.23%   |
| LG Electronics                 | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 28        | 6.41%   |
| Protectli FW4B                     | 11        | 2.52%   |
| Techvision TVI7309X                | 10        | 2.29%   |
| Protectli FW6                      | 6         | 1.37%   |
| Intel Q3XXG4-P V1.0                | 6         | 1.37%   |
| Supermicro Super Server            | 5         | 1.14%   |
| AWOW PC BOX                        | 5         | 1.14%   |
| Intel NDISB533                     | 4         | 0.92%   |
| HP EliteDesk 800 G1 SFF            | 4         | 0.92%   |
| Dell OptiPlex 9010                 | 4         | 0.92%   |
| AZW U59                            | 4         | 0.92%   |
| AMI Aptio CRB                      | 4         | 0.92%   |
| PC Engines APU2                    | 3         | 0.69%   |
| Intel H81U                         | 3         | 0.69%   |
| HP Z440 Workstation                | 3         | 0.69%   |
| HP t730 Thin Client                | 3         | 0.69%   |
| HP Compaq 8200 Elite SFF PC        | 3         | 0.69%   |
| HP Compaq 6200 Pro MT PC           | 3         | 0.69%   |
| Dell OptiPlex 7010                 | 3         | 0.69%   |
| ASUS All Series                    | 3         | 0.69%   |
| ZOTAC ZBOX-CI323NANO               | 2         | 0.46%   |
| Supermicro X8STi                   | 2         | 0.46%   |
| Protectli VP2420                   | 2         | 0.46%   |
| PC Engines apu4                    | 2         | 0.46%   |
| MW GMLK-2_5G4L                     | 2         | 0.46%   |
| MSI MS-7A40                        | 2         | 0.46%   |
| Lenovo ThinkCentre M93p 10A8S16X0J | 2         | 0.46%   |
| Intel CRESCENTBAY                  | 2         | 0.46%   |
| HP Compaq Elite 8300 SFF           | 2         | 0.46%   |
| HP 500-459                         | 2         | 0.46%   |
| Dell Precision WorkStation T3500   | 2         | 0.46%   |
| Dell Precision Tower 5810          | 2         | 0.46%   |
| Dell PowerEdge R210 II             | 2         | 0.46%   |
| Dell PowerEdge R210                | 2         | 0.46%   |
| Dell OptiPlex 7060                 | 2         | 0.46%   |
| Dell OptiPlex 7050                 | 2         | 0.46%   |
| Dell OptiPlex 7020                 | 2         | 0.46%   |
| Dell OptiPlex 3060                 | 2         | 0.46%   |
| Dell OptiPlex 3020                 | 2         | 0.46%   |
| Dell OptiPlex 3010                 | 2         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Unknown              | 28        | 6.41%   |
| Dell OptiPlex        | 26        | 5.95%   |
| Lenovo ThinkCentre   | 24        | 5.49%   |
| Lenovo ThinkPad      | 23        | 5.26%   |
| Dell PowerEdge       | 12        | 2.75%   |
| Protectli FW4B       | 11        | 2.52%   |
| Techvision TVI7309X  | 10        | 2.29%   |
| HP Compaq            | 10        | 2.29%   |
| ASUS PRIME           | 8         | 1.83%   |
| HP ProDesk           | 7         | 1.6%    |
| HP EliteDesk         | 7         | 1.6%    |
| Acer Aspire          | 7         | 1.6%    |
| Protectli FW6        | 6         | 1.37%   |
| Intel Q3XXG4-P       | 6         | 1.37%   |
| Dell Inspiron        | 6         | 1.37%   |
| ASUS ROG             | 6         | 1.37%   |
| Supermicro Super     | 5         | 1.14%   |
| Dell Precision       | 5         | 1.14%   |
| AWOW PC              | 5         | 1.14%   |
| Intel NDISB533       | 4         | 0.92%   |
| AZW U59              | 4         | 0.92%   |
| AMI Aptio            | 4         | 0.92%   |
| PC Engines APU2      | 3         | 0.69%   |
| Intel H81U           | 3         | 0.69%   |
| HP Z440              | 3         | 0.69%   |
| HP t730              | 3         | 0.69%   |
| HP ProLiant          | 3         | 0.69%   |
| HP Pavilion          | 3         | 0.69%   |
| Dell Latitude        | 3         | 0.69%   |
| ASUS TUF             | 3         | 0.69%   |
| ASUS All             | 3         | 0.69%   |
| ASRock B450M         | 3         | 0.69%   |
| ZOTAC ZBOX-CI323NANO | 2         | 0.46%   |
| Toshiba Satellite    | 2         | 0.46%   |
| Supermicro X8STi     | 2         | 0.46%   |
| Protectli VP2420     | 2         | 0.46%   |
| PC Engines apu4      | 2         | 0.46%   |
| MW GMLK-2            | 2         | 0.46%   |
| MSI MS-7A40          | 2         | 0.46%   |
| Intel CRESCENTBAY    | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 56        | 12.81%  |
| 2022    | 45        | 10.3%   |
| 2020    | 42        | 9.61%   |
| 2014    | 35        | 8.01%   |
| 2019    | 29        | 6.64%   |
| 2016    | 29        | 6.64%   |
| 2011    | 26        | 5.95%   |
| 2010    | 26        | 5.95%   |
| 2021    | 24        | 5.49%   |
| 2015    | 24        | 5.49%   |
| 2013    | 24        | 5.49%   |
| 2012    | 22        | 5.03%   |
| 2017    | 16        | 3.66%   |
| 2009    | 13        | 2.97%   |
| 2023    | 10        | 2.29%   |
| 2008    | 8         | 1.83%   |
| Unknown | 4         | 0.92%   |
| 2006    | 2         | 0.46%   |
| 2007    | 1         | 0.23%   |
| 2002    | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 286       | 65.45%  |
| Notebook       | 80        | 18.31%  |
| Mini pc        | 34        | 7.78%   |
| Server         | 29        | 6.64%   |
| Firewall       | 4         | 0.92%   |
| All in one     | 3         | 0.69%   |
| System on chip | 1         | 0.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 425       | 97.25%  |
| Yes  | 12        | 2.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 167       | 37.44%  |
| 16.01-24.0      | 93        | 20.85%  |
| 4.01-8.0        | 80        | 17.94%  |
| 32.01-64.0      | 48        | 10.76%  |
| 64.01-256.0     | 21        | 4.71%   |
| 2.01-3.0        | 13        | 2.91%   |
| 3.01-4.0        | 10        | 2.24%   |
| 24.01-32.0      | 7         | 1.57%   |
| 1.01-2.0        | 3         | 0.67%   |
| 0.51-1.0        | 3         | 0.67%   |
| More than 256.0 | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 225       | 50.22%  |
| 0.51-1.0    | 132       | 29.46%  |
| 1.01-2.0    | 54        | 12.05%  |
| 2.01-3.0    | 9         | 2.01%   |
| 4.01-8.0    | 8         | 1.79%   |
| 3.01-4.0    | 7         | 1.56%   |
| 0           | 4         | 0.89%   |
| 24.01-32.0  | 3         | 0.67%   |
| 64.01-256.0 | 2         | 0.45%   |
| 8.01-16.0   | 2         | 0.45%   |
| 32.01-64.0  | 1         | 0.22%   |
| Unknown     | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 310       | 69.35%  |
| 2      | 62        | 13.87%  |
| 0      | 34        | 7.61%   |
| 3      | 19        | 4.25%   |
| 4      | 9         | 2.01%   |
| 13     | 2         | 0.45%   |
| 7      | 2         | 0.45%   |
| 5      | 2         | 0.45%   |
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

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 346       | 77.93%  |
| Yes       | 98        | 22.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 426       | 97.26%  |
| No        | 12        | 2.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 285       | 64.48%  |
| Yes       | 157       | 35.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 324       | 73.64%  |
| Yes       | 116       | 26.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Canada  | 437       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 54        | 11.09%  |
| Toronto           | 44        | 9.03%   |
| Calgary           | 27        | 5.54%   |
| Ottawa            | 19        | 3.9%    |
| Victoria          | 18        | 3.7%    |
| Edmonton          | 18        | 3.7%    |
| Vancouver         | 15        | 3.08%   |
| Saint-Laurent     | 14        | 2.87%   |
| Winnipeg          | 12        | 2.46%   |
| Brampton          | 11        | 2.26%   |
| Surrey            | 10        | 2.05%   |
| Kitchener         | 10        | 2.05%   |
| QuГ©bec         | 6         | 1.23%   |
| Regina            | 5         | 1.03%   |
| Québec           | 5         | 1.03%   |
| London            | 5         | 1.03%   |
| Laval             | 5         | 1.03%   |
| Cambridge         | 5         | 1.03%   |
| St. Jean Baptiste | 4         | 0.82%   |
| St. Albert        | 4         | 0.82%   |
| Scarborough       | 4         | 0.82%   |
| Saskatoon         | 4         | 0.82%   |
| Sainte-Julie      | 4         | 0.82%   |
| Peterborough      | 4         | 0.82%   |
| North Vancouver   | 4         | 0.82%   |
| Moncton           | 4         | 0.82%   |
| Kingston          | 4         | 0.82%   |
| Gatineau          | 4         | 0.82%   |
| Burnaby           | 4         | 0.82%   |
| Windsor           | 3         | 0.62%   |
| Sherwood Park     | 3         | 0.62%   |
| Sarnia            | 3         | 0.62%   |
| QuÃ©bec         | 3         | 0.62%   |
| Pierrefonds       | 3         | 0.62%   |
| Oshawa            | 3         | 0.62%   |
| Oakville          | 3         | 0.62%   |
| Nanaimo           | 3         | 0.62%   |
| Mississauga       | 3         | 0.62%   |
| Maple Ridge       | 3         | 0.62%   |
| Longueuil         | 3         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 133    | 15.61%  |
| WDC                 | 74        | 198    | 14.62%  |
| Kingston            | 58        | 76     | 11.46%  |
| Seagate             | 55        | 119    | 10.87%  |
| Intel               | 22        | 35     | 4.35%   |
| Crucial             | 19        | 29     | 3.75%   |
| A-DATA Technology   | 18        | 33     | 3.56%   |
| Toshiba             | 16        | 30     | 3.16%   |
| Hitachi             | 15        | 58     | 2.96%   |
| SanDisk             | 13        | 17     | 2.57%   |
| Patriot             | 10        | 11     | 1.98%   |
| Dogfish             | 8         | 21     | 1.58%   |
| SPCC                | 7         | 8      | 1.38%   |
| SK hynix            | 7         | 9      | 1.38%   |
| Micron Technology   | 7         | 11     | 1.38%   |
| FORESEE             | 7         | 21     | 1.38%   |
| Transcend           | 6         | 7      | 1.19%   |
| OCZ                 | 6         | 10     | 1.19%   |
| Hewlett-Packard     | 6         | 6      | 1.19%   |
| HGST                | 5         | 75     | 0.99%   |
| Protectli           | 4         | 5      | 0.79%   |
| Phison              | 4         | 5      | 0.79%   |
| NVMe                | 4         | 5      | 0.79%   |
| Mushkin             | 4         | 4      | 0.79%   |
| Hoodisk             | 4         | 5      | 0.79%   |
| BIWIN               | 4         | 6      | 0.79%   |
| PNY                 | 3         | 4      | 0.59%   |
| Lexar               | 3         | 4      | 0.59%   |
| China               | 3         | 6      | 0.59%   |
| VisionTek           | 2         | 6      | 0.4%    |
| Timetec             | 2         | 2      | 0.4%    |
| Team                | 2         | 5      | 0.4%    |
| Silicon Motion      | 2         | 2      | 0.4%    |
| Netac               | 2         | 2      | 0.4%    |
| HPE                 | 2         | 9      | 0.4%    |
| Fujitsu             | 2         | 2      | 0.4%    |
| Corsair             | 2         | 4      | 0.4%    |
| Apacer              | 2         | 2      | 0.4%    |
| ZTC                 | 1         | 1      | 0.2%    |
| XPG                 | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 17        | 3.07%   |
| Kingston SA400S37120G 120GB          | 12        | 2.17%   |
| Samsung SSD 850 EVO 250GB            | 7         | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB       | 6         | 1.08%   |
| FORESEE 128GB SSD                    | 6         | 1.08%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB       | 5         | 0.9%    |
| Samsung SSD 860 EVO 500GB            | 5         | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.72%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.72%   |
| Samsung SSD 840 EVO 120GB            | 4         | 0.72%   |
| Dogfish SSD 128GB                    | 4         | 0.72%   |
| BIWIN SSD 128GB                      | 4         | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB         | 3         | 0.54%   |
| WDC WD20EZRX-00DC0B0 2TB             | 3         | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 0.54%   |
| Transcend TS256GMSA230S 256GB        | 3         | 0.54%   |
| Toshiba DT01ACA100 1TB               | 3         | 0.54%   |
| SPCC Solid State Disk 256GB          | 3         | 0.54%   |
| Seagate ST3500413AS 500GB            | 3         | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB       | 3         | 0.54%   |
| SanDisk SD6SB1M064G1022I 64GB        | 3         | 0.54%   |
| Samsung SSD 980 1TB                  | 3         | 0.54%   |
| Samsung SSD 970 EVO Plus 250GB       | 3         | 0.54%   |
| Samsung SSD 870 EVO 500GB            | 3         | 0.54%   |
| Samsung SSD 850 PRO 256GB            | 3         | 0.54%   |
| Kingston SUV500MS120G 120GB          | 3         | 0.54%   |
| Intel SSDSA2CW120G3 120GB            | 3         | 0.54%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 0.54%   |
| A-DATA SU800 256GB                   | 3         | 0.54%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 2         | 0.36%   |
| WDC WD6400AAKS-22A7B2 640GB          | 2         | 0.36%   |
| WDC WD40EFRX-68WT0N0 4TB             | 2         | 0.36%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.36%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2         | 0.36%   |
| WDC WD120EDAZ-11F3RA0 12TB           | 2         | 0.36%   |
| WDC WD10JPLX-00MBPT0 1TB             | 2         | 0.36%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.36%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 53        | 166    | 35.33%  |
| Seagate             | 53        | 117    | 35.33%  |
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

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 101    | 20.27%  |
| Kingston            | 55        | 67     | 18.9%   |
| Intel               | 19        | 32     | 6.53%   |
| A-DATA Technology   | 17        | 32     | 5.84%   |
| Crucial             | 16        | 24     | 5.5%    |
| SanDisk             | 13        | 17     | 4.47%   |
| WDC                 | 12        | 14     | 4.12%   |
| Dogfish             | 8         | 21     | 2.75%   |
| Patriot             | 7         | 8      | 2.41%   |
| FORESEE             | 7         | 21     | 2.41%   |
| Transcend           | 6         | 7      | 2.06%   |
| SPCC                | 6         | 7      | 2.06%   |
| OCZ                 | 6         | 10     | 2.06%   |
| Micron Technology   | 5         | 8      | 1.72%   |
| Protectli           | 4         | 5      | 1.37%   |
| Mushkin             | 4         | 4      | 1.37%   |
| Hoodisk             | 4         | 5      | 1.37%   |
| BIWIN               | 4         | 6      | 1.37%   |
| PNY                 | 3         | 4      | 1.03%   |
| China               | 3         | 6      | 1.03%   |
| VisionTek           | 2         | 6      | 0.69%   |
| SK hynix            | 2         | 2      | 0.69%   |
| Seagate             | 2         | 2      | 0.69%   |
| Netac               | 2         | 2      | 0.69%   |
| Lexar               | 2         | 3      | 0.69%   |
| Hewlett-Packard     | 2         | 2      | 0.69%   |
| Corsair             | 2         | 4      | 0.69%   |
| Apacer              | 2         | 2      | 0.69%   |
| ZTC                 | 1         | 1      | 0.34%   |
| walram              | 1         | 1      | 0.34%   |
| Toshiba             | 1         | 1      | 0.34%   |
| Timetec             | 1         | 1      | 0.34%   |
| Star Drive          | 1         | 1      | 0.34%   |
| SATADOM             | 1         | 2      | 0.34%   |
| Phison              | 1         | 1      | 0.34%   |
| NVMe                | 1         | 1      | 0.34%   |
| LITEON              | 1         | 1      | 0.34%   |
| Kston               | 1         | 2      | 0.34%   |
| KingDian            | 1         | 1      | 0.34%   |
| Innodisk            | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 265       | 446    | 57.61%  |
| HDD  | 127       | 457    | 27.61%  |
| NVMe | 68        | 103    | 14.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 359       | 903    | 84.07%  |
| NVMe | 68        | 103    | 15.93%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 294       | 500    | 71.01%  |
| 0.51-1.0   | 62        | 126    | 14.98%  |
| 1.01-2.0   | 26        | 63     | 6.28%   |
| 3.01-4.0   | 12        | 109    | 2.9%    |
| 4.01-10.0  | 9         | 52     | 2.17%   |
| 2.01-3.0   | 6         | 27     | 1.45%   |
| 10.01-20.0 | 5         | 26     | 1.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 181       | 39.26%  |
| 251-500        | 70        | 15.18%  |
| 1-20           | 56        | 12.15%  |
| 51-100         | 54        | 11.71%  |
| 21-50          | 48        | 10.41%  |
| 501-1000       | 34        | 7.38%   |
| 1001-2000      | 11        | 2.39%   |
| Unknown        | 4         | 0.87%   |
| More than 3000 | 3         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 393       | 86.37%  |
| 21-50     | 36        | 7.91%   |
| 51-100    | 11        | 2.42%   |
| 101-250   | 4         | 0.88%   |
| Unknown   | 4         | 0.88%   |
| 501-1000  | 3         | 0.66%   |
| 251-500   | 2         | 0.44%   |
| 1001-2000 | 2         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


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
| Mushkin MKNSSDEC512GB                      | 1         | 1      | 1.43%   |
| Micron Technology M500_MTFDDAK960MAV 960GB | 1         | 4      | 1.43%   |
| Kingston SV300S37A60G 64GB                 | 1         | 2      | 1.43%   |
| Kingston SV300S37A120G 120GB               | 1         | 1      | 1.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


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
| Mushkin             | 1         | 1      | 1.47%   |
| Micron Technology   | 1         | 4      | 1.47%   |
| HP Phison           | 1         | 1      | 1.47%   |
| Crucial             | 1         | 1      | 1.47%   |
| Apacer              | 1         | 1      | 1.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 76     | 50%     |
| SSD  | 32        | 57     | 48.48%  |
| NVMe | 1         | 2      | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-00Z10T0 1TB                         | 1         | 1      | 25%     |
| Seagate ST3250310AS 250GB                        | 1         | 1      | 25%     |
| SanDisk pSSD 256GB                               | 1         | 1      | 25%     |
| Samsung Electronics SSD PM830 2.5-inch 7mm 256GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |
| SanDisk             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 359       | 853    | 81.78%  |
| Malfunc  | 64        | 135    | 14.58%  |
| Detected | 12        | 14     | 2.73%   |
| Failed   | 4         | 4      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 354       | 65.68%  |
| AMD                                     | 55        | 10.2%   |
| Samsung Electronics                     | 25        | 4.64%   |
| SanDisk                                 | 17        | 3.15%   |
| Broadcom / LSI                          | 16        | 2.97%   |
| Nvidia                                  | 7         | 1.3%    |
| MAXIO Technology (Hangzhou)             | 7         | 1.3%    |
| Marvell Technology Group                | 6         | 1.11%   |
| ASMedia Technology                      | 6         | 1.11%   |
| SK hynix                                | 5         | 0.93%   |
| Silicon Motion                          | 5         | 0.93%   |
| Kingston Technology Company             | 5         | 0.93%   |
| Micron/Crucial Technology               | 4         | 0.74%   |
| Chelsio Communications                  | 4         | 0.74%   |
| Toshiba                                 | 3         | 0.56%   |
| Phison Electronics                      | 3         | 0.56%   |
| JMicron Technology                      | 3         | 0.56%   |
| VIA Technologies                        | 2         | 0.37%   |
| Silicon Image                           | 2         | 0.37%   |
| Micron Technology                       | 2         | 0.37%   |
| Hewlett-Packard                         | 2         | 0.37%   |
| Shenzhen Unionmemory Information System | 1         | 0.19%   |
| Realtek Semiconductor                   | 1         | 0.19%   |
| Netac Technology                        | 1         | 0.19%   |
| HighPoint Technologies                  | 1         | 0.19%   |
| Dell                                    | 1         | 0.19%   |
| ADATA Technology                        | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 38        | 6.22%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 29        | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 24        | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 23        | 3.76%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 23        | 3.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 17        | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 17        | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 2.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 14        | 2.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                           | 13        | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 1.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 1.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 11        | 1.8%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 10        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.47%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                     | 7         | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 1.15%   |
| Samsung NVMe SSD Controller 980                                                  | 6         | 0.98%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 6         | 0.98%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 6         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.82%   |
| Intel Elkhart Lake SATA AHCI                                                     | 5         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 0.82%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 5         | 0.82%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 5         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.65%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 4         | 0.65%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 4         | 0.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 364       | 67.66%  |
| NVMe | 77        | 14.31%  |
| IDE  | 58        | 10.78%  |
| RAID | 21        | 3.9%    |
| SAS  | 11        | 2.04%   |
| SCSI | 7         | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 374       | 85%     |
| AMD     | 63        | 14.32%  |
| Unknown | 2         | 0.45%   |
| ARM     | 1         | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron N5105 @ 2.00GHz            | 19        | 4.24%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 12        | 2.68%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 8         | 1.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 8         | 1.79%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 7         | 1.56%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 7         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 1.34%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 6         | 1.34%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 5         | 1.12%   |
| Intel Celeron CPU J3455E @ 1.50GHz       | 5         | 1.12%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5         | 1.12%   |
| AMD GX-412TC SOC                         | 5         | 1.12%   |
| Intel Core i5-4570TE CPU @ 2.70GHz       | 4         | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 4         | 0.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 4         | 0.89%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 4         | 0.89%   |
| Intel Core i3-2100 CPU @ 3.10GHz         | 4         | 0.89%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz      | 3         | 0.67%   |
| Intel Xeon                               | 3         | 0.67%   |
| Intel Pentium Silver N6005 @ 2.00GHz     | 3         | 0.67%   |
| Intel Pentium CPU G4560 @ 3.50GHz        | 3         | 0.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz        | 3         | 0.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 0.67%   |
| Intel Core i5-8500 CPU @ 3.00GHz         | 3         | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 3         | 0.67%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 3         | 0.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 3         | 0.67%   |
| Intel Core i3-4010U CPU @ 1.70GHz        | 3         | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 3         | 0.67%   |
| Intel Celeron J6413 @ 1.80GHz            | 3         | 0.67%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.67%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 3         | 0.67%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 3         | 0.67%   |
| Intel Xeon CPU X3430 @ 2.40GHz           | 2         | 0.45%   |
| Intel Xeon CPU E5645 @ 2.40GHz           | 2         | 0.45%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz      | 2         | 0.45%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz      | 2         | 0.45%   |
| Intel N100                               | 2         | 0.45%   |
| Intel CPU Version                        | 2         | 0.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 2         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 111       | 24.94%  |
| Intel Celeron           | 79        | 17.75%  |
| Intel Xeon              | 47        | 10.56%  |
| Intel Core i7           | 40        | 8.99%   |
| Intel Core i3           | 35        | 7.87%   |
| Other                   | 22        | 4.94%   |
| Intel Atom              | 16        | 3.6%    |
| Intel Core 2 Duo        | 10        | 2.25%   |
| Intel Pentium           | 8         | 1.8%    |
| AMD Ryzen 5             | 8         | 1.8%    |
| AMD GX                  | 7         | 1.57%   |
| AMD Ryzen 9             | 6         | 1.35%   |
| AMD Ryzen 7             | 6         | 1.35%   |
| AMD FX                  | 6         | 1.35%   |
| Intel Pentium Dual-Core | 5         | 1.12%   |
| Intel Pentium Silver    | 4         | 0.9%    |
| Intel Core 2 Quad       | 3         | 0.67%   |
| AMD EPYC                | 3         | 0.67%   |
| AMD Athlon 64 X2        | 3         | 0.67%   |
| Intel Pentium 4         | 2         | 0.45%   |
| AMD Ryzen Embedded      | 2         | 0.45%   |
| AMD Ryzen 5 PRO         | 2         | 0.45%   |
| AMD Ryzen 3             | 2         | 0.45%   |
| AMD Opteron             | 2         | 0.45%   |
| AMD G                   | 2         | 0.45%   |
| AMD Athlon II X2        | 2         | 0.45%   |
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

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 214       | 48.42%  |
| 2       | 128       | 28.96%  |
| 6       | 25        | 5.66%   |
| 8       | 19        | 4.3%    |
| Unknown | 15        | 3.39%   |
| 12      | 14        | 3.17%   |
| 16      | 9         | 2.04%   |
| 32      | 5         | 1.13%   |
| 10      | 4         | 0.9%    |
| 24      | 3         | 0.68%   |
| 1       | 2         | 0.45%   |
| 64      | 1         | 0.23%   |
| 20      | 1         | 0.23%   |
| 11      | 1         | 0.23%   |
| 3       | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 418       | 95%     |
| 2       | 15        | 3.41%   |
| Unknown | 7         | 1.59%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 250       | 57.08%  |
| 2       | 172       | 39.27%  |
| Unknown | 16        | 3.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 59        | 13.2%   |
| Unknown       | 48        | 10.74%  |
| KabyLake      | 44        | 9.84%   |
| IvyBridge     | 36        | 8.05%   |
| Silvermont    | 29        | 6.49%   |
| Skylake       | 27        | 6.04%   |
| SandyBridge   | 27        | 6.04%   |
| Penryn        | 19        | 4.25%   |
| Broadwell     | 17        | 3.8%    |
| Westmere      | 15        | 3.36%   |
| Goldmont plus | 15        | 3.36%   |
| Goldmont      | 14        | 3.13%   |
| Zen+          | 9         | 2.01%   |
| Piledriver    | 9         | 2.01%   |
| Nehalem       | 9         | 2.01%   |
| CometLake     | 8         | 1.79%   |
| Zen           | 7         | 1.57%   |
| Bonnell       | 7         | 1.57%   |
| Zen 3         | 6         | 1.34%   |
| Puma          | 5         | 1.12%   |
| K10           | 5         | 1.12%   |
| Jaguar        | 5         | 1.12%   |
| Zen 2         | 4         | 0.89%   |
| TigerLake     | 4         | 0.89%   |
| K8 Hammer     | 4         | 0.89%   |
| Core          | 4         | 0.89%   |
| Steamroller   | 3         | 0.67%   |
| Bobcat        | 3         | 0.67%   |
| NetBurst      | 2         | 0.45%   |
| P6            | 1         | 0.22%   |
| IceLake       | 1         | 0.22%   |
| Excavator     | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 291       | 66.29%  |
| AMD                        | 57        | 12.98%  |
| Nvidia                     | 53        | 12.07%  |
| Matrox Electronics Systems | 21        | 4.78%   |
| ASPEED Technology          | 16        | 3.64%   |
| Silicon Motion             | 1         | 0.23%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 32        | 7.13%   |
| Intel JasperLake [UHD Graphics]                                                          | 25        | 5.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 4.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 4.23%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 3.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 3.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 3.12%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 13        | 2.9%    |
| Intel HD Graphics 530                                                                    | 13        | 2.9%    |
| Intel HD Graphics 5500                                                                   | 12        | 2.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.45%   |
| Intel HD Graphics 500                                                                    | 10        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2%      |
| Intel HD Graphics 620                                                                    | 9         | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 1.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 1.56%   |
| Intel HD Graphics 630                                                                    | 6         | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.34%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.11%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5         | 1.11%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 5         | 1.11%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.89%   |
| Matrox Electronics Systems G200eR2                                                       | 4         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.89%   |
| Intel HD Graphics 610                                                                    | 4         | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.89%   |
| Nvidia GM107GL [Quadro K620]                                                             | 3         | 0.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.67%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3         | 0.67%   |
| AMD ES1000                                                                               | 3         | 0.67%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.45%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 2         | 0.45%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 2         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 264       | 59.59%  |
| 1 x AMD            | 50        | 11.29%  |
| 1 x Nvidia         | 44        | 9.93%   |
| 1 x Matrox         | 21        | 4.74%   |
| Other              | 17        | 3.84%   |
| 2 x Intel          | 16        | 3.61%   |
| 1 x ASPEED         | 15        | 3.39%   |
| Intel + Nvidia     | 8         | 1.81%   |
| 2 x AMD            | 3         | 0.68%   |
| Intel + AMD        | 2         | 0.45%   |
| 1 x Silicon Motion | 1         | 0.23%   |
| AMD + Nvidia       | 1         | 0.23%   |
| AMD + ASPEED       | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 396       | 89.39%  |
| Proprietary | 28        | 6.32%   |
| Unknown     | 19        | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 393       | 89.12%  |
| 1.01-2.0   | 13        | 2.95%   |
| 0.51-1.0   | 11        | 2.49%   |
| 3.01-4.0   | 8         | 1.81%   |
| 0.01-0.5   | 6         | 1.36%   |
| 7.01-8.0   | 4         | 0.91%   |
| 5.01-6.0   | 3         | 0.68%   |
| 8.01-16.0  | 2         | 0.45%   |
| 2.01-3.0   | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 12        | 11.11%  |
| Dell                    | 11        | 10.19%  |
| Samsung Electronics     | 10        | 9.26%   |
| LG Display              | 10        | 9.26%   |
| Chimei Innolux          | 9         | 8.33%   |
| Lenovo                  | 6         | 5.56%   |
| BenQ                    | 6         | 5.56%   |
| AU Optronics            | 6         | 5.56%   |
| BOE                     | 5         | 4.63%   |
| Acer                    | 4         | 3.7%    |
| Sony                    | 3         | 2.78%   |
| LG Electronics          | 3         | 2.78%   |
| Chi Mei Optoelectronics | 3         | 2.78%   |
| ASUSTek Computer        | 3         | 2.78%   |
| AOC                     | 3         | 2.78%   |
| Toshiba                 | 2         | 1.85%   |
| Hewlett-Packard         | 2         | 1.85%   |
| Apple                   | 2         | 1.85%   |
| Ancor Communications    | 2         | 1.85%   |
| ViewSonic               | 1         | 0.93%   |
| Videoseven              | 1         | 0.93%   |
| RTK                     | 1         | 0.93%   |
| LTV                     | 1         | 0.93%   |
| Insignia                | 1         | 0.93%   |
| HKC                     | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor TV XV 1920x1080                                       | 2         | 1.79%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 2         | 1.79%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 2         | 1.79%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 2         | 1.79%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2         | 1.79%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch       | 2         | 1.79%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch         | 2         | 1.79%   |
| ViewSonic LCD Monitor VSCFA2B 1920x1080 510x290mm 23.1-inch            | 1         | 0.89%   |
| Videoseven WL19A IGM1908 1280x1024 380x300mm 19.1-inch                 | 1         | 0.89%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1         | 0.89%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch               | 1         | 0.89%   |
| Sony TV  *30 SNY05D1 3840x2160 1660x930mm 74.9-inch                    | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1210x680mm 54.6-inch | 1         | 0.89%   |
| RTK CPL AIO PC RTK2482 1920x1080 510x280mm 22.9-inch                   | 1         | 0.89%   |
| LTV LTV1280M1A LTV0A3C 1024x768 800x450mm 36.1-inch                    | 1         | 0.89%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440                      | 1         | 0.89%   |
| LG Electronics LCD Monitor LG Ultra HD 7680x2160                       | 1         | 0.89%   |
| LG Electronics LCD Monitor LG Ultra HD                                 | 1         | 0.89%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 0.89%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch            | 1         | 0.89%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch           | 1         | 0.89%   |
| Lenovo LEN-M93z-B  LEN0093 1920x1080 510x290mm 23.1-inch               | 1         | 0.89%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                | 1         | 0.89%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 1         | 0.89%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                | 1         | 0.89%   |
| Insignia LCD Monitor BBY0050 1920x1080 700x400mm 31.7-inch             | 1         | 0.89%   |
| HKC 27E6QC HKC274F 2560x1440 600x330mm 27.0-inch                       | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 43.93%  |
| 1366x768 (WXGA)    | 18        | 16.82%  |
| 3840x2160 (4K)     | 8         | 7.48%   |
| 1600x900 (HD+)     | 6         | 5.61%   |
| 2560x1440 (QHD)    | 4         | 3.74%   |
| 1280x800 (WXGA)    | 4         | 3.74%   |
| 1680x1050 (WSXGA+) | 3         | 2.8%    |
| 3440x1440          | 2         | 1.87%   |
| 2560x1080          | 2         | 1.87%   |
| 1920x1200 (WUXGA)  | 2         | 1.87%   |
| 1440x900 (WXGA+)   | 2         | 1.87%   |
| 1280x1024 (SXGA)   | 2         | 1.87%   |
| Unknown            | 2         | 1.87%   |
| 7680x2160          | 1         | 0.93%   |
| 2256x1504          | 1         | 0.93%   |
| 1600x1200          | 1         | 0.93%   |
| 1280x854           | 1         | 0.93%   |
| 1024x768 (XGA)     | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 17        | 15.6%   |
| 24      | 13        | 11.93%  |
| 15      | 13        | 11.93%  |
| 27      | 11        | 10.09%  |
| 21      | 8         | 7.34%   |
| 12      | 7         | 6.42%   |
| Unknown | 7         | 6.42%   |
| 23      | 5         | 4.59%   |
| 19      | 5         | 4.59%   |
| 34      | 4         | 3.67%   |
| 22      | 4         | 3.67%   |
| 54      | 3         | 2.75%   |
| 14      | 3         | 2.75%   |
| 31      | 2         | 1.83%   |
| 17      | 2         | 1.83%   |
| 74      | 1         | 0.92%   |
| 36      | 1         | 0.92%   |
| 20      | 1         | 0.92%   |
| 18      | 1         | 0.92%   |
| 11      | 1         | 0.92%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 29        | 26.85%  |
| 301-350     | 25        | 23.15%  |
| 401-500     | 16        | 14.81%  |
| 201-300     | 16        | 14.81%  |
| Unknown     | 7         | 6.48%   |
| 701-800     | 5         | 4.63%   |
| 351-400     | 4         | 3.7%    |
| 1001-1500   | 3         | 2.78%   |
| 601-700     | 2         | 1.85%   |
| 1501-2000   | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 78        | 74.29%  |
| 16/10   | 11        | 10.48%  |
| Unknown | 7         | 6.67%   |
| 21/9    | 4         | 3.81%   |
| 5/4     | 2         | 1.9%    |
| 3/2     | 2         | 1.9%    |
| 4/3     | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 26        | 24.07%  |
| 81-90          | 15        | 13.89%  |
| 301-350        | 11        | 10.19%  |
| 61-70          | 7         | 6.48%   |
| 101-110        | 7         | 6.48%   |
| 91-100         | 7         | 6.48%   |
| Unknown        | 7         | 6.48%   |
| 351-500        | 6         | 5.56%   |
| 151-200        | 6         | 5.56%   |
| More than 1000 | 4         | 3.7%    |
| 71-80          | 4         | 3.7%    |
| 251-300        | 3         | 2.78%   |
| 121-130        | 2         | 1.85%   |
| 51-60          | 1         | 0.93%   |
| 141-150        | 1         | 0.93%   |
| 501-1000       | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 44        | 40.37%  |
| 101-120 | 28        | 25.69%  |
| 121-160 | 20        | 18.35%  |
| 161-240 | 9         | 8.26%   |
| Unknown | 7         | 6.42%   |
| 1-50    | 1         | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 316       | 71.33%  |
| 1     | 117       | 26.41%  |
| 2     | 10        | 2.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 341       | 54.74%  |
| Realtek Semiconductor             | 159       | 25.52%  |
| Broadcom                          | 42        | 6.74%   |
| Qualcomm Atheros                  | 28        | 4.49%   |
| Chelsio Communications            | 6         | 0.96%   |
| MediaTek                          | 5         | 0.8%    |
| Marvell Technology Group          | 4         | 0.64%   |
| Solarflare Communications         | 3         | 0.48%   |
| Ralink                            | 3         | 0.48%   |
| Mellanox Technologies             | 3         | 0.48%   |
| Sierra Wireless                   | 2         | 0.32%   |
| Nvidia                            | 2         | 0.32%   |
| IBM                               | 2         | 0.32%   |
| Ericsson Business Mobile Networks | 2         | 0.32%   |
| Apple                             | 2         | 0.32%   |
| 3Com                              | 2         | 0.32%   |
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

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 130       | 16.54%  |
| Intel I211 Gigabit Network Connection                                         | 38        | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 34        | 4.33%   |
| Intel 82574L Gigabit Network Connection                                       | 28        | 3.56%   |
| Intel I210 Gigabit Network Connection                                         | 23        | 2.93%   |
| Intel Ethernet Connection I217-LM                                             | 22        | 2.8%    |
| Intel Ethernet Controller I225-V                                              | 21        | 2.67%   |
| Intel I350 Gigabit Network Connection                                         | 20        | 2.54%   |
| Intel Ethernet Controller I226-V                                              | 17        | 2.16%   |
| Intel 82576 Gigabit Network Connection                                        | 15        | 1.91%   |
| Intel Wireless 7265                                                           | 13        | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                             | 11        | 1.4%    |
| Intel 82583V Gigabit Network Connection                                       | 11        | 1.4%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11        | 1.4%    |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 1.15%   |
| Intel Wireless 8260                                                           | 9         | 1.15%   |
| Intel Ethernet Connection I219-LM                                             | 9         | 1.15%   |
| Intel Wireless 3165                                                           | 8         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                           | 8         | 1.02%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.02%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 8         | 1.02%   |
| Intel Wireless 7260                                                           | 7         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 0.89%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 5         | 0.64%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.64%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 0.51%   |
| Intel Wireless 3160                                                           | 4         | 0.51%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 4         | 0.51%   |
| Intel Ethernet Controller X550                                                | 4         | 0.51%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 4         | 0.51%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.51%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.51%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 62.96%  |
| Qualcomm Atheros                | 20        | 12.35%  |
| Realtek Semiconductor           | 15        | 9.26%   |
| Broadcom                        | 8         | 4.94%   |
| MediaTek                        | 5         | 3.09%   |
| Ralink                          | 3         | 1.85%   |
| TP-Link                         | 1         | 0.62%   |
| Sierra Wireless                 | 1         | 0.62%   |
| Ralink Technology               | 1         | 0.62%   |
| Qualcomm Atheros Communications | 1         | 0.62%   |
| NetGear                         | 1         | 0.62%   |
| Marvell Technology Group        | 1         | 0.62%   |
| Linksys                         | 1         | 0.62%   |
| IMC Networks                    | 1         | 0.62%   |
| D-Link                          | 1         | 0.62%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 13        | 7.88%   |
| Intel Wireless 8260                                                     | 9         | 5.45%   |
| Intel Wireless 3165                                                     | 8         | 4.85%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 4.85%   |
| Intel Wireless 7260                                                     | 7         | 4.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 4.24%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.42%   |
| Intel Wireless 3160                                                     | 4         | 2.42%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 4         | 2.42%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 4         | 2.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.82%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.82%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.21%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.21%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.21%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.21%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.21%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 0.61%   |
| Sierra Wireless EM7455                                                  | 1         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 293       | 56.67%  |
| Realtek Semiconductor     | 154       | 29.79%  |
| Broadcom                  | 34        | 6.58%   |
| Qualcomm Atheros          | 11        | 2.13%   |
| Chelsio Communications    | 4         | 0.77%   |
| Solarflare Communications | 3         | 0.58%   |
| Marvell Technology Group  | 3         | 0.58%   |
| Nvidia                    | 2         | 0.39%   |
| Apple                     | 2         | 0.39%   |
| 3Com                      | 2         | 0.39%   |
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

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 130       | 21.49%  |
| Intel I211 Gigabit Network Connection                                         | 38        | 6.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 34        | 5.62%   |
| Intel 82574L Gigabit Network Connection                                       | 28        | 4.63%   |
| Intel I210 Gigabit Network Connection                                         | 23        | 3.8%    |
| Intel Ethernet Connection I217-LM                                             | 22        | 3.64%   |
| Intel Ethernet Controller I225-V                                              | 21        | 3.47%   |
| Intel I350 Gigabit Network Connection                                         | 20        | 3.31%   |
| Intel Ethernet Controller I226-V                                              | 17        | 2.81%   |
| Intel 82576 Gigabit Network Connection                                        | 15        | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 11        | 1.82%   |
| Intel 82583V Gigabit Network Connection                                       | 11        | 1.82%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 11        | 1.82%   |
| Intel 82580 Gigabit Network Connection                                        | 10        | 1.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 9         | 1.49%   |
| Intel Ethernet Connection I219-LM                                             | 9         | 1.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 8         | 1.32%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 8         | 1.32%   |
| Intel Ethernet Connection (2) I219-LM                                         | 7         | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                          | 5         | 0.83%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.83%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 5         | 0.83%   |
| Intel Ethernet Controller X550                                                | 4         | 0.66%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4         | 0.66%   |
| Intel Ethernet Connection (5) I219-LM                                         | 4         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 0.66%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.66%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 4         | 0.66%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 4         | 0.66%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 3         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 3         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 3         | 0.5%    |
| Intel Ethernet Connection I354                                                | 3         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.5%    |
| Intel Ethernet Connection (3) I218-V                                          | 3         | 0.5%    |
| Intel Ethernet Connection (2) I218-LM                                         | 3         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                                        | 3         | 0.5%    |
| Intel 82575GB Gigabit Network Connection                                      | 3         | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                                    | 3         | 0.5%    |
| Intel 82541PI Gigabit Ethernet Controller                                     | 3         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 426       | 71.12%  |
| WiFi     | 157       | 26.21%  |
| Unknown  | 12        | 2%      |
| Modem    | 4         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 396       | 84.43%  |
| WiFi     | 73        | 15.57%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 152       | 34.16%  |
| 4     | 75        | 16.85%  |
| 3     | 74        | 16.63%  |
| 1     | 59        | 13.26%  |
| 6     | 31        | 6.97%   |
| 5     | 31        | 6.97%   |
| 8     | 7         | 1.57%   |
| 7     | 6         | 1.35%   |
| 0     | 4         | 0.9%    |
| 10    | 2         | 0.45%   |
| 9     | 2         | 0.45%   |
| 14    | 1         | 0.22%   |
| 12    | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 387       | 86%     |
| Yes  | 63        | 14%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 61.54%  |
| Cambridge Silicon Radio         | 9         | 7.69%   |
| Realtek Semiconductor           | 5         | 4.27%   |
| IMC Networks                    | 5         | 4.27%   |
| Foxconn / Hon Hai               | 5         | 4.27%   |
| Broadcom                        | 5         | 4.27%   |
| Qualcomm Atheros Communications | 4         | 3.42%   |
| Apple                           | 3         | 2.56%   |
| Lite-On Technology              | 2         | 1.71%   |
| ASUSTek Computer                | 2         | 1.71%   |
| Alps Electric                   | 2         | 1.71%   |
| Toshiba                         | 1         | 0.85%   |
| MediaTek                        | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 36        | 30.51%  |
| Intel AX201 Bluetooth                                       | 13        | 11.02%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9         | 7.63%   |
| Intel AX200 Bluetooth                                       | 8         | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 6         | 5.08%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 4.24%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 2.54%   |
| Realtek Bluetooth Adapter                                   | 2         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.69%   |
| Intel Wireless Bluetooth                                    | 2         | 1.69%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 2         | 1.69%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 2         | 1.69%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.69%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 1.69%   |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 0.85%   |
| Realtek RTL8723A Bluetooth                                  | 1         | 0.85%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.85%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.85%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.85%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.85%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.85%   |
| Intel AX210 Bluetooth                                       | 1         | 0.85%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1         | 0.85%   |
| IMC Networks Bluetooth                                      | 1         | 0.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.85%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.85%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.85%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.85%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 0.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 0.85%   |
| Apple Bluetooth Host Controller                             | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 287       | 68.66%  |
| AMD                      | 60        | 14.35%  |
| Nvidia                   | 45        | 10.77%  |
| C-Media Electronics      | 6         | 1.44%   |
| KTMicro                  | 4         | 0.96%   |
| Logitech                 | 3         | 0.72%   |
| Texas Instruments        | 2         | 0.48%   |
| ASUSTek Computer         | 2         | 0.48%   |
| Yamaha                   | 1         | 0.24%   |
| XMOS                     | 1         | 0.24%   |
| SteelSeries ApS          | 1         | 0.24%   |
| Plantronics              | 1         | 0.24%   |
| MosArt Semiconductor     | 1         | 0.24%   |
| Micro Star International | 1         | 0.24%   |
| Generalplus Technology   | 1         | 0.24%   |
| Elgato Systems           | 1         | 0.24%   |
| Creative Labs            | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 6.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 29        | 5.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 5.23%   |
| Intel Jasper Lake HD Audio                                                                        | 25        | 5.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 4.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 3.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 3.42%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 2.41%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.21%   |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.21%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 6         | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.21%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 1.01%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 5         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.01%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 5         | 1.01%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.01%   |
| KTMicro KT USB Audio                                                                              | 4         | 0.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.8%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 0.8%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 3         | 0.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 83        | 17.26%  |
| Samsung Electronics          | 75        | 15.59%  |
| Kingston                     | 68        | 14.14%  |
| Unknown                      | 42        | 8.73%   |
| Micron Technology            | 37        | 7.69%   |
| Crucial                      | 33        | 6.86%   |
| Corsair                      | 33        | 6.86%   |
| G.Skill                      | 28        | 5.82%   |
| Unknown                      | 16        | 3.33%   |
| Unknown (ABCD)               | 8         | 1.66%   |
| A-DATA Technology            | 8         | 1.66%   |
| Ramaxel Technology           | 7         | 1.46%   |
| Apacer                       | 5         | 1.04%   |
| Transcend                    | 4         | 0.83%   |
| Team                         | 4         | 0.83%   |
| Nanya Technology             | 4         | 0.83%   |
| Unknown (0x0C26)             | 3         | 0.62%   |
| Timetec                      | 3         | 0.62%   |
| Patriot                      | 3         | 0.62%   |
| OCZ                          | 3         | 0.62%   |
| Avant                        | 2         | 0.42%   |
| V-Color                      | 1         | 0.21%   |
| Unknown (0x0DD5)             | 1         | 0.21%   |
| Toshiba                      | 1         | 0.21%   |
| Teikon                       | 1         | 0.21%   |
| Silicon Power                | 1         | 0.21%   |
| PNY                          | 1         | 0.21%   |
| Patriot Memory (PDP Systems) | 1         | 0.21%   |
| Lexar Co Limited             | 1         | 0.21%   |
| Elpida                       | 1         | 0.21%   |
| Cors                         | 1         | 0.21%   |
| AMD                          | 1         | 0.21%   |
| 0C26000000AD                 | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 16        | 3.09%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 0.97%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 5         | 0.97%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s        | 5         | 0.97%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 4         | 0.77%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 4         | 0.77%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 0.77%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s            | 4         | 0.77%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s            | 4         | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 3         | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3         | 0.58%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.58%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 0.58%   |
| SK hynix RAM HMT351U7BFR8A-H9 4GB DIMM DDR3 1333MT/s           | 3         | 0.58%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 3         | 0.58%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s             | 3         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 3         | 0.58%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 3         | 0.58%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 3         | 0.58%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s         | 3         | 0.58%   |
| Unknown RAM Module 8GB 1600MT/s                                | 2         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 2         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                      | 2         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 2         | 0.39%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s             | 2         | 0.39%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 2         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.39%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s           | 2         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.39%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.39%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 2         | 0.39%   |
| SK hynix RAM HMT151R7BFR4C-H9 4GB DIMM DDR3 1333MT/s           | 2         | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 2         | 0.39%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s           | 2         | 0.39%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB RIMM DDR4 2133MT/s           | 2         | 0.39%   |
| SK hynix RAM HMA451R7AFR8N-TF 4GB RIMM DDR4 2133MT/s           | 2         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 201       | 47.86%  |
| DDR4    | 156       | 37.14%  |
| DDR2    | 18        | 4.29%   |
| Unknown | 15        | 3.57%   |
| LPDDR4  | 12        | 2.86%   |
| SDRAM   | 7         | 1.67%   |
| DDR5    | 7         | 1.67%   |
| LPDDR3  | 2         | 0.48%   |
| DDR     | 2         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 229       | 55.18%  |
| SODIMM       | 173       | 41.69%  |
| Row Of Chips | 4         | 0.96%   |
| RIMM         | 3         | 0.72%   |
| Unknown      | 3         | 0.72%   |
| Chip         | 2         | 0.48%   |
| FB-DIMM      | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 155       | 33.84%  |
| 8192  | 153       | 33.41%  |
| 2048  | 62        | 13.54%  |
| 16384 | 61        | 13.32%  |
| 1024  | 15        | 3.28%   |
| 32768 | 10        | 2.18%   |
| 512   | 2         | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 135       | 29.93%  |
| 1333    | 64        | 14.19%  |
| 3200    | 44        | 9.76%   |
| 2400    | 44        | 9.76%   |
| 2667    | 42        | 9.31%   |
| 2133    | 29        | 6.43%   |
| 1067    | 14        | 3.1%    |
| 800     | 13        | 2.88%   |
| 2666    | 10        | 2.22%   |
| Unknown | 10        | 2.22%   |
| 667     | 9         | 2%      |
| 4800    | 6         | 1.33%   |
| 1334    | 6         | 1.33%   |
| 3000    | 5         | 1.11%   |
| 1066    | 4         | 0.89%   |
| 3600    | 3         | 0.67%   |
| 1867    | 3         | 0.67%   |
| 4267    | 2         | 0.44%   |
| 1866    | 2         | 0.44%   |
| 400     | 2         | 0.44%   |
| 6400    | 1         | 0.22%   |
| 5200    | 1         | 0.22%   |
| 3400    | 1         | 0.22%   |
| 333     | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 18        | 33.33%  |
| Microdia                      | 6         | 11.11%  |
| Bison Electronics             | 6         | 11.11%  |
| Realtek Semiconductor         | 5         | 9.26%   |
| Logitech                      | 3         | 5.56%   |
| Lite-On Technology            | 3         | 5.56%   |
| IMC Networks                  | 3         | 5.56%   |
| Syntek                        | 2         | 3.7%    |
| Sunplus Innovation Technology | 2         | 3.7%    |
| Suyin                         | 1         | 1.85%   |
| Quanta                        | 1         | 1.85%   |
| Luxvisions Innotech Limited   | 1         | 1.85%   |
| Lenovo                        | 1         | 1.85%   |
| ALi                           | 1         | 1.85%   |
| Alcor Micro                   | 1         | 1.85%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 4         | 7.41%   |
| Bison Integrated Camera                       | 4         | 7.41%   |
| Lite-On Integrated Camera                     | 3         | 5.56%   |
| Chicony HD Webcam                             | 3         | 5.56%   |
| Syntek Lenovo EasyCamera                      | 1         | 1.85%   |
| Syntek ASUS USB2.0 camera                     | 1         | 1.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 1.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 1.85%   |
| Sunplus ASUS Webcam                           | 1         | 1.85%   |
| Realtek USB 2.0 PC Camera                     | 1         | 1.85%   |
| Realtek PC Camera                             | 1         | 1.85%   |
| Realtek Integrated Webcam HD                  | 1         | 1.85%   |
| Realtek Integrated Webcam                     | 1         | 1.85%   |
| Realtek HD Webcam - Realtek                   | 1         | 1.85%   |
| Quanta Realtek PC Camera                      | 1         | 1.85%   |
| Microdia Sonix USB 2.0 Camera                 | 1         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_2M          | 1         | 1.85%   |
| Microdia JOYACCESS JA-Webcam                  | 1         | 1.85%   |
| Microdia Integrated_Webcam_HD                 | 1         | 1.85%   |
| Microdia Integrated Webcam HD                 | 1         | 1.85%   |
| Microdia Integrated Webcam                    | 1         | 1.85%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 1.85%   |
| Logitech Webcam C310                          | 1         | 1.85%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.85%   |
| Logitech BRIO Ultra HD Webcam                 | 1         | 1.85%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.85%   |
| IMC Networks UVC VGA Webcam                   | 1         | 1.85%   |
| IMC Networks Integrated Webcam                | 1         | 1.85%   |
| IMC Networks Integrated Camera                | 1         | 1.85%   |
| Chicony WebCam                                | 1         | 1.85%   |
| Chicony VGA 24fps UVC Webcam                  | 1         | 1.85%   |
| Chicony USB2.0 HD UVC WebCam                  | 1         | 1.85%   |
| Chicony TOSHIBA Web Camera - FHD              | 1         | 1.85%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.85%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 1.85%   |
| Chicony Integrated Camera [ThinkPad]          | 1         | 1.85%   |
| Chicony HP HD Camera                          | 1         | 1.85%   |
| Chicony HP 0.3MP Webcam                       | 1         | 1.85%   |
| Chicony FJ Camera                             | 1         | 1.85%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 1         | 1.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 225       | 49.34%  |
| 0     | 120       | 26.32%  |
| 2     | 70        | 15.35%  |
| 3     | 29        | 6.36%   |
| 4     | 10        | 2.19%   |
| 5     | 2         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 280       | 63.93%  |
| Bluetooth                | 50        | 11.42%  |
| Net/wireless             | 32        | 7.31%   |
| Card reader              | 20        | 4.57%   |
| Firewire controller      | 15        | 3.42%   |
| Fingerprint reader       | 13        | 2.97%   |
| Net/ethernet             | 8         | 1.83%   |
| Sound                    | 6         | 1.37%   |
| Network                  | 6         | 1.37%   |
| Graphics card            | 3         | 0.68%   |
| Storage/raid             | 2         | 0.46%   |
| Storage                  | 2         | 0.46%   |
| Storage/ata              | 1         | 0.23%   |

