BSD in Russia - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for BSD in Russia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 641

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Techvision    | TVI7309X B0                 | [d4bdab4711](https://bsd-hardware.info/?probe=d4bdab4711) | Feb 10, 2024 |
| HP            | 339A                        | [5d1b482427](https://bsd-hardware.info/?probe=5d1b482427) | Feb 10, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | [47e91ddd92](https://bsd-hardware.info/?probe=47e91ddd92) | Feb 08, 2024 |
| Unknown       | Unknown                     | [05745ae76a](https://bsd-hardware.info/?probe=05745ae76a) | Feb 04, 2024 |
| Foxconn       | 2ABF                        | [d145d7a650](https://bsd-hardware.info/?probe=d145d7a650) | Feb 01, 2024 |
| ASUSTek       | P5E3 PRO                    | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| Unknown       | Unknown                     | [80f34deedc](https://bsd-hardware.info/?probe=80f34deedc) | Jan 29, 2024 |
| Unknown       | Unknown                     | [18168c211d](https://bsd-hardware.info/?probe=18168c211d) | Jan 29, 2024 |
| Unknown       | Unknown                     | [754c764123](https://bsd-hardware.info/?probe=754c764123) | Jan 29, 2024 |
| ASRock        | H310CM-HDV/M.2              | [4f45811a17](https://bsd-hardware.info/?probe=4f45811a17) | Jan 27, 2024 |
| Unknown       | Q-790                       | [ec71672aed](https://bsd-hardware.info/?probe=ec71672aed) | Jan 25, 2024 |
| Gigabyte      | GA-970A-D3                  | [6aeb253575](https://bsd-hardware.info/?probe=6aeb253575) | Jan 25, 2024 |
| Unknown       | Q-790                       | [b94e9febe7](https://bsd-hardware.info/?probe=b94e9febe7) | Jan 24, 2024 |
| AMI           | PEISIA E3845 VER1.0         | [2448066e32](https://bsd-hardware.info/?probe=2448066e32) | Jan 23, 2024 |
| HP            | 339A                        | [c61c3c0b1b](https://bsd-hardware.info/?probe=c61c3c0b1b) | Jan 23, 2024 |
| Gigabyte      | GA-970A-D3                  | [838906ef1b](https://bsd-hardware.info/?probe=838906ef1b) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [e2053919c4](https://bsd-hardware.info/?probe=e2053919c4) | Jan 15, 2024 |
| Intel         | D410PT AAE76528-404         | [87da69a1ef](https://bsd-hardware.info/?probe=87da69a1ef) | Jan 10, 2024 |
| HP            | 3641h                       | [90626880cf](https://bsd-hardware.info/?probe=90626880cf) | Jan 09, 2024 |
| Unknown       | Unknown                     | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Huanan        | X99-F8 V2.0                 | [04c19f755d](https://bsd-hardware.info/?probe=04c19f755d) | Jan 03, 2024 |
| Unknown       | Unknown                     | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown       | Unknown                     | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Supermicro    | X10DRi-T                    | [0001356297](https://bsd-hardware.info/?probe=0001356297) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | [1f28c229cb](https://bsd-hardware.info/?probe=1f28c229cb) | Dec 27, 2023 |
| Techvision    | TVI7309X B0                 | [d4f5a9c35a](https://bsd-hardware.info/?probe=d4f5a9c35a) | Dec 27, 2023 |
| Unknown       | Unknown                     | [84a9704b97](https://bsd-hardware.info/?probe=84a9704b97) | Dec 21, 2023 |
| ASUSTek       | P5B-VM                      | [00e7a346b2](https://bsd-hardware.info/?probe=00e7a346b2) | Dec 19, 2023 |
| Gigabyte      | H61M-S2PV                   | [88d2ae1175](https://bsd-hardware.info/?probe=88d2ae1175) | Dec 14, 2023 |
| Supermicro    | X7SBi                       | [a0124f00ba](https://bsd-hardware.info/?probe=a0124f00ba) | Dec 13, 2023 |
| Unknown       | Unknown                     | [123088175c](https://bsd-hardware.info/?probe=123088175c) | Dec 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [1034c9883a](https://bsd-hardware.info/?probe=1034c9883a) | Dec 06, 2023 |
| ASUSTek       | H81M-C                      | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | 3129 SDK0J40679 WIN 3273... | [da81c9605d](https://bsd-hardware.info/?probe=da81c9605d) | Dec 01, 2023 |
| Intel         | Geminilake                  | [0b0a4f8d68](https://bsd-hardware.info/?probe=0b0a4f8d68) | Nov 30, 2023 |
| MSI           | B350 PC MATE                | [87351f500b](https://bsd-hardware.info/?probe=87351f500b) | Nov 26, 2023 |
| MSI           | PRO H610M-B DDR4            | [c6ff092502](https://bsd-hardware.info/?probe=c6ff092502) | Nov 26, 2023 |
| Unknown       | Unknown                     | [ce88332d94](https://bsd-hardware.info/?probe=ce88332d94) | Nov 25, 2023 |
| HP            | 339A                        | [fdc6ee7b57](https://bsd-hardware.info/?probe=fdc6ee7b57) | Nov 22, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Unknown       | Unknown                     | [626ff9ba56](https://bsd-hardware.info/?probe=626ff9ba56) | Nov 13, 2023 |
| Unknown       | Unknown                     | [c535fae89f](https://bsd-hardware.info/?probe=c535fae89f) | Nov 10, 2023 |
| Techvision    | TVI7309X B0                 | [227e21dfdf](https://bsd-hardware.info/?probe=227e21dfdf) | Nov 09, 2023 |
| Techvision    | TVI7309X B0                 | [3dafd6bd42](https://bsd-hardware.info/?probe=3dafd6bd42) | Nov 07, 2023 |
| Techvision    | TVI7309X B0                 | [40dffa3e21](https://bsd-hardware.info/?probe=40dffa3e21) | Nov 06, 2023 |
| Gigabyte      | B450M H                     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| Unknown       | Unknown                     | [1a63df656e](https://bsd-hardware.info/?probe=1a63df656e) | Oct 31, 2023 |
| Intel         | DCP847SKE                   | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| Intel         | DCP847SKE                   | [ba44d23972](https://bsd-hardware.info/?probe=ba44d23972) | Oct 29, 2023 |
| Unknown       | Unknown                     | [b688e6b635](https://bsd-hardware.info/?probe=b688e6b635) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Gigabyte      | H81M-S2PV                   | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| Unknown       | Unknown                     | [6b3f2cf24c](https://bsd-hardware.info/?probe=6b3f2cf24c) | Oct 25, 2023 |
| Unknown       | Unknown                     | [db96ffb93a](https://bsd-hardware.info/?probe=db96ffb93a) | Oct 25, 2023 |
| Unknown       | Unknown                     | [06f91445cb](https://bsd-hardware.info/?probe=06f91445cb) | Oct 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Unknown       | Unknown                     | [629eefe0c2](https://bsd-hardware.info/?probe=629eefe0c2) | Oct 21, 2023 |
| ASUSTek       | PRIME H470M-PLUS            | [88cdd6135f](https://bsd-hardware.info/?probe=88cdd6135f) | Oct 20, 2023 |
| MSI           | PRO H610M-B DDR4            | [1cc822b8c1](https://bsd-hardware.info/?probe=1cc822b8c1) | Oct 19, 2023 |
| Unknown       | Unknown                     | [0fd1a7196f](https://bsd-hardware.info/?probe=0fd1a7196f) | Oct 13, 2023 |
| Wistron       | ProLiant ML110 G6           | [d5676f7895](https://bsd-hardware.info/?probe=d5676f7895) | Oct 10, 2023 |
| TONK          | TN2800                      | [a47aba3406](https://bsd-hardware.info/?probe=a47aba3406) | Oct 10, 2023 |
| Gigabyte      | B550M DS3H                  | [66a1e081e6](https://bsd-hardware.info/?probe=66a1e081e6) | Oct 07, 2023 |
| Unknown       | Unknown                     | [9d236eb8bb](https://bsd-hardware.info/?probe=9d236eb8bb) | Oct 06, 2023 |
| Unknown       | Unknown                     | [9ad768a37a](https://bsd-hardware.info/?probe=9ad768a37a) | Oct 04, 2023 |
| Techvision    | TVI7309X B0                 | [9748abc90d](https://bsd-hardware.info/?probe=9748abc90d) | Oct 02, 2023 |
| TONK          | TN2800                      | [bce9c62915](https://bsd-hardware.info/?probe=bce9c62915) | Sep 29, 2023 |
| ASRock        | Z690 Phantom Gaming 4/D5    | [6eab8daef7](https://bsd-hardware.info/?probe=6eab8daef7) | Sep 21, 2023 |
| Apple         | MacPro4,1                   | [c368087050](https://bsd-hardware.info/?probe=c368087050) | Sep 20, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | [53d31a28bf](https://bsd-hardware.info/?probe=53d31a28bf) | Sep 14, 2023 |
| Gigabyte      | GA-870A-UD3                 | [095b8aa8fb](https://bsd-hardware.info/?probe=095b8aa8fb) | Sep 11, 2023 |
| Lenovo        | 3140 NOK                    | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| Unknown       | Unknown                     | [29578638c1](https://bsd-hardware.info/?probe=29578638c1) | Sep 08, 2023 |
| Intel         | HM570                       | [3112f263f5](https://bsd-hardware.info/?probe=3112f263f5) | Sep 07, 2023 |
| Intel         | HM570                       | [0e4bfa9794](https://bsd-hardware.info/?probe=0e4bfa9794) | Sep 07, 2023 |
| Gigabyte      | P35C-DS3R                   | [4424751223](https://bsd-hardware.info/?probe=4424751223) | Sep 04, 2023 |
| Shuttle       | DS20U                       | [d034a8e5b8](https://bsd-hardware.info/?probe=d034a8e5b8) | Sep 02, 2023 |
| VIA Techno... | VT8623-8235                 | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| MSI           | H110M PRO-VD                | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| Techvision    | TVI7309X B0                 | [ebb4e825a3](https://bsd-hardware.info/?probe=ebb4e825a3) | Aug 25, 2023 |
| ASUSTek       | P5M2-R                      | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| Gigabyte      | C1037UN-EU                  | [76945fc8cb](https://bsd-hardware.info/?probe=76945fc8cb) | Aug 22, 2023 |
| Unknown       | Unknown                     | [341152089f](https://bsd-hardware.info/?probe=341152089f) | Aug 21, 2023 |
| Unknown       | Unknown                     | [5ab27fdf53](https://bsd-hardware.info/?probe=5ab27fdf53) | Aug 21, 2023 |
| Shuttle       | DS20U                       | [5c511e0613](https://bsd-hardware.info/?probe=5c511e0613) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | A520M-A PRO                 | [cc946b2a89](https://bsd-hardware.info/?probe=cc946b2a89) | Aug 15, 2023 |
| ASUSTek       | P6X58D PREMIUM              | [946e123320](https://bsd-hardware.info/?probe=946e123320) | Aug 13, 2023 |
| Dell          | 0CNWVK A00                  | [fdb03dc15f](https://bsd-hardware.info/?probe=fdb03dc15f) | Aug 09, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [4fc1fbaba1](https://bsd-hardware.info/?probe=4fc1fbaba1) | Aug 09, 2023 |
| MSI           | MS-7623                     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| ASRock        | B550 PG Velocita            | [3ff5fcfbc0](https://bsd-hardware.info/?probe=3ff5fcfbc0) | Aug 02, 2023 |
| MSI           | G41M-P33 Combo              | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
| Techvision    | TVI7309X B0                 | [65599626a9](https://bsd-hardware.info/?probe=65599626a9) | Jul 23, 2023 |
| Unknown       | Q-790                       | [49f9861c7f](https://bsd-hardware.info/?probe=49f9861c7f) | Jul 17, 2023 |
| Unknown       | Unknown                     | [4a82a6a375](https://bsd-hardware.info/?probe=4a82a6a375) | Jul 17, 2023 |
| ECS           | H61H2-M17                   | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a322b1ee22](https://bsd-hardware.info/?probe=a322b1ee22) | Jul 13, 2023 |
| Unknown       | Q-790                       | [cc02bb60de](https://bsd-hardware.info/?probe=cc02bb60de) | Jul 13, 2023 |
| Radxa         | rock-pi-n10a                | [a9767501e2](https://bsd-hardware.info/?probe=a9767501e2) | Jul 12, 2023 |
| ASRock        | P67 Pro3 SE                 | [a7284068da](https://bsd-hardware.info/?probe=a7284068da) | Jul 12, 2023 |
| ASRock        | H61M-GS                     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| Foxconn       | 2ABF                        | [26e209d8e1](https://bsd-hardware.info/?probe=26e209d8e1) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | [a9ab5114e1](https://bsd-hardware.info/?probe=a9ab5114e1) | Jul 10, 2023 |
| ASRock        | Z690 PG Riptide             | [813e46e924](https://bsd-hardware.info/?probe=813e46e924) | Jul 10, 2023 |
| Unknown       | Unknown                     | [c930867e8e](https://bsd-hardware.info/?probe=c930867e8e) | Jul 07, 2023 |
| ASRock        | Z690 PG Riptide             | [364cf5800b](https://bsd-hardware.info/?probe=364cf5800b) | Jul 06, 2023 |
| HP            | 339A                        | [f80f7cc14c](https://bsd-hardware.info/?probe=f80f7cc14c) | Jul 05, 2023 |
| ASUSTek       | PRIME H510M-A               | [fd5fa70fb7](https://bsd-hardware.info/?probe=fd5fa70fb7) | Jul 03, 2023 |
| Gigabyte      | B360M D2V                   | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| Unknown       | Unknown                     | [c07f4ffa1e](https://bsd-hardware.info/?probe=c07f4ffa1e) | Jun 29, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| ASUSTek       | P7P55D LE                   | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Unknown       | Unknown                     | [f41e1f2b83](https://bsd-hardware.info/?probe=f41e1f2b83) | Jun 14, 2023 |
| Gigabyte      | B450M S2H                   | [2008116e96](https://bsd-hardware.info/?probe=2008116e96) | Jun 10, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [15a71633ec](https://bsd-hardware.info/?probe=15a71633ec) | Jun 08, 2023 |
| Gigabyte      | G41MT-S2                    | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| Supermicro    | X10DRi-T                    | [c72eaa89d7](https://bsd-hardware.info/?probe=c72eaa89d7) | May 31, 2023 |
| Unknown       | Unknown                     | [086747eef4](https://bsd-hardware.info/?probe=086747eef4) | May 29, 2023 |
| ASRockRack    | E3C242D4U                   | [ae8287e8fd](https://bsd-hardware.info/?probe=ae8287e8fd) | May 29, 2023 |
| ASUSTek       | PRIME H510M-K               | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| Gigabyte      | B360M D2V                   | [5960982eb3](https://bsd-hardware.info/?probe=5960982eb3) | May 25, 2023 |
| HP            | 0A60h                       | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| Dell          | 0CNWVK A00                  | [0d1e1a3ca4](https://bsd-hardware.info/?probe=0d1e1a3ca4) | May 16, 2023 |
| Acer          | Revo RN86                   | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown       | Unknown                     | [990b3eb510](https://bsd-hardware.info/?probe=990b3eb510) | May 12, 2023 |
| Gigabyte      | H77N-WIFI                   | [cf2014c973](https://bsd-hardware.info/?probe=cf2014c973) | May 04, 2023 |
| Supermicro    | X10DRi-T                    | [ba54a43cb4](https://bsd-hardware.info/?probe=ba54a43cb4) | May 03, 2023 |
| HP            | 82B4                        | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Unknown       | Unknown                     | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Unknown       | Unknown                     | [290fabd69d](https://bsd-hardware.info/?probe=290fabd69d) | Apr 26, 2023 |
| Gigabyte      | B360M D2V                   | [d4881f1fb6](https://bsd-hardware.info/?probe=d4881f1fb6) | Apr 25, 2023 |
| Dell          | 0CNWVK A00                  | [6642a4b35d](https://bsd-hardware.info/?probe=6642a4b35d) | Apr 18, 2023 |
| Gigabyte      | B360M D2V                   | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown       | Unknown                     | [926ab149ae](https://bsd-hardware.info/?probe=926ab149ae) | Apr 14, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [882a817f46](https://bsd-hardware.info/?probe=882a817f46) | Apr 13, 2023 |
| Unknown       | Unknown                     | [c960f2dc8b](https://bsd-hardware.info/?probe=c960f2dc8b) | Apr 12, 2023 |
| ASUSTek       | P10S-I Series               | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| PC Engines    | APU2                        | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Intel         | DG35EC AAE29266-205         | [821368d0f0](https://bsd-hardware.info/?probe=821368d0f0) | Apr 09, 2023 |
| HP            | 2820h                       | [e304f130aa](https://bsd-hardware.info/?probe=e304f130aa) | Apr 09, 2023 |
| HP            | 2820h                       | [ff9500303d](https://bsd-hardware.info/?probe=ff9500303d) | Apr 09, 2023 |
| Unknown       | Unknown                     | [f96c113329](https://bsd-hardware.info/?probe=f96c113329) | Apr 08, 2023 |
| Gigabyte      | B360M D2V                   | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Intel         | B75                         | [3a7eee851b](https://bsd-hardware.info/?probe=3a7eee851b) | Apr 03, 2023 |
| Unknown       | Unknown                     | [c801b9e5af](https://bsd-hardware.info/?probe=c801b9e5af) | Apr 03, 2023 |
| Unknown       | Unknown                     | [9b2420726f](https://bsd-hardware.info/?probe=9b2420726f) | Apr 03, 2023 |
| Unknown       | Unknown                     | [414cbf5935](https://bsd-hardware.info/?probe=414cbf5935) | Apr 03, 2023 |
| Unknown       | Unknown                     | [6b79c64c73](https://bsd-hardware.info/?probe=6b79c64c73) | Apr 03, 2023 |
| ASRock        | AB350M Pro4-F               | [424f3a2021](https://bsd-hardware.info/?probe=424f3a2021) | Apr 02, 2023 |
| ASRock        | X570S PG Riptide            | [8ccb321056](https://bsd-hardware.info/?probe=8ccb321056) | Apr 01, 2023 |
| Biostar       | TH67B                       | [234c5e0b83](https://bsd-hardware.info/?probe=234c5e0b83) | Mar 31, 2023 |
| ASRock        | X570S PG Riptide            | [0d66edbd38](https://bsd-hardware.info/?probe=0d66edbd38) | Mar 27, 2023 |
| Dell          | 0VD5HY A00                  | [1b54a68123](https://bsd-hardware.info/?probe=1b54a68123) | Mar 26, 2023 |
| MSI           | 870-G45                     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| MSI           | PRO H610M-B DDR4            | [ee01b690bc](https://bsd-hardware.info/?probe=ee01b690bc) | Mar 25, 2023 |
| MSI           | 870-G45                     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| Stonesoft     | DEV-1301-2-C1-R             | [3bc0fc5d63](https://bsd-hardware.info/?probe=3bc0fc5d63) | Mar 24, 2023 |
| Stonesoft     | DEV-1301-2-C1-R             | [2699b59d1b](https://bsd-hardware.info/?probe=2699b59d1b) | Mar 24, 2023 |
| Unknown       | T360D11                     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| Gigabyte      | F2A55-DS3                   | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| ASUSTek       | M5A78L-M LX3                | [3f78d8f1ae](https://bsd-hardware.info/?probe=3f78d8f1ae) | Mar 18, 2023 |
| Intel         | B75                         | [11bcf42a35](https://bsd-hardware.info/?probe=11bcf42a35) | Mar 18, 2023 |
| Unknown       | Unknown                     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| Intel         | DG35EC AAE29266-205         | [0ab42ce2ee](https://bsd-hardware.info/?probe=0ab42ce2ee) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Lenovo        | NO DPK                      | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| Gigabyte      | B365M H                     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Techvision    | TVI7309X B0                 | [f07e092146](https://bsd-hardware.info/?probe=f07e092146) | Mar 11, 2023 |
| MSI           | PRO H610M-B DDR4            | [b08fd92e36](https://bsd-hardware.info/?probe=b08fd92e36) | Mar 10, 2023 |
| MSI           | PRO H610M-B DDR4            | [654bdb4eb2](https://bsd-hardware.info/?probe=654bdb4eb2) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Elpitech      | ET101-A1                    | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |
| Huanan        | X99-QD4 V1.0                | [58090b9dbf](https://bsd-hardware.info/?probe=58090b9dbf) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [a2873d7c87](https://bsd-hardware.info/?probe=a2873d7c87) | Mar 09, 2023 |
| ASUSTek       | P7H55                       | [3c78171104](https://bsd-hardware.info/?probe=3c78171104) | Mar 04, 2023 |
| ASUSTek       | P7H55                       | [5ce8dbf5f3](https://bsd-hardware.info/?probe=5ce8dbf5f3) | Mar 04, 2023 |
| Huanan        | X99-QD4 V1.0                | [8404060d9e](https://bsd-hardware.info/?probe=8404060d9e) | Mar 02, 2023 |
| Unknown       | Unknown                     | [13ac9d6b7e](https://bsd-hardware.info/?probe=13ac9d6b7e) | Mar 01, 2023 |
| MSI           | PRO H610M-B DDR4            | [2072e8fac6](https://bsd-hardware.info/?probe=2072e8fac6) | Feb 28, 2023 |
| MSI           | PRO H610M-B DDR4            | [e85ed3f609](https://bsd-hardware.info/?probe=e85ed3f609) | Feb 27, 2023 |
| Unknown       | Unknown                     | [95c62844de](https://bsd-hardware.info/?probe=95c62844de) | Feb 25, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| MSI           | MS-92E3 0A                  | [683ff1f7d0](https://bsd-hardware.info/?probe=683ff1f7d0) | Feb 22, 2023 |
| Intel         | DN2820FYK H24582-203        | [dd0d96422f](https://bsd-hardware.info/?probe=dd0d96422f) | Feb 19, 2023 |
| ASRock        | G41M-GS3                    | [eace523f17](https://bsd-hardware.info/?probe=eace523f17) | Feb 18, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Huanan        | X99-QD4 V1.0                | [9a0c17560f](https://bsd-hardware.info/?probe=9a0c17560f) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [5507e05838](https://bsd-hardware.info/?probe=5507e05838) | Feb 12, 2023 |
| ASRock        | A770DE+                     | [cf1c018ede](https://bsd-hardware.info/?probe=cf1c018ede) | Feb 10, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| Intel         | DN2820FYK H24582-203        | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Unknown       | Unknown                     | [7fcfb747a7](https://bsd-hardware.info/?probe=7fcfb747a7) | Feb 06, 2023 |
| Techvision    | TVI7309X B0                 | [222da5a477](https://bsd-hardware.info/?probe=222da5a477) | Feb 04, 2023 |
| Techvision    | TVI7309X B0                 | [a58d9501ad](https://bsd-hardware.info/?probe=a58d9501ad) | Jan 31, 2023 |
| MACHINIST     | X99-K9 V2.0                 | [eb8a6cb004](https://bsd-hardware.info/?probe=eb8a6cb004) | Jan 30, 2023 |
| ChangWang     | CW56-58                     | [2d48772c23](https://bsd-hardware.info/?probe=2d48772c23) | Jan 27, 2023 |
| Citrix        | CB-1100                     | [36199a59e2](https://bsd-hardware.info/?probe=36199a59e2) | Jan 26, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| ChangWang     | CW56-58                     | [89ec5e42ef](https://bsd-hardware.info/?probe=89ec5e42ef) | Jan 26, 2023 |
| Gigabyte      | B360M D2V                   | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | [a712c2d054](https://bsd-hardware.info/?probe=a712c2d054) | Jan 26, 2023 |
| Gigabyte      | H61M-S2PV                   | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| ASUSTek       | P5G41T-M LX3                | [7b2fee315d](https://bsd-hardware.info/?probe=7b2fee315d) | Jan 26, 2023 |
| Shuttle       | DS20U                       | [71033e4a64](https://bsd-hardware.info/?probe=71033e4a64) | Jan 26, 2023 |
| Dell          | 0HY9JP A02                  | [ca71c8ab2b](https://bsd-hardware.info/?probe=ca71c8ab2b) | Jan 25, 2023 |
| Dell          | 0CNWVK A00                  | [e59d4ab226](https://bsd-hardware.info/?probe=e59d4ab226) | Jan 25, 2023 |
| ASUSTek       | P7P55D LE                   | [5da1e71837](https://bsd-hardware.info/?probe=5da1e71837) | Jan 25, 2023 |
| ASRock        | Z390 Pro4                   | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| AZW           | U59                         | [1f97b27470](https://bsd-hardware.info/?probe=1f97b27470) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Unknown       | Unknown                     | [8956f4503e](https://bsd-hardware.info/?probe=8956f4503e) | Jan 21, 2023 |
| Unknown       | AMD-GX3                     | [a38ff8331a](https://bsd-hardware.info/?probe=a38ff8331a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [3afbfc6cea](https://bsd-hardware.info/?probe=3afbfc6cea) | Jan 20, 2023 |
| Unknown       | YL-SKUL6                    | [ef4abfe322](https://bsd-hardware.info/?probe=ef4abfe322) | Jan 20, 2023 |
| Unknown       | Unknown                     | [e13627df1a](https://bsd-hardware.info/?probe=e13627df1a) | Jan 20, 2023 |
| Unknown       | Unknown                     | [8c44d6309f](https://bsd-hardware.info/?probe=8c44d6309f) | Jan 15, 2023 |
| ASUSTek       | PRIME Z390-P                | [3126dc27f1](https://bsd-hardware.info/?probe=3126dc27f1) | Jan 12, 2023 |
| ASUSTek       | H81M-E                      | [1008903f65](https://bsd-hardware.info/?probe=1008903f65) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | [2293d4960d](https://bsd-hardware.info/?probe=2293d4960d) | Jan 11, 2023 |
| Citrix        | CB-1100                     | [860f27ce64](https://bsd-hardware.info/?probe=860f27ce64) | Jan 11, 2023 |
| Techvision    | TVI7309X B0                 | [19f4631b5a](https://bsd-hardware.info/?probe=19f4631b5a) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| MSI           | PRO H610M-B DDR4            | [cc9d84d5ed](https://bsd-hardware.info/?probe=cc9d84d5ed) | Jan 05, 2023 |
| Unknown       | Unknown                     | [ea01217f17](https://bsd-hardware.info/?probe=ea01217f17) | Jan 02, 2023 |
| Gigabyte      | C1037UN-EU                  | [9c526b27dd](https://bsd-hardware.info/?probe=9c526b27dd) | Jan 02, 2023 |
| Shuttle       | DS20U                       | [a5aa09e49f](https://bsd-hardware.info/?probe=a5aa09e49f) | Jan 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| Unknown       | Unknown                     | [d702dfcde2](https://bsd-hardware.info/?probe=d702dfcde2) | Dec 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Unknown       | Unknown                     | [7c644cc639](https://bsd-hardware.info/?probe=7c644cc639) | Dec 15, 2022 |
| Unknown       | Unknown                     | [9b5307f44d](https://bsd-hardware.info/?probe=9b5307f44d) | Dec 15, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| ASUSTek       | P8H77-V LE                  | [10b6c81bce](https://bsd-hardware.info/?probe=10b6c81bce) | Dec 09, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0CNWVK A00                  | [5a022db6bf](https://bsd-hardware.info/?probe=5a022db6bf) | Dec 05, 2022 |
| Intel         | X99                         | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| MSI           | PRO H610M-B DDR4            | [929e4bda1e](https://bsd-hardware.info/?probe=929e4bda1e) | Nov 29, 2022 |
| MSI           | PRO H610M-B DDR4            | [7c9ee800c5](https://bsd-hardware.info/?probe=7c9ee800c5) | Nov 29, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Acer          | Revo RN86                   | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Gigabyte      | H81M-HD3                    | [564cf3d66a](https://bsd-hardware.info/?probe=564cf3d66a) | Nov 22, 2022 |
| Unknown       | Unknown                     | [0760ed34c3](https://bsd-hardware.info/?probe=0760ed34c3) | Nov 21, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Acer          | RS880M05                    | [455f9b5026](https://bsd-hardware.info/?probe=455f9b5026) | Nov 07, 2022 |
| ASUSTek       | Z170-K                      | [907b8c2402](https://bsd-hardware.info/?probe=907b8c2402) | Nov 05, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 339A                        | [370d93ecde](https://bsd-hardware.info/?probe=370d93ecde) | Nov 02, 2022 |
| Gigabyte      | Z68XP-UD3                   | [0f22defdb3](https://bsd-hardware.info/?probe=0f22defdb3) | Oct 30, 2022 |
| Unknown       | Unknown                     | [acf41f7000](https://bsd-hardware.info/?probe=acf41f7000) | Oct 29, 2022 |
| PC Engines    | APU2                        | [d52e3d0ce3](https://bsd-hardware.info/?probe=d52e3d0ce3) | Oct 25, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [d7b32200a5](https://bsd-hardware.info/?probe=d7b32200a5) | Oct 22, 2022 |
| Acer          | Revo RN86                   | [692ea69bab](https://bsd-hardware.info/?probe=692ea69bab) | Oct 21, 2022 |
| PC Engines    | APU2                        | [cf1abf5e46](https://bsd-hardware.info/?probe=cf1abf5e46) | Oct 21, 2022 |
| Unknown       | Unknown                     | [d5586487b4](https://bsd-hardware.info/?probe=d5586487b4) | Oct 21, 2022 |
| ASUSTek       | P10S-I Series               | [ceb58e75b8](https://bsd-hardware.info/?probe=ceb58e75b8) | Oct 20, 2022 |
| Supermicro    | X11SSL-F                    | [24faa4663c](https://bsd-hardware.info/?probe=24faa4663c) | Oct 19, 2022 |
| ASUSTek       | N3050I-C                    | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| Gigabyte      | C1037UN-EU                  | [734ff7f48c](https://bsd-hardware.info/?probe=734ff7f48c) | Oct 02, 2022 |
| ASRock        | X570M Pro4                  | [433857f5f7](https://bsd-hardware.info/?probe=433857f5f7) | Sep 27, 2022 |
| YANYU         | H67SL                       | [5f5819ef11](https://bsd-hardware.info/?probe=5f5819ef11) | Sep 24, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| YANYU         | H67SL                       | [37ba00c2f3](https://bsd-hardware.info/?probe=37ba00c2f3) | Sep 15, 2022 |
| Maxtang       | BYT30                       | [90053990c3](https://bsd-hardware.info/?probe=90053990c3) | Sep 10, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [98dff45d54](https://bsd-hardware.info/?probe=98dff45d54) | Sep 09, 2022 |
| Dell          | 0Y7WYT A00                  | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Maxtang       | BYT30                       | [f5c34c7662](https://bsd-hardware.info/?probe=f5c34c7662) | Sep 03, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Gigabyte      | C1037UN-EU                  | [0a867d7017](https://bsd-hardware.info/?probe=0a867d7017) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | [a2fc8d9c67](https://bsd-hardware.info/?probe=a2fc8d9c67) | Aug 18, 2022 |
| Gigabyte      | H61M-DS2                    | [9a7d45e51c](https://bsd-hardware.info/?probe=9a7d45e51c) | Aug 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [4055810ef2](https://bsd-hardware.info/?probe=4055810ef2) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Unknown       | Unknown                     | [467bcd3c04](https://bsd-hardware.info/?probe=467bcd3c04) | Aug 07, 2022 |
| Unknown       | Unknown                     | [b3c0b4a4f4](https://bsd-hardware.info/?probe=b3c0b4a4f4) | Aug 04, 2022 |
| Unknown       | Unknown                     | [612282319b](https://bsd-hardware.info/?probe=612282319b) | Aug 04, 2022 |
| Acer          | Revo 70                     | [0c23ffdc5a](https://bsd-hardware.info/?probe=0c23ffdc5a) | Aug 03, 2022 |
| ASRock        | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte      | 970A-DS3P FX                | [3c33e546bb](https://bsd-hardware.info/?probe=3c33e546bb) | Jul 31, 2022 |
| HP            | 339A                        | [241e56a349](https://bsd-hardware.info/?probe=241e56a349) | Jul 27, 2022 |
| Gigabyte      | H61M-DS2                    | [3ba3cedec4](https://bsd-hardware.info/?probe=3ba3cedec4) | Jul 21, 2022 |
| Acer          | RS880M05                    | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Gigabyte      | H310M S2 x.x                | [b11ca9c369](https://bsd-hardware.info/?probe=b11ca9c369) | Jul 16, 2022 |
| Acer          | Revo 70                     | [aad484a882](https://bsd-hardware.info/?probe=aad484a882) | Jul 13, 2022 |
| Acer          | Revo 70                     | [c8b51a94bd](https://bsd-hardware.info/?probe=c8b51a94bd) | Jul 13, 2022 |
| Kraftway      | KWH77                       | [c34f44a495](https://bsd-hardware.info/?probe=c34f44a495) | Jul 12, 2022 |
| Gigabyte      | C1037UN-EU                  | [3644f56368](https://bsd-hardware.info/?probe=3644f56368) | Jul 10, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| Lenovo        | NO DPK                      | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | [12279c8a4b](https://bsd-hardware.info/?probe=12279c8a4b) | Jul 06, 2022 |
| Techvision    | TVI7309X B0                 | [19a4b27ae7](https://bsd-hardware.info/?probe=19a4b27ae7) | Jul 05, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| Gigabyte      | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Dell          | 07KY25 A00                  | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| Pegatron      | 2A94h                       | [17078490f7](https://bsd-hardware.info/?probe=17078490f7) | Jun 11, 2022 |
| Pegatron      | 2A94h                       | [438d4f9b2f](https://bsd-hardware.info/?probe=438d4f9b2f) | Jun 09, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| Unknown       | Unknown                     | [a56bc64f26](https://bsd-hardware.info/?probe=a56bc64f26) | May 27, 2022 |
| ASUSTek       | P5LD2                       | [64208afa2c](https://bsd-hardware.info/?probe=64208afa2c) | May 25, 2022 |
| khadas        | edge-v                      | [60fb48e34c](https://bsd-hardware.info/?probe=60fb48e34c) | May 23, 2022 |
| khadas        | edge-v                      | [6facaa8032](https://bsd-hardware.info/?probe=6facaa8032) | May 22, 2022 |
| Gigabyte      | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | [e7055d83e2](https://bsd-hardware.info/?probe=e7055d83e2) | May 20, 2022 |
| Supermicro    | X10DRi-T                    | [d6fa145c7c](https://bsd-hardware.info/?probe=d6fa145c7c) | May 16, 2022 |
| HP            | ProLiant MicroServer        | [e569bffe8f](https://bsd-hardware.info/?probe=e569bffe8f) | May 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [224614e9ab](https://bsd-hardware.info/?probe=224614e9ab) | May 10, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [76eef59920](https://bsd-hardware.info/?probe=76eef59920) | May 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [bf3d4941a2](https://bsd-hardware.info/?probe=bf3d4941a2) | May 06, 2022 |
| Gigabyte      | A320M-H-CF                  | [24d308754b](https://bsd-hardware.info/?probe=24d308754b) | May 02, 2022 |
| Unknown       | Unknown                     | [d036c00d6c](https://bsd-hardware.info/?probe=d036c00d6c) | Apr 28, 2022 |
| ASRock        | J3355B-ITX                  | [c0739686fb](https://bsd-hardware.info/?probe=c0739686fb) | Apr 28, 2022 |
| Supermicro    | X10DRi-T                    | [dcd02e012d](https://bsd-hardware.info/?probe=dcd02e012d) | Apr 28, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1a475f0939](https://bsd-hardware.info/?probe=1a475f0939) | Apr 27, 2022 |
| ASRock        | X570S PG Riptide            | [928d2abb5e](https://bsd-hardware.info/?probe=928d2abb5e) | Apr 26, 2022 |
| Gigabyte      | H310M S2 x.x                | [549053284c](https://bsd-hardware.info/?probe=549053284c) | Apr 25, 2022 |
| PC Engines    | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [955922ebe2](https://bsd-hardware.info/?probe=955922ebe2) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [4d66b2b328](https://bsd-hardware.info/?probe=4d66b2b328) | Apr 23, 2022 |
| Intel         | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Gigabyte      | B450 AORUS M                | [427cf12b45](https://bsd-hardware.info/?probe=427cf12b45) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [8e64404e52](https://bsd-hardware.info/?probe=8e64404e52) | Apr 19, 2022 |
| Shuttle       | DS20U                       | [f01372719f](https://bsd-hardware.info/?probe=f01372719f) | Apr 16, 2022 |
| HP            | ProLiant MicroServer        | [fa76da045a](https://bsd-hardware.info/?probe=fa76da045a) | Apr 13, 2022 |
| Gigabyte      | E3000N                      | [7169c296cc](https://bsd-hardware.info/?probe=7169c296cc) | Apr 08, 2022 |
| Supermicro    | X10DRi-T                    | [e17bbe2186](https://bsd-hardware.info/?probe=e17bbe2186) | Apr 05, 2022 |
| Gigabyte      | H310M S2 x.x                | [29a9462f72](https://bsd-hardware.info/?probe=29a9462f72) | Apr 04, 2022 |
| Intel         | DCP847SKE                   | [a79e298be3](https://bsd-hardware.info/?probe=a79e298be3) | Apr 03, 2022 |
| Supermicro    | X10DRi-T                    | [eae4612261](https://bsd-hardware.info/?probe=eae4612261) | Mar 31, 2022 |
| MSI           | B85-G43                     | [f0a919c35f](https://bsd-hardware.info/?probe=f0a919c35f) | Mar 25, 2022 |
| MSI           | B85-G43                     | [7bd545fda8](https://bsd-hardware.info/?probe=7bd545fda8) | Mar 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | [8696405d09](https://bsd-hardware.info/?probe=8696405d09) | Mar 24, 2022 |
| Huanan        | X99-F8D V2.4                | [4ef193841e](https://bsd-hardware.info/?probe=4ef193841e) | Mar 13, 2022 |
| Gigabyte      | G31M-S2C                    | [5a22bb6991](https://bsd-hardware.info/?probe=5a22bb6991) | Mar 12, 2022 |
| MSI           | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASRock        | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Gigabyte      | X58A-UD5                    | [58d57520c1](https://bsd-hardware.info/?probe=58d57520c1) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | [5b6dd82da8](https://bsd-hardware.info/?probe=5b6dd82da8) | Feb 18, 2022 |
| ASRock        | B460M Pro4                  | [7a2781344f](https://bsd-hardware.info/?probe=7a2781344f) | Feb 17, 2022 |
| MW            | GMLK-2_5G4L                 | [2dd03795ba](https://bsd-hardware.info/?probe=2dd03795ba) | Feb 11, 2022 |
| ASRock        | X370 Gaming X               | [22f8d133d4](https://bsd-hardware.info/?probe=22f8d133d4) | Feb 09, 2022 |
| ASRock        | D1800M                      | [0902154c8e](https://bsd-hardware.info/?probe=0902154c8e) | Feb 08, 2022 |
| Dell          | 0654JC A01                  | [bbcf2bad96](https://bsd-hardware.info/?probe=bbcf2bad96) | Feb 08, 2022 |
| ASUSTek       | P5G41T-M                    | [a7d5b65ba1](https://bsd-hardware.info/?probe=a7d5b65ba1) | Feb 07, 2022 |
| MSI           | MS-7C96                     | [c08331ad58](https://bsd-hardware.info/?probe=c08331ad58) | Feb 06, 2022 |
| Kontron       | KT965/ATXP 61420000         | [b5389bbf43](https://bsd-hardware.info/?probe=b5389bbf43) | Feb 06, 2022 |
| ASRock        | H81M-VG4 R2.0               | [8af8b5270e](https://bsd-hardware.info/?probe=8af8b5270e) | Feb 04, 2022 |
| ASUSTek       | P4P800-VM                   | [2343c503a7](https://bsd-hardware.info/?probe=2343c503a7) | Feb 04, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [58ea01e4e6](https://bsd-hardware.info/?probe=58ea01e4e6) | Jan 29, 2022 |
| Lenovo        | 30C9 NOK                    | [7169d2989c](https://bsd-hardware.info/?probe=7169d2989c) | Jan 29, 2022 |
| Pegatron      | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| ASUSTek       | P5GC-MX                     | [372749f9d7](https://bsd-hardware.info/?probe=372749f9d7) | Jan 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [eb44c8d7e1](https://bsd-hardware.info/?probe=eb44c8d7e1) | Jan 27, 2022 |
| ASUSTek       | P5B SE                      | [f97fba19c1](https://bsd-hardware.info/?probe=f97fba19c1) | Jan 26, 2022 |
| Kontron       | KT965/ATXP 61420000         | [36109b09ca](https://bsd-hardware.info/?probe=36109b09ca) | Jan 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [9f0a000ceb](https://bsd-hardware.info/?probe=9f0a000ceb) | Jan 25, 2022 |
| ASUSTek       | P5B SE                      | [e3332e7b94](https://bsd-hardware.info/?probe=e3332e7b94) | Jan 25, 2022 |
| ASRock        | B460M Pro4                  | [107a1e59f5](https://bsd-hardware.info/?probe=107a1e59f5) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [10ca6492c1](https://bsd-hardware.info/?probe=10ca6492c1) | Jan 25, 2022 |
| MSI           | G31TM-P21                   | [7563c4cf09](https://bsd-hardware.info/?probe=7563c4cf09) | Jan 25, 2022 |
| Kontron       | KT965/ATXP 61420000         | [db757ea2ef](https://bsd-hardware.info/?probe=db757ea2ef) | Jan 25, 2022 |
| Gigabyte      | H310M S2 x.x                | [b0aeac1ef8](https://bsd-hardware.info/?probe=b0aeac1ef8) | Jan 25, 2022 |
| ASUSTek       | P5M2                        | [f2d4eccf4d](https://bsd-hardware.info/?probe=f2d4eccf4d) | Jan 24, 2022 |
| ASUSTek       | P7H55-M                     | [fb73c2f7dc](https://bsd-hardware.info/?probe=fb73c2f7dc) | Jan 23, 2022 |
| ASRock        | J3455-ITX                   | [55d70a3070](https://bsd-hardware.info/?probe=55d70a3070) | Jan 22, 2022 |
| ASRock        | J3455-ITX                   | [bf033b6b9f](https://bsd-hardware.info/?probe=bf033b6b9f) | Jan 22, 2022 |
| Intel         | DCP847SKE                   | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | PRIME Z590-P                | [0473b57d99](https://bsd-hardware.info/?probe=0473b57d99) | Jan 19, 2022 |
| Intel CNCT... | Unknown                     | [0debf023f1](https://bsd-hardware.info/?probe=0debf023f1) | Jan 18, 2022 |
| Gigabyte      | B365 HD3                    | [62fc48bd99](https://bsd-hardware.info/?probe=62fc48bd99) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d377e06101](https://bsd-hardware.info/?probe=d377e06101) | Jan 15, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [384cbe9714](https://bsd-hardware.info/?probe=384cbe9714) | Jan 13, 2022 |
| ASUSTek       | A68HM-PLUS                  | [650628a974](https://bsd-hardware.info/?probe=650628a974) | Jan 10, 2022 |
| friendlyel... | nanopi-m4                   | [bb29e50061](https://bsd-hardware.info/?probe=bb29e50061) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| khadas        | edge-v                      | [42c428aac0](https://bsd-hardware.info/?probe=42c428aac0) | Dec 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [0918f0a5b9](https://bsd-hardware.info/?probe=0918f0a5b9) | Dec 25, 2021 |
| ASUSTek       | PRIME B350M-A               | [b0aa3885bb](https://bsd-hardware.info/?probe=b0aa3885bb) | Dec 25, 2021 |
| Acer          | Revo RN86                   | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| Gigabyte      | E3000N                      | [eb0ba1b296](https://bsd-hardware.info/?probe=eb0ba1b296) | Dec 22, 2021 |
| HP            | 1850                        | [aa737033c4](https://bsd-hardware.info/?probe=aa737033c4) | Dec 21, 2021 |
| HP            | 1850                        | [17f42cda78](https://bsd-hardware.info/?probe=17f42cda78) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5cc62c68f9](https://bsd-hardware.info/?probe=5cc62c68f9) | Dec 21, 2021 |
| ASRock        | H110M-DGS                   | [40c4553adb](https://bsd-hardware.info/?probe=40c4553adb) | Dec 21, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [bc55ac50d1](https://bsd-hardware.info/?probe=bc55ac50d1) | Dec 20, 2021 |
| Acer          | Revo RN86                   | [68541bb331](https://bsd-hardware.info/?probe=68541bb331) | Dec 20, 2021 |
| Acer          | Aspire XC-895 V:1.0         | [58440d7663](https://bsd-hardware.info/?probe=58440d7663) | Dec 20, 2021 |
| MSI           | MS-9852 10                  | [4b851eef0a](https://bsd-hardware.info/?probe=4b851eef0a) | Dec 19, 2021 |
| ASUSTek       | P5G41T-M                    | [44bba395e8](https://bsd-hardware.info/?probe=44bba395e8) | Dec 13, 2021 |
| ASUSTek       | P5G41T-M                    | [1fb865c4ae](https://bsd-hardware.info/?probe=1fb865c4ae) | Dec 09, 2021 |
| Gigabyte      | Z68XP-UD3                   | [9fca53da56](https://bsd-hardware.info/?probe=9fca53da56) | Dec 08, 2021 |
| ASUSTek       | P5B                         | [93b542ab79](https://bsd-hardware.info/?probe=93b542ab79) | Dec 06, 2021 |
| Gigabyte      | GA-8S661FXM-775             | [3a64909558](https://bsd-hardware.info/?probe=3a64909558) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| Unknown       | Q2XX V1.1                   | [66d6a26e35](https://bsd-hardware.info/?probe=66d6a26e35) | Dec 04, 2021 |
| Unknown       | Unknown                     | [a91c9ec877](https://bsd-hardware.info/?probe=a91c9ec877) | Dec 04, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [dab56eef53](https://bsd-hardware.info/?probe=dab56eef53) | Nov 07, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [f26b302e43](https://bsd-hardware.info/?probe=f26b302e43) | Nov 07, 2021 |
| Unknown       | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| Gigabyte      | Z77X-UD3H                   | [4c9b877754](https://bsd-hardware.info/?probe=4c9b877754) | Oct 29, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [767ef0f0a6](https://bsd-hardware.info/?probe=767ef0f0a6) | Oct 27, 2021 |
| Radxa         | rock-pi-4                   | [fcd3e65f7e](https://bsd-hardware.info/?probe=fcd3e65f7e) | Oct 26, 2021 |
| Acer          | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Radxa         | rock-pi-4                   | [876564310f](https://bsd-hardware.info/?probe=876564310f) | Oct 19, 2021 |
| Unknown       | Unknown                     | [9716564d5e](https://bsd-hardware.info/?probe=9716564d5e) | Oct 19, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [39c78ac754](https://bsd-hardware.info/?probe=39c78ac754) | Oct 19, 2021 |
| ASUSTek       | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [5173ffc13b](https://bsd-hardware.info/?probe=5173ffc13b) | Oct 17, 2021 |
| Dell          | 0Y7WYT A00                  | [1de7ed2a67](https://bsd-hardware.info/?probe=1de7ed2a67) | Oct 16, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| ASUSTek       | F2A85-M                     | [b4e3f33e5c](https://bsd-hardware.info/?probe=b4e3f33e5c) | Oct 14, 2021 |
| Lenovo        | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Gigabyte      | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel         | J1900                       | [9d6c7612d3](https://bsd-hardware.info/?probe=9d6c7612d3) | Oct 05, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| Unknown       | Unknown                     | [b45dad63f6](https://bsd-hardware.info/?probe=b45dad63f6) | Sep 20, 2021 |
| Unknown       | Unknown                     | [ed7c1c1f3b](https://bsd-hardware.info/?probe=ed7c1c1f3b) | Sep 20, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [198c4264f9](https://bsd-hardware.info/?probe=198c4264f9) | Sep 16, 2021 |
| Firefly       | roc-rk3399-pc-plus          | [062602e8db](https://bsd-hardware.info/?probe=062602e8db) | Sep 15, 2021 |
| ASRock        | B450M Pro4-F                | [ae1765efd5](https://bsd-hardware.info/?probe=ae1765efd5) | Sep 10, 2021 |
| Gigabyte      | Z68P-DS3                    | [9a2545337b](https://bsd-hardware.info/?probe=9a2545337b) | Sep 09, 2021 |
| ASUSTek       | P5KPL-CM                    | [01ac3a91d0](https://bsd-hardware.info/?probe=01ac3a91d0) | Sep 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [aeb23122b6](https://bsd-hardware.info/?probe=aeb23122b6) | Aug 31, 2021 |
| Intel         | DG33BU AAD79951-408         | [e8f4f644e3](https://bsd-hardware.info/?probe=e8f4f644e3) | Aug 30, 2021 |
| ASUSTek       | P4P800-VM                   | [f23a539453](https://bsd-hardware.info/?probe=f23a539453) | Aug 30, 2021 |
| Unknown       | Q2XX V1.1                   | [5ca9aa0bf2](https://bsd-hardware.info/?probe=5ca9aa0bf2) | Aug 19, 2021 |
| Gigabyte      | HA65M-D2H-B3                | [fc9b50bb85](https://bsd-hardware.info/?probe=fc9b50bb85) | Aug 16, 2021 |
| Supermicro    | X10DRH-CT                   | [6ccb3c09d6](https://bsd-hardware.info/?probe=6ccb3c09d6) | Aug 12, 2021 |
| Pegatron      | IPPCR-SS                    | [8a7fc2689b](https://bsd-hardware.info/?probe=8a7fc2689b) | Aug 09, 2021 |
| MSI           | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock        | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| Gigabyte      | PH67A-D3-B3                 | [73dff53f04](https://bsd-hardware.info/?probe=73dff53f04) | Jul 23, 2021 |
| HP            | ProLiant DL360e Gen8        | [30eeb098b0](https://bsd-hardware.info/?probe=30eeb098b0) | Jul 10, 2021 |
| HP            | ProLiant DL320 G5           | [3b4ee33976](https://bsd-hardware.info/?probe=3b4ee33976) | Jul 10, 2021 |
| Foxconn       | AT-7000 Series              | [3802fb98b5](https://bsd-hardware.info/?probe=3802fb98b5) | Jul 10, 2021 |
| MSI           | H81M-E33                    | [c9fda90944](https://bsd-hardware.info/?probe=c9fda90944) | Jul 08, 2021 |
| Pegatron      | IPPCR-SS                    | [86b2e85d24](https://bsd-hardware.info/?probe=86b2e85d24) | Jul 05, 2021 |
| ASUSTek       | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| Supermicro    | X10DRH-CT                   | [583e9e5a66](https://bsd-hardware.info/?probe=583e9e5a66) | Jun 26, 2021 |
| ECS           | A740GM-M                    | [a9d9106f11](https://bsd-hardware.info/?probe=a9d9106f11) | Jun 24, 2021 |
| Gigabyte      | GA-IMB370TN                 | [449fc82ff8](https://bsd-hardware.info/?probe=449fc82ff8) | Jun 21, 2021 |
| MSI           | H110M PRO-VH PLUS           | [45b842180e](https://bsd-hardware.info/?probe=45b842180e) | Jun 20, 2021 |
| ASUSTek       | H110I-PLUS                  | [0cb30b464d](https://bsd-hardware.info/?probe=0cb30b464d) | Jun 17, 2021 |
| ASUSTek       | M4A78LT-M                   | [0c8d6cd661](https://bsd-hardware.info/?probe=0c8d6cd661) | Jun 14, 2021 |
| Intel         | X79 V2.72A                  | [88173bcf06](https://bsd-hardware.info/?probe=88173bcf06) | Jun 14, 2021 |
| ASUSTek       | P5K SE/EPU                  | [60d9b24b69](https://bsd-hardware.info/?probe=60d9b24b69) | Jun 13, 2021 |
| Gigabyte      | GA-IMB370TN                 | [b486e670fe](https://bsd-hardware.info/?probe=b486e670fe) | Jun 02, 2021 |
| Biostar       | TH67B                       | [1f2321ec41](https://bsd-hardware.info/?probe=1f2321ec41) | Jun 01, 2021 |
| Gigabyte      | H61M-DS2                    | [d9657e7246](https://bsd-hardware.info/?probe=d9657e7246) | Jun 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [8c06f6b716](https://bsd-hardware.info/?probe=8c06f6b716) | Jun 01, 2021 |
| Unknown       | Unknown                     | [d098ba539d](https://bsd-hardware.info/?probe=d098ba539d) | May 27, 2021 |
| ASUSTek       | P7H55-M/USB3                | [87068a97be](https://bsd-hardware.info/?probe=87068a97be) | May 26, 2021 |
| Unknown       | Unknown                     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASUSTek       | Z87-PLUS                    | [629d15378d](https://bsd-hardware.info/?probe=629d15378d) | May 10, 2021 |
| ASUSTek       | H81M-K                      | [ae105fb8bc](https://bsd-hardware.info/?probe=ae105fb8bc) | May 09, 2021 |
| ASUSTek       | Maximus II Formula          | [493bb4da66](https://bsd-hardware.info/?probe=493bb4da66) | May 07, 2021 |
| Gigabyte      | X58A-UD5                    | [24502c7f7b](https://bsd-hardware.info/?probe=24502c7f7b) | May 04, 2021 |
| ASUSTek       | P10S-I Series               | [6548ae7d88](https://bsd-hardware.info/?probe=6548ae7d88) | May 01, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [8055ed41df](https://bsd-hardware.info/?probe=8055ed41df) | Apr 25, 2021 |
| Gigabyte      | F2A75M-HD2                  | [18a74377ac](https://bsd-hardware.info/?probe=18a74377ac) | Apr 25, 2021 |
| Unknown       | Q2XX V1.1                   | [5c7ea7fb7d](https://bsd-hardware.info/?probe=5c7ea7fb7d) | Apr 24, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [ab8235808d](https://bsd-hardware.info/?probe=ab8235808d) | Apr 23, 2021 |
| Gigabyte      | C1037UN-EU                  | [a379c24586](https://bsd-hardware.info/?probe=a379c24586) | Apr 19, 2021 |
| Gigabyte      | GA-IMB370TN                 | [7c77a33f75](https://bsd-hardware.info/?probe=7c77a33f75) | Apr 18, 2021 |
| Unknown       | Unknown                     | [48090193c1](https://bsd-hardware.info/?probe=48090193c1) | Apr 17, 2021 |
| Unknown       | Unknown                     | [1c4a81b9a5](https://bsd-hardware.info/?probe=1c4a81b9a5) | Apr 17, 2021 |
| Unknown       | Unknown                     | [7b295345e6](https://bsd-hardware.info/?probe=7b295345e6) | Apr 17, 2021 |
| Unknown       | Unknown                     | [0c708350cd](https://bsd-hardware.info/?probe=0c708350cd) | Apr 17, 2021 |
| Gigabyte      | GA-IMB370TN                 | [513027c242](https://bsd-hardware.info/?probe=513027c242) | Apr 13, 2021 |
| Gigabyte      | GA-IMB370TN                 | [8023a25ccb](https://bsd-hardware.info/?probe=8023a25ccb) | Mar 29, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| ASRock        | H71M-DGS                    | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| ASUSTek       | P8H77-I                     | [46d36c6b23](https://bsd-hardware.info/?probe=46d36c6b23) | Mar 21, 2021 |
| Intel         | PB_1900A V2.1               | [a2378c3bee](https://bsd-hardware.info/?probe=a2378c3bee) | Mar 17, 2021 |
| ASUSTek       | AT5NM10T-I                  | [7c26a8b81e](https://bsd-hardware.info/?probe=7c26a8b81e) | Mar 12, 2021 |
| ASRock        | Q1900M                      | [f366c06928](https://bsd-hardware.info/?probe=f366c06928) | Mar 09, 2021 |
| Gigabyte      | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | [cf965a3a5b](https://bsd-hardware.info/?probe=cf965a3a5b) | Mar 06, 2021 |
| Gigabyte      | 8IG1000MK                   | [49ee1efce0](https://bsd-hardware.info/?probe=49ee1efce0) | Mar 01, 2021 |
| Kontron       | KT965/ATXP 61420000         | [8755a0003d](https://bsd-hardware.info/?probe=8755a0003d) | Mar 01, 2021 |
| Lenovo        | Board                       | [395ef09e6d](https://bsd-hardware.info/?probe=395ef09e6d) | Feb 25, 2021 |
| Lenovo        | Board                       | [96fbaf0644](https://bsd-hardware.info/?probe=96fbaf0644) | Feb 25, 2021 |
| ASRock        | G31M-VS2                    | [6c7150dc1b](https://bsd-hardware.info/?probe=6c7150dc1b) | Feb 24, 2021 |
| Acer          | TPDS05 R3700                | [651f8a2bb4](https://bsd-hardware.info/?probe=651f8a2bb4) | Feb 23, 2021 |
| PC Engines    | APU2                        | [02a107a767](https://bsd-hardware.info/?probe=02a107a767) | Feb 23, 2021 |
| ASRock        | J4205-ITX                   | [c8e0b22858](https://bsd-hardware.info/?probe=c8e0b22858) | Feb 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8e52de9bec](https://bsd-hardware.info/?probe=8e52de9bec) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| ASUSTek       | H87I-PLUS                   | [8f8f08f763](https://bsd-hardware.info/?probe=8f8f08f763) | Feb 17, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [ae42a14150](https://bsd-hardware.info/?probe=ae42a14150) | Feb 16, 2021 |
| Supermicro    | A2SDi-8C-HLN4F              | [24551b886c](https://bsd-hardware.info/?probe=24551b886c) | Feb 16, 2021 |
| ASRock        | B550M Pro4                  | [61a5641019](https://bsd-hardware.info/?probe=61a5641019) | Feb 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| ASUSTek       | P8H77-V                     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| ASUSTek       | P5GDC Pro                   | [ca50169bf4](https://bsd-hardware.info/?probe=ca50169bf4) | Feb 11, 2021 |
| Gigabyte      | J3455N-D3H                  | [65e5edcfd7](https://bsd-hardware.info/?probe=65e5edcfd7) | Feb 11, 2021 |
| ASRock        | J3455M                      | [0493901aff](https://bsd-hardware.info/?probe=0493901aff) | Feb 10, 2021 |
| ASRock        | H61M-S                      | [f7b01b5274](https://bsd-hardware.info/?probe=f7b01b5274) | Feb 08, 2021 |
| Gigabyte      | Z68A-D3H-B3                 | [e1c3b89d0d](https://bsd-hardware.info/?probe=e1c3b89d0d) | Feb 06, 2021 |
| Gigabyte      | J3455N-D3H                  | [e2fd3451b6](https://bsd-hardware.info/?probe=e2fd3451b6) | Jan 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | [2a81a1bd1f](https://bsd-hardware.info/?probe=2a81a1bd1f) | Jan 24, 2021 |
| MSI           | MS-7235                     | [6a0d60ad2c](https://bsd-hardware.info/?probe=6a0d60ad2c) | Jan 21, 2021 |
| Dell          | 0Y7WYT A00                  | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ad33eaab8a](https://bsd-hardware.info/?probe=ad33eaab8a) | Jan 19, 2021 |
| Centerm       | C30                         | [862ffd88e6](https://bsd-hardware.info/?probe=862ffd88e6) | Dec 16, 2020 |
| Gigabyte      | Z68P-DS3                    | [a1fe36fd99](https://bsd-hardware.info/?probe=a1fe36fd99) | Dec 16, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [fb6286f788](https://bsd-hardware.info/?probe=fb6286f788) | Dec 13, 2020 |
| ASUSTek       | P4P800-VM                   | [4fe4c14195](https://bsd-hardware.info/?probe=4fe4c14195) | Dec 05, 2020 |
| Acer          | Aspire XC-895 V:1.0         | [c5017eff06](https://bsd-hardware.info/?probe=c5017eff06) | Dec 04, 2020 |
| PC Engines    | APU2                        | [90d68eee14](https://bsd-hardware.info/?probe=90d68eee14) | Dec 04, 2020 |
| PC Engines    | APU2                        | [fab3041b1e](https://bsd-hardware.info/?probe=fab3041b1e) | Dec 04, 2020 |
| Gigabyte      | Unknown                     | [8a9ae48d42](https://bsd-hardware.info/?probe=8a9ae48d42) | Dec 01, 2020 |
| ASRock        | N68-GE                      | [ce9159c2fa](https://bsd-hardware.info/?probe=ce9159c2fa) | Nov 30, 2020 |
| Unknown       | Unknown                     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| ASRock        | N68-GE                      | [028eabaec2](https://bsd-hardware.info/?probe=028eabaec2) | Nov 28, 2020 |
| ASUSTek       | H97M-E                      | [c3230a9065](https://bsd-hardware.info/?probe=c3230a9065) | Nov 23, 2020 |
| ASUSTek       | P5GDC Pro                   | [8776b186c1](https://bsd-hardware.info/?probe=8776b186c1) | Nov 14, 2020 |
| ASRock        | X570 Steel Legend           | [8a79e3f5e4](https://bsd-hardware.info/?probe=8a79e3f5e4) | Nov 11, 2020 |
| Pegatron      | 1.03                        | [e660e12e3c](https://bsd-hardware.info/?probe=e660e12e3c) | Nov 10, 2020 |
| Gigabyte      | M61SME-S2L                  | [d8809eb5e7](https://bsd-hardware.info/?probe=d8809eb5e7) | Nov 09, 2020 |
| Gigabyte      | M61SME-S2L                  | [e5f658c70a](https://bsd-hardware.info/?probe=e5f658c70a) | Nov 09, 2020 |
| MSI           | Z97S SLI Krait Edition      | [c766aab801](https://bsd-hardware.info/?probe=c766aab801) | Nov 09, 2020 |
| Pegatron      | SKLD4-P1                    | [ea548b4c71](https://bsd-hardware.info/?probe=ea548b4c71) | Nov 08, 2020 |
| ASUSTek       | B75M-A                      | [43ece33e8c](https://bsd-hardware.info/?probe=43ece33e8c) | Oct 31, 2020 |
| ASRock        | J3455-ITX                   | [52fe99a6d6](https://bsd-hardware.info/?probe=52fe99a6d6) | Oct 29, 2020 |
| Gigabyte      | X58A-UD5                    | [6e642641e5](https://bsd-hardware.info/?probe=6e642641e5) | Oct 25, 2020 |
| ASUSTek       | B150M-K                     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| ASUSTek       | Z170-A                      | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| ASUSTek       | Z170-K                      | [19cb3ccc34](https://bsd-hardware.info/?probe=19cb3ccc34) | Oct 20, 2020 |
| Intel         | S3000AH                     | [f5b858601a](https://bsd-hardware.info/?probe=f5b858601a) | Oct 20, 2020 |
| Unknown       | Unknown                     | [bedb4a4b37](https://bsd-hardware.info/?probe=bedb4a4b37) | Oct 20, 2020 |
| ASUSTek       | P10S-I Series               | [1a0e9f0100](https://bsd-hardware.info/?probe=1a0e9f0100) | Oct 19, 2020 |
| IBM           | Board                       | [af2f64a7a8](https://bsd-hardware.info/?probe=af2f64a7a8) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [dc7b96e637](https://bsd-hardware.info/?probe=dc7b96e637) | Oct 19, 2020 |
| Foxconn       | AT-7000 Series              | [0184fcedcf](https://bsd-hardware.info/?probe=0184fcedcf) | Oct 19, 2020 |
| Unknown       | Unknown                     | [e36fc2b2b2](https://bsd-hardware.info/?probe=e36fc2b2b2) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [027fbd78f5](https://bsd-hardware.info/?probe=027fbd78f5) | Oct 19, 2020 |
| MSI           | B450M MORTAR MAX            | [1123cb92ba](https://bsd-hardware.info/?probe=1123cb92ba) | Oct 04, 2020 |
| ASUSTek       | H81M-D PLUS                 | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Gigabyte      | C246-WU4-CF                 | [4117a39b03](https://bsd-hardware.info/?probe=4117a39b03) | Sep 23, 2020 |
| Acer          | Revo RN86                   | [d1b1775be3](https://bsd-hardware.info/?probe=d1b1775be3) | Sep 23, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e8ab84404c](https://bsd-hardware.info/?probe=e8ab84404c) | Sep 22, 2020 |
| Acer          | Revo RN86                   | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS                 | [e9dd488fe0](https://bsd-hardware.info/?probe=e9dd488fe0) | Sep 13, 2020 |
| ASUSTek       | P5QD TURBO                  | [598e77539b](https://bsd-hardware.info/?probe=598e77539b) | Aug 21, 2020 |
| ASUSTek       | P5QD TURBO                  | [e210609359](https://bsd-hardware.info/?probe=e210609359) | Aug 21, 2020 |
| Gigabyte      | X58A-UD5                    | [63a429ad0e](https://bsd-hardware.info/?probe=63a429ad0e) | Aug 16, 2020 |
| ASUSTek       | P8P67                       | [c61cac017e](https://bsd-hardware.info/?probe=c61cac017e) | Aug 06, 2020 |
| ASUSTek       | K8N-VM                      | [0ddf168986](https://bsd-hardware.info/?probe=0ddf168986) | Aug 06, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | [4f4cb01708](https://bsd-hardware.info/?probe=4f4cb01708) | Aug 05, 2020 |
| MSI           | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| ASRock        | E350M1                      | [08eec78cdf](https://bsd-hardware.info/?probe=08eec78cdf) | Jul 25, 2020 |
| ASUSTek       | P5Q DELUXE                  | [eb3f0a19ae](https://bsd-hardware.info/?probe=eb3f0a19ae) | Jul 25, 2020 |
| Pegatron      | 2A73                        | [05dea28605](https://bsd-hardware.info/?probe=05dea28605) | Jul 21, 2020 |
| Supermicro    | NSM5200A                    | [49a39eb60f](https://bsd-hardware.info/?probe=49a39eb60f) | Jul 15, 2020 |
| Gigabyte      | GA-790FXTA-UD5              | [667d98ccb2](https://bsd-hardware.info/?probe=667d98ccb2) | Jul 15, 2020 |
| ASRock        | B450 Pro4                   | [836bf04a97](https://bsd-hardware.info/?probe=836bf04a97) | Jul 15, 2020 |
| ASUSTek       | P5KPL-AM                    | [daaa05bbf4](https://bsd-hardware.info/?probe=daaa05bbf4) | Jul 15, 2020 |
| Gigabyte      | Z77-D3H                     | [97c6656398](https://bsd-hardware.info/?probe=97c6656398) | Jul 12, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [08dd1b91a8](https://bsd-hardware.info/?probe=08dd1b91a8) | Jun 30, 2020 |
| Foxconn       | nT-330i                     | [79ab8efb37](https://bsd-hardware.info/?probe=79ab8efb37) | Jun 29, 2020 |
| ASRock        | J3455-ITX                   | [1c8e18b787](https://bsd-hardware.info/?probe=1c8e18b787) | Jun 15, 2020 |
| Unknown       | Unknown                     | [ee9f9df2c1](https://bsd-hardware.info/?probe=ee9f9df2c1) | May 31, 2020 |
| Unknown       | Unknown                     | [6034ab8e6e](https://bsd-hardware.info/?probe=6034ab8e6e) | May 31, 2020 |
| ASRock        | Q1900M                      | [8787d15bc5](https://bsd-hardware.info/?probe=8787d15bc5) | May 31, 2020 |
| ASRock        | Q1900M                      | [79fe3017ef](https://bsd-hardware.info/?probe=79fe3017ef) | May 31, 2020 |
| Gigabyte      | M68MT-S2P                   | [08534174df](https://bsd-hardware.info/?probe=08534174df) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [8e0f831fd8](https://bsd-hardware.info/?probe=8e0f831fd8) | May 27, 2020 |
| Gigabyte      | M68MT-S2P                   | [03ea0992c4](https://bsd-hardware.info/?probe=03ea0992c4) | May 27, 2020 |
| IBM           | Board                       | [1bcc2b8e0b](https://bsd-hardware.info/?probe=1bcc2b8e0b) | May 27, 2020 |
| Unknown       | TI AM335x BeagleBone Bla... | [74b9526162](https://bsd-hardware.info/?probe=74b9526162) | May 27, 2020 |
| Gigabyte      | B450M GAMING                | [b4c4c676c4](https://bsd-hardware.info/?probe=b4c4c676c4) | May 26, 2020 |
| Unknown       | YL-J3060L2                  | [55be2fab24](https://bsd-hardware.info/?probe=55be2fab24) | May 26, 2020 |
| Gigabyte      | GA-MA78GM-UD2H              | [66bce86f33](https://bsd-hardware.info/?probe=66bce86f33) | May 26, 2020 |
| Acer          | WMCP78M                     | [db1e7a52b9](https://bsd-hardware.info/?probe=db1e7a52b9) | May 25, 2020 |
| Acer          | WMCP78M                     | [d9b08cfc0c](https://bsd-hardware.info/?probe=d9b08cfc0c) | May 25, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [8b9481baf2](https://bsd-hardware.info/?probe=8b9481baf2) | May 25, 2020 |
| ASUSTek       | P4P800-VM                   | [33c4579f99](https://bsd-hardware.info/?probe=33c4579f99) | May 25, 2020 |
| MSI           | MS-7255                     | [3984f45545](https://bsd-hardware.info/?probe=3984f45545) | May 25, 2020 |
| Gigabyte      | 945GM-S2                    | [59e3624de7](https://bsd-hardware.info/?probe=59e3624de7) | May 25, 2020 |
| Gigabyte      | F2A75M-HD2                  | [09bfdeafbd](https://bsd-hardware.info/?probe=09bfdeafbd) | May 25, 2020 |
| ASRock        | J4205-ITX                   | [bb67f0e80b](https://bsd-hardware.info/?probe=bb67f0e80b) | May 25, 2020 |
| ASUSTek       | Z87-EXPERT                  | [9f0ad7bbcf](https://bsd-hardware.info/?probe=9f0ad7bbcf) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | [1db4784753](https://bsd-hardware.info/?probe=1db4784753) | May 25, 2020 |
| Supermicro    | X11DPH-T                    | [79aea35f1f](https://bsd-hardware.info/?probe=79aea35f1f) | May 25, 2020 |
| ASUSTek       | P5M2                        | [c1f04b3a84](https://bsd-hardware.info/?probe=c1f04b3a84) | May 25, 2020 |
| ASUSTek       | P6T SE                      | [66bbed8d59](https://bsd-hardware.info/?probe=66bbed8d59) | May 25, 2020 |
| ASUSTek       | P6T SE                      | [6eb355eabd](https://bsd-hardware.info/?probe=6eb355eabd) | May 25, 2020 |
| Gigabyte      | EX58-UD4                    | [e7f015c6da](https://bsd-hardware.info/?probe=e7f015c6da) | May 25, 2020 |
| ASUSTek       | P5Q                         | [97732c8106](https://bsd-hardware.info/?probe=97732c8106) | May 25, 2020 |
| ASUSTek       | P5GD2-Deluxe                | [5b1dc84da5](https://bsd-hardware.info/?probe=5b1dc84da5) | May 25, 2020 |
| Acer          | WMCP78M                     | [55755e9ab9](https://bsd-hardware.info/?probe=55755e9ab9) | May 25, 2020 |
| ASUSTek       | P5K-E                       | [a1b81962ac](https://bsd-hardware.info/?probe=a1b81962ac) | May 25, 2020 |
| ASUSTek       | P5K-E                       | [8f72d18bff](https://bsd-hardware.info/?probe=8f72d18bff) | May 25, 2020 |
| Gigabyte      | Z68P-DS3                    | [c06e03cda0](https://bsd-hardware.info/?probe=c06e03cda0) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| ASUSTek       | B75M-PLUS                   | [4620a00ccc](https://bsd-hardware.info/?probe=4620a00ccc) | May 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| helloSystem 0.8.1    | 29       | 5.53%   |
| helloSystem 0.7.0    | 27       | 5.15%   |
| OpenBSD 6.8          | 19       | 3.63%   |
| FreeBSD 14.0-CURRENT | 16       | 3.05%   |
| FreeBSD 13.1         | 15       | 2.86%   |
| FreeBSD 13.0         | 15       | 2.86%   |
| FreeBSD 12.1-p5      | 15       | 2.86%   |
| helloSystem 0.8.0    | 14       | 2.67%   |
| OpenBSD 7.3          | 13       | 2.48%   |
| FreeBSD 13.2         | 13       | 2.48%   |
| OpenBSD 7.1          | 10       | 1.91%   |
| helloSystem 0.5.0    | 9        | 1.72%   |
| FreeBSD 13.0-STABLE  | 9        | 1.72%   |
| OpenBSD 7.0          | 8        | 1.53%   |
| OpenBSD 6.7          | 8        | 1.53%   |
| FreeBSD 12.1-STABLE  | 7        | 1.34%   |
| OpenBSD 7.2          | 6        | 1.15%   |
| helloSystem 0.6.0    | 6        | 1.15%   |
| helloSystem 0.4.0    | 6        | 1.15%   |
| FreeBSD 12.2         | 6        | 1.15%   |
| OPNsense 23.7.10     | 5        | 0.95%   |
| OPNsense 22.7.11     | 5        | 0.95%   |
| helloSystem 0.8.2    | 5        | 0.95%   |
| GhostBSD 20.04.02    | 5        | 0.95%   |
| FreeBSD 12.1-p7      | 5        | 0.95%   |
| OPNsense 23.7.12     | 4        | 0.76%   |
| OPNsense 23.1        | 4        | 0.76%   |
| OPNsense 22.7.6      | 4        | 0.76%   |
| OPNsense 22.1.6      | 4        | 0.76%   |
| OPNsense 22.1.10     | 4        | 0.76%   |
| OPNsense 21.1.5      | 4        | 0.76%   |
| OpenBSD 6.9          | 4        | 0.76%   |
| MyBee 13.2           | 4        | 0.76%   |
| helloSystem 0.9.0    | 4        | 0.76%   |
| FreeBSD 12.2-p3      | 4        | 0.76%   |
| FreeBSD 12.2-p2      | 4        | 0.76%   |
| OPNsense 23.7.9      | 3        | 0.57%   |
| OPNsense 23.7.7      | 3        | 0.57%   |
| OPNsense 23.7.1      | 3        | 0.57%   |
| OPNsense 23.1.8      | 3        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| FreeBSD     | 155      | 35.71%  |
| helloSystem | 97       | 22.35%  |
| OPNsense    | 85       | 19.59%  |
| OpenBSD     | 51       | 11.75%  |
| MyBee       | 16       | 3.69%   |
| NetBSD      | 10       | 2.3%    |
| GhostBSD    | 6        | 1.38%   |
| NomadBSD    | 3        | 0.69%   |
| ClonOS      | 3        | 0.69%   |
| Ting        | 2        | 0.46%   |
| XigmaNAS    | 1        | 0.23%   |
| TrueNAS     | 1        | 0.23%   |
| pfSense     | 1        | 0.23%   |
| PC-BSD      | 1        | 0.23%   |
| FuryBSD     | 1        | 0.23%   |
| DragonFly   | 1        | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 373      | 88.81%  |
| arm64   | 25       | 5.95%   |
| i386    | 14       | 3.33%   |
| macppc  | 2        | 0.48%   |
| arm     | 2        | 0.48%   |
| sparc64 | 1        | 0.24%   |
| powerpc | 1        | 0.24%   |
| evbarm  | 1        | 0.24%   |
| armv7   | 1        | 0.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 200      | 46.08%  |
| helloDesktop | 121      | 27.88%  |
| KDE5         | 24       | 5.53%   |
| XFCE         | 22       | 5.07%   |
| fvwm         | 19       | 4.38%   |
| MATE         | 14       | 3.23%   |
| Openbox      | 10       | 2.3%    |
| TWM          | 8        | 1.84%   |
| GNOME        | 7        | 1.61%   |
| Fluxbox      | 5        | 1.15%   |
| plasma       | 1        | 0.23%   |
| KWin         | 1        | 0.23%   |
| Budgie       | 1        | 0.23%   |
| akonadi_newm | 1        | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 211      | 49.88%  |
| Console | 211      | 49.88%  |
| Wayland | 1        | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 269      | 63.29%  |
| SLiM    | 113      | 26.59%  |
| SDDM    | 22       | 5.18%   |
| LightDM | 13       | 3.06%   |
| XDM     | 4        | 0.94%   |
| GDM     | 4        | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 160      | 36.36%  |
| en_US          | 110      | 25%     |
| ru_RU          | 99       | 22.5%   |
| C              | 48       | 10.91%  |
| fr_FR          | 11       | 2.5%    |
| ru             | 6        | 1.36%   |
| ru_RU.KOI8-R   | 3        | 0.68%   |
| fr             | 1        | 0.23%   |
| en_GB          | 1        | 0.23%   |
| cv_RU.US-ASCII | 1        | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 280      | 65.57%  |
| BIOS | 147      | 34.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Zfs     | 184      | 42.69%  |
| Ufs     | 144      | 33.41%  |
| Ffs     | 51       | 11.83%  |
| Cd9660  | 51       | 11.83%  |
| Hammer2 | 1        | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 344      | 82.1%   |
| MBR     | 72       | 17.18%  |
| Unknown | 3        | 0.72%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 92       | 22.01%  |
| Gigabyte Technology | 71       | 16.99%  |
| Unknown             | 59       | 14.11%  |
| ASRock              | 43       | 10.29%  |
| MSI                 | 27       | 6.46%   |
| Intel               | 16       | 3.83%   |
| Hewlett-Packard     | 12       | 2.87%   |
| Supermicro          | 9        | 2.15%   |
| Lenovo              | 8        | 1.91%   |
| Huanan              | 8        | 1.91%   |
| Techvision          | 7        | 1.67%   |
| Pegatron            | 7        | 1.67%   |
| Dell                | 7        | 1.67%   |
| Acer                | 6        | 1.44%   |
| PC Engines          | 3        | 0.72%   |
| Fujitsu             | 3        | 0.72%   |
| Foxconn             | 3        | 0.72%   |
| Shuttle             | 2        | 0.48%   |
| Radxa               | 2        | 0.48%   |
| ECS                 | 2        | 0.48%   |
| YANYU               | 1        | 0.24%   |
| Wistron             | 1        | 0.24%   |
| VIA Technologies    | 1        | 0.24%   |
| TONK                | 1        | 0.24%   |
| Sun                 | 1        | 0.24%   |
| Stonesoft           | 1        | 0.24%   |
| Sony                | 1        | 0.24%   |
| Seeed Studio        | 1        | 0.24%   |
| QIYIDA              | 1        | 0.24%   |
| NITRINOnet          | 1        | 0.24%   |
| MW                  | 1        | 0.24%   |
| Maxtang             | 1        | 0.24%   |
| MACHINIST           | 1        | 0.24%   |
| Kraftway            | 1        | 0.24%   |
| Kontron             | 1        | 0.24%   |
| KOHJINSHA           | 1        | 0.24%   |
| khadas              | 1        | 0.24%   |
| Intel CNCTION-IAF   | 1        | 0.24%   |
| IceWhale Technology | 1        | 0.24%   |
| IBM                 | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 60       | 14.35%  |
| ASUS All Series                                                       | 12       | 2.87%   |
| Techvision TVI7309X                                                   | 7        | 1.67%   |
| PC Engines APU2                                                       | 3        | 0.72%   |
| Huanan X99-QD4 V1.0                                                   | 3        | 0.72%   |
| Gigabyte C1037UN-EU                                                   | 3        | 0.72%   |
| Supermicro SYS-6028R-TRT                                              | 2        | 0.48%   |
| Supermicro SSG-6029P-E1CR12L                                          | 2        | 0.48%   |
| Shuttle DS20U                                                         | 2        | 0.48%   |
| Pegatron SAISHIAT2                                                    | 2        | 0.48%   |
| MSI MS-7D46                                                           | 2        | 0.48%   |
| MSI MS-7B89                                                           | 2        | 0.48%   |
| MSI MS-7817                                                           | 2        | 0.48%   |
| Intel X79 V2.72A                                                      | 2        | 0.48%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 2        | 0.48%   |
| HP ProLiant MicroServer                                               | 2        | 0.48%   |
| HP Compaq Pro 6300 SFF                                                | 2        | 0.48%   |
| Gigabyte Z68XP-UD3                                                    | 2        | 0.48%   |
| Gigabyte M68MT-S2P                                                    | 2        | 0.48%   |
| Gigabyte H61M-S2PV                                                    | 2        | 0.48%   |
| Gigabyte H61M-DS2                                                     | 2        | 0.48%   |
| Gigabyte H310M S2 2.0                                                 | 2        | 0.48%   |
| Gigabyte GA-IMB370TN                                                  | 2        | 0.48%   |
| Gigabyte B450 AORUS M                                                 | 2        | 0.48%   |
| Gigabyte A320M-H                                                      | 2        | 0.48%   |
| Dell OptiPlex 7040                                                    | 2        | 0.48%   |
| ASUS PRIME Z590-P                                                     | 2        | 0.48%   |
| ASUS PRIME X370-PRO                                                   | 2        | 0.48%   |
| ASUS PRIME B550-PLUS                                                  | 2        | 0.48%   |
| ASUS P8Z77-V LX                                                       | 2        | 0.48%   |
| ASUS P6T SE                                                           | 2        | 0.48%   |
| ASUS P4P800-VM                                                        | 2        | 0.48%   |
| ASUS M5A97 R2.0                                                       | 2        | 0.48%   |
| ASRock Z690 PG Riptide                                                | 2        | 0.48%   |
| ASRock X570S PG Riptide                                               | 2        | 0.48%   |
| ASRock J4205-ITX                                                      | 2        | 0.48%   |
| YANYU H67SL                                                           | 1        | 0.24%   |
| Wistron ProLiant ML110 G6                                             | 1        | 0.24%   |
| VIA VT8623-8235                                                       | 1        | 0.24%   |
| TONK TN2800                                                           | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 60       | 14.35%  |
| ASUS PRIME                   | 13       | 3.11%   |
| ASUS All                     | 12       | 2.87%   |
| Techvision TVI7309X          | 7        | 1.67%   |
| Lenovo ThinkCentre           | 5        | 1.2%    |
| HP Compaq                    | 5        | 1.2%    |
| Dell OptiPlex                | 5        | 1.2%    |
| ASUS ROG                     | 5        | 1.2%    |
| HP ProLiant                  | 4        | 0.96%   |
| PC Engines APU2              | 3        | 0.72%   |
| Huanan X99-QD4               | 3        | 0.72%   |
| Gigabyte C1037UN-EU          | 3        | 0.72%   |
| Gigabyte B450M               | 3        | 0.72%   |
| ASUS TUF                     | 3        | 0.72%   |
| ASUS P8Z77-V                 | 3        | 0.72%   |
| ASUS P5Q                     | 3        | 0.72%   |
| ASRock Z690                  | 3        | 0.72%   |
| ASRock X570                  | 3        | 0.72%   |
| Acer Aspire                  | 3        | 0.72%   |
| Supermicro SYS-6028R-TRT     | 2        | 0.48%   |
| Supermicro SSG-6029P-E1CR12L | 2        | 0.48%   |
| Shuttle DS20U                | 2        | 0.48%   |
| Pegatron SAISHIAT2           | 2        | 0.48%   |
| MSI MS-7D46                  | 2        | 0.48%   |
| MSI MS-7B89                  | 2        | 0.48%   |
| MSI MS-7817                  | 2        | 0.48%   |
| Intel X79                    | 2        | 0.48%   |
| Huanan X99-F8D               | 2        | 0.48%   |
| Huanan X79                   | 2        | 0.48%   |
| HP ProDesk                   | 2        | 0.48%   |
| Gigabyte Z68XP-UD3           | 2        | 0.48%   |
| Gigabyte M68MT-S2P           | 2        | 0.48%   |
| Gigabyte H61M-S2PV           | 2        | 0.48%   |
| Gigabyte H61M-DS2            | 2        | 0.48%   |
| Gigabyte H310M               | 2        | 0.48%   |
| Gigabyte GA-IMB370TN         | 2        | 0.48%   |
| Gigabyte B450                | 2        | 0.48%   |
| Gigabyte A320M-H             | 2        | 0.48%   |
| Gigabyte 970A-DS3P           | 2        | 0.48%   |
| Fujitsu ESPRIMO              | 2        | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 42       | 10.05%  |
| 2022    | 38       | 9.09%   |
| 2019    | 36       | 8.61%   |
| 2021    | 31       | 7.42%   |
| Unknown | 30       | 7.18%   |
| 2011    | 27       | 6.46%   |
| 2013    | 26       | 6.22%   |
| 2010    | 25       | 5.98%   |
| 2020    | 22       | 5.26%   |
| 2012    | 21       | 5.02%   |
| 2009    | 19       | 4.55%   |
| 2014    | 17       | 4.07%   |
| 2017    | 16       | 3.83%   |
| 2008    | 13       | 3.11%   |
| 2007    | 13       | 3.11%   |
| 2016    | 11       | 2.63%   |
| 2015    | 11       | 2.63%   |
| 2023    | 7        | 1.67%   |
| 2006    | 5        | 1.2%    |
| 2005    | 5        | 1.2%    |
| 2004    | 3        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 418      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 415      | 99.28%  |
| Yes  | 3        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 104      | 24.47%  |
| 4.01-8.0        | 88       | 20.71%  |
| 16.01-24.0      | 88       | 20.71%  |
| 32.01-64.0      | 48       | 11.29%  |
| 2.01-3.0        | 31       | 7.29%   |
| 3.01-4.0        | 21       | 4.94%   |
| 64.01-256.0     | 16       | 3.76%   |
| 0.51-1.0        | 11       | 2.59%   |
| 24.01-32.0      | 7        | 1.65%   |
| 0.01-0.5        | 5        | 1.18%   |
| 1.01-2.0        | 4        | 0.94%   |
| More than 256.0 | 2        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 220      | 50.57%  |
| 0.51-1.0   | 105      | 24.14%  |
| 1.01-2.0   | 55       | 12.64%  |
| 3.01-4.0   | 10       | 2.3%    |
| Unknown    | 10       | 2.3%    |
| 4.01-8.0   | 9        | 2.07%   |
| 8.01-16.0  | 8        | 1.84%   |
| 2.01-3.0   | 6        | 1.38%   |
| 0          | 6        | 1.38%   |
| 16.01-24.0 | 4        | 0.92%   |
| 24.01-32.0 | 2        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 195      | 44.22%  |
| 2      | 92       | 20.86%  |
| 3      | 46       | 10.43%  |
| 0      | 45       | 10.2%   |
| 4      | 32       | 7.26%   |
| 5      | 15       | 3.4%    |
| 6      | 6        | 1.36%   |
| 7      | 4        | 0.91%   |
| 19     | 1        | 0.23%   |
| 14     | 1        | 0.23%   |
| 11     | 1        | 0.23%   |
| 10     | 1        | 0.23%   |
| 9      | 1        | 0.23%   |
| 8      | 1        | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 360      | 84.71%  |
| Yes       | 65       | 15.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 397      | 94.98%  |
| No        | 21       | 5.02%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 77.67%  |
| Yes       | 94       | 22.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 365      | 86.7%   |
| Yes       | 56       | 13.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 418      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 116      | 26.79%  |
| St Petersburg     | 52       | 12.01%  |
| Krasnodar         | 22       | 5.08%   |
| Yekaterinburg     | 15       | 3.46%   |
| Chelyabinsk       | 14       | 3.23%   |
| Novosibirsk       | 11       | 2.54%   |
| Vladivostok       | 8        | 1.85%   |
| Ozersk            | 8        | 1.85%   |
| Stavropol         | 7        | 1.62%   |
| Barnaul           | 7        | 1.62%   |
| Voronezh          | 6        | 1.39%   |
| Surgut            | 6        | 1.39%   |
| Omsk              | 6        | 1.39%   |
| Kamensk-Ural'skiy | 6        | 1.39%   |
| Saratov           | 5        | 1.15%   |
| Krasnoyarsk       | 5        | 1.15%   |
| Volgograd         | 4        | 0.92%   |
| Ufa               | 4        | 0.92%   |
| Podolsk           | 4        | 0.92%   |
| Penza             | 4        | 0.92%   |
| Lipetsk           | 4        | 0.92%   |
| Kirov             | 4        | 0.92%   |
| Cherepovets       | 4        | 0.92%   |
| Tambov            | 3        | 0.69%   |
| Perm              | 3        | 0.69%   |
| Orenburg          | 3        | 0.69%   |
| Nizhniy Novgorod  | 3        | 0.69%   |
| Khimki            | 3        | 0.69%   |
| Khabarovsk        | 3        | 0.69%   |
| Irkutsk           | 3        | 0.69%   |
| Volzhskiy         | 2        | 0.46%   |
| Vladimir          | 2        | 0.46%   |
| Vidnoye           | 2        | 0.46%   |
| Ulyanovsk         | 2        | 0.46%   |
| Smolensk          | 2        | 0.46%   |
| Samara            | 2        | 0.46%   |
| Rostov-on-Don     | 2        | 0.46%   |
| Reutov            | 2        | 0.46%   |
| Orsk              | 2        | 0.46%   |
| Odintsovo         | 2        | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 119      | 202    | 19.6%   |
| Seagate             | 113      | 260    | 18.62%  |
| Samsung Electronics | 66       | 95     | 10.87%  |
| Kingston            | 38       | 48     | 6.26%   |
| Toshiba             | 33       | 66     | 5.44%   |
| Hitachi             | 24       | 61     | 3.95%   |
| Intel               | 21       | 38     | 3.46%   |
| Crucial             | 15       | 22     | 2.47%   |
| A-DATA Technology   | 13       | 18     | 2.14%   |
| Apacer              | 9        | 11     | 1.48%   |
| AMD                 | 9        | 10     | 1.48%   |
| SPCC                | 8        | 9      | 1.32%   |
| Silicon Motion      | 8        | 12     | 1.32%   |
| KingSpec            | 8        | 11     | 1.32%   |
| HGST                | 8        | 21     | 1.32%   |
| Smartbuy            | 7        | 10     | 1.15%   |
| Plextor             | 7        | 10     | 1.15%   |
| Patriot             | 7        | 7      | 1.15%   |
| Maxtor              | 7        | 7      | 1.15%   |
| SanDisk             | 6        | 7      | 0.99%   |
| OPENBSD             | 5        | 12     | 0.82%   |
| OCZ                 | 5        | 5      | 0.82%   |
| Micron Technology   | 5        | 9      | 0.82%   |
| Transcend           | 4        | 4      | 0.66%   |
| Netac               | 4        | 4      | 0.66%   |
| Kston               | 4        | 4      | 0.66%   |
| Hewlett-Packard     | 4        | 7      | 0.66%   |
| Gigabyte Technology | 4        | 4      | 0.66%   |
| Team                | 3        | 3      | 0.49%   |
| Fujitsu             | 3        | 4      | 0.49%   |
| China               | 3        | 3      | 0.49%   |
| XrayDisk            | 2        | 2      | 0.33%   |
| XPG                 | 2        | 2      | 0.33%   |
| Verbatim            | 2        | 2      | 0.33%   |
| NVMe                | 2        | 7      | 0.33%   |
| Hoodisk             | 2        | 4      | 0.33%   |
| GOODRAM             | 2        | 2      | 0.33%   |
| FORESEE             | 2        | 2      | 0.33%   |
| XUNZHE              | 1        | 1      | 0.16%   |
| TAMMUZ              | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 9        | 1.28%   |
| Toshiba DT01ACA100 1TB             | 8        | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB       | 6        | 0.86%   |
| Kingston SA400S37240G 240GB        | 6        | 0.86%   |
| WDC WDS120G2G0A-00JH30 120GB       | 5        | 0.71%   |
| WDC WD20EARX-00PASB0 2TB           | 5        | 0.71%   |
| Seagate ST250DM000-1BD141 250GB    | 5        | 0.71%   |
| OPENBSD SR RAID 1 2TB              | 5        | 0.71%   |
| AMD R5SL120G 120GB                 | 5        | 0.71%   |
| A-DATA SU650 120GB                 | 5        | 0.71%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 4        | 0.57%   |
| Toshiba DT01ACA050 500GB           | 4        | 0.57%   |
| SPCC Solid State Disk 128GB        | 4        | 0.57%   |
| Seagate ST500DM002-1BD142 500GB    | 4        | 0.57%   |
| Seagate ST3300657SS 304GB          | 4        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4        | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB     | 4        | 0.57%   |
| Samsung SSD 970 EVO Plus 250GB     | 4        | 0.57%   |
| Samsung SSD 860 EVO 500GB          | 4        | 0.57%   |
| Samsung SSD 860 EVO 250GB          | 4        | 0.57%   |
| Kston SSD 128GB                    | 4        | 0.57%   |
| Kingston SA400S37120G 120GB        | 4        | 0.57%   |
| Intel SSDSC2BW480H6 480GB          | 4        | 0.57%   |
| WDC WDS500G1B0A-00H9H0 500GB       | 3        | 0.43%   |
| WDC WD800AAJS-00PSA0 80GB          | 3        | 0.43%   |
| WDC WD6400AARS-00Y5B1 640GB        | 3        | 0.43%   |
| WDC WD5000AZLX-00K2TA0 500GB       | 3        | 0.43%   |
| WDC WD10JFCX-68N6GN0 1TB           | 3        | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3        | 0.43%   |
| Silicon Motion NE-256 256GB        | 3        | 0.43%   |
| Seagate ST4000VN008-2DR166 4TB     | 3        | 0.43%   |
| Seagate ST380815AS 80GB            | 3        | 0.43%   |
| Seagate ST3500413AS 500GB          | 3        | 0.43%   |
| Seagate ST3250318AS 250GB          | 3        | 0.43%   |
| Seagate ST31000524AS 1TB           | 3        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB     | 3        | 0.43%   |
| Seagate ST2000DM001-1CH164 2TB     | 3        | 0.43%   |
| Seagate ST1000DM003-1SB10C 1TB     | 3        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB       | 3        | 0.43%   |
| Samsung SSD 870 QVO 1TB            | 3        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate                            | 113      | 260    | 36.22%  |
| WDC                                | 102      | 176    | 32.69%  |
| Toshiba                            | 31       | 64     | 9.94%   |
| Hitachi                            | 24       | 61     | 7.69%   |
| Samsung Electronics                | 11       | 17     | 3.53%   |
| HGST                               | 8        | 21     | 2.56%   |
| Maxtor                             | 7        | 7      | 2.24%   |
| OPENBSD                            | 5        | 12     | 1.6%    |
| Fujitsu                            | 3        | 4      | 0.96%   |
| NVMe                               | 2        | 7      | 0.64%   |
| Hewlett-Packard                    | 2        | 5      | 0.64%   |
| Product:              USB DISK 2.0 | 1        | 1      | 0.32%   |
| MaxDigital                         | 1        | 1      | 0.32%   |
| LSILOGIC                           | 1        | 1      | 0.32%   |
| IBM                                | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 37       | 44     | 15.88%  |
| Kingston            | 28       | 34     | 12.02%  |
| WDC                 | 18       | 20     | 7.73%   |
| Intel               | 15       | 26     | 6.44%   |
| Crucial             | 13       | 19     | 5.58%   |
| A-DATA Technology   | 10       | 13     | 4.29%   |
| KingSpec            | 8        | 11     | 3.43%   |
| SPCC                | 7        | 8      | 3%      |
| Smartbuy            | 7        | 10     | 3%      |
| Plextor             | 7        | 10     | 3%      |
| Apacer              | 7        | 8      | 3%      |
| AMD                 | 7        | 8      | 3%      |
| SanDisk             | 6        | 7      | 2.58%   |
| Patriot             | 6        | 6      | 2.58%   |
| OCZ                 | 5        | 5      | 2.15%   |
| Micron Technology   | 5        | 9      | 2.15%   |
| Transcend           | 4        | 4      | 1.72%   |
| Kston               | 4        | 4      | 1.72%   |
| Team                | 3        | 3      | 1.29%   |
| Netac               | 3        | 3      | 1.29%   |
| China               | 3        | 3      | 1.29%   |
| Verbatim            | 2        | 2      | 0.86%   |
| Toshiba             | 2        | 2      | 0.86%   |
| Hoodisk             | 2        | 4      | 0.86%   |
| Hewlett-Packard     | 2        | 2      | 0.86%   |
| Gigabyte Technology | 2        | 2      | 0.86%   |
| XUNZHE              | 1        | 1      | 0.43%   |
| XrayDisk            | 1        | 1      | 0.43%   |
| XPG                 | 1        | 1      | 0.43%   |
| TAMMUZ              | 1        | 1      | 0.43%   |
| SETHRISE            | 1        | 1      | 0.43%   |
| SATADOM             | 1        | 1      | 0.43%   |
| Qumo                | 1        | 1      | 0.43%   |
| Palit               | 1        | 1      | 0.43%   |
| MSI                 | 1        | 4      | 0.43%   |
| LuminouTek          | 1        | 1      | 0.43%   |
| LITEON              | 1        | 1      | 0.43%   |
| KingDian            | 1        | 3      | 0.43%   |
| Kingchuxing         | 1        | 1      | 0.43%   |
| HEORIADY            | 1        | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 235      | 638    | 46.44%  |
| SSD  | 204      | 293    | 40.32%  |
| NVMe | 67       | 105    | 13.24%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 353      | 931    | 84.05%  |
| NVMe | 67       | 105    | 15.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 297      | 492    | 62.13%  |
| 0.51-1.0   | 99       | 189    | 20.71%  |
| 1.01-2.0   | 38       | 145    | 7.95%   |
| 3.01-4.0   | 19       | 39     | 3.97%   |
| 4.01-10.0  | 13       | 30     | 2.72%   |
| 2.01-3.0   | 10       | 26     | 2.09%   |
| 10.01-20.0 | 2        | 10     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 124      | 27.93%  |
| 1-20           | 95       | 21.4%   |
| 251-500        | 77       | 17.34%  |
| 51-100         | 47       | 10.59%  |
| 21-50          | 34       | 7.66%   |
| 501-1000       | 32       | 7.21%   |
| More than 3000 | 15       | 3.38%   |
| 1001-2000      | 13       | 2.93%   |
| 2001-3000      | 4        | 0.9%    |
| Unknown        | 3        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 354      | 81.76%  |
| 21-50          | 34       | 7.85%   |
| 101-250        | 10       | 2.31%   |
| 51-100         | 8        | 1.85%   |
| More than 3000 | 7        | 1.62%   |
| 501-1000       | 7        | 1.62%   |
| 2001-3000      | 4        | 0.92%   |
| 1001-2000      | 4        | 0.92%   |
| Unknown        | 3        | 0.69%   |
| 251-500        | 2        | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Intel SSDSC2BW480H6 480GB           | 4        | 4      | 3.54%   |
| Samsung Electronics SSD 870 EVO 1TB | 3        | 7      | 2.65%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2        | 2      | 1.77%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2        | 2      | 1.77%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 2        | 2      | 1.77%   |
| Seagate ST3500413AS 500GB           | 2        | 4      | 1.77%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 1.77%   |
| Seagate ST250DM000-1BD141 250GB     | 2        | 4      | 1.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2        | 2      | 1.77%   |
| Samsung Electronics HD161HJ 160GB   | 2        | 3      | 1.77%   |
| Maxtor STM3320613AS 320GB           | 2        | 2      | 1.77%   |
| Kingston SA400S37120G 120GB         | 2        | 2      | 1.77%   |
| Hitachi HDS721010CLA332 1TB         | 2        | 4      | 1.77%   |
| XPG SX950U 240GB                    | 1        | 1      | 0.88%   |
| WDC WD800AAJS-00TDA0 80GB           | 1        | 1      | 0.88%   |
| WDC WD7501AALS-00E8B0 752GB         | 1        | 1      | 0.88%   |
| WDC WD7500AACS-00ZJB0 752GB         | 1        | 1      | 0.88%   |
| WDC WD60EFRX-68MYMN1 6TB            | 1        | 1      | 0.88%   |
| WDC WD5003AZEX-00MK2A0 500GB        | 1        | 1      | 0.88%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1        | 2      | 0.88%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1        | 1      | 0.88%   |
| WDC WD5000AZRZ-00HTKB0 500GB        | 1        | 1      | 0.88%   |
| WDC WD5000AZLX-00CL5A0 500GB        | 1        | 1      | 0.88%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 0.88%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1      | 0.88%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 3      | 0.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 0.88%   |
| WDC WD3200BEVT-00A0RT0 233GB        | 1        | 1      | 0.88%   |
| WDC WD3200AAKX-001CA0 320GB         | 1        | 1      | 0.88%   |
| WDC WD3200AAKS-00L9A0 320GB         | 1        | 1      | 0.88%   |
| WDC WD20EURX-63T0FY0 2TB            | 1        | 1      | 0.88%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 2      | 0.88%   |
| WDC WD1600YS-01SHB1 164GB           | 1        | 1      | 0.88%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1      | 0.88%   |
| WDC WD15EARS-00Z5B1 1.5TB           | 1        | 1      | 0.88%   |
| WDC WD15EADS-00P8B0 1.5TB           | 1        | 1      | 0.88%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1        | 1      | 0.88%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1        | 5      | 0.88%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 0.88%   |
| Transcend TS120GSSD220S 120GB       | 1        | 1      | 0.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 43     | 26.85%  |
| WDC                 | 28       | 39     | 25.93%  |
| Samsung Electronics | 10       | 16     | 9.26%   |
| Hitachi             | 8        | 12     | 7.41%   |
| Intel               | 7        | 7      | 6.48%   |
| Kingston            | 6        | 6      | 5.56%   |
| Toshiba             | 4        | 6      | 3.7%    |
| Maxtor              | 4        | 4      | 3.7%    |
| Plextor             | 2        | 2      | 1.85%   |
| XPG                 | 1        | 1      | 0.93%   |
| Transcend           | 1        | 1      | 0.93%   |
| SPCC                | 1        | 1      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |
| Hewlett-Packard     | 1        | 1      | 0.93%   |
| GLOWAY              | 1        | 2      | 0.93%   |
| GK                  | 1        | 1      | 0.93%   |
| Crucial             | 1        | 1      | 0.93%   |
| AMD                 | 1        | 2      | 0.93%   |
| A-DATA Technology   | 1        | 1      | 0.93%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 29       | 43     | 37.18%  |
| WDC                 | 26       | 37     | 33.33%  |
| Hitachi             | 8        | 12     | 10.26%  |
| Samsung Electronics | 5        | 7      | 6.41%   |
| Toshiba             | 4        | 6      | 5.13%   |
| Maxtor              | 4        | 4      | 5.13%   |
| HGST                | 1        | 1      | 1.28%   |
| Hewlett-Packard     | 1        | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 76       | 111    | 72.38%  |
| SSD  | 28       | 35     | 26.67%  |
| NVMe | 1        | 1      | 0.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                                | Desktops | Drives | Percent |
|--------------------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB          | 1        | 1      | 16.67%  |
| WDC WD6400AARS-00Y5B1 640GB          | 1        | 2      | 16.67%  |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1        | 1      | 16.67%  |
| Toshiba MG05ACA800E 8TB              | 1        | 1      | 16.67%  |
| Hitachi HDS721010DLE630 1TB          | 1        | 1      | 16.67%  |
| Crucial M4-CT256M4SSD1 256GB         | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 3        | 4      | 50%     |
| Toshiba | 1        | 1      | 16.67%  |
| Hitachi | 1        | 1      | 16.67%  |
| Crucial | 1        | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 314      | 814    | 69.47%  |
| Malfunc  | 101      | 147    | 22.35%  |
| Detected | 31       | 68     | 6.86%   |
| Failed   | 6        | 7      | 1.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 288      | 53.83%  |
| AMD                              | 78       | 14.58%  |
| Samsung Electronics              | 27       | 5.05%   |
| Silicon Motion                   | 19       | 3.55%   |
| Marvell Technology Group         | 18       | 3.36%   |
| JMicron Technology               | 15       | 2.8%    |
| ASMedia Technology               | 13       | 2.43%   |
| Nvidia                           | 11       | 2.06%   |
| Kingston Technology Company      | 10       | 1.87%   |
| Broadcom / LSI                   | 8        | 1.5%    |
| ADATA Technology                 | 6        | 1.12%   |
| SanDisk                          | 5        | 0.93%   |
| Realtek Semiconductor            | 5        | 0.93%   |
| Phison Electronics               | 4        | 0.75%   |
| Areca Technology                 | 4        | 0.75%   |
| VIA Technologies                 | 3        | 0.56%   |
| Micron/Crucial Technology        | 3        | 0.56%   |
| Toshiba                          | 2        | 0.37%   |
| Silicon Image                    | 2        | 0.37%   |
| Shenzhen Longsys Electronics     | 2        | 0.37%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.37%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.37%   |
| Integrated Technology Express    | 2        | 0.37%   |
| SK hynix                         | 1        | 0.19%   |
| Silicon Integrated Systems [SiS] | 1        | 0.19%   |
| Netac Technology                 | 1        | 0.19%   |
| Lite-On Technology               | 1        | 0.19%   |
| KIOXIA                           | 1        | 0.19%   |
| 3ware                            | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 38       | 5.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23       | 3.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21       | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 3.14%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 19       | 2.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 19       | 2.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18       | 2.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18       | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17       | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16       | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12       | 1.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 1.89%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 1.89%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 11       | 1.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 10       | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 1.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 9        | 1.42%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 9        | 1.42%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8        | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 8        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.26%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7        | 1.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 7        | 1.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7        | 1.1%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 6        | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 0.79%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 5        | 0.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5        | 0.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 0.79%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 0.79%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 5        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4        | 0.63%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 4        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 307      | 59.61%  |
| IDE  | 99       | 19.22%  |
| NVMe | 91       | 17.67%  |
| RAID | 8        | 1.55%   |
| SCSI | 6        | 1.17%   |
| SAS  | 4        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 298      | 70.78%  |
| AMD     | 88       | 20.9%   |
| ARM     | 26       | 6.18%   |
| Unknown | 6        | 1.43%   |
| VIA     | 1        | 0.24%   |
| PowerPC | 1        | 0.24%   |
| 7447A   | 1        | 0.24%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| ARM Cortex-A55 r2p0                      | 14       | 3.29%   |
| Intel Celeron N5105 @ 2.00GHz            | 7        | 1.64%   |
| AMD Ryzen 5 3600 6-Core Processor        | 6        | 1.41%   |
|                                          | 6        | 1.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 5        | 1.17%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 5        | 1.17%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 5        | 1.17%   |
| ARM Cortex-A57 r1p3                      | 5        | 1.17%   |
| Intel Core i5-7400 CPU @ 3.00GHz         | 4        | 0.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 4        | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 4        | 0.94%   |
| Intel Celeron CPU J1800 @ 2.41GHz        | 4        | 0.94%   |
| Intel Celeron CPU 1037U @ 1.80GHz        | 4        | 0.94%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz   | 3        | 0.7%    |
| Intel Pentium CPU G3220 @ 3.00GHz        | 3        | 0.7%    |
| Intel N100                               | 3        | 0.7%    |
| Intel Core i7-6700 CPU @ 3.40GHz         | 3        | 0.7%    |
| Intel Core i5-10400 CPU @ 2.90GHz        | 3        | 0.7%    |
| Intel Core i3-6100 CPU @ 3.70GHz         | 3        | 0.7%    |
| Intel Core i3-3220 CPU @ 3.30GHz         | 3        | 0.7%    |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz     | 3        | 0.7%    |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz     | 3        | 0.7%    |
| Intel Celeron N5100 @ 1.10GHz            | 3        | 0.7%    |
| Intel Celeron CPU J3455 @ 1.50GHz        | 3        | 0.7%    |
| AMD Ryzen 9 3900X 12-Core Processor      | 3        | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor      | 3        | 0.7%    |
| AMD GX-412TC SOC                         | 3        | 0.7%    |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz      | 2        | 0.47%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz      | 2        | 0.47%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz      | 2        | 0.47%   |
| Intel Xeon CPU E31270 @ 3.40GHz          | 2        | 0.47%   |
| Intel Xeon CPU E3-1265L V2 @ 2.50GHz     | 2        | 0.47%   |
| Intel Xeon Bronze 3104 CPU @ 1.70GHz     | 2        | 0.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 2        | 0.47%   |
| Intel Pentium Gold G5400T CPU @ 3.10GHz  | 2        | 0.47%   |
| Intel Pentium CPU J4205 @ 1.50GHz        | 2        | 0.47%   |
| Intel Pentium CPU G850 @ 2.90GHz         | 2        | 0.47%   |
| Intel Pentium 4 CPU                      | 2        | 0.47%   |
| Intel Core i9-9900K CPU @ 3.60GHz        | 2        | 0.47%   |
| Intel Core i7-7700 CPU @ 3.60GHz         | 2        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 55       | 13.06%  |
| Intel Core i5           | 43       | 10.21%  |
| Intel Xeon              | 34       | 8.08%   |
| Intel Core i7           | 30       | 7.13%   |
| Intel Core i3           | 30       | 7.13%   |
| ARM Cortex              | 26       | 6.18%   |
| Other                   | 20       | 4.75%   |
| AMD Ryzen 5             | 18       | 4.28%   |
| Intel Core 2 Duo        | 16       | 3.8%    |
| Intel Atom              | 14       | 3.33%   |
| Intel Pentium           | 13       | 3.09%   |
| Intel Core 2 Quad       | 13       | 3.09%   |
| AMD Ryzen 7             | 10       | 2.38%   |
| AMD FX                  | 8        | 1.9%    |
| Intel Pentium 4         | 7        | 1.66%   |
| Intel Pentium Gold      | 5        | 1.19%   |
| AMD Ryzen 9             | 5        | 1.19%   |
| AMD Ryzen 3             | 5        | 1.19%   |
| AMD Phenom II X4        | 5        | 1.19%   |
| Intel Pentium Dual-Core | 4        | 0.95%   |
| AMD GX                  | 4        | 0.95%   |
| Intel Pentium Dual      | 3        | 0.71%   |
| Intel Pentium D         | 3        | 0.71%   |
| Intel Genuine           | 3        | 0.71%   |
| Intel Core i9           | 3        | 0.71%   |
| Intel Core 2            | 3        | 0.71%   |
| AMD Athlon 64 X2        | 3        | 0.71%   |
| AMD A4                  | 3        | 0.71%   |
| Intel Xeon Bronze       | 2        | 0.48%   |
| Intel Pentium Silver    | 2        | 0.48%   |
| Intel Celeron D         | 2        | 0.48%   |
| Intel 686-class         | 2        | 0.48%   |
| AMD Turion II Neo       | 2        | 0.48%   |
| AMD Sempron             | 2        | 0.48%   |
| AMD Ryzen 5 PRO         | 2        | 0.48%   |
| AMD Phenom II X6        | 2        | 0.48%   |
| AMD Phenom              | 2        | 0.48%   |
| AMD E                   | 2        | 0.48%   |
| AMD Athlon X4           | 2        | 0.48%   |
| AMD Athlon II X3        | 2        | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 143      | 33.97%  |
| 2       | 94       | 22.33%  |
| Unknown | 69       | 16.39%  |
| 6       | 37       | 8.79%   |
| 8       | 20       | 4.75%   |
| 12      | 18       | 4.28%   |
| 1       | 16       | 3.8%    |
| 16      | 10       | 2.38%   |
| 24      | 5        | 1.19%   |
| 28      | 2        | 0.48%   |
| 14      | 2        | 0.48%   |
| 3       | 2        | 0.48%   |
| 32      | 1        | 0.24%   |
| 20      | 1        | 0.24%   |
| 18      | 1        | 0.24%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 372      | 88.36%  |
| Unknown | 41       | 9.74%   |
| 2       | 8        | 1.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 224      | 53.08%  |
| 2       | 119      | 28.2%   |
| Unknown | 79       | 18.72%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Unknown       | 63       | 14.96%  |
| KabyLake      | 40       | 9.5%    |
| IvyBridge     | 31       | 7.36%   |
| SandyBridge   | 29       | 6.89%   |
| Haswell       | 28       | 6.65%   |
| Penryn        | 26       | 6.18%   |
| Zen 2         | 18       | 4.28%   |
| Core          | 17       | 4.04%   |
| Silvermont    | 16       | 3.8%    |
| K10           | 16       | 3.8%    |
| Skylake       | 14       | 3.33%   |
| NetBurst      | 12       | 2.85%   |
| Bonnell       | 11       | 2.61%   |
| Piledriver    | 10       | 2.38%   |
| Goldmont      | 10       | 2.38%   |
| CometLake     | 10       | 2.38%   |
| Zen           | 9        | 2.14%   |
| Nehalem       | 9        | 2.14%   |
| Zen 3         | 8        | 1.9%    |
| Zen+          | 7        | 1.66%   |
| Goldmont plus | 7        | 1.66%   |
| K8 Hammer     | 6        | 1.43%   |
| Broadwell     | 6        | 1.43%   |
| Bulldozer     | 4        | 0.95%   |
| Westmere      | 3        | 0.71%   |
| Puma          | 3        | 0.71%   |
| Bobcat        | 3        | 0.71%   |
| Jaguar        | 2        | 0.48%   |
| Steamroller   | 1        | 0.24%   |
| P6            | 1        | 0.24%   |
| Geode         | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 182      | 46.19%  |
| Nvidia                                       | 115      | 29.19%  |
| AMD                                          | 82       | 20.81%  |
| ASPEED Technology                            | 9        | 2.28%   |
| Matrox Electronics Systems                   | 3        | 0.76%   |
| VIA Technologies                             | 2        | 0.51%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.25%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12       | 2.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 2.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 2.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11       | 2.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10       | 2.48%   |
| Intel JasperLake [UHD Graphics]                                                          | 10       | 2.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10       | 2.48%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9        | 2.23%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 9        | 2.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7        | 1.73%   |
| Intel HD Graphics 530                                                                    | 7        | 1.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7        | 1.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7        | 1.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 1.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6        | 1.49%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 1.24%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 5        | 1.24%   |
| Intel HD Graphics 630                                                                    | 5        | 1.24%   |
| Intel HD Graphics 500                                                                    | 5        | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5        | 1.24%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 5        | 1.24%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5        | 1.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5        | 1.24%   |
| AMD ES1000                                                                               | 5        | 1.24%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 0.99%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4        | 0.99%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 4        | 0.99%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 4        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 0.99%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 4        | 0.99%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 4        | 0.99%   |
| Intel 82865G Integrated Graphics Controller                                              | 4        | 0.99%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 4        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 0.74%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3        | 0.74%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 3        | 0.74%   |
| Intel UHD Graphics 620                                                                   | 3        | 0.74%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 3        | 0.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 162      | 38.48%  |
| 1 x Nvidia               | 108      | 25.65%  |
| 1 x AMD                  | 69       | 16.39%  |
| Other                    | 39       | 9.26%   |
| 2 x Intel                | 10       | 2.38%   |
| 1 x ASPEED               | 9        | 2.14%   |
| 2 x AMD                  | 7        | 1.66%   |
| Intel + AMD              | 5        | 1.19%   |
| Intel + Nvidia           | 4        | 0.95%   |
| 1 x Matrox               | 3        | 0.71%   |
| 1 x VIA                  | 2        | 0.48%   |
| 1 x XGI                  | 1        | 0.24%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.24%   |
| AMD + Nvidia             | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 306      | 72.34%  |
| Proprietary | 69       | 16.31%  |
| Unknown     | 48       | 11.35%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 323      | 76.54%  |
| 0.51-1.0   | 24       | 5.69%   |
| 3.01-4.0   | 21       | 4.98%   |
| 1.01-2.0   | 21       | 4.98%   |
| 0.01-0.5   | 10       | 2.37%   |
| 7.01-8.0   | 9        | 2.13%   |
| 5.01-6.0   | 8        | 1.9%    |
| 8.01-16.0  | 4        | 0.95%   |
| 2.01-3.0   | 2        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 38       | 22.75%  |
| Goldstar             | 23       | 13.77%  |
| Dell                 | 14       | 8.38%   |
| Philips              | 12       | 7.19%   |
| ViewSonic            | 11       | 6.59%   |
| BenQ                 | 10       | 5.99%   |
| Ancor Communications | 10       | 5.99%   |
| Acer                 | 10       | 5.99%   |
| NEC Computers        | 7        | 4.19%   |
| AOC                  | 7        | 4.19%   |
| Sony                 | 4        | 2.4%    |
| LG Electronics       | 4        | 2.4%    |
| Hewlett-Packard      | 4        | 2.4%    |
| RTK                  | 2        | 1.2%    |
| Iiyama               | 2        | 1.2%    |
| Fujitsu Siemens      | 2        | 1.2%    |
| Unknown (CDD)        | 1        | 0.6%    |
| Panasonic            | 1        | 0.6%    |
| Microstep            | 1        | 0.6%    |
| Lenovo               | 1        | 0.6%    |
| InfoVision           | 1        | 0.6%    |
| Daewoo               | 1        | 0.6%    |
| Unknown              | 1        | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 4        | 2.27%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 3        | 1.7%    |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 2        | 1.14%   |
| Samsung Electronics SyncMaster SAM027D 1680x1050 430x270mm 20.0-inch   | 2        | 1.14%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 2        | 1.14%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch     | 2        | 1.14%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 2        | 1.14%   |
| Samsung Electronics LCD Monitor SAM0AC6 1920x1080 1110x620mm 50.1-inch | 2        | 1.14%   |
| RTK WCS Display RTK1A1B 1920x1080 344x195mm 15.6-inch                  | 2        | 1.14%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 2        | 1.14%   |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                     | 2        | 1.14%   |
| NEC Computers FE791SB NEC61D7 1600x1200 330x240mm 16.1-inch            | 2        | 1.14%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 2        | 1.14%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 2        | 1.14%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 2        | 1.14%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 2        | 1.14%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch             | 1        | 0.57%   |
| ViewSonic VP171s-2 VSC4B1B 1280x1024 340x270mm 17.1-inch               | 1        | 0.57%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch          | 1        | 0.57%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch          | 1        | 0.57%   |
| ViewSonic VA2710-FHD VSCA736 1920x1080 600x340mm 27.2-inch             | 1        | 0.57%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch             | 1        | 0.57%   |
| ViewSonic LCD Monitor VX2451 SERIES 1920x1080                          | 1        | 0.57%   |
| ViewSonic LCD Monitor VSC8724 1440x900 410x260mm 19.1-inch             | 1        | 0.57%   |
| ViewSonic LCD Monitor VSC5826 1366x768 410x230mm 18.5-inch             | 1        | 0.57%   |
| ViewSonic LCD Monitor VSC2528 1920x1080 520x290mm 23.4-inch            | 1        | 0.57%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch               | 1        | 0.57%   |
| Sony TV  *00 SNY8204 3840x2160 1220x680mm 55.0-inch                    | 1        | 0.57%   |
| Sony TV  *00 SNY7C04 3840x2160 1080x610mm 48.8-inch                    | 1        | 0.57%   |
| Sony SDM-S75D/F/N SNY3800 1280x1024 340x270mm 17.1-inch                | 1        | 0.57%   |
| Sony SDM-E76D SNYB200 1280x1024 340x270mm 17.1-inch                    | 1        | 0.57%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 700x390mm 31.5-inch      | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 380x300mm 19.1-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x260mm 19.1-inch    | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM01BB 1280x1024 380x300mm 19.1-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 380x300mm 19.1-inch   | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 340x270mm 17.1-inch   | 1        | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 72       | 44.17%  |
| 1280x1024 (SXGA)   | 29       | 17.79%  |
| 3840x2160 (4K)     | 12       | 7.36%   |
| 1680x1050 (WSXGA+) | 9        | 5.52%   |
| 1440x900 (WXGA+)   | 9        | 5.52%   |
| 1920x1200 (WUXGA)  | 8        | 4.91%   |
| 1600x900 (HD+)     | 7        | 4.29%   |
| 2560x1440 (QHD)    | 5        | 3.07%   |
| 1366x768 (WXGA)    | 5        | 3.07%   |
| 1600x1200          | 2        | 1.23%   |
| Unknown            | 2        | 1.23%   |
| 3440x1440          | 1        | 0.61%   |
| 2560x1080          | 1        | 0.61%   |
| 1024x768 (XGA)     | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 25       | 14.88%  |
| 21      | 23       | 13.69%  |
| 19      | 22       | 13.1%   |
| 17      | 18       | 10.71%  |
| Unknown | 18       | 10.71%  |
| 27      | 16       | 9.52%   |
| 23      | 14       | 8.33%   |
| 22      | 5        | 2.98%   |
| 20      | 5        | 2.98%   |
| 18      | 5        | 2.98%   |
| 31      | 3        | 1.79%   |
| 50      | 2        | 1.19%   |
| 16      | 2        | 1.19%   |
| 15      | 2        | 1.19%   |
| 57      | 1        | 0.6%    |
| 55      | 1        | 0.6%    |
| 52      | 1        | 0.6%    |
| 48      | 1        | 0.6%    |
| 34      | 1        | 0.6%    |
| 26      | 1        | 0.6%    |
| 14      | 1        | 0.6%    |
| 12      | 1        | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 33.13%  |
| 401-500     | 50       | 30.12%  |
| 301-350     | 22       | 13.25%  |
| Unknown     | 18       | 10.84%  |
| 351-400     | 9        | 5.42%   |
| 1001-1500   | 6        | 3.61%   |
| 601-700     | 3        | 1.81%   |
| 201-300     | 2        | 1.2%    |
| 701-800     | 1        | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 92       | 56.1%   |
| 5/4     | 26       | 15.85%  |
| 16/10   | 26       | 15.85%  |
| Unknown | 16       | 9.76%   |
| 4/3     | 3        | 1.83%   |
| 21/9    | 1        | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 59       | 34.91%  |
| 151-200        | 29       | 17.16%  |
| 141-150        | 22       | 13.02%  |
| Unknown        | 18       | 10.65%  |
| 301-350        | 17       | 10.06%  |
| 251-300        | 8        | 4.73%   |
| More than 1000 | 6        | 3.55%   |
| 351-500        | 4        | 2.37%   |
| 101-110        | 3        | 1.78%   |
| 121-130        | 2        | 1.18%   |
| 61-70          | 1        | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 103      | 62.05%  |
| 101-120 | 25       | 15.06%  |
| Unknown | 18       | 10.84%  |
| 121-160 | 10       | 6.02%   |
| 161-240 | 6        | 3.61%   |
| 1-50    | 4        | 2.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 254      | 59.48%  |
| 1     | 161      | 37.7%   |
| 2     | 11       | 2.58%   |
| 3     | 1        | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 246      | 46.42%  |
| Intel                             | 154      | 29.06%  |
| Qualcomm Atheros                  | 46       | 8.68%   |
| Broadcom                          | 16       | 3.02%   |
| Marvell Technology Group          | 9        | 1.7%    |
| D-Link System                     | 8        | 1.51%   |
| VIA Technologies                  | 7        | 1.32%   |
| Huawei Technologies               | 6        | 1.13%   |
| TP-Link                           | 3        | 0.57%   |
| Ralink                            | 3        | 0.57%   |
| IMC Networks                      | 3        | 0.57%   |
| 3Com                              | 3        | 0.57%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.38%   |
| Samsung Electronics               | 2        | 0.38%   |
| Ralink Technology                 | 2        | 0.38%   |
| Qualcomm Atheros Communications   | 2        | 0.38%   |
| Qualcomm                          | 2        | 0.38%   |
| D-Link                            | 2        | 0.38%   |
| Sundance Technology Inc / IC Plus | 1        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.19%   |
| Qcom                              | 1        | 0.19%   |
| OPPO Electronics                  | 1        | 0.19%   |
| Nvidia                            | 1        | 0.19%   |
| MYRICOM                           | 1        | 0.19%   |
| Mercucys                          | 1        | 0.19%   |
| Mellanox Technologies             | 1        | 0.19%   |
| Edimax Technology                 | 1        | 0.19%   |
| Atmel                             | 1        | 0.19%   |
| ASUSTek Computer                  | 1        | 0.19%   |
| Aquantia                          | 1        | 0.19%   |
| Apple                             | 1        | 0.19%   |
| Accton Technology                 | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 196      | 32.03%  |
| Realtek RTL8125 2.5GbE Controller                                             | 21       | 3.43%   |
| Intel I211 Gigabit Network Connection                                         | 21       | 3.43%   |
| Intel 82574L Gigabit Network Connection                                       | 21       | 3.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 11       | 1.8%    |
| Intel Ethernet Controller I225-V                                              | 11       | 1.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 1.63%   |
| Intel I350 Gigabit Network Connection                                         | 10       | 1.63%   |
| Intel Ethernet Controller I226-V                                              | 9        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 1.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 7        | 1.14%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 1.14%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 6        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 0.98%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 5        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5        | 0.82%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 0.82%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 4        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.65%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 4        | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 4        | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 4        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 4        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4        | 0.65%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.65%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 0.65%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 0.65%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.65%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 3        | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3        | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 3        | 0.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.49%   |
| Intel Wireless 7265                                                           | 3        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 28       | 28%     |
| Realtek Semiconductor           | 24       | 24%     |
| Qualcomm Atheros                | 24       | 24%     |
| Broadcom                        | 5        | 5%      |
| TP-Link                         | 3        | 3%      |
| Ralink                          | 3        | 3%      |
| IMC Networks                    | 3        | 3%      |
| Ralink Technology               | 2        | 2%      |
| Qualcomm Atheros Communications | 2        | 2%      |
| D-Link                          | 2        | 2%      |
| Qcom                            | 1        | 1%      |
| Mercucys                        | 1        | 1%      |
| Edimax Technology               | 1        | 1%      |
| ASUSTek Computer                | 1        | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 7        | 6.93%   |
| Intel Wi-Fi 6 AX200                                                                  | 5        | 4.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 4        | 3.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 4        | 3.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 3        | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 3        | 2.97%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 3        | 2.97%   |
| Intel Wireless 7265                                                                  | 3        | 2.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                             | 2        | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 2        | 1.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                      | 2        | 1.98%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 2        | 1.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 2        | 1.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 2        | 1.98%   |
| Intel Wireless 8265 / 8275                                                           | 2        | 1.98%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                            | 2        | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 2        | 1.98%   |
| Intel CNVi: Wi-Fi                                                                    | 2        | 1.98%   |
| Intel Centrino Wireless-N 2230                                                       | 2        | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 2        | 1.98%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter          | 2        | 1.98%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                         | 2        | 1.98%   |
| TP-Link Wireless USB Adapter                                                         | 1        | 0.99%   |
| TP-Link Wireless MU-MIMO USB Adapter                                                 | 1        | 0.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1        | 0.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                          | 1        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 1        | 0.99%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 1        | 0.99%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 1        | 0.99%   |
| Realtek Bluetooth Adapter                                                            | 1        | 0.99%   |
| Realtek 802.11n WLAN Adapter                                                         | 1        | 0.99%   |
| Ralink RT5370 Wireless Adapter                                                       | 1        | 0.99%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 1        | 0.99%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 1        | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                            | 1        | 0.99%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 1        | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 1        | 0.99%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1        | 0.99%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271]        | 1        | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 241      | 52.51%  |
| Intel                             | 141      | 30.72%  |
| Qualcomm Atheros                  | 23       | 5.01%   |
| Broadcom                          | 11       | 2.4%    |
| Marvell Technology Group          | 9        | 1.96%   |
| D-Link System                     | 8        | 1.74%   |
| VIA Technologies                  | 7        | 1.53%   |
| 3Com                              | 3        | 0.65%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.44%   |
| Samsung Electronics               | 2        | 0.44%   |
| Qualcomm                          | 2        | 0.44%   |
| Huawei Technologies               | 2        | 0.44%   |
| Sundance Technology Inc / IC Plus | 1        | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.22%   |
| OPPO Electronics                  | 1        | 0.22%   |
| Nvidia                            | 1        | 0.22%   |
| MYRICOM                           | 1        | 0.22%   |
| Aquantia                          | 1        | 0.22%   |
| Apple                             | 1        | 0.22%   |
| Accton Technology                 | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 196      | 38.81%  |
| Realtek RTL8125 2.5GbE Controller                                             | 21       | 4.16%   |
| Intel I211 Gigabit Network Connection                                         | 21       | 4.16%   |
| Intel 82574L Gigabit Network Connection                                       | 21       | 4.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 11       | 2.18%   |
| Intel Ethernet Controller I225-V                                              | 11       | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10       | 1.98%   |
| Intel I350 Gigabit Network Connection                                         | 10       | 1.98%   |
| Intel Ethernet Controller I226-V                                              | 9        | 1.78%   |
| Intel Ethernet Connection (2) I219-V                                          | 8        | 1.58%   |
| Intel I210 Gigabit Network Connection                                         | 7        | 1.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 6        | 1.19%   |
| Intel 82579V Gigabit Network Connection                                       | 6        | 1.19%   |
| VIA VT6105/VT6106S [Rhine-III]                                                | 5        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5        | 0.99%   |
| Intel 82583V Gigabit Network Connection                                       | 5        | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 0.99%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 4        | 0.79%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 4        | 0.79%   |
| Realtek Killer E3000 2.5GbE Controller                                        | 4        | 0.79%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 4        | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 4        | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 4        | 0.79%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 4        | 0.79%   |
| Intel Ethernet Connection I217-V                                              | 4        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                          | 4        | 0.79%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 4        | 0.79%   |
| Intel 82576 Gigabit Network Connection                                        | 4        | 0.79%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 4        | 0.79%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 4        | 0.79%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 3        | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                                         | 3        | 0.59%   |
| Intel Ethernet Connection (17) I219-V                                         | 3        | 0.59%   |
| Intel 82572EI Gigabit Ethernet Controller (Copper)                            | 3        | 0.59%   |
| Intel 82562EZ 10/100 Ethernet Controller                                      | 3        | 0.59%   |
| Intel 82540EM Gigabit Ethernet Controller                                     | 3        | 0.59%   |
| Broadcom NetXtreme BCM5723 Gigabit Ethernet PCIe                              | 3        | 0.59%   |
| ZTE WCDMA MSM Remote NDIS based Internet Sharing Device                       | 2        | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 2        | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 397      | 79.88%  |
| WiFi     | 94       | 18.91%  |
| Unknown  | 5        | 1.01%   |
| Modem    | 1        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 351      | 91.64%  |
| WiFi     | 31       | 8.09%   |
| Unknown  | 1        | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 193      | 45.2%   |
| 2     | 107      | 25.06%  |
| 3     | 44       | 10.3%   |
| 0     | 36       | 8.43%   |
| 4     | 25       | 5.85%   |
| 6     | 9        | 2.11%   |
| 5     | 5        | 1.17%   |
| 7     | 3        | 0.7%    |
| 9     | 2        | 0.47%   |
| 8     | 2        | 0.47%   |
| 12    | 1        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 407      | 95.99%  |
| Yes  | 17       | 4.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 44.83%  |
| Cambridge Silicon Radio         | 7        | 12.07%  |
| Realtek Semiconductor           | 5        | 8.62%   |
| IMC Networks                    | 5        | 8.62%   |
| Qualcomm Atheros Communications | 4        | 6.9%    |
| ASUSTek Computer                | 3        | 5.17%   |
| Apple                           | 2        | 3.45%   |
| Silicon Wave                    | 1        | 1.72%   |
| Ralink                          | 1        | 1.72%   |
| Lite-On Technology              | 1        | 1.72%   |
| Foxconn / Hon Hai               | 1        | 1.72%   |
| Edimax Technology               | 1        | 1.72%   |
| Broadcom                        | 1        | 1.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                          | 8        | 13.56%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 7        | 11.86%  |
| Intel AX200 Bluetooth                                       | 6        | 10.17%  |
| Realtek Bluetooth Adapter                                   | 4        | 6.78%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3        | 5.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 5.08%   |
| Intel AX201 Bluetooth                                       | 3        | 5.08%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0          | 3        | 5.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2        | 3.39%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 3.39%   |
| Intel AX210 Bluetooth                                       | 2        | 3.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 2        | 3.39%   |
| Silicon Wave Bluetooth Wireless Adapter                     | 1        | 1.69%   |
| Realtek Bluetooth 4.0 Adapter                               | 1        | 1.69%   |
| Ralink RT3290 Bluetooth                                     | 1        | 1.69%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 1.69%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 1.69%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 1.69%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1        | 1.69%   |
| IMC Networks Realtek Bluetooth 4.0 + High Speed Chip        | 1        | 1.69%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 1.69%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1        | 1.69%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter            | 1        | 1.69%   |
| ASUS Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter     | 1        | 1.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.69%   |
| Apple Bluetooth Host Controller                             | 1        | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 244      | 51.15%  |
| Nvidia                                       | 94       | 19.71%  |
| AMD                                          | 90       | 18.87%  |
| C-Media Electronics                          | 6        | 1.26%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.84%   |
| VIA Technologies                             | 4        | 0.84%   |
| Realtek Semiconductor                        | 4        | 0.84%   |
| JMTek                                        | 4        | 0.84%   |
| Texas Instruments                            | 3        | 0.63%   |
| Logitech                                     | 3        | 0.63%   |
| Creative Technology                          | 3        | 0.63%   |
| Creative Labs                                | 3        | 0.63%   |
| Xilinx                                       | 1        | 0.21%   |
| SteelSeries ApS                              | 1        | 0.21%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.21%   |
| Samsung Electronics                          | 1        | 0.21%   |
| Microsoft                                    | 1        | 0.21%   |
| M-Audio                                      | 1        | 0.21%   |
| KTMicro                                      | 1        | 0.21%   |
| HECATE G2 GAMING HEADSET                     | 1        | 0.21%   |
| GN Netcom                                    | 1        | 0.21%   |
| Generalplus Technology                       | 1        | 0.21%   |
| FiiO Electronics Technology                  | 1        | 0.21%   |
| ESS Technology                               | 1        | 0.21%   |
| Edifier Technology                           | 1        | 0.21%   |
| Cambridge Silicon Radio                      | 1        | 0.21%   |
| Unknown                                      | 1        | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 25       | 4.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23       | 4.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20       | 3.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 19       | 3.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 19       | 3.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 17       | 3.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 15       | 2.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 2.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 13       | 2.46%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 12       | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 12       | 2.27%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11       | 2.08%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 1.89%   |
| Intel Jasper Lake HD Audio                                                 | 10       | 1.89%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8        | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 8        | 1.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                              | 7        | 1.33%   |
| Nvidia High Definition Audio Controller                                    | 7        | 1.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7        | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7        | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6        | 1.14%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 1.14%   |
| Nvidia GP108 High Definition Audio Controller                              | 5        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                  | 5        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 5        | 0.95%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 0.95%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 0.95%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 4        | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4        | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 4        | 0.76%   |
| Nvidia GA102 High Definition Audio Controller                              | 4        | 0.76%   |
| JMTek USB PnP Audio Device                                                 | 4        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Unknown                                 | 86       | 21.88%  |
| Kingston                                | 81       | 20.61%  |
| Samsung Electronics                     | 39       | 9.92%   |
| Crucial                                 | 27       | 6.87%   |
| SK hynix                                | 20       | 5.09%   |
| Unknown                                 | 19       | 4.83%   |
| Micron Technology                       | 16       | 4.07%   |
| Patriot                                 | 12       | 3.05%   |
| AMD                                     | 12       | 3.05%   |
| Corsair                                 | 10       | 2.54%   |
| A-DATA Technology                       | 8        | 2.04%   |
| G.Skill                                 | 7        | 1.78%   |
| Patriot Memory (PDP Systems)            | 5        | 1.27%   |
| Atermiter                               | 5        | 1.27%   |
| Unknown (ABCD)                          | 4        | 1.02%   |
| Ramaxel Technology                      | 4        | 1.02%   |
| Nanya Technology                        | 4        | 1.02%   |
| Apacer                                  | 4        | 1.02%   |
| Transcend                               | 3        | 0.76%   |
| Goldkey                                 | 3        | 0.76%   |
| Unifosa                                 | 2        | 0.51%   |
| Silicon Power Computer & Communications | 2        | 0.51%   |
| Qumo                                    | 2        | 0.51%   |
| Netac                                   | 2        | 0.51%   |
| Kllisre                                 | 2        | 0.51%   |
| Kingmax                                 | 2        | 0.51%   |
| Elpida                                  | 2        | 0.51%   |
| Unknown (0x0DD5)                        | 1        | 0.25%   |
| Tigo                                    | 1        | 0.25%   |
| Silicon Power                           | 1        | 0.25%   |
| S                                       | 1        | 0.25%   |
| Ramos Technology                        | 1        | 0.25%   |
| PDPSystems                              | 1        | 0.25%   |
| Innodisk                                | 1        | 0.25%   |
| H                                       | 1        | 0.25%   |
| GOODRAM                                 | 1        | 0.25%   |
| Foxline                                 | 1        | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| Unknown                                                                  | 19       | 4.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                     | 9        | 2.05%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 6        | 1.37%   |
| Unknown RAM Module 2GB DIMM SDRAM                                        | 5        | 1.14%   |
| Unknown RAM Module 1GB DIMM SDRAM                                        | 5        | 1.14%   |
| Unknown RAM Module 512MB DIMM SDRAM                                      | 4        | 0.91%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                              | 4        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s             | 4        | 0.91%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 3        | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                                 | 3        | 0.68%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                      | 3        | 0.68%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                      | 3        | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 3        | 0.68%   |
| G.Skill RAM F4-4000C18-32GVK 32GB DIMM DDR4 4000MT/s                     | 3        | 0.68%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s                    | 3        | 0.68%   |
| AMD RAM R748G2400U2S 8GB DIMM DDR4 2400MT/s                              | 3        | 0.68%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3400MT/s                              | 3        | 0.68%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                                  | 2        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                                | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                                | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                 | 2        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 2        | 0.46%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                               | 2        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 400MT/s                                 | 2        | 0.46%   |
| Unknown RAM Module 1GB DIMM 1333MT/s                                     | 2        | 0.46%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                     | 2        | 0.46%   |
| Transcend RAM JM2666HLE-32G 32GB DIMM DDR4 2666MT/s                      | 2        | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s                     | 2        | 0.46%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                   | 2        | 0.46%   |
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s                        | 2        | 0.46%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                    | 2        | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                    | 2        | 0.46%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s                     | 2        | 0.46%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s                     | 2        | 0.46%   |
| Patriot Memory (PDP Systems) RAM PSD416G320081 16GB DIMM DDR4 3200MT/s   | 2        | 0.46%   |
| Patriot Memory (PDP Systems) RAM 3200 C16 Series 32GB DIMM DDR4 2667MT/s | 2        | 0.46%   |
| Netac RAM Module 8GB SODIMM DDR4 2667MT/s                                | 2        | 0.46%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 0.46%   |
| Kingston RAM Module 1GB DIMM DDR2 800MT/s                                | 2        | 0.46%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3200MT/s                    | 2        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 136      | 39.08%  |
| DDR3    | 116      | 33.33%  |
| Unknown | 34       | 9.77%   |
| DDR2    | 27       | 7.76%   |
| SDRAM   | 19       | 5.46%   |
| DDR     | 9        | 2.59%   |
| LPDDR4  | 4        | 1.15%   |
| DDR5    | 2        | 0.57%   |
| LPDDR5  | 1        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 292      | 84.15%  |
| SODIMM       | 54       | 15.56%  |
| Row Of Chips | 1        | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 99       | 25.85%  |
| 4096  | 93       | 24.28%  |
| 2048  | 75       | 19.58%  |
| 16384 | 51       | 13.32%  |
| 1024  | 31       | 8.09%   |
| 32768 | 19       | 4.96%   |
| 512   | 13       | 3.39%   |
| 256   | 1        | 0.26%   |
| 8     | 1        | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 58       | 15.98%  |
| 1333    | 58       | 15.98%  |
| 3200    | 47       | 12.95%  |
| 2400    | 43       | 11.85%  |
| 2667    | 25       | 6.89%   |
| 800     | 25       | 6.89%   |
| Unknown | 20       | 5.51%   |
| 667     | 15       | 4.13%   |
| 2133    | 13       | 3.58%   |
| 400     | 8        | 2.2%    |
| 1066    | 7        | 1.93%   |
| 1067    | 6        | 1.65%   |
| 2666    | 4        | 1.1%    |
| 4000    | 3        | 0.83%   |
| 3600    | 3        | 0.83%   |
| 3400    | 3        | 0.83%   |
| 3000    | 3        | 0.83%   |
| 2933    | 3        | 0.83%   |
| 1866    | 3        | 0.83%   |
| 533     | 3        | 0.83%   |
| 6400    | 1        | 0.28%   |
| 5600    | 1        | 0.28%   |
| 4800    | 1        | 0.28%   |
| 3733    | 1        | 0.28%   |
| 2048    | 1        | 0.28%   |
| 1867    | 1        | 0.28%   |
| 1400    | 1        | 0.28%   |
| 1334    | 1        | 0.28%   |
| 1332    | 1        | 0.28%   |
| 933     | 1        | 0.28%   |
| 333     | 1        | 0.28%   |
| 266     | 1        | 0.28%   |
| 133     | 1        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Seiko Epson        | 1        | 25%     |
| Kyocera            | 1        | 25%     |
| Hewlett-Packard    | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1        | 25%     |
| Kyocera FS-1025MFP                    | 1        | 25%     |
| HP Laser 107a Printer                 | 1        | 25%     |
| Brother HL-2030 Laser Printer         | 1        | 25%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Logitech                | 4        | 20%     |
| Microdia                | 3        | 15%     |
| Z-Star Microelectronics | 2        | 10%     |
| Arkmicro Technologies   | 2        | 10%     |
| Silicon Motion          | 1        | 5%      |
| Ricoh                   | 1        | 5%      |
| Realtek Semiconductor   | 1        | 5%      |
| Pixart Imaging          | 1        | 5%      |
| Huawei Technologies     | 1        | 5%      |
| GEMBIRD                 | 1        | 5%      |
| Chicony Electronics     | 1        | 5%      |
| Aveo Technology         | 1        | 5%      |
| A4Tech                  | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Logitech Webcam C270                | 2        | 10%     |
| Z-Star Venus USB2.0 Camera          | 1        | 5%      |
| Z-Star Integrated Camera            | 1        | 5%      |
| Silicon Motion 300k Pixel Camera    | 1        | 5%      |
| Ricoh USB2.0 Camera                 | 1        | 5%      |
| Realtek USB Video Device            | 1        | 5%      |
| Pixart Imaging PAC731x Trust Webcam | 1        | 5%      |
| Microdia Webcam Vitade AF           | 1        | 5%      |
| Microdia USB 2.0 Camera             | 1        | 5%      |
| Microdia ASUS USB 2.0 Webcam        | 1        | 5%      |
| Logitech Webcam C170                | 1        | 5%      |
| Logitech C505 HD Webcam             | 1        | 5%      |
| Huawei HiCamera                     | 1        | 5%      |
| GEMBIRD USB2.0 PC CAMERA            | 1        | 5%      |
| Chicony USB2.0 VGA UVC WebCam       | 1        | 5%      |
| Aveo Camera                         | 1        | 5%      |
| Arkmicro Webcam Carrefour           | 1        | 5%      |
| Arkmicro USB 2.0 PC CAMERA          | 1        | 5%      |
| A4Tech A4tech FHD 1080P PC Camera   | 1        | 5%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Validity Sensors  | 1        | 50%     |
| FocalTech Systems | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 50%     |
| FocalTech Systems Fingerprint Reader         | 1        | 50%     |

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 195      | 45.35%  |
| 1     | 176      | 40.93%  |
| 2     | 46       | 10.7%   |
| 3     | 10       | 2.33%   |
| 4     | 3        | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 185      | 66.31%  |
| Net/wireless             | 27       | 9.68%   |
| Sound                    | 19       | 6.81%   |
| Bluetooth                | 13       | 4.66%   |
| Firewire controller      | 12       | 4.3%    |
| Net/ethernet             | 7        | 2.51%   |
| Graphics card            | 4        | 1.43%   |
| Card reader              | 4        | 1.43%   |
| Storage/ata              | 3        | 1.08%   |
| Network                  | 3        | 1.08%   |
| Storage                  | 1        | 0.36%   |
| Fingerprint reader       | 1        | 0.36%   |

