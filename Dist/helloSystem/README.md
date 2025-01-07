helloSystem - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for helloSystem.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem/Desktop/README.md) and [notebooks](/Dist/helloSystem/Notebook/README.md).

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

Total: 2582

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4bd0423b13](https://bsd-hardware.info/?probe=4bd0423b13) | Jan 05, 2025 |
| Dell          | 0MGK50 A02                  | Desktop     | [fe0b9484f5](https://bsd-hardware.info/?probe=fe0b9484f5) | Jan 05, 2025 |
| Dell          | Latitude E5520              | Notebook    | [e8415a5758](https://bsd-hardware.info/?probe=e8415a5758) | Jan 05, 2025 |
| HP            | EliteBook 840 G3            | Notebook    | [5e09879203](https://bsd-hardware.info/?probe=5e09879203) | Jan 03, 2025 |
| ASUSTek       | Q87M-E                      | Desktop     | [845a04a779](https://bsd-hardware.info/?probe=845a04a779) | Jan 03, 2025 |
| HP            | 18E7                        | Desktop     | [fdac2d0362](https://bsd-hardware.info/?probe=fdac2d0362) | Jan 03, 2025 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [20976f758a](https://bsd-hardware.info/?probe=20976f758a) | Jan 02, 2025 |
| Dell          | Latitude E7250              | Notebook    | [dbff7c2ebb](https://bsd-hardware.info/?probe=dbff7c2ebb) | Jan 02, 2025 |
| Dell          | Inspiron 3421               | Notebook    | [0cae3b71cd](https://bsd-hardware.info/?probe=0cae3b71cd) | Dec 31, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [62c66a5499](https://bsd-hardware.info/?probe=62c66a5499) | Dec 29, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [67ea149c61](https://bsd-hardware.info/?probe=67ea149c61) | Dec 29, 2024 |
| Radio Vict... | A24Win8                     | Notebook    | [f85030bb1a](https://bsd-hardware.info/?probe=f85030bb1a) | Dec 27, 2024 |
| Radio Vict... | A24Win8                     | Notebook    | [17813c478e](https://bsd-hardware.info/?probe=17813c478e) | Dec 27, 2024 |
| Dell          | Precision M2800             | Notebook    | [176ae44ed3](https://bsd-hardware.info/?probe=176ae44ed3) | Dec 25, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [c90d1d5857](https://bsd-hardware.info/?probe=c90d1d5857) | Dec 24, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [9fe06419eb](https://bsd-hardware.info/?probe=9fe06419eb) | Dec 21, 2024 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [86efb87e9e](https://bsd-hardware.info/?probe=86efb87e9e) | Dec 21, 2024 |
| Dell          | 0D6H9T A00                  | Desktop     | [53d4b51f32](https://bsd-hardware.info/?probe=53d4b51f32) | Dec 18, 2024 |
| HP            | 2000                        | Notebook    | [0705a401f8](https://bsd-hardware.info/?probe=0705a401f8) | Dec 16, 2024 |
| MSI           | ZH77A-G43                   | Desktop     | [f000f3f0cc](https://bsd-hardware.info/?probe=f000f3f0cc) | Dec 16, 2024 |
| HP            | ProBook 4430s               | Notebook    | [45102636ac](https://bsd-hardware.info/?probe=45102636ac) | Dec 16, 2024 |
| Dell          | 0KYJ8C A00                  | Desktop     | [06b326f6d3](https://bsd-hardware.info/?probe=06b326f6d3) | Dec 15, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [0aea251037](https://bsd-hardware.info/?probe=0aea251037) | Dec 13, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [52f3e1cf1a](https://bsd-hardware.info/?probe=52f3e1cf1a) | Dec 09, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [474ddb6777](https://bsd-hardware.info/?probe=474ddb6777) | Dec 08, 2024 |
| ASUSTek       | N550JV                      | Notebook    | [43db70e6e9](https://bsd-hardware.info/?probe=43db70e6e9) | Dec 07, 2024 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [772e88509f](https://bsd-hardware.info/?probe=772e88509f) | Dec 04, 2024 |
| MSI           | Z97 GAMING 3                | Desktop     | [9cd14a585d](https://bsd-hardware.info/?probe=9cd14a585d) | Dec 04, 2024 |
| HP            | 339A                        | Desktop     | [3c450d9163](https://bsd-hardware.info/?probe=3c450d9163) | Dec 04, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [196fb6634a](https://bsd-hardware.info/?probe=196fb6634a) | Dec 03, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a6e076d9f](https://bsd-hardware.info/?probe=1a6e076d9f) | Dec 02, 2024 |
| Sony          | VGN-FZ11MR                  | Notebook    | [0d1d0647c3](https://bsd-hardware.info/?probe=0d1d0647c3) | Dec 01, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [9cfdbbc839](https://bsd-hardware.info/?probe=9cfdbbc839) | Nov 29, 2024 |
| Gigabyte      | H110MSTX-HD3 Reborn by d... | Desktop     | [c1473102cc](https://bsd-hardware.info/?probe=c1473102cc) | Nov 29, 2024 |
| HP            | 3048h                       | Desktop     | [36a9b2f835](https://bsd-hardware.info/?probe=36a9b2f835) | Nov 29, 2024 |
| Gigabyte      | H110MSTX-HD3 Reborn by d... | Desktop     | [d99e7bd515](https://bsd-hardware.info/?probe=d99e7bd515) | Nov 28, 2024 |
| Sony          | VGN-FZ11MR                  | Notebook    | [9d737dbace](https://bsd-hardware.info/?probe=9d737dbace) | Nov 28, 2024 |
| Intel         | NUC5i3RYB K23918-501        | Mini pc     | [41e7363228](https://bsd-hardware.info/?probe=41e7363228) | Nov 25, 2024 |
| Inventec      | D CLASS A02                 | Desktop     | [dd77e68b2d](https://bsd-hardware.info/?probe=dd77e68b2d) | Nov 24, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [d66960aa84](https://bsd-hardware.info/?probe=d66960aa84) | Nov 24, 2024 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [577dc596e5](https://bsd-hardware.info/?probe=577dc596e5) | Nov 23, 2024 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [b5cfe0c0b2](https://bsd-hardware.info/?probe=b5cfe0c0b2) | Nov 23, 2024 |
| ASRock        | G41C-GS                     | Desktop     | [6330b64304](https://bsd-hardware.info/?probe=6330b64304) | Nov 23, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9422dbf997](https://bsd-hardware.info/?probe=9422dbf997) | Nov 22, 2024 |
| Lenovo        | 30C9 SDK0J40705 WIN 3425... | Desktop     | [80514ce1ec](https://bsd-hardware.info/?probe=80514ce1ec) | Nov 22, 2024 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ed161aa339](https://bsd-hardware.info/?probe=ed161aa339) | Nov 21, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [65071f6e52](https://bsd-hardware.info/?probe=65071f6e52) | Nov 18, 2024 |
| Biostar       | A68N-5200                   | Desktop     | [c0e81ef062](https://bsd-hardware.info/?probe=c0e81ef062) | Nov 13, 2024 |
| ASUSTek       | K54C                        | Notebook    | [4f0c073344](https://bsd-hardware.info/?probe=4f0c073344) | Nov 12, 2024 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [4bcf1051ee](https://bsd-hardware.info/?probe=4bcf1051ee) | Nov 09, 2024 |
| Lenovo        | 370B No DPK                 | All in one  | [d5270ebe40](https://bsd-hardware.info/?probe=d5270ebe40) | Nov 08, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [b5a01ca528](https://bsd-hardware.info/?probe=b5a01ca528) | Nov 05, 2024 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [cf1f1b90ea](https://bsd-hardware.info/?probe=cf1f1b90ea) | Nov 04, 2024 |
| Apple         | MacBook7,1                  | Notebook    | [056bc64a0c](https://bsd-hardware.info/?probe=056bc64a0c) | Nov 03, 2024 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [fa70f945fe](https://bsd-hardware.info/?probe=fa70f945fe) | Nov 03, 2024 |
| ASUSTek       | GL752VW                     | Notebook    | [efc1d86951](https://bsd-hardware.info/?probe=efc1d86951) | Nov 02, 2024 |
| Positivo      | H14BT58                     | Notebook    | [b54614c603](https://bsd-hardware.info/?probe=b54614c603) | Oct 31, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [fddb380732](https://bsd-hardware.info/?probe=fddb380732) | Oct 31, 2024 |
| Lenovo        | ThinkPad X280 20KES2VQ00    | Notebook    | [d864971168](https://bsd-hardware.info/?probe=d864971168) | Oct 30, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [4609004e3e](https://bsd-hardware.info/?probe=4609004e3e) | Oct 30, 2024 |
| ASUSTek       | X453SA                      | Notebook    | [51933883d6](https://bsd-hardware.info/?probe=51933883d6) | Oct 29, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [959da1d116](https://bsd-hardware.info/?probe=959da1d116) | Oct 29, 2024 |
| Lenovo        | ThinkPad E470 20H1002FLM    | Notebook    | [d11900e726](https://bsd-hardware.info/?probe=d11900e726) | Oct 25, 2024 |
| HP            | 829A                        | Mini pc     | [562f878b39](https://bsd-hardware.info/?probe=562f878b39) | Oct 25, 2024 |
| Lenovo        | ThinkPad X201T 3093A79      | Notebook    | [9f1d2db1a6](https://bsd-hardware.info/?probe=9f1d2db1a6) | Oct 25, 2024 |
| ASUSTek       | X99-A/USB                   | Desktop     | [92261cfa8a](https://bsd-hardware.info/?probe=92261cfa8a) | Oct 24, 2024 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [934ff561a5](https://bsd-hardware.info/?probe=934ff561a5) | Oct 20, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [6c6e16db1a](https://bsd-hardware.info/?probe=6c6e16db1a) | Oct 19, 2024 |
| HP            | ProLiant BL460c G7          | Server      | [efbbeb4731](https://bsd-hardware.info/?probe=efbbeb4731) | Oct 18, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [fa31be6f2f](https://bsd-hardware.info/?probe=fa31be6f2f) | Oct 17, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [f9dd56fa54](https://bsd-hardware.info/?probe=f9dd56fa54) | Oct 12, 2024 |
| MSI           | H81M-P33                    | Desktop     | [2d8b4d829c](https://bsd-hardware.info/?probe=2d8b4d829c) | Oct 12, 2024 |
| HP            | 3048h                       | Desktop     | [ac96e7804d](https://bsd-hardware.info/?probe=ac96e7804d) | Oct 09, 2024 |
| Dell          | 00V62H A00                  | Desktop     | [87e3fa093a](https://bsd-hardware.info/?probe=87e3fa093a) | Oct 09, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [37cb237ce2](https://bsd-hardware.info/?probe=37cb237ce2) | Oct 07, 2024 |
| Medion        | S15449                      | Notebook    | [b7a0fc4f21](https://bsd-hardware.info/?probe=b7a0fc4f21) | Oct 06, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | Notebook    | [12b6d4abf3](https://bsd-hardware.info/?probe=12b6d4abf3) | Oct 06, 2024 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [74e780b044](https://bsd-hardware.info/?probe=74e780b044) | Oct 05, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [370c96e120](https://bsd-hardware.info/?probe=370c96e120) | Oct 02, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [71dbda24c3](https://bsd-hardware.info/?probe=71dbda24c3) | Oct 02, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [4713dcbd2c](https://bsd-hardware.info/?probe=4713dcbd2c) | Oct 02, 2024 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [c1a712cb6a](https://bsd-hardware.info/?probe=c1a712cb6a) | Sep 30, 2024 |
| Sony          | VGN-FZ19VN                  | Notebook    | [a5e398c41f](https://bsd-hardware.info/?probe=a5e398c41f) | Sep 28, 2024 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [0f0cf20fe9](https://bsd-hardware.info/?probe=0f0cf20fe9) | Sep 28, 2024 |
| Acer          | Aspire 4820                 | Notebook    | [2ba56db0c4](https://bsd-hardware.info/?probe=2ba56db0c4) | Sep 26, 2024 |
| Dell          | 03NVJ6 A01                  | Desktop     | [ebf63c5ffd](https://bsd-hardware.info/?probe=ebf63c5ffd) | Sep 22, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [6b5e02a63b](https://bsd-hardware.info/?probe=6b5e02a63b) | Sep 22, 2024 |
| Dell          | Latitude E6440              | Notebook    | [cfabb27e7a](https://bsd-hardware.info/?probe=cfabb27e7a) | Sep 21, 2024 |
| Dell          | Latitude E6540              | Notebook    | [e8bdb7007b](https://bsd-hardware.info/?probe=e8bdb7007b) | Sep 19, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8657f5a0d9](https://bsd-hardware.info/?probe=8657f5a0d9) | Sep 19, 2024 |
| Dell          | 03NVJ6 A01                  | Desktop     | [f13225748a](https://bsd-hardware.info/?probe=f13225748a) | Sep 18, 2024 |
| Supermicro    | X10DAi                      | Desktop     | [11f1473c17](https://bsd-hardware.info/?probe=11f1473c17) | Sep 17, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [f2a74cd513](https://bsd-hardware.info/?probe=f2a74cd513) | Sep 17, 2024 |
| ASUSTek       | X540SC                      | Notebook    | [6eb57b9354](https://bsd-hardware.info/?probe=6eb57b9354) | Sep 13, 2024 |
| MSI           | Z170I GAMING PRO AC         | Desktop     | [373dba44f0](https://bsd-hardware.info/?probe=373dba44f0) | Sep 13, 2024 |
| Dell          | Latitude E7440              | Notebook    | [0e95a909ad](https://bsd-hardware.info/?probe=0e95a909ad) | Sep 11, 2024 |
| HP            | Mini 210-1000               | Notebook    | [5271409065](https://bsd-hardware.info/?probe=5271409065) | Sep 11, 2024 |
| MSI           | H81M-P33                    | Desktop     | [677cd5d559](https://bsd-hardware.info/?probe=677cd5d559) | Sep 10, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [0e601e6efb](https://bsd-hardware.info/?probe=0e601e6efb) | Sep 09, 2024 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [2fd4b148bb](https://bsd-hardware.info/?probe=2fd4b148bb) | Sep 06, 2024 |
| HP            | Stream Notebook             | Notebook    | [7d427180ae](https://bsd-hardware.info/?probe=7d427180ae) | Aug 30, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [d5e4a58748](https://bsd-hardware.info/?probe=d5e4a58748) | Aug 27, 2024 |
| Intel         | ChiefRiver                  | Desktop     | [fbd6c1a3b4](https://bsd-hardware.info/?probe=fbd6c1a3b4) | Aug 25, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [2d6cb49646](https://bsd-hardware.info/?probe=2d6cb49646) | Aug 23, 2024 |
| ASRock        | A320M-ITX                   | Desktop     | [73f83a9526](https://bsd-hardware.info/?probe=73f83a9526) | Aug 22, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [d74ebfd0d0](https://bsd-hardware.info/?probe=d74ebfd0d0) | Aug 19, 2024 |
| Intel         | X99H                        | Desktop     | [aa96aabb57](https://bsd-hardware.info/?probe=aa96aabb57) | Aug 18, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [e7df8e47f0](https://bsd-hardware.info/?probe=e7df8e47f0) | Aug 17, 2024 |
| Intelbras     | S41ILx                      | Notebook    | [85e9cf50b4](https://bsd-hardware.info/?probe=85e9cf50b4) | Aug 16, 2024 |
| ASUSTek       | 1215N                       | Notebook    | [0970f34b42](https://bsd-hardware.info/?probe=0970f34b42) | Aug 15, 2024 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | Desktop     | [38f29aa721](https://bsd-hardware.info/?probe=38f29aa721) | Aug 14, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [fa5e1f0cae](https://bsd-hardware.info/?probe=fa5e1f0cae) | Aug 11, 2024 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [49322a0f1b](https://bsd-hardware.info/?probe=49322a0f1b) | Aug 10, 2024 |
| Lenovo        | ThinkPad X270 20HMA04EJP    | Notebook    | [d515224367](https://bsd-hardware.info/?probe=d515224367) | Aug 09, 2024 |
| Lenovo        | ThinkPad T520 4243FS9       | Notebook    | [664d48690e](https://bsd-hardware.info/?probe=664d48690e) | Aug 08, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [242b9ea518](https://bsd-hardware.info/?probe=242b9ea518) | Aug 04, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [7ed3471df1](https://bsd-hardware.info/?probe=7ed3471df1) | Aug 04, 2024 |
| Fujitsu       | CELSIUS H710                | Notebook    | [dc35b855e5](https://bsd-hardware.info/?probe=dc35b855e5) | Jul 31, 2024 |
| ASUSTek       | P8P67 LE                    | Desktop     | [38d26ac7ef](https://bsd-hardware.info/?probe=38d26ac7ef) | Jul 30, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [cd3e80c5af](https://bsd-hardware.info/?probe=cd3e80c5af) | Jul 28, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3RV0... | Notebook    | [271f4b1030](https://bsd-hardware.info/?probe=271f4b1030) | Jul 27, 2024 |
| Lenovo        | ThinkPad T470s 20HGS3RV0... | Notebook    | [a5fe1bd04d](https://bsd-hardware.info/?probe=a5fe1bd04d) | Jul 27, 2024 |
| ASRock        | H67DE                       | Desktop     | [cd6ed79756](https://bsd-hardware.info/?probe=cd6ed79756) | Jul 26, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [2bad6a4269](https://bsd-hardware.info/?probe=2bad6a4269) | Jul 26, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [153f0e6cfb](https://bsd-hardware.info/?probe=153f0e6cfb) | Jul 25, 2024 |
| Toshiba       | QOSMIO F60                  | Notebook    | [fadd162caa](https://bsd-hardware.info/?probe=fadd162caa) | Jul 25, 2024 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [7f2ef42cea](https://bsd-hardware.info/?probe=7f2ef42cea) | Jul 24, 2024 |
| Dell          | Latitude 3410               | Notebook    | [c5b69d8cf7](https://bsd-hardware.info/?probe=c5b69d8cf7) | Jul 23, 2024 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [64726b8282](https://bsd-hardware.info/?probe=64726b8282) | Jul 21, 2024 |
| HP            | Pavilion dv7                | Notebook    | [5178909b84](https://bsd-hardware.info/?probe=5178909b84) | Jul 21, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f2ae8a59aa](https://bsd-hardware.info/?probe=f2ae8a59aa) | Jul 21, 2024 |
| HP            | Pavilion g6                 | Notebook    | [19ddfa696d](https://bsd-hardware.info/?probe=19ddfa696d) | Jul 20, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c043693b87](https://bsd-hardware.info/?probe=c043693b87) | Jul 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b66947b74a](https://bsd-hardware.info/?probe=b66947b74a) | Jul 16, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f8e29bf3c5](https://bsd-hardware.info/?probe=f8e29bf3c5) | Jul 16, 2024 |
| Lenovo        | ThinkPad X200 7459WT6       | Notebook    | [fa49267388](https://bsd-hardware.info/?probe=fa49267388) | Jul 13, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [45d3874955](https://bsd-hardware.info/?probe=45d3874955) | Jul 13, 2024 |
| HP            | 18E7                        | Desktop     | [23520b25c4](https://bsd-hardware.info/?probe=23520b25c4) | Jul 12, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [0de2223643](https://bsd-hardware.info/?probe=0de2223643) | Jul 11, 2024 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [35b96c6c77](https://bsd-hardware.info/?probe=35b96c6c77) | Jul 11, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [0529ba7873](https://bsd-hardware.info/?probe=0529ba7873) | Jul 09, 2024 |
| Unknown       | NF-MCP61                    | Desktop     | [74d9784221](https://bsd-hardware.info/?probe=74d9784221) | Jul 06, 2024 |
| Lenovo        | ThinkPad X230 2325SCM       | Notebook    | [8406cad5be](https://bsd-hardware.info/?probe=8406cad5be) | Jul 06, 2024 |
| Unknown       | NF-MCP61                    | Desktop     | [b2f074d817](https://bsd-hardware.info/?probe=b2f074d817) | Jul 06, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [d28277fb98](https://bsd-hardware.info/?probe=d28277fb98) | Jun 30, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [fd24cae390](https://bsd-hardware.info/?probe=fd24cae390) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [e9a1a61239](https://bsd-hardware.info/?probe=e9a1a61239) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [babc2efc9e](https://bsd-hardware.info/?probe=babc2efc9e) | Jun 26, 2024 |
| Lenovo        | M30-70 20446                | Notebook    | [0251872176](https://bsd-hardware.info/?probe=0251872176) | Jun 26, 2024 |
| HP            | ZBook 17 G3                 | Notebook    | [6b15cd05af](https://bsd-hardware.info/?probe=6b15cd05af) | Jun 26, 2024 |
| MSI           | Z77A-G43                    | Desktop     | [9dbddeec9f](https://bsd-hardware.info/?probe=9dbddeec9f) | Jun 26, 2024 |
| MSI           | Z77A-G43                    | Desktop     | [794812339d](https://bsd-hardware.info/?probe=794812339d) | Jun 26, 2024 |
| Gigabyte      | Z590 VISION G               | Desktop     | [39bb67c433](https://bsd-hardware.info/?probe=39bb67c433) | Jun 25, 2024 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [a0118881e6](https://bsd-hardware.info/?probe=a0118881e6) | Jun 20, 2024 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [70254105eb](https://bsd-hardware.info/?probe=70254105eb) | Jun 19, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [65d6791029](https://bsd-hardware.info/?probe=65d6791029) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [fb23c3c64b](https://bsd-hardware.info/?probe=fb23c3c64b) | Jun 18, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [49f31626da](https://bsd-hardware.info/?probe=49f31626da) | Jun 16, 2024 |
| Dell          | Latitude E6410              | Notebook    | [30f7b05dcf](https://bsd-hardware.info/?probe=30f7b05dcf) | Jun 15, 2024 |
| Gigabyte      | H410M S2H V3                | Desktop     | [38e99138bb](https://bsd-hardware.info/?probe=38e99138bb) | Jun 12, 2024 |
| Intel         | H61                         | Desktop     | [cd7988a906](https://bsd-hardware.info/?probe=cd7988a906) | Jun 12, 2024 |
| Framework     | Laptop                      | Notebook    | [f43baabeee](https://bsd-hardware.info/?probe=f43baabeee) | Jun 12, 2024 |
| Fujitsu       | CELSIUS H710                | Notebook    | [93308d8e8e](https://bsd-hardware.info/?probe=93308d8e8e) | Jun 11, 2024 |
| Notebook      | W740SU                      | Notebook    | [31be7db967](https://bsd-hardware.info/?probe=31be7db967) | Jun 09, 2024 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [c4e275f1a2](https://bsd-hardware.info/?probe=c4e275f1a2) | Jun 08, 2024 |
| Acer          | Aspire C20-720              | All in one  | [b4c8bfd036](https://bsd-hardware.info/?probe=b4c8bfd036) | Jun 07, 2024 |
| Dell          | 0PU052                      | Desktop     | [ed6212c9ae](https://bsd-hardware.info/?probe=ed6212c9ae) | Jun 07, 2024 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [7e175ff9bd](https://bsd-hardware.info/?probe=7e175ff9bd) | Jun 06, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [cc126b0787](https://bsd-hardware.info/?probe=cc126b0787) | Jun 06, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [20959ef447](https://bsd-hardware.info/?probe=20959ef447) | Jun 05, 2024 |
| ASUSTek       | X555UJ                      | Notebook    | [df9f681ce9](https://bsd-hardware.info/?probe=df9f681ce9) | Jun 05, 2024 |
| Toshiba       | Satellite C800D             | Notebook    | [3b26adb52f](https://bsd-hardware.info/?probe=3b26adb52f) | Jun 05, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [05a19cce97](https://bsd-hardware.info/?probe=05a19cce97) | Jun 05, 2024 |
| Sony          | SVF1521G6EW                 | Notebook    | [b977d6f1e0](https://bsd-hardware.info/?probe=b977d6f1e0) | Jun 02, 2024 |
| Dell          | 03F1TC A00                  | Desktop     | [dbfad2d18f](https://bsd-hardware.info/?probe=dbfad2d18f) | Jun 02, 2024 |
| Dell          | Latitude E7250              | Notebook    | [b5504e5573](https://bsd-hardware.info/?probe=b5504e5573) | Jun 02, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51df4f57c5](https://bsd-hardware.info/?probe=51df4f57c5) | Jun 02, 2024 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [76d2f8d955](https://bsd-hardware.info/?probe=76d2f8d955) | May 28, 2024 |
| HP            | 21D0                        | Desktop     | [907ca67edb](https://bsd-hardware.info/?probe=907ca67edb) | May 27, 2024 |
| ASUSTek       | N50Vc                       | Notebook    | [69d37366c1](https://bsd-hardware.info/?probe=69d37366c1) | May 27, 2024 |
| Toshiba       | Satellite A110              | Notebook    | [df367f56ee](https://bsd-hardware.info/?probe=df367f56ee) | May 26, 2024 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [86a944edc8](https://bsd-hardware.info/?probe=86a944edc8) | May 26, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [ddf13477d5](https://bsd-hardware.info/?probe=ddf13477d5) | May 24, 2024 |
| Thomson       | N15C                        | Notebook    | [45c095d0c8](https://bsd-hardware.info/?probe=45c095d0c8) | May 23, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [ac725cc2bd](https://bsd-hardware.info/?probe=ac725cc2bd) | May 22, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [7148244e3e](https://bsd-hardware.info/?probe=7148244e3e) | May 21, 2024 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [91bfac051b](https://bsd-hardware.info/?probe=91bfac051b) | May 20, 2024 |
| ASUSTek       | Lancaster8                  | Desktop     | [6b2abc4d47](https://bsd-hardware.info/?probe=6b2abc4d47) | May 20, 2024 |
| HP            | Compaq Presario CQ71        | Notebook    | [7646daa3c0](https://bsd-hardware.info/?probe=7646daa3c0) | May 19, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [98429d1dc9](https://bsd-hardware.info/?probe=98429d1dc9) | May 19, 2024 |
| ASRock        | G41M-S3                     | Desktop     | [aeef672c4b](https://bsd-hardware.info/?probe=aeef672c4b) | May 17, 2024 |
| HP            | 83E1                        | Desktop     | [2227565c4c](https://bsd-hardware.info/?probe=2227565c4c) | May 15, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [26808aa91f](https://bsd-hardware.info/?probe=26808aa91f) | May 15, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [2a3fed3377](https://bsd-hardware.info/?probe=2a3fed3377) | May 15, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | Notebook    | [dc41ec80ef](https://bsd-hardware.info/?probe=dc41ec80ef) | May 14, 2024 |
| Acer          | Aspire XC-603               | Desktop     | [0d17afb0ea](https://bsd-hardware.info/?probe=0d17afb0ea) | May 13, 2024 |
| Pegatron      | 2A6C                        | Desktop     | [c133f11fe6](https://bsd-hardware.info/?probe=c133f11fe6) | May 11, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | Notebook    | [9bc81955aa](https://bsd-hardware.info/?probe=9bc81955aa) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | Notebook    | [651bd2de24](https://bsd-hardware.info/?probe=651bd2de24) | May 08, 2024 |
| Acer          | Aspire R3-131T              | Notebook    | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Dell          | 0DFRFW A01                  | Desktop     | [4532391ffd](https://bsd-hardware.info/?probe=4532391ffd) | May 06, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| Lenovo        | ThinkPad L420 7827W27       | Notebook    | [5231c79a27](https://bsd-hardware.info/?probe=5231c79a27) | May 05, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [d87059c342](https://bsd-hardware.info/?probe=d87059c342) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [35ab248dd4](https://bsd-hardware.info/?probe=35ab248dd4) | May 04, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [227924f274](https://bsd-hardware.info/?probe=227924f274) | May 03, 2024 |
| Shenzhen M... | PHBRC                       | Mini pc     | [f657134100](https://bsd-hardware.info/?probe=f657134100) | Apr 30, 2024 |
| Lenovo        | Legion Y7000P 81HC          | Notebook    | [3dff76a9dd](https://bsd-hardware.info/?probe=3dff76a9dd) | Apr 27, 2024 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [52ac87d342](https://bsd-hardware.info/?probe=52ac87d342) | Apr 27, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [a6e153110d](https://bsd-hardware.info/?probe=a6e153110d) | Apr 22, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [c1435ee19d](https://bsd-hardware.info/?probe=c1435ee19d) | Apr 21, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [6778d6844d](https://bsd-hardware.info/?probe=6778d6844d) | Apr 17, 2024 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [8e3f536127](https://bsd-hardware.info/?probe=8e3f536127) | Apr 16, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [256e25b666](https://bsd-hardware.info/?probe=256e25b666) | Apr 16, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0de254980a](https://bsd-hardware.info/?probe=0de254980a) | Apr 16, 2024 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [6ad215125a](https://bsd-hardware.info/?probe=6ad215125a) | Apr 14, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| MAXSUN        | MS-Challenger B450M         | Desktop     | [e3d38c06bf](https://bsd-hardware.info/?probe=e3d38c06bf) | Apr 13, 2024 |
| ASUSTek       | N76VZ                       | Notebook    | [c1af06bf99](https://bsd-hardware.info/?probe=c1af06bf99) | Apr 12, 2024 |
| Acer          | Aspire A314-35              | Notebook    | [6d4fa8616c](https://bsd-hardware.info/?probe=6d4fa8616c) | Apr 09, 2024 |
| MSI           | B360M BAZOOKA               | Desktop     | [af945cd1ad](https://bsd-hardware.info/?probe=af945cd1ad) | Apr 09, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [227f0ffb18](https://bsd-hardware.info/?probe=227f0ffb18) | Apr 09, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [426677818b](https://bsd-hardware.info/?probe=426677818b) | Apr 07, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| HP            | 8056                        | Desktop     | [a9e956a80b](https://bsd-hardware.info/?probe=a9e956a80b) | Apr 05, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Acer          | Aspire V5-431               | Notebook    | [9abe9b5007](https://bsd-hardware.info/?probe=9abe9b5007) | Apr 03, 2024 |
| Dell          | 06HR05 A00                  | Desktop     | [9505b5cf4f](https://bsd-hardware.info/?probe=9505b5cf4f) | Apr 02, 2024 |
| Lenovo        | ThinkPad W530 2447GH2       | Notebook    | [0cb3f41765](https://bsd-hardware.info/?probe=0cb3f41765) | Apr 01, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b46f6ead5d](https://bsd-hardware.info/?probe=b46f6ead5d) | Mar 28, 2024 |
| Lenovo        | N22 80S6                    | Notebook    | [7f8b876a83](https://bsd-hardware.info/?probe=7f8b876a83) | Mar 26, 2024 |
| Gigabyte      | H55M-USB3                   | Desktop     | [748ef69c9f](https://bsd-hardware.info/?probe=748ef69c9f) | Mar 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [faf771068a](https://bsd-hardware.info/?probe=faf771068a) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0fbac8264b](https://bsd-hardware.info/?probe=0fbac8264b) | Mar 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| HP            | 2B34                        | Desktop     | [850e6bf958](https://bsd-hardware.info/?probe=850e6bf958) | Mar 20, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| HP            | 2B5E                        | Desktop     | [35b1572267](https://bsd-hardware.info/?probe=35b1572267) | Mar 17, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [51841c9dfd](https://bsd-hardware.info/?probe=51841c9dfd) | Mar 17, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [8bcd2d01e2](https://bsd-hardware.info/?probe=8bcd2d01e2) | Mar 16, 2024 |
| HP            | 21D0                        | Desktop     | [7ca5d182a1](https://bsd-hardware.info/?probe=7ca5d182a1) | Mar 16, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2e83945861](https://bsd-hardware.info/?probe=2e83945861) | Mar 16, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Lenovo        | ThinkPad X220 429147U       | Notebook    | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| HP            | dx2480 MT(FN868PA)          | Desktop     | [d700a91a81](https://bsd-hardware.info/?probe=d700a91a81) | Mar 14, 2024 |
| HP            | 21D0                        | Desktop     | [69b7737f88](https://bsd-hardware.info/?probe=69b7737f88) | Mar 12, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6741cefeb7](https://bsd-hardware.info/?probe=6741cefeb7) | Mar 12, 2024 |
| ASUSTek       | PRIME J3355I-C              | Desktop     | [0b1cea4778](https://bsd-hardware.info/?probe=0b1cea4778) | Mar 12, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fd60868096](https://bsd-hardware.info/?probe=fd60868096) | Mar 10, 2024 |
| Dell          | Latitude E6220              | Notebook    | [5a42aa442f](https://bsd-hardware.info/?probe=5a42aa442f) | Mar 09, 2024 |
| Maibenben     | MaiBook X series            | Notebook    | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [3653895b8e](https://bsd-hardware.info/?probe=3653895b8e) | Mar 03, 2024 |
| Dell          | 07F37C A00                  | Desktop     | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | Notebook    | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| ASUSTek       | X550EA                      | Notebook    | [42b10a3b6a](https://bsd-hardware.info/?probe=42b10a3b6a) | Mar 01, 2024 |
| Gigabyte      | H81M-D3H                    | Desktop     | [798bfe44fe](https://bsd-hardware.info/?probe=798bfe44fe) | Feb 29, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [d877d925e1](https://bsd-hardware.info/?probe=d877d925e1) | Feb 28, 2024 |
| Itautec       | Infoway                     | Notebook    | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [ec927cc965](https://bsd-hardware.info/?probe=ec927cc965) | Feb 27, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9c88473675](https://bsd-hardware.info/?probe=9c88473675) | Feb 27, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [dd8beb7c03](https://bsd-hardware.info/?probe=dd8beb7c03) | Feb 27, 2024 |
| Roqos         | Core RC10                   | Desktop     | [5aeeba64ff](https://bsd-hardware.info/?probe=5aeeba64ff) | Feb 26, 2024 |
| HP            | 213D A01                    | Desktop     | [eef6db0d05](https://bsd-hardware.info/?probe=eef6db0d05) | Feb 26, 2024 |
| Dell          | 0G261D A00                  | Desktop     | [34a8d8ab2f](https://bsd-hardware.info/?probe=34a8d8ab2f) | Feb 25, 2024 |
| ASUSTek       | X550EA                      | Notebook    | [a49aa7d3d8](https://bsd-hardware.info/?probe=a49aa7d3d8) | Feb 24, 2024 |
| Lenovo        | ThinkPad X220 4290KV8       | Notebook    | [9bc55d7f8a](https://bsd-hardware.info/?probe=9bc55d7f8a) | Feb 23, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [49b226f804](https://bsd-hardware.info/?probe=49b226f804) | Feb 23, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
| HP            | 802E                        | Desktop     | [6ef690a057](https://bsd-hardware.info/?probe=6ef690a057) | Feb 17, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [0fc891ba64](https://bsd-hardware.info/?probe=0fc891ba64) | Feb 17, 2024 |
| ASRock        | B360M Xtreme                | Desktop     | [e84af03816](https://bsd-hardware.info/?probe=e84af03816) | Feb 16, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afe2427e9d](https://bsd-hardware.info/?probe=afe2427e9d) | Feb 15, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [191c41587b](https://bsd-hardware.info/?probe=191c41587b) | Feb 12, 2024 |
| Notebook      | N960Kx                      | Notebook    | [4e83c12f96](https://bsd-hardware.info/?probe=4e83c12f96) | Feb 12, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [47f57b0893](https://bsd-hardware.info/?probe=47f57b0893) | Feb 11, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [5315513827](https://bsd-hardware.info/?probe=5315513827) | Feb 11, 2024 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [32822eef4c](https://bsd-hardware.info/?probe=32822eef4c) | Feb 11, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [47e91ddd92](https://bsd-hardware.info/?probe=47e91ddd92) | Feb 08, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | Notebook    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Desktop     | [87313cc66c](https://bsd-hardware.info/?probe=87313cc66c) | Feb 07, 2024 |
| Intel         | STK1AW32SC H91596-303       | Desktop     | [14fcea4fb9](https://bsd-hardware.info/?probe=14fcea4fb9) | Feb 06, 2024 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a2c1b1addb](https://bsd-hardware.info/?probe=a2c1b1addb) | Feb 06, 2024 |
| ASUSTek       | K52F                        | Notebook    | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Panasonic     | CF-52PGNBX2M                | Notebook    | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | F8Vr                        | Notebook    | [2f3b6a6089](https://bsd-hardware.info/?probe=2f3b6a6089) | Feb 03, 2024 |
| ASUSTek       | K52F                        | Notebook    | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [f9481e59b6](https://bsd-hardware.info/?probe=f9481e59b6) | Feb 01, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [952fa413fe](https://bsd-hardware.info/?probe=952fa413fe) | Feb 01, 2024 |
| ASUSTek       | P5E3 PRO                    | Desktop     | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [b5cc2ab7ff](https://bsd-hardware.info/?probe=b5cc2ab7ff) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [a952b43f14](https://bsd-hardware.info/?probe=a952b43f14) | Jan 31, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [b66edf2033](https://bsd-hardware.info/?probe=b66edf2033) | Jan 31, 2024 |
| ASUSTek       | A68HM-K                     | Desktop     | [f321ac1114](https://bsd-hardware.info/?probe=f321ac1114) | Jan 31, 2024 |
| Fujitsu       | LIFEBOOK LH772              | Notebook    | [afe4fb6608](https://bsd-hardware.info/?probe=afe4fb6608) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK LH772              | Notebook    | [491823db1e](https://bsd-hardware.info/?probe=491823db1e) | Jan 30, 2024 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [8cad8e084d](https://bsd-hardware.info/?probe=8cad8e084d) | Jan 28, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | Notebook    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [94f04895fe](https://bsd-hardware.info/?probe=94f04895fe) | Jan 27, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [f0db40d2f4](https://bsd-hardware.info/?probe=f0db40d2f4) | Jan 24, 2024 |
| Dell          | Precision M4700             | Notebook    | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | 0YNVJG A02                  | Desktop     | [7c9f213d88](https://bsd-hardware.info/?probe=7c9f213d88) | Jan 20, 2024 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [e52e1e182e](https://bsd-hardware.info/?probe=e52e1e182e) | Jan 20, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [2065609a0c](https://bsd-hardware.info/?probe=2065609a0c) | Jan 19, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [62abffe402](https://bsd-hardware.info/?probe=62abffe402) | Jan 19, 2024 |
| Dell          | Latitude 7480               | Notebook    | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | Mini 210-1000               | Notebook    | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| Star Labs     | StarBook                    | Notebook    | [1e903acb93](https://bsd-hardware.info/?probe=1e903acb93) | Jan 16, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [5642aa5018](https://bsd-hardware.info/?probe=5642aa5018) | Jan 16, 2024 |
| HP            | Mini 210-1000               | Notebook    | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [b56a8b041a](https://bsd-hardware.info/?probe=b56a8b041a) | Jan 14, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e0d9f347e9](https://bsd-hardware.info/?probe=e0d9f347e9) | Jan 13, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2f960c437](https://bsd-hardware.info/?probe=b2f960c437) | Jan 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [514b270501](https://bsd-hardware.info/?probe=514b270501) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [13f09671ce](https://bsd-hardware.info/?probe=13f09671ce) | Jan 07, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [7561797db6](https://bsd-hardware.info/?probe=7561797db6) | Jan 06, 2024 |
| HP            | 1905                        | Desktop     | [9e67ddf10b](https://bsd-hardware.info/?probe=9e67ddf10b) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [9fed9e1dd9](https://bsd-hardware.info/?probe=9fed9e1dd9) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | Notebook    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [45a80466a3](https://bsd-hardware.info/?probe=45a80466a3) | Jan 04, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [4b0c5d65b0](https://bsd-hardware.info/?probe=4b0c5d65b0) | Jan 02, 2024 |
| Samsung       | R510/P510                   | Notebook    | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| Dell          | Vostro V130                 | Notebook    | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0e31087126](https://bsd-hardware.info/?probe=0e31087126) | Dec 30, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d08712b71d](https://bsd-hardware.info/?probe=d08712b71d) | Dec 26, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | Notebook    | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| AMI           | Intel                       | Notebook    | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Lenovo        | ThinkPad X250 20CLS8Q601    | Notebook    | [2c52684baa](https://bsd-hardware.info/?probe=2c52684baa) | Dec 25, 2023 |
| eMachines     | eM350                       | Notebook    | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [84a9704b97](https://bsd-hardware.info/?probe=84a9704b97) | Dec 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| Intel         | NUC11ATBPE M49844-303       | Mini pc     | [1e083d16ac](https://bsd-hardware.info/?probe=1e083d16ac) | Dec 21, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [bd9dd3d647](https://bsd-hardware.info/?probe=bd9dd3d647) | Dec 19, 2023 |
| HP            | 212B                        | Desktop     | [d110ce488b](https://bsd-hardware.info/?probe=d110ce488b) | Dec 18, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ba2cad0d55](https://bsd-hardware.info/?probe=ba2cad0d55) | Dec 18, 2023 |
| HP            | 212B                        | Desktop     | [1737c1241b](https://bsd-hardware.info/?probe=1737c1241b) | Dec 16, 2023 |
| Acer          | V5-131                      | Notebook    | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [61aea25165](https://bsd-hardware.info/?probe=61aea25165) | Dec 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2b600594af](https://bsd-hardware.info/?probe=2b600594af) | Dec 07, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | ThinkCentre M70e 0828W17    | Desktop     | [02c7f33254](https://bsd-hardware.info/?probe=02c7f33254) | Dec 03, 2023 |
| Intel         | H81U                        | Notebook    | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [818a6b3f2c](https://bsd-hardware.info/?probe=818a6b3f2c) | Nov 29, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [87351f500b](https://bsd-hardware.info/?probe=87351f500b) | Nov 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [bf23ac0d57](https://bsd-hardware.info/?probe=bf23ac0d57) | Nov 26, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| ASRock        | X399 Professional Gaming    | Desktop     | [9c9645e87a](https://bsd-hardware.info/?probe=9c9645e87a) | Nov 23, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [daca9b37fd](https://bsd-hardware.info/?probe=daca9b37fd) | Nov 23, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [81faa8cbd2](https://bsd-hardware.info/?probe=81faa8cbd2) | Nov 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Toshiba       | Satellite C40-A             | Notebook    | [0c545b75e9](https://bsd-hardware.info/?probe=0c545b75e9) | Nov 21, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [9f690594a0](https://bsd-hardware.info/?probe=9f690594a0) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | Notebook    | [cecd389c82](https://bsd-hardware.info/?probe=cecd389c82) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [797f393ce0](https://bsd-hardware.info/?probe=797f393ce0) | Nov 19, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | Desktop     | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [fc54b10db3](https://bsd-hardware.info/?probe=fc54b10db3) | Nov 18, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [204ee8891b](https://bsd-hardware.info/?probe=204ee8891b) | Nov 16, 2023 |
| Dell          | Precision 7720              | Notebook    | [65a0287ad6](https://bsd-hardware.info/?probe=65a0287ad6) | Nov 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | Notebook    | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [e28d22b5ed](https://bsd-hardware.info/?probe=e28d22b5ed) | Nov 16, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [e5f0053202](https://bsd-hardware.info/?probe=e5f0053202) | Nov 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [6d55a75c4d](https://bsd-hardware.info/?probe=6d55a75c4d) | Nov 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [52593923f0](https://bsd-hardware.info/?probe=52593923f0) | Nov 13, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Gateway       | NV79                        | Notebook    | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [6ee8baf52b](https://bsd-hardware.info/?probe=6ee8baf52b) | Nov 08, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [abaff39583](https://bsd-hardware.info/?probe=abaff39583) | Nov 08, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [1f6c70fd78](https://bsd-hardware.info/?probe=1f6c70fd78) | Nov 07, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6e2c3d13a4](https://bsd-hardware.info/?probe=6e2c3d13a4) | Nov 07, 2023 |
| Dell          | Precision 7720              | Notebook    | [45614f0ff9](https://bsd-hardware.info/?probe=45614f0ff9) | Nov 06, 2023 |
| HP            | 3031h                       | Desktop     | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a217880b63](https://bsd-hardware.info/?probe=a217880b63) | Nov 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [ef59e0f80d](https://bsd-hardware.info/?probe=ef59e0f80d) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [a5bf30aeac](https://bsd-hardware.info/?probe=a5bf30aeac) | Nov 02, 2023 |
| Dell          | Precision 7720              | Notebook    | [cc321f8dea](https://bsd-hardware.info/?probe=cc321f8dea) | Nov 01, 2023 |
| Shuttle       | NC10U                       | Desktop     | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [534dc363f2](https://bsd-hardware.info/?probe=534dc363f2) | Oct 30, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6aee98fb1a](https://bsd-hardware.info/?probe=6aee98fb1a) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Toshiba       | Unknown                     | Notebook    | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | Latitude 3440               | Notebook    | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0aa91c2a5c](https://bsd-hardware.info/?probe=0aa91c2a5c) | Oct 15, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fbc9fe11b1](https://bsd-hardware.info/?probe=fbc9fe11b1) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Dell          | Latitude D830               | Notebook    | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| HP            | 1497                        | Desktop     | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [02d64d7433](https://bsd-hardware.info/?probe=02d64d7433) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [66a1e081e6](https://bsd-hardware.info/?probe=66a1e081e6) | Oct 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c25c930afa](https://bsd-hardware.info/?probe=c25c930afa) | Oct 05, 2023 |
| ASUSTek       | K73E                        | Notebook    | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | Desktop     | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [5c6c241347](https://bsd-hardware.info/?probe=5c6c241347) | Oct 02, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [05dc7174b1](https://bsd-hardware.info/?probe=05dc7174b1) | Oct 01, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [14ead4227b](https://bsd-hardware.info/?probe=14ead4227b) | Oct 01, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [9b9f826560](https://bsd-hardware.info/?probe=9b9f826560) | Oct 01, 2023 |
| Lenovo        | ThinkCentre M81 5049D7G     | Desktop     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [f98d4be34d](https://bsd-hardware.info/?probe=f98d4be34d) | Sep 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e587bca33a](https://bsd-hardware.info/?probe=e587bca33a) | Sep 29, 2023 |
| Dell          | Latitude E6430              | Notebook    | [bec165c243](https://bsd-hardware.info/?probe=bec165c243) | Sep 27, 2023 |
| HP            | 8055                        | Desktop     | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | Desktop     | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| HP            | 18E8                        | Desktop     | [cb4a5de309](https://bsd-hardware.info/?probe=cb4a5de309) | Sep 21, 2023 |
| HP            | 83F3                        | Desktop     | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [1b0fcd812e](https://bsd-hardware.info/?probe=1b0fcd812e) | Sep 13, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [92ce33c604](https://bsd-hardware.info/?probe=92ce33c604) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | Notebook    | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| Acer          | Monserrat                   | Notebook    | [9c79dbac8b](https://bsd-hardware.info/?probe=9c79dbac8b) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [d615a8daba](https://bsd-hardware.info/?probe=d615a8daba) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [6f5db06303](https://bsd-hardware.info/?probe=6f5db06303) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [6811f92db7](https://bsd-hardware.info/?probe=6811f92db7) | Sep 08, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [231ef39d3b](https://bsd-hardware.info/?probe=231ef39d3b) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Intel         | HM570                       | Desktop     | [3112f263f5](https://bsd-hardware.info/?probe=3112f263f5) | Sep 07, 2023 |
| Intel         | HM570                       | Desktop     | [0e4bfa9794](https://bsd-hardware.info/?probe=0e4bfa9794) | Sep 07, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | Notebook    | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [bd2df105c0](https://bsd-hardware.info/?probe=bd2df105c0) | Sep 06, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | Notebook    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | Notebook    | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ed1fade3db](https://bsd-hardware.info/?probe=ed1fade3db) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d1dbf86d9](https://bsd-hardware.info/?probe=5d1dbf86d9) | Sep 04, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [00a4f6e5a0](https://bsd-hardware.info/?probe=00a4f6e5a0) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| ASUSTek       | 1005PXD                     | Notebook    | [8dac93d19d](https://bsd-hardware.info/?probe=8dac93d19d) | Sep 03, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [df0a3f55c2](https://bsd-hardware.info/?probe=df0a3f55c2) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d49b8413db](https://bsd-hardware.info/?probe=d49b8413db) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9b322dc202](https://bsd-hardware.info/?probe=9b322dc202) | Sep 02, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [4356e5b30f](https://bsd-hardware.info/?probe=4356e5b30f) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d4a4a46409](https://bsd-hardware.info/?probe=d4a4a46409) | Aug 31, 2023 |
| HP            | 2000                        | Notebook    | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [c2ed5fa6bd](https://bsd-hardware.info/?probe=c2ed5fa6bd) | Aug 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| HP            | Pavilion dv3500             | Notebook    | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Fujitsu       | FMVA0803D                   | Notebook    | [36528b957c](https://bsd-hardware.info/?probe=36528b957c) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [eb85f0b975](https://bsd-hardware.info/?probe=eb85f0b975) | Aug 27, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [5f23f0620f](https://bsd-hardware.info/?probe=5f23f0620f) | Aug 27, 2023 |
| Fujitsu       | FMVA0803D                   | Notebook    | [8ce6118bf4](https://bsd-hardware.info/?probe=8ce6118bf4) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a085ba3865](https://bsd-hardware.info/?probe=a085ba3865) | Aug 25, 2023 |
| NVN-ED01      | Unknown                     | Notebook    | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | Notebook    | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| HP            | 82A5                        | Mini pc     | [4b56141a3b](https://bsd-hardware.info/?probe=4b56141a3b) | Aug 21, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | Notebook    | [c32aad1b1f](https://bsd-hardware.info/?probe=c32aad1b1f) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | Notebook    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| ASRock        | H110M-STX                   | Desktop     | [5c819b9ff1](https://bsd-hardware.info/?probe=5c819b9ff1) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Star Labs     | Lite                        | Notebook    | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [30c58f7403](https://bsd-hardware.info/?probe=30c58f7403) | Aug 15, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [472c17f992](https://bsd-hardware.info/?probe=472c17f992) | Aug 15, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | Notebook    | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | Notebook    | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4b0b4b88a7](https://bsd-hardware.info/?probe=4b0b4b88a7) | Aug 10, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [4f4c550075](https://bsd-hardware.info/?probe=4f4c550075) | Aug 10, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [4fc1fbaba1](https://bsd-hardware.info/?probe=4fc1fbaba1) | Aug 09, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9693a5fc69](https://bsd-hardware.info/?probe=9693a5fc69) | Aug 08, 2023 |
| HP            | 82C0                        | Mini pc     | [6ad9c871cb](https://bsd-hardware.info/?probe=6ad9c871cb) | Aug 07, 2023 |
| HP            | 82C0                        | Mini pc     | [124e7b14df](https://bsd-hardware.info/?probe=124e7b14df) | Aug 07, 2023 |
| Intel         | H81                         | Desktop     | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Mini pc     | [6a45c89f9c](https://bsd-hardware.info/?probe=6a45c89f9c) | Aug 06, 2023 |
| HP            | 0AACh                       | Desktop     | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| HP            | 82C0                        | Mini pc     | [be2c1dd2f5](https://bsd-hardware.info/?probe=be2c1dd2f5) | Aug 03, 2023 |
| HP            | 82C0                        | Mini pc     | [6fa14d3439](https://bsd-hardware.info/?probe=6fa14d3439) | Aug 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | Notebook    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| ASUSTek       | P5B SE                      | Desktop     | [6361457008](https://bsd-hardware.info/?probe=6361457008) | Jul 27, 2023 |
| HP            | 83E1                        | Desktop     | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [274a1e508f](https://bsd-hardware.info/?probe=274a1e508f) | Jul 26, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e266a42fa5](https://bsd-hardware.info/?probe=e266a42fa5) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [1b3ba2b86a](https://bsd-hardware.info/?probe=1b3ba2b86a) | Jul 25, 2023 |
| HP            | 339A                        | Desktop     | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [b0745153e4](https://bsd-hardware.info/?probe=b0745153e4) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| Acer          | Spin SP314-21               | Convertible | [375c9f30cd](https://bsd-hardware.info/?probe=375c9f30cd) | Jul 22, 2023 |
| Panasonic     | CF-F9JYFNDR                 | Notebook    | [be7b261f26](https://bsd-hardware.info/?probe=be7b261f26) | Jul 21, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | Notebook    | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| Dell          | 04YP6J A01                  | Desktop     | [f474b9f986](https://bsd-hardware.info/?probe=f474b9f986) | Jul 16, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [82bc9b32bd](https://bsd-hardware.info/?probe=82bc9b32bd) | Jul 16, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | Notebook    | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [a7284068da](https://bsd-hardware.info/?probe=a7284068da) | Jul 12, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| ASUSTek       | 1005PXD                     | Notebook    | [246032ee65](https://bsd-hardware.info/?probe=246032ee65) | Jul 02, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | Notebook    | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [127f92759b](https://bsd-hardware.info/?probe=127f92759b) | Jun 26, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [a6e959358f](https://bsd-hardware.info/?probe=a6e959358f) | Jun 25, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [111b9572ba](https://bsd-hardware.info/?probe=111b9572ba) | Jun 25, 2023 |
| Dell          | Latitude E4310              | Notebook    | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | Desktop     | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [485ba68539](https://bsd-hardware.info/?probe=485ba68539) | Jun 22, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [9f41fa4740](https://bsd-hardware.info/?probe=9f41fa4740) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8eb0be633d](https://bsd-hardware.info/?probe=8eb0be633d) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| ASUSTek       | 1015P                       | Notebook    | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | Notebook    | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2008116e96](https://bsd-hardware.info/?probe=2008116e96) | Jun 10, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| Lenovo        | S10-3                       | Notebook    | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | Notebook    | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | 3398                        | Desktop     | [980c0fc5a8](https://bsd-hardware.info/?probe=980c0fc5a8) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [fdd78a8f45](https://bsd-hardware.info/?probe=fdd78a8f45) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [16dd6af1a9](https://bsd-hardware.info/?probe=16dd6af1a9) | Jun 03, 2023 |
| Panasonic     | CF-NX1GDHYS                 | Notebook    | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Intel         | H81                         | Desktop     | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| ASRock        | H410M/ac                    | Desktop     | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| HP            | 21D0                        | Desktop     | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | Desktop     | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Fujitsu       | Unknown                     | Notebook    | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | Desktop     | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [05bd720b57](https://bsd-hardware.info/?probe=05bd720b57) | May 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [5960982eb3](https://bsd-hardware.info/?probe=5960982eb3) | May 25, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Timi          | TM1701                      | Notebook    | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | Desktop     | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | Notebook    | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [4965fc4251](https://bsd-hardware.info/?probe=4965fc4251) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [047b049834](https://bsd-hardware.info/?probe=047b049834) | May 18, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Sony          | SVF14A15CBB                 | Notebook    | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [b22c9a0cdf](https://bsd-hardware.info/?probe=b22c9a0cdf) | May 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [4eea72e4a6](https://bsd-hardware.info/?probe=4eea72e4a6) | May 11, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | Desktop     | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [bb96adbb13](https://bsd-hardware.info/?probe=bb96adbb13) | May 08, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| Acer          | V5-131                      | Notebook    | [9d3ba324bc](https://bsd-hardware.info/?probe=9d3ba324bc) | May 06, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| HP            | 82B4                        | Desktop     | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e4e2bba5fb](https://bsd-hardware.info/?probe=e4e2bba5fb) | May 02, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [83ccb5ff07](https://bsd-hardware.info/?probe=83ccb5ff07) | May 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
| Gigabyte      | GA-MA790X-UD4               | Desktop     | [71e5f4aa1f](https://bsd-hardware.info/?probe=71e5f4aa1f) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3f089673e0](https://bsd-hardware.info/?probe=3f089673e0) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [396d7f268c](https://bsd-hardware.info/?probe=396d7f268c) | May 01, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [50836a160a](https://bsd-hardware.info/?probe=50836a160a) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [779f5f8827](https://bsd-hardware.info/?probe=779f5f8827) | Apr 30, 2023 |
| Dell          | Latitude E5570              | Notebook    | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| NCR           | Richmond BIOS.6.0           | Desktop     | [e41e1e5c70](https://bsd-hardware.info/?probe=e41e1e5c70) | Apr 28, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [e735610d5c](https://bsd-hardware.info/?probe=e735610d5c) | Apr 27, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [db767ed552](https://bsd-hardware.info/?probe=db767ed552) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| Acer          | Spin SP314-21               | Convertible | [f5debc3ef8](https://bsd-hardware.info/?probe=f5debc3ef8) | Apr 27, 2023 |
| HP            | 8056                        | Desktop     | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cf0771c3a2](https://bsd-hardware.info/?probe=cf0771c3a2) | Apr 25, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [9678198b3b](https://bsd-hardware.info/?probe=9678198b3b) | Apr 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7caed06fdb](https://bsd-hardware.info/?probe=7caed06fdb) | Apr 24, 2023 |
| Google        | Peppy                       | Notebook    | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | Notebook    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| Packard Be... | DOT SE                      | Notebook    | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | Notebook    | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Dell          | 0VTC0D A02                  | Desktop     | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Acer          | Acadia V1.44                | Desktop     | [97bda17afa](https://bsd-hardware.info/?probe=97bda17afa) | Apr 19, 2023 |
| Acer          | V5-131                      | Notebook    | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Acer          | Spin SP314-21               | Convertible | [820e7da3c8](https://bsd-hardware.info/?probe=820e7da3c8) | Apr 18, 2023 |
| Medion        | E15302                      | Notebook    | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [a9c8c58abc](https://bsd-hardware.info/?probe=a9c8c58abc) | Apr 16, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Pegatron      | 2A72h                       | Desktop     | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| HP            | 3397                        | Desktop     | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| Samsung       | 370E4K                      | Notebook    | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | Notebook    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Acer          | Spin SP314-21               | Convertible | [a5ee042606](https://bsd-hardware.info/?probe=a5ee042606) | Apr 12, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | Notebook    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [689c25b4f6](https://bsd-hardware.info/?probe=689c25b4f6) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| Lenovo        | Tilapia CRB                 | Desktop     | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Google        | Wolf                        | Notebook    | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| HP            | 8055                        | Desktop     | [acef283e7c](https://bsd-hardware.info/?probe=acef283e7c) | Apr 02, 2023 |
| ASRock        | AB350M Pro4-F               | Desktop     | [424f3a2021](https://bsd-hardware.info/?probe=424f3a2021) | Apr 02, 2023 |
| ASUSTek       | X58C                        | Notebook    | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [068773e0e8](https://bsd-hardware.info/?probe=068773e0e8) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| DNS           | W9x0LU                      | Notebook    | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| Acer          | Aspire 5745DG               | Notebook    | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | Notebook    | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [a9bc1579c1](https://bsd-hardware.info/?probe=a9bc1579c1) | Mar 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Intel         | Intel                       | Notebook    | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Dell          | Inspiron 3195               | Convertible | [2afbb563b7](https://bsd-hardware.info/?probe=2afbb563b7) | Mar 30, 2023 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [a69c208286](https://bsd-hardware.info/?probe=a69c208286) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | Notebook    | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | Notebook    | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [0eb67759f0](https://bsd-hardware.info/?probe=0eb67759f0) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | Notebook    | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| Irbis         | NB78                        | Notebook    | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| LG Electro... | COLUMBIA                    | Notebook    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | Notebook    | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | Notebook    | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| MSI           | 870-G45                     | Desktop     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | Notebook    | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [ea2865cbf5](https://bsd-hardware.info/?probe=ea2865cbf5) | Mar 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [97d37b6e2f](https://bsd-hardware.info/?probe=97d37b6e2f) | Mar 25, 2023 |
| Samsung       | R468/R418                   | Notebook    | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | Notebook    | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7945f26073](https://bsd-hardware.info/?probe=7945f26073) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| MSI           | 870-G45                     | Desktop     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [c0b8eb494e](https://bsd-hardware.info/?probe=c0b8eb494e) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| HP            | 8055                        | Desktop     | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| HP            | 8350                        | Desktop     | [46dedb22a0](https://bsd-hardware.info/?probe=46dedb22a0) | Mar 24, 2023 |
| Dell          | Latitude 5500               | Notebook    | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [ff97717798](https://bsd-hardware.info/?probe=ff97717798) | Mar 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [e7cadcdae1](https://bsd-hardware.info/?probe=e7cadcdae1) | Mar 23, 2023 |
| Acer          | Revo 70                     | Desktop     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ef7c622d8d](https://bsd-hardware.info/?probe=ef7c622d8d) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ededfcfd39](https://bsd-hardware.info/?probe=ededfcfd39) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Unknown       | T360D11                     | Desktop     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | Notebook    | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| Biostar       | H61MGC                      | Desktop     | [94e565457c](https://bsd-hardware.info/?probe=94e565457c) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| Foxconn       | M61PMV FAB                  | Desktop     | [197d75cbaa](https://bsd-hardware.info/?probe=197d75cbaa) | Mar 21, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Intel         | X99                         | Desktop     | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| Dell          | 0GM819                      | Desktop     | [9d5996dd7a](https://bsd-hardware.info/?probe=9d5996dd7a) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| HP            | 8054                        | Desktop     | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Dell          | 0GM819                      | Desktop     | [da7c02c542](https://bsd-hardware.info/?probe=da7c02c542) | Mar 20, 2023 |
| Lenovo        | ThinkPad E595 20NF0002BM    | Notebook    | [83ee1d297d](https://bsd-hardware.info/?probe=83ee1d297d) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASUSTek       | K501UQ                      | Notebook    | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | Notebook    | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [40a4d98b9c](https://bsd-hardware.info/?probe=40a4d98b9c) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | Notebook    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [f26bbd9dde](https://bsd-hardware.info/?probe=f26bbd9dde) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | Notebook    | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29b3a70374](https://bsd-hardware.info/?probe=29b3a70374) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | Notebook    | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| HP            | 1632                        | Desktop     | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | Notebook    | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | Notebook    | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [0bae1528b9](https://bsd-hardware.info/?probe=0bae1528b9) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [c1c53bb88b](https://bsd-hardware.info/?probe=c1c53bb88b) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f14a448799](https://bsd-hardware.info/?probe=f14a448799) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [44c7f21a07](https://bsd-hardware.info/?probe=44c7f21a07) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| HP            | 3398                        | Desktop     | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | Notebook    | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | 81B7                        | All in one  | [fa5eb6a694](https://bsd-hardware.info/?probe=fa5eb6a694) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [c4798050c6](https://bsd-hardware.info/?probe=c4798050c6) | Mar 15, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [ecb9b5d004](https://bsd-hardware.info/?probe=ecb9b5d004) | Mar 14, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [25256b1698](https://bsd-hardware.info/?probe=25256b1698) | Mar 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cb6b586564](https://bsd-hardware.info/?probe=cb6b586564) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| MSI           | 0A48                        | Desktop     | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| Dell          | Latitude D630               | Notebook    | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | Notebook    | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| AZW           | U59                         | Desktop     | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | Desktop     | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Google        | Panther                     | Desktop     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| Samsung       | R468/R418                   | Notebook    | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [e96ecce822](https://bsd-hardware.info/?probe=e96ecce822) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| T-bao         | MINI PC                     | Desktop     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | Notebook    | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | Notebook    | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [de20e463ea](https://bsd-hardware.info/?probe=de20e463ea) | Mar 12, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [8a41ff57c2](https://bsd-hardware.info/?probe=8a41ff57c2) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | Notebook    | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [a39b128f44](https://bsd-hardware.info/?probe=a39b128f44) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | Notebook    | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [34afe9e044](https://bsd-hardware.info/?probe=34afe9e044) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | Desktop     | [aebf680e82](https://bsd-hardware.info/?probe=aebf680e82) | Mar 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | Desktop     | [6c50fda85b](https://bsd-hardware.info/?probe=6c50fda85b) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [5fc3d86bac](https://bsd-hardware.info/?probe=5fc3d86bac) | Mar 12, 2023 |
| MSI           | H61M-E22                    | Desktop     | [227c78f3c1](https://bsd-hardware.info/?probe=227c78f3c1) | Mar 12, 2023 |
| ASRock        | Q1900M                      | Desktop     | [5d0f6c2276](https://bsd-hardware.info/?probe=5d0f6c2276) | Mar 12, 2023 |
| HP            | 8768 A                      | Desktop     | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ad604088a2](https://bsd-hardware.info/?probe=ad604088a2) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ededc04017](https://bsd-hardware.info/?probe=ededc04017) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| Fujitsu       | JIM86YD                     | Desktop     | [7a69b91093](https://bsd-hardware.info/?probe=7a69b91093) | Mar 12, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [5ae8ebe3cd](https://bsd-hardware.info/?probe=5ae8ebe3cd) | Mar 11, 2023 |
| HP            | 843B                        | Desktop     | [c1886bcd29](https://bsd-hardware.info/?probe=c1886bcd29) | Mar 11, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | Notebook    | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| HP            | 3398                        | Desktop     | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | Notebook    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | Notebook    | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d05a143723](https://bsd-hardware.info/?probe=d05a143723) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | Notebook    | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/helloSystem/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| helloSystem 0.8.1       | 577       | 27.14%  |
| helloSystem 0.7.0       | 452       | 21.26%  |
| helloSystem 0.8.0       | 254       | 11.95%  |
| helloSystem 0.5.0       | 245       | 11.52%  |
| helloSystem 0.4.0       | 190       | 8.94%   |
| helloSystem 0.9.0       | 168       | 7.9%    |
| helloSystem 0.6.0       | 141       | 6.63%   |
| helloSystem 0.8.2       | 68        | 3.2%    |
| helloSystem 0.3.0       | 25        | 1.18%   |
| helloSystem 13.1-p2     | 2         | 0.09%   |
| helloSystem 13.1        | 1         | 0.05%   |
| helloSystem 13.0-STABLE | 1         | 0.05%   |
| helloSystem 13.0-p11    | 1         | 0.05%   |
| helloSystem             | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 1966      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 1964      | 99.9%   |
| arm64 | 2         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 1945      | 98.48%  |
| GNOME        | 10        | 0.51%   |
| KDE5         | 8         | 0.41%   |
| XFCE         | 4         | 0.2%    |
| TWM          | 2         | 0.1%    |
| Cinnamon     | 2         | 0.1%    |
| Window Maker | 1         | 0.05%   |
| LXQt         | 1         | 0.05%   |
| JWM          | 1         | 0.05%   |
| IceWM        | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 1966      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 1960      | 99.49%  |
| SDDM    | 3         | 0.15%   |
| GDM     | 3         | 0.15%   |
| Console | 3         | 0.15%   |
| LightDM | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_US        | 1337      | 65.35%  |
| Unknown      | 161       | 7.87%   |
| fr_FR        | 138       | 6.74%   |
| en           | 92        | 4.5%    |
| ru_RU        | 52        | 2.54%   |
| de_DE        | 51        | 2.49%   |
| es_ES        | 47        | 2.3%    |
| it_IT        | 21        | 1.03%   |
| pt_BR        | 18        | 0.88%   |
| fr           | 17        | 0.83%   |
| pl_PL        | 13        | 0.64%   |
| ru           | 12        | 0.59%   |
| C            | 11        | 0.54%   |
| zh_CN        | 9         | 0.44%   |
| pt           | 9         | 0.44%   |
| es           | 9         | 0.44%   |
| de           | 7         | 0.34%   |
| nl_NL        | 6         | 0.29%   |
| en_GB        | 5         | 0.24%   |
| tr_TR        | 4         | 0.2%    |
| jp_JP        | 4         | 0.2%    |
| it           | 3         | 0.15%   |
| fi_FI        | 3         | 0.15%   |
| zh_TW        | 2         | 0.1%    |
| pt_PT        | 2         | 0.1%    |
| pl           | 2         | 0.1%    |
| nl           | 2         | 0.1%    |
| ko_KR        | 2         | 0.1%    |
| uk_UA        | 1         | 0.05%   |
| sv           | 1         | 0.05%   |
| LANG="en_US" | 1         | 0.05%   |
| ko           | 1         | 0.05%   |
| fi_DK        | 1         | 0.05%   |
| es_AR        | 1         | 0.05%   |
| en_UK        | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1862      | 94.23%  |
| BIOS | 114       | 5.77%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 1210      | 59.58%  |
| Cd9660 | 818       | 40.28%  |
| Ufs    | 3         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 1951      | 99.24%  |
| MBR  | 15        | 0.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 356       | 18.11%  |
| ASUSTek Computer    | 313       | 15.92%  |
| Hewlett-Packard     | 242       | 12.31%  |
| Dell                | 237       | 12.05%  |
| Gigabyte Technology | 140       | 7.12%   |
| Apple               | 86        | 4.37%   |
| Acer                | 79        | 4.02%   |
| ASRock              | 75        | 3.81%   |
| MSI                 | 66        | 3.36%   |
| Intel               | 57        | 2.9%    |
| Toshiba             | 32        | 1.63%   |
| Fujitsu             | 28        | 1.42%   |
| Samsung Electronics | 26        | 1.32%   |
| Unknown             | 18        | 0.92%   |
| Sony                | 16        | 0.81%   |
| Biostar             | 11        | 0.56%   |
| Pegatron            | 10        | 0.51%   |
| Google              | 10        | 0.51%   |
| Packard Bell        | 9         | 0.46%   |
| LG Electronics      | 7         | 0.36%   |
| Panasonic           | 6         | 0.31%   |
| Notebook            | 6         | 0.31%   |
| Foxconn             | 6         | 0.31%   |
| Acidanthera         | 6         | 0.31%   |
| Medion              | 5         | 0.25%   |
| Fujitsu Siemens     | 5         | 0.25%   |
| TUXEDO              | 4         | 0.2%    |
| Timi                | 4         | 0.2%    |
| Itautec             | 4         | 0.2%    |
| Gateway             | 4         | 0.2%    |
| AZW                 | 4         | 0.2%    |
| Supermicro          | 3         | 0.15%   |
| Star Labs           | 3         | 0.15%   |
| Shuttle             | 3         | 0.15%   |
| Positivo            | 3         | 0.15%   |
| HUAWEI              | 3         | 0.15%   |
| eMachines           | 3         | 0.15%   |
| T-bao               | 2         | 0.1%    |
| Razer               | 2         | 0.1%    |
| Microsoft           | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 24        | 1.22%   |
| ASUS All Series                | 18        | 0.92%   |
| Dell OptiPlex 9020             | 7         | 0.36%   |
| Apple MacBook4,1               | 7         | 0.36%   |
| Apple iMac9,1                  | 7         | 0.36%   |
| HP EliteDesk 800 G2 DM 35W     | 6         | 0.31%   |
| Dell Inspiron 3442             | 6         | 0.31%   |
| Apple MacPro5,1                | 6         | 0.31%   |
| Apple MacBookPro9,2            | 6         | 0.31%   |
| Intel H61                      | 5         | 0.25%   |
| HP Pavilion dv6                | 5         | 0.25%   |
| HP 2000                        | 5         | 0.25%   |
| Dell OptiPlex 780              | 5         | 0.25%   |
| Dell OptiPlex 755              | 5         | 0.25%   |
| Dell OptiPlex 3020             | 5         | 0.25%   |
| ASUS M5A78L-M/USB3             | 5         | 0.25%   |
| MSI MS-7C37                    | 4         | 0.2%    |
| HP ProDesk 600 G1 SFF          | 4         | 0.2%    |
| HP Pavilion Notebook           | 4         | 0.2%    |
| HP Pavilion g6                 | 4         | 0.2%    |
| HP EliteBook 840 G3            | 4         | 0.2%    |
| HP Compaq Elite 8300 USDT      | 4         | 0.2%    |
| Dell OptiPlex 7010             | 4         | 0.2%    |
| Dell Latitude E6420            | 4         | 0.2%    |
| Dell Latitude E5570            | 4         | 0.2%    |
| ASUS ROG STRIX B550-F GAMING   | 4         | 0.2%    |
| Apple MacBookPro5,5            | 4         | 0.2%    |
| Apple MacBookAir5,1            | 4         | 0.2%    |
| Apple MacBook5,1               | 4         | 0.2%    |
| Acer Aspire ES1-533            | 4         | 0.2%    |
| MSI MS-7B86                    | 3         | 0.15%   |
| MSI MS-7758                    | 3         | 0.15%   |
| Lenovo Z50-70 20354            | 3         | 0.15%   |
| Lenovo IdeaPad 110S-11IBR 80WG | 3         | 0.15%   |
| Intel X99                      | 3         | 0.15%   |
| Intel H81                      | 3         | 0.15%   |
| HP ProDesk 600 G1 DM           | 3         | 0.15%   |
| HP Notebook                    | 3         | 0.15%   |
| HP EliteDesk 800 G2 SFF        | 3         | 0.15%   |
| HP Compaq Elite 8300 SFF       | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 206       | 10.48%  |
| Dell Latitude         | 73        | 3.71%   |
| Dell OptiPlex         | 60        | 3.05%   |
| Acer Aspire           | 56        | 2.85%   |
| Dell Inspiron         | 53        | 2.7%    |
| HP Pavilion           | 42        | 2.14%   |
| ASUS PRIME            | 42        | 2.14%   |
| Lenovo IdeaPad        | 41        | 2.09%   |
| Lenovo ThinkCentre    | 40        | 2.03%   |
| HP Compaq             | 31        | 1.58%   |
| ASUS ROG              | 28        | 1.42%   |
| Unknown               | 24        | 1.22%   |
| HP EliteBook          | 23        | 1.17%   |
| Dell Precision        | 23        | 1.17%   |
| Toshiba Satellite     | 19        | 0.97%   |
| HP Laptop             | 19        | 0.97%   |
| HP EliteDesk          | 19        | 0.97%   |
| ASUS All              | 18        | 0.92%   |
| HP ProDesk            | 16        | 0.81%   |
| HP ProBook            | 14        | 0.71%   |
| ASUS VivoBook         | 14        | 0.71%   |
| ASUS TUF              | 13        | 0.66%   |
| Fujitsu LIFEBOOK      | 12        | 0.61%   |
| ASUS M5A78L-M         | 9         | 0.46%   |
| Lenovo Yoga           | 8         | 0.41%   |
| Dell XPS              | 8         | 0.41%   |
| Dell Vostro           | 8         | 0.41%   |
| Lenovo Legion         | 7         | 0.36%   |
| Gigabyte X570         | 7         | 0.36%   |
| ASUS P8Z77-V          | 7         | 0.36%   |
| Apple MacBookPro9     | 7         | 0.36%   |
| Apple MacBook5        | 7         | 0.36%   |
| Apple MacBook4        | 7         | 0.36%   |
| Apple iMac9           | 7         | 0.36%   |
| Packard Bell EasyNote | 6         | 0.31%   |
| Gigabyte B450M        | 6         | 0.31%   |
| Apple MacPro5         | 6         | 0.31%   |
| Apple MacBookPro5     | 6         | 0.31%   |
| Toshiba PORTEGE       | 5         | 0.25%   |
| Intel H61             | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 168       | 8.55%   |
| 2020    | 161       | 8.19%   |
| 2012    | 160       | 8.14%   |
| 2019    | 156       | 7.93%   |
| 2018    | 144       | 7.32%   |
| 2021    | 134       | 6.82%   |
| 2011    | 131       | 6.66%   |
| 2014    | 126       | 6.41%   |
| 2016    | 120       | 6.1%    |
| 2010    | 114       | 5.8%    |
| 2017    | 104       | 5.29%   |
| 2015    | 97        | 4.93%   |
| 2022    | 95        | 4.83%   |
| 2009    | 95        | 4.83%   |
| 2008    | 67        | 3.41%   |
| 2023    | 40        | 2.03%   |
| 2007    | 35        | 1.78%   |
| 2006    | 9         | 0.46%   |
| 2024    | 7         | 0.36%   |
| Unknown | 3         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1002      | 50.97%  |
| Desktop        | 856       | 43.54%  |
| Mini pc        | 43        | 2.19%   |
| All in one     | 33        | 1.68%   |
| Convertible    | 18        | 0.92%   |
| Server         | 8         | 0.41%   |
| Tablet         | 4         | 0.2%    |
| System on chip | 2         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1951      | 99.24%  |
| Yes  | 15        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 677       | 34.19%  |
| 4.01-8.0    | 522       | 26.36%  |
| 16.01-24.0  | 469       | 23.69%  |
| 32.01-64.0  | 147       | 7.42%   |
| 2.01-3.0    | 69        | 3.48%   |
| 64.01-256.0 | 42        | 2.12%   |
| 24.01-32.0  | 25        | 1.26%   |
| 3.01-4.0    | 24        | 1.21%   |
| 0.51-1.0    | 3         | 0.15%   |
| 1.01-2.0    | 2         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 1044      | 52.49%  |
| 0.51-1.0  | 631       | 31.72%  |
| 1.01-2.0  | 226       | 11.36%  |
| 2.01-3.0  | 62        | 3.12%   |
| 3.01-4.0  | 14        | 0.7%    |
| 4.01-8.0  | 7         | 0.35%   |
| 8.01-16.0 | 5         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1243      | 61.17%  |
| 2      | 391       | 19.24%  |
| 0      | 149       | 7.33%   |
| 3      | 142       | 6.99%   |
| 4      | 56        | 2.76%   |
| 5      | 27        | 1.33%   |
| 6      | 13        | 0.64%   |
| 9      | 3         | 0.15%   |
| 7      | 3         | 0.15%   |
| 10     | 2         | 0.1%    |
| 8      | 2         | 0.1%    |
| 13     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1231      | 62.46%  |
| Yes       | 740       | 37.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1794      | 91.25%  |
| No        | 172       | 8.75%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1334      | 67.72%  |
| No        | 636       | 32.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1017      | 51.34%  |
| No        | 964       | 48.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 326       | 16.57%  |
| Russia      | 173       | 8.79%   |
| Germany     | 163       | 8.28%   |
| Brazil      | 123       | 6.25%   |
| Spain       | 84        | 4.27%   |
| Italy       | 76        | 3.86%   |
| Poland      | 67        | 3.4%    |
| UK          | 66        | 3.35%   |
| China       | 66        | 3.35%   |
| Canada      | 57        | 2.9%    |
| France      | 54        | 2.74%   |
| Netherlands | 44        | 2.24%   |
| Indonesia   | 42        | 2.13%   |
| India       | 40        | 2.03%   |
| Hungary     | 36        | 1.83%   |
| Australia   | 36        | 1.83%   |
| Ukraine     | 33        | 1.68%   |
| Mexico      | 33        | 1.68%   |
| Romania     | 24        | 1.22%   |
| Turkey      | 21        | 1.07%   |
| Taiwan      | 21        | 1.07%   |
| Sweden      | 18        | 0.91%   |
| Argentina   | 18        | 0.91%   |
| Belgium     | 17        | 0.86%   |
| Portugal    | 16        | 0.81%   |
| Bulgaria    | 15        | 0.76%   |
| Switzerland | 14        | 0.71%   |
| South Korea | 13        | 0.66%   |
| Greece      | 13        | 0.66%   |
| Finland     | 13        | 0.66%   |
| Japan       | 12        | 0.61%   |
| Chile       | 12        | 0.61%   |
| Peru        | 10        | 0.51%   |
| Norway      | 10        | 0.51%   |
| Czechia     | 10        | 0.51%   |
| Colombia    | 10        | 0.51%   |
| Serbia      | 9         | 0.46%   |
| Vietnam     | 8         | 0.41%   |
| Lithuania   | 8         | 0.41%   |
| Venezuela   | 7         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 33        | 1.59%   |
| St Petersburg | 23        | 1.11%   |
| Sao Paulo     | 13        | 0.63%   |
| Berlin        | 13        | 0.63%   |
| Budapest      | 12        | 0.58%   |
| Paris         | 11        | 0.53%   |
| Guangzhou     | 11        | 0.53%   |
| Madrid        | 10        | 0.48%   |
| Wroclaw       | 9         | 0.43%   |
| New York      | 9         | 0.43%   |
| Krakow        | 9         | 0.43%   |
| Jakarta       | 9         | 0.43%   |
| Curitiba      | 9         | 0.43%   |
| Valencia      | 8         | 0.39%   |
| Sydney        | 8         | 0.39%   |
| Munich        | 8         | 0.39%   |
| Kyiv          | 8         | 0.39%   |
| Istanbul      | 8         | 0.39%   |
| Brisbane      | 8         | 0.39%   |
| Yekaterinburg | 7         | 0.34%   |
| Warsaw        | 7         | 0.34%   |
| Santiago      | 7         | 0.34%   |
| Manchester    | 7         | 0.34%   |
| Los Angeles   | 7         | 0.34%   |
| Lima          | 7         | 0.34%   |
| Zurich        | 6         | 0.29%   |
| Utrecht       | 6         | 0.29%   |
| Temple        | 6         | 0.29%   |
| Taichung      | 6         | 0.29%   |
| Surabaya      | 6         | 0.29%   |
| Stuttgart     | 6         | 0.29%   |
| Rome          | 6         | 0.29%   |
| Melbourne     | 6         | 0.29%   |
| Krasnodar     | 6         | 0.29%   |
| Kochi         | 6         | 0.29%   |
| Hanoi         | 6         | 0.29%   |
| Hamburg       | 6         | 0.29%   |
| Chicago       | 6         | 0.29%   |
| Chelyabinsk   | 6         | 0.29%   |
| Buenos Aires  | 6         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 417       | 573    | 15.81%  |
| Samsung Electronics | 394       | 542    | 14.94%  |
| Seagate             | 387       | 529    | 14.68%  |
| Kingston            | 187       | 215    | 7.09%   |
| Toshiba             | 176       | 209    | 6.67%   |
| Crucial             | 128       | 168    | 4.85%   |
| SanDisk             | 118       | 128    | 4.47%   |
| Hitachi             | 112       | 140    | 4.25%   |
| Intel               | 63        | 70     | 2.39%   |
| A-DATA Technology   | 61        | 74     | 2.31%   |
| HGST                | 40        | 47     | 1.52%   |
| Micron Technology   | 32        | 33     | 1.21%   |
| SPCC                | 29        | 38     | 1.1%    |
| SK hynix            | 28        | 31     | 1.06%   |
| Apple               | 28        | 32     | 1.06%   |
| Patriot             | 24        | 27     | 0.91%   |
| Transcend           | 21        | 23     | 0.8%    |
| China               | 21        | 22     | 0.8%    |
| PNY                 | 20        | 32     | 0.76%   |
| GOODRAM             | 17        | 18     | 0.64%   |
| Phison              | 16        | 20     | 0.61%   |
| OCZ                 | 16        | 18     | 0.61%   |
| KingSpec            | 15        | 19     | 0.57%   |
| Gigabyte Technology | 15        | 19     | 0.57%   |
| Fujitsu             | 14        | 17     | 0.53%   |
| Intenso             | 13        | 16     | 0.49%   |
| Corsair             | 13        | 13     | 0.49%   |
| Hewlett-Packard     | 11        | 13     | 0.42%   |
| Apacer              | 11        | 11     | 0.42%   |
| Silicon Motion      | 10        | 11     | 0.38%   |
| Lexar               | 10        | 11     | 0.38%   |
| Team                | 9         | 10     | 0.34%   |
| Maxtor              | 9         | 10     | 0.34%   |
| KIOXIA              | 9         | 9      | 0.34%   |
| LITEON              | 8         | 9      | 0.3%    |
| Plextor             | 7         | 8      | 0.27%   |
| LITEONIT            | 7         | 7      | 0.27%   |
| XPG                 | 6         | 7      | 0.23%   |
| SSSTC               | 5         | 5      | 0.19%   |
| Pioneer             | 5         | 5      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 36        | 1.25%   |
| Samsung SSD 860 EVO 500GB           | 28        | 0.97%   |
| Crucial CT500MX500SSD1 500GB        | 26        | 0.9%    |
| Samsung SSD 850 EVO 250GB           | 22        | 0.76%   |
| Kingston SA400S37120G 120GB         | 22        | 0.76%   |
| Seagate ST500DM002-1BD142 500GB     | 20        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 20        | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 19        | 0.66%   |
| Samsung SSD 860 EVO 1TB             | 18        | 0.62%   |
| Samsung SSD 860 EVO 250GB           | 17        | 0.59%   |
| Toshiba MQ01ABF050 500GB            | 16        | 0.55%   |
| Kingston SV300S37A120G 120GB        | 16        | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB        | 15        | 0.52%   |
| Toshiba MQ01ABD100 1TB              | 15        | 0.52%   |
| Toshiba DT01ACA100 1TB              | 15        | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 15        | 0.52%   |
| Seagate ST9500325AS 500GB           | 14        | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB      | 14        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB      | 14        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB      | 13        | 0.45%   |
| Kingston SA400S37480G 480GB         | 13        | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB        | 11        | 0.38%   |
| Toshiba HDWD110 1TB                 | 11        | 0.38%   |
| Seagate ST500LT012-1DG142 500GB     | 11        | 0.38%   |
| Seagate ST3500418AS 500GB           | 11        | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB      | 10        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB        | 10        | 0.35%   |
| Samsung SSD 870 EVO 500GB           | 10        | 0.35%   |
| Samsung SSD 850 EVO 500GB           | 10        | 0.35%   |
| Samsung SSD 840 EVO 250GB           | 10        | 0.35%   |
| A-DATA SU650 120GB                  | 10        | 0.35%   |
| Seagate ST9320325AS 320GB           | 9         | 0.31%   |
| Crucial CT480BX500SSD1 480GB        | 9         | 0.31%   |
| Crucial CT120BX500SSD1 120GB        | 9         | 0.31%   |
| WDC WDS500G2B0A-00SM50 500GB        | 8         | 0.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 8         | 0.28%   |
| Seagate ST1000LM049-2GH172 1TB      | 8         | 0.28%   |
| Seagate ST1000DM003-1CH162 1TB      | 8         | 0.28%   |
| Samsung SSD 980 PRO 1TB             | 8         | 0.28%   |
| Samsung SSD 980 1TB                 | 8         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 384       | 523    | 34.56%  |
| WDC                 | 331       | 443    | 29.79%  |
| Toshiba             | 143       | 170    | 12.87%  |
| Hitachi             | 112       | 140    | 10.08%  |
| Samsung Electronics | 63        | 81     | 5.67%   |
| HGST                | 40        | 47     | 3.6%    |
| Fujitsu             | 13        | 15     | 1.17%   |
| Maxtor              | 9         | 10     | 0.81%   |
| Apple               | 9         | 9      | 0.81%   |
| Hewlett-Packard     | 4         | 5      | 0.36%   |
| QUANTUM             | 1         | 1      | 0.09%   |
| LSI                 | 1         | 1      | 0.09%   |
| CLOVER              | 1         | 2      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 225       | 283    | 19.36%  |
| Kingston            | 149       | 173    | 12.82%  |
| SanDisk             | 118       | 128    | 10.15%  |
| Crucial             | 112       | 146    | 9.64%   |
| WDC                 | 65        | 77     | 5.59%   |
| A-DATA Technology   | 46        | 51     | 3.96%   |
| Intel               | 39        | 44     | 3.36%   |
| SPCC                | 25        | 33     | 2.15%   |
| Patriot             | 22        | 25     | 1.89%   |
| Toshiba             | 21        | 27     | 1.81%   |
| Micron Technology   | 21        | 21     | 1.81%   |
| China               | 21        | 22     | 1.81%   |
| PNY                 | 20        | 30     | 1.72%   |
| Transcend           | 19        | 21     | 1.64%   |
| Apple               | 18        | 22     | 1.55%   |
| GOODRAM             | 17        | 18     | 1.46%   |
| OCZ                 | 16        | 18     | 1.38%   |
| KingSpec            | 15        | 19     | 1.29%   |
| Intenso             | 13        | 16     | 1.12%   |
| Apacer              | 11        | 11     | 0.95%   |
| Gigabyte Technology | 9         | 11     | 0.77%   |
| LITEON              | 8         | 9      | 0.69%   |
| SK hynix            | 7         | 7      | 0.6%    |
| Plextor             | 7         | 8      | 0.6%    |
| LITEONIT            | 7         | 7      | 0.6%    |
| Lexar               | 7         | 7      | 0.6%    |
| Corsair             | 7         | 7      | 0.6%    |
| Team                | 6         | 7      | 0.52%   |
| Pioneer             | 5         | 5      | 0.43%   |
| Hewlett-Packard     | 5         | 6      | 0.43%   |
| XrayDisk            | 4         | 4      | 0.34%   |
| MidasForce          | 4         | 4      | 0.34%   |
| Dogfish             | 4         | 5      | 0.34%   |
| Verbatim            | 3         | 5      | 0.26%   |
| Smartbuy            | 3         | 3      | 0.26%   |
| OWC                 | 3         | 3      | 0.26%   |
| Leven               | 3         | 4      | 0.26%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.26%   |
| Hikvision           | 3         | 3      | 0.26%   |
| Fanxiang            | 3         | 3      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 990       | 1375   | 42.69%  |
| HDD  | 940       | 1447   | 40.53%  |
| NVMe | 389       | 507    | 16.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1657      | 2822   | 80.99%  |
| NVMe | 389       | 507    | 19.01%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1385      | 1997   | 70.23%  |
| 0.51-1.0   | 410       | 544    | 20.79%  |
| 1.01-2.0   | 103       | 159    | 5.22%   |
| 3.01-4.0   | 35        | 53     | 1.77%   |
| 4.01-10.0  | 20        | 34     | 1.01%   |
| 2.01-3.0   | 17        | 31     | 0.86%   |
| 10.01-20.0 | 2         | 4      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1104      | 53.64%  |
| 101-250        | 378       | 18.37%  |
| 251-500        | 259       | 12.59%  |
| 51-100         | 122       | 5.93%   |
| 501-1000       | 113       | 5.49%   |
| 21-50          | 50        | 2.43%   |
| 1001-2000      | 17        | 0.83%   |
| More than 3000 | 7         | 0.34%   |
| Unknown        | 7         | 0.34%   |
| 2001-3000      | 1         | 0.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1908      | 96.66%  |
| 101-250        | 19        | 0.96%   |
| 21-50          | 17        | 0.86%   |
| 251-500        | 7         | 0.35%   |
| Unknown        | 7         | 0.35%   |
| 51-100         | 6         | 0.3%    |
| 501-1000       | 4         | 0.2%    |
| More than 3000 | 3         | 0.15%   |
| 1001-2000      | 2         | 0.1%    |
| 2001-3000      | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 8         | 10     | 1.57%   |
| Seagate ST9320325AS 320GB           | 7         | 7      | 1.38%   |
| Seagate ST500DM002-1BD142 500GB     | 7         | 9      | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 11     | 1.38%   |
| Toshiba MQ01ABD100 1TB              | 6         | 6      | 1.18%   |
| Seagate ST3500418AS 500GB           | 5         | 5      | 0.98%   |
| Hitachi HTS545050A7E380 500GB       | 5         | 5      | 0.98%   |
| HGST HTS725050A7E630 500GB          | 5         | 6      | 0.98%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 4      | 0.79%   |
| Toshiba MQ01ABF050 500GB            | 4         | 6      | 0.79%   |
| Toshiba DT01ACA100 1TB              | 4         | 7      | 0.79%   |
| Samsung Electronics HD322HJ 320GB   | 4         | 5      | 0.79%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 0.79%   |
| Hitachi HTS541612J9SA00 120GB       | 4         | 4      | 0.79%   |
| HGST HTS541010A9E680 1TB            | 4         | 5      | 0.79%   |
| Toshiba MQ01ABD050 500GB            | 3         | 3      | 0.59%   |
| Toshiba MK3261GSYN 320GB            | 3         | 5      | 0.59%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 0.59%   |
| Seagate ST9160821AS 160GB           | 3         | 3      | 0.59%   |
| Seagate ST9160412AS 160GB           | 3         | 3      | 0.59%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 3      | 0.59%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 3      | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 3      | 0.59%   |
| Seagate ST380815AS 80GB             | 3         | 3      | 0.59%   |
| Seagate ST3320418AS 320GB           | 3         | 3      | 0.59%   |
| Seagate ST3250410AS 250GB           | 3         | 3      | 0.59%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 0.59%   |
| Seagate ST31000528AS 1TB            | 3         | 4      | 0.59%   |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.59%   |
| Samsung Electronics HD161HJ 160GB   | 3         | 3      | 0.59%   |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 0.59%   |
| HGST HTS545032A7E380 320GB          | 3         | 3      | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.39%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 4      | 0.39%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.39%   |
| WDC WD5000AAKS-08V0A0 500GB         | 2         | 2      | 0.39%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB            | 2         | 2      | 0.39%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 2      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 131       | 160    | 26.68%  |
| WDC                 | 105       | 115    | 21.38%  |
| Toshiba             | 59        | 70     | 12.02%  |
| Hitachi             | 57        | 65     | 11.61%  |
| Samsung Electronics | 37        | 50     | 7.54%   |
| HGST                | 19        | 22     | 3.87%   |
| Kingston            | 12        | 12     | 2.44%   |
| SanDisk             | 9         | 9      | 1.83%   |
| Intel               | 9         | 9      | 1.83%   |
| Crucial             | 9         | 14     | 1.83%   |
| Micron Technology   | 5         | 5      | 1.02%   |
| Apple               | 5         | 5      | 1.02%   |
| Maxtor              | 4         | 5      | 0.81%   |
| Fujitsu             | 4         | 4      | 0.81%   |
| SK hynix            | 3         | 3      | 0.61%   |
| Corsair             | 3         | 3      | 0.61%   |
| A-DATA Technology   | 3         | 3      | 0.61%   |
| SSSTC               | 2         | 2      | 0.41%   |
| OCZ                 | 2         | 2      | 0.41%   |
| LITEON              | 2         | 2      | 0.41%   |
| China               | 2         | 2      | 0.41%   |
| XrayDisk            | 1         | 1      | 0.2%    |
| Transcend           | 1         | 1      | 0.2%    |
| Silicon Motion      | 1         | 1      | 0.2%    |
| Pioneer             | 1         | 1      | 0.2%    |
| MidasForce          | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| faspeed             | 1         | 2      | 0.2%    |
| AGI                 | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 131       | 160    | 32.59%  |
| WDC                 | 100       | 110    | 24.88%  |
| Toshiba             | 57        | 68     | 14.18%  |
| Hitachi             | 57        | 65     | 14.18%  |
| Samsung Electronics | 26        | 31     | 6.47%   |
| HGST                | 19        | 22     | 4.73%   |
| Maxtor              | 4         | 5      | 1%      |
| Fujitsu             | 4         | 4      | 1%      |
| Apple               | 4         | 4      | 1%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 373       | 469    | 80.56%  |
| SSD  | 79        | 91     | 17.06%  |
| NVMe | 11        | 12     | 2.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                 | 3         | 3      | 21.43%  |
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-00YZCA0 320GB      | 1         | 1      | 7.14%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 7.14%   |
| Seagate ST3250310AS 250GB         | 1         | 1      | 7.14%   |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 7.14%   |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 7.14%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 7.14%   |
| Hitachi HDS721032CLA362 320GB     | 1         | 1      | 7.14%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.14%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 21.43%  |
| SanDisk             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| Samsung Electronics | 2         | 3      | 14.29%  |
| Seagate             | 1         | 1      | 7.14%   |
| HPE                 | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1523      | 2670   | 74.66%  |
| Malfunc  | 453       | 572    | 22.21%  |
| Detected | 50        | 72     | 2.45%   |
| Failed   | 14        | 15     | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1483      | 61.18%  |
| AMD                                     | 325       | 13.41%  |
| Samsung Electronics                     | 156       | 6.44%   |
| SanDisk                                 | 64        | 2.64%   |
| Nvidia                                  | 51        | 2.1%    |
| Kingston Technology Company             | 41        | 1.69%   |
| Phison Electronics                      | 35        | 1.44%   |
| ASMedia Technology                      | 32        | 1.32%   |
| Silicon Motion                          | 29        | 1.2%    |
| SK hynix                                | 22        | 0.91%   |
| Micron/Crucial Technology               | 20        | 0.83%   |
| JMicron Technology                      | 20        | 0.83%   |
| Marvell Technology Group                | 18        | 0.74%   |
| ADATA Technology                        | 16        | 0.66%   |
| KIOXIA                                  | 14        | 0.58%   |
| Realtek Semiconductor                   | 12        | 0.5%    |
| Micron Technology                       | 12        | 0.5%    |
| Broadcom / LSI                          | 12        | 0.5%    |
| Toshiba                                 | 11        | 0.45%   |
| VIA Technologies                        | 7         | 0.29%   |
| Shenzhen Longsys Electronics            | 6         | 0.25%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.21%   |
| Solid State Storage Technology          | 4         | 0.17%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.17%   |
| Seagate Technology                      | 4         | 0.17%   |
| Hewlett-Packard                         | 3         | 0.12%   |
| Adaptec                                 | 3         | 0.12%   |
| Lite-On IT Corp. / Plextor              | 2         | 0.08%   |
| Biwin Storage Technology                | 2         | 0.08%   |
| Silicon Image                           | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| OCZ Technology Group                    | 1         | 0.04%   |
| Lenovo                                  | 1         | 0.04%   |
| INNOGRIT                                | 1         | 0.04%   |
| Hosin Global Electronics                | 1         | 0.04%   |
| Enmotus                                 | 1         | 0.04%   |
| Chelsio Communications                  | 1         | 0.04%   |
| Broadcom                                | 1         | 0.04%   |
| Areca Technology                        | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 199       | 7.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 140       | 4.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 126       | 4.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 103       | 3.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 86        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 78        | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 73        | 2.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 65        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 61        | 2.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 54        | 1.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 46        | 1.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 45        | 1.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 45        | 1.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 45        | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 43        | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 42        | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 42        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 41        | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 40        | 1.43%   |
| Intel SATA Controller [RAID mode]                                                       | 38        | 1.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 37        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 37        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 36        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34        | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 33        | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 30        | 1.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 27        | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                            | 27        | 0.96%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 27        | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 24        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 24        | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 23        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 20        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19        | 0.68%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 19        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 18        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1585      | 64.8%   |
| NVMe | 438       | 17.91%  |
| IDE  | 299       | 12.22%  |
| RAID | 107       | 4.37%   |
| SAS  | 9         | 0.37%   |
| SCSI | 8         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1587      | 80.72%  |
| AMD      | 377       | 19.18%  |
| Rockchip | 1         | 0.05%   |
| ARM      | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 24        | 1.22%   |
| Intel CPU Version                           | 22        | 1.12%   |
| Intel Core 2 Duo                            | 22        | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 20        | 1.01%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 19        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 18        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 17        | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 17        | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 16        | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 15        | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 14        | 0.71%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 11        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 11        | 0.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 11        | 0.56%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 11        | 0.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 11        | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 11        | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 11        | 0.56%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 11        | 0.56%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 10        | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10        | 0.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 9         | 0.46%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 9         | 0.46%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 9         | 0.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 9         | 0.46%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 9         | 0.46%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 9         | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 9         | 0.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 9         | 0.46%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9         | 0.46%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 9         | 0.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 8         | 0.41%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 8         | 0.41%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 8         | 0.41%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 8         | 0.41%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 8         | 0.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 8         | 0.41%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 8         | 0.41%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 8         | 0.41%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 8         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 508       | 25.79%  |
| Intel Core i7           | 284       | 14.42%  |
| Intel Core i3           | 205       | 10.41%  |
| Intel Core 2 Duo        | 143       | 7.26%   |
| Intel Celeron           | 109       | 5.53%   |
| AMD Ryzen 5             | 89        | 4.52%   |
| Other                   | 86        | 4.37%   |
| Intel Xeon              | 80        | 4.06%   |
| Intel Pentium           | 61        | 3.1%    |
| AMD Ryzen 7             | 61        | 3.1%    |
| AMD Ryzen 3             | 30        | 1.52%   |
| Intel Pentium Dual-Core | 26        | 1.32%   |
| AMD FX                  | 26        | 1.32%   |
| Intel Atom              | 23        | 1.17%   |
| AMD Phenom II X4        | 18        | 0.91%   |
| Intel Core 2 Quad       | 17        | 0.86%   |
| AMD E1                  | 13        | 0.66%   |
| AMD A6                  | 13        | 0.66%   |
| Intel Genuine           | 12        | 0.61%   |
| AMD Ryzen 9             | 12        | 0.61%   |
| AMD A10                 | 12        | 0.61%   |
| Intel Core 2            | 10        | 0.51%   |
| AMD Athlon II X2        | 10        | 0.51%   |
| Intel Pentium Silver    | 8         | 0.41%   |
| Intel Core i9           | 8         | 0.41%   |
| AMD Ryzen Threadripper  | 8         | 0.41%   |
| AMD A8                  | 8         | 0.41%   |
| AMD E                   | 7         | 0.36%   |
| AMD Athlon              | 7         | 0.36%   |
| AMD A4                  | 7         | 0.36%   |
| AMD Athlon II X4        | 5         | 0.25%   |
| AMD Athlon 64 X2        | 5         | 0.25%   |
| Intel Pentium Dual      | 4         | 0.2%    |
| AMD Ryzen 5 PRO         | 4         | 0.2%    |
| AMD Phenom II X6        | 4         | 0.2%    |
| AMD E2                  | 4         | 0.2%    |
| Intel Pentium Gold      | 3         | 0.15%   |
| Intel Core m3           | 3         | 0.15%   |
| Intel Pentium 4         | 2         | 0.1%    |
| Intel Core m7           | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 857       | 43.55%  |
| 4       | 594       | 30.18%  |
| Unknown | 141       | 7.16%   |
| 6       | 111       | 5.64%   |
| 8       | 85        | 4.32%   |
| 12      | 71        | 3.61%   |
| 16      | 61        | 3.1%    |
| 1       | 18        | 0.91%   |
| 24      | 10        | 0.51%   |
| 10      | 6         | 0.3%    |
| 32      | 3         | 0.15%   |
| 20      | 3         | 0.15%   |
| 64      | 2         | 0.1%    |
| 48      | 2         | 0.1%    |
| 14      | 2         | 0.1%    |
| 18      | 1         | 0.05%   |
| 3       | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1904      | 96.85%  |
| 2       | 57        | 2.9%    |
| Unknown | 4         | 0.2%    |
| 8       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 960       | 48.83%  |
| 1       | 859       | 43.69%  |
| Unknown | 147       | 7.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 262       | 13.31%  |
| Haswell       | 212       | 10.77%  |
| IvyBridge     | 200       | 10.16%  |
| SandyBridge   | 171       | 8.68%   |
| Penryn        | 165       | 8.38%   |
| Skylake       | 153       | 7.77%   |
| Westmere      | 79        | 4.01%   |
| Core          | 74        | 3.76%   |
| Zen+          | 63        | 3.2%    |
| Unknown       | 54        | 2.74%   |
| Silvermont    | 53        | 2.69%   |
| Broadwell     | 53        | 2.69%   |
| Zen 2         | 52        | 2.64%   |
| Zen 3         | 50        | 2.54%   |
| Piledriver    | 45        | 2.29%   |
| K10           | 43        | 2.18%   |
| Zen           | 38        | 1.93%   |
| CometLake     | 33        | 1.68%   |
| Bonnell       | 21        | 1.07%   |
| Nehalem       | 20        | 1.02%   |
| TigerLake     | 19        | 0.96%   |
| Bobcat        | 19        | 0.96%   |
| Goldmont plus | 18        | 0.91%   |
| Excavator     | 18        | 0.91%   |
| Jaguar        | 13        | 0.66%   |
| Goldmont      | 13        | 0.66%   |
| K8 Hammer     | 11        | 0.56%   |
| Bulldozer     | 5         | 0.25%   |
| NetBurst      | 3         | 0.15%   |
| K10 Llano     | 3         | 0.15%   |
| IceLake       | 3         | 0.15%   |
| Puma          | 2         | 0.1%    |
| Steamroller   | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1199      | 54.13%  |
| Nvidia                           | 567       | 25.6%   |
| AMD                              | 441       | 19.91%  |
| Matrox Electronics Systems       | 4         | 0.18%   |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |
| ASPEED Technology                | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 137       | 6.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 119       | 5.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 3.09%   |
| Intel HD Graphics 530                                                                    | 58        | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 57        | 2.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 56        | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 53        | 2.34%   |
| Intel HD Graphics 620                                                                    | 51        | 2.25%   |
| Intel HD Graphics 5500                                                                   | 43        | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 43        | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 42        | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 41        | 1.81%   |
| Intel UHD Graphics 620                                                                   | 36        | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 32        | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 1.32%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 1.32%   |
| Intel HD Graphics 630                                                                    | 30        | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 29        | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 24        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 0.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 21        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 0.84%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 18        | 0.79%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 18        | 0.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 0.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 0.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 15        | 0.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 15        | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 14        | 0.62%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 14        | 0.62%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.62%   |
| Nvidia C79 [GeForce 9400M]                                                               | 13        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 867       | 43.74%  |
| 1 x Nvidia               | 389       | 19.63%  |
| 1 x AMD                  | 357       | 18.01%  |
| Intel + Nvidia           | 158       | 7.97%   |
| 2 x Intel                | 110       | 5.55%   |
| Intel + AMD              | 61        | 3.08%   |
| AMD + Nvidia             | 17        | 0.86%   |
| 2 x AMD                  | 7         | 0.35%   |
| 1 x Matrox               | 4         | 0.2%    |
| Other                    | 3         | 0.15%   |
| 2 x Nvidia               | 3         | 0.15%   |
| 1 x SiS                  | 3         | 0.15%   |
| 2 x Intel + 1 x Nvidia   | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + ASPEED             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1596      | 80.16%  |
| Proprietary | 293       | 14.72%  |
| Unknown     | 102       | 5.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1456      | 72.69%  |
| 0.01-0.5   | 134       | 6.69%   |
| 1.01-2.0   | 125       | 6.24%   |
| 0.51-1.0   | 101       | 5.04%   |
| 3.01-4.0   | 87        | 4.34%   |
| 7.01-8.0   | 49        | 2.45%   |
| 5.01-6.0   | 33        | 1.65%   |
| 2.01-3.0   | 10        | 0.5%    |
| 8.01-16.0  | 7         | 0.35%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 169       | 11.46%  |
| AU Optronics            | 158       | 10.71%  |
| LG Display              | 148       | 10.03%  |
| Chimei Innolux          | 114       | 7.73%   |
| BOE                     | 90        | 6.1%    |
| Dell                    | 88        | 5.97%   |
| Goldstar                | 83        | 5.63%   |
| Lenovo                  | 61        | 4.14%   |
| Acer                    | 61        | 4.14%   |
| Hewlett-Packard         | 57        | 3.86%   |
| Apple                   | 48        | 3.25%   |
| BenQ                    | 44        | 2.98%   |
| AOC                     | 37        | 2.51%   |
| Philips                 | 36        | 2.44%   |
| Ancor Communications    | 32        | 2.17%   |
| Chi Mei Optoelectronics | 25        | 1.69%   |
| ViewSonic               | 18        | 1.22%   |
| InfoVision              | 14        | 0.95%   |
| Sharp                   | 13        | 0.88%   |
| ASUSTek Computer        | 13        | 0.88%   |
| Iiyama                  | 11        | 0.75%   |
| Fujitsu Siemens         | 10        | 0.68%   |
| Sony                    | 8         | 0.54%   |
| MSI                     | 7         | 0.47%   |
| HannStar                | 7         | 0.47%   |
| PANDA                   | 6         | 0.41%   |
| NEC Computers           | 6         | 0.41%   |
| LG Philips              | 6         | 0.41%   |
| Toshiba                 | 5         | 0.34%   |
| Eizo                    | 5         | 0.34%   |
| Vizio                   | 4         | 0.27%   |
| Vestel Elektronik       | 4         | 0.27%   |
| LG Electronics          | 4         | 0.27%   |
| Unknown                 | 4         | 0.27%   |
| Packard Bell            | 3         | 0.2%    |
| Medion                  | 3         | 0.2%    |
| SAC                     | 2         | 0.14%   |
| RTK                     | 2         | 0.14%   |
| RS                      | 2         | 0.14%   |
| ONN                     | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 10        | 0.67%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 7         | 0.47%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                  | 7         | 0.47%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                       | 6         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch     | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 5         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 5         | 0.33%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                  | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch         | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch            | 5         | 0.33%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch       | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch    | 4         | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.27%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x160mm 12.0-inch                  | 4         | 0.27%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 4         | 0.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                | 4         | 0.27%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch         | 4         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 4         | 0.27%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                     | 4         | 0.27%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                        | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch           | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch            | 4         | 0.27%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 4         | 0.27%   |
| Unknown                                                                  | 4         | 0.27%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                          | 3         | 0.2%    |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                         | 3         | 0.2%    |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                   | 3         | 0.2%    |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                          | 3         | 0.2%    |
| LG Display LCD Monitor LGD045C 1366x768 340x190mm 15.3-inch              | 3         | 0.2%    |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch             | 3         | 0.2%    |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 3         | 0.2%    |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch             | 3         | 0.2%    |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 556       | 38.24%  |
| 1366x768 (WXGA)    | 393       | 27.03%  |
| 1600x900 (HD+)     | 70        | 4.81%   |
| 1280x800 (WXGA)    | 63        | 4.33%   |
| 2560x1440 (QHD)    | 59        | 4.06%   |
| 1280x1024 (SXGA)   | 53        | 3.65%   |
| 3840x2160 (4K)     | 49        | 3.37%   |
| 1680x1050 (WSXGA+) | 46        | 3.16%   |
| 1440x900 (WXGA+)   | 40        | 2.75%   |
| 1920x1200 (WUXGA)  | 24        | 1.65%   |
| 2560x1080          | 16        | 1.1%    |
| 1024x600           | 13        | 0.89%   |
| 1024x768 (XGA)     | 11        | 0.76%   |
| 3440x1440          | 10        | 0.69%   |
| 1920x540           | 8         | 0.55%   |
| 2560x1600          | 7         | 0.48%   |
| 1360x768           | 7         | 0.48%   |
| 3200x1800 (QHD+)   | 6         | 0.41%   |
| 1600x1200          | 3         | 0.21%   |
| Unknown            | 3         | 0.21%   |
| 3840x1080          | 2         | 0.14%   |
| 2048x1152          | 2         | 0.14%   |
| 1400x1050          | 2         | 0.14%   |
| 5760x2160          | 1         | 0.07%   |
| 3840x2400          | 1         | 0.07%   |
| 3520x1080          | 1         | 0.07%   |
| 3200x2000          | 1         | 0.07%   |
| 2880x1800          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2256x1504          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 2160x1440          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |
| 1800x1200          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 301       | 20.37%  |
| 13      | 250       | 16.91%  |
| 24      | 118       | 7.98%   |
| 21      | 107       | 7.24%   |
| 27      | 98        | 6.63%   |
| 23      | 87        | 5.89%   |
| 19      | 80        | 5.41%   |
| 12      | 73        | 4.94%   |
| 17      | 59        | 3.99%   |
| Unknown | 44        | 2.98%   |
| 18      | 40        | 2.71%   |
| 14      | 38        | 2.57%   |
| 11      | 32        | 2.17%   |
| 31      | 29        | 1.96%   |
| 22      | 21        | 1.42%   |
| 20      | 20        | 1.35%   |
| 34      | 17        | 1.15%   |
| 10      | 13        | 0.88%   |
| 40      | 6         | 0.41%   |
| 42      | 5         | 0.34%   |
| 28      | 5         | 0.34%   |
| 16      | 5         | 0.34%   |
| 29      | 4         | 0.27%   |
| 52      | 3         | 0.2%    |
| 50      | 3         | 0.2%    |
| 33      | 3         | 0.2%    |
| 9       | 3         | 0.2%    |
| 64      | 2         | 0.14%   |
| 54      | 2         | 0.14%   |
| 32      | 2         | 0.14%   |
| 25      | 2         | 0.14%   |
| 43      | 1         | 0.07%   |
| 41      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 30      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 498       | 33.99%  |
| 501-600     | 286       | 19.52%  |
| 401-500     | 237       | 16.18%  |
| 201-300     | 227       | 15.49%  |
| 351-400     | 79        | 5.39%   |
| 601-700     | 47        | 3.21%   |
| Unknown     | 44        | 3%      |
| 701-800     | 23        | 1.57%   |
| 1001-1500   | 10        | 0.68%   |
| 801-900     | 7         | 0.48%   |
| 901-1000    | 7         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1095      | 77%     |
| 16/10   | 182       | 12.8%   |
| 5/4     | 45        | 3.16%   |
| Unknown | 30        | 2.11%   |
| 21/9    | 26        | 1.83%   |
| 4/3     | 21        | 1.48%   |
| 3/2     | 20        | 1.41%   |
| 6/5     | 2         | 0.14%   |
| 3.88    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 288       | 19.62%  |
| 81-90          | 233       | 15.87%  |
| 91-100         | 233       | 15.87%  |
| 151-200        | 109       | 7.43%   |
| 301-350        | 101       | 6.88%   |
| 101-110        | 77        | 5.25%   |
| 61-70          | 72        | 4.9%    |
| 351-500        | 54        | 3.68%   |
| 141-150        | 52        | 3.54%   |
| Unknown        | 44        | 3%      |
| 71-80          | 42        | 2.86%   |
| 251-300        | 38        | 2.59%   |
| 121-130        | 37        | 2.52%   |
| 51-60          | 30        | 2.04%   |
| 41-50          | 16        | 1.09%   |
| 501-1000       | 15        | 1.02%   |
| More than 1000 | 10        | 0.68%   |
| 111-120        | 10        | 0.68%   |
| 131-140        | 6         | 0.41%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 520       | 35.64%  |
| 101-120       | 471       | 32.28%  |
| 121-160       | 345       | 23.65%  |
| 161-240       | 56        | 3.84%   |
| Unknown       | 44        | 3.02%   |
| More than 240 | 13        | 0.89%   |
| 1-50          | 10        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1594      | 79.98%  |
| 0     | 300       | 15.05%  |
| 2     | 97        | 4.87%   |
| 3     | 2         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 985       | 34.98%  |
| Realtek Semiconductor                  | 965       | 34.27%  |
| Qualcomm Atheros                       | 324       | 11.51%  |
| Broadcom                               | 199       | 7.07%   |
| Marvell Technology Group               | 42        | 1.49%   |
| Ralink Technology                      | 29        | 1.03%   |
| Ralink                                 | 29        | 1.03%   |
| Nvidia                                 | 29        | 1.03%   |
| Samsung Electronics                    | 28        | 0.99%   |
| TP-Link                                | 17        | 0.6%    |
| MediaTek                               | 14        | 0.5%    |
| Xiaomi                                 | 12        | 0.43%   |
| Sierra Wireless                        | 12        | 0.43%   |
| Google                                 | 11        | 0.39%   |
| JMicron Technology                     | 10        | 0.36%   |
| Ericsson Business Mobile Networks      | 10        | 0.36%   |
| Edimax Technology                      | 10        | 0.36%   |
| Dell                                   | 10        | 0.36%   |
| D-Link System                          | 7         | 0.25%   |
| Huawei Technologies                    | 6         | 0.21%   |
| D-Link                                 | 6         | 0.21%   |
| Qualcomm                               | 5         | 0.18%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.14%   |
| OPPO Electronics                       | 4         | 0.14%   |
| NetGear                                | 4         | 0.14%   |
| Hewlett-Packard                        | 4         | 0.14%   |
| ASUSTek Computer                       | 4         | 0.14%   |
| Motorola PCS                           | 3         | 0.11%   |
| Aquantia                               | 3         | 0.11%   |
| T & A Mobile Phones                    | 2         | 0.07%   |
| Mellanox Technologies                  | 2         | 0.07%   |
| IMC Networks                           | 2         | 0.07%   |
| Belkin Components                      | 2         | 0.07%   |
| VIA Technologies                       | 1         | 0.04%   |
| Toshiba                                | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Raspberry Pi                           | 1         | 0.04%   |
| Qualcomm Technologies                  | 1         | 0.04%   |
| Qualcomm Atheros Communications        | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 723       | 21.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 130       | 3.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 118       | 3.47%   |
| Intel Wireless 8265 / 8275                                             | 69        | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 62        | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 59        | 1.74%   |
| Intel Wireless 7260                                                    | 59        | 1.74%   |
| Intel Ethernet Connection I217-LM                                      | 59        | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 56        | 1.65%   |
| Intel Wireless 7265                                                    | 55        | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 51        | 1.5%    |
| Intel Wireless 8260                                                    | 50        | 1.47%   |
| Intel I211 Gigabit Network Connection                                  | 42        | 1.24%   |
| Intel Wi-Fi 6 AX200                                                    | 40        | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                                  | 39        | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 37        | 1.09%   |
| Intel Wireless 3165                                                    | 30        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 29        | 0.85%   |
| Intel Ethernet Connection I219-LM                                      | 29        | 0.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 29        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 28        | 0.82%   |
| Nvidia MCP79 Ethernet                                                  | 26        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                   | 26        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 26        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                               | 26        | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 24        | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 24        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                  | 21        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 20        | 0.59%   |
| Intel Ethernet Controller I225-V                                       | 20        | 0.59%   |
| Intel Centrino Advanced-N 6200                                         | 19        | 0.56%   |
| Intel 82574L Gigabit Network Connection                                | 19        | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 18        | 0.53%   |
| Intel Ethernet Connection I218-LM                                      | 18        | 0.53%   |
| Intel 82579V Gigabit Network Connection                                | 18        | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 18        | 0.53%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 18        | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 17        | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                  | 16        | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 16        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 672       | 46.6%   |
| Qualcomm Atheros                | 268       | 18.59%  |
| Realtek Semiconductor           | 213       | 14.77%  |
| Broadcom                        | 150       | 10.4%   |
| Ralink Technology               | 29        | 2.01%   |
| Ralink                          | 29        | 2.01%   |
| TP-Link                         | 17        | 1.18%   |
| MediaTek                        | 11        | 0.76%   |
| Edimax Technology               | 10        | 0.69%   |
| Sierra Wireless                 | 9         | 0.62%   |
| D-Link                          | 6         | 0.42%   |
| Dell                            | 5         | 0.35%   |
| NetGear                         | 4         | 0.28%   |
| D-Link System                   | 4         | 0.28%   |
| ASUSTek Computer                | 4         | 0.28%   |
| IMC Networks                    | 2         | 0.14%   |
| Belkin Components               | 2         | 0.14%   |
| Qualcomm Technologies           | 1         | 0.07%   |
| Qualcomm Atheros Communications | 1         | 0.07%   |
| Mercucys                        | 1         | 0.07%   |
| BUFFALO                         | 1         | 0.07%   |
| Atheros                         | 1         | 0.07%   |
| Accton Technology               | 1         | 0.07%   |
| AboCom Systems                  | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 69        | 4.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 62        | 4.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 59        | 4.04%   |
| Intel Wireless 7260                                                     | 59        | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 56        | 3.83%   |
| Intel Wireless 7265                                                     | 55        | 3.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 51        | 3.49%   |
| Intel Wireless 8260                                                     | 50        | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 40        | 2.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 37        | 2.53%   |
| Intel Wireless 3165                                                     | 30        | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.98%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 29        | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 28        | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 1.64%   |
| Intel Centrino Advanced-N 6200                                          | 19        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 18        | 1.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 18        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 16        | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 1.03%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 15        | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 15        | 1.03%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 15        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.03%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 15        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 14        | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 14        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 14        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.89%   |
| Intel WiFi Link 5100                                                    | 13        | 0.89%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 12        | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 877       | 46.9%   |
| Intel                                  | 653       | 34.92%  |
| Qualcomm Atheros                       | 97        | 5.19%   |
| Broadcom                               | 80        | 4.28%   |
| Marvell Technology Group               | 42        | 2.25%   |
| Nvidia                                 | 29        | 1.55%   |
| Samsung Electronics                    | 28        | 1.5%    |
| Xiaomi                                 | 12        | 0.64%   |
| JMicron Technology                     | 10        | 0.53%   |
| Qualcomm                               | 5         | 0.27%   |
| Google                                 | 5         | 0.27%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.21%   |
| OPPO Electronics                       | 4         | 0.21%   |
| Huawei Technologies                    | 4         | 0.21%   |
| Motorola PCS                           | 3         | 0.16%   |
| MediaTek                               | 3         | 0.16%   |
| Aquantia                               | 3         | 0.16%   |
| T & A Mobile Phones                    | 2         | 0.11%   |
| D-Link System                          | 2         | 0.11%   |
| VIA Technologies                       | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Fujitsu Connected Technologies Limited | 1         | 0.05%   |
| Emulex                                 | 1         | 0.05%   |
| Chelsio Communications                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 723       | 38.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 130       | 6.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 118       | 6.24%   |
| Intel Ethernet Connection I217-LM                                      | 59        | 3.12%   |
| Intel I211 Gigabit Network Connection                                  | 42        | 2.22%   |
| Intel Ethernet Connection (2) I219-LM                                  | 39        | 2.06%   |
| Intel Ethernet Connection I219-LM                                      | 29        | 1.53%   |
| Nvidia MCP79 Ethernet                                                  | 26        | 1.38%   |
| Intel Ethernet Connection (7) I219-V                                   | 26        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                                   | 26        | 1.38%   |
| Intel 82577LM Gigabit Network Connection                               | 26        | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 21        | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 20        | 1.06%   |
| Intel Ethernet Controller I225-V                                       | 20        | 1.06%   |
| Intel 82574L Gigabit Network Connection                                | 19        | 1.01%   |
| Intel Ethernet Connection I218-LM                                      | 18        | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 18        | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 17        | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                                  | 16        | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 15        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 15        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 14        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 13        | 0.69%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 13        | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 13        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.63%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.63%   |
| Intel 82566MM Gigabit Network Connection                               | 12        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 10        | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 0.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 8         | 0.42%   |
| Intel I210 Gigabit Network Connection                                  | 8         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                  | 8         | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 8         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7         | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.37%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 7         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1797      | 56.56%  |
| WiFi     | 1335      | 42.02%  |
| Unknown  | 30        | 0.94%   |
| Modem    | 15        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1407      | 63.87%  |
| WiFi     | 784       | 35.59%  |
| Unknown  | 7         | 0.32%   |
| Modem    | 5         | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1100      | 55.87%  |
| 1     | 800       | 40.63%  |
| 3     | 39        | 1.98%   |
| 0     | 23        | 1.17%   |
| 4     | 6         | 0.3%    |
| 9     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1892      | 95.17%  |
| Yes  | 96        | 4.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 462       | 44.68%  |
| Realtek Semiconductor           | 87        | 8.41%   |
| Broadcom                        | 84        | 8.12%   |
| Apple                           | 84        | 8.12%   |
| Qualcomm Atheros Communications | 73        | 7.06%   |
| Cambridge Silicon Radio         | 66        | 6.38%   |
| IMC Networks                    | 38        | 3.68%   |
| Foxconn / Hon Hai               | 31        | 3%      |
| Lite-On Technology              | 24        | 2.32%   |
| ASUSTek Computer                | 22        | 2.13%   |
| Hewlett-Packard                 | 14        | 1.35%   |
| Dell                            | 14        | 1.35%   |
| Ralink                          | 8         | 0.77%   |
| TP-Link                         | 6         | 0.58%   |
| Alps Electric                   | 5         | 0.48%   |
| Integrated System Solution      | 3         | 0.29%   |
| Toshiba                         | 2         | 0.19%   |
| MediaTek                        | 2         | 0.19%   |
| Fujitsu                         | 2         | 0.19%   |
| Askey Computer                  | 2         | 0.19%   |
| Silicon Wave                    | 1         | 0.1%    |
| Primax Electronics              | 1         | 0.1%    |
| HTC (High Tech Computer)        | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 255       | 24.54%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 66        | 6.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 44        | 4.23%   |
| Intel AX201 Bluetooth                                       | 41        | 3.95%   |
| Intel AX200 Bluetooth                                       | 37        | 3.56%   |
| Apple Bluetooth Host Controller                             | 34        | 3.27%   |
| Intel Wireless-AC 3168 Bluetooth                            | 28        | 2.69%   |
| Realtek Bluetooth Adapter                                   | 27        | 2.6%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 23        | 2.21%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 22        | 2.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 20        | 1.92%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 20        | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 19        | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                              | 16        | 1.54%   |
| Apple Broadcom Built-in Bluetooth                           | 15        | 1.44%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 14        | 1.35%   |
| Intel AX210 Bluetooth                                       | 14        | 1.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 11        | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 10        | 0.96%   |
| Apple Built-in iSight (no firmware loaded)                  | 10        | 0.96%   |
| Realtek Bluetooth 4.2 Adapter                               | 9         | 0.87%   |
| Realtek Bluetooth 4.0 Adapter                               | 9         | 0.87%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 9         | 0.87%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 9         | 0.87%   |
| Ralink RT3290 Bluetooth                                     | 8         | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                            | 8         | 0.77%   |
| IMC Networks Realtek Bluetooth Adapter                      | 8         | 0.77%   |
| Realtek RTL8821A Bluetooth                                  | 7         | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 7         | 0.67%   |
| ASUS USB-BT500                                              | 7         | 0.67%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 6         | 0.58%   |
| Realtek RTL8723B Bluetooth                                  | 6         | 0.58%   |
| Dell DW375 Bluetooth Module                                 | 6         | 0.58%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 6         | 0.58%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 5         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 5         | 0.48%   |
| Intel AX211 Bluetooth                                       | 5         | 0.48%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 5         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 5         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1518      | 58.56%  |
| AMD                                          | 475       | 18.33%  |
| Nvidia                                       | 396       | 15.28%  |
| C-Media Electronics                          | 51        | 1.97%   |
| Texas Instruments                            | 20        | 0.77%   |
| GN Netcom                                    | 11        | 0.42%   |
| Creative Labs                                | 11        | 0.42%   |
| JMTek                                        | 7         | 0.27%   |
| Generalplus Technology                       | 7         | 0.27%   |
| SteelSeries ApS                              | 6         | 0.23%   |
| Creative Technology                          | 6         | 0.23%   |
| Logitech                                     | 5         | 0.19%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.15%   |
| Realtek Semiconductor                        | 4         | 0.15%   |
| Hewlett-Packard                              | 4         | 0.15%   |
| Yamaha                                       | 3         | 0.12%   |
| Kingston Technology                          | 3         | 0.12%   |
| Focusrite-Novation                           | 3         | 0.12%   |
| ASUSTek Computer                             | 3         | 0.12%   |
| XMOS                                         | 2         | 0.08%   |
| VIA Technologies                             | 2         | 0.08%   |
| Sony                                         | 2         | 0.08%   |
| Razer USA                                    | 2         | 0.08%   |
| Nektar                                       | 2         | 0.08%   |
| Micro Star International                     | 2         | 0.08%   |
| Google                                       | 2         | 0.08%   |
| GEMBIRD                                      | 2         | 0.08%   |
| Ensoniq                                      | 2         | 0.08%   |
| Corsair                                      | 2         | 0.08%   |
| Cambridge Silicon Radio                      | 2         | 0.08%   |
| BEHRINGER International                      | 2         | 0.08%   |
| Unknown                                      | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| ZOOM                                         | 1         | 0.04%   |
| Superlux digit                               | 1         | 0.04%   |
| Steinberg Soft-und Hardware                  | 1         | 0.04%   |
| RODE Microphones                             | 1         | 0.04%   |
| RME                                          | 1         | 0.04%   |
| Plantronics                                  | 1         | 0.04%   |
| Phison Electronics                           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 194       | 6.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 158       | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 156       | 5.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 119       | 3.87%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 118       | 3.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 92        | 2.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 91        | 2.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 80        | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 75        | 2.44%   |
| Intel 8 Series HD Audio Controller                                                                | 71        | 2.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 68        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 68        | 2.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 65        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 63        | 2.05%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 56        | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 55        | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 52        | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 51        | 1.66%   |
| Intel Broadwell-U Audio Controller                                                                | 48        | 1.56%   |
| Intel 200 Series PCH HD Audio                                                                     | 48        | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 45        | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 44        | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 44        | 1.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 39        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 37        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 30        | 0.98%   |
| Nvidia MCP79 High Definition Audio                                                                | 28        | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 27        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 25        | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 24        | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 24        | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 22        | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 22        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 21        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 21        | 0.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 20        | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 19        | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 0.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 452       | 19.34%  |
| SK hynix            | 339       | 14.51%  |
| Kingston            | 309       | 13.22%  |
| Unknown             | 236       | 10.1%   |
| Micron Technology   | 213       | 9.11%   |
| Crucial             | 133       | 5.69%   |
| Corsair             | 85        | 3.64%   |
| G.Skill             | 71        | 3.04%   |
| Unknown             | 65        | 2.78%   |
| Elpida              | 50        | 2.14%   |
| Ramaxel Technology  | 46        | 1.97%   |
| A-DATA Technology   | 46        | 1.97%   |
| Nanya Technology    | 39        | 1.67%   |
| Smart               | 27        | 1.16%   |
| Team                | 24        | 1.03%   |
| Transcend           | 20        | 0.86%   |
| Patriot             | 18        | 0.77%   |
| Apacer              | 12        | 0.51%   |
| Unknown (ABCD)      | 11        | 0.47%   |
| GOODRAM             | 10        | 0.43%   |
| Teikon              | 9         | 0.39%   |
| Avant               | 8         | 0.34%   |
| AMD                 | 7         | 0.3%    |
| Smart Brazil        | 6         | 0.26%   |
| PNY                 | 6         | 0.26%   |
| High Bridge         | 6         | 0.26%   |
| ASint Technology    | 6         | 0.26%   |
| Silicon Power       | 5         | 0.21%   |
| Atermiter           | 5         | 0.21%   |
| GeIL                | 4         | 0.17%   |
| SHARETRONIC         | 3         | 0.13%   |
| Kingmax             | 3         | 0.13%   |
| 48spaces            | 3         | 0.13%   |
| Unifosa             | 2         | 0.09%   |
| Toshiba             | 2         | 0.09%   |
| Sesame              | 2         | 0.09%   |
| Multilaser          | 2         | 0.09%   |
| Lexar               | 2         | 0.09%   |
| Lenovo              | 2         | 0.09%   |
| Kllisre             | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 65        | 2.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 28        | 1.11%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 26        | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 24        | 0.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 19        | 0.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 18        | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 15        | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 15        | 0.6%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 14        | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 14        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 12        | 0.48%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s  | 12        | 0.48%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 11        | 0.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s | 11        | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 11        | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s  | 11        | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s             | 10        | 0.4%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s            | 10        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s  | 10        | 0.4%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s  | 10        | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 10        | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                     | 9         | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 9         | 0.36%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s     | 9         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 9         | 0.36%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s  | 9         | 0.36%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s            | 8         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3                     | 8         | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 8         | 0.32%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s           | 8         | 0.32%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 8         | 0.32%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s  | 8         | 0.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 8         | 0.32%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s  | 8         | 0.32%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 8         | 0.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 8         | 0.32%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s | 7         | 0.28%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 7         | 0.28%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 7         | 0.28%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 7         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 912       | 46.87%  |
| DDR4    | 703       | 36.13%  |
| DDR2    | 159       | 8.17%   |
| Unknown | 76        | 3.91%   |
| SDRAM   | 30        | 1.54%   |
| LPDDR3  | 22        | 1.13%   |
| LPDDR4  | 19        | 0.98%   |
| DDR     | 10        | 0.51%   |
| DDR5    | 9         | 0.46%   |
| LPDDR5  | 3         | 0.15%   |
| DRAM    | 3         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1099      | 56.39%  |
| DIMM         | 773       | 39.66%  |
| Row Of Chips | 44        | 2.26%   |
| Chip         | 17        | 0.87%   |
| Unknown      | 9         | 0.46%   |
| FB-DIMM      | 4         | 0.21%   |
| RIMM         | 3         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 764       | 34.73%  |
| 8192  | 674       | 30.64%  |
| 2048  | 438       | 19.91%  |
| 16384 | 213       | 9.68%   |
| 1024  | 75        | 3.41%   |
| 32768 | 34        | 1.55%   |
| 512   | 2         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 552       | 26.09%  |
| 1333    | 278       | 13.14%  |
| 2400    | 205       | 9.69%   |
| 3200    | 198       | 9.36%   |
| 2667    | 167       | 7.89%   |
| 2133    | 142       | 6.71%   |
| 667     | 102       | 4.82%   |
| 800     | 79        | 3.73%   |
| 1067    | 70        | 3.31%   |
| 1334    | 67        | 3.17%   |
| Unknown | 51        | 2.41%   |
| 1867    | 38        | 1.8%    |
| 2666    | 28        | 1.32%   |
| 1066    | 27        | 1.28%   |
| 3600    | 15        | 0.71%   |
| 1866    | 14        | 0.66%   |
| 3000    | 11        | 0.52%   |
| 2933    | 9         | 0.43%   |
| 533     | 9         | 0.43%   |
| 400     | 8         | 0.38%   |
| 4800    | 7         | 0.33%   |
| 3733    | 5         | 0.24%   |
| 2048    | 5         | 0.24%   |
| 975     | 5         | 0.24%   |
| 6400    | 4         | 0.19%   |
| 333     | 4         | 0.19%   |
| 4267    | 3         | 0.14%   |
| 4000    | 2         | 0.09%   |
| 1639    | 2         | 0.09%   |
| 5600    | 1         | 0.05%   |
| 4400    | 1         | 0.05%   |
| 4266    | 1         | 0.05%   |
| 3400    | 1         | 0.05%   |
| 3333    | 1         | 0.05%   |
| 2866    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 1332    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 10        | 40%     |
| Hewlett-Packard       | 8         | 32%     |
| Lexmark International | 2         | 8%      |
| Seiko Epson           | 1         | 4%      |
| Samsung Electronics   | 1         | 4%      |
| Ricoh                 | 1         | 4%      |
| Prolific Technology   | 1         | 4%      |
| Kyocera               | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 3.85%   |
| Samsung ML-2010P Mono Laser Printer                                                                               | 1         | 3.85%   |
| Ricoh SP 112                                                                                                      | 1         | 3.85%   |
| Prolific PL2305 Parallel Port                                                                                     | 1         | 3.85%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 3.85%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 3.85%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 3.85%   |
| HP LaserJet P3005                                                                                                 | 1         | 3.85%   |
| HP LaserJet 3390                                                                                                  | 1         | 3.85%   |
| HP LaserJet 2200                                                                                                  | 1         | 3.85%   |
| HP LaserJet 1200                                                                                                  | 1         | 3.85%   |
| HP LaserJet 1020                                                                                                  | 1         | 3.85%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 3.85%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 3.85%   |
| HP DeskJet 5850c                                                                                                  | 1         | 3.85%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 3.85%   |
| Brother MFC-L2685DW                                                                                               | 1         | 3.85%   |
| Brother MFC-J200                                                                                                  | 1         | 3.85%   |
| Brother MFC-7360N                                                                                                 | 1         | 3.85%   |
| Brother HL-L3270CDW series                                                                                        | 1         | 3.85%   |
| Brother HL-L2310D series                                                                                          | 1         | 3.85%   |
| Brother HL-L2300D series                                                                                          | 1         | 3.85%   |
| Brother HL-1430 Laser Printer                                                                                     | 1         | 3.85%   |
| Brother DCP-J152W                                                                                                 | 1         | 3.85%   |
| Brother DCP-J100                                                                                                  | 1         | 3.85%   |
| Brother DCP-9015CDW                                                                                               | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 8         | 80%     |
| Seiko Epson | 2         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 20%     |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 10%     |
| Seiko Epson PX-501A [Stylus NX400]                                                  | 1         | 10%     |
| Canon CanoScan N650U/N656U                                                          | 1         | 10%     |
| Canon CanoScan N1240U/LiDE 30                                                       | 1         | 10%     |
| Canon CanoScan LiDE 700F                                                            | 1         | 10%     |
| Canon CanoScan LiDE 220                                                             | 1         | 10%     |
| Canon CanoScan LiDE 120                                                             | 1         | 10%     |
| Canon CanoScan LiDE 100                                                             | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 214       | 24.88%  |
| Bison Electronics                      | 83        | 9.65%   |
| Microdia                               | 72        | 8.37%   |
| IMC Networks                           | 70        | 8.14%   |
| Realtek Semiconductor                  | 68        | 7.91%   |
| Sunplus Innovation Technology          | 48        | 5.58%   |
| Suyin                                  | 30        | 3.49%   |
| Logitech                               | 28        | 3.26%   |
| Syntek                                 | 25        | 2.91%   |
| Apple                                  | 25        | 2.91%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 2.79%   |
| Quanta                                 | 23        | 2.67%   |
| Lite-On Technology                     | 22        | 2.56%   |
| Alcor Micro                            | 17        | 1.98%   |
| Z-Star Microelectronics                | 14        | 1.63%   |
| Silicon Motion                         | 13        | 1.51%   |
| Lenovo                                 | 13        | 1.51%   |
| Luxvisions Innotech Limited            | 9         | 1.05%   |
| ALi                                    | 7         | 0.81%   |
| Importek                               | 6         | 0.7%    |
| GEMBIRD                                | 4         | 0.47%   |
| ARC International                      | 4         | 0.47%   |
| Supreme Electronics                    | 3         | 0.35%   |
| Ricoh                                  | 3         | 0.35%   |
| Intel                                  | 3         | 0.35%   |
| Arkmicro Technologies                  | 3         | 0.35%   |
| Primax Electronics                     | 2         | 0.23%   |
| Jiangxi Shinetech Optical              | 2         | 0.23%   |
| Hewlett-Packard                        | 2         | 0.23%   |
| Genesys Logic                          | 2         | 0.23%   |
| Generalplus Technology                 | 2         | 0.23%   |
| DigiTech                               | 2         | 0.23%   |
| Creative Technology                    | 2         | 0.23%   |
| Y Media                                | 1         | 0.12%   |
| ValueHD                                | 1         | 0.12%   |
| USB Camera                             | 1         | 0.12%   |
| Unknown                                | 1         | 0.12%   |
| Trust                                  | 1         | 0.12%   |
| Tripath Technology                     | 1         | 0.12%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 52        | 6.01%   |
| Bison Integrated Camera                   | 28        | 3.24%   |
| Microdia Integrated_Webcam_HD             | 22        | 2.54%   |
| Sunplus Integrated_Webcam_HD              | 17        | 1.97%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 15        | 1.73%   |
| Realtek USB 2.0 PC Camera                 | 14        | 1.62%   |
| Realtek Integrated_Webcam_HD              | 14        | 1.62%   |
| Lite-On Integrated Camera                 | 14        | 1.62%   |
| Bison Lenovo EasyCamera                   | 14        | 1.62%   |
| Chicony HD WebCam                         | 13        | 1.5%    |
| IMC Networks Integrated Camera            | 12        | 1.39%   |
| Microdia Integrated Webcam                | 11        | 1.27%   |
| IMC Networks Realtek PC Camera            | 11        | 1.27%   |
| Apple FaceTime HD Camera                  | 11        | 1.27%   |
| Syntek Lenovo EasyCamera                  | 10        | 1.16%   |
| Realtek USB Camera                        | 10        | 1.16%   |
| Apple FaceTime HD Camera (Built-in)       | 10        | 1.16%   |
| Chicony FJ Camera                         | 9         | 1.04%   |
| Logitech Webcam C270                      | 8         | 0.92%   |
| Chicony Lenovo EasyCamera                 | 8         | 0.92%   |
| Chicony HP HD Webcam [Fixed]              | 8         | 0.92%   |
| Bison ThinkPad Integrated Camera          | 8         | 0.92%   |
| Syntek EasyCamera                         | 7         | 0.81%   |
| Microdia Dell Laptop Integrated Webcam HD | 7         | 0.81%   |
| IMC Networks EasyCamera                   | 7         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam              | 7         | 0.81%   |
| Bison HD Webcam                           | 7         | 0.81%   |
| Suyin Integrated_Webcam_HD                | 6         | 0.69%   |
| Quanta HP TrueVision HD Camera            | 6         | 0.69%   |
| Microdia USB  Live camera                 | 6         | 0.69%   |
| Lenovo Integrated Webcam                  | 6         | 0.69%   |
| IMC Networks UVC VGA Webcam               | 6         | 0.69%   |
| IMC Networks USB2.0 HD UVC WebCam         | 6         | 0.69%   |
| Chicony USB 2.0 Camera                    | 6         | 0.69%   |
| Chicony Realtek DMFT RGB                  | 6         | 0.69%   |
| Bison SunplusIT Integrated Camera         | 6         | 0.69%   |
| Syntek Integrated Camera                  | 5         | 0.58%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 5         | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD      | 5         | 0.58%   |
| Logitech HD Pro Webcam C920               | 5         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 80        | 43.96%  |
| AuthenTec                  | 26        | 14.29%  |
| Upek                       | 22        | 12.09%  |
| Synaptics                  | 15        | 8.24%   |
| STMicroelectronics         | 11        | 6.04%   |
| Elan Microelectronics      | 10        | 5.49%   |
| Broadcom                   | 8         | 4.4%    |
| Shenzhen Goodix Technology | 4         | 2.2%    |
| LighTuning Technology      | 4         | 2.2%    |
| FocalTech Systems          | 1         | 0.55%   |
| Fingerprint Cards          | 1         | 0.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 20        | 10.99%  |
| Validity Sensors VFS495 Fingerprint Reader                                        | 16        | 8.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 16        | 8.79%   |
| Validity Sensors Synaptics WBDI                                                   | 13        | 7.14%   |
| STMicroelectronics Fingerprint Reader                                             | 11        | 6.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 10        | 5.49%   |
| Elan Fingerprint Sensor                                                           | 9         | 4.95%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor      | 8         | 4.4%    |
| AuthenTec AES2810                                                                 | 6         | 3.3%    |
| AuthenTec AES1600                                                                 | 6         | 3.3%    |
| Validity Sensors Fingerprint scanner                                              | 5         | 2.75%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                                 | 5         | 2.75%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 5         | 2.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 4         | 2.2%    |
| Validity Sensors VFS491                                                           | 4         | 2.2%    |
| Synaptics WBDI Fingerprint Reader USB 086                                         | 4         | 2.2%    |
| AuthenTec AES1660                                                                 | 4         | 2.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                        | 3         | 1.65%   |
| Shenzhen Goodix Fingerprint Reader                                                | 3         | 1.65%   |
| AuthenTec AES2660                                                                 | 3         | 1.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                        | 2         | 1.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                        | 2         | 1.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                         | 2         | 1.1%    |
| Upek TCS5B Fingerprint sensor                                                     | 2         | 1.1%    |
| Synaptics WBDI                                                                    | 2         | 1.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                                  | 2         | 1.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 2         | 1.1%    |
| Validity Sensors VFS301 Fingerprint Reader                                        | 1         | 0.55%   |
| Validity Sensors VFS Fingerprint sensor                                           | 1         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint        | 1         | 0.55%   |
| Synaptics UWP WBDI Device                                                         | 1         | 0.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                                  | 1         | 0.55%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 1         | 0.55%   |
| LighTuning Fingerprint Sensor                                                     | 1         | 0.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                         | 1         | 0.55%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 0.55%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 0.55%   |
| Elan WBF Fingerprint Sensor                                                       | 1         | 0.55%   |
| AuthenTec AES2550 Fingerprint Sensor                                              | 1         | 0.55%   |
| AuthenTec AES1660 Fingerprint Sensor                                              | 1         | 0.55%   |

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
| 1     | 812       | 40.58%  |
| 0     | 496       | 24.79%  |
| 2     | 467       | 23.34%  |
| 3     | 166       | 8.3%    |
| 4     | 48        | 2.4%    |
| 5     | 10        | 0.5%    |
| 6     | 2         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1241      | 53.7%   |
| Net/wireless             | 306       | 13.24%  |
| Card reader              | 244       | 10.56%  |
| Bluetooth                | 184       | 7.96%   |
| Fingerprint reader       | 179       | 7.75%   |
| Sound                    | 60        | 2.6%    |
| Firewire controller      | 29        | 1.25%   |
| Network                  | 24        | 1.04%   |
| Storage                  | 19        | 0.82%   |
| Net/ethernet             | 14        | 0.61%   |
| Storage/raid             | 5         | 0.22%   |
| Dvb card                 | 5         | 0.22%   |
| Storage/nvme             | 1         | 0.04%   |

