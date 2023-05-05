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

Total: 4385

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Dell          | 0KV62T A01                  | Desktop     | [f26926526d](https://bsd-hardware.info/?probe=f26926526d) | Apr 27, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fc81710889](https://bsd-hardware.info/?probe=fc81710889) | Apr 27, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [9d15e108e6](https://bsd-hardware.info/?probe=9d15e108e6) | Apr 27, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [8a4ea432e6](https://bsd-hardware.info/?probe=8a4ea432e6) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| Acer          | Spin SP314-21               | Convertible | [f5debc3ef8](https://bsd-hardware.info/?probe=f5debc3ef8) | Apr 27, 2023 |
| HP            | 83EE                        | Desktop     | [b5a00cabd1](https://bsd-hardware.info/?probe=b5a00cabd1) | Apr 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [ece1b6bacb](https://bsd-hardware.info/?probe=ece1b6bacb) | Apr 26, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [acb9ca23c8](https://bsd-hardware.info/?probe=acb9ca23c8) | Apr 26, 2023 |
| HP            | 859B                        | Desktop     | [357ef27be4](https://bsd-hardware.info/?probe=357ef27be4) | Apr 26, 2023 |
| HP            | 83E1                        | Desktop     | [58c58b6a82](https://bsd-hardware.info/?probe=58c58b6a82) | Apr 26, 2023 |
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
| HP            | 83E1                        | Desktop     | [35360c7568](https://bsd-hardware.info/?probe=35360c7568) | Apr 22, 2023 |
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
| Techvision    | TVI7309X B0                 | Desktop     | [8a16d2e606](https://bsd-hardware.info/?probe=8a16d2e606) | Feb 24, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [cd96288347](https://bsd-hardware.info/?probe=cd96288347) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [867c14f8d1](https://bsd-hardware.info/?probe=867c14f8d1) | Feb 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [efce6f6c1e](https://bsd-hardware.info/?probe=efce6f6c1e) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [31122bd298](https://bsd-hardware.info/?probe=31122bd298) | Feb 24, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c55b1dd170](https://bsd-hardware.info/?probe=c55b1dd170) | Feb 23, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Desktop     | [d6ab3464c6](https://bsd-hardware.info/?probe=d6ab3464c6) | Feb 23, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [26b7986e0b](https://bsd-hardware.info/?probe=26b7986e0b) | Feb 23, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [96aceb6d32](https://bsd-hardware.info/?probe=96aceb6d32) | Feb 23, 2023 |
| ASUSTek       | Pro A520M-C II              | Desktop     | [542b244f4b](https://bsd-hardware.info/?probe=542b244f4b) | Feb 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [765b1a8064](https://bsd-hardware.info/?probe=765b1a8064) | Feb 22, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [639886b591](https://bsd-hardware.info/?probe=639886b591) | Feb 22, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [8d1496f3a9](https://bsd-hardware.info/?probe=8d1496f3a9) | Feb 22, 2023 |
| Protectli     | VP2410                      | Desktop     | [b31bcf2087](https://bsd-hardware.info/?probe=b31bcf2087) | Feb 22, 2023 |
| Protectli     | VP2410                      | Desktop     | [8dff61bc43](https://bsd-hardware.info/?probe=8dff61bc43) | Feb 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9e92cf3575](https://bsd-hardware.info/?probe=9e92cf3575) | Feb 22, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [25a3e5cea1](https://bsd-hardware.info/?probe=25a3e5cea1) | Feb 22, 2023 |
| Supermicro    | X7SLA                       | Desktop     | [80d6f2c0f8](https://bsd-hardware.info/?probe=80d6f2c0f8) | Feb 21, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [ff6ddb74bb](https://bsd-hardware.info/?probe=ff6ddb74bb) | Feb 21, 2023 |
| Protectli     | FW2B                        | Desktop     | [34b349eead](https://bsd-hardware.info/?probe=34b349eead) | Feb 21, 2023 |
| Dell          | 01V648 A01                  | Server      | [51fbbaf053](https://bsd-hardware.info/?probe=51fbbaf053) | Feb 21, 2023 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [9a3d7de5ff](https://bsd-hardware.info/?probe=9a3d7de5ff) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [da5536f58a](https://bsd-hardware.info/?probe=da5536f58a) | Feb 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [67c7a561a9](https://bsd-hardware.info/?probe=67c7a561a9) | Feb 21, 2023 |
| Dell          | 01V648 A01                  | Server      | [fa7b2a91e8](https://bsd-hardware.info/?probe=fa7b2a91e8) | Feb 21, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [43147a0d7b](https://bsd-hardware.info/?probe=43147a0d7b) | Feb 20, 2023 |
| ASUSTek       | Pro A520M-C II              | Desktop     | [205bf8b29d](https://bsd-hardware.info/?probe=205bf8b29d) | Feb 20, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [820b3d1a1b](https://bsd-hardware.info/?probe=820b3d1a1b) | Feb 20, 2023 |
| Protectli     | VP4650                      | Desktop     | [44b691e7b8](https://bsd-hardware.info/?probe=44b691e7b8) | Feb 20, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [648e3b6a57](https://bsd-hardware.info/?probe=648e3b6a57) | Feb 20, 2023 |
| Protectli     | VP4650                      | Desktop     | [a3011cc486](https://bsd-hardware.info/?probe=a3011cc486) | Feb 20, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| HP            | 8076 MVB,A                  | Desktop     | [7743861bae](https://bsd-hardware.info/?probe=7743861bae) | Feb 19, 2023 |
| MSI           | H81M-P33                    | Desktop     | [28f48b7936](https://bsd-hardware.info/?probe=28f48b7936) | Feb 19, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [b3525afaa7](https://bsd-hardware.info/?probe=b3525afaa7) | Feb 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [19c7044a7d](https://bsd-hardware.info/?probe=19c7044a7d) | Feb 19, 2023 |
| HP            | 1998                        | Desktop     | [e0ab2d859c](https://bsd-hardware.info/?probe=e0ab2d859c) | Feb 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [81041acbb7](https://bsd-hardware.info/?probe=81041acbb7) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 427638U       | Notebook    | [baa0e928a8](https://bsd-hardware.info/?probe=baa0e928a8) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [5b10e92d28](https://bsd-hardware.info/?probe=5b10e92d28) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [633becefb6](https://bsd-hardware.info/?probe=633becefb6) | Feb 18, 2023 |
| Supermicro    | X10SRL-F                    | Server      | [49c49487e2](https://bsd-hardware.info/?probe=49c49487e2) | Feb 17, 2023 |
| Google        | Lulu                        | Notebook    | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| AZW           | Green G1                    | Desktop     | [f5da027d84](https://bsd-hardware.info/?probe=f5da027d84) | Feb 17, 2023 |
| Unknown       | CMB-A9SC2                   | Server      | [6d3e23081c](https://bsd-hardware.info/?probe=6d3e23081c) | Feb 17, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [26cd25b4ca](https://bsd-hardware.info/?probe=26cd25b4ca) | Feb 17, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [ef370f6033](https://bsd-hardware.info/?probe=ef370f6033) | Feb 17, 2023 |
| Jingsha       | x79-P3 by xUz               | Desktop     | [0e5ed7f4de](https://bsd-hardware.info/?probe=0e5ed7f4de) | Feb 17, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Desktop     | [897a3b3bf5](https://bsd-hardware.info/?probe=897a3b3bf5) | Feb 16, 2023 |
| Protectli     | FW2B Ver                    | Desktop     | [b72039f369](https://bsd-hardware.info/?probe=b72039f369) | Feb 16, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [f74527184f](https://bsd-hardware.info/?probe=f74527184f) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [b241a8afd7](https://bsd-hardware.info/?probe=b241a8afd7) | Feb 16, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [dd083df1a2](https://bsd-hardware.info/?probe=dd083df1a2) | Feb 16, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | Notebook    | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [c6946f5300](https://bsd-hardware.info/?probe=c6946f5300) | Feb 15, 2023 |
| MSI           | A88XM-E45                   | Desktop     | [933b4d3226](https://bsd-hardware.info/?probe=933b4d3226) | Feb 15, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [0f07f95c55](https://bsd-hardware.info/?probe=0f07f95c55) | Feb 15, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [1eda4c5b48](https://bsd-hardware.info/?probe=1eda4c5b48) | Feb 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [415389b74c](https://bsd-hardware.info/?probe=415389b74c) | Feb 14, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [fb2a05c862](https://bsd-hardware.info/?probe=fb2a05c862) | Feb 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b0020c937b](https://bsd-hardware.info/?probe=b0020c937b) | Feb 14, 2023 |
| PC Engines    | APU2                        | Desktop     | [0648ebd771](https://bsd-hardware.info/?probe=0648ebd771) | Feb 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d9ff025ff](https://bsd-hardware.info/?probe=2d9ff025ff) | Feb 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b60f91e47](https://bsd-hardware.info/?probe=7b60f91e47) | Feb 14, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [a477c2b046](https://bsd-hardware.info/?probe=a477c2b046) | Feb 14, 2023 |
| Gigabyte      | H97N                        | Desktop     | [88e7d124ef](https://bsd-hardware.info/?probe=88e7d124ef) | Feb 14, 2023 |
| Dell          | 0D02VH A01                  | Desktop     | [a629bf3445](https://bsd-hardware.info/?probe=a629bf3445) | Feb 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b3f41e1cb4](https://bsd-hardware.info/?probe=b3f41e1cb4) | Feb 13, 2023 |
| CWWK          | MINIPC-G4                   | Desktop     | [a186c77c21](https://bsd-hardware.info/?probe=a186c77c21) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b962baf73d](https://bsd-hardware.info/?probe=b962baf73d) | Feb 13, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [431374482e](https://bsd-hardware.info/?probe=431374482e) | Feb 13, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [3e96602a8f](https://bsd-hardware.info/?probe=3e96602a8f) | Feb 13, 2023 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6acbae85b9](https://bsd-hardware.info/?probe=6acbae85b9) | Feb 13, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [f686e3756c](https://bsd-hardware.info/?probe=f686e3756c) | Feb 13, 2023 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | Desktop     | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| Dell          | 0D02VH A01                  | Desktop     | [d0823031a5](https://bsd-hardware.info/?probe=d0823031a5) | Feb 12, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [5988d9a034](https://bsd-hardware.info/?probe=5988d9a034) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [71aa276f7f](https://bsd-hardware.info/?probe=71aa276f7f) | Feb 12, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [ba5f8c568b](https://bsd-hardware.info/?probe=ba5f8c568b) | Feb 12, 2023 |
| MSI           | H81M-P33                    | Desktop     | [84aff26f99](https://bsd-hardware.info/?probe=84aff26f99) | Feb 12, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [4e899d9a1c](https://bsd-hardware.info/?probe=4e899d9a1c) | Feb 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d16e93b7f3](https://bsd-hardware.info/?probe=d16e93b7f3) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [133d9aedfd](https://bsd-hardware.info/?probe=133d9aedfd) | Feb 12, 2023 |
| HP            | 8522 A01                    | Mini pc     | [4a8f9eefc9](https://bsd-hardware.info/?probe=4a8f9eefc9) | Feb 12, 2023 |
| HP            | 843B                        | Desktop     | [2b9c5f49f5](https://bsd-hardware.info/?probe=2b9c5f49f5) | Feb 12, 2023 |
| Dell          | 0PU052                      | Desktop     | [03bcc500c0](https://bsd-hardware.info/?probe=03bcc500c0) | Feb 12, 2023 |
| Dell          | 0PU052                      | Desktop     | [035408150f](https://bsd-hardware.info/?probe=035408150f) | Feb 11, 2023 |
| Sophos        | SG                          | Firewall    | [08b02dfc2d](https://bsd-hardware.info/?probe=08b02dfc2d) | Feb 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0684ee3bb7](https://bsd-hardware.info/?probe=0684ee3bb7) | Feb 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7d908f5c62](https://bsd-hardware.info/?probe=7d908f5c62) | Feb 11, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [3724be73d9](https://bsd-hardware.info/?probe=3724be73d9) | Feb 11, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [b9caeb411f](https://bsd-hardware.info/?probe=b9caeb411f) | Feb 11, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [9a97e27b37](https://bsd-hardware.info/?probe=9a97e27b37) | Feb 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [1d63a08b5d](https://bsd-hardware.info/?probe=1d63a08b5d) | Feb 10, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [882f0868fe](https://bsd-hardware.info/?probe=882f0868fe) | Feb 10, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [367edc6620](https://bsd-hardware.info/?probe=367edc6620) | Feb 10, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [f853cd2270](https://bsd-hardware.info/?probe=f853cd2270) | Feb 10, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d6be869761](https://bsd-hardware.info/?probe=d6be869761) | Feb 09, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [1d8b9a30c5](https://bsd-hardware.info/?probe=1d8b9a30c5) | Feb 09, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [a15eee8687](https://bsd-hardware.info/?probe=a15eee8687) | Feb 09, 2023 |
| Dell          | 051FJ8 A01                  | Desktop     | [573c8ffac2](https://bsd-hardware.info/?probe=573c8ffac2) | Feb 09, 2023 |
| Biostar       | TA970                       | Desktop     | [8c1a7aedf1](https://bsd-hardware.info/?probe=8c1a7aedf1) | Feb 09, 2023 |
| Sophos        | XG                          | Firewall    | [8bf27537e4](https://bsd-hardware.info/?probe=8bf27537e4) | Feb 09, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d6c8ad1034](https://bsd-hardware.info/?probe=d6c8ad1034) | Feb 08, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b9166d8134](https://bsd-hardware.info/?probe=b9166d8134) | Feb 08, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [9111a4027f](https://bsd-hardware.info/?probe=9111a4027f) | Feb 08, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [b359adb611](https://bsd-hardware.info/?probe=b359adb611) | Feb 08, 2023 |
| ADI Engine... | RCC                         | Desktop     | [d28d10f385](https://bsd-hardware.info/?probe=d28d10f385) | Feb 08, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [d3b116f637](https://bsd-hardware.info/?probe=d3b116f637) | Feb 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [9f2744c3af](https://bsd-hardware.info/?probe=9f2744c3af) | Feb 07, 2023 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c52d47435b](https://bsd-hardware.info/?probe=c52d47435b) | Feb 07, 2023 |
| BESSTAR Te... | GB7B                        | Mini pc     | [f67ce5d559](https://bsd-hardware.info/?probe=f67ce5d559) | Feb 07, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [8642fcacb2](https://bsd-hardware.info/?probe=8642fcacb2) | Feb 07, 2023 |
| Panasonic     | CF-30KAPAXAM                | Notebook    | [baa7612257](https://bsd-hardware.info/?probe=baa7612257) | Feb 07, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [259f0ae05e](https://bsd-hardware.info/?probe=259f0ae05e) | Feb 06, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2f92461169](https://bsd-hardware.info/?probe=2f92461169) | Feb 06, 2023 |
| CheckPoint    | T-120-00                    | Desktop     | [f1f935b515](https://bsd-hardware.info/?probe=f1f935b515) | Feb 06, 2023 |
| Dell          | 0M788G A01                  | Server      | [9f4ac237db](https://bsd-hardware.info/?probe=9f4ac237db) | Feb 06, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [a8c0107319](https://bsd-hardware.info/?probe=a8c0107319) | Feb 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [27702234cc](https://bsd-hardware.info/?probe=27702234cc) | Feb 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c04d9caf55](https://bsd-hardware.info/?probe=c04d9caf55) | Feb 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [61019d305c](https://bsd-hardware.info/?probe=61019d305c) | Feb 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [cc612f1fa0](https://bsd-hardware.info/?probe=cc612f1fa0) | Feb 06, 2023 |
| CheckPoint    | T-120-00                    | Desktop     | [fbce242920](https://bsd-hardware.info/?probe=fbce242920) | Feb 05, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [7be10e8844](https://bsd-hardware.info/?probe=7be10e8844) | Feb 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [6f8f329a5b](https://bsd-hardware.info/?probe=6f8f329a5b) | Feb 05, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [bd418783d4](https://bsd-hardware.info/?probe=bd418783d4) | Feb 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ec1ab0bf97](https://bsd-hardware.info/?probe=ec1ab0bf97) | Feb 05, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [dc0514457f](https://bsd-hardware.info/?probe=dc0514457f) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| HP            | 8103 A01                    | Mini pc     | [3987499e64](https://bsd-hardware.info/?probe=3987499e64) | Feb 05, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [5512097fd0](https://bsd-hardware.info/?probe=5512097fd0) | Feb 05, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [7cb3eeeb08](https://bsd-hardware.info/?probe=7cb3eeeb08) | Feb 04, 2023 |
| HP            | 8103 A01                    | Mini pc     | [1cc384c148](https://bsd-hardware.info/?probe=1cc384c148) | Feb 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [b1713eb2b5](https://bsd-hardware.info/?probe=b1713eb2b5) | Feb 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [79deea0fd2](https://bsd-hardware.info/?probe=79deea0fd2) | Feb 03, 2023 |
| Intel         | S1200BTL E98681-306         | Server      | [11bc81ef41](https://bsd-hardware.info/?probe=11bc81ef41) | Feb 03, 2023 |
| Supermicro    | X11SSH-F                    | Server      | [7e2b421011](https://bsd-hardware.info/?probe=7e2b421011) | Feb 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [84ad5cfa43](https://bsd-hardware.info/?probe=84ad5cfa43) | Feb 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [5511770d75](https://bsd-hardware.info/?probe=5511770d75) | Feb 03, 2023 |
| Supermicro    | M11SDV-8CT-LN4F             | Server      | [568bc002e2](https://bsd-hardware.info/?probe=568bc002e2) | Feb 03, 2023 |
| Dell          | 0DRG19 A00                  | Mini pc     | [1df309e6ec](https://bsd-hardware.info/?probe=1df309e6ec) | Feb 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [e6c145f7b3](https://bsd-hardware.info/?probe=e6c145f7b3) | Feb 02, 2023 |
| Protectli     | FW4B                        | Desktop     | [a140b31d9d](https://bsd-hardware.info/?probe=a140b31d9d) | Feb 02, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [c8993dcca5](https://bsd-hardware.info/?probe=c8993dcca5) | Feb 02, 2023 |
| Protectli     | VP2410                      | Desktop     | [595e8af4d0](https://bsd-hardware.info/?probe=595e8af4d0) | Feb 02, 2023 |
| Dell          | 0KM5PX A04                  | Server      | [5b86b7c534](https://bsd-hardware.info/?probe=5b86b7c534) | Feb 02, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [af957bb4fa](https://bsd-hardware.info/?probe=af957bb4fa) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [1364889ca4](https://bsd-hardware.info/?probe=1364889ca4) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [3f5428623d](https://bsd-hardware.info/?probe=3f5428623d) | Feb 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [27f3968fd4](https://bsd-hardware.info/?probe=27f3968fd4) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [c00728e738](https://bsd-hardware.info/?probe=c00728e738) | Jan 31, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [28530f37ec](https://bsd-hardware.info/?probe=28530f37ec) | Jan 31, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [1e97ee1c05](https://bsd-hardware.info/?probe=1e97ee1c05) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| ASRock        | 970 Extreme3                | Desktop     | [5e2fd4b48f](https://bsd-hardware.info/?probe=5e2fd4b48f) | Jan 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [348805aada](https://bsd-hardware.info/?probe=348805aada) | Jan 30, 2023 |
| Protectli     | FW6                         | Desktop     | [5a05c9fe40](https://bsd-hardware.info/?probe=5a05c9fe40) | Jan 30, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5b55b50956](https://bsd-hardware.info/?probe=5b55b50956) | Jan 30, 2023 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [27e7ae6041](https://bsd-hardware.info/?probe=27e7ae6041) | Jan 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [951295643c](https://bsd-hardware.info/?probe=951295643c) | Jan 30, 2023 |
| HP            | 8103 A01                    | Mini pc     | [8bcc484918](https://bsd-hardware.info/?probe=8bcc484918) | Jan 29, 2023 |
| MSI           | A88XM-E45                   | Desktop     | [f7eb6735d3](https://bsd-hardware.info/?probe=f7eb6735d3) | Jan 29, 2023 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [3676751039](https://bsd-hardware.info/?probe=3676751039) | Jan 29, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e6626da98c](https://bsd-hardware.info/?probe=e6626da98c) | Jan 29, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [3d5ea9f313](https://bsd-hardware.info/?probe=3d5ea9f313) | Jan 29, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9b7532b795](https://bsd-hardware.info/?probe=9b7532b795) | Jan 29, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [7cfdbb0e90](https://bsd-hardware.info/?probe=7cfdbb0e90) | Jan 29, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [7db7965ebb](https://bsd-hardware.info/?probe=7db7965ebb) | Jan 29, 2023 |
| HP            | 213D A01                    | Desktop     | [dea507ebe0](https://bsd-hardware.info/?probe=dea507ebe0) | Jan 29, 2023 |
| Protectli     | FW4B Ver                    | Desktop     | [ac63fa59a6](https://bsd-hardware.info/?probe=ac63fa59a6) | Jan 29, 2023 |
| Biostar       | Hi-Fi A85S3                 | Desktop     | [f4b661ad85](https://bsd-hardware.info/?probe=f4b661ad85) | Jan 28, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [1c4edf62e6](https://bsd-hardware.info/?probe=1c4edf62e6) | Jan 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [431cf63cae](https://bsd-hardware.info/?probe=431cf63cae) | Jan 28, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2db24eed0a](https://bsd-hardware.info/?probe=2db24eed0a) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [d473269837](https://bsd-hardware.info/?probe=d473269837) | Jan 28, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [a0a26f529c](https://bsd-hardware.info/?probe=a0a26f529c) | Jan 27, 2023 |
| HP            | 8299                        | Desktop     | [61b1c41f22](https://bsd-hardware.info/?probe=61b1c41f22) | Jan 27, 2023 |
| Google        | Kefka                       | Notebook    | [83771661c6](https://bsd-hardware.info/?probe=83771661c6) | Jan 27, 2023 |
| Protectli     | FW4B                        | Desktop     | [06eeeaa67b](https://bsd-hardware.info/?probe=06eeeaa67b) | Jan 27, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [226f25a086](https://bsd-hardware.info/?probe=226f25a086) | Jan 27, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [56fea0c931](https://bsd-hardware.info/?probe=56fea0c931) | Jan 27, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [18e688307e](https://bsd-hardware.info/?probe=18e688307e) | Jan 27, 2023 |
| AMD           | Kabini CRB                  | Desktop     | [3405de1629](https://bsd-hardware.info/?probe=3405de1629) | Jan 27, 2023 |
| Deciso        | Netboard A20                | Notebook    | [07de4617d2](https://bsd-hardware.info/?probe=07de4617d2) | Jan 26, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [d1e71effc5](https://bsd-hardware.info/?probe=d1e71effc5) | Jan 26, 2023 |
| Dell          | 0YDJK3 A02                  | Server      | [ca78843973](https://bsd-hardware.info/?probe=ca78843973) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [bc41bdb431](https://bsd-hardware.info/?probe=bc41bdb431) | Jan 26, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [1803740ba6](https://bsd-hardware.info/?probe=1803740ba6) | Jan 25, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [82718999a8](https://bsd-hardware.info/?probe=82718999a8) | Jan 25, 2023 |
| HP            | 802E                        | Desktop     | [1f3bf517af](https://bsd-hardware.info/?probe=1f3bf517af) | Jan 25, 2023 |
| Google        | Panther                     | Desktop     | [73d3147166](https://bsd-hardware.info/?probe=73d3147166) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [0a40a0b8e2](https://bsd-hardware.info/?probe=0a40a0b8e2) | Jan 24, 2023 |
| Deciso        | NetBoard-A20                | Notebook    | [211bc64e5e](https://bsd-hardware.info/?probe=211bc64e5e) | Jan 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [54be5c792e](https://bsd-hardware.info/?probe=54be5c792e) | Jan 24, 2023 |
| HP            | 83F2                        | Desktop     | [970c786b06](https://bsd-hardware.info/?probe=970c786b06) | Jan 24, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [556e872ffe](https://bsd-hardware.info/?probe=556e872ffe) | Jan 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Protectli     | FW4A Ver                    | Desktop     | [b91fe4d66f](https://bsd-hardware.info/?probe=b91fe4d66f) | Jan 23, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [f2f100ee10](https://bsd-hardware.info/?probe=f2f100ee10) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d03f9c19f8](https://bsd-hardware.info/?probe=d03f9c19f8) | Jan 23, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [771f2c4d96](https://bsd-hardware.info/?probe=771f2c4d96) | Jan 23, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [006553f965](https://bsd-hardware.info/?probe=006553f965) | Jan 23, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [26d1d923d6](https://bsd-hardware.info/?probe=26d1d923d6) | Jan 22, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0bbc074f1c](https://bsd-hardware.info/?probe=0bbc074f1c) | Jan 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [28d8d82d34](https://bsd-hardware.info/?probe=28d8d82d34) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | Notebook    | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Datto         | 1000                        | Notebook    | [3d2880dd30](https://bsd-hardware.info/?probe=3d2880dd30) | Jan 21, 2023 |
| AZW           | Green G1                    | Desktop     | [80498a4090](https://bsd-hardware.info/?probe=80498a4090) | Jan 21, 2023 |
| AZW           | Green G1                    | Desktop     | [0c84e93ba7](https://bsd-hardware.info/?probe=0c84e93ba7) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1d040b684b](https://bsd-hardware.info/?probe=1d040b684b) | Jan 21, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [7a21bfbfb9](https://bsd-hardware.info/?probe=7a21bfbfb9) | Jan 20, 2023 |
| Gigabyte      | F2A75M-HD2                  | Desktop     | [4770b980d6](https://bsd-hardware.info/?probe=4770b980d6) | Jan 20, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [a4688e4059](https://bsd-hardware.info/?probe=a4688e4059) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2ea8c1d1a4](https://bsd-hardware.info/?probe=2ea8c1d1a4) | Jan 20, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [8ffe26845d](https://bsd-hardware.info/?probe=8ffe26845d) | Jan 20, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [47742b68d5](https://bsd-hardware.info/?probe=47742b68d5) | Jan 19, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [dc3f072645](https://bsd-hardware.info/?probe=dc3f072645) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [62bad8c9f8](https://bsd-hardware.info/?probe=62bad8c9f8) | Jan 19, 2023 |
| HP            | ProLiant DL120 Gen9         | Server      | [7df2c509dd](https://bsd-hardware.info/?probe=7df2c509dd) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [28bb1a7282](https://bsd-hardware.info/?probe=28bb1a7282) | Jan 19, 2023 |
| Datto         | Unknown                     | Notebook    | [0b70f2b2b0](https://bsd-hardware.info/?probe=0b70f2b2b0) | Jan 18, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [c5d050f0d6](https://bsd-hardware.info/?probe=c5d050f0d6) | Jan 18, 2023 |
| Datto         | 1000                        | Notebook    | [c2abd24ed6](https://bsd-hardware.info/?probe=c2abd24ed6) | Jan 18, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [f929122d8a](https://bsd-hardware.info/?probe=f929122d8a) | Jan 18, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [37ae895d75](https://bsd-hardware.info/?probe=37ae895d75) | Jan 17, 2023 |
| Intel         | DQ45CB AAE30148-302         | Desktop     | [349da05405](https://bsd-hardware.info/?probe=349da05405) | Jan 17, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [65ce4b26be](https://bsd-hardware.info/?probe=65ce4b26be) | Jan 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d8007634f3](https://bsd-hardware.info/?probe=d8007634f3) | Jan 17, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [11943e270e](https://bsd-hardware.info/?probe=11943e270e) | Jan 17, 2023 |
| HP            | 1998                        | Desktop     | [6c36e5e82e](https://bsd-hardware.info/?probe=6c36e5e82e) | Jan 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [63689d3fbc](https://bsd-hardware.info/?probe=63689d3fbc) | Jan 17, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [78a4659386](https://bsd-hardware.info/?probe=78a4659386) | Jan 16, 2023 |
| Unknown       | QD-CMU01                    | Desktop     | [768a10819b](https://bsd-hardware.info/?probe=768a10819b) | Jan 16, 2023 |
| HP            | 0AECh D                     | Desktop     | [25b7a10166](https://bsd-hardware.info/?probe=25b7a10166) | Jan 16, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [e25304fa01](https://bsd-hardware.info/?probe=e25304fa01) | Jan 15, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Desktop     | [af7a4d3493](https://bsd-hardware.info/?probe=af7a4d3493) | Jan 15, 2023 |
| MSI           | H81M-P33                    | Desktop     | [800b3bc34b](https://bsd-hardware.info/?probe=800b3bc34b) | Jan 15, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [ffbcac312f](https://bsd-hardware.info/?probe=ffbcac312f) | Jan 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [48e7397e29](https://bsd-hardware.info/?probe=48e7397e29) | Jan 15, 2023 |
| Silicom       | 80300-0214-G01 R311         | Desktop     | [547b59be2b](https://bsd-hardware.info/?probe=547b59be2b) | Jan 15, 2023 |
| Dell          | 0C2KJT A00                  | Desktop     | [9364056dac](https://bsd-hardware.info/?probe=9364056dac) | Jan 15, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a975d143b8](https://bsd-hardware.info/?probe=a975d143b8) | Jan 15, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05cc17947c](https://bsd-hardware.info/?probe=05cc17947c) | Jan 15, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [9c70b7e4e1](https://bsd-hardware.info/?probe=9c70b7e4e1) | Jan 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [c85b254f84](https://bsd-hardware.info/?probe=c85b254f84) | Jan 15, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [ad094a458b](https://bsd-hardware.info/?probe=ad094a458b) | Jan 14, 2023 |
| HP            | Presario V2000 (EZ621UA#... | Notebook    | [847af5b70f](https://bsd-hardware.info/?probe=847af5b70f) | Jan 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f682e06d06](https://bsd-hardware.info/?probe=f682e06d06) | Jan 13, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [c908dc76a1](https://bsd-hardware.info/?probe=c908dc76a1) | Jan 13, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c5769bcae3](https://bsd-hardware.info/?probe=c5769bcae3) | Jan 13, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [82f4b97203](https://bsd-hardware.info/?probe=82f4b97203) | Jan 13, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [a18d3bf0ea](https://bsd-hardware.info/?probe=a18d3bf0ea) | Jan 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| Dell          | 051FJ8 A01                  | Desktop     | [8d5c03acf1](https://bsd-hardware.info/?probe=8d5c03acf1) | Jan 12, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [8f3e58f2bc](https://bsd-hardware.info/?probe=8f3e58f2bc) | Jan 12, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [4154475f49](https://bsd-hardware.info/?probe=4154475f49) | Jan 12, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [53a5719c6a](https://bsd-hardware.info/?probe=53a5719c6a) | Jan 12, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b1b7d05863](https://bsd-hardware.info/?probe=b1b7d05863) | Jan 12, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [619a877f82](https://bsd-hardware.info/?probe=619a877f82) | Jan 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [cb7b02c421](https://bsd-hardware.info/?probe=cb7b02c421) | Jan 11, 2023 |
| HP            | 843B                        | Desktop     | [3e2070415f](https://bsd-hardware.info/?probe=3e2070415f) | Jan 11, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [5eedf320f8](https://bsd-hardware.info/?probe=5eedf320f8) | Jan 11, 2023 |
| Datto         | 1000                        | Notebook    | [ab1aa0f250](https://bsd-hardware.info/?probe=ab1aa0f250) | Jan 11, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [82e9263905](https://bsd-hardware.info/?probe=82e9263905) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [5386547734](https://bsd-hardware.info/?probe=5386547734) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b1707aed4](https://bsd-hardware.info/?probe=9b1707aed4) | Jan 11, 2023 |
| HP            | 805D                        | Desktop     | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| MSI           | H110M-A PRO M2              | Desktop     | [3cf7d4a076](https://bsd-hardware.info/?probe=3cf7d4a076) | Jan 11, 2023 |
| HP            | 805D                        | Desktop     | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [e4af143188](https://bsd-hardware.info/?probe=e4af143188) | Jan 10, 2023 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [0b16265d11](https://bsd-hardware.info/?probe=0b16265d11) | Jan 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [6b37f8e185](https://bsd-hardware.info/?probe=6b37f8e185) | Jan 10, 2023 |
| Dell          | 0RC130 A03                  | Server      | [861cdcfef1](https://bsd-hardware.info/?probe=861cdcfef1) | Jan 10, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b37db9216b](https://bsd-hardware.info/?probe=b37db9216b) | Jan 10, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [c554f29fbb](https://bsd-hardware.info/?probe=c554f29fbb) | Jan 10, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9bda43254c](https://bsd-hardware.info/?probe=9bda43254c) | Jan 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2db049304e](https://bsd-hardware.info/?probe=2db049304e) | Jan 10, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [12a726c7f3](https://bsd-hardware.info/?probe=12a726c7f3) | Jan 10, 2023 |
| HP            | 8054                        | Desktop     | [7a7dd659c8](https://bsd-hardware.info/?probe=7a7dd659c8) | Jan 09, 2023 |
| Protectli     | FW6                         | Desktop     | [606f595213](https://bsd-hardware.info/?probe=606f595213) | Jan 09, 2023 |
| Protectli     | FW6                         | Desktop     | [6db7b1f01d](https://bsd-hardware.info/?probe=6db7b1f01d) | Jan 09, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [1ebacfe659](https://bsd-hardware.info/?probe=1ebacfe659) | Jan 09, 2023 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [e217534893](https://bsd-hardware.info/?probe=e217534893) | Jan 09, 2023 |
| HP            | 8299                        | Desktop     | [f80e368b24](https://bsd-hardware.info/?probe=f80e368b24) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [917b19fbeb](https://bsd-hardware.info/?probe=917b19fbeb) | Jan 09, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [97b65880b0](https://bsd-hardware.info/?probe=97b65880b0) | Jan 09, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [c86fd3a6ff](https://bsd-hardware.info/?probe=c86fd3a6ff) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [0714b46000](https://bsd-hardware.info/?probe=0714b46000) | Jan 08, 2023 |
| Deciso        | OPNsense Appliance          | Notebook    | [cc421d80b4](https://bsd-hardware.info/?probe=cc421d80b4) | Jan 08, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [011121c9a5](https://bsd-hardware.info/?probe=011121c9a5) | Jan 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [585a3dc78c](https://bsd-hardware.info/?probe=585a3dc78c) | Jan 08, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [1e9d8cc278](https://bsd-hardware.info/?probe=1e9d8cc278) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [490261883c](https://bsd-hardware.info/?probe=490261883c) | Jan 08, 2023 |
| CheckPoint    | T-180-00                    | Desktop     | [5cee1fe8d6](https://bsd-hardware.info/?probe=5cee1fe8d6) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c877bf16e](https://bsd-hardware.info/?probe=8c877bf16e) | Jan 08, 2023 |
| Protectli     | FW6                         | Desktop     | [6ce513ba71](https://bsd-hardware.info/?probe=6ce513ba71) | Jan 08, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [c42af2bdc3](https://bsd-hardware.info/?probe=c42af2bdc3) | Jan 08, 2023 |
| HP            | 3397                        | Desktop     | [516464d7ef](https://bsd-hardware.info/?probe=516464d7ef) | Jan 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [bb243a8862](https://bsd-hardware.info/?probe=bb243a8862) | Jan 08, 2023 |
| HP            | 8617                        | Desktop     | [2dd1830de4](https://bsd-hardware.info/?probe=2dd1830de4) | Jan 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [44969e64ee](https://bsd-hardware.info/?probe=44969e64ee) | Jan 06, 2023 |
| Dell          | 02K9CR A02                  | Desktop     | [3547d6c126](https://bsd-hardware.info/?probe=3547d6c126) | Jan 06, 2023 |
| Supermicro    | X10SDV-6C-TLN4F             | Server      | [19dc10e659](https://bsd-hardware.info/?probe=19dc10e659) | Jan 05, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [379b59f079](https://bsd-hardware.info/?probe=379b59f079) | Jan 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [b3295065c3](https://bsd-hardware.info/?probe=b3295065c3) | Jan 05, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [e3f89954bd](https://bsd-hardware.info/?probe=e3f89954bd) | Jan 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [6a0f56a7c4](https://bsd-hardware.info/?probe=6a0f56a7c4) | Jan 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3e4f41ff05](https://bsd-hardware.info/?probe=3e4f41ff05) | Jan 05, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [9dc3183152](https://bsd-hardware.info/?probe=9dc3183152) | Jan 04, 2023 |
| Supermicro    | X10DRiB                     | Desktop     | [d120c268f7](https://bsd-hardware.info/?probe=d120c268f7) | Jan 04, 2023 |
| Supermicro    | X10DRi-T                    | Desktop     | [3bd4e1dc9c](https://bsd-hardware.info/?probe=3bd4e1dc9c) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [6062f9823e](https://bsd-hardware.info/?probe=6062f9823e) | Jan 04, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [f10075e5d1](https://bsd-hardware.info/?probe=f10075e5d1) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [42277bd8ff](https://bsd-hardware.info/?probe=42277bd8ff) | Jan 04, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [97e19b4cd1](https://bsd-hardware.info/?probe=97e19b4cd1) | Jan 03, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [8069ed414b](https://bsd-hardware.info/?probe=8069ed414b) | Jan 03, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7d6e899adb](https://bsd-hardware.info/?probe=7d6e899adb) | Jan 03, 2023 |
| HP            | 213D A01                    | Desktop     | [3a1fd3f0a0](https://bsd-hardware.info/?probe=3a1fd3f0a0) | Jan 02, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [203823deda](https://bsd-hardware.info/?probe=203823deda) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [5159265605](https://bsd-hardware.info/?probe=5159265605) | Jan 02, 2023 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [c96a5de4ed](https://bsd-hardware.info/?probe=c96a5de4ed) | Jan 02, 2023 |
| HP            | 8103 A01                    | Mini pc     | [989cfd51a8](https://bsd-hardware.info/?probe=989cfd51a8) | Jan 02, 2023 |
| HP            | 8055                        | Desktop     | [c8f3d3687d](https://bsd-hardware.info/?probe=c8f3d3687d) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [1697219032](https://bsd-hardware.info/?probe=1697219032) | Jan 02, 2023 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [dcf6e2df1a](https://bsd-hardware.info/?probe=dcf6e2df1a) | Jan 02, 2023 |
| SmbiosType... | SmbiosType2_BoardProduct... | Desktop     | [d8d62a103a](https://bsd-hardware.info/?probe=d8d62a103a) | Jan 02, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [3b0ef08599](https://bsd-hardware.info/?probe=3b0ef08599) | Jan 01, 2023 |
| MSI           | H81M-P33                    | Desktop     | [0a57dcce99](https://bsd-hardware.info/?probe=0a57dcce99) | Jan 01, 2023 |
| ASUSTek       | P5Q-E                       | Desktop     | [d3306559de](https://bsd-hardware.info/?probe=d3306559de) | Jan 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [772779fadf](https://bsd-hardware.info/?probe=772779fadf) | Jan 01, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [6345f92400](https://bsd-hardware.info/?probe=6345f92400) | Jan 01, 2023 |
| Dell          | 04415J A00                  | Mini pc     | [3737d80840](https://bsd-hardware.info/?probe=3737d80840) | Dec 31, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [21e1293019](https://bsd-hardware.info/?probe=21e1293019) | Dec 31, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [0bf1c2abef](https://bsd-hardware.info/?probe=0bf1c2abef) | Dec 31, 2022 |
| Dell          | 04415J A00                  | Mini pc     | [c6c6858ef0](https://bsd-hardware.info/?probe=c6c6858ef0) | Dec 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [68a847f5c2](https://bsd-hardware.info/?probe=68a847f5c2) | Dec 31, 2022 |
| GoWin Solu... | R86S                        | Desktop     | [4243d313a1](https://bsd-hardware.info/?probe=4243d313a1) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2518C3U       | Notebook    | [c791e3e3fd](https://bsd-hardware.info/?probe=c791e3e3fd) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [d4460f8031](https://bsd-hardware.info/?probe=d4460f8031) | Dec 30, 2022 |
| Protectli     | FW6                         | Desktop     | [0d62222b7a](https://bsd-hardware.info/?probe=0d62222b7a) | Dec 30, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [46c3e7ffdd](https://bsd-hardware.info/?probe=46c3e7ffdd) | Dec 30, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8b4c84d972](https://bsd-hardware.info/?probe=8b4c84d972) | Dec 30, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [77e235d9f8](https://bsd-hardware.info/?probe=77e235d9f8) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dab2c420a](https://bsd-hardware.info/?probe=1dab2c420a) | Dec 28, 2022 |
| Intel         | DENLOW_REFRESH_WS           | Desktop     | [4f86e686d2](https://bsd-hardware.info/?probe=4f86e686d2) | Dec 28, 2022 |
| Google        | Peppy                       | Notebook    | [e063619f03](https://bsd-hardware.info/?probe=e063619f03) | Dec 27, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [8cb1f1a8ea](https://bsd-hardware.info/?probe=8cb1f1a8ea) | Dec 27, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d4296fd9d8](https://bsd-hardware.info/?probe=d4296fd9d8) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [39bce6117f](https://bsd-hardware.info/?probe=39bce6117f) | Dec 26, 2022 |
| Dell          | 051FJ8 A01                  | Desktop     | [7f66a21d24](https://bsd-hardware.info/?probe=7f66a21d24) | Dec 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [e52abbf1b8](https://bsd-hardware.info/?probe=e52abbf1b8) | Dec 26, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [5f713b6061](https://bsd-hardware.info/?probe=5f713b6061) | Dec 26, 2022 |
| Protectli     | FW6                         | Desktop     | [90758fca97](https://bsd-hardware.info/?probe=90758fca97) | Dec 26, 2022 |
| Dell          | 0M877N A01                  | Server      | [340dc7255c](https://bsd-hardware.info/?probe=340dc7255c) | Dec 26, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [3fc9a4fd5c](https://bsd-hardware.info/?probe=3fc9a4fd5c) | Dec 26, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [bc829dbb1a](https://bsd-hardware.info/?probe=bc829dbb1a) | Dec 25, 2022 |
| MSI           | H81M-P33                    | Desktop     | [f73a37ab81](https://bsd-hardware.info/?probe=f73a37ab81) | Dec 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e842ddb27](https://bsd-hardware.info/?probe=2e842ddb27) | Dec 25, 2022 |
| Cisco         | ASA5515 A0                  | Desktop     | [9e587b9499](https://bsd-hardware.info/?probe=9e587b9499) | Dec 25, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| HP            | 213D A01                    | Desktop     | [bd620f0fc0](https://bsd-hardware.info/?probe=bd620f0fc0) | Dec 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd212706ad](https://bsd-hardware.info/?probe=bd212706ad) | Dec 24, 2022 |
| Lenovo        | 314D NOK                    | Mini pc     | [af60c7ce81](https://bsd-hardware.info/?probe=af60c7ce81) | Dec 24, 2022 |
| Supermicro    | X10SRH-CLN4FA               | Desktop     | [84c360ad02](https://bsd-hardware.info/?probe=84c360ad02) | Dec 24, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [153f99a846](https://bsd-hardware.info/?probe=153f99a846) | Dec 24, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [b29f2e4573](https://bsd-hardware.info/?probe=b29f2e4573) | Dec 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [701c6e95d6](https://bsd-hardware.info/?probe=701c6e95d6) | Dec 24, 2022 |
| Gigabyte      | Z390 AORUS ELITE            | Desktop     | [91b7417b84](https://bsd-hardware.info/?probe=91b7417b84) | Dec 24, 2022 |
| MSI           | A78M-E35                    | Desktop     | [03176e6683](https://bsd-hardware.info/?probe=03176e6683) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [52327286e4](https://bsd-hardware.info/?probe=52327286e4) | Dec 23, 2022 |
| Dell          | 03X6X0 A00                  | Server      | [0d70cc442b](https://bsd-hardware.info/?probe=0d70cc442b) | Dec 23, 2022 |
| Lenovo        | ThinkPad T480 20L6S13100    | Notebook    | [67daa912fa](https://bsd-hardware.info/?probe=67daa912fa) | Dec 23, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [e0b4e13386](https://bsd-hardware.info/?probe=e0b4e13386) | Dec 23, 2022 |
| Dell          | Vostro 1400                 | Notebook    | [087a3d269f](https://bsd-hardware.info/?probe=087a3d269f) | Dec 23, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [062fb4cccd](https://bsd-hardware.info/?probe=062fb4cccd) | Dec 23, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [527bf6bbe4](https://bsd-hardware.info/?probe=527bf6bbe4) | Dec 22, 2022 |
| Supermicro    | X10SDV-8C-TLN4F+            | Server      | [633b9a5425](https://bsd-hardware.info/?probe=633b9a5425) | Dec 22, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [df221cefbc](https://bsd-hardware.info/?probe=df221cefbc) | Dec 22, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Supermicro    | X10SLH-N6-ST031             | Server      | [16f59f69dc](https://bsd-hardware.info/?probe=16f59f69dc) | Dec 20, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [9596576df7](https://bsd-hardware.info/?probe=9596576df7) | Dec 20, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [31f17adc5b](https://bsd-hardware.info/?probe=31f17adc5b) | Dec 20, 2022 |
| Supermicro    | X10SDV-4C-TLN4F             | Server      | [c0c8d1f85e](https://bsd-hardware.info/?probe=c0c8d1f85e) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [4c5ccd04d0](https://bsd-hardware.info/?probe=4c5ccd04d0) | Dec 19, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b84941cdd5](https://bsd-hardware.info/?probe=b84941cdd5) | Dec 19, 2022 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [9a3cbe1893](https://bsd-hardware.info/?probe=9a3cbe1893) | Dec 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [fad0a431e5](https://bsd-hardware.info/?probe=fad0a431e5) | Dec 19, 2022 |
| Lenovo        | ThinkPad X200 Tablet 744... | Notebook    | [ea686f63f5](https://bsd-hardware.info/?probe=ea686f63f5) | Dec 19, 2022 |
| Framework     | Laptop                      | Notebook    | [9dcd3592db](https://bsd-hardware.info/?probe=9dcd3592db) | Dec 19, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [b9df714117](https://bsd-hardware.info/?probe=b9df714117) | Dec 19, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [0af7422e2f](https://bsd-hardware.info/?probe=0af7422e2f) | Dec 18, 2022 |
| Dell          | Precision M4800             | Notebook    | [b7a834c4d0](https://bsd-hardware.info/?probe=b7a834c4d0) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c1b0b83306](https://bsd-hardware.info/?probe=c1b0b83306) | Dec 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [78e4743abd](https://bsd-hardware.info/?probe=78e4743abd) | Dec 18, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [f232e5746e](https://bsd-hardware.info/?probe=f232e5746e) | Dec 18, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [638b27bc34](https://bsd-hardware.info/?probe=638b27bc34) | Dec 18, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a40ada7f7f](https://bsd-hardware.info/?probe=a40ada7f7f) | Dec 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [f6fababc22](https://bsd-hardware.info/?probe=f6fababc22) | Dec 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e06fa5d522](https://bsd-hardware.info/?probe=e06fa5d522) | Dec 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1b29c356e](https://bsd-hardware.info/?probe=a1b29c356e) | Dec 17, 2022 |
| Protectli     | FW6                         | Desktop     | [56f62226e7](https://bsd-hardware.info/?probe=56f62226e7) | Dec 17, 2022 |
| HP            | 213D A01                    | Desktop     | [088766f04d](https://bsd-hardware.info/?probe=088766f04d) | Dec 17, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [f6085ba691](https://bsd-hardware.info/?probe=f6085ba691) | Dec 17, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [afef2952f9](https://bsd-hardware.info/?probe=afef2952f9) | Dec 17, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [b7e599f99d](https://bsd-hardware.info/?probe=b7e599f99d) | Dec 17, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [0da9ef9752](https://bsd-hardware.info/?probe=0da9ef9752) | Dec 17, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2fe9b1b8c9](https://bsd-hardware.info/?probe=2fe9b1b8c9) | Dec 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [a94bfdaa5c](https://bsd-hardware.info/?probe=a94bfdaa5c) | Dec 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [6bf18dfe5a](https://bsd-hardware.info/?probe=6bf18dfe5a) | Dec 16, 2022 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [cc51093e02](https://bsd-hardware.info/?probe=cc51093e02) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [76f607b100](https://bsd-hardware.info/?probe=76f607b100) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [a77d60297f](https://bsd-hardware.info/?probe=a77d60297f) | Dec 14, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [6ebcd7c974](https://bsd-hardware.info/?probe=6ebcd7c974) | Dec 14, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [ad7f977515](https://bsd-hardware.info/?probe=ad7f977515) | Dec 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [f52a3d3fa6](https://bsd-hardware.info/?probe=f52a3d3fa6) | Dec 13, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [abed96a938](https://bsd-hardware.info/?probe=abed96a938) | Dec 13, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [66e0c118d2](https://bsd-hardware.info/?probe=66e0c118d2) | Dec 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [128ce54404](https://bsd-hardware.info/?probe=128ce54404) | Dec 12, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [76519f54e9](https://bsd-hardware.info/?probe=76519f54e9) | Dec 12, 2022 |
| Gigabyte      | X99-Designare EX-CF         | Desktop     | [de5bf4b420](https://bsd-hardware.info/?probe=de5bf4b420) | Dec 12, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [2bf8839d12](https://bsd-hardware.info/?probe=2bf8839d12) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [809da57d90](https://bsd-hardware.info/?probe=809da57d90) | Dec 11, 2022 |
| MSI           | H81M-P33                    | Desktop     | [1f110891d0](https://bsd-hardware.info/?probe=1f110891d0) | Dec 11, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [028383847e](https://bsd-hardware.info/?probe=028383847e) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [99502ebe9a](https://bsd-hardware.info/?probe=99502ebe9a) | Dec 11, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ad71b00b0d](https://bsd-hardware.info/?probe=ad71b00b0d) | Dec 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4b14039072](https://bsd-hardware.info/?probe=4b14039072) | Dec 11, 2022 |
| Dell          | 03X6X0 A02                  | Server      | [0939871923](https://bsd-hardware.info/?probe=0939871923) | Dec 11, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [808108016d](https://bsd-hardware.info/?probe=808108016d) | Dec 10, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [0b08951f1c](https://bsd-hardware.info/?probe=0b08951f1c) | Dec 10, 2022 |
| Dell          | 0DRG19 A00                  | Mini pc     | [bbca9fc84f](https://bsd-hardware.info/?probe=bbca9fc84f) | Dec 09, 2022 |
| Protectli     | VP2410 10                   | Desktop     | [3f55143fd9](https://bsd-hardware.info/?probe=3f55143fd9) | Dec 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [6b03cb139e](https://bsd-hardware.info/?probe=6b03cb139e) | Dec 09, 2022 |
| Dell          | 05GD68 A00                  | Desktop     | [b2f0da8246](https://bsd-hardware.info/?probe=b2f0da8246) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Protectli     | FW4C Ver                    | Desktop     | [71368e5cde](https://bsd-hardware.info/?probe=71368e5cde) | Dec 08, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [9862c1b507](https://bsd-hardware.info/?probe=9862c1b507) | Dec 07, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6db81b5ffe](https://bsd-hardware.info/?probe=6db81b5ffe) | Dec 07, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [8ac499a511](https://bsd-hardware.info/?probe=8ac499a511) | Dec 07, 2022 |
| HP            | 1495                        | Desktop     | [3f033cb7f5](https://bsd-hardware.info/?probe=3f033cb7f5) | Dec 07, 2022 |
| Sophos        | XG                          | Firewall    | [b29a7eaa33](https://bsd-hardware.info/?probe=b29a7eaa33) | Dec 07, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [61347ab3e9](https://bsd-hardware.info/?probe=61347ab3e9) | Dec 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [e3dad11b11](https://bsd-hardware.info/?probe=e3dad11b11) | Dec 06, 2022 |
| DFI           | BE17X(170/171/173)          | Notebook    | [9822160345](https://bsd-hardware.info/?probe=9822160345) | Dec 05, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f130844e1e](https://bsd-hardware.info/?probe=f130844e1e) | Dec 05, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [05566134f9](https://bsd-hardware.info/?probe=05566134f9) | Dec 05, 2022 |
| Google        | Lick                        | Notebook    | [8099b2df21](https://bsd-hardware.info/?probe=8099b2df21) | Dec 04, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [54d1511b82](https://bsd-hardware.info/?probe=54d1511b82) | Dec 04, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d72a45fb8f](https://bsd-hardware.info/?probe=d72a45fb8f) | Dec 04, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [595d174631](https://bsd-hardware.info/?probe=595d174631) | Dec 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8ee41750dc](https://bsd-hardware.info/?probe=8ee41750dc) | Dec 04, 2022 |
| Sophos        | XG                          | Firewall    | [a51c56cb12](https://bsd-hardware.info/?probe=a51c56cb12) | Dec 04, 2022 |
| Google        | Lick                        | Notebook    | [9eb2abcdcc](https://bsd-hardware.info/?probe=9eb2abcdcc) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [aeb690b9f3](https://bsd-hardware.info/?probe=aeb690b9f3) | Dec 03, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [1916a4064b](https://bsd-hardware.info/?probe=1916a4064b) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d4e60c5984](https://bsd-hardware.info/?probe=d4e60c5984) | Dec 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [90de1777bc](https://bsd-hardware.info/?probe=90de1777bc) | Dec 02, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [f8719b2320](https://bsd-hardware.info/?probe=f8719b2320) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [5c3941eb3f](https://bsd-hardware.info/?probe=5c3941eb3f) | Dec 02, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d3b72fdce8](https://bsd-hardware.info/?probe=d3b72fdce8) | Dec 02, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [243e309a04](https://bsd-hardware.info/?probe=243e309a04) | Dec 01, 2022 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [03708406e8](https://bsd-hardware.info/?probe=03708406e8) | Dec 01, 2022 |
| HP            | 8054                        | Desktop     | [c25adeb2ff](https://bsd-hardware.info/?probe=c25adeb2ff) | Dec 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [504a659236](https://bsd-hardware.info/?probe=504a659236) | Dec 01, 2022 |
| HP            | 8103 A01                    | Mini pc     | [5cd982c2ee](https://bsd-hardware.info/?probe=5cd982c2ee) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [794e041b13](https://bsd-hardware.info/?probe=794e041b13) | Nov 30, 2022 |
| Protectli     | FW6                         | Desktop     | [95f3201109](https://bsd-hardware.info/?probe=95f3201109) | Nov 30, 2022 |
| Protectli     | FW4A Ver                    | Desktop     | [9e6e0f5548](https://bsd-hardware.info/?probe=9e6e0f5548) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7308d658dc](https://bsd-hardware.info/?probe=7308d658dc) | Nov 29, 2022 |
| HP            | 8299                        | Desktop     | [d697a2e953](https://bsd-hardware.info/?probe=d697a2e953) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | Notebook    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b1f32ca8a1](https://bsd-hardware.info/?probe=b1f32ca8a1) | Nov 28, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [b4cc780c40](https://bsd-hardware.info/?probe=b4cc780c40) | Nov 28, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fd111870fa](https://bsd-hardware.info/?probe=fd111870fa) | Nov 28, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI           | H81M-P33                    | Desktop     | [597d48d1c9](https://bsd-hardware.info/?probe=597d48d1c9) | Nov 27, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [10d76fd431](https://bsd-hardware.info/?probe=10d76fd431) | Nov 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [383341b2f1](https://bsd-hardware.info/?probe=383341b2f1) | Nov 27, 2022 |
| HP            | 18E7                        | Desktop     | [c7635c715f](https://bsd-hardware.info/?probe=c7635c715f) | Nov 26, 2022 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [33c1878560](https://bsd-hardware.info/?probe=33c1878560) | Nov 26, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [2b00248458](https://bsd-hardware.info/?probe=2b00248458) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [6de307244e](https://bsd-hardware.info/?probe=6de307244e) | Nov 26, 2022 |
| Protectli     | FW2B Ver                    | Desktop     | [e03929e52f](https://bsd-hardware.info/?probe=e03929e52f) | Nov 25, 2022 |
| Supermicro    | M11SDV-8C+-LN4F             | Server      | [bcf17b19ec](https://bsd-hardware.info/?probe=bcf17b19ec) | Nov 25, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [dc8015adc3](https://bsd-hardware.info/?probe=dc8015adc3) | Nov 25, 2022 |
| Dell          | 0HFG24 A01                  | Server      | [ca48ff12d3](https://bsd-hardware.info/?probe=ca48ff12d3) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [de7f2ee053](https://bsd-hardware.info/?probe=de7f2ee053) | Nov 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [5aa1f0193a](https://bsd-hardware.info/?probe=5aa1f0193a) | Nov 24, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [08d048da80](https://bsd-hardware.info/?probe=08d048da80) | Nov 24, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [1b6870d481](https://bsd-hardware.info/?probe=1b6870d481) | Nov 23, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [7fabc0cb8a](https://bsd-hardware.info/?probe=7fabc0cb8a) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [337d5f0f4b](https://bsd-hardware.info/?probe=337d5f0f4b) | Nov 23, 2022 |
| Protectli     | FW4B                        | Desktop     | [d3090c9e8e](https://bsd-hardware.info/?probe=d3090c9e8e) | Nov 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [4d33b6da51](https://bsd-hardware.info/?probe=4d33b6da51) | Nov 23, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [d4791d1dfc](https://bsd-hardware.info/?probe=d4791d1dfc) | Nov 22, 2022 |
| Dell          | Edge Gateway 5000           | Mini pc     | [18f8f8f8b5](https://bsd-hardware.info/?probe=18f8f8f8b5) | Nov 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [77fa42b66c](https://bsd-hardware.info/?probe=77fa42b66c) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f7129f1c87](https://bsd-hardware.info/?probe=f7129f1c87) | Nov 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [17aa370584](https://bsd-hardware.info/?probe=17aa370584) | Nov 21, 2022 |
| Supermicro    | M11SDV-4CT-LN4F             | Server      | [2d8d0056c4](https://bsd-hardware.info/?probe=2d8d0056c4) | Nov 21, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [5030575f0a](https://bsd-hardware.info/?probe=5030575f0a) | Nov 20, 2022 |
| Dell          | 07F37C A01                  | Desktop     | [efb5c9d03d](https://bsd-hardware.info/?probe=efb5c9d03d) | Nov 20, 2022 |
| MSI           | H81M-P33                    | Desktop     | [d3303d1962](https://bsd-hardware.info/?probe=d3303d1962) | Nov 20, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [b1512a254c](https://bsd-hardware.info/?probe=b1512a254c) | Nov 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [521e5ffa8e](https://bsd-hardware.info/?probe=521e5ffa8e) | Nov 20, 2022 |
| HP            | 8054                        | Desktop     | [2c1e20c9e7](https://bsd-hardware.info/?probe=2c1e20c9e7) | Nov 20, 2022 |
| Hardkernel    | ODROID-H3                   | Desktop     | [ec7611edd1](https://bsd-hardware.info/?probe=ec7611edd1) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [c226ac3d9b](https://bsd-hardware.info/?probe=c226ac3d9b) | Nov 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [5d3ccb6891](https://bsd-hardware.info/?probe=5d3ccb6891) | Nov 20, 2022 |
| CncTion       | N5105-4L B0                 | Desktop     | [449dcd1463](https://bsd-hardware.info/?probe=449dcd1463) | Nov 19, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [794fe8eb65](https://bsd-hardware.info/?probe=794fe8eb65) | Nov 19, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [bf83fc6cdb](https://bsd-hardware.info/?probe=bf83fc6cdb) | Nov 19, 2022 |
| Supermicro    | X11SDV-4C-TP8F              | Desktop     | [402a623ed0](https://bsd-hardware.info/?probe=402a623ed0) | Nov 19, 2022 |
| Foxconn       | H67S/H61SP                  | Desktop     | [80ad331089](https://bsd-hardware.info/?probe=80ad331089) | Nov 19, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [18062e5bd5](https://bsd-hardware.info/?probe=18062e5bd5) | Nov 19, 2022 |
| Dell          | 0GN4PW A00                  | Desktop     | [9127ec4dac](https://bsd-hardware.info/?probe=9127ec4dac) | Nov 19, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2eba32390f](https://bsd-hardware.info/?probe=2eba32390f) | Nov 19, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [eaf4ec693e](https://bsd-hardware.info/?probe=eaf4ec693e) | Nov 19, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f25480c54a](https://bsd-hardware.info/?probe=f25480c54a) | Nov 18, 2022 |
| HP            | 82FE 11                     | Desktop     | [547e5e3ce1](https://bsd-hardware.info/?probe=547e5e3ce1) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [296b446a8f](https://bsd-hardware.info/?probe=296b446a8f) | Nov 18, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [ddf3f8603a](https://bsd-hardware.info/?probe=ddf3f8603a) | Nov 17, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [d98d84f1a4](https://bsd-hardware.info/?probe=d98d84f1a4) | Nov 17, 2022 |
| Supermicro    | A2SDi-4C-HLN4F              | Desktop     | [9cd1c1fc21](https://bsd-hardware.info/?probe=9cd1c1fc21) | Nov 17, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [15458aff84](https://bsd-hardware.info/?probe=15458aff84) | Nov 16, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [47f82850da](https://bsd-hardware.info/?probe=47f82850da) | Nov 16, 2022 |
| HP            | ProLiant DL120 Gen9         | Server      | [94513a53f8](https://bsd-hardware.info/?probe=94513a53f8) | Nov 16, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [94afb24fbc](https://bsd-hardware.info/?probe=94afb24fbc) | Nov 16, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [5096994f99](https://bsd-hardware.info/?probe=5096994f99) | Nov 16, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [314916c885](https://bsd-hardware.info/?probe=314916c885) | Nov 15, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [dd637e0562](https://bsd-hardware.info/?probe=dd637e0562) | Nov 15, 2022 |
| Dell          | 06D7TR A00                  | Desktop     | [9e568eb5ee](https://bsd-hardware.info/?probe=9e568eb5ee) | Nov 14, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [74a717c2e6](https://bsd-hardware.info/?probe=74a717c2e6) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6f1e732a53](https://bsd-hardware.info/?probe=6f1e732a53) | Nov 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| OPNsense 21.7.7   | 90        | 2.61%   |
| OPNsense 22.7.10  | 81        | 2.35%   |
| OPNsense 23.1     | 78        | 2.26%   |
| OPNsense 21.7.3   | 77        | 2.23%   |
| OPNsense 21.7.1   | 69        | 2%      |
| OPNsense 22.1     | 68        | 1.97%   |
| OPNsense 21.1.5   | 67        | 1.94%   |
| OPNsense 23.1.1   | 66        | 1.91%   |
| helloSystem 0.7.0 | 66        | 1.91%   |
| OPNsense 22.7.4   | 65        | 1.88%   |
| OPNsense 23.1.5   | 64        | 1.85%   |
| OPNsense 22.1.10  | 64        | 1.85%   |
| OPNsense 20.7.8   | 61        | 1.77%   |
| OPNsense 21.1.4   | 60        | 1.74%   |
| FreeBSD 13.0      | 60        | 1.74%   |
| OPNsense 22.1.8   | 58        | 1.68%   |
| OPNsense 21.1.3   | 58        | 1.68%   |
| FreeBSD 13.1      | 56        | 1.62%   |
| OPNsense 21.1     | 51        | 1.48%   |
| OPNsense 22.7.9   | 50        | 1.45%   |
| OPNsense 21.1.8   | 50        | 1.45%   |
| OPNsense 22.7.6   | 49        | 1.42%   |
| helloSystem 0.8.0 | 46        | 1.33%   |
| OPNsense 22.7.8   | 45        | 1.3%    |
| OPNsense 22.7.2   | 45        | 1.3%    |
| OPNsense 23.1.6   | 43        | 1.24%   |
| OPNsense 22.7     | 43        | 1.24%   |
| OPNsense 22.1.6   | 42        | 1.22%   |
| OPNsense 22.1.4   | 42        | 1.22%   |
| OPNsense 22.1.2   | 42        | 1.22%   |
| OPNsense 21.1.7   | 42        | 1.22%   |
| OPNsense 21.1.1   | 42        | 1.22%   |
| helloSystem 0.5.0 | 42        | 1.22%   |
| OPNsense 22.7.7   | 40        | 1.16%   |
| OPNsense 23.1.3   | 37        | 1.07%   |
| OPNsense 22.1.1   | 36        | 1.04%   |
| OPNsense 21.7.6   | 36        | 1.04%   |
| OPNsense 21.1.6   | 36        | 1.04%   |
| OPNsense 23.1.4   | 34        | 0.98%   |
| helloSystem 0.8.1 | 34        | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 1548      | 60.73%  |
| FreeBSD     | 502       | 19.69%  |
| helloSystem | 227       | 8.91%   |
| OpenBSD     | 96        | 3.77%   |
| GhostBSD    | 49        | 1.92%   |
| NomadBSD    | 36        | 1.41%   |
| pfSense     | 18        | 0.71%   |
| FreeNAS     | 17        | 0.67%   |
| MidnightBSD | 15        | 0.59%   |
| TrueNAS     | 11        | 0.43%   |
| HardenedBSD | 9         | 0.35%   |
| NetBSD      | 7         | 0.27%   |
| DragonFly   | 6         | 0.24%   |
| FuryBSD     | 3         | 0.12%   |
| XigmaNAS    | 2         | 0.08%   |
| OS108       | 2         | 0.08%   |
| ClonOS      | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 2473      | 97.82%  |
| i386    | 28        | 1.11%   |
| arm64   | 23        | 0.91%   |
| powerpc | 3         | 0.12%   |
| sparc64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 1795      | 69.68%  |
| helloDesktop  | 241       | 9.36%   |
| XFCE          | 106       | 4.11%   |
| KDE5          | 79        | 3.07%   |
| MATE          | 71        | 2.76%   |
| fvwm          | 58        | 2.25%   |
| TWM           | 54        | 2.1%    |
| Openbox       | 47        | 1.82%   |
| GNOME         | 46        | 1.79%   |
| i3            | 29        | 1.13%   |
| Cinnamon      | 12        | 0.47%   |
| Enlightenment | 8         | 0.31%   |
| Fluxbox       | 6         | 0.23%   |
| Lumina        | 5         | 0.19%   |
| AwesomeWM     | 3         | 0.12%   |
| Xfwm4         | 2         | 0.08%   |
| LXQt          | 2         | 0.08%   |
| GNUstep       | 2         | 0.08%   |
| DWM           | 2         | 0.08%   |
| Window Maker  | 1         | 0.04%   |
| spectrwm      | 1         | 0.04%   |
| sdorfehs      | 1         | 0.04%   |
| Picom         | 1         | 0.04%   |
| LXDE          | 1         | 0.04%   |
| KDE           | 1         | 0.04%   |
| Compton       | 1         | 0.04%   |
| CDE           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 1819      | 71.56%  |
| X11     | 717       | 28.21%  |
| Wayland | 6         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 2001      | 78.26%  |
| SLiM    | 323       | 12.63%  |
| LightDM | 82        | 3.21%   |
| SDDM    | 78        | 3.05%   |
| XDM     | 43        | 1.68%   |
| GDM     | 27        | 1.06%   |
| Ly      | 3         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 1858      | 71.82%  |
| en_US           | 382       | 14.77%  |
| C               | 297       | 11.48%  |
| en              | 32        | 1.24%   |
| fr_FR           | 4         | 0.15%   |
| fr              | 3         | 0.12%   |
| ru_RU           | 2         | 0.08%   |
| en_US.US-ASCII  | 2         | 0.08%   |
| en_US.ISO8859-1 | 2         | 0.08%   |
| en_GB           | 2         | 0.08%   |
| es_CO           | 1         | 0.04%   |
| en_US.utf-8     | 1         | 0.04%   |
| de_DE           | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2156      | 83.92%  |
| BIOS | 413       | 16.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 1320      | 50.67%  |
| Zfs     | 1103      | 42.34%  |
| Ffs     | 96        | 3.69%   |
| Cd9660  | 79        | 3.03%   |
| Hammer2 | 6         | 0.23%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2334      | 91.39%  |
| MBR     | 193       | 7.56%   |
| Unknown | 21        | 0.82%   |
| BSD     | 6         | 0.23%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 424       | 16.79%  |
| Hewlett-Packard         | 265       | 10.49%  |
| Lenovo                  | 230       | 9.11%   |
| Supermicro              | 220       | 8.71%   |
| Protectli               | 183       | 7.24%   |
| Unknown                 | 183       | 7.24%   |
| ASUSTek Computer        | 169       | 6.69%   |
| Intel                   | 104       | 4.12%   |
| ASRock                  | 94        | 3.72%   |
| Gigabyte Technology     | 73        | 2.89%   |
| MSI                     | 65        | 2.57%   |
| Apple                   | 43        | 1.7%    |
| AMI                     | 43        | 1.7%    |
| PC Engines              | 34        | 1.35%   |
| Acer                    | 25        | 0.99%   |
| Techvision              | 20        | 0.79%   |
| Deciso                  | 19        | 0.75%   |
| Sophos                  | 16        | 0.63%   |
| AZW                     | 14        | 0.55%   |
| Google                  | 12        | 0.48%   |
| CompuLab                | 12        | 0.48%   |
| Biostar                 | 12        | 0.48%   |
| Toshiba                 | 10        | 0.4%    |
| System76                | 10        | 0.4%    |
| AWOW                    | 10        | 0.4%    |
| MW                      | 9         | 0.36%   |
| BESSTAR Tech            | 9         | 0.36%   |
| ASRockRack              | 9         | 0.36%   |
| Foxconn                 | 8         | 0.32%   |
| Seeed Studio            | 7         | 0.28%   |
| Fujitsu                 | 7         | 0.28%   |
| Framework               | 7         | 0.28%   |
| Shuttle                 | 6         | 0.24%   |
| SeeedStudio             | 6         | 0.24%   |
| HARDKERNEL              | 6         | 0.24%   |
| Datto                   | 6         | 0.24%   |
| CheckPoint              | 6         | 0.24%   |
| ZOTAC                   | 5         | 0.2%    |
| Raspberry Pi Foundation | 5         | 0.2%    |
| Cisco Systems           | 5         | 0.2%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 189       | 7.48%   |
| Protectli FW4B                      | 68        | 2.69%   |
| Supermicro Super Server             | 59        | 2.34%   |
| Protectli FW6                       | 50        | 1.98%   |
| AMI Aptio CRB                       | 38        | 1.5%    |
| Intel Q3XXG4-P V1.0                 | 34        | 1.35%   |
| HP t620 PLUS Quad Core TC           | 24        | 0.95%   |
| HP t730 Thin Client                 | 23        | 0.91%   |
| Dell OptiPlex 9020                  | 22        | 0.87%   |
| Dell OptiPlex 3020                  | 22        | 0.87%   |
| Supermicro X9SCL/X9SCM              | 21        | 0.83%   |
| Techvision TVI7309X                 | 20        | 0.79%   |
| ASUS All Series                     | 19        | 0.75%   |
| Dell PowerEdge R210 II              | 18        | 0.71%   |
| Supermicro X10SLH-N6-ST031          | 16        | 0.63%   |
| PC Engines APU2                     | 16        | 0.63%   |
| Protectli VP2410                    | 14        | 0.55%   |
| Dell OptiPlex 7010                  | 14        | 0.55%   |
| Protectli FW2B                      | 13        | 0.51%   |
| PC Engines apu4                     | 13        | 0.51%   |
| Dell OptiPlex 990                   | 13        | 0.51%   |
| CompuLab fitlet2                    | 12        | 0.48%   |
| HP EliteDesk 800 G1 SFF             | 11        | 0.44%   |
| Dell Wyse 5070 Extended Thin Client | 11        | 0.44%   |
| Supermicro A1SAi                    | 10        | 0.4%    |
| Dell OptiPlex 9010                  | 10        | 0.4%    |
| Deciso Netboard A20                 | 10        | 0.4%    |
| Sophos XG                           | 9         | 0.36%   |
| MW GMLK-2_5G4L                      | 9         | 0.36%   |
| Intel Nobilis                       | 9         | 0.36%   |
| Dell PowerEdge R610                 | 9         | 0.36%   |
| Protectli FW4C                      | 8         | 0.32%   |
| HP ProDesk 600 G1 SFF               | 8         | 0.32%   |
| Dell PowerEdge R630                 | 8         | 0.32%   |
| Protectli FW6E                      | 7         | 0.28%   |
| Protectli FW6D                      | 7         | 0.28%   |
| Protectli FW1                       | 7         | 0.28%   |
| HP EliteDesk 800 G2 SFF             | 7         | 0.28%   |
| HP Compaq Elite 8300 SFF            | 7         | 0.28%   |
| Framework Laptop                    | 7         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 189       | 7.48%   |
| Dell OptiPlex              | 166       | 6.57%   |
| Lenovo ThinkPad            | 134       | 5.3%    |
| Dell PowerEdge             | 104       | 4.12%   |
| Protectli FW4B             | 68        | 2.69%   |
| Supermicro Super           | 59        | 2.34%   |
| Lenovo ThinkCentre         | 51        | 2.02%   |
| Protectli FW6              | 50        | 1.98%   |
| Dell Inspiron              | 42        | 1.66%   |
| Dell Latitude              | 38        | 1.5%    |
| AMI Aptio                  | 38        | 1.5%    |
| HP EliteDesk               | 36        | 1.43%   |
| Intel Q3XXG4-P             | 35        | 1.39%   |
| Dell Precision             | 31        | 1.23%   |
| HP ProDesk                 | 29        | 1.15%   |
| HP t620                    | 26        | 1.03%   |
| ASUS ROG                   | 26        | 1.03%   |
| ASUS TUF                   | 24        | 0.95%   |
| HP t730                    | 23        | 0.91%   |
| HP Pavilion                | 23        | 0.91%   |
| ASUS PRIME                 | 23        | 0.91%   |
| Supermicro X9SCL           | 21        | 0.83%   |
| HP ProLiant                | 21        | 0.83%   |
| HP Compaq                  | 21        | 0.83%   |
| Techvision TVI7309X        | 20        | 0.79%   |
| ASUS All                   | 19        | 0.75%   |
| Supermicro X10SLH-N6-ST031 | 16        | 0.63%   |
| PC Engines APU2            | 16        | 0.63%   |
| ASRock X570                | 15        | 0.59%   |
| Protectli VP2410           | 14        | 0.55%   |
| Protectli FW2B             | 13        | 0.51%   |
| PC Engines apu4            | 13        | 0.51%   |
| Dell XPS                   | 12        | 0.48%   |
| CompuLab fitlet2           | 12        | 0.48%   |
| Dell Wyse                  | 11        | 0.44%   |
| Deciso Netboard            | 11        | 0.44%   |
| Supermicro A1SAi           | 10        | 0.4%    |
| Lenovo IdeaPad             | 10        | 0.4%    |
| Acer Aspire                | 10        | 0.4%    |
| Sophos XG                  | 9         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 328       | 12.98%  |
| 2019    | 286       | 11.32%  |
| 2020    | 234       | 9.26%   |
| 2021    | 202       | 8%      |
| 2022    | 196       | 7.76%   |
| 2016    | 174       | 6.89%   |
| 2014    | 172       | 6.81%   |
| 2011    | 152       | 6.02%   |
| 2013    | 150       | 5.94%   |
| 2015    | 148       | 5.86%   |
| 2017    | 133       | 5.27%   |
| 2012    | 117       | 4.63%   |
| 2010    | 67        | 2.65%   |
| 2009    | 45        | 1.78%   |
| Unknown | 38        | 1.5%    |
| 2008    | 33        | 1.31%   |
| 2007    | 20        | 0.79%   |
| 2023    | 12        | 0.48%   |
| 2006    | 11        | 0.44%   |
| 2004    | 4         | 0.16%   |
| 2005    | 1         | 0.04%   |
| 2003    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1583      | 62.67%  |
| Notebook       | 449       | 17.78%  |
| Server         | 260       | 10.29%  |
| Mini pc        | 174       | 6.89%   |
| Firewall       | 23        | 0.91%   |
| Convertible    | 17        | 0.67%   |
| System on chip | 13        | 0.51%   |
| All in one     | 7         | 0.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2423      | 95.92%  |
| Yes  | 103       | 4.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 928       | 35.83%  |
| 16.01-24.0      | 610       | 23.55%  |
| 4.01-8.0        | 413       | 15.95%  |
| 32.01-64.0      | 328       | 12.66%  |
| 64.01-256.0     | 145       | 5.6%    |
| 2.01-3.0        | 56        | 2.16%   |
| 24.01-32.0      | 51        | 1.97%   |
| 3.01-4.0        | 30        | 1.16%   |
| 0.51-1.0        | 12        | 0.46%   |
| 1.01-2.0        | 9         | 0.35%   |
| 0.01-0.5        | 5         | 0.19%   |
| More than 256.0 | 3         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 1162      | 43.92%  |
| 0.51-1.0    | 790       | 29.86%  |
| 1.01-2.0    | 390       | 14.74%  |
| 2.01-3.0    | 77        | 2.91%   |
| 4.01-8.0    | 68        | 2.57%   |
| 3.01-4.0    | 46        | 1.74%   |
| 8.01-16.0   | 37        | 1.4%    |
| 24.01-32.0  | 18        | 0.68%   |
| 16.01-24.0  | 18        | 0.68%   |
| 32.01-64.0  | 12        | 0.45%   |
| 0           | 11        | 0.42%   |
| Unknown     | 11        | 0.42%   |
| 64.01-256.0 | 6         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1772      | 67.94%  |
| 2      | 353       | 13.54%  |
| 0      | 220       | 8.44%   |
| 3      | 102       | 3.91%   |
| 4      | 43        | 1.65%   |
| 5      | 31        | 1.19%   |
| 6      | 22        | 0.84%   |
| 7      | 12        | 0.46%   |
| 14     | 8         | 0.31%   |
| 10     | 7         | 0.27%   |
| 8      | 7         | 0.27%   |
| 12     | 6         | 0.23%   |
| 9      | 6         | 0.23%   |
| 11     | 4         | 0.15%   |
| 21     | 2         | 0.08%   |
| 18     | 2         | 0.08%   |
| 17     | 2         | 0.08%   |
| 58     | 1         | 0.04%   |
| 40     | 1         | 0.04%   |
| 28     | 1         | 0.04%   |
| 26     | 1         | 0.04%   |
| 22     | 1         | 0.04%   |
| 19     | 1         | 0.04%   |
| 16     | 1         | 0.04%   |
| 15     | 1         | 0.04%   |
| 13     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1983      | 77.58%  |
| Yes       | 573       | 22.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2424      | 95.96%  |
| No        | 102       | 4.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1672      | 65.62%  |
| Yes       | 876       | 34.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1937      | 76.17%  |
| Yes       | 606       | 23.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 2526      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Seattle        | 41        | 1.48%   |
| Brooklyn       | 41        | 1.48%   |
| Chicago        | 40        | 1.44%   |
| New York       | 37        | 1.34%   |
| Denver         | 34        | 1.23%   |
| Los Angeles    | 30        | 1.08%   |
| Portland       | 29        | 1.05%   |
| Dallas         | 29        | 1.05%   |
| Austin         | 24        | 0.87%   |
| Rochester      | 21        | 0.76%   |
| Phoenix        | 21        | 0.76%   |
| San Francisco  | 19        | 0.69%   |
| Atlanta        | 18        | 0.65%   |
| Columbus       | 17        | 0.61%   |
| Mountain View  | 16        | 0.58%   |
| Grand Rapids   | 16        | 0.58%   |
| Houston        | 15        | 0.54%   |
| Springfield    | 14        | 0.51%   |
| Ypsilanti      | 13        | 0.47%   |
| Omaha          | 13        | 0.47%   |
| Oakland        | 13        | 0.47%   |
| Minneapolis    | 13        | 0.47%   |
| Salem          | 11        | 0.4%    |
| Las Vegas      | 11        | 0.4%    |
| Charlotte      | 11        | 0.4%    |
| Washington     | 10        | 0.36%   |
| Vienna         | 10        | 0.36%   |
| San Jose       | 10        | 0.36%   |
| San Antonio    | 10        | 0.36%   |
| Salt Lake City | 10        | 0.36%   |
| Raleigh        | 10        | 0.36%   |
| Milwaukee      | 10        | 0.36%   |
| Lexington      | 10        | 0.36%   |
| Kansas City    | 10        | 0.36%   |
| Jacksonville   | 10        | 0.36%   |
| Fremont        | 10        | 0.36%   |
| Fort Worth     | 10        | 0.36%   |
| Bothell        | 10        | 0.36%   |
| Philadelphia   | 9         | 0.32%   |
| Orlando        | 9         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 475       | 882    | 15.79%  |
| WDC                 | 388       | 1102   | 12.9%   |
| Seagate             | 279       | 748    | 9.28%   |
| Kingston            | 208       | 272    | 6.91%   |
| Crucial             | 141       | 221    | 4.69%   |
| SanDisk             | 135       | 173    | 4.49%   |
| Intel               | 132       | 245    | 4.39%   |
| Toshiba             | 107       | 186    | 3.56%   |
| Transcend           | 99        | 184    | 3.29%   |
| Hitachi             | 66        | 157    | 2.19%   |
| Hoodisk             | 61        | 83     | 2.03%   |
| A-DATA Technology   | 61        | 95     | 2.03%   |
| SK hynix            | 58        | 74     | 1.93%   |
| Phison              | 58        | 91     | 1.93%   |
| China               | 54        | 80     | 1.8%    |
| PNY                 | 53        | 72     | 1.76%   |
| Protectli           | 49        | 80     | 1.63%   |
| SPCC                | 41        | 73     | 1.36%   |
| HGST                | 37        | 107    | 1.23%   |
| Hewlett-Packard     | 34        | 102    | 1.13%   |
| Micron Technology   | 30        | 38     | 1%      |
| Dogfish             | 28        | 46     | 0.93%   |
| NVMe                | 24        | 31     | 0.8%    |
| BIWIN               | 23        | 38     | 0.76%   |
| FORESEE             | 20        | 28     | 0.66%   |
| OCZ                 | 19        | 30     | 0.63%   |
| Apple               | 19        | 23     | 0.63%   |
| Team                | 18        | 29     | 0.6%    |
| Apacer              | 16        | 19     | 0.53%   |
| KingSpec            | 15        | 18     | 0.5%    |
| Corsair             | 15        | 35     | 0.5%    |
| Mushkin             | 13        | 20     | 0.43%   |
| Patriot             | 12        | 13     | 0.4%    |
| Zheino              | 10        | 18     | 0.33%   |
| Supermicro          | 10        | 10     | 0.33%   |
| LITEON              | 10        | 16     | 0.33%   |
| KIOXIA              | 10        | 16     | 0.33%   |
| Silicon Motion      | 9         | 11     | 0.3%    |
| OWC                 | 9         | 13     | 0.3%    |
| Lexar               | 9         | 15     | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB       | 30        | 0.91%   |
| Kingston SA400S37240G 240GB     | 30        | 0.91%   |
| Hoodisk SSD 32GB                | 24        | 0.73%   |
| Kingston SUV500MS240G 240GB     | 23        | 0.7%    |
| Seagate ST500DM002-1BD142 500GB | 21        | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB  | 20        | 0.61%   |
| Samsung SSD 860 EVO 500GB       | 20        | 0.61%   |
| Samsung SSD 860 EVO 1TB         | 20        | 0.61%   |
| Kingston SUV500MS120G 120GB     | 20        | 0.61%   |
| PNY CS900 120GB SSD             | 19        | 0.58%   |
| Kingston SA400S37120G 120GB     | 18        | 0.54%   |
| Samsung SSD 850 EVO 500GB       | 17        | 0.51%   |
| Protectli 120GB mSATA           | 17        | 0.51%   |
| Hoodisk SSD 128GB               | 17        | 0.51%   |
| BIWIN SSD 128GB                 | 17        | 0.51%   |
| Samsung SSD 860 EVO 250GB       | 16        | 0.48%   |
| WDC WD800JD-75MSA3 80GB         | 15        | 0.45%   |
| Crucial CT250MX500SSD1 250GB    | 15        | 0.45%   |
| SanDisk SSD PLUS 240GB          | 14        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB    | 14        | 0.42%   |
| Phison Sabrent 2TB              | 14        | 0.42%   |
| Hoodisk SSD 64GB                | 14        | 0.42%   |
| Crucial CT500MX500SSD1 500GB    | 14        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB     | 14        | 0.42%   |
| Transcend TS256GMTS952T2 256GB  | 13        | 0.39%   |
| Samsung SSD 870 EVO 500GB       | 13        | 0.39%   |
| Samsung SSD 860 EVO M.2 250GB   | 13        | 0.39%   |
| Kingston SV300S37A120G 120GB    | 13        | 0.39%   |
| FORESEE 128GB SSD               | 13        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB        | 12        | 0.36%   |
| SPCC Solid State Disk 128GB     | 12        | 0.36%   |
| China SATA SSD 120GB            | 12        | 0.36%   |
| WDC WDS500G3X0C-00SJG0 500GB    | 11        | 0.33%   |
| SanDisk SDSSDA120G 120GB        | 11        | 0.33%   |
| SanDisk SDSA6MM-016G-1006 16GB  | 11        | 0.33%   |
| HP RAID 0 293GB                 | 11        | 0.33%   |
| Dogfish SSD 128GB               | 11        | 0.33%   |
| WDC WD30EFRX-68EUZN0 3TB        | 10        | 0.3%    |
| Toshiba DT01ACA100 1TB          | 10        | 0.3%    |
| Samsung SSD 960 EVO 500GB       | 10        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 289       | 929    | 34.82%  |
| Seagate                            | 267       | 718    | 32.17%  |
| Toshiba                            | 85        | 158    | 10.24%  |
| Hitachi                            | 66        | 157    | 7.95%   |
| HGST                               | 37        | 107    | 4.46%   |
| Hewlett-Packard                    | 16        | 54     | 1.93%   |
| NVMe                               | 15        | 18     | 1.81%   |
| Samsung Electronics                | 12        | 17     | 1.45%   |
| Apple                              | 9         | 10     | 1.08%   |
| Maxtor                             | 4         | 8      | 0.48%   |
| Lexar                              | 3         | 3      | 0.36%   |
| Fujitsu                            | 3         | 3      | 0.36%   |
| LSI                                | 2         | 7      | 0.24%   |
| HPE                                | 2         | 7      | 0.24%   |
| Adaptec                            | 2         | 2      | 0.24%   |
| WD MediaMax                        | 1         | 3      | 0.12%   |
| QUANTUM                            | 1         | 2      | 0.12%   |
| Product:              USB DISK 3.0 | 1         | 1      | 0.12%   |
| OPENBSD                            | 1         | 1      | 0.12%   |
| NETAPP                             | 1         | 2      | 0.12%   |
| Memorex                            | 1         | 1      | 0.12%   |
| MaxDigital                         | 1         | 1      | 0.12%   |
| MARVELL                            | 1         | 1      | 0.12%   |
| IBM/Hitachi                        | 1         | 1      | 0.12%   |
| IBM-ESXS                           | 1         | 1      | 0.12%   |
| IBM-207x                           | 1         | 1      | 0.12%   |
| HPT                                | 1         | 8      | 0.12%   |
| Generic                            | 1         | 1      | 0.12%   |
| General                            | 1         | 1      | 0.12%   |
| ExcelStor Technology               | 1         | 4      | 0.12%   |
| Dell                               | 1         | 3      | 0.12%   |
| China                              | 1         | 1      | 0.12%   |
| ASMT                               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 318       | 595    | 18.42%  |
| Kingston            | 186       | 249    | 10.78%  |
| SanDisk             | 133       | 168    | 7.71%   |
| Crucial             | 119       | 183    | 6.89%   |
| Intel               | 98        | 198    | 5.68%   |
| Transcend           | 94        | 178    | 5.45%   |
| Hoodisk             | 60        | 82     | 3.48%   |
| China               | 53        | 79     | 3.07%   |
| PNY                 | 51        | 70     | 2.95%   |
| A-DATA Technology   | 51        | 76     | 2.95%   |
| Protectli           | 49        | 80     | 2.84%   |
| WDC                 | 45        | 82     | 2.61%   |
| SK hynix            | 31        | 40     | 1.8%    |
| SPCC                | 30        | 59     | 1.74%   |
| Phison              | 28        | 37     | 1.62%   |
| Dogfish             | 28        | 46     | 1.62%   |
| BIWIN               | 23        | 38     | 1.33%   |
| FORESEE             | 20        | 28     | 1.16%   |
| OCZ                 | 19        | 30     | 1.1%    |
| Micron Technology   | 19        | 24     | 1.1%    |
| Apacer              | 16        | 19     | 0.93%   |
| KingSpec            | 15        | 18     | 0.87%   |
| Hewlett-Packard     | 12        | 23     | 0.7%    |
| Corsair             | 12        | 17     | 0.7%    |
| Seagate             | 11        | 23     | 0.64%   |
| Zheino              | 10        | 18     | 0.58%   |
| Toshiba             | 10        | 13     | 0.58%   |
| Team                | 10        | 20     | 0.58%   |
| Supermicro          | 10        | 10     | 0.58%   |
| Patriot             | 10        | 11     | 0.58%   |
| Mushkin             | 10        | 16     | 0.58%   |
| Apple               | 10        | 13     | 0.58%   |
| OWC                 | 9         | 13     | 0.52%   |
| NVMe                | 9         | 11     | 0.52%   |
| LITEON              | 9         | 15     | 0.52%   |
| Plextor             | 7         | 12     | 0.41%   |
| LITEONIT            | 7         | 10     | 0.41%   |
| Innodisk            | 7         | 8      | 0.41%   |
| Lexar               | 6         | 12     | 0.35%   |
| ShiJi               | 5         | 6      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1556      | 2741   | 57.67%  |
| HDD  | 686       | 2232   | 25.43%  |
| NVMe | 456       | 756    | 16.9%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2030      | 4973   | 81.66%  |
| NVMe | 456       | 756    | 18.34%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1699      | 2942   | 72.11%  |
| 0.51-1.0   | 355       | 705    | 15.07%  |
| 1.01-2.0   | 128       | 341    | 5.43%   |
| 4.01-10.0  | 62        | 473    | 2.63%   |
| 3.01-4.0   | 49        | 202    | 2.08%   |
| 2.01-3.0   | 45        | 178    | 1.91%   |
| 10.01-20.0 | 17        | 128    | 0.72%   |
| 20.01-50.0 | 1         | 4      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1039      | 39.69%  |
| 251-500        | 474       | 18.11%  |
| 1-20           | 274       | 10.47%  |
| 51-100         | 251       | 9.59%   |
| 501-1000       | 242       | 9.24%   |
| 21-50          | 233       | 8.9%    |
| 1001-2000      | 62        | 2.37%   |
| More than 3000 | 23        | 0.88%   |
| Unknown        | 13        | 0.5%    |
| 2001-3000      | 7         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2345      | 89.78%  |
| 21-50          | 142       | 5.44%   |
| 51-100         | 57        | 2.18%   |
| 101-250        | 29        | 1.11%   |
| 251-500        | 13        | 0.5%    |
| Unknown        | 13        | 0.5%    |
| More than 3000 | 5         | 0.19%   |
| 501-1000       | 4         | 0.15%   |
| 2001-3000      | 2         | 0.08%   |
| 1001-2000      | 1         | 0.04%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7         | 11     | 1.97%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.41%   |
| Kingston SV300S37A60G 64GB            | 4         | 4      | 1.13%   |
| Kingston SMS200S3120G 120GB           | 4         | 4      | 1.13%   |
| Crucial CT275MX300SSD1 275GB          | 4         | 7      | 1.13%   |
| Apacer 16GB SATA Flash Drive          | 4         | 6      | 1.13%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3         | 3      | 0.85%   |
| SK hynix SC210 mSATA 256GB            | 3         | 3      | 0.85%   |
| Seagate ST3500418AS 500GB             | 3         | 10     | 0.85%   |
| Seagate ST2000DM008-2FR102 2TB        | 3         | 3      | 0.85%   |
| SanDisk SSD PLUS 240GB                | 3         | 4      | 0.85%   |
| Kingston SV300S37A120G 120GB          | 3         | 3      | 0.85%   |
| Apacer 32GB SATA Flash Drive          | 3         | 3      | 0.85%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 9      | 0.56%   |
| WDC WD2001FASS-00W2B0 2TB             | 2         | 3      | 0.56%   |
| WDC WD1600BEKT-66F3T2 160GB           | 2         | 4      | 0.56%   |
| WDC WD1600AAJS-75M0A0 160GB           | 2         | 2      | 0.56%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.56%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.56%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 0.56%   |
| SSSTC CVB-8D128-HP 128GB              | 2         | 2      | 0.56%   |
| SK hynix SC308 SATA 128GB             | 2         | 3      | 0.56%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 3      | 0.56%   |
| Seagate ST3500413AS 500GB             | 2         | 10     | 0.56%   |
| Seagate ST31000528AS 1TB              | 2         | 2      | 0.56%   |
| Seagate ST2000DL001-9VT156 2TB        | 2         | 2      | 0.56%   |
| Seagate ST1000DM003-9YN162 1TB        | 2         | 6      | 0.56%   |
| Samsung Electronics SSD 950 PRO 256GB | 2         | 2      | 0.56%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.56%   |
| MyDigitalSSD SB2 256GB                | 2         | 4      | 0.56%   |
| Kingston SUV400S37120G 120GB          | 2         | 3      | 0.56%   |
| Kingston SNS4151S316GD 16GB           | 2         | 4      | 0.56%   |
| Kingston SNS4151S316G 16GB            | 2         | 2      | 0.56%   |
| Intel SSDSC2BX200G4R 200GB            | 2         | 3      | 0.56%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.56%   |
| Hitachi HUA722020ALA331 2TB           | 2         | 4      | 0.56%   |
| Hitachi HUA722020ALA330 2TB           | 2         | 3      | 0.56%   |
| Hitachi HTS725032A9A364 320GB         | 2         | 2      | 0.56%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 0.56%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 128    | 21.28%  |
| WDC                 | 50        | 95     | 14.58%  |
| Kingston            | 26        | 29     | 7.58%   |
| Intel               | 26        | 32     | 7.58%   |
| Samsung Electronics | 23        | 34     | 6.71%   |
| Hitachi             | 23        | 29     | 6.71%   |
| Toshiba             | 21        | 30     | 6.12%   |
| Crucial             | 15        | 21     | 4.37%   |
| SanDisk             | 10        | 13     | 2.92%   |
| SK hynix            | 9         | 11     | 2.62%   |
| HGST                | 9         | 9      | 2.62%   |
| Apacer              | 7         | 9      | 2.04%   |
| OCZ                 | 4         | 4      | 1.17%   |
| Phison              | 3         | 3      | 0.87%   |
| LITEON              | 3         | 4      | 0.87%   |
| HP Phison           | 3         | 3      | 0.87%   |
| Apple               | 3         | 3      | 0.87%   |
| SSSTC               | 2         | 2      | 0.58%   |
| Patriot             | 2         | 2      | 0.58%   |
| MyDigitalSSD        | 2         | 4      | 0.58%   |
| Micron Technology   | 2         | 2      | 0.58%   |
| Maxtor              | 2         | 5      | 0.58%   |
| Corsair             | 2         | 2      | 0.58%   |
| A-DATA Technology   | 2         | 2      | 0.58%   |
| ZTC                 | 1         | 3      | 0.29%   |
| Wintec              | 1         | 1      | 0.29%   |
| WD MediaMax         | 1         | 3      | 0.29%   |
| VisionTek           | 1         | 1      | 0.29%   |
| Transcend           | 1         | 4      | 0.29%   |
| SPCC                | 1         | 3      | 0.29%   |
| PNY                 | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 3      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| KingDian            | 1         | 1      | 0.29%   |
| KeepData            | 1         | 1      | 0.29%   |
| INDMEM              | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| HPE                 | 1         | 3      | 0.29%   |
| Hewlett-Packard     | 1         | 4      | 0.29%   |
| Fujitsu             | 1         | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor               | Computers | Drives | Percent |
|----------------------|-----------|--------|---------|
| Seagate              | 73        | 128    | 38.62%  |
| WDC                  | 49        | 94     | 25.93%  |
| Hitachi              | 23        | 29     | 12.17%  |
| Toshiba              | 19        | 28     | 10.05%  |
| HGST                 | 9         | 9      | 4.76%   |
| Samsung Electronics  | 5         | 6      | 2.65%   |
| Maxtor               | 2         | 5      | 1.06%   |
| Apple                | 2         | 2      | 1.06%   |
| WD MediaMax          | 1         | 3      | 0.53%   |
| IBM/Hitachi          | 1         | 1      | 0.53%   |
| HPE                  | 1         | 3      | 0.53%   |
| Hewlett-Packard      | 1         | 4      | 0.53%   |
| Fujitsu              | 1         | 1      | 0.53%   |
| ExcelStor Technology | 1         | 2      | 0.53%   |
| China                | 1         | 1      | 0.53%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 182       | 316    | 54.33%  |
| SSD  | 150       | 199    | 44.78%  |
| NVMe | 3         | 3      | 0.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZYLN256HCHP-000L2 256GB | 2         | 2      | 28.57%  |
| SK hynix SC308 SATA 256GB                    | 1         | 1      | 14.29%  |
| Seagate ST3500418AS 500GB                    | 1         | 2      | 14.29%  |
| Samsung Electronics SSD 970 EVO Plus 500GB   | 1         | 1      | 14.29%  |
| Samsung Electronics HD204UI 2TB              | 1         | 2      | 14.29%  |
| Kingston SA2000M8500G 500GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 57.14%  |
| SK hynix            | 1         | 1      | 14.29%  |
| Seagate             | 1         | 2      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2078      | 5053   | 83.39%  |
| Malfunc  | 329       | 518    | 13.2%   |
| Detected | 78        | 149    | 3.13%   |
| Failed   | 7         | 9      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1945      | 61.28%  |
| AMD                              | 411       | 12.95%  |
| Samsung Electronics              | 184       | 5.8%    |
| Broadcom / LSI                   | 121       | 3.81%   |
| SanDisk                          | 93        | 2.93%   |
| Phison Electronics               | 51        | 1.61%   |
| ASMedia Technology               | 50        | 1.58%   |
| Marvell Technology Group         | 33        | 1.04%   |
| Silicon Motion                   | 31        | 0.98%   |
| SK hynix                         | 29        | 0.91%   |
| Kingston Technology Company      | 22        | 0.69%   |
| Chelsio Communications           | 21        | 0.66%   |
| Micron/Crucial Technology        | 20        | 0.63%   |
| Hewlett-Packard                  | 19        | 0.6%    |
| Nvidia                           | 14        | 0.44%   |
| Micron Technology                | 13        | 0.41%   |
| JMicron Technology               | 13        | 0.41%   |
| Toshiba                          | 11        | 0.35%   |
| MAXIO Technology (Hangzhou)      | 11        | 0.35%   |
| KIOXIA                           | 11        | 0.35%   |
| Adaptec                          | 9         | 0.28%   |
| ADATA Technology                 | 8         | 0.25%   |
| Silicon Image                    | 6         | 0.19%   |
| Seagate Technology               | 6         | 0.19%   |
| Realtek Semiconductor            | 6         | 0.19%   |
| Transcend                        | 5         | 0.16%   |
| Shenzhen Longsys Electronics     | 4         | 0.13%   |
| VIA Technologies                 | 3         | 0.09%   |
| Solid State Storage Technology   | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Netac Technology                 | 2         | 0.06%   |
| Lite-On Technology               | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| HighPoint Technologies           | 2         | 0.06%   |
| Broadcom                         | 2         | 0.06%   |
| Biwin Storage Technology         | 2         | 0.06%   |
| Union Memory (Shenzhen)          | 1         | 0.03%   |
| Innodisk                         | 1         | 0.03%   |
| HGST                             | 1         | 0.03%   |
| Dell                             | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 285       | 7.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 213       | 5.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 148       | 4.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 127       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 107       | 2.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 106       | 2.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 97        | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 92        | 2.53%   |
| Intel SATA Controller [RAID mode]                                                | 70        | 1.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 67        | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 64        | 1.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 57        | 1.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 54        | 1.49%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 51        | 1.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 47        | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 45        | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 45        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 45        | 1.24%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 44        | 1.21%   |
| AMD 400 Series Chipset SATA Controller                                           | 44        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 40        | 1.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 39        | 1.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 39        | 1.07%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                     | 37        | 1.02%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 35        | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 34        | 0.94%   |
| AMD FCH IDE Controller                                                           | 34        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 33        | 0.91%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 32        | 0.88%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 32        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 31        | 0.85%   |
| Phison E12 NVMe Controller                                                       | 30        | 0.83%   |
| AMD 500 Series Chipset SATA Controller                                           | 30        | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 29        | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 29        | 0.8%    |
| Samsung NVMe SSD Controller 980                                                  | 28        | 0.77%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 28        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 27        | 0.74%   |
| Unknown                                                                          | 27        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 25        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2073      | 64.7%   |
| NVMe | 511       | 15.95%  |
| IDE  | 308       | 9.61%   |
| RAID | 200       | 6.24%   |
| SAS  | 72        | 2.25%   |
| SCSI | 40        | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2056      | 81.23%  |
| AMD      | 446       | 17.62%  |
| ARM      | 19        | 0.75%   |
| Unknown  | 5         | 0.2%    |
| IBM      | 2         | 0.08%   |
| NXP      | 1         | 0.04%   |
| Motorola | 1         | 0.04%   |
| i        | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Celeron CPU J3160 @ 1.60GHz        | 72        | 2.81%   |
| Intel Celeron J4125 CPU @ 2.00GHz        | 68        | 2.65%   |
| Intel Celeron N5105 @ 2.00GHz            | 48        | 1.87%   |
| Intel Celeron CPU J1900 @ 1.99GHz        | 38        | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 31        | 1.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 31        | 1.21%   |
| AMD GX-412TC SOC                         | 30        | 1.17%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 26        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 25        | 0.97%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 25        | 0.97%   |
| AMD RX-427BB with AMD Radeon R7 Graphics | 25        | 0.97%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 24        | 0.94%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 24        | 0.94%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 22        | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 21        | 0.82%   |
| Intel Celeron CPU J3455 @ 1.50GHz        | 20        | 0.78%   |
| Intel Atom CPU D525 @ 1.80GHz            | 18        | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz        | 17        | 0.66%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz        | 16        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 16        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 16        | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 15        | 0.58%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 15        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 14        | 0.55%   |
| Intel Core 2 Duo                         | 14        | 0.55%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 14        | 0.55%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 13        | 0.51%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 13        | 0.51%   |
| Intel Xeon CPU E3-1270 v3 @ 3.50GHz      | 12        | 0.47%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz      | 12        | 0.47%   |
| Intel Xeon CPU D-1518 @ 2.20GHz          | 12        | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz         | 12        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 12        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 12        | 0.47%   |
| Intel Core i3-4160 CPU @ 3.60GHz         | 12        | 0.47%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz | 11        | 0.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz         | 11        | 0.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 11        | 0.43%   |
| AMD Ryzen 7 2700 Eight-Core Processor    | 11        | 0.43%   |
| AMD EPYC 3201 8-Core Processor           | 11        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 502       | 19.69%  |
| Intel Celeron           | 378       | 14.82%  |
| Intel Xeon              | 354       | 13.88%  |
| Intel Core i7           | 298       | 11.69%  |
| Intel Core i3           | 162       | 6.35%   |
| Intel Atom              | 127       | 4.98%   |
| Other                   | 98        | 3.84%   |
| AMD Ryzen 7             | 75        | 2.94%   |
| AMD GX                  | 66        | 2.59%   |
| Intel Pentium           | 56        | 2.2%    |
| AMD Ryzen 5             | 56        | 2.2%    |
| Intel Core 2 Duo        | 49        | 1.92%   |
| AMD Ryzen 9             | 24        | 0.94%   |
| Intel Pentium Silver    | 22        | 0.86%   |
| AMD FX                  | 21        | 0.82%   |
| AMD EPYC                | 21        | 0.82%   |
| AMD Ryzen 3             | 20        | 0.78%   |
| ARM Cortex              | 18        | 0.71%   |
| AMD A10                 | 17        | 0.67%   |
| Intel Core i9           | 12        | 0.47%   |
| AMD Ryzen 5 PRO         | 10        | 0.39%   |
| AMD Phenom II X4        | 10        | 0.39%   |
| AMD G                   | 10        | 0.39%   |
| AMD Athlon              | 10        | 0.39%   |
| Intel Core 2 Quad       | 9         | 0.35%   |
| Intel Core 2            | 9         | 0.35%   |
| AMD Ryzen Embedded      | 8         | 0.31%   |
| AMD A8                  | 8         | 0.31%   |
| Intel Pentium 4         | 6         | 0.24%   |
| AMD Opteron             | 6         | 0.24%   |
| AMD A6                  | 6         | 0.24%   |
| Intel Pentium Dual-Core | 5         | 0.2%    |
| Intel Genuine           | 5         | 0.2%    |
| AMD Ryzen Threadripper  | 5         | 0.2%    |
| AMD A4                  | 5         | 0.2%    |
| AMD Phenom II X6        | 4         | 0.16%   |
| AMD E2                  | 4         | 0.16%   |
| AMD E                   | 4         | 0.16%   |
| Intel Xeon Gold         | 3         | 0.12%   |
| Intel Pentium M         | 3         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1289      | 50.49%  |
| 2       | 624       | 24.44%  |
| 8       | 171       | 6.7%    |
| 6       | 121       | 4.74%   |
| Unknown | 96        | 3.76%   |
| 16      | 91        | 3.56%   |
| 12      | 81        | 3.17%   |
| 1       | 22        | 0.86%   |
| 24      | 16        | 0.63%   |
| 32      | 11        | 0.43%   |
| 10      | 9         | 0.35%   |
| 20      | 7         | 0.27%   |
| 48      | 3         | 0.12%   |
| 14      | 3         | 0.12%   |
| 64      | 2         | 0.08%   |
| 36      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |
| 3       | 2         | 0.08%   |
| 40      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2384      | 94.15%  |
| 2       | 107       | 4.23%   |
| Unknown | 39        | 1.54%   |
| 8       | 1         | 0.04%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1376      | 54.13%  |
| 2       | 1060      | 41.7%   |
| Unknown | 105       | 4.13%   |
| 4       | 1         | 0.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 332       | 13.02%  |
| Haswell         | 292       | 11.45%  |
| Silvermont      | 230       | 9.02%   |
| IvyBridge       | 186       | 7.29%   |
| SandyBridge     | 164       | 6.43%   |
| Skylake         | 159       | 6.24%   |
| Unknown         | 132       | 5.18%   |
| Goldmont plus   | 111       | 4.35%   |
| Broadwell       | 103       | 4.04%   |
| Goldmont        | 67        | 2.63%   |
| Westmere        | 66        | 2.59%   |
| Zen 2           | 61        | 2.39%   |
| Zen+            | 60        | 2.35%   |
| Penryn          | 55        | 2.16%   |
| Zen             | 53        | 2.08%   |
| Zen 3           | 46        | 1.8%    |
| Bonnell         | 46        | 1.8%    |
| Nehalem         | 44        | 1.73%   |
| Jaguar          | 42        | 1.65%   |
| Core            | 41        | 1.61%   |
| Puma            | 38        | 1.49%   |
| CometLake       | 38        | 1.49%   |
| Piledriver      | 34        | 1.33%   |
| Steamroller     | 32        | 1.25%   |
| K10             | 24        | 0.94%   |
| Bobcat          | 22        | 0.86%   |
| TigerLake       | 20        | 0.78%   |
| NetBurst        | 14        | 0.55%   |
| Excavator       | 12        | 0.47%   |
| K8 Hammer       | 10        | 0.39%   |
| P6              | 5         | 0.2%    |
| K10 Llano       | 4         | 0.16%   |
| IceLake         | 3         | 0.12%   |
| Bulldozer       | 2         | 0.08%   |
| K8 & K10 hybrid | 1         | 0.04%   |
| Geode           | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1500      | 59.1%   |
| AMD                                          | 412       | 16.23%  |
| Nvidia                                       | 267       | 10.52%  |
| ASPEED Technology                            | 182       | 7.17%   |
| Matrox Electronics Systems                   | 171       | 6.74%   |
| XGI Technology (eXtreme Graphics Innovation) | 4         | 0.16%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 182       | 7.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 128       | 4.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 115       | 4.45%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 106       | 4.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 103       | 3.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 98        | 3.79%   |
| Intel HD Graphics 530                                                                    | 83        | 3.21%   |
| Intel HD Graphics 620                                                                    | 74        | 2.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 2.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 62        | 2.4%    |
| Intel JasperLake [UHD Graphics]                                                          | 59        | 2.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 1.93%   |
| Intel UHD Graphics 620                                                                   | 49        | 1.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 1.74%   |
| Matrox Electronics Systems G200eR2                                                       | 41        | 1.59%   |
| Intel HD Graphics 500                                                                    | 40        | 1.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 1.55%   |
| Intel HD Graphics 630                                                                    | 36        | 1.39%   |
| Intel HD Graphics 5500                                                                   | 33        | 1.28%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 32        | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 1.2%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 26        | 1.01%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 25        | 0.97%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 24        | 0.93%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 24        | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 23        | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 0.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 20        | 0.77%   |
| AMD Renoir                                                                               | 20        | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 0.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 0.7%    |
| AMD ES1000                                                                               | 18        | 0.7%    |
| Intel HD Graphics 610                                                                    | 17        | 0.66%   |
| Intel HD Graphics 6000                                                                   | 14        | 0.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 0.54%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1348      | 52.93%  |
| 1 x AMD         | 368       | 14.45%  |
| 1 x Nvidia      | 191       | 7.5%    |
| 1 x ASPEED      | 171       | 6.71%   |
| 1 x Matrox      | 169       | 6.64%   |
| Other           | 114       | 4.48%   |
| 2 x Intel       | 61        | 2.39%   |
| Intel + Nvidia  | 61        | 2.39%   |
| Intel + AMD     | 22        | 0.86%   |
| AMD + Nvidia    | 11        | 0.43%   |
| 2 x AMD         | 9         | 0.35%   |
| Intel + ASPEED  | 7         | 0.27%   |
| 1 x XGI         | 4         | 0.16%   |
| 2 x Nvidia      | 3         | 0.12%   |
| Nvidia + ASPEED | 3         | 0.12%   |
| 1 x SiS         | 2         | 0.08%   |
| AMD + ASPEED    | 2         | 0.08%   |
| AMD + Matrox    | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2256      | 88.85%  |
| Unknown     | 145       | 5.71%   |
| Proprietary | 138       | 5.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2313      | 90.78%  |
| 1.01-2.0   | 63        | 2.47%   |
| 0.01-0.5   | 49        | 1.92%   |
| 3.01-4.0   | 38        | 1.49%   |
| 0.51-1.0   | 29        | 1.14%   |
| 7.01-8.0   | 27        | 1.06%   |
| 5.01-6.0   | 17        | 0.67%   |
| 8.01-16.0  | 7         | 0.27%   |
| 2.01-3.0   | 4         | 0.16%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 63        | 10.7%   |
| LG Display              | 63        | 10.7%   |
| AU Optronics            | 57        | 9.68%   |
| Dell                    | 54        | 9.17%   |
| BOE                     | 45        | 7.64%   |
| Chimei Innolux          | 33        | 5.6%    |
| Goldstar                | 32        | 5.43%   |
| Acer                    | 31        | 5.26%   |
| Lenovo                  | 28        | 4.75%   |
| Hewlett-Packard         | 23        | 3.9%    |
| Ancor Communications    | 22        | 3.74%   |
| Apple                   | 17        | 2.89%   |
| Vizio                   | 9         | 1.53%   |
| ASUSTek Computer        | 9         | 1.53%   |
| AOC                     | 9         | 1.53%   |
| ViewSonic               | 8         | 1.36%   |
| Sharp                   | 8         | 1.36%   |
| Sceptre Tech            | 8         | 1.36%   |
| LG Electronics          | 7         | 1.19%   |
| Chi Mei Optoelectronics | 7         | 1.19%   |
| BenQ                    | 7         | 1.19%   |
| Sony                    | 3         | 0.51%   |
| Philips                 | 3         | 0.51%   |
| MSI                     | 3         | 0.51%   |
| LGD                     | 3         | 0.51%   |
| InfoVision              | 3         | 0.51%   |
| HannStar                | 3         | 0.51%   |
| Westinghouse            | 2         | 0.34%   |
| NEC Computers           | 2         | 0.34%   |
| Lenovo Group Limited    | 2         | 0.34%   |
| Insignia                | 2         | 0.34%   |
| IBM                     | 2         | 0.34%   |
| Unknown                 | 2         | 0.34%   |
| unknown                 | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| Tech Concepts           | 1         | 0.17%   |
| SHI                     | 1         | 0.17%   |
| SGT                     | 1         | 0.17%   |
| Seiko/Epson             | 1         | 0.17%   |
| Quanta Display          | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 280x190mm 13.3-inch                | 7         | 1.15%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 6         | 0.99%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch          | 5         | 0.82%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch       | 4         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch | 4         | 0.66%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 4         | 0.66%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch              | 4         | 0.66%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                      | 3         | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch          | 3         | 0.49%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                | 3         | 0.49%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch             | 3         | 0.49%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch              | 3         | 0.49%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch              | 3         | 0.49%   |
| Dell U2518D DEL413C 2560x1440 550x310mm 24.9-inch                    | 3         | 0.49%   |
| Dell U2412M DELA07B 1920x1200 520x320mm 24.0-inch                    | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch     | 3         | 0.49%   |
| BOE LCD Monitor BOE05DA 1366x768 280x160mm 12.7-inch                 | 3         | 0.49%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch         | 3         | 0.49%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch     | 3         | 0.49%   |
| Acer V246HL ACR032E 1920x1080 530x300mm 24.0-inch                    | 3         | 0.49%   |
| Sony TV SNY9C01 1360x768                                             | 2         | 0.33%   |
| Sceptre Tech Sceptre C35 SPT0DB7 3440x1440 820x350mm 35.1-inch       | 2         | 0.33%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch    | 2         | 0.33%   |
| Samsung Electronics SyncMaster SAM00A4 1024x768 300x230mm 14.9-inch  | 2         | 0.33%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 600x340mm 27.2-inch    | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch | 2         | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch         | 2         | 0.33%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch         | 2         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch         | 2         | 0.33%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch         | 2         | 0.33%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x170mm 13.9-inch         | 2         | 0.33%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD02EB 1366x768 310x170mm 13.9-inch          | 2         | 0.33%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch          | 2         | 0.33%   |
| IBM LCD Monitor IBM2887 1680x1050 330x210mm 15.4-inch                | 2         | 0.33%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch     | 2         | 0.33%   |
| Goldstar W2246 GSM5784 1920x1080 480x270mm 21.7-inch                 | 2         | 0.33%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch           | 2         | 0.33%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 191       | 32.99%  |
| 1366x768 (WXGA)    | 112       | 19.34%  |
| 2560x1440 (QHD)    | 40        | 6.91%   |
| 3840x2160 (4K)     | 38        | 6.56%   |
| 1600x900 (HD+)     | 32        | 5.53%   |
| 1280x800 (WXGA)    | 23        | 3.97%   |
| 1920x1200 (WUXGA)  | 18        | 3.11%   |
| 1280x1024 (SXGA)   | 18        | 3.11%   |
| 1680x1050 (WSXGA+) | 16        | 2.76%   |
| 2560x1080          | 13        | 2.25%   |
| 1440x900 (WXGA+)   | 12        | 2.07%   |
| 3440x1440          | 10        | 1.73%   |
| 2256x1504          | 7         | 1.21%   |
| 1360x768           | 7         | 1.21%   |
| Unknown            | 7         | 1.21%   |
| 2560x1600          | 5         | 0.86%   |
| 1024x768 (XGA)     | 5         | 0.86%   |
| 1024x600           | 5         | 0.86%   |
| 3840x1600          | 2         | 0.35%   |
| 3840x1080          | 2         | 0.35%   |
| 3200x1800 (QHD+)   | 2         | 0.35%   |
| 1600x1200          | 2         | 0.35%   |
| 7040x1440          | 1         | 0.17%   |
| 5760x2160          | 1         | 0.17%   |
| 5760x1080          | 1         | 0.17%   |
| 4640x1080          | 1         | 0.17%   |
| 4480x1080          | 1         | 0.17%   |
| 3520x1080          | 1         | 0.17%   |
| 2880x1620          | 1         | 0.17%   |
| 2806x900           | 1         | 0.17%   |
| 1920x540           | 1         | 0.17%   |
| 1920x1920          | 1         | 0.17%   |
| 1400x1050          | 1         | 0.17%   |
| 1280x768           | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 19.28%  |
| 13      | 95        | 16.21%  |
| 24      | 50        | 8.53%   |
| 27      | 45        | 7.68%   |
| Unknown | 40        | 6.83%   |
| 31      | 27        | 4.61%   |
| 12      | 26        | 4.44%   |
| 19      | 24        | 4.1%    |
| 17      | 24        | 4.1%    |
| 23      | 21        | 3.58%   |
| 21      | 19        | 3.24%   |
| 14      | 19        | 3.24%   |
| 11      | 17        | 2.9%    |
| 34      | 14        | 2.39%   |
| 22      | 8         | 1.37%   |
| 29      | 7         | 1.19%   |
| 20      | 5         | 0.85%   |
| 64      | 4         | 0.68%   |
| 26      | 4         | 0.68%   |
| 18      | 4         | 0.68%   |
| 37      | 2         | 0.34%   |
| 35      | 2         | 0.34%   |
| 16      | 2         | 0.34%   |
| 10      | 2         | 0.34%   |
| 9       | 2         | 0.34%   |
| 54      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 49      | 1         | 0.17%   |
| 42      | 1         | 0.17%   |
| 41      | 1         | 0.17%   |
| 39      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 28      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |
| 8       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 186       | 32.4%   |
| 501-600     | 107       | 18.64%  |
| 201-300     | 96        | 16.72%  |
| 401-500     | 52        | 9.06%   |
| 601-700     | 40        | 6.97%   |
| Unknown     | 40        | 6.97%   |
| 351-400     | 21        | 3.66%   |
| 701-800     | 15        | 2.61%   |
| 1001-1500   | 7         | 1.22%   |
| 801-900     | 5         | 0.87%   |
| 101-200     | 3         | 0.52%   |
| 901-1000    | 2         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 382       | 69.84%  |
| 16/10   | 65        | 11.88%  |
| Unknown | 36        | 6.58%   |
| 21/9    | 23        | 4.2%    |
| 5/4     | 15        | 2.74%   |
| 3/2     | 12        | 2.19%   |
| 4/3     | 9         | 1.65%   |
| 6/5     | 3         | 0.55%   |
| 32/9    | 1         | 0.18%   |
| 1.00    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 97        | 16.61%  |
| 91-100         | 88        | 15.07%  |
| 201-250        | 80        | 13.7%   |
| 301-350        | 51        | 8.73%   |
| 351-500        | 47        | 8.05%   |
| Unknown        | 40        | 6.85%   |
| 151-200        | 29        | 4.97%   |
| 61-70          | 27        | 4.62%   |
| 101-110        | 27        | 4.62%   |
| 251-300        | 19        | 3.25%   |
| 51-60          | 16        | 2.74%   |
| 121-130        | 15        | 2.57%   |
| 141-150        | 14        | 2.4%    |
| 71-80          | 12        | 2.05%   |
| More than 1000 | 6         | 1.03%   |
| 501-1000       | 6         | 1.03%   |
| 1-40           | 3         | 0.51%   |
| 111-120        | 3         | 0.51%   |
| 41-50          | 2         | 0.34%   |
| 131-140        | 2         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 179       | 31.57%  |
| 121-160       | 153       | 26.98%  |
| 101-120       | 141       | 24.87%  |
| 161-240       | 41        | 7.23%   |
| Unknown       | 40        | 7.05%   |
| More than 240 | 10        | 1.76%   |
| 1-50          | 3         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1924      | 75.57%  |
| 1     | 552       | 21.68%  |
| 2     | 62        | 2.44%   |
| 3     | 7         | 0.27%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2025      | 57.27%  |
| Realtek Semiconductor           | 760       | 21.49%  |
| Broadcom                        | 264       | 7.47%   |
| Qualcomm Atheros                | 161       | 4.55%   |
| Mellanox Technologies           | 43        | 1.22%   |
| Ralink Technology               | 28        | 0.79%   |
| Chelsio Communications          | 24        | 0.68%   |
| IMC Networks                    | 18        | 0.51%   |
| AMD                             | 18        | 0.51%   |
| Ralink                          | 15        | 0.42%   |
| TP-Link                         | 14        | 0.4%    |
| Marvell Technology Group        | 14        | 0.4%    |
| Edimax Technology               | 13        | 0.37%   |
| Solarflare Communications       | 11        | 0.31%   |
| U-Blox                          | 9         | 0.25%   |
| Aquantia                        | 8         | 0.23%   |
| Novatel Wireless                | 7         | 0.2%    |
| NetGear                         | 7         | 0.2%    |
| Nvidia                          | 6         | 0.17%   |
| Google                          | 6         | 0.17%   |
| Seeed Technology                | 5         | 0.14%   |
| QLogic                          | 5         | 0.14%   |
| MediaTek                        | 5         | 0.14%   |
| Emulex                          | 5         | 0.14%   |
| Apple                           | 5         | 0.14%   |
| Dell                            | 4         | 0.11%   |
| D-Link System                   | 4         | 0.11%   |
| Cisco Systems                   | 3         | 0.08%   |
| ASUSTek Computer                | 3         | 0.08%   |
| VIA Technologies                | 2         | 0.06%   |
| Sierra Wireless                 | 2         | 0.06%   |
| Sequans Communications          | 2         | 0.06%   |
| Qualcomm Atheros Communications | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)   | 2         | 0.06%   |
| Linksys                         | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| American Megatrends             | 2         | 0.06%   |
| Accton Technology               | 2         | 0.06%   |
| 3Com                            | 2         | 0.06%   |
| ZyXEL Communications            | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 598       | 13.17%  |
| Intel I211 Gigabit Network Connection                                         | 287       | 6.32%   |
| Intel I210 Gigabit Network Connection                                         | 215       | 4.74%   |
| Intel I350 Gigabit Network Connection                                         | 191       | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 166       | 3.66%   |
| Intel 82574L Gigabit Network Connection                                       | 134       | 2.95%   |
| Intel Ethernet Controller I225-V                                              | 111       | 2.45%   |
| Intel Ethernet Connection I217-LM                                             | 106       | 2.34%   |
| Intel 82580 Gigabit Network Connection                                        | 82        | 1.81%   |
| Intel 82583V Gigabit Network Connection                                       | 75        | 1.65%   |
| Intel Wi-Fi 6 AX200                                                           | 70        | 1.54%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 69        | 1.52%   |
| Intel 82576 Gigabit Network Connection                                        | 67        | 1.48%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 67        | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 65        | 1.43%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 58        | 1.28%   |
| Intel Ethernet Connection (2) I219-LM                                         | 53        | 1.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 49        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 47        | 1.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 46        | 1.01%   |
| Intel Ethernet Controller I226-V                                              | 44        | 0.97%   |
| Intel Wireless 8265 / 8275                                                    | 41        | 0.9%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 41        | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 40        | 0.88%   |
| Intel Wireless 8260                                                           | 36        | 0.79%   |
| Intel Wireless 7260                                                           | 36        | 0.79%   |
| Intel Wireless 7265                                                           | 35        | 0.77%   |
| Intel Wireless 3165                                                           | 31        | 0.68%   |
| Intel Ethernet Connection I354                                                | 31        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                                         | 29        | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                          | 29        | 0.64%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 29        | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 25        | 0.55%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 24        | 0.53%   |
| Intel Wireless-AC 9260                                                        | 23        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 22        | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 22        | 0.48%   |
| Intel Ethernet Controller X550                                                | 22        | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 22        | 0.48%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 21        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 514       | 54.33%  |
| Qualcomm Atheros                | 138       | 14.59%  |
| Realtek Semiconductor           | 107       | 11.31%  |
| Broadcom                        | 72        | 7.61%   |
| Ralink Technology               | 28        | 2.96%   |
| IMC Networks                    | 18        | 1.9%    |
| Ralink                          | 15        | 1.59%   |
| TP-Link                         | 14        | 1.48%   |
| Edimax Technology               | 13        | 1.37%   |
| NetGear                         | 7         | 0.74%   |
| MediaTek                        | 5         | 0.53%   |
| ASUSTek Computer                | 3         | 0.32%   |
| Sierra Wireless                 | 2         | 0.21%   |
| Qualcomm Atheros Communications | 2         | 0.21%   |
| Belkin Components               | 2         | 0.21%   |
| ZyXEL Communications            | 1         | 0.11%   |
| Marvell Technology Group        | 1         | 0.11%   |
| Linksys                         | 1         | 0.11%   |
| D-Link System                   | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |
| AboCom Systems                  | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 70        | 7.33%   |
| Intel Wireless 8265 / 8275                                     | 41        | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 40        | 4.19%   |
| Intel Wireless 8260                                            | 36        | 3.77%   |
| Intel Wireless 7260                                            | 36        | 3.77%   |
| Intel Wireless 7265                                            | 35        | 3.66%   |
| Intel Wireless 3165                                            | 31        | 3.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 2.62%   |
| Intel Wireless-AC 9260                                         | 23        | 2.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 22        | 2.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22        | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 2.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 18        | 1.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 1.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 18        | 1.88%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card           | 18        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 1.78%   |
| Ralink RT5370 Wireless Adapter                                 | 15        | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 13        | 1.36%   |
| Intel Wireless 3160                                            | 13        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.36%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 13        | 1.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 13        | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 1.26%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 12        | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 10        | 1.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 10        | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 0.94%   |
| Intel Centrino Wireless-N 2230                                 | 9         | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 9         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 8         | 0.84%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 7         | 0.73%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 7         | 0.73%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 7         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1805      | 62.28%  |
| Realtek Semiconductor            | 711       | 24.53%  |
| Broadcom                         | 221       | 7.63%   |
| Qualcomm Atheros                 | 31        | 1.07%   |
| Chelsio Communications           | 21        | 0.72%   |
| AMD                              | 17        | 0.59%   |
| Marvell Technology Group         | 13        | 0.45%   |
| Solarflare Communications        | 11        | 0.38%   |
| Aquantia                         | 8         | 0.28%   |
| Novatel Wireless                 | 7         | 0.24%   |
| Nvidia                           | 6         | 0.21%   |
| QLogic                           | 5         | 0.17%   |
| Emulex                           | 5         | 0.17%   |
| Apple                            | 4         | 0.14%   |
| Google                           | 3         | 0.1%    |
| D-Link System                    | 3         | 0.1%    |
| Cisco Systems                    | 3         | 0.1%    |
| VIA Technologies                 | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.07%   |
| American Megatrends              | 2         | 0.07%   |
| 3Com                             | 2         | 0.07%   |
| Xiaomi                           | 1         | 0.03%   |
| Tehuti Networks                  | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Silicom                          | 1         | 0.03%   |
| Samsung Electronics              | 1         | 0.03%   |
| Qualcomm                         | 1         | 0.03%   |
| Oracle/SUN                       | 1         | 0.03%   |
| National Semiconductor           | 1         | 0.03%   |
| MYRICOM                          | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Lenovo                           | 1         | 0.03%   |
| Insyde Software                  | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| Amazon.com                       | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 598       | 17.17%  |
| Intel I211 Gigabit Network Connection                                         | 287       | 8.24%   |
| Intel I210 Gigabit Network Connection                                         | 215       | 6.17%   |
| Intel I350 Gigabit Network Connection                                         | 191       | 5.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 166       | 4.77%   |
| Intel 82574L Gigabit Network Connection                                       | 134       | 3.85%   |
| Intel Ethernet Controller I225-V                                              | 111       | 3.19%   |
| Intel Ethernet Connection I217-LM                                             | 106       | 3.04%   |
| Intel 82580 Gigabit Network Connection                                        | 82        | 2.35%   |
| Intel 82583V Gigabit Network Connection                                       | 75        | 2.15%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 69        | 1.98%   |
| Intel 82576 Gigabit Network Connection                                        | 67        | 1.92%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 67        | 1.92%   |
| Realtek RTL8125 2.5GbE Controller                                             | 63        | 1.81%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 58        | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                         | 53        | 1.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 49        | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 47        | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 46        | 1.32%   |
| Intel Ethernet Controller I226-V                                              | 44        | 1.26%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 41        | 1.18%   |
| Intel Ethernet Connection I354                                                | 31        | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                                         | 29        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                                          | 29        | 0.83%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                                | 29        | 0.83%   |
| Intel Ethernet Controller X550                                                | 22        | 0.63%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 21        | 0.6%    |
| Intel 82579V Gigabit Network Connection                                       | 20        | 0.57%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 19        | 0.55%   |
| Intel Ethernet Connection X553 1GbE                                           | 18        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                          | 17        | 0.49%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                     | 17        | 0.49%   |
| Intel 82575EB Gigabit Network Connection                                      | 16        | 0.46%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                              | 15        | 0.43%   |
| Intel Ethernet Connection X552 10 GbE SFP+                                    | 15        | 0.43%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 15        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 14        | 0.4%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                            | 14        | 0.4%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                                 | 13        | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                          | 13        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2424      | 71.29%  |
| WiFi     | 877       | 25.79%  |
| Unknown  | 72        | 2.12%   |
| Modem    | 27        | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2267      | 85.07%  |
| WiFi     | 389       | 14.6%   |
| Unknown  | 9         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 764       | 29.6%   |
| 4     | 481       | 18.64%  |
| 3     | 347       | 13.44%  |
| 1     | 331       | 12.82%  |
| 6     | 268       | 10.38%  |
| 5     | 193       | 7.48%   |
| 8     | 63        | 2.44%   |
| 7     | 49        | 1.9%    |
| 0     | 24        | 0.93%   |
| 10    | 21        | 0.81%   |
| 9     | 21        | 0.81%   |
| 11    | 5         | 0.19%   |
| 16    | 3         | 0.12%   |
| 14    | 3         | 0.12%   |
| 13    | 3         | 0.12%   |
| 12    | 3         | 0.12%   |
| 20    | 1         | 0.04%   |
| 15    | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2115      | 80.6%   |
| Yes  | 509       | 19.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 378       | 61.46%  |
| Broadcom                        | 48        | 7.8%    |
| Apple                           | 42        | 6.83%   |
| Realtek Semiconductor           | 36        | 5.85%   |
| Qualcomm Atheros Communications | 28        | 4.55%   |
| IMC Networks                    | 23        | 3.74%   |
| Cambridge Silicon Radio         | 14        | 2.28%   |
| ASUSTek Computer                | 10        | 1.63%   |
| Dell                            | 8         | 1.3%    |
| Lite-On Technology              | 7         | 1.14%   |
| Foxconn / Hon Hai               | 6         | 0.98%   |
| Alps Electric                   | 4         | 0.65%   |
| MediaTek                        | 3         | 0.49%   |
| Ralink                          | 2         | 0.33%   |
| TP-Link                         | 1         | 0.16%   |
| Taiyo Yuden                     | 1         | 0.16%   |
| Primax Electronics              | 1         | 0.16%   |
| Hewlett-Packard                 | 1         | 0.16%   |
| Esel International              | 1         | 0.16%   |
| Dynex                           | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 155       | 25.08%  |
| Intel AX200 Bluetooth                                       | 62        | 10.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 50        | 8.09%   |
| Intel AX201 Bluetooth                                       | 33        | 5.34%   |
| Intel Wireless-AC 3168 Bluetooth                            | 22        | 3.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 21        | 3.4%    |
| Intel AX210 Bluetooth                                       | 20        | 3.24%   |
| Apple Bluetooth Host Controller                             | 19        | 3.07%   |
| Realtek  Bluetooth 4.2 Adapter                              | 17        | 2.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 15        | 2.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 14        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 13        | 2.1%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 11        | 1.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 10        | 1.62%   |
| Apple Broadcom Built-in Bluetooth                           | 9         | 1.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 8         | 1.29%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 7         | 1.13%   |
| Realtek Bluetooth Adapter                                   | 6         | 0.97%   |
| IMC Networks Realtek Bluetooth Adapter                      | 6         | 0.97%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 6         | 0.97%   |
| Realtek Bluetooth 4.2 Adapter                               | 5         | 0.81%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 0.81%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 5         | 0.81%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 5         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 4         | 0.65%   |
| Lite-On Bluetooth USB Module                                | 4         | 0.65%   |
| Dell DW375 Bluetooth Module                                 | 4         | 0.65%   |
| Apple Built-in iSight (no firmware loaded)                  | 4         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 3         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 2         | 0.32%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 0.32%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 0.32%   |
| Ralink RT3290 Bluetooth                                     | 2         | 0.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.1                      | 2         | 0.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 0.32%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 2         | 0.32%   |
| MediaTek RZ608 Bluetooth Adapter                            | 2         | 0.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 2         | 0.32%   |
| Intel Wireless Bluetooth                                    | 2         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1447      | 65.42%  |
| AMD                                  | 446       | 20.16%  |
| Nvidia                               | 208       | 9.4%    |
| C-Media Electronics                  | 32        | 1.45%   |
| Creative Labs                        | 13        | 0.59%   |
| SteelSeries ApS                      | 6         | 0.27%   |
| Texas Instruments                    | 5         | 0.23%   |
| Logitech                             | 5         | 0.23%   |
| Blue Microphones                     | 5         | 0.23%   |
| Realtek Semiconductor                | 4         | 0.18%   |
| Corsair                              | 3         | 0.14%   |
| Yamaha                               | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.09%   |
| Razer USA                            | 2         | 0.09%   |
| MosArt Semiconductor                 | 2         | 0.09%   |
| Lenovo                               | 2         | 0.09%   |
| Google                               | 2         | 0.09%   |
| Creative Technology                  | 2         | 0.09%   |
| Cambridge Silicon Radio              | 2         | 0.09%   |
| ASUSTek Computer                     | 2         | 0.09%   |
| Apple                                | 2         | 0.09%   |
| XMOS                                 | 1         | 0.05%   |
| VIA Technologies                     | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Tenx Technology                      | 1         | 0.05%   |
| Quanta                               | 1         | 0.05%   |
| Nektar                               | 1         | 0.05%   |
| LG Electronics                       | 1         | 0.05%   |
| KORG                                 | 1         | 0.05%   |
| Kingston Technology                  | 1         | 0.05%   |
| JMTek                                | 1         | 0.05%   |
| Genesys Logic                        | 1         | 0.05%   |
| Focusrite-Novation                   | 1         | 0.05%   |
| ESS Technology                       | 1         | 0.05%   |
| Dell                                 | 1         | 0.05%   |
| CMX Systems                          | 1         | 0.05%   |
| Cirrus Logic                         | 1         | 0.05%   |
| Astro Gaming                         | 1         | 0.05%   |
| AKAI  Professional M.I.              | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 155       | 5.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 139       | 5.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 121       | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 117       | 4.34%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 114       | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 114       | 4.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 97        | 3.6%    |
| AMD FCH Azalia Controller                                                                         | 89        | 3.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 88        | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 81        | 3%      |
| Intel Cannon Lake PCH cAVS                                                                        | 77        | 2.85%   |
| Intel Jasper Lake HD Audio                                                                        | 59        | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 58        | 2.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 54        | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 52        | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 50        | 1.85%   |
| Intel Broadwell-U Audio Controller                                                                | 49        | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 48        | 1.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 47        | 1.74%   |
| Intel 200 Series PCH HD Audio                                                                     | 45        | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 43        | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 41        | 1.52%   |
| Intel 8 Series HD Audio Controller                                                                | 41        | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 36        | 1.33%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 31        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 29        | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 29        | 1.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 29        | 1.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 25        | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 19        | 0.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 17        | 0.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 0.59%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 16        | 0.59%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 0.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 0.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 498       | 18.36%  |
| SK hynix                                | 435       | 16.04%  |
| Micron Technology                       | 292       | 10.77%  |
| Crucial                                 | 270       | 9.96%   |
| Kingston                                | 246       | 9.07%   |
| Unknown                                 | 234       | 8.63%   |
| G.Skill                                 | 125       | 4.61%   |
| Corsair                                 | 107       | 3.95%   |
| Unknown                                 | 68        | 2.51%   |
| Team                                    | 40        | 1.47%   |
| Unknown (ABCD)                          | 39        | 1.44%   |
| Transcend                               | 37        | 1.36%   |
| Ramaxel Technology                      | 35        | 1.29%   |
| A-DATA Technology                       | 30        | 1.11%   |
| Nanya Technology                        | 29        | 1.07%   |
| Patriot                                 | 28        | 1.03%   |
| PNY                                     | 24        | 0.88%   |
| Elpida                                  | 20        | 0.74%   |
| Kimtigo                                 | 13        | 0.48%   |
| Toshiba                                 | 12        | 0.44%   |
| Timetec                                 | 11        | 0.41%   |
| Super Talent                            | 11        | 0.41%   |
| Silicon Power                           | 9         | 0.33%   |
| Avant                                   | 9         | 0.33%   |
| Sesame                                  | 6         | 0.22%   |
| Silicon Power Computer & Communications | 5         | 0.18%   |
| Innodisk                                | 5         | 0.18%   |
| SK_Hynix                                | 3         | 0.11%   |
| Patriot Memory (PDP Systems)            | 3         | 0.11%   |
| Neo Forza                               | 3         | 0.11%   |
| Hewlett-Packard                         | 3         | 0.11%   |
| Goldkey                                 | 3         | 0.11%   |
| GeIL                                    | 3         | 0.11%   |
| Apacer                                  | 3         | 0.11%   |
| Tigo                                    | 2         | 0.07%   |
| Ramsta                                  | 2         | 0.07%   |
| Qimonda                                 | 2         | 0.07%   |
| Mushkin                                 | 2         | 0.07%   |
| J&A Information                         | 2         | 0.07%   |
| HPE                                     | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 68        | 2.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 36        | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 24        | 0.83%   |
| Unknown RAM Module 8GB 1600MT/s                                | 18        | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 18        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 16        | 0.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 15        | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 14        | 0.48%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 14        | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 14        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 14        | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 13        | 0.45%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s           | 13        | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 12        | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 12        | 0.41%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 12        | 0.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 12        | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 12        | 0.41%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 12        | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s            | 11        | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 10        | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 10        | 0.34%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s           | 10        | 0.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s          | 10        | 0.34%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 10        | 0.34%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s          | 10        | 0.34%   |
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s          | 9         | 0.31%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 9         | 0.31%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 9         | 0.31%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 9         | 0.31%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 8         | 0.28%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 8         | 0.28%   |
| Samsung RAM M471B5273DH0-CK0 8GB SODIMM DDR3 1600MT/s          | 8         | 0.28%   |
| Samsung RAM M471B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s            | 8         | 0.28%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 8         | 0.28%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 8         | 0.28%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s           | 8         | 0.28%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 8         | 0.28%   |
| Crucial RAM CT102464BF160B.C16 8GB DIMM DDR3 1600MT/s          | 8         | 0.28%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s          | 8         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1150      | 48.52%  |
| DDR4         | 957       | 40.38%  |
| DDR2         | 94        | 3.97%   |
| Unknown      | 54        | 2.28%   |
| LPDDR4       | 52        | 2.19%   |
| SDRAM        | 21        | 0.89%   |
| DDR          | 15        | 0.63%   |
| LPDDR3       | 14        | 0.59%   |
| DDR5         | 6         | 0.25%   |
| LPDDR5       | 3         | 0.13%   |
| DRAM         | 2         | 0.08%   |
| SRAM         | 1         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 1340      | 56.71%  |
| SODIMM       | 930       | 39.36%  |
| Unknown      | 38        | 1.61%   |
| Row Of Chips | 30        | 1.27%   |
| Chip         | 11        | 0.47%   |
| FB-DIMM      | 9         | 0.38%   |
| RIMM         | 5         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1005      | 39.43%  |
| 4096   | 782       | 30.68%  |
| 16384  | 357       | 14.01%  |
| 2048   | 261       | 10.24%  |
| 32768  | 85        | 3.33%   |
| 1024   | 49        | 1.92%   |
| 512    | 6         | 0.24%   |
| 65536  | 2         | 0.08%   |
| 131072 | 1         | 0.04%   |
| 256    | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 780       | 30.81%  |
| 1333    | 319       | 12.6%   |
| 2400    | 318       | 12.56%  |
| 2667    | 230       | 9.08%   |
| 2133    | 216       | 8.53%   |
| 3200    | 210       | 8.29%   |
| 800     | 65        | 2.57%   |
| 667     | 58        | 2.29%   |
| 2666    | 49        | 1.94%   |
| 1334    | 39        | 1.54%   |
| 1867    | 37        | 1.46%   |
| 1066    | 34        | 1.34%   |
| 1067    | 32        | 1.26%   |
| Unknown | 26        | 1.03%   |
| 3000    | 24        | 0.95%   |
| 3600    | 22        | 0.87%   |
| 2933    | 11        | 0.43%   |
| 1866    | 11        | 0.43%   |
| 533     | 11        | 0.43%   |
| 4800    | 6         | 0.24%   |
| 4267    | 5         | 0.2%    |
| 975     | 4         | 0.16%   |
| 6400    | 3         | 0.12%   |
| 400     | 3         | 0.12%   |
| 4000    | 2         | 0.08%   |
| 1400    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 4266    | 1         | 0.04%   |
| 4133    | 1         | 0.04%   |
| 3733    | 1         | 0.04%   |
| 3534    | 1         | 0.04%   |
| 3333    | 1         | 0.04%   |
| 2866    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 2048    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 266     | 1         | 0.04%   |
| 200     | 1         | 0.04%   |
| 166     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


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

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


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

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson WF-2850 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 50%     |
| HP ScanJet 5300c/5370c                                                              | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 90        | 25.28%  |
| Bison Electronics                      | 38        | 10.67%  |
| Microdia                               | 30        | 8.43%   |
| Realtek Semiconductor                  | 27        | 7.58%   |
| IMC Networks                           | 25        | 7.02%   |
| Sunplus Innovation Technology          | 24        | 6.74%   |
| Logitech                               | 23        | 6.46%   |
| Apple                                  | 14        | 3.93%   |
| Quanta                                 | 11        | 3.09%   |
| Suyin                                  | 10        | 2.81%   |
| Lite-On Technology                     | 9         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 2.53%   |
| Luxvisions Innotech Limited            | 7         | 1.97%   |
| Syntek                                 | 6         | 1.69%   |
| Lenovo                                 | 6         | 1.69%   |
| Importek                               | 3         | 0.84%   |
| WCM_USB                                | 2         | 0.56%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.56%   |
| Ricoh                                  | 2         | 0.56%   |
| Primax Electronics                     | 2         | 0.56%   |
| OmniVision Technologies                | 2         | 0.56%   |
| Intel                                  | 2         | 0.56%   |
| Alcor Micro                            | 2         | 0.56%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| Xiongmai                               | 1         | 0.28%   |
| Supreme Electronics                    | 1         | 0.28%   |
| Silicon Motion                         | 1         | 0.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.28%   |
| Goodong Industry                       | 1         | 0.28%   |
| Generalplus Technology                 | 1         | 0.28%   |
| Arkmicro Technologies                  | 1         | 0.28%   |
| ARC International                      | 1         | 0.28%   |
| ALi                                    | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 29        | 8.03%   |
| Bison Integrated Camera                             | 22        | 6.09%   |
| Realtek Integrated_Webcam_HD                        | 10        | 2.77%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 10        | 2.77%   |
| Apple FaceTime HD Camera                            | 9         | 2.49%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 2.22%   |
| Microdia Integrated Webcam                          | 8         | 2.22%   |
| Chicony Integrated Camera (1280x720@30)             | 8         | 2.22%   |
| Logitech HD Pro Webcam C920                         | 7         | 1.94%   |
| IMC Networks Integrated Camera                      | 7         | 1.94%   |
| Chicony Integrated Camera [ThinkPad]                | 7         | 1.94%   |
| Realtek USB 2.0 PC Camera                           | 6         | 1.66%   |
| Logitech Webcam C270                                | 6         | 1.66%   |
| Lite-On Integrated Camera                           | 6         | 1.66%   |
| Microdia Integrated_Webcam_HD                       | 5         | 1.39%   |
| Bison ThinkPad Integrated Camera                    | 5         | 1.39%   |
| Suyin Integrated_Webcam_HD                          | 4         | 1.11%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 1.11%   |
| Microdia Webcam Vitade AF                           | 4         | 1.11%   |
| Microdia Dell Laptop Integrated Webcam HD           | 4         | 1.11%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 1.11%   |
| IMC Networks Realtek PC Camera                      | 4         | 1.11%   |
| Chicony Integrated IR Camera                        | 4         | 1.11%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 1.11%   |
| Syntek EasyCamera                                   | 3         | 0.83%   |
| Sunplus HD WebCam                                   | 3         | 0.83%   |
| Realtek Laptop Camera                               | 3         | 0.83%   |
| Quanta HP Webcam                                    | 3         | 0.83%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.83%   |
| Luxvisions Innotech Limited Integrated Camera       | 3         | 0.83%   |
| Logitech C922 Pro Stream Webcam                     | 3         | 0.83%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.83%   |
| IMC Networks EasyCamera                             | 3         | 0.83%   |
| Chicony HP TrueVision HD Camera                     | 3         | 0.83%   |
| Chicony HD WebCam                                   | 3         | 0.83%   |
| Chicony Chicony USB2.0 Camera                       | 3         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.83%   |
| Bison SunplusIT Integrated Camera                   | 3         | 0.83%   |
| Bison Lenovo Integrated Webcam                      | 3         | 0.83%   |
| Bison Lenovo EasyCamera                             | 3         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 34.09%  |
| Synaptics                  | 17        | 19.32%  |
| Upek                       | 13        | 14.77%  |
| STMicroelectronics         | 11        | 12.5%   |
| Shenzhen Goodix Technology | 6         | 6.82%   |
| AuthenTec                  | 6         | 6.82%   |
| Samsung Electronics        | 1         | 1.14%   |
| LighTuning Technology      | 1         | 1.14%   |
| FocalTech Systems          | 1         | 1.14%   |
| Elan Microelectronics      | 1         | 1.14%   |
| Broadcom                   | 1         | 1.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                 | 15        | 17.05%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 13        | 14.77%  |
| STMicroelectronics Fingerprint Reader                                        | 11        | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                             | 8         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 6         | 6.82%   |
| Shenzhen Goodix Fingerprint Reader                                           | 5         | 5.68%   |
| Validity Sensors Synaptics WBDI                                              | 4         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 3         | 3.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 3.41%   |
| AuthenTec AES2810                                                            | 2         | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 2         | 2.27%   |
| AuthenTec AES1660                                                            | 2         | 2.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 1.14%   |
| Validity Sensors VFS491                                                      | 1         | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 1.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 1.14%   |
| Validity Sensors Fingerprint scanner                                         | 1         | 1.14%   |
| Synaptics WBDI Fingerprint Reader USB 102                                    | 1         | 1.14%   |
| Synaptics WBDI                                                               | 1         | 1.14%   |
| Synaptics UWP WBDI                                                           | 1         | 1.14%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 1.14%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 1.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 1         | 1.14%   |
| FocalTech Systems Fingerprint Reader                                         | 1         | 1.14%   |
| Elan Fingerprint Sensor                                                      | 1         | 1.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.14%   |

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
| 1     | 1010      | 38.76%  |
| 0     | 809       | 31.04%  |
| 2     | 508       | 19.49%  |
| 3     | 203       | 7.79%   |
| 4     | 56        | 2.15%   |
| 5     | 13        | 0.5%    |
| 6     | 5         | 0.19%   |
| 7     | 2         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1494      | 60.61%  |
| Bluetooth                | 262       | 10.63%  |
| Net/wireless             | 233       | 9.45%   |
| Card reader              | 128       | 5.19%   |
| Firewire controller      | 96        | 3.89%   |
| Fingerprint reader       | 74        | 3%      |
| Net/ethernet             | 47        | 1.91%   |
| Sound                    | 43        | 1.74%   |
| Network                  | 34        | 1.38%   |
| Graphics card            | 22        | 0.89%   |
| Storage                  | 11        | 0.45%   |
| Modem                    | 7         | 0.28%   |
| Storage/raid             | 6         | 0.24%   |
| Storage/ata              | 3         | 0.12%   |
| Dvb card                 | 3         | 0.12%   |
| Storage/ide              | 2         | 0.08%   |

