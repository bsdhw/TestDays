BSD in Italy - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for BSD in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 473

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 0F0XJ6 A00                  | Server      | [c049ffad9d](https://bsd-hardware.info/?probe=c049ffad9d) | May 06, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [2656d00123](https://bsd-hardware.info/?probe=2656d00123) | May 03, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [3e01e5ffbf](https://bsd-hardware.info/?probe=3e01e5ffbf) | May 03, 2024 |
| Quantum en... | HackBoard 2                 | Desktop     | [a7b0ea1eca](https://bsd-hardware.info/?probe=a7b0ea1eca) | Apr 28, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [a696ddada6](https://bsd-hardware.info/?probe=a696ddada6) | Apr 20, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [67e558c746](https://bsd-hardware.info/?probe=67e558c746) | Apr 16, 2024 |
| PC Engines    | apu1                        | Desktop     | [cceec3e9bd](https://bsd-hardware.info/?probe=cceec3e9bd) | Apr 14, 2024 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [962837890c](https://bsd-hardware.info/?probe=962837890c) | Apr 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [a9c935db85](https://bsd-hardware.info/?probe=a9c935db85) | Apr 09, 2024 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [be1566e796](https://bsd-hardware.info/?probe=be1566e796) | Apr 07, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [426677818b](https://bsd-hardware.info/?probe=426677818b) | Apr 07, 2024 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [574ff40323](https://bsd-hardware.info/?probe=574ff40323) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [1af73d4146](https://bsd-hardware.info/?probe=1af73d4146) | Apr 04, 2024 |
| HPE           | ProLiant DL380 Gen10        | Server      | [d566684a72](https://bsd-hardware.info/?probe=d566684a72) | Apr 02, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [b9c567bdde](https://bsd-hardware.info/?probe=b9c567bdde) | Mar 21, 2024 |
| HP            | 2B5E                        | Desktop     | [35b1572267](https://bsd-hardware.info/?probe=35b1572267) | Mar 17, 2024 |
| PC Engines    | APU2                        | Desktop     | [9cd0068a06](https://bsd-hardware.info/?probe=9cd0068a06) | Mar 13, 2024 |
| PC Engines    | APU2                        | Desktop     | [891b69ea9c](https://bsd-hardware.info/?probe=891b69ea9c) | Mar 13, 2024 |
| BESSTAR Te... | VB9                         | All in one  | [0fdf31a212](https://bsd-hardware.info/?probe=0fdf31a212) | Feb 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [7f49c436eb](https://bsd-hardware.info/?probe=7f49c436eb) | Feb 27, 2024 |
| PC Engines    | APU2                        | Desktop     | [bd47726af7](https://bsd-hardware.info/?probe=bd47726af7) | Feb 25, 2024 |
| Intel(R) C... | NUC10i3FNH                  | Mini pc     | [924461c416](https://bsd-hardware.info/?probe=924461c416) | Feb 22, 2024 |
| Intel         | NUC7i3BNHX                  | Mini pc     | [cf452e34d1](https://bsd-hardware.info/?probe=cf452e34d1) | Feb 20, 2024 |
| Fujitsu       | D3313-E1 S26361-D3313-E1    | Desktop     | [8f0a5d2d0a](https://bsd-hardware.info/?probe=8f0a5d2d0a) | Feb 16, 2024 |
| PC Engines    | APU2                        | Desktop     | [df18317865](https://bsd-hardware.info/?probe=df18317865) | Feb 14, 2024 |
| PC Engines    | APU2                        | Desktop     | [251265d29e](https://bsd-hardware.info/?probe=251265d29e) | Feb 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [19e59c140c](https://bsd-hardware.info/?probe=19e59c140c) | Feb 09, 2024 |
| HP            | ProLiant DL380 G4           | Server      | [1d58307095](https://bsd-hardware.info/?probe=1d58307095) | Feb 09, 2024 |
| PC Engines    | APU2                        | Desktop     | [6d52e4dad5](https://bsd-hardware.info/?probe=6d52e4dad5) | Feb 07, 2024 |
| ASUSTek       | K52F                        | Notebook    | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| ASUSTek       | K52F                        | Notebook    | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| PC Engines    | APU2                        | Desktop     | [591ead54fc](https://bsd-hardware.info/?probe=591ead54fc) | Jan 30, 2024 |
| Unknown       | Unknown                     | Desktop     | [f2406d4352](https://bsd-hardware.info/?probe=f2406d4352) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [4ff002fe77](https://bsd-hardware.info/?probe=4ff002fe77) | Jan 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [de7d99595c](https://bsd-hardware.info/?probe=de7d99595c) | Jan 23, 2024 |
| ASUSTek       | X555LAB                     | Notebook    | [c396fcc8d9](https://bsd-hardware.info/?probe=c396fcc8d9) | Jan 22, 2024 |
| HP            | 1494                        | Desktop     | [45c45d492a](https://bsd-hardware.info/?probe=45c45d492a) | Jan 18, 2024 |
| HP            | Mini 210-1000               | Notebook    | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| HP            | Mini 210-1000               | Notebook    | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e0d9f347e9](https://bsd-hardware.info/?probe=e0d9f347e9) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [df4f6b185b](https://bsd-hardware.info/?probe=df4f6b185b) | Jan 09, 2024 |
| PC Engines    | APU2                        | Desktop     | [b08ca32731](https://bsd-hardware.info/?probe=b08ca32731) | Jan 07, 2024 |
| Samsung       | R510/P510                   | Notebook    | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [1952b64d3d](https://bsd-hardware.info/?probe=1952b64d3d) | Dec 28, 2023 |
| Protectli     | VP2420                      | Desktop     | [5368ee9cc8](https://bsd-hardware.info/?probe=5368ee9cc8) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [89b65e7036](https://bsd-hardware.info/?probe=89b65e7036) | Dec 23, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [2556fa3be1](https://bsd-hardware.info/?probe=2556fa3be1) | Dec 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [7b24999fbb](https://bsd-hardware.info/?probe=7b24999fbb) | Dec 22, 2023 |
| Protectli     | VP2420                      | Desktop     | [74c1ede426](https://bsd-hardware.info/?probe=74c1ede426) | Dec 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [426e43d7f2](https://bsd-hardware.info/?probe=426e43d7f2) | Dec 08, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4a74f06217](https://bsd-hardware.info/?probe=4a74f06217) | Dec 06, 2023 |
| PC Engines    | APU2                        | Desktop     | [6bbcef15d3](https://bsd-hardware.info/?probe=6bbcef15d3) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca548efdec](https://bsd-hardware.info/?probe=ca548efdec) | Dec 04, 2023 |
| PC Engines    | APU2                        | Desktop     | [46fa133d51](https://bsd-hardware.info/?probe=46fa133d51) | Dec 04, 2023 |
| HP            | 1825                        | Desktop     | [3edf79b1ba](https://bsd-hardware.info/?probe=3edf79b1ba) | Dec 03, 2023 |
| Lenovo        | ThinkPad X280 20KES5M300    | Notebook    | [28d67ab74a](https://bsd-hardware.info/?probe=28d67ab74a) | Dec 02, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [5631aa6b68](https://bsd-hardware.info/?probe=5631aa6b68) | Nov 27, 2023 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [3997370fc6](https://bsd-hardware.info/?probe=3997370fc6) | Nov 25, 2023 |
| YANYU         | ITX-M9F VER:1.3 baytrail    | Desktop     | [c9e7bbc120](https://bsd-hardware.info/?probe=c9e7bbc120) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | Desktop     | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e26144a9ce](https://bsd-hardware.info/?probe=e26144a9ce) | Nov 23, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [17d29b1055](https://bsd-hardware.info/?probe=17d29b1055) | Nov 19, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [98fac2d452](https://bsd-hardware.info/?probe=98fac2d452) | Nov 15, 2023 |
| YENTEK        | D41SL                       | Desktop     | [8cb79449c8](https://bsd-hardware.info/?probe=8cb79449c8) | Nov 10, 2023 |
| BESSTAR Te... | VB9                         | All in one  | [e750d16fb3](https://bsd-hardware.info/?probe=e750d16fb3) | Nov 05, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | Desktop     | [018805dc37](https://bsd-hardware.info/?probe=018805dc37) | Nov 03, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [7077dec0a1](https://bsd-hardware.info/?probe=7077dec0a1) | Nov 01, 2023 |
| YANYU         | M9F baytrail                | Desktop     | [746772e77b](https://bsd-hardware.info/?probe=746772e77b) | Oct 30, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [bb195148f7](https://bsd-hardware.info/?probe=bb195148f7) | Oct 29, 2023 |
| Dell          | PowerEdge T110 II           | Desktop     | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| YANYU         | M9F baytrail                | Desktop     | [f9e833a5f9](https://bsd-hardware.info/?probe=f9e833a5f9) | Oct 27, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [8af7ab0e4d](https://bsd-hardware.info/?probe=8af7ab0e4d) | Oct 27, 2023 |
| Toshiba       | Unknown                     | Notebook    | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| HP            | 213D A01                    | Desktop     | [6a023bfe9f](https://bsd-hardware.info/?probe=6a023bfe9f) | Oct 14, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fbc9fe11b1](https://bsd-hardware.info/?probe=fbc9fe11b1) | Oct 13, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [c823cbad48](https://bsd-hardware.info/?probe=c823cbad48) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [1bb43f3258](https://bsd-hardware.info/?probe=1bb43f3258) | Oct 10, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [9e99e33fa3](https://bsd-hardware.info/?probe=9e99e33fa3) | Oct 09, 2023 |
| Dell          | Latitude D830               | Notebook    | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [08dab02121](https://bsd-hardware.info/?probe=08dab02121) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [af88ff7c18](https://bsd-hardware.info/?probe=af88ff7c18) | Oct 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9190b85f99](https://bsd-hardware.info/?probe=9190b85f99) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [914de9ed88](https://bsd-hardware.info/?probe=914de9ed88) | Oct 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ba9a892240](https://bsd-hardware.info/?probe=ba9a892240) | Oct 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [002103bb3a](https://bsd-hardware.info/?probe=002103bb3a) | Oct 02, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [dffc2e116d](https://bsd-hardware.info/?probe=dffc2e116d) | Sep 30, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [29bcb3ca3e](https://bsd-hardware.info/?probe=29bcb3ca3e) | Sep 29, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [8d5549809c](https://bsd-hardware.info/?probe=8d5549809c) | Sep 27, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Bochs         | Unknown                     | Desktop     | [65f7da4601](https://bsd-hardware.info/?probe=65f7da4601) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [67d1f42d7c](https://bsd-hardware.info/?probe=67d1f42d7c) | Sep 13, 2023 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [f509d12cea](https://bsd-hardware.info/?probe=f509d12cea) | Aug 29, 2023 |
| PC Engines    | APU2                        | Desktop     | [3d3b16c0cf](https://bsd-hardware.info/?probe=3d3b16c0cf) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Protectli     | FW4B                        | Desktop     | [4b358b0106](https://bsd-hardware.info/?probe=4b358b0106) | Aug 24, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3ac93594a2](https://bsd-hardware.info/?probe=3ac93594a2) | Aug 20, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [3b430afdad](https://bsd-hardware.info/?probe=3b430afdad) | Aug 18, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [66449212d1](https://bsd-hardware.info/?probe=66449212d1) | Aug 18, 2023 |
| BESSTAR Te... | IB9                         | Desktop     | [c9f5ede507](https://bsd-hardware.info/?probe=c9f5ede507) | Aug 18, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [664ee85747](https://bsd-hardware.info/?probe=664ee85747) | Aug 15, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [46a6b88b33](https://bsd-hardware.info/?probe=46a6b88b33) | Aug 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f0398bfb85](https://bsd-hardware.info/?probe=f0398bfb85) | Aug 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [28f0d503fd](https://bsd-hardware.info/?probe=28f0d503fd) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [6238337b24](https://bsd-hardware.info/?probe=6238337b24) | Aug 07, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [155f885c95](https://bsd-hardware.info/?probe=155f885c95) | Aug 01, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [0e10359af8](https://bsd-hardware.info/?probe=0e10359af8) | Jul 29, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [a3624fdcfc](https://bsd-hardware.info/?probe=a3624fdcfc) | Jul 24, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [a441b76fb8](https://bsd-hardware.info/?probe=a441b76fb8) | Jul 20, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [57b4bfc1bf](https://bsd-hardware.info/?probe=57b4bfc1bf) | Jul 17, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [0f55bad1af](https://bsd-hardware.info/?probe=0f55bad1af) | Jul 08, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [48fcb6e4ab](https://bsd-hardware.info/?probe=48fcb6e4ab) | Jul 05, 2023 |
| Protectli     | FW4B                        | Desktop     | [a3cf476fe8](https://bsd-hardware.info/?probe=a3cf476fe8) | Jul 03, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [c30f91d5cc](https://bsd-hardware.info/?probe=c30f91d5cc) | Jul 01, 2023 |
| ASUSTek       | N3700T                      | Desktop     | [16b73b05ef](https://bsd-hardware.info/?probe=16b73b05ef) | Jun 26, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| ASUSTek       | 1015P                       | Notebook    | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [229e573059](https://bsd-hardware.info/?probe=229e573059) | Jun 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [9d271bc94c](https://bsd-hardware.info/?probe=9d271bc94c) | Jun 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fe412825f2](https://bsd-hardware.info/?probe=fe412825f2) | Jun 10, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d08f309c4c](https://bsd-hardware.info/?probe=d08f309c4c) | May 26, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [9160d45441](https://bsd-hardware.info/?probe=9160d45441) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b5ec8c5f4](https://bsd-hardware.info/?probe=8b5ec8c5f4) | May 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b26eac2277](https://bsd-hardware.info/?probe=b26eac2277) | May 13, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [1dac5a7bb2](https://bsd-hardware.info/?probe=1dac5a7bb2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [bf8246ecb5](https://bsd-hardware.info/?probe=bf8246ecb5) | May 11, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [5c6c169e73](https://bsd-hardware.info/?probe=5c6c169e73) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d572f5ff91](https://bsd-hardware.info/?probe=d572f5ff91) | May 01, 2023 |
| Unknown       | HX90                        | Desktop     | [b3300c45bc](https://bsd-hardware.info/?probe=b3300c45bc) | May 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1774da050f](https://bsd-hardware.info/?probe=1774da050f) | Apr 29, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [0471af8c22](https://bsd-hardware.info/?probe=0471af8c22) | Apr 24, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [30062ec670](https://bsd-hardware.info/?probe=30062ec670) | Apr 23, 2023 |
| HP            | 82B4                        | Desktop     | [9ec1e6d6f4](https://bsd-hardware.info/?probe=9ec1e6d6f4) | Apr 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [03dd920110](https://bsd-hardware.info/?probe=03dd920110) | Apr 22, 2023 |
| Sophos        | UTM                         | Firewall    | [85bf260703](https://bsd-hardware.info/?probe=85bf260703) | Apr 21, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [d343800c53](https://bsd-hardware.info/?probe=d343800c53) | Apr 16, 2023 |
| PC Engines    | apu4                        | Desktop     | [9217e1982f](https://bsd-hardware.info/?probe=9217e1982f) | Apr 14, 2023 |
| ASRock        | G31M-S                      | Desktop     | [fed4a42c32](https://bsd-hardware.info/?probe=fed4a42c32) | Apr 08, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4596f78aee](https://bsd-hardware.info/?probe=4596f78aee) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [5168183b15](https://bsd-hardware.info/?probe=5168183b15) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [45f590d129](https://bsd-hardware.info/?probe=45f590d129) | Apr 04, 2023 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [ab0643727f](https://bsd-hardware.info/?probe=ab0643727f) | Apr 02, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [fb6477d43e](https://bsd-hardware.info/?probe=fb6477d43e) | Mar 31, 2023 |
| Dell          | 0M877N A01                  | Server      | [dabe853e69](https://bsd-hardware.info/?probe=dabe853e69) | Mar 30, 2023 |
| LG Electro... | COLUMBIA                    | Notebook    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| YANYU         | H17SL                       | Desktop     | [0f9829ebe4](https://bsd-hardware.info/?probe=0f9829ebe4) | Mar 26, 2023 |
| ASUSTek       | F1A55                       | Desktop     | [91ad5bab75](https://bsd-hardware.info/?probe=91ad5bab75) | Mar 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a7e98f9a10](https://bsd-hardware.info/?probe=a7e98f9a10) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cbbeb5c41c](https://bsd-hardware.info/?probe=cbbeb5c41c) | Mar 22, 2023 |
| HP            | 8054                        | Desktop     | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Intel         | S1200RP_SE                  | Notebook    | [5ae9400f0b](https://bsd-hardware.info/?probe=5ae9400f0b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| SiComputer    | Embedded                    | Soc         | [9d6aa61a5c](https://bsd-hardware.info/?probe=9d6aa61a5c) | Mar 17, 2023 |
| YANYU         | H17SL                       | Desktop     | [37a549331f](https://bsd-hardware.info/?probe=37a549331f) | Mar 14, 2023 |
| MSI           | 0A48                        | Desktop     | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| AZW           | U59                         | Desktop     | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [a3f921de9a](https://bsd-hardware.info/?probe=a3f921de9a) | Mar 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [2050921c3d](https://bsd-hardware.info/?probe=2050921c3d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Gigabyte      | B450M K                     | Desktop     | [0d0433284e](https://bsd-hardware.info/?probe=0d0433284e) | Mar 11, 2023 |
| NF692         | 1.0                         | Desktop     | [16fa0b0102](https://bsd-hardware.info/?probe=16fa0b0102) | Mar 11, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6729453203](https://bsd-hardware.info/?probe=6729453203) | Mar 09, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [6dee276a48](https://bsd-hardware.info/?probe=6dee276a48) | Mar 07, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [77a58527da](https://bsd-hardware.info/?probe=77a58527da) | Mar 01, 2023 |
| Stonesoft     | FW-315-C1                   | Desktop     | [e8a2206ad2](https://bsd-hardware.info/?probe=e8a2206ad2) | Feb 28, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | Notebook    | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Intel         | JSL MRD                     | Desktop     | [1587ea95da](https://bsd-hardware.info/?probe=1587ea95da) | Feb 18, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [df7f4524d7](https://bsd-hardware.info/?probe=df7f4524d7) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [7f9208dc11](https://bsd-hardware.info/?probe=7f9208dc11) | Feb 06, 2023 |
| HP            | Mini 210-1000               | Notebook    | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| HP            | 213D A01                    | Desktop     | [659939cc8b](https://bsd-hardware.info/?probe=659939cc8b) | Jan 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [aa940792fc](https://bsd-hardware.info/?probe=aa940792fc) | Jan 25, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRO A520M-C                 | Desktop     | [bebcd1a008](https://bsd-hardware.info/?probe=bebcd1a008) | Jan 20, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [c1e1ba5558](https://bsd-hardware.info/?probe=c1e1ba5558) | Jan 16, 2023 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [942d966486](https://bsd-hardware.info/?probe=942d966486) | Jan 11, 2023 |
| Sophos        | UTM                         | Firewall    | [6379cce732](https://bsd-hardware.info/?probe=6379cce732) | Jan 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2265227a5c](https://bsd-hardware.info/?probe=2265227a5c) | Dec 26, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| MSI           | MS-7922                     | Desktop     | [95dbf4f7a8](https://bsd-hardware.info/?probe=95dbf4f7a8) | Dec 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [511f2a6d16](https://bsd-hardware.info/?probe=511f2a6d16) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Gigabyte      | N3160ND3V                   | Desktop     | [c84bedc821](https://bsd-hardware.info/?probe=c84bedc821) | Dec 15, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [435807287e](https://bsd-hardware.info/?probe=435807287e) | Dec 15, 2022 |
| AZW           | U59                         | Desktop     | [9b22c68e98](https://bsd-hardware.info/?probe=9b22c68e98) | Dec 13, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [6860cd72f8](https://bsd-hardware.info/?probe=6860cd72f8) | Nov 26, 2022 |
| ASUSTek       | P11C-X Series               | Desktop     | [cfdb06e761](https://bsd-hardware.info/?probe=cfdb06e761) | Nov 26, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [2aeadb4dfc](https://bsd-hardware.info/?probe=2aeadb4dfc) | Nov 14, 2022 |
| Dell          | 0VD5HY A00                  | Desktop     | [1a0df311e3](https://bsd-hardware.info/?probe=1a0df311e3) | Nov 07, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [72d95a4938](https://bsd-hardware.info/?probe=72d95a4938) | Nov 03, 2022 |
| Acer          | Veriton X2610G              | Desktop     | [e4289c3f15](https://bsd-hardware.info/?probe=e4289c3f15) | Oct 24, 2022 |
| Sophos        | UTM                         | Firewall    | [6a4c00a973](https://bsd-hardware.info/?probe=6a4c00a973) | Oct 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [1188b56e14](https://bsd-hardware.info/?probe=1188b56e14) | Oct 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [915c66f8bd](https://bsd-hardware.info/?probe=915c66f8bd) | Oct 19, 2022 |
| PC Engines    | apu4                        | Desktop     | [20cfd8a3c8](https://bsd-hardware.info/?probe=20cfd8a3c8) | Oct 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [c57cc3a923](https://bsd-hardware.info/?probe=c57cc3a923) | Oct 17, 2022 |
| ASRock        | Q1900M                      | Desktop     | [7d0380e2d0](https://bsd-hardware.info/?probe=7d0380e2d0) | Oct 15, 2022 |
| Sophos        | UTM                         | Firewall    | [364e007b1c](https://bsd-hardware.info/?probe=364e007b1c) | Oct 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [d802705c1d](https://bsd-hardware.info/?probe=d802705c1d) | Oct 10, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [a28ea59f1f](https://bsd-hardware.info/?probe=a28ea59f1f) | Oct 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdabafdcb1](https://bsd-hardware.info/?probe=bdabafdcb1) | Oct 01, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [81722a937a](https://bsd-hardware.info/?probe=81722a937a) | Sep 13, 2022 |
| HP            | 8648                        | Desktop     | [e7e610794c](https://bsd-hardware.info/?probe=e7e610794c) | Sep 12, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b54e6663f9](https://bsd-hardware.info/?probe=b54e6663f9) | Sep 10, 2022 |
| Intel         | J1900                       | Desktop     | [a95dd12c65](https://bsd-hardware.info/?probe=a95dd12c65) | Sep 06, 2022 |
| HP            | 1496                        | Desktop     | [7cd97bd330](https://bsd-hardware.info/?probe=7cd97bd330) | Sep 05, 2022 |
| PC Engines    | APU2                        | Desktop     | [d9216cb730](https://bsd-hardware.info/?probe=d9216cb730) | Sep 05, 2022 |
| HP            | 1496                        | Desktop     | [94e8713f6d](https://bsd-hardware.info/?probe=94e8713f6d) | Sep 03, 2022 |
| Dell          | 0TY179 A05                  | Server      | [482bca3952](https://bsd-hardware.info/?probe=482bca3952) | Sep 01, 2022 |
| HP            | 1496                        | Desktop     | [1567aa1c21](https://bsd-hardware.info/?probe=1567aa1c21) | Sep 01, 2022 |
| Unknown       | HX90                        | Desktop     | [568468e95b](https://bsd-hardware.info/?probe=568468e95b) | Sep 01, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2349014a6c](https://bsd-hardware.info/?probe=2349014a6c) | Aug 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [b3d60c2790](https://bsd-hardware.info/?probe=b3d60c2790) | Aug 22, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [02e11159f5](https://bsd-hardware.info/?probe=02e11159f5) | Aug 18, 2022 |
| Fujitsu       | D3373-B1 S26361-D3373-B1... | Server      | [676fd4e9b4](https://bsd-hardware.info/?probe=676fd4e9b4) | Aug 17, 2022 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [c03da8657e](https://bsd-hardware.info/?probe=c03da8657e) | Aug 17, 2022 |
| PC Engines    | APU2                        | Desktop     | [028dc7aa20](https://bsd-hardware.info/?probe=028dc7aa20) | Aug 17, 2022 |
| BESSTAR Te... | VB9                         | All in one  | [ec5b4884a7](https://bsd-hardware.info/?probe=ec5b4884a7) | Aug 13, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [1d4ccaabda](https://bsd-hardware.info/?probe=1d4ccaabda) | Aug 13, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [17dc06ed68](https://bsd-hardware.info/?probe=17dc06ed68) | Aug 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [af3d9689c2](https://bsd-hardware.info/?probe=af3d9689c2) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5049417b7b](https://bsd-hardware.info/?probe=5049417b7b) | Aug 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c7010b7ebc](https://bsd-hardware.info/?probe=c7010b7ebc) | Aug 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [21cda0eb5d](https://bsd-hardware.info/?probe=21cda0eb5d) | Aug 09, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bc7d4d8e1e](https://bsd-hardware.info/?probe=bc7d4d8e1e) | Aug 08, 2022 |
| eMachines     | eME728                      | Notebook    | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [df3667156b](https://bsd-hardware.info/?probe=df3667156b) | Aug 02, 2022 |
| Lex           | Pineview-D                  | Desktop     | [7d7195024e](https://bsd-hardware.info/?probe=7d7195024e) | Aug 02, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d6a3d57165](https://bsd-hardware.info/?probe=d6a3d57165) | Jul 29, 2022 |
| PC Engines    | APU2                        | Desktop     | [bb5d45a75d](https://bsd-hardware.info/?probe=bb5d45a75d) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [e3655742ba](https://bsd-hardware.info/?probe=e3655742ba) | Jul 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [4b9e0bb7bb](https://bsd-hardware.info/?probe=4b9e0bb7bb) | Jul 18, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [af1e80d15d](https://bsd-hardware.info/?probe=af1e80d15d) | Jul 18, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0434c94fad](https://bsd-hardware.info/?probe=0434c94fad) | Jul 09, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [4ac86f5979](https://bsd-hardware.info/?probe=4ac86f5979) | Jul 09, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [d3aba12432](https://bsd-hardware.info/?probe=d3aba12432) | Jul 09, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [6011c70ca4](https://bsd-hardware.info/?probe=6011c70ca4) | Jul 07, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dbbe9124a2](https://bsd-hardware.info/?probe=dbbe9124a2) | Jul 05, 2022 |
| HP            | 0A98h                       | Desktop     | [655fc531fb](https://bsd-hardware.info/?probe=655fc531fb) | Jun 30, 2022 |
| Acer          | AOD260                      | Notebook    | [08dc464d1b](https://bsd-hardware.info/?probe=08dc464d1b) | Jun 30, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e461a4559d](https://bsd-hardware.info/?probe=e461a4559d) | Jun 29, 2022 |
| HP            | 304Bh                       | Desktop     | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| NF692         | 1.0                         | Desktop     | [e87866bf5a](https://bsd-hardware.info/?probe=e87866bf5a) | Jun 10, 2022 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [5b66684c4a](https://bsd-hardware.info/?probe=5b66684c4a) | Jun 05, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [4b3b7a0929](https://bsd-hardware.info/?probe=4b3b7a0929) | May 31, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5d3db8382f](https://bsd-hardware.info/?probe=5d3db8382f) | May 31, 2022 |
| Lenovo        | ThinkPad X250 20CMS0FA00    | Notebook    | [5afeac632d](https://bsd-hardware.info/?probe=5afeac632d) | May 28, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [a89b2081bb](https://bsd-hardware.info/?probe=a89b2081bb) | May 25, 2022 |
| ASUSTek       | F50SL                       | Notebook    | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [2769c8f286](https://bsd-hardware.info/?probe=2769c8f286) | May 17, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | Notebook    | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | Notebook    | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [407fc42fad](https://bsd-hardware.info/?probe=407fc42fad) | May 05, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ff176fff8](https://bsd-hardware.info/?probe=5ff176fff8) | May 05, 2022 |
| Deciso        | OPNsense Appliance          | Notebook    | [8a8db12cf2](https://bsd-hardware.info/?probe=8a8db12cf2) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | Notebook    | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| Dell          | 0TY179 A05                  | Server      | [124e42e2c1](https://bsd-hardware.info/?probe=124e42e2c1) | Apr 21, 2022 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [9a50fe43a7](https://bsd-hardware.info/?probe=9a50fe43a7) | Apr 21, 2022 |
| Pegatron      | Benicia                     | Desktop     | [9045b4f449](https://bsd-hardware.info/?probe=9045b4f449) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [680303f943](https://bsd-hardware.info/?probe=680303f943) | Apr 16, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [47d17d48a7](https://bsd-hardware.info/?probe=47d17d48a7) | Apr 15, 2022 |
| Dell          | 07978V A08                  | Server      | [f315c33e95](https://bsd-hardware.info/?probe=f315c33e95) | Apr 06, 2022 |
| ShenZhen M... | MW-NANO-APL-4L              | Desktop     | [fbdd8d4f48](https://bsd-hardware.info/?probe=fbdd8d4f48) | Apr 05, 2022 |
| HP            | 212B                        | Desktop     | [33e7c65907](https://bsd-hardware.info/?probe=33e7c65907) | Apr 04, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3877a33214](https://bsd-hardware.info/?probe=3877a33214) | Apr 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [3da637e3c6](https://bsd-hardware.info/?probe=3da637e3c6) | Apr 02, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7b79164c18](https://bsd-hardware.info/?probe=7b79164c18) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9f760529c1](https://bsd-hardware.info/?probe=9f760529c1) | Mar 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [bddd5d8963](https://bsd-hardware.info/?probe=bddd5d8963) | Mar 18, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [bb895c5df3](https://bsd-hardware.info/?probe=bb895c5df3) | Mar 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [65ada9d5da](https://bsd-hardware.info/?probe=65ada9d5da) | Mar 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| HP            | 3397                        | Desktop     | [841ed56816](https://bsd-hardware.info/?probe=841ed56816) | Mar 02, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [6696106165](https://bsd-hardware.info/?probe=6696106165) | Feb 19, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [e098f52d51](https://bsd-hardware.info/?probe=e098f52d51) | Feb 19, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [df6278638e](https://bsd-hardware.info/?probe=df6278638e) | Feb 15, 2022 |
| Acer          | V5-131                      | Notebook    | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [ea7cf2885f](https://bsd-hardware.info/?probe=ea7cf2885f) | Feb 13, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [946c9acc2e](https://bsd-hardware.info/?probe=946c9acc2e) | Feb 11, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6997de25f9](https://bsd-hardware.info/?probe=6997de25f9) | Feb 11, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [7a3744a41a](https://bsd-hardware.info/?probe=7a3744a41a) | Feb 07, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| Dell          | 0TK7TF A00                  | Desktop     | [d13ca7163c](https://bsd-hardware.info/?probe=d13ca7163c) | Jan 30, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [f4d8bd7979](https://bsd-hardware.info/?probe=f4d8bd7979) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [f7e7df9416](https://bsd-hardware.info/?probe=f7e7df9416) | Jan 30, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [fc63aa695e](https://bsd-hardware.info/?probe=fc63aa695e) | Jan 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [52bd5dc1ce](https://bsd-hardware.info/?probe=52bd5dc1ce) | Jan 26, 2022 |
| ASUSTek       | BM6835_BM6635_BP6335        | Desktop     | [73562aa169](https://bsd-hardware.info/?probe=73562aa169) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cf360a6098](https://bsd-hardware.info/?probe=cf360a6098) | Jan 16, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [d76873c5dd](https://bsd-hardware.info/?probe=d76873c5dd) | Jan 16, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ed9f5d1a27](https://bsd-hardware.info/?probe=ed9f5d1a27) | Jan 15, 2022 |
| PC Engines    | APU2                        | Desktop     | [c2b05fc937](https://bsd-hardware.info/?probe=c2b05fc937) | Jan 14, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [7b99b0eaa6](https://bsd-hardware.info/?probe=7b99b0eaa6) | Jan 10, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [4ac0707c49](https://bsd-hardware.info/?probe=4ac0707c49) | Jan 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [341401bb02](https://bsd-hardware.info/?probe=341401bb02) | Jan 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [46e5f9b021](https://bsd-hardware.info/?probe=46e5f9b021) | Dec 29, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7a43524381](https://bsd-hardware.info/?probe=7a43524381) | Dec 13, 2021 |
| Packard Be... | EasyNote_MX61-B-038         | Notebook    | [235d60060d](https://bsd-hardware.info/?probe=235d60060d) | Dec 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [50fba6deda](https://bsd-hardware.info/?probe=50fba6deda) | Dec 11, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [a084ff48c2](https://bsd-hardware.info/?probe=a084ff48c2) | Dec 09, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [17b557d792](https://bsd-hardware.info/?probe=17b557d792) | Dec 08, 2021 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ddcab97db2](https://bsd-hardware.info/?probe=ddcab97db2) | Dec 03, 2021 |
| Toshiba       | Satellite C855-1U4          | Notebook    | [4107fc9eee](https://bsd-hardware.info/?probe=4107fc9eee) | Nov 14, 2021 |
| Toshiba       | PORTEGE M780                | Notebook    | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| T-bao         | MINI PC V1.0                | Desktop     | [4ee7de3597](https://bsd-hardware.info/?probe=4ee7de3597) | Nov 12, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [22a18ba45e](https://bsd-hardware.info/?probe=22a18ba45e) | Nov 08, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [5f026ff3a2](https://bsd-hardware.info/?probe=5f026ff3a2) | Oct 17, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [ca23d3bbf0](https://bsd-hardware.info/?probe=ca23d3bbf0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [b3b31d25b0](https://bsd-hardware.info/?probe=b3b31d25b0) | Oct 13, 2021 |
| Pegatron      | 2ACF                        | Desktop     | [97aa5e56e4](https://bsd-hardware.info/?probe=97aa5e56e4) | Oct 12, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [5a7c1871b1](https://bsd-hardware.info/?probe=5a7c1871b1) | Oct 11, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [a9c135bf27](https://bsd-hardware.info/?probe=a9c135bf27) | Oct 10, 2021 |
| Acer          | Veriton X2610G              | Desktop     | [1e9ed23164](https://bsd-hardware.info/?probe=1e9ed23164) | Oct 03, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [51b47d9321](https://bsd-hardware.info/?probe=51b47d9321) | Sep 27, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [de031313ff](https://bsd-hardware.info/?probe=de031313ff) | Sep 27, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [e0ad80acf9](https://bsd-hardware.info/?probe=e0ad80acf9) | Sep 20, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [0d23147c7d](https://bsd-hardware.info/?probe=0d23147c7d) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0b73df29bf](https://bsd-hardware.info/?probe=0b73df29bf) | Sep 15, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [e0ae9af4ab](https://bsd-hardware.info/?probe=e0ae9af4ab) | Sep 15, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [f1a2baeecb](https://bsd-hardware.info/?probe=f1a2baeecb) | Sep 14, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [bc2a287495](https://bsd-hardware.info/?probe=bc2a287495) | Sep 13, 2021 |
| BESSTAR Te... | GB1B                        | Mini pc     | [3607c373aa](https://bsd-hardware.info/?probe=3607c373aa) | Sep 11, 2021 |
| Apple         | Mac-F2268DC8                | All in one  | [73912d5852](https://bsd-hardware.info/?probe=73912d5852) | Sep 09, 2021 |
| Protectli     | FW4B                        | Desktop     | [861a1f7012](https://bsd-hardware.info/?probe=861a1f7012) | Aug 25, 2021 |
| MSI           | MS-B1591                    | Desktop     | [679b2010e9](https://bsd-hardware.info/?probe=679b2010e9) | Aug 03, 2021 |
| MSI           | MS-B1591                    | Desktop     | [b370a74ec0](https://bsd-hardware.info/?probe=b370a74ec0) | Aug 02, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [16e6ec4054](https://bsd-hardware.info/?probe=16e6ec4054) | Aug 02, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [acfe0caa83](https://bsd-hardware.info/?probe=acfe0caa83) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9c9d4cc782](https://bsd-hardware.info/?probe=9c9d4cc782) | Jul 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d5e512e18](https://bsd-hardware.info/?probe=3d5e512e18) | Jul 18, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [dc1b4d8a6b](https://bsd-hardware.info/?probe=dc1b4d8a6b) | Jul 16, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [d51149c1d5](https://bsd-hardware.info/?probe=d51149c1d5) | Jul 13, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [7fe4b5ff70](https://bsd-hardware.info/?probe=7fe4b5ff70) | Jul 12, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [dbacaa5c65](https://bsd-hardware.info/?probe=dbacaa5c65) | Jul 08, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| Lenovo        | B590 62743PG                | Notebook    | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f0e80b0788](https://bsd-hardware.info/?probe=f0e80b0788) | Jun 28, 2021 |
| PC Engines    | APU2                        | Desktop     | [dde9077545](https://bsd-hardware.info/?probe=dde9077545) | Jun 24, 2021 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [7cf77c6f1f](https://bsd-hardware.info/?probe=7cf77c6f1f) | Jun 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [822df8eb91](https://bsd-hardware.info/?probe=822df8eb91) | May 11, 2021 |
| Unknown       | Unknown                     | Desktop     | [cc17eea606](https://bsd-hardware.info/?probe=cc17eea606) | May 10, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [e26ecef661](https://bsd-hardware.info/?probe=e26ecef661) | May 03, 2021 |
| MSI           | B450-A PRO                  | Desktop     | [ed656e816f](https://bsd-hardware.info/?probe=ed656e816f) | May 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb09a1b771](https://bsd-hardware.info/?probe=cb09a1b771) | Apr 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [62376c16a4](https://bsd-hardware.info/?probe=62376c16a4) | Mar 31, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [5a7ba137e0](https://bsd-hardware.info/?probe=5a7ba137e0) | Mar 27, 2021 |
| Acer          | EG43M                       | Desktop     | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [139e702b9a](https://bsd-hardware.info/?probe=139e702b9a) | Mar 27, 2021 |
| Lenovo        | ThinkPad L530 24812TG       | Notebook    | [520982317e](https://bsd-hardware.info/?probe=520982317e) | Mar 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [5ae508dfa8](https://bsd-hardware.info/?probe=5ae508dfa8) | Mar 19, 2021 |
| Lenovo        | ThinkPad X260 20F5S82N00    | Notebook    | [aa3deadedd](https://bsd-hardware.info/?probe=aa3deadedd) | Mar 19, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [0a3b290f9f](https://bsd-hardware.info/?probe=0a3b290f9f) | Mar 15, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [1c30f7523f](https://bsd-hardware.info/?probe=1c30f7523f) | Mar 15, 2021 |
| PC Engines    | APU3                        | Desktop     | [822a83f208](https://bsd-hardware.info/?probe=822a83f208) | Mar 11, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [c672201bcb](https://bsd-hardware.info/?probe=c672201bcb) | Mar 10, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| Dell          | 00NH4P A07                  | Server      | [7cff5a5c58](https://bsd-hardware.info/?probe=7cff5a5c58) | Mar 08, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf572bc102](https://bsd-hardware.info/?probe=bf572bc102) | Mar 06, 2021 |
| Dell          | 0R849J A00                  | Desktop     | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [55045aa9e5](https://bsd-hardware.info/?probe=55045aa9e5) | Mar 03, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [10d02d0982](https://bsd-hardware.info/?probe=10d02d0982) | Mar 03, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [3c5bd7b7f8](https://bsd-hardware.info/?probe=3c5bd7b7f8) | Mar 02, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [04e66ca239](https://bsd-hardware.info/?probe=04e66ca239) | Mar 02, 2021 |
| ASUSTek       | G1S                         | Notebook    | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [50652a4263](https://bsd-hardware.info/?probe=50652a4263) | Feb 26, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Dell          | 00NH4P A07                  | Server      | [fff0533829](https://bsd-hardware.info/?probe=fff0533829) | Feb 20, 2021 |
| Intel         | MAHOBAY                     | Desktop     | [5257239fdc](https://bsd-hardware.info/?probe=5257239fdc) | Feb 20, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [837c6f28b4](https://bsd-hardware.info/?probe=837c6f28b4) | Feb 19, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [d0c0433452](https://bsd-hardware.info/?probe=d0c0433452) | Feb 16, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [74d43ccd10](https://bsd-hardware.info/?probe=74d43ccd10) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [4d225e7ebe](https://bsd-hardware.info/?probe=4d225e7ebe) | Feb 04, 2021 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [01a2dd5a52](https://bsd-hardware.info/?probe=01a2dd5a52) | Feb 02, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [f813782c8a](https://bsd-hardware.info/?probe=f813782c8a) | Jan 29, 2021 |
| ZOTAC         | ZBOX-MI640/MI660/MI620NA... | Mini pc     | [2aa7735e59](https://bsd-hardware.info/?probe=2aa7735e59) | Jan 24, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [622589c8e7](https://bsd-hardware.info/?probe=622589c8e7) | Jan 22, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [7a3cb6a061](https://bsd-hardware.info/?probe=7a3cb6a061) | Jan 22, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9eca3b0463](https://bsd-hardware.info/?probe=9eca3b0463) | Jan 22, 2021 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [12ea57f317](https://bsd-hardware.info/?probe=12ea57f317) | Jan 22, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [fcc759e013](https://bsd-hardware.info/?probe=fcc759e013) | Jan 21, 2021 |
| ASRock        | H81 Pro BTC                 | Desktop     | [afb7cd1f1a](https://bsd-hardware.info/?probe=afb7cd1f1a) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [92577053eb](https://bsd-hardware.info/?probe=92577053eb) | Jan 20, 2021 |
| Intel         | CRESCENTBAY                 | Desktop     | [33a6dda088](https://bsd-hardware.info/?probe=33a6dda088) | Jan 20, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [539b95f535](https://bsd-hardware.info/?probe=539b95f535) | Jan 20, 2021 |
| PC Engines    | APU2                        | Desktop     | [a178f8eb47](https://bsd-hardware.info/?probe=a178f8eb47) | Jan 19, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [bc4bca1e5e](https://bsd-hardware.info/?probe=bc4bca1e5e) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Supermicro    | X8STi                       | Desktop     | [7d0e121099](https://bsd-hardware.info/?probe=7d0e121099) | Jan 15, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| Unknown       | Unknown                     | Desktop     | [d2cdc0fc7f](https://bsd-hardware.info/?probe=d2cdc0fc7f) | Nov 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [aee9f448af](https://bsd-hardware.info/?probe=aee9f448af) | Nov 25, 2020 |
| Lenovo        | ThinkPad T495 20NJS0KP00    | Notebook    | [7a706e46de](https://bsd-hardware.info/?probe=7a706e46de) | Oct 31, 2020 |
| Lenovo        | ThinkPad T430 23501B3       | Notebook    | [53233cc736](https://bsd-hardware.info/?probe=53233cc736) | Oct 31, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [58678b0643](https://bsd-hardware.info/?probe=58678b0643) | Oct 30, 2020 |
| Intel         | D945GCLF2                   | Desktop     | [3354fb903b](https://bsd-hardware.info/?probe=3354fb903b) | Oct 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [973b62551f](https://bsd-hardware.info/?probe=973b62551f) | Oct 30, 2020 |
| AZW           | BT3 X                       | Desktop     | [b9f23ee753](https://bsd-hardware.info/?probe=b9f23ee753) | Oct 30, 2020 |
| Dell          | Precision 3510              | Notebook    | [85a55ab7c3](https://bsd-hardware.info/?probe=85a55ab7c3) | Oct 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7faf1699d6](https://bsd-hardware.info/?probe=7faf1699d6) | Oct 04, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2f119a81b4](https://bsd-hardware.info/?probe=2f119a81b4) | Aug 13, 2020 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [f437a3b5ab](https://bsd-hardware.info/?probe=f437a3b5ab) | Jul 06, 2020 |
| ASRock        | 990FX Extreme9              | Desktop     | [6c0bba6d4f](https://bsd-hardware.info/?probe=6c0bba6d4f) | Jun 26, 2020 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [6b854263e7](https://bsd-hardware.info/?probe=6b854263e7) | May 25, 2020 |
| Lenovo        | ThinkPad T440 20B7S1C600    | Notebook    | [a4a62cb85e](https://bsd-hardware.info/?probe=a4a62cb85e) | May 24, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| helloSystem 0.7.0 | 19        | 5.08%   |
| helloSystem 0.8.1 | 18        | 4.81%   |
| helloSystem 0.4.0 | 12        | 3.21%   |
| OpenBSD 7.1       | 9         | 2.41%   |
| helloSystem 0.5.0 | 9         | 2.41%   |
| OPNsense 23.7.9   | 7         | 1.87%   |
| OPNsense 22.7     | 7         | 1.87%   |
| helloSystem 0.8.0 | 7         | 1.87%   |
| OPNsense 23.7.5   | 6         | 1.6%    |
| OPNsense 23.1.6   | 6         | 1.6%    |
| OPNsense 23.1.5   | 6         | 1.6%    |
| OPNsense 23.1.11  | 6         | 1.6%    |
| helloSystem 0.9.0 | 6         | 1.6%    |
| helloSystem 0.6.0 | 6         | 1.6%    |
| FreeBSD 13.1      | 6         | 1.6%    |
| OPNsense 23.7.7   | 5         | 1.34%   |
| OPNsense 23.7.12  | 5         | 1.34%   |
| OPNsense 22.1.6   | 5         | 1.34%   |
| OPNsense 21.1     | 5         | 1.34%   |
| OpenBSD 7.2       | 5         | 1.34%   |
| helloSystem 0.3.0 | 5         | 1.34%   |
| OPNsense 24.1.5   | 4         | 1.07%   |
| OPNsense 24.1.1   | 4         | 1.07%   |
| OPNsense 23.7.10  | 4         | 1.07%   |
| OPNsense 22.7.9   | 4         | 1.07%   |
| OPNsense 22.7.6   | 4         | 1.07%   |
| OPNsense 22.7.3   | 4         | 1.07%   |
| OPNsense 22.7.10  | 4         | 1.07%   |
| OPNsense 22.1.9   | 4         | 1.07%   |
| OPNsense 22.1.10  | 4         | 1.07%   |
| OPNsense 22.1     | 4         | 1.07%   |
| OpenBSD 7.4       | 4         | 1.07%   |
| OPNsense 24.1.4   | 3         | 0.8%    |
| OPNsense 23.7.2   | 3         | 0.8%    |
| OPNsense 23.1.9   | 3         | 0.8%    |
| OPNsense 23.1.7   | 3         | 0.8%    |
| OPNsense 23.1.4   | 3         | 0.8%    |
| OPNsense 23.1.1   | 3         | 0.8%    |
| OPNsense 23.1     | 3         | 0.8%    |
| OPNsense 22.7.2   | 3         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 127       | 44.41%  |
| helloSystem | 70        | 24.48%  |
| FreeBSD     | 39        | 13.64%  |
| OpenBSD     | 26        | 9.09%   |
| NetBSD      | 9         | 3.15%   |
| NomadBSD    | 7         | 2.45%   |
| GhostBSD    | 7         | 2.45%   |
| XigmaNAS    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 278       | 97.54%  |
| i386    | 3         | 1.05%   |
| evbarm  | 3         | 1.05%   |
| sparc64 | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Console       | 140       | 48.61%  |
| helloDesktop  | 76        | 26.39%  |
| XFCE          | 23        | 7.99%   |
| KDE5          | 10        | 3.47%   |
| Openbox       | 7         | 2.43%   |
| MATE          | 7         | 2.43%   |
| CTWM          | 5         | 1.74%   |
| TWM           | 4         | 1.39%   |
| fvwm          | 4         | 1.39%   |
| i3            | 3         | 1.04%   |
| Cinnamon      | 3         | 1.04%   |
| xfwm          | 2         | 0.69%   |
| LXQt          | 1         | 0.35%   |
| LXDE          | 1         | 0.35%   |
| Fluxbox       | 1         | 0.35%   |
| Enlightenment | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 144       | 50.35%  |
| Console | 141       | 49.3%   |
| Wayland | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 184       | 64.11%  |
| SLiM    | 83        | 28.92%  |
| LightDM | 10        | 3.48%   |
| SDDM    | 6         | 2.09%   |
| XDM     | 3         | 1.05%   |
| GDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 162       | 54.92%  |
| en_US            | 64        | 21.69%  |
| it_IT            | 31        | 10.51%  |
| C                | 22        | 7.46%   |
| fr_FR            | 6         | 2.03%   |
| it               | 3         | 1.02%   |
| it_IT.ISO8859-15 | 2         | 0.68%   |
| en               | 2         | 0.68%   |
| ru_RU            | 1         | 0.34%   |
| it_IT.ISO8859-1  | 1         | 0.34%   |
| en_GB            | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 244       | 85.02%  |
| BIOS | 43        | 14.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Ufs    | 125       | 42.66%  |
| Zfs    | 111       | 37.88%  |
| Cd9660 | 31        | 10.58%  |
| Ffs    | 26        | 8.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 258       | 89.58%  |
| MBR     | 21        | 7.29%   |
| Unknown | 9         | 3.13%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| ASUSTek Computer           | 44        | 15.44%  |
| Unknown                    | 30        | 10.53%  |
| Lenovo                     | 23        | 8.07%   |
| Dell                       | 23        | 8.07%   |
| Hewlett-Packard            | 21        | 7.37%   |
| Intel                      | 16        | 5.61%   |
| PC Engines                 | 11        | 3.86%   |
| Gigabyte Technology        | 10        | 3.51%   |
| ASRock                     | 9         | 3.16%   |
| Acer                       | 9         | 3.16%   |
| MSI                        | 8         | 2.81%   |
| Fujitsu                    | 8         | 2.81%   |
| BESSTAR Tech               | 6         | 2.11%   |
| Supermicro                 | 5         | 1.75%   |
| Apple                      | 5         | 1.75%   |
| AZW                        | 4         | 1.4%    |
| AMI                        | 4         | 1.4%    |
| YANYU                      | 3         | 1.05%   |
| Toshiba                    | 3         | 1.05%   |
| Samsung Electronics        | 3         | 1.05%   |
| Protectli                  | 3         | 1.05%   |
| ZOTAC                      | 2         | 0.7%    |
| Sophos                     | 2         | 0.7%    |
| Pegatron                   | 2         | 0.7%    |
| MW                         | 2         | 0.7%    |
| IceWhale Technology        | 2         | 0.7%    |
| eMachines                  | 2         | 0.7%    |
| YENTEK                     | 1         | 0.35%   |
| TUXEDO                     | 1         | 0.35%   |
| TULPAR                     | 1         | 0.35%   |
| T-bao                      | 1         | 0.35%   |
| Sun Microsystems           | 1         | 0.35%   |
| Stonesoft                  | 1         | 0.35%   |
| SiComputer                 | 1         | 0.35%   |
| ShenZhen MinWin Technology | 1         | 0.35%   |
| Raspberry Pi Foundation    | 1         | 0.35%   |
| Quantum engineering        | 1         | 0.35%   |
| Packard Bell               | 1         | 0.35%   |
| NF692                      | 1         | 0.35%   |
| LG Electronics             | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 32        | 11.23%  |
| PC Engines APU2                        | 7         | 2.46%   |
| Supermicro Super Server                | 3         | 1.05%   |
| Fujitsu FUTRO S920                     | 3         | 1.05%   |
| BESSTAR Tech N40                       | 3         | 1.05%   |
| ASUS PRIME H410M-A                     | 3         | 1.05%   |
| ASUS PRIME B650-PLUS                   | 3         | 1.05%   |
| Sophos UTM                             | 2         | 0.7%    |
| Protectli FW4B                         | 2         | 0.7%    |
| PC Engines apu4                        | 2         | 0.7%    |
| MW GMLK-2_5G4L                         | 2         | 0.7%    |
| MSI MS-7B86                            | 2         | 0.7%    |
| Lenovo ThinkCentre M83 10AHS35Q00      | 2         | 0.7%    |
| Intel Q3XXG4-P V1.0                    | 2         | 0.7%    |
| Intel NCB-4210WG                       | 2         | 0.7%    |
| HP t620 PLUS Quad Core TC              | 2         | 0.7%    |
| HP Laptop 15-da0xxx                    | 2         | 0.7%    |
| Gigabyte X570 AORUS ELITE              | 2         | 0.7%    |
| Gigabyte A520M S2H                     | 2         | 0.7%    |
| Dell OptiPlex 3020                     | 2         | 0.7%    |
| AZW U59                                | 2         | 0.7%    |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 2         | 0.7%    |
| ASUS P8Z77-V LX                        | 2         | 0.7%    |
| ASUS M4A88TD-V EVO/USB3                | 2         | 0.7%    |
| ASUS IP4BL-ME                          | 2         | 0.7%    |
| Apple MacBook4,1                       | 2         | 0.7%    |
| AMI Aptio CRB                          | 2         | 0.7%    |
| ZOTAC ZBOX-MI640/MI660/MI620NANO       | 1         | 0.35%   |
| ZOTAC ZBOX-CI323NANO                   | 1         | 0.35%   |
| YENTEK D41SL                           | 1         | 0.35%   |
| YANYU M9F baytrail                     | 1         | 0.35%   |
| YANYU ITX-M9F VER:1.3 baytrail         | 1         | 0.35%   |
| YANYU H17SL                            | 1         | 0.35%   |
| TUXEDO N14xWU                          | 1         | 0.35%   |
| TULPAR A5 V20.3                        | 1         | 0.35%   |
| Toshiba Satellite C855-1U4             | 1         | 0.35%   |
| Toshiba PORTEGE M780                   | 1         | 0.35%   |
| T-bao MINI PC                          | 1         | 0.35%   |
| Supermicro X9SCI/X9SCA                 | 1         | 0.35%   |
| Supermicro X8STi                       | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Unknown            | 32        | 11.23%  |
| Lenovo ThinkPad    | 16        | 5.61%   |
| ASUS PRIME         | 12        | 4.21%   |
| PC Engines APU2    | 7         | 2.46%   |
| Dell PowerEdge     | 7         | 2.46%   |
| Dell OptiPlex      | 5         | 1.75%   |
| HP Compaq          | 4         | 1.4%    |
| Fujitsu FUTRO      | 4         | 1.4%    |
| Acer Aspire        | 4         | 1.4%    |
| Supermicro Super   | 3         | 1.05%   |
| Lenovo ThinkCentre | 3         | 1.05%   |
| Gigabyte X570      | 3         | 1.05%   |
| Dell Precision     | 3         | 1.05%   |
| Dell Latitude      | 3         | 1.05%   |
| BESSTAR Tech N40   | 3         | 1.05%   |
| ASUS VivoBook      | 3         | 1.05%   |
| ASUS P8Z77-V       | 3         | 1.05%   |
| Sophos UTM         | 2         | 0.7%    |
| Protectli FW4B     | 2         | 0.7%    |
| PC Engines apu4    | 2         | 0.7%    |
| MW GMLK-2          | 2         | 0.7%    |
| MSI MS-7B86        | 2         | 0.7%    |
| Intel Q3XXG4-P     | 2         | 0.7%    |
| Intel NUC5i5RYB    | 2         | 0.7%    |
| Intel NCB-4210WG   | 2         | 0.7%    |
| IceWhale ZimaBoard | 2         | 0.7%    |
| HP t620            | 2         | 0.7%    |
| HP ProLiant        | 2         | 0.7%    |
| HP Laptop          | 2         | 0.7%    |
| HP EliteDesk       | 2         | 0.7%    |
| Gigabyte A520M     | 2         | 0.7%    |
| Fujitsu PRIMERGY   | 2         | 0.7%    |
| Fujitsu ESPRIMO    | 2         | 0.7%    |
| Dell Inspiron      | 2         | 0.7%    |
| AZW U59            | 2         | 0.7%    |
| ASUS M4A88TD-V     | 2         | 0.7%    |
| ASUS IP4BL-ME      | 2         | 0.7%    |
| Apple MacBook4     | 2         | 0.7%    |
| AMI Aptio          | 2         | 0.7%    |
| ZOTAC ZBOX-MI640   | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 25        | 8.77%   |
| 2014    | 25        | 8.77%   |
| 2016    | 24        | 8.42%   |
| 2019    | 21        | 7.37%   |
| 2018    | 20        | 7.02%   |
| 2023    | 19        | 6.67%   |
| 2020    | 19        | 6.67%   |
| 2011    | 19        | 6.67%   |
| 2010    | 19        | 6.67%   |
| 2022    | 18        | 6.32%   |
| 2012    | 16        | 5.61%   |
| 2013    | 14        | 4.91%   |
| 2017    | 11        | 3.86%   |
| 2008    | 10        | 3.51%   |
| 2015    | 8         | 2.81%   |
| 2009    | 8         | 2.81%   |
| Unknown | 4         | 1.4%    |
| 2007    | 2         | 0.7%    |
| 2005    | 2         | 0.7%    |
| 2006    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 171       | 60%     |
| Notebook       | 78        | 27.37%  |
| Mini pc        | 18        | 6.32%   |
| Server         | 12        | 4.21%   |
| System on chip | 2         | 0.7%    |
| Firewall       | 2         | 0.7%    |
| All in one     | 2         | 0.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 273       | 95.45%  |
| Yes  | 13        | 4.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 112       | 38.36%  |
| 4.01-8.0    | 70        | 23.97%  |
| 16.01-24.0  | 48        | 16.44%  |
| 32.01-64.0  | 22        | 7.53%   |
| 2.01-3.0    | 21        | 7.19%   |
| 64.01-256.0 | 7         | 2.4%    |
| 3.01-4.0    | 4         | 1.37%   |
| 24.01-32.0  | 3         | 1.03%   |
| 0.51-1.0    | 3         | 1.03%   |
| 1.01-2.0    | 1         | 0.34%   |
| 0.01-0.5    | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 173       | 59.25%  |
| 0.51-1.0   | 69        | 23.63%  |
| 1.01-2.0   | 22        | 7.53%   |
| 4.01-8.0   | 9         | 3.08%   |
| Unknown    | 9         | 3.08%   |
| 2.01-3.0   | 7         | 2.4%    |
| 3.01-4.0   | 1         | 0.34%   |
| 24.01-32.0 | 1         | 0.34%   |
| 8.01-16.0  | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 195       | 66.78%  |
| 2      | 44        | 15.07%  |
| 0      | 26        | 8.9%    |
| 3      | 11        | 3.77%   |
| 4      | 9         | 3.08%   |
| 7      | 2         | 0.68%   |
| 6      | 2         | 0.68%   |
| 10     | 1         | 0.34%   |
| 9      | 1         | 0.34%   |
| 5      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 212       | 73.87%  |
| Yes       | 75        | 26.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 271       | 95.09%  |
| No        | 14        | 4.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 58.04%  |
| Yes       | 120       | 41.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 204       | 71.08%  |
| Yes       | 83        | 28.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 285       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milan                 | 48        | 14.08%  |
| Rome                  | 34        | 9.97%   |
| Bologna               | 10        | 2.93%   |
| Turin                 | 7         | 2.05%   |
| Trieste               | 7         | 2.05%   |
| Naples                | 6         | 1.76%   |
| Monza                 | 4         | 1.17%   |
| Brescia               | 4         | 1.17%   |
| Venice                | 3         | 0.88%   |
| Sesto San Giovanni    | 3         | 0.88%   |
| Rho                   | 3         | 0.88%   |
| Reggio Emilia         | 3         | 0.88%   |
| Padova                | 3         | 0.88%   |
| Milano                | 3         | 0.88%   |
| Bari                  | 3         | 0.88%   |
| Verona                | 2         | 0.59%   |
| Turrivalignani        | 2         | 0.59%   |
| Treviso               | 2         | 0.59%   |
| Taviano               | 2         | 0.59%   |
| Silea                 | 2         | 0.59%   |
| Scandicci             | 2         | 0.59%   |
| San Giustino Valdarno | 2         | 0.59%   |
| San Giuliano Terme    | 2         | 0.59%   |
| Rosignano Marittimo   | 2         | 0.59%   |
| Reggio Calabria       | 2         | 0.59%   |
| Palermo               | 2         | 0.59%   |
| Monterotondo          | 2         | 0.59%   |
| Momo                  | 2         | 0.59%   |
| Modena                | 2         | 0.59%   |
| Messina               | 2         | 0.59%   |
| Lucca                 | 2         | 0.59%   |
| Lecco                 | 2         | 0.59%   |
| Genoa                 | 2         | 0.59%   |
| Gallarate             | 2         | 0.59%   |
| Florence              | 2         | 0.59%   |
| Ferrara               | 2         | 0.59%   |
| Desio                 | 2         | 0.59%   |
| Catania               | 2         | 0.59%   |
| Cagliari              | 2         | 0.59%   |
| Besana in Brianza     | 2         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 64     | 12.79%  |
| WDC                 | 39        | 77     | 11.34%  |
| Seagate             | 37        | 69     | 10.76%  |
| Kingston            | 32        | 40     | 9.3%    |
| Crucial             | 27        | 47     | 7.85%   |
| Toshiba             | 22        | 48     | 6.4%    |
| Transcend           | 21        | 34     | 6.1%    |
| SanDisk             | 12        | 13     | 3.49%   |
| NVMe                | 8         | 9      | 2.33%   |
| Hitachi             | 8         | 10     | 2.33%   |
| China               | 8         | 14     | 2.33%   |
| Intel               | 6         | 7      | 1.74%   |
| PNY                 | 4         | 8      | 1.16%   |
| Micron Technology   | 4         | 4      | 1.16%   |
| Maxtor              | 4         | 4      | 1.16%   |
| Innodisk            | 4         | 6      | 1.16%   |
| Hoodisk             | 4         | 6      | 1.16%   |
| HGST                | 4         | 4      | 1.16%   |
| Emtec               | 4         | 6      | 1.16%   |
| SPCC                | 3         | 3      | 0.87%   |
| OCZ                 | 3         | 3      | 0.87%   |
| KingSpec            | 3         | 4      | 0.87%   |
| FORESEE             | 3         | 4      | 0.87%   |
| SK hynix            | 2         | 2      | 0.58%   |
| Silicon Motion      | 2         | 3      | 0.58%   |
| Phison              | 2         | 2      | 0.58%   |
| Pccooler            | 2         | 4      | 0.58%   |
| LITEON              | 2         | 2      | 0.58%   |
| Leven               | 2         | 2      | 0.58%   |
| Indilinx            | 2         | 2      | 0.58%   |
| Dogfish             | 2         | 2      | 0.58%   |
| Corsair             | 2         | 3      | 0.58%   |
| BAITITON            | 2         | 2      | 0.58%   |
| Apple               | 2         | 2      | 0.58%   |
| A-DATA Technology   | 2         | 3      | 0.58%   |
| VICKTER             | 1         | 1      | 0.29%   |
| Verbatim            | 1         | 1      | 0.29%   |
| Union Memory        | 1         | 1      | 0.29%   |
| T-FORCE             | 1         | 1      | 0.29%   |
| Protectli           | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB    | 7         | 1.9%    |
| Samsung SSD 860 EVO 250GB       | 6         | 1.63%   |
| Kingston SA400S37120G 120GB     | 5         | 1.36%   |
| Samsung SSD 870 EVO 250GB       | 4         | 1.08%   |
| Samsung SSD 860 EVO 500GB       | 4         | 1.08%   |
| Samsung SSD 850 EVO 250GB       | 4         | 1.08%   |
| NVMe Samsung SSD 980 1TB        | 4         | 1.08%   |
| Kingston SA400S37240G 240GB     | 4         | 1.08%   |
| Crucial CT500MX500SSD1 500GB    | 4         | 1.08%   |
| Transcend TS128GMSA230S 128GB   | 3         | 0.81%   |
| Seagate ST1000DM003-1ER162 1TB  | 3         | 0.81%   |
| Samsung SSD 850 EVO 500GB       | 3         | 0.81%   |
| Kingston SV300S37A120G 120GB    | 3         | 0.81%   |
| Kingston SEDC500M480G 480GB     | 3         | 0.81%   |
| Emtec X150 120GB                | 3         | 0.81%   |
| Crucial CT250MX500SSD1 250GB    | 3         | 0.81%   |
| Crucial CT120BX500SSD1 120GB    | 3         | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2         | 0.54%   |
| WDC WD5000AAKS-22V1A0 500GB     | 2         | 0.54%   |
| Transcend TS64GSSD370 64GB      | 2         | 0.54%   |
| Transcend TS64GMSA370 64GB      | 2         | 0.54%   |
| Transcend TS256GSSD230S 256GB   | 2         | 0.54%   |
| Transcend TS256GMTS430S 256GB   | 2         | 0.54%   |
| Transcend TS16GMSA370 16GB      | 2         | 0.54%   |
| Toshiba Q300 240GB              | 2         | 0.54%   |
| Toshiba MQ04ABF100 1TB          | 2         | 0.54%   |
| Toshiba MQ01ABD100 1TB          | 2         | 0.54%   |
| Toshiba HDWG440 4TB             | 2         | 0.54%   |
| Toshiba HDWD110 1TB             | 2         | 0.54%   |
| Toshiba DT01ACA050 500GB        | 2         | 0.54%   |
| Seagate ST320LT007-9ZV142 320GB | 2         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB  | 2         | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB  | 2         | 0.54%   |
| SanDisk SDSSDP128G 128GB        | 2         | 0.54%   |
| Samsung SSD 970 EVO 250GB       | 2         | 0.54%   |
| Samsung SSD 870 EVO 500GB       | 2         | 0.54%   |
| Samsung SSD 870 EVO 1TB         | 2         | 0.54%   |
| Samsung HM321HI 320GB           | 2         | 0.54%   |
| PNY CS900 120GB SSD             | 2         | 0.54%   |
| Phison SATA SSD 16GB            | 2         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 69     | 33.04%  |
| WDC                 | 31        | 66     | 27.68%  |
| Toshiba             | 19        | 40     | 16.96%  |
| Hitachi             | 8         | 10     | 7.14%   |
| Samsung Electronics | 4         | 4      | 3.57%   |
| Maxtor              | 4         | 4      | 3.57%   |
| HGST                | 4         | 4      | 3.57%   |
| NVMe                | 2         | 3      | 1.79%   |
| HPE                 | 1         | 1      | 0.89%   |
| Hewlett-Packard     | 1         | 2      | 0.89%   |
| Fujitsu             | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 50     | 16.43%  |
| Kingston            | 24        | 30     | 11.59%  |
| Crucial             | 24        | 40     | 11.59%  |
| Transcend           | 20        | 33     | 9.66%   |
| SanDisk             | 12        | 13     | 5.8%    |
| WDC                 | 8         | 10     | 3.86%   |
| China               | 8         | 14     | 3.86%   |
| NVMe                | 6         | 6      | 2.9%    |
| Intel               | 5         | 6      | 2.42%   |
| PNY                 | 4         | 8      | 1.93%   |
| Innodisk            | 4         | 6      | 1.93%   |
| Hoodisk             | 4         | 6      | 1.93%   |
| Emtec               | 4         | 6      | 1.93%   |
| Toshiba             | 3         | 8      | 1.45%   |
| SPCC                | 3         | 3      | 1.45%   |
| OCZ                 | 3         | 3      | 1.45%   |
| Micron Technology   | 3         | 3      | 1.45%   |
| KingSpec            | 3         | 4      | 1.45%   |
| FORESEE             | 3         | 4      | 1.45%   |
| SK hynix            | 2         | 2      | 0.97%   |
| Phison              | 2         | 2      | 0.97%   |
| Pccooler            | 2         | 4      | 0.97%   |
| LITEON              | 2         | 2      | 0.97%   |
| Leven               | 2         | 2      | 0.97%   |
| Indilinx            | 2         | 2      | 0.97%   |
| Dogfish             | 2         | 2      | 0.97%   |
| Corsair             | 2         | 3      | 0.97%   |
| BAITITON            | 2         | 2      | 0.97%   |
| Apple               | 2         | 2      | 0.97%   |
| A-DATA Technology   | 2         | 3      | 0.97%   |
| VICKTER             | 1         | 1      | 0.48%   |
| Verbatim            | 1         | 1      | 0.48%   |
| T-FORCE             | 1         | 1      | 0.48%   |
| Protectli           | 1         | 1      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| Lexar               | 1         | 1      | 0.48%   |
| KingDian            | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| ASUSTek Computer    | 1         | 2      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 180       | 290    | 60.81%  |
| HDD  | 88        | 204    | 29.73%  |
| NVMe | 28        | 38     | 9.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 242       | 494    | 89.63%  |
| NVMe | 28        | 38     | 10.37%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 353    | 74.91%  |
| 0.51-1.0   | 43        | 86     | 15.64%  |
| 1.01-2.0   | 13        | 17     | 4.73%   |
| 3.01-4.0   | 7         | 15     | 2.55%   |
| 4.01-10.0  | 3         | 10     | 1.09%   |
| 2.01-3.0   | 2         | 5      | 0.73%   |
| 10.01-20.0 | 1         | 8      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 100       | 33.9%   |
| 1-20           | 77        | 26.1%   |
| 251-500        | 45        | 15.25%  |
| 21-50          | 24        | 8.14%   |
| 51-100         | 21        | 7.12%   |
| 501-1000       | 20        | 6.78%   |
| More than 3000 | 4         | 1.36%   |
| 1001-2000      | 3         | 1.02%   |
| Unknown        | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 264       | 89.19%  |
| 21-50          | 18        | 6.08%   |
| 51-100         | 6         | 2.03%   |
| 101-250        | 3         | 1.01%   |
| 501-1000       | 2         | 0.68%   |
| More than 3000 | 1         | 0.34%   |
| 1001-2000      | 1         | 0.34%   |
| Unknown        | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-22V1A0 500GB             | 2         | 2      | 4.08%   |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 2      | 4.08%   |
| OCZ VERTEX3 120GB                       | 2         | 2      | 4.08%   |
| Intel SSDSC2BF180A4L 180GB              | 2         | 2      | 4.08%   |
| WDC WD800JD-75MSA3 80GB                 | 1         | 1      | 2.04%   |
| WDC WD5000AAKX-75U6AA0 500GB            | 1         | 2      | 2.04%   |
| WDC WD5000AAKS-00E4A0 500GB             | 1         | 1      | 2.04%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 1      | 2.04%   |
| WDC WD20EVDS-63T3B0 2TB                 | 1         | 1      | 2.04%   |
| WDC WD2002FYPS-01U1B1 2TB               | 1         | 1      | 2.04%   |
| WDC WD10EZEX-60M2NA0 1TB                | 1         | 1      | 2.04%   |
| WDC WD1000DHTZ-04N21V1 1TB              | 1         | 2      | 2.04%   |
| Transcend TS128GMSA230S 128GB           | 1         | 2      | 2.04%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 2.04%   |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 2.04%   |
| SK hynix SC313 HFS256G32TNF-N3A0A 256GB | 1         | 1      | 2.04%   |
| Seagate ST9750420AS 752GB               | 1         | 1      | 2.04%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 2.04%   |
| Seagate ST9160821AS 160GB               | 1         | 1      | 2.04%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 2.04%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 1      | 2.04%   |
| Seagate ST500LM021-1KJ152 500GB         | 1         | 1      | 2.04%   |
| Seagate ST500DM002-1BD142 500GB         | 1         | 6      | 2.04%   |
| Seagate ST4000LM024-2AN17V 4TB          | 1         | 1      | 2.04%   |
| Seagate ST31500341AS 1.5TB              | 1         | 1      | 2.04%   |
| SanDisk SDSSDP064G 64GB                 | 1         | 1      | 2.04%   |
| SanDisk SD9SN8W-128G-1006 128GB         | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 870 EVO 500GB   | 1         | 1      | 2.04%   |
| Samsung Electronics HM321HI 320GB       | 1         | 1      | 2.04%   |
| Netac SSD 256GB                         | 1         | 1      | 2.04%   |
| Maxtor 6V080E0 80GB                     | 1         | 1      | 2.04%   |
| Maxtor 6E040L0 40GB                     | 1         | 1      | 2.04%   |
| LITEON CV8-8E128-HP 128GB               | 1         | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB            | 1         | 1      | 2.04%   |
| Hitachi HTS548040M9AT00 37GB            | 1         | 2      | 2.04%   |
| Hitachi HTS545050A7E380 500GB           | 1         | 1      | 2.04%   |
| Hitachi HDS723030ALA640 3TB             | 1         | 2      | 2.04%   |
| HGST HTS725050A7E630 500GB              | 1         | 1      | 2.04%   |
| HGST HTS541075A9E680 752GB              | 1         | 1      | 2.04%   |
| HGST HTS541010A9E680 1TB                | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 22.45%  |
| WDC                 | 10        | 12     | 20.41%  |
| Hitachi             | 3         | 5      | 6.12%   |
| HGST                | 3         | 3      | 6.12%   |
| Toshiba             | 2         | 2      | 4.08%   |
| SanDisk             | 2         | 2      | 4.08%   |
| Samsung Electronics | 2         | 2      | 4.08%   |
| OCZ                 | 2         | 2      | 4.08%   |
| Maxtor              | 2         | 2      | 4.08%   |
| Intel               | 2         | 2      | 4.08%   |
| China               | 2         | 2      | 4.08%   |
| Transcend           | 1         | 2      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| Netac               | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| Kingston            | 1         | 1      | 2.04%   |
| Crucial             | 1         | 3      | 2.04%   |
| BAITITON            | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 16     | 34.38%  |
| WDC                 | 10        | 12     | 31.25%  |
| Hitachi             | 3         | 5      | 9.38%   |
| HGST                | 3         | 3      | 9.38%   |
| Toshiba             | 2         | 2      | 6.25%   |
| Maxtor              | 2         | 2      | 6.25%   |
| Samsung Electronics | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 41     | 65.22%  |
| SSD  | 16        | 20     | 34.78%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Crucial CT500P3SSD8 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Crucial | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 216       | 436    | 76.6%   |
| Malfunc  | 46        | 61     | 16.31%  |
| Detected | 19        | 34     | 6.74%   |
| Failed   | 1         | 1      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 209       | 62.2%   |
| AMD                              | 57        | 16.96%  |
| Samsung Electronics              | 15        | 4.46%   |
| Kingston Technology Company      | 8         | 2.38%   |
| Marvell Technology Group         | 5         | 1.49%   |
| Broadcom / LSI                   | 5         | 1.49%   |
| ASMedia Technology               | 5         | 1.49%   |
| Micron/Crucial Technology        | 4         | 1.19%   |
| VIA Technologies                 | 2         | 0.6%    |
| Silicon Motion                   | 2         | 0.6%    |
| Silicon Integrated Systems [SiS] | 2         | 0.6%    |
| SanDisk                          | 2         | 0.6%    |
| Nvidia                           | 2         | 0.6%    |
| Micron Technology                | 2         | 0.6%    |
| JMicron Technology               | 2         | 0.6%    |
| Adaptec                          | 2         | 0.6%    |
| Union Memory (Shenzhen)          | 1         | 0.3%    |
| ULi Electronics                  | 1         | 0.3%    |
| Transcend                        | 1         | 0.3%    |
| Silicon Image                    | 1         | 0.3%    |
| Shenzhen Longsys Electronics     | 1         | 0.3%    |
| Phison Electronics               | 1         | 0.3%    |
| MAXIO Technology (Hangzhou)      | 1         | 0.3%    |
| KIOXIA                           | 1         | 0.3%    |
| Integrated Technology Express    | 1         | 0.3%    |
| Hosin Global Electronics         | 1         | 0.3%    |
| Compaq Computer                  | 1         | 0.3%    |
| Unknown                          | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 34        | 8.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 15        | 3.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 13        | 3.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 2.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 2.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 2.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 11        | 2.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 2.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 8         | 2.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 2.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 2.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 1.83%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 7         | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 7         | 1.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                           | 5         | 1.31%   |
| AMD 400 Series Chipset SATA Controller                                           | 5         | 1.31%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 4         | 1.04%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 4         | 1.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 1.04%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                    | 4         | 1.04%   |
| AMD FCH SATA Controller [IDE mode]                                               | 4         | 1.04%   |
| Intel SATA Controller [RAID mode]                                                | 3         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3         | 0.78%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 3         | 0.78%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 3         | 0.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 3         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 231       | 68.14%  |
| IDE  | 48        | 14.16%  |
| NVMe | 41        | 12.09%  |
| RAID | 14        | 4.13%   |
| SCSI | 3         | 0.88%   |
| SAS  | 2         | 0.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 222       | 77.62%  |
| AMD             | 59        | 20.63%  |
| SUNW,UltraAX-i2 | 1         | 0.35%   |
| Broadcom        | 1         | 0.35%   |
| Bochs           | 1         | 0.35%   |
| Arm             | 1         | 0.35%   |
| Unknown         | 1         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                              | 10        | 3.48%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 8         | 2.79%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 7         | 2.44%   |
| Intel Celeron N5105 @ 2.00GHz                 | 6         | 2.09%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 5         | 1.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.39%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.39%   |
| Intel Pentium Gold 8505                       | 3         | 1.05%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.05%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 3         | 1.05%   |
| Intel Core i3-10100F CPU @ 3.60GHz            | 3         | 1.05%   |
| Intel Celeron CPU J3160 @ 1.60GHz             | 3         | 1.05%   |
| AMD Phenom II X4 965 Processor                | 3         | 1.05%   |
| AMD GX-415GA SOC with Radeon HD Graphics      | 3         | 1.05%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 2         | 0.7%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 2         | 0.7%    |
| Intel Pentium CPU G3220 @ 3.00GHz             | 2         | 0.7%    |
| Intel CPU Version                             | 2         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.7%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.7%    |
| Intel Core i5-3470S CPU @ 2.90GHz             | 2         | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.7%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.7%    |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2         | 0.7%    |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.7%    |
| Intel Core 2 Duo                              | 2         | 0.7%    |
| Intel Celeron J4105 CPU @ 1.50GHz             | 2         | 0.7%    |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.7%    |
| Intel Celeron CPU J3455 @ 1.50GHz             | 2         | 0.7%    |
| Intel Celeron CPU J3355 @ 2.00GHz             | 2         | 0.7%    |
| Intel Atom CPU E3826 @ 1.46GHz                | 2         | 0.7%    |
| Intel Atom CPU D525 @ 1.80GHz                 | 2         | 0.7%    |
| AMD Ryzen 9 7950X 16-Core Processor           | 2         | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.7%    |
| AMD GX-420CA SOC with Radeon HD Graphics      | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 51        | 17.77%  |
| Intel Core i5           | 42        | 14.63%  |
| Intel Core i7           | 25        | 8.71%   |
| Intel Core i3           | 22        | 7.67%   |
| Intel Xeon              | 19        | 6.62%   |
| AMD GX                  | 17        | 5.92%   |
| Intel Atom              | 16        | 5.57%   |
| Other                   | 12        | 4.18%   |
| Intel Core 2 Duo        | 11        | 3.83%   |
| Intel Pentium           | 10        | 3.48%   |
| AMD Ryzen 5             | 10        | 3.48%   |
| AMD Ryzen 7             | 7         | 2.44%   |
| Intel Pentium Dual-Core | 5         | 1.74%   |
| AMD Ryzen 9             | 5         | 1.74%   |
| Intel Pentium Gold      | 3         | 1.05%   |
| Intel Pentium Dual      | 3         | 1.05%   |
| AMD Phenom II X4        | 3         | 1.05%   |
| Intel Core 2 Quad       | 2         | 0.7%    |
| AMD EPYC                | 2         | 0.7%    |
| AMD A4                  | 2         | 0.7%    |
| Intel Xeon Silver       | 1         | 0.35%   |
| Intel Xeon Gold         | 1         | 0.35%   |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Pentium M         | 1         | 0.35%   |
| Intel Pentium 4         | 1         | 0.35%   |
| Intel Core 2 Extreme    | 1         | 0.35%   |
| Intel Core 2            | 1         | 0.35%   |
| Intel 686-class         | 1         | 0.35%   |
| AMD Turion 64 X2 Mobile | 1         | 0.35%   |
| AMD Ryzen Embedded      | 1         | 0.35%   |
| AMD Ryzen 7 PRO         | 1         | 0.35%   |
| AMD Ryzen 3             | 1         | 0.35%   |
| AMD Opteron             | 1         | 0.35%   |
| AMD G                   | 1         | 0.35%   |
| AMD FX                  | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD Athlon II X4        | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 109       | 37.98%  |
| 2       | 100       | 34.84%  |
| Unknown | 23        | 8.01%   |
| 16      | 11        | 3.83%   |
| 12      | 11        | 3.83%   |
| 8       | 11        | 3.83%   |
| 1       | 8         | 2.79%   |
| 6       | 7         | 2.44%   |
| 32      | 3         | 1.05%   |
| 3       | 2         | 0.7%    |
| 24      | 1         | 0.35%   |
| 10      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 270       | 94.41%  |
| 2       | 9         | 3.15%   |
| Unknown | 6         | 2.1%    |
| 8       | 1         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 159       | 55.21%  |
| 2       | 106       | 36.81%  |
| Unknown | 23        | 7.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 27        | 9.41%   |
| KabyLake      | 23        | 8.01%   |
| Penryn        | 22        | 7.67%   |
| SandyBridge   | 19        | 6.62%   |
| Haswell       | 19        | 6.62%   |
| Silvermont    | 18        | 6.27%   |
| IvyBridge     | 15        | 5.23%   |
| Goldmont plus | 15        | 5.23%   |
| Bonnell       | 14        | 4.88%   |
| Skylake       | 13        | 4.53%   |
| Puma          | 13        | 4.53%   |
| Broadwell     | 12        | 4.18%   |
| Zen 3         | 8         | 2.79%   |
| CometLake     | 8         | 2.79%   |
| Westmere      | 7         | 2.44%   |
| Jaguar        | 7         | 2.44%   |
| Zen+          | 6         | 2.09%   |
| Nehalem       | 6         | 2.09%   |
| Goldmont      | 6         | 2.09%   |
| Zen           | 5         | 1.74%   |
| Core          | 5         | 1.74%   |
| Zen 2         | 4         | 1.39%   |
| K10           | 4         | 1.39%   |
| NetBurst      | 2         | 0.7%    |
| K10 Llano     | 2         | 0.7%    |
| Bobcat        | 2         | 0.7%    |
| Piledriver    | 1         | 0.35%   |
| P6            | 1         | 0.35%   |
| K8 Hammer     | 1         | 0.35%   |
| IceLake       | 1         | 0.35%   |
| Bulldozer     | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 170       | 59.65%  |
| AMD                              | 61        | 21.4%   |
| Nvidia                           | 38        | 13.33%  |
| Matrox Electronics Systems       | 10        | 3.51%   |
| ASPEED Technology                | 4         | 1.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Red Hat                          | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 4.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 3.78%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 10        | 3.44%   |
| Intel JasperLake [UHD Graphics]                                                          | 8         | 2.75%   |
| Intel HD Graphics 620                                                                    | 7         | 2.41%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.41%   |
| Intel HD Graphics 500                                                                    | 6         | 2.06%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6         | 2.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 5         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.72%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 5         | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.37%   |
| Intel HD Graphics 6000                                                                   | 4         | 1.37%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.37%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.03%   |
| Intel HD Graphics 630                                                                    | 3         | 1.03%   |
| Intel HD Graphics 530                                                                    | 3         | 1.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.03%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 3         | 1.03%   |
| AMD Raphael                                                                              | 3         | 1.03%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 3         | 1.03%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.69%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 2         | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.69%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.69%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.69%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 140       | 48.78%  |
| 1 x AMD        | 52        | 18.12%  |
| 1 x Nvidia     | 25        | 8.71%   |
| Other          | 18        | 6.27%   |
| 2 x Intel      | 18        | 6.27%   |
| Intel + Nvidia | 10        | 3.48%   |
| 1 x Matrox     | 9         | 3.14%   |
| 1 x ASPEED     | 4         | 1.39%   |
| 2 x AMD        | 3         | 1.05%   |
| AMD + Nvidia   | 3         | 1.05%   |
| Intel + AMD    | 2         | 0.7%    |
| 1 x SiS        | 1         | 0.35%   |
| 1 x Red Hat    | 1         | 0.35%   |
| AMD + Matrox   | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 240       | 83.04%  |
| Proprietary | 25        | 8.65%   |
| Unknown     | 24        | 8.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 238       | 82.93%  |
| 0.01-0.5   | 16        | 5.57%   |
| 1.01-2.0   | 12        | 4.18%   |
| 3.01-4.0   | 7         | 2.44%   |
| 0.51-1.0   | 6         | 2.09%   |
| 5.01-6.0   | 5         | 1.74%   |
| 7.01-8.0   | 1         | 0.35%   |
| 2.01-3.0   | 1         | 0.35%   |
| 8.01-16.0  | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Philips                 | 18        | 15.25%  |
| AU Optronics            | 16        | 13.56%  |
| Samsung Electronics     | 15        | 12.71%  |
| LG Display              | 11        | 9.32%   |
| Hewlett-Packard         | 8         | 6.78%   |
| BOE                     | 6         | 5.08%   |
| Acer                    | 6         | 5.08%   |
| Chimei Innolux          | 5         | 4.24%   |
| Dell                    | 4         | 3.39%   |
| Apple                   | 4         | 3.39%   |
| HannStar                | 3         | 2.54%   |
| Goldstar                | 3         | 2.54%   |
| Lenovo                  | 2         | 1.69%   |
| Iiyama                  | 2         | 1.69%   |
| Ancor Communications    | 2         | 1.69%   |
| ___                     | 1         | 0.85%   |
| Sony                    | 1         | 0.85%   |
| Packard Bell            | 1         | 0.85%   |
| Orion                   | 1         | 0.85%   |
| Mi                      | 1         | 0.85%   |
| LPL                     | 1         | 0.85%   |
| LG Philips              | 1         | 0.85%   |
| LG Electronics          | 1         | 0.85%   |
| HKC                     | 1         | 0.85%   |
| Fujitsu Siemens         | 1         | 0.85%   |
| Eizo                    | 1         | 0.85%   |
| Chi Mei Optoelectronics | 1         | 0.85%   |
| ASUSTek Computer        | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 15        | 12.71%  |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 3         | 2.54%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch      | 2         | 1.69%   |
| Hewlett-Packard 27w HPN3494 1920x1080 600x340mm 27.2-inch             | 2         | 1.69%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 310x170mm 13.9-inch         | 2         | 1.69%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 2         | 1.69%   |
| Acer V193W ACR0025 1440x900 400x250mm 18.6-inch                       | 2         | 1.69%   |
| ___ MY TV LED TV ___0101 1920x1080                                    | 1         | 0.85%   |
| Sony TV SNY5D01 1360x768                                              | 1         | 0.85%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1         | 0.85%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch     | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1         | 0.85%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 530x300mm 24.0-inch     | 1         | 0.85%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC314D 1366x768 310x170mm 13.9-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM7032 1920x1080 700x390mm 31.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor B2430L 1920x1080                      | 1         | 0.85%   |
| Philips PHL 328E9Q PHLC180 1920x1080 700x390mm 31.5-inch              | 1         | 0.85%   |
| Philips PHL 278B1 PHL0949 3840x2160 600x340mm 27.2-inch               | 1         | 0.85%   |
| Philips 22PFL3404D PHLD05D 1920x1080 640x360mm 28.9-inch              | 1         | 0.85%   |
| Packard Bell Viseo 193 Ws PKB008C 1440x900 410x260mm 19.1-inch        | 1         | 0.85%   |
| Orion LCD Monitor ORN1207 1920x1080                                   | 1         | 0.85%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                      | 1         | 0.85%   |
| LPL LCD Monitor 1680x1050                                             | 1         | 0.85%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 0.85%   |
| LG Electronics LCD Monitor E2360 1920x1080                            | 1         | 0.85%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD045D 1366x768 350x190mm 15.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD039F 1366x768 350x190mm 15.7-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 50.88%  |
| 1366x768 (WXGA)    | 25        | 21.93%  |
| 1440x900 (WXGA+)   | 4         | 3.51%   |
| 1024x600           | 4         | 3.51%   |
| 1600x900 (HD+)     | 3         | 2.63%   |
| 1280x800 (WXGA)    | 3         | 2.63%   |
| 1280x1024 (SXGA)   | 3         | 2.63%   |
| 3840x2160 (4K)     | 2         | 1.75%   |
| 2560x1440 (QHD)    | 2         | 1.75%   |
| 2560x1080          | 2         | 1.75%   |
| 1920x1200 (WUXGA)  | 2         | 1.75%   |
| 3840x2400          | 1         | 0.88%   |
| 2160x1440          | 1         | 0.88%   |
| 1680x1050 (WSXGA+) | 1         | 0.88%   |
| 1600x1200          | 1         | 0.88%   |
| 1360x768           | 1         | 0.88%   |
| 1024x768 (XGA)     | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 23.73%  |
| 21      | 18        | 15.25%  |
| Unknown | 12        | 10.17%  |
| 13      | 11        | 9.32%   |
| 27      | 10        | 8.47%   |
| 24      | 7         | 5.93%   |
| 23      | 5         | 4.24%   |
| 31      | 4         | 3.39%   |
| 19      | 4         | 3.39%   |
| 10      | 4         | 3.39%   |
| 12      | 3         | 2.54%   |
| 18      | 2         | 1.69%   |
| 17      | 2         | 1.69%   |
| 14      | 2         | 1.69%   |
| 39      | 1         | 0.85%   |
| 34      | 1         | 0.85%   |
| 28      | 1         | 0.85%   |
| 22      | 1         | 0.85%   |
| 20      | 1         | 0.85%   |
| 11      | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 31.9%   |
| 401-500     | 21        | 18.1%   |
| 501-600     | 20        | 17.24%  |
| 201-300     | 12        | 10.34%  |
| Unknown     | 12        | 10.34%  |
| 601-700     | 6         | 5.17%   |
| 351-400     | 6         | 5.17%   |
| 701-800     | 1         | 0.86%   |
| 901-1000    | 1         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 88        | 79.28%  |
| 16/10   | 11        | 9.91%   |
| Unknown | 5         | 4.5%    |
| 5/4     | 2         | 1.8%    |
| 4/3     | 2         | 1.8%    |
| 21/9    | 2         | 1.8%    |
| 3/2     | 1         | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 27        | 23.48%  |
| 91-100         | 18        | 15.65%  |
| Unknown        | 12        | 10.43%  |
| 81-90          | 11        | 9.57%   |
| 101-110        | 11        | 9.57%   |
| 301-350        | 10        | 8.7%    |
| 351-500        | 6         | 5.22%   |
| 151-200        | 6         | 5.22%   |
| 41-50          | 4         | 3.48%   |
| 61-70          | 3         | 2.61%   |
| 251-300        | 2         | 1.74%   |
| 121-130        | 2         | 1.74%   |
| 51-60          | 1         | 0.87%   |
| 111-120        | 1         | 0.87%   |
| 501-1000       | 1         | 0.87%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 42        | 36.84%  |
| 51-100        | 39        | 34.21%  |
| 121-160       | 17        | 14.91%  |
| Unknown       | 12        | 10.53%  |
| 161-240       | 3         | 2.63%   |
| More than 240 | 1         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 162       | 56.06%  |
| 1     | 122       | 42.21%  |
| 2     | 5         | 1.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 173       | 43.36%  |
| Realtek Semiconductor            | 118       | 29.57%  |
| Qualcomm Atheros                 | 37        | 9.27%   |
| Broadcom                         | 31        | 7.77%   |
| Ralink Technology                | 4         | 1%      |
| Marvell Technology Group         | 4         | 1%      |
| MediaTek                         | 3         | 0.75%   |
| T & A Mobile Phones              | 2         | 0.5%    |
| Samsung Electronics              | 2         | 0.5%    |
| Ralink                           | 2         | 0.5%    |
| Huawei Technologies              | 2         | 0.5%    |
| Davicom Semiconductor            | 2         | 0.5%    |
| Xiaomi                           | 1         | 0.25%   |
| Sitecom Europe                   | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| OPPO Electronics                 | 1         | 0.25%   |
| Nvidia                           | 1         | 0.25%   |
| NetGear                          | 1         | 0.25%   |
| Mellanox Technologies            | 1         | 0.25%   |
| Lenovo                           | 1         | 0.25%   |
| JMicron Technology               | 1         | 0.25%   |
| IMC Networks                     | 1         | 0.25%   |
| Hewlett-Packard                  | 1         | 0.25%   |
| Google                           | 1         | 0.25%   |
| Edimax Technology                | 1         | 0.25%   |
| Digital Equipment                | 1         | 0.25%   |
| D-Link System                    | 1         | 0.25%   |
| BUFFALO                          | 1         | 0.25%   |
| Aquantia                         | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |
| AMD                              | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 101       | 21%     |
| Intel I211 Gigabit Network Connection                                         | 28        | 5.82%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 2.91%   |
| Intel Ethernet Controller I226-V                                              | 11        | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10        | 2.08%   |
| Intel 82574L Gigabit Network Connection                                       | 10        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 1.46%   |
| Intel Wireless 7265                                                           | 7         | 1.46%   |
| Intel Wireless 3165                                                           | 7         | 1.46%   |
| Intel 82583V Gigabit Network Connection                                       | 7         | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 6         | 1.25%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 1.25%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 1.25%   |
| Intel Ethernet Controller I225-V                                              | 6         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                             | 5         | 1.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.04%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 5         | 1.04%   |
| Intel Wireless 8260                                                           | 5         | 1.04%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 4         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 0.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 3         | 0.62%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 3         | 0.62%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 3         | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 0.62%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3         | 0.62%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.62%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.62%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.62%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 0.62%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 3         | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 3         | 0.62%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                                   | 2         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 40%     |
| Qualcomm Atheros      | 36        | 27.69%  |
| Realtek Semiconductor | 16        | 12.31%  |
| Broadcom              | 13        | 10%     |
| Ralink Technology     | 4         | 3.08%   |
| Ralink                | 2         | 1.54%   |
| MediaTek              | 2         | 1.54%   |
| Sitecom Europe        | 1         | 0.77%   |
| NetGear               | 1         | 0.77%   |
| IMC Networks          | 1         | 0.77%   |
| Edimax Technology     | 1         | 0.77%   |
| BUFFALO               | 1         | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 5.22%   |
| Intel Wireless 7265                                                     | 7         | 5.22%   |
| Intel Wireless 3165                                                     | 7         | 5.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.48%   |
| Intel Wireless 8265 / 8275                                              | 6         | 4.48%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 3.73%   |
| Intel Wireless 8260                                                     | 5         | 3.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.24%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 3         | 2.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 2.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 2.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.49%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 1.49%   |
| Intel Wireless 7260                                                     | 2         | 1.49%   |
| Intel WiFi Link 5100                                                    | 2         | 1.49%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.49%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.49%   |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.49%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 1.49%   |
| Sitecom Europe 802.11n WLAN Adapter                                     | 1         | 0.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 1         | 0.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.75%   |
| Realtek Bluetooth Adapter                                               | 1         | 0.75%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.75%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.75%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 146       | 47.1%   |
| Realtek Semiconductor            | 113       | 36.45%  |
| Broadcom                         | 19        | 6.13%   |
| Qualcomm Atheros                 | 10        | 3.23%   |
| Marvell Technology Group         | 4         | 1.29%   |
| T & A Mobile Phones              | 2         | 0.65%   |
| Samsung Electronics              | 2         | 0.65%   |
| Davicom Semiconductor            | 2         | 0.65%   |
| Xiaomi                           | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| OPPO Electronics                 | 1         | 0.32%   |
| Nvidia                           | 1         | 0.32%   |
| MediaTek                         | 1         | 0.32%   |
| Lenovo                           | 1         | 0.32%   |
| JMicron Technology               | 1         | 0.32%   |
| Digital Equipment                | 1         | 0.32%   |
| D-Link System                    | 1         | 0.32%   |
| Aquantia                         | 1         | 0.32%   |
| Apple                            | 1         | 0.32%   |
| AMD                              | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 101       | 29.88%  |
| Intel I211 Gigabit Network Connection                                         | 28        | 8.28%   |
| Intel I210 Gigabit Network Connection                                         | 14        | 4.14%   |
| Intel Ethernet Controller I226-V                                              | 11        | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 10        | 2.96%   |
| Intel 82574L Gigabit Network Connection                                       | 10        | 2.96%   |
| Intel 82583V Gigabit Network Connection                                       | 7         | 2.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 1.78%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 1.78%   |
| Intel Ethernet Controller I225-V                                              | 6         | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 5         | 1.48%   |
| Intel Ethernet Connection I217-LM                                             | 5         | 1.48%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 1.18%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                 | 3         | 0.89%   |
| Intel Ethernet Connection I219-LM                                             | 3         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.89%   |
| Intel 82579V Gigabit Network Connection                                       | 3         | 0.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 3         | 0.89%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 3         | 0.89%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3         | 0.89%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 3         | 0.89%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                                   | 2         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 2         | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                         | 2         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 2         | 0.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 2         | 0.59%   |
| Intel Ethernet Connection (7) I219-V                                          | 2         | 0.59%   |
| Intel Ethernet Connection (3) I218-V                                          | 2         | 0.59%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                                         | 2         | 0.59%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 2         | 0.59%   |
| Intel 82580 Gigabit Network Connection                                        | 2         | 0.59%   |
| Intel 82576 Gigabit Network Connection                                        | 2         | 0.59%   |
| Intel 82575EB Gigabit Network Connection                                      | 2         | 0.59%   |
| Davicom DM9102 Fast Ethernet Controller                                       | 2         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 2         | 0.59%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 2         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 271       | 67.75%  |
| WiFi     | 120       | 30%     |
| Unknown  | 6         | 1.5%    |
| Modem    | 3         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 241       | 79.8%   |
| WiFi     | 61        | 20.2%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 108       | 37.76%  |
| 1     | 69        | 24.13%  |
| 4     | 34        | 11.89%  |
| 3     | 30        | 10.49%  |
| 6     | 15        | 5.24%   |
| 5     | 14        | 4.9%    |
| 7     | 5         | 1.75%   |
| 8     | 4         | 1.4%    |
| 0     | 3         | 1.05%   |
| 9     | 2         | 0.7%    |
| 12    | 1         | 0.35%   |
| 10    | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 279       | 97.89%  |
| Yes  | 6         | 2.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 44.19%  |
| Realtek Semiconductor           | 7         | 8.14%   |
| Broadcom                        | 7         | 8.14%   |
| Qualcomm Atheros Communications | 6         | 6.98%   |
| IMC Networks                    | 6         | 6.98%   |
| Cambridge Silicon Radio         | 6         | 6.98%   |
| Lite-On Technology              | 4         | 4.65%   |
| Apple                           | 4         | 4.65%   |
| Integrated System Solution      | 2         | 2.33%   |
| Toshiba                         | 1         | 1.16%   |
| MediaTek                        | 1         | 1.16%   |
| Hewlett-Packard                 | 1         | 1.16%   |
| Foxconn / Hon Hai               | 1         | 1.16%   |
| Dell                            | 1         | 1.16%   |
| ASUSTek Computer                | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 26.74%  |
| Intel AX201 Bluetooth                                       | 6         | 6.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 6.98%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 3         | 3.49%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 2.33%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 2.33%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 2         | 2.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.33%   |
| Intel AX200 Bluetooth                                       | 2         | 2.33%   |
| Integrated System Solution Bluetooth Device                 | 2         | 2.33%   |
| IMC Networks Realtek Bluetooth Adapter                      | 2         | 2.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.33%   |
| Apple Broadcom Built-in Bluetooth                           | 2         | 2.33%   |
| Toshiba Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 1.16%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 1.16%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 1.16%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.16%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.16%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1         | 1.16%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.16%   |
| MediaTek RZ608 Bluetooth Adapter                            | 1         | 1.16%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 1.16%   |
| Intel AX210 Bluetooth                                       | 1         | 1.16%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 1.16%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.16%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.16%   |
| Dell Wireless 360 Bluetooth                                 | 1         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth Device                        | 1         | 1.16%   |
| Broadcom BCM20702A0 Bluetooth                               | 1         | 1.16%   |
| Broadcom BCM2070 Bluetooth 2.1+EDR USB Device               | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 1.16%   |
| Broadcom BCM2045 Bluetooth                                  | 1         | 1.16%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                       | 1         | 1.16%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 178       | 62.46%  |
| AMD                              | 62        | 21.75%  |
| Nvidia                           | 28        | 9.82%   |
| C-Media Electronics              | 6         | 2.11%   |
| Silicon Integrated Systems [SiS] | 2         | 0.7%    |
| Logitech                         | 2         | 0.7%    |
| KTMicro                          | 2         | 0.7%    |
| Samson Technologies              | 1         | 0.35%   |
| Plantronics                      | 1         | 0.35%   |
| Creative Labs                    | 1         | 0.35%   |
| Bose                             | 1         | 0.35%   |
| Apogee Electronics               | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 3.46%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 3.17%   |
| AMD FCH Azalia Controller                                                                         | 11        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 2.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.59%   |
| Intel Jasper Lake HD Audio                                                                        | 8         | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 2.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 1.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.73%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6         | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.44%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.44%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4         | 1.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.15%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 1.15%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.86%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.86%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.86%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 0.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 3         | 0.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 58        | 19.86%  |
| Unknown                      | 39        | 13.36%  |
| Kingston                     | 36        | 12.33%  |
| SK hynix                     | 32        | 10.96%  |
| Crucial                      | 24        | 8.22%   |
| Micron Technology            | 18        | 6.16%   |
| Unknown                      | 17        | 5.82%   |
| Unknown (ABCD)               | 11        | 3.77%   |
| Nanya Technology             | 8         | 2.74%   |
| Transcend                    | 7         | 2.4%    |
| Corsair                      | 7         | 2.4%    |
| Ramaxel Technology           | 5         | 1.71%   |
| Elpida                       | 5         | 1.71%   |
| A-DATA Technology            | 5         | 1.71%   |
| Unknown (AB)                 | 2         | 0.68%   |
| G.Skill                      | 2         | 0.68%   |
| Unknown (F301)               | 1         | 0.34%   |
| Unknown (89F8)               | 1         | 0.34%   |
| Unknown (0x0DD5)             | 1         | 0.34%   |
| SK_Hynix                     | 1         | 0.34%   |
| Patriot Memory (PDP Systems) | 1         | 0.34%   |
| KomputerBay                  | 1         | 0.34%   |
| Intersil                     | 1         | 0.34%   |
| HPE                          | 1         | 0.34%   |
| Heoriady                     | 1         | 0.34%   |
| ASint Technology             | 1         | 0.34%   |
| Apacer                       | 1         | 0.34%   |
| 48spaces                     | 1         | 0.34%   |
| 2C0C0843D7349CA2             | 1         | 0.34%   |
| 2C0C0843D7349C9D             | 1         | 0.34%   |
| 2C080815D82F5C7B             | 1         | 0.34%   |
| 2C0108214C359D20             | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 17        | 5.31%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 11        | 3.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 6         | 1.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 5         | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 1.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.25%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 3         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.94%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s      | 3         | 0.94%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 3         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                  | 2         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 2         | 0.63%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 2         | 0.63%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                     | 2         | 0.63%   |
| Transcend RAM TS512MLH72V1H 4GB DIMM DDR4 2133MT/s           | 2         | 0.63%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 2         | 0.63%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                    | 2         | 0.63%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 2         | 0.63%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.63%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB DIMM DDR3 1600MT/s          | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 2         | 0.63%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 2         | 0.63%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s        | 2         | 0.63%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1333MT/s         | 2         | 0.63%   |
| Micron RAM MT41K512M8RH-125:E 4GB SODIMM DDR3 1600MT/s       | 2         | 0.63%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 0.63%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s       | 2         | 0.63%   |
| Kingston RAM 99P5700-017.A00G 16GB SODIMM DDR4 2667MT/s      | 2         | 0.63%   |
| Kingston RAM 9965754-059.C00G 32GB DIMM DDR4 3200MT/s        | 2         | 0.63%   |
| Crucial RAM CT8G4DFRA32A.M4FF 8GB DIMM DDR4 3200MT/s         | 2         | 0.63%   |
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s     | 2         | 0.63%   |
| Corsair RAM CML16GX3M4A1600C9 4GB DIMM DDR3 1600MT/s         | 2         | 0.63%   |
| Unknown SODIMM 4GB SODIMM 800MT/s                            | 1         | 0.31%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                  | 1         | 0.31%   |
| Unknown RAM Module 8GB DIMM DDR3 1866MT/s                    | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 117       | 46.25%  |
| DDR4    | 72        | 28.46%  |
| DDR2    | 28        | 11.07%  |
| LPDDR4  | 15        | 5.93%   |
| Unknown | 8         | 3.16%   |
| SDRAM   | 5         | 1.98%   |
| DDR5    | 3         | 1.19%   |
| DDR     | 3         | 1.19%   |
| RAM     | 1         | 0.4%    |
| LPDDR3  | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 133       | 52.78%  |
| DIMM         | 108       | 42.86%  |
| Row Of Chips | 5         | 1.98%   |
| Chip         | 4         | 1.59%   |
| FB-DIMM      | 1         | 0.4%    |
| Unknown      | 1         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 93        | 33.7%   |
| 8192  | 75        | 27.17%  |
| 2048  | 55        | 19.93%  |
| 16384 | 32        | 11.59%  |
| 1024  | 11        | 3.99%   |
| 32768 | 7         | 2.54%   |
| 65536 | 1         | 0.36%   |
| 1491  | 1         | 0.36%   |
| 256   | 1         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 65        | 24.16%  |
| 1333    | 38        | 14.13%  |
| 2400    | 32        | 11.9%   |
| 3200    | 25        | 9.29%   |
| 2667    | 20        | 7.43%   |
| 667     | 18        | 6.69%   |
| 800     | 14        | 5.2%    |
| 2133    | 13        | 4.83%   |
| 1067    | 10        | 3.72%   |
| Unknown | 8         | 2.97%   |
| 1066    | 6         | 2.23%   |
| 1334    | 4         | 1.49%   |
| 4800    | 3         | 1.12%   |
| 2933    | 3         | 1.12%   |
| 1867    | 2         | 0.74%   |
| 3600    | 1         | 0.37%   |
| 2666    | 1         | 0.37%   |
| 2048    | 1         | 0.37%   |
| 1866    | 1         | 0.37%   |
| 1200    | 1         | 0.37%   |
| 975     | 1         | 0.37%   |
| 400     | 1         | 0.37%   |
| 333     | 1         | 0.37%   |

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

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Canon CanoScan N650U/N656U | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 27.54%  |
| IMC Networks                           | 8         | 11.59%  |
| Realtek Semiconductor                  | 7         | 10.14%  |
| Sunplus Innovation Technology          | 6         | 8.7%    |
| Bison Electronics                      | 5         | 7.25%   |
| Logitech                               | 3         | 4.35%   |
| ALi                                    | 3         | 4.35%   |
| Z-Star Microelectronics                | 2         | 2.9%    |
| Silicon Motion                         | 2         | 2.9%    |
| Microdia                               | 2         | 2.9%    |
| Genesys Logic                          | 2         | 2.9%    |
| Trust                                  | 1         | 1.45%   |
| Syntek                                 | 1         | 1.45%   |
| Suyin                                  | 1         | 1.45%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.45%   |
| Lite-On Technology                     | 1         | 1.45%   |
| Lenovo                                 | 1         | 1.45%   |
| KYE Systems (Mouse Systems)            | 1         | 1.45%   |
| Cubeternet                             | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.45%   |
| Apple                                  | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 4         | 5.8%    |
| Realtek Integrated_Webcam_HD                     | 3         | 4.35%   |
| Realtek USB Camera                               | 2         | 2.9%    |
| Realtek Lenovo EasyCamera                        | 2         | 2.9%    |
| IMC Networks Realtek PC Camera                   | 2         | 2.9%    |
| IMC Networks Integrated Camera                   | 2         | 2.9%    |
| Genesys Logic Digital Microscope                 | 2         | 2.9%    |
| Chicony USB2.0 VGA UVC WebCam                    | 2         | 2.9%    |
| Chicony HD WebCam (Acer)                         | 2         | 2.9%    |
| Bison Integrated Camera                          | 2         | 2.9%    |
| ALi Gateway Webcam                               | 2         | 2.9%    |
| Z-Star Webcam                                    | 1         | 1.45%   |
| Z-Star Vega USB 2.0 Camera                       | 1         | 1.45%   |
| Trust Trust QHD Webcam                           | 1         | 1.45%   |
| Syntek EasyCamera                                | 1         | 1.45%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 1         | 1.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 1         | 1.45%   |
| Sunplus Integrated Camera                        | 1         | 1.45%   |
| Sunplus Hy HD Camera                             | 1         | 1.45%   |
| Sunplus Dell E5570 integrated webcam             | 1         | 1.45%   |
| Sunplus Aukey-PC-LM1E Camera                     | 1         | 1.45%   |
| Sunplus 1.3M HD WebCam                           | 1         | 1.45%   |
| Silicon Motion Realtek USB 2.0 PC Camera         | 1         | 1.45%   |
| Silicon Motion HP Webcam-50                      | 1         | 1.45%   |
| Shenzhen Kingcome Optoelectronic HD Webcam       | 1         | 1.45%   |
| Microdia Integrated_Webcam_HD                    | 1         | 1.45%   |
| Microdia ASUS USB 2.0 Webcam                     | 1         | 1.45%   |
| Logitech Webcam C310                             | 1         | 1.45%   |
| Logitech Webcam C270                             | 1         | 1.45%   |
| Logitech C505 HD Webcam                          | 1         | 1.45%   |
| Lite-On HP TrueVision HD Camera                  | 1         | 1.45%   |
| Lenovo Integrated Webcam [R5U877]                | 1         | 1.45%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1         | 1.45%   |
| IMC Networks UVC VGA Webcam                      | 1         | 1.45%   |
| IMC Networks USB 2.0 UVC HD Webcam               | 1         | 1.45%   |
| IMC Networks Realtek DMFT RGB                    | 1         | 1.45%   |
| IMC Networks Integrated Webcam                   | 1         | 1.45%   |
| Cubeternet WebCam                                | 1         | 1.45%   |
| Chicony WebCam                                   | 1         | 1.45%   |
| Chicony Toshiba Integrated Webcam                | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 27.27%  |
| AuthenTec             | 3         | 27.27%  |
| Synaptics             | 2         | 18.18%  |
| Upek                  | 1         | 9.09%   |
| STMicroelectronics    | 1         | 9.09%   |
| Elan Microelectronics | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES1600                                      | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics UWP WBDI Device                              | 1         | 9.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 9.09%   |
| Elan Fingerprint Sensor                                | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |

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
| 1     | 118       | 40.55%  |
| 0     | 100       | 34.36%  |
| 2     | 41        | 14.09%  |
| 3     | 28        | 9.62%   |
| 4     | 4         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 150       | 54.95%  |
| Net/wireless             | 32        | 11.72%  |
| Bluetooth                | 27        | 9.89%   |
| Card reader              | 25        | 9.16%   |
| Firewire controller      | 12        | 4.4%    |
| Fingerprint reader       | 11        | 4.03%   |
| Graphics card            | 6         | 2.2%    |
| Network                  | 4         | 1.47%   |
| Storage                  | 2         | 0.73%   |
| Dvb card                 | 2         | 0.73%   |
| Sound                    | 1         | 0.37%   |
| Modem                    | 1         | 0.37%   |

