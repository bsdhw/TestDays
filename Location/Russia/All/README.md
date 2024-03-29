BSD in Russia - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Russia/Desktop/README.md) and [notebooks](/Location/Russia/Notebook/README.md).

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

Total: 1053

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [a7aada8678](https://bsd-hardware.info/?probe=a7aada8678) | Feb 17, 2024 |
| Deciso        | NetBoard-A20                | Notebook    | [ebbe4a0d21](https://bsd-hardware.info/?probe=ebbe4a0d21) | Feb 17, 2024 |
| IBM           | 94Y7614                     | Server      | [d2178f7e1a](https://bsd-hardware.info/?probe=d2178f7e1a) | Feb 13, 2024 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4bdab4711](https://bsd-hardware.info/?probe=d4bdab4711) | Feb 10, 2024 |
| HP            | 339A                        | Desktop     | [5d1b482427](https://bsd-hardware.info/?probe=5d1b482427) | Feb 10, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [bf8b98f373](https://bsd-hardware.info/?probe=bf8b98f373) | Feb 08, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [47e91ddd92](https://bsd-hardware.info/?probe=47e91ddd92) | Feb 08, 2024 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [d5a88cb5c0](https://bsd-hardware.info/?probe=d5a88cb5c0) | Feb 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [05745ae76a](https://bsd-hardware.info/?probe=05745ae76a) | Feb 04, 2024 |
| ASUSTek       | F8Vr                        | Notebook    | [2f3b6a6089](https://bsd-hardware.info/?probe=2f3b6a6089) | Feb 03, 2024 |
| ETegro Tec... | ETRS130G3 31S98MB0020       | Server      | [fcd2bfeb09](https://bsd-hardware.info/?probe=fcd2bfeb09) | Feb 03, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [d145d7a650](https://bsd-hardware.info/?probe=d145d7a650) | Feb 01, 2024 |
| ASUSTek       | P5E3 PRO                    | Desktop     | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [80f34deedc](https://bsd-hardware.info/?probe=80f34deedc) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [18168c211d](https://bsd-hardware.info/?probe=18168c211d) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [754c764123](https://bsd-hardware.info/?probe=754c764123) | Jan 29, 2024 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [4f45811a17](https://bsd-hardware.info/?probe=4f45811a17) | Jan 27, 2024 |
| Unknown       | Q-790                       | Desktop     | [ec71672aed](https://bsd-hardware.info/?probe=ec71672aed) | Jan 25, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [6aeb253575](https://bsd-hardware.info/?probe=6aeb253575) | Jan 25, 2024 |
| Intel         | H81U                        | Notebook    | [9b68a7c006](https://bsd-hardware.info/?probe=9b68a7c006) | Jan 25, 2024 |
| Unknown       | Q-790                       | Desktop     | [b94e9febe7](https://bsd-hardware.info/?probe=b94e9febe7) | Jan 24, 2024 |
| Intel         | H81U                        | Notebook    | [c36eaa9c79](https://bsd-hardware.info/?probe=c36eaa9c79) | Jan 24, 2024 |
| HP            | ProLiant DL180 G6           | Server      | [8682cccdcb](https://bsd-hardware.info/?probe=8682cccdcb) | Jan 24, 2024 |
| AMI           | PEISIA E3845 VER1.0         | Desktop     | [2448066e32](https://bsd-hardware.info/?probe=2448066e32) | Jan 23, 2024 |
| HP            | 339A                        | Desktop     | [c61c3c0b1b](https://bsd-hardware.info/?probe=c61c3c0b1b) | Jan 23, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [838906ef1b](https://bsd-hardware.info/?probe=838906ef1b) | Jan 21, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [e2053919c4](https://bsd-hardware.info/?probe=e2053919c4) | Jan 15, 2024 |
| Intel         | D410PT AAE76528-404         | Desktop     | [87da69a1ef](https://bsd-hardware.info/?probe=87da69a1ef) | Jan 10, 2024 |
| Rembrandt     | ARB928                      | Notebook    | [47621d7796](https://bsd-hardware.info/?probe=47621d7796) | Jan 10, 2024 |
| HP            | 3641h                       | Desktop     | [90626880cf](https://bsd-hardware.info/?probe=90626880cf) | Jan 09, 2024 |
| ASUSTek       | P8B-E Series                | Server      | [32d763e38e](https://bsd-hardware.info/?probe=32d763e38e) | Jan 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5d4fc3e285](https://bsd-hardware.info/?probe=5d4fc3e285) | Jan 05, 2024 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [04c19f755d](https://bsd-hardware.info/?probe=04c19f755d) | Jan 03, 2024 |
| Unknown       | Unknown                     | Desktop     | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c1c8f32b44](https://bsd-hardware.info/?probe=c1c8f32b44) | Dec 30, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [0001356297](https://bsd-hardware.info/?probe=0001356297) | Dec 27, 2023 |
| Rembrandt     | ARB928                      | Notebook    | [c9a9bfd4aa](https://bsd-hardware.info/?probe=c9a9bfd4aa) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1f28c229cb](https://bsd-hardware.info/?probe=1f28c229cb) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d4f5a9c35a](https://bsd-hardware.info/?probe=d4f5a9c35a) | Dec 27, 2023 |
| eMachines     | eM350                       | Notebook    | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Orange Pi     | 5P                          | Soc         | [aa6c177cb0](https://bsd-hardware.info/?probe=aa6c177cb0) | Dec 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [84a9704b97](https://bsd-hardware.info/?probe=84a9704b97) | Dec 21, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL1... | Notebook    | [97fb2e025e](https://bsd-hardware.info/?probe=97fb2e025e) | Dec 20, 2023 |
| ASUSTek       | P5B-VM                      | Desktop     | [00e7a346b2](https://bsd-hardware.info/?probe=00e7a346b2) | Dec 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Supermicro    | X7SBi                       | Desktop     | [a0124f00ba](https://bsd-hardware.info/?probe=a0124f00ba) | Dec 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [9368c19a35](https://bsd-hardware.info/?probe=9368c19a35) | Dec 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1034c9883a](https://bsd-hardware.info/?probe=1034c9883a) | Dec 06, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [0df52370a2](https://bsd-hardware.info/?probe=0df52370a2) | Dec 04, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [e96bb84b37](https://bsd-hardware.info/?probe=e96bb84b37) | Dec 02, 2023 |
| Lenovo        | 3129 SDK0J40679 WIN 3273... | Desktop     | [da81c9605d](https://bsd-hardware.info/?probe=da81c9605d) | Dec 01, 2023 |
| Intel         | Geminilake                  | Desktop     | [0b0a4f8d68](https://bsd-hardware.info/?probe=0b0a4f8d68) | Nov 30, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [87351f500b](https://bsd-hardware.info/?probe=87351f500b) | Nov 26, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [c6ff092502](https://bsd-hardware.info/?probe=c6ff092502) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce88332d94](https://bsd-hardware.info/?probe=ce88332d94) | Nov 25, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| HP            | 339A                        | Desktop     | [fdc6ee7b57](https://bsd-hardware.info/?probe=fdc6ee7b57) | Nov 22, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | Desktop     | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Supermicro    | H8DGU                       | Server      | [aa3a09d113](https://bsd-hardware.info/?probe=aa3a09d113) | Nov 15, 2023 |
| Supermicro    | H8DGU                       | Server      | [5ca736990f](https://bsd-hardware.info/?probe=5ca736990f) | Nov 15, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3e93db0df7](https://bsd-hardware.info/?probe=3e93db0df7) | Nov 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [626ff9ba56](https://bsd-hardware.info/?probe=626ff9ba56) | Nov 13, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [c535fae89f](https://bsd-hardware.info/?probe=c535fae89f) | Nov 10, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [81e93afe2e](https://bsd-hardware.info/?probe=81e93afe2e) | Nov 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [227e21dfdf](https://bsd-hardware.info/?probe=227e21dfdf) | Nov 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [3dafd6bd42](https://bsd-hardware.info/?probe=3dafd6bd42) | Nov 07, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [40dffa3e21](https://bsd-hardware.info/?probe=40dffa3e21) | Nov 06, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| Intel         | DCP847SKE                   | Desktop     | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [b688e6b635](https://bsd-hardware.info/?probe=b688e6b635) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | Desktop     | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7148ec01b2](https://bsd-hardware.info/?probe=7148ec01b2) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| Intel         | S5520UR E22554-752          | Server      | [8e20922890](https://bsd-hardware.info/?probe=8e20922890) | Oct 20, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Intel         | H81U                        | Notebook    | [9ed05368b5](https://bsd-hardware.info/?probe=9ed05368b5) | Oct 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [d5676f7895](https://bsd-hardware.info/?probe=d5676f7895) | Oct 10, 2023 |
| TONK          | TN2800                      | Desktop     | [a47aba3406](https://bsd-hardware.info/?probe=a47aba3406) | Oct 10, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [66a1e081e6](https://bsd-hardware.info/?probe=66a1e081e6) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [3f63740c0e](https://bsd-hardware.info/?probe=3f63740c0e) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [9748abc90d](https://bsd-hardware.info/?probe=9748abc90d) | Oct 02, 2023 |
| Platform      | ARB938                      | Notebook    | [141d043221](https://bsd-hardware.info/?probe=141d043221) | Oct 02, 2023 |
| TONK          | TN2800                      | Desktop     | [bce9c62915](https://bsd-hardware.info/?probe=bce9c62915) | Sep 29, 2023 |
| Intel         | S5520UR E22554-752          | Server      | [ab0b5c4d36](https://bsd-hardware.info/?probe=ab0b5c4d36) | Sep 27, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [0a035e25a9](https://bsd-hardware.info/?probe=0a035e25a9) | Sep 26, 2023 |
| Intel         | S5520UR E22554-753          | Server      | [4094543b6f](https://bsd-hardware.info/?probe=4094543b6f) | Sep 25, 2023 |
| ASUSTek       | P9D-MV Series               | Server      | [bccf02e740](https://bsd-hardware.info/?probe=bccf02e740) | Sep 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [11cf3b211c](https://bsd-hardware.info/?probe=11cf3b211c) | Sep 22, 2023 |
| ASRock        | Z690 Phantom Gaming 4/D5    | Desktop     | [6eab8daef7](https://bsd-hardware.info/?probe=6eab8daef7) | Sep 21, 2023 |
| Apple         | MacPro4,1                   | Desktop     | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| Platform      | ARB938                      | Notebook    | [17b7c850c4](https://bsd-hardware.info/?probe=17b7c850c4) | Sep 14, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [6be22d7887](https://bsd-hardware.info/?probe=6be22d7887) | Sep 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| Intel         | HM570                       | Desktop     | [3112f263f5](https://bsd-hardware.info/?probe=3112f263f5) | Sep 07, 2023 |
| Intel         | HM570                       | Desktop     | [0e4bfa9794](https://bsd-hardware.info/?probe=0e4bfa9794) | Sep 07, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [4424751223](https://bsd-hardware.info/?probe=4424751223) | Sep 04, 2023 |
| Shuttle       | DS20U                       | Desktop     | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| VIA Techno... | VT8623-8235                 | Desktop     | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | Desktop     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [ebb4e825a3](https://bsd-hardware.info/?probe=ebb4e825a3) | Aug 25, 2023 |
| ASUSTek       | P5M2-R                      | Desktop     | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| Dell          | 068CDY A01                  | Server      | [c3e69db640](https://bsd-hardware.info/?probe=c3e69db640) | Aug 22, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [76945fc8cb](https://bsd-hardware.info/?probe=76945fc8cb) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [341152089f](https://bsd-hardware.info/?probe=341152089f) | Aug 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [5ab27fdf53](https://bsd-hardware.info/?probe=5ab27fdf53) | Aug 21, 2023 |
| Shuttle       | DS20U                       | Desktop     | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [4b101af84b](https://bsd-hardware.info/?probe=4b101af84b) | Aug 19, 2023 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0238ea2cab](https://bsd-hardware.info/?probe=0238ea2cab) | Aug 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [9beb5f6126](https://bsd-hardware.info/?probe=9beb5f6126) | Aug 17, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [7aa7ba9ea9](https://bsd-hardware.info/?probe=7aa7ba9ea9) | Aug 17, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [946e123320](https://bsd-hardware.info/?probe=946e123320) | Aug 13, 2023 |
| Fujitsu Si... | LIFEBOOK P1610              | Notebook    | [bb055a94f0](https://bsd-hardware.info/?probe=bb055a94f0) | Aug 12, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [63c10b6ae5](https://bsd-hardware.info/?probe=63c10b6ae5) | Aug 11, 2023 |
| Dell          | 0CNWVK A00                  | Desktop     | [fdb03dc15f](https://bsd-hardware.info/?probe=fdb03dc15f) | Aug 09, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [4fc1fbaba1](https://bsd-hardware.info/?probe=4fc1fbaba1) | Aug 09, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [ab14c7b62e](https://bsd-hardware.info/?probe=ab14c7b62e) | Aug 09, 2023 |
| MSI           | MS-7623                     | Desktop     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [5cab750b7b](https://bsd-hardware.info/?probe=5cab750b7b) | Aug 03, 2023 |
| ASRock        | B550 PG Velocita            | Desktop     | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [d29e99dd04](https://bsd-hardware.info/?probe=d29e99dd04) | Aug 01, 2023 |
| Lenovo        | ThinkPad T410 2522NP6       | Notebook    | [194b8efa98](https://bsd-hardware.info/?probe=194b8efa98) | Jul 25, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| Intel         | S3210SH FRU Ver             | Server      | [b4112bd797](https://bsd-hardware.info/?probe=b4112bd797) | Jul 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [65599626a9](https://bsd-hardware.info/?probe=65599626a9) | Jul 23, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [f77e9a46c3](https://bsd-hardware.info/?probe=f77e9a46c3) | Jul 22, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [7d7e180d2e](https://bsd-hardware.info/?probe=7d7e180d2e) | Jul 21, 2023 |
| ASUSTek       | 900                         | Notebook    | [2e55f5d4cc](https://bsd-hardware.info/?probe=2e55f5d4cc) | Jul 20, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [c9852c1ee3](https://bsd-hardware.info/?probe=c9852c1ee3) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| IBM           | ThinkPad T43 1871F1G        | Notebook    | [d6fbc6ebfb](https://bsd-hardware.info/?probe=d6fbc6ebfb) | Jul 18, 2023 |
| ASUSTek       | K42Jr                       | Notebook    | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Unknown       | Q-790                       | Desktop     | [49f9861c7f](https://bsd-hardware.info/?probe=49f9861c7f) | Jul 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [12124d8753](https://bsd-hardware.info/?probe=12124d8753) | Jul 15, 2023 |
| Sony          | VPCX115KX                   | Notebook    | [9dab449a23](https://bsd-hardware.info/?probe=9dab449a23) | Jul 15, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| Unknown       | Q-790                       | Desktop     | [cc02bb60de](https://bsd-hardware.info/?probe=cc02bb60de) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | Desktop     | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [a7284068da](https://bsd-hardware.info/?probe=a7284068da) | Jul 12, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [26e209d8e1](https://bsd-hardware.info/?probe=26e209d8e1) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [a9ab5114e1](https://bsd-hardware.info/?probe=a9ab5114e1) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [03e83e60ca](https://bsd-hardware.info/?probe=03e83e60ca) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3096d8532a](https://bsd-hardware.info/?probe=3096d8532a) | Jul 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [c930867e8e](https://bsd-hardware.info/?probe=c930867e8e) | Jul 07, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| HP            | 339A                        | Desktop     | [f80f7cc14c](https://bsd-hardware.info/?probe=f80f7cc14c) | Jul 05, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| Insyde        | Purley                      | Server      | [c6ffd34b07](https://bsd-hardware.info/?probe=c6ffd34b07) | Jun 21, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [a14227cbb3](https://bsd-hardware.info/?probe=a14227cbb3) | Jun 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2008116e96](https://bsd-hardware.info/?probe=2008116e96) | Jun 10, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [27ba75252a](https://bsd-hardware.info/?probe=27ba75252a) | Jun 09, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [15a71633ec](https://bsd-hardware.info/?probe=15a71633ec) | Jun 08, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [c72eaa89d7](https://bsd-hardware.info/?probe=c72eaa89d7) | May 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [086747eef4](https://bsd-hardware.info/?probe=086747eef4) | May 29, 2023 |
| ASRockRack    | E3C242D4U                   | Desktop     | [ae8287e8fd](https://bsd-hardware.info/?probe=ae8287e8fd) | May 29, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [5960982eb3](https://bsd-hardware.info/?probe=5960982eb3) | May 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [47d985333c](https://bsd-hardware.info/?probe=47d985333c) | May 19, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [52a0191a95](https://bsd-hardware.info/?probe=52a0191a95) | May 18, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | Notebook    | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| HP            | 0A60h                       | Desktop     | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| Dell          | 0CNWVK A00                  | Desktop     | [0d1e1a3ca4](https://bsd-hardware.info/?probe=0d1e1a3ca4) | May 16, 2023 |
| Acer          | Revo RN86                   | Desktop     | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [7c3fd3c9ca](https://bsd-hardware.info/?probe=7c3fd3c9ca) | May 08, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [cf2014c973](https://bsd-hardware.info/?probe=cf2014c973) | May 04, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [a80b700f3a](https://bsd-hardware.info/?probe=a80b700f3a) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 82B4                        | Desktop     | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [ea55a6fecf](https://bsd-hardware.info/?probe=ea55a6fecf) | May 02, 2023 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [f94bed3cc6](https://bsd-hardware.info/?probe=f94bed3cc6) | May 02, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9972265a41](https://bsd-hardware.info/?probe=9972265a41) | May 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [290fabd69d](https://bsd-hardware.info/?probe=290fabd69d) | Apr 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| Dell          | 0CNWVK A00                  | Desktop     | [6642a4b35d](https://bsd-hardware.info/?probe=6642a4b35d) | Apr 18, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [b8d2c0d81d](https://bsd-hardware.info/?probe=b8d2c0d81d) | Apr 16, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [4dfa2f0148](https://bsd-hardware.info/?probe=4dfa2f0148) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| HP            | ProLiant DL180 G6           | Server      | [4ccb132836](https://bsd-hardware.info/?probe=4ccb132836) | Apr 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [b189b0988c](https://bsd-hardware.info/?probe=b189b0988c) | Apr 14, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [882a817f46](https://bsd-hardware.info/?probe=882a817f46) | Apr 13, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [3d7bf4205b](https://bsd-hardware.info/?probe=3d7bf4205b) | Apr 13, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [298d106fd1](https://bsd-hardware.info/?probe=298d106fd1) | Apr 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| PC Engines    | APU2                        | Desktop     | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [821368d0f0](https://bsd-hardware.info/?probe=821368d0f0) | Apr 09, 2023 |
| HP            | 2820h                       | Desktop     | [e304f130aa](https://bsd-hardware.info/?probe=e304f130aa) | Apr 09, 2023 |
| HP            | 2820h                       | Desktop     | [ff9500303d](https://bsd-hardware.info/?probe=ff9500303d) | Apr 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| ETegro Tec... | ETRS130G3 31S98MB0020       | Server      | [0b5cb610e0](https://bsd-hardware.info/?probe=0b5cb610e0) | Apr 07, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Intel         | B75                         | Desktop     | [3a7eee851b](https://bsd-hardware.info/?probe=3a7eee851b) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [640aad419a](https://bsd-hardware.info/?probe=640aad419a) | Apr 02, 2023 |
| ASRock        | AB350M Pro4-F               | Desktop     | [424f3a2021](https://bsd-hardware.info/?probe=424f3a2021) | Apr 02, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| Biostar       | TH67B                       | Desktop     | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| DNS           | W9x0LU                      | Notebook    | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| HMT           | W041-TF-A-45                | Notebook    | [666df5a7e0](https://bsd-hardware.info/?probe=666df5a7e0) | Mar 31, 2023 |
| Intel         | Intel                       | Notebook    | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Irbis         | NB78                        | Notebook    | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| ETegro Tec... | ETRS130G3 31S98MB0020       | Server      | [94addf97d5](https://bsd-hardware.info/?probe=94addf97d5) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| ASRock        | X570S PG Riptide            | Desktop     | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | Desktop     | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| MSI           | 870-G45                     | Desktop     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| Samsung       | R468/R418                   | Notebook    | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ee01b690bc](https://bsd-hardware.info/?probe=ee01b690bc) | Mar 25, 2023 |
| MSI           | 870-G45                     | Desktop     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| Stonesoft     | DEV-1301-2-C1-R             | Desktop     | [3bc0fc5d63](https://bsd-hardware.info/?probe=3bc0fc5d63) | Mar 24, 2023 |
| Stonesoft     | DEV-1301-2-C1-R             | Desktop     | [2699b59d1b](https://bsd-hardware.info/?probe=2699b59d1b) | Mar 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [9b7714cbab](https://bsd-hardware.info/?probe=9b7714cbab) | Mar 24, 2023 |
| Dell          | G5 5587                     | Notebook    | [c118e0665f](https://bsd-hardware.info/?probe=c118e0665f) | Mar 24, 2023 |
| Unknown       | T360D11                     | Desktop     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e1b5d66244](https://bsd-hardware.info/?probe=e1b5d66244) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| ASUSTek       | K501UQ                      | Notebook    | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [3f78d8f1ae](https://bsd-hardware.info/?probe=3f78d8f1ae) | Mar 18, 2023 |
| Intel         | B75                         | Desktop     | [11bcf42a35](https://bsd-hardware.info/?probe=11bcf42a35) | Mar 18, 2023 |
| IP3 Techno... | ACN1S                       | Notebook    | [d0761f4192](https://bsd-hardware.info/?probe=d0761f4192) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [0ab42ce2ee](https://bsd-hardware.info/?probe=0ab42ce2ee) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| Samsung       | R468/R418                   | Notebook    | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [f07e092146](https://bsd-hardware.info/?probe=f07e092146) | Mar 11, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [b08fd92e36](https://bsd-hardware.info/?probe=b08fd92e36) | Mar 10, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Elpitech      | ET101-A1                    | Desktop     | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | Desktop     | [a2873d7c87](https://bsd-hardware.info/?probe=a2873d7c87) | Mar 09, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [3c78171104](https://bsd-hardware.info/?probe=3c78171104) | Mar 04, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [5ce8dbf5f3](https://bsd-hardware.info/?probe=5ce8dbf5f3) | Mar 04, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [8404060d9e](https://bsd-hardware.info/?probe=8404060d9e) | Mar 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [13ac9d6b7e](https://bsd-hardware.info/?probe=13ac9d6b7e) | Mar 01, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [2072e8fac6](https://bsd-hardware.info/?probe=2072e8fac6) | Feb 28, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [95c62844de](https://bsd-hardware.info/?probe=95c62844de) | Feb 25, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| MSI           | MS-92E3 0A                  | Desktop     | [683ff1f7d0](https://bsd-hardware.info/?probe=683ff1f7d0) | Feb 22, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [c30dd3fbca](https://bsd-hardware.info/?probe=c30dd3fbca) | Feb 19, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [a27331804b](https://bsd-hardware.info/?probe=a27331804b) | Feb 19, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [eace523f17](https://bsd-hardware.info/?probe=eace523f17) | Feb 18, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9a0c17560f](https://bsd-hardware.info/?probe=9a0c17560f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| ASRock        | A770DE+                     | Desktop     | [cf1c018ede](https://bsd-hardware.info/?probe=cf1c018ede) | Feb 10, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ef722fc37b](https://bsd-hardware.info/?probe=ef722fc37b) | Feb 06, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5921937764](https://bsd-hardware.info/?probe=5921937764) | Feb 06, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [5f6f4145d4](https://bsd-hardware.info/?probe=5f6f4145d4) | Feb 06, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [7fcfb747a7](https://bsd-hardware.info/?probe=7fcfb747a7) | Feb 06, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [222da5a477](https://bsd-hardware.info/?probe=222da5a477) | Feb 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [0232c45faa](https://bsd-hardware.info/?probe=0232c45faa) | Feb 04, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [a58d9501ad](https://bsd-hardware.info/?probe=a58d9501ad) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [c2f84d2103](https://bsd-hardware.info/?probe=c2f84d2103) | Jan 31, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [165d435f30](https://bsd-hardware.info/?probe=165d435f30) | Jan 31, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [eb8a6cb004](https://bsd-hardware.info/?probe=eb8a6cb004) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [d5f06d91db](https://bsd-hardware.info/?probe=d5f06d91db) | Jan 28, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [d32c9457b9](https://bsd-hardware.info/?probe=d32c9457b9) | Jan 28, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [2d48772c23](https://bsd-hardware.info/?probe=2d48772c23) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [448f9265f2](https://bsd-hardware.info/?probe=448f9265f2) | Jan 27, 2023 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [512bf8f61d](https://bsd-hardware.info/?probe=512bf8f61d) | Jan 27, 2023 |
| Citrix        | CB-1100                     | Desktop     | [36199a59e2](https://bsd-hardware.info/?probe=36199a59e2) | Jan 26, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [89ec5e42ef](https://bsd-hardware.info/?probe=89ec5e42ef) | Jan 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a712c2d054](https://bsd-hardware.info/?probe=a712c2d054) | Jan 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7b2fee315d](https://bsd-hardware.info/?probe=7b2fee315d) | Jan 26, 2023 |
| Shuttle       | DS20U                       | Desktop     | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [ca71c8ab2b](https://bsd-hardware.info/?probe=ca71c8ab2b) | Jan 25, 2023 |
| Dell          | 0CNWVK A00                  | Desktop     | [e59d4ab226](https://bsd-hardware.info/?probe=e59d4ab226) | Jan 25, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [5da1e71837](https://bsd-hardware.info/?probe=5da1e71837) | Jan 25, 2023 |
| Timi          | TM1607                      | Notebook    | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [ab59ccf04c](https://bsd-hardware.info/?probe=ab59ccf04c) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | Notebook    | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | Notebook    | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| ASUSTek       | K50IN                       | Notebook    | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| ASRock        | Z390 Pro4                   | Desktop     | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| AZW           | U59                         | Desktop     | [1f97b27470](https://bsd-hardware.info/?probe=1f97b27470) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | Notebook    | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [8956f4503e](https://bsd-hardware.info/?probe=8956f4503e) | Jan 21, 2023 |
| Unknown       | AMD-GX3                     | Desktop     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | Desktop     | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c44d6309f](https://bsd-hardware.info/?probe=8c44d6309f) | Jan 15, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X220 4291LF6       | Notebook    | [25cddb26c3](https://bsd-hardware.info/?probe=25cddb26c3) | Jan 11, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [1008903f65](https://bsd-hardware.info/?probe=1008903f65) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2293d4960d](https://bsd-hardware.info/?probe=2293d4960d) | Jan 11, 2023 |
| Citrix        | CB-1100                     | Desktop     | [860f27ce64](https://bsd-hardware.info/?probe=860f27ce64) | Jan 11, 2023 |
| HP            | ProLiant DL160 Gen9         | Server      | [3a9ec9299c](https://bsd-hardware.info/?probe=3a9ec9299c) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [19f4631b5a](https://bsd-hardware.info/?probe=19f4631b5a) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [ea01217f17](https://bsd-hardware.info/?probe=ea01217f17) | Jan 02, 2023 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [9c526b27dd](https://bsd-hardware.info/?probe=9c526b27dd) | Jan 02, 2023 |
| Shuttle       | DS20U                       | Desktop     | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [ce5e882952](https://bsd-hardware.info/?probe=ce5e882952) | Dec 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Dell          | 0H28RR A04                  | Server      | [8e22402d9e](https://bsd-hardware.info/?probe=8e22402d9e) | Dec 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ced12f0b41](https://bsd-hardware.info/?probe=ced12f0b41) | Dec 19, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [53a90a6c63](https://bsd-hardware.info/?probe=53a90a6c63) | Dec 18, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [b8bfdec836](https://bsd-hardware.info/?probe=b8bfdec836) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [639993a130](https://bsd-hardware.info/?probe=639993a130) | Dec 15, 2022 |
| Dell          | Latitude 5400               | Notebook    | [5b9eb16e5e](https://bsd-hardware.info/?probe=5b9eb16e5e) | Dec 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [55f876d83f](https://bsd-hardware.info/?probe=55f876d83f) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [babe4bb620](https://bsd-hardware.info/?probe=babe4bb620) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | Desktop     | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | X99                         | Desktop     | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Acer          | Revo RN86                   | Desktop     | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Sony          | SVP1321V9RB                 | Notebook    | [932facd689](https://bsd-hardware.info/?probe=932facd689) | Nov 25, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [62ab446b5d](https://bsd-hardware.info/?probe=62ab446b5d) | Nov 09, 2022 |
| Acer          | RS880M05                    | Desktop     | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 339A                        | Desktop     | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [289d2f383b](https://bsd-hardware.info/?probe=289d2f383b) | Nov 02, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Acer          | Revo RN86                   | Desktop     | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | Desktop     | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| Supermicro    | X11SSL-F                    | Desktop     | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| ASUSTek       | N3050I-C                    | Desktop     | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [0da59dff8f](https://bsd-hardware.info/?probe=0da59dff8f) | Oct 12, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | Notebook    | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| Kraftway      | KW10T                       | Notebook    | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| Dell          | System Vostro 3750          | Notebook    | [166fbacd73](https://bsd-hardware.info/?probe=166fbacd73) | Sep 24, 2022 |
| YANYU         | H67SL                       | Desktop     | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | Desktop     | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| YANYU         | H67SL                       | Desktop     | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5abbba28de](https://bsd-hardware.info/?probe=5abbba28de) | Sep 11, 2022 |
| Maxtang       | BYT30                       | Desktop     | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Dell          | Vostro 5415                 | Notebook    | [ef6d4ee660](https://bsd-hardware.info/?probe=ef6d4ee660) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cffed92600](https://bsd-hardware.info/?probe=cffed92600) | Sep 06, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | Desktop     | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Maxtang       | BYT30                       | Desktop     | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Intel         | X79 V2.72A                  | Desktop     | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [fcfa6205d8](https://bsd-hardware.info/?probe=fcfa6205d8) | Aug 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6184507a45](https://bsd-hardware.info/?probe=6184507a45) | Aug 21, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| ASUSTek       | ZenBook 14 UX410UFR         | Notebook    | [2bf0f0ef08](https://bsd-hardware.info/?probe=2bf0f0ef08) | Aug 19, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [0a867d7017](https://bsd-hardware.info/?probe=0a867d7017) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Intel         | S2600WTTR G92187-372        | Server      | [ce1988c8ff](https://bsd-hardware.info/?probe=ce1988c8ff) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| Sony          | VGN-UX1XRN                  | Notebook    | [312df080a7](https://bsd-hardware.info/?probe=312df080a7) | Aug 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2da32e59b0](https://bsd-hardware.info/?probe=2da32e59b0) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9124f0eb45](https://bsd-hardware.info/?probe=9124f0eb45) | Aug 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [b3c0b4a4f4](https://bsd-hardware.info/?probe=b3c0b4a4f4) | Aug 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [612282319b](https://bsd-hardware.info/?probe=612282319b) | Aug 04, 2022 |
| Acer          | Revo 70                     | Desktop     | [0c23ffdc5a](https://bsd-hardware.info/?probe=0c23ffdc5a) | Aug 03, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [d9a4a9745d](https://bsd-hardware.info/?probe=d9a4a9745d) | Jul 28, 2022 |
| HP            | 339A                        | Desktop     | [241e56a349](https://bsd-hardware.info/?probe=241e56a349) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7b130fb168](https://bsd-hardware.info/?probe=7b130fb168) | Jul 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Acer          | RS880M05                    | Desktop     | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Supermicro    | H8DGU                       | Server      | [172bfe70b5](https://bsd-hardware.info/?probe=172bfe70b5) | Jul 14, 2022 |
| Acer          | Revo 70                     | Desktop     | [aad484a882](https://bsd-hardware.info/?probe=aad484a882) | Jul 13, 2022 |
| Acer          | Revo 70                     | Desktop     | [c8b51a94bd](https://bsd-hardware.info/?probe=c8b51a94bd) | Jul 13, 2022 |
| Kraftway      | KWH77                       | Desktop     | [c34f44a495](https://bsd-hardware.info/?probe=c34f44a495) | Jul 12, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [3644f56368](https://bsd-hardware.info/?probe=3644f56368) | Jul 10, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [2d521e085b](https://bsd-hardware.info/?probe=2d521e085b) | Jul 08, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [12279c8a4b](https://bsd-hardware.info/?probe=12279c8a4b) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [19a4b27ae7](https://bsd-hardware.info/?probe=19a4b27ae7) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | Desktop     | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| HP            | ProLiant DL160 G6           | Server      | [a4c075339a](https://bsd-hardware.info/?probe=a4c075339a) | Jun 29, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| ASRock        | P67 Professional            | Desktop     | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [d3659c85e9](https://bsd-hardware.info/?probe=d3659c85e9) | Jun 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [a4cd230718](https://bsd-hardware.info/?probe=a4cd230718) | Jun 27, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [e057898546](https://bsd-hardware.info/?probe=e057898546) | Jun 18, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [380218b2c1](https://bsd-hardware.info/?probe=380218b2c1) | Jun 12, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [17078490f7](https://bsd-hardware.info/?probe=17078490f7) | Jun 11, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [438d4f9b2f](https://bsd-hardware.info/?probe=438d4f9b2f) | Jun 09, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Notebook    | [73ab89b8f0](https://bsd-hardware.info/?probe=73ab89b8f0) | Jun 05, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Notebook    | [637f87f44e](https://bsd-hardware.info/?probe=637f87f44e) | Jun 05, 2022 |
| Lenovo        | Aptio CRB SDK0E50515 STD    | Mini pc     | [260ae5b2fe](https://bsd-hardware.info/?probe=260ae5b2fe) | Jun 04, 2022 |
| Supermicro    | X9DRW                       | Server      | [bdfce3deff](https://bsd-hardware.info/?probe=bdfce3deff) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| khadas        | edge-v                      | Desktop     | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | Desktop     | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| HP            | ProLiant DL160 G5           | Server      | [e07440e3e0](https://bsd-hardware.info/?probe=e07440e3e0) | May 22, 2022 |
| Supermicro    | X9SRW-F                     | Server      | [89da730497](https://bsd-hardware.info/?probe=89da730497) | May 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [cf5f498572](https://bsd-hardware.info/?probe=cf5f498572) | May 21, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c6944afe69](https://bsd-hardware.info/?probe=c6944afe69) | May 19, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [d6fa145c7c](https://bsd-hardware.info/?probe=d6fa145c7c) | May 16, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [89db84f7ec](https://bsd-hardware.info/?probe=89db84f7ec) | May 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| Acer          | Aspire ES1-132              | Notebook    | [18426698ad](https://bsd-hardware.info/?probe=18426698ad) | May 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [5701dac149](https://bsd-hardware.info/?probe=5701dac149) | Apr 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [d036c00d6c](https://bsd-hardware.info/?probe=d036c00d6c) | Apr 28, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [c0739686fb](https://bsd-hardware.info/?probe=c0739686fb) | Apr 28, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [dcd02e012d](https://bsd-hardware.info/?probe=dcd02e012d) | Apr 28, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | Desktop     | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [09a475e0bc](https://bsd-hardware.info/?probe=09a475e0bc) | Apr 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [3834dccb1f](https://bsd-hardware.info/?probe=3834dccb1f) | Apr 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| PC Engines    | APU2                        | Desktop     | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| Intel         | DH67BL                      | Desktop     | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | Desktop     | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | Desktop     | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| DEXP          | NAVIS P100                  | Notebook    | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | Desktop     | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | Notebook    | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Samsung       | DP700A3D-X01RU SEC_SW_RE... | All in one  | [22febd212f](https://bsd-hardware.info/?probe=22febd212f) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8e64404e52](https://bsd-hardware.info/?probe=8e64404e52) | Apr 19, 2022 |
| Shuttle       | DS20U                       | Desktop     | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| Gigabyte      | E3000N                      | Desktop     | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| DNS           | W9x0LU                      | Notebook    | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [e17bbe2186](https://bsd-hardware.info/?probe=e17bbe2186) | Apr 05, 2022 |
| Timi          | TM1612                      | Notebook    | [0389c8d487](https://bsd-hardware.info/?probe=0389c8d487) | Apr 05, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [1dd1823662](https://bsd-hardware.info/?probe=1dd1823662) | Apr 04, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| Supermicro    | X10DRi-T                    | Desktop     | [eae4612261](https://bsd-hardware.info/?probe=eae4612261) | Mar 31, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e750905413](https://bsd-hardware.info/?probe=e750905413) | Mar 29, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [47ef9ef91a](https://bsd-hardware.info/?probe=47ef9ef91a) | Mar 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | Desktop     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [9b3dac520a](https://bsd-hardware.info/?probe=9b3dac520a) | Mar 24, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Supermicro    | A1SAi 123456789             | Mini pc     | [0f1362e9a9](https://bsd-hardware.info/?probe=0f1362e9a9) | Mar 16, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [1617262a28](https://bsd-hardware.info/?probe=1617262a28) | Mar 16, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [7fb743c654](https://bsd-hardware.info/?probe=7fb743c654) | Mar 15, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [6e7384f4cc](https://bsd-hardware.info/?probe=6e7384f4cc) | Mar 15, 2022 |
| Huanan        | X99-F8D V2.4                | Desktop     | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | Desktop     | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |
| Gigabyte      | X58A-UD5                    | Desktop     | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [da786acd84](https://bsd-hardware.info/?probe=da786acd84) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [5b6dd82da8](https://bsd-hardware.info/?probe=5b6dd82da8) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| Lenovo        | E31-80 80MX                 | Notebook    | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [06887b10fd](https://bsd-hardware.info/?probe=06887b10fd) | Feb 15, 2022 |
| Firefly       | ROC-RK3566-PC               | Soc         | [b5c6aa26de](https://bsd-hardware.info/?probe=b5c6aa26de) | Feb 13, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [2dd03795ba](https://bsd-hardware.info/?probe=2dd03795ba) | Feb 11, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASRock        | D1800M                      | Desktop     | [0902154c8e](https://bsd-hardware.info/?probe=0902154c8e) | Feb 08, 2022 |
| Dell          | 0654JC A01                  | Desktop     | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [494195b923](https://bsd-hardware.info/?probe=494195b923) | Feb 08, 2022 |
| ASUSTek       | P5G41T-M                    | Desktop     | [a7d5b65ba1](https://bsd-hardware.info/?probe=a7d5b65ba1) | Feb 07, 2022 |
| MSI           | MS-7C96                     | Desktop     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| ASUSTek       | P4P800-VM                   | Desktop     | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| HP            | Laptop 15-rb0xx             | Notebook    | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Lenovo        | 30C9 NOK                    | Desktop     | [7169d2989c](https://bsd-hardware.info/?probe=7169d2989c) | Jan 29, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| Firefly       | ROC-RK3566-PC               | Soc         | [aac0cd5332](https://bsd-hardware.info/?probe=aac0cd5332) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [48b172bfe8](https://bsd-hardware.info/?probe=48b172bfe8) | Jan 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| HP            | ProLiant DL180 G6           | Server      | [28f84e935f](https://bsd-hardware.info/?probe=28f84e935f) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| Intel         | S3420GP E77063-304          | Server      | [acaa85b561](https://bsd-hardware.info/?probe=acaa85b561) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| Wistron       | ProLiant DL120 G6           | Server      | [379fcf9804](https://bsd-hardware.info/?probe=379fcf9804) | Jan 24, 2022 |
| ASUSTek       | P5M2                        | Desktop     | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [55d70a3070](https://bsd-hardware.info/?probe=55d70a3070) | Jan 22, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [bf033b6b9f](https://bsd-hardware.info/?probe=bf033b6b9f) | Jan 22, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Intel CNCT... | Unknown                     | Desktop     | [0debf023f1](https://bsd-hardware.info/?probe=0debf023f1) | Jan 18, 2022 |
| Gigabyte      | B365 HD3                    | Desktop     | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [6836fc60f6](https://bsd-hardware.info/?probe=6836fc60f6) | Jan 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [87c8ee9b4c](https://bsd-hardware.info/?probe=87c8ee9b4c) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| friendlyel... | nanopi-m4                   | Desktop     | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4bb84a33fa](https://bsd-hardware.info/?probe=4bb84a33fa) | Dec 26, 2021 |
| khadas        | edge-v                      | Desktop     | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| Acer          | Revo RN86                   | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| HP            | 1850                        | Desktop     | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | Desktop     | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | Desktop     | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | Desktop     | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| MSI           | MS-9852 10                  | Desktop     | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | P5G41T-M                    | Desktop     | [44bba395e8](https://bsd-hardware.info/?probe=44bba395e8) | Dec 13, 2021 |
| ASUSTek       | P5G41T-M                    | Desktop     | [1fb865c4ae](https://bsd-hardware.info/?probe=1fb865c4ae) | Dec 09, 2021 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [9fca53da56](https://bsd-hardware.info/?probe=9fca53da56) | Dec 08, 2021 |
| ASUSTek       | P5B                         | Desktop     | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | Desktop     | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| Unknown       | Q2XX V1.1                   | Desktop     | [66d6a26e35](https://bsd-hardware.info/?probe=66d6a26e35) | Dec 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ade9f77281](https://bsd-hardware.info/?probe=ade9f77281) | Nov 25, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| Unknown       | Intel X79                   | Desktop     | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [2478821f6e](https://bsd-hardware.info/?probe=2478821f6e) | Oct 28, 2021 |
| HP            | 0A60h                       | Desktop     | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | Desktop     | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [b0ef9f0259](https://bsd-hardware.info/?probe=b0ef9f0259) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | Desktop     | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Acer          | RS880M05                    | Desktop     | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Radxa         | rock-pi-4                   | Desktop     | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | Desktop     | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Lenovo        | S20-30 Touch 20434          | Notebook    | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | J1900                       | Desktop     | [9d6c7612d3](https://bsd-hardware.info/?probe=9d6c7612d3) | Oct 05, 2021 |
| ASUSTek       | UX21A                       | Notebook    | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| HP            | 81BA                        | All in one  | [c2204a3dd2](https://bsd-hardware.info/?probe=c2204a3dd2) | Oct 04, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| IBM           | ThinkPad H 1846AQG          | Notebook    | [5e5c7247ca](https://bsd-hardware.info/?probe=5e5c7247ca) | Oct 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | Desktop     | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [ae1765efd5](https://bsd-hardware.info/?probe=ae1765efd5) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [8b51d2aabb](https://bsd-hardware.info/?probe=8b51d2aabb) | Sep 09, 2021 |
| ASUSTek       | VX7SX                       | Notebook    | [6ca36a455d](https://bsd-hardware.info/?probe=6ca36a455d) | Sep 09, 2021 |
| Kraftway      | KW10T                       | Notebook    | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [01ac3a91d0](https://bsd-hardware.info/?probe=01ac3a91d0) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [28bf815655](https://bsd-hardware.info/?probe=28bf815655) | Aug 30, 2021 |
| Intel         | DG33BU AAD79951-408         | Desktop     | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | Desktop     | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| Unknown       | Q2XX V1.1                   | Desktop     | [5ca9aa0bf2](https://bsd-hardware.info/?probe=5ca9aa0bf2) | Aug 19, 2021 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Supermicro    | X10DRH-CT                   | Desktop     | [6ccb3c09d6](https://bsd-hardware.info/?probe=6ccb3c09d6) | Aug 12, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| MSI           | H81M-P33                    | Desktop     | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Supermicro    | X8DTU                       | Server      | [2862bf1465](https://bsd-hardware.info/?probe=2862bf1465) | Jul 29, 2021 |
| Lenovo        | ThinkPad E590 20NB0012RT    | Notebook    | [98072b8db6](https://bsd-hardware.info/?probe=98072b8db6) | Jul 26, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3fb09d0402](https://bsd-hardware.info/?probe=3fb09d0402) | Jul 24, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [bef816fe74](https://bsd-hardware.info/?probe=bef816fe74) | Jul 24, 2021 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [f613cb0452](https://bsd-hardware.info/?probe=f613cb0452) | Jul 23, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [7542ae751d](https://bsd-hardware.info/?probe=7542ae751d) | Jul 20, 2021 |
| HP            | ProLiant DL360e Gen8        | Desktop     | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | Desktop     | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | Desktop     | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| MSI           | H81M-E33                    | Desktop     | [c9fda90944](https://bsd-hardware.info/?probe=c9fda90944) | Jul 08, 2021 |
| Pegatron      | IPPCR-SS                    | Desktop     | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| eMachines     | eM350                       | Notebook    | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Supermicro    | X10DRH-CT                   | Desktop     | [583e9e5a66](https://bsd-hardware.info/?probe=583e9e5a66) | Jun 26, 2021 |
| ECS           | A740GM-M                    | Desktop     | [a9d9106f11](https://bsd-hardware.info/?probe=a9d9106f11) | Jun 24, 2021 |
| eMachines     | eM350                       | Notebook    | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines     | eM350                       | Notebook    | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [449fc82ff8](https://bsd-hardware.info/?probe=449fc82ff8) | Jun 21, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | Desktop     | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [4ac6c9b3eb](https://bsd-hardware.info/?probe=4ac6c9b3eb) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [62c87cf194](https://bsd-hardware.info/?probe=62c87cf194) | Jun 07, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8fc867cfae](https://bsd-hardware.info/?probe=8fc867cfae) | Jun 06, 2021 |
| Lenovo        | ThinkPad T430 23511A6       | Notebook    | [89fb2aa493](https://bsd-hardware.info/?probe=89fb2aa493) | Jun 05, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [bf605b741b](https://bsd-hardware.info/?probe=bf605b741b) | Jun 04, 2021 |
| Intel         | S2600WTTR G92187-372        | Server      | [289d61b1b2](https://bsd-hardware.info/?probe=289d61b1b2) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [84e93d02e1](https://bsd-hardware.info/?probe=84e93d02e1) | Jun 03, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [1bb850edca](https://bsd-hardware.info/?probe=1bb850edca) | Jun 03, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [b486e670fe](https://bsd-hardware.info/?probe=b486e670fe) | Jun 02, 2021 |
| Biostar       | TH67B                       | Desktop     | [1f2321ec41](https://bsd-hardware.info/?probe=1f2321ec41) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [8c06f6b716](https://bsd-hardware.info/?probe=8c06f6b716) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [629d15378d](https://bsd-hardware.info/?probe=629d15378d) | May 10, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [ae105fb8bc](https://bsd-hardware.info/?probe=ae105fb8bc) | May 09, 2021 |
| ASUSTek       | Maximus II Formula          | Desktop     | [493bb4da66](https://bsd-hardware.info/?probe=493bb4da66) | May 07, 2021 |
| Gigabyte      | X58A-UD5                    | Desktop     | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [87c4175f48](https://bsd-hardware.info/?probe=87c4175f48) | May 03, 2021 |
| ASUSTek       | P10S-I Series               | Desktop     | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Unknown       | Q2XX V1.1                   | Desktop     | [5c7ea7fb7d](https://bsd-hardware.info/?probe=5c7ea7fb7d) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| HP            | 8430 1000                   | All in one  | [0d21e083f4](https://bsd-hardware.info/?probe=0d21e083f4) | Apr 20, 2021 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [a379c24586](https://bsd-hardware.info/?probe=a379c24586) | Apr 19, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [7c77a33f75](https://bsd-hardware.info/?probe=7c77a33f75) | Apr 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [513027c242](https://bsd-hardware.info/?probe=513027c242) | Apr 13, 2021 |
| Acer          | Extensa 2540                | Notebook    | [e7d6ece4ba](https://bsd-hardware.info/?probe=e7d6ece4ba) | Apr 11, 2021 |
| ASUSTek       | 1225B                       | Notebook    | [3eff93bfb5](https://bsd-hardware.info/?probe=3eff93bfb5) | Mar 31, 2021 |
| Gigabyte      | GA-IMB370TN                 | Desktop     | [8023a25ccb](https://bsd-hardware.info/?probe=8023a25ccb) | Mar 29, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [a38a620353](https://bsd-hardware.info/?probe=a38a620353) | Mar 29, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [342e914968](https://bsd-hardware.info/?probe=342e914968) | Mar 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [dd877e6c6c](https://bsd-hardware.info/?probe=dd877e6c6c) | Mar 27, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| ASRock        | H71M-DGS                    | Desktop     | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [46d36c6b23](https://bsd-hardware.info/?probe=46d36c6b23) | Mar 21, 2021 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [eff02dafe1](https://bsd-hardware.info/?probe=eff02dafe1) | Mar 18, 2021 |
| Intel         | PB_1900A V2.1               | Desktop     | [a2378c3bee](https://bsd-hardware.info/?probe=a2378c3bee) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480s 20L7001HR... | Notebook    | [ebd44c21d9](https://bsd-hardware.info/?probe=ebd44c21d9) | Mar 17, 2021 |
| Samsung       | N150P                       | Notebook    | [68483fab9d](https://bsd-hardware.info/?probe=68483fab9d) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [52584aaa97](https://bsd-hardware.info/?probe=52584aaa97) | Mar 14, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [fb136a79e7](https://bsd-hardware.info/?probe=fb136a79e7) | Mar 13, 2021 |
| ASUSTek       | AT5NM10T-I                  | Desktop     | [7c26a8b81e](https://bsd-hardware.info/?probe=7c26a8b81e) | Mar 12, 2021 |
| Dell          | Latitude 3410               | Notebook    | [80d7bf959a](https://bsd-hardware.info/?probe=80d7bf959a) | Mar 10, 2021 |
| HP            | 255 G3                      | Notebook    | [861bdc647d](https://bsd-hardware.info/?probe=861bdc647d) | Mar 09, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [1fcde7c0e1](https://bsd-hardware.info/?probe=1fcde7c0e1) | Mar 09, 2021 |
| ASRock        | Q1900M                      | Desktop     | [f366c06928](https://bsd-hardware.info/?probe=f366c06928) | Mar 09, 2021 |
| HP            | 255 G3                      | Notebook    | [bd82ed65e9](https://bsd-hardware.info/?probe=bd82ed65e9) | Mar 07, 2021 |
| Gigabyte      | EG43M-S2H                   | Desktop     | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cf965a3a5b](https://bsd-hardware.info/?probe=cf965a3a5b) | Mar 06, 2021 |
| HP            | ProLiant DL180 G6           | Server      | [4907dd5d8f](https://bsd-hardware.info/?probe=4907dd5d8f) | Mar 03, 2021 |
| Supermicro    | X8DTU                       | Server      | [6dd2d44aa1](https://bsd-hardware.info/?probe=6dd2d44aa1) | Mar 03, 2021 |
| Gigabyte      | 8IG1000MK                   | Desktop     | [49ee1efce0](https://bsd-hardware.info/?probe=49ee1efce0) | Mar 01, 2021 |
| Intel         | S3420GP E77063-304          | Server      | [044617a994](https://bsd-hardware.info/?probe=044617a994) | Mar 01, 2021 |
| Kontron       | KT965/ATXP 61420000         | Desktop     | [8755a0003d](https://bsd-hardware.info/?probe=8755a0003d) | Mar 01, 2021 |
| HP            | Compaq 6820s                | Notebook    | [f63d65b78c](https://bsd-hardware.info/?probe=f63d65b78c) | Feb 26, 2021 |
| Lenovo        | Board                       | Desktop     | [395ef09e6d](https://bsd-hardware.info/?probe=395ef09e6d) | Feb 25, 2021 |
| Lenovo        | Board                       | Desktop     | [96fbaf0644](https://bsd-hardware.info/?probe=96fbaf0644) | Feb 25, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| Acer          | TPDS05 R3700                | Desktop     | [651f8a2bb4](https://bsd-hardware.info/?probe=651f8a2bb4) | Feb 23, 2021 |
| PC Engines    | APU2                        | Desktop     | [02a107a767](https://bsd-hardware.info/?probe=02a107a767) | Feb 23, 2021 |
| ASRock        | J4205-ITX                   | Desktop     | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| Dell          | Studio 1537                 | Notebook    | [a4c1d361eb](https://bsd-hardware.info/?probe=a4c1d361eb) | Feb 23, 2021 |
| Intel         | NUC5PPYB H76558-107         | Mini pc     | [2c106472cb](https://bsd-hardware.info/?probe=2c106472cb) | Feb 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [41ea02c8bc](https://bsd-hardware.info/?probe=41ea02c8bc) | Feb 21, 2021 |
| Sophos        | SG                          | Firewall    | [b1c99da59c](https://bsd-hardware.info/?probe=b1c99da59c) | Feb 20, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [8e52de9bec](https://bsd-hardware.info/?probe=8e52de9bec) | Feb 19, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | Desktop     | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [ed75b3d15b](https://bsd-hardware.info/?probe=ed75b3d15b) | Feb 18, 2021 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [8f8f08f763](https://bsd-hardware.info/?probe=8f8f08f763) | Feb 17, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [3df4abb2e9](https://bsd-hardware.info/?probe=3df4abb2e9) | Feb 16, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [ae42a14150](https://bsd-hardware.info/?probe=ae42a14150) | Feb 16, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [24551b886c](https://bsd-hardware.info/?probe=24551b886c) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ada1119026](https://bsd-hardware.info/?probe=ada1119026) | Feb 14, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [0e5e228d18](https://bsd-hardware.info/?probe=0e5e228d18) | Feb 13, 2021 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [2d93a6bebc](https://bsd-hardware.info/?probe=2d93a6bebc) | Feb 13, 2021 |
| Sony          | VPCX115KX                   | Notebook    | [fef3d94e6c](https://bsd-hardware.info/?probe=fef3d94e6c) | Feb 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | P5GDC Pro                   | Desktop     | [ca50169bf4](https://bsd-hardware.info/?probe=ca50169bf4) | Feb 11, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [65e5edcfd7](https://bsd-hardware.info/?probe=65e5edcfd7) | Feb 11, 2021 |
| ASRock        | J3455M                      | Desktop     | [0493901aff](https://bsd-hardware.info/?probe=0493901aff) | Feb 10, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [3b4a7e7fc2](https://bsd-hardware.info/?probe=3b4a7e7fc2) | Feb 10, 2021 |
| ASRock        | H61M-S                      | Desktop     | [f7b01b5274](https://bsd-hardware.info/?probe=f7b01b5274) | Feb 08, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4a36ea2ecd](https://bsd-hardware.info/?probe=4a36ea2ecd) | Feb 07, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [b35f7a5610](https://bsd-hardware.info/?probe=b35f7a5610) | Feb 05, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | Notebook    | [503378cac9](https://bsd-hardware.info/?probe=503378cac9) | Jan 31, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [e2fd3451b6](https://bsd-hardware.info/?probe=e2fd3451b6) | Jan 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| MSI           | MS-7235                     | Desktop     | [6a0d60ad2c](https://bsd-hardware.info/?probe=6a0d60ad2c) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ad33eaab8a](https://bsd-hardware.info/?probe=ad33eaab8a) | Jan 19, 2021 |
| Sony          | VPCM13M1R                   | Notebook    | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [112792b300](https://bsd-hardware.info/?probe=112792b300) | Jan 02, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [8b571cc947](https://bsd-hardware.info/?probe=8b571cc947) | Jan 02, 2021 |
| Centerm       | C30                         | Desktop     | [862ffd88e6](https://bsd-hardware.info/?probe=862ffd88e6) | Dec 16, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [0309e4ac24](https://bsd-hardware.info/?probe=0309e4ac24) | Dec 16, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a1fe36fd99](https://bsd-hardware.info/?probe=a1fe36fd99) | Dec 16, 2020 |
| HP            | ProLiant DL360e Gen8        | Server      | [e22af8ee52](https://bsd-hardware.info/?probe=e22af8ee52) | Dec 16, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c8c11a071d](https://bsd-hardware.info/?probe=c8c11a071d) | Dec 14, 2020 |
| Acer          | Aspire V5-122               | Notebook    | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Intel         | S5000PSL                    | Server      | [0546131058](https://bsd-hardware.info/?probe=0546131058) | Dec 14, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [fb6286f788](https://bsd-hardware.info/?probe=fb6286f788) | Dec 13, 2020 |
| Panasonic     | CF-19AHNC8FN                | Notebook    | [04a42812bb](https://bsd-hardware.info/?probe=04a42812bb) | Dec 11, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3a78e7dc1a](https://bsd-hardware.info/?probe=3a78e7dc1a) | Dec 11, 2020 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [b4cb55c681](https://bsd-hardware.info/?probe=b4cb55c681) | Dec 05, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [c5017eff06](https://bsd-hardware.info/?probe=c5017eff06) | Dec 04, 2020 |
| PC Engines    | APU2                        | Desktop     | [90d68eee14](https://bsd-hardware.info/?probe=90d68eee14) | Dec 04, 2020 |
| PC Engines    | APU2                        | Desktop     | [fab3041b1e](https://bsd-hardware.info/?probe=fab3041b1e) | Dec 04, 2020 |
| Gigabyte      | Unknown                     | Desktop     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| Sony          | SVP1321V9RB                 | Notebook    | [9cddee6a0a](https://bsd-hardware.info/?probe=9cddee6a0a) | Dec 01, 2020 |
| ASRock        | N68-GE                      | Desktop     | [ce9159c2fa](https://bsd-hardware.info/?probe=ce9159c2fa) | Nov 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| ASRock        | N68-GE                      | Desktop     | [028eabaec2](https://bsd-hardware.info/?probe=028eabaec2) | Nov 28, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [c3230a9065](https://bsd-hardware.info/?probe=c3230a9065) | Nov 23, 2020 |
| ASUSTek       | P5GDC Pro                   | Desktop     | [8776b186c1](https://bsd-hardware.info/?probe=8776b186c1) | Nov 14, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [8a79e3f5e4](https://bsd-hardware.info/?probe=8a79e3f5e4) | Nov 11, 2020 |
| Sony          | VGN-S150(UC)                | Notebook    | [f2f3923ea6](https://bsd-hardware.info/?probe=f2f3923ea6) | Nov 10, 2020 |
| Pegatron      | 1.03                        | Desktop     | [e660e12e3c](https://bsd-hardware.info/?probe=e660e12e3c) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [c766aab801](https://bsd-hardware.info/?probe=c766aab801) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | Desktop     | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| Toshiba       | Satellite M100              | Notebook    | [e6e0a1294c](https://bsd-hardware.info/?probe=e6e0a1294c) | Nov 01, 2020 |
| ASUSTek       | B75M-A                      | Desktop     | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [52fe99a6d6](https://bsd-hardware.info/?probe=52fe99a6d6) | Oct 29, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| Supermicro    | H8DGU                       | Server      | [58a580dd6b](https://bsd-hardware.info/?probe=58a580dd6b) | Oct 24, 2020 |
| Supermicro    | X10DRW-i                    | Server      | [3c7d64a2cb](https://bsd-hardware.info/?probe=3c7d64a2cb) | Oct 24, 2020 |
| Sony          | SVP1321V9RB                 | Notebook    | [3f414895be](https://bsd-hardware.info/?probe=3f414895be) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| ASUSTek       | B150M-K                     | Desktop     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Dell          | Latitude C400               | Notebook    | [1dcc5e7972](https://bsd-hardware.info/?probe=1dcc5e7972) | Oct 21, 2020 |
| Dell          | Latitude C400               | Notebook    | [8330d23bd7](https://bsd-hardware.info/?probe=8330d23bd7) | Oct 21, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| Google        | Chell                       | Notebook    | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [b2e65dd4c5](https://bsd-hardware.info/?probe=b2e65dd4c5) | Oct 20, 2020 |
| Intel         | S3000AH                     | Desktop     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| Lenovo        | ThinkPad X240 20AL00DKRT    | Notebook    | [623801416c](https://bsd-hardware.info/?probe=623801416c) | Oct 20, 2020 |
| ASUSTek       | P10S-I Series               | Desktop     | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| Lenovo        | ThinkPad T495s 20QKS1812... | Notebook    | [a3bc7a0c88](https://bsd-hardware.info/?probe=a3bc7a0c88) | Oct 19, 2020 |
| IBM           | Board                       | Desktop     | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | Desktop     | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Unknown       | Unknown                     | Desktop     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4f54c8f399](https://bsd-hardware.info/?probe=4f54c8f399) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [0e0656d228](https://bsd-hardware.info/?probe=0e0656d228) | Oct 19, 2020 |
| HP            | OmniBook PC                 | Notebook    | [60e72f1c10](https://bsd-hardware.info/?probe=60e72f1c10) | Oct 19, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1ac21e1660](https://bsd-hardware.info/?probe=1ac21e1660) | Oct 08, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1123cb92ba](https://bsd-hardware.info/?probe=1123cb92ba) | Oct 04, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [4117a39b03](https://bsd-hardware.info/?probe=4117a39b03) | Sep 23, 2020 |
| Acer          | Revo RN86                   | Desktop     | [d1b1775be3](https://bsd-hardware.info/?probe=d1b1775be3) | Sep 23, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [e8ab84404c](https://bsd-hardware.info/?probe=e8ab84404c) | Sep 22, 2020 |
| Acer          | Revo RN86                   | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [e9dd488fe0](https://bsd-hardware.info/?probe=e9dd488fe0) | Sep 13, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [1f28f1c311](https://bsd-hardware.info/?probe=1f28f1c311) | Aug 30, 2020 |
| Lenovo        | ThinkPad X230 2325Y36       | Notebook    | [11a0bbb73f](https://bsd-hardware.info/?probe=11a0bbb73f) | Aug 30, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0e99e72ec9](https://bsd-hardware.info/?probe=0e99e72ec9) | Aug 26, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b9477154b9](https://bsd-hardware.info/?probe=b9477154b9) | Aug 26, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [598e77539b](https://bsd-hardware.info/?probe=598e77539b) | Aug 21, 2020 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [e210609359](https://bsd-hardware.info/?probe=e210609359) | Aug 21, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [19d1c3d086](https://bsd-hardware.info/?probe=19d1c3d086) | Aug 20, 2020 |
| Gigabyte      | X58A-UD5                    | Desktop     | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [bc97c1c0fa](https://bsd-hardware.info/?probe=bc97c1c0fa) | Aug 13, 2020 |
| Dell          | Inspiron 1501               | Notebook    | [9ee3e7cbc2](https://bsd-hardware.info/?probe=9ee3e7cbc2) | Aug 11, 2020 |
| Dell          | Inspiron 1501               | Notebook    | [807aae7095](https://bsd-hardware.info/?probe=807aae7095) | Aug 11, 2020 |
| ASUSTek       | P8P67                       | Desktop     | [c61cac017e](https://bsd-hardware.info/?probe=c61cac017e) | Aug 06, 2020 |
| ASUSTek       | K8N-VM                      | Desktop     | [0ddf168986](https://bsd-hardware.info/?probe=0ddf168986) | Aug 06, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [d08ea3542e](https://bsd-hardware.info/?probe=d08ea3542e) | Aug 05, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4f4cb01708](https://bsd-hardware.info/?probe=4f4cb01708) | Aug 05, 2020 |
| Dell          | Latitude 7490               | Notebook    | [b1d5e8c619](https://bsd-hardware.info/?probe=b1d5e8c619) | Aug 05, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [0227811abb](https://bsd-hardware.info/?probe=0227811abb) | Aug 05, 2020 |
| MSI           | H61M-P20                    | Desktop     | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| ASRock        | E350M1                      | Desktop     | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [eb3f0a19ae](https://bsd-hardware.info/?probe=eb3f0a19ae) | Jul 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [d06bcfe514](https://bsd-hardware.info/?probe=d06bcfe514) | Jul 19, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Supermicro    | X10SRi-FB                   | Server      | [81db3f5be2](https://bsd-hardware.info/?probe=81db3f5be2) | Jul 15, 2020 |
| Supermicro    | NSM5200A                    | Desktop     | [49a39eb60f](https://bsd-hardware.info/?probe=49a39eb60f) | Jul 15, 2020 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [667d98ccb2](https://bsd-hardware.info/?probe=667d98ccb2) | Jul 15, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [836bf04a97](https://bsd-hardware.info/?probe=836bf04a97) | Jul 15, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [daaa05bbf4](https://bsd-hardware.info/?probe=daaa05bbf4) | Jul 15, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [97c6656398](https://bsd-hardware.info/?probe=97c6656398) | Jul 12, 2020 |
| HP            | ProBook 430 G2              | Notebook    | [3a33aa0d8c](https://bsd-hardware.info/?probe=3a33aa0d8c) | Jun 30, 2020 |
| HP            | ProBook 430 G2              | Notebook    | [365ebdaf9c](https://bsd-hardware.info/?probe=365ebdaf9c) | Jun 30, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [08dd1b91a8](https://bsd-hardware.info/?probe=08dd1b91a8) | Jun 30, 2020 |
| Foxconn       | nT-330i                     | Desktop     | [79ab8efb37](https://bsd-hardware.info/?probe=79ab8efb37) | Jun 29, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [a24cfb5df9](https://bsd-hardware.info/?probe=a24cfb5df9) | Jun 16, 2020 |
| ASRock        | J3455-ITX                   | Desktop     | [1c8e18b787](https://bsd-hardware.info/?probe=1c8e18b787) | Jun 15, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [220313b249](https://bsd-hardware.info/?probe=220313b249) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [c7f3bf660a](https://bsd-hardware.info/?probe=c7f3bf660a) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [b84d1b49d8](https://bsd-hardware.info/?probe=b84d1b49d8) | Jun 02, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [0cc3c53651](https://bsd-hardware.info/?probe=0cc3c53651) | Jun 02, 2020 |
| Supermicro    | X11SAE-M                    | Server      | [f6cf8f7870](https://bsd-hardware.info/?probe=f6cf8f7870) | Jun 02, 2020 |
| Dell          | Latitude E5400              | Notebook    | [54854343e4](https://bsd-hardware.info/?probe=54854343e4) | Jun 01, 2020 |
| Unknown       | Unknown                     | Desktop     | [ee9f9df2c1](https://bsd-hardware.info/?probe=ee9f9df2c1) | May 31, 2020 |
| Unknown       | Unknown                     | Desktop     | [6034ab8e6e](https://bsd-hardware.info/?probe=6034ab8e6e) | May 31, 2020 |
| ASRock        | Q1900M                      | Desktop     | [8787d15bc5](https://bsd-hardware.info/?probe=8787d15bc5) | May 31, 2020 |
| ASRock        | Q1900M                      | Desktop     | [79fe3017ef](https://bsd-hardware.info/?probe=79fe3017ef) | May 31, 2020 |
| Dell          | Latitude E6420              | Notebook    | [324265fe3f](https://bsd-hardware.info/?probe=324265fe3f) | May 31, 2020 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Server      | [1f4d1e4607](https://bsd-hardware.info/?probe=1f4d1e4607) | May 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [68840c222b](https://bsd-hardware.info/?probe=68840c222b) | May 28, 2020 |
| Lenovo        | ThinkPad X240 20AMA52RUK    | Notebook    | [c65cdb97de](https://bsd-hardware.info/?probe=c65cdb97de) | May 28, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | Desktop     | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | Desktop     | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Acer          | Aspire 4820T                | Notebook    | [239eea83c6](https://bsd-hardware.info/?probe=239eea83c6) | May 26, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [b4c4c676c4](https://bsd-hardware.info/?probe=b4c4c676c4) | May 26, 2020 |
| Unknown       | YL-J3060L2                  | Desktop     | [55be2fab24](https://bsd-hardware.info/?probe=55be2fab24) | May 26, 2020 |
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [66bce86f33](https://bsd-hardware.info/?probe=66bce86f33) | May 26, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [dc7bb56859](https://bsd-hardware.info/?probe=dc7bb56859) | May 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [9728d93191](https://bsd-hardware.info/?probe=9728d93191) | May 25, 2020 |
| Acer          | WMCP78M                     | Desktop     | [db1e7a52b9](https://bsd-hardware.info/?probe=db1e7a52b9) | May 25, 2020 |
| Acer          | WMCP78M                     | Desktop     | [d9b08cfc0c](https://bsd-hardware.info/?probe=d9b08cfc0c) | May 25, 2020 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| IBM           | ThinkPad X41 2525FAG        | Notebook    | [1e849f86cf](https://bsd-hardware.info/?probe=1e849f86cf) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | Desktop     | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| MSI           | MS-7255                     | Desktop     | [3984f45545](https://bsd-hardware.info/?probe=3984f45545) | May 25, 2020 |
| HP            | ProLiant DL365 G5           | Server      | [4ebc960e9c](https://bsd-hardware.info/?probe=4ebc960e9c) | May 25, 2020 |
| Gigabyte      | 945GM-S2                    | Desktop     | [59e3624de7](https://bsd-hardware.info/?probe=59e3624de7) | May 25, 2020 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [09bfdeafbd](https://bsd-hardware.info/?probe=09bfdeafbd) | May 25, 2020 |
| ASRock        | J4205-ITX                   | Desktop     | [bb67f0e80b](https://bsd-hardware.info/?probe=bb67f0e80b) | May 25, 2020 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [9f0ad7bbcf](https://bsd-hardware.info/?probe=9f0ad7bbcf) | May 25, 2020 |
| Intel         | S3420GP E51976-406          | Server      | [6b7fba08dd](https://bsd-hardware.info/?probe=6b7fba08dd) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | Desktop     | [1db4784753](https://bsd-hardware.info/?probe=1db4784753) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.8.1    | 49        | 5.91%   |
| helloSystem 0.7.0    | 44        | 5.31%   |
| OpenBSD 6.8          | 30        | 3.62%   |
| FreeBSD 13.1         | 27        | 3.26%   |
| FreeBSD 14.0-CURRENT | 26        | 3.14%   |
| helloSystem 0.8.0    | 24        | 2.9%    |
| FreeBSD 13.0         | 24        | 2.9%    |
| OpenBSD 7.3          | 22        | 2.65%   |
| FreeBSD 13.2         | 20        | 2.41%   |
| FreeBSD 12.1-p5      | 20        | 2.41%   |
| OpenBSD 7.1          | 17        | 2.05%   |
| FreeBSD 13.0-STABLE  | 12        | 1.45%   |
| FreeBSD 12.1-STABLE  | 12        | 1.45%   |
| helloSystem 0.6.0    | 11        | 1.33%   |
| OpenBSD 6.7          | 10        | 1.21%   |
| helloSystem 0.8.2    | 10        | 1.21%   |
| OpenBSD 7.2          | 9         | 1.09%   |
| OpenBSD 7.0          | 9         | 1.09%   |
| NomadBSD 1.3.2       | 9         | 1.09%   |
| helloSystem 0.5.0    | 9         | 1.09%   |
| FreeBSD 13.1-p5      | 9         | 1.09%   |
| FreeBSD 13.0-CURRENT | 9         | 1.09%   |
| GhostBSD 20.04.02    | 8         | 0.97%   |
| FreeBSD 12.2-p4      | 8         | 0.97%   |
| FreeBSD 12.1-p7      | 8         | 0.97%   |
| OpenBSD 6.9          | 7         | 0.84%   |
| FreeBSD 12.2         | 7         | 0.84%   |
| NomadBSD 5806f915    | 6         | 0.72%   |
| MyBee 13.2           | 6         | 0.72%   |
| helloSystem 0.9.0    | 6         | 0.72%   |
| helloSystem 0.4.0    | 6         | 0.72%   |
| FreeBSD 13.1-p2      | 6         | 0.72%   |
| FreeBSD 12.2-p3      | 6         | 0.72%   |
| FreeBSD 12.2-p2      | 6         | 0.72%   |
| OPNsense 23.7.10     | 5         | 0.6%    |
| OPNsense 22.7.11     | 5         | 0.6%    |
| OPNsense 21.1.1      | 5         | 0.6%    |
| FreeBSD 12.3-STABLE  | 5         | 0.6%    |
| FreeBSD 12.1-p8      | 5         | 0.6%    |
| OPNsense 24.1        | 4         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| FreeBSD     | 278       | 39.43%  |
| helloSystem | 153       | 21.7%   |
| OPNsense    | 108       | 15.32%  |
| OpenBSD     | 84        | 11.91%  |
| MyBee       | 22        | 3.12%   |
| NomadBSD    | 18        | 2.55%   |
| NetBSD      | 15        | 2.13%   |
| GhostBSD    | 13        | 1.84%   |
| ClonOS      | 3         | 0.43%   |
| Ting        | 2         | 0.28%   |
| XigmaNAS    | 1         | 0.14%   |
| TrueNAS     | 1         | 0.14%   |
| pfSense     | 1         | 0.14%   |
| PC-BSD      | 1         | 0.14%   |
| OS108       | 1         | 0.14%   |
| LibertyBSD  | 1         | 0.14%   |
| FuryBSD     | 1         | 0.14%   |
| FuguIta     | 1         | 0.14%   |
| DragonFly   | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 601       | 89.17%  |
| i386    | 33        | 4.9%    |
| arm64   | 31        | 4.6%    |
| arm     | 3         | 0.45%   |
| macppc  | 2         | 0.3%    |
| sparc64 | 1         | 0.15%   |
| powerpc | 1         | 0.15%   |
| evbarm  | 1         | 0.15%   |
| armv7   | 1         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 273       | 38.67%  |
| helloDesktop  | 193       | 27.34%  |
| KDE5          | 51        | 7.22%   |
| XFCE          | 44        | 6.23%   |
| fvwm          | 33        | 4.67%   |
| Openbox       | 27        | 3.82%   |
| MATE          | 24        | 3.4%    |
| GNOME         | 18        | 2.55%   |
| TWM           | 16        | 2.27%   |
| Fluxbox       | 5         | 0.71%   |
| IceWM         | 3         | 0.42%   |
| i3            | 3         | 0.42%   |
| LXQt          | 2         | 0.28%   |
| LXDE          | 2         | 0.28%   |
| Lumina        | 2         | 0.28%   |
| AwesomeWM     | 2         | 0.28%   |
| xinitrc       | 1         | 0.14%   |
| StumpWM       | 1         | 0.14%   |
| plasma        | 1         | 0.14%   |
| KWin          | 1         | 0.14%   |
| Enlightenment | 1         | 0.14%   |
| DWM           | 1         | 0.14%   |
| Budgie        | 1         | 0.14%   |
| akonadi_newm  | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 393       | 57.37%  |
| Console | 289       | 42.19%  |
| Wayland | 3         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 399       | 57.91%  |
| SLiM    | 196       | 28.45%  |
| SDDM    | 46        | 6.68%   |
| LightDM | 28        | 4.06%   |
| XDM     | 10        | 1.45%   |
| GDM     | 8         | 1.16%   |
| PCDM    | 1         | 0.15%   |
| Ly      | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 229       | 32.25%  |
| ru_RU          | 181       | 25.49%  |
| en_US          | 172       | 24.23%  |
| C              | 96        | 13.52%  |
| fr_FR          | 11        | 1.55%   |
| ru             | 10        | 1.41%   |
| ru_RU.KOI8-R   | 4         | 0.56%   |
| en_GB          | 2         | 0.28%   |
| fr             | 1         | 0.14%   |
| en_EN          | 1         | 0.14%   |
| en             | 1         | 0.14%   |
| cv_RU.US-ASCII | 1         | 0.14%   |
| ba_RU          | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 462       | 67.05%  |
| BIOS | 227       | 32.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 312       | 44.64%  |
| Ufs     | 225       | 32.19%  |
| Ffs     | 86        | 12.3%   |
| Cd9660  | 74        | 10.59%  |
| Xfs     | 1         | 0.14%   |
| Hammer2 | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 559       | 82.45%  |
| MBR     | 112       | 16.52%  |
| Unknown | 6         | 0.88%   |
| BSD     | 1         | 0.15%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 119       | 17.71%  |
| Gigabyte Technology | 71        | 10.57%  |
| Lenovo              | 64        | 9.52%   |
| Unknown             | 61        | 9.08%   |
| ASRock              | 43        | 6.4%    |
| Hewlett-Packard     | 42        | 6.25%   |
| MSI                 | 32        | 4.76%   |
| Intel               | 31        | 4.61%   |
| Dell                | 31        | 4.61%   |
| Supermicro          | 21        | 3.13%   |
| Acer                | 21        | 3.13%   |
| Samsung Electronics | 9         | 1.34%   |
| Huanan              | 8         | 1.19%   |
| Techvision          | 7         | 1.04%   |
| Sony                | 7         | 1.04%   |
| Pegatron            | 7         | 1.04%   |
| Apple               | 7         | 1.04%   |
| IBM                 | 5         | 0.74%   |
| HUAWEI              | 4         | 0.6%    |
| Fujitsu             | 4         | 0.6%    |
| Toshiba             | 3         | 0.45%   |
| Timi                | 3         | 0.45%   |
| PC Engines          | 3         | 0.45%   |
| Foxconn             | 3         | 0.45%   |
| Firefly             | 3         | 0.45%   |
| F-Plus Mobile       | 3         | 0.45%   |
| AMI                 | 3         | 0.45%   |
| Wistron             | 2         | 0.3%    |
| Shuttle             | 2         | 0.3%    |
| Radxa               | 2         | 0.3%    |
| Kraftway            | 2         | 0.3%    |
| HMT                 | 2         | 0.3%    |
| ETegro Technologies | 2         | 0.3%    |
| ECS                 | 2         | 0.3%    |
| ZOTAC               | 1         | 0.15%   |
| YANYU               | 1         | 0.15%   |
| VIA Technologies    | 1         | 0.15%   |
| TONK                | 1         | 0.15%   |
| Sun                 | 1         | 0.15%   |
| Stonesoft           | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown                                                               | 62        | 9.23%   |
| ASUS All Series                                                       | 12        | 1.79%   |
| Techvision TVI7309X                                                   | 7         | 1.04%   |
| Supermicro H8DGU                                                      | 3         | 0.45%   |
| PC Engines APU2                                                       | 3         | 0.45%   |
| Intel S5520UR                                                         | 3         | 0.45%   |
| Huanan X99-QD4 V1.0                                                   | 3         | 0.45%   |
| HP ProLiant DL360e Gen8                                               | 3         | 0.45%   |
| Gigabyte C1037UN-EU                                                   | 3         | 0.45%   |
| F-Plus Mobile FLAPTOP r                                               | 3         | 0.45%   |
| Supermicro SYS-6028R-TRT                                              | 2         | 0.3%    |
| Supermicro Super Server                                               | 2         | 0.3%    |
| Supermicro SSG-6029P-E1CR12L                                          | 2         | 0.3%    |
| Shuttle DS20U                                                         | 2         | 0.3%    |
| Samsung N145P/N250P/N260P                                             | 2         | 0.3%    |
| Pegatron SAISHIAT2                                                    | 2         | 0.3%    |
| MSI PS63 Modern 8M                                                    | 2         | 0.3%    |
| MSI MS-7D46                                                           | 2         | 0.3%    |
| MSI MS-7B89                                                           | 2         | 0.3%    |
| MSI MS-7817                                                           | 2         | 0.3%    |
| Lenovo IdeaPad 330-15ARR 81D2                                         | 2         | 0.3%    |
| Lenovo IdeaPad 320-15ISK 80XH                                         | 2         | 0.3%    |
| Lenovo G570 20079                                                     | 2         | 0.3%    |
| Intel X79 V2.72A                                                      | 2         | 0.3%    |
| Intel S3420GP                                                         | 2         | 0.3%    |
| Intel H81U                                                            | 2         | 0.3%    |
| HUAWEI CREM-WXX9                                                      | 2         | 0.3%    |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2         | 0.3%    |
| HMT W041-TF-A-45                                                      | 2         | 0.3%    |
| HP ProLiant MicroServer                                               | 2         | 0.3%    |
| HP ProLiant DL180 G6                                                  | 2         | 0.3%    |
| HP Compaq Pro 6300 SFF                                                | 2         | 0.3%    |
| Gigabyte Z68XP-UD3                                                    | 2         | 0.3%    |
| Gigabyte M68MT-S2P                                                    | 2         | 0.3%    |
| Gigabyte H61M-S2PV                                                    | 2         | 0.3%    |
| Gigabyte H61M-DS2                                                     | 2         | 0.3%    |
| Gigabyte H310M S2 2.0                                                 | 2         | 0.3%    |
| Gigabyte GA-IMB370TN                                                  | 2         | 0.3%    |
| Gigabyte B450 AORUS M                                                 | 2         | 0.3%    |
| Gigabyte A320M-H                                                      | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 62        | 9.23%   |
| Lenovo ThinkPad              | 30        | 4.46%   |
| Acer Aspire                  | 16        | 2.38%   |
| Lenovo IdeaPad               | 14        | 2.08%   |
| HP ProLiant                  | 13        | 1.93%   |
| ASUS PRIME                   | 13        | 1.93%   |
| ASUS All                     | 12        | 1.79%   |
| Dell Inspiron                | 10        | 1.49%   |
| Dell Latitude                | 8         | 1.19%   |
| Techvision TVI7309X          | 7         | 1.04%   |
| Lenovo ThinkCentre           | 7         | 1.04%   |
| HP ProBook                   | 6         | 0.89%   |
| HP Compaq                    | 6         | 0.89%   |
| ASUS ROG                     | 6         | 0.89%   |
| Dell OptiPlex                | 5         | 0.74%   |
| ASUS VivoBook                | 5         | 0.74%   |
| HP Laptop                    | 4         | 0.6%    |
| Toshiba Satellite            | 3         | 0.45%   |
| Supermicro H8DGU             | 3         | 0.45%   |
| PC Engines APU2              | 3         | 0.45%   |
| Intel S5520UR                | 3         | 0.45%   |
| IBM ThinkPad                 | 3         | 0.45%   |
| Huanan X99-QD4               | 3         | 0.45%   |
| Gigabyte C1037UN-EU          | 3         | 0.45%   |
| Gigabyte B450M               | 3         | 0.45%   |
| F-Plus Mobile FLAPTOP        | 3         | 0.45%   |
| Dell PowerEdge               | 3         | 0.45%   |
| ASUS TUF                     | 3         | 0.45%   |
| ASUS P8Z77-V                 | 3         | 0.45%   |
| ASUS P5Q                     | 3         | 0.45%   |
| ASRock Z690                  | 3         | 0.45%   |
| ASRock X570                  | 3         | 0.45%   |
| Wistron ProLiant             | 2         | 0.3%    |
| Supermicro SYS-6028R-TRT     | 2         | 0.3%    |
| Supermicro Super             | 2         | 0.3%    |
| Supermicro SSG-6029P-E1CR12L | 2         | 0.3%    |
| Shuttle DS20U                | 2         | 0.3%    |
| Samsung N145P                | 2         | 0.3%    |
| Pegatron SAISHIAT2           | 2         | 0.3%    |
| MSI PS63                     | 2         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 61        | 9.08%   |
| 2022    | 60        | 8.93%   |
| 2018    | 56        | 8.33%   |
| 2021    | 48        | 7.14%   |
| 2020    | 47        | 6.99%   |
| 2011    | 44        | 6.55%   |
| 2010    | 44        | 6.55%   |
| 2012    | 40        | 5.95%   |
| 2013    | 34        | 5.06%   |
| Unknown | 33        | 4.91%   |
| 2017    | 29        | 4.32%   |
| 2014    | 29        | 4.32%   |
| 2009    | 29        | 4.32%   |
| 2008    | 24        | 3.57%   |
| 2015    | 23        | 3.42%   |
| 2016    | 20        | 2.98%   |
| 2007    | 17        | 2.53%   |
| 2023    | 12        | 1.79%   |
| 2006    | 9         | 1.34%   |
| 2005    | 7         | 1.04%   |
| 2004    | 5         | 0.74%   |
| 2003    | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 418       | 62.2%   |
| Notebook       | 190       | 28.27%  |
| Server         | 40        | 5.95%   |
| Mini pc        | 10        | 1.49%   |
| System on chip | 7         | 1.04%   |
| All in one     | 5         | 0.74%   |
| Firewall       | 1         | 0.15%   |
| Convertible    | 1         | 0.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 668       | 99.4%   |
| Yes  | 4         | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 173       | 25.26%  |
| 4.01-8.0        | 146       | 21.31%  |
| 16.01-24.0      | 144       | 21.02%  |
| 32.01-64.0      | 65        | 9.49%   |
| 2.01-3.0        | 48        | 7.01%   |
| 3.01-4.0        | 28        | 4.09%   |
| 64.01-256.0     | 26        | 3.8%    |
| 0.51-1.0        | 20        | 2.92%   |
| 24.01-32.0      | 10        | 1.46%   |
| 1.01-2.0        | 10        | 1.46%   |
| 0.01-0.5        | 8         | 1.17%   |
| More than 256.0 | 7         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 344       | 49.07%  |
| 0.51-1.0   | 170       | 24.25%  |
| 1.01-2.0   | 84        | 11.98%  |
| 4.01-8.0   | 22        | 3.14%   |
| Unknown    | 17        | 2.43%   |
| 2.01-3.0   | 15        | 2.14%   |
| 0          | 14        | 2%      |
| 3.01-4.0   | 12        | 1.71%   |
| 8.01-16.0  | 12        | 1.71%   |
| 24.01-32.0 | 5         | 0.71%   |
| 16.01-24.0 | 5         | 0.71%   |
| 32.01-64.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 359       | 50.71%  |
| 2      | 152       | 21.47%  |
| 0      | 70        | 9.89%   |
| 3      | 53        | 7.49%   |
| 4      | 37        | 5.23%   |
| 5      | 17        | 2.4%    |
| 6      | 8         | 1.13%   |
| 7      | 5         | 0.71%   |
| 10     | 2         | 0.28%   |
| 19     | 1         | 0.14%   |
| 14     | 1         | 0.14%   |
| 11     | 1         | 0.14%   |
| 9      | 1         | 0.14%   |
| 8      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 561       | 82.62%  |
| Yes       | 118       | 17.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 603       | 89.73%  |
| No        | 69        | 10.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 385       | 56.95%  |
| Yes       | 291       | 43.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 480       | 70.9%   |
| Yes       | 197       | 29.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 672       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 210       | 30.26%  |
| St Petersburg     | 88        | 12.68%  |
| Krasnodar         | 27        | 3.89%   |
| Yekaterinburg     | 23        | 3.31%   |
| Novosibirsk       | 18        | 2.59%   |
| Chelyabinsk       | 17        | 2.45%   |
| Vladivostok       | 15        | 2.16%   |
| Ozersk            | 13        | 1.87%   |
| Krasnoyarsk       | 11        | 1.59%   |
| Surgut            | 8         | 1.15%   |
| Saratov           | 8         | 1.15%   |
| Perm              | 8         | 1.15%   |
| Voronezh          | 7         | 1.01%   |
| Ufa               | 7         | 1.01%   |
| Stavropol         | 7         | 1.01%   |
| Omsk              | 7         | 1.01%   |
| Barnaul           | 7         | 1.01%   |
| Ulyanovsk         | 6         | 0.86%   |
| Rostov-on-Don     | 6         | 0.86%   |
| Kirov             | 6         | 0.86%   |
| Kamensk-Ural'skiy | 6         | 0.86%   |
| Penza             | 5         | 0.72%   |
| Irkutsk           | 5         | 0.72%   |
| Volgograd         | 4         | 0.58%   |
| Podolsk           | 4         | 0.58%   |
| Nizhniy Novgorod  | 4         | 0.58%   |
| Lipetsk           | 4         | 0.58%   |
| Khabarovsk        | 4         | 0.58%   |
| Cherepovets       | 4         | 0.58%   |
| Armavir           | 4         | 0.58%   |
| Vladimir          | 3         | 0.43%   |
| Vidnoye           | 3         | 0.43%   |
| Tyumen            | 3         | 0.43%   |
| Tolyatti          | 3         | 0.43%   |
| Tambov            | 3         | 0.43%   |
| Smolensk          | 3         | 0.43%   |
| Samara            | 3         | 0.43%   |
| Orenburg          | 3         | 0.43%   |
| Obninsk           | 3         | 0.43%   |
| Khimki            | 3         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 170       | 294    | 18.89%  |
| Seagate             | 145       | 301    | 16.11%  |
| Samsung Electronics | 95        | 135    | 10.56%  |
| Toshiba             | 54        | 88     | 6%      |
| Kingston            | 51        | 65     | 5.67%   |
| Intel               | 37        | 67     | 4.11%   |
| Hitachi             | 35        | 74     | 3.89%   |
| A-DATA Technology   | 20        | 26     | 2.22%   |
| SanDisk             | 19        | 28     | 2.11%   |
| HGST                | 15        | 33     | 1.67%   |
| Crucial             | 15        | 22     | 1.67%   |
| SPCC                | 14        | 16     | 1.56%   |
| Hewlett-Packard     | 12        | 26     | 1.33%   |
| Apacer              | 12        | 14     | 1.33%   |
| AMD                 | 11        | 12     | 1.22%   |
| SK hynix            | 10        | 13     | 1.11%   |
| Micron Technology   | 10        | 14     | 1.11%   |
| Transcend           | 9         | 9      | 1%      |
| Silicon Motion      | 9         | 13     | 1%      |
| Smartbuy            | 8         | 11     | 0.89%   |
| Patriot             | 8         | 8      | 0.89%   |
| KingSpec            | 8         | 11     | 0.89%   |
| Gigabyte Technology | 8         | 11     | 0.89%   |
| Plextor             | 7         | 10     | 0.78%   |
| OCZ                 | 7         | 8      | 0.78%   |
| NVMe                | 7         | 12     | 0.78%   |
| Maxtor              | 7         | 7      | 0.78%   |
| FORESEE             | 7         | 8      | 0.78%   |
| Netac               | 6         | 6      | 0.67%   |
| OPENBSD             | 5         | 12     | 0.56%   |
| Kston               | 4         | 4      | 0.44%   |
| Fujitsu             | 4         | 5      | 0.44%   |
| China               | 4         | 4      | 0.44%   |
| Team                | 3         | 3      | 0.33%   |
| SSSTC               | 3         | 5      | 0.33%   |
| KIOXIA              | 3         | 3      | 0.33%   |
| Innostor            | 3         | 3      | 0.33%   |
| Hoodisk             | 3         | 5      | 0.33%   |
| Apple               | 3         | 3      | 0.33%   |
| XrayDisk            | 2         | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB         | 9         | 0.89%   |
| Toshiba DT01ACA100 1TB               | 9         | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB       | 9         | 0.89%   |
| Kingston SA400S37240G 240GB          | 8         | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB         | 7         | 0.69%   |
| SPCC Solid State Disk 128GB          | 7         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 7         | 0.69%   |
| WDC WD20EARX-00PASB0 2TB             | 6         | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB       | 6         | 0.59%   |
| Samsung SSD 860 EVO 250GB            | 6         | 0.59%   |
| Kingston SV300S37A120G 120GB         | 6         | 0.59%   |
| Kingston SA400S37120G 120GB          | 6         | 0.59%   |
| HP RAID 1(1+0) 73GB                  | 6         | 0.59%   |
| AMD R5SL120G 120GB                   | 6         | 0.59%   |
| A-DATA SU650 120GB                   | 6         | 0.59%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.49%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 0.49%   |
| Seagate ST250DM000-1BD141 250GB      | 5         | 0.49%   |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.49%   |
| Samsung SSD 970 EVO Plus 250GB       | 5         | 0.49%   |
| Samsung SSD 860 EVO 500GB            | 5         | 0.49%   |
| OPENBSD SR RAID 1 2TB                | 5         | 0.49%   |
| Intel SSDSC2BW480H6 480GB            | 5         | 0.49%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 4         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.4%    |
| WDC WD1002FAEX-00Y9A0 1TB            | 4         | 0.4%    |
| Toshiba DT01ACA050 500GB             | 4         | 0.4%    |
| Seagate ST4000VN008-2DR166 4TB       | 4         | 0.4%    |
| Seagate ST3300657SS 304GB            | 4         | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB       | 4         | 0.4%    |
| Kston SSD 128GB                      | 4         | 0.4%    |
| FORESEE XP1000F001T 1TB              | 4         | 0.4%    |
| WDC WDS500G1B0A-00H9H0 500GB         | 3         | 0.3%    |
| WDC WD800AAJS-00PSA0 80GB            | 3         | 0.3%    |
| WDC WD6400AARS-00Y5B1 640GB          | 3         | 0.3%    |
| WDC WD5000LPCX-60VHAT0 500GB         | 3         | 0.3%    |
| WDC WD5000AZLX-00K2TA0 500GB         | 3         | 0.3%    |
| WDC WD10JFCX-68N6GN0 1TB             | 3         | 0.3%    |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.3%    |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 3         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 145       | 301    | 33.26%  |
| WDC                                | 134       | 243    | 30.73%  |
| Toshiba                            | 49        | 83     | 11.24%  |
| Hitachi                            | 35        | 74     | 8.03%   |
| Samsung Electronics                | 15        | 25     | 3.44%   |
| HGST                               | 15        | 33     | 3.44%   |
| Hewlett-Packard                    | 9         | 23     | 2.06%   |
| Maxtor                             | 7         | 7      | 1.61%   |
| NVMe                               | 6         | 11     | 1.38%   |
| OPENBSD                            | 5         | 12     | 1.15%   |
| Fujitsu                            | 4         | 5      | 0.92%   |
| JetFlash                           | 2         | 2      | 0.46%   |
| Adaptec                            | 2         | 12     | 0.46%   |
| USB                                | 1         | 1      | 0.23%   |
| UFD 2.0                            | 1         | 1      | 0.23%   |
| Product:              USB DISK 2.0 | 1         | 1      | 0.23%   |
| MaxDigital                         | 1         | 1      | 0.23%   |
| LSILOGIC                           | 1         | 1      | 0.23%   |
| IBM                                | 1         | 1      | 0.23%   |
| Areca                              | 1         | 2      | 0.23%   |
| Apple                              | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 66     | 15.84%  |
| Kingston            | 39        | 49     | 11.44%  |
| WDC                 | 26        | 29     | 7.62%   |
| Intel               | 26        | 48     | 7.62%   |
| SanDisk             | 19        | 28     | 5.57%   |
| A-DATA Technology   | 15        | 19     | 4.4%    |
| SPCC                | 13        | 15     | 3.81%   |
| Crucial             | 13        | 19     | 3.81%   |
| Apacer              | 10        | 11     | 2.93%   |
| Smartbuy            | 8         | 11     | 2.35%   |
| Micron Technology   | 8         | 12     | 2.35%   |
| KingSpec            | 8         | 11     | 2.35%   |
| AMD                 | 8         | 9      | 2.35%   |
| Transcend           | 7         | 7      | 2.05%   |
| Plextor             | 7         | 10     | 2.05%   |
| Patriot             | 7         | 7      | 2.05%   |
| OCZ                 | 7         | 8      | 2.05%   |
| Netac               | 5         | 5      | 1.47%   |
| Kston               | 4         | 4      | 1.17%   |
| Gigabyte Technology | 4         | 6      | 1.17%   |
| China               | 4         | 4      | 1.17%   |
| Team                | 3         | 3      | 0.88%   |
| Innostor            | 3         | 3      | 0.88%   |
| Hewlett-Packard     | 3         | 3      | 0.88%   |
| Verbatim            | 2         | 2      | 0.59%   |
| Toshiba             | 2         | 2      | 0.59%   |
| SK hynix            | 2         | 2      | 0.59%   |
| SETHRISE            | 2         | 2      | 0.59%   |
| Hoodisk             | 2         | 4      | 0.59%   |
| FORESEE             | 2         | 3      | 0.59%   |
| Apple               | 2         | 2      | 0.59%   |
| XUNZHE              | 1         | 1      | 0.29%   |
| XrayDisk            | 1         | 1      | 0.29%   |
| XPG                 | 1         | 1      | 0.29%   |
| Union Memory        | 1         | 1      | 0.29%   |
| TAMMUZ              | 1         | 1      | 0.29%   |
| SATADOM             | 1         | 1      | 0.29%   |
| Qumo                | 1         | 1      | 0.29%   |
| Palit               | 1         | 1      | 0.29%   |
| NVMe                | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 344       | 840    | 44.33%  |
| SSD  | 304       | 437    | 39.18%  |
| NVMe | 128       | 179    | 16.49%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 539       | 1277   | 80.81%  |
| NVMe | 128       | 179    | 19.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 444       | 731    | 64.16%  |
| 0.51-1.0        | 149       | 253    | 21.53%  |
| 1.01-2.0        | 49        | 165    | 7.08%   |
| 3.01-4.0        | 22        | 53     | 3.18%   |
| 4.01-10.0       | 14        | 34     | 2.02%   |
| 2.01-3.0        | 10        | 26     | 1.45%   |
| 10.01-20.0      | 3         | 14     | 0.43%   |
| More than 100.0 | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 198       | 27.46%  |
| 1-20           | 154       | 21.36%  |
| 251-500        | 137       | 19%     |
| 51-100         | 67        | 9.29%   |
| 501-1000       | 61        | 8.46%   |
| 21-50          | 52        | 7.21%   |
| 1001-2000      | 24        | 3.33%   |
| More than 3000 | 18        | 2.5%    |
| Unknown        | 6         | 0.83%   |
| 2001-3000      | 4         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 567       | 81.35%  |
| 21-50          | 53        | 7.6%    |
| 101-250        | 22        | 3.16%   |
| 51-100         | 20        | 2.87%   |
| 501-1000       | 9         | 1.29%   |
| More than 3000 | 8         | 1.15%   |
| Unknown        | 6         | 0.86%   |
| 251-500        | 4         | 0.57%   |
| 2001-3000      | 4         | 0.57%   |
| 1001-2000      | 4         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Intel SSDSC2BW480H6 480GB           | 5         | 5      | 3.21%   |
| WDC WDS240G2G0A-00JH30 240GB        | 3         | 3      | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 1.92%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 7      | 1.92%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 2         | 3      | 1.28%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 1.28%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 2         | 2      | 1.28%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 1.28%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 1.28%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 1.28%   |
| Seagate ST3500413AS 500GB           | 2         | 4      | 1.28%   |
| Seagate ST3320418AS 320GB           | 2         | 2      | 1.28%   |
| Seagate ST250DM000-1BD141 250GB     | 2         | 4      | 1.28%   |
| Samsung Electronics HD501LJ 500GB   | 2         | 4      | 1.28%   |
| Samsung Electronics HD161HJ 160GB   | 2         | 3      | 1.28%   |
| Micron Technology 1100 SATA 256GB   | 2         | 2      | 1.28%   |
| Maxtor STM3320613AS 320GB           | 2         | 2      | 1.28%   |
| Kingston SA400S37120G 120GB         | 2         | 2      | 1.28%   |
| Hitachi HTS547550A9E384 500GB       | 2         | 2      | 1.28%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 4      | 1.28%   |
| XPG SX950U 240GB                    | 1         | 1      | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1      | 0.64%   |
| WDC WD800AAJS-00TDA0 80GB           | 1         | 1      | 0.64%   |
| WDC WD7501AALS-00E8B0 752GB         | 1         | 1      | 0.64%   |
| WDC WD7500AACS-00ZJB0 752GB         | 1         | 1      | 0.64%   |
| WDC WD60EFRX-68MYMN1 6TB            | 1         | 1      | 0.64%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 1         | 1      | 0.64%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 0.64%   |
| WDC WD5000AZRZ-00HTKB0 500GB        | 1         | 1      | 0.64%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1         | 1      | 0.64%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 1      | 0.64%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1         | 1      | 0.64%   |
| WDC WD40EFRX-68N32N0 4TB            | 1         | 3      | 0.64%   |
| WDC WD4000FYYZ-01UL1B0 4TB          | 1         | 1      | 0.64%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 2      | 0.64%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1         | 1      | 0.64%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1         | 1      | 0.64%   |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 0.64%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1         | 1      | 0.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 52     | 25.17%  |
| WDC                 | 35        | 47     | 23.18%  |
| Hitachi             | 16        | 20     | 10.6%   |
| Samsung Electronics | 12        | 19     | 7.95%   |
| Toshiba             | 11        | 13     | 7.28%   |
| Intel               | 11        | 11     | 7.28%   |
| Kingston            | 7         | 7      | 4.64%   |
| Maxtor              | 4         | 4      | 2.65%   |
| HGST                | 3         | 4      | 1.99%   |
| Plextor             | 2         | 2      | 1.32%   |
| Micron Technology   | 2         | 2      | 1.32%   |
| XPG                 | 1         | 1      | 0.66%   |
| Transcend           | 1         | 1      | 0.66%   |
| SPCC                | 1         | 1      | 0.66%   |
| Hewlett-Packard     | 1         | 1      | 0.66%   |
| GLOWAY              | 1         | 2      | 0.66%   |
| GK                  | 1         | 1      | 0.66%   |
| Crucial             | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |
| AMD                 | 1         | 2      | 0.66%   |
| A-DATA Technology   | 1         | 1      | 0.66%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 52     | 34.23%  |
| WDC                 | 31        | 43     | 27.93%  |
| Hitachi             | 16        | 20     | 14.41%  |
| Toshiba             | 11        | 13     | 9.91%   |
| Samsung Electronics | 7         | 10     | 6.31%   |
| Maxtor              | 4         | 4      | 3.6%    |
| HGST                | 3         | 4      | 2.7%    |
| Hewlett-Packard     | 1         | 1      | 0.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 109       | 147    | 73.65%  |
| SSD  | 38        | 45     | 25.68%  |
| NVMe | 1         | 1      | 0.68%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB          | 1         | 1      | 12.5%   |
| WDC WD6400AARS-00Y5B1 640GB          | 1         | 2      | 12.5%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 1      | 12.5%   |
| Toshiba MG05ACA800E 8TB              | 1         | 1      | 12.5%   |
| SanDisk pSSD 16GB                    | 1         | 1      | 12.5%   |
| Hitachi HTS545025B9A300 250GB        | 1         | 1      | 12.5%   |
| Hitachi HDS721010DLE630 1TB          | 1         | 1      | 12.5%   |
| Crucial M4-CT256M4SSD1 256GB         | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 4      | 37.5%   |
| Hitachi | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| SanDisk | 1         | 1      | 12.5%   |
| Crucial | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 510       | 1151   | 71.93%  |
| Malfunc  | 144       | 193    | 20.31%  |
| Detected | 47        | 103    | 6.63%   |
| Failed   | 8         | 9      | 1.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 463       | 55.65%  |
| AMD                                     | 107       | 12.86%  |
| Samsung Electronics                     | 37        | 4.45%   |
| Silicon Motion                          | 24        | 2.88%   |
| Marvell Technology Group                | 19        | 2.28%   |
| SanDisk                                 | 17        | 2.04%   |
| Broadcom / LSI                          | 17        | 2.04%   |
| JMicron Technology                      | 16        | 1.92%   |
| Nvidia                                  | 14        | 1.68%   |
| ASMedia Technology                      | 14        | 1.68%   |
| Kingston Technology Company             | 12        | 1.44%   |
| SK hynix                                | 10        | 1.2%    |
| Phison Electronics                      | 8         | 0.96%   |
| Hewlett-Packard                         | 8         | 0.96%   |
| Realtek Semiconductor                   | 7         | 0.84%   |
| Shenzhen Longsys Electronics            | 6         | 0.72%   |
| ADATA Technology                        | 6         | 0.72%   |
| Areca Technology                        | 5         | 0.6%    |
| Toshiba                                 | 4         | 0.48%   |
| KIOXIA                                  | 4         | 0.48%   |
| VIA Technologies                        | 3         | 0.36%   |
| Solid State Storage Technology          | 3         | 0.36%   |
| Micron/Crucial Technology               | 3         | 0.36%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.36%   |
| Transcend                               | 2         | 0.24%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.24%   |
| Silicon Image                           | 2         | 0.24%   |
| Micron Technology                       | 2         | 0.24%   |
| Lite-On IT Corp. / Plextor              | 2         | 0.24%   |
| Integrated Technology Express           | 2         | 0.24%   |
| Adaptec                                 | 2         | 0.24%   |
| Union Memory (Shenzhen)                 | 1         | 0.12%   |
| Shenzhen Unionmemory Information System | 1         | 0.12%   |
| Netac Technology                        | 1         | 0.12%   |
| Lite-On Technology                      | 1         | 0.12%   |
| Lenovo                                  | 1         | 0.12%   |
| Hosin Global Electronics                | 1         | 0.12%   |
| Broadcom                                | 1         | 0.12%   |
| 3ware                                   | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 60        | 6.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 25        | 2.61%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 24        | 2.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23        | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 2.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 22        | 2.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 2.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 21        | 2.19%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 20        | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 20        | 2.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 19        | 1.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 1.98%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 17        | 1.77%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 17        | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 17        | 1.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 12        | 1.25%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 12        | 1.25%   |
| AMD 400 Series Chipset SATA Controller                                           | 12        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 1.15%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 10        | 1.04%   |
| JMicron JMB363 SATA/IDE Controller                                               | 9         | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 0.94%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 9         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 9         | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 8         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                           | 8         | 0.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 7         | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 7         | 0.73%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 7         | 0.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 483       | 58.69%  |
| NVMe | 157       | 19.08%  |
| IDE  | 129       | 15.67%  |
| RAID | 38        | 4.62%   |
| SAS  | 10        | 1.22%   |
| SCSI | 6         | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Intel              | 493       | 72.93%  |
| AMD                | 140       | 20.71%  |
| ARM                | 29        | 4.29%   |
| Unknown            | 6         | 0.89%   |
| Rockchip           | 3         | 0.44%   |
| VIA                | 1         | 0.15%   |
| PowerPC            | 1         | 0.15%   |
| Baikal Electronics | 1         | 0.15%   |
| 7447A              | 1         | 0.15%   |
| 11th               | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| ARM Cortex-A55 r2p0                      | 14        | 2.04%   |
| Intel Celeron N5105 @ 2.00GHz            | 7         | 1.02%   |
| Intel Core i3-6006U CPU @ 2.00GHz        | 6         | 0.87%   |
| Intel Celeron CPU J1800 @ 2.41GHz        | 6         | 0.87%   |
| AMD Ryzen 5 3600 6-Core Processor        | 6         | 0.87%   |
|                                          | 6         | 0.87%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 5         | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 5         | 0.73%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5         | 0.73%   |
| Intel 686-class                          | 5         | 0.73%   |
| ARM Cortex-A57 r1p3                      | 5         | 0.73%   |
| Intel N100                               | 4         | 0.58%   |
| Intel CPU Version                        | 4         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 4         | 0.58%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 4         | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 4         | 0.58%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 4         | 0.58%   |
| Intel Celeron CPU 1037U @ 1.80GHz        | 4         | 0.58%   |
| ARM Cortex-A53 r0p4                      | 4         | 0.58%   |
| AMD Ryzen 7 5825U with Radeon Graphics   | 4         | 0.58%   |
| Intel Xeon CPU X3450 @ 2.67GHz           | 3         | 0.44%   |
| Intel Xeon CPU E5645 @ 2.40GHz           | 3         | 0.44%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 3         | 0.44%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz   | 3         | 0.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 3         | 0.44%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 3         | 0.44%   |
| Intel Pentium CPU G3220 @ 3.00GHz        | 3         | 0.44%   |
| Intel Core i7-8665U CPU @ 1.90GHz        | 3         | 0.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 0.44%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 3         | 0.44%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 3         | 0.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 0.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz        | 3         | 0.44%   |
| Intel Core i3-6100 CPU @ 3.70GHz         | 3         | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz         | 3         | 0.44%   |
| Intel Core i3 CPU M 350 @ 2.27GHz        | 3         | 0.44%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz     | 3         | 0.44%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz     | 3         | 0.44%   |
| Intel Celeron N5100 @ 1.10GHz            | 3         | 0.44%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 79        | 11.65%  |
| Intel Celeron           | 69        | 10.18%  |
| Intel Xeon              | 67        | 9.88%   |
| Intel Core i7           | 54        | 7.96%   |
| Intel Core i3           | 47        | 6.93%   |
| Other                   | 41        | 6.05%   |
| ARM Cortex              | 29        | 4.28%   |
| Intel Core 2 Duo        | 26        | 3.83%   |
| AMD Ryzen 7             | 26        | 3.83%   |
| AMD Ryzen 5             | 24        | 3.54%   |
| Intel Atom              | 23        | 3.39%   |
| Intel Pentium           | 22        | 3.24%   |
| Intel Core 2 Quad       | 13        | 1.92%   |
| AMD Ryzen 3             | 13        | 1.92%   |
| Intel Genuine           | 8         | 1.18%   |
| AMD FX                  | 8         | 1.18%   |
| Intel Pentium Dual-Core | 7         | 1.03%   |
| Intel Pentium 4         | 7         | 1.03%   |
| AMD Ryzen 9             | 6         | 0.88%   |
| Intel Pentium Silver    | 5         | 0.74%   |
| Intel Pentium M         | 5         | 0.74%   |
| Intel Pentium Gold      | 5         | 0.74%   |
| Intel 686-class         | 5         | 0.74%   |
| AMD Phenom II X4        | 5         | 0.74%   |
| AMD E                   | 5         | 0.74%   |
| AMD A6                  | 5         | 0.74%   |
| Intel Core i9           | 4         | 0.59%   |
| AMD GX                  | 4         | 0.59%   |
| Intel Xeon Gold         | 3         | 0.44%   |
| Intel Pentium Dual      | 3         | 0.44%   |
| Intel Pentium D         | 3         | 0.44%   |
| Intel Core 2            | 3         | 0.44%   |
| AMD Ryzen 7 PRO         | 3         | 0.44%   |
| AMD Opteron             | 3         | 0.44%   |
| AMD Athlon 64 X2        | 3         | 0.44%   |
| AMD A4                  | 3         | 0.44%   |
| AMD A10                 | 3         | 0.44%   |
| Intel Xeon Bronze       | 2         | 0.29%   |
| Intel Core m3           | 2         | 0.29%   |
| Intel Celeron D         | 2         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 212       | 31.18%  |
| 2       | 185       | 27.21%  |
| Unknown | 93        | 13.68%  |
| 6       | 44        | 6.47%   |
| 8       | 39        | 5.74%   |
| 1       | 30        | 4.41%   |
| 16      | 28        | 4.12%   |
| 12      | 28        | 4.12%   |
| 24      | 8         | 1.18%   |
| 28      | 3         | 0.44%   |
| 32      | 2         | 0.29%   |
| 14      | 2         | 0.29%   |
| 3       | 2         | 0.29%   |
| 48      | 1         | 0.15%   |
| 36      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |
| 18      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 592       | 86.93%  |
| Unknown | 56        | 8.22%   |
| 2       | 33        | 4.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 329       | 48.31%  |
| 2       | 239       | 35.1%   |
| Unknown | 113       | 16.59%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 82        | 12.11%  |
| KabyLake      | 70        | 10.34%  |
| IvyBridge     | 45        | 6.65%   |
| SandyBridge   | 44        | 6.5%    |
| Penryn        | 40        | 5.91%   |
| Haswell       | 39        | 5.76%   |
| Skylake       | 32        | 4.73%   |
| Silvermont    | 29        | 4.28%   |
| Zen 2         | 26        | 3.84%   |
| Core          | 25        | 3.69%   |
| Bonnell       | 21        | 3.1%    |
| K10           | 20        | 2.95%   |
| Zen 3         | 19        | 2.81%   |
| Westmere      | 18        | 2.66%   |
| Broadwell     | 16        | 2.36%   |
| Nehalem       | 14        | 2.07%   |
| Goldmont      | 14        | 2.07%   |
| CometLake     | 14        | 2.07%   |
| Zen           | 13        | 1.92%   |
| NetBurst      | 13        | 1.92%   |
| Zen+          | 12        | 1.77%   |
| P6            | 12        | 1.77%   |
| Piledriver    | 11        | 1.62%   |
| Goldmont plus | 9         | 1.33%   |
| K8 Hammer     | 7         | 1.03%   |
| TigerLake     | 6         | 0.89%   |
| Bobcat        | 6         | 0.89%   |
| Puma          | 5         | 0.74%   |
| Excavator     | 4         | 0.59%   |
| Bulldozer     | 4         | 0.59%   |
| Jaguar        | 3         | 0.44%   |
| Steamroller   | 1         | 0.15%   |
| K10 Llano     | 1         | 0.15%   |
| IceLake       | 1         | 0.15%   |
| Geode         | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 321       | 47.49%  |
| Nvidia                                       | 152       | 22.49%  |
| AMD                                          | 150       | 22.19%  |
| Matrox Electronics Systems                   | 30        | 4.44%   |
| ASPEED Technology                            | 19        | 2.81%   |
| VIA Technologies                             | 2         | 0.3%    |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.15%   |
| ATI                                          | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 3.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 2.73%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 19        | 2.73%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 14        | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 12        | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.58%   |
| Intel JasperLake [UHD Graphics]                                                          | 11        | 1.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 1.58%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 1.44%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 10        | 1.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.15%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.15%   |
| Intel HD Graphics 630                                                                    | 8         | 1.15%   |
| Intel HD Graphics 530                                                                    | 8         | 1.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.15%   |
| AMD ES1000                                                                               | 8         | 1.15%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 7         | 1.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7         | 1.01%   |
| Intel HD Graphics 500                                                                    | 7         | 1.01%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7         | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.86%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 6         | 0.86%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6         | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.86%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.72%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 5         | 0.72%   |
| Matrox Electronics Systems MGA G200EH                                                    | 5         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 0.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.72%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 5         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 250       | 36.98%  |
| 1 x AMD                  | 126       | 18.64%  |
| 1 x Nvidia               | 116       | 17.16%  |
| Other                    | 47        | 6.95%   |
| 2 x Intel                | 30        | 4.44%   |
| 1 x Matrox               | 30        | 4.44%   |
| Intel + Nvidia           | 30        | 4.44%   |
| 1 x ASPEED               | 18        | 2.66%   |
| 2 x AMD                  | 11        | 1.63%   |
| Intel + AMD              | 10        | 1.48%   |
| AMD + Nvidia             | 3         | 0.44%   |
| 1 x VIA                  | 2         | 0.3%    |
| 1 x XGI                  | 1         | 0.15%   |
| Nvidia + ASPEED          | 1         | 0.15%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 531       | 77.86%  |
| Proprietary | 81        | 11.88%  |
| Unknown     | 70        | 10.26%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 535       | 78.22%  |
| 0.01-0.5   | 41        | 5.99%   |
| 0.51-1.0   | 31        | 4.53%   |
| 1.01-2.0   | 29        | 4.24%   |
| 3.01-4.0   | 24        | 3.51%   |
| 7.01-8.0   | 9         | 1.32%   |
| 5.01-6.0   | 8         | 1.17%   |
| 8.01-16.0  | 4         | 0.58%   |
| 2.01-3.0   | 3         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 50        | 16.03%  |
| AU Optronics            | 33        | 10.58%  |
| Goldstar                | 26        | 8.33%   |
| BOE                     | 21        | 6.73%   |
| Chimei Innolux          | 20        | 6.41%   |
| LG Display              | 17        | 5.45%   |
| ViewSonic               | 15        | 4.81%   |
| Dell                    | 15        | 4.81%   |
| Philips                 | 13        | 4.17%   |
| Acer                    | 13        | 4.17%   |
| Ancor Communications    | 11        | 3.53%   |
| BenQ                    | 10        | 3.21%   |
| NEC Computers           | 8         | 2.56%   |
| AOC                     | 8         | 2.56%   |
| Hewlett-Packard         | 6         | 1.92%   |
| InfoVision              | 5         | 1.6%    |
| Sony                    | 4         | 1.28%   |
| LG Electronics          | 4         | 1.28%   |
| LG Philips              | 3         | 0.96%   |
| Lenovo                  | 3         | 0.96%   |
| Chi Mei Optoelectronics | 3         | 0.96%   |
| Apple                   | 3         | 0.96%   |
| RTK                     | 2         | 0.64%   |
| PANDA                   | 2         | 0.64%   |
| Panasonic               | 2         | 0.64%   |
| Iiyama                  | 2         | 0.64%   |
| HKC                     | 2         | 0.64%   |
| HannStar                | 2         | 0.64%   |
| Fujitsu Siemens         | 2         | 0.64%   |
| Unknown (CDD)           | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| Microstep               | 1         | 0.32%   |
| Daewoo                  | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch            | 4         | 1.24%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 4         | 1.24%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch     | 3         | 0.93%   |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                       | 3         | 0.93%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 2         | 0.62%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch     | 2         | 0.62%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch      | 2         | 0.62%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch       | 2         | 0.62%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch        | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 220x130mm 10.1-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch   | 2         | 0.62%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                    | 2         | 0.62%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                  | 2         | 0.62%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch              | 2         | 0.62%   |
| HKC LCD Monitor HKC3D05 1920x1080 340x190mm 15.3-inch                    | 2         | 0.62%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 2         | 0.62%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                      | 2         | 0.62%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.62%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2         | 0.62%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.62%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                    | 2         | 0.62%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                        | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch         | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch         | 2         | 0.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO1457 1366x768 310x170mm 13.9-inch | 2         | 0.62%   |
| BOE LCD Monitor BOE0AC1 2560x1600 340x210mm 15.7-inch                    | 2         | 0.62%   |
| BOE HF BOE0691 1920x1080 280x160mm 12.7-inch                             | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 2         | 0.62%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 2         | 0.62%   |
| Acer K272HUL ACR0524 2560x1440 600x340mm 27.2-inch                       | 2         | 0.62%   |
| Acer AL1716 ACRAD46 1280x1024 340x270mm 17.1-inch                        | 2         | 0.62%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch               | 1         | 0.31%   |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch                 | 1         | 0.31%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch            | 1         | 0.31%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch               | 1         | 0.31%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch               | 1         | 0.31%   |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                            | 1         | 0.31%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch               | 1         | 0.31%   |
| ViewSonic LCD Monitor VSC6F2E 1920x1080 480x270mm 21.7-inch              | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 139       | 45.42%  |
| 1366x768 (WXGA)    | 38        | 12.42%  |
| 1280x1024 (SXGA)   | 32        | 10.46%  |
| 3840x2160 (4K)     | 16        | 5.23%   |
| 1440x900 (WXGA+)   | 13        | 4.25%   |
| 1600x900 (HD+)     | 12        | 3.92%   |
| 2560x1440 (QHD)    | 10        | 3.27%   |
| 1920x1200 (WUXGA)  | 9         | 2.94%   |
| 1680x1050 (WSXGA+) | 9         | 2.94%   |
| 1280x800 (WXGA)    | 7         | 2.29%   |
| 1024x600           | 5         | 1.63%   |
| 2560x1600          | 2         | 0.65%   |
| 2560x1080          | 2         | 0.65%   |
| 1600x1200          | 2         | 0.65%   |
| Unknown            | 2         | 0.65%   |
| 3440x1440          | 1         | 0.33%   |
| 3200x1800 (QHD+)   | 1         | 0.33%   |
| 2520x1680          | 1         | 0.33%   |
| 2240x1400          | 1         | 0.33%   |
| 2160x1440          | 1         | 0.33%   |
| 2160x1350          | 1         | 0.33%   |
| 1920x540           | 1         | 0.33%   |
| 1024x768 (XGA)     | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 58        | 18.53%  |
| 13      | 36        | 11.5%   |
| 21      | 29        | 9.27%   |
| 17      | 29        | 9.27%   |
| 24      | 26        | 8.31%   |
| 19      | 23        | 7.35%   |
| 27      | 19        | 6.07%   |
| Unknown | 19        | 6.07%   |
| 23      | 18        | 5.75%   |
| 14      | 7         | 2.24%   |
| 12      | 6         | 1.92%   |
| 10      | 6         | 1.92%   |
| 22      | 5         | 1.6%    |
| 20      | 5         | 1.6%    |
| 18      | 5         | 1.6%    |
| 11      | 5         | 1.6%    |
| 31      | 4         | 1.28%   |
| 16      | 3         | 0.96%   |
| 50      | 2         | 0.64%   |
| 34      | 2         | 0.64%   |
| 57      | 1         | 0.32%   |
| 55      | 1         | 0.32%   |
| 54      | 1         | 0.32%   |
| 52      | 1         | 0.32%   |
| 48      | 1         | 0.32%   |
| 26      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 34.73%  |
| 501-600     | 63        | 20.26%  |
| 401-500     | 56        | 18.01%  |
| 201-300     | 33        | 10.61%  |
| 351-400     | 19        | 6.11%   |
| Unknown     | 19        | 6.11%   |
| 1001-1500   | 7         | 2.25%   |
| 601-700     | 4         | 1.29%   |
| 701-800     | 2         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 202       | 67.11%  |
| 16/10   | 45        | 14.95%  |
| 5/4     | 29        | 9.63%   |
| Unknown | 17        | 5.65%   |
| 4/3     | 3         | 1%      |
| 3/2     | 3         | 1%      |
| 21/9    | 2         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 68        | 21.79%  |
| 91-100         | 46        | 14.74%  |
| 81-90          | 34        | 10.9%   |
| 151-200        | 30        | 9.62%   |
| 141-150        | 24        | 7.69%   |
| 301-350        | 20        | 6.41%   |
| Unknown        | 19        | 6.09%   |
| 101-110        | 12        | 3.85%   |
| 121-130        | 9         | 2.88%   |
| 71-80          | 8         | 2.56%   |
| 251-300        | 8         | 2.56%   |
| More than 1000 | 7         | 2.24%   |
| 351-500        | 6         | 1.92%   |
| 41-50          | 6         | 1.92%   |
| 61-70          | 5         | 1.6%    |
| 51-60          | 5         | 1.6%    |
| 131-140        | 3         | 0.96%   |
| 111-120        | 2         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 124       | 39.87%  |
| 121-160       | 70        | 22.51%  |
| 101-120       | 66        | 21.22%  |
| 161-240       | 25        | 8.04%   |
| Unknown       | 19        | 6.11%   |
| 1-50          | 4         | 1.29%   |
| More than 240 | 3         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 350       | 50.58%  |
| 1     | 319       | 46.1%   |
| 2     | 22        | 3.18%   |
| 3     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 351       | 37.7%   |
| Intel                             | 300       | 32.22%  |
| Qualcomm Atheros                  | 104       | 11.17%  |
| Broadcom                          | 45        | 4.83%   |
| Marvell Technology Group          | 21        | 2.26%   |
| TP-Link                           | 11        | 1.18%   |
| Huawei Technologies               | 8         | 0.86%   |
| D-Link System                     | 8         | 0.86%   |
| VIA Technologies                  | 7         | 0.75%   |
| Ralink Technology                 | 6         | 0.64%   |
| Samsung Electronics               | 5         | 0.54%   |
| Ralink                            | 5         | 0.54%   |
| MediaTek                          | 4         | 0.43%   |
| 3Com                              | 4         | 0.43%   |
| Xiaomi                            | 3         | 0.32%   |
| Nvidia                            | 3         | 0.32%   |
| IMC Networks                      | 3         | 0.32%   |
| D-Link                            | 3         | 0.32%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.21%   |
| Qualcomm Atheros Communications   | 2         | 0.21%   |
| Qualcomm                          | 2         | 0.21%   |
| QLogic                            | 2         | 0.21%   |
| Mercucys                          | 2         | 0.21%   |
| JMicron Technology                | 2         | 0.21%   |
| Fibocom                           | 2         | 0.21%   |
| Ericsson Business Mobile Networks | 2         | 0.21%   |
| ASUSTek Computer                  | 2         | 0.21%   |
| Arduino SA                        | 2         | 0.21%   |
| Sundance Technology Inc / IC Plus | 1         | 0.11%   |
| Shenzhen Goodix Technology        | 1         | 0.11%   |
| Realtek                           | 1         | 0.11%   |
| Qcom                              | 1         | 0.11%   |
| OPPO Electronics                  | 1         | 0.11%   |
| MYRICOM                           | 1         | 0.11%   |
| Mellanox Technologies             | 1         | 0.11%   |
| IBM                               | 1         | 0.11%   |
| Edimax Technology                 | 1         | 0.11%   |
| Dell                              | 1         | 0.11%   |
| BUFFALO                           | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 268       | 24.59%  |
| Intel 82574L Gigabit Network Connection                                | 28        | 2.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 22        | 2.02%   |
| Intel I211 Gigabit Network Connection                                  | 22        | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 21        | 1.93%   |
| Intel I350 Gigabit Network Connection                                  | 18        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 1.28%   |
| Intel 82576 Gigabit Network Connection                                 | 14        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 13        | 1.19%   |
| Intel Wireless 7265                                                    | 13        | 1.19%   |
| Intel Wi-Fi 6 AX200                                                    | 12        | 1.1%    |
| Intel Ethernet Controller I225-V                                       | 12        | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 1.01%   |
| Intel I210 Gigabit Network Connection                                  | 11        | 1.01%   |
| Intel Wireless 8265 / 8275                                             | 10        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 9         | 0.83%   |
| Intel Ethernet Controller I226-V                                       | 9         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 9         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 8         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 7         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 0.55%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 6         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.55%   |
| Intel Wireless 8260                                                    | 6         | 0.55%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 6         | 0.55%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 6         | 0.55%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.55%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 5         | 0.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.46%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 5         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 5         | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 5         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 131       | 40.81%  |
| Qualcomm Atheros                | 74        | 23.05%  |
| Realtek Semiconductor           | 56        | 17.45%  |
| Broadcom                        | 19        | 5.92%   |
| TP-Link                         | 11        | 3.43%   |
| Ralink Technology               | 6         | 1.87%   |
| Ralink                          | 5         | 1.56%   |
| MediaTek                        | 3         | 0.93%   |
| IMC Networks                    | 3         | 0.93%   |
| D-Link                          | 3         | 0.93%   |
| Qualcomm Atheros Communications | 2         | 0.62%   |
| Mercucys                        | 2         | 0.62%   |
| ASUSTek Computer                | 2         | 0.62%   |
| Qcom                            | 1         | 0.31%   |
| Edimax Technology               | 1         | 0.31%   |
| BUFFALO                         | 1         | 0.31%   |
| Atheros                         | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 21        | 6.42%   |
| Intel Wireless 7265                                                     | 13        | 3.98%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 3.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 3.36%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 2.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 2.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 2.14%   |
| Intel Wireless 8260                                                     | 6         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.53%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1.53%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 1.53%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 4         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 4         | 1.22%   |
| Intel Wireless 3165                                                     | 4         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.92%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.92%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.92%   |
| Intel Wireless 7260                                                     | 3         | 0.92%   |
| Intel WiFi Link 5100                                                    | 3         | 0.92%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 3         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.92%   |
| Intel CNVi: Wi-Fi                                                       | 3         | 0.92%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 329       | 48.45%  |
| Intel                             | 209       | 30.78%  |
| Qualcomm Atheros                  | 40        | 5.89%   |
| Broadcom                          | 28        | 4.12%   |
| Marvell Technology Group          | 21        | 3.09%   |
| D-Link System                     | 8         | 1.18%   |
| VIA Technologies                  | 7         | 1.03%   |
| Samsung Electronics               | 5         | 0.74%   |
| 3Com                              | 4         | 0.59%   |
| Xiaomi                            | 3         | 0.44%   |
| Nvidia                            | 3         | 0.44%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.29%   |
| Qualcomm                          | 2         | 0.29%   |
| QLogic                            | 2         | 0.29%   |
| JMicron Technology                | 2         | 0.29%   |
| Huawei Technologies               | 2         | 0.29%   |
| Sundance Technology Inc / IC Plus | 1         | 0.15%   |
| Realtek                           | 1         | 0.15%   |
| OPPO Electronics                  | 1         | 0.15%   |
| MYRICOM                           | 1         | 0.15%   |
| MediaTek                          | 1         | 0.15%   |
| Attansic                          | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |
| Apple                             | 1         | 0.15%   |
| AMD                               | 1         | 0.15%   |
| Accton Technology                 | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 268       | 36.22%  |
| Intel 82574L Gigabit Network Connection                                       | 28        | 3.78%   |
| Realtek RTL8125 2.5GbE Controller                                             | 23        | 3.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 22        | 2.97%   |
| Intel I211 Gigabit Network Connection                                         | 22        | 2.97%   |
| Intel I350 Gigabit Network Connection                                         | 18        | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 14        | 1.89%   |
| Intel 82576 Gigabit Network Connection                                        | 14        | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 13        | 1.76%   |
| Intel Ethernet Controller I225-V                                              | 12        | 1.62%   |
| Intel I210 Gigabit Network Connection                                         | 11        | 1.49%   |
| Intel Ethernet Controller I226-V                                              | 9         | 1.22%   |
| Intel Ethernet Connection (2) I219-V                                          | 8         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 7         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 6         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 6         | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 6         | 0.81%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                          | 6         | 0.81%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 6         | 0.81%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6         | 0.81%   |
| Intel 82579V Gigabit Network Connection                                       | 6         | 0.81%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 5         | 0.68%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5         | 0.68%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 5         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                          | 5         | 0.68%   |
| Intel 82583V Gigabit Network Connection                                       | 5         | 0.68%   |
| Intel 82575EB Gigabit Network Connection                                      | 5         | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 4         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4         | 0.54%   |
| Intel Ethernet Connection I217-V                                              | 4         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 0.54%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 4         | 0.54%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4         | 0.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4         | 0.54%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 4         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 3         | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 3         | 0.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3         | 0.41%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 603       | 65.76%  |
| WiFi     | 291       | 31.73%  |
| Unknown  | 14        | 1.53%   |
| Modem    | 9         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 494       | 75.77%  |
| WiFi     | 155       | 23.77%  |
| Unknown  | 3         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 268       | 39.3%   |
| 1     | 245       | 35.92%  |
| 3     | 56        | 8.21%   |
| 0     | 49        | 7.18%   |
| 4     | 34        | 4.99%   |
| 6     | 15        | 2.2%    |
| 5     | 6         | 0.88%   |
| 8     | 3         | 0.44%   |
| 7     | 3         | 0.44%   |
| 9     | 2         | 0.29%   |
| 12    | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 656       | 96.33%  |
| Yes  | 25        | 3.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 48.76%  |
| Qualcomm Atheros Communications | 20        | 9.95%   |
| Realtek Semiconductor           | 18        | 8.96%   |
| IMC Networks                    | 12        | 5.97%   |
| Cambridge Silicon Radio         | 7         | 3.48%   |
| Broadcom                        | 7         | 3.48%   |
| ASUSTek Computer                | 7         | 3.48%   |
| Apple                           | 7         | 3.48%   |
| Foxconn / Hon Hai               | 5         | 2.49%   |
| Lite-On Technology              | 4         | 1.99%   |
| Skylight Digital                | 3         | 1.49%   |
| Alps Electric                   | 3         | 1.49%   |
| Ralink                          | 2         | 1%      |
| Hewlett-Packard                 | 2         | 1%      |
| TP-Link                         | 1         | 0.5%    |
| Taiyo Yuden                     | 1         | 0.5%    |
| Silicon Wave                    | 1         | 0.5%    |
| Opticis                         | 1         | 0.5%    |
| Edimax Technology               | 1         | 0.5%    |
| Dell                            | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 35        | 17.33%  |
| Intel AX201 Bluetooth                                       | 16        | 7.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 14        | 6.93%   |
| Intel AX200 Bluetooth                                       | 13        | 6.44%   |
| Realtek Bluetooth Adapter                                   | 9         | 4.46%   |
| Intel Wireless-AC 3168 Bluetooth                            | 9         | 4.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 7         | 3.47%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 2.48%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 2.48%   |
| Intel AX210 Bluetooth                                       | 5         | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 1.98%   |
| Skylight Digital Realtek Bluetooth Adapter                  | 3         | 1.49%   |
| Realtek RTL8723B Bluetooth                                  | 3         | 1.49%   |
| Lite-On Atheros AR3012 Bluetooth                            | 3         | 1.49%   |
| IMC Networks Realtek Bluetooth Adapter                      | 3         | 1.49%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 3         | 1.49%   |
| Apple Bluetooth Host Controller                             | 3         | 1.49%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.99%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 2         | 0.99%   |
| Ralink RT3290 Bluetooth                                     | 2         | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 0.99%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 2         | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 0.99%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 0.99%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2         | 0.99%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 0.99%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 0.99%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 1         | 0.5%    |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                     | 1         | 0.5%    |
| Silicon Wave Bluetooth Wireless Adapter                     | 1         | 0.5%    |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.5%    |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.5%    |
| Qualcomm Atheros QCA9565 Bluetooth 4.0 + HS Adapter         | 1         | 0.5%    |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.5%    |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 398       | 56.53%  |
| AMD                                          | 143       | 20.31%  |
| Nvidia                                       | 105       | 14.91%  |
| C-Media Electronics                          | 6         | 0.85%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.57%   |
| VIA Technologies                             | 4         | 0.57%   |
| Texas Instruments                            | 4         | 0.57%   |
| Realtek Semiconductor                        | 4         | 0.57%   |
| JMTek                                        | 4         | 0.57%   |
| Creative Technology                          | 4         | 0.57%   |
| Logitech                                     | 3         | 0.43%   |
| Lenovo                                       | 3         | 0.43%   |
| Creative Labs                                | 3         | 0.43%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.28%   |
| Samsung Electronics                          | 2         | 0.28%   |
| Generalplus Technology                       | 2         | 0.28%   |
| ESS Technology                               | 2         | 0.28%   |
| Xilinx                                       | 1         | 0.14%   |
| SteelSeries ApS                              | 1         | 0.14%   |
| Microsoft                                    | 1         | 0.14%   |
| M-Audio                                      | 1         | 0.14%   |
| KTMicro                                      | 1         | 0.14%   |
| HECATE G2 GAMING HEADSET                     | 1         | 0.14%   |
| GN Netcom                                    | 1         | 0.14%   |
| FiiO Electronics Technology                  | 1         | 0.14%   |
| Edifier Technology                           | 1         | 0.14%   |
| Cambridge Silicon Radio                      | 1         | 0.14%   |
| Unknown                                      | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 46        | 5.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 34        | 4.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 32        | 3.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 3.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 2.33%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 19        | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 18        | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 16        | 1.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 15        | 1.84%   |
| AMD FCH Azalia Controller                                                                         | 14        | 1.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 13        | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.6%    |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.47%   |
| Intel Jasper Lake HD Audio                                                                        | 11        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 11        | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 10        | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 1.11%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.98%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 0.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.74%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 6         | 0.74%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 119       | 18.14%  |
| Kingston                                | 112       | 17.07%  |
| Samsung Electronics                     | 105       | 16.01%  |
| SK hynix                                | 65        | 9.91%   |
| Micron Technology                       | 44        | 6.71%   |
| Crucial                                 | 33        | 5.03%   |
| Unknown                                 | 33        | 5.03%   |
| Patriot                                 | 13        | 1.98%   |
| AMD                                     | 13        | 1.98%   |
| Corsair                                 | 12        | 1.83%   |
| A-DATA Technology                       | 12        | 1.83%   |
| Transcend                               | 7         | 1.07%   |
| Ramaxel Technology                      | 7         | 1.07%   |
| G.Skill                                 | 7         | 1.07%   |
| Elpida                                  | 7         | 1.07%   |
| Apacer                                  | 6         | 0.91%   |
| Unknown (ABCD)                          | 5         | 0.76%   |
| Patriot Memory (PDP Systems)            | 5         | 0.76%   |
| Nanya Technology                        | 5         | 0.76%   |
| Atermiter                               | 5         | 0.76%   |
| Hewlett-Packard                         | 3         | 0.46%   |
| Goldkey                                 | 3         | 0.46%   |
| 48spaces                                | 3         | 0.46%   |
| Unifosa                                 | 2         | 0.3%    |
| Silicon Power Computer & Communications | 2         | 0.3%    |
| Silicon Power                           | 2         | 0.3%    |
| Qumo                                    | 2         | 0.3%    |
| NOT SUPPORT                             | 2         | 0.3%    |
| Netac                                   | 2         | 0.3%    |
| Kllisre                                 | 2         | 0.3%    |
| Kingmax                                 | 2         | 0.3%    |
| GOODRAM                                 | 2         | 0.3%    |
| Unknown (0x0DD5)                        | 1         | 0.15%   |
| Unknown (0x0809)                        | 1         | 0.15%   |
| Unknown (0x0191)                        | 1         | 0.15%   |
| Tigo                                    | 1         | 0.15%   |
| TBD                                     | 1         | 0.15%   |
| S                                       | 1         | 0.15%   |
| Rayson                                  | 1         | 0.15%   |
| Ramos Technology                        | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 33        | 4.53%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                      | 9         | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 7         | 0.96%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                      | 6         | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                                         | 5         | 0.69%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 5         | 0.69%   |
| Unknown RAM Module 1GB DIMM SDRAM                                         | 5         | 0.69%   |
| Unknown RAM Module 512MB DIMM SDRAM                                       | 4         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 4         | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                               | 4         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s              | 4         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                     | 4         | 0.55%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                      | 3         | 0.41%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 3         | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                                 | 3         | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                  | 3         | 0.41%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                       | 3         | 0.41%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 3         | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                    | 3         | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 0.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 3         | 0.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 3         | 0.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 3         | 0.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 3         | 0.41%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                       | 3         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 3         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s                | 3         | 0.41%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                                 | 3         | 0.41%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                      | 3         | 0.41%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s                    | 3         | 0.41%   |
| G.Skill RAM F4-4000C18-32GVK 32GB DIMM DDR4 4000MT/s                      | 3         | 0.41%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                     | 3         | 0.41%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                               | 3         | 0.41%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                               | 3         | 0.41%   |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 800MT/s | 3         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 2         | 0.27%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                                   | 2         | 0.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                                 | 2         | 0.27%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                                 | 2         | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 224       | 38.62%  |
| DDR3    | 193       | 33.28%  |
| DDR2    | 49        | 8.45%   |
| Unknown | 45        | 7.76%   |
| SDRAM   | 24        | 4.14%   |
| DDR     | 15        | 2.59%   |
| LPDDR4  | 9         | 1.55%   |
| LPDDR3  | 7         | 1.21%   |
| LPDDR5  | 6         | 1.03%   |
| DDR5    | 4         | 0.69%   |
| DRAM    | 3         | 0.52%   |
| RAM     | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 336       | 58.13%  |
| SODIMM       | 222       | 38.41%  |
| Row Of Chips | 14        | 2.42%   |
| Chip         | 4         | 0.69%   |
| FB-DIMM      | 1         | 0.17%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 185       | 28.91%  |
| 4096  | 164       | 25.63%  |
| 2048  | 121       | 18.91%  |
| 16384 | 76        | 11.88%  |
| 1024  | 45        | 7.03%   |
| 32768 | 24        | 3.75%   |
| 512   | 17        | 2.66%   |
| 256   | 3         | 0.47%   |
| 65536 | 1         | 0.16%   |
| 3072  | 1         | 0.16%   |
| 2560  | 1         | 0.16%   |
| 128   | 1         | 0.16%   |
| 8     | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 105       | 17.27%  |
| 1333    | 83        | 13.65%  |
| 3200    | 80        | 13.16%  |
| 2400    | 68        | 11.18%  |
| 2667    | 53        | 8.72%   |
| 800     | 35        | 5.76%   |
| Unknown | 35        | 5.76%   |
| 667     | 29        | 4.77%   |
| 2133    | 23        | 3.78%   |
| 1067    | 12        | 1.97%   |
| 1066    | 9         | 1.48%   |
| 400     | 9         | 1.48%   |
| 1867    | 8         | 1.32%   |
| 6400    | 6         | 0.99%   |
| 1866    | 5         | 0.82%   |
| 2933    | 4         | 0.66%   |
| 2666    | 4         | 0.66%   |
| 1334    | 4         | 0.66%   |
| 4800    | 3         | 0.49%   |
| 4000    | 3         | 0.49%   |
| 3600    | 3         | 0.49%   |
| 3400    | 3         | 0.49%   |
| 3000    | 3         | 0.49%   |
| 2048    | 3         | 0.49%   |
| 533     | 3         | 0.49%   |
| 266     | 3         | 0.49%   |
| 1332    | 2         | 0.33%   |
| 5600    | 1         | 0.16%   |
| 4267    | 1         | 0.16%   |
| 3733    | 1         | 0.16%   |
| 1639    | 1         | 0.16%   |
| 1400    | 1         | 0.16%   |
| 975     | 1         | 0.16%   |
| 933     | 1         | 0.16%   |
| 333     | 1         | 0.16%   |
| 133     | 1         | 0.16%   |
| 100     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 25%     |
| Kyocera            | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1         | 25%     |
| Kyocera FS-1025MFP                    | 1         | 25%     |
| HP Laser 107a Printer                 | 1         | 25%     |
| Brother HL-2030 Laser Printer         | 1         | 25%     |

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
| Chicony Electronics                    | 36        | 21.05%  |
| IMC Networks                           | 20        | 11.7%   |
| Microdia                               | 18        | 10.53%  |
| Realtek Semiconductor                  | 14        | 8.19%   |
| Bison Electronics                      | 10        | 5.85%   |
| Silicon Motion                         | 6         | 3.51%   |
| Quanta                                 | 6         | 3.51%   |
| Suyin                                  | 5         | 2.92%   |
| Sunplus Innovation Technology          | 5         | 2.92%   |
| Lite-On Technology                     | 5         | 2.92%   |
| Syntek                                 | 4         | 2.34%   |
| Logitech                               | 4         | 2.34%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.34%   |
| ALi                                    | 4         | 2.34%   |
| Z-Star Microelectronics                | 3         | 1.75%   |
| Luxvisions Innotech Limited            | 3         | 1.75%   |
| Jiangxi Shinetech Optical              | 3         | 1.75%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 1.17%   |
| Ricoh                                  | 2         | 1.17%   |
| Lenovo                                 | 2         | 1.17%   |
| DigiTech                               | 2         | 1.17%   |
| Arkmicro Technologies                  | 2         | 1.17%   |
| Y Media                                | 1         | 0.58%   |
| Supreme Electronics                    | 1         | 0.58%   |
| Pixart Imaging                         | 1         | 0.58%   |
| Intel                                  | 1         | 0.58%   |
| Huawei Technologies                    | 1         | 0.58%   |
| Genesys Logic                          | 1         | 0.58%   |
| GEMBIRD                                | 1         | 0.58%   |
| Denron                                 | 1         | 0.58%   |
| Aveo Technology                        | 1         | 0.58%   |
| Apple                                  | 1         | 0.58%   |
| A4Tech                                 | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 12        | 6.94%   |
| Microdia Integrated_Webcam_HD                 | 7         | 4.05%   |
| IMC Networks Integrated Camera                | 6         | 3.47%   |
| Silicon Motion WebCam SCX Series              | 4         | 2.31%   |
| IMC Networks EasyCamera                       | 4         | 2.31%   |
| Realtek USB 2.0 PC Camera                     | 3         | 1.73%   |
| Realtek Acer 640 x 480 laptop camera          | 3         | 1.73%   |
| Quanta VGA WebCam                             | 3         | 1.73%   |
| Microdia USB Camera                           | 3         | 1.73%   |
| Bison Lenovo EasyCamera                       | 3         | 1.73%   |
| ALi Gateway Webcam                            | 3         | 1.73%   |
| Syntek EasyCamera                             | 2         | 1.16%   |
| Sunplus Hy HD Camera                          | 2         | 1.16%   |
| Realtek Integrated Webcam                     | 2         | 1.16%   |
| Quanta Realtek PC Camera                      | 2         | 1.16%   |
| Microdia Webcam Vitade AF                     | 2         | 1.16%   |
| Microdia Integrated Webcam                    | 2         | 1.16%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.16%   |
| Logitech Webcam C270                          | 2         | 1.16%   |
| Lite-On Integrated Camera                     | 2         | 1.16%   |
| Lite-On HP HD Camera                          | 2         | 1.16%   |
| Jiangxi Shinetech Optical HD Camera           | 2         | 1.16%   |
| IMC Networks UVC VGA Webcam                   | 2         | 1.16%   |
| IMC Networks Realtek DMFT RGB                 | 2         | 1.16%   |
| DigiTech WebCam SCB-0350M                     | 2         | 1.16%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 2         | 1.16%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 1.16%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.16%   |
| Chicony EasyCamera                            | 2         | 1.16%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 2         | 1.16%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.16%   |
| Bison Lenovo Integrated Webcam                | 2         | 1.16%   |
| Bison Integrated Camera                       | 2         | 1.16%   |
| Z-Star Webcam                                 | 1         | 0.58%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 0.58%   |
| Z-Star Integrated Camera                      | 1         | 0.58%   |
| Y Media USB Camera                            | 1         | 0.58%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.58%   |
| Syntek Integrated Camera                      | 1         | 0.58%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 26.67%  |
| Validity Sensors           | 11        | 24.44%  |
| FocalTech Systems          | 5         | 11.11%  |
| AuthenTec                  | 5         | 11.11%  |
| STMicroelectronics         | 4         | 8.89%   |
| Upek                       | 3         | 6.67%   |
| Shenzhen Goodix Technology | 3         | 6.67%   |
| Elan Microelectronics      | 1         | 2.22%   |
| Broadcom                   | 1         | 2.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 7         | 15.56%  |
| FocalTech Systems Fingerprint Reader                                         | 5         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                        | 4         | 8.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 3         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                                          | 3         | 6.67%   |
| AuthenTec AES1600                                                            | 3         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 2         | 4.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 4.44%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 2         | 4.44%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 2.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 1         | 2.22%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                     | 1         | 2.22%   |
| Elan Fingerprint Sensor                                                      | 1         | 2.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.22%   |
| AuthenTec AES2810                                                            | 1         | 2.22%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 2.22%   |

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
| 0     | 263       | 37.46%  |
| 1     | 262       | 37.32%  |
| 2     | 107       | 15.24%  |
| 3     | 39        | 5.56%   |
| 4     | 23        | 3.28%   |
| 5     | 3         | 0.43%   |
| 7     | 2         | 0.28%   |
| 9     | 1         | 0.14%   |
| 8     | 1         | 0.14%   |
| 6     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 301       | 47.78%  |
| Net/wireless             | 82        | 13.02%  |
| Bluetooth                | 60        | 9.52%   |
| Card reader              | 43        | 6.83%   |
| Fingerprint reader       | 37        | 5.87%   |
| Sound                    | 29        | 4.6%    |
| Firewire controller      | 28        | 4.44%   |
| Graphics card            | 15        | 2.38%   |
| Network                  | 11        | 1.75%   |
| Net/ethernet             | 8         | 1.27%   |
| Storage/ata              | 6         | 0.95%   |
| Storage                  | 6         | 0.95%   |
| Modem                    | 4         | 0.63%   |

